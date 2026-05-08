# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/models/hg/test_hg_adapter.py

Prompts

```
['test HgCausalLMAdapter to find embedding layers like embed_tokens, wte, or nested model.embed_tokens on a HuggingFace model', 'test HgCausalLMAdapter gradient checkpointing enable and verify it raises RuntimeError when the model does not support it', 'test HgCausalLMAdapter forward pass with targets and target_mask to compute scalar loss during training', 'test HgCausalLMAdapter forward pass without targets to return logits tensor for inference', 'test wrap_hg_model_if_causal_lm to wrap causal LM models in HgCausalLMAdapter and pass through non-causal models', 'test that _LegacyHuggingFaceConverter.to_hg_config raises NotSupportedError when called', 'test that _LegacyHuggingFaceConverter.to_hg_state_dict raises NotSupportedError when called', 'test that get_hugging_face_converter raises NotSupportedError for an unregistered model family', 'test that get_hugging_face_converter returns a converter for a registered model family', 'test saving a valid Hugging Face model with a state dict and config', 'register a custom HuggingFace model class with config, model, tokenizer, and processor class names to the user registry', 'create a HuggingFace model from a HuggingFaceModelConfig by delegating to HgFactory and calling create_model', 'create a HuggingFace model using HgFactory with auto model detection or special model loading based on config class', 'build a HuggingFaceModelConfig with hf_name, model_type, dtype, device, trust_remote_code, and custom load_kwargs parameters', 'handle HuggingFace model loading errors with model_name context for not found and generic failure cases', 'create an HgTokenizerConfig with custom special tokens like unk, bos, eos, pad, boh, and eoh', 'create an HgTokenizer instance by passing an HG token model to the constructor', 'encode text to token tensors and decode token tensors back to text using HgTokenizer', 'create a HuggingFaceTokenEncoder or HuggingFaceTokenDecoder from an HgTokenizer with optional device and pin_memory settings', 'load an HgTokenizer from a file path using load_hg_tokenizer with an HgTokenizerConfig for special tokens']
```

Usage

```
{'test_HgCausalLMAdapter_embedding_lookup': 'test HgCausalLMAdapter to find embedding layers like embed_tokens, wte, or nested model.embed_tokens on a HuggingFace model', 'test_HgCausalLMAdapter_gradient_checkpointing': 'test HgCausalLMAdapter gradient checkpointing enable and verify it raises RuntimeError when the model does not support it', 'test_HgCausalLMAdapter_forward_training': 'test HgCausalLMAdapter forward pass with targets and target_mask to compute scalar loss during training', 'test_HgCausalLMAdapter_forward_inference': 'test HgCausalLMAdapter forward pass without targets to return logits tensor for inference', 'test_wrap_hg_model_if_causal_lm': 'test wrap_hg_model_if_causal_lm to wrap causal LM models in HgCausalLMAdapter and pass through non-causal models'}
```

## File: facebookresearch_fairseq2/tests/unit/models/hg/test_hg_converter.py

Prompts

```
['test HgCausalLMAdapter to find embedding layers like embed_tokens, wte, or nested model.embed_tokens on a HuggingFace model', 'test HgCausalLMAdapter gradient checkpointing enable and verify it raises RuntimeError when the model does not support it', 'test HgCausalLMAdapter forward pass with targets and target_mask to compute scalar loss during training', 'test HgCausalLMAdapter forward pass without targets to return logits tensor for inference', 'test wrap_hg_model_if_causal_lm to wrap causal LM models in HgCausalLMAdapter and pass through non-causal models', 'test that _LegacyHuggingFaceConverter.to_hg_config raises NotSupportedError when called', 'test that _LegacyHuggingFaceConverter.to_hg_state_dict raises NotSupportedError when called', 'test that get_hugging_face_converter raises NotSupportedError for an unregistered model family', 'test that get_hugging_face_converter returns a converter for a registered model family', 'test saving a valid Hugging Face model with a state dict and config', 'register a custom HuggingFace model class with config, model, tokenizer, and processor class names to the user registry', 'create a HuggingFace model from a HuggingFaceModelConfig by delegating to HgFactory and calling create_model', 'create a HuggingFace model using HgFactory with auto model detection or special model loading based on config class', 'build a HuggingFaceModelConfig with hf_name, model_type, dtype, device, trust_remote_code, and custom load_kwargs parameters', 'handle HuggingFace model loading errors with model_name context for not found and generic failure cases', 'create an HgTokenizerConfig with custom special tokens like unk, bos, eos, pad, boh, and eoh', 'create an HgTokenizer instance by passing an HG token model to the constructor', 'encode text to token tensors and decode token tensors back to text using HgTokenizer', 'create a HuggingFaceTokenEncoder or HuggingFaceTokenDecoder from an HgTokenizer with optional device and pin_memory settings', 'load an HgTokenizer from a file path using load_hg_tokenizer with an HgTokenizerConfig for special tokens']
```

Usage

```
{'test_legacy_converter_to_hg_config': 'test that _LegacyHuggingFaceConverter.to_hg_config raises NotSupportedError when called', 'test_legacy_converter_to_hg_state_dict': 'test that _LegacyHuggingFaceConverter.to_hg_state_dict raises NotSupportedError when called', 'test_get_hugging_face_converter_unknown_family': 'test that get_hugging_face_converter raises NotSupportedError for an unregistered model family', 'test_get_hugging_face_converter_known_family': 'test that get_hugging_face_converter returns a converter for a registered model family', 'test_save_hugging_face_model_valid': 'test saving a valid Hugging Face model with a state dict and config'}
```

