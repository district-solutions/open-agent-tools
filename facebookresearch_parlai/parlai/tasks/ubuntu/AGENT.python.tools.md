# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/ubuntu/agents.py

Prompts

```
['build a Parlai UbuntuTeacher to load single-turn Ubuntu dialog data from CSV with candidate responses', 'create a MultiturnTeacher to load multi-turn Ubuntu dialog conversations and alternate speaker roles', 'run the UbuntuTeacher setup_data method to parse CSV dialog fields and yield context-response pairs', 'run the MultiturnTeacher get method to retrieve a specific turn from a multi-turn dialog episode', 'run the MultiturnTeacher share method to share dialog data across Hogwild training workers', 'run the build function to download and prepare the Ubuntu dataset for ParlAI', 'review the build function that downloads Ubuntu dialogue data and marks it as built', 'summarize the build function logic for downloading and caching the Ubuntu dataset', 'test the build function with a custom datapath option dictionary', 'refactor the build function to support versioned Ubuntu dataset downloads']
```

Usage

```
{'build_ubuntu_teacher': 'build a Parlai UbuntuTeacher to load single-turn Ubuntu dialog data from CSV with candidate responses', 'create_multiturn_teacher': 'create a MultiturnTeacher to load multi-turn Ubuntu dialog conversations and alternate speaker roles', 'setup_data_ubuntu': 'run the UbuntuTeacher setup_data method to parse CSV dialog fields and yield context-response pairs', 'get_multiturn_entry': 'run the MultiturnTeacher get method to retrieve a specific turn from a multi-turn dialog episode', 'share_multiturn_data': 'run the MultiturnTeacher share method to share dialog data across Hogwild training workers'}
```

## File: facebookresearch_parlai/parlai/tasks/ubuntu/build.py

Prompts

```
['build a Parlai UbuntuTeacher to load single-turn Ubuntu dialog data from CSV with candidate responses', 'create a MultiturnTeacher to load multi-turn Ubuntu dialog conversations and alternate speaker roles', 'run the UbuntuTeacher setup_data method to parse CSV dialog fields and yield context-response pairs', 'run the MultiturnTeacher get method to retrieve a specific turn from a multi-turn dialog episode', 'run the MultiturnTeacher share method to share dialog data across Hogwild training workers', 'run the build function to download and prepare the Ubuntu dataset for ParlAI', 'review the build function that downloads Ubuntu dialogue data and marks it as built', 'summarize the build function logic for downloading and caching the Ubuntu dataset', 'test the build function with a custom datapath option dictionary', 'refactor the build function to support versioned Ubuntu dataset downloads']
```

Usage

```
{'run_build_ubuntu_data': 'run the build function to download and prepare the Ubuntu dataset for ParlAI', 'review_build_function': 'review the build function that downloads Ubuntu dialogue data and marks it as built', 'summarize_build_function': 'summarize the build function logic for downloading and caching the Ubuntu dataset', 'test_build_function': 'test the build function with a custom datapath option dictionary', 'refactor_build_function': 'refactor the build function to support versioned Ubuntu dataset downloads'}
```

