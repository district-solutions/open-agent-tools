# Agent Python Tools

- repo: facebookresearch/pointcontrast
- repo_uri: https://github.com/facebookresearch/pointcontrast

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/ddp_main.py

Prompts

```
['run the VoteNet 3D object detection training pipeline on SUNRGBD or ScanNet datasets with Hydra config', 'run the VoteNet 3D object detection testing pipeline on a validation dataset with Hydra config', 'run the BoxNet 3D object detection training pipeline using the main entry point with config', "load pretrained model weights by filtering keys that match the target model's state dict shape", 'setup logging with a StreamHandler that formats output with the hostname and timestamp']
```

Usage

```
{'run_VoteNet_training': 'run the VoteNet 3D object detection training pipeline on SUNRGBD or ScanNet datasets with Hydra config', 'run_VoteNet_testing': 'run the VoteNet 3D object detection testing pipeline on a validation dataset with Hydra config', 'run_BoxNet_training': 'run the BoxNet 3D object detection training pipeline using the main entry point with config', 'load_state_with_same_shape': "load pretrained model weights by filtering keys that match the target model's state dict shape", 'setup_logging': 'setup logging with a StreamHandler that formats output with the hostname and timestamp'}
```

