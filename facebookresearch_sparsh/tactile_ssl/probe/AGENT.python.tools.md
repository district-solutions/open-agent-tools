# Agent Python Tools

- repo: facebookresearch/sparsh
- repo_uri: https://github.com/facebookresearch/sparsh

## File: facebookresearch_sparsh/tactile_ssl/probe/online_probe.py

Prompts

```
['create an OnlineProbeModule with a decoder and loss function for probing embeddings', 'run embeddings through the OnlineProbeModule decoder to get predictions', 'run a full forward pass through OnlineProbeModule to compute loss and predictions', 'review the OnlineProbeModule class and its forward pass logic', 'test the OnlineProbeModule forward_decoder method with sample tensor embeddings', 'build a DecoderViT model that decodes embeddings back to image patches using a Vision Transformer', 'build a MaskDecoderViT model that reconstructs masked image patches using learnable mask tokens', 'build a preconfigured DecoderViT image decoder with 12 heads and sinusoidal positional encoding', 'test the DecoderViT forward pass by passing embeddings and image shape to get reconstructed patches', 'test the MaskDecoderViT forward pass by passing embeddings, image shape, and restore indices']
```

Usage

```
{'create_online_probe_module': 'create an OnlineProbeModule with a decoder and loss function for probing embeddings', 'run_forward_decoder': 'run embeddings through the OnlineProbeModule decoder to get predictions', 'run_forward_pass': 'run a full forward pass through OnlineProbeModule to compute loss and predictions', 'review_online_probe_module': 'review the OnlineProbeModule class and its forward pass logic', 'test_forward_decoder': 'test the OnlineProbeModule forward_decoder method with sample tensor embeddings'}
```

## File: facebookresearch_sparsh/tactile_ssl/probe/reconstruction.py

Prompts

```
['create an OnlineProbeModule with a decoder and loss function for probing embeddings', 'run embeddings through the OnlineProbeModule decoder to get predictions', 'run a full forward pass through OnlineProbeModule to compute loss and predictions', 'review the OnlineProbeModule class and its forward pass logic', 'test the OnlineProbeModule forward_decoder method with sample tensor embeddings', 'build a DecoderViT model that decodes embeddings back to image patches using a Vision Transformer', 'build a MaskDecoderViT model that reconstructs masked image patches using learnable mask tokens', 'build a preconfigured DecoderViT image decoder with 12 heads and sinusoidal positional encoding', 'test the DecoderViT forward pass by passing embeddings and image shape to get reconstructed patches', 'test the MaskDecoderViT forward pass by passing embeddings, image shape, and restore indices']
```

Usage

```
{'build_DecoderViT': 'build a DecoderViT model that decodes embeddings back to image patches using a Vision Transformer', 'build_MaskDecoderViT': 'build a MaskDecoderViT model that reconstructs masked image patches using learnable mask tokens', 'build_DecoderImage': 'build a preconfigured DecoderViT image decoder with 12 heads and sinusoidal positional encoding', 'test_DecoderViT_forward': 'test the DecoderViT forward pass by passing embeddings and image shape to get reconstructed patches', 'test_MaskDecoderViT_forward': 'test the MaskDecoderViT forward pass by passing embeddings, image shape, and restore indices'}
```

