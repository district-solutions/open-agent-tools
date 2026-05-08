# Agent Python Tools

- repo: facebookresearch/covidprognosis
- repo_uri: https://github.com/facebookresearch/covidprognosis

## File: facebookresearch_covidprognosis/cp_examples/sip_finetune/sip_finetune.py

Prompts

```
['create a PyTorch Lightning module for fine-tuning a pretrained model with a linear classifier on pathology data', 'run a training step that computes BCE loss and logs accuracy metrics for each pathology label', 'run a validation step that computes loss and collects logits and targets for each pathology', 'configure an Adam optimizer with cosine annealing scheduler for the classifier or full model', 'filter NaN values from logits and labels tensors before computing loss or metrics', 'run the SIP fine-tuning training pipeline for chest X-ray pathology classification using PyTorch Lightning', 'build command-line arguments for SIP fine-tuning with dataset, GPU, batch size, and checkpoint configuration', 'fetch positive class weights from a CSV dataset to handle label imbalance for NIH or MIMIC data', 'review the build_args function to understand default training hyperparameters and dataset path resolution', 'refactor the cli_main function to customize data transforms or model architecture for SIP fine-tuning']
```

Usage

```
{'create_SipModule': 'create a PyTorch Lightning module for fine-tuning a pretrained model with a linear classifier on pathology data', 'run_SipModule_training_step': 'run a training step that computes BCE loss and logs accuracy metrics for each pathology label', 'run_SipModule_validation_step': 'run a validation step that computes loss and collects logits and targets for each pathology', 'run_SipModule_configure_optimizers': 'configure an Adam optimizer with cosine annealing scheduler for the classifier or full model', 'run_filter_nans': 'filter NaN values from logits and labels tensors before computing loss or metrics'}
```

## File: facebookresearch_covidprognosis/cp_examples/sip_finetune/train_sip.py

Prompts

```
['create a PyTorch Lightning module for fine-tuning a pretrained model with a linear classifier on pathology data', 'run a training step that computes BCE loss and logs accuracy metrics for each pathology label', 'run a validation step that computes loss and collects logits and targets for each pathology', 'configure an Adam optimizer with cosine annealing scheduler for the classifier or full model', 'filter NaN values from logits and labels tensors before computing loss or metrics', 'run the SIP fine-tuning training pipeline for chest X-ray pathology classification using PyTorch Lightning', 'build command-line arguments for SIP fine-tuning with dataset, GPU, batch size, and checkpoint configuration', 'fetch positive class weights from a CSV dataset to handle label imbalance for NIH or MIMIC data', 'review the build_args function to understand default training hyperparameters and dataset path resolution', 'refactor the cli_main function to customize data transforms or model architecture for SIP fine-tuning']
```

Usage

```
{'run_sip_finetune_training': 'run the SIP fine-tuning training pipeline for chest X-ray pathology classification using PyTorch Lightning', 'build_args_cli': 'build command-line arguments for SIP fine-tuning with dataset, GPU, batch size, and checkpoint configuration', 'fetch_pos_weights': 'fetch positive class weights from a CSV dataset to handle label imbalance for NIH or MIMIC data', 'review_build_args': 'review the build_args function to understand default training hyperparameters and dataset path resolution', 'refactor_cli_main': 'refactor the cli_main function to customize data transforms or model architecture for SIP fine-tuning'}
```

