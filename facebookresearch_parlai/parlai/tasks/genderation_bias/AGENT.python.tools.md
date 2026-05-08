# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/genderation_bias/agents.py

Prompts

```
['run the ControllableTaskTeacher to flatten multi-turn dialogues into single example episodes with classification tokens', 'build and load lists of explicitly gendered male and female words from the genderation_bias data files', 'setup flattened and classified data by iterating through the original task teacher and saving episodes', 'load pre-built flattened controllable gen data from the most recently saved JSON cache file', 'get a flattened example by episode index with optional fixed control string appended to the text', 'call build(datapath) to download male and female word list files for the genderation_bias task', 'download the male word file from the UCL NLP GN GloVe repository using RESOURCES', 'download the female word file from the UCL NLP GN GloVe repository using RESOURCES', 'check if the genderation_bias data directory is already built using build_data.built(dpath, version)', 'remove an older version of the genderation_bias data directory using build_data.remove_dir(dpath)', 'format text by lowercasing and adding spaces before punctuation marks', 'get a gender control token from text using male and female word lists', 'flatten dialogue episodes into new examples with gender control tokens added', 'load the original ParlAI task module from an opt configuration dict', 'review the format_text function that lowercases text and spaces punctuation for tokenization']
```

Usage

```
{'run_controllable_task_teacher': 'run the ControllableTaskTeacher to flatten multi-turn dialogues into single example episodes with classification tokens', 'build_wordlists': 'build and load lists of explicitly gendered male and female words from the genderation_bias data files', 'setup_data': 'setup flattened and classified data by iterating through the original task teacher and saving episodes', 'load_data': 'load pre-built flattened controllable gen data from the most recently saved JSON cache file', 'get_example': 'get a flattened example by episode index with optional fixed control string appended to the text'}
```

## File: facebookresearch_parlai/parlai/tasks/genderation_bias/build.py

Prompts

```
['run the ControllableTaskTeacher to flatten multi-turn dialogues into single example episodes with classification tokens', 'build and load lists of explicitly gendered male and female words from the genderation_bias data files', 'setup flattened and classified data by iterating through the original task teacher and saving episodes', 'load pre-built flattened controllable gen data from the most recently saved JSON cache file', 'get a flattened example by episode index with optional fixed control string appended to the text', 'call build(datapath) to download male and female word list files for the genderation_bias task', 'download the male word file from the UCL NLP GN GloVe repository using RESOURCES', 'download the female word file from the UCL NLP GN GloVe repository using RESOURCES', 'check if the genderation_bias data directory is already built using build_data.built(dpath, version)', 'remove an older version of the genderation_bias data directory using build_data.remove_dir(dpath)', 'format text by lowercasing and adding spaces before punctuation marks', 'get a gender control token from text using male and female word lists', 'flatten dialogue episodes into new examples with gender control tokens added', 'load the original ParlAI task module from an opt configuration dict', 'review the format_text function that lowercases text and spaces punctuation for tokenization']
```

Usage

```
{'build_genderation_bias_data': 'call build(datapath) to download male and female word list files for the genderation_bias task', 'download_male_word_file': 'download the male word file from the UCL NLP GN GloVe repository using RESOURCES', 'download_female_word_file': 'download the female word file from the UCL NLP GN GloVe repository using RESOURCES', 'check_data_built': 'check if the genderation_bias data directory is already built using build_data.built(dpath, version)', 'remove_outdated_data': 'remove an older version of the genderation_bias data directory using build_data.remove_dir(dpath)'}
```

## File: facebookresearch_parlai/parlai/tasks/genderation_bias/utils.py

Prompts

```
['run the ControllableTaskTeacher to flatten multi-turn dialogues into single example episodes with classification tokens', 'build and load lists of explicitly gendered male and female words from the genderation_bias data files', 'setup flattened and classified data by iterating through the original task teacher and saving episodes', 'load pre-built flattened controllable gen data from the most recently saved JSON cache file', 'get a flattened example by episode index with optional fixed control string appended to the text', 'call build(datapath) to download male and female word list files for the genderation_bias task', 'download the male word file from the UCL NLP GN GloVe repository using RESOURCES', 'download the female word file from the UCL NLP GN GloVe repository using RESOURCES', 'check if the genderation_bias data directory is already built using build_data.built(dpath, version)', 'remove an older version of the genderation_bias data directory using build_data.remove_dir(dpath)', 'format text by lowercasing and adding spaces before punctuation marks', 'get a gender control token from text using male and female word lists', 'flatten dialogue episodes into new examples with gender control tokens added', 'load the original ParlAI task module from an opt configuration dict', 'review the format_text function that lowercases text and spaces punctuation for tokenization']
```

Usage

```
{'format_text_lowercase_punctuate': 'format text by lowercasing and adding spaces before punctuation marks', 'get_word_list_token_gender': 'get a gender control token from text using male and female word lists', 'flatten_and_classify_episode': 'flatten dialogue episodes into new examples with gender control tokens added', 'get_original_task_module_load': 'load the original ParlAI task module from an opt configuration dict', 'review_format_text': 'review the format_text function that lowercases text and spaces punctuation for tokenization'}
```

