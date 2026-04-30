# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/examples/quantizing_moe/deepseek_r1_example.py

Prompts

```
['quantize a DeepSeek MoE model using GPTQ with W4A16 scheme and ignore MoE gate layers', 'load a large language model from HuggingFace with AutoModelForCausalLM and apply BF16 dtype', 'calibrate a quantization model using ultrachat_200k dataset with GPTQ oneshot pipeline', 'preprocess a chat dataset by applying tokenizer chat templates and tokenizing samples', 'save a quantized language model and tokenizer to disk in compressed format', 'run oneshot quantization on a GLM-4.7 MoE model using AWQModifier with W4A16 scheme', 'create an AWQModifier recipe targeting Linear layers with W4A16 quantization scheme and ignore patterns', 'tokenize a calibration dataset with max sequence length truncation and no padding', 'save a quantized model and tokenizer to disk in compressed format', 'create an AWQModifier recipe targeting Linear layers with W4A16 scheme and ignore patterns', 'build a CalibrationGlmMoeDsaMoE module to unpack fused MoE expert weights for quantization', 'test preprocessing a chat dataset with tokenizer apply_chat_template for calibration', 'summarize tokenizing calibration samples with truncation and max sequence length', 'run FP8 quantization on a Mixtral MoE model using llmcompressor oneshot with calibration data', 'create a QuantizationModifier recipe targeting Linear layers while ignoring MoE gate and lm_head', 'create a GPTQModifier recipe to quantize Linear layers with FP8 scheme while ignoring MoE gate layers', 'test dispatch_model to offload a quantized MoE model for inference', 'build a causal language model from pretrained Qwen MoE weights with bfloat16 dtype', 'summarize the full pipeline to quantize a Mixture of Experts model with GPTQ and save compressed output']
```

Usage

```
{'quantize_moe_model_gptq': 'quantize a DeepSeek MoE model using GPTQ with W4A16 scheme and ignore MoE gate layers', 'load_llm_model_pretrained': 'load a large language model from HuggingFace with AutoModelForCausalLM and apply BF16 dtype', 'calibrate_dataset_gptq': 'calibrate a quantization model using ultrachat_200k dataset with GPTQ oneshot pipeline', 'preprocess_chat_dataset': 'preprocess a chat dataset by applying tokenizer chat templates and tokenizing samples', 'save_quantized_model_compressed': 'save a quantized language model and tokenizer to disk in compressed format'}
```

## File: vllm-project_llm-compressor/examples/quantizing_moe/glm4_7_example.py

Prompts

```
['quantize a DeepSeek MoE model using GPTQ with W4A16 scheme and ignore MoE gate layers', 'load a large language model from HuggingFace with AutoModelForCausalLM and apply BF16 dtype', 'calibrate a quantization model using ultrachat_200k dataset with GPTQ oneshot pipeline', 'preprocess a chat dataset by applying tokenizer chat templates and tokenizing samples', 'save a quantized language model and tokenizer to disk in compressed format', 'run oneshot quantization on a GLM-4.7 MoE model using AWQModifier with W4A16 scheme', 'create an AWQModifier recipe targeting Linear layers with W4A16 quantization scheme and ignore patterns', 'tokenize a calibration dataset with max sequence length truncation and no padding', 'save a quantized model and tokenizer to disk in compressed format', 'create an AWQModifier recipe targeting Linear layers with W4A16 scheme and ignore patterns', 'build a CalibrationGlmMoeDsaMoE module to unpack fused MoE expert weights for quantization', 'test preprocessing a chat dataset with tokenizer apply_chat_template for calibration', 'summarize tokenizing calibration samples with truncation and max sequence length', 'run FP8 quantization on a Mixtral MoE model using llmcompressor oneshot with calibration data', 'create a QuantizationModifier recipe targeting Linear layers while ignoring MoE gate and lm_head', 'create a GPTQModifier recipe to quantize Linear layers with FP8 scheme while ignoring MoE gate layers', 'test dispatch_model to offload a quantized MoE model for inference', 'build a causal language model from pretrained Qwen MoE weights with bfloat16 dtype', 'summarize the full pipeline to quantize a Mixture of Experts model with GPTQ and save compressed output']
```

