# Agent Python Tools

- repo: facebookresearch/covidprognosis
- repo_uri: https://github.com/facebookresearch/covidprognosis

## File: facebookresearch_covidprognosis/cp_examples/mip_finetune/mip_model.py

Prompts

```
['load a pretrained DenseNet model from a checkpoint file and return the model and feature dimension', 'filter out NaN values from paired logits and labels tensors', 'create a MIPModel with a pretrained image encoder, transformer encoder, and classifier for temporal image sequences', 'create a PyTorch Lightning MIPModule for training a multiple instance learning model with configurable optimizer and scheduler', 'add model-specific CLI arguments for pretrained file, architecture, pooling, and transformer hyperparameters', 'run the MIP fine-tuning training pipeline via the cli_main entry point', 'build argument parser with defaults for MIP model training using build_args', 'fetch positive class weights from a CSV dataset using fetch_pos_weights', 'review the build_args function to customize default training hyperparameters', 'refactor the create_data_module stub to instantiate an actual XrayDataModule']
```

Usage

```
{'load_pretrained_model': 'load a pretrained DenseNet model from a checkpoint file and return the model and feature dimension', 'filter_nans': 'filter out NaN values from paired logits and labels tensors', 'create_MIPModel': 'create a MIPModel with a pretrained image encoder, transformer encoder, and classifier for temporal image sequences', 'create_MIPModule': 'create a PyTorch Lightning MIPModule for training a multiple instance learning model with configurable optimizer and scheduler', 'add_model_specific_args': 'add model-specific CLI arguments for pretrained file, architecture, pooling, and transformer hyperparameters'}
```

## File: facebookresearch_covidprognosis/cp_examples/mip_finetune/train_mip.py

Prompts

```
['load a pretrained DenseNet model from a checkpoint file and return the model and feature dimension', 'filter out NaN values from paired logits and labels tensors', 'create a MIPModel with a pretrained image encoder, transformer encoder, and classifier for temporal image sequences', 'create a PyTorch Lightning MIPModule for training a multiple instance learning model with configurable optimizer and scheduler', 'add model-specific CLI arguments for pretrained file, architecture, pooling, and transformer hyperparameters', 'run the MIP fine-tuning training pipeline via the cli_main entry point', 'build argument parser with defaults for MIP model training using build_args', 'fetch positive class weights from a CSV dataset using fetch_pos_weights', 'review the build_args function to customize default training hyperparameters', 'refactor the create_data_module stub to instantiate an actual XrayDataModule']
```

Usage

```
{'run_MIP_finetune_training': 'run the MIP fine-tuning training pipeline via the cli_main entry point', 'build_args_for_training': 'build argument parser with defaults for MIP model training using build_args', 'fetch_pos_weights_from_csv': 'fetch positive class weights from a CSV dataset using fetch_pos_weights', 'review_build_args_defaults': 'review the build_args function to customize default training hyperparameters', 'refactor_create_data_module': 'refactor the create_data_module stub to instantiate an actual XrayDataModule'}
```

