# Agent Python Tools

- repo: facebookresearch/perfect
- repo_uri: https://github.com/facebookresearch/perfect

## File: facebookresearch_perfect/fewshot/data/preprocessing.py

Prompts

```
['create an MLMProcessor instance with a tokenizer, verbalizers, max sequence length, and processor for masked language modeling data preprocessing', 'run the MLMProcessor forward method on an example to get tokenized input IDs, attention masks, and candidate token IDs', 'test the MLMProcessor truncate method to verify two text sequences are shortened to fit the maximum sequence length', 'review the MLMProcessor prepare_classification_inputs method to understand how classification inputs are tokenized, padded, and returned with labels', 'refactor the MLMProcessor tokenize method to customize how text entries are encoded into token ID tuples with shortenable flags', 'use AutoProcessor.get to create a task-specific processor like MR or BoolQ with a tokenizer and pattern settings', 'call get_sentence_parts on a processor to convert an example into tokenized sentence parts with mask tokens', 'call get_prompt_parts on a processor to build a PET-style prompt with verbalizer masks for a given example', 'call get_verbalizers on a processor to retrieve the list of verbalizer words mapped to label classes', 'call get_tokenized_verbalizers on a processor to get token IDs for each verbalizer word using the tokenizer', 'use AutoTask.get to instantiate a task class by name with seed and sample parameters', 'call load_datasets on a task instance to load GLUE or SuperGLUE datasets from HuggingFace', 'call sample_datasets to split training data into balanced train and validation sets by label', 'call get_datasets on a task instance to load, sample, and post-process datasets in one step', 'subclass AbstractTask to define a new few-shot NLP task with custom dataset loading logic', 'tokenize a verbalization word using a HuggingFace tokenizer and return token ids', 'remove trailing punctuation characters from a word string', 'convert a word string to lowercase', 'create a Text dataclass with shortenable bool tensor and text string fields', 'review the Text dataclass inheriting from transformers ModelOutput for dataset processing']
```

Usage

```
{'create_MLMProcessor': 'create an MLMProcessor instance with a tokenizer, verbalizers, max sequence length, and processor for masked language modeling data preprocessing', 'run_MLMProcessor_forward': 'run the MLMProcessor forward method on an example to get tokenized input IDs, attention masks, and candidate token IDs', 'test_MLMProcessor_truncate': 'test the MLMProcessor truncate method to verify two text sequences are shortened to fit the maximum sequence length', 'review_MLMProcessor_prepare_classification_inputs': 'review the MLMProcessor prepare_classification_inputs method to understand how classification inputs are tokenized, padded, and returned with labels', 'refactor_MLMProcessor_tokenize': 'refactor the MLMProcessor tokenize method to customize how text entries are encoded into token ID tuples with shortenable flags'}
```

## File: facebookresearch_perfect/fewshot/data/processors.py

Prompts

```
['create an MLMProcessor instance with a tokenizer, verbalizers, max sequence length, and processor for masked language modeling data preprocessing', 'run the MLMProcessor forward method on an example to get tokenized input IDs, attention masks, and candidate token IDs', 'test the MLMProcessor truncate method to verify two text sequences are shortened to fit the maximum sequence length', 'review the MLMProcessor prepare_classification_inputs method to understand how classification inputs are tokenized, padded, and returned with labels', 'refactor the MLMProcessor tokenize method to customize how text entries are encoded into token ID tuples with shortenable flags', 'use AutoProcessor.get to create a task-specific processor like MR or BoolQ with a tokenizer and pattern settings', 'call get_sentence_parts on a processor to convert an example into tokenized sentence parts with mask tokens', 'call get_prompt_parts on a processor to build a PET-style prompt with verbalizer masks for a given example', 'call get_verbalizers on a processor to retrieve the list of verbalizer words mapped to label classes', 'call get_tokenized_verbalizers on a processor to get token IDs for each verbalizer word using the tokenizer', 'use AutoTask.get to instantiate a task class by name with seed and sample parameters', 'call load_datasets on a task instance to load GLUE or SuperGLUE datasets from HuggingFace', 'call sample_datasets to split training data into balanced train and validation sets by label', 'call get_datasets on a task instance to load, sample, and post-process datasets in one step', 'subclass AbstractTask to define a new few-shot NLP task with custom dataset loading logic', 'tokenize a verbalization word using a HuggingFace tokenizer and return token ids', 'remove trailing punctuation characters from a word string', 'convert a word string to lowercase', 'create a Text dataclass with shortenable bool tensor and text string fields', 'review the Text dataclass inheriting from transformers ModelOutput for dataset processing']
```

Usage

```
{'create_processor_for_task': 'use AutoProcessor.get to create a task-specific processor like MR or BoolQ with a tokenizer and pattern settings', 'get_sentence_parts_with_masks': 'call get_sentence_parts on a processor to convert an example into tokenized sentence parts with mask tokens', 'get_prompt_parts_for_PET': 'call get_prompt_parts on a processor to build a PET-style prompt with verbalizer masks for a given example', 'get_verbalizers_for_task': 'call get_verbalizers on a processor to retrieve the list of verbalizer words mapped to label classes', 'get_tokenized_verbalizer_ids': 'call get_tokenized_verbalizers on a processor to get token IDs for each verbalizer word using the tokenizer'}
```

