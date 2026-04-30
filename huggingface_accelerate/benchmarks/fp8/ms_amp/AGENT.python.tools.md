# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/benchmarks/fp8/ms_amp/ddp.py

Prompts

```
['run the train_baseline function to train a BERT model using raw MS-AMP with DDP', 'run the train_integration function to train a BERT model using Accelerate FP8 with MS-AMP', 'test that Accelerate FP8 DDP training matches raw MS-AMP baseline accuracy and F1 scores', 'review the train_baseline function that wraps a model with msamp.initialize and DDP', 'review the train_integration function that uses FP8RecipeKwargs with Accelerator for MS-AMP training', 'run the main block to compare baseline MS-AMP training results against Accelerate integration across ZeRO stages and opt levels', 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'extract named parameters from a parallel-wrapped HuggingFace Accelerate model', 'run model evaluation on a dataloader with bfloat16 autocast and multi-process metric gathering', 'review the evaluate_model function to understand bfloat16 autocast and gather_for_metrics usage', 'run the non_distributed benchmark script to compare Accelerate FP8 performance against raw MS-AMP on single GPU']
```

Usage

```
{'run_train_baseline': 'run the train_baseline function to train a BERT model using raw MS-AMP with DDP', 'run_train_integration': 'run the train_integration function to train a BERT model using Accelerate FP8 with MS-AMP', 'test_ddp_fp8_benchmark': 'test that Accelerate FP8 DDP training matches raw MS-AMP baseline accuracy and F1 scores', 'review_train_baseline': 'review the train_baseline function that wraps a model with msamp.initialize and DDP', 'review_train_integration': 'review the train_integration function that uses FP8RecipeKwargs with Accelerator for MS-AMP training'}
```

## File: huggingface_accelerate/benchmarks/fp8/ms_amp/distrib_deepspeed.py

Prompts

```
['run the train_baseline function to train a BERT model using raw MS-AMP with DDP', 'run the train_integration function to train a BERT model using Accelerate FP8 with MS-AMP', 'test that Accelerate FP8 DDP training matches raw MS-AMP baseline accuracy and F1 scores', 'review the train_baseline function that wraps a model with msamp.initialize and DDP', 'review the train_integration function that uses FP8RecipeKwargs with Accelerator for MS-AMP training', 'run the main block to compare baseline MS-AMP training results against Accelerate integration across ZeRO stages and opt levels', 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'extract named parameters from a parallel-wrapped HuggingFace Accelerate model', 'run model evaluation on a dataloader with bfloat16 autocast and multi-process metric gathering', 'review the evaluate_model function to understand bfloat16 autocast and gather_for_metrics usage', 'run the non_distributed benchmark script to compare Accelerate FP8 performance against raw MS-AMP on single GPU']
```

Usage

```
{'run_train_baseline': 'run the train_baseline function to train a BERT model using raw MS-AMP with DeepSpeed ZeRO optimization', 'run_train_integration': 'run the train_integration function to train a BERT model using Accelerate with DeepSpeedPlugin and MS-AMP enabled', 'run_comparison_benchmark': 'run the main block to compare baseline MS-AMP training results against Accelerate integration across ZeRO stages and opt levels', 'review_train_baseline': 'review the train_baseline function that initializes MS-AMP DeepSpeed training with configurable zero_stage and opt_level parameters', 'review_train_integration': 'review the train_integration function that uses Accelerator with DeepSpeedPlugin for fp8 mixed precision training'}
```

## File: huggingface_accelerate/benchmarks/fp8/ms_amp/fp8_utils.py

Prompts

```
['run the train_baseline function to train a BERT model using raw MS-AMP with DDP', 'run the train_integration function to train a BERT model using Accelerate FP8 with MS-AMP', 'test that Accelerate FP8 DDP training matches raw MS-AMP baseline accuracy and F1 scores', 'review the train_baseline function that wraps a model with msamp.initialize and DDP', 'review the train_integration function that uses FP8RecipeKwargs with Accelerator for MS-AMP training', 'run the main block to compare baseline MS-AMP training results against Accelerate integration across ZeRO stages and opt levels', 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'extract named parameters from a parallel-wrapped HuggingFace Accelerate model', 'run model evaluation on a dataloader with bfloat16 autocast and multi-process metric gathering', 'review the evaluate_model function to understand bfloat16 autocast and gather_for_metrics usage', 'run the non_distributed benchmark script to compare Accelerate FP8 performance against raw MS-AMP on single GPU']
```

Usage

```
{'get_dataloaders': 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'get_training_utilities': 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'get_named_parameters': 'extract named parameters from a parallel-wrapped HuggingFace Accelerate model', 'evaluate_model': 'run model evaluation on a dataloader with bfloat16 autocast and multi-process metric gathering', 'review_evaluate_model': 'review the evaluate_model function to understand bfloat16 autocast and gather_for_metrics usage'}
```

## File: huggingface_accelerate/benchmarks/fp8/ms_amp/non_distributed.py

Prompts

```
['run the train_baseline function to train a BERT model using raw MS-AMP with DDP', 'run the train_integration function to train a BERT model using Accelerate FP8 with MS-AMP', 'test that Accelerate FP8 DDP training matches raw MS-AMP baseline accuracy and F1 scores', 'review the train_baseline function that wraps a model with msamp.initialize and DDP', 'review the train_integration function that uses FP8RecipeKwargs with Accelerator for MS-AMP training', 'run the main block to compare baseline MS-AMP training results against Accelerate integration across ZeRO stages and opt levels', 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'extract named parameters from a parallel-wrapped HuggingFace Accelerate model', 'run model evaluation on a dataloader with bfloat16 autocast and multi-process metric gathering', 'review the evaluate_model function to understand bfloat16 autocast and gather_for_metrics usage', 'run the non_distributed benchmark script to compare Accelerate FP8 performance against raw MS-AMP on single GPU']
```

Usage

```
{'run_train_baseline': 'run the train_baseline function to train a BERT model using raw MS-AMP with opt_level O2', 'run_train_integration': 'run the train_integration function to train a BERT model using Accelerate with FP8 MS-AMP backend', 'run_non_distributed_benchmark': 'run the non_distributed benchmark script to compare Accelerate FP8 performance against raw MS-AMP on single GPU', 'review_train_baseline': 'review the train_baseline function that initializes MS-AMP and trains a model with gradient scaling', 'review_train_integration': 'review the train_integration function that uses Accelerator with FP8RecipeKwargs for mixed precision training'}
```