## File: facebookresearch_fairseq2/tests/unit/models/hg/test_hg_factory.py

Prompts

```
['test HgCausalLMAdapter to find embedding layers like embed_tokens, wte, or nested model.embed_tokens on a HuggingFace model', 'test HgCausalLMAdapter gradient checkpointing enable and verify it raises RuntimeError when the model does not support it', 'test HgCausalLMAdapter forward pass with targets and target_mask to compute scalar loss during training', 'test HgCausalLMAdapter forward pass without targets to return logits tensor for inference', 'test wrap_hg_model_if_causal_lm to wrap causal LM models in HgCausalLMAdapter and pass through non-causal models', 'test that _LegacyHuggingFaceConverter.to_hg_config raises NotSupportedError when called', 'test that _LegacyHuggingFaceConverter.to_hg_state_dict raises NotSupportedError when called', 'test that get_hugging_face_converter raises NotSupportedError for an unregistered model family', 'test that get_hugging_face_converter returns a converter for a registered model family', 'test saving a valid Hugging Face model with a state dict and config', 'register a custom HuggingFace model class with config, model, tokenizer, and processor class names to the user registry', 'create a HuggingFace model from a HuggingFaceModelConfig by delegating to HgFactory and calling create_model', 'create a HuggingFace model using HgFactory with auto model detection or special model loading based on config class', 'build a HuggingFaceModelConfig with hf_name, model_type, dtype, device, trust_remote_code, and custom load_kwargs parameters', 'handle HuggingFace model loading errors with model_name context for not found and generic failure cases', 'create an HgTokenizerConfig with custom special tokens like unk, bos, eos, pad, boh, and eoh', 'create an HgTokenizer instance by passing an HG token model to the constructor', 'encode text to token tensors and decode token tensors back to text using HgTokenizer', 'create a HuggingFaceTokenEncoder or HuggingFaceTokenDecoder from an HgTokenizer with optional device and pin_memory settings', 'load an HgTokenizer from a file path using load_hg_tokenizer with an HgTokenizerConfig for special tokens']
```

Usage

```
{'register_hg_model_class': 'register a custom HuggingFace model class with config, model, tokenizer, and processor class names to the user registry', 'create_hg_model': 'create a HuggingFace model from a HuggingFaceModelConfig by delegating to HgFactory and calling create_model', 'HgFactory_create_model': 'create a HuggingFace model using HgFactory with auto model detection or special model loading based on config class', 'HuggingFaceModelConfig': 'build a HuggingFaceModelConfig with hf_name, model_type, dtype, device, trust_remote_code, and custom load_kwargs parameters', 'HuggingFaceModelError': 'handle HuggingFace model loading errors with model_name context for not found and generic failure cases'}
```

## File: facebookresearch_fairseq2/tests/unit/models/hg/test_hg_tokenizer.py

Prompts

```
['test HgCausalLMAdapter to find embedding layers like embed_tokens, wte, or nested model.embed_tokens on a HuggingFace model', 'test HgCausalLMAdapter gradient checkpointing enable and verify it raises RuntimeError when the model does not support it', 'test HgCausalLMAdapter forward pass with targets and target_mask to compute scalar loss during training', 'test HgCausalLMAdapter forward pass without targets to return logits tensor for inference', 'test wrap_hg_model_if_causal_lm to wrap causal LM models in HgCausalLMAdapter and pass through non-causal models', 'test that _LegacyHuggingFaceConverter.to_hg_config raises NotSupportedError when called', 'test that _LegacyHuggingFaceConverter.to_hg_state_dict raises NotSupportedError when called', 'test that get_hugging_face_converter raises NotSupportedError for an unregistered model family', 'test that get_hugging_face_converter returns a converter for a registered model family', 'test saving a valid Hugging Face model with a state dict and config', 'register a custom HuggingFace model class with config, model, tokenizer, and processor class names to the user registry', 'create a HuggingFace model from a HuggingFaceModelConfig by delegating to HgFactory and calling create_model', 'create a HuggingFace model using HgFactory with auto model detection or special model loading based on config class', 'build a HuggingFaceModelConfig with hf_name, model_type, dtype, device, trust_remote_code, and custom load_kwargs parameters', 'handle HuggingFace model loading errors with model_name context for not found and generic failure cases', 'create an HgTokenizerConfig with custom special tokens like unk, bos, eos, pad, boh, and eoh', 'create an HgTokenizer instance by passing an HG token model to the constructor', 'encode text to token tensors and decode token tensors back to text using HgTokenizer', 'create a HuggingFaceTokenEncoder or HuggingFaceTokenDecoder from an HgTokenizer with optional device and pin_memory settings', 'load an HgTokenizer from a file path using load_hg_tokenizer with an HgTokenizerConfig for special tokens']
```

Usage

```
{'create_HgTokenizerConfig': 'create an HgTokenizerConfig with custom special tokens like unk, bos, eos, pad, boh, and eoh', 'create_HgTokenizer': 'create an HgTokenizer instance by passing an HG token model to the constructor', 'encode_decode_HgTokenizer': 'encode text to token tensors and decode token tensors back to text using HgTokenizer', 'create_encoder_decoder_HgTokenizer': 'create a HuggingFaceTokenEncoder or HuggingFaceTokenDecoder from an HgTokenizer with optional device and pin_memory settings', 'load_hg_tokenizer': 'load an HgTokenizer from a file path using load_hg_tokenizer with an HgTokenizerConfig for special tokens'}
```

