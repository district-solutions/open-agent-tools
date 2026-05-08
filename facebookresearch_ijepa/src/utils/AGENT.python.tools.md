# Agent Python Tools

- repo: facebookresearch/ijepa
- repo_uri: https://github.com/facebookresearch/ijepa

## File: facebookresearch_ijepa/src/utils/distributed.py

Prompts

```
['init a distributed process group using NCCL backend with SLURM or manual rank and world size', 'gather tensors from all ranks into a single concatenated tensor using the AllGather autograd function', 'sum a tensor across all ranks using the AllReduceSum autograd function with gradient support', 'compute the mean of a tensor across all ranks using the AllReduce autograd function with gradient support', 'review the distributed training utilities including init_distributed, AllGather, AllReduceSum, and AllReduce classes', 'use gpu_timer to measure the GPU execution time of a callable closure function', 'create a CSVLogger instance to write typed header rows and data rows to a CSV file', 'use the CSVLogger log method to append a formatted data row to an existing CSV file', 'use AverageMeter to compute running average, min, max, and sum of updated values over time', 'use grad_logger to compute gradient norm statistics across model named parameters including first and last layer', 'create a WarmupCosineSchedule to linearly warm up then cosine decay the optimizer learning rate', 'run a step on the WarmupCosineSchedule to update the optimizer learning rate for the current step', 'create a CosineWDSchedule to cosine anneal the optimizer weight decay from ref_wd to final_wd', 'run a step on the CosineWDSchedule to update the optimizer weight decay for the current step', 'review the WarmupCosineSchedule and CosineWDSchedule classes for optimizer hyperparameter scheduling patterns', 'apply masks to a batch of patch tensors to gather selected patches by index', 'repeat and interleave batches of tensor rows a specified number of times', 'initialize a tensor with truncated normal distribution values clamped between bounds', 'review the apply_masks function that gathers tensor patches using index masks and concatenates results', 'summarize the trunc_normal_ function that fills a tensor with truncated normal distribution values']
```

Usage

```
{'init_distributed_process_group': 'init a distributed process group using NCCL backend with SLURM or manual rank and world size', 'all_gather_tensor_across_ranks': 'gather tensors from all ranks into a single concatenated tensor using the AllGather autograd function', 'all_reduce_sum_tensor': 'sum a tensor across all ranks using the AllReduceSum autograd function with gradient support', 'all_reduce_mean_tensor': 'compute the mean of a tensor across all ranks using the AllReduce autograd function with gradient support', 'review_distributed_utils': 'review the distributed training utilities including init_distributed, AllGather, AllReduceSum, and AllReduce classes'}
```

## File: facebookresearch_ijepa/src/utils/logging.py

Prompts

```
['init a distributed process group using NCCL backend with SLURM or manual rank and world size', 'gather tensors from all ranks into a single concatenated tensor using the AllGather autograd function', 'sum a tensor across all ranks using the AllReduceSum autograd function with gradient support', 'compute the mean of a tensor across all ranks using the AllReduce autograd function with gradient support', 'review the distributed training utilities including init_distributed, AllGather, AllReduceSum, and AllReduce classes', 'use gpu_timer to measure the GPU execution time of a callable closure function', 'create a CSVLogger instance to write typed header rows and data rows to a CSV file', 'use the CSVLogger log method to append a formatted data row to an existing CSV file', 'use AverageMeter to compute running average, min, max, and sum of updated values over time', 'use grad_logger to compute gradient norm statistics across model named parameters including first and last layer', 'create a WarmupCosineSchedule to linearly warm up then cosine decay the optimizer learning rate', 'run a step on the WarmupCosineSchedule to update the optimizer learning rate for the current step', 'create a CosineWDSchedule to cosine anneal the optimizer weight decay from ref_wd to final_wd', 'run a step on the CosineWDSchedule to update the optimizer weight decay for the current step', 'review the WarmupCosineSchedule and CosineWDSchedule classes for optimizer hyperparameter scheduling patterns', 'apply masks to a batch of patch tensors to gather selected patches by index', 'repeat and interleave batches of tensor rows a specified number of times', 'initialize a tensor with truncated normal distribution values clamped between bounds', 'review the apply_masks function that gathers tensor patches using index masks and concatenates results', 'summarize the trunc_normal_ function that fills a tensor with truncated normal distribution values']
```

Usage

```
{'time_gpu_closure': 'use gpu_timer to measure the GPU execution time of a callable closure function', 'create_csv_logger': 'create a CSVLogger instance to write typed header rows and data rows to a CSV file', 'log_csv_row': 'use the CSVLogger log method to append a formatted data row to an existing CSV file', 'track_average_meter': 'use AverageMeter to compute running average, min, max, and sum of updated values over time', 'log_gradient_norms': 'use grad_logger to compute gradient norm statistics across model named parameters including first and last layer'}
```

