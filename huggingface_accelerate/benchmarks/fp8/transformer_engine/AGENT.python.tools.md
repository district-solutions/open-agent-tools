# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/benchmarks/fp8/transformer_engine/ddp.py

Prompts

```
['run the baseline DDP training with raw Transformer Engine FP8 autocast and bfloat16 mixed precision', 'run the DDP training integration test using Accelerator with FP8RecipeKwargs and mixed precision fp8', 'test the baseline training function that converts a model to Transformer Engine and wraps it in DDP', 'test the integration training function that uses Accelerator prepare with FP8 recipe kwargs handlers', 'run the DDP benchmark comparing baseline raw Transformer Engine training against Accelerator FP8 integration training', 'run the distributed DeepSpeed FP8 benchmark comparing baseline and Accelerate across ZERO stages 1, 2, and 3', 'review the train_baseline function that converts a model to Transformer Engine and trains with raw DeepSpeed', 'review the train_integration function that trains a model using Accelerator with FP8 mixed precision and DeepSpeed plugin', 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'extract named parameters from a model wrapped in DataParallel or DDP', 'run a model in eval mode over a dataloader and compute metrics with multi-process gathering', 'refactor get_dataloaders to support a different GLUE task or custom tokenizer settings', 'run the full FSDP benchmark comparing baseline raw TE training against accelerate integration training', 'run the non_distributed benchmark script to verify Accelerate FP8 parity with raw Transformer Engine']
```

Usage

```
{'run_train_baseline': 'run the baseline DDP training with raw Transformer Engine FP8 autocast and bfloat16 mixed precision', 'run_train_integration': 'run the DDP training integration test using Accelerator with FP8RecipeKwargs and mixed precision fp8', 'test_train_baseline': 'test the baseline training function that converts a model to Transformer Engine and wraps it in DDP', 'test_train_integration': 'test the integration training function that uses Accelerator prepare with FP8 recipe kwargs handlers', 'run_ddp_benchmark': 'run the DDP benchmark comparing baseline raw Transformer Engine training against Accelerator FP8 integration training'}
```

## File: huggingface_accelerate/benchmarks/fp8/transformer_engine/distrib_deepspeed.py

Prompts

```
['run the baseline DDP training with raw Transformer Engine FP8 autocast and bfloat16 mixed precision', 'run the DDP training integration test using Accelerator with FP8RecipeKwargs and mixed precision fp8', 'test the baseline training function that converts a model to Transformer Engine and wraps it in DDP', 'test the integration training function that uses Accelerator prepare with FP8 recipe kwargs handlers', 'run the DDP benchmark comparing baseline raw Transformer Engine training against Accelerator FP8 integration training', 'run the distributed DeepSpeed FP8 benchmark comparing baseline and Accelerate across ZERO stages 1, 2, and 3', 'review the train_baseline function that converts a model to Transformer Engine and trains with raw DeepSpeed', 'review the train_integration function that trains a model using Accelerator with FP8 mixed precision and DeepSpeed plugin', 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'extract named parameters from a model wrapped in DataParallel or DDP', 'run a model in eval mode over a dataloader and compute metrics with multi-process gathering', 'refactor get_dataloaders to support a different GLUE task or custom tokenizer settings', 'run the full FSDP benchmark comparing baseline raw TE training against accelerate integration training', 'run the non_distributed benchmark script to verify Accelerate FP8 parity with raw Transformer Engine']
```

Usage

```
{'run_train_baseline': 'run the baseline DeepSpeed FP8 training loop for a given ZERO stage', 'run_train_integration': 'run the Accelerate DeepSpeed FP8 integration training loop for a given ZERO stage', 'run_distrib_deepspeed_benchmark': 'run the distributed DeepSpeed FP8 benchmark comparing baseline and Accelerate across ZERO stages 1, 2, and 3', 'review_train_baseline': 'review the train_baseline function that converts a model to Transformer Engine and trains with raw DeepSpeed', 'review_train_integration': 'review the train_integration function that trains a model using Accelerator with FP8 mixed precision and DeepSpeed plugin'}
```

## File: huggingface_accelerate/benchmarks/fp8/transformer_engine/fp8_utils.py

Prompts

```
['run the baseline DDP training with raw Transformer Engine FP8 autocast and bfloat16 mixed precision', 'run the DDP training integration test using Accelerator with FP8RecipeKwargs and mixed precision fp8', 'test the baseline training function that converts a model to Transformer Engine and wraps it in DDP', 'test the integration training function that uses Accelerator prepare with FP8 recipe kwargs handlers', 'run the DDP benchmark comparing baseline raw Transformer Engine training against Accelerator FP8 integration training', 'run the distributed DeepSpeed FP8 benchmark comparing baseline and Accelerate across ZERO stages 1, 2, and 3', 'review the train_baseline function that converts a model to Transformer Engine and trains with raw DeepSpeed', 'review the train_integration function that trains a model using Accelerator with FP8 mixed precision and DeepSpeed plugin', 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'extract named parameters from a model wrapped in DataParallel or DDP', 'run a model in eval mode over a dataloader and compute metrics with multi-process gathering', 'refactor get_dataloaders to support a different GLUE task or custom tokenizer settings', 'run the full FSDP benchmark comparing baseline raw TE training against accelerate integration training', 'run the non_distributed benchmark script to verify Accelerate FP8 parity with raw Transformer Engine']
```

