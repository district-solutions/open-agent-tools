# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/mobile_cv/model_zoo/tools/create_model.py

Prompts

```
['run the CLI to create a model from the model zoo with a specified builder and arch_name', 'create a model from the model zoo factory using a builder name and optional arch arguments', 'convert a PyTorch model to TorchScript JIT format with optional batch norm fusion', 'convert a PyTorch model to int8 quantized TorchScript using graph mode post-training quantization', 'print per-layer FLOPs for a model given input data shape using flops_utils', 'create a self-contained TorchScript model from a given model file and input data with bundled inputs', 'trace or script a PyTorch model and save it as a TorchScript file with optional lite format', 'load a JIT-compiled PyTorch model from a file path or directory with optional int8 quantization backend', 'load input data from a file or generate synthetic tensors based on a specified shape configuration', 'run optimize_for_mobile on a TorchScript model to prepare it for mobile deployment with preserved methods', 'run a benchmark on a TorchScript JIT model with specified input dimensions and thread count', 'run a JIT model benchmark with autograd profiling enabled to analyze per-op latency', 'run a JIT model benchmark on GPU with warmup iterations and garbage collection', 'run a JIT model benchmark using an int8 quantized backend like fbgemm', 'run a JIT model benchmark using input tensors loaded from a torch save file', 'run the model exporter CLI to export a task model to torchscript format in an output directory', 'export a PyTorch model to TorchScript format with optional mobile optimization and bundled inputs', 'export a PyTorch model to TorchScript int8 quantized format using post-training quantization', 'run the model exporter in batch mode to export multiple models in parallel using a multiprocessing pool', 'copy a file from source to destination skipping if the destination already exists', 'save a Python dictionary as a formatted JSON file with sorted keys and indentation', 'extract and validate the attrs dictionary from a PyTorch model module', "get a post-training quantized model using a task's get_quantized_model method with a data loader", 'get a post-training quantized model using the FX graph mode quantization backend with calibration']
```

Usage

```
{'run_create_model_cli': 'run the CLI to create a model from the model zoo with a specified builder and arch_name', 'create_model_from_zoo': 'create a model from the model zoo factory using a builder name and optional arch arguments', 'convert_model_to_jit': 'convert a PyTorch model to TorchScript JIT format with optional batch norm fusion', 'convert_model_to_int8': 'convert a PyTorch model to int8 quantized TorchScript using graph mode post-training quantization', 'print_model_flops': 'print per-layer FLOPs for a model given input data shape using flops_utils'}
```

## File: facebookresearch_mobile-vision/mobile_cv/model_zoo/tools/create_self_contained_model.py

Prompts

```
['run the CLI to create a model from the model zoo with a specified builder and arch_name', 'create a model from the model zoo factory using a builder name and optional arch arguments', 'convert a PyTorch model to TorchScript JIT format with optional batch norm fusion', 'convert a PyTorch model to int8 quantized TorchScript using graph mode post-training quantization', 'print per-layer FLOPs for a model given input data shape using flops_utils', 'create a self-contained TorchScript model from a given model file and input data with bundled inputs', 'trace or script a PyTorch model and save it as a TorchScript file with optional lite format', 'load a JIT-compiled PyTorch model from a file path or directory with optional int8 quantization backend', 'load input data from a file or generate synthetic tensors based on a specified shape configuration', 'run optimize_for_mobile on a TorchScript model to prepare it for mobile deployment with preserved methods', 'run a benchmark on a TorchScript JIT model with specified input dimensions and thread count', 'run a JIT model benchmark with autograd profiling enabled to analyze per-op latency', 'run a JIT model benchmark on GPU with warmup iterations and garbage collection', 'run a JIT model benchmark using an int8 quantized backend like fbgemm', 'run a JIT model benchmark using input tensors loaded from a torch save file', 'run the model exporter CLI to export a task model to torchscript format in an output directory', 'export a PyTorch model to TorchScript format with optional mobile optimization and bundled inputs', 'export a PyTorch model to TorchScript int8 quantized format using post-training quantization', 'run the model exporter in batch mode to export multiple models in parallel using a multiprocessing pool', 'copy a file from source to destination skipping if the destination already exists', 'save a Python dictionary as a formatted JSON file with sorted keys and indentation', 'extract and validate the attrs dictionary from a PyTorch model module', "get a post-training quantized model using a task's get_quantized_model method with a data loader", 'get a post-training quantized model using the FX graph mode quantization backend with calibration']
```

