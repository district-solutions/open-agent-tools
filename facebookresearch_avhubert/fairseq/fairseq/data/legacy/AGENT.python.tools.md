# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/data/legacy/block_pair_dataset.py

Prompts

```
['create a BlockPairDataset instance with doc break mode to generate sentence pairs respecting document boundaries', 'create a BlockPairDataset instance with none break mode to cut tokens evenly without respecting boundaries', 'review the BlockPairDataset constructor to understand how block_size, break_mode, and short_seq_prob configure sentence pairing', 'summarize the BlockPairDataset __getitem__ method that fetches paired token blocks and their next sentence prediction labels', 'test the BlockPairDataset prefetch method to verify it correctly preloads underlying dataset indices for batched sentence pairs', 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style training', 'mask tokens in a sentence block using the BERT strategy with mask, random, and original token probabilities', 'collate a list of masked language model samples into a mini-batch with source tokens, segment labels, and targets', 'get a single sample from the MaskedLMDataset returning block one, block two, and sentence target by index', 'return ordered indices for the MaskedLMDataset either shuffled randomly or sorted by sample size for batching', 'create a MaskedLMDictionary instance with custom pad, eos, unk, and mask symbols for masked language modeling', 'use the MaskedLMDictionary mask method to retrieve the index of the mask symbol', 'create a BertDictionary instance with cls and sep symbols added on top of masked LM symbols', 'use the BertDictionary cls and sep methods to retrieve the indices of cls and sep symbols', 'review the MaskedLMDictionary class and its inheritance from Dictionary to understand special symbol handling']
```

Usage

```
{'create_BlockPairDataset_doc_mode': 'create a BlockPairDataset instance with doc break mode to generate sentence pairs respecting document boundaries', 'create_BlockPairDataset_none_mode': 'create a BlockPairDataset instance with none break mode to cut tokens evenly without respecting boundaries', 'review_BlockPairDataset_init': 'review the BlockPairDataset constructor to understand how block_size, break_mode, and short_seq_prob configure sentence pairing', 'summarize_BlockPairDataset_getitem': 'summarize the BlockPairDataset __getitem__ method that fetches paired token blocks and their next sentence prediction labels', 'test_BlockPairDataset_prefetch': 'test the BlockPairDataset prefetch method to verify it correctly preloads underlying dataset indices for batched sentence pairs'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/data/legacy/masked_lm_dataset.py

Prompts

```
['create a BlockPairDataset instance with doc break mode to generate sentence pairs respecting document boundaries', 'create a BlockPairDataset instance with none break mode to cut tokens evenly without respecting boundaries', 'review the BlockPairDataset constructor to understand how block_size, break_mode, and short_seq_prob configure sentence pairing', 'summarize the BlockPairDataset __getitem__ method that fetches paired token blocks and their next sentence prediction labels', 'test the BlockPairDataset prefetch method to verify it correctly preloads underlying dataset indices for batched sentence pairs', 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style training', 'mask tokens in a sentence block using the BERT strategy with mask, random, and original token probabilities', 'collate a list of masked language model samples into a mini-batch with source tokens, segment labels, and targets', 'get a single sample from the MaskedLMDataset returning block one, block two, and sentence target by index', 'return ordered indices for the MaskedLMDataset either shuffled randomly or sorted by sample size for batching', 'create a MaskedLMDictionary instance with custom pad, eos, unk, and mask symbols for masked language modeling', 'use the MaskedLMDictionary mask method to retrieve the index of the mask symbol', 'create a BertDictionary instance with cls and sep symbols added on top of masked LM symbols', 'use the BertDictionary cls and sep methods to retrieve the indices of cls and sep symbols', 'review the MaskedLMDictionary class and its inheritance from Dictionary to understand special symbol handling']
```

Usage

```
{'create_masked_lm_dataset': 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style training', 'mask_block_tokens': 'mask tokens in a sentence block using the BERT strategy with mask, random, and original token probabilities', 'collate_masked_lm_batch': 'collate a list of masked language model samples into a mini-batch with source tokens, segment labels, and targets', 'get_masked_lm_sample': 'get a single sample from the MaskedLMDataset returning block one, block two, and sentence target by index', 'order_masked_lm_indices': 'return ordered indices for the MaskedLMDataset either shuffled randomly or sorted by sample size for batching'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/data/legacy/masked_lm_dictionary.py

Prompts

```
['create a BlockPairDataset instance with doc break mode to generate sentence pairs respecting document boundaries', 'create a BlockPairDataset instance with none break mode to cut tokens evenly without respecting boundaries', 'review the BlockPairDataset constructor to understand how block_size, break_mode, and short_seq_prob configure sentence pairing', 'summarize the BlockPairDataset __getitem__ method that fetches paired token blocks and their next sentence prediction labels', 'test the BlockPairDataset prefetch method to verify it correctly preloads underlying dataset indices for batched sentence pairs', 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style training', 'mask tokens in a sentence block using the BERT strategy with mask, random, and original token probabilities', 'collate a list of masked language model samples into a mini-batch with source tokens, segment labels, and targets', 'get a single sample from the MaskedLMDataset returning block one, block two, and sentence target by index', 'return ordered indices for the MaskedLMDataset either shuffled randomly or sorted by sample size for batching', 'create a MaskedLMDictionary instance with custom pad, eos, unk, and mask symbols for masked language modeling', 'use the MaskedLMDictionary mask method to retrieve the index of the mask symbol', 'create a BertDictionary instance with cls and sep symbols added on top of masked LM symbols', 'use the BertDictionary cls and sep methods to retrieve the indices of cls and sep symbols', 'review the MaskedLMDictionary class and its inheritance from Dictionary to understand special symbol handling']
```

Usage

```
{'create_MaskedLMDictionary': 'create a MaskedLMDictionary instance with custom pad, eos, unk, and mask symbols for masked language modeling', 'use_MaskedLMDictionary_mask': 'use the MaskedLMDictionary mask method to retrieve the index of the mask symbol', 'create_BertDictionary': 'create a BertDictionary instance with cls and sep symbols added on top of masked LM symbols', 'use_BertDictionary_cls_sep': 'use the BertDictionary cls and sep methods to retrieve the indices of cls and sep symbols', 'review_MaskedLMDictionary_inheritance': 'review the MaskedLMDictionary class and its inheritance from Dictionary to understand special symbol handling'}
```

