# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/crypten/nn/privacy/dp_split.py

Prompts

```
['create a DPSplitModel wrapping a PyTorch model with DP noise magnitude and feature and label sources', 'run a forward pass through a DPSplitModel to get encrypted logits and predictions', 'compute the encrypted loss between DPSplitModel predictions and encrypted targets using BCE or RAPPOR loss', 'run backward pass on a DPSplitModel using layer_estimation or full_jacobian protocol to compute DP gradients', 'create a SkippedLoss placeholder object with a message for skipped loss function output']
```

Usage

```
{'create_DPSplitModel': 'create a DPSplitModel wrapping a PyTorch model with DP noise magnitude and feature and label sources', 'run_DPSplitModel_forward': 'run a forward pass through a DPSplitModel to get encrypted logits and predictions', 'compute_DPSplitModel_loss': 'compute the encrypted loss between DPSplitModel predictions and encrypted targets using BCE or RAPPOR loss', 'run_DPSplitModel_backward': 'run backward pass on a DPSplitModel using layer_estimation or full_jacobian protocol to compute DP gradients', 'create_SkippedLoss': 'create a SkippedLoss placeholder object with a message for skipped loss function output'}
```

