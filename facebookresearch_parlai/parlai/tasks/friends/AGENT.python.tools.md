# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/friends/agents.py

Prompts

```
['build a DialogTeacher subclass to load Friends TV show dialogue data from JSONL files', 'run setup_data to parse conversation utterances and yield training examples with speaker labels', 'refactor _get_message_fields to control speaker inclusion in context and label formatting', 'review the ParlaiParser arguments for character selection, silence token dropout, and start token options', 'create a character-specific teacher subclass like RachelTeacher or ChandlerTeacher by setting the character option', 'build the Friends corpus dataset by downloading and generating train valid test folds', 'generate train valid and test data folds from the Friends corpus utterances JSONL file', 'download the Friends corpus zip file from Cornell Convokit and extract to datapath', 'review the generate_folds function that splits conversations into 80 10 10 train valid test sets', 'refactor the build function to update the version string or change the data split ratios']
```

Usage

```
{'build_DefaultTeacher': 'build a DialogTeacher subclass to load Friends TV show dialogue data from JSONL files', 'run_setup_data': 'run setup_data to parse conversation utterances and yield training examples with speaker labels', 'refactor_get_message_fields': 'refactor _get_message_fields to control speaker inclusion in context and label formatting', 'review_add_cmdline_args': 'review the ParlaiParser arguments for character selection, silence token dropout, and start token options', 'create_character_teacher': 'create a character-specific teacher subclass like RachelTeacher or ChandlerTeacher by setting the character option'}
```

## File: facebookresearch_parlai/parlai/tasks/friends/build.py

Prompts

```
['build a DialogTeacher subclass to load Friends TV show dialogue data from JSONL files', 'run setup_data to parse conversation utterances and yield training examples with speaker labels', 'refactor _get_message_fields to control speaker inclusion in context and label formatting', 'review the ParlaiParser arguments for character selection, silence token dropout, and start token options', 'create a character-specific teacher subclass like RachelTeacher or ChandlerTeacher by setting the character option', 'build the Friends corpus dataset by downloading and generating train valid test folds', 'generate train valid and test data folds from the Friends corpus utterances JSONL file', 'download the Friends corpus zip file from Cornell Convokit and extract to datapath', 'review the generate_folds function that splits conversations into 80 10 10 train valid test sets', 'refactor the build function to update the version string or change the data split ratios']
```

Usage

```
{'build_friends_corpus_data': 'build the Friends corpus dataset by downloading and generating train valid test folds', 'generate_folds_split': 'generate train valid and test data folds from the Friends corpus utterances JSONL file', 'download_friends_corpus': 'download the Friends corpus zip file from Cornell Convokit and extract to datapath', 'review_generate_folds': 'review the generate_folds function that splits conversations into 80 10 10 train valid test sets', 'refactor_build_version': 'refactor the build function to update the version string or change the data split ratios'}
```

