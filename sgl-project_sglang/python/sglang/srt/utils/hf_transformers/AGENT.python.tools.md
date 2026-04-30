# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/utils/hf_transformers/common.py

Prompts

```
['download a model from HuggingFace Hub and return the local path', 'get the text sub-config from a multi-modal model config for llm usage', 'get the context length of a model from a huggingface model config', 'load the generation config from a model path with error handling', 'check if a file is a valid GGUF model file by reading its header', 'load a HuggingFace model config with GGUF, remote URL, and model type overrides support', 'apply DeepSeek OCR model overrides including architecture and head dimension fixes', 'set the architectures field on a HuggingFace config object', 'load a Mistral model config with trust remote code and revision parameters', 'load a DeepSeek v3.2 model config when AutoConfig fails with a deepseek_v32 error', 'adapt a Mistral-style config dict into a HuggingFace PretrainedConfig with proper remapping', 'parse a Mistral params.json config file and return a HuggingFace-compatible config dict and config object', 'test whether a model name refers to a Mistral model needing the custom config parser', 'patch a MistralCommon tokenizer to be compatible with the HuggingFace tokenizer API', 'build a processor from a model path using get_processor with trust_remote_code and revision arguments', 'build a processor manually when AutoProcessor fails due to missing feature_extractor_type in preprocessor_config.json', 'test loading a DeepSeek OCR or OCR2 model processor with get_processor and automatic config overrides', 'test loading a Pixtral model processor and wrapping it with wrap_as_pixtral utility', 'test loading a Mistral model processor with mistral_common tokenizer patching and special token fixes', 'create a tokenizer for a model name via HuggingFace with auto or slow mode and trust remote code support', 'resolve special tokenizer name formats like GGUF files, remote URLs, and RunAI object storage URIs to local paths', 'fix transformers v5 tokenizer component mismatches by restoring original pre_tokenizer and decoder from tokenizer.json', 'restore add_bos_token and add_eos_token attributes stripped by transformers v5 from the tokenizer config', 'fix special tokens like <image> that encode as subwords instead of single tokens in transformers v5']
```

Usage

```
{'download_from_hf': 'download a model from HuggingFace Hub and return the local path', 'get_hf_text_config': 'get the text sub-config from a multi-modal model config for llm usage', 'get_context_length': 'get the context length of a model from a huggingface model config', 'get_generation_config': 'load the generation config from a model path with error handling', 'check_gguf_file': 'check if a file is a valid GGUF model file by reading its header'}
```

## File: sgl-project_sglang/python/sglang/srt/utils/hf_transformers/config.py

Prompts

```
['download a model from HuggingFace Hub and return the local path', 'get the text sub-config from a multi-modal model config for llm usage', 'get the context length of a model from a huggingface model config', 'load the generation config from a model path with error handling', 'check if a file is a valid GGUF model file by reading its header', 'load a HuggingFace model config with GGUF, remote URL, and model type overrides support', 'apply DeepSeek OCR model overrides including architecture and head dimension fixes', 'set the architectures field on a HuggingFace config object', 'load a Mistral model config with trust remote code and revision parameters', 'load a DeepSeek v3.2 model config when AutoConfig fails with a deepseek_v32 error', 'adapt a Mistral-style config dict into a HuggingFace PretrainedConfig with proper remapping', 'parse a Mistral params.json config file and return a HuggingFace-compatible config dict and config object', 'test whether a model name refers to a Mistral model needing the custom config parser', 'patch a MistralCommon tokenizer to be compatible with the HuggingFace tokenizer API', 'build a processor from a model path using get_processor with trust_remote_code and revision arguments', 'build a processor manually when AutoProcessor fails due to missing feature_extractor_type in preprocessor_config.json', 'test loading a DeepSeek OCR or OCR2 model processor with get_processor and automatic config overrides', 'test loading a Pixtral model processor and wrapping it with wrap_as_pixtral utility', 'test loading a Mistral model processor with mistral_common tokenizer patching and special token fixes', 'create a tokenizer for a model name via HuggingFace with auto or slow mode and trust remote code support', 'resolve special tokenizer name formats like GGUF files, remote URLs, and RunAI object storage URIs to local paths', 'fix transformers v5 tokenizer component mismatches by restoring original pre_tokenizer and decoder from tokenizer.json', 'restore add_bos_token and add_eos_token attributes stripped by transformers v5 from the tokenizer config', 'fix special tokens like <image> that encode as subwords instead of single tokens in transformers v5']
```

