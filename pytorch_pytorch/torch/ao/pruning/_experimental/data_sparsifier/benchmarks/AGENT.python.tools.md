# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/pruning/_experimental/data_sparsifier/benchmarks/dlrm_utils.py

Prompts

```
['create a DLRM model using get_dlrm_model with configurable sparse or dense architecture', 'build a name sanitizer that replaces dots with underscores for data sparsifier compatibility', 'test the dlrm_wrap function that moves input tensors to a specified device', 'create a test data loader for the Kaggle Criteo dataset with configurable batch size and workers', 'fetch and load a DLRM model checkpoint from a zipped or raw file onto a target device', 'create a DataNormSparsifier and attach it to model embedding layers with configurable sparsity level, norm, and block shape', 'save a model state dictionary to disk with optional zip compression and return the file path and size in MB', 'sparsify a DLRM model embedding layers across multiple sparsity levels, norms, and block shapes and output results to CSV', 'run the evaluate_disk_savings CLI with --model-path and --sparsified-model-dump-path arguments', 'test the sparsify_model function to benchmark disk savings from data norm sparsification on DLRM embedding layers', 'run the forward pass of a DLRM model and return the average forward pass time over 100 iterations', 'create a sample test batch from raw and processed data files for benchmarking the model forward pass', 'measure and track forward pass times across all sparsity levels and block shapes from a metadata CSV file', 'test the evaluate_forward_time module with raw data, processed data, and sparse model metadata arguments', 'build a benchmark script that compares forward pass times between sparse and normal DLRM models', 'run the python module evaluate_model_metrics to evaluate sparsified DLRM model metrics from a metadata CSV', 'test the inference_and_evaluation function that runs inference on a DLRM model and returns accuracy, f1, auc, precision, recall metrics', 'test the evaluate_metrics function that evaluates sparsified DLRM models at various sparsity levels and saves results to CSV', 'summarize the inference_and_evaluation function that performs forward pass inference and computes sklearn metrics on a DLRM model', 'summarize the evaluate_metrics function that iterates over sparsified model metadata and outputs a metrics CSV file']
```

Usage

```
{'create_get_dlrm_model': 'create a DLRM model using get_dlrm_model with configurable sparse or dense architecture', 'build_get_valid_name': 'build a name sanitizer that replaces dots with underscores for data sparsifier compatibility', 'test_dlrm_wrap': 'test the dlrm_wrap function that moves input tensors to a specified device', 'create_make_test_data_loader': 'create a test data loader for the Kaggle Criteo dataset with configurable batch size and workers', 'fetch_model_checkpoint': 'fetch and load a DLRM model checkpoint from a zipped or raw file onto a target device'}
```

## File: pytorch_pytorch/torch/ao/pruning/_experimental/data_sparsifier/benchmarks/evaluate_disk_savings.py

Prompts

```
['create a DLRM model using get_dlrm_model with configurable sparse or dense architecture', 'build a name sanitizer that replaces dots with underscores for data sparsifier compatibility', 'test the dlrm_wrap function that moves input tensors to a specified device', 'create a test data loader for the Kaggle Criteo dataset with configurable batch size and workers', 'fetch and load a DLRM model checkpoint from a zipped or raw file onto a target device', 'create a DataNormSparsifier and attach it to model embedding layers with configurable sparsity level, norm, and block shape', 'save a model state dictionary to disk with optional zip compression and return the file path and size in MB', 'sparsify a DLRM model embedding layers across multiple sparsity levels, norms, and block shapes and output results to CSV', 'run the evaluate_disk_savings CLI with --model-path and --sparsified-model-dump-path arguments', 'test the sparsify_model function to benchmark disk savings from data norm sparsification on DLRM embedding layers', 'run the forward pass of a DLRM model and return the average forward pass time over 100 iterations', 'create a sample test batch from raw and processed data files for benchmarking the model forward pass', 'measure and track forward pass times across all sparsity levels and block shapes from a metadata CSV file', 'test the evaluate_forward_time module with raw data, processed data, and sparse model metadata arguments', 'build a benchmark script that compares forward pass times between sparse and normal DLRM models', 'run the python module evaluate_model_metrics to evaluate sparsified DLRM model metrics from a metadata CSV', 'test the inference_and_evaluation function that runs inference on a DLRM model and returns accuracy, f1, auc, precision, recall metrics', 'test the evaluate_metrics function that evaluates sparsified DLRM models at various sparsity levels and saves results to CSV', 'summarize the inference_and_evaluation function that performs forward pass inference and computes sklearn metrics on a DLRM model', 'summarize the evaluate_metrics function that iterates over sparsified model metadata and outputs a metrics CSV file']
```

Usage

```
{'create_attach_sparsifier': 'create a DataNormSparsifier and attach it to model embedding layers with configurable sparsity level, norm, and block shape', 'save_model_states': 'save a model state dictionary to disk with optional zip compression and return the file path and size in MB', 'sparsify_model': 'sparsify a DLRM model embedding layers across multiple sparsity levels, norms, and block shapes and output results to CSV', 'run_evaluate_disk_savings_cli': 'run the evaluate_disk_savings CLI with --model-path and --sparsified-model-dump-path arguments', 'test_sparsify_model': 'test the sparsify_model function to benchmark disk savings from data norm sparsification on DLRM embedding layers'}
```

