# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/pruning/_experimental/data_sparsifier/lightning/callbacks/data_sparsity.py

Prompts

```
['create a PostTrainingDataSparsity Lightning callback to sparsify a model after training completes', 'create a TrainingAwareDataSparsity Lightning callback to sparsify a model during training with a data scheduler', 'run post-training data sparsification by copying the model, attaching to sparsifier, stepping, and squashing the mask', 'run in-training data sparsification by attaching model to sparsifier each epoch, stepping sparsifier and scheduler, and saving state', 'test the PostTrainingDataSparsity or TrainingAwareDataSparsity Lightning callback with a BaseDataSparsifier and BaseDataScheduler']
```

Usage

```
{'create_post_training_data_sparsity': 'create a PostTrainingDataSparsity Lightning callback to sparsify a model after training completes', 'create_training_aware_data_sparsity': 'create a TrainingAwareDataSparsity Lightning callback to sparsify a model during training with a data scheduler', 'run_post_training_sparsify': 'run post-training data sparsification by copying the model, attaching to sparsifier, stepping, and squashing the mask', 'run_training_aware_sparsify': 'run in-training data sparsification by attaching model to sparsifier each epoch, stepping sparsifier and scheduler, and saving state', 'test_data_sparsity_callback': 'test the PostTrainingDataSparsity or TrainingAwareDataSparsity Lightning callback with a BaseDataSparsifier and BaseDataScheduler'}
```

