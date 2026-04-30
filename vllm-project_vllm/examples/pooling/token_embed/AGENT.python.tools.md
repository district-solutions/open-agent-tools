# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/pooling/token_embed/colqwen3_token_embed_online.py

Prompts

```
['run the ColQwen3 multi-vector embedding example against a vLLM pooling API server', 'encode text queries into multi-vector embeddings via the vLLM pooling endpoint', 'encode image documents into multi-vector embeddings via the vLLM pooling endpoint', 'compute ColBERT-style MaxSim scores between query and document multi-vector embeddings', 'score text query-document pairs via the vLLM /score late interaction endpoint', 'create a vLLM LLM model with pooling runner for Jina embeddings v4', 'create a TextPrompt with a query string for embedding inference', 'fetch an image from a URL for use in a multimodal TextPrompt', 'encode a list of TextPrompts using model.encode with pooling_task token_embed', 'get pooled and normalized embeddings from model encode outputs handling vision tokens', 'run the multi_vector_retrieval_offline script to generate sentence-level embeddings using an embedding model like BAAI/bge-m3', "run the script with pooling_task='token_embed' to generate per-token embeddings for each prompt", "create an LLM instance with runner='pooling' for embedding model inference via argparse CLI", 'generate sentence-level embeddings by calling llm.embed(prompts) on a pooling runner LLM', "generate per-token multi-vector embeddings by calling llm.encode(prompts, pooling_task='token_embed')", 'run the vLLM pooling API example to retrieve multi-vector embeddings from BAAI/bge-m3', 'create a function that posts a JSON prompt to a vLLM pooling API endpoint and returns the response', 'create an argument parser that accepts host, port, and model flags for the vLLM pooling client', 'run the main entry point to send multiple prompts to a vLLM pooling server and print embedding shapes', 'test the post_http_request function with a sample prompt dict and mock API URL']
```

Usage

```
{'run_colqwen3_token_embed': 'run the ColQwen3 multi-vector embedding example against a vLLM pooling API server', 'encode_text_queries': 'encode text queries into multi-vector embeddings via the vLLM pooling endpoint', 'encode_image_documents': 'encode image documents into multi-vector embeddings via the vLLM pooling endpoint', 'compute_maxsim_scores': 'compute ColBERT-style MaxSim scores between query and document multi-vector embeddings', 'score_text_pairs': 'score text query-document pairs via the vLLM /score late interaction endpoint'}
```

## File: vllm-project_vllm/examples/pooling/token_embed/jina_embeddings_v4_offline.py

Prompts

```
['run the ColQwen3 multi-vector embedding example against a vLLM pooling API server', 'encode text queries into multi-vector embeddings via the vLLM pooling endpoint', 'encode image documents into multi-vector embeddings via the vLLM pooling endpoint', 'compute ColBERT-style MaxSim scores between query and document multi-vector embeddings', 'score text query-document pairs via the vLLM /score late interaction endpoint', 'create a vLLM LLM model with pooling runner for Jina embeddings v4', 'create a TextPrompt with a query string for embedding inference', 'fetch an image from a URL for use in a multimodal TextPrompt', 'encode a list of TextPrompts using model.encode with pooling_task token_embed', 'get pooled and normalized embeddings from model encode outputs handling vision tokens', 'run the multi_vector_retrieval_offline script to generate sentence-level embeddings using an embedding model like BAAI/bge-m3', "run the script with pooling_task='token_embed' to generate per-token embeddings for each prompt", "create an LLM instance with runner='pooling' for embedding model inference via argparse CLI", 'generate sentence-level embeddings by calling llm.embed(prompts) on a pooling runner LLM', "generate per-token multi-vector embeddings by calling llm.encode(prompts, pooling_task='token_embed')", 'run the vLLM pooling API example to retrieve multi-vector embeddings from BAAI/bge-m3', 'create a function that posts a JSON prompt to a vLLM pooling API endpoint and returns the response', 'create an argument parser that accepts host, port, and model flags for the vLLM pooling client', 'run the main entry point to send multiple prompts to a vLLM pooling server and print embedding shapes', 'test the post_http_request function with a sample prompt dict and mock API URL']
```

Usage

```
{'create_llm_pooling_model': 'create a vLLM LLM model with pooling runner for Jina embeddings v4', 'create_text_prompt': 'create a TextPrompt with a query string for embedding inference', 'fetch_image_multimodal': 'fetch an image from a URL for use in a multimodal TextPrompt', 'encode_prompts_token_embed': 'encode a list of TextPrompts using model.encode with pooling_task token_embed', 'get_embeddings_pool_normalize': 'get pooled and normalized embeddings from model encode outputs handling vision tokens'}
```

