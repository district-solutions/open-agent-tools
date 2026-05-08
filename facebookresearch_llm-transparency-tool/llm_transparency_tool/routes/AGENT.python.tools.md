# Agent Python Tools

- repo: facebookresearch/llm-transparency-tool
- repo_uri: https://github.com/facebookresearch/llm-transparency-tool

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/routes/contributions.py

Prompts

```
['compute normalized contributions of parts vectors into a whole vector using pairwise distance', 'compute contributions of parts and a one-off residual stream vector into a whole vector', 'compute per-token per-head attention contributions and residual stream contributions from decomposed attention', 'compute per-neuron MLP contributions and residual stream contributions from decomposed MLP output', 'apply a threshold to block and residual contributions then renormalize to sum to one', 'build a contribution graph for all blocks and tokens of a TransparentLlm model using build_full_graph', 'build subgraph trees leading to specified output tokens from a full contribution graph with edge threshold filtering', 'create a GraphBuilder instance with a specified number of layers and tokens to construct a NetworkX DiGraph', 'add an attention edge between tokens across layers to the GraphBuilder contribution graph with a given weight', 'add an FFN edge connecting the attention output to the residual stream through the MLP block with a weight', 'create a GraphNode dataclass instance with layer, token, and NodeType for LLM activation graphing', 'check if a GraphNode is in the residual stream using the is_in_residual_stream method', 'get the predecessor GraphNode in the residual stream using get_residual_predecessor method', 'get a formatted hierarchical name string for a GraphNode using the get_name method', 'get a formatted attention head or FFN neuron name using get_head_name or get_neuron_name', 'run the unittest that verifies MLP contribution calculations between residual and MLP output tensors', 'run the unittest that verifies decomposed attention contribution calculations using pairwise distance norms', 'run the unittest that verifies decomposed MLP neuron contribution calculations with neuron impact tensors', 'run the unittest that verifies thresholding and renormalization of block and residual contribution tensors', 'run the unittest that verifies output tensor shapes for attention and residual contribution computations']
```

Usage

```
{'compute_part_contributions_to_whole': 'compute normalized contributions of parts vectors into a whole vector using pairwise distance', 'compute_contributions_with_residual_stream': 'compute contributions of parts and a one-off residual stream vector into a whole vector', 'compute_attention_head_contributions': 'compute per-token per-head attention contributions and residual stream contributions from decomposed attention', 'compute_mlp_neuron_contributions': 'compute per-neuron MLP contributions and residual stream contributions from decomposed MLP output', 'threshold_and_renormalize_contributions': 'apply a threshold to block and residual contributions then renormalize to sum to one'}
```

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/routes/graph.py

Prompts

```
['compute normalized contributions of parts vectors into a whole vector using pairwise distance', 'compute contributions of parts and a one-off residual stream vector into a whole vector', 'compute per-token per-head attention contributions and residual stream contributions from decomposed attention', 'compute per-neuron MLP contributions and residual stream contributions from decomposed MLP output', 'apply a threshold to block and residual contributions then renormalize to sum to one', 'build a contribution graph for all blocks and tokens of a TransparentLlm model using build_full_graph', 'build subgraph trees leading to specified output tokens from a full contribution graph with edge threshold filtering', 'create a GraphBuilder instance with a specified number of layers and tokens to construct a NetworkX DiGraph', 'add an attention edge between tokens across layers to the GraphBuilder contribution graph with a given weight', 'add an FFN edge connecting the attention output to the residual stream through the MLP block with a weight', 'create a GraphNode dataclass instance with layer, token, and NodeType for LLM activation graphing', 'check if a GraphNode is in the residual stream using the is_in_residual_stream method', 'get the predecessor GraphNode in the residual stream using get_residual_predecessor method', 'get a formatted hierarchical name string for a GraphNode using the get_name method', 'get a formatted attention head or FFN neuron name using get_head_name or get_neuron_name', 'run the unittest that verifies MLP contribution calculations between residual and MLP output tensors', 'run the unittest that verifies decomposed attention contribution calculations using pairwise distance norms', 'run the unittest that verifies decomposed MLP neuron contribution calculations with neuron impact tensors', 'run the unittest that verifies thresholding and renormalization of block and residual contribution tensors', 'run the unittest that verifies output tensor shapes for attention and residual contribution computations']
```

Usage

```
{'build_contribution_graph': 'build a contribution graph for all blocks and tokens of a TransparentLlm model using build_full_graph', 'build_paths_to_predictions': 'build subgraph trees leading to specified output tokens from a full contribution graph with edge threshold filtering', 'create_graph_builder': 'create a GraphBuilder instance with a specified number of layers and tokens to construct a NetworkX DiGraph', 'add_attention_edge': 'add an attention edge between tokens across layers to the GraphBuilder contribution graph with a given weight', 'add_ffn_edge': 'add an FFN edge connecting the attention output to the residual stream through the MLP block with a weight'}
```

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/routes/graph_node.py

