# Agent Python Tools

- repo: facebookresearch/paq
- repo_uri: https://github.com/facebookresearch/paq

## File: facebookresearch_paq/paq/retrievers/build_index.py

Prompts

```
['build a FAISS index from precomputed embedding vectors using the build_index_streaming function', 'build an HNSW approximate nearest neighbor index from embedding vectors with configurable store_n and ef parameters', 'build a FAISS index with SQ8 or fp16 scalar quantization to reduce memory usage', 'sample a fraction of embedding vectors from a directory for training a quantizer', 'augment embedding vectors with an auxiliary dimension for normalized inner product search', 'run the embed CLI to generate embeddings for questions in a JSONL file using a HuggingFace model', 'run the embed_job function to embed a chunk of questions and save the resulting tensor matrix', 'run the embed function to batch-process QA items through a model and return concatenated embeddings', 'run the embed CLI with multiple SLURM jobs via submitit for distributed embedding across a cluster', 'run the embed CLI with fp16 mode enabled to generate half-precision embeddings on a GPU', 'run the REPAQ QA-pair retrieval CLI to retrieve answers from a corpus of QA pairs', 'run QA retrieval queries using a model, tokenizer, and MIPS search against a corpus', 'run Maximal Inner Product Search on an index with batched query parallelization', 'load a FAISS index or precomputed embeddings directory for retrieval search', 'format retrieval results into structured output with input QA and retrieved QA pairs', 'load a retriever model and tokenizer from a pretrained model path using load_retriever', 'create a RetrieverEncoder from a pretrained model path using RetrieverEncoder.from_pretrained', 'build a RetrieverEncoder with a transformers config and optional projection dimension', 'run a forward pass through the RetrieverEncoder to get CLS token embeddings', "inspect a model's pytorch_model.bin state dict to find the encode_proj projection dimension"]
```

Usage

```
{'build_faiss_index_streaming': 'build a FAISS index from precomputed embedding vectors using the build_index_streaming function', 'build_hnsw_index': 'build an HNSW approximate nearest neighbor index from embedding vectors with configurable store_n and ef parameters', 'build_quantized_index': 'build a FAISS index with SQ8 or fp16 scalar quantization to reduce memory usage', 'get_vector_sample': 'sample a fraction of embedding vectors from a directory for training a quantizer', 'augment_vectors': 'augment embedding vectors with an auxiliary dimension for normalized inner product search'}
```

## File: facebookresearch_paq/paq/retrievers/embed.py

Prompts

```
['build a FAISS index from precomputed embedding vectors using the build_index_streaming function', 'build an HNSW approximate nearest neighbor index from embedding vectors with configurable store_n and ef parameters', 'build a FAISS index with SQ8 or fp16 scalar quantization to reduce memory usage', 'sample a fraction of embedding vectors from a directory for training a quantizer', 'augment embedding vectors with an auxiliary dimension for normalized inner product search', 'run the embed CLI to generate embeddings for questions in a JSONL file using a HuggingFace model', 'run the embed_job function to embed a chunk of questions and save the resulting tensor matrix', 'run the embed function to batch-process QA items through a model and return concatenated embeddings', 'run the embed CLI with multiple SLURM jobs via submitit for distributed embedding across a cluster', 'run the embed CLI with fp16 mode enabled to generate half-precision embeddings on a GPU', 'run the REPAQ QA-pair retrieval CLI to retrieve answers from a corpus of QA pairs', 'run QA retrieval queries using a model, tokenizer, and MIPS search against a corpus', 'run Maximal Inner Product Search on an index with batched query parallelization', 'load a FAISS index or precomputed embeddings directory for retrieval search', 'format retrieval results into structured output with input QA and retrieved QA pairs', 'load a retriever model and tokenizer from a pretrained model path using load_retriever', 'create a RetrieverEncoder from a pretrained model path using RetrieverEncoder.from_pretrained', 'build a RetrieverEncoder with a transformers config and optional projection dimension', 'run a forward pass through the RetrieverEncoder to get CLS token embeddings', "inspect a model's pytorch_model.bin state dict to find the encode_proj projection dimension"]
```

Usage

```
{'run_embed_questions': 'run the embed CLI to generate embeddings for questions in a JSONL file using a HuggingFace model', 'run_embed_job': 'run the embed_job function to embed a chunk of questions and save the resulting tensor matrix', 'run_embed_batch': 'run the embed function to batch-process QA items through a model and return concatenated embeddings', 'run_embed_slurm': 'run the embed CLI with multiple SLURM jobs via submitit for distributed embedding across a cluster', 'run_embed_fp16': 'run the embed CLI with fp16 mode enabled to generate half-precision embeddings on a GPU'}
```

