# Contributing

## Setting-up

### Preferred method - VSCode Dev Container

VSCode dev containers are a great way to containerize not only the necessary requirements but also recommended IDE extensions as well as settings such as pre-commit hooks and linting preferences. Using this will allow you to jump in to the perfect DSPY contribution environment without having to do much. Additionally, you'll be able to contribute through the web browser using Github Codespaces!

To use our dev container:

1. Download Docker Desktop
2. Download VSCode
3. Within VSCode, install the Remote Development extension (ms-vscode-remote.vscode-remote-extensionpack)
4. Open the VSCode command palette (cmd / ctrl + shift + p)
5. Select `Dev Containers: Rebuild and Reopen in container`. A new VSCode window should open up and it should begin setting up your environment. Once it's done, you can open up a new terminal and start running tests or contributing!
   - Be sure the correct VSCode Python Interpreter is selected. Additional instructions are provided in yellow at the end of the dev container build logs. In short, you need to make sure you have the Poetry interpreter selected or else you'll be using an interpreter without access to the necessary Python packages.
6. To test that your environment is set up correctly, open a new terminal and run the command `pytest`. You should be able to run all tests and see them pass. Alternatively, you can open up the testing panel, which looks like a beaker, and click the play button to run all of our tests.
7. After the initial build, you should now be able to leave and re-enter the container any time without needing to rebuild. To do this, open the command palette and select `Dev Containers: Reopen in container`. This will not rebuild the container if you've done it correctly.

NOTE: If you use this method, your default shell will be the poetry shell which will contain all the necessary requirements in your terminal. You shouldn't need to prefix python commands with poetry as you're already using the correct poetry virtual environment.

### Alternative method

To run the tests, you need to first clone the repository.

Then install the package through poetry:
Note - You may need to install poetry. You likely will just need to run `pip install poetry`. See [here](https://python-poetry.org/docs/#installing-with-the-official-installer)

After installing poetry, use it to install our development requirements.

```bash
poetry install --with dev
```

## Testing

To run the all tests, or a specific test suite, use the following commands:

```bash
poetry run pytest
poetry run pytest tests/PATH_TO_TEST_SUITE
```

If you are changing CI actions, you can use the [act](https://nektosact.com/introduction.html) tool to test the CI locally.

Example for testing the push action:
You may need the `--container-architecture linux/amd64` flag if you are on an M1/2 mac.

```bash
 act push
```

## How to commit

After running `git commit` the [commitizen](https://commitizen-tools.github.io/commitizen/) cli utility is invoked. The prompt will step by step prompt you to fill in the data for the commit according to the [Conventional Commit Format](https://www.conventionalcommits.org/en/v1.0.0/). This is required to enable [changelog generation](https://commitizen-tools.github.io/commitizen/commands/changelog/) from commit history.

### Steps:

1. `Select the type of change you are committing` **(REQUIRED)**

   - **feat**: A new feature. Correlates with MINOR in SemVer (x.X.x)
   - **fix**: A bug fix. Correlates with PATCH in SemVer (x.x.X)
   - **test**: Adding missing or correcting existing tests
   - **ci**: Changes to continuous integration configuration files and scripts
   - **perf**: Performance improvements
   - **refactor**: Code changes without affecting behavior (neither fixes a bug nor adds a feature)
   - **chore**: Maintenance, revert, release
   - **style**: Code style or formatting changes, that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
   - **docs**: Documentation only changes

2. `What is the scope of this change (entity you've been working on)?` **(REQUIRED)**

3. `Write a short and imperative summary of the code changes (lower case and no period)` **(REQUIRED)**

   - If you want the github issue link you're working on to be rendered in the changelog, you can reference github issue in parentheses in the end of line, e.g.: `enable changelog generation (#1455)`
   - Parantheses are required `()`, Number sign `#` with the actual number `123` are required

4. `If this is a BREAKING CHANGE (correllates with MAJOR in SemVer (X.x.x)), describe the breaking changes and how to update the code to use it: (press [enter] to skip)` **(OPTIONAL)**

   - If your commit introduces a breaking change, here you can describe what exactly is breaking and how, what APIs have changed, etc., any useful information for users about how to address it in their code

5. `Provide additional contextual information about the code changes: (press [enter] to skip)` **(OPTIONAL)**

---

6. After filling in the commit message data according to these steps, the resulting formatted commit message will be opened in `COMMIT_EDITMSG` window. Here you can edit it, if needed. In order to create a commit, you have to fill in at least commit type, scope, short summary.

   - Commit with all fields filled in might look like:

     ```
     fix(my-scope): add commitizen as cli prompt for commits, git-cliff for changelog generation (#1455)

     BREAKING CHANGE: description of the breaking change
     CONTEXT: additional context
     ```

   - How this commit would be generated in the **CHANGELOG.md**:
     - **(my-scope)**: Short summary ([#1455](https://github.com/stanfordnlp/dspy/issues/1455)) - ([c9e802b](https://github.com/stanfordnlp/dspy/commit/c9e802b215f93d9e0910b9037f052edd04133bb9))
       - **BREAKING**: description of the breaking change
       - **context**: additional context

## How to generate changelog (manually)

To generate changelog:

```
git cliff -o
```

The changelog is generated with access to Github API. Because of this you have to have your [Github Personal Access Token](https://github.com/settings/tokens) exported as an env variable:

- Create your Personal Access Token, if you don't have one (with access to public repos)
- Export Github Personal Access Token as an env variable (without ""):

  ```
  export GITHUB_TOKEN=...
  ```

## How commits are rendered in the changelog

### Based on commit type

Commits of the following types are rendered into corresponding groups based on selected **commit type**:

| Commit type | Changelog group          |
| ----------- | ------------------------ |
| feat        | 🚀 Features              |
| fix         | 💊 Bug Fixes             |
| test        | 🧪 Testing               |
| ci          | 🛠 Continuous Integration |
| perf        | ⚡️ Performance          |
| refactor    | 🚜 Refactor              |
| chore       | ⚙️ Chore                 |
| style       | 🎨 Styling               |
| docs        | 📚 Documentation         |
| test        | 🧪 Testing               |

### Based on words in the commit message

Commits, that are rendered into changelog groups based on the **words**, they contain **in the body of the commit** (in the short summary):

| Word             | Changelog group     |
| ---------------- | ------------------- |
| breaking changes | 🟡 BREAKING CHANGES |
| security         | 🛡️ Security         |
| revert           | ⏪ Revert           |

<!-- test -->