Usage

```
{'get_dataloaders': 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'get_training_utilities': 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'get_named_parameters': 'extract named parameters from a model wrapped in DataParallel or DDP', 'evaluate_model': 'run a model in eval mode over a dataloader and compute metrics with multi-process gathering', 'refactor_get_dataloaders': 'refactor get_dataloaders to support a different GLUE task or custom tokenizer settings'}
```

## File: huggingface_accelerate/benchmarks/fp8/transformer_engine/fsdp.py

Prompts

```
['run the baseline DDP training with raw Transformer Engine FP8 autocast and bfloat16 mixed precision', 'run the DDP training integration test using Accelerator with FP8RecipeKwargs and mixed precision fp8', 'test the baseline training function that converts a model to Transformer Engine and wraps it in DDP', 'test the integration training function that uses Accelerator prepare with FP8 recipe kwargs handlers', 'run the DDP benchmark comparing baseline raw Transformer Engine training against Accelerator FP8 integration training', 'run the distributed DeepSpeed FP8 benchmark comparing baseline and Accelerate across ZERO stages 1, 2, and 3', 'review the train_baseline function that converts a model to Transformer Engine and trains with raw DeepSpeed', 'review the train_integration function that trains a model using Accelerator with FP8 mixed precision and DeepSpeed plugin', 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'extract named parameters from a model wrapped in DataParallel or DDP', 'run a model in eval mode over a dataloader and compute metrics with multi-process gathering', 'refactor get_dataloaders to support a different GLUE task or custom tokenizer settings', 'run the full FSDP benchmark comparing baseline raw TE training against accelerate integration training', 'run the non_distributed benchmark script to verify Accelerate FP8 parity with raw Transformer Engine']
```

Usage

```
{'run_train_baseline': 'run the baseline FSDP training with raw Transformer Engine FP8 autocast on a BERT model', 'run_train_integration': 'run the accelerate integration FSDP training with FP8 recipe kwargs on a BERT model', 'run_fsdp_benchmark': 'run the full FSDP benchmark comparing baseline raw TE training against accelerate integration training', 'review_train_baseline': 'review the train_baseline function that converts a model to TE and wraps it with FSDP', 'review_train_integration': 'review the train_integration function that uses Accelerator with FSDPPlugin and FP8RecipeKwargs for training'}
```

## File: huggingface_accelerate/benchmarks/fp8/transformer_engine/non_distributed.py

Prompts

```
['run the baseline DDP training with raw Transformer Engine FP8 autocast and bfloat16 mixed precision', 'run the DDP training integration test using Accelerator with FP8RecipeKwargs and mixed precision fp8', 'test the baseline training function that converts a model to Transformer Engine and wraps it in DDP', 'test the integration training function that uses Accelerator prepare with FP8 recipe kwargs handlers', 'run the DDP benchmark comparing baseline raw Transformer Engine training against Accelerator FP8 integration training', 'run the distributed DeepSpeed FP8 benchmark comparing baseline and Accelerate across ZERO stages 1, 2, and 3', 'review the train_baseline function that converts a model to Transformer Engine and trains with raw DeepSpeed', 'review the train_integration function that trains a model using Accelerator with FP8 mixed precision and DeepSpeed plugin', 'create train and eval dataloaders for the MRPC GLUE dataset with FP8-compatible padding', 'build a model, optimizer, dataloaders, and LR scheduler for MRPC sequence classification training', 'extract named parameters from a model wrapped in DataParallel or DDP', 'run a model in eval mode over a dataloader and compute metrics with multi-process gathering', 'refactor get_dataloaders to support a different GLUE task or custom tokenizer settings', 'run the full FSDP benchmark comparing baseline raw TE training against accelerate integration training', 'run the non_distributed benchmark script to verify Accelerate FP8 parity with raw Transformer Engine']
```

Usage

```
{'run_train_baseline': 'run the train_baseline function to train a BERT model using raw Transformer Engine with FP8 precision', 'run_train_integration': 'run the train_integration function to train a BERT model using Accelerate with FP8 precision', 'run_non_distributed_benchmark': 'run the non_distributed benchmark script to verify Accelerate FP8 parity with raw Transformer Engine', 'review_train_baseline': 'review the train_baseline function that converts a model to Transformer Engine and trains with FP8 autocast', 'review_train_integration': 'review the train_integration function that uses Accelerator with FP8RecipeKwargs for FP8 training'}
```

