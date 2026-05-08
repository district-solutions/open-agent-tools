# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/memnn/memnn.py

Prompts

```
['build a MemNN memory network model with configurable embedding size, hops, and memory size', 'score candidate responses against query and memory using the MemNN agent scoring method', 'encode padded candidate vectors into embeddings using the MemNN answer embedder', 'build a padded 3D memory tensor from a batch of memory vectors with optional time features', 'add MemNN-specific command line arguments for embedding size, hops, memsize, time features, and position encoding', 'run a forward pass through the MemNN model with queries, memories, and candidate tokens', 'create a custom Embedding layer with position encoding and mean or sum reduction strategies', 'review the Hop class attention mechanism that computes softmax-weighted memory outputs with query rotation', 'summarize the position encoding matrix generation using the End-to-End Memory Networks formula']
```

Usage

```
{'build_memnn_model': 'build a MemNN memory network model with configurable embedding size, hops, and memory size', 'score_candidates_memnn': 'score candidate responses against query and memory using the MemNN agent scoring method', 'encode_candidates_memnn': 'encode padded candidate vectors into embeddings using the MemNN answer embedder', 'build_mems_tensor': 'build a padded 3D memory tensor from a batch of memory vectors with optional time features', 'add_memnn_cmdline_args': 'add MemNN-specific command line arguments for embedding size, hops, memsize, time features, and position encoding'}
```

## File: facebookresearch_parlai/parlai/agents/memnn/modules.py

Prompts

```
['build a MemNN memory network model with configurable embedding size, hops, and memory size', 'score candidate responses against query and memory using the MemNN agent scoring method', 'encode padded candidate vectors into embeddings using the MemNN answer embedder', 'build a padded 3D memory tensor from a batch of memory vectors with optional time features', 'add MemNN-specific command line arguments for embedding size, hops, memsize, time features, and position encoding', 'run a forward pass through the MemNN model with queries, memories, and candidate tokens', 'create a custom Embedding layer with position encoding and mean or sum reduction strategies', 'review the Hop class attention mechanism that computes softmax-weighted memory outputs with query rotation', 'summarize the position encoding matrix generation using the End-to-End Memory Networks formula']
```

Usage

```
{'build_memnn_model': 'build a Memory Network model with configurable hops, embedding size, and position encoding', 'run_memnn_forward': 'run a forward pass through the MemNN model with queries, memories, and candidate tokens', 'create_embed_layer': 'create a custom Embedding layer with position encoding and mean or sum reduction strategies', 'review_hop_attention': 'review the Hop class attention mechanism that computes softmax-weighted memory outputs with query rotation', 'summarize_position_matrix': 'summarize the position encoding matrix generation using the End-to-End Memory Networks formula'}
```

