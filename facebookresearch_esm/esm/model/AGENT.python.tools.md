# Agent Python Tools

- repo: facebookresearch/esm
- repo_uri: https://github.com/facebookresearch/esm

## File: facebookresearch_esm/esm/model/esm1.py

Prompts

```
['build a ProteinBertModel with args and alphabet to run ESM-1 or ESM-1b protein language model', 'run a forward pass on tokenized protein sequences to get logits and hidden representations', 'predict residue-residue contacts from protein sequence tokens using the contact prediction head', 'extract attention weights from all transformer layers by setting need_head_weights to True', 'configure model hyperparameters like num_layers, embed_dim, ffn_embed_dim, and attention_heads via add_args', 'build an ESM2 protein language model with configurable layers, embed_dim, and attention heads', 'run the ESM2 forward pass on tokenized protein sequences to get logits and hidden representations', 'run the ESM2 model to predict protein contact maps from attention head weights', 'review the ESM2 _init_submodules method that creates TransformerLayer stack, contact head, and LM head', 'summarize the ESM2 token dropout mechanism that masks and rescales embeddings during training', 'build an MSA Transformer model with configurable layers, embedding dim, and attention heads', 'run a forward pass on MSA token tensors to get logits and hidden representations', 'predict residue-residue contacts from MSA token input using the contact prediction head', 'configure MSA Transformer hyperparameters like num_layers, embed_dim, ffn_embed_dim, and dropout via argparse', 'set the max_tokens_per_msa threshold to control attention batching for larger MSA inputs at inference']
```

Usage

```
{'build_protein_bert_model': 'build a ProteinBertModel with args and alphabet to run ESM-1 or ESM-1b protein language model', 'run_forward_pass': 'run a forward pass on tokenized protein sequences to get logits and hidden representations', 'predict_contacts': 'predict residue-residue contacts from protein sequence tokens using the contact prediction head', 'extract_attention_weights': 'extract attention weights from all transformer layers by setting need_head_weights to True', 'configure_model_args': 'configure model hyperparameters like num_layers, embed_dim, ffn_embed_dim, and attention_heads via add_args'}
```

## File: facebookresearch_esm/esm/model/esm2.py

Prompts

```
['build a ProteinBertModel with args and alphabet to run ESM-1 or ESM-1b protein language model', 'run a forward pass on tokenized protein sequences to get logits and hidden representations', 'predict residue-residue contacts from protein sequence tokens using the contact prediction head', 'extract attention weights from all transformer layers by setting need_head_weights to True', 'configure model hyperparameters like num_layers, embed_dim, ffn_embed_dim, and attention_heads via add_args', 'build an ESM2 protein language model with configurable layers, embed_dim, and attention heads', 'run the ESM2 forward pass on tokenized protein sequences to get logits and hidden representations', 'run the ESM2 model to predict protein contact maps from attention head weights', 'review the ESM2 _init_submodules method that creates TransformerLayer stack, contact head, and LM head', 'summarize the ESM2 token dropout mechanism that masks and rescales embeddings during training', 'build an MSA Transformer model with configurable layers, embedding dim, and attention heads', 'run a forward pass on MSA token tensors to get logits and hidden representations', 'predict residue-residue contacts from MSA token input using the contact prediction head', 'configure MSA Transformer hyperparameters like num_layers, embed_dim, ffn_embed_dim, and dropout via argparse', 'set the max_tokens_per_msa threshold to control attention batching for larger MSA inputs at inference']
```

Usage

```
{'build_esm2_model': 'build an ESM2 protein language model with configurable layers, embed_dim, and attention heads', 'run_esm2_forward': 'run the ESM2 forward pass on tokenized protein sequences to get logits and hidden representations', 'run_esm2_contacts': 'run the ESM2 model to predict protein contact maps from attention head weights', 'review_esm2_init_submodules': 'review the ESM2 _init_submodules method that creates TransformerLayer stack, contact head, and LM head', 'summarize_esm2_token_dropout': 'summarize the ESM2 token dropout mechanism that masks and rescales embeddings during training'}
```

## File: facebookresearch_esm/esm/model/msa_transformer.py

Prompts

```
['build a ProteinBertModel with args and alphabet to run ESM-1 or ESM-1b protein language model', 'run a forward pass on tokenized protein sequences to get logits and hidden representations', 'predict residue-residue contacts from protein sequence tokens using the contact prediction head', 'extract attention weights from all transformer layers by setting need_head_weights to True', 'configure model hyperparameters like num_layers, embed_dim, ffn_embed_dim, and attention_heads via add_args', 'build an ESM2 protein language model with configurable layers, embed_dim, and attention heads', 'run the ESM2 forward pass on tokenized protein sequences to get logits and hidden representations', 'run the ESM2 model to predict protein contact maps from attention head weights', 'review the ESM2 _init_submodules method that creates TransformerLayer stack, contact head, and LM head', 'summarize the ESM2 token dropout mechanism that masks and rescales embeddings during training', 'build an MSA Transformer model with configurable layers, embedding dim, and attention heads', 'run a forward pass on MSA token tensors to get logits and hidden representations', 'predict residue-residue contacts from MSA token input using the contact prediction head', 'configure MSA Transformer hyperparameters like num_layers, embed_dim, ffn_embed_dim, and dropout via argparse', 'set the max_tokens_per_msa threshold to control attention batching for larger MSA inputs at inference']
```

Usage

```
{'build_msa_transformer_model': 'build an MSA Transformer model with configurable layers, embedding dim, and attention heads', 'run_forward_pass_msa': 'run a forward pass on MSA token tensors to get logits and hidden representations', 'predict_contacts_msa': 'predict residue-residue contacts from MSA token input using the contact prediction head', 'configure_args_msa_transformer': 'configure MSA Transformer hyperparameters like num_layers, embed_dim, ffn_embed_dim, and dropout via argparse', 'set_max_tokens_per_msa': 'set the max_tokens_per_msa threshold to control attention batching for larger MSA inputs at inference'}
```