## File: vllm-project_vllm/examples/pooling/token_embed/multi_vector_retrieval_offline.py

Prompts

```
['run the ColQwen3 multi-vector embedding example against a vLLM pooling API server', 'encode text queries into multi-vector embeddings via the vLLM pooling endpoint', 'encode image documents into multi-vector embeddings via the vLLM pooling endpoint', 'compute ColBERT-style MaxSim scores between query and document multi-vector embeddings', 'score text query-document pairs via the vLLM /score late interaction endpoint', 'create a vLLM LLM model with pooling runner for Jina embeddings v4', 'create a TextPrompt with a query string for embedding inference', 'fetch an image from a URL for use in a multimodal TextPrompt', 'encode a list of TextPrompts using model.encode with pooling_task token_embed', 'get pooled and normalized embeddings from model encode outputs handling vision tokens', 'run the multi_vector_retrieval_offline script to generate sentence-level embeddings using an embedding model like BAAI/bge-m3', "run the script with pooling_task='token_embed' to generate per-token embeddings for each prompt", "create an LLM instance with runner='pooling' for embedding model inference via argparse CLI", 'generate sentence-level embeddings by calling llm.embed(prompts) on a pooling runner LLM', "generate per-token multi-vector embeddings by calling llm.encode(prompts, pooling_task='token_embed')", 'run the vLLM pooling API example to retrieve multi-vector embeddings from BAAI/bge-m3', 'create a function that posts a JSON prompt to a vLLM pooling API endpoint and returns the response', 'create an argument parser that accepts host, port, and model flags for the vLLM pooling client', 'run the main entry point to send multiple prompts to a vLLM pooling server and print embedding shapes', 'test the post_http_request function with a sample prompt dict and mock API URL']
```

Usage

```
{'run_multi_vector_retrieval_offline': 'run the multi_vector_retrieval_offline script to generate sentence-level embeddings using an embedding model like BAAI/bge-m3', 'run_token_embed': "run the script with pooling_task='token_embed' to generate per-token embeddings for each prompt", 'create_llm_pooling': "create an LLM instance with runner='pooling' for embedding model inference via argparse CLI", 'generate_sentence_embeddings': 'generate sentence-level embeddings by calling llm.embed(prompts) on a pooling runner LLM', 'generate_token_embeddings': "generate per-token multi-vector embeddings by calling llm.encode(prompts, pooling_task='token_embed')"}
```

## File: vllm-project_vllm/examples/pooling/token_embed/multi_vector_retrieval_online.py

Prompts

```
['run the ColQwen3 multi-vector embedding example against a vLLM pooling API server', 'encode text queries into multi-vector embeddings via the vLLM pooling endpoint', 'encode image documents into multi-vector embeddings via the vLLM pooling endpoint', 'compute ColBERT-style MaxSim scores between query and document multi-vector embeddings', 'score text query-document pairs via the vLLM /score late interaction endpoint', 'create a vLLM LLM model with pooling runner for Jina embeddings v4', 'create a TextPrompt with a query string for embedding inference', 'fetch an image from a URL for use in a multimodal TextPrompt', 'encode a list of TextPrompts using model.encode with pooling_task token_embed', 'get pooled and normalized embeddings from model encode outputs handling vision tokens', 'run the multi_vector_retrieval_offline script to generate sentence-level embeddings using an embedding model like BAAI/bge-m3', "run the script with pooling_task='token_embed' to generate per-token embeddings for each prompt", "create an LLM instance with runner='pooling' for embedding model inference via argparse CLI", 'generate sentence-level embeddings by calling llm.embed(prompts) on a pooling runner LLM', "generate per-token multi-vector embeddings by calling llm.encode(prompts, pooling_task='token_embed')", 'run the vLLM pooling API example to retrieve multi-vector embeddings from BAAI/bge-m3', 'create a function that posts a JSON prompt to a vLLM pooling API endpoint and returns the response', 'create an argument parser that accepts host, port, and model flags for the vLLM pooling client', 'run the main entry point to send multiple prompts to a vLLM pooling server and print embedding shapes', 'test the post_http_request function with a sample prompt dict and mock API URL']
```

Usage

```
{'run_multi_vector_retrieval': 'run the vLLM pooling API example to retrieve multi-vector embeddings from BAAI/bge-m3', 'create_post_http_request': 'create a function that posts a JSON prompt to a vLLM pooling API endpoint and returns the response', 'create_parse_args': 'create an argument parser that accepts host, port, and model flags for the vLLM pooling client', 'run_main_entry_point': 'run the main entry point to send multiple prompts to a vLLM pooling server and print embedding shapes', 'test_post_http_request': 'test the post_http_request function with a sample prompt dict and mock API URL'}
```