## File: facebookresearch_perfect/fewshot/data/tasks.py

Prompts

```
['create an MLMProcessor instance with a tokenizer, verbalizers, max sequence length, and processor for masked language modeling data preprocessing', 'run the MLMProcessor forward method on an example to get tokenized input IDs, attention masks, and candidate token IDs', 'test the MLMProcessor truncate method to verify two text sequences are shortened to fit the maximum sequence length', 'review the MLMProcessor prepare_classification_inputs method to understand how classification inputs are tokenized, padded, and returned with labels', 'refactor the MLMProcessor tokenize method to customize how text entries are encoded into token ID tuples with shortenable flags', 'use AutoProcessor.get to create a task-specific processor like MR or BoolQ with a tokenizer and pattern settings', 'call get_sentence_parts on a processor to convert an example into tokenized sentence parts with mask tokens', 'call get_prompt_parts on a processor to build a PET-style prompt with verbalizer masks for a given example', 'call get_verbalizers on a processor to retrieve the list of verbalizer words mapped to label classes', 'call get_tokenized_verbalizers on a processor to get token IDs for each verbalizer word using the tokenizer', 'use AutoTask.get to instantiate a task class by name with seed and sample parameters', 'call load_datasets on a task instance to load GLUE or SuperGLUE datasets from HuggingFace', 'call sample_datasets to split training data into balanced train and validation sets by label', 'call get_datasets on a task instance to load, sample, and post-process datasets in one step', 'subclass AbstractTask to define a new few-shot NLP task with custom dataset loading logic', 'tokenize a verbalization word using a HuggingFace tokenizer and return token ids', 'remove trailing punctuation characters from a word string', 'convert a word string to lowercase', 'create a Text dataclass with shortenable bool tensor and text string fields', 'review the Text dataclass inheriting from transformers ModelOutput for dataset processing']
```

Usage

```
{'get_task_instance': 'use AutoTask.get to instantiate a task class by name with seed and sample parameters', 'load_datasets': 'call load_datasets on a task instance to load GLUE or SuperGLUE datasets from HuggingFace', 'sample_datasets': 'call sample_datasets to split training data into balanced train and validation sets by label', 'get_datasets': 'call get_datasets on a task instance to load, sample, and post-process datasets in one step', 'create_custom_task': 'subclass AbstractTask to define a new few-shot NLP task with custom dataset loading logic'}
```

## File: facebookresearch_perfect/fewshot/data/utils.py

Prompts

```
['create an MLMProcessor instance with a tokenizer, verbalizers, max sequence length, and processor for masked language modeling data preprocessing', 'run the MLMProcessor forward method on an example to get tokenized input IDs, attention masks, and candidate token IDs', 'test the MLMProcessor truncate method to verify two text sequences are shortened to fit the maximum sequence length', 'review the MLMProcessor prepare_classification_inputs method to understand how classification inputs are tokenized, padded, and returned with labels', 'refactor the MLMProcessor tokenize method to customize how text entries are encoded into token ID tuples with shortenable flags', 'use AutoProcessor.get to create a task-specific processor like MR or BoolQ with a tokenizer and pattern settings', 'call get_sentence_parts on a processor to convert an example into tokenized sentence parts with mask tokens', 'call get_prompt_parts on a processor to build a PET-style prompt with verbalizer masks for a given example', 'call get_verbalizers on a processor to retrieve the list of verbalizer words mapped to label classes', 'call get_tokenized_verbalizers on a processor to get token IDs for each verbalizer word using the tokenizer', 'use AutoTask.get to instantiate a task class by name with seed and sample parameters', 'call load_datasets on a task instance to load GLUE or SuperGLUE datasets from HuggingFace', 'call sample_datasets to split training data into balanced train and validation sets by label', 'call get_datasets on a task instance to load, sample, and post-process datasets in one step', 'subclass AbstractTask to define a new few-shot NLP task with custom dataset loading logic', 'tokenize a verbalization word using a HuggingFace tokenizer and return token ids', 'remove trailing punctuation characters from a word string', 'convert a word string to lowercase', 'create a Text dataclass with shortenable bool tensor and text string fields', 'review the Text dataclass inheriting from transformers ModelOutput for dataset processing']
```

Usage

```
{'get_verbalization_ids_tokenize_word': 'tokenize a verbalization word using a HuggingFace tokenizer and return token ids', 'remove_final_punctuation_strip_trailing': 'remove trailing punctuation characters from a word string', 'lowercase_convert_word': 'convert a word string to lowercase', 'create_Text_dataclass': 'create a Text dataclass with shortenable bool tensor and text string fields', 'review_Text_ModelOutput': 'review the Text dataclass inheriting from transformers ModelOutput for dataset processing'}
```

