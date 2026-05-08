# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/examples/mpc_imagenet/mpc_imagenet.py

Prompts

```
['run inference using an encrypted torchvision model on the ImageNet validation dataset', 'convert a pretrained PyTorch model to an encrypted model using crypten.nn.from_pytorch', 'create an encrypted tensor from a plain PyTorch tensor using crypten.cryptensor', 'decrypt an encrypted model output by calling get_plain_text on the cryptensor', 'log an encrypted model graph to TensorBoard using crypten SummaryWriter']
```

Usage

```
{'run_mpc_imagenet_inference': 'run inference using an encrypted torchvision model on the ImageNet validation dataset', 'encrypt_pytorch_model': 'convert a pretrained PyTorch model to an encrypted model using crypten.nn.from_pytorch', 'encrypt_tensor': 'create an encrypted tensor from a plain PyTorch tensor using crypten.cryptensor', 'decrypt_encrypted_output': 'decrypt an encrypted model output by calling get_plain_text on the cryptensor', 'visualize_encrypted_model': 'log an encrypted model graph to TensorBoard using crypten SummaryWriter'}
```