## File: facebookresearch_ijepa/src/utils/schedulers.py

Prompts

```
['init a distributed process group using NCCL backend with SLURM or manual rank and world size', 'gather tensors from all ranks into a single concatenated tensor using the AllGather autograd function', 'sum a tensor across all ranks using the AllReduceSum autograd function with gradient support', 'compute the mean of a tensor across all ranks using the AllReduce autograd function with gradient support', 'review the distributed training utilities including init_distributed, AllGather, AllReduceSum, and AllReduce classes', 'use gpu_timer to measure the GPU execution time of a callable closure function', 'create a CSVLogger instance to write typed header rows and data rows to a CSV file', 'use the CSVLogger log method to append a formatted data row to an existing CSV file', 'use AverageMeter to compute running average, min, max, and sum of updated values over time', 'use grad_logger to compute gradient norm statistics across model named parameters including first and last layer', 'create a WarmupCosineSchedule to linearly warm up then cosine decay the optimizer learning rate', 'run a step on the WarmupCosineSchedule to update the optimizer learning rate for the current step', 'create a CosineWDSchedule to cosine anneal the optimizer weight decay from ref_wd to final_wd', 'run a step on the CosineWDSchedule to update the optimizer weight decay for the current step', 'review the WarmupCosineSchedule and CosineWDSchedule classes for optimizer hyperparameter scheduling patterns', 'apply masks to a batch of patch tensors to gather selected patches by index', 'repeat and interleave batches of tensor rows a specified number of times', 'initialize a tensor with truncated normal distribution values clamped between bounds', 'review the apply_masks function that gathers tensor patches using index masks and concatenates results', 'summarize the trunc_normal_ function that fills a tensor with truncated normal distribution values']
```

Usage

```
{'create_warmup_cosine_lr_schedule': 'create a WarmupCosineSchedule to linearly warm up then cosine decay the optimizer learning rate', 'run_warmup_cosine_schedule_step': 'run a step on the WarmupCosineSchedule to update the optimizer learning rate for the current step', 'create_cosine_weight_decay_schedule': 'create a CosineWDSchedule to cosine anneal the optimizer weight decay from ref_wd to final_wd', 'run_cosine_wd_schedule_step': 'run a step on the CosineWDSchedule to update the optimizer weight decay for the current step', 'review_scheduler_classes': 'review the WarmupCosineSchedule and CosineWDSchedule classes for optimizer hyperparameter scheduling patterns'}
```

## File: facebookresearch_ijepa/src/utils/tensors.py

Prompts

```
['init a distributed process group using NCCL backend with SLURM or manual rank and world size', 'gather tensors from all ranks into a single concatenated tensor using the AllGather autograd function', 'sum a tensor across all ranks using the AllReduceSum autograd function with gradient support', 'compute the mean of a tensor across all ranks using the AllReduce autograd function with gradient support', 'review the distributed training utilities including init_distributed, AllGather, AllReduceSum, and AllReduce classes', 'use gpu_timer to measure the GPU execution time of a callable closure function', 'create a CSVLogger instance to write typed header rows and data rows to a CSV file', 'use the CSVLogger log method to append a formatted data row to an existing CSV file', 'use AverageMeter to compute running average, min, max, and sum of updated values over time', 'use grad_logger to compute gradient norm statistics across model named parameters including first and last layer', 'create a WarmupCosineSchedule to linearly warm up then cosine decay the optimizer learning rate', 'run a step on the WarmupCosineSchedule to update the optimizer learning rate for the current step', 'create a CosineWDSchedule to cosine anneal the optimizer weight decay from ref_wd to final_wd', 'run a step on the CosineWDSchedule to update the optimizer weight decay for the current step', 'review the WarmupCosineSchedule and CosineWDSchedule classes for optimizer hyperparameter scheduling patterns', 'apply masks to a batch of patch tensors to gather selected patches by index', 'repeat and interleave batches of tensor rows a specified number of times', 'initialize a tensor with truncated normal distribution values clamped between bounds', 'review the apply_masks function that gathers tensor patches using index masks and concatenates results', 'summarize the trunc_normal_ function that fills a tensor with truncated normal distribution values']
```

Usage

```
{'apply_masks_tensor_patches': 'apply masks to a batch of patch tensors to gather selected patches by index', 'repeat_interleave_batch_tensor': 'repeat and interleave batches of tensor rows a specified number of times', 'trunc_normal_tensor_init': 'initialize a tensor with truncated normal distribution values clamped between bounds', 'review_apply_masks_gather': 'review the apply_masks function that gathers tensor patches using index masks and concatenates results', 'summarize_trunc_normal_init': 'summarize the trunc_normal_ function that fills a tensor with truncated normal distribution values'}
```

