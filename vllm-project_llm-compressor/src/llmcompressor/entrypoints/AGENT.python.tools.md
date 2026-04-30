# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/entrypoints/oneshot.py

Prompts

```
['run oneshot calibration on a pretrained model with a compression recipe and calibration dataset', 'create an Oneshot class instance to apply quantization or sparsification to a pretrained model', 'apply recipe modifiers to a model using a calibration dataloader via the Oneshot class', 'test oneshot calibration on an MoE model with all experts calibrated', 'summarize the available calibration pipeline options for oneshot model compression', 'run pre_process to prepare the model and processor for calibration with model and dataset arguments', 'run post_process to save the compressed model and processor to the output directory', 'build initialize_model_from_path to load a pretrained causal LM model from a given path with config and dtype', 'build initialize_processor_from_path to load a transformer processor from a model path with fast fallback', 'review pre_process to understand model initialization, processor loading, and save_pretrained patching for compression workflows']
```

Usage

```
{'run_oneshot_calibrate_model': 'run oneshot calibration on a pretrained model with a compression recipe and calibration dataset', 'create_oneshot_class_instance': 'create an Oneshot class instance to apply quantization or sparsification to a pretrained model', 'apply_recipe_modifiers_calibrate': 'apply recipe modifiers to a model using a calibration dataloader via the Oneshot class', 'test_oneshot_with_moe_model': 'test oneshot calibration on an MoE model with all experts calibrated', 'summarize_oneshot_pipeline_options': 'summarize the available calibration pipeline options for oneshot model compression'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/entrypoints/utils.py

Prompts

```
['run oneshot calibration on a pretrained model with a compression recipe and calibration dataset', 'create an Oneshot class instance to apply quantization or sparsification to a pretrained model', 'apply recipe modifiers to a model using a calibration dataloader via the Oneshot class', 'test oneshot calibration on an MoE model with all experts calibrated', 'summarize the available calibration pipeline options for oneshot model compression', 'run pre_process to prepare the model and processor for calibration with model and dataset arguments', 'run post_process to save the compressed model and processor to the output directory', 'build initialize_model_from_path to load a pretrained causal LM model from a given path with config and dtype', 'build initialize_processor_from_path to load a transformer processor from a model path with fast fallback', 'review pre_process to understand model initialization, processor loading, and save_pretrained patching for compression workflows']
```

Usage

```
{'run_pre_process': 'run pre_process to prepare the model and processor for calibration with model and dataset arguments', 'run_post_process': 'run post_process to save the compressed model and processor to the output directory', 'build_initialize_model_from_path': 'build initialize_model_from_path to load a pretrained causal LM model from a given path with config and dtype', 'build_initialize_processor_from_path': 'build initialize_processor_from_path to load a transformer processor from a model path with fast fallback', 'review_pre_process': 'review pre_process to understand model initialization, processor loading, and save_pretrained patching for compression workflows'}
```

