# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/parlai_diplomacy/agents/prefix_generation/agents.py

Prompts

```
['generate text using beam search with prefix tokens that must begin the decoded sequence', 'vectorize prefix text into token IDs using the dictionary txt2vec method for conditioning generation', 'batchify observations into a Batch structure that includes prefix_vecs for each example in the batch', 'get prefix tokens from a Batch object to seed decoding for each sample in the batch', 'register a BART agent with prefix generation support using the bart_prefix name for ParlAI']
```

Usage

```
{'generate_with_prefix_beam_search': 'generate text using beam search with prefix tokens that must begin the decoded sequence', 'vectorize_prefix_tokens': 'vectorize prefix text into token IDs using the dictionary txt2vec method for conditioning generation', 'batchify_with_prefix_vecs': 'batchify observations into a Batch structure that includes prefix_vecs for each example in the batch', 'get_prefix_tokens_from_batch': 'get prefix tokens from a Batch object to seed decoding for each sample in the batch', 'register_bart_prefix_agent': 'register a BART agent with prefix generation support using the bart_prefix name for ParlAI'}
```

