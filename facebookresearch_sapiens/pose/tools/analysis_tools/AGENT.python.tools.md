# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/tools/analysis_tools/analyze_logs.py

Prompts

```
['plot training metric curves from JSON log files and save to an output image file', 'calculate average training iteration time per epoch from JSON log files', 'load JSON training logs and convert them to a dictionary keyed by epoch', 'review the plot_curve function that generates metric plots using matplotlib and seaborn', 'refactor the cal_train_time function to include or exclude outlier iterations', 'run a script to get FLOPs and parameter count from a model config file', 'run get_flops with a specified batch size to calculate average FLOPs across batches', 'run get_flops with the show-arch-info flag to display model architecture details', 'run get_flops with a custom input shape and device for model complexity analysis', 'run get_flops with cfg-options to override backbone depth or other config settings', 'check if a caught exception is any type of out of memory error including CUDA, cuDNN, or CPU', 'check if a caught exception is a CUDA out of memory RuntimeError', 'check if a caught exception is a cuDNN not supported error', 'check if a caught exception is a CPU allocator out of memory error', 'run garbage collection to free Torch CUDA memory and empty the cache', 'run the optimal batch size finder tool to find the best batch size for pose estimation models', 'run power scaling to find optimal batch size by doubling until OOM error is encountered', 'run object detection inference on images using a detector model with configurable test pipeline', 'prepare batch data for top-down pose estimator inference with bounding boxes and images', 'plot batch size versus seconds per image and FPS with error bars for performance analysis', 'run the print_config tool to display the full contents of an mmengine config file', 'run the print_config tool with --options to override specific config values before printing', 'parse command line arguments for a config file path and optional dict overrides', 'merge additional key-value options into an existing mmengine Config object', 'print the pretty formatted text representation of an mmengine Config object']
```

Usage

```
{'plot_training_curves': 'plot training metric curves from JSON log files and save to an output image file', 'calculate_train_time': 'calculate average training iteration time per epoch from JSON log files', 'load_json_logs': 'load JSON training logs and convert them to a dictionary keyed by epoch', 'review_plot_curve': 'review the plot_curve function that generates metric plots using matplotlib and seaborn', 'refactor_cal_train_time': 'refactor the cal_train_time function to include or exclude outlier iterations'}
```

## File: facebookresearch_sapiens/pose/tools/analysis_tools/get_flops.py

Prompts

```
['plot training metric curves from JSON log files and save to an output image file', 'calculate average training iteration time per epoch from JSON log files', 'load JSON training logs and convert them to a dictionary keyed by epoch', 'review the plot_curve function that generates metric plots using matplotlib and seaborn', 'refactor the cal_train_time function to include or exclude outlier iterations', 'run a script to get FLOPs and parameter count from a model config file', 'run get_flops with a specified batch size to calculate average FLOPs across batches', 'run get_flops with the show-arch-info flag to display model architecture details', 'run get_flops with a custom input shape and device for model complexity analysis', 'run get_flops with cfg-options to override backbone depth or other config settings', 'check if a caught exception is any type of out of memory error including CUDA, cuDNN, or CPU', 'check if a caught exception is a CUDA out of memory RuntimeError', 'check if a caught exception is a cuDNN not supported error', 'check if a caught exception is a CPU allocator out of memory error', 'run garbage collection to free Torch CUDA memory and empty the cache', 'run the optimal batch size finder tool to find the best batch size for pose estimation models', 'run power scaling to find optimal batch size by doubling until OOM error is encountered', 'run object detection inference on images using a detector model with configurable test pipeline', 'prepare batch data for top-down pose estimator inference with bounding boxes and images', 'plot batch size versus seconds per image and FPS with error bars for performance analysis', 'run the print_config tool to display the full contents of an mmengine config file', 'run the print_config tool with --options to override specific config values before printing', 'parse command line arguments for a config file path and optional dict overrides', 'merge additional key-value options into an existing mmengine Config object', 'print the pretty formatted text representation of an mmengine Config object']
```

Usage

```
{'run_get_flops': 'run a script to get FLOPs and parameter count from a model config file', 'run_get_flops_with_batch': 'run get_flops with a specified batch size to calculate average FLOPs across batches', 'run_get_flops_show_arch': 'run get_flops with the show-arch-info flag to display model architecture details', 'run_get_flops_custom_input': 'run get_flops with a custom input shape and device for model complexity analysis', 'run_get_flops_cfg_override': 'run get_flops with cfg-options to override backbone depth or other config settings'}
```

## File: facebookresearch_sapiens/pose/tools/analysis_tools/memory_error_utils.py

Prompts

```
['plot training metric curves from JSON log files and save to an output image file', 'calculate average training iteration time per epoch from JSON log files', 'load JSON training logs and convert them to a dictionary keyed by epoch', 'review the plot_curve function that generates metric plots using matplotlib and seaborn', 'refactor the cal_train_time function to include or exclude outlier iterations', 'run a script to get FLOPs and parameter count from a model config file', 'run get_flops with a specified batch size to calculate average FLOPs across batches', 'run get_flops with the show-arch-info flag to display model architecture details', 'run get_flops with a custom input shape and device for model complexity analysis', 'run get_flops with cfg-options to override backbone depth or other config settings', 'check if a caught exception is any type of out of memory error including CUDA, cuDNN, or CPU', 'check if a caught exception is a CUDA out of memory RuntimeError', 'check if a caught exception is a cuDNN not supported error', 'check if a caught exception is a CPU allocator out of memory error', 'run garbage collection to free Torch CUDA memory and empty the cache', 'run the optimal batch size finder tool to find the best batch size for pose estimation models', 'run power scaling to find optimal batch size by doubling until OOM error is encountered', 'run object detection inference on images using a detector model with configurable test pipeline', 'prepare batch data for top-down pose estimator inference with bounding boxes and images', 'plot batch size versus seconds per image and FPS with error bars for performance analysis', 'run the print_config tool to display the full contents of an mmengine config file', 'run the print_config tool with --options to override specific config values before printing', 'parse command line arguments for a config file path and optional dict overrides', 'merge additional key-value options into an existing mmengine Config object', 'print the pretty formatted text representation of an mmengine Config object']
```

