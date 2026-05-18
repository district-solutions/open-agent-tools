# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/cli/interactive_cli.py

Prompts

```
['run the MetaSeq interactive CLI to generate text from user prompts via command line', 'run the distributed worker to load a model and generate text from broadcasted prompts', 'run the input loop to collect multi-line user prompts with colored terminal display', 'review the worker_main function that handles distributed model loading and text generation', 'review the cli_main function that parses arguments and launches distributed inference workers', 'run an interactive text generation CLI using FasterTransformer with MPI distributed inference', 'generate text from token inputs using beam search, top-k, top-p, and temperature sampling parameters', 'measure the GPU execution time of a function using CUDA events and synchronization', 'review the generate function that preprocesses inputs, calls FasterTransformer forward, and decodes output tokens', 'refactor the main function to load int8 quantized weights and scales for inference acceleration', 'run the MetaSeq hosted generation API server locally using python -m metaseq.cli.interactive_hosted', 'run the dynamic batching loop to group and execute generation requests in optimized batches', 'run a POST request to the /completions endpoint to generate text completions via the API', 'run the CLI entry point to launch the hosted web UI for text generation', 'run the metaseq training loop on one or multiple GPUs with a given config', 'train the model for one epoch and return validation losses', 'evaluate the model on validation subsets and return the losses', 'validate the model and save checkpoints based on update intervals', 'parse CLI arguments and launch distributed training via cli_main', 'run the metaseq validation CLI to evaluate a model on a validation dataset subset', 'run the main validation function to load models and compute metrics on a dataset', 'load a model ensemble and task from a checkpoint path using checkpoint_utils', 'build a criterion from the task and saved configuration for validation evaluation', 'reduce and aggregate validation log outputs across distributed workers to compute final metrics']
```

Usage

```
{'run_interactive_cli': 'run the MetaSeq interactive CLI to generate text from user prompts via command line', 'run_worker_main': 'run the distributed worker to load a model and generate text from broadcasted prompts', 'run_input_loop': 'run the input loop to collect multi-line user prompts with colored terminal display', 'review_worker_main': 'review the worker_main function that handles distributed model loading and text generation', 'review_cli_main': 'review the cli_main function that parses arguments and launches distributed inference workers'}
```

## File: facebookresearch_metaseq/metaseq/cli/interactive_ft.py

Prompts

```
['run the MetaSeq interactive CLI to generate text from user prompts via command line', 'run the distributed worker to load a model and generate text from broadcasted prompts', 'run the input loop to collect multi-line user prompts with colored terminal display', 'review the worker_main function that handles distributed model loading and text generation', 'review the cli_main function that parses arguments and launches distributed inference workers', 'run an interactive text generation CLI using FasterTransformer with MPI distributed inference', 'generate text from token inputs using beam search, top-k, top-p, and temperature sampling parameters', 'measure the GPU execution time of a function using CUDA events and synchronization', 'review the generate function that preprocesses inputs, calls FasterTransformer forward, and decodes output tokens', 'refactor the main function to load int8 quantized weights and scales for inference acceleration', 'run the MetaSeq hosted generation API server locally using python -m metaseq.cli.interactive_hosted', 'run the dynamic batching loop to group and execute generation requests in optimized batches', 'run a POST request to the /completions endpoint to generate text completions via the API', 'run the CLI entry point to launch the hosted web UI for text generation', 'run the metaseq training loop on one or multiple GPUs with a given config', 'train the model for one epoch and return validation losses', 'evaluate the model on validation subsets and return the losses', 'validate the model and save checkpoints based on update intervals', 'parse CLI arguments and launch distributed training via cli_main', 'run the metaseq validation CLI to evaluate a model on a validation dataset subset', 'run the main validation function to load models and compute metrics on a dataset', 'load a model ensemble and task from a checkpoint path using checkpoint_utils', 'build a criterion from the task and saved configuration for validation evaluation', 'reduce and aggregate validation log outputs across distributed workers to compute final metrics']
```

Usage

```
{'run_interactive_generation': 'run an interactive text generation CLI using FasterTransformer with MPI distributed inference', 'generate_text_with_sampling': 'generate text from token inputs using beam search, top-k, top-p, and temperature sampling parameters', 'measure_cuda_function_time': 'measure the GPU execution time of a function using CUDA events and synchronization', 'review_generate_function': 'review the generate function that preprocesses inputs, calls FasterTransformer forward, and decodes output tokens', 'refactor_main_for_int8': 'refactor the main function to load int8 quantized weights and scales for inference acceleration'}
```

## File: facebookresearch_metaseq/metaseq/cli/interactive_hosted.py

Prompts

```
['run the MetaSeq interactive CLI to generate text from user prompts via command line', 'run the distributed worker to load a model and generate text from broadcasted prompts', 'run the input loop to collect multi-line user prompts with colored terminal display', 'review the worker_main function that handles distributed model loading and text generation', 'review the cli_main function that parses arguments and launches distributed inference workers', 'run an interactive text generation CLI using FasterTransformer with MPI distributed inference', 'generate text from token inputs using beam search, top-k, top-p, and temperature sampling parameters', 'measure the GPU execution time of a function using CUDA events and synchronization', 'review the generate function that preprocesses inputs, calls FasterTransformer forward, and decodes output tokens', 'refactor the main function to load int8 quantized weights and scales for inference acceleration', 'run the MetaSeq hosted generation API server locally using python -m metaseq.cli.interactive_hosted', 'run the dynamic batching loop to group and execute generation requests in optimized batches', 'run a POST request to the /completions endpoint to generate text completions via the API', 'run the CLI entry point to launch the hosted web UI for text generation', 'run the metaseq training loop on one or multiple GPUs with a given config', 'train the model for one epoch and return validation losses', 'evaluate the model on validation subsets and return the losses', 'validate the model and save checkpoints based on update intervals', 'parse CLI arguments and launch distributed training via cli_main', 'run the metaseq validation CLI to evaluate a model on a validation dataset subset', 'run the main validation function to load models and compute metrics on a dataset', 'load a model ensemble and task from a checkpoint path using checkpoint_utils', 'build a criterion from the task and saved configuration for validation evaluation', 'reduce and aggregate validation log outputs across distributed workers to compute final metrics']
```

