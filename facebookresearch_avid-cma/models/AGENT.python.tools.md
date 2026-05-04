# Agent Python Tools

- repo: facebookresearch/avid-cma
- repo_uri: https://github.com/facebookresearch/avid-cma

## File: facebookresearch_avid-cma/models/audio.py

Prompts

```
['build a Conv2D audio feature extractor model with depth 10 and 512 output dimensions', 'run the Conv2D forward pass on an input tensor to get a pooled 512-dim embedding', 'run the Conv2D forward pass with return_embs=True to get multi-scale intermediate feature maps', 'review the Conv2D architecture with conv1, four Basic2DBlock stages, and adaptive max pooling', 'test that the Conv2D model outputs a tensor with out_dim equal to 512', 'build an audio-visual wrapper model from video and audio backbone models with a shared projection dimension', 'create a multi-layer linear projection head with ReLU activations for embedding dimensionality reduction', 'create an AV_Wrapper module that processes video and audio inputs through separate models and optional projection layers', 'run forward pass on video and audio tensors to get projected embeddings from both modalities', 'load a pretrained audio-visual wrapper model from a checkpoint file with DataParallel state dict', 'create a Basic2DBlock with specified input and output planes for 2D convolution', 'build a forward pass through a Basic2DBlock using two 3x3 convolutions with batch norm', 'create a BasicR2P1DBlock with specified input and output planes for 3D spatiotemporal convolution', 'run a forward pass through a BasicR2P1DBlock with residual connection and spatiotemporal convolutions', 'review the BasicR2P1DBlock residual connection logic that adds identity or 1x1x1 conv output', 'build an R2Plus1D video model with default depth 18 for feature extraction', 'build an R2Plus1D video model with depth 34 for deeper feature extraction', 'run the R2Plus1D model forward pass on video tensor and return pooled embeddings', 'run the R2Plus1D model forward pass with return_embs to get all intermediate layer features', 'review the BasicR2P1DBlock class and its spatial-temporal convolution with residual connection logic']
```

Usage

```
{'build_Conv2D_model': 'build a Conv2D audio feature extractor model with depth 10 and 512 output dimensions', 'run_Conv2D_forward': 'run the Conv2D forward pass on an input tensor to get a pooled 512-dim embedding', 'run_Conv2D_forward_with_embs': 'run the Conv2D forward pass with return_embs=True to get multi-scale intermediate feature maps', 'review_Conv2D_architecture': 'review the Conv2D architecture with conv1, four Basic2DBlock stages, and adaptive max pooling', 'test_Conv2D_out_dim': 'test that the Conv2D model outputs a tensor with out_dim equal to 512'}
```

## File: facebookresearch_avid-cma/models/av_wrapper.py

Prompts

```
['build a Conv2D audio feature extractor model with depth 10 and 512 output dimensions', 'run the Conv2D forward pass on an input tensor to get a pooled 512-dim embedding', 'run the Conv2D forward pass with return_embs=True to get multi-scale intermediate feature maps', 'review the Conv2D architecture with conv1, four Basic2DBlock stages, and adaptive max pooling', 'test that the Conv2D model outputs a tensor with out_dim equal to 512', 'build an audio-visual wrapper model from video and audio backbone models with a shared projection dimension', 'create a multi-layer linear projection head with ReLU activations for embedding dimensionality reduction', 'create an AV_Wrapper module that processes video and audio inputs through separate models and optional projection layers', 'run forward pass on video and audio tensors to get projected embeddings from both modalities', 'load a pretrained audio-visual wrapper model from a checkpoint file with DataParallel state dict', 'create a Basic2DBlock with specified input and output planes for 2D convolution', 'build a forward pass through a Basic2DBlock using two 3x3 convolutions with batch norm', 'create a BasicR2P1DBlock with specified input and output planes for 3D spatiotemporal convolution', 'run a forward pass through a BasicR2P1DBlock with residual connection and spatiotemporal convolutions', 'review the BasicR2P1DBlock residual connection logic that adds identity or 1x1x1 conv output', 'build an R2Plus1D video model with default depth 18 for feature extraction', 'build an R2Plus1D video model with depth 34 for deeper feature extraction', 'run the R2Plus1D model forward pass on video tensor and return pooled embeddings', 'run the R2Plus1D model forward pass with return_embs to get all intermediate layer features', 'review the BasicR2P1DBlock class and its spatial-temporal convolution with residual connection logic']
```

Usage

```
{'build_av_wrapper_model': 'build an audio-visual wrapper model from video and audio backbone models with a shared projection dimension', 'create_head_projection': 'create a multi-layer linear projection head with ReLU activations for embedding dimensionality reduction', 'create_av_wrapper_module': 'create an AV_Wrapper module that processes video and audio inputs through separate models and optional projection layers', 'run_av_wrapper_forward': 'run forward pass on video and audio tensors to get projected embeddings from both modalities', 'load_av_wrapper_checkpoint': 'load a pretrained audio-visual wrapper model from a checkpoint file with DataParallel state dict'}
```

