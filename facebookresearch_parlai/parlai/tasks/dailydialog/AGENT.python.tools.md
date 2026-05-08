# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/dailydialog/agents.py

Prompts

```
['build a Convai2Teacher to load and serve DailyDialog dataset examples for dialogue training', 'create a NoStartTeacher to serve DailyDialog examples without silence start entries', 'get a dialogue example with emotion, act_type, and topic metadata from the teacher', 'setup DailyDialog JSON dialogue data for a specific fold like train or valid', 'share DailyDialog teacher data across parallel workers using the share method', 'run the build function to download and prepare the dailydialog dataset into the datapath directory', 'review the build function to understand how it downloads and marks the dailydialog dataset as built', 'summarize the build function logic for downloading dailydialog data and checking for existing versions', 'refactor the build function to support a new version string for the dailydialog dataset', 'test the build function to verify it correctly downloads dailydialog data and marks it as done', 'run cleanup_text to normalize unicode characters and fix broken sentence tokenization in dialogue text', 'test cleanup_text with unicode quotes and broken sentence boundaries to verify normalization', 'review cleanup_text SWITCH_LIST to add or remove unicode character replacements for dialogue preprocessing', 'refactor cleanup_text to accept a configurable list of unicode character replacements instead of a hardcoded list', 'summarize the parse.py script that converts DailyDialog raw text files into ParlAI JSON format with emotion and act labels']
```

Usage

```
{'build_dailydialog_teacher': 'build a Convai2Teacher to load and serve DailyDialog dataset examples for dialogue training', 'create_nostart_teacher': 'create a NoStartTeacher to serve DailyDialog examples without silence start entries', 'get_dialogue_example': 'get a dialogue example with emotion, act_type, and topic metadata from the teacher', 'setup_dailydialog_data': 'setup DailyDialog JSON dialogue data for a specific fold like train or valid', 'share_teacher_data': 'share DailyDialog teacher data across parallel workers using the share method'}
```

## File: facebookresearch_parlai/parlai/tasks/dailydialog/build.py

Prompts

```
['build a Convai2Teacher to load and serve DailyDialog dataset examples for dialogue training', 'create a NoStartTeacher to serve DailyDialog examples without silence start entries', 'get a dialogue example with emotion, act_type, and topic metadata from the teacher', 'setup DailyDialog JSON dialogue data for a specific fold like train or valid', 'share DailyDialog teacher data across parallel workers using the share method', 'run the build function to download and prepare the dailydialog dataset into the datapath directory', 'review the build function to understand how it downloads and marks the dailydialog dataset as built', 'summarize the build function logic for downloading dailydialog data and checking for existing versions', 'refactor the build function to support a new version string for the dailydialog dataset', 'test the build function to verify it correctly downloads dailydialog data and marks it as done', 'run cleanup_text to normalize unicode characters and fix broken sentence tokenization in dialogue text', 'test cleanup_text with unicode quotes and broken sentence boundaries to verify normalization', 'review cleanup_text SWITCH_LIST to add or remove unicode character replacements for dialogue preprocessing', 'refactor cleanup_text to accept a configurable list of unicode character replacements instead of a hardcoded list', 'summarize the parse.py script that converts DailyDialog raw text files into ParlAI JSON format with emotion and act labels']
```

Usage

```
{'build_dailydialog_data': 'run the build function to download and prepare the dailydialog dataset into the datapath directory', 'review_build_function': 'review the build function to understand how it downloads and marks the dailydialog dataset as built', 'summarize_build_function': 'summarize the build function logic for downloading dailydialog data and checking for existing versions', 'refactor_build_function': 'refactor the build function to support a new version string for the dailydialog dataset', 'test_build_function': 'test the build function to verify it correctly downloads dailydialog data and marks it as done'}
```

## File: facebookresearch_parlai/parlai/tasks/dailydialog/parse.py

Prompts

```
['build a Convai2Teacher to load and serve DailyDialog dataset examples for dialogue training', 'create a NoStartTeacher to serve DailyDialog examples without silence start entries', 'get a dialogue example with emotion, act_type, and topic metadata from the teacher', 'setup DailyDialog JSON dialogue data for a specific fold like train or valid', 'share DailyDialog teacher data across parallel workers using the share method', 'run the build function to download and prepare the dailydialog dataset into the datapath directory', 'review the build function to understand how it downloads and marks the dailydialog dataset as built', 'summarize the build function logic for downloading dailydialog data and checking for existing versions', 'refactor the build function to support a new version string for the dailydialog dataset', 'test the build function to verify it correctly downloads dailydialog data and marks it as done', 'run cleanup_text to normalize unicode characters and fix broken sentence tokenization in dialogue text', 'test cleanup_text with unicode quotes and broken sentence boundaries to verify normalization', 'review cleanup_text SWITCH_LIST to add or remove unicode character replacements for dialogue preprocessing', 'refactor cleanup_text to accept a configurable list of unicode character replacements instead of a hardcoded list', 'summarize the parse.py script that converts DailyDialog raw text files into ParlAI JSON format with emotion and act labels']
```

Usage

```
{'run_cleanup_text': 'run cleanup_text to normalize unicode characters and fix broken sentence tokenization in dialogue text', 'test_cleanup_text': 'test cleanup_text with unicode quotes and broken sentence boundaries to verify normalization', 'review_cleanup_text': 'review cleanup_text SWITCH_LIST to add or remove unicode character replacements for dialogue preprocessing', 'refactor_cleanup_text': 'refactor cleanup_text to accept a configurable list of unicode character replacements instead of a hardcoded list', 'summarize_parse_script': 'summarize the parse.py script that converts DailyDialog raw text files into ParlAI JSON format with emotion and act labels'}
```

