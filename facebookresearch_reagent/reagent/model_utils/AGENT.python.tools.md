# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/model_utils/seq2slate_utils.py

Prompts

```
['print the parameter count for each component of a Seq2Slate model including encoder, decoder, and embedder', 'mask logits by target indices to exclude padding, start symbols, and already-selected candidates', 'create a subsequent position mask tensor to prevent attending to future items during decoding', 'produce N identical deep copies of a PyTorch nn.Module as an nn.ModuleList', 'compute scaled dot-product attention with optional masking over query, key, and value tensors']
```

Usage

```
{'print_model_info': 'print the parameter count for each component of a Seq2Slate model including encoder, decoder, and embedder', 'mask_logits_by_idx': 'mask logits by target indices to exclude padding, start symbols, and already-selected candidates', 'subsequent_mask': 'create a subsequent position mask tensor to prevent attending to future items during decoding', 'clones': 'produce N identical deep copies of a PyTorch nn.Module as an nn.ModuleList', 'attention': 'compute scaled dot-product attention with optional masking over query, key, and value tensors'}
```

