# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/tokwise/heads.py

Prompts

```
['create a TokenEmbeddingPoolerHead with optional projector, activation, and head dtype', 'create a TokenClassifierPoolerHead with classifier, logit calibration, and activation', 'build token pooler forward pass over a list of pooled data items and metadata', 'test the TokenEmbeddingPoolerHead forward_chunk with pooled data and pooling params', 'test the TokenClassifierPoolerHead forward_chunk with logit calibration and activation', 'create a token pooling method from a pooling type string or enum, returning AllPool or StepPool', 'build AllPool forward to extract hidden state slices per request using pooling metadata cursor indices', 'build StepPool forward to filter pooled hidden states by returned token ids and step tag id', 'test TokenPoolingMethod get_supported_tasks returns a set containing token_embed and token_classify', 'review TokenPoolingMethod get_pooling_updates and StepPool override that requires token ids', 'create a TokenPooler instance with a pooling method and optional head for token-level pooling', 'build a token embedding pooler from a PoolerConfig with an optional projector function', 'build a token classification pooler from a PoolerConfig with optional classifier and activation function', 'test the TokenPooler forward method with hidden states and pooling metadata', 'review the TokenPooler get_supported_tasks method to determine compatible pooling tasks']
```

Usage

```
{'create_TokenEmbeddingPoolerHead': 'create a TokenEmbeddingPoolerHead with optional projector, activation, and head dtype', 'create_TokenClassifierPoolerHead': 'create a TokenClassifierPoolerHead with classifier, logit calibration, and activation', 'build_TokenPoolerHead_forward': 'build token pooler forward pass over a list of pooled data items and metadata', 'test_TokenEmbeddingPoolerHead_forward_chunk': 'test the TokenEmbeddingPoolerHead forward_chunk with pooled data and pooling params', 'test_TokenClassifierPoolerHead_forward_chunk': 'test the TokenClassifierPoolerHead forward_chunk with logit calibration and activation'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/tokwise/methods.py

Prompts

```
['create a TokenEmbeddingPoolerHead with optional projector, activation, and head dtype', 'create a TokenClassifierPoolerHead with classifier, logit calibration, and activation', 'build token pooler forward pass over a list of pooled data items and metadata', 'test the TokenEmbeddingPoolerHead forward_chunk with pooled data and pooling params', 'test the TokenClassifierPoolerHead forward_chunk with logit calibration and activation', 'create a token pooling method from a pooling type string or enum, returning AllPool or StepPool', 'build AllPool forward to extract hidden state slices per request using pooling metadata cursor indices', 'build StepPool forward to filter pooled hidden states by returned token ids and step tag id', 'test TokenPoolingMethod get_supported_tasks returns a set containing token_embed and token_classify', 'review TokenPoolingMethod get_pooling_updates and StepPool override that requires token ids', 'create a TokenPooler instance with a pooling method and optional head for token-level pooling', 'build a token embedding pooler from a PoolerConfig with an optional projector function', 'build a token classification pooler from a PoolerConfig with optional classifier and activation function', 'test the TokenPooler forward method with hidden states and pooling metadata', 'review the TokenPooler get_supported_tasks method to determine compatible pooling tasks']
```

Usage

```
{'create_get_tok_pooling_method': 'create a token pooling method from a pooling type string or enum, returning AllPool or StepPool', 'build_AllPool_forward': 'build AllPool forward to extract hidden state slices per request using pooling metadata cursor indices', 'build_StepPool_forward': 'build StepPool forward to filter pooled hidden states by returned token ids and step tag id', 'test_get_supported_tasks': 'test TokenPoolingMethod get_supported_tasks returns a set containing token_embed and token_classify', 'review_get_pooling_updates': 'review TokenPoolingMethod get_pooling_updates and StepPool override that requires token ids'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/tokwise/poolers.py

Prompts

```
['create a TokenEmbeddingPoolerHead with optional projector, activation, and head dtype', 'create a TokenClassifierPoolerHead with classifier, logit calibration, and activation', 'build token pooler forward pass over a list of pooled data items and metadata', 'test the TokenEmbeddingPoolerHead forward_chunk with pooled data and pooling params', 'test the TokenClassifierPoolerHead forward_chunk with logit calibration and activation', 'create a token pooling method from a pooling type string or enum, returning AllPool or StepPool', 'build AllPool forward to extract hidden state slices per request using pooling metadata cursor indices', 'build StepPool forward to filter pooled hidden states by returned token ids and step tag id', 'test TokenPoolingMethod get_supported_tasks returns a set containing token_embed and token_classify', 'review TokenPoolingMethod get_pooling_updates and StepPool override that requires token ids', 'create a TokenPooler instance with a pooling method and optional head for token-level pooling', 'build a token embedding pooler from a PoolerConfig with an optional projector function', 'build a token classification pooler from a PoolerConfig with optional classifier and activation function', 'test the TokenPooler forward method with hidden states and pooling metadata', 'review the TokenPooler get_supported_tasks method to determine compatible pooling tasks']
```

Usage

```
{'create_TokenPooler': 'create a TokenPooler instance with a pooling method and optional head for token-level pooling', 'build_pooler_token_embed': 'build a token embedding pooler from a PoolerConfig with an optional projector function', 'build_pooler_token_classify': 'build a token classification pooler from a PoolerConfig with optional classifier and activation function', 'test_TokenPooler_forward': 'test the TokenPooler forward method with hidden states and pooling metadata', 'review_TokenPooler_get_supported_tasks': 'review the TokenPooler get_supported_tasks method to determine compatible pooling tasks'}
```

