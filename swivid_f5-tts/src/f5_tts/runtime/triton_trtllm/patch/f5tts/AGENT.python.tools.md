# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/patch/f5tts/model.py

Prompts

```
['build an F5TTS model with a PretrainedConfig for TensorRT-LLM inference', 'create an InputEmbedding module that projects concatenated audio and text features', 'run the F5TTS forward pass to denoise noisy input audio conditioned on text', 'build Tensor input definitions for F5TTS with configurable batch size and sequence length', 'review the F5TTS forward method that applies DiT transformer blocks with RoPE embeddings', 'build a DiT transformer block with adaptive layer norm, attention, and feed-forward layers', 'create a multi-head attention module with rotary position embeddings and TRT plugin support', 'create adaptive layer normalization conditioned on a timestep embedding for diffusion models', 'run rotary positional embedding application on 3D tensors with optional input padding removal', 'review the attention processor that handles TRT bert_attention plugin and manual attention fallback']
```

Usage

```
{'build_F5TTS_model': 'build an F5TTS model with a PretrainedConfig for TensorRT-LLM inference', 'create_InputEmbedding': 'create an InputEmbedding module that projects concatenated audio and text features', 'run_F5TTS_forward': 'run the F5TTS forward pass to denoise noisy input audio conditioned on text', 'build_F5TTS_prepare_inputs': 'build Tensor input definitions for F5TTS with configurable batch size and sequence length', 'review_F5TTS_forward': 'review the F5TTS forward method that applies DiT transformer blocks with RoPE embeddings'}
```

## File: swivid_f5-tts/src/f5_tts/runtime/triton_trtllm/patch/f5tts/modules.py

Prompts

```
['build an F5TTS model with a PretrainedConfig for TensorRT-LLM inference', 'create an InputEmbedding module that projects concatenated audio and text features', 'run the F5TTS forward pass to denoise noisy input audio conditioned on text', 'build Tensor input definitions for F5TTS with configurable batch size and sequence length', 'review the F5TTS forward method that applies DiT transformer blocks with RoPE embeddings', 'build a DiT transformer block with adaptive layer norm, attention, and feed-forward layers', 'create a multi-head attention module with rotary position embeddings and TRT plugin support', 'create adaptive layer normalization conditioned on a timestep embedding for diffusion models', 'run rotary positional embedding application on 3D tensors with optional input padding removal', 'review the attention processor that handles TRT bert_attention plugin and manual attention fallback']
```

Usage

```
{'build_DiTBlock': 'build a DiT transformer block with adaptive layer norm, attention, and feed-forward layers', 'create_Attention': 'create a multi-head attention module with rotary position embeddings and TRT plugin support', 'create_AdaLayerNormZero': 'create adaptive layer normalization conditioned on a timestep embedding for diffusion models', 'run_apply_rotary_pos_emb_3dim': 'run rotary positional embedding application on 3D tensors with optional input padding removal', 'review_AttnProcessor': 'review the attention processor that handles TRT bert_attention plugin and manual attention fallback'}
```

