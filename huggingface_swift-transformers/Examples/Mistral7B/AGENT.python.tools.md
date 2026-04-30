# Agent Python Tools

- repo: huggingface/swift-transformers
- repo_uri: https://github.com/huggingface/swift-transformers

## File: huggingface_swift-transformers/Examples/Mistral7B/export.py

Prompts

```
['run the export function to convert Mistral 7B to a quantized Core ML model', 'create a StatefulMistralForCausalLM instance with a custom model path and max context size', 'update key and value cache tensors for a specific slice range using SliceUpdateKeyValueCache', 'build a SliceUpdateMistralAttention module that updates KV cache slices during forward pass', "quantize a Core ML model's weights to int4 using per-block linear symmetric quantization", 'run text generation using a Core ML Mistral model with a custom prompt', 'load a Core ML model and its tokenizer from the model metadata', 'generate text from a prompt using greedy decoding and a Core ML model', 'get the next token from a Core ML model using a generator with KV cache', 'review the causal mask construction and inference logic for token generation']
```

Usage

```
{'export_mistral_to_coreml': 'run the export function to convert Mistral 7B to a quantized Core ML model', 'create_stateful_mistral_model': 'create a StatefulMistralForCausalLM instance with a custom model path and max context size', 'update_kv_cache_slices': 'update key and value cache tensors for a specific slice range using SliceUpdateKeyValueCache', 'build_attention_with_slice_cache': 'build a SliceUpdateMistralAttention module that updates KV cache slices during forward pass', 'quantize_coreml_weights_int4': "quantize a Core ML model's weights to int4 using per-block linear symmetric quantization"}
```

## File: huggingface_swift-transformers/Examples/Mistral7B/generate.py

Prompts

```
['run the export function to convert Mistral 7B to a quantized Core ML model', 'create a StatefulMistralForCausalLM instance with a custom model path and max context size', 'update key and value cache tensors for a specific slice range using SliceUpdateKeyValueCache', 'build a SliceUpdateMistralAttention module that updates KV cache slices during forward pass', "quantize a Core ML model's weights to int4 using per-block linear symmetric quantization", 'run text generation using a Core ML Mistral model with a custom prompt', 'load a Core ML model and its tokenizer from the model metadata', 'generate text from a prompt using greedy decoding and a Core ML model', 'get the next token from a Core ML model using a generator with KV cache', 'review the causal mask construction and inference logic for token generation']
```

Usage

```
{'run_coreml_text_generation': 'run text generation using a Core ML Mistral model with a custom prompt', 'load_coreml_model_and_tokenizer': 'load a Core ML model and its tokenizer from the model metadata', 'generate_text_with_greedy_decoding': 'generate text from a prompt using greedy decoding and a Core ML model', 'get_next_token_generator': 'get the next token from a Core ML model using a generator with KV cache', 'review_causal_mask_inference': 'review the causal mask construction and inference logic for token generation'}
```