Usage

```
{'create_self_contained_model': 'create a self-contained TorchScript model from a given model file and input data with bundled inputs', 'trace_and_save_torchscript': 'trace or script a PyTorch model and save it as a TorchScript file with optional lite format', 'load_model': 'load a JIT-compiled PyTorch model from a file path or directory with optional int8 quantization backend', 'load_inputs': 'load input data from a file or generate synthetic tensors based on a specified shape configuration', 'optimize_for_mobile': 'run optimize_for_mobile on a TorchScript model to prepare it for mobile deployment with preserved methods'}
```

## File: facebookresearch_mobile-vision/mobile_cv/model_zoo/tools/jit_speed_benchmark.py

Prompts

```
['run the CLI to create a model from the model zoo with a specified builder and arch_name', 'create a model from the model zoo factory using a builder name and optional arch arguments', 'convert a PyTorch model to TorchScript JIT format with optional batch norm fusion', 'convert a PyTorch model to int8 quantized TorchScript using graph mode post-training quantization', 'print per-layer FLOPs for a model given input data shape using flops_utils', 'create a self-contained TorchScript model from a given model file and input data with bundled inputs', 'trace or script a PyTorch model and save it as a TorchScript file with optional lite format', 'load a JIT-compiled PyTorch model from a file path or directory with optional int8 quantization backend', 'load input data from a file or generate synthetic tensors based on a specified shape configuration', 'run optimize_for_mobile on a TorchScript model to prepare it for mobile deployment with preserved methods', 'run a benchmark on a TorchScript JIT model with specified input dimensions and thread count', 'run a JIT model benchmark with autograd profiling enabled to analyze per-op latency', 'run a JIT model benchmark on GPU with warmup iterations and garbage collection', 'run a JIT model benchmark using an int8 quantized backend like fbgemm', 'run a JIT model benchmark using input tensors loaded from a torch save file', 'run the model exporter CLI to export a task model to torchscript format in an output directory', 'export a PyTorch model to TorchScript format with optional mobile optimization and bundled inputs', 'export a PyTorch model to TorchScript int8 quantized format using post-training quantization', 'run the model exporter in batch mode to export multiple models in parallel using a multiprocessing pool', 'copy a file from source to destination skipping if the destination already exists', 'save a Python dictionary as a formatted JSON file with sorted keys and indentation', 'extract and validate the attrs dictionary from a PyTorch model module', "get a post-training quantized model using a task's get_quantized_model method with a data loader", 'get a post-training quantized model using the FX graph mode quantization backend with calibration']
```

Usage

```
{'run_jit_benchmark': 'run a benchmark on a TorchScript JIT model with specified input dimensions and thread count', 'run_benchmark_with_profiling': 'run a JIT model benchmark with autograd profiling enabled to analyze per-op latency', 'run_benchmark_on_gpu': 'run a JIT model benchmark on GPU with warmup iterations and garbage collection', 'run_benchmark_int8': 'run a JIT model benchmark using an int8 quantized backend like fbgemm', 'run_benchmark_from_file': 'run a JIT model benchmark using input tensors loaded from a torch save file'}
```

## File: facebookresearch_mobile-vision/mobile_cv/model_zoo/tools/model_exporter.py

Prompts

