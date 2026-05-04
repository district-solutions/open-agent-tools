# Agent Python Tools

- repo: facebookresearch/dlrm
- repo_uri: https://github.com/facebookresearch/dlrm

## File: facebookresearch_dlrm/torchrec_dlrm/aws_component.py

Prompts

```
['run the DLRM training job with 8 trainers on a single AWS p4d instance using default settings', 'run the DLRM training job with 16 trainers spanning 2 hosts using multiples of 8', 'run the DLRM training job with custom script arguments passed to dlrm_main.py entrypoint', 'review the run_dlrm_main function to understand how it configures DDP training on AWS p4d instances', 'refactor the run_dlrm_main function to support configurable CPU and GPU resource allocation per node', 'run the DLRM model training on Criteo dataset with configurable epochs and batch size', 'run the DLRM-DCN model training with deep and cross network interaction layers', 'run the DLRM-Projection model training with dual branch interaction architecture', 'run the DLRM training with multi-hot encoding for sparse features using pareto distribution', 'run the DLRM training using the Adagrad optimizer with fused backward pass updates', 'create a LRPolicyScheduler with warmup steps, decay start step, and decay steps for an optimizer', 'build a learning rate schedule that linearly warms up from zero over a specified number of steps', 'build a learning rate schedule that quadratically decays the learning rate over a specified number of steps', 'review the LRPolicyScheduler get_lr method that returns the current learning rate based on step count', 'test the LRPolicyScheduler constructor validation that ensures warmup finishes before decay starts', 'create a Multihot instance with uniform or pareto distribution to convert 1-hot sparse features to multi-hot', 'convert a torchrec Batch with 1-hot sparse features into a multi-hot Batch using convert_to_multi_hot', 'save pre-hash and post-hash frequency statistics as numpy files using save_freqs_stats', 'pause frequency stats collection during validation by calling pause_stats_collection_during_val_and_test with a model', 'create a RestartableMap iterator that applies a function to each element of a source iterable']
```

Usage

```
{'run_dlrm_main_default': 'run the DLRM training job with 8 trainers on a single AWS p4d instance using default settings', 'run_dlrm_main_multi_host': 'run the DLRM training job with 16 trainers spanning 2 hosts using multiples of 8', 'run_dlrm_main_custom_args': 'run the DLRM training job with custom script arguments passed to dlrm_main.py entrypoint', 'review_run_dlrm_main': 'review the run_dlrm_main function to understand how it configures DDP training on AWS p4d instances', 'refactor_run_dlrm_main': 'refactor the run_dlrm_main function to support configurable CPU and GPU resource allocation per node'}
```

## File: facebookresearch_dlrm/torchrec_dlrm/dlrm_main.py

Prompts

```
['run the DLRM training job with 8 trainers on a single AWS p4d instance using default settings', 'run the DLRM training job with 16 trainers spanning 2 hosts using multiples of 8', 'run the DLRM training job with custom script arguments passed to dlrm_main.py entrypoint', 'review the run_dlrm_main function to understand how it configures DDP training on AWS p4d instances', 'refactor the run_dlrm_main function to support configurable CPU and GPU resource allocation per node', 'run the DLRM model training on Criteo dataset with configurable epochs and batch size', 'run the DLRM-DCN model training with deep and cross network interaction layers', 'run the DLRM-Projection model training with dual branch interaction architecture', 'run the DLRM training with multi-hot encoding for sparse features using pareto distribution', 'run the DLRM training using the Adagrad optimizer with fused backward pass updates', 'create a LRPolicyScheduler with warmup steps, decay start step, and decay steps for an optimizer', 'build a learning rate schedule that linearly warms up from zero over a specified number of steps', 'build a learning rate schedule that quadratically decays the learning rate over a specified number of steps', 'review the LRPolicyScheduler get_lr method that returns the current learning rate based on step count', 'test the LRPolicyScheduler constructor validation that ensures warmup finishes before decay starts', 'create a Multihot instance with uniform or pareto distribution to convert 1-hot sparse features to multi-hot', 'convert a torchrec Batch with 1-hot sparse features into a multi-hot Batch using convert_to_multi_hot', 'save pre-hash and post-hash frequency statistics as numpy files using save_freqs_stats', 'pause frequency stats collection during validation by calling pause_stats_collection_during_val_and_test with a model', 'create a RestartableMap iterator that applies a function to each element of a source iterable']
```

Usage

```
{'run_dlrm_training': 'run the DLRM model training on Criteo dataset with configurable epochs and batch size', 'run_dlrm_with_dcn': 'run the DLRM-DCN model training with deep and cross network interaction layers', 'run_dlrm_with_projection': 'run the DLRM-Projection model training with dual branch interaction architecture', 'run_dlrm_multi_hot': 'run the DLRM training with multi-hot encoding for sparse features using pareto distribution', 'run_dlrm_adagrad': 'run the DLRM training using the Adagrad optimizer with fused backward pass updates'}
```

