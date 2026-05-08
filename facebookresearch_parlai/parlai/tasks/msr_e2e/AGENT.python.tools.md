# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/msr_e2e/agents.py

Prompts

```
['build a MsrE2EParser to load and parse MSR-E2E dialogue data across movie, restaurant, and taxi domains', 'parse a dialogue act string from MSR-E2E data into a structured dictionary of key-value slot pairs', 'setup structured TOD episodes from raw MSR-E2E dialogue utterances with API calls and responses', 'run the SystemTeacher to train a dialogue agent on the MSR-E2E task using ParlAI', 'run the UserSimulatorTeacher to simulate user dialogue turns for the MSR-E2E task', 'call build(opt) to download the MSR E2E dialog dataset into the datapath directory', 'review the build function that downloads movie, restaurant, and taxi TSV files for the MSR E2E task', 'summarize the RESOURCES list containing three DownloadableFile entries for movie, restaurant, and taxi data', 'refactor the build function to support a newer version string for the MSR E2E dataset', 'test the build function to verify it downloads and marks the MSR E2E dataset as complete']
```

Usage

```
{'build_msr_e2e_parser': 'build a MsrE2EParser to load and parse MSR-E2E dialogue data across movie, restaurant, and taxi domains', 'parse_dialogue_act': 'parse a dialogue act string from MSR-E2E data into a structured dictionary of key-value slot pairs', 'setup_episodes': 'setup structured TOD episodes from raw MSR-E2E dialogue utterances with API calls and responses', 'run_system_teacher': 'run the SystemTeacher to train a dialogue agent on the MSR-E2E task using ParlAI', 'run_user_simulator': 'run the UserSimulatorTeacher to simulate user dialogue turns for the MSR-E2E task'}
```

## File: facebookresearch_parlai/parlai/tasks/msr_e2e/build.py

Prompts

```
['build a MsrE2EParser to load and parse MSR-E2E dialogue data across movie, restaurant, and taxi domains', 'parse a dialogue act string from MSR-E2E data into a structured dictionary of key-value slot pairs', 'setup structured TOD episodes from raw MSR-E2E dialogue utterances with API calls and responses', 'run the SystemTeacher to train a dialogue agent on the MSR-E2E task using ParlAI', 'run the UserSimulatorTeacher to simulate user dialogue turns for the MSR-E2E task', 'call build(opt) to download the MSR E2E dialog dataset into the datapath directory', 'review the build function that downloads movie, restaurant, and taxi TSV files for the MSR E2E task', 'summarize the RESOURCES list containing three DownloadableFile entries for movie, restaurant, and taxi data', 'refactor the build function to support a newer version string for the MSR E2E dataset', 'test the build function to verify it downloads and marks the MSR E2E dataset as complete']
```

Usage

```
{'build_msr_e2e_dataset': 'call build(opt) to download the MSR E2E dialog dataset into the datapath directory', 'review_build_function': 'review the build function that downloads movie, restaurant, and taxi TSV files for the MSR E2E task', 'summarize_resources_list': 'summarize the RESOURCES list containing three DownloadableFile entries for movie, restaurant, and taxi data', 'refactor_build_versioning': 'refactor the build function to support a newer version string for the MSR E2E dataset', 'test_build_download': 'test the build function to verify it downloads and marks the MSR E2E dataset as complete'}
```

