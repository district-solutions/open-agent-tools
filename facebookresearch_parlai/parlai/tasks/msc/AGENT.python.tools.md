# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/msc/agents.py

Prompts

```
['run the SessionBasePersonaSummaryTeacher to summarize persona lines from MSC dialogue data for a given session', 'run the SessionBaseMscTeacher to generate text in multi-session chat with configurable previous persona context types', 'run the ContextGenerator to extract persona strings and dialogue context for bot prompt generation in human evaluation', 'run the PersonaSummaryTeacher multi-task teacher across sessions 1-4 for persona summarization training and evaluation', 'run the MscTeacher multi-task teacher across sessions 1-5 for multi-session chat dialogue generation', 'build the MSC dataset by downloading and extracting resources to the data directory', 'get the MSC dataset directory path from the ParlAI options dictionary', 'review the build function to understand how it handles version checks and resource downloads', 'summarize the MSC dataset RESOURCES list and its DownloadableFile entries', 'test the get_msc_dir_path function with a sample options dictionary containing datapath', 'build a python module using LongTermMemoryMutator to replace episode labels with personal_knowledge', 'create a mutator that flattens dialogue episodes and replaces labels with personal_knowledge', 'test the LongTermMemoryMutator many_episode_mutation method with a list of dialogue messages', 'refactor the LongTermMemoryMutator to customize the label replacement string or history format', 'review the LongTermMemoryMutator class and its many_episode_mutation method for dialogue history handling']
```

Usage

```
{'run_persona_summary_teacher': 'run the SessionBasePersonaSummaryTeacher to summarize persona lines from MSC dialogue data for a given session', 'run_msc_dialogue_teacher': 'run the SessionBaseMscTeacher to generate text in multi-session chat with configurable previous persona context types', 'run_context_generator': 'run the ContextGenerator to extract persona strings and dialogue context for bot prompt generation in human evaluation', 'run_multitask_summary_teacher': 'run the PersonaSummaryTeacher multi-task teacher across sessions 1-4 for persona summarization training and evaluation', 'run_msc_multitask_teacher': 'run the MscTeacher multi-task teacher across sessions 1-5 for multi-session chat dialogue generation'}
```

## File: facebookresearch_parlai/parlai/tasks/msc/build.py

Prompts

```
['run the SessionBasePersonaSummaryTeacher to summarize persona lines from MSC dialogue data for a given session', 'run the SessionBaseMscTeacher to generate text in multi-session chat with configurable previous persona context types', 'run the ContextGenerator to extract persona strings and dialogue context for bot prompt generation in human evaluation', 'run the PersonaSummaryTeacher multi-task teacher across sessions 1-4 for persona summarization training and evaluation', 'run the MscTeacher multi-task teacher across sessions 1-5 for multi-session chat dialogue generation', 'build the MSC dataset by downloading and extracting resources to the data directory', 'get the MSC dataset directory path from the ParlAI options dictionary', 'review the build function to understand how it handles version checks and resource downloads', 'summarize the MSC dataset RESOURCES list and its DownloadableFile entries', 'test the get_msc_dir_path function with a sample options dictionary containing datapath', 'build a python module using LongTermMemoryMutator to replace episode labels with personal_knowledge', 'create a mutator that flattens dialogue episodes and replaces labels with personal_knowledge', 'test the LongTermMemoryMutator many_episode_mutation method with a list of dialogue messages', 'refactor the LongTermMemoryMutator to customize the label replacement string or history format', 'review the LongTermMemoryMutator class and its many_episode_mutation method for dialogue history handling']
```

Usage

```
{'build_msc_dataset': 'build the MSC dataset by downloading and extracting resources to the data directory', 'get_msc_dir_path': 'get the MSC dataset directory path from the ParlAI options dictionary', 'review_build_function': 'review the build function to understand how it handles version checks and resource downloads', 'summarize_msc_resources': 'summarize the MSC dataset RESOURCES list and its DownloadableFile entries', 'test_get_msc_dir_path': 'test the get_msc_dir_path function with a sample options dictionary containing datapath'}
```

## File: facebookresearch_parlai/parlai/tasks/msc/mutators.py

Prompts

```
['run the SessionBasePersonaSummaryTeacher to summarize persona lines from MSC dialogue data for a given session', 'run the SessionBaseMscTeacher to generate text in multi-session chat with configurable previous persona context types', 'run the ContextGenerator to extract persona strings and dialogue context for bot prompt generation in human evaluation', 'run the PersonaSummaryTeacher multi-task teacher across sessions 1-4 for persona summarization training and evaluation', 'run the MscTeacher multi-task teacher across sessions 1-5 for multi-session chat dialogue generation', 'build the MSC dataset by downloading and extracting resources to the data directory', 'get the MSC dataset directory path from the ParlAI options dictionary', 'review the build function to understand how it handles version checks and resource downloads', 'summarize the MSC dataset RESOURCES list and its DownloadableFile entries', 'test the get_msc_dir_path function with a sample options dictionary containing datapath', 'build a python module using LongTermMemoryMutator to replace episode labels with personal_knowledge', 'create a mutator that flattens dialogue episodes and replaces labels with personal_knowledge', 'test the LongTermMemoryMutator many_episode_mutation method with a list of dialogue messages', 'refactor the LongTermMemoryMutator to customize the label replacement string or history format', 'review the LongTermMemoryMutator class and its many_episode_mutation method for dialogue history handling']
```

Usage

```
{'build_ltm_mutator': 'build a python module using LongTermMemoryMutator to replace episode labels with personal_knowledge', 'create_mutator_for_dialogue': 'create a mutator that flattens dialogue episodes and replaces labels with personal_knowledge', 'test_many_episode_mutation': 'test the LongTermMemoryMutator many_episode_mutation method with a list of dialogue messages', 'refactor_ltm_mutator': 'refactor the LongTermMemoryMutator to customize the label replacement string or history format', 'review_longtermmemorymutator': 'review the LongTermMemoryMutator class and its many_episode_mutation method for dialogue history handling'}
```

