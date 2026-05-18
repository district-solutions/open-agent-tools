# Agent Python Tools

- repo: facebookresearch/neuraldb
- repo_uri: https://github.com/facebookresearch/neuraldb

## File: facebookresearch_neuraldb/modelling/src/neuraldb/dataset/instance_generator/instance_generator.py

Prompts

```
['generate training instances from a database dict by calling InstanceGenerator.generate with database and optional index', 'encode a query context example dict into tokenized input_ids and labels using InstanceGenerator.encode', 'encode an example with multiple context passages separately using InstanceGenerator.fusion_encode for multi-passage models', 'concatenate a list of context token lists into one with context delimiter separators using InstanceGenerator.concatenate_context', 'tokenize an answer string into tokens using special tokens for TRUE FALSE or null via InstanceGenerator.maybe_tokenize_answer', 'create a Subsampler instance with a dictionary mapping query types to sample rates', 'use maybe_drop_sample to probabilistically decide whether to keep a query based on its type', 'configure sample rates per query type as a float or a three-element list for true/false/empty answers', 'filter a list of queries by calling maybe_drop_sample on each and keeping only those returned as true', 'review the Subsampler class and its maybe_drop_sample method to understand the probabilistic sampling logic']
```

Usage

```
{'generate_instances_from_database': 'generate training instances from a database dict by calling InstanceGenerator.generate with database and optional index', 'encode_example_for_model': 'encode a query context example dict into tokenized input_ids and labels using InstanceGenerator.encode', 'fuse_encode_multiple_contexts': 'encode an example with multiple context passages separately using InstanceGenerator.fusion_encode for multi-passage models', 'concatenate_context_with_delimiters': 'concatenate a list of context token lists into one with context delimiter separators using InstanceGenerator.concatenate_context', 'tokenize_answer_with_special_tokens': 'tokenize an answer string into tokens using special tokens for TRUE FALSE or null via InstanceGenerator.maybe_tokenize_answer'}
```

## File: facebookresearch_neuraldb/modelling/src/neuraldb/dataset/instance_generator/subsampler.py

Prompts

```
['generate training instances from a database dict by calling InstanceGenerator.generate with database and optional index', 'encode a query context example dict into tokenized input_ids and labels using InstanceGenerator.encode', 'encode an example with multiple context passages separately using InstanceGenerator.fusion_encode for multi-passage models', 'concatenate a list of context token lists into one with context delimiter separators using InstanceGenerator.concatenate_context', 'tokenize an answer string into tokens using special tokens for TRUE FALSE or null via InstanceGenerator.maybe_tokenize_answer', 'create a Subsampler instance with a dictionary mapping query types to sample rates', 'use maybe_drop_sample to probabilistically decide whether to keep a query based on its type', 'configure sample rates per query type as a float or a three-element list for true/false/empty answers', 'filter a list of queries by calling maybe_drop_sample on each and keeping only those returned as true', 'review the Subsampler class and its maybe_drop_sample method to understand the probabilistic sampling logic']
```

Usage

```
{'create_subsampler': 'create a Subsampler instance with a dictionary mapping query types to sample rates', 'use_maybe_drop_sample': 'use maybe_drop_sample to probabilistically decide whether to keep a query based on its type', 'configure_sample_rates_per_type': 'configure sample rates per query type as a float or a three-element list for true/false/empty answers', 'filter_queries_with_subsampler': 'filter a list of queries by calling maybe_drop_sample on each and keeping only those returned as true', 'review_subsampler_logic': 'review the Subsampler class and its maybe_drop_sample method to understand the probabilistic sampling logic'}
```

