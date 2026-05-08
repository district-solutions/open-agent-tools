# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/models/utils/ac.py

Prompts

```
['apply activation checkpointing to every Nth layer in a ModuleList to reduce memory usage during training', 'review the apply_layerwise_ac function to understand how it wraps layers with CheckpointWrapper', 'refactor apply_layerwise_ac to support custom checkpointing strategies beyond NO_REENTRANT', 'test apply_layerwise_ac with a ModuleList to verify every Nth layer is wrapped correctly', 'summarize how apply_layerwise_ac uses CheckpointWrapper to enable layerwise activation checkpointing', 'load checkpoint tensors into a PyTorch model with progress reporting and mismatch validation', 'convert model state dictionary keys using regex pattern replacements from a key map', 'convert a Fairseq state dictionary to Fairseq2 format by applying key mapping and removing legacy keys', 'create a reversed regex key map to convert Fairseq2 keys back to the original format', 'handle errors when checkpoint keys are missing, unexpected, or have shape mismatches with the model', 'apply layerwise FSDP wrapping to a ModuleList of transformer layers using an FSDPWrapper', 'review the apply_layerwise_fsdp function to understand how it wraps layers with FSDP and disables resharding on the last layer', 'refactor apply_layerwise_fsdp to support custom resharding logic per layer instead of only disabling it on the last layer', 'test apply_layerwise_fsdp by wrapping a ModuleList of dummy modules and verifying FSDPWrapper is applied to each layer', 'summarize how apply_layerwise_fsdp iterates over a ModuleList and wraps each layer with FSDPWrapper using reshard_after_forward optimization', 'run the fairseq2 Hugging Face export CLI to convert a model to Hugging Face format', 'run the hg_export CLI with a custom checkpoint directory to export a local model', 'run the hg_export CLI with an extra asset card path to export a custom model', 'run the hg_export CLI to export a fairseq2 model directly to an S3 bucket URI', 'run the hg_export CLI with rich text output disabled for plain logging']
```

Usage