Usage

```
{'run_oneshot_quantization': 'run oneshot quantization on a GLM-4.7 MoE model using AWQModifier with W4A16 scheme', 'create_awq_modifier_recipe': 'create an AWQModifier recipe targeting Linear layers with W4A16 quantization scheme and ignore patterns', 'preprocess_chat_dataset': 'preprocess a chat dataset by applying a tokenizer chat template to convert messages to text', 'tokenize_calibration_dataset': 'tokenize a calibration dataset with max sequence length truncation and no padding', 'save_quantized_model': 'save a quantized model and tokenizer to disk in compressed format'}
```

## File: vllm-project_llm-compressor/examples/quantizing_moe/glm5_example.py

Prompts

```
['quantize a DeepSeek MoE model using GPTQ with W4A16 scheme and ignore MoE gate layers', 'load a large language model from HuggingFace with AutoModelForCausalLM and apply BF16 dtype', 'calibrate a quantization model using ultrachat_200k dataset with GPTQ oneshot pipeline', 'preprocess a chat dataset by applying tokenizer chat templates and tokenizing samples', 'save a quantized language model and tokenizer to disk in compressed format', 'run oneshot quantization on a GLM-4.7 MoE model using AWQModifier with W4A16 scheme', 'create an AWQModifier recipe targeting Linear layers with W4A16 quantization scheme and ignore patterns', 'tokenize a calibration dataset with max sequence length truncation and no padding', 'save a quantized model and tokenizer to disk in compressed format', 'create an AWQModifier recipe targeting Linear layers with W4A16 scheme and ignore patterns', 'build a CalibrationGlmMoeDsaMoE module to unpack fused MoE expert weights for quantization', 'test preprocessing a chat dataset with tokenizer apply_chat_template for calibration', 'summarize tokenizing calibration samples with truncation and max sequence length', 'run FP8 quantization on a Mixtral MoE model using llmcompressor oneshot with calibration data', 'create a QuantizationModifier recipe targeting Linear layers while ignoring MoE gate and lm_head', 'create a GPTQModifier recipe to quantize Linear layers with FP8 scheme while ignoring MoE gate layers', 'test dispatch_model to offload a quantized MoE model for inference', 'build a causal language model from pretrained Qwen MoE weights with bfloat16 dtype', 'summarize the full pipeline to quantize a Mixture of Experts model with GPTQ and save compressed output']
```

Usage

```
{'run_oneshot_quantization': 'run oneshot quantization on a causal LM model with a calibration dataset and AWQ recipe', 'create_awq_modifier': 'create an AWQModifier recipe targeting Linear layers with W4A16 scheme and ignore patterns', 'build_glm_moe_calibration': 'build a CalibrationGlmMoeDsaMoE module to unpack fused MoE expert weights for quantization', 'test_preprocess_chat_dataset': 'test preprocessing a chat dataset with tokenizer apply_chat_template for calibration', 'summarize_tokenize_calibration': 'summarize tokenizing calibration samples with truncation and max sequence length'}
```

## File: vllm-project_llm-compressor/examples/quantizing_moe/mixtral_example.py

Prompts

