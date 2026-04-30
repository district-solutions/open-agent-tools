# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/pooling/pooling/api_router.py

Prompts

```
['create a POST endpoint at /pooling that accepts a PoolingRequest and returns pooled embeddings', 'run the pooling handler from request app state to process embedding pooling requests', 'build a FastAPI router with a /pooling POST route that validates JSON and supports request cancellation', 'test the pooling dependency function that retrieves ServingPooling from request app state', 'review the create_pooling async function that delegates to the ServingPooling handler', 'build a PoolingIOProcessor subclass that initializes an io_processor from vllm_config and renderer', 'test the pre_process_online method that validates prompt data and renders completion engine inputs', 'test the post_process_online method that processes final result batches into IOProcessorResponse objects', 'test the pre_process_offline method that validates prompt data and converts pooling params to sequences', 'test the post_process_offline method that processes outputs into PoolingRequestOutput objects', 'build a PoolingCompletionRequest with task, embedding, and classification parameters for pooling models', 'build a PoolingChatRequest with chat messages and pooling task configuration for embedding generation', 'build a generic IOProcessorRequest with typed data and plugin pooling task for custom IO processing', 'create a PoolingResponse containing a list of PoolingResponseData with embeddings and usage info', 'build a PoolingBytesResponse with binary content and optional headers for byte-stream pooling output', 'create a ServingPooling instance with supported_tasks and vLLM configuration', 'verify a PoolingRequest task against supported tasks and raise errors for unsupported requests', 'build a JSONResponse from pooling outputs encoded as float or base64', 'get the appropriate IOProcessor for a given PoolingRequest based on its task']
```

Usage

