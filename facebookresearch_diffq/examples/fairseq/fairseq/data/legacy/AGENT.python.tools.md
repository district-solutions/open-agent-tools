# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/data/legacy/block_pair_dataset.py

Prompts

```
['create a BlockPairDataset instance in doc mode to break tokens into sentence pair blocks respecting document boundaries', 'create a BlockPairDataset instance in none mode to cut tokens evenly without respecting document boundaries', 'review the BlockPairDataset constructor to understand how block_size, break_mode, and short_seq_prob configure sentence pairing', 'summarize the BlockPairDataset __getitem__ method that fetches paired token blocks and their next sentence prediction labels', 'test the BlockPairDataset prefetch method to verify it correctly preloads underlying dataset indices for given block pairs', 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style pretraining', 'build a masked language model training batch by masking tokens with MASK, random, or original tokens per BERT strategy', 'collate a list of masked LM samples into a mini-batch with source tokens, segment labels, and LM targets', 'review the MaskedLMDataset getitem method to understand how it returns block pairs and sentence targets', 'test the MaskedLMDataset ordered_indices method to verify shuffle and size-based sorting behavior for batching', 'create a MaskedLMDictionary instance with pad, eos, unk, and mask symbols for masked language modeling', 'use the MaskedLMDictionary mask method to retrieve the index of the mask symbol', 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep symbols for BERT tasks', 'use the BertDictionary cls method to retrieve the index of the cls symbol', 'use the BertDictionary sep method to retrieve the index of the sep symbol']
```

Usage

```
{'create_BlockPairDataset_doc_mode': 'create a BlockPairDataset instance in doc mode to break tokens into sentence pair blocks respecting document boundaries', 'create_BlockPairDataset_none_mode': 'create a BlockPairDataset instance in none mode to cut tokens evenly without respecting document boundaries', 'review_BlockPairDataset_init': 'review the BlockPairDataset constructor to understand how block_size, break_mode, and short_seq_prob configure sentence pairing', 'summarize_BlockPairDataset_getitem': 'summarize the BlockPairDataset __getitem__ method that fetches paired token blocks and their next sentence prediction labels', 'test_BlockPairDataset_prefetch': 'test the BlockPairDataset prefetch method to verify it correctly preloads underlying dataset indices for given block pairs'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/data/legacy/masked_lm_dataset.py

Prompts

```
['create a BlockPairDataset instance in doc mode to break tokens into sentence pair blocks respecting document boundaries', 'create a BlockPairDataset instance in none mode to cut tokens evenly without respecting document boundaries', 'review the BlockPairDataset constructor to understand how block_size, break_mode, and short_seq_prob configure sentence pairing', 'summarize the BlockPairDataset __getitem__ method that fetches paired token blocks and their next sentence prediction labels', 'test the BlockPairDataset prefetch method to verify it correctly preloads underlying dataset indices for given block pairs', 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style pretraining', 'build a masked language model training batch by masking tokens with MASK, random, or original tokens per BERT strategy', 'collate a list of masked LM samples into a mini-batch with source tokens, segment labels, and LM targets', 'review the MaskedLMDataset getitem method to understand how it returns block pairs and sentence targets', 'test the MaskedLMDataset ordered_indices method to verify shuffle and size-based sorting behavior for batching', 'create a MaskedLMDictionary instance with pad, eos, unk, and mask symbols for masked language modeling', 'use the MaskedLMDictionary mask method to retrieve the index of the mask symbol', 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep symbols for BERT tasks', 'use the BertDictionary cls method to retrieve the index of the cls symbol', 'use the BertDictionary sep method to retrieve the index of the sep symbol']
```

Usage

```
{'create_masked_lm_dataset': 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style pretraining', 'build_mask_block': 'build a masked language model training batch by masking tokens with MASK, random, or original tokens per BERT strategy', 'collate_samples': 'collate a list of masked LM samples into a mini-batch with source tokens, segment labels, and LM targets', 'review_masked_lm_dataset_getitem': 'review the MaskedLMDataset getitem method to understand how it returns block pairs and sentence targets', 'test_ordered_indices': 'test the MaskedLMDataset ordered_indices method to verify shuffle and size-based sorting behavior for batching'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/data/legacy/masked_lm_dictionary.py

Prompts

```
['create a BlockPairDataset instance in doc mode to break tokens into sentence pair blocks respecting document boundaries', 'create a BlockPairDataset instance in none mode to cut tokens evenly without respecting document boundaries', 'review the BlockPairDataset constructor to understand how block_size, break_mode, and short_seq_prob configure sentence pairing', 'summarize the BlockPairDataset __getitem__ method that fetches paired token blocks and their next sentence prediction labels', 'test the BlockPairDataset prefetch method to verify it correctly preloads underlying dataset indices for given block pairs', 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style pretraining', 'build a masked language model training batch by masking tokens with MASK, random, or original tokens per BERT strategy', 'collate a list of masked LM samples into a mini-batch with source tokens, segment labels, and LM targets', 'review the MaskedLMDataset getitem method to understand how it returns block pairs and sentence targets', 'test the MaskedLMDataset ordered_indices method to verify shuffle and size-based sorting behavior for batching', 'create a MaskedLMDictionary instance with pad, eos, unk, and mask symbols for masked language modeling', 'use the MaskedLMDictionary mask method to retrieve the index of the mask symbol', 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep symbols for BERT tasks', 'use the BertDictionary cls method to retrieve the index of the cls symbol', 'use the BertDictionary sep method to retrieve the index of the sep symbol']
```

Usage

```
{'create_MaskedLMDictionary': 'create a MaskedLMDictionary instance with pad, eos, unk, and mask symbols for masked language modeling', 'use_MaskedLMDictionary_mask': 'use the MaskedLMDictionary mask method to retrieve the index of the mask symbol', 'create_BertDictionary': 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep symbols for BERT tasks', 'use_BertDictionary_cls': 'use the BertDictionary cls method to retrieve the index of the cls symbol', 'use_BertDictionary_sep': 'use the BertDictionary sep method to retrieve the index of the sep symbol'}
```

