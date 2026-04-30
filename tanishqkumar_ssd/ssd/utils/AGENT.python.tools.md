# Agent Python Tools

- repo: tanishqkumar/ssd
- repo_uri: https://github.com/tanishqkumar/ssd

## File: tanishqkumar_ssd/ssd/utils/context.py

Prompts

```
['get the global Context object containing KV cache and sequence metadata', 'set the global Context for prefill phase with cu_seqlens_q, cu_seqlens_k, and max sequence lengths', 'set the global Context for decode phase with slot_mapping, context_lens, and block_tables', 'reset the global Context to default values with all fields cleared', 'check the is_prefill flag on the global Context to determine inference phase', 'load an EAGLE3 draft model from a path with optional target model for embedding weights', 'load a standard model from safetensors files in a given path', 'load an EAGLE3 draft model with packed module mappings for quantized weights', 'load embedding weights from a target model path into a draft model', 'load model weights from safetensors files with packed module name remapping', 'build a function to infer if a model is Llama or Qwen based on its path name', 'create a function that decodes a list of token IDs into readable strings using a tokenizer', 'test the infer_model_family function with Llama and Qwen model paths', 'test the decode_tokens function with token IDs and an AutoTokenizer instance', 'refactor the infer_model_family function to support additional model families beyond Llama and Qwen', 'verify speculative-decoding acceptance using greedy argmax and p/q-ratio acceptance with recovery sampling', 'run greedy verification by comparing draft tokens against target model argmax predictions', 'test ratio-based token acceptance with softmax probabilities and random thresholding', 'build adjusted max(0, p-q) recovery distribution for rejected draft tokens', 'test async speculative decoding with cache-hit filtering and sampler_x rescaling']
```

Usage

```
{'get_context': 'get the global Context object containing KV cache and sequence metadata', 'set_context_prefill': 'set the global Context for prefill phase with cu_seqlens_q, cu_seqlens_k, and max sequence lengths', 'set_context_decode': 'set the global Context for decode phase with slot_mapping, context_lens, and block_tables', 'reset_context': 'reset the global Context to default values with all fields cleared', 'check_is_prefill': 'check the is_prefill flag on the global Context to determine inference phase'}
```

## File: tanishqkumar_ssd/ssd/utils/loader.py

Prompts

```
['get the global Context object containing KV cache and sequence metadata', 'set the global Context for prefill phase with cu_seqlens_q, cu_seqlens_k, and max sequence lengths', 'set the global Context for decode phase with slot_mapping, context_lens, and block_tables', 'reset the global Context to default values with all fields cleared', 'check the is_prefill flag on the global Context to determine inference phase', 'load an EAGLE3 draft model from a path with optional target model for embedding weights', 'load a standard model from safetensors files in a given path', 'load an EAGLE3 draft model with packed module mappings for quantized weights', 'load embedding weights from a target model path into a draft model', 'load model weights from safetensors files with packed module name remapping', 'build a function to infer if a model is Llama or Qwen based on its path name', 'create a function that decodes a list of token IDs into readable strings using a tokenizer', 'test the infer_model_family function with Llama and Qwen model paths', 'test the decode_tokens function with token IDs and an AutoTokenizer instance', 'refactor the infer_model_family function to support additional model families beyond Llama and Qwen', 'verify speculative-decoding acceptance using greedy argmax and p/q-ratio acceptance with recovery sampling', 'run greedy verification by comparing draft tokens against target model argmax predictions', 'test ratio-based token acceptance with softmax probabilities and random thresholding', 'build adjusted max(0, p-q) recovery distribution for rejected draft tokens', 'test async speculative decoding with cache-hit filtering and sampler_x rescaling']
```

Usage

```
{'load_model_eagle_from_path': 'load an EAGLE3 draft model from a path with optional target model for embedding weights', 'load_model_safetensors_from_path': 'load a standard model from safetensors files in a given path', 'load_eagle_model_with_packed_modules': 'load an EAGLE3 draft model with packed module mappings for quantized weights', 'load_embedding_from_target_model': 'load embedding weights from a target model path into a draft model', 'load_safetensors_model_with_packed_modules': 'load model weights from safetensors files with packed module name remapping'}
```

