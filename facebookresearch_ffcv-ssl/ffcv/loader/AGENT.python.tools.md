# Agent Python Tools

- repo: facebookresearch/ffcv-ssl
- repo_uri: https://github.com/facebookresearch/ffcv-ssl

## File: facebookresearch_ffcv-ssl/ffcv/loader/epoch_iterator.py

Prompts

```
['create an EpochIterator thread that processes batches from a Loader with a given sample ordering sequence', 'run the EpochIterator background thread to process batches through the pipeline and push results to the output queue', 'run a single batch through all pipeline stages with CUDA stream synchronization and memory bank allocation', 'iterate over the EpochIterator to fetch the next batch result from the output queue with CUDA stream waiting', 'close the EpochIterator by setting the terminate event and exiting the memory context to free resources', 'create a Loader instance to load a .beton dataset with a specified batch size and traversal order', 'filter a Loader to keep only samples matching a user-defined boolean condition on a specific field', 'iterate over a Loader to yield batches of data in the specified traversal order per epoch', 'generate and compile stage code for pipeline operations using AST-based code generation and JIT compilation', 'configure a Loader with SEQUENTIAL, RANDOM, SEQUENTIAL_CONTIGUOUS, or QUASI_RANDOM traversal order options']
```

Usage

```
{'create_EpochIterator': 'create an EpochIterator thread that processes batches from a Loader with a given sample ordering sequence', 'run_EpochIterator_run': 'run the EpochIterator background thread to process batches through the pipeline and push results to the output queue', 'run_EpochIterator_run_pipeline': 'run a single batch through all pipeline stages with CUDA stream synchronization and memory bank allocation', 'iterate_EpochIterator_next': 'iterate over the EpochIterator to fetch the next batch result from the output queue with CUDA stream waiting', 'close_EpochIterator': 'close the EpochIterator by setting the terminate event and exiting the memory context to free resources'}
```

## File: facebookresearch_ffcv-ssl/ffcv/loader/loader.py

Prompts

```
['create an EpochIterator thread that processes batches from a Loader with a given sample ordering sequence', 'run the EpochIterator background thread to process batches through the pipeline and push results to the output queue', 'run a single batch through all pipeline stages with CUDA stream synchronization and memory bank allocation', 'iterate over the EpochIterator to fetch the next batch result from the output queue with CUDA stream waiting', 'close the EpochIterator by setting the terminate event and exiting the memory context to free resources', 'create a Loader instance to load a .beton dataset with a specified batch size and traversal order', 'filter a Loader to keep only samples matching a user-defined boolean condition on a specific field', 'iterate over a Loader to yield batches of data in the specified traversal order per epoch', 'generate and compile stage code for pipeline operations using AST-based code generation and JIT compilation', 'configure a Loader with SEQUENTIAL, RANDOM, SEQUENTIAL_CONTIGUOUS, or QUASI_RANDOM traversal order options']
```

Usage

```
{'create_loader_for_beton_dataset': 'create a Loader instance to load a .beton dataset with a specified batch size and traversal order', 'filter_loader_by_condition': 'filter a Loader to keep only samples matching a user-defined boolean condition on a specific field', 'iterate_loader_with_epoch_iterator': 'iterate over a Loader to yield batches of data in the specified traversal order per epoch', 'generate_code_for_pipeline_stages': 'generate and compile stage code for pipeline operations using AST-based code generation and JIT compilation', 'configure_order_option_for_loader': 'configure a Loader with SEQUENTIAL, RANDOM, SEQUENTIAL_CONTIGUOUS, or QUASI_RANDOM traversal order options'}
```

