# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/MMPT/scripts/text_token_extractor/pretokenization.py

Prompts

```
['run the pretokenization script to convert caption JSON files into pickle format using a config file', 'create a TokenizerDataset that wraps PKLJSONStrTextProcessor for iterating over video IDs and their captions', 'run the tokenize function to process all captions through a DataLoader and save results to a pickle file', 'run the sharding function to load tokenized captions and split them into train and val shards', 'run the numpify function to convert caption start/end times and token IDs into numpy arrays and save as ShardedTensor']
```

Usage

```
{'run_pretokenize_captions': 'run the pretokenization script to convert caption JSON files into pickle format using a config file', 'create_TokenizerDataset': 'create a TokenizerDataset that wraps PKLJSONStrTextProcessor for iterating over video IDs and their captions', 'run_tokenize_function': 'run the tokenize function to process all captions through a DataLoader and save results to a pickle file', 'run_sharding_function': 'run the sharding function to load tokenized captions and split them into train and val shards', 'run_numpify_function': 'run the numpify function to convert caption start/end times and token IDs into numpy arrays and save as ShardedTensor'}
```

