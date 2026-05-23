# Agent Python Tools

- repo: facebookresearch/torchdim
- repo_uri: https://github.com/facebookresearch/torchdim

## File: facebookresearch_torchdim/third_party/functorch/examples/compilation/eager_fusion.py

Prompts

```
['create a TVM compiler using tvm_compile with target llvm and a tuning logfile', 'build an AOT-compiled function using aot_function with separate forward and backward TVM compilers', 'run the bench function to benchmark forward and backward passes over multiple iterations', 'run bench_jax to benchmark the equivalent computation using JAX JIT and grad', 'review the forward function f that multiplies two tensors and sums along dimension 0', 'run a benchmark comparing eager versus compiled module inference performance using timeit', 'create a compiled module from a PyTorch nn.Module using compiled_module with forward and backward compilers', 'test that a compiled module produces the same outputs and gradients as the original module', 'review the Foo nn.Module class that uses a Parameter and registered buffer in its forward pass', 'run a linear model training benchmark comparing PyTorch, NNC JIT, and TorchScript performance', 'create a functional model from a PyTorch module using functorch make_functional for manual gradient updates', 'run the nnc_jit compiler on a functional training step to optimize linear model training performance', 'train a multi-layer linear model with SGD optimizer using TorchScript JIT compilation', 'bench a training function by running warmup iterations then timing subsequent iterations', 'run the grad function from functorch to compute the gradient of f', 'run make_fx to trace a gradient function into an FX graph representation', 'run nnc_jit to compile a gradient function with NNC JIT optimization', 'run the f function to compute the sum of torch.sin on a tensor']
```

Usage

```
{'create_tvm_compiler': 'create a TVM compiler using tvm_compile with target llvm and a tuning logfile', 'build_aot_compiled_function': 'build an AOT-compiled function using aot_function with separate forward and backward TVM compilers', 'run_bench': 'run the bench function to benchmark forward and backward passes over multiple iterations', 'run_bench_jax': 'run bench_jax to benchmark the equivalent computation using JAX JIT and grad', 'review_f': 'review the forward function f that multiplies two tensors and sums along dimension 0'}
```

## File: facebookresearch_torchdim/third_party/functorch/examples/compilation/fuse_module.py

Prompts

```
['create a TVM compiler using tvm_compile with target llvm and a tuning logfile', 'build an AOT-compiled function using aot_function with separate forward and backward TVM compilers', 'run the bench function to benchmark forward and backward passes over multiple iterations', 'run bench_jax to benchmark the equivalent computation using JAX JIT and grad', 'review the forward function f that multiplies two tensors and sums along dimension 0', 'run a benchmark comparing eager versus compiled module inference performance using timeit', 'create a compiled module from a PyTorch nn.Module using compiled_module with forward and backward compilers', 'test that a compiled module produces the same outputs and gradients as the original module', 'review the Foo nn.Module class that uses a Parameter and registered buffer in its forward pass', 'run a linear model training benchmark comparing PyTorch, NNC JIT, and TorchScript performance', 'create a functional model from a PyTorch module using functorch make_functional for manual gradient updates', 'run the nnc_jit compiler on a functional training step to optimize linear model training performance', 'train a multi-layer linear model with SGD optimizer using TorchScript JIT compilation', 'bench a training function by running warmup iterations then timing subsequent iterations', 'run the grad function from functorch to compute the gradient of f', 'run make_fx to trace a gradient function into an FX graph representation', 'run nnc_jit to compile a gradient function with NNC JIT optimization', 'run the f function to compute the sum of torch.sin on a tensor']
```

Usage

```
{'run_compiled_module_benchmark': 'run a benchmark comparing eager versus compiled module inference performance using timeit', 'create_compiled_module': 'create a compiled module from a PyTorch nn.Module using compiled_module with forward and backward compilers', 'test_compiled_module_correctness': 'test that a compiled module produces the same outputs and gradients as the original module', 'create_tvm_compiler': 'create a TVM compiler for forward or backward passes using tvm_compile with an llvm target', 'review_Foo_module': 'review the Foo nn.Module class that uses a Parameter and registered buffer in its forward pass'}
```