## File: pytorch_pytorch/torch/ao/pruning/_experimental/data_sparsifier/benchmarks/evaluate_forward_time.py

Prompts

```
['create a DLRM model using get_dlrm_model with configurable sparse or dense architecture', 'build a name sanitizer that replaces dots with underscores for data sparsifier compatibility', 'test the dlrm_wrap function that moves input tensors to a specified device', 'create a test data loader for the Kaggle Criteo dataset with configurable batch size and workers', 'fetch and load a DLRM model checkpoint from a zipped or raw file onto a target device', 'create a DataNormSparsifier and attach it to model embedding layers with configurable sparsity level, norm, and block shape', 'save a model state dictionary to disk with optional zip compression and return the file path and size in MB', 'sparsify a DLRM model embedding layers across multiple sparsity levels, norms, and block shapes and output results to CSV', 'run the evaluate_disk_savings CLI with --model-path and --sparsified-model-dump-path arguments', 'test the sparsify_model function to benchmark disk savings from data norm sparsification on DLRM embedding layers', 'run the forward pass of a DLRM model and return the average forward pass time over 100 iterations', 'create a sample test batch from raw and processed data files for benchmarking the model forward pass', 'measure and track forward pass times across all sparsity levels and block shapes from a metadata CSV file', 'test the evaluate_forward_time module with raw data, processed data, and sparse model metadata arguments', 'build a benchmark script that compares forward pass times between sparse and normal DLRM models', 'run the python module evaluate_model_metrics to evaluate sparsified DLRM model metrics from a metadata CSV', 'test the inference_and_evaluation function that runs inference on a DLRM model and returns accuracy, f1, auc, precision, recall metrics', 'test the evaluate_metrics function that evaluates sparsified DLRM models at various sparsity levels and saves results to CSV', 'summarize the inference_and_evaluation function that performs forward pass inference and computes sklearn metrics on a DLRM model', 'summarize the evaluate_metrics function that iterates over sparsified model metadata and outputs a metrics CSV file']
```

Usage

```
{'run_forward_model': 'run the forward pass of a DLRM model and return the average forward pass time over 100 iterations', 'make_sample_test_batch': 'create a sample test batch from raw and processed data files for benchmarking the model forward pass', 'measure_forward_pass': 'measure and track forward pass times across all sparsity levels and block shapes from a metadata CSV file', 'test_evaluate_forward_time': 'test the evaluate_forward_time module with raw data, processed data, and sparse model metadata arguments', 'build_forward_time_benchmark': 'build a benchmark script that compares forward pass times between sparse and normal DLRM models'}
```

## File: pytorch_pytorch/torch/ao/pruning/_experimental/data_sparsifier/benchmarks/evaluate_model_metrics.py

Prompts

```
['create a DLRM model using get_dlrm_model with configurable sparse or dense architecture', 'build a name sanitizer that replaces dots with underscores for data sparsifier compatibility', 'test the dlrm_wrap function that moves input tensors to a specified device', 'create a test data loader for the Kaggle Criteo dataset with configurable batch size and workers', 'fetch and load a DLRM model checkpoint from a zipped or raw file onto a target device', 'create a DataNormSparsifier and attach it to model embedding layers with configurable sparsity level, norm, and block shape', 'save a model state dictionary to disk with optional zip compression and return the file path and size in MB', 'sparsify a DLRM model embedding layers across multiple sparsity levels, norms, and block shapes and output results to CSV', 'run the evaluate_disk_savings CLI with --model-path and --sparsified-model-dump-path arguments', 'test the sparsify_model function to benchmark disk savings from data norm sparsification on DLRM embedding layers', 'run the forward pass of a DLRM model and return the average forward pass time over 100 iterations', 'create a sample test batch from raw and processed data files for benchmarking the model forward pass', 'measure and track forward pass times across all sparsity levels and block shapes from a metadata CSV file', 'test the evaluate_forward_time module with raw data, processed data, and sparse model metadata arguments', 'build a benchmark script that compares forward pass times between sparse and normal DLRM models', 'run the python module evaluate_model_metrics to evaluate sparsified DLRM model metrics from a metadata CSV', 'test the inference_and_evaluation function that runs inference on a DLRM model and returns accuracy, f1, auc, precision, recall metrics', 'test the evaluate_metrics function that evaluates sparsified DLRM models at various sparsity levels and saves results to CSV', 'summarize the inference_and_evaluation function that performs forward pass inference and computes sklearn metrics on a DLRM model', 'summarize the evaluate_metrics function that iterates over sparsified model metadata and outputs a metrics CSV file']
```

Usage

```
{'run_evaluate_model_metrics': 'run the python module evaluate_model_metrics to evaluate sparsified DLRM model metrics from a metadata CSV', 'test_inference_and_evaluation': 'test the inference_and_evaluation function that runs inference on a DLRM model and returns accuracy, f1, auc, precision, recall metrics', 'test_evaluate_metrics': 'test the evaluate_metrics function that evaluates sparsified DLRM models at various sparsity levels and saves results to CSV', 'summarize_inference_and_evaluation': 'summarize the inference_and_evaluation function that performs forward pass inference and computes sklearn metrics on a DLRM model', 'summarize_evaluate_metrics': 'summarize the evaluate_metrics function that iterates over sparsified model metadata and outputs a metrics CSV file'}
```

