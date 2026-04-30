# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/pipelines/sequential/ast_helpers.py

Prompts

```
['autowrap the forward methods of a list of torch modules to remove untraceable code patterns', 'autowrap the forward method of a single torch module to replace untraceable code with torch.fx wrappers', 'append autowrapped source lines to exceptions when autowrapped forward code fails during execution', 'autowrap forward methods of modules while ignoring specified function names from wrapping', 'autowrap a module forward and raise ValueError when the module lacks an implemented forward method', 'trace a pretrained model to produce executable subgraphs for sequential calibration', 'create a dataclass specifying an executable subgraph of a model graph with input and consumed names', 'dispatch a model for sequential calibration with configurable onload and offload devices', 'wrap a function to catch out-of-memory errors and suggest smaller sequential targets', 'partition a traced model graph into a list of subgraphs for sequential execution', 'symbolic_trace a transformers PreTrainedModel and return a torch.fx GraphModule for analysis', 'check_if_model_supported a transformers PreTrainedModel and raise if the model type is not in the supported list', 'get_concrete_args from a model forward signature by filtering out the specified input names', 'trace a PreTrainedModel using HFTracer to record operations and handle data-dependent control flow', 'create proxyable cache classes for Cache, DynamicCache, and StaticCache to enable FX tracing of KV cache usage']
```

Usage

```
{'autowrap_forwards_modules': 'autowrap the forward methods of a list of torch modules to remove untraceable code patterns', 'autowrap_forward_module': 'autowrap the forward method of a single torch module to replace untraceable code with torch.fx wrappers', 'append_autowrap_source_on_fail': 'append autowrapped source lines to exceptions when autowrapped forward code fails during execution', 'autowrap_forwards_ignore': 'autowrap forward methods of modules while ignoring specified function names from wrapping', 'autowrap_forward_validate': 'autowrap a module forward and raise ValueError when the module lacks an implemented forward method'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/pipelines/sequential/helpers.py

Prompts

```
['autowrap the forward methods of a list of torch modules to remove untraceable code patterns', 'autowrap the forward method of a single torch module to replace untraceable code with torch.fx wrappers', 'append autowrapped source lines to exceptions when autowrapped forward code fails during execution', 'autowrap forward methods of modules while ignoring specified function names from wrapping', 'autowrap a module forward and raise ValueError when the module lacks an implemented forward method', 'trace a pretrained model to produce executable subgraphs for sequential calibration', 'create a dataclass specifying an executable subgraph of a model graph with input and consumed names', 'dispatch a model for sequential calibration with configurable onload and offload devices', 'wrap a function to catch out-of-memory errors and suggest smaller sequential targets', 'partition a traced model graph into a list of subgraphs for sequential execution', 'symbolic_trace a transformers PreTrainedModel and return a torch.fx GraphModule for analysis', 'check_if_model_supported a transformers PreTrainedModel and raise if the model type is not in the supported list', 'get_concrete_args from a model forward signature by filtering out the specified input names', 'trace a PreTrainedModel using HFTracer to record operations and handle data-dependent control flow', 'create proxyable cache classes for Cache, DynamicCache, and StaticCache to enable FX tracing of KV cache usage']
```

Usage

```
{'trace_subgraphs': 'trace a pretrained model to produce executable subgraphs for sequential calibration', 'create_Subgraph': 'create a dataclass specifying an executable subgraph of a model graph with input and consumed names', 'dispatch_for_sequential': 'dispatch a model for sequential calibration with configurable onload and offload devices', 'handle_sequential_oom': 'wrap a function to catch out-of-memory errors and suggest smaller sequential targets', 'partition_graph': 'partition a traced model graph into a list of subgraphs for sequential execution'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/pipelines/sequential/transformers_helpers.py

Prompts

```
['autowrap the forward methods of a list of torch modules to remove untraceable code patterns', 'autowrap the forward method of a single torch module to replace untraceable code with torch.fx wrappers', 'append autowrapped source lines to exceptions when autowrapped forward code fails during execution', 'autowrap forward methods of modules while ignoring specified function names from wrapping', 'autowrap a module forward and raise ValueError when the module lacks an implemented forward method', 'trace a pretrained model to produce executable subgraphs for sequential calibration', 'create a dataclass specifying an executable subgraph of a model graph with input and consumed names', 'dispatch a model for sequential calibration with configurable onload and offload devices', 'wrap a function to catch out-of-memory errors and suggest smaller sequential targets', 'partition a traced model graph into a list of subgraphs for sequential execution', 'symbolic_trace a transformers PreTrainedModel and return a torch.fx GraphModule for analysis', 'check_if_model_supported a transformers PreTrainedModel and raise if the model type is not in the supported list', 'get_concrete_args from a model forward signature by filtering out the specified input names', 'trace a PreTrainedModel using HFTracer to record operations and handle data-dependent control flow', 'create proxyable cache classes for Cache, DynamicCache, and StaticCache to enable FX tracing of KV cache usage']
```

Usage

```
{'symbolic_trace_model': 'symbolic_trace a transformers PreTrainedModel and return a torch.fx GraphModule for analysis', 'check_if_model_supported': 'check_if_model_supported a transformers PreTrainedModel and raise if the model type is not in the supported list', 'get_concrete_args': 'get_concrete_args from a model forward signature by filtering out the specified input names', 'trace_model_with_hftracer': 'trace a PreTrainedModel using HFTracer to record operations and handle data-dependent control flow', 'create_proxyable_cache_classes': 'create proxyable cache classes for Cache, DynamicCache, and StaticCache to enable FX tracing of KV cache usage'}
```

