# Agent Python Tools

- repo: facebookresearch/dpr
- repo_uri: https://github.com/facebookresearch/dpr

## File: facebookresearch_dpr/dpr/utils/data_utils.py

Prompts

```
['create a python module to read and aggregate pickle serialized data from multiple file paths into a single list', 'build a python script to read and merge data from multiple JSON files into one aggregated list', 'create a function to read and aggregate records from multiple JSONL files into a single list', 'build a python utility to normalize a question string by replacing curly quotes with straight quotes', 'create a python module to iterate over a sharded dataset for PyTorch DDP distributed training with configurable batch size', 'get the current process rank in a PyTorch distributed training job', 'get the total number of processes in a PyTorch distributed training job', 'get the default WORLD process group for PyTorch distributed communication', 'perform an all-reduce operation on a tensor across all processes in a distributed group', 'gather arbitrary picklable Python data from all workers into a list across a distributed group', 'setup a PyTorch model and optimizer for distributed training with optional fp16 support', 'move a nested sample of tensors, dicts, and lists to a specified device', 'create a linear warmup then decay learning rate schedule for a PyTorch optimizer', 'initialize Linear, Embedding, and LayerNorm module weights with normal distribution and zero bias', 'load a saved model checkpoint file and return a CheckpointState namedtuple with model and optimizer dicts', 'use SimpleTokenizer to tokenize text into tokens with regex-based word boundary splitting', 'use SpacyTokenizer to tokenize text with spaCy and extract pos, lemma, and ner annotations', 'call the ngrams method on a Tokens object to extract n-grams up to length n from tokenized text', 'call entity_groups on a Tokens object to group consecutive NER-tagged tokens by their entity type', 'call untokenize on a Tokens object to reconstruct the original text with whitespace from token data']
```

Usage

```
{'read_serialized_data_from_files': 'create a python module to read and aggregate pickle serialized data from multiple file paths into a single list', 'read_data_from_json_files': 'build a python script to read and merge data from multiple JSON files into one aggregated list', 'read_data_from_jsonl_files': 'create a function to read and aggregate records from multiple JSONL files into a single list', 'normalize_question': 'build a python utility to normalize a question string by replacing curly quotes with straight quotes', 'ShardedDataIterator': 'create a python module to iterate over a sharded dataset for PyTorch DDP distributed training with configurable batch size'}
```

## File: facebookresearch_dpr/dpr/utils/dist_utils.py

Prompts

```
['create a python module to read and aggregate pickle serialized data from multiple file paths into a single list', 'build a python script to read and merge data from multiple JSON files into one aggregated list', 'create a function to read and aggregate records from multiple JSONL files into a single list', 'build a python utility to normalize a question string by replacing curly quotes with straight quotes', 'create a python module to iterate over a sharded dataset for PyTorch DDP distributed training with configurable batch size', 'get the current process rank in a PyTorch distributed training job', 'get the total number of processes in a PyTorch distributed training job', 'get the default WORLD process group for PyTorch distributed communication', 'perform an all-reduce operation on a tensor across all processes in a distributed group', 'gather arbitrary picklable Python data from all workers into a list across a distributed group', 'setup a PyTorch model and optimizer for distributed training with optional fp16 support', 'move a nested sample of tensors, dicts, and lists to a specified device', 'create a linear warmup then decay learning rate schedule for a PyTorch optimizer', 'initialize Linear, Embedding, and LayerNorm module weights with normal distribution and zero bias', 'load a saved model checkpoint file and return a CheckpointState namedtuple with model and optimizer dicts', 'use SimpleTokenizer to tokenize text into tokens with regex-based word boundary splitting', 'use SpacyTokenizer to tokenize text with spaCy and extract pos, lemma, and ner annotations', 'call the ngrams method on a Tokens object to extract n-grams up to length n from tokenized text', 'call entity_groups on a Tokens object to group consecutive NER-tagged tokens by their entity type', 'call untokenize on a Tokens object to reconstruct the original text with whitespace from token data']
```

Usage

```
{'get_rank': 'get the current process rank in a PyTorch distributed training job', 'get_world_size': 'get the total number of processes in a PyTorch distributed training job', 'get_default_group': 'get the default WORLD process group for PyTorch distributed communication', 'all_reduce': 'perform an all-reduce operation on a tensor across all processes in a distributed group', 'all_gather_list': 'gather arbitrary picklable Python data from all workers into a list across a distributed group'}
```