Usage

```
{'load_hf_config': 'load a HuggingFace model config with GGUF, remote URL, and model type overrides support', 'apply_deepseek_ocr_overrides': 'apply DeepSeek OCR model overrides including architecture and head dimension fixes', 'set_architectures': 'set the architectures field on a HuggingFace config object', 'load_mistral_config': 'load a Mistral model config with trust remote code and revision parameters', 'load_deepseek_v32_model': 'load a DeepSeek v3.2 model config when AutoConfig fails with a deepseek_v32 error'}
```

## File: sgl-project_sglang/python/sglang/srt/utils/hf_transformers/mistral_utils.py

Prompts

```
['download a model from HuggingFace Hub and return the local path', 'get the text sub-config from a multi-modal model config for llm usage', 'get the context length of a model from a huggingface model config', 'load the generation config from a model path with error handling', 'check if a file is a valid GGUF model file by reading its header', 'load a HuggingFace model config with GGUF, remote URL, and model type overrides support', 'apply DeepSeek OCR model overrides including architecture and head dimension fixes', 'set the architectures field on a HuggingFace config object', 'load a Mistral model config with trust remote code and revision parameters', 'load a DeepSeek v3.2 model config when AutoConfig fails with a deepseek_v32 error', 'adapt a Mistral-style config dict into a HuggingFace PretrainedConfig with proper remapping', 'parse a Mistral params.json config file and return a HuggingFace-compatible config dict and config object', 'test whether a model name refers to a Mistral model needing the custom config parser', 'patch a MistralCommon tokenizer to be compatible with the HuggingFace tokenizer API', 'build a processor from a model path using get_processor with trust_remote_code and revision arguments', 'build a processor manually when AutoProcessor fails due to missing feature_extractor_type in preprocessor_config.json', 'test loading a DeepSeek OCR or OCR2 model processor with get_processor and automatic config overrides', 'test loading a Pixtral model processor and wrapping it with wrap_as_pixtral utility', 'test loading a Mistral model processor with mistral_common tokenizer patching and special token fixes', 'create a tokenizer for a model name via HuggingFace with auto or slow mode and trust remote code support', 'resolve special tokenizer name formats like GGUF files, remote URLs, and RunAI object storage URIs to local paths', 'fix transformers v5 tokenizer component mismatches by restoring original pre_tokenizer and decoder from tokenizer.json', 'restore add_bos_token and add_eos_token attributes stripped by transformers v5 from the tokenizer config', 'fix special tokens like <image> that encode as subwords instead of single tokens in transformers v5']
```

Usage

```
{'load_mistral_config': 'load and parse a Mistral model config from a local or HuggingFace model path', 'adapt_config_dict': 'adapt a Mistral-style config dict into a HuggingFace PretrainedConfig with proper remapping', 'parse_mistral_config': 'parse a Mistral params.json config file and return a HuggingFace-compatible config dict and config object', 'is_mistral_model': 'test whether a model name refers to a Mistral model needing the custom config parser', 'patch_mistral_common_tokenizer': 'patch a MistralCommon tokenizer to be compatible with the HuggingFace tokenizer API'}
```

## File: sgl-project_sglang/python/sglang/srt/utils/hf_transformers/processor.py

Prompts

