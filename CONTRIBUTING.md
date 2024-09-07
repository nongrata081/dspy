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

After running `git commit` the [commitizen](https://commitizen-tools.github.io/commitizen/) cli utility is invoked. The prompt will step by step prompt you to fill in the data for the commit according to the [Conventional Commit Format](https://www.conventionalcommits.org/en/v1.0.0/). This is required to enable [changelog generation](https://commitizen-tools.github.io/commitizen/commands/changelog/) from commit history. Note, only commits of type **fix**, **feat**, or **BREAKING CHANGE** get into the generated changelog.

### Steps:

1. `Select the type of change you are committing`

   - **fix**: A bug fix. Correlates with PATCH in SemVer
   - **feat**: A new feature. Correlates with MINOR in SemVer
   - **docs**: Documentation only changes
   - **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
   - **refactor**: A code change that neither fixes a bug nor adds a feature
   - **perf**: A code change that improves performance
   - **test**: Adding missing or correcting existing tests
   - **build**: Changes that affect the build system or external dependencies (example scopes: pip, docker, npm)
   - **ci**: Changes to CI configuration files and scripts (example scopes: GitLabCI)

2. `What is the scope of this change? (class or file name)`

   - is optional. Can be any entity you were working on, so that it is easier to navigate

3. `Write a short and imperative summary of the code changes (lower case and no period)`
   - isn't optional, is required.
4. `Provide additional contextual information about the code changes`
   - is optional
5. `Is this a BREAKING CHANGE? Correlates with MAJOR in SemVer (y/N)`
   - is optional. Pressing `Enter` will default to `No` and proceed to next step
6. `Footer. Information about Breaking Changes and reference issues that this commit closes`

   - If your commit introduces a breaking change, here you can describe what exactly is breaking and how, any useful info for users about how to address it in their code
   - You can reference github issue just by stating the number, e.g. #123
   - is optional. Pressing `Enter` will default to `No` and proceed to next step

7. After filling in the commit message data according to these steps, the resulting formatted commit message will be opened in `COMMIT_EDITMSG` window. Here you can edit it, if needed, e.g.:

   ```
   feat(scope): short summary

   contextual information

   BREAKING CHANGE: breaking change is this and that, fix by using fixedApi() instead of brokenApi(), issue #123
   ```

   After closing the window, the commit message will be validated with commitizen check to verify if the commit message format complies with [Conventional Commit Format](https://www.conventionalcommits.org/en/v1.0.0/). The commit is made after successfully passing this check. If it doesn't pass, you have to edit the commit message according to the format.

   ***

   ## How to generate changelog (manually)

   ...
