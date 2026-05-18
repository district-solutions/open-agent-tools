# Agent Python Tools

- repo: facebookresearch/nbref
- repo_uri: https://github.com/facebookresearch/nbref

## File: facebookresearch_nbref/baseline_model/modules/encoder_decoder_layers.py

Prompts

```
['build a multi-head attention layer with query key value projections and optional masking', 'build a multi-head attention layer with learnable memory keys and values for augmented attention', 'build an encoder layer combining self-attention, feedforward, and optional GNN message passing on graphs', 'build a decoder layer with self-attention, encoder cross-attention, and optional GNN graph message passing', 'build a final decoder layer with self-attention, AST attention, and encoder cross-attention', 'build a CODE_SIM_ASM_Model with a GNN and transformer encoder for code similarity', 'build a VUL_DETECT_ASM_Model with a GNN and transformer encoder for vulnerability detection', 'build a Graph_NN using GraphSAGE or GatedGraphConv for graph neural network feature extraction', 'build a Transformer Encoder with positional encoding and multi-head attention layers', 'build a Decoder_AST with AST self-attention and cross-attention for sequence generation']
```

Usage

```
{'build_MultiHeadAttentionLayer': 'build a multi-head attention layer with query key value projections and optional masking', 'build_MultiHeadAttentionLayer_wMem': 'build a multi-head attention layer with learnable memory keys and values for augmented attention', 'build_EncoderLayer': 'build an encoder layer combining self-attention, feedforward, and optional GNN message passing on graphs', 'build_DecoderLayer': 'build a decoder layer with self-attention, encoder cross-attention, and optional GNN graph message passing', 'build_DecoderLayer_last': 'build a final decoder layer with self-attention, AST attention, and encoder cross-attention'}
```

## File: facebookresearch_nbref/baseline_model/modules/transformer_tree_model.py

Prompts

```
['build a multi-head attention layer with query key value projections and optional masking', 'build a multi-head attention layer with learnable memory keys and values for augmented attention', 'build an encoder layer combining self-attention, feedforward, and optional GNN message passing on graphs', 'build a decoder layer with self-attention, encoder cross-attention, and optional GNN graph message passing', 'build a final decoder layer with self-attention, AST attention, and encoder cross-attention', 'build a CODE_SIM_ASM_Model with a GNN and transformer encoder for code similarity', 'build a VUL_DETECT_ASM_Model with a GNN and transformer encoder for vulnerability detection', 'build a Graph_NN using GraphSAGE or GatedGraphConv for graph neural network feature extraction', 'build a Transformer Encoder with positional encoding and multi-head attention layers', 'build a Decoder_AST with AST self-attention and cross-attention for sequence generation']
```

Usage

```
{'build_CODE_SIM_ASM_Model': 'build a CODE_SIM_ASM_Model with a GNN and transformer encoder for code similarity', 'build_VUL_DETECT_ASM_Model': 'build a VUL_DETECT_ASM_Model with a GNN and transformer encoder for vulnerability detection', 'build_Graph_NN': 'build a Graph_NN using GraphSAGE or GatedGraphConv for graph neural network feature extraction', 'build_Encoder': 'build a Transformer Encoder with positional encoding and multi-head attention layers', 'build_Decoder_AST': 'build a Decoder_AST with AST self-attention and cross-attention for sequence generation'}
```

