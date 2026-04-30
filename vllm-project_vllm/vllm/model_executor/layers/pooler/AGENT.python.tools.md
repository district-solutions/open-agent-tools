# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/abstract.py

Prompts

```
['create a Pooler subclass that implements get_supported_tasks and forward methods', 'build a Pooler forward pass that takes hidden_states and PoolingMetadata to produce PoolerOutput', 'test the Pooler.get_supported_tasks method returns a Set of PoolingTask values', 'review the Pooler.get_pooling_updates method that constructs updated pooling parameters for a task', 'summarize the Pooler abstract class interface for pooling models in vLLM', 'get an activation function from a transformers PretrainedConfig based on problem_type', 'resolve a classifier activation function from a vLLM ModelConfig', 'create a PoolerActivation subclass with a forward_chunk method for tensor transformations', 'build a PoolerClassify instance that applies softmax or sigmoid based on num_labels', 'wrap a torch.nn.Module as a PoolerActivation using PoolerActivation.wraps', 'create a PoolingParamsUpdate instance to enable requires_token_ids for a pooler', 'build combined PoolingParamsUpdate by OR-ing multiple updates together', 'test applying a PoolingParamsUpdate to mutate PoolingParams.requires_token_ids', 'review the ProjectorFn callable type alias for tensor-to-tensor projector functions', 'review the ClassifierFn callable type alias for tensor-to-tensor classifier functions', 'build a DispatchPooler for embedding tasks using pooler_for_token_embed and pooler_for_embed', 'build a DispatchPooler for sequence classification with custom pooling and classifier functions', 'create a BOSEOSFilter that removes BOS and EOS token outputs from pooled results', 'build a BgeM3Pooler that concatenates embed and token_classify pooler outputs', 'create an IdentityPooler that passes hidden states through unchanged']
```

Usage