Usage

```
{'check_is_oom_error': 'check if a caught exception is any type of out of memory error including CUDA, cuDNN, or CPU', 'check_is_cuda_out_of_memory': 'check if a caught exception is a CUDA out of memory RuntimeError', 'check_is_cudnn_snafu': 'check if a caught exception is a cuDNN not supported error', 'check_is_out_of_cpu_memory': 'check if a caught exception is a CPU allocator out of memory error', 'run_garbage_collection_cuda': 'run garbage collection to free Torch CUDA memory and empty the cache'}
```

## File: facebookresearch_sapiens/pose/tools/analysis_tools/optimal_batch_size.py

Prompts

```
['plot training metric curves from JSON log files and save to an output image file', 'calculate average training iteration time per epoch from JSON log files', 'load JSON training logs and convert them to a dictionary keyed by epoch', 'review the plot_curve function that generates metric plots using matplotlib and seaborn', 'refactor the cal_train_time function to include or exclude outlier iterations', 'run a script to get FLOPs and parameter count from a model config file', 'run get_flops with a specified batch size to calculate average FLOPs across batches', 'run get_flops with the show-arch-info flag to display model architecture details', 'run get_flops with a custom input shape and device for model complexity analysis', 'run get_flops with cfg-options to override backbone depth or other config settings', 'check if a caught exception is any type of out of memory error including CUDA, cuDNN, or CPU', 'check if a caught exception is a CUDA out of memory RuntimeError', 'check if a caught exception is a cuDNN not supported error', 'check if a caught exception is a CPU allocator out of memory error', 'run garbage collection to free Torch CUDA memory and empty the cache', 'run the optimal batch size finder tool to find the best batch size for pose estimation models', 'run power scaling to find optimal batch size by doubling until OOM error is encountered', 'run object detection inference on images using a detector model with configurable test pipeline', 'prepare batch data for top-down pose estimator inference with bounding boxes and images', 'plot batch size versus seconds per image and FPS with error bars for performance analysis', 'run the print_config tool to display the full contents of an mmengine config file', 'run the print_config tool with --options to override specific config values before printing', 'parse command line arguments for a config file path and optional dict overrides', 'merge additional key-value options into an existing mmengine Config object', 'print the pretty formatted text representation of an mmengine Config object']
```

Usage

```
{'run_optimal_batch_size_finder': 'run the optimal batch size finder tool to find the best batch size for pose estimation models', 'run_power_scaling_pose': 'run power scaling to find optimal batch size by doubling until OOM error is encountered', 'inference_detector': 'run object detection inference on images using a detector model with configurable test pipeline', 'prep_batch_inference_topdown': 'prepare batch data for top-down pose estimator inference with bounding boxes and images', 'plot_batch_performance': 'plot batch size versus seconds per image and FPS with error bars for performance analysis'}
```

## File: facebookresearch_sapiens/pose/tools/analysis_tools/print_config.py

Prompts

```
['plot training metric curves from JSON log files and save to an output image file', 'calculate average training iteration time per epoch from JSON log files', 'load JSON training logs and convert them to a dictionary keyed by epoch', 'review the plot_curve function that generates metric plots using matplotlib and seaborn', 'refactor the cal_train_time function to include or exclude outlier iterations', 'run a script to get FLOPs and parameter count from a model config file', 'run get_flops with a specified batch size to calculate average FLOPs across batches', 'run get_flops with the show-arch-info flag to display model architecture details', 'run get_flops with a custom input shape and device for model complexity analysis', 'run get_flops with cfg-options to override backbone depth or other config settings', 'check if a caught exception is any type of out of memory error including CUDA, cuDNN, or CPU', 'check if a caught exception is a CUDA out of memory RuntimeError', 'check if a caught exception is a cuDNN not supported error', 'check if a caught exception is a CPU allocator out of memory error', 'run garbage collection to free Torch CUDA memory and empty the cache', 'run the optimal batch size finder tool to find the best batch size for pose estimation models', 'run power scaling to find optimal batch size by doubling until OOM error is encountered', 'run object detection inference on images using a detector model with configurable test pipeline', 'prepare batch data for top-down pose estimator inference with bounding boxes and images', 'plot batch size versus seconds per image and FPS with error bars for performance analysis', 'run the print_config tool to display the full contents of an mmengine config file', 'run the print_config tool with --options to override specific config values before printing', 'parse command line arguments for a config file path and optional dict overrides', 'merge additional key-value options into an existing mmengine Config object', 'print the pretty formatted text representation of an mmengine Config object']
```

Usage

```
{'run_print_config': 'run the print_config tool to display the full contents of an mmengine config file', 'run_print_config_with_options': 'run the print_config tool with --options to override specific config values before printing', 'parse_args_CONFIG': 'parse command line arguments for a config file path and optional dict overrides', 'merge_config_from_dict': 'merge additional key-value options into an existing mmengine Config object', 'pretty_print_config': 'print the pretty formatted text representation of an mmengine Config object'}
```

