# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/tasks/base_task.py

Prompts

```
['build a dictionary from a list of text files with configurable threshold and padding factor', 'load a pre-built dictionary from a file using the BaseTask load_dictionary class method', 'setup a new task instance from an omegaconf DictConfig with optional keyword arguments', 'build a model instance for a task using the task configuration and task object', 'get an EpochBatchIterator that yields batches from a dataset with configurable max tokens and sentences', 'build a LanguageModelingTask to train a language model using HuggingFace or ByteLevelBPE tokenizers', 'load a dataset split like train or valid for language modeling with configurable token block sizes', 'configure the LanguageModelingConfig sample_break_mode to control how samples are split at sentence or document boundaries', 'build a dataset for inference that prepends BOS/EOS tokens and appends PAD tokens to targets', 'create an evaluation dataloader for language model scoring with configurable context window and sharding', 'load a JSONL dataset split for streaming finetune language modeling with sharded epoch support', 'tokenize source and target JSON pairs into full and target-only token tensors for language modeling', 'collate batch items into src_tokens input and tgt_tokens target tensors for the model', 'register the streaming finetune language modeling task with the MetaSeq task registry', 'apply alpha-weighted sampling across multiple corpora datasets based on corpus size and sampling parameters', 'build a StreamingLanguageModelingTask to train a language model on JSONL data with on-the-fly BPE tokenization', 'create CM3 special sentinel tokens for causal masked language modeling with configurable masking modes', 'load a streaming dataset split from JSONL shards with optional alpha sampling across multiple corpora', 'configure multicorpus alpha sampling to upsample or downsample corpora by smoothed probability ratios']
```

Usage

```
{'build_dictionary_from_files': 'build a dictionary from a list of text files with configurable threshold and padding factor', 'load_dictionary_from_file': 'load a pre-built dictionary from a file using the BaseTask load_dictionary class method', 'setup_task_from_config': 'setup a new task instance from an omegaconf DictConfig with optional keyword arguments', 'build_model_for_task': 'build a model instance for a task using the task configuration and task object', 'get_batch_iterator': 'get an EpochBatchIterator that yields batches from a dataset with configurable max tokens and sentences'}
```

## File: facebookresearch_metaseq/metaseq/tasks/language_modeling.py

Prompts

```
['build a dictionary from a list of text files with configurable threshold and padding factor', 'load a pre-built dictionary from a file using the BaseTask load_dictionary class method', 'setup a new task instance from an omegaconf DictConfig with optional keyword arguments', 'build a model instance for a task using the task configuration and task object', 'get an EpochBatchIterator that yields batches from a dataset with configurable max tokens and sentences', 'build a LanguageModelingTask to train a language model using HuggingFace or ByteLevelBPE tokenizers', 'load a dataset split like train or valid for language modeling with configurable token block sizes', 'configure the LanguageModelingConfig sample_break_mode to control how samples are split at sentence or document boundaries', 'build a dataset for inference that prepends BOS/EOS tokens and appends PAD tokens to targets', 'create an evaluation dataloader for language model scoring with configurable context window and sharding', 'load a JSONL dataset split for streaming finetune language modeling with sharded epoch support', 'tokenize source and target JSON pairs into full and target-only token tensors for language modeling', 'collate batch items into src_tokens input and tgt_tokens target tensors for the model', 'register the streaming finetune language modeling task with the MetaSeq task registry', 'apply alpha-weighted sampling across multiple corpora datasets based on corpus size and sampling parameters', 'build a StreamingLanguageModelingTask to train a language model on JSONL data with on-the-fly BPE tokenization', 'create CM3 special sentinel tokens for causal masked language modeling with configurable masking modes', 'load a streaming dataset split from JSONL shards with optional alpha sampling across multiple corpora', 'configure multicorpus alpha sampling to upsample or downsample corpora by smoothed probability ratios']
```

Usage

```
{'build_language_modeling_task': 'build a LanguageModelingTask to train a language model using HuggingFace or ByteLevelBPE tokenizers', 'load_dataset_for_split': 'load a dataset split like train or valid for language modeling with configurable token block sizes', 'configure_sample_break_mode': 'configure the LanguageModelingConfig sample_break_mode to control how samples are split at sentence or document boundaries', 'build_inference_dataset': 'build a dataset for inference that prepends BOS/EOS tokens and appends PAD tokens to targets', 'create_eval_lm_dataloader': 'create an evaluation dataloader for language model scoring with configurable context window and sharding'}
```

## File: facebookresearch_metaseq/metaseq/tasks/streaming_finetune_language_modeling.py