## File: tanishqkumar_ssd/ssd/utils/misc.py

Prompts

```
['get the global Context object containing KV cache and sequence metadata', 'set the global Context for prefill phase with cu_seqlens_q, cu_seqlens_k, and max sequence lengths', 'set the global Context for decode phase with slot_mapping, context_lens, and block_tables', 'reset the global Context to default values with all fields cleared', 'check the is_prefill flag on the global Context to determine inference phase', 'load an EAGLE3 draft model from a path with optional target model for embedding weights', 'load a standard model from safetensors files in a given path', 'load an EAGLE3 draft model with packed module mappings for quantized weights', 'load embedding weights from a target model path into a draft model', 'load model weights from safetensors files with packed module name remapping', 'build a function to infer if a model is Llama or Qwen based on its path name', 'create a function that decodes a list of token IDs into readable strings using a tokenizer', 'test the infer_model_family function with Llama and Qwen model paths', 'test the decode_tokens function with token IDs and an AutoTokenizer instance', 'refactor the infer_model_family function to support additional model families beyond Llama and Qwen', 'verify speculative-decoding acceptance using greedy argmax and p/q-ratio acceptance with recovery sampling', 'run greedy verification by comparing draft tokens against target model argmax predictions', 'test ratio-based token acceptance with softmax probabilities and random thresholding', 'build adjusted max(0, p-q) recovery distribution for rejected draft tokens', 'test async speculative decoding with cache-hit filtering and sampler_x rescaling']
```

Usage

```
{'build_infer_model_family': 'build a function to infer if a model is Llama or Qwen based on its path name', 'create_decode_tokens': 'create a function that decodes a list of token IDs into readable strings using a tokenizer', 'test_infer_model_family': 'test the infer_model_family function with Llama and Qwen model paths', 'test_decode_tokens': 'test the decode_tokens function with token IDs and an AutoTokenizer instance', 'refactor_infer_model_family': 'refactor the infer_model_family function to support additional model families beyond Llama and Qwen'}
```

## File: tanishqkumar_ssd/ssd/utils/verify.py

Prompts

```
['get the global Context object containing KV cache and sequence metadata', 'set the global Context for prefill phase with cu_seqlens_q, cu_seqlens_k, and max sequence lengths', 'set the global Context for decode phase with slot_mapping, context_lens, and block_tables', 'reset the global Context to default values with all fields cleared', 'check the is_prefill flag on the global Context to determine inference phase', 'load an EAGLE3 draft model from a path with optional target model for embedding weights', 'load a standard model from safetensors files in a given path', 'load an EAGLE3 draft model with packed module mappings for quantized weights', 'load embedding weights from a target model path into a draft model', 'load model weights from safetensors files with packed module name remapping', 'build a function to infer if a model is Llama or Qwen based on its path name', 'create a function that decodes a list of token IDs into readable strings using a tokenizer', 'test the infer_model_family function with Llama and Qwen model paths', 'test the decode_tokens function with token IDs and an AutoTokenizer instance', 'refactor the infer_model_family function to support additional model families beyond Llama and Qwen', 'verify speculative-decoding acceptance using greedy argmax and p/q-ratio acceptance with recovery sampling', 'run greedy verification by comparing draft tokens against target model argmax predictions', 'test ratio-based token acceptance with softmax probabilities and random thresholding', 'build adjusted max(0, p-q) recovery distribution for rejected draft tokens', 'test async speculative decoding with cache-hit filtering and sampler_x rescaling']
```

Usage

```
{'verify_speculative_decoding': 'verify speculative-decoding acceptance using greedy argmax and p/q-ratio acceptance with recovery sampling', 'run_greedy_verification': 'run greedy verification by comparing draft tokens against target model argmax predictions', 'test_ratio_acceptance': 'test ratio-based token acceptance with softmax probabilities and random thresholding', 'build_recovery_distribution': 'build adjusted max(0, p-q) recovery distribution for rejected draft tokens', 'test_async_cache_handling': 'test async speculative decoding with cache-hit filtering and sampler_x rescaling'}
```

