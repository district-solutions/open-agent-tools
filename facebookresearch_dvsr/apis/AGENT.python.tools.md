# Agent Python Tools

- repo: facebookresearch/dvsr
- repo_uri: https://github.com/facebookresearch/dvsr

## File: facebookresearch_dvsr/apis/inference.py

Prompts

```
['run video inference on a directory using the sliding window framework with a specified window size', 'run video inference on a directory using the recurrent framework without a sliding window', 'run video inference on long sequences by splitting them into segments with a max sequence length', 'pad a tensor sequence by flipping edge frames for sliding window inference with a given window size', 'review the video inference function to understand how it handles sliding window versus recurrent frameworks', 'test a PyTorch model on a single GPU using single_gpu_test with a data loader', 'test a PyTorch model across multiple GPUs using multi_gpu_test with gpu or cpu result collection', 'collect distributed test results from multiple GPUs to CPU using pickle files in a temp directory', 'collect distributed test results from multiple GPUs using GPU tensor communication and all_gather', 'review the test module functions for single and multi GPU model evaluation and result collection', 'train a PyTorch model using distributed training with config, dataset, and validation hooks', 'train a PyTorch model using single GPU training with config, dataset, and evaluation', 'initialize a random seed and broadcast it across all distributed training processes', 'set random seed for Python, NumPy, PyTorch, and CUDA for reproducible training', 'run distributed training with custom hooks, visualization, and checkpoint resume support']
```

Usage

```
{'run_video_inference_sliding_window': 'run video inference on a directory using the sliding window framework with a specified window size', 'run_video_inference_recurrent': 'run video inference on a directory using the recurrent framework without a sliding window', 'run_video_inference_segmented': 'run video inference on long sequences by splitting them into segments with a max sequence length', 'pad_sequence_tensor': 'pad a tensor sequence by flipping edge frames for sliding window inference with a given window size', 'review_video_inference': 'review the video inference function to understand how it handles sliding window versus recurrent frameworks'}
```

## File: facebookresearch_dvsr/apis/test.py

Prompts

```
['run video inference on a directory using the sliding window framework with a specified window size', 'run video inference on a directory using the recurrent framework without a sliding window', 'run video inference on long sequences by splitting them into segments with a max sequence length', 'pad a tensor sequence by flipping edge frames for sliding window inference with a given window size', 'review the video inference function to understand how it handles sliding window versus recurrent frameworks', 'test a PyTorch model on a single GPU using single_gpu_test with a data loader', 'test a PyTorch model across multiple GPUs using multi_gpu_test with gpu or cpu result collection', 'collect distributed test results from multiple GPUs to CPU using pickle files in a temp directory', 'collect distributed test results from multiple GPUs using GPU tensor communication and all_gather', 'review the test module functions for single and multi GPU model evaluation and result collection', 'train a PyTorch model using distributed training with config, dataset, and validation hooks', 'train a PyTorch model using single GPU training with config, dataset, and evaluation', 'initialize a random seed and broadcast it across all distributed training processes', 'set random seed for Python, NumPy, PyTorch, and CUDA for reproducible training', 'run distributed training with custom hooks, visualization, and checkpoint resume support']
```

Usage

```
{'test_model_single_gpu': 'test a PyTorch model on a single GPU using single_gpu_test with a data loader', 'test_model_multi_gpu': 'test a PyTorch model across multiple GPUs using multi_gpu_test with gpu or cpu result collection', 'collect_results_cpu': 'collect distributed test results from multiple GPUs to CPU using pickle files in a temp directory', 'collect_results_gpu': 'collect distributed test results from multiple GPUs using GPU tensor communication and all_gather', 'review_test_module': 'review the test module functions for single and multi GPU model evaluation and result collection'}
```

## File: facebookresearch_dvsr/apis/train.py

Prompts

```
['run video inference on a directory using the sliding window framework with a specified window size', 'run video inference on a directory using the recurrent framework without a sliding window', 'run video inference on long sequences by splitting them into segments with a max sequence length', 'pad a tensor sequence by flipping edge frames for sliding window inference with a given window size', 'review the video inference function to understand how it handles sliding window versus recurrent frameworks', 'test a PyTorch model on a single GPU using single_gpu_test with a data loader', 'test a PyTorch model across multiple GPUs using multi_gpu_test with gpu or cpu result collection', 'collect distributed test results from multiple GPUs to CPU using pickle files in a temp directory', 'collect distributed test results from multiple GPUs using GPU tensor communication and all_gather', 'review the test module functions for single and multi GPU model evaluation and result collection', 'train a PyTorch model using distributed training with config, dataset, and validation hooks', 'train a PyTorch model using single GPU training with config, dataset, and evaluation', 'initialize a random seed and broadcast it across all distributed training processes', 'set random seed for Python, NumPy, PyTorch, and CUDA for reproducible training', 'run distributed training with custom hooks, visualization, and checkpoint resume support']
```

Usage

```
{'train_model_distributed': 'train a PyTorch model using distributed training with config, dataset, and validation hooks', 'train_model_non_distributed': 'train a PyTorch model using single GPU training with config, dataset, and evaluation', 'init_random_seed': 'initialize a random seed and broadcast it across all distributed training processes', 'set_random_seed': 'set random seed for Python, NumPy, PyTorch, and CUDA for reproducible training', 'dist_train_with_hooks': 'run distributed training with custom hooks, visualization, and checkpoint resume support'}
```

