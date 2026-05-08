# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/checkpoint/api.py

Prompts

```
['check if a Checkpointer instance supports distributed checkpointing using is_distributed_checkpoint', 'review the is_distributed_checkpoint function that checks if a Checkpointer supports distributed checkpointing', 'refactor is_distributed_checkpoint to add fallback logic for Checkpointer types without is_distributed method', 'test is_distributed_checkpoint with a Checkpointer that has and lacks the is_distributed method', 'summarize the is_distributed_checkpoint function that returns bool based on Checkpointer distributed support', 'create an FSDPCheckpointer instance to save and load FSDP model checkpoints in distributed training', 'load a sharded or full FSDP checkpoint from a directory or file path using FSDPCheckpointer', 'save an FSDP model checkpoint with sharded or full state dict using FSDPCheckpointer', 'review the FSDPCheckpointer load method to understand how it handles LOCAL_STATE_DICT and FULL_STATE_DICT', 'summarize the FSDPCheckpointer save method and how it gathers optimizer and EMA state dicts', 'log a checkpoint with a unique id, checkpoint type, and state string', 'review the log_checkpoint function to understand its logging behavior and parameters', 'refactor log_checkpoint to support additional checkpoint metadata fields', 'test the log_checkpoint function with various checkpoint types and states', 'summarize the log_checkpoint function and its fb_overwritable decorator usage', 'gather the full or sharded optimizer state dict from an FSDP model for checkpointing', 'load and scatter a full or sharded optimizer state dict into an FSDP model', 'gather the full or sharded EMA state dict from an FSDP model across all ranks', 'load a full or sharded EMA state dict into an FSDP model and restore model state', 'review the FSDP checkpoint utility functions for optimizer and EMA state dict gathering and scattering']
```

Usage

```
{'check_distributed_checkpoint': 'check if a Checkpointer instance supports distributed checkpointing using is_distributed_checkpoint', 'review_is_distributed_checkpoint': 'review the is_distributed_checkpoint function that checks if a Checkpointer supports distributed checkpointing', 'refactor_is_distributed_checkpoint': 'refactor is_distributed_checkpoint to add fallback logic for Checkpointer types without is_distributed method', 'test_is_distributed_checkpoint': 'test is_distributed_checkpoint with a Checkpointer that has and lacks the is_distributed method', 'summarize_is_distributed_checkpoint': 'summarize the is_distributed_checkpoint function that returns bool based on Checkpointer distributed support'}
```

## File: facebookresearch_d2go/d2go/checkpoint/fsdp_checkpoint.py

Prompts

```
['check if a Checkpointer instance supports distributed checkpointing using is_distributed_checkpoint', 'review the is_distributed_checkpoint function that checks if a Checkpointer supports distributed checkpointing', 'refactor is_distributed_checkpoint to add fallback logic for Checkpointer types without is_distributed method', 'test is_distributed_checkpoint with a Checkpointer that has and lacks the is_distributed method', 'summarize the is_distributed_checkpoint function that returns bool based on Checkpointer distributed support', 'create an FSDPCheckpointer instance to save and load FSDP model checkpoints in distributed training', 'load a sharded or full FSDP checkpoint from a directory or file path using FSDPCheckpointer', 'save an FSDP model checkpoint with sharded or full state dict using FSDPCheckpointer', 'review the FSDPCheckpointer load method to understand how it handles LOCAL_STATE_DICT and FULL_STATE_DICT', 'summarize the FSDPCheckpointer save method and how it gathers optimizer and EMA state dicts', 'log a checkpoint with a unique id, checkpoint type, and state string', 'review the log_checkpoint function to understand its logging behavior and parameters', 'refactor log_checkpoint to support additional checkpoint metadata fields', 'test the log_checkpoint function with various checkpoint types and states', 'summarize the log_checkpoint function and its fb_overwritable decorator usage', 'gather the full or sharded optimizer state dict from an FSDP model for checkpointing', 'load and scatter a full or sharded optimizer state dict into an FSDP model', 'gather the full or sharded EMA state dict from an FSDP model across all ranks', 'load a full or sharded EMA state dict into an FSDP model and restore model state', 'review the FSDP checkpoint utility functions for optimizer and EMA state dict gathering and scattering']
```

Usage

```
{'create_FSDPCheckpointer': 'create an FSDPCheckpointer instance to save and load FSDP model checkpoints in distributed training', 'load_FSDPCheckpointer': 'load a sharded or full FSDP checkpoint from a directory or file path using FSDPCheckpointer', 'save_FSDPCheckpointer': 'save an FSDP model checkpoint with sharded or full state dict using FSDPCheckpointer', 'review_FSDPCheckpointer_load': 'review the FSDPCheckpointer load method to understand how it handles LOCAL_STATE_DICT and FULL_STATE_DICT', 'summarize_FSDPCheckpointer_save': 'summarize the FSDPCheckpointer save method and how it gathers optimizer and EMA state dicts'}
```