```
{'create_pooling_endpoint': 'create a POST endpoint at /pooling that accepts a PoolingRequest and returns pooled embeddings', 'run_pooling_handler': 'run the pooling handler from request app state to process embedding pooling requests', 'build_pooling_router': 'build a FastAPI router with a /pooling POST route that validates JSON and supports request cancellation', 'test_pooling_dependency': 'test the pooling dependency function that retrieves ServingPooling from request app state', 'review_create_pooling': 'review the create_pooling async function that delegates to the ServingPooling handler'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/pooling/io_processor.py

Prompts

```
['create a POST endpoint at /pooling that accepts a PoolingRequest and returns pooled embeddings', 'run the pooling handler from request app state to process embedding pooling requests', 'build a FastAPI router with a /pooling POST route that validates JSON and supports request cancellation', 'test the pooling dependency function that retrieves ServingPooling from request app state', 'review the create_pooling async function that delegates to the ServingPooling handler', 'build a PoolingIOProcessor subclass that initializes an io_processor from vllm_config and renderer', 'test the pre_process_online method that validates prompt data and renders completion engine inputs', 'test the post_process_online method that processes final result batches into IOProcessorResponse objects', 'test the pre_process_offline method that validates prompt data and converts pooling params to sequences', 'test the post_process_offline method that processes outputs into PoolingRequestOutput objects', 'build a PoolingCompletionRequest with task, embedding, and classification parameters for pooling models', 'build a PoolingChatRequest with chat messages and pooling task configuration for embedding generation', 'build a generic IOProcessorRequest with typed data and plugin pooling task for custom IO processing', 'create a PoolingResponse containing a list of PoolingResponseData with embeddings and usage info', 'build a PoolingBytesResponse with binary content and optional headers for byte-stream pooling output', 'create a ServingPooling instance with supported_tasks and vLLM configuration', 'verify a PoolingRequest task against supported tasks and raise errors for unsupported requests', 'build a JSONResponse from pooling outputs encoded as float or base64', 'get the appropriate IOProcessor for a given PoolingRequest based on its task']
```

Usage

```
{'build_plugin_with_io_processor': 'build a PoolingIOProcessor subclass that initializes an io_processor from vllm_config and renderer', 'test_pre_process_online': 'test the pre_process_online method that validates prompt data and renders completion engine inputs', 'test_post_process_online': 'test the post_process_online method that processes final result batches into IOProcessorResponse objects', 'test_pre_process_offline': 'test the pre_process_offline method that validates prompt data and converts pooling params to sequences', 'test_post_process_offline': 'test the post_process_offline method that processes outputs into PoolingRequestOutput objects'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/pooling/protocol.py

Prompts

```
['create a POST endpoint at /pooling that accepts a PoolingRequest and returns pooled embeddings', 'run the pooling handler from request app state to process embedding pooling requests', 'build a FastAPI router with a /pooling POST route that validates JSON and supports request cancellation', 'test the pooling dependency function that retrieves ServingPooling from request app state', 'review the create_pooling async function that delegates to the ServingPooling handler', 'build a PoolingIOProcessor subclass that initializes an io_processor from vllm_config and renderer', 'test the pre_process_online method that validates prompt data and renders completion engine inputs', 'test the post_process_online method that processes final result batches into IOProcessorResponse objects', 'test the pre_process_offline method that validates prompt data and converts pooling params to sequences', 'test the post_process_offline method that processes outputs into PoolingRequestOutput objects', 'build a PoolingCompletionRequest with task, embedding, and classification parameters for pooling models', 'build a PoolingChatRequest with chat messages and pooling task configuration for embedding generation', 'build a generic IOProcessorRequest with typed data and plugin pooling task for custom IO processing', 'create a PoolingResponse containing a list of PoolingResponseData with embeddings and usage info', 'build a PoolingBytesResponse with binary content and optional headers for byte-stream pooling output', 'create a ServingPooling instance with supported_tasks and vLLM configuration', 'verify a PoolingRequest task against supported tasks and raise errors for unsupported requests', 'build a JSONResponse from pooling outputs encoded as float or base64', 'get the appropriate IOProcessor for a given PoolingRequest based on its task']
```

Usage

```
{'build_pooling_completion_request': 'build a PoolingCompletionRequest with task, embedding, and classification parameters for pooling models', 'build_pooling_chat_request': 'build a PoolingChatRequest with chat messages and pooling task configuration for embedding generation', 'build_io_processor_request': 'build a generic IOProcessorRequest with typed data and plugin pooling task for custom IO processing', 'create_pooling_response': 'create a PoolingResponse containing a list of PoolingResponseData with embeddings and usage info', 'build_pooling_bytes_response': 'build a PoolingBytesResponse with binary content and optional headers for byte-stream pooling output'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/pooling/serving.py

Prompts

```
['create a POST endpoint at /pooling that accepts a PoolingRequest and returns pooled embeddings', 'run the pooling handler from request app state to process embedding pooling requests', 'build a FastAPI router with a /pooling POST route that validates JSON and supports request cancellation', 'test the pooling dependency function that retrieves ServingPooling from request app state', 'review the create_pooling async function that delegates to the ServingPooling handler', 'build a PoolingIOProcessor subclass that initializes an io_processor from vllm_config and renderer', 'test the pre_process_online method that validates prompt data and renders completion engine inputs', 'test the post_process_online method that processes final result batches into IOProcessorResponse objects', 'test the pre_process_offline method that validates prompt data and converts pooling params to sequences', 'test the post_process_offline method that processes outputs into PoolingRequestOutput objects', 'build a PoolingCompletionRequest with task, embedding, and classification parameters for pooling models', 'build a PoolingChatRequest with chat messages and pooling task configuration for embedding generation', 'build a generic IOProcessorRequest with typed data and plugin pooling task for custom IO processing', 'create a PoolingResponse containing a list of PoolingResponseData with embeddings and usage info', 'build a PoolingBytesResponse with binary content and optional headers for byte-stream pooling output', 'create a ServingPooling instance with supported_tasks and vLLM configuration', 'verify a PoolingRequest task against supported tasks and raise errors for unsupported requests', 'build a JSONResponse from pooling outputs encoded as float or base64', 'get the appropriate IOProcessor for a given PoolingRequest based on its task']
```

Usage

```
{'create_serving_pooling': 'create a ServingPooling instance with supported_tasks and vLLM configuration', 'verify_pooling_task': 'verify a PoolingRequest task against supported tasks and raise errors for unsupported requests', 'build_pooling_json_response': 'build a JSONResponse from pooling outputs encoded as float or base64', 'build_pooling_bytes_response': 'build a StreamingResponse from pooling outputs encoded as raw bytes', 'get_io_processor': 'get the appropriate IOProcessor for a given PoolingRequest based on its task'}
```

