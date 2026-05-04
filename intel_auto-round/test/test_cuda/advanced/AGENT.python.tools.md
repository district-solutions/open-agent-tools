# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cuda/advanced/test_evaluation.py

Prompts

```
['test the auto_round CLI with --eval flag to evaluate a model using the HF backend', 'test auto_round quantization with iters=0 and HF backend evaluation on a model', 'test auto_round quantization with iters=0 and task-by-task evaluation across multiple tasks', 'run the TestHFEvaluation pytest class to validate all evaluation modes on CUDA', 'review the test_evaluation module to understand auto_round evaluation test coverage and skip conditions', 'run the auto_round CLI with multiple GPU devices for model calibration quantization', 'run the auto_round CLI with NVFP4 scheme across multiple GPUs with torch compile enabled', 'test AutoRound quantization using a regex-based device map string to assign layers to specific GPUs', 'test AutoRound activation quantization with custom device map dict and 4-bit act_bits across GPUs', 'test AutoRound multi-modal LLM device mapping with string, integer, auto, and dict device_map options']
```

Usage

```
{'test_eval_mode_hf_backend': 'test the auto_round CLI with --eval flag to evaluate a model using the HF backend', 'test_iters_0_hf_backend': 'test auto_round quantization with iters=0 and HF backend evaluation on a model', 'test_iters_0_task_by_task': 'test auto_round quantization with iters=0 and task-by-task evaluation across multiple tasks', 'run_test_hf_evaluation_class': 'run the TestHFEvaluation pytest class to validate all evaluation modes on CUDA', 'review_test_evaluation': 'review the test_evaluation module to understand auto_round evaluation test coverage and skip conditions'}
```

## File: intel_auto-round/test/test_cuda/advanced/test_multiple_card.py

Prompts

```
['test the auto_round CLI with --eval flag to evaluate a model using the HF backend', 'test auto_round quantization with iters=0 and HF backend evaluation on a model', 'test auto_round quantization with iters=0 and task-by-task evaluation across multiple tasks', 'run the TestHFEvaluation pytest class to validate all evaluation modes on CUDA', 'review the test_evaluation module to understand auto_round evaluation test coverage and skip conditions', 'run the auto_round CLI with multiple GPU devices for model calibration quantization', 'run the auto_round CLI with NVFP4 scheme across multiple GPUs with torch compile enabled', 'test AutoRound quantization using a regex-based device map string to assign layers to specific GPUs', 'test AutoRound activation quantization with custom device map dict and 4-bit act_bits across GPUs', 'test AutoRound multi-modal LLM device mapping with string, integer, auto, and dict device_map options']
```

Usage

```
{'test_autoround_cli_multi_card_calibration': 'run the auto_round CLI with multiple GPU devices for model calibration quantization', 'test_autoround_cli_nvfp4_quantization': 'run the auto_round CLI with NVFP4 scheme across multiple GPUs with torch compile enabled', 'test_autoround_device_map_string': 'test AutoRound quantization using a regex-based device map string to assign layers to specific GPUs', 'test_autoround_act_quantization': 'test AutoRound activation quantization with custom device map dict and 4-bit act_bits across GPUs', 'test_autoround_mllm_device_map': 'test AutoRound multi-modal LLM device mapping with string, integer, auto, and dict device_map options'}
```