## File: facebookresearch_avid-cma/models/network_blocks.py

Prompts

```
['build a Conv2D audio feature extractor model with depth 10 and 512 output dimensions', 'run the Conv2D forward pass on an input tensor to get a pooled 512-dim embedding', 'run the Conv2D forward pass with return_embs=True to get multi-scale intermediate feature maps', 'review the Conv2D architecture with conv1, four Basic2DBlock stages, and adaptive max pooling', 'test that the Conv2D model outputs a tensor with out_dim equal to 512', 'build an audio-visual wrapper model from video and audio backbone models with a shared projection dimension', 'create a multi-layer linear projection head with ReLU activations for embedding dimensionality reduction', 'create an AV_Wrapper module that processes video and audio inputs through separate models and optional projection layers', 'run forward pass on video and audio tensors to get projected embeddings from both modalities', 'load a pretrained audio-visual wrapper model from a checkpoint file with DataParallel state dict', 'create a Basic2DBlock with specified input and output planes for 2D convolution', 'build a forward pass through a Basic2DBlock using two 3x3 convolutions with batch norm', 'create a BasicR2P1DBlock with specified input and output planes for 3D spatiotemporal convolution', 'run a forward pass through a BasicR2P1DBlock with residual connection and spatiotemporal convolutions', 'review the BasicR2P1DBlock residual connection logic that adds identity or 1x1x1 conv output', 'build an R2Plus1D video model with default depth 18 for feature extraction', 'build an R2Plus1D video model with depth 34 for deeper feature extraction', 'run the R2Plus1D model forward pass on video tensor and return pooled embeddings', 'run the R2Plus1D model forward pass with return_embs to get all intermediate layer features', 'review the BasicR2P1DBlock class and its spatial-temporal convolution with residual connection logic']
```

Usage

```
{'create_Basic2DBlock': 'create a Basic2DBlock with specified input and output planes for 2D convolution', 'build_Basic2DBlock_forward': 'build a forward pass through a Basic2DBlock using two 3x3 convolutions with batch norm', 'create_BasicR2P1DBlock': 'create a BasicR2P1DBlock with specified input and output planes for 3D spatiotemporal convolution', 'run_BasicR2P1DBlock_forward': 'run a forward pass through a BasicR2P1DBlock with residual connection and spatiotemporal convolutions', 'review_BasicR2P1DBlock_residual': 'review the BasicR2P1DBlock residual connection logic that adds identity or 1x1x1 conv output'}
```

## File: facebookresearch_avid-cma/models/video.py

Prompts

```
['build a Conv2D audio feature extractor model with depth 10 and 512 output dimensions', 'run the Conv2D forward pass on an input tensor to get a pooled 512-dim embedding', 'run the Conv2D forward pass with return_embs=True to get multi-scale intermediate feature maps', 'review the Conv2D architecture with conv1, four Basic2DBlock stages, and adaptive max pooling', 'test that the Conv2D model outputs a tensor with out_dim equal to 512', 'build an audio-visual wrapper model from video and audio backbone models with a shared projection dimension', 'create a multi-layer linear projection head with ReLU activations for embedding dimensionality reduction', 'create an AV_Wrapper module that processes video and audio inputs through separate models and optional projection layers', 'run forward pass on video and audio tensors to get projected embeddings from both modalities', 'load a pretrained audio-visual wrapper model from a checkpoint file with DataParallel state dict', 'create a Basic2DBlock with specified input and output planes for 2D convolution', 'build a forward pass through a Basic2DBlock using two 3x3 convolutions with batch norm', 'create a BasicR2P1DBlock with specified input and output planes for 3D spatiotemporal convolution', 'run a forward pass through a BasicR2P1DBlock with residual connection and spatiotemporal convolutions', 'review the BasicR2P1DBlock residual connection logic that adds identity or 1x1x1 conv output', 'build an R2Plus1D video model with default depth 18 for feature extraction', 'build an R2Plus1D video model with depth 34 for deeper feature extraction', 'run the R2Plus1D model forward pass on video tensor and return pooled embeddings', 'run the R2Plus1D model forward pass with return_embs to get all intermediate layer features', 'review the BasicR2P1DBlock class and its spatial-temporal convolution with residual connection logic']
```

Usage

```
{'build_r2plus1d_model_depth18': 'build an R2Plus1D video model with default depth 18 for feature extraction', 'build_r2plus1d_model_depth34': 'build an R2Plus1D video model with depth 34 for deeper feature extraction', 'run_r2plus1d_forward_pooled': 'run the R2Plus1D model forward pass on video tensor and return pooled embeddings', 'run_r2plus1d_forward_embeddings': 'run the R2Plus1D model forward pass with return_embs to get all intermediate layer features', 'review_basicr2p1dblock_residual': 'review the BasicR2P1DBlock class and its spatial-temporal convolution with residual connection logic'}
```

