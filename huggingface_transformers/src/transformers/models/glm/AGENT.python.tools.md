# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/glm/convert_glm_weights_to_hf.py

Prompts

```
['convert GLM model weights from original format to HuggingFace Transformers format and save to output directory', 'convert GLM state dict keys and split qkv_proj into separate q_proj, k_proj, v_proj tensors', 'convert original GLM config dictionary to HuggingFace GlmConfig with renamed and mapped keys', 'convert GLM tokenizer to HuggingFace PreTrainedTokenizerFast with optional special token post processor', 'load GLM model weights from safetensors or .bin files in the input directory', 'build a GLM causal language model for text generation using GlmForCausalLM with pretrained weights', 'create a GLM base model for feature extraction using GlmModel with input embeddings and causal masking', 'test the multi-headed attention mechanism with rotary position embeddings in GlmAttention', 'refactor the GLM decoder layer to support gradient checkpointing and cached key-value states', 'summarize using GlmForSequenceClassification for text classification with a pretrained GLM config', 'create a GLM causal language model using GlmForCausalLM with a GlmConfig for inference', 'build a GLM attention layer using GlmAttention with rotary position embeddings for transformer blocks', 'test the GlmRotaryEmbedding compute_default_rope_parameters method to generate inverse frequencies', 'run apply_rotary_pos_emb to rotate query and key tensors with cosine and sine embeddings', 'create a GLM sequence classification model using GlmForSequenceClassification for text classification tasks']
```

Usage

```
{'convert_glm_model': 'convert GLM model weights from original format to HuggingFace Transformers format and save to output directory', 'convert_state_dict': 'convert GLM state dict keys and split qkv_proj into separate q_proj, k_proj, v_proj tensors', 'convert_config': 'convert original GLM config dictionary to HuggingFace GlmConfig with renamed and mapped keys', 'convert_glm_tokenizer': 'convert GLM tokenizer to HuggingFace PreTrainedTokenizerFast with optional special token post processor', 'load_weights': 'load GLM model weights from safetensors or .bin files in the input directory'}
```

## File: huggingface_transformers/src/transformers/models/glm/modeling_glm.py

Prompts

```
['convert GLM model weights from original format to HuggingFace Transformers format and save to output directory', 'convert GLM state dict keys and split qkv_proj into separate q_proj, k_proj, v_proj tensors', 'convert original GLM config dictionary to HuggingFace GlmConfig with renamed and mapped keys', 'convert GLM tokenizer to HuggingFace PreTrainedTokenizerFast with optional special token post processor', 'load GLM model weights from safetensors or .bin files in the input directory', 'build a GLM causal language model for text generation using GlmForCausalLM with pretrained weights', 'create a GLM base model for feature extraction using GlmModel with input embeddings and causal masking', 'test the multi-headed attention mechanism with rotary position embeddings in GlmAttention', 'refactor the GLM decoder layer to support gradient checkpointing and cached key-value states', 'summarize using GlmForSequenceClassification for text classification with a pretrained GLM config', 'create a GLM causal language model using GlmForCausalLM with a GlmConfig for inference', 'build a GLM attention layer using GlmAttention with rotary position embeddings for transformer blocks', 'test the GlmRotaryEmbedding compute_default_rope_parameters method to generate inverse frequencies', 'run apply_rotary_pos_emb to rotate query and key tensors with cosine and sine embeddings', 'create a GLM sequence classification model using GlmForSequenceClassification for text classification tasks']
```

Usage

```
{'build_glm_causal_lm_model': 'build a GLM causal language model for text generation using GlmForCausalLM with pretrained weights', 'create_glm_model_inference': 'create a GLM base model for feature extraction using GlmModel with input embeddings and causal masking', 'test_glm_attention_mechanism': 'test the multi-headed attention mechanism with rotary position embeddings in GlmAttention', 'refactor_glm_decoder_layer': 'refactor the GLM decoder layer to support gradient checkpointing and cached key-value states', 'summarize_glm_sequence_classification': 'summarize using GlmForSequenceClassification for text classification with a pretrained GLM config'}
```

## File: huggingface_transformers/src/transformers/models/glm/modular_glm.py

Prompts

```
['convert GLM model weights from original format to HuggingFace Transformers format and save to output directory', 'convert GLM state dict keys and split qkv_proj into separate q_proj, k_proj, v_proj tensors', 'convert original GLM config dictionary to HuggingFace GlmConfig with renamed and mapped keys', 'convert GLM tokenizer to HuggingFace PreTrainedTokenizerFast with optional special token post processor', 'load GLM model weights from safetensors or .bin files in the input directory', 'build a GLM causal language model for text generation using GlmForCausalLM with pretrained weights', 'create a GLM base model for feature extraction using GlmModel with input embeddings and causal masking', 'test the multi-headed attention mechanism with rotary position embeddings in GlmAttention', 'refactor the GLM decoder layer to support gradient checkpointing and cached key-value states', 'summarize using GlmForSequenceClassification for text classification with a pretrained GLM config', 'create a GLM causal language model using GlmForCausalLM with a GlmConfig for inference', 'build a GLM attention layer using GlmAttention with rotary position embeddings for transformer blocks', 'test the GlmRotaryEmbedding compute_default_rope_parameters method to generate inverse frequencies', 'run apply_rotary_pos_emb to rotate query and key tensors with cosine and sine embeddings', 'create a GLM sequence classification model using GlmForSequenceClassification for text classification tasks']
```

Usage

```
{'create_glm_model': 'create a GLM causal language model using GlmForCausalLM with a GlmConfig for inference', 'build_glm_attention': 'build a GLM attention layer using GlmAttention with rotary position embeddings for transformer blocks', 'test_rotary_embedding': 'test the GlmRotaryEmbedding compute_default_rope_parameters method to generate inverse frequencies', 'run_apply_rotary_pos_emb': 'run apply_rotary_pos_emb to rotate query and key tensors with cosine and sine embeddings', 'create_glm_classifier': 'create a GLM sequence classification model using GlmForSequenceClassification for text classification tasks'}
```

