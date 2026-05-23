# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/tools/misc/browse_dataset.py

Prompts

```
['browse a pose dataset in original mode to visualize raw images with keypoints and bounding boxes', 'browse a pose dataset in transformed mode to visualize images after data transformations are applied', 'browse a pose dataset and save visualization outputs to a specified directory instead of displaying', 'browse a specific phase of the dataset such as train, test, or val for visualization', 'browse a pose dataset with overridden config options to customize dataset settings on the fly', "run the script to remove the 'backbone.' prefix from a PyTorch checkpoint file and save a cleaned version", 'run the parse_args function to validate a checkpoint path argument from the command line', "run the main function to load a checkpoint, strip the 'backbone.' prefix from state dict keys, and save the cleaned checkpoint", 'review the parse_args function that validates checkpoint path existence and returns parsed CLI arguments', "summarize the main function that uses _load_checkpoint_with_prefix to strip 'backbone.' keys and saves a new .pth file", 'run the publish_model script to process a PyTorch checkpoint for publication with sha256 naming', 'run process_checkpoint to strip unused keys from a checkpoint and save with hash-based filename', 'refactor process_checkpoint to add custom key filtering logic before saving the checkpoint', 'review the publish_model module to understand checkpoint processing, key filtering, and hash-based file naming']
```

Usage

```
{'browse_dataset_original': 'browse a pose dataset in original mode to visualize raw images with keypoints and bounding boxes', 'browse_dataset_transformed': 'browse a pose dataset in transformed mode to visualize images after data transformations are applied', 'browse_dataset_save_output': 'browse a pose dataset and save visualization outputs to a specified directory instead of displaying', 'browse_dataset_select_phase': 'browse a specific phase of the dataset such as train, test, or val for visualization', 'browse_dataset_override_config': 'browse a pose dataset with overridden config options to customize dataset settings on the fly'}
```

## File: facebookresearch_sapiens/pose/tools/misc/create_no_backbone_prefix_checkpoint.py

Prompts

```
['browse a pose dataset in original mode to visualize raw images with keypoints and bounding boxes', 'browse a pose dataset in transformed mode to visualize images after data transformations are applied', 'browse a pose dataset and save visualization outputs to a specified directory instead of displaying', 'browse a specific phase of the dataset such as train, test, or val for visualization', 'browse a pose dataset with overridden config options to customize dataset settings on the fly', "run the script to remove the 'backbone.' prefix from a PyTorch checkpoint file and save a cleaned version", 'run the parse_args function to validate a checkpoint path argument from the command line', "run the main function to load a checkpoint, strip the 'backbone.' prefix from state dict keys, and save the cleaned checkpoint", 'review the parse_args function that validates checkpoint path existence and returns parsed CLI arguments', "summarize the main function that uses _load_checkpoint_with_prefix to strip 'backbone.' keys and saves a new .pth file", 'run the publish_model script to process a PyTorch checkpoint for publication with sha256 naming', 'run process_checkpoint to strip unused keys from a checkpoint and save with hash-based filename', 'refactor process_checkpoint to add custom key filtering logic before saving the checkpoint', 'review the publish_model module to understand checkpoint processing, key filtering, and hash-based file naming']
```

Usage

```
{'run_create_no_backbone_prefix_checkpoint': "run the script to remove the 'backbone.' prefix from a PyTorch checkpoint file and save a cleaned version", 'run_parse_args': 'run the parse_args function to validate a checkpoint path argument from the command line', 'run_main': "run the main function to load a checkpoint, strip the 'backbone.' prefix from state dict keys, and save the cleaned checkpoint", 'review_parse_args': 'review the parse_args function that validates checkpoint path existence and returns parsed CLI arguments', 'summarize_main': "summarize the main function that uses _load_checkpoint_with_prefix to strip 'backbone.' keys and saves a new .pth file"}
```

## File: facebookresearch_sapiens/pose/tools/misc/publish_model.py

Prompts

```
['browse a pose dataset in original mode to visualize raw images with keypoints and bounding boxes', 'browse a pose dataset in transformed mode to visualize images after data transformations are applied', 'browse a pose dataset and save visualization outputs to a specified directory instead of displaying', 'browse a specific phase of the dataset such as train, test, or val for visualization', 'browse a pose dataset with overridden config options to customize dataset settings on the fly', "run the script to remove the 'backbone.' prefix from a PyTorch checkpoint file and save a cleaned version", 'run the parse_args function to validate a checkpoint path argument from the command line', "run the main function to load a checkpoint, strip the 'backbone.' prefix from state dict keys, and save the cleaned checkpoint", 'review the parse_args function that validates checkpoint path existence and returns parsed CLI arguments', "summarize the main function that uses _load_checkpoint_with_prefix to strip 'backbone.' keys and saves a new .pth file", 'run the publish_model script to process a PyTorch checkpoint for publication with sha256 naming', 'run process_checkpoint to strip unused keys from a checkpoint and save with hash-based filename', 'refactor process_checkpoint to add custom key filtering logic before saving the checkpoint', 'review the publish_model module to understand checkpoint processing, key filtering, and hash-based file naming']
```

Usage

```
{'run_publish_model': 'run the publish_model script to process a PyTorch checkpoint for publication with sha256 naming', 'run_process_checkpoint': 'run process_checkpoint to strip unused keys from a checkpoint and save with hash-based filename', 'run_parse_args': 'run parse_args to get CLI arguments for input file, output file, and save keys', 'refactor_process_checkpoint': 'refactor process_checkpoint to add custom key filtering logic before saving the checkpoint', 'review_publish_model': 'review the publish_model module to understand checkpoint processing, key filtering, and hash-based file naming'}
```