```
{'create_pooler_subclass': 'create a Pooler subclass that implements get_supported_tasks and forward methods', 'build_pooling_forward': 'build a Pooler forward pass that takes hidden_states and PoolingMetadata to produce PoolerOutput', 'test_get_supported_tasks': 'test the Pooler.get_supported_tasks method returns a Set of PoolingTask values', 'review_pooling_updates': 'review the Pooler.get_pooling_updates method that constructs updated pooling parameters for a task', 'summarize_pooler_interface': 'summarize the Pooler abstract class interface for pooling models in vLLM'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/activations.py

Prompts

```
['create a Pooler subclass that implements get_supported_tasks and forward methods', 'build a Pooler forward pass that takes hidden_states and PoolingMetadata to produce PoolerOutput', 'test the Pooler.get_supported_tasks method returns a Set of PoolingTask values', 'review the Pooler.get_pooling_updates method that constructs updated pooling parameters for a task', 'summarize the Pooler abstract class interface for pooling models in vLLM', 'get an activation function from a transformers PretrainedConfig based on problem_type', 'resolve a classifier activation function from a vLLM ModelConfig', 'create a PoolerActivation subclass with a forward_chunk method for tensor transformations', 'build a PoolerClassify instance that applies softmax or sigmoid based on num_labels', 'wrap a torch.nn.Module as a PoolerActivation using PoolerActivation.wraps', 'create a PoolingParamsUpdate instance to enable requires_token_ids for a pooler', 'build combined PoolingParamsUpdate by OR-ing multiple updates together', 'test applying a PoolingParamsUpdate to mutate PoolingParams.requires_token_ids', 'review the ProjectorFn callable type alias for tensor-to-tensor projector functions', 'review the ClassifierFn callable type alias for tensor-to-tensor classifier functions', 'build a DispatchPooler for embedding tasks using pooler_for_token_embed and pooler_for_embed', 'build a DispatchPooler for sequence classification with custom pooling and classifier functions', 'create a BOSEOSFilter that removes BOS and EOS token outputs from pooled results', 'build a BgeM3Pooler that concatenates embed and token_classify pooler outputs', 'create an IdentityPooler that passes hidden states through unchanged']
```

Usage

```
{'get_act_fn': 'get an activation function from a transformers PretrainedConfig based on problem_type', 'resolve_classifier_act_fn': 'resolve a classifier activation function from a vLLM ModelConfig', 'create_PoolerActivation': 'create a PoolerActivation subclass with a forward_chunk method for tensor transformations', 'build_PoolerClassify': 'build a PoolerClassify instance that applies softmax or sigmoid based on num_labels', 'wrap_torch_module': 'wrap a torch.nn.Module as a PoolerActivation using PoolerActivation.wraps'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/common.py

Prompts

```
['create a Pooler subclass that implements get_supported_tasks and forward methods', 'build a Pooler forward pass that takes hidden_states and PoolingMetadata to produce PoolerOutput', 'test the Pooler.get_supported_tasks method returns a Set of PoolingTask values', 'review the Pooler.get_pooling_updates method that constructs updated pooling parameters for a task', 'summarize the Pooler abstract class interface for pooling models in vLLM', 'get an activation function from a transformers PretrainedConfig based on problem_type', 'resolve a classifier activation function from a vLLM ModelConfig', 'create a PoolerActivation subclass with a forward_chunk method for tensor transformations', 'build a PoolerClassify instance that applies softmax or sigmoid based on num_labels', 'wrap a torch.nn.Module as a PoolerActivation using PoolerActivation.wraps', 'create a PoolingParamsUpdate instance to enable requires_token_ids for a pooler', 'build combined PoolingParamsUpdate by OR-ing multiple updates together', 'test applying a PoolingParamsUpdate to mutate PoolingParams.requires_token_ids', 'review the ProjectorFn callable type alias for tensor-to-tensor projector functions', 'review the ClassifierFn callable type alias for tensor-to-tensor classifier functions', 'build a DispatchPooler for embedding tasks using pooler_for_token_embed and pooler_for_embed', 'build a DispatchPooler for sequence classification with custom pooling and classifier functions', 'create a BOSEOSFilter that removes BOS and EOS token outputs from pooled results', 'build a BgeM3Pooler that concatenates embed and token_classify pooler outputs', 'create an IdentityPooler that passes hidden states through unchanged']
```

Usage

```
{'create_PoolingParamsUpdate': 'create a PoolingParamsUpdate instance to enable requires_token_ids for a pooler', 'build_PoolingParamsUpdate_combine': 'build combined PoolingParamsUpdate by OR-ing multiple updates together', 'test_PoolingParamsUpdate_apply': 'test applying a PoolingParamsUpdate to mutate PoolingParams.requires_token_ids', 'review_ProjectorFn': 'review the ProjectorFn callable type alias for tensor-to-tensor projector functions', 'review_ClassifierFn': 'review the ClassifierFn callable type alias for tensor-to-tensor classifier functions'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/pooler/special.py

Prompts

```
['create a Pooler subclass that implements get_supported_tasks and forward methods', 'build a Pooler forward pass that takes hidden_states and PoolingMetadata to produce PoolerOutput', 'test the Pooler.get_supported_tasks method returns a Set of PoolingTask values', 'review the Pooler.get_pooling_updates method that constructs updated pooling parameters for a task', 'summarize the Pooler abstract class interface for pooling models in vLLM', 'get an activation function from a transformers PretrainedConfig based on problem_type', 'resolve a classifier activation function from a vLLM ModelConfig', 'create a PoolerActivation subclass with a forward_chunk method for tensor transformations', 'build a PoolerClassify instance that applies softmax or sigmoid based on num_labels', 'wrap a torch.nn.Module as a PoolerActivation using PoolerActivation.wraps', 'create a PoolingParamsUpdate instance to enable requires_token_ids for a pooler', 'build combined PoolingParamsUpdate by OR-ing multiple updates together', 'test applying a PoolingParamsUpdate to mutate PoolingParams.requires_token_ids', 'review the ProjectorFn callable type alias for tensor-to-tensor projector functions', 'review the ClassifierFn callable type alias for tensor-to-tensor classifier functions', 'build a DispatchPooler for embedding tasks using pooler_for_token_embed and pooler_for_embed', 'build a DispatchPooler for sequence classification with custom pooling and classifier functions', 'create a BOSEOSFilter that removes BOS and EOS token outputs from pooled results', 'build a BgeM3Pooler that concatenates embed and token_classify pooler outputs', 'create an IdentityPooler that passes hidden states through unchanged']
```

Usage

```
{'build_DispatchPooler_for_embedding': 'build a DispatchPooler for embedding tasks using pooler_for_token_embed and pooler_for_embed', 'build_DispatchPooler_for_seq_cls': 'build a DispatchPooler for sequence classification with custom pooling and classifier functions', 'create_BOSEOSFilter': 'create a BOSEOSFilter that removes BOS and EOS token outputs from pooled results', 'build_BgeM3Pooler': 'build a BgeM3Pooler that concatenates embed and token_classify pooler outputs', 'create_IdentityPooler': 'create an IdentityPooler that passes hidden states through unchanged'}
```

