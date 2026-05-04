# Agent Python Tools

- repo: facebookresearch/flowmatching
- repo_uri: https://github.com/facebookresearch/flow_matching

## File: facebookresearch_flowmatching/examples/text/data/data.py

Prompts

```
['load tokenize and chunk a HuggingFace dataset like wikitext103 or fineweb-edu using GPT2 tokenizer', 'build a DataState with train and test datasets from an OmegaConf configuration object', 'create cyclical train and validation DataLoader iterators from a DataState and config', 'create a Dataset dataclass that wraps a HuggingFace dataset with a StatefulDistributedSampler', 'create a DataState dataclass that holds train and test Dataset objects for model training', 'run the wt_detokenizer function to detokenize a string with contractions and punctuation', 'test the wt_detokenizer function with tokenized text containing spaced punctuation marks', 'refactor the wt_detokenizer function to support additional tokenization schemes beyond wordpiece', 'review the wt_detokenizer function for handling contractions brackets and number separators', 'summarize the wt_detokenizer function which reverses subword tokenization artifacts in text', 'create a generator that infinitely cycles through a PyTorch DataLoader yielding each batch', 'create a StatefulDistributedSampler for a PyTorch dataset to enable checkpoint-aware distributed sampling', 'test saving the yielded count state of a StatefulDistributedSampler via its state_dict method', 'test restoring a StatefulDistributedSampler from a saved state_dict to resume sampling from a checkpoint', 'review the StatefulDistributedSampler class and its state_dict and load_state_dict methods for checkpoint support']
```

Usage

```
{'get_hf_dataset': 'load tokenize and chunk a HuggingFace dataset like wikitext103 or fineweb-edu using GPT2 tokenizer', 'get_data_state': 'build a DataState with train and test datasets from an OmegaConf configuration object', 'get_data_loaders': 'create cyclical train and validation DataLoader iterators from a DataState and config', 'create_Dataset_dataclass': 'create a Dataset dataclass that wraps a HuggingFace dataset with a StatefulDistributedSampler', 'create_DataState_dataclass': 'create a DataState dataclass that holds train and test Dataset objects for model training'}
```

## File: facebookresearch_flowmatching/examples/text/data/tokenizer.py

Prompts

```
['load tokenize and chunk a HuggingFace dataset like wikitext103 or fineweb-edu using GPT2 tokenizer', 'build a DataState with train and test datasets from an OmegaConf configuration object', 'create cyclical train and validation DataLoader iterators from a DataState and config', 'create a Dataset dataclass that wraps a HuggingFace dataset with a StatefulDistributedSampler', 'create a DataState dataclass that holds train and test Dataset objects for model training', 'run the wt_detokenizer function to detokenize a string with contractions and punctuation', 'test the wt_detokenizer function with tokenized text containing spaced punctuation marks', 'refactor the wt_detokenizer function to support additional tokenization schemes beyond wordpiece', 'review the wt_detokenizer function for handling contractions brackets and number separators', 'summarize the wt_detokenizer function which reverses subword tokenization artifacts in text', 'create a generator that infinitely cycles through a PyTorch DataLoader yielding each batch', 'create a StatefulDistributedSampler for a PyTorch dataset to enable checkpoint-aware distributed sampling', 'test saving the yielded count state of a StatefulDistributedSampler via its state_dict method', 'test restoring a StatefulDistributedSampler from a saved state_dict to resume sampling from a checkpoint', 'review the StatefulDistributedSampler class and its state_dict and load_state_dict methods for checkpoint support']
```

Usage

```
{'run_wt_detokenizer': 'run the wt_detokenizer function to detokenize a string with contractions and punctuation', 'test_wt_detokenizer': 'test the wt_detokenizer function with tokenized text containing spaced punctuation marks', 'refactor_wt_detokenizer': 'refactor the wt_detokenizer function to support additional tokenization schemes beyond wordpiece', 'review_wt_detokenizer': 'review the wt_detokenizer function for handling contractions brackets and number separators', 'summarize_wt_detokenizer': 'summarize the wt_detokenizer function which reverses subword tokenization artifacts in text'}
```

## File: facebookresearch_flowmatching/examples/text/data/utils.py

Prompts

```
['load tokenize and chunk a HuggingFace dataset like wikitext103 or fineweb-edu using GPT2 tokenizer', 'build a DataState with train and test datasets from an OmegaConf configuration object', 'create cyclical train and validation DataLoader iterators from a DataState and config', 'create a Dataset dataclass that wraps a HuggingFace dataset with a StatefulDistributedSampler', 'create a DataState dataclass that holds train and test Dataset objects for model training', 'run the wt_detokenizer function to detokenize a string with contractions and punctuation', 'test the wt_detokenizer function with tokenized text containing spaced punctuation marks', 'refactor the wt_detokenizer function to support additional tokenization schemes beyond wordpiece', 'review the wt_detokenizer function for handling contractions brackets and number separators', 'summarize the wt_detokenizer function which reverses subword tokenization artifacts in text', 'create a generator that infinitely cycles through a PyTorch DataLoader yielding each batch', 'create a StatefulDistributedSampler for a PyTorch dataset to enable checkpoint-aware distributed sampling', 'test saving the yielded count state of a StatefulDistributedSampler via its state_dict method', 'test restoring a StatefulDistributedSampler from a saved state_dict to resume sampling from a checkpoint', 'review the StatefulDistributedSampler class and its state_dict and load_state_dict methods for checkpoint support']
```

Usage

```
{'create_cycle_loader': 'create a generator that infinitely cycles through a PyTorch DataLoader yielding each batch', 'create_stateful_distributed_sampler': 'create a StatefulDistributedSampler for a PyTorch dataset to enable checkpoint-aware distributed sampling', 'test_state_dict_save': 'test saving the yielded count state of a StatefulDistributedSampler via its state_dict method', 'test_state_dict_load': 'test restoring a StatefulDistributedSampler from a saved state_dict to resume sampling from a checkpoint', 'review_stateful_distributed_sampler': 'review the StatefulDistributedSampler class and its state_dict and load_state_dict methods for checkpoint support'}
```

