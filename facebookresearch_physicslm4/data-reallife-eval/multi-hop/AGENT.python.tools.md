# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/data-reallife-eval/multi-hop/multihop-birthyear.py

Prompts

```
['generate a multi-hop birth year retrieval sample with N people, k hops, and M background tokens', 'create a MultiHopTaskGenerator instance with a HuggingFace tokenizer for birth year retrieval tasks', 'reset the random seed to 42 in MultiHopTaskGenerator for reproducible task generation', 'generate multi-hop task sentences linking N people across k hops with birth year facts', 'interleave background wiki sentences with problem sentences at random positions for noise injection']
```

Usage

```
{'generate_sample_multihop_task': 'generate a multi-hop birth year retrieval sample with N people, k hops, and M background tokens', 'create_MultiHopTaskGenerator': 'create a MultiHopTaskGenerator instance with a HuggingFace tokenizer for birth year retrieval tasks', 'reset_randomness_MultiHopTaskGenerator': 'reset the random seed to 42 in MultiHopTaskGenerator for reproducible task generation', 'generate_multi_hop_task_sentences': 'generate multi-hop task sentences linking N people across k hops with birth year facts', 'interleave_background_problem_sentences': 'interleave background wiki sentences with problem sentences at random positions for noise injection'}
```