```
['download a model from HuggingFace Hub and return the local path', 'get the text sub-config from a multi-modal model config for llm usage', 'get the context length of a model from a huggingface model config', 'load the generation config from a model path with error handling', 'check if a file is a valid GGUF model file by reading its header', 'load a HuggingFace model config with GGUF, remote URL, and model type overrides support', 'apply DeepSeek OCR model overrides including architecture and head dimension fixes', 'set the architectures field on a HuggingFace config object', 'load a Mistral model config with trust remote code and revision parameters', 'load a DeepSeek v3.2 model config when AutoConfig fails with a deepseek_v32 error', 'adapt a Mistral-style config dict into a HuggingFace PretrainedConfig with proper remapping', 'parse a Mistral params.json config file and return a HuggingFace-compatible config dict and config object', 'test whether a model name refers to a Mistral model needing the custom config parser', 'patch a MistralCommon tokenizer to be compatible with the HuggingFace tokenizer API', 'build a processor from a model path using get_processor with trust_remote_code and revision arguments', 'build a processor manually when AutoProcessor fails due to missing feature_extractor_type in preprocessor_config.json', 'test loading a DeepSeek OCR or OCR2 model processor with get_processor and automatic config overrides', 'test loading a Pixtral model processor and wrapping it with wrap_as_pixtral utility', 'test loading a Mistral model processor with mistral_common tokenizer patching and special token fixes', 'create a tokenizer for a model name via HuggingFace with auto or slow mode and trust remote code support', 'resolve special tokenizer name formats like GGUF files, remote URLs, and RunAI object storage URIs to local paths', 'fix transformers v5 tokenizer component mismatches by restoring original pre_tokenizer and decoder from tokenizer.json', 'restore add_bos_token and add_eos_token attributes stripped by transformers v5 from the tokenizer config', 'fix special tokens like <image> that encode as subwords instead of single tokens in transformers v5']
```

Usage

```
{'build_processor_from_model': 'build a processor from a model path using get_processor with trust_remote_code and revision arguments', 'build_processor_manually': 'build a processor manually when AutoProcessor fails due to missing feature_extractor_type in preprocessor_config.json', 'test_processor_with_ocr_model': 'test loading a DeepSeek OCR or OCR2 model processor with get_processor and automatic config overrides', 'test_processor_with_pixtral': 'test loading a Pixtral model processor and wrapping it with wrap_as_pixtral utility', 'test_processor_with_mistral': 'test loading a Mistral model processor with mistral_common tokenizer patching and special token fixes'}
```

## File: sgl-project_sglang/python/sglang/srt/utils/hf_transformers/tokenizer.py

Prompts

```
['download a model from HuggingFace Hub and return the local path', 'get the text sub-config from a multi-modal model config for llm usage', 'get the context length of a model from a huggingface model config', 'load the generation config from a model path with error handling', 'check if a file is a valid GGUF model file by reading its header', 'load a HuggingFace model config with GGUF, remote URL, and model type overrides support', 'apply DeepSeek OCR model overrides including architecture and head dimension fixes', 'set the architectures field on a HuggingFace config object', 'load a Mistral model config with trust remote code and revision parameters', 'load a DeepSeek v3.2 model config when AutoConfig fails with a deepseek_v32 error', 'adapt a Mistral-style config dict into a HuggingFace PretrainedConfig with proper remapping', 'parse a Mistral params.json config file and return a HuggingFace-compatible config dict and config object', 'test whether a model name refers to a Mistral model needing the custom config parser', 'patch a MistralCommon tokenizer to be compatible with the HuggingFace tokenizer API', 'build a processor from a model path using get_processor with trust_remote_code and revision arguments', 'build a processor manually when AutoProcessor fails due to missing feature_extractor_type in preprocessor_config.json', 'test loading a DeepSeek OCR or OCR2 model processor with get_processor and automatic config overrides', 'test loading a Pixtral model processor and wrapping it with wrap_as_pixtral utility', 'test loading a Mistral model processor with mistral_common tokenizer patching and special token fixes', 'create a tokenizer for a model name via HuggingFace with auto or slow mode and trust remote code support', 'resolve special tokenizer name formats like GGUF files, remote URLs, and RunAI object storage URIs to local paths', 'fix transformers v5 tokenizer component mismatches by restoring original pre_tokenizer and decoder from tokenizer.json', 'restore add_bos_token and add_eos_token attributes stripped by transformers v5 from the tokenizer config', 'fix special tokens like <image> that encode as subwords instead of single tokens in transformers v5']
```

Usage

```
{'create_get_tokenizer': 'create a tokenizer for a model name via HuggingFace with auto or slow mode and trust remote code support', 'resolve_tokenizer_name': 'resolve special tokenizer name formats like GGUF files, remote URLs, and RunAI object storage URIs to local paths', 'fix_v5_tokenizer_components': 'fix transformers v5 tokenizer component mismatches by restoring original pre_tokenizer and decoder from tokenizer.json', 'fix_v5_add_bos_eos_token': 'restore add_bos_token and add_eos_token attributes stripped by transformers v5 from the tokenizer config', 'fix_added_tokens_encoding': 'fix special tokens like <image> that encode as subwords instead of single tokens in transformers v5'}
```