## File: facebookresearch_d2go/d2go/checkpoint/log_checkpoint.py

Prompts

```
['check if a Checkpointer instance supports distributed checkpointing using is_distributed_checkpoint', 'review the is_distributed_checkpoint function that checks if a Checkpointer supports distributed checkpointing', 'refactor is_distributed_checkpoint to add fallback logic for Checkpointer types without is_distributed method', 'test is_distributed_checkpoint with a Checkpointer that has and lacks the is_distributed method', 'summarize the is_distributed_checkpoint function that returns bool based on Checkpointer distributed support', 'create an FSDPCheckpointer instance to save and load FSDP model checkpoints in distributed training', 'load a sharded or full FSDP checkpoint from a directory or file path using FSDPCheckpointer', 'save an FSDP model checkpoint with sharded or full state dict using FSDPCheckpointer', 'review the FSDPCheckpointer load method to understand how it handles LOCAL_STATE_DICT and FULL_STATE_DICT', 'summarize the FSDPCheckpointer save method and how it gathers optimizer and EMA state dicts', 'log a checkpoint with a unique id, checkpoint type, and state string', 'review the log_checkpoint function to understand its logging behavior and parameters', 'refactor log_checkpoint to support additional checkpoint metadata fields', 'test the log_checkpoint function with various checkpoint types and states', 'summarize the log_checkpoint function and its fb_overwritable decorator usage', 'gather the full or sharded optimizer state dict from an FSDP model for checkpointing', 'load and scatter a full or sharded optimizer state dict into an FSDP model', 'gather the full or sharded EMA state dict from an FSDP model across all ranks', 'load a full or sharded EMA state dict into an FSDP model and restore model state', 'review the FSDP checkpoint utility functions for optimizer and EMA state dict gathering and scattering']
```

Usage

```
{'log_checkpoint_info': 'log a checkpoint with a unique id, checkpoint type, and state string', 'review_log_checkpoint': 'review the log_checkpoint function to understand its logging behavior and parameters', 'refactor_log_checkpoint': 'refactor log_checkpoint to support additional checkpoint metadata fields', 'test_log_checkpoint': 'test the log_checkpoint function with various checkpoint types and states', 'summarize_log_checkpoint': 'summarize the log_checkpoint function and its fb_overwritable decorator usage'}
```

## File: facebookresearch_d2go/d2go/checkpoint/utils.py

Prompts

```
['check if a Checkpointer instance supports distributed checkpointing using is_distributed_checkpoint', 'review the is_distributed_checkpoint function that checks if a Checkpointer supports distributed checkpointing', 'refactor is_distributed_checkpoint to add fallback logic for Checkpointer types without is_distributed method', 'test is_distributed_checkpoint with a Checkpointer that has and lacks the is_distributed method', 'summarize the is_distributed_checkpoint function that returns bool based on Checkpointer distributed support', 'create an FSDPCheckpointer instance to save and load FSDP model checkpoints in distributed training', 'load a sharded or full FSDP checkpoint from a directory or file path using FSDPCheckpointer', 'save an FSDP model checkpoint with sharded or full state dict using FSDPCheckpointer', 'review the FSDPCheckpointer load method to understand how it handles LOCAL_STATE_DICT and FULL_STATE_DICT', 'summarize the FSDPCheckpointer save method and how it gathers optimizer and EMA state dicts', 'log a checkpoint with a unique id, checkpoint type, and state string', 'review the log_checkpoint function to understand its logging behavior and parameters', 'refactor log_checkpoint to support additional checkpoint metadata fields', 'test the log_checkpoint function with various checkpoint types and states', 'summarize the log_checkpoint function and its fb_overwritable decorator usage', 'gather the full or sharded optimizer state dict from an FSDP model for checkpointing', 'load and scatter a full or sharded optimizer state dict into an FSDP model', 'gather the full or sharded EMA state dict from an FSDP model across all ranks', 'load a full or sharded EMA state dict into an FSDP model and restore model state', 'review the FSDP checkpoint utility functions for optimizer and EMA state dict gathering and scattering']
```

Usage

```
{'gather_optimizer_state_dict': 'gather the full or sharded optimizer state dict from an FSDP model for checkpointing', 'scatter_optimizer_state_dict': 'load and scatter a full or sharded optimizer state dict into an FSDP model', 'gather_ema_state_dict': 'gather the full or sharded EMA state dict from an FSDP model across all ranks', 'scatter_ema_state_dict': 'load a full or sharded EMA state dict into an FSDP model and restore model state', 'review_utils_checkpoint': 'review the FSDP checkpoint utility functions for optimizer and EMA state dict gathering and scattering'}
```

