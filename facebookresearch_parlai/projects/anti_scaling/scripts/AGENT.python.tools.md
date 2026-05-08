# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/anti_scaling/scripts/remove_projection_matrices.py

Prompts

```
['remove projection matrices from a ParlAI model checkpoint file and re-save it', 'run the CLI tool to remove distillation projection matrices from a model file', 'create a backup copy of the original model file before removing projection matrices', 'filter out encoder_proj_layer, embedding_proj_layers, and hidden_proj_layers keys from a model state dict', 'atomically save the modified model state dict back to the model file path']
```

Usage

```
{'remove_projection_matrices': 'remove projection matrices from a ParlAI model checkpoint file and re-save it', 'run_remove_projection_matrices_cli': 'run the CLI tool to remove distillation projection matrices from a model file', 'backup_model_before_modification': 'create a backup copy of the original model file before removing projection matrices', 'filter_model_state_dict_keys': 'filter out encoder_proj_layer, embedding_proj_layers, and hidden_proj_layers keys from a model state dict', 'atomic_save_model': 'atomically save the modified model state dict back to the model file path'}
```