## File: facebookresearch_dlrm/torchrec_dlrm/lr_scheduler.py

Prompts

```
['run the DLRM training job with 8 trainers on a single AWS p4d instance using default settings', 'run the DLRM training job with 16 trainers spanning 2 hosts using multiples of 8', 'run the DLRM training job with custom script arguments passed to dlrm_main.py entrypoint', 'review the run_dlrm_main function to understand how it configures DDP training on AWS p4d instances', 'refactor the run_dlrm_main function to support configurable CPU and GPU resource allocation per node', 'run the DLRM model training on Criteo dataset with configurable epochs and batch size', 'run the DLRM-DCN model training with deep and cross network interaction layers', 'run the DLRM-Projection model training with dual branch interaction architecture', 'run the DLRM training with multi-hot encoding for sparse features using pareto distribution', 'run the DLRM training using the Adagrad optimizer with fused backward pass updates', 'create a LRPolicyScheduler with warmup steps, decay start step, and decay steps for an optimizer', 'build a learning rate schedule that linearly warms up from zero over a specified number of steps', 'build a learning rate schedule that quadratically decays the learning rate over a specified number of steps', 'review the LRPolicyScheduler get_lr method that returns the current learning rate based on step count', 'test the LRPolicyScheduler constructor validation that ensures warmup finishes before decay starts', 'create a Multihot instance with uniform or pareto distribution to convert 1-hot sparse features to multi-hot', 'convert a torchrec Batch with 1-hot sparse features into a multi-hot Batch using convert_to_multi_hot', 'save pre-hash and post-hash frequency statistics as numpy files using save_freqs_stats', 'pause frequency stats collection during validation by calling pause_stats_collection_during_val_and_test with a model', 'create a RestartableMap iterator that applies a function to each element of a source iterable']
```

Usage

```
{'create_LRPolicyScheduler': 'create a LRPolicyScheduler with warmup steps, decay start step, and decay steps for an optimizer', 'build_lr_warmup_schedule': 'build a learning rate schedule that linearly warms up from zero over a specified number of steps', 'build_lr_decay_schedule': 'build a learning rate schedule that quadratically decays the learning rate over a specified number of steps', 'review_LRPolicyScheduler_get_lr': 'review the LRPolicyScheduler get_lr method that returns the current learning rate based on step count', 'test_LRPolicyScheduler_validation': 'test the LRPolicyScheduler constructor validation that ensures warmup finishes before decay starts'}
```

## File: facebookresearch_dlrm/torchrec_dlrm/multi_hot.py

Prompts

```
['run the DLRM training job with 8 trainers on a single AWS p4d instance using default settings', 'run the DLRM training job with 16 trainers spanning 2 hosts using multiples of 8', 'run the DLRM training job with custom script arguments passed to dlrm_main.py entrypoint', 'review the run_dlrm_main function to understand how it configures DDP training on AWS p4d instances', 'refactor the run_dlrm_main function to support configurable CPU and GPU resource allocation per node', 'run the DLRM model training on Criteo dataset with configurable epochs and batch size', 'run the DLRM-DCN model training with deep and cross network interaction layers', 'run the DLRM-Projection model training with dual branch interaction architecture', 'run the DLRM training with multi-hot encoding for sparse features using pareto distribution', 'run the DLRM training using the Adagrad optimizer with fused backward pass updates', 'create a LRPolicyScheduler with warmup steps, decay start step, and decay steps for an optimizer', 'build a learning rate schedule that linearly warms up from zero over a specified number of steps', 'build a learning rate schedule that quadratically decays the learning rate over a specified number of steps', 'review the LRPolicyScheduler get_lr method that returns the current learning rate based on step count', 'test the LRPolicyScheduler constructor validation that ensures warmup finishes before decay starts', 'create a Multihot instance with uniform or pareto distribution to convert 1-hot sparse features to multi-hot', 'convert a torchrec Batch with 1-hot sparse features into a multi-hot Batch using convert_to_multi_hot', 'save pre-hash and post-hash frequency statistics as numpy files using save_freqs_stats', 'pause frequency stats collection during validation by calling pause_stats_collection_during_val_and_test with a model', 'create a RestartableMap iterator that applies a function to each element of a source iterable']
```

Usage

```
{'create_multihot_converter': 'create a Multihot instance with uniform or pareto distribution to convert 1-hot sparse features to multi-hot', 'convert_batch_to_multi_hot': 'convert a torchrec Batch with 1-hot sparse features into a multi-hot Batch using convert_to_multi_hot', 'save_frequency_stats': 'save pre-hash and post-hash frequency statistics as numpy files using save_freqs_stats', 'pause_stats_collection': 'pause frequency stats collection during validation by calling pause_stats_collection_during_val_and_test with a model', 'create_restartable_map': 'create a RestartableMap iterator that applies a function to each element of a source iterable'}
```

