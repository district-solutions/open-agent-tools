# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/examples/text-generation/model_adapter.py

Prompts

```
['create a HabanaModelAdapter instance wrapping a HuggingFace causal LM for HPU-accelerated evaluation', 'run a forward pass through the Habana model to get logits from input token IDs', 'generate text completions for a list of lm-eval harness instances using the Habana adapter', 'warm up the Habana model by running dummy inputs through all configured bucket sizes', 'find the smallest bucket size greater than or equal to a given sequence length', 'run text generation inference on Habana Gaudi using a pre-trained model with configurable batch size and tokens', 'run text generation with Habana Flash Attention enabled for improved performance on HPU devices', 'run text generation using a quantized model loaded via AutoGPTQ, AutoAWQ, BnB NF4, or INC', 'run text generation with Habana profiling enabled to capture warmup and active steps for performance analysis', 'run text generation benchmark over a Hugging Face Hub dataset with configurable column and sample limits', 'run lm-eval benchmark tasks like hellaswag and lambada on an HPU device with a language model', 'run lm-eval with few-shot examples as multi-turn conversations using a chat template on HPU', 'run lm-eval on a quantized model on HPU and save the quantized model with INC', 'create an argparse parser for lm-eval with tasks, limits, buckets, and chat template options', 'review the LimitedSpawnPool function that creates a spawn-context multiprocessing pool sized for HPU multinode', 'initialize a HuggingFace causal LM model for text generation on Intel Gaudi HPU with optional DeepSpeed or tensor parallelism', 'adjust a batch dictionary of input_ids and attention_mask tensors to a target sequence size by truncating or padding', "compile a model's transformer module with torch.compile using the hpu_backend for Gaudi acceleration", 'setup FP8 quantization on a model using neural_compressor with a JSON config for measure or quantize modes', 'setup a tokenizer for a Llama model with proper pad, eos, and bos token configuration for generation']
```

Usage

```
{'create_HabanaModelAdapter': 'create a HabanaModelAdapter instance wrapping a HuggingFace causal LM for HPU-accelerated evaluation', 'run_model_call': 'run a forward pass through the Habana model to get logits from input token IDs', 'generate_until': 'generate text completions for a list of lm-eval harness instances using the Habana adapter', 'warm_up_model': 'warm up the Habana model by running dummy inputs through all configured bucket sizes', 'find_bucket': 'find the smallest bucket size greater than or equal to a given sequence length'}
```

## File: huggingface_optimum-habana/examples/text-generation/run_generation.py

Prompts

```
['create a HabanaModelAdapter instance wrapping a HuggingFace causal LM for HPU-accelerated evaluation', 'run a forward pass through the Habana model to get logits from input token IDs', 'generate text completions for a list of lm-eval harness instances using the Habana adapter', 'warm up the Habana model by running dummy inputs through all configured bucket sizes', 'find the smallest bucket size greater than or equal to a given sequence length', 'run text generation inference on Habana Gaudi using a pre-trained model with configurable batch size and tokens', 'run text generation with Habana Flash Attention enabled for improved performance on HPU devices', 'run text generation using a quantized model loaded via AutoGPTQ, AutoAWQ, BnB NF4, or INC', 'run text generation with Habana profiling enabled to capture warmup and active steps for performance analysis', 'run text generation benchmark over a Hugging Face Hub dataset with configurable column and sample limits', 'run lm-eval benchmark tasks like hellaswag and lambada on an HPU device with a language model', 'run lm-eval with few-shot examples as multi-turn conversations using a chat template on HPU', 'run lm-eval on a quantized model on HPU and save the quantized model with INC', 'create an argparse parser for lm-eval with tasks, limits, buckets, and chat template options', 'review the LimitedSpawnPool function that creates a spawn-context multiprocessing pool sized for HPU multinode', 'initialize a HuggingFace causal LM model for text generation on Intel Gaudi HPU with optional DeepSpeed or tensor parallelism', 'adjust a batch dictionary of input_ids and attention_mask tensors to a target sequence size by truncating or padding', "compile a model's transformer module with torch.compile using the hpu_backend for Gaudi acceleration", 'setup FP8 quantization on a model using neural_compressor with a JSON config for measure or quantize modes', 'setup a tokenizer for a Llama model with proper pad, eos, and bos token configuration for generation']
```

Usage

```
{'run_text_generation_hpu': 'run text generation inference on Habana Gaudi using a pre-trained model with configurable batch size and tokens', 'run_generation_with_flash_attention': 'run text generation with Habana Flash Attention enabled for improved performance on HPU devices', 'run_generation_with_quantization': 'run text generation using a quantized model loaded via AutoGPTQ, AutoAWQ, BnB NF4, or INC', 'run_generation_with_profiling': 'run text generation with Habana profiling enabled to capture warmup and active steps for performance analysis', 'run_generation_with_dataset': 'run text generation benchmark over a Hugging Face Hub dataset with configurable column and sample limits'}
```

## File: huggingface_optimum-habana/examples/text-generation/run_lm_eval.py

