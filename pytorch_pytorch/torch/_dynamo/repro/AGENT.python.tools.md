# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/_dynamo/repro/after_aot.py

Prompts

```
['run a PyTorch Inductor repro script with run, minify, analyze, or minifier-query subcommands', 'minify a failing PyTorch Inductor repro graph to isolate the root cause of compilation errors', 'analyze a PyTorch Inductor repro graph for accuracy divergence between eager, compiled, and fp64 execution', 'wrap a compiler function to intercept and dump repro graphs after AOT autograd compilation', 'dump a checkpoint of a compiler graph state with example inputs to disk for later debugging', 'isolate a failing PyTorch graph by running it in a subprocess and returning whether it fails', 'test whether a PyTorch graph fails when compiled by Inductor with optional error string matching', 'run a TorchDynamo repro script to test compiled Fx GraphModule accuracy or errors', 'run the minifier on a TorchDynamo repro script to reduce graph size while preserving failures', 'wrap a compiler function to intercept Fx GraphModules and auto-generate repro scripts on failure', 'generate a standalone repro Python script string from a TorchDynamo Fx GraphModule and example inputs', 'save a TorchDynamo Fx GraphModule repro as a runnable Python file in the checkpoints directory']
```

Usage

```
{'run_repro_graph': 'run a PyTorch Inductor repro script with run, minify, analyze, or minifier-query subcommands', 'minify_inductor_repro': 'minify a failing PyTorch Inductor repro graph to isolate the root cause of compilation errors', 'analyze_inductor_accuracy': 'analyze a PyTorch Inductor repro graph for accuracy divergence between eager, compiled, and fp64 execution', 'wrap_compiler_debug_fn': 'wrap a compiler function to intercept and dump repro graphs after AOT autograd compilation', 'dump_compiler_checkpoint': 'dump a checkpoint of a compiler graph state with example inputs to disk for later debugging', 'isolate_failing_graph': 'isolate a failing PyTorch graph by running it in a subprocess and returning whether it fails', 'test_inductor_fails': 'test whether a PyTorch graph fails when compiled by Inductor with optional error string matching'}
```

## File: pytorch_pytorch/torch/_dynamo/repro/after_dynamo.py

Prompts

```
['run a PyTorch Inductor repro script with run, minify, analyze, or minifier-query subcommands', 'minify a failing PyTorch Inductor repro graph to isolate the root cause of compilation errors', 'analyze a PyTorch Inductor repro graph for accuracy divergence between eager, compiled, and fp64 execution', 'wrap a compiler function to intercept and dump repro graphs after AOT autograd compilation', 'dump a checkpoint of a compiler graph state with example inputs to disk for later debugging', 'isolate a failing PyTorch graph by running it in a subprocess and returning whether it fails', 'test whether a PyTorch graph fails when compiled by Inductor with optional error string matching', 'run a TorchDynamo repro script to test compiled Fx GraphModule accuracy or errors', 'run the minifier on a TorchDynamo repro script to reduce graph size while preserving failures', 'wrap a compiler function to intercept Fx GraphModules and auto-generate repro scripts on failure', 'generate a standalone repro Python script string from a TorchDynamo Fx GraphModule and example inputs', 'save a TorchDynamo Fx GraphModule repro as a runnable Python file in the checkpoints directory']
```

Usage

```
{'run_repro': 'run a TorchDynamo repro script to test compiled Fx GraphModule accuracy or errors', 'run_repro_minify': 'run the minifier on a TorchDynamo repro script to reduce graph size while preserving failures', 'wrap_backend_debug': 'wrap a compiler function to intercept Fx GraphModules and auto-generate repro scripts on failure', 'generate_dynamo_fx_repro_string': 'generate a standalone repro Python script string from a TorchDynamo Fx GraphModule and example inputs', 'dump_backend_repro_as_file': 'save a TorchDynamo Fx GraphModule repro as a runnable Python file in the checkpoints directory'}
```

