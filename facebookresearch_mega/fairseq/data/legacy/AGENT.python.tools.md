# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/data/legacy/block_pair_dataset.py

Prompts

```
['create a BlockPairDataset that breaks tokens into sentence pairs respecting document boundaries for next sentence prediction', 'create a BlockPairDataset with break_mode none to cut tokens evenly without respecting document boundaries', 'review the BlockPairDataset _generate_sentence_pair method that creates sentence pairs from a single document chunk', 'review the BlockPairDataset _truncate_sentences method that truncates sentence pairs to fit max token limits', 'summarize the BlockPairDataset _pair_sentences method that pairs sentences with 50 percent consecutive and 50 percent random', 'create a MaskedLMDataset wrapping a TokenBlockDataset or BlockPairDataset for masked language model training', 'mask tokens in a sentence block using the BERT-style masking strategy with mask, random, and original token probabilities', 'collate a list of masked LM samples into a mini-batch with source tokens, segment labels, and LM targets', 'get a single sample from the MaskedLMDataset returning block one, block two, and sentence target', 'return ordered indices for batching the MaskedLMDataset either shuffled or sorted by size', 'create a MaskedLMDictionary instance with pad, eos, unk, and mask special symbols for masked language modeling', 'get the integer index of the mask symbol from a MaskedLMDictionary using the mask method', 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep special symbols for BERT tasks', 'get the integer index of the cls or sep symbol from a BertDictionary using the cls or sep method', 'review the MaskedLMDictionary class and its mask symbol handling for masked language modeling tasks']
```

Usage

```
{'create_BlockPairDataset_doc_mode': 'create a BlockPairDataset that breaks tokens into sentence pairs respecting document boundaries for next sentence prediction', 'create_BlockPairDataset_none_mode': 'create a BlockPairDataset with break_mode none to cut tokens evenly without respecting document boundaries', 'review_BlockPairDataset_generate_sentence_pair': 'review the BlockPairDataset _generate_sentence_pair method that creates sentence pairs from a single document chunk', 'review_BlockPairDataset_truncate_sentences': 'review the BlockPairDataset _truncate_sentences method that truncates sentence pairs to fit max token limits', 'summarize_BlockPairDataset_pair_sentences': 'summarize the BlockPairDataset _pair_sentences method that pairs sentences with 50 percent consecutive and 50 percent random'}
```

## File: facebookresearch_mega/fairseq/data/legacy/masked_lm_dataset.py

Prompts

```
['create a BlockPairDataset that breaks tokens into sentence pairs respecting document boundaries for next sentence prediction', 'create a BlockPairDataset with break_mode none to cut tokens evenly without respecting document boundaries', 'review the BlockPairDataset _generate_sentence_pair method that creates sentence pairs from a single document chunk', 'review the BlockPairDataset _truncate_sentences method that truncates sentence pairs to fit max token limits', 'summarize the BlockPairDataset _pair_sentences method that pairs sentences with 50 percent consecutive and 50 percent random', 'create a MaskedLMDataset wrapping a TokenBlockDataset or BlockPairDataset for masked language model training', 'mask tokens in a sentence block using the BERT-style masking strategy with mask, random, and original token probabilities', 'collate a list of masked LM samples into a mini-batch with source tokens, segment labels, and LM targets', 'get a single sample from the MaskedLMDataset returning block one, block two, and sentence target', 'return ordered indices for batching the MaskedLMDataset either shuffled or sorted by size', 'create a MaskedLMDictionary instance with pad, eos, unk, and mask special symbols for masked language modeling', 'get the integer index of the mask symbol from a MaskedLMDictionary using the mask method', 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep special symbols for BERT tasks', 'get the integer index of the cls or sep symbol from a BertDictionary using the cls or sep method', 'review the MaskedLMDictionary class and its mask symbol handling for masked language modeling tasks']
```

Usage

```
{'create_masked_lm_dataset': 'create a MaskedLMDataset wrapping a TokenBlockDataset or BlockPairDataset for masked language model training', 'mask_block_tokens': 'mask tokens in a sentence block using the BERT-style masking strategy with mask, random, and original token probabilities', 'collate_masked_lm_batch': 'collate a list of masked LM samples into a mini-batch with source tokens, segment labels, and LM targets', 'get_masked_lm_sample': 'get a single sample from the MaskedLMDataset returning block one, block two, and sentence target', 'order_masked_lm_indices': 'return ordered indices for batching the MaskedLMDataset either shuffled or sorted by size'}
```

## File: facebookresearch_mega/fairseq/data/legacy/masked_lm_dictionary.py

Prompts

```
['create a BlockPairDataset that breaks tokens into sentence pairs respecting document boundaries for next sentence prediction', 'create a BlockPairDataset with break_mode none to cut tokens evenly without respecting document boundaries', 'review the BlockPairDataset _generate_sentence_pair method that creates sentence pairs from a single document chunk', 'review the BlockPairDataset _truncate_sentences method that truncates sentence pairs to fit max token limits', 'summarize the BlockPairDataset _pair_sentences method that pairs sentences with 50 percent consecutive and 50 percent random', 'create a MaskedLMDataset wrapping a TokenBlockDataset or BlockPairDataset for masked language model training', 'mask tokens in a sentence block using the BERT-style masking strategy with mask, random, and original token probabilities', 'collate a list of masked LM samples into a mini-batch with source tokens, segment labels, and LM targets', 'get a single sample from the MaskedLMDataset returning block one, block two, and sentence target', 'return ordered indices for batching the MaskedLMDataset either shuffled or sorted by size', 'create a MaskedLMDictionary instance with pad, eos, unk, and mask special symbols for masked language modeling', 'get the integer index of the mask symbol from a MaskedLMDictionary using the mask method', 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep special symbols for BERT tasks', 'get the integer index of the cls or sep symbol from a BertDictionary using the cls or sep method', 'review the MaskedLMDictionary class and its mask symbol handling for masked language modeling tasks']
```

Usage

```
{'create_masked_lm_dictionary': 'create a MaskedLMDictionary instance with pad, eos, unk, and mask special symbols for masked language modeling', 'get_mask_index': 'get the integer index of the mask symbol from a MaskedLMDictionary using the mask method', 'create_bert_dictionary': 'create a BertDictionary instance with pad, eos, unk, mask, cls, and sep special symbols for BERT tasks', 'get_cls_sep_index': 'get the integer index of the cls or sep symbol from a BertDictionary using the cls or sep method', 'review_masked_lm_dictionary_class': 'review the MaskedLMDictionary class and its mask symbol handling for masked language modeling tasks'}
```