Prompts

```
['create a HabanaModelAdapter instance wrapping a HuggingFace causal LM for HPU-accelerated evaluation', 'run a forward pass through the Habana model to get logits from input token IDs', 'generate text completions for a list of lm-eval harness instances using the Habana adapter', 'warm up the Habana model by running dummy inputs through all configured bucket sizes', 'find the smallest bucket size greater than or equal to a given sequence length', 'run text generation inference on Habana Gaudi using a pre-trained model with configurable batch size and tokens', 'run text generation with Habana Flash Attention enabled for improved performance on HPU devices', 'run text generation using a quantized model loaded via AutoGPTQ, AutoAWQ, BnB NF4, or INC', 'run text generation with Habana profiling enabled to capture warmup and active steps for performance analysis', 'run text generation benchmark over a Hugging Face Hub dataset with configurable column and sample limits', 'run lm-eval benchmark tasks like hellaswag and lambada on an HPU device with a language model', 'run lm-eval with few-shot examples as multi-turn conversations using a chat template on HPU', 'run lm-eval on a quantized model on HPU and save the quantized model with INC', 'create an argparse parser for lm-eval with tasks, limits, buckets, and chat template options', 'review the LimitedSpawnPool function that creates a spawn-context multiprocessing pool sized for HPU multinode', 'initialize a HuggingFace causal LM model for text generation on Intel Gaudi HPU with optional DeepSpeed or tensor parallelism', 'adjust a batch dictionary of input_ids and attention_mask tensors to a target sequence size by truncating or padding', "compile a model's transformer module with torch.compile using the hpu_backend for Gaudi acceleration", 'setup FP8 quantization on a model using neural_compressor with a JSON config for measure or quantize modes', 'setup a tokenizer for a Llama model with proper pad, eos, and bos token configuration for generation']
```

Usage

```
{'run_lm_eval_on_hpu': 'run lm-eval benchmark tasks like hellaswag and lambada on an HPU device with a language model', 'run_lm_eval_with_fewshot': 'run lm-eval with few-shot examples as multi-turn conversations using a chat template on HPU', 'run_lm_eval_with_quantization': 'run lm-eval on a quantized model on HPU and save the quantized model with INC', 'setup_lm_eval_parser': 'create an argparse parser for lm-eval with tasks, limits, buckets, and chat template options', 'review_LimitedSpawnPool': 'review the LimitedSpawnPool function that creates a spawn-context multiprocessing pool sized for HPU multinode'}
```

## File: huggingface_optimum-habana/examples/text-generation/utils.py

Prompts

```
['create a HabanaModelAdapter instance wrapping a HuggingFace causal LM for HPU-accelerated evaluation', 'run a forward pass through the Habana model to get logits from input token IDs', 'generate text completions for a list of lm-eval harness instances using the Habana adapter', 'warm up the Habana model by running dummy inputs through all configured bucket sizes', 'find the smallest bucket size greater than or equal to a given sequence length', 'run text generation inference on Habana Gaudi using a pre-trained model with configurable batch size and tokens', 'run text generation with Habana Flash Attention enabled for improved performance on HPU devices', 'run text generation using a quantized model loaded via AutoGPTQ, AutoAWQ, BnB NF4, or INC', 'run text generation with Habana profiling enabled to capture warmup and active steps for performance analysis', 'run text generation benchmark over a Hugging Face Hub dataset with configurable column and sample limits', 'run lm-eval benchmark tasks like hellaswag and lambada on an HPU device with a language model', 'run lm-eval with few-shot examples as multi-turn conversations using a chat template on HPU', 'run lm-eval on a quantized model on HPU and save the quantized model with INC', 'create an argparse parser for lm-eval with tasks, limits, buckets, and chat template options', 'review the LimitedSpawnPool function that creates a spawn-context multiprocessing pool sized for HPU multinode', 'initialize a HuggingFace causal LM model for text generation on Intel Gaudi HPU with optional DeepSpeed or tensor parallelism', 'adjust a batch dictionary of input_ids and attention_mask tensors to a target sequence size by truncating or padding', "compile a model's transformer module with torch.compile using the hpu_backend for Gaudi acceleration", 'setup FP8 quantization on a model using neural_compressor with a JSON config for measure or quantize modes', 'setup a tokenizer for a Llama model with proper pad, eos, and bos token configuration for generation']
```

Usage

```
{'initialize_model_hpu': 'initialize a HuggingFace causal LM model for text generation on Intel Gaudi HPU with optional DeepSpeed or tensor parallelism', 'adjust_batch_size': 'adjust a batch dictionary of input_ids and attention_mask tensors to a target sequence size by truncating or padding', 'compile_model_torch': "compile a model's transformer module with torch.compile using the hpu_backend for Gaudi acceleration", 'setup_quantization_fp8': 'setup FP8 quantization on a model using neural_compressor with a JSON config for measure or quantize modes', 'setup_tokenizer_llama': 'setup a tokenizer for a Llama model with proper pad, eos, and bos token configuration for generation'}
```