Prompts

```
['compute normalized contributions of parts vectors into a whole vector using pairwise distance', 'compute contributions of parts and a one-off residual stream vector into a whole vector', 'compute per-token per-head attention contributions and residual stream contributions from decomposed attention', 'compute per-neuron MLP contributions and residual stream contributions from decomposed MLP output', 'apply a threshold to block and residual contributions then renormalize to sum to one', 'build a contribution graph for all blocks and tokens of a TransparentLlm model using build_full_graph', 'build subgraph trees leading to specified output tokens from a full contribution graph with edge threshold filtering', 'create a GraphBuilder instance with a specified number of layers and tokens to construct a NetworkX DiGraph', 'add an attention edge between tokens across layers to the GraphBuilder contribution graph with a given weight', 'add an FFN edge connecting the attention output to the residual stream through the MLP block with a weight', 'create a GraphNode dataclass instance with layer, token, and NodeType for LLM activation graphing', 'check if a GraphNode is in the residual stream using the is_in_residual_stream method', 'get the predecessor GraphNode in the residual stream using get_residual_predecessor method', 'get a formatted hierarchical name string for a GraphNode using the get_name method', 'get a formatted attention head or FFN neuron name using get_head_name or get_neuron_name', 'run the unittest that verifies MLP contribution calculations between residual and MLP output tensors', 'run the unittest that verifies decomposed attention contribution calculations using pairwise distance norms', 'run the unittest that verifies decomposed MLP neuron contribution calculations with neuron impact tensors', 'run the unittest that verifies thresholding and renormalization of block and residual contribution tensors', 'run the unittest that verifies output tensor shapes for attention and residual contribution computations']
```

Usage

```
{'create_graphnode': 'create a GraphNode dataclass instance with layer, token, and NodeType for LLM activation graphing', 'check_residual_stream': 'check if a GraphNode is in the residual stream using the is_in_residual_stream method', 'get_residual_predecessor': 'get the predecessor GraphNode in the residual stream using get_residual_predecessor method', 'get_node_name': 'get a formatted hierarchical name string for a GraphNode using the get_name method', 'get_head_or_neuron_name': 'get a formatted attention head or FFN neuron name using get_head_name or get_neuron_name'}
```

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/routes/test_contributions.py

Prompts

```
['compute normalized contributions of parts vectors into a whole vector using pairwise distance', 'compute contributions of parts and a one-off residual stream vector into a whole vector', 'compute per-token per-head attention contributions and residual stream contributions from decomposed attention', 'compute per-neuron MLP contributions and residual stream contributions from decomposed MLP output', 'apply a threshold to block and residual contributions then renormalize to sum to one', 'build a contribution graph for all blocks and tokens of a TransparentLlm model using build_full_graph', 'build subgraph trees leading to specified output tokens from a full contribution graph with edge threshold filtering', 'create a GraphBuilder instance with a specified number of layers and tokens to construct a NetworkX DiGraph', 'add an attention edge between tokens across layers to the GraphBuilder contribution graph with a given weight', 'add an FFN edge connecting the attention output to the residual stream through the MLP block with a weight', 'create a GraphNode dataclass instance with layer, token, and NodeType for LLM activation graphing', 'check if a GraphNode is in the residual stream using the is_in_residual_stream method', 'get the predecessor GraphNode in the residual stream using get_residual_predecessor method', 'get a formatted hierarchical name string for a GraphNode using the get_name method', 'get a formatted attention head or FFN neuron name using get_head_name or get_neuron_name', 'run the unittest that verifies MLP contribution calculations between residual and MLP output tensors', 'run the unittest that verifies decomposed attention contribution calculations using pairwise distance norms', 'run the unittest that verifies decomposed MLP neuron contribution calculations with neuron impact tensors', 'run the unittest that verifies thresholding and renormalization of block and residual contribution tensors', 'run the unittest that verifies output tensor shapes for attention and residual contribution computations']
```

Usage

```
{'run_test_mlp_contributions': 'run the unittest that verifies MLP contribution calculations between residual and MLP output tensors', 'run_test_decomposed_attn_contributions': 'run the unittest that verifies decomposed attention contribution calculations using pairwise distance norms', 'run_test_decomposed_mlp_contributions': 'run the unittest that verifies decomposed MLP neuron contribution calculations with neuron impact tensors', 'run_test_renormalizing_threshold': 'run the unittest that verifies thresholding and renormalization of block and residual contribution tensors', 'run_test_attention_contributions_shape': 'run the unittest that verifies output tensor shapes for attention and residual contribution computations'}
```

