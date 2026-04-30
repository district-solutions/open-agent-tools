# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/seqwise/heads.py

Prompts

```
['create an EmbeddingPoolerHead with optional projector, head_dtype, and activation for embedding generation', 'create a ClassifierPoolerHead with optional classifier, logit_mean, logit_sigma, head_dtype, and activation for classification', 'build a SequencePoolerHead abstract base class defining get_supported_tasks and forward interface', 'test the EmbeddingPoolerHead forward method with pooled_data and pooling_metadata producing embeddings', 'review the ClassifierPoolerHead forward method applying affine score calibration and activation to logits', 'create a sequence pooling method from a pooling type string like CLS, LAST, or MEAN', 'build a CLS pooling method that extracts the first token hidden states for each sequence', 'build a LAST pooling method that extracts the last token hidden states for each sequence', 'build a MEAN pooling method that computes per-sequence mean of hidden states with chunked accumulation', 'review the abstract SequencePoolingMethod base class with forward and supported tasks methods', 'create a SequencePooler instance with a pooling method and head for sequence-level pooling', 'build an embedding pooler from a PoolerConfig that normalizes pooled embeddings', 'build a classifier pooler from a PoolerConfig with optional pooling, classifier, and activation functions', 'test the SequencePooler forward method that applies pooling then head postprocessing to hidden states', 'review the SequencePooler get_supported_tasks method that intersects supported tasks from pooling and head']
```

Usage

```
{'create_EmbeddingPoolerHead': 'create an EmbeddingPoolerHead with optional projector, head_dtype, and activation for embedding generation', 'create_ClassifierPoolerHead': 'create a ClassifierPoolerHead with optional classifier, logit_mean, logit_sigma, head_dtype, and activation for classification', 'build_SquencePoolerHead': 'build a SequencePoolerHead abstract base class defining get_supported_tasks and forward interface', 'test_EmbeddingPoolerHead_forward': 'test the EmbeddingPoolerHead forward method with pooled_data and pooling_metadata producing embeddings', 'review_ClassifierPoolerHead_forward': 'review the ClassifierPoolerHead forward method applying affine score calibration and activation to logits'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/seqwise/methods.py

Prompts

```
['create an EmbeddingPoolerHead with optional projector, head_dtype, and activation for embedding generation', 'create a ClassifierPoolerHead with optional classifier, logit_mean, logit_sigma, head_dtype, and activation for classification', 'build a SequencePoolerHead abstract base class defining get_supported_tasks and forward interface', 'test the EmbeddingPoolerHead forward method with pooled_data and pooling_metadata producing embeddings', 'review the ClassifierPoolerHead forward method applying affine score calibration and activation to logits', 'create a sequence pooling method from a pooling type string like CLS, LAST, or MEAN', 'build a CLS pooling method that extracts the first token hidden states for each sequence', 'build a LAST pooling method that extracts the last token hidden states for each sequence', 'build a MEAN pooling method that computes per-sequence mean of hidden states with chunked accumulation', 'review the abstract SequencePoolingMethod base class with forward and supported tasks methods', 'create a SequencePooler instance with a pooling method and head for sequence-level pooling', 'build an embedding pooler from a PoolerConfig that normalizes pooled embeddings', 'build a classifier pooler from a PoolerConfig with optional pooling, classifier, and activation functions', 'test the SequencePooler forward method that applies pooling then head postprocessing to hidden states', 'review the SequencePooler get_supported_tasks method that intersects supported tasks from pooling and head']
```

Usage

```
{'create_pooling_method': 'create a sequence pooling method from a pooling type string like CLS, LAST, or MEAN', 'build_cls_pool': 'build a CLS pooling method that extracts the first token hidden states for each sequence', 'build_last_pool': 'build a LAST pooling method that extracts the last token hidden states for each sequence', 'build_mean_pool': 'build a MEAN pooling method that computes per-sequence mean of hidden states with chunked accumulation', 'review_sequence_pooling_method': 'review the abstract SequencePoolingMethod base class with forward and supported tasks methods'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/seqwise/poolers.py

Prompts

```
['create an EmbeddingPoolerHead with optional projector, head_dtype, and activation for embedding generation', 'create a ClassifierPoolerHead with optional classifier, logit_mean, logit_sigma, head_dtype, and activation for classification', 'build a SequencePoolerHead abstract base class defining get_supported_tasks and forward interface', 'test the EmbeddingPoolerHead forward method with pooled_data and pooling_metadata producing embeddings', 'review the ClassifierPoolerHead forward method applying affine score calibration and activation to logits', 'create a sequence pooling method from a pooling type string like CLS, LAST, or MEAN', 'build a CLS pooling method that extracts the first token hidden states for each sequence', 'build a LAST pooling method that extracts the last token hidden states for each sequence', 'build a MEAN pooling method that computes per-sequence mean of hidden states with chunked accumulation', 'review the abstract SequencePoolingMethod base class with forward and supported tasks methods', 'create a SequencePooler instance with a pooling method and head for sequence-level pooling', 'build an embedding pooler from a PoolerConfig that normalizes pooled embeddings', 'build a classifier pooler from a PoolerConfig with optional pooling, classifier, and activation functions', 'test the SequencePooler forward method that applies pooling then head postprocessing to hidden states', 'review the SequencePooler get_supported_tasks method that intersects supported tasks from pooling and head']
```

Usage

```
{'create_SequencePooler': 'create a SequencePooler instance with a pooling method and head for sequence-level pooling', 'build_pooler_for_embed': 'build an embedding pooler from a PoolerConfig that normalizes pooled embeddings', 'build_pooler_for_classify': 'build a classifier pooler from a PoolerConfig with optional pooling, classifier, and activation functions', 'test_SequencePooler_forward': 'test the SequencePooler forward method that applies pooling then head postprocessing to hidden states', 'review_SequencePooler_get_supported_tasks': 'review the SequencePooler get_supported_tasks method that intersects supported tasks from pooling and head'}
```

