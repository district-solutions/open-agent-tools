# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/checkpoint/checkpointer.py

Prompts

```
['create a Checkpointer instance wrapping a PyTorch model for distributed checkpointing', 'save the model checkpoint to a given file path using FsspecWriter and return metadata', 'load a model checkpoint from a given file path using FsspecReader into the checkpointer states', 'review the Checkpointer class and its save and load methods for distributed checkpoint usage', 'summarize the Checkpointer API including init, load_from_path, and save_to_path methods', 'create a DCPModelWrapper instance wrapping a single torch.nn.Module for distributed checkpointing', 'create a DCPModelWrapper instance wrapping a list of torch.nn.Module models for distributed checkpointing', 'call state_dict on a DCPModelWrapper to extract the model state dictionary for saving', 'call load_state_dict on a DCPModelWrapper to restore model state from a saved dictionary', 'review the DCPModelWrapper class and its state_dict and load_state_dict methods for distributed checkpoint usage']
```

Usage

```
{'create_checkpointer': 'create a Checkpointer instance wrapping a PyTorch model for distributed checkpointing', 'save_checkpoint_to_path': 'save the model checkpoint to a given file path using FsspecWriter and return metadata', 'load_checkpoint_from_path': 'load a model checkpoint from a given file path using FsspecReader into the checkpointer states', 'review_checkpointer_class': 'review the Checkpointer class and its save and load methods for distributed checkpoint usage', 'summarize_checkpointer_api': 'summarize the Checkpointer API including init, load_from_path, and save_to_path methods'}
```

## File: facebookresearch_cwm/cwm/checkpoint/stateful_utils.py

Prompts

```
['create a Checkpointer instance wrapping a PyTorch model for distributed checkpointing', 'save the model checkpoint to a given file path using FsspecWriter and return metadata', 'load a model checkpoint from a given file path using FsspecReader into the checkpointer states', 'review the Checkpointer class and its save and load methods for distributed checkpoint usage', 'summarize the Checkpointer API including init, load_from_path, and save_to_path methods', 'create a DCPModelWrapper instance wrapping a single torch.nn.Module for distributed checkpointing', 'create a DCPModelWrapper instance wrapping a list of torch.nn.Module models for distributed checkpointing', 'call state_dict on a DCPModelWrapper to extract the model state dictionary for saving', 'call load_state_dict on a DCPModelWrapper to restore model state from a saved dictionary', 'review the DCPModelWrapper class and its state_dict and load_state_dict methods for distributed checkpoint usage']
```

Usage

```
{'create_DCPModelWrapper': 'create a DCPModelWrapper instance wrapping a single torch.nn.Module for distributed checkpointing', 'create_DCPModelWrapper_list': 'create a DCPModelWrapper instance wrapping a list of torch.nn.Module models for distributed checkpointing', 'get_state_dict': 'call state_dict on a DCPModelWrapper to extract the model state dictionary for saving', 'load_state_dict': 'call load_state_dict on a DCPModelWrapper to restore model state from a saved dictionary', 'review_DCPModelWrapper': 'review the DCPModelWrapper class and its state_dict and load_state_dict methods for distributed checkpoint usage'}
```