## File: facebookresearch_paq/paq/retrievers/retrieve.py

Prompts

```
['build a FAISS index from precomputed embedding vectors using the build_index_streaming function', 'build an HNSW approximate nearest neighbor index from embedding vectors with configurable store_n and ef parameters', 'build a FAISS index with SQ8 or fp16 scalar quantization to reduce memory usage', 'sample a fraction of embedding vectors from a directory for training a quantizer', 'augment embedding vectors with an auxiliary dimension for normalized inner product search', 'run the embed CLI to generate embeddings for questions in a JSONL file using a HuggingFace model', 'run the embed_job function to embed a chunk of questions and save the resulting tensor matrix', 'run the embed function to batch-process QA items through a model and return concatenated embeddings', 'run the embed CLI with multiple SLURM jobs via submitit for distributed embedding across a cluster', 'run the embed CLI with fp16 mode enabled to generate half-precision embeddings on a GPU', 'run the REPAQ QA-pair retrieval CLI to retrieve answers from a corpus of QA pairs', 'run QA retrieval queries using a model, tokenizer, and MIPS search against a corpus', 'run Maximal Inner Product Search on an index with batched query parallelization', 'load a FAISS index or precomputed embeddings directory for retrieval search', 'format retrieval results into structured output with input QA and retrieved QA pairs', 'load a retriever model and tokenizer from a pretrained model path using load_retriever', 'create a RetrieverEncoder from a pretrained model path using RetrieverEncoder.from_pretrained', 'build a RetrieverEncoder with a transformers config and optional projection dimension', 'run a forward pass through the RetrieverEncoder to get CLS token embeddings', "inspect a model's pytorch_model.bin state dict to find the encode_proj projection dimension"]
```

Usage

```
{'run_REPAQ_retrieval_cli': 'run the REPAQ QA-pair retrieval CLI to retrieve answers from a corpus of QA pairs', 'run_queries_function': 'run QA retrieval queries using a model, tokenizer, and MIPS search against a corpus', 'run_mips_search': 'run Maximal Inner Product Search on an index with batched query parallelization', 'load_faiss_index': 'load a FAISS index or precomputed embeddings directory for retrieval search', 'format_retrieval_results': 'format retrieval results into structured output with input QA and retrieved QA pairs'}
```

## File: facebookresearch_paq/paq/retrievers/retriever_utils.py

Prompts

```
['build a FAISS index from precomputed embedding vectors using the build_index_streaming function', 'build an HNSW approximate nearest neighbor index from embedding vectors with configurable store_n and ef parameters', 'build a FAISS index with SQ8 or fp16 scalar quantization to reduce memory usage', 'sample a fraction of embedding vectors from a directory for training a quantizer', 'augment embedding vectors with an auxiliary dimension for normalized inner product search', 'run the embed CLI to generate embeddings for questions in a JSONL file using a HuggingFace model', 'run the embed_job function to embed a chunk of questions and save the resulting tensor matrix', 'run the embed function to batch-process QA items through a model and return concatenated embeddings', 'run the embed CLI with multiple SLURM jobs via submitit for distributed embedding across a cluster', 'run the embed CLI with fp16 mode enabled to generate half-precision embeddings on a GPU', 'run the REPAQ QA-pair retrieval CLI to retrieve answers from a corpus of QA pairs', 'run QA retrieval queries using a model, tokenizer, and MIPS search against a corpus', 'run Maximal Inner Product Search on an index with batched query parallelization', 'load a FAISS index or precomputed embeddings directory for retrieval search', 'format retrieval results into structured output with input QA and retrieved QA pairs', 'load a retriever model and tokenizer from a pretrained model path using load_retriever', 'create a RetrieverEncoder from a pretrained model path using RetrieverEncoder.from_pretrained', 'build a RetrieverEncoder with a transformers config and optional projection dimension', 'run a forward pass through the RetrieverEncoder to get CLS token embeddings', "inspect a model's pytorch_model.bin state dict to find the encode_proj projection dimension"]
```

Usage

```
{'load_retriever_model_and_tokenizer': 'load a retriever model and tokenizer from a pretrained model path using load_retriever', 'create_retriever_encoder_from_pretrained': 'create a RetrieverEncoder from a pretrained model path using RetrieverEncoder.from_pretrained', 'build_retriever_encoder_with_config': 'build a RetrieverEncoder with a transformers config and optional projection dimension', 'run_retriever_encoder_forward_pass': 'run a forward pass through the RetrieverEncoder to get CLS token embeddings', 'inspect_projection_dimension_from_model': "inspect a model's pytorch_model.bin state dict to find the encode_proj projection dimension"}
```

