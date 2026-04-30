# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/phi/convert_phi_weights_to_hf.py

Prompts

```
['convert Phi model weights from Microsoft checkpoint format to HuggingFace model format', 'run the CLI script to convert phi-2 weights from checkpoint_path to pytorch_dump_folder_path', 'convert original weight keys to HuggingFace naming convention using the PHI_MAPPING dictionary', 'download a Phi model checkpoint from HuggingFace hub to a specified local path', 'save converted Phi weights as a full pretrained model with config using save_pretrained', 'create a PhiForCausalLM model for autoregressive text generation with causal masking', 'build a PhiForSequenceClassification model for classifying text sequences using PhiPreTrainedModel', 'build a PhiForTokenClassification model for labeling tokens in text sequences', 'run PhiAttention forward pass with multi-headed self-attention and rotary position embeddings', 'test PhiDecoderLayer forward pass with input layernorm, self-attention, MLP, and residual connections', 'build a PhiForCausalLM model for autoregressive text generation with partial rotary embeddings', 'create a PhiModel to generate hidden states with causal masking and past key-value caching', 'test the PhiAttention forward pass with partial rotary position embeddings and QK layer normalization', 'review the PhiDecoderLayer that combines self-attention, MLP, residual connections, and dropout', 'summarize how PhiRotaryEmbedding computes inverse frequencies using partial rotary factor and rope_theta']
```

Usage

```
{'convert_phi_weights': 'convert Phi model weights from Microsoft checkpoint format to HuggingFace model format', 'run_convert_phi_cli': 'run the CLI script to convert phi-2 weights from checkpoint_path to pytorch_dump_folder_path', 'convert_weights_mapping': 'convert original weight keys to HuggingFace naming convention using the PHI_MAPPING dictionary', 'download_phi_checkpoint': 'download a Phi model checkpoint from HuggingFace hub to a specified local path', 'save_phi_model_pretrained': 'save converted Phi weights as a full pretrained model with config using save_pretrained'}
```

## File: huggingface_transformers/src/transformers/models/phi/modeling_phi.py

Prompts

```
['convert Phi model weights from Microsoft checkpoint format to HuggingFace model format', 'run the CLI script to convert phi-2 weights from checkpoint_path to pytorch_dump_folder_path', 'convert original weight keys to HuggingFace naming convention using the PHI_MAPPING dictionary', 'download a Phi model checkpoint from HuggingFace hub to a specified local path', 'save converted Phi weights as a full pretrained model with config using save_pretrained', 'create a PhiForCausalLM model for autoregressive text generation with causal masking', 'build a PhiForSequenceClassification model for classifying text sequences using PhiPreTrainedModel', 'build a PhiForTokenClassification model for labeling tokens in text sequences', 'run PhiAttention forward pass with multi-headed self-attention and rotary position embeddings', 'test PhiDecoderLayer forward pass with input layernorm, self-attention, MLP, and residual connections', 'build a PhiForCausalLM model for autoregressive text generation with partial rotary embeddings', 'create a PhiModel to generate hidden states with causal masking and past key-value caching', 'test the PhiAttention forward pass with partial rotary position embeddings and QK layer normalization', 'review the PhiDecoderLayer that combines self-attention, MLP, residual connections, and dropout', 'summarize how PhiRotaryEmbedding computes inverse frequencies using partial rotary factor and rope_theta']
```

Usage

```
{'create_phi_causal_lm_model': 'create a PhiForCausalLM model for autoregressive text generation with causal masking', 'build_phi_sequence_classifier': 'build a PhiForSequenceClassification model for classifying text sequences using PhiPreTrainedModel', 'build_phi_token_classifier': 'build a PhiForTokenClassification model for labeling tokens in text sequences', 'run_phi_attention_forward': 'run PhiAttention forward pass with multi-headed self-attention and rotary position embeddings', 'test_phi_decoder_layer': 'test PhiDecoderLayer forward pass with input layernorm, self-attention, MLP, and residual connections'}
```

## File: huggingface_transformers/src/transformers/models/phi/modular_phi.py

Prompts

```
['convert Phi model weights from Microsoft checkpoint format to HuggingFace model format', 'run the CLI script to convert phi-2 weights from checkpoint_path to pytorch_dump_folder_path', 'convert original weight keys to HuggingFace naming convention using the PHI_MAPPING dictionary', 'download a Phi model checkpoint from HuggingFace hub to a specified local path', 'save converted Phi weights as a full pretrained model with config using save_pretrained', 'create a PhiForCausalLM model for autoregressive text generation with causal masking', 'build a PhiForSequenceClassification model for classifying text sequences using PhiPreTrainedModel', 'build a PhiForTokenClassification model for labeling tokens in text sequences', 'run PhiAttention forward pass with multi-headed self-attention and rotary position embeddings', 'test PhiDecoderLayer forward pass with input layernorm, self-attention, MLP, and residual connections', 'build a PhiForCausalLM model for autoregressive text generation with partial rotary embeddings', 'create a PhiModel to generate hidden states with causal masking and past key-value caching', 'test the PhiAttention forward pass with partial rotary position embeddings and QK layer normalization', 'review the PhiDecoderLayer that combines self-attention, MLP, residual connections, and dropout', 'summarize how PhiRotaryEmbedding computes inverse frequencies using partial rotary factor and rope_theta']
```

Usage

```
{'build_phi_causal_lm_model': 'build a PhiForCausalLM model for autoregressive text generation with partial rotary embeddings', 'create_phi_model_inference': 'create a PhiModel to generate hidden states with causal masking and past key-value caching', 'test_phi_attention_forward': 'test the PhiAttention forward pass with partial rotary position embeddings and QK layer normalization', 'review_phi_decoder_layer': 'review the PhiDecoderLayer that combines self-attention, MLP, residual connections, and dropout', 'summarize_phi_rope_parameters': 'summarize how PhiRotaryEmbedding computes inverse frequencies using partial rotary factor and rope_theta'}
```

