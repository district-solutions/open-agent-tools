# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/git/convert_git_to_pytorch.py

Prompts

```
['convert a GIT checkpoint from the original Microsoft repository to HuggingFace PyTorch format', 'get GIT model configuration including vision config, image size, and video flag from model name', 'create a list of weight key renames from original Microsoft GIT to HuggingFace transformer naming', 'split combined attention in_proj weight and bias into separate query, key, and value projections', 'download and sample 6 frames from a demo video for video-based GIT model verification', 'create a GitForCausalLM model for autoregressive language modeling with image input support', 'build a GitModel combining a CLIP image encoder and text decoder for multimodal hidden states', 'create a GitVisionModel using a CLIP-based vision transformer to encode image pixel values', 'test GitEncoder layers with self-attention and feed-forward blocks for multimodal sequence processing', 'review GitForCausalLM prepare_inputs_for_generation method for handling pixel values during autoregressive generation']
```

Usage

```
{'convert_git_checkpoint': 'convert a GIT checkpoint from the original Microsoft repository to HuggingFace PyTorch format', 'get_git_config': 'get GIT model configuration including vision config, image size, and video flag from model name', 'create_rename_keys': 'create a list of weight key renames from original Microsoft GIT to HuggingFace transformer naming', 'read_in_q_k_v': 'split combined attention in_proj weight and bias into separate query, key, and value projections', 'prepare_video': 'download and sample 6 frames from a demo video for video-based GIT model verification'}
```

## File: huggingface_transformers/src/transformers/models/git/modeling_git.py

Prompts

```
['convert a GIT checkpoint from the original Microsoft repository to HuggingFace PyTorch format', 'get GIT model configuration including vision config, image size, and video flag from model name', 'create a list of weight key renames from original Microsoft GIT to HuggingFace transformer naming', 'split combined attention in_proj weight and bias into separate query, key, and value projections', 'download and sample 6 frames from a demo video for video-based GIT model verification', 'create a GitForCausalLM model for autoregressive language modeling with image input support', 'build a GitModel combining a CLIP image encoder and text decoder for multimodal hidden states', 'create a GitVisionModel using a CLIP-based vision transformer to encode image pixel values', 'test GitEncoder layers with self-attention and feed-forward blocks for multimodal sequence processing', 'review GitForCausalLM prepare_inputs_for_generation method for handling pixel values during autoregressive generation']
```

Usage

```
{'create_git_for_causal_lm': 'create a GitForCausalLM model for autoregressive language modeling with image input support', 'build_git_model': 'build a GitModel combining a CLIP image encoder and text decoder for multimodal hidden states', 'create_git_vision_model': 'create a GitVisionModel using a CLIP-based vision transformer to encode image pixel values', 'test_git_encoder_layers': 'test GitEncoder layers with self-attention and feed-forward blocks for multimodal sequence processing', 'review_git_for_causal_lm_generate': 'review GitForCausalLM prepare_inputs_for_generation method for handling pixel values during autoregressive generation'}
```

