# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/pooling/base/io_processor.py

Prompts

```
['create pooling params from a request using request.to_pooling_params()', 'preprocess online pooling requests for chat or completion formats into engine inputs', 'preprocess offline batch pooling prompts into engine inputs with tokenization parameters', 'postprocess offline pooling outputs into a list of pooling request outputs', 'validate chat template safety by checking trust-request-chat-template flag before use', 'create a pooling basic request mixin with model, user, priority, and cache_salt parameters', 'create a completion request mixin with input tokens and add_special_tokens option', 'create a chat request mixin with messages, chat template, and generation prompt parameters', 'build chat params from chat request mixin using default template and content format', 'create an embed request mixin with encoding format, dimensions, and dtype options', 'create a classify request mixin with activation option for pooler outputs', 'create a PoolingServingBase instance with an engine client, models, and request logger for pooling inference', 'run a pooling request through the serving base to preprocess, encode, and postprocess embeddings', 'build a PoolingIOProcessor subclass to handle request preprocessing and postprocessing for pooling tasks', "test whether a given model name is supported by the serving base's model registry", "validate pooling request parameters such as truncate_prompt_tokens against the model's max_model_len"]
```

Usage

```
{'create_pooling_params': 'create pooling params from a request using request.to_pooling_params()', 'pre_process_online': 'preprocess online pooling requests for chat or completion formats into engine inputs', 'pre_process_offline': 'preprocess offline batch pooling prompts into engine inputs with tokenization parameters', 'post_process_offline': 'postprocess offline pooling outputs into a list of pooling request outputs', 'validate_chat_template': 'validate chat template safety by checking trust-request-chat-template flag before use'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/base/protocol.py

Prompts

```
['create pooling params from a request using request.to_pooling_params()', 'preprocess online pooling requests for chat or completion formats into engine inputs', 'preprocess offline batch pooling prompts into engine inputs with tokenization parameters', 'postprocess offline pooling outputs into a list of pooling request outputs', 'validate chat template safety by checking trust-request-chat-template flag before use', 'create a pooling basic request mixin with model, user, priority, and cache_salt parameters', 'create a completion request mixin with input tokens and add_special_tokens option', 'create a chat request mixin with messages, chat template, and generation prompt parameters', 'build chat params from chat request mixin using default template and content format', 'create an embed request mixin with encoding format, dimensions, and dtype options', 'create a classify request mixin with activation option for pooler outputs', 'create a PoolingServingBase instance with an engine client, models, and request logger for pooling inference', 'run a pooling request through the serving base to preprocess, encode, and postprocess embeddings', 'build a PoolingIOProcessor subclass to handle request preprocessing and postprocessing for pooling tasks', "test whether a given model name is supported by the serving base's model registry", "validate pooling request parameters such as truncate_prompt_tokens against the model's max_model_len"]
```

Usage

```
{'create_pooling_request': 'create a pooling basic request mixin with model, user, priority, and cache_salt parameters', 'create_completion_request': 'create a completion request mixin with input tokens and add_special_tokens option', 'create_chat_request': 'create a chat request mixin with messages, chat template, and generation prompt parameters', 'build_chat_params': 'build chat params from chat request mixin using default template and content format', 'create_embed_request': 'create an embed request mixin with encoding format, dimensions, and dtype options', 'create_classify_request': 'create a classify request mixin with activation option for pooler outputs'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/base/serving.py

Prompts

```
['create pooling params from a request using request.to_pooling_params()', 'preprocess online pooling requests for chat or completion formats into engine inputs', 'preprocess offline batch pooling prompts into engine inputs with tokenization parameters', 'postprocess offline pooling outputs into a list of pooling request outputs', 'validate chat template safety by checking trust-request-chat-template flag before use', 'create a pooling basic request mixin with model, user, priority, and cache_salt parameters', 'create a completion request mixin with input tokens and add_special_tokens option', 'create a chat request mixin with messages, chat template, and generation prompt parameters', 'build chat params from chat request mixin using default template and content format', 'create an embed request mixin with encoding format, dimensions, and dtype options', 'create a classify request mixin with activation option for pooler outputs', 'create a PoolingServingBase instance with an engine client, models, and request logger for pooling inference', 'run a pooling request through the serving base to preprocess, encode, and postprocess embeddings', 'build a PoolingIOProcessor subclass to handle request preprocessing and postprocessing for pooling tasks', "test whether a given model name is supported by the serving base's model registry", "validate pooling request parameters such as truncate_prompt_tokens against the model's max_model_len"]
```

Usage

```
{'create_pooling_serving_instance': 'create a PoolingServingBase instance with an engine client, models, and request logger for pooling inference', 'run_pooling_request': 'run a pooling request through the serving base to preprocess, encode, and postprocess embeddings', 'build_pooling_io_processor': 'build a PoolingIOProcessor subclass to handle request preprocessing and postprocessing for pooling tasks', 'test_model_support': "test whether a given model name is supported by the serving base's model registry", 'validate_request_parameters': "validate pooling request parameters such as truncate_prompt_tokens against the model's max_model_len"}
```