## File: facebookresearch_torchdim/third_party/functorch/examples/compilation/linear_train.py

Prompts

```
['create a TVM compiler using tvm_compile with target llvm and a tuning logfile', 'build an AOT-compiled function using aot_function with separate forward and backward TVM compilers', 'run the bench function to benchmark forward and backward passes over multiple iterations', 'run bench_jax to benchmark the equivalent computation using JAX JIT and grad', 'review the forward function f that multiplies two tensors and sums along dimension 0', 'run a benchmark comparing eager versus compiled module inference performance using timeit', 'create a compiled module from a PyTorch nn.Module using compiled_module with forward and backward compilers', 'test that a compiled module produces the same outputs and gradients as the original module', 'review the Foo nn.Module class that uses a Parameter and registered buffer in its forward pass', 'run a linear model training benchmark comparing PyTorch, NNC JIT, and TorchScript performance', 'create a functional model from a PyTorch module using functorch make_functional for manual gradient updates', 'run the nnc_jit compiler on a functional training step to optimize linear model training performance', 'train a multi-layer linear model with SGD optimizer using TorchScript JIT compilation', 'bench a training function by running warmup iterations then timing subsequent iterations', 'run the grad function from functorch to compute the gradient of f', 'run make_fx to trace a gradient function into an FX graph representation', 'run nnc_jit to compile a gradient function with NNC JIT optimization', 'run the f function to compute the sum of torch.sin on a tensor']
```

Usage

```
{'run_linear_training_benchmark': 'run a linear model training benchmark comparing PyTorch, NNC JIT, and TorchScript performance', 'create_functional_model': 'create a functional model from a PyTorch module using functorch make_functional for manual gradient updates', 'run_nnc_jit_compilation': 'run the nnc_jit compiler on a functional training step to optimize linear model training performance', 'train_linear_model': 'train a multi-layer linear model with SGD optimizer using TorchScript JIT compilation', 'bench_training_function': 'bench a training function by running warmup iterations then timing subsequent iterations'}
```

## File: facebookresearch_torchdim/third_party/functorch/examples/compilation/simple_function.py

Prompts

```
['create a TVM compiler using tvm_compile with target llvm and a tuning logfile', 'build an AOT-compiled function using aot_function with separate forward and backward TVM compilers', 'run the bench function to benchmark forward and backward passes over multiple iterations', 'run bench_jax to benchmark the equivalent computation using JAX JIT and grad', 'review the forward function f that multiplies two tensors and sums along dimension 0', 'run a benchmark comparing eager versus compiled module inference performance using timeit', 'create a compiled module from a PyTorch nn.Module using compiled_module with forward and backward compilers', 'test that a compiled module produces the same outputs and gradients as the original module', 'review the Foo nn.Module class that uses a Parameter and registered buffer in its forward pass', 'run a linear model training benchmark comparing PyTorch, NNC JIT, and TorchScript performance', 'create a functional model from a PyTorch module using functorch make_functional for manual gradient updates', 'run the nnc_jit compiler on a functional training step to optimize linear model training performance', 'train a multi-layer linear model with SGD optimizer using TorchScript JIT compilation', 'bench a training function by running warmup iterations then timing subsequent iterations', 'run the grad function from functorch to compute the gradient of f', 'run make_fx to trace a gradient function into an FX graph representation', 'run nnc_jit to compile a gradient function with NNC JIT optimization', 'run the f function to compute the sum of torch.sin on a tensor']
```

Usage

```
{'run_bench': 'run the bench function to benchmark a callable with configurable iterations and warmup', 'run_grad_f': 'run the grad function from functorch to compute the gradient of f', 'run_make_fx': 'run make_fx to trace a gradient function into an FX graph representation', 'run_nnc_jit': 'run nnc_jit to compile a gradient function with NNC JIT optimization', 'run_f': 'run the f function to compute the sum of torch.sin on a tensor'}
```

