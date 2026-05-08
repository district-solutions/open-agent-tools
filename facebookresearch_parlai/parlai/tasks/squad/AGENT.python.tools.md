# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/squad/agents.py

Prompts

```
['build a SQuAD IndexTeacher that loads JSON data and provides answer_start indices for each example', 'create a SQuAD DefaultTeacher that inherits DialogTeacher and yields context plus question examples', 'run a SQuAD SentenceTeacher that returns sentences containing the true answer as labels', 'review the SquadQATeacher wrapper that extracts only the passage and ignores the question', 'test the get_sentence_tokenizer function that loads and returns the NLTK English sentence tokenizer', 'build the SQuAD dataset by downloading train and dev JSON files into the datapath directory', 'build the SQuAD fulldoc dataset by downloading and extracting squad_fulldocs.tgz into the datapath', 'review the build function that downloads SQuAD train and dev data and marks the directory as done', 'review the RESOURCES list containing DownloadableFile entries for SQuAD train, dev, and fulldocs datasets', 'refactor the build function to support versioned SQuAD dataset downloads with a version string']
```

Usage

```
{'build_IndexTeacher': 'build a SQuAD IndexTeacher that loads JSON data and provides answer_start indices for each example', 'create_DefaultTeacher': 'create a SQuAD DefaultTeacher that inherits DialogTeacher and yields context plus question examples', 'run_SentenceTeacher': 'run a SQuAD SentenceTeacher that returns sentences containing the true answer as labels', 'review_SquadQATeacher': 'review the SquadQATeacher wrapper that extracts only the passage and ignores the question', 'test_get_sentence_tokenizer': 'test the get_sentence_tokenizer function that loads and returns the NLTK English sentence tokenizer'}
```

## File: facebookresearch_parlai/parlai/tasks/squad/build.py

Prompts

```
['build a SQuAD IndexTeacher that loads JSON data and provides answer_start indices for each example', 'create a SQuAD DefaultTeacher that inherits DialogTeacher and yields context plus question examples', 'run a SQuAD SentenceTeacher that returns sentences containing the true answer as labels', 'review the SquadQATeacher wrapper that extracts only the passage and ignores the question', 'test the get_sentence_tokenizer function that loads and returns the NLTK English sentence tokenizer', 'build the SQuAD dataset by downloading train and dev JSON files into the datapath directory', 'build the SQuAD fulldoc dataset by downloading and extracting squad_fulldocs.tgz into the datapath', 'review the build function that downloads SQuAD train and dev data and marks the directory as done', 'review the RESOURCES list containing DownloadableFile entries for SQuAD train, dev, and fulldocs datasets', 'refactor the build function to support versioned SQuAD dataset downloads with a version string']
```

Usage

```
{'build_squad_data': 'build the SQuAD dataset by downloading train and dev JSON files into the datapath directory', 'build_squad_fulldoc_data': 'build the SQuAD fulldoc dataset by downloading and extracting squad_fulldocs.tgz into the datapath', 'review_build_function': 'review the build function that downloads SQuAD train and dev data and marks the directory as done', 'review_resources_list': 'review the RESOURCES list containing DownloadableFile entries for SQuAD train, dev, and fulldocs datasets', 'refactor_build_for_versioning': 'refactor the build function to support versioned SQuAD dataset downloads with a version string'}
```