```
{'apply_layerwise_ac': 'apply activation checkpointing to every Nth layer in a ModuleList to reduce memory usage during training', 'review_apply_layerwise_ac': 'review the apply_layerwise_ac function to understand how it wraps layers with CheckpointWrapper', 'refactor_apply_layerwise_ac': 'refactor apply_layerwise_ac to support custom checkpointing strategies beyond NO_REENTRANT', 'test_apply_layerwise_ac': 'test apply_layerwise_ac with a ModuleList to verify every Nth layer is wrapped correctly', 'summarize_apply_layerwise_ac': 'summarize how apply_layerwise_ac uses CheckpointWrapper to enable layerwise activation checkpointing'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/utils/checkpoint.py

Prompts

```
['apply activation checkpointing to every Nth layer in a ModuleList to reduce memory usage during training', 'review the apply_layerwise_ac function to understand how it wraps layers with CheckpointWrapper', 'refactor apply_layerwise_ac to support custom checkpointing strategies beyond NO_REENTRANT', 'test apply_layerwise_ac with a ModuleList to verify every Nth layer is wrapped correctly', 'summarize how apply_layerwise_ac uses CheckpointWrapper to enable layerwise activation checkpointing', 'load checkpoint tensors into a PyTorch model with progress reporting and mismatch validation', 'convert model state dictionary keys using regex pattern replacements from a key map', 'convert a Fairseq state dictionary to Fairseq2 format by applying key mapping and removing legacy keys', 'create a reversed regex key map to convert Fairseq2 keys back to the original format', 'handle errors when checkpoint keys are missing, unexpected, or have shape mismatches with the model', 'apply layerwise FSDP wrapping to a ModuleList of transformer layers using an FSDPWrapper', 'review the apply_layerwise_fsdp function to understand how it wraps layers with FSDP and disables resharding on the last layer', 'refactor apply_layerwise_fsdp to support custom resharding logic per layer instead of only disabling it on the last layer', 'test apply_layerwise_fsdp by wrapping a ModuleList of dummy modules and verifying FSDPWrapper is applied to each layer', 'summarize how apply_layerwise_fsdp iterates over a ModuleList and wraps each layer with FSDPWrapper using reshard_after_forward optimization', 'run the fairseq2 Hugging Face export CLI to convert a model to Hugging Face format', 'run the hg_export CLI with a custom checkpoint directory to export a local model', 'run the hg_export CLI with an extra asset card path to export a custom model', 'run the hg_export CLI to export a fairseq2 model directly to an S3 bucket URI', 'run the hg_export CLI with rich text output disabled for plain logging']
```

Usage

```
{'set_model_state': 'load checkpoint tensors into a PyTorch model with progress reporting and mismatch validation', 'convert_state_dict': 'convert model state dictionary keys using regex pattern replacements from a key map', 'convert_fairseq_state_dict': 'convert a Fairseq state dictionary to Fairseq2 format by applying key mapping and removing legacy keys', 'create_reverse_key_map': 'create a reversed regex key map to convert Fairseq2 keys back to the original format', 'ModelCheckpointMismatchError': 'handle errors when checkpoint keys are missing, unexpected, or have shape mismatches with the model'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/utils/fsdp.py

Prompts

```
['apply activation checkpointing to every Nth layer in a ModuleList to reduce memory usage during training', 'review the apply_layerwise_ac function to understand how it wraps layers with CheckpointWrapper', 'refactor apply_layerwise_ac to support custom checkpointing strategies beyond NO_REENTRANT', 'test apply_layerwise_ac with a ModuleList to verify every Nth layer is wrapped correctly', 'summarize how apply_layerwise_ac uses CheckpointWrapper to enable layerwise activation checkpointing', 'load checkpoint tensors into a PyTorch model with progress reporting and mismatch validation', 'convert model state dictionary keys using regex pattern replacements from a key map', 'convert a Fairseq state dictionary to Fairseq2 format by applying key mapping and removing legacy keys', 'create a reversed regex key map to convert Fairseq2 keys back to the original format', 'handle errors when checkpoint keys are missing, unexpected, or have shape mismatches with the model', 'apply layerwise FSDP wrapping to a ModuleList of transformer layers using an FSDPWrapper', 'review the apply_layerwise_fsdp function to understand how it wraps layers with FSDP and disables resharding on the last layer', 'refactor apply_layerwise_fsdp to support custom resharding logic per layer instead of only disabling it on the last layer', 'test apply_layerwise_fsdp by wrapping a ModuleList of dummy modules and verifying FSDPWrapper is applied to each layer', 'summarize how apply_layerwise_fsdp iterates over a ModuleList and wraps each layer with FSDPWrapper using reshard_after_forward optimization', 'run the fairseq2 Hugging Face export CLI to convert a model to Hugging Face format', 'run the hg_export CLI with a custom checkpoint directory to export a local model', 'run the hg_export CLI with an extra asset card path to export a custom model', 'run the hg_export CLI to export a fairseq2 model directly to an S3 bucket URI', 'run the hg_export CLI with rich text output disabled for plain logging']
```

Usage

```
{'apply_layerwise_fsdp': 'apply layerwise FSDP wrapping to a ModuleList of transformer layers using an FSDPWrapper', 'review_apply_layerwise_fsdp': 'review the apply_layerwise_fsdp function to understand how it wraps layers with FSDP and disables resharding on the last layer', 'refactor_apply_layerwise_fsdp': 'refactor apply_layerwise_fsdp to support custom resharding logic per layer instead of only disabling it on the last layer', 'test_apply_layerwise_fsdp': 'test apply_layerwise_fsdp by wrapping a ModuleList of dummy modules and verifying FSDPWrapper is applied to each layer', 'summarize_apply_layerwise_fsdp': 'summarize how apply_layerwise_fsdp iterates over a ModuleList and wraps each layer with FSDPWrapper using reshard_after_forward optimization'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/utils/hg_export.py

Prompts

```
['apply activation checkpointing to every Nth layer in a ModuleList to reduce memory usage during training', 'review the apply_layerwise_ac function to understand how it wraps layers with CheckpointWrapper', 'refactor apply_layerwise_ac to support custom checkpointing strategies beyond NO_REENTRANT', 'test apply_layerwise_ac with a ModuleList to verify every Nth layer is wrapped correctly', 'summarize how apply_layerwise_ac uses CheckpointWrapper to enable layerwise activation checkpointing', 'load checkpoint tensors into a PyTorch model with progress reporting and mismatch validation', 'convert model state dictionary keys using regex pattern replacements from a key map', 'convert a Fairseq state dictionary to Fairseq2 format by applying key mapping and removing legacy keys', 'create a reversed regex key map to convert Fairseq2 keys back to the original format', 'handle errors when checkpoint keys are missing, unexpected, or have shape mismatches with the model', 'apply layerwise FSDP wrapping to a ModuleList of transformer layers using an FSDPWrapper', 'review the apply_layerwise_fsdp function to understand how it wraps layers with FSDP and disables resharding on the last layer', 'refactor apply_layerwise_fsdp to support custom resharding logic per layer instead of only disabling it on the last layer', 'test apply_layerwise_fsdp by wrapping a ModuleList of dummy modules and verifying FSDPWrapper is applied to each layer', 'summarize how apply_layerwise_fsdp iterates over a ModuleList and wraps each layer with FSDPWrapper using reshard_after_forward optimization', 'run the fairseq2 Hugging Face export CLI to convert a model to Hugging Face format', 'run the hg_export CLI with a custom checkpoint directory to export a local model', 'run the hg_export CLI with an extra asset card path to export a custom model', 'run the hg_export CLI to export a fairseq2 model directly to an S3 bucket URI', 'run the hg_export CLI with rich text output disabled for plain logging']
```

Usage

```
{'run_hg_export_cli': 'run the fairseq2 Hugging Face export CLI to convert a model to Hugging Face format', 'run_export_with_checkpoint_dir': 'run the hg_export CLI with a custom checkpoint directory to export a local model', 'run_export_with_extra_asset': 'run the hg_export CLI with an extra asset card path to export a custom model', 'run_export_to_s3': 'run the hg_export CLI to export a fairseq2 model directly to an S3 bucket URI', 'run_export_no_rich': 'run the hg_export CLI with rich text output disabled for plain logging'}
```