```
['run the CLI to create a model from the model zoo with a specified builder and arch_name', 'create a model from the model zoo factory using a builder name and optional arch arguments', 'convert a PyTorch model to TorchScript JIT format with optional batch norm fusion', 'convert a PyTorch model to int8 quantized TorchScript using graph mode post-training quantization', 'print per-layer FLOPs for a model given input data shape using flops_utils', 'create a self-contained TorchScript model from a given model file and input data with bundled inputs', 'trace or script a PyTorch model and save it as a TorchScript file with optional lite format', 'load a JIT-compiled PyTorch model from a file path or directory with optional int8 quantization backend', 'load input data from a file or generate synthetic tensors based on a specified shape configuration', 'run optimize_for_mobile on a TorchScript model to prepare it for mobile deployment with preserved methods', 'run a benchmark on a TorchScript JIT model with specified input dimensions and thread count', 'run a JIT model benchmark with autograd profiling enabled to analyze per-op latency', 'run a JIT model benchmark on GPU with warmup iterations and garbage collection', 'run a JIT model benchmark using an int8 quantized backend like fbgemm', 'run a JIT model benchmark using input tensors loaded from a torch save file', 'run the model exporter CLI to export a task model to torchscript format in an output directory', 'export a PyTorch model to TorchScript format with optional mobile optimization and bundled inputs', 'export a PyTorch model to TorchScript int8 quantized format using post-training quantization', 'run the model exporter in batch mode to export multiple models in parallel using a multiprocessing pool', 'copy a file from source to destination skipping if the destination already exists', 'save a Python dictionary as a formatted JSON file with sorted keys and indentation', 'extract and validate the attrs dictionary from a PyTorch model module', "get a post-training quantized model using a task's get_quantized_model method with a data loader", 'get a post-training quantized model using the FX graph mode quantization backend with calibration']
```

Usage

```
{'run_model_exporter_cli': 'run the model exporter CLI to export a task model to torchscript format in an output directory', 'export_to_torchscript': 'export a PyTorch model to TorchScript format with optional mobile optimization and bundled inputs', 'export_to_torchscript_int8': 'export a PyTorch model to TorchScript int8 quantized format using post-training quantization', 'trace_and_save_torchscript': 'trace a PyTorch model and save it as a TorchScript file with optional attributes and extra files', 'main_batch_mode': 'run the model exporter in batch mode to export multiple models in parallel using a multiprocessing pool'}
```

## File: facebookresearch_mobile-vision/mobile_cv/model_zoo/tools/utils.py

Prompts

```
['run the CLI to create a model from the model zoo with a specified builder and arch_name', 'create a model from the model zoo factory using a builder name and optional arch arguments', 'convert a PyTorch model to TorchScript JIT format with optional batch norm fusion', 'convert a PyTorch model to int8 quantized TorchScript using graph mode post-training quantization', 'print per-layer FLOPs for a model given input data shape using flops_utils', 'create a self-contained TorchScript model from a given model file and input data with bundled inputs', 'trace or script a PyTorch model and save it as a TorchScript file with optional lite format', 'load a JIT-compiled PyTorch model from a file path or directory with optional int8 quantization backend', 'load input data from a file or generate synthetic tensors based on a specified shape configuration', 'run optimize_for_mobile on a TorchScript model to prepare it for mobile deployment with preserved methods', 'run a benchmark on a TorchScript JIT model with specified input dimensions and thread count', 'run a JIT model benchmark with autograd profiling enabled to analyze per-op latency', 'run a JIT model benchmark on GPU with warmup iterations and garbage collection', 'run a JIT model benchmark using an int8 quantized backend like fbgemm', 'run a JIT model benchmark using input tensors loaded from a torch save file', 'run the model exporter CLI to export a task model to torchscript format in an output directory', 'export a PyTorch model to TorchScript format with optional mobile optimization and bundled inputs', 'export a PyTorch model to TorchScript int8 quantized format using post-training quantization', 'run the model exporter in batch mode to export multiple models in parallel using a multiprocessing pool', 'copy a file from source to destination skipping if the destination already exists', 'save a Python dictionary as a formatted JSON file with sorted keys and indentation', 'extract and validate the attrs dictionary from a PyTorch model module', "get a post-training quantized model using a task's get_quantized_model method with a data loader", 'get a post-training quantized model using the FX graph mode quantization backend with calibration']
```

Usage

```
{'copy_file_skip_exists': 'copy a file from source to destination skipping if the destination already exists', 'save_json_data': 'save a Python dictionary as a formatted JSON file with sorted keys and indentation', 'get_model_attributes': 'extract and validate the attrs dictionary from a PyTorch model module', 'get_ptq_model_task_quantized': "get a post-training quantized model using a task's get_quantized_model method with a data loader", 'get_ptq_model_fx_backend': 'get a post-training quantized model using the FX graph mode quantization backend with calibration'}
```