Prompts

```
['build a dictionary from a list of text files with configurable threshold and padding factor', 'load a pre-built dictionary from a file using the BaseTask load_dictionary class method', 'setup a new task instance from an omegaconf DictConfig with optional keyword arguments', 'build a model instance for a task using the task configuration and task object', 'get an EpochBatchIterator that yields batches from a dataset with configurable max tokens and sentences', 'build a LanguageModelingTask to train a language model using HuggingFace or ByteLevelBPE tokenizers', 'load a dataset split like train or valid for language modeling with configurable token block sizes', 'configure the LanguageModelingConfig sample_break_mode to control how samples are split at sentence or document boundaries', 'build a dataset for inference that prepends BOS/EOS tokens and appends PAD tokens to targets', 'create an evaluation dataloader for language model scoring with configurable context window and sharding', 'load a JSONL dataset split for streaming finetune language modeling with sharded epoch support', 'tokenize source and target JSON pairs into full and target-only token tensors for language modeling', 'collate batch items into src_tokens input and tgt_tokens target tensors for the model', 'register the streaming finetune language modeling task with the MetaSeq task registry', 'apply alpha-weighted sampling across multiple corpora datasets based on corpus size and sampling parameters', 'build a StreamingLanguageModelingTask to train a language model on JSONL data with on-the-fly BPE tokenization', 'create CM3 special sentinel tokens for causal masked language modeling with configurable masking modes', 'load a streaming dataset split from JSONL shards with optional alpha sampling across multiple corpora', 'configure multicorpus alpha sampling to upsample or downsample corpora by smoothed probability ratios']
```

Usage

```
{'load_dataset_split': 'load a JSONL dataset split for streaming finetune language modeling with sharded epoch support', 'tokenize_src_tgt_json': 'tokenize source and target JSON pairs into full and target-only token tensors for language modeling', 'collate_batch_items': 'collate batch items into src_tokens input and tgt_tokens target tensors for the model', 'register_streaming_finetune_task': 'register the streaming finetune language modeling task with the MetaSeq task registry', 'alpha_sampling_multicorpus': 'apply alpha-weighted sampling across multiple corpora datasets based on corpus size and sampling parameters'}
```

## File: facebookresearch_metaseq/metaseq/tasks/streaming_language_modeling.py

Prompts

```
['build a dictionary from a list of text files with configurable threshold and padding factor', 'load a pre-built dictionary from a file using the BaseTask load_dictionary class method', 'setup a new task instance from an omegaconf DictConfig with optional keyword arguments', 'build a model instance for a task using the task configuration and task object', 'get an EpochBatchIterator that yields batches from a dataset with configurable max tokens and sentences', 'build a LanguageModelingTask to train a language model using HuggingFace or ByteLevelBPE tokenizers', 'load a dataset split like train or valid for language modeling with configurable token block sizes', 'configure the LanguageModelingConfig sample_break_mode to control how samples are split at sentence or document boundaries', 'build a dataset for inference that prepends BOS/EOS tokens and appends PAD tokens to targets', 'create an evaluation dataloader for language model scoring with configurable context window and sharding', 'load a JSONL dataset split for streaming finetune language modeling with sharded epoch support', 'tokenize source and target JSON pairs into full and target-only token tensors for language modeling', 'collate batch items into src_tokens input and tgt_tokens target tensors for the model', 'register the streaming finetune language modeling task with the MetaSeq task registry', 'apply alpha-weighted sampling across multiple corpora datasets based on corpus size and sampling parameters', 'build a StreamingLanguageModelingTask to train a language model on JSONL data with on-the-fly BPE tokenization', 'create CM3 special sentinel tokens for causal masked language modeling with configurable masking modes', 'load a streaming dataset split from JSONL shards with optional alpha sampling across multiple corpora', 'configure multicorpus alpha sampling to upsample or downsample corpora by smoothed probability ratios']
```

Usage

```
{'build_streaming_lm_task': 'build a StreamingLanguageModelingTask to train a language model on JSONL data with on-the-fly BPE tokenization', 'create_cm3_sentinel_tokens': 'create CM3 special sentinel tokens for causal masked language modeling with configurable masking modes', 'load_dataset_streaming': 'load a streaming dataset split from JSONL shards with optional alpha sampling across multiple corpora', 'configure_multicorpus_sampling': 'configure multicorpus alpha sampling to upsample or downsample corpora by smoothed probability ratios', 'get_batch_iterator': 'get a batch iterator that partitions and shuffles streaming token blocks across data parallel workers'}
```

