# Agent Python Tools

- repo: google-deepmind/dmnevis
- repo_uri: https://github.com/google-deepmind/dm_nevis

## File: google-deepmind_dmnevis/experiments_jax/environment/noop_checkpointer.py

Prompts

```
['create a NoOpCheckpointer instance with optional namespace, base_path, and restore_path arguments', 'call write on a NoOpCheckpointer to log a warning without persisting any state', 'call restore on a NoOpCheckpointer to return None and log a warning instead of loading state', 'review the NoOpCheckpointer class to understand its no-op behavior for testing and debugging', 'summarize the NoOpCheckpointer API which provides write and restore methods that do nothing', 'create a PickleCheckpointer instance with a base path to save and restore checkpoints', 'write an arbitrary state object to a pickle checkpoint file using PickleCheckpointer write method', 'restore the most recent checkpointed state from a pickle file using PickleCheckpointer restore method', 'build a python module that saves and restores arbitrary state objects using pickle serialization', 'review the PickleCheckpointer class and its atomic write pattern using partial file rename', 'load pretrained model parameters from a checkpoint file into Haiku params and state', 'freeze pretrained backbone parameters when loading a model from a checkpoint path', 'merge pretrained backbone parameters from a checkpoint into existing model parameters', 'partition model parameters into trainable and frozen sets based on backbone module names', 'restore training state including trainable and frozen params from a checkpoint path']
```

Usage

```
{'create_noop_checkpointer': 'create a NoOpCheckpointer instance with optional namespace, base_path, and restore_path arguments', 'write_checkpoint_noop': 'call write on a NoOpCheckpointer to log a warning without persisting any state', 'restore_checkpoint_noop': 'call restore on a NoOpCheckpointer to return None and log a warning instead of loading state', 'review_noop_checkpointer_class': 'review the NoOpCheckpointer class to understand its no-op behavior for testing and debugging', 'summarize_noop_checkpointer_api': 'summarize the NoOpCheckpointer API which provides write and restore methods that do nothing'}
```

## File: google-deepmind_dmnevis/experiments_jax/environment/pickle_checkpointer.py

Prompts

```
['create a NoOpCheckpointer instance with optional namespace, base_path, and restore_path arguments', 'call write on a NoOpCheckpointer to log a warning without persisting any state', 'call restore on a NoOpCheckpointer to return None and log a warning instead of loading state', 'review the NoOpCheckpointer class to understand its no-op behavior for testing and debugging', 'summarize the NoOpCheckpointer API which provides write and restore methods that do nothing', 'create a PickleCheckpointer instance with a base path to save and restore checkpoints', 'write an arbitrary state object to a pickle checkpoint file using PickleCheckpointer write method', 'restore the most recent checkpointed state from a pickle file using PickleCheckpointer restore method', 'build a python module that saves and restores arbitrary state objects using pickle serialization', 'review the PickleCheckpointer class and its atomic write pattern using partial file rename', 'load pretrained model parameters from a checkpoint file into Haiku params and state', 'freeze pretrained backbone parameters when loading a model from a checkpoint path', 'merge pretrained backbone parameters from a checkpoint into existing model parameters', 'partition model parameters into trainable and frozen sets based on backbone module names', 'restore training state including trainable and frozen params from a checkpoint path']
```

Usage

```
{'create_pickle_checkpointer': 'create a PickleCheckpointer instance with a base path to save and restore checkpoints', 'write_checkpoint': 'write an arbitrary state object to a pickle checkpoint file using PickleCheckpointer write method', 'restore_checkpoint': 'restore the most recent checkpointed state from a pickle file using PickleCheckpointer restore method', 'build_checkpoint_save_restore': 'build a python module that saves and restores arbitrary state objects using pickle serialization', 'review_pickle_checkpointer_class': 'review the PickleCheckpointer class and its atomic write pattern using partial file rename'}
```

## File: google-deepmind_dmnevis/experiments_jax/environment/pretrained_model_loader.py

Prompts

```
['create a NoOpCheckpointer instance with optional namespace, base_path, and restore_path arguments', 'call write on a NoOpCheckpointer to log a warning without persisting any state', 'call restore on a NoOpCheckpointer to return None and log a warning instead of loading state', 'review the NoOpCheckpointer class to understand its no-op behavior for testing and debugging', 'summarize the NoOpCheckpointer API which provides write and restore methods that do nothing', 'create a PickleCheckpointer instance with a base path to save and restore checkpoints', 'write an arbitrary state object to a pickle checkpoint file using PickleCheckpointer write method', 'restore the most recent checkpointed state from a pickle file using PickleCheckpointer restore method', 'build a python module that saves and restores arbitrary state objects using pickle serialization', 'review the PickleCheckpointer class and its atomic write pattern using partial file rename', 'load pretrained model parameters from a checkpoint file into Haiku params and state', 'freeze pretrained backbone parameters when loading a model from a checkpoint path', 'merge pretrained backbone parameters from a checkpoint into existing model parameters', 'partition model parameters into trainable and frozen sets based on backbone module names', 'restore training state including trainable and frozen params from a checkpoint path']
```

Usage

```
{'load_pretrained_model_params': 'load pretrained model parameters from a checkpoint file into Haiku params and state', 'freeze_backbone_params': 'freeze pretrained backbone parameters when loading a model from a checkpoint path', 'merge_pretrained_params': 'merge pretrained backbone parameters from a checkpoint into existing model parameters', 'partition_trainable_frozen': 'partition model parameters into trainable and frozen sets based on backbone module names', 'restore_train_state': 'restore training state including trainable and frozen params from a checkpoint path'}
```

