# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cuda/calibration/test_calib_dataset.py

Prompts

```
['test the AutoRound quantization with multiple comma-separated datasets for calibration', 'run AutoRound quantization on a model with specified bits, group size, and symmetry settings', 'create an AutoRound instance with a model path, dataset, and quantization hyperparameters', 'test AutoRound quantization using a comma-separated list of HuggingFace datasets', 'review the AutoRound quantization process with custom iterations and sequence length', 'test AutoRound quantization with a list of batch-encoded tokenizer inputs as calibration data', 'test AutoRound quantization with split input_ids tensors passed as a list dataset', 'test AutoRound quantization with batch-encoded inputs moved to the model device', 'review the TestCustomizedData pytest class and its three calibration data format test methods', 'summarize how AutoRound accepts different calibration data formats including lists, split tensors, and batch encodings']
```

Usage

```
{'test_combine_dataset': 'test the AutoRound quantization with multiple comma-separated datasets for calibration', 'run_autoround_quantize': 'run AutoRound quantization on a model with specified bits, group size, and symmetry settings', 'create_autoround_instance': 'create an AutoRound instance with a model path, dataset, and quantization hyperparameters', 'test_autoround_with_combined_datasets': 'test AutoRound quantization using a comma-separated list of HuggingFace datasets', 'review_autoround_quantization': 'review the AutoRound quantization process with custom iterations and sequence length'}
```

## File: intel_auto-round/test/test_cuda/calibration/test_customized_data.py

Prompts

```
['test the AutoRound quantization with multiple comma-separated datasets for calibration', 'run AutoRound quantization on a model with specified bits, group size, and symmetry settings', 'create an AutoRound instance with a model path, dataset, and quantization hyperparameters', 'test AutoRound quantization using a comma-separated list of HuggingFace datasets', 'review the AutoRound quantization process with custom iterations and sequence length', 'test AutoRound quantization with a list of batch-encoded tokenizer inputs as calibration data', 'test AutoRound quantization with split input_ids tensors passed as a list dataset', 'test AutoRound quantization with batch-encoded inputs moved to the model device', 'review the TestCustomizedData pytest class and its three calibration data format test methods', 'summarize how AutoRound accepts different calibration data formats including lists, split tensors, and batch encodings']
```

Usage

```
{'test_autoround_list_batch_encoding': 'test AutoRound quantization with a list of batch-encoded tokenizer inputs as calibration data', 'test_autoround_mixed_attention_mask': 'test AutoRound quantization with split input_ids tensors passed as a list dataset', 'test_autoround_batch_encoding': 'test AutoRound quantization with batch-encoded inputs moved to the model device', 'review_test_customized_data_class': 'review the TestCustomizedData pytest class and its three calibration data format test methods', 'summarize_autoround_calibration_patterns': 'summarize how AutoRound accepts different calibration data formats including lists, split tensors, and batch encodings'}
```

