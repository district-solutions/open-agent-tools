# Agent Python Tools

- repo: facebookresearch/omnivore
- repo_uri: https://github.com/facebookresearch/omnivore

## File: facebookresearch_omnivore/omnivision/trainer/omnivision_trainer.py

Prompts

```
['run the OmnivisionTrainer to train a vision model using DDP strategy with configurable epochs and validation', 'create an OmnivisionTrainer instance with model, data, optimizer, loss, and checkpoint configuration dicts', 'chunk a batch into smaller sub-batches for gradient accumulation across multiple steps', 'recursively split tensors inside a data object into equal-sized chunks by chunk index', 'save the model state dict, optimizer state, epoch, and scaler to a checkpoint file on disk']
```

Usage

```
{'run_OmnivisionTrainer': 'run the OmnivisionTrainer to train a vision model using DDP strategy with configurable epochs and validation', 'create_OmnivisionTrainer': 'create an OmnivisionTrainer instance with model, data, optimizer, loss, and checkpoint configuration dicts', 'chunk_batch_for_accum_steps': 'chunk a batch into smaller sub-batches for gradient accumulation across multiple steps', 'get_chunk_from_data': 'recursively split tensors inside a data object into equal-sized chunks by chunk index', 'checkpoint_save': 'save the model state dict, optimizer state, epoch, and scaler to a checkpoint file on disk'}
```