Usage

```
{'run_interactive_hosted_server': 'run the MetaSeq hosted generation API server locally using python -m metaseq.cli.interactive_hosted', 'run_batching_loop': 'run the dynamic batching loop to group and execute generation requests in optimized batches', 'run_worker_main': 'run the worker main function to load a model and start the Flask generation server', 'run_completions_endpoint': 'run a POST request to the /completions endpoint to generate text completions via the API', 'run_cli_main': 'run the CLI entry point to launch the hosted web UI for text generation'}
```

## File: facebookresearch_metaseq/metaseq/cli/train.py

Prompts

```
['run the MetaSeq interactive CLI to generate text from user prompts via command line', 'run the distributed worker to load a model and generate text from broadcasted prompts', 'run the input loop to collect multi-line user prompts with colored terminal display', 'review the worker_main function that handles distributed model loading and text generation', 'review the cli_main function that parses arguments and launches distributed inference workers', 'run an interactive text generation CLI using FasterTransformer with MPI distributed inference', 'generate text from token inputs using beam search, top-k, top-p, and temperature sampling parameters', 'measure the GPU execution time of a function using CUDA events and synchronization', 'review the generate function that preprocesses inputs, calls FasterTransformer forward, and decodes output tokens', 'refactor the main function to load int8 quantized weights and scales for inference acceleration', 'run the MetaSeq hosted generation API server locally using python -m metaseq.cli.interactive_hosted', 'run the dynamic batching loop to group and execute generation requests in optimized batches', 'run a POST request to the /completions endpoint to generate text completions via the API', 'run the CLI entry point to launch the hosted web UI for text generation', 'run the metaseq training loop on one or multiple GPUs with a given config', 'train the model for one epoch and return validation losses', 'evaluate the model on validation subsets and return the losses', 'validate the model and save checkpoints based on update intervals', 'parse CLI arguments and launch distributed training via cli_main', 'run the metaseq validation CLI to evaluate a model on a validation dataset subset', 'run the main validation function to load models and compute metrics on a dataset', 'load a model ensemble and task from a checkpoint path using checkpoint_utils', 'build a criterion from the task and saved configuration for validation evaluation', 'reduce and aggregate validation log outputs across distributed workers to compute final metrics']
```

Usage

```
{'run_training': 'run the metaseq training loop on one or multiple GPUs with a given config', 'train_epoch': 'train the model for one epoch and return validation losses', 'validate_model': 'evaluate the model on validation subsets and return the losses', 'validate_and_save_checkpoint': 'validate the model and save checkpoints based on update intervals', 'run_cli_training': 'parse CLI arguments and launch distributed training via cli_main'}
```

## File: facebookresearch_metaseq/metaseq/cli/validate.py

Prompts

```
['run the MetaSeq interactive CLI to generate text from user prompts via command line', 'run the distributed worker to load a model and generate text from broadcasted prompts', 'run the input loop to collect multi-line user prompts with colored terminal display', 'review the worker_main function that handles distributed model loading and text generation', 'review the cli_main function that parses arguments and launches distributed inference workers', 'run an interactive text generation CLI using FasterTransformer with MPI distributed inference', 'generate text from token inputs using beam search, top-k, top-p, and temperature sampling parameters', 'measure the GPU execution time of a function using CUDA events and synchronization', 'review the generate function that preprocesses inputs, calls FasterTransformer forward, and decodes output tokens', 'refactor the main function to load int8 quantized weights and scales for inference acceleration', 'run the MetaSeq hosted generation API server locally using python -m metaseq.cli.interactive_hosted', 'run the dynamic batching loop to group and execute generation requests in optimized batches', 'run a POST request to the /completions endpoint to generate text completions via the API', 'run the CLI entry point to launch the hosted web UI for text generation', 'run the metaseq training loop on one or multiple GPUs with a given config', 'train the model for one epoch and return validation losses', 'evaluate the model on validation subsets and return the losses', 'validate the model and save checkpoints based on update intervals', 'parse CLI arguments and launch distributed training via cli_main', 'run the metaseq validation CLI to evaluate a model on a validation dataset subset', 'run the main validation function to load models and compute metrics on a dataset', 'load a model ensemble and task from a checkpoint path using checkpoint_utils', 'build a criterion from the task and saved configuration for validation evaluation', 'reduce and aggregate validation log outputs across distributed workers to compute final metrics']
```

Usage

```
{'run_validation_cli': 'run the metaseq validation CLI to evaluate a model on a validation dataset subset', 'run_main_validation': 'run the main validation function to load models and compute metrics on a dataset', 'load_model_ensemble': 'load a model ensemble and task from a checkpoint path using checkpoint_utils', 'build_criterion': 'build a criterion from the task and saved configuration for validation evaluation', 'reduce_metrics': 'reduce and aggregate validation log outputs across distributed workers to compute final metrics'}
```

