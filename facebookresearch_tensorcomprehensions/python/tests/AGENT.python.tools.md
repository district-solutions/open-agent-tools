# Agent Python Tools

- repo: facebookresearch/tensorcomprehensions
- repo_uri: https://github.com/facebookresearch/tensorcomprehensions

## File: facebookresearch_tensorcomprehensions/python/tests/test_caffe2.py

Prompts

```
['run the Caffe2 TcOp matmul test with hypothesis-based random inputs and gradient checks', 'run the Caffe2 TcOp matmul test with auto-tuned mapping options via tc.Tuner', 'create a Caffe2 TcOp operator with tensor comprehension definitions for forward and backward passes', 'tune a tensor comprehension kernel using tc.Tuner with TunerConfig generations, threads, and population size', 'initialize the Tensor Comprehensions Caffe2 ops library via dyndep.InitOpsLibrary or CONDA_PREFIX', 'compile a tensor comprehension kernel with naive mapping options for element-wise add on CUDA tensors', 'autotune and compile a tensor comprehension kernel starting from naive options with a tuner config', 'define multiple tensor comprehension kernels using make_naive_options_factory or make_autotuned_options_factory', 'create an autograd-compatible function from forward and backward tensor comprehension kernels using make_autograd', 'tune a tensor comprehension kernel with Tuner, save best options to cache file, and reload for reinforced tuning']
```

Usage

```
{'run_test_matmul': 'run the Caffe2 TcOp matmul test with hypothesis-based random inputs and gradient checks', 'run_test_matmul_tune_and_run': 'run the Caffe2 TcOp matmul test with auto-tuned mapping options via tc.Tuner', 'create_tc_operator': 'create a Caffe2 TcOp operator with tensor comprehension definitions for forward and backward passes', 'tune_tc_kernel': 'tune a tensor comprehension kernel using tc.Tuner with TunerConfig generations, threads, and population size', 'init_tc_ops_library': 'initialize the Tensor Comprehensions Caffe2 ops library via dyndep.InitOpsLibrary or CONDA_PREFIX'}
```

## File: facebookresearch_tensorcomprehensions/python/tests/test_tc.py

Prompts

```
['run the Caffe2 TcOp matmul test with hypothesis-based random inputs and gradient checks', 'run the Caffe2 TcOp matmul test with auto-tuned mapping options via tc.Tuner', 'create a Caffe2 TcOp operator with tensor comprehension definitions for forward and backward passes', 'tune a tensor comprehension kernel using tc.Tuner with TunerConfig generations, threads, and population size', 'initialize the Tensor Comprehensions Caffe2 ops library via dyndep.InitOpsLibrary or CONDA_PREFIX', 'compile a tensor comprehension kernel with naive mapping options for element-wise add on CUDA tensors', 'autotune and compile a tensor comprehension kernel starting from naive options with a tuner config', 'define multiple tensor comprehension kernels using make_naive_options_factory or make_autotuned_options_factory', 'create an autograd-compatible function from forward and backward tensor comprehension kernels using make_autograd', 'tune a tensor comprehension kernel with Tuner, save best options to cache file, and reload for reinforced tuning']
```

Usage

```
{'compile_tc_kernel_naive': 'compile a tensor comprehension kernel with naive mapping options for element-wise add on CUDA tensors', 'autotune_and_compile_tc': 'autotune and compile a tensor comprehension kernel starting from naive options with a tuner config', 'define_tc_with_factory': 'define multiple tensor comprehension kernels using make_naive_options_factory or make_autotuned_options_factory', 'make_autograd_tc': 'create an autograd-compatible function from forward and backward tensor comprehension kernels using make_autograd', 'tune_and_cache_tc': 'tune a tensor comprehension kernel with Tuner, save best options to cache file, and reload for reinforced tuning'}
```

