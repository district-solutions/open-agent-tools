# Agent Python Tools

- repo: facebookresearch/attentivenas
- repo_uri: https://github.com/facebookresearch/attentivenas

## File: facebookresearch_attentivenas/evaluate/attentive_nas_eval.py

Prompts

```
['run validation on a list of subnets from a supernet with BN calibration and accuracy reporting', 'evaluate the min, max, and random subnets of an AttentiveNAS supernet using the validate function', 'evaluate a custom subnet by specifying resolution, width, depth, kernel size, and expand ratio', 'calibrate batch normalization running statistics on a subnet before evaluating its accuracy on the validation set', 'collect and reduce evaluation results across distributed GPUs using comm.reduce_eval_results', 'run validation on a subnet model using a val_loader and criterion to get accuracy and loss metrics', 'run FLOPs and parameter counting on a subnet model given its input data shape', 'test the validate_one_subnet function with a dummy val_loader and subnet to verify accuracy computation', 'review the validate_one_subnet function for distributed evaluation logic and accuracy measurement across GPU processes', 'refactor the log_helper function to support additional logging levels beyond info and print']
```

Usage

```
{'validate_subnet_evaluation': 'run validation on a list of subnets from a supernet with BN calibration and accuracy reporting', 'validate_min_max_random_subnets': 'evaluate the min, max, and random subnets of an AttentiveNAS supernet using the validate function', 'validate_custom_subnet_config': 'evaluate a custom subnet by specifying resolution, width, depth, kernel size, and expand ratio', 'validate_bn_calibration': 'calibrate batch normalization running statistics on a subnet before evaluating its accuracy on the validation set', 'validate_distributed_results': 'collect and reduce evaluation results across distributed GPUs using comm.reduce_eval_results'}
```

## File: facebookresearch_attentivenas/evaluate/imagenet_eval.py

Prompts

```
['run validation on a list of subnets from a supernet with BN calibration and accuracy reporting', 'evaluate the min, max, and random subnets of an AttentiveNAS supernet using the validate function', 'evaluate a custom subnet by specifying resolution, width, depth, kernel size, and expand ratio', 'calibrate batch normalization running statistics on a subnet before evaluating its accuracy on the validation set', 'collect and reduce evaluation results across distributed GPUs using comm.reduce_eval_results', 'run validation on a subnet model using a val_loader and criterion to get accuracy and loss metrics', 'run FLOPs and parameter counting on a subnet model given its input data shape', 'test the validate_one_subnet function with a dummy val_loader and subnet to verify accuracy computation', 'review the validate_one_subnet function for distributed evaluation logic and accuracy measurement across GPU processes', 'refactor the log_helper function to support additional logging levels beyond info and print']
```

Usage

```
{'run_validate_subnet': 'run validation on a subnet model using a val_loader and criterion to get accuracy and loss metrics', 'run_flops_count': 'run FLOPs and parameter counting on a subnet model given its input data shape', 'test_validate_one_subnet': 'test the validate_one_subnet function with a dummy val_loader and subnet to verify accuracy computation', 'review_validate_one_subnet': 'review the validate_one_subnet function for distributed evaluation logic and accuracy measurement across GPU processes', 'refactor_log_helper': 'refactor the log_helper function to support additional logging levels beyond info and print'}
```

