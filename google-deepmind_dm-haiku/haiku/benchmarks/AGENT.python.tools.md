# Agent Python Tools

- repo: google-deepmind/dm-haiku
- repo_uri: https://github.com/google-deepmind/dm-haiku

## File: google-deepmind_dm-haiku/haiku/benchmarks/eval_shape.py

Prompts

```
['run the google benchmark suite to benchmark eval_shape for Haiku models', 'benchmark the JAX trace of hk.init for an MLP or ResNet50 model using jax.eval_shape', 'benchmark the compiled hk.init for a Haiku model using hk.experimental.fast_eval_shape', 'create a benchmark for a custom Haiku model by decorating it with the init_benchmark decorator', 'review the init_benchmark decorator that transforms a model and registers slow and fast benchmark functions', 'run the init_benchmark decorator to benchmark trace compile and run timings of a Haiku model', 'benchmark the initialization trace compile and run of an MLP network with Haiku', 'benchmark the initialization trace compile and run of a ResNet50 network with Haiku', 'trace a Haiku model init function using jax.jit and compiler_ir to measure tracing performance', 'compile a Haiku model init function using jax.jit lower and compile to measure compilation time']
```

Usage

```
{'run_benchmark_eval_shape': 'run the google benchmark suite to benchmark eval_shape for Haiku models', 'benchmark_init_slow': 'benchmark the JAX trace of hk.init for an MLP or ResNet50 model using jax.eval_shape', 'benchmark_init_fast': 'benchmark the compiled hk.init for a Haiku model using hk.experimental.fast_eval_shape', 'create_benchmark_for_model': 'create a benchmark for a custom Haiku model by decorating it with the init_benchmark decorator', 'review_init_benchmark': 'review the init_benchmark decorator that transforms a model and registers slow and fast benchmark functions'}
```

## File: google-deepmind_dm-haiku/haiku/benchmarks/init.py

Prompts

```
['run the google benchmark suite to benchmark eval_shape for Haiku models', 'benchmark the JAX trace of hk.init for an MLP or ResNet50 model using jax.eval_shape', 'benchmark the compiled hk.init for a Haiku model using hk.experimental.fast_eval_shape', 'create a benchmark for a custom Haiku model by decorating it with the init_benchmark decorator', 'review the init_benchmark decorator that transforms a model and registers slow and fast benchmark functions', 'run the init_benchmark decorator to benchmark trace compile and run timings of a Haiku model', 'benchmark the initialization trace compile and run of an MLP network with Haiku', 'benchmark the initialization trace compile and run of a ResNet50 network with Haiku', 'trace a Haiku model init function using jax.jit and compiler_ir to measure tracing performance', 'compile a Haiku model init function using jax.jit lower and compile to measure compilation time']
```

Usage

```
{'run_init_benchmark': 'run the init_benchmark decorator to benchmark trace compile and run timings of a Haiku model', 'benchmark_mlp_init': 'benchmark the initialization trace compile and run of an MLP network with Haiku', 'benchmark_resnet50_init': 'benchmark the initialization trace compile and run of a ResNet50 network with Haiku', 'trace_benchmark_model': 'trace a Haiku model init function using jax.jit and compiler_ir to measure tracing performance', 'compile_benchmark_model': 'compile a Haiku model init function using jax.jit lower and compile to measure compilation time'}
```

