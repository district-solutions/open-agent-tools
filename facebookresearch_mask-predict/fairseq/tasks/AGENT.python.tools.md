# Agent Python Tools

- repo: facebookresearch/mask-predict
- repo_uri: https://github.com/facebookresearch/mask-predict

## File: facebookresearch_mask-predict/fairseq/tasks/fairseq_task.py

Prompts

```
['build a dictionary from a list of text files with configurable threshold and padding factor', 'load a fairseq dictionary from a saved dictionary file on disk', 'setup a fairseq task instance from parsed command-line arguments', 'get an epoch batch iterator that yields batches from a dataset with size constraints', 'run a training step that computes loss and performs backward pass with the optimizer', 'build a fairseq TranslationTask to translate between source and target language pairs', 'load a language pair dataset from indexed files for a given split and data path', 'setup a TranslationTask by loading source and target dictionaries from data paths', 'load a specific dataset split like train valid or test for translation training', 'build a LanguagePairDataset for inference from source tokens and their lengths', 'setup a TranslationSelfTask by calling setup_task with parsed args to load source and target dictionaries', 'add translation self task arguments to an argparse parser including source lang, target lang, and mask range', 'load a train, valid, or test dataset split for the translation self task with dynamic length masking', 'get the max source and target positions allowed by the translation self task', 'review the TranslationSelfTask class and its load_dataset method for self-supervised translation with mask range support']
```

Usage

```
{'build_dictionary_from_files': 'build a dictionary from a list of text files with configurable threshold and padding factor', 'load_dictionary_from_file': 'load a fairseq dictionary from a saved dictionary file on disk', 'setup_task_from_args': 'setup a fairseq task instance from parsed command-line arguments', 'get_batch_iterator': 'get an epoch batch iterator that yields batches from a dataset with size constraints', 'train_step_forward_backward': 'run a training step that computes loss and performs backward pass with the optimizer'}
```

## File: facebookresearch_mask-predict/fairseq/tasks/translation.py

Prompts

```
['build a dictionary from a list of text files with configurable threshold and padding factor', 'load a fairseq dictionary from a saved dictionary file on disk', 'setup a fairseq task instance from parsed command-line arguments', 'get an epoch batch iterator that yields batches from a dataset with size constraints', 'run a training step that computes loss and performs backward pass with the optimizer', 'build a fairseq TranslationTask to translate between source and target language pairs', 'load a language pair dataset from indexed files for a given split and data path', 'setup a TranslationTask by loading source and target dictionaries from data paths', 'load a specific dataset split like train valid or test for translation training', 'build a LanguagePairDataset for inference from source tokens and their lengths', 'setup a TranslationSelfTask by calling setup_task with parsed args to load source and target dictionaries', 'add translation self task arguments to an argparse parser including source lang, target lang, and mask range', 'load a train, valid, or test dataset split for the translation self task with dynamic length masking', 'get the max source and target positions allowed by the translation self task', 'review the TranslationSelfTask class and its load_dataset method for self-supervised translation with mask range support']
```

Usage

```
{'build_translation_task': 'build a fairseq TranslationTask to translate between source and target language pairs', 'load_langpair_dataset': 'load a language pair dataset from indexed files for a given split and data path', 'setup_translation_task': 'setup a TranslationTask by loading source and target dictionaries from data paths', 'load_dataset_split': 'load a specific dataset split like train valid or test for translation training', 'build_inference_dataset': 'build a LanguagePairDataset for inference from source tokens and their lengths'}
```

## File: facebookresearch_mask-predict/fairseq/tasks/translation_self.py

Prompts

```
['build a dictionary from a list of text files with configurable threshold and padding factor', 'load a fairseq dictionary from a saved dictionary file on disk', 'setup a fairseq task instance from parsed command-line arguments', 'get an epoch batch iterator that yields batches from a dataset with size constraints', 'run a training step that computes loss and performs backward pass with the optimizer', 'build a fairseq TranslationTask to translate between source and target language pairs', 'load a language pair dataset from indexed files for a given split and data path', 'setup a TranslationTask by loading source and target dictionaries from data paths', 'load a specific dataset split like train valid or test for translation training', 'build a LanguagePairDataset for inference from source tokens and their lengths', 'setup a TranslationSelfTask by calling setup_task with parsed args to load source and target dictionaries', 'add translation self task arguments to an argparse parser including source lang, target lang, and mask range', 'load a train, valid, or test dataset split for the translation self task with dynamic length masking', 'get the max source and target positions allowed by the translation self task', 'review the TranslationSelfTask class and its load_dataset method for self-supervised translation with mask range support']
```

Usage

```
{'setup_translation_self_task': 'setup a TranslationSelfTask by calling setup_task with parsed args to load source and target dictionaries', 'add_translation_self_args': 'add translation self task arguments to an argparse parser including source lang, target lang, and mask range', 'load_translation_dataset': 'load a train, valid, or test dataset split for the translation self task with dynamic length masking', 'get_max_positions': 'get the max source and target positions allowed by the translation self task', 'review_TranslationSelfTask': 'review the TranslationSelfTask class and its load_dataset method for self-supervised translation with mask range support'}
```