## File: facebookresearch_dpr/dpr/utils/model_utils.py

Prompts

```
['create a python module to read and aggregate pickle serialized data from multiple file paths into a single list', 'build a python script to read and merge data from multiple JSON files into one aggregated list', 'create a function to read and aggregate records from multiple JSONL files into a single list', 'build a python utility to normalize a question string by replacing curly quotes with straight quotes', 'create a python module to iterate over a sharded dataset for PyTorch DDP distributed training with configurable batch size', 'get the current process rank in a PyTorch distributed training job', 'get the total number of processes in a PyTorch distributed training job', 'get the default WORLD process group for PyTorch distributed communication', 'perform an all-reduce operation on a tensor across all processes in a distributed group', 'gather arbitrary picklable Python data from all workers into a list across a distributed group', 'setup a PyTorch model and optimizer for distributed training with optional fp16 support', 'move a nested sample of tensors, dicts, and lists to a specified device', 'create a linear warmup then decay learning rate schedule for a PyTorch optimizer', 'initialize Linear, Embedding, and LayerNorm module weights with normal distribution and zero bias', 'load a saved model checkpoint file and return a CheckpointState namedtuple with model and optimizer dicts', 'use SimpleTokenizer to tokenize text into tokens with regex-based word boundary splitting', 'use SpacyTokenizer to tokenize text with spaCy and extract pos, lemma, and ner annotations', 'call the ngrams method on a Tokens object to extract n-grams up to length n from tokenized text', 'call entity_groups on a Tokens object to group consecutive NER-tagged tokens by their entity type', 'call untokenize on a Tokens object to reconstruct the original text with whitespace from token data']
```

Usage

```
{'setup_distributed_model': 'setup a PyTorch model and optimizer for distributed training with optional fp16 support', 'move_tensors_to_device': 'move a nested sample of tensors, dicts, and lists to a specified device', 'create_linear_lr_schedule': 'create a linear warmup then decay learning rate schedule for a PyTorch optimizer', 'initialize_model_weights': 'initialize Linear, Embedding, and LayerNorm module weights with normal distribution and zero bias', 'load_checkpoint_state': 'load a saved model checkpoint file and return a CheckpointState namedtuple with model and optimizer dicts'}
```

## File: facebookresearch_dpr/dpr/utils/tokenizers.py

Prompts

```
['create a python module to read and aggregate pickle serialized data from multiple file paths into a single list', 'build a python script to read and merge data from multiple JSON files into one aggregated list', 'create a function to read and aggregate records from multiple JSONL files into a single list', 'build a python utility to normalize a question string by replacing curly quotes with straight quotes', 'create a python module to iterate over a sharded dataset for PyTorch DDP distributed training with configurable batch size', 'get the current process rank in a PyTorch distributed training job', 'get the total number of processes in a PyTorch distributed training job', 'get the default WORLD process group for PyTorch distributed communication', 'perform an all-reduce operation on a tensor across all processes in a distributed group', 'gather arbitrary picklable Python data from all workers into a list across a distributed group', 'setup a PyTorch model and optimizer for distributed training with optional fp16 support', 'move a nested sample of tensors, dicts, and lists to a specified device', 'create a linear warmup then decay learning rate schedule for a PyTorch optimizer', 'initialize Linear, Embedding, and LayerNorm module weights with normal distribution and zero bias', 'load a saved model checkpoint file and return a CheckpointState namedtuple with model and optimizer dicts', 'use SimpleTokenizer to tokenize text into tokens with regex-based word boundary splitting', 'use SpacyTokenizer to tokenize text with spaCy and extract pos, lemma, and ner annotations', 'call the ngrams method on a Tokens object to extract n-grams up to length n from tokenized text', 'call entity_groups on a Tokens object to group consecutive NER-tagged tokens by their entity type', 'call untokenize on a Tokens object to reconstruct the original text with whitespace from token data']
```

Usage

```
{'tokenize_text_simple': 'use SimpleTokenizer to tokenize text into tokens with regex-based word boundary splitting', 'tokenize_text_spacy': 'use SpacyTokenizer to tokenize text with spaCy and extract pos, lemma, and ner annotations', 'extract_ngrams': 'call the ngrams method on a Tokens object to extract n-grams up to length n from tokenized text', 'extract_entity_groups': 'call entity_groups on a Tokens object to group consecutive NER-tagged tokens by their entity type', 'untokenize_tokens': 'call untokenize on a Tokens object to reconstruct the original text with whitespace from token data'}
```

