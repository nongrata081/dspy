# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### 🟡 BREAKING CHANGES

- **(my-scope)**: Short summary of the commit ([#1455](https://github.com/stanfordnlp/dspy/issues/1455)) - ([1000724](https://github.com/stanfordnlp/dspy/commit/10007243682c01bf22544b831d70091c3759d4f9))
  - **BREAKING**: description of the breaking change. Don't use the broken_api(), use fixed_api() instead
  - **context**: Here is the description of the context, for better understanding the introduced changes if needed

### 🛠 Continuous Integration

- **(changelog)**: Add commitizen as cli prompt for commits, git-cliff for changelog generation ([#1455](https://github.com/stanfordnlp/dspy/issues/1455)) - ([7bb4a8f](https://github.com/stanfordnlp/dspy/commit/7bb4a8f5a78e757be30ac1c16ddc321b2fbb8f75))

### ⚙️ Chore

- Fix langtrace in usecase.md - ([316e0b4](https://github.com/stanfordnlp/dspy/commit/316e0b419dbafd9e2ec1a40ee904cd9542824ecb))
- Update dspy-usecases.md - ([86ee13a](https://github.com/stanfordnlp/dspy/commit/86ee13a57e11fd74ae86f8b163c5335a434bb0fa))
- Update dspy-usecases.md - ([1afb6d7](https://github.com/stanfordnlp/dspy/commit/1afb6d7cdfff5409496b612b5395c17e7fd1df87))

## [2.4.14](https://github.com/stanfordnlp/dspy/compare/2.4.13..2.4.14) - 2024-09-01

### 🚀 Features

- **(dspy)**: Refined missing hf error - ([bdc9b98](https://github.com/stanfordnlp/dspy/commit/bdc9b98e7380558fcbf1a68be653847b85edf1ce))
- **(dspy)**: Dspy-integration-with-langfuse ([#1186](https://github.com/stanfordnlp/dspy/issues/1186)) - ([23724aa](https://github.com/stanfordnlp/dspy/commit/23724aa5d91b87ada3806cd972445332b70fa81c))

- **(dspy)**: Added beginner example for multi-input-output - ([cfbd1a1](https://github.com/stanfordnlp/dspy/commit/cfbd1a16f9f2fdb94879da0e2fd6227b791c7433))

### 📚 Documentation

- **(ChromadbRM)**: Change reference to chromadb embeddings - ([55994e8](https://github.com/stanfordnlp/dspy/commit/55994e8aa26dc56211ab6ecb384e68563d8c3c0d))
- **(dspy)**: Add Dicer.ai to usecase list - ([291ff85](https://github.com/stanfordnlp/dspy/commit/291ff85222fea6d781fb93e9f9617c42f5a70943))
- **(dspy)**: Update usecase table headers for clarity - ([d2f8f13](https://github.com/stanfordnlp/dspy/commit/d2f8f1366d2dcb558e82ddde3d4368995dab6d4c))
- Filter reference - ([3fe1fd1](https://github.com/stanfordnlp/dspy/commit/3fe1fd14e3a3480054ea8735872989fd6055e0c3))
- QdrantRM docs - ([99a25f3](https://github.com/stanfordnlp/dspy/commit/99a25f362343facde59027e52cf3897635041846))

### 💊 Bug Fixes

- **(dsp)**: Update imports after mistral migration update - ([63ec13b](https://github.com/stanfordnlp/dspy/commit/63ec13b295c6ae8be8f1bf7cf65a6160052416f8))
- **(dsp)**: Update imports after mistral migration update - ([8669785](https://github.com/stanfordnlp/dspy/commit/8669785892e8afacefe6602002aca91e0b569ffb))
- **(dspy)**: Prompt_eval_count occasionally is None and causes TypeError - ([aa68c81](https://github.com/stanfordnlp/dspy/commit/aa68c81c7e8f01548682f9206c372da085ce176c))
- **(dspy)**: PR feedback : fixing typos and dataset loading from external source - ([7999668](https://github.com/stanfordnlp/dspy/commit/7999668b79dd5f626bb1d3dcf3efffbdcbe384fa))
- **(dspy)**: PR feedback : typos, save as json, print for score - ([4c5da99](https://github.com/stanfordnlp/dspy/commit/4c5da9920742952fd87050f21a98d43e94db5507))
- **(dspy)**: Chromadb_rm import error ([#1353](https://github.com/stanfordnlp/dspy/issues/1353)) - ([882ca3f](https://github.com/stanfordnlp/dspy/commit/882ca3f1f0ec8a74811a8afc2665ae2430fda99e))
- **(dspy)**: Support nested objects in set_attribute_by_name() via magicattr - ([988a107](https://github.com/stanfordnlp/dspy/commit/988a10792a2d06c3483c63aeac7d77f1262c8811))
- **(mlc-llm)**: Fix mlc-llm ChatModuleClient with MLCEngine - ([5c0c96a](https://github.com/stanfordnlp/dspy/commit/5c0c96ae0e86af13884c5bbec1fc28dca0f1e2b8))
- Support default_headers in OpenAI LM Client - ([61c40e9](https://github.com/stanfordnlp/dspy/commit/61c40e9ab588d5be519d4b5f35c3f635c9a111a5))
- Forward return in class MilvusRM - ([6b71f25](https://github.com/stanfordnlp/dspy/commit/6b71f252cbeb9d3d532ca09da1283d568814fe13))

### ⚙️ Chore

- **(dspy)**: Update readme and usecases - ([bbfa27b](https://github.com/stanfordnlp/dspy/commit/bbfa27b6a1e1b60746df3b301bd5fa6baac05834))
- Update production usecases markdown file - ([782833c](https://github.com/stanfordnlp/dspy/commit/782833cf3b4f3affa3f0f53b891ae6cec4b54488))
- Remove unhelpful external links from README.md - ([32d0db0](https://github.com/stanfordnlp/dspy/commit/32d0db00eb8741069b8beea5577493f4e3af8cd2))

### 🎨 Styling

- **(dspy)**: Ruff linting - ([a738615](https://github.com/stanfordnlp/dspy/commit/a7386151f892e0f1158927dfdeca2d3f38c1f9e9))

## [2.4.13](https://github.com/stanfordnlp/dspy/compare/v2.4.12..2.4.13) - 2024-07-29

### 🚀 Features

- **(dspy)**: Add system and format options to ollama - ([871eebe](https://github.com/stanfordnlp/dspy/commit/871eebefa26668a9d2c375533f84b4c68c4befd2))

### 📚 Documentation

- **(readme)**: Fix minor typo - ([a6ca941](https://github.com/stanfordnlp/dspy/commit/a6ca94173cba3884915829bad98aedd29cac4f6e))

### 💊 Bug Fixes

- **(dependency/semver)**: Updated semver to allow tests to run - ([bb7e18e](https://github.com/stanfordnlp/dspy/commit/bb7e18ea37886f48d15d67912d5dc62f93cf049c))
- **(dspy)**: Added type check on evaluator result - ([902eb3a](https://github.com/stanfordnlp/dspy/commit/902eb3aa2cb3f61a2dd75564bba00a1db33248e1))
- **(dspy)**: Fix conditional in Module.named_parameters() to prevent infinite recursion - ([3585efc](https://github.com/stanfordnlp/dspy/commit/3585efc30fba837c07fc022d56201a518795eae8))
- **(dspy)**: Add metric_threshold to MIPROv2 - ([7cd4011](https://github.com/stanfordnlp/dspy/commit/7cd4011400aef8de19afac1ce363d7fe301a20b6))

## [2.4.12](https://github.com/stanfordnlp/dspy/compare/v2.4.11..v2.4.12) - 2024-07-08

### 💊 Bug Fixes

- **(GroundedProposer)**: Accept custom view_data_batch_size to create dataset summary - ([174b9b4](https://github.com/stanfordnlp/dspy/commit/174b9b42db53cc59da3a3e9d2bd16cf5bd0de007))
- **(miprov2)**: Custom view_data_batch_size pass to GroundPorposer to create dataset summary - ([6590d59](https://github.com/stanfordnlp/dspy/commit/6590d592f96daa627c7bc520a19abba33b6070cd))

## [2.4.11](https://github.com/stanfordnlp/dspy/compare/v2.4.10..v2.4.11) - 2024-07-06

### 🚀 Features

- **(dspy)**: Support for pandas dataframe in dataloader and ruff fixes - ([2a63778](https://github.com/stanfordnlp/dspy/commit/2a63778b82bf382a547f62d7f5f38f375853e4c6))
- **(dspy)**: Add support for PremAI vectorizer - ([899b65c](https://github.com/stanfordnlp/dspy/commit/899b65c4e4616e650ae51bcd8f3921562cb9d6cb))
- **(dspy)**: Added PREMAI api key recognizer from env - ([39ca9f9](https://github.com/stanfordnlp/dspy/commit/39ca9f9b1529562e24cba873d58418900883da5a))
- **(dspy)**: Support for pandas dataframe in dataloader and ruff fixes - ([e70d5b9](https://github.com/stanfordnlp/dspy/commit/e70d5b952fd7b02b79affe3def84f7e45ee5e984))
- **(dspy)**: Added support for managed identity in AzureOpenAI - ([70c6f21](https://github.com/stanfordnlp/dspy/commit/70c6f219031970f537a062f522c3d03c93c0d2b3))
- **(tests)**: Remove base.py - ([481e0f1](https://github.com/stanfordnlp/dspy/commit/481e0f1073e69433b53b6b09f5b31c9948b658c0))
- **(tests)**: Revert requirements.txt - ([beca119](https://github.com/stanfordnlp/dspy/commit/beca1197ed5e7631ad23989fa749591bcba78c97))
- **(tests)**: Arnav comments on intro integration - ([e06883c](https://github.com/stanfordnlp/dspy/commit/e06883cff49014fbee30e3e6ca2fe8e2c8ab64ff))
- **(tests)**: Remove second ruff. - ([1c65f3c](https://github.com/stanfordnlp/dspy/commit/1c65f3c40745de44411cffff2322f6a1534567aa))
- **(tests)**: Cleanup. - ([c9e687e](https://github.com/stanfordnlp/dspy/commit/c9e687e9d7b63bb29ec29f4763a68a64155d7855))
- **(tests)**: Fix ruff. - ([b42e8bf](https://github.com/stanfordnlp/dspy/commit/b42e8bf0da8ce9fb6eab213ba62efdda1e538dc3))
- **(tests)**: Fix ruff. - ([26f2ffd](https://github.com/stanfordnlp/dspy/commit/26f2ffd00c8144ce2c97cb2e8326db547e7c6b1c))
- **(tests)**: Fix ruff. - ([01b671d](https://github.com/stanfordnlp/dspy/commit/01b671dedafe47918b70e5b8e5e4fc4727d0ee7b))
- **(tests)**: Fix ruff. - ([1be9a20](https://github.com/stanfordnlp/dspy/commit/1be9a20fab1eaa7a779fb1505954fe576d3f5147))
- **(tests)**: Fix ruff. - ([66309ee](https://github.com/stanfordnlp/dspy/commit/66309ee9dd541ad5d72af08f53a4589cb16c58da))
- **(tests)**: Revert requirements. - ([c1d49c0](https://github.com/stanfordnlp/dspy/commit/c1d49c0e9c850f28df5a75618af873bac136eb89))
- **(tests)**: Show ruff errors. - ([f0bd17d](https://github.com/stanfordnlp/dspy/commit/f0bd17db427535ee50e6cf4328c697e1192fe412))
- **(tests)**: Clean up. - ([c1aa768](https://github.com/stanfordnlp/dspy/commit/c1aa768743e825956a5fae962494e8050680b530))
- **(tests)**: Revert pre-commit. - ([a11e80e](https://github.com/stanfordnlp/dspy/commit/a11e80ee7542e89adeeaa9c1ff99d753bc2ca8f0))
- **(tests)**: Revert cache - ([9a847f5](https://github.com/stanfordnlp/dspy/commit/9a847f53c3a06c5d28cda333b61f4681baf73253))
- **(tests)**: Revert cache - ([53fb2a5](https://github.com/stanfordnlp/dspy/commit/53fb2a5866764b44383a88af2a2898bb26aaafcf))
- **(tests)**: Split requirements and requirements-dev - ([5f31aa2](https://github.com/stanfordnlp/dspy/commit/5f31aa226ee66c005d4fadaa91f7cfb111181398))
- **(tests)**: Remove pytest-ci.ini - ([a6f1395](https://github.com/stanfordnlp/dspy/commit/a6f1395939015f508b39eaab387eb21f604f888a))
- **(tests)**: Fix run_tests.yml - ([5d994d4](https://github.com/stanfordnlp/dspy/commit/5d994d4f71f3a58a72db714d342c1d37feb69260))
- **(tests)**: Fix run_tests.yml - ([d6a36f9](https://github.com/stanfordnlp/dspy/commit/d6a36f934f1a947dcff941d259fa82ba4af4ffa2))
- **(tests)**: Fix run_tests.yml - ([f5573c5](https://github.com/stanfordnlp/dspy/commit/f5573c57353423becaabbff9e6a5ecb8287fccf6))
- **(tests)**: Add new pytest-ci.ini - ([9c2652d](https://github.com/stanfordnlp/dspy/commit/9c2652de726053feb9611a0d67af91a75410adca))
- **(tests)**: Remove top import. - ([9811198](https://github.com/stanfordnlp/dspy/commit/981119889ca8c49753c0eef3b814beaac3fee3c4))
- **(tests)**: Fix cache in the ci. - ([f14c91d](https://github.com/stanfordnlp/dspy/commit/f14c91d79c50cefd1c43cfe39240a7fe7cfbaa6c))
- **(tests)**: Fix cache in the ci. - ([87dd340](https://github.com/stanfordnlp/dspy/commit/87dd340e9fb2e5837801314b0faf2b229d57d632))
- **(tests)**: Fix cache in the ci. - ([c5e1e28](https://github.com/stanfordnlp/dspy/commit/c5e1e2899cd0ed6a6eed45cc6374ce1f68b114f3))
- **(tests)**: Fix versions for cache. - ([abdb933](https://github.com/stanfordnlp/dspy/commit/abdb9337e9d70ce490ec9d6bf91a0dcf3eeb9270))
- **(tests)**: Fix versions for cache. - ([9de0989](https://github.com/stanfordnlp/dspy/commit/9de09891283a8bdd63b3e8882f2414b74cd66b2b))
- **(tests)**: Add print for start file. - ([29ec21f](https://github.com/stanfordnlp/dspy/commit/29ec21f781ace7a7fdba6aaca5019a63ac84e526))
- **(tests)**: Cache file. - ([4ad4b9f](https://github.com/stanfordnlp/dspy/commit/4ad4b9ff1197295bc18bc0ba443ee601f43131e1))
- **(tests)**: Cache file. - ([a7c229e](https://github.com/stanfordnlp/dspy/commit/a7c229e4bc02c55bcec0a490a2ae267f33277f53))
- **(tests)**: Cache file. - ([cac66f8](https://github.com/stanfordnlp/dspy/commit/cac66f8efd86f128ce643a14178e060e813d7a90))
- **(tests)**: Cache file. - ([b2e51bb](https://github.com/stanfordnlp/dspy/commit/b2e51bbf76d7463717515ffbede46ef0cf9504b8))
- **(tests)**: Cache file. - ([8f81e6c](https://github.com/stanfordnlp/dspy/commit/8f81e6ce844f72e756b888e5cb51aabe2fda8c37))
- **(tests)**: Cache file. - ([0098e4e](https://github.com/stanfordnlp/dspy/commit/0098e4e74316924d7fbf6717e2c20ac06f5be1b0))
- **(tests)**: Change it to ci way -\_- - ([b4f3391](https://github.com/stanfordnlp/dspy/commit/b4f33913af5a670b27dc4cdff9f55ef5e0dd9dac))
- **(tests)**: Change it to ci way -\_- - ([d96c0ce](https://github.com/stanfordnlp/dspy/commit/d96c0ce78d34f171d42253bb76bf809c308b825d))
- **(tests)**: Change it to ci way -\_- - ([11c84bb](https://github.com/stanfordnlp/dspy/commit/11c84bb45226f0dc2936f75ad0c1608851f73d3b))
- **(tests)**: Change it to ci way -\_- - ([3b7da8d](https://github.com/stanfordnlp/dspy/commit/3b7da8d81657a75e54a62236b482070ccf5dc5ad))
- **(tests)**: Change it to ci way -\_- - ([f7fa698](https://github.com/stanfordnlp/dspy/commit/f7fa69878f836b6de7c2705ac130fa68867afb29))
- **(tests)**: Change it to ci way -\_- - ([81851d1](https://github.com/stanfordnlp/dspy/commit/81851d124cbc7faf54ea2af31e250375d01f7e59))
- **(tests)**: Change it to ci way -\_- - ([065f2d1](https://github.com/stanfordnlp/dspy/commit/065f2d120b500652e6d684fa3b86a70093e18d3f))
- **(tests)**: Change it to ci way -\_- - ([35c39ad](https://github.com/stanfordnlp/dspy/commit/35c39ad5f8a5ef90ff6d34060d5147ff28f5f6c3))
- **(tests)**: Change it to ci way -\_- - ([e593154](https://github.com/stanfordnlp/dspy/commit/e593154132e102790037f64f6938f2417fe0dd11))
- **(tests)**: Change it to ci way -\_- - ([f6a64e3](https://github.com/stanfordnlp/dspy/commit/f6a64e36d12a15e387d4fccc970a4f1227c2b10a))
- **(tests)**: Change it to ci way -\_- - ([73ff317](https://github.com/stanfordnlp/dspy/commit/73ff317f05e095f5802aae03a3cab42a61173a39))
- **(tests)**: Add pytest.ini for integration - ([598f831](https://github.com/stanfordnlp/dspy/commit/598f8319dbadb6bca5cc3bfc355092b020a0ae5c))
- **(tests)**: Add pytest.ini for integration - ([742eb56](https://github.com/stanfordnlp/dspy/commit/742eb56616fdd8673df9d7f21acafc4792e1c604))
- **(tests)**: Add integration test to CI. - ([56b00ad](https://github.com/stanfordnlp/dspy/commit/56b00adb009fd6535e66ff5f9cf0eabbfc76293f))
- **(tests)**: Add integration test to CI. - ([ff075fe](https://github.com/stanfordnlp/dspy/commit/ff075fed549975954c3c91a3c15504f7cf4962f1))
- **(tests)**: Add integration test to CI. - ([965fbf3](https://github.com/stanfordnlp/dspy/commit/965fbf35109cd61ce791f8e97badeccab397791f))
- **(tests)**: Add integration test to CI. - ([195cd03](https://github.com/stanfordnlp/dspy/commit/195cd03292ffb0d59c134475d410a1116e4d8237))
- **(tests)**: Add integration test to CI. - ([6df93fc](https://github.com/stanfordnlp/dspy/commit/6df93fce35063c4ecf2a7fc397d78f2f15814152))
- **(tests)**: Add integration test to CI. - ([2e10d67](https://github.com/stanfordnlp/dspy/commit/2e10d67ff17ff0a6127cd8b3a5ac939b1f6aab05))
- **(tests)**: TestIntroIntegration - ([32b5470](https://github.com/stanfordnlp/dspy/commit/32b5470579f2487846f85f71c256ae4079332d24))
- **(tests)**: TestIntroIntegration - ([b773796](https://github.com/stanfordnlp/dspy/commit/b77379676dc561e30353ef85469a29f6f0330443))
- **(tests)**: TestIntroIntegration - ([6f1c120](https://github.com/stanfordnlp/dspy/commit/6f1c1209dac538f71cb36a1fd06e501fb8e04e94))
- **(tests)**: Ignore assert in ruff - ([a1c8491](https://github.com/stanfordnlp/dspy/commit/a1c84916ca5910a4bb845a53033e5a970669dcfe))
- **(tests)**: BaseIntegrationTestWithCache - ([35dcaed](https://github.com/stanfordnlp/dspy/commit/35dcaed2e1b01a6f46fd322982a50800fb339c25))
- **(tests)**: Add requirements-dev.txt - ([9a8026c](https://github.com/stanfordnlp/dspy/commit/9a8026c2e0372e67527ec6b864d731bdf98a243f))

### 💊 Bug Fixes

- **(dspy)**: Run ruff - ([a8034f6](https://github.com/stanfordnlp/dspy/commit/a8034f68b897b7a566c45e6d948ad5f19cfe2b90))
- **(dspy)**: Remove redundant code by importing it from module - ([b61d78a](https://github.com/stanfordnlp/dspy/commit/b61d78ac04cb8f210b840b2642709f7fc378ecef))
- **(dspy)**: Run ruff - ([6a9de65](https://github.com/stanfordnlp/dspy/commit/6a9de6545a68ace19067b61d8893bd4504ae5476))
- **(dspy)**: Missing typing imports - ([4ae8049](https://github.com/stanfordnlp/dspy/commit/4ae8049329e9a1781e29871510a51d190fdb07ee))
- **(dspy)**: Fixed the doc length in Vectorizer class - ([ec09f4a](https://github.com/stanfordnlp/dspy/commit/ec09f4a133bb65b5d6ad8d13b0005ef92b60abd4))
- **(dspy)**: Add from error after raise - ([d99e549](https://github.com/stanfordnlp/dspy/commit/d99e5494f3e45fc0bcb1923ff15e120bdafbcce0))
- **(dspy)**: Remove dummy csv file - ([00c7b65](https://github.com/stanfordnlp/dspy/commit/00c7b65a0ed11fa4fc53b59283eb632d190d3f97))
- Remove cache issue and retriever bugs - ([cf4191b](https://github.com/stanfordnlp/dspy/commit/cf4191b21d071217c11ea9d7423a254ff869c3d8))

### 🚜 Refactor

- **(dspy)**: Revert to initial implementation with from_pandas function - ([3f50a79](https://github.com/stanfordnlp/dspy/commit/3f50a7956b7e2cb5245c17f67cb9e0517185539a))

## [2.4.10](https://github.com/stanfordnlp/dspy/compare/v2.4.9..v2.4.10) - 2024-06-21

### 🚀 Features

- **(dspy)**: Nvidia TensorRT LLM integration - ([b75dd73](https://github.com/stanfordnlp/dspy/commit/b75dd7314da2b3ee21fe00d9a801021337953181))
- **(dspy)**: Introducing Prem Templates in dspy - ([b727d12](https://github.com/stanfordnlp/dspy/commit/b727d1253d9a482382e3125a71166a17d05d0000))
- **(dspy)**: Add docs - ([f3db229](https://github.com/stanfordnlp/dspy/commit/f3db229496b8f238d159bd307aaeabe46dcc2bd7))
- **(dspy)**: Add helper method for updating multiple signatures at once - ([2e58656](https://github.com/stanfordnlp/dspy/commit/2e586565ed736d78ae184112e1fabac090318436))
- **(dspy)**: Add replace method to signiture class - ([63e2297](https://github.com/stanfordnlp/dspy/commit/63e229728754bbf766a5c1479d1873c97522b242))
- **(dspy)**: Added retrieval module for Watson Discovery ([#1100](https://github.com/stanfordnlp/dspy/issues/1100)) - ([57527d4](https://github.com/stanfordnlp/dspy/commit/57527d41e44e52bb32409a1a857a52642f5de9b4))
- **(dspy)**: Generate a graphical representation of modules - ([0c1326d](https://github.com/stanfordnlp/dspy/commit/0c1326d3a01d2aba44f87776a8420501480b13c2))
- **(dspy)**: Generate a graphical representation of modules - ([cad5291](https://github.com/stanfordnlp/dspy/commit/cad5291312a8aaf97ba8a12e8f4df5b7fd872b50))
- **(dspy)**: Generate a graphical representation of modules - ([383cca5](https://github.com/stanfordnlp/dspy/commit/383cca5463d5d56a9d1d609294c51632fbb24827))
- **(dspy)**: Add epsilla retriever - ([4d4ca25](https://github.com/stanfordnlp/dspy/commit/4d4ca25114fc4dd46919c2e496ae0206e6c8bbbe))
- **(dspy)**: Add MyScale in Retrieve - ([47b45d2](https://github.com/stanfordnlp/dspy/commit/47b45d267f69ad1344a83ffdae48d1a6f2db3f98))
- **(dspy)**: Add MyScale in Retrieve - ([e150392](https://github.com/stanfordnlp/dspy/commit/e150392918bf32d4bc66ea6987502cf7c2f14fd8))
- **(dspy)**: Add MyScale in Retrieve - ([7510b12](https://github.com/stanfordnlp/dspy/commit/7510b12b1596d94b85730bd979adb568d7dc36c6))
- **(dspy)**: Add MyScale in Retrieve - ([5346766](https://github.com/stanfordnlp/dspy/commit/53467661b0b27b88dcb208c7327d083ce1e5bc2a))
- **(dspy)**: Add MyScale in Retrieve - ([b1d53e3](https://github.com/stanfordnlp/dspy/commit/b1d53e3f3d085a4ab1481c24e0c4908937b0fbd5))
- **(dspy)**: Add MyScale in Retrieve - ([bbadff7](https://github.com/stanfordnlp/dspy/commit/bbadff7b3c2c023b70c3eec33a7b964b7dc30d24))
- **(dspy)**: Nested models - ([052700c](https://github.com/stanfordnlp/dspy/commit/052700c4438003e33501a949067154ee3a4ef7a1))
- **(dspy)**: Add a test - ([2edd705](https://github.com/stanfordnlp/dspy/commit/2edd705a35221ab192fc7e83514fdb4e5553dc16))
- **(dspy)**: Make logic simplet - ([c237252](https://github.com/stanfordnlp/dspy/commit/c2372522955feec26747e869b95d4119c9d7d178))
- **(dspy)**: Update mechanism by which paser is applied - ([7e87595](https://github.com/stanfordnlp/dspy/commit/7e875950b99ce93e8d0dbfc4231a583898ed252f))
- **(dspy)**: Merge branch 'main' into feature/try-model-validate-before-hardcoded-string-logic-in-typed-predictor - ([90e7046](https://github.com/stanfordnlp/dspy/commit/90e7046c637c3f85aadfb5b6ca40f6f454b7a6b8))
- **(dspy)**: Fix typing for 3.9 - ([f6958c3](https://github.com/stanfordnlp/dspy/commit/f6958c3ff28b43ead816b165b44e7d1477e574f5))
- **(dspy)**: Try from json before applying formatting logic in typed predictor - ([7c2ffff](https://github.com/stanfordnlp/dspy/commit/7c2ffffc51c56b4bfa64c76b8f6a5240f41a2323))
- **(dspy)**: Added support for prem repositories natively in dspy - ([3b12cd6](https://github.com/stanfordnlp/dspy/commit/3b12cd6a4e117c5a9bff7b725efb50ffe18ec164))
- **(dspy)**: Add premai python sdk - ([9b021f0](https://github.com/stanfordnlp/dspy/commit/9b021f02554fd00e00f6fba6d69a1733f9ea85f7))
- **(dspy)**: Added Snowflake Cortex (LM) and Snowflake RM support - ([bbb6204](https://github.com/stanfordnlp/dspy/commit/bbb62045538dd2e32a4b4f425403c7bc22d26c3c))
- **(dspy)**: Added Snowflake Cortex (LM) and Snowflake RM support - ([8ce1378](https://github.com/stanfordnlp/dspy/commit/8ce13780e72e5406a4ad640b9ad8a6e28c939e82))
- **(dspy)**: Added SnowflakeRM retriever and cleanup of Snowflake (LM) support - ([f42df77](https://github.com/stanfordnlp/dspy/commit/f42df77df10b5a6c41cce1ee67d28b98875e1479))
- **(dspy)**: Added SnowflakeRM retriever and cleanup of Snowflake (LM) support - ([6af2d47](https://github.com/stanfordnlp/dspy/commit/6af2d47d05f182e18fdb715f79cc9c152adad2c2))
- **(dspy)**: Added SnowflakeRM retriever and cleanup of Snowflake (LM) support - ([f2ce44f](https://github.com/stanfordnlp/dspy/commit/f2ce44fa02fb38d0523885cde31ed1baf44bc62a))
- **(dspy)**: Added SnowflakeRM retriever and cleanup of Snowflake (LM) support - ([e492cfa](https://github.com/stanfordnlp/dspy/commit/e492cfaca892aacd564461123cbeccc967dbd411))
- **(dspy)**: Initial cleanup of Snowflake (LM)support - ([dfae177](https://github.com/stanfordnlp/dspy/commit/dfae177731d33b84bc0430b9f8ec44e8fe643696))
- **(dspy)**: Testing initial commit - ([d7b41cd](https://github.com/stanfordnlp/dspy/commit/d7b41cd7299e1bdf91f36c124d172d6807444a69))
- **(dspy)**: Add dspy.Claude helper - ([bb88c79](https://github.com/stanfordnlp/dspy/commit/bb88c795b7df62b0366c9ac8c195d86eb0bb7e2c))
- **(llamaindex)**: Refactored tests - ([d630d8e](https://github.com/stanfordnlp/dspy/commit/d630d8eb2260d937856ccb000751fbe110c73196))
- **(llamaindex)**: Added llamaindex rm - ([1bebd46](https://github.com/stanfordnlp/dspy/commit/1bebd460c60de1021c2eec7c4cac59acc981270f))
- **(llamaindex)**: Added llamaindex support - ([b3b47eb](https://github.com/stanfordnlp/dspy/commit/b3b47eba4f2314b858970c24f6632c93cbb8328a))
- Adds Cloudflare Workers AI - ([3dcddbe](https://github.com/stanfordnlp/dspy/commit/3dcddbef43bba72adc217b0bbd496b19abe16997))

### 📚 Documentation

- **(building-blocks)**: Fix typos and missing hyperlinks - ([de13626](https://github.com/stanfordnlp/dspy/commit/de13626f58a2361049456c8b4fd45d2dadae2fc7))
- **(dspy)**: Create TensorRTLLM.md - ([ddde99a](https://github.com/stanfordnlp/dspy/commit/ddde99a04d41769c7422a6725c787f2d67a00a37))
- **(dspy)**: Fix typos and add additional explaination - ([052e4c3](https://github.com/stanfordnlp/dspy/commit/052e4c3c771024e37d468a8ce8786989d83f86ea))
- **(dspy)**: Updated dspy docs with Prem Templates - ([3ef2688](https://github.com/stanfordnlp/dspy/commit/3ef26886eb5e63948afb1368b1243a83b25ed017))
- **(dspy)**: Removed additional retrievals in docs - ([1db9cb9](https://github.com/stanfordnlp/dspy/commit/1db9cb93673b5797675071165116ed8d6b9b3090))
- **(dspy)**: Removed session id and support for prem repositories - ([1f621d7](https://github.com/stanfordnlp/dspy/commit/1f621d7d048e572a3d19574abc06ed43e7c5d8f6))
- **(dspy)**: Added prem repositories support in dspy prem documentation - ([b708d86](https://github.com/stanfordnlp/dspy/commit/b708d86b21207ee31219ab25786524fcaef1ef42))
- **(dspy)**: Adding documentation for Snowflake RM - ([daef34e](https://github.com/stanfordnlp/dspy/commit/daef34e9a36ab31e7b27df47368d7400ce4c19e1))
- **(dspy)**: Adding documentation for Snowflake RM - ([2cb77df](https://github.com/stanfordnlp/dspy/commit/2cb77df507f507eb2029b096b91c9d39d59c15de))
- **(dspy)**: Adding documentation for Snowflake LM - ([c663444](https://github.com/stanfordnlp/dspy/commit/c663444fec6ed20f61171c3d5af15cac84a04b77))
- Qdrant RM example - ([b0b0308](https://github.com/stanfordnlp/dspy/commit/b0b03084a1dc17d6cdd87822a5cad99dd7016424))
- Clarify deployment_id for Azure - ([58c3ba6](https://github.com/stanfordnlp/dspy/commit/58c3ba6dff5ecddb4a6a7ff227bdaee78c28acb2))
- Add tutorial on dspy program tracing & optimization tracking to readme - ([b88693d](https://github.com/stanfordnlp/dspy/commit/b88693d6bbb9d99b1159087d5b34070f1448b7e2))
- Add tutorial on dspy program tracing & optimization tracking - ([f467098](https://github.com/stanfordnlp/dspy/commit/f46709882905274a4aeff72714f6a30c03cab0f1))

### 💊 Bug Fixes

- **(aws_models)**: Fix issues 894 and 858 - ([0a7a460](https://github.com/stanfordnlp/dspy/commit/0a7a4600f11e8a74f019ae4f2aeb81c3f67c2cb2))
- **(conflicts)**: Resolved li dependency conflicts - ([216546b](https://github.com/stanfordnlp/dspy/commit/216546b92c463a66f133694249801e050f750002))
- **(dependencies)**: Updated LI tests to be optional - ([269d9e8](https://github.com/stanfordnlp/dspy/commit/269d9e8822ce73839a85f896db7ca6bcccbb2494))
- **(dsp)**: AWS::max_new_token is redundant to LM::max_tokens - ([59241d5](https://github.com/stanfordnlp/dspy/commit/59241d51840f4f0c17030b69afc737b554b07c52))
- **(dsp)**: Indicate other completions only if choices is list, not string - ([5d3d7b3](https://github.com/stanfordnlp/dspy/commit/5d3d7b304f0ac2342d58011e43dc72767f4de542))
- **(dspy)**: Return type of basic request as list not str - ([5d98bf2](https://github.com/stanfordnlp/dspy/commit/5d98bf2f0da73e8191e9ed919c930d2ac1070530))
- **(dspy)**: Fixed formatting - ([386aa53](https://github.com/stanfordnlp/dspy/commit/386aa535f4e78c86db8877842f408df12126a73e))
- **(dspy)**: Re-added \*\*kwargs argument in the search function - ([f0d4e13](https://github.com/stanfordnlp/dspy/commit/f0d4e13a9c48b0ad195c663f140590914fa9c31f))
- **(dspy)**: Fixed bug in retriever part - ([010d7ba](https://github.com/stanfordnlp/dspy/commit/010d7ba9350546199af18c09c67255d2b379257f))
- **(dspy)**: Fix return type in \_generate - ([6f9c1f3](https://github.com/stanfordnlp/dspy/commit/6f9c1f37d2dc885e630e5ef9ad866ea4fcf248ed))
- **(dspy)**: Add additional comma btwn cloudflare and google - ([ffbc0cd](https://github.com/stanfordnlp/dspy/commit/ffbc0cd7454ad26ce7638689afa1297ab7f14e58))
- **(dspy)**: Add TensorRTModel in **init** and change import info in docs - ([478f6a5](https://github.com/stanfordnlp/dspy/commit/478f6a528ba877d764838760ec619a8070352c80))
- **(dspy)**: Provide type check for history - ([c8726b9](https://github.com/stanfordnlp/dspy/commit/c8726b97959ed16f27ade2361d2b2e792a3f26d5))
- **(dspy)**: Together client response parsing - ([285dc90](https://github.com/stanfordnlp/dspy/commit/285dc907de4186e573c497ed2209f3ba4588ae4d))
- **(dspy)**: Fix langchain predict ([#1091](https://github.com/stanfordnlp/dspy/issues/1091)) - ([a8c1a0f](https://github.com/stanfordnlp/dspy/commit/a8c1a0f4166e9335c93a66ea7f6289137b0787ee))
- **(dspy)**: Run ruff - ([6bc6fdc](https://github.com/stanfordnlp/dspy/commit/6bc6fdc8d2ce70862eea0b3b0be7b8016053f469))
- **(dspy)**: Imports and minor bugs - ([86f5470](https://github.com/stanfordnlp/dspy/commit/86f5470fd30997c6dfec3847308103a8ec19ff91))
- **(dspy)**: Lint and run - ([852e3bf](https://github.com/stanfordnlp/dspy/commit/852e3bf0f7818b402a32cf2905ee462310057cd3))
- **(dspy)**: Adding LM connection parameter update to docs, resolving ruff issues and failing tests - ([23cd780](https://github.com/stanfordnlp/dspy/commit/23cd780897c908f61906069c810aae4ae0c89b9f))
- **(dspy)**: Solving for null response bug in Cortex API - ([8dedd00](https://github.com/stanfordnlp/dspy/commit/8dedd000d59c6c45cda037faf223eaa75c6bee86))
- **(dspy)**: Updating syntax for Snowflake cos similarity method which will be deprecated at the end of the month - ([b0b18a7](https://github.com/stanfordnlp/dspy/commit/b0b18a7d7d19ea3663a1502faab5a4e3bc0afbee))
- **(dspy)**: Updating syntax for Snowflake cos similarity method which will be deprecated at the end of the month - ([53630da](https://github.com/stanfordnlp/dspy/commit/53630da5f5789c2a43090429062c6cf979202243))
- **(dspy)**: Updating syntax for Snowflake cos similarity method which will be deprecated at the end of the month - ([b3af69c](https://github.com/stanfordnlp/dspy/commit/b3af69cc0528c5e53c57f5ec8c7694b3f4da1f66))
- **(dspy)**: Updating syntax for embeddings method call which will be deprecated - ([a048a51](https://github.com/stanfordnlp/dspy/commit/a048a511f8e95b2916a802c55481bd4ce1001ae8))
- **(dspy)**: Adding language for recently released snowflake retriever model and updating snowflake session init to also include session log - ([8775674](https://github.com/stanfordnlp/dspy/commit/87756741ff47f962e237b4da3a42fee6463da364))
- **(dspy)**: Adding missing LLMs supported in Snowflake and tag for session logs - ([441fd43](https://github.com/stanfordnlp/dspy/commit/441fd434cbfb780e50e84b5007328600bf93caf4))
- **(dspy)**: Adding missing LLMs supported in Snowflake and tag for session logs - ([fad2f11](https://github.com/stanfordnlp/dspy/commit/fad2f11dd56d998fad91ae141da561f2703a1c36))
- **(dspy)**: Adding self.history definition to Snowflake LM - ([4f10658](https://github.com/stanfordnlp/dspy/commit/4f1065848af696e2469f55ce0676240405635a06))
- **(dspy)**: Updating sort order to be descending for retriever results - ([75cd65b](https://github.com/stanfordnlp/dspy/commit/75cd65bacf3217fbeb516106d5af6beba27e924e))
- **(dspy)**: Updating SnowflakeRM typos - ([cfa67d6](https://github.com/stanfordnlp/dspy/commit/cfa67d675a5991dfe09b0ead03b723622d0cf8c9))
- **(dspy)**: Updating README to include Snowflake as optional supported extras dependency - ([315d71a](https://github.com/stanfordnlp/dspy/commit/315d71abc994bbf991420d73e4ba9fc47f28d5be))
- **(dspy)**: Updating import error handling language for SnowflakeRM - ([4ed0753](https://github.com/stanfordnlp/dspy/commit/4ed07531e5842f9f437722d7c93099613353398b))
- **(dspy)**: Removing unnecessary ipykernel dependency - ([bf9247f](https://github.com/stanfordnlp/dspy/commit/bf9247f08937089eccc5fbdba037420afe169472))
- **(dspy)**: Remove common indentations in signature according to Python docstring standards - ([f5e39ee](https://github.com/stanfordnlp/dspy/commit/f5e39eef9581839757b0ef689645a97a26e4129f))
- **(dspy)**: Added `copy` to `OllamaLocal` to propagate `model`, `model_type`, `base_url` and `timeout_s`. - ([c7d45b6](https://github.com/stanfordnlp/dspy/commit/c7d45b6d4bc33593e84213a16c85c5ce5c482bd9))
- **(dspy)**: Remove unreachable type condition in TypedPredictor - ([67e20ce](https://github.com/stanfordnlp/dspy/commit/67e20ce4427ea264c1aae4dcaab49b8e57b7df96))
- **(evaluate)**: Display table - ([d1075af](https://github.com/stanfordnlp/dspy/commit/d1075af4417cb6a0763e14956924f9e057079757))
- **(optimizer)**: Undo fix for issue #824 - ([9d582d9](https://github.com/stanfordnlp/dspy/commit/9d582d9e82f7b4c1267cde51e899d54dbd3d7f58))
- **(optimizer)**: Fixed issue #824 - ([0c40d09](https://github.com/stanfordnlp/dspy/commit/0c40d09e703f5519d9ace7d8885a97d02563d986))
- **(optimizer)**: Undo fix for issue #824 - ([12a9ae6](https://github.com/stanfordnlp/dspy/commit/12a9ae63916c2288ef27c5691810d8e5c9ab3b96))
- **(pinecone_rm)**: Refactored to use cloud_embed and fix pinecone init - ([f7f4ee7](https://github.com/stanfordnlp/dspy/commit/f7f4ee7964cd92389180aa1a2450dd4084511e84))
- Missing groq extra install option - ([9b864f5](https://github.com/stanfordnlp/dspy/commit/9b864f536485712b01881a462e256c6a4e262689))
- Typo in `faqs.md` - ([e51e19b](https://github.com/stanfordnlp/dspy/commit/e51e19b0bd42270e798bf2cfdc4788bc7ea2f8cf))
- Typo in `cheatsheet.md` - ([f729d83](https://github.com/stanfordnlp/dspy/commit/f729d83cf7ed441a7f55777998896622efcaaba2))
- Assertion and chain-of-thought bugs - ([bb074a7](https://github.com/stanfordnlp/dspy/commit/bb074a71a807f92f2910055b180fe8cb66f10b1a))

### 🧪 Testing

- **(evaluate)**: Update unit tests - ([0c14d38](https://github.com/stanfordnlp/dspy/commit/0c14d38f1ff3af871b5c9148b3d82f4e4a12ec71))

### 🚜 Refactor

- **(dspy)**: Added tensorrt_llm in history inspect - ([5fc1337](https://github.com/stanfordnlp/dspy/commit/5fc1337569f0f9586d1a815d41a09f1b38330e26))
- **(dspy)**: Add tensorrt llm in **init** - ([27a74c8](https://github.com/stanfordnlp/dspy/commit/27a74c83210b981c75721ff61b5c6e4502faf50e))
- **(dspy)**: Combined all_kwargs and kwargs into kwargs before passing to history - ([591ce61](https://github.com/stanfordnlp/dspy/commit/591ce6157249d8354783ace68368088c48a2572b))
- **(dspy)**: Added template id and params in kwargs - ([8d87850](https://github.com/stanfordnlp/dspy/commit/8d87850f0d1bfbd3045dc5b62c59427dedbc52ba))
- **(dspy)**: Removed template_id and params in all_kwargs - ([0a128a4](https://github.com/stanfordnlp/dspy/commit/0a128a43baea95dfcd856ff0940763e47fb7e8f6))
- **(dspy)**: Added prem integration as remote llm inside main doc - ([47f9199](https://github.com/stanfordnlp/dspy/commit/47f919949684d7c10c73d89cc50a3a3d214f1016))
- **(dspy)**: Added premai integration in **init** files - ([74944b3](https://github.com/stanfordnlp/dspy/commit/74944b33bac13793a736edebf0ccbcd6f425aaa8))
- **(inspect-history)**: Simplify branches - ([713f224](https://github.com/stanfordnlp/dspy/commit/713f224867a8f68024c57ee1758e710aafe6be3c))
- **(llama_index_rm)**: Per pr comments - ([a2f2bd2](https://github.com/stanfordnlp/dspy/commit/a2f2bd26eaa7e33b8dd8ce9bde28d061c0461686))
- QdrantRM - ([f8f7203](https://github.com/stanfordnlp/dspy/commit/f8f72035c5e4cce94210999e09359e797040e3be))

### ⚙️ Chore

- Simplified return qdrant_rm.py - ([33949d0](https://github.com/stanfordnlp/dspy/commit/33949d015e129b6c128108863abc5f07306969af))
- Poetry.lock - ([7738d8b](https://github.com/stanfordnlp/dspy/commit/7738d8b4336063253970453b72c327d605956fc4))

### 🎨 Styling

- **(code)**: Type fix - ([ab02886](https://github.com/stanfordnlp/dspy/commit/ab028862770f87c0a1f22924c0ed9bc828090709))

## [2.4.9](https://github.com/stanfordnlp/dspy/compare/v2.4.3..v2.4.9) - 2024-04-29

### 🚀 Features

- **(aws_models)**: Anthropic_version param should be set in constructor and is for bedrock only - ([8680068](https://github.com/stanfordnlp/dspy/commit/86800688ed3bedbfcf4c9bc06598ffef10530d65))
- **(docs)**: Documented the aws_provider class. Renamed the aws md files. Updated docs in aws_providers.py - ([b65e17f](https://github.com/stanfordnlp/dspy/commit/b65e17f02045fb7243e60c657015903a92b694e0))
- **(dspy)**: Add support for vector, hybrid and fulltext search in azure ai search - ([2818fce](https://github.com/stanfordnlp/dspy/commit/2818fce29e4ce306345a6deed6ba888ec66c9ebf))
- **(dspy)**: Add Milvus in Retrieve - ([c7f47bc](https://github.com/stanfordnlp/dspy/commit/c7f47bc9c0a28a3a40a7b6655663a49746a124fc))

- **(module)**: Update lock file since we added boto3 - ([f667bf2](https://github.com/stanfordnlp/dspy/commit/f667bf27a94300054c55fc26af945f3d6dbbc27f))
- **(modules)**: Deleteing obsolete code - ([f4dc495](https://github.com/stanfordnlp/dspy/commit/f4dc4955733cbaddd5f2aa05e6859009c8eaa83c))
- **(modules)**: Fixed bugs and tested inspect_history - ([51135c0](https://github.com/stanfordnlp/dspy/commit/51135c0c683f59a2b472d0cde15399d9beb5cf5e))
- **(modules)**: Added support for aws providers (bedrock and sagemaker) and models (mistral, anthropic, meta) - ([702c04f](https://github.com/stanfordnlp/dspy/commit/702c04fc25f351cfc12432d8276545b66cd70b0a))
- **(modules)**: Support inspect_history for aws models - ([d192057](https://github.com/stanfordnlp/dspy/commit/d19205741491d084ab47856831ac88d1fc9ecf87))
- **(modules)**: Added support for aws providers (bedrock and sagemaker) and models (mistral, anthropic, meta) - ([3477491](https://github.com/stanfordnlp/dspy/commit/34774912729c4f78553fe1f1ad7a3729c89bde92))
- FastEmbedVectorizer - ([5d3a1f9](https://github.com/stanfordnlp/dspy/commit/5d3a1f9b9477dbe02ac9dc3393ddd89b43b80eaa))
- Silence backoff - ([8d6c56d](https://github.com/stanfordnlp/dspy/commit/8d6c56dd545bd57d010262a67d48f8b71407c3a0))
- Expanded llm usage logging, and moved to debug - ([3c03bf0](https://github.com/stanfordnlp/dspy/commit/3c03bf068f876d9127b9b4461481291e9d9493c1))
- Deprecate log_azure_usage configuration setting - ([36e9ae7](https://github.com/stanfordnlp/dspy/commit/36e9ae7f9177d410a7e18f65962e46d387797168))
- Moved logging basicConfig to function opt in - ([6991cc6](https://github.com/stanfordnlp/dspy/commit/6991cc63e8bd3f880b1ee114afdb4b806cfb5785))

### 📚 Documentation

- **(aws)**: Removed pylint disable and tweaked import error message - ([1b45f72](https://github.com/stanfordnlp/dspy/commit/1b45f721c2f24d65e5922177f75cd5d9f66a7ed1))
- **(aws.md)**: Added commentary on AWSModel methods - ([fbe22a2](https://github.com/stanfordnlp/dspy/commit/fbe22a233efab5a7839df0b02981ad0501e887f0))
- **(aws.md)**: Fixed typo - ([f33eeff](https://github.com/stanfordnlp/dspy/commit/f33eeff3389c9c8c0772ce9c6e5adf4d3c2f3b2b))
- **(aws.md)**: Changed lm calls to dspy.Bedrock etc. - ([d2707eb](https://github.com/stanfordnlp/dspy/commit/d2707eb7d019710ba10b75176be7186af2ac9f8a))
- **(dspy)**: Fixed doc string for OpenAI having wrong default model ([#794](https://github.com/stanfordnlp/dspy/issues/794)) - ([38c26cc](https://github.com/stanfordnlp/dspy/commit/38c26cc14b50eedb9840ba36f080dc507c7226b0))

- **(faqs)**: Update documentation for disabling the cache - ([42b95ca](https://github.com/stanfordnlp/dspy/commit/42b95ca3fb54e4047b7ff0eee4bfa2728b5a7aaf))
- **(rag)**: Fix broken link - ([a983662](https://github.com/stanfordnlp/dspy/commit/a983662ba16232537057c0d925f5bf35c7edc1a4))
- Add tutorial on dspy program tracing & optimization tracking ([#926](https://github.com/stanfordnlp/dspy/issues/926)) - ([ae23d6e](https://github.com/stanfordnlp/dspy/commit/ae23d6ee5f1199e4b740f4aa904b33f673e936ee))

### 💊 Bug Fixes

- **(cohere)**: Catch attribute error - ([64209c1](https://github.com/stanfordnlp/dspy/commit/64209c1287299ea5bfd0aa5818caa89cd7c4799f))
- **(dependencies)**: Update ^2.0 to ~= 2.0 - ([3d0d814](https://github.com/stanfordnlp/dspy/commit/3d0d814f5f22cbb7d79288018bfc8036ec79bf14))
- **(dspy)**: Fix spelling mistake in azure ai search - ([4067d9a](https://github.com/stanfordnlp/dspy/commit/4067d9a3ac28b1e264c8de50d315a8e73e6827ce))
- **(dspy)**: Update the pyproject.toml - ([d94294c](https://github.com/stanfordnlp/dspy/commit/d94294c29aeb909706b99454401a80af2aad9ec3))
- **(dspy)**: Update the pyproject.toml - ([05bba1c](https://github.com/stanfordnlp/dspy/commit/05bba1c88d1e556bbb13f1dd6914a0cba6060498))
- **(dspy)**: Add author doc string for azure ai search retrieval module - ([385a35d](https://github.com/stanfordnlp/dspy/commit/385a35d0daf273050dd1e6531af37110e7e9d4be))
- **(dspy)**: Update documentation for azure ai search retrieval class - ([94b7fcd](https://github.com/stanfordnlp/dspy/commit/94b7fcdb06c527d34da2eb2287539cf5cb266073))
- **(dspy)**: Update args description for azure ai search retrieval module - ([fdf76cc](https://github.com/stanfordnlp/dspy/commit/fdf76cc2cf14366b2adbceb3dab8e22a08f42b61))
- **(dspy)**: Update pyproject.toml - ([807882c](https://github.com/stanfordnlp/dspy/commit/807882c390fa8167dbad91f03f83c6961bc285d8))
- **(groq_client)**: Corrected attribute access in log_usage - ([50c6ae0](https://github.com/stanfordnlp/dspy/commit/50c6ae0f5001e5b36ac02dace084886ade73a913))
- **(qdrant_rm)**: Forward can be called without specifying k - ([8c410cf](https://github.com/stanfordnlp/dspy/commit/8c410cfaf1be35545d21ffce9c80ae53c212c3cb))
- Remove set_log_level and fix LOG_LEVEL environment variables - ([43edcd0](https://github.com/stanfordnlp/dspy/commit/43edcd06da68bbfc6ecf6223fe43a74fd9cade93))
- Remove redundant tqdm redirect - ([b446554](https://github.com/stanfordnlp/dspy/commit/b44655406308c681e247fd0ba8e036de474c39e6))
- Add DeprecationWarning to Evaluate - ([136896b](https://github.com/stanfordnlp/dspy/commit/136896b3d3ef11bbce2fc9861c947e7e9e65205a))
- Move copro to dspy.logger versus print logger - ([f7c0dac](https://github.com/stanfordnlp/dspy/commit/f7c0dac434bcd913cb604c5ade25a62af2bae5dd))
- Move tqdm in evaluate to output to stdout to match dspy.logger - ([cbdfefa](https://github.com/stanfordnlp/dspy/commit/cbdfefa652a502b447eaea832daeb6c377203c35))
- Remove logging.basicConfig from groq_client - ([5f3ab10](https://github.com/stanfordnlp/dspy/commit/5f3ab1014b718247de37e5c4915f84774d9b9c08))
- Moved faiss_rm to dspy.logger - ([1181d80](https://github.com/stanfordnlp/dspy/commit/1181d803d27ef9db8943b8a76f3a845706ff567f))
- Removed assertions specific log in favour of generic dspy.logger - ([8300b68](https://github.com/stanfordnlp/dspy/commit/8300b6839520d62c8240e0c710611125a63e95e6))

### 🛠 Continuous Integration

- Removed FastEmbed run_tests.yml - ([f47a304](https://github.com/stanfordnlp/dspy/commit/f47a304ca3d97919deabfaf63c26230731e45603))
- FastEmbed tests - ([9b04c68](https://github.com/stanfordnlp/dspy/commit/9b04c68f8eed9da0af6d7ac19b2a5e657f2f4d26))

### ⚙️ Chore

- Poetry.lock - ([33c4c2c](https://github.com/stanfordnlp/dspy/commit/33c4c2c147a2718cd1b59ca474bc1d86bba86bcb))
- Poetry.lock - ([62b4fad](https://github.com/stanfordnlp/dspy/commit/62b4fad9fe69d61228e2d02189ec6eec21d1fe11))
- Ruff fixes - ([d8fb600](https://github.com/stanfordnlp/dspy/commit/d8fb600f0cdb9c708f51b27f4226f8546a6b3507))
- Clean up comments - ([91e39f6](https://github.com/stanfordnlp/dspy/commit/91e39f6aa4976206e5643efe443f296d893a5de3))
- Ruff fixes - ([9de3076](https://github.com/stanfordnlp/dspy/commit/9de30764498f4f255da07454ddba1cfa0cbc6992))
- Moved print logging to dspy.logger for bootstrap and random search - ([1088ea0](https://github.com/stanfordnlp/dspy/commit/1088ea05c62a261f92a8b97e97b6d1c8461563c3))
- Deprecated, display input argument, instead log all messages by default - ([d1d6cc6](https://github.com/stanfordnlp/dspy/commit/d1d6cc6ec9901379e67fe78ff76952018111fd4f))

### 🎨 Styling

- **(dspy)**: Run ruff check - ([355174d](https://github.com/stanfordnlp/dspy/commit/355174d59606c1fc77046299e73f8d7817f7c130))

## [2.4.3] - 2024-04-08

### 🚀 Features

- **(Evaluate)**: Callable objects can be used as metric for Evaluate - ([1900081](https://github.com/stanfordnlp/dspy/commit/1900081c03d82d110969d8f7e3e61c98f73da250))
- **(ProgramofThought)**: Added support for custom whitelist and dynamic input and output field naming for program of thought. - ([8e246e0](https://github.com/stanfordnlp/dspy/commit/8e246e067a72bca75e989d806862379d0da3f4f4))
- **(bedrock-lm)**: Set boto3 as an optional dependency - ([b78b922](https://github.com/stanfordnlp/dspy/commit/b78b922e3ada92134e4b6b0c6670466c435a24c2))
- **(bedrock-lm)**: Added a LM for Bedrock and a base AWS LM class that can later be used for Sagemaker. - ([04fad29](https://github.com/stanfordnlp/dspy/commit/04fad29321fb1c090dc6a76d77271d33c2af29a7))
- **(data-generation)**: Implement dynamic synthetic data generation from pydantic model or via initial sample data - ([c73f9c0](https://github.com/stanfordnlp/dspy/commit/c73f9c0b6b922ad9a631c5fb79a624cae39af418))
- **(data-generation)**: Implement dynamic synthetic data generation from pydantic model or via initial sample data - ([76750d2](https://github.com/stanfordnlp/dspy/commit/76750d2058044901373cf0b016ac00767ad064b1))
- **(data-generation)**: Implement dynamic synthetic data generation from pydantic model or via initial sample data - ([94a3cd3](https://github.com/stanfordnlp/dspy/commit/94a3cd33106baf5eb84fd12b68a2ca6fba04d0df))
- **(data-generation)**: Implement dynamic synthetic data generation - ([42377c0](https://github.com/stanfordnlp/dspy/commit/42377c0c24f94ee51df192ab35ef55e6066f3f31))
- **(data-generation)**: Implement dynamic synthetic data generation - ([1aebd97](https://github.com/stanfordnlp/dspy/commit/1aebd979d3c5345089481045294784604da526b7))
- **(dspy)**: Support more embedding models and return all fields - ([3a9262c](https://github.com/stanfordnlp/dspy/commit/3a9262c2fdb295c3e5f8e7720c16612bde05beb5))
- **(dspy)**: Add documentation for azure ai search retrieval class - ([da8e52a](https://github.com/stanfordnlp/dspy/commit/da8e52ad796445c253552079de4bc19627259169))
- **(dspy)**: Add support for azure ai search - ([f119c6a](https://github.com/stanfordnlp/dspy/commit/f119c6ad070f335b1548692d1a2e976a89a63a39))
- **(dspy)**: Added Metadata for ChromaDB retrieval - ([48663a2](https://github.com/stanfordnlp/dspy/commit/48663a2327b082b17526a8b7c0bd13714b397e98))
- **(dspy)**: Adding missing precommit files - ([3c0eb6b](https://github.com/stanfordnlp/dspy/commit/3c0eb6b4333b5d9faaf78185253cda594109296c))
- **(hotfix)**: Fixing bug with bedrock n parameter and max_tokens parameters - ([4fd70be](https://github.com/stanfordnlp/dspy/commit/4fd70be99cfd5a187d894a2b473d1f25e6d9b8f7))
- **(hotfix)**: Fixing bug with bedrock parameter and parameters - ([bef884e](https://github.com/stanfordnlp/dspy/commit/bef884e24073100ec183d00c3b291aaa244770bb))
- **(new-LM)**: GPT3-turbo integration - ([64d679b](https://github.com/stanfordnlp/dspy/commit/64d679bc02f828139d368e79f19794af2f27e440))
- **(retrieve)**: Add support for faiss retriever, update setup.md, docs - ([7e1212c](https://github.com/stanfordnlp/dspy/commit/7e1212c8f75f5ccf028fb9ea4523e2d838eb0a91))
- **(search)**: Reranker - ([a2e5cb1](https://github.com/stanfordnlp/dspy/commit/a2e5cb19c5f359525febafd9cbc0030d10a88453))
- Expanded settings for stack tracing in logging - ([752f570](https://github.com/stanfordnlp/dspy/commit/752f57029d223c3d07d9b6d7f198d58ba598ba0f))
- Add log file & output type to logging - ([bff4309](https://github.com/stanfordnlp/dspy/commit/bff430952170d874920461d4b59594725be1eb0a))
- Update logging to include all info necessary for the standard library - ([a03446b](https://github.com/stanfordnlp/dspy/commit/a03446b5959aeaa2caaf66e1090adaf14a42de10))
- Added initial logger - ([e9de0b9](https://github.com/stanfordnlp/dspy/commit/e9de0b9552b7d4959722171b4ffd39933e7785d4))
- Add PgVectorRM for postgresql database retrieval - ([ebe0068](https://github.com/stanfordnlp/dspy/commit/ebe00686b7cfa8bacd7d9e10296795fa9062d9ba))
- Add docs to language_models_client for AzureOpenAI - ([cf5dbb0](https://github.com/stanfordnlp/dspy/commit/cf5dbb0fc459004c6165001cd33ea5769349821d))
- Added new AzureOpenAI class - ([712eeb0](https://github.com/stanfordnlp/dspy/commit/712eeb09537f896ff91c7a6542fdf8922623b8cc))
- Add dl.from_json to support native json formats - ([69680e5](https://github.com/stanfordnlp/dspy/commit/69680e5d3d168a98f5ccb049077d5130c3a6dc48))
- Add GitHub Actions workflow to build the package - ([c18acf7](https://github.com/stanfordnlp/dspy/commit/c18acf77ce11a025ce195f20f8bbdd4c36dec542))

### 📚 Documentation

- **(devcontainer)**: Specify interpreter instructions - ([0f9acb0](https://github.com/stanfordnlp/dspy/commit/0f9acb0d679b68102ee4bfb91a50964637637981))
- **(devcontainer)**: Add interpreter instructions at end of dev container build - ([31ff873](https://github.com/stanfordnlp/dspy/commit/31ff87381cf9a0b0aca8affe8687d1382f39a6a0))
- **(dspy)**: Fix typo to run tests - ([4263f7e](https://github.com/stanfordnlp/dspy/commit/4263f7e96f6bde34572ac7feeb3c45c5ea7434ea))

- **(dspy)**: Add toy invocation of model to minimal-example - ([b879095](https://github.com/stanfordnlp/dspy/commit/b87909500ba99b530950f82140ed76baa8eabc25))
- **(dspy)**: Setting up base structure for mkdocs based (versioned) documentation - ([1ddd9a0](https://github.com/stanfordnlp/dspy/commit/1ddd9a0b48e53ccb8cbb8cb5d8eee4a9971587cf))
- **(dspy)**: Setting up base structure for mkdocs based (versioned) documentation - ([a91c17c](https://github.com/stanfordnlp/dspy/commit/a91c17cd25b760b32b6192a55b73f3485e59097e))
- Examples for saving and loading modules after optimizing - ([d5bc784](https://github.com/stanfordnlp/dspy/commit/d5bc784ef8a21c64bc7a22ceaa8490fcc2b45d92))
- Add an explain blog post to other resources - ([6895d39](https://github.com/stanfordnlp/dspy/commit/6895d3995d63c883b42bb80af36a9c16edb5c2e1))
- Missing links in the doc - ([aca741c](https://github.com/stanfordnlp/dspy/commit/aca741c9bcc62e4287bdf1ad38929aa32a092d95))
- Fix the order of the output section - ([c368dbc](https://github.com/stanfordnlp/dspy/commit/c368dbced6948794b591e12bb1b491fc9994eb42))
- Fixes typos - removes extra bracket and adds preposition - ([2615dcd](https://github.com/stanfordnlp/dspy/commit/2615dcd7d7cfb79e262a15f7559aaa8293a8ba5f))
- Adds missing bracket for hyperlink - ([91eda4a](https://github.com/stanfordnlp/dspy/commit/91eda4ac646e17bf172331f8a190293976b7f7bb))

### ⏪ Revert

- **(dependencies)**: Revert all dependency changes - ([ff64905](https://github.com/stanfordnlp/dspy/commit/ff6490528d8f499b04d6b181d8f400c99feba820))

### 💊 Bug Fixes

- **(datasets)**: Relax datasets version constraint - ([a36c528](https://github.com/stanfordnlp/dspy/commit/a36c5287adb8fdc1be48c4295ccba30e75b303e9))
- **(dependencies)**: Recompile lock file - ([316b735](https://github.com/stanfordnlp/dspy/commit/316b735d06f2d9171aba99eaf1b68737e16188e3))
- **(devcontainer)**: Make poetry interpreter VSCode default - ([fa99638](https://github.com/stanfordnlp/dspy/commit/fa996389cd83633b6dea9ff1f743a15d03b446a9))
- **(dsp)**: In HFClientVLLM, merge self.kwargs instead of overwriting it - ([9e65747](https://github.com/stanfordnlp/dspy/commit/9e657477a8f4f9736910b8b80c02fbcfe8362dbb))
- **(dsp)**: Get the model from the kwargs attached by the parent class - ([aee2b8f](https://github.com/stanfordnlp/dspy/commit/aee2b8f242ee838f8ae71eadf31a1713fd24e88e))
- **(dsp)**: Append `kwargs` to the payload for vllm - ([e74c361](https://github.com/stanfordnlp/dspy/commit/e74c36153df674e4113ee8119de38d00ac0adbf2))
- **(dsp)**: Allow optional parameters to be optional - ([40dcd03](https://github.com/stanfordnlp/dspy/commit/40dcd03548ca70376b3267905b8db64ab3c19ce7))
- **(dsp)**: Use the model declared in the constructor - ([9ead2e9](https://github.com/stanfordnlp/dspy/commit/9ead2e94c0afeb2c47c31821186d13e186be70b1))
- **(dsp)**: Attach `kwargs` to HFClientVLLM instance - ([58affaa](https://github.com/stanfordnlp/dspy/commit/58affaae23c85d5247ea8cab99416985e37fbb25))
- **(dspy)**: Add `copy` to AzureOpenAI to propagate `api_(key|version|base)` - ([6b2c09f](https://github.com/stanfordnlp/dspy/commit/6b2c09f7db1cea23a16de79197b3e38cc3bf29f4))
- **(dspy)**: Resolve lint issue - ([eca7e5b](https://github.com/stanfordnlp/dspy/commit/eca7e5bd5e8b28e0eba7a198352eac33bce9a497))
- **(dspy)**: Fix linting in azure ai search retrieval - ([204fb46](https://github.com/stanfordnlp/dspy/commit/204fb46ae563e61c1829e0fe00a02a8eee428415))
- **(dspy)**: Remove debug print statement - ([0dce4f7](https://github.com/stanfordnlp/dspy/commit/0dce4f7daf22457ddff0ca3ec3f5191e78b7265c))
- **(dspy)**: Use DataFrame.applymap in older pandas - ([e53fcbe](https://github.com/stanfordnlp/dspy/commit/e53fcbe8953e5d221f3b53d20049938c4e4d88bb))
- **(pgvectorrm)**: Fixed bug when include similarity = false - ([f14dae8](https://github.com/stanfordnlp/dspy/commit/f14dae8eb081e0af3028df4236b095efe8ecbc4e))
- Missing links - ([0ecefce](https://github.com/stanfordnlp/dspy/commit/0ecefce250311aeed21c85cc6d220c8d9fe064cd))
- Typo in ChromadbRM import - ([44b3924](https://github.com/stanfordnlp/dspy/commit/44b3924046406c722c3f30d53751d66cdfa1d9a8))
- Printing value. - ([410c356](https://github.com/stanfordnlp/dspy/commit/410c356f6500b6a60209f524a9b56e95210286b1))
- Return value in the inspect_history beside printing. - ([d726b84](https://github.com/stanfordnlp/dspy/commit/d726b84155dcd7c2247d38bdfd82683c0bc84265))
- Update requirements for structlog - ([bfdf273](https://github.com/stanfordnlp/dspy/commit/bfdf273926be0e657081a16acd3b3a1bf1224ec3))
- Persist log level to settings struct - ([9ba99f3](https://github.com/stanfordnlp/dspy/commit/9ba99f3c14f0232ef6301155b46e5f0f849c4b6e))
- Setting log level appropriately for logging - ([c60530d](https://github.com/stanfordnlp/dspy/commit/c60530d317141e795783369a0d4b186b082fd1cf))
- More ruff fixes - ([15d50c3](https://github.com/stanfordnlp/dspy/commit/15d50c335da56fc7c86d7507a0f983b4d307e82f))
- Ruff fixes - ([7b7c290](https://github.com/stanfordnlp/dspy/commit/7b7c29087ad6c06f2fc92bf5153857b21887a2ff))
- Removed module specific logging handlers - ([f8a2e6c](https://github.com/stanfordnlp/dspy/commit/f8a2e6c0ed066fe681d92d9d236737ca3b08edf4))
- Remove incorrect dev dependencies in poetry file - ([cc1d881](https://github.com/stanfordnlp/dspy/commit/cc1d88126cc45afab7193da8145997cbf4c14265))
- Use generic embedding function as default in ChromadbRM - ([a81f9a3](https://github.com/stanfordnlp/dspy/commit/a81f9a32a79f96f44c18516e793396f4dd28177a))
- Default collection embedding function attribute in ChromadbRM constructor - ([bafb475](https://github.com/stanfordnlp/dspy/commit/bafb475c7e6a9ca2586a62b35c8e4d6adaf2b570))
- Import of ChromaRM - ([0936884](https://github.com/stanfordnlp/dspy/commit/09368843e12cb546c668dd2a9ba81eabdc38a9aa))
- Printing signature fields in verbose mode for signature_opt - ([c2737f6](https://github.com/stanfordnlp/dspy/commit/c2737f641220f8342fb830266da63b3e6e584969))
- Use proper string composition for sql.SQL object - ([417e6d3](https://github.com/stanfordnlp/dspy/commit/417e6d3f0415ca1d13763012773ee36845909b38))
- Remove extra default field, to keep example consistent - ([a95db2d](https://github.com/stanfordnlp/dspy/commit/a95db2d02ee0b17cd6185bce107b221ec98d5c94))
- Small completion typo and updated model type - ([bf10630](https://github.com/stanfordnlp/dspy/commit/bf10630df714d9c9086f3867c692af36ce1f7e04))
- Updated constructor for AzureOpenAI to accomodate for mandatory arguments - ([69f201c](https://github.com/stanfordnlp/dspy/commit/69f201cca7e349683cc78225e8d010ad0147724d))
- Updated docstrings and log file - ([fb63c1b](https://github.com/stanfordnlp/dspy/commit/fb63c1b20c699504b55b757d4d2a6fa54f439a3c))
- Update parameters for azure v1 - ([4e0d370](https://github.com/stanfordnlp/dspy/commit/4e0d37072dd93f0f963c819c698c6caf434ef3af))
- Update gpt3 lm for openai v1.0 - ([9e3d8a6](https://github.com/stanfordnlp/dspy/commit/9e3d8a6aadf240e798aa0f4c2974535e84a672c0))
- Update imports to allow global dspy.Google - ([e7c5f9f](https://github.com/stanfordnlp/dspy/commit/e7c5f9f4511e8decb47a556b25bd645991985e83))
- Manually iterate kwargs['n'] in anyscale - ([2c11aa0](https://github.com/stanfordnlp/dspy/commit/2c11aa0929080d289677882c5cb84c4d1e2986ed))
- Signature not reachable - ([6407b36](https://github.com/stanfordnlp/dspy/commit/6407b3667792c384d81d2567bdb09a1a84217678))
- Prompt_eval_count occasionally is None - ([c7a6fdd](https://github.com/stanfordnlp/dspy/commit/c7a6fdd05e5516022de9b556f8f7e60193b3198c))
- Teacher discards assertion failure - ([ed5aa11](https://github.com/stanfordnlp/dspy/commit/ed5aa11aee1c515465924c97b899e144df6433b4))

### 🧪 Testing

- **(pgvectorrm)**: Added integration tests - ([3a47bc3](https://github.com/stanfordnlp/dspy/commit/3a47bc3f8d64777a45589e1ba0111b5882210a29))

### 🛠 Continuous Integration

- **(dspy)**: Add main push test run back ([#600](https://github.com/stanfordnlp/dspy/issues/600)) - ([fc664d5](https://github.com/stanfordnlp/dspy/commit/fc664d5e339d2c16b3b537bdbb13d9707e6fd9c4))
- **(dspy)**: Fix tests failing - remove --no-root flag ([#541](https://github.com/stanfordnlp/dspy/issues/541)) - ([2bd6fda](https://github.com/stanfordnlp/dspy/commit/2bd6fdaced86def090cbe4661fdaa07ee8a3bd03))

- **(dspy)**: Add Ruff linting workflow ([#538](https://github.com/stanfordnlp/dspy/issues/538)) - ([a637bf4](https://github.com/stanfordnlp/dspy/commit/a637bf47b527cd7373ac32fcc5db2f662e81b01f))

### 🚜 Refactor

- **(cohere)**: Inherit from LM base class - ([7648c74](https://github.com/stanfordnlp/dspy/commit/7648c7419573d359eb836b67762646367b62c967))
- **(cohere-lm)**: Retry wrapper should ignore optional coheere ([#46](https://github.com/stanfordnlp/dspy/issues/46)) - ([12d7f11](https://github.com/stanfordnlp/dspy/commit/12d7f1106f2f524be161d35865a81e0ea016e929))

### ⚙️ Chore

- **(build_package.yml)**: Add newline at the end of the file for consistency with other files in the repository - ([73f1161](https://github.com/stanfordnlp/dspy/commit/73f1161d41a89c42b61c2e61ee33c464459f7936))
- **(build_package.yml)**: Remove debug step from the workflow - ([e29eac9](https://github.com/stanfordnlp/dspy/commit/e29eac9a12bef6feea361f9f16aca17408563077))
- **(dspy)**: Deprecate dsp AzureCognitiveSearch retrieval class - ([4309e58](https://github.com/stanfordnlp/dspy/commit/4309e585c3559303138f69c8da13e38cd194b78e))
- Removed versions restrictions - ([4ee962d](https://github.com/stanfordnlp/dspy/commit/4ee962dd596a6598e475ecfae1edee4e40e9771d))
- Ruff fixes for logging - ([d0271f8](https://github.com/stanfordnlp/dspy/commit/d0271f87bb5b07fa1b2fc645a583dd62857cc556))
- Remove pinned versions setup.py - ([8ea1e93](https://github.com/stanfordnlp/dspy/commit/8ea1e93dd5393b05172a7466922461c71c4de3f1))
- Bump qdrant extra deps - ([48f5393](https://github.com/stanfordnlp/dspy/commit/48f5393786142f4e36ecf058227da31255d2899b))
- Move torch init to when it is not client in hf module - ([25eeef4](https://github.com/stanfordnlp/dspy/commit/25eeef46a0914afb14d8acf174df49d3a4a0bd66))
- Autoformat - ([5d5c448](https://github.com/stanfordnlp/dspy/commit/5d5c448cbeaf6e40402f05bd4f0c8de4c0a99ddb))
- Remove duplicate comment, print statement. - ([f2f6e47](https://github.com/stanfordnlp/dspy/commit/f2f6e47f00d606b5e1c886f3b6f16bec48b0d97a))
- Refactor OllamaLocal constructor - ([1de4cc4](https://github.com/stanfordnlp/dspy/commit/1de4cc467bf793d4ef6957d0a8abccd48c35c9ad))
<!-- generated by git-cliff -->