```
['quantize a DeepSeek MoE model using GPTQ with W4A16 scheme and ignore MoE gate layers', 'load a large language model from HuggingFace with AutoModelForCausalLM and apply BF16 dtype', 'calibrate a quantization model using ultrachat_200k dataset with GPTQ oneshot pipeline', 'preprocess a chat dataset by applying tokenizer chat templates and tokenizing samples', 'save a quantized language model and tokenizer to disk in compressed format', 'run oneshot quantization on a GLM-4.7 MoE model using AWQModifier with W4A16 scheme', 'create an AWQModifier recipe targeting Linear layers with W4A16 quantization scheme and ignore patterns', 'tokenize a calibration dataset with max sequence length truncation and no padding', 'save a quantized model and tokenizer to disk in compressed format', 'create an AWQModifier recipe targeting Linear layers with W4A16 scheme and ignore patterns', 'build a CalibrationGlmMoeDsaMoE module to unpack fused MoE expert weights for quantization', 'test preprocessing a chat dataset with tokenizer apply_chat_template for calibration', 'summarize tokenizing calibration samples with truncation and max sequence length', 'run FP8 quantization on a Mixtral MoE model using llmcompressor oneshot with calibration data', 'create a QuantizationModifier recipe targeting Linear layers while ignoring MoE gate and lm_head', 'create a GPTQModifier recipe to quantize Linear layers with FP8 scheme while ignoring MoE gate layers', 'test dispatch_model to offload a quantized MoE model for inference', 'build a causal language model from pretrained Qwen MoE weights with bfloat16 dtype', 'summarize the full pipeline to quantize a Mixture of Experts model with GPTQ and save compressed output']
```

Usage

```
{'run_quantization_mixtral': 'run FP8 quantization on a Mixtral MoE model using llmcompressor oneshot with calibration data', 'create_quantization_recipe': 'create a QuantizationModifier recipe targeting Linear layers while ignoring MoE gate and lm_head', 'preprocess_chat_dataset': 'preprocess a HuggingFace chat dataset by applying a tokenizer chat template', 'tokenize_calibration_dataset': 'tokenize a calibration dataset with max sequence length truncation and no padding', 'save_quantized_model': 'save a quantized model and tokenizer to disk in compressed format'}
```

## File: vllm-project_llm-compressor/examples/quantizing_moe/qwen_example.py

Prompts

```
['quantize a DeepSeek MoE model using GPTQ with W4A16 scheme and ignore MoE gate layers', 'load a large language model from HuggingFace with AutoModelForCausalLM and apply BF16 dtype', 'calibrate a quantization model using ultrachat_200k dataset with GPTQ oneshot pipeline', 'preprocess a chat dataset by applying tokenizer chat templates and tokenizing samples', 'save a quantized language model and tokenizer to disk in compressed format', 'run oneshot quantization on a GLM-4.7 MoE model using AWQModifier with W4A16 scheme', 'create an AWQModifier recipe targeting Linear layers with W4A16 quantization scheme and ignore patterns', 'tokenize a calibration dataset with max sequence length truncation and no padding', 'save a quantized model and tokenizer to disk in compressed format', 'create an AWQModifier recipe targeting Linear layers with W4A16 scheme and ignore patterns', 'build a CalibrationGlmMoeDsaMoE module to unpack fused MoE expert weights for quantization', 'test preprocessing a chat dataset with tokenizer apply_chat_template for calibration', 'summarize tokenizing calibration samples with truncation and max sequence length', 'run FP8 quantization on a Mixtral MoE model using llmcompressor oneshot with calibration data', 'create a QuantizationModifier recipe targeting Linear layers while ignoring MoE gate and lm_head', 'create a GPTQModifier recipe to quantize Linear layers with FP8 scheme while ignoring MoE gate layers', 'test dispatch_model to offload a quantized MoE model for inference', 'build a causal language model from pretrained Qwen MoE weights with bfloat16 dtype', 'summarize the full pipeline to quantize a Mixture of Experts model with GPTQ and save compressed output']
```

Usage

```
{'create_gptq_quantization_recipe': 'create a GPTQModifier recipe to quantize Linear layers with FP8 scheme while ignoring MoE gate layers', 'run_oneshot_quantization': 'run oneshot quantization on a Qwen MoE model using a calibration dataset and GPTQ recipe', 'test_dispatch_model_offload': 'test dispatch_model to offload a quantized MoE model for inference', 'build_load_causal_lm_model': 'build a causal language model from pretrained Qwen MoE weights with bfloat16 dtype', 'summarize_quantize_moe_pipeline': 'summarize the full pipeline to quantize a Mixture of Experts model with GPTQ and save compressed output'}
```

