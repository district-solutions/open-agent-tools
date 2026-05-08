# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/data/legacy/block_pair_dataset.py

Prompts

```
['create a BlockPairDataset that breaks tokens into sentence pairs respecting document boundaries for next sentence prediction', 'create a BlockPairDataset with break_mode none to cut tokens evenly without respecting document boundaries', 'review the BlockPairDataset _generate_sentence_pair method that creates sentence pairs from a single document chunk', 'review the BlockPairDataset _truncate_sentences method that truncates sentence pairs to fit max token limits', 'summarize the BlockPairDataset _pair_sentences method that pairs blocks with 50% consecutive and 50% random sentences', 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style training', 'build a masked language model training batch by masking tokens with MASK, random, or original tokens per BERT strategy', 'collate a list of sample dicts into a mini-batch tensor with source tokens, segment labels, and LM targets', 'review the MaskedLMDataset __getitem__ method to understand how it returns block pairs with sentence targets', 'test the MaskedLMDataset ordered_indices method to verify shuffle or size-based sorting behavior for batching', 'create a MaskedLMDictionary instance with pad, eos, unk, and mask special symbols for masked language modeling', 'get the mask symbol index from a MaskedLMDictionary using the mask helper method', 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep special symbols for BERT tasks', 'get the cls and sep symbol indices from a BertDictionary using the cls and sep helper methods', 'review the MaskedLMDictionary class and its mask symbol handling for masked language modeling tasks']
```

Usage

```
{'create_BlockPairDataset_doc_mode': 'create a BlockPairDataset that breaks tokens into sentence pairs respecting document boundaries for next sentence prediction', 'create_BlockPairDataset_none_mode': 'create a BlockPairDataset with break_mode none to cut tokens evenly without respecting document boundaries', 'review_BlockPairDataset_generate_sentence_pair': 'review the BlockPairDataset _generate_sentence_pair method that creates sentence pairs from a single document chunk', 'review_BlockPairDataset_truncate_sentences': 'review the BlockPairDataset _truncate_sentences method that truncates sentence pairs to fit max token limits', 'summarize_BlockPairDataset_pair_sentences': 'summarize the BlockPairDataset _pair_sentences method that pairs blocks with 50% consecutive and 50% random sentences'}
```

## File: facebookresearch_fairseq/fairseq/data/legacy/masked_lm_dataset.py

Prompts

```
['create a BlockPairDataset that breaks tokens into sentence pairs respecting document boundaries for next sentence prediction', 'create a BlockPairDataset with break_mode none to cut tokens evenly without respecting document boundaries', 'review the BlockPairDataset _generate_sentence_pair method that creates sentence pairs from a single document chunk', 'review the BlockPairDataset _truncate_sentences method that truncates sentence pairs to fit max token limits', 'summarize the BlockPairDataset _pair_sentences method that pairs blocks with 50% consecutive and 50% random sentences', 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style training', 'build a masked language model training batch by masking tokens with MASK, random, or original tokens per BERT strategy', 'collate a list of sample dicts into a mini-batch tensor with source tokens, segment labels, and LM targets', 'review the MaskedLMDataset __getitem__ method to understand how it returns block pairs with sentence targets', 'test the MaskedLMDataset ordered_indices method to verify shuffle or size-based sorting behavior for batching', 'create a MaskedLMDictionary instance with pad, eos, unk, and mask special symbols for masked language modeling', 'get the mask symbol index from a MaskedLMDictionary using the mask helper method', 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep special symbols for BERT tasks', 'get the cls and sep symbol indices from a BertDictionary using the cls and sep helper methods', 'review the MaskedLMDictionary class and its mask symbol handling for masked language modeling tasks']
```

Usage

```
{'create_MaskedLMDataset': 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style training', 'build_mask_block': 'build a masked language model training batch by masking tokens with MASK, random, or original tokens per BERT strategy', 'collate_samples': 'collate a list of sample dicts into a mini-batch tensor with source tokens, segment labels, and LM targets', 'review_MaskedLMDataset_getitem': 'review the MaskedLMDataset __getitem__ method to understand how it returns block pairs with sentence targets', 'test_ordered_indices': 'test the MaskedLMDataset ordered_indices method to verify shuffle or size-based sorting behavior for batching'}
```

## File: facebookresearch_fairseq/fairseq/data/legacy/masked_lm_dictionary.py

Prompts

```
['create a BlockPairDataset that breaks tokens into sentence pairs respecting document boundaries for next sentence prediction', 'create a BlockPairDataset with break_mode none to cut tokens evenly without respecting document boundaries', 'review the BlockPairDataset _generate_sentence_pair method that creates sentence pairs from a single document chunk', 'review the BlockPairDataset _truncate_sentences method that truncates sentence pairs to fit max token limits', 'summarize the BlockPairDataset _pair_sentences method that pairs blocks with 50% consecutive and 50% random sentences', 'create a MaskedLMDataset wrapping a TokenBlockDataset with configurable masking ratio and probability for BERT-style training', 'build a masked language model training batch by masking tokens with MASK, random, or original tokens per BERT strategy', 'collate a list of sample dicts into a mini-batch tensor with source tokens, segment labels, and LM targets', 'review the MaskedLMDataset __getitem__ method to understand how it returns block pairs with sentence targets', 'test the MaskedLMDataset ordered_indices method to verify shuffle or size-based sorting behavior for batching', 'create a MaskedLMDictionary instance with pad, eos, unk, and mask special symbols for masked language modeling', 'get the mask symbol index from a MaskedLMDictionary using the mask helper method', 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep special symbols for BERT tasks', 'get the cls and sep symbol indices from a BertDictionary using the cls and sep helper methods', 'review the MaskedLMDictionary class and its mask symbol handling for masked language modeling tasks']
```

Usage

```
{'create_masked_lm_dictionary': 'create a MaskedLMDictionary instance with pad, eos, unk, and mask special symbols for masked language modeling', 'get_mask_index': 'get the mask symbol index from a MaskedLMDictionary using the mask helper method', 'create_bert_dictionary': 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep special symbols for BERT tasks', 'get_cls_sep_index': 'get the cls and sep symbol indices from a BertDictionary using the cls and sep helper methods', 'review_masked_lm_dictionary_class': 'review the MaskedLMDictionary class and its mask symbol handling for masked language modeling tasks'}
```

