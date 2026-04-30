# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/transformers/generation/stopping_criteria.py

Prompts

```
['patch MaxLengthCriteria.call to use token_idx for optimized Gaudi text generation stopping', 'patch MaxTimeCriteria.call to stop Gaudi text generation after a maximum time limit', 'patch EosTokenCriteria.call to detect EOS tokens per sequence on Gaudi hardware', 'patch StoppingCriteriaList.call to evaluate all stopping criteria with EOS-aware tensor output on Gaudi', 'check whether tensor output is needed based on ignore_eos and eos_token_id flags', 'generate text sequences using a HPU-optimized model with lazy mode and HPU graphs for accelerated inference', 'run beam search decoding on a HPU-optimized model with static shapes and bucketing support', 'run contrastive search generation with degeneration penalty and top-k candidate re-ranking on HPU', 'run assisted decoding with a candidate generator to accelerate token generation on HPU', 'run multinomial sampling or greedy search generation with HPU graphs and lazy mode optimizations']
```

Usage

```
{'gaudi_MaxLengthCriteria_call': 'patch MaxLengthCriteria.call to use token_idx for optimized Gaudi text generation stopping', 'gaudi_MaxTimeCriteria_call': 'patch MaxTimeCriteria.call to stop Gaudi text generation after a maximum time limit', 'gaudi_EosTokenCriteria_call': 'patch EosTokenCriteria.call to detect EOS tokens per sequence on Gaudi hardware', 'gaudi_StoppingCriteriaList_call': 'patch StoppingCriteriaList.call to evaluate all stopping criteria with EOS-aware tensor output on Gaudi', 'needs_tensor_output': 'check whether tensor output is needed based on ignore_eos and eos_token_id flags'}
```

## File: huggingface_optimum-habana/optimum/habana/transformers/generation/utils.py

Prompts

```
['patch MaxLengthCriteria.call to use token_idx for optimized Gaudi text generation stopping', 'patch MaxTimeCriteria.call to stop Gaudi text generation after a maximum time limit', 'patch EosTokenCriteria.call to detect EOS tokens per sequence on Gaudi hardware', 'patch StoppingCriteriaList.call to evaluate all stopping criteria with EOS-aware tensor output on Gaudi', 'check whether tensor output is needed based on ignore_eos and eos_token_id flags', 'generate text sequences using a HPU-optimized model with lazy mode and HPU graphs for accelerated inference', 'run beam search decoding on a HPU-optimized model with static shapes and bucketing support', 'run contrastive search generation with degeneration penalty and top-k candidate re-ranking on HPU', 'run assisted decoding with a candidate generator to accelerate token generation on HPU', 'run multinomial sampling or greedy search generation with HPU graphs and lazy mode optimizations']
```

Usage

```
{'generate_text_hpu': 'generate text sequences using a HPU-optimized model with lazy mode and HPU graphs for accelerated inference', 'run_beam_search_generation': 'run beam search decoding on a HPU-optimized model with static shapes and bucketing support', 'run_contrastive_search': 'run contrastive search generation with degeneration penalty and top-k candidate re-ranking on HPU', 'run_assisted_decoding': 'run assisted decoding with a candidate generator to accelerate token generation on HPU', 'run_sample_generation': 'run multinomial sampling or greedy search generation with HPU graphs and lazy mode optimizations'}
```

