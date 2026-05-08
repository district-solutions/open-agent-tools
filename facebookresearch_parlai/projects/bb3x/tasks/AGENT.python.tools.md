# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/bb3x/tasks/agents.py

Prompts

```
['create a BB3DataBotTeacher to load bot-labeled dialogue examples from the BB3 dataset', 'create a BB3DataHumanTeacher to load human-labeled dialogue examples from the BB3 dataset', 'create a FilterOutAdversarialHumansBotTeacher to load bot examples excluding adversarial human conversations', 'create a BB3DataCrowdworkersBotTeacher to load bot examples with crowdworker annotations', 'review the BaseBB3DataTeacher class and its chunk loading, safety filtering, and example generation methods', 'run the build function to download and set up the bb3_demo dataset in the specified datapath', 'review the build function that checks version, downloads resources, and marks data as built', 'refactor the build function to support a newer version of the bb3_demo dataset', 'summarize the build workflow that downloads bb3_demo_chunks.tgz and marks the data directory as done', 'test the build function to verify it downloads bb3_demo data and handles version upgrades']
```

Usage

```
{'create_BB3DataBotTeacher': 'create a BB3DataBotTeacher to load bot-labeled dialogue examples from the BB3 dataset', 'create_BB3DataHumanTeacher': 'create a BB3DataHumanTeacher to load human-labeled dialogue examples from the BB3 dataset', 'create_FilterOutAdversarialHumansBotTeacher': 'create a FilterOutAdversarialHumansBotTeacher to load bot examples excluding adversarial human conversations', 'create_BB3DataCrowdworkersBotTeacher': 'create a BB3DataCrowdworkersBotTeacher to load bot examples with crowdworker annotations', 'review_BaseBB3DataTeacher': 'review the BaseBB3DataTeacher class and its chunk loading, safety filtering, and example generation methods'}
```

## File: facebookresearch_parlai/projects/bb3x/tasks/build.py

Prompts

```
['create a BB3DataBotTeacher to load bot-labeled dialogue examples from the BB3 dataset', 'create a BB3DataHumanTeacher to load human-labeled dialogue examples from the BB3 dataset', 'create a FilterOutAdversarialHumansBotTeacher to load bot examples excluding adversarial human conversations', 'create a BB3DataCrowdworkersBotTeacher to load bot examples with crowdworker annotations', 'review the BaseBB3DataTeacher class and its chunk loading, safety filtering, and example generation methods', 'run the build function to download and set up the bb3_demo dataset in the specified datapath', 'review the build function that checks version, downloads resources, and marks data as built', 'refactor the build function to support a newer version of the bb3_demo dataset', 'summarize the build workflow that downloads bb3_demo_chunks.tgz and marks the data directory as done', 'test the build function to verify it downloads bb3_demo data and handles version upgrades']
```

Usage

```
{'build_bb3_demo_data': 'run the build function to download and set up the bb3_demo dataset in the specified datapath', 'review_build_function': 'review the build function that checks version, downloads resources, and marks data as built', 'refactor_build_versioning': 'refactor the build function to support a newer version of the bb3_demo dataset', 'summarize_build_workflow': 'summarize the build workflow that downloads bb3_demo_chunks.tgz and marks the data directory as done', 'test_build_function': 'test the build function to verify it downloads bb3_demo data and handles version upgrades'}
```

