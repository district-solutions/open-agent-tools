# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/moshi/configuration_moshi.py

Prompts

```
['create a MoshiConfig instance with custom audio encoder and depth decoder configurations', 'create a MoshiDepthConfig instance for the depth decoder with custom hidden size and ffn_dim', 'build a MoshiConfig from an existing audio encoder configuration using from_audio_encoder_config', 'test the MoshiConfig validate_architecture method to ensure ffn_dim is even and num_codebooks is valid', 'test the MoshiDepthConfig validate_architecture method to ensure ffn_dim is even', 'convert a Moshi checkpoint to HuggingFace transformers format using the convert_checkpoint CLI', 'run the Moshi conversion CLI with checkpoint path, mimi repo id, and output folder', 'convert a Moshi sentencepiece tokenizer to HuggingFace PreTrainedTokenizerFast format', 'build a converted Moshi model state dict with gating mechanism preprocessing and QKV splitting', 'test parameter counts between two models excluding final_proj layers', 'run MoshiForConditionalGeneration.generate to generate speech-to-speech responses from text and audio prompts', 'create a MoshiForCausalLM model for text-only next-token prediction and autoregressive generation', 'build a delayed pattern mask for multi-codebook audio token generation with BOS and PAD token handling', 'test MoshiAttention, MoshiFlashAttention2, and MoshiSdpaAttention modules with rotary embeddings and KV caching', 'review MoshiDepthDecoder and MoshiDecoderLayer components including flexible linear projections and gating MLPs']
```

Usage

```
{'create_MoshiConfig': 'create a MoshiConfig instance with custom audio encoder and depth decoder configurations', 'create_MoshiDepthConfig': 'create a MoshiDepthConfig instance for the depth decoder with custom hidden size and ffn_dim', 'build_MoshiConfig_from_audio_encoder': 'build a MoshiConfig from an existing audio encoder configuration using from_audio_encoder_config', 'test_MoshiConfig_validate': 'test the MoshiConfig validate_architecture method to ensure ffn_dim is even and num_codebooks is valid', 'test_MoshiDepthConfig_validate': 'test the MoshiDepthConfig validate_architecture method to ensure ffn_dim is even'}
```

## File: huggingface_transformers/src/transformers/models/moshi/convert_moshi_transformers.py

Prompts

```
['create a MoshiConfig instance with custom audio encoder and depth decoder configurations', 'create a MoshiDepthConfig instance for the depth decoder with custom hidden size and ffn_dim', 'build a MoshiConfig from an existing audio encoder configuration using from_audio_encoder_config', 'test the MoshiConfig validate_architecture method to ensure ffn_dim is even and num_codebooks is valid', 'test the MoshiDepthConfig validate_architecture method to ensure ffn_dim is even', 'convert a Moshi checkpoint to HuggingFace transformers format using the convert_checkpoint CLI', 'run the Moshi conversion CLI with checkpoint path, mimi repo id, and output folder', 'convert a Moshi sentencepiece tokenizer to HuggingFace PreTrainedTokenizerFast format', 'build a converted Moshi model state dict with gating mechanism preprocessing and QKV splitting', 'test parameter counts between two models excluding final_proj layers', 'run MoshiForConditionalGeneration.generate to generate speech-to-speech responses from text and audio prompts', 'create a MoshiForCausalLM model for text-only next-token prediction and autoregressive generation', 'build a delayed pattern mask for multi-codebook audio token generation with BOS and PAD token handling', 'test MoshiAttention, MoshiFlashAttention2, and MoshiSdpaAttention modules with rotary embeddings and KV caching', 'review MoshiDepthDecoder and MoshiDecoderLayer components including flexible linear projections and gating MLPs']
```

Usage

```
{'convert_moshi_checkpoint': 'convert a Moshi checkpoint to HuggingFace transformers format using the convert_checkpoint CLI', 'run_moshi_conversion_cli': 'run the Moshi conversion CLI with checkpoint path, mimi repo id, and output folder', 'convert_moshi_tokenizer': 'convert a Moshi sentencepiece tokenizer to HuggingFace PreTrainedTokenizerFast format', 'build_moshi_model_conversion': 'build a converted Moshi model state dict with gating mechanism preprocessing and QKV splitting', 'test_moshi_param_count': 'test parameter counts between two models excluding final_proj layers'}
```

## File: huggingface_transformers/src/transformers/models/moshi/modeling_moshi.py

Prompts

```
['create a MoshiConfig instance with custom audio encoder and depth decoder configurations', 'create a MoshiDepthConfig instance for the depth decoder with custom hidden size and ffn_dim', 'build a MoshiConfig from an existing audio encoder configuration using from_audio_encoder_config', 'test the MoshiConfig validate_architecture method to ensure ffn_dim is even and num_codebooks is valid', 'test the MoshiDepthConfig validate_architecture method to ensure ffn_dim is even', 'convert a Moshi checkpoint to HuggingFace transformers format using the convert_checkpoint CLI', 'run the Moshi conversion CLI with checkpoint path, mimi repo id, and output folder', 'convert a Moshi sentencepiece tokenizer to HuggingFace PreTrainedTokenizerFast format', 'build a converted Moshi model state dict with gating mechanism preprocessing and QKV splitting', 'test parameter counts between two models excluding final_proj layers', 'run MoshiForConditionalGeneration.generate to generate speech-to-speech responses from text and audio prompts', 'create a MoshiForCausalLM model for text-only next-token prediction and autoregressive generation', 'build a delayed pattern mask for multi-codebook audio token generation with BOS and PAD token handling', 'test MoshiAttention, MoshiFlashAttention2, and MoshiSdpaAttention modules with rotary embeddings and KV caching', 'review MoshiDepthDecoder and MoshiDecoderLayer components including flexible linear projections and gating MLPs']
```

Usage

```
{'run_generate_speech_to_speech': 'run MoshiForConditionalGeneration.generate to generate speech-to-speech responses from text and audio prompts', 'create_text_causal_lm': 'create a MoshiForCausalLM model for text-only next-token prediction and autoregressive generation', 'build_delay_pattern_mask': 'build a delayed pattern mask for multi-codebook audio token generation with BOS and PAD token handling', 'test_moshi_attention': 'test MoshiAttention, MoshiFlashAttention2, and MoshiSdpaAttention modules with rotary embeddings and KV caching', 'review_moshi_decoder': 'review MoshiDepthDecoder and MoshiDecoderLayer components including flexible linear projections and gating MLPs'}
```

