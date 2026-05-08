# Agent Python Tools

- repo: facebookresearch/consistentdepth
- repo_uri: https://github.com/facebookresearch/consistent_depth

## File: facebookresearch_consistentdepth/monodepth/monodepth2/networks/depth_decoder.py

Prompts

```
['create a DepthDecoder instance with encoder channel counts and multi-scale output configuration', 'run the DepthDecoder forward pass on encoder feature lists to produce multi-scale disparity maps', 'review the DepthDecoder upsampling convolutions and skip connection design for monocular depth estimation', 'refactor the DepthDecoder scales parameter to control which pyramid levels output disparity predictions', 'summarize the DepthDecoder forward method that upsamples features through ConvBlocks and applies sigmoid for disparity', 'create a ResnetEncoder with 18 or 50 layers for monocular depth estimation feature extraction', 'run the ResnetEncoder forward pass on an input image tensor to extract multi-scale features', 'build a ResNet model with multiple stacked input images for multi-frame depth estimation', 'create a ResNetMultiImageInput model that accepts varying numbers of input image channels', 'review the ResnetEncoder num_ch_enc array to understand feature channel dimensions at each layer']
```

Usage

```
{'create_depth_decoder': 'create a DepthDecoder instance with encoder channel counts and multi-scale output configuration', 'run_depth_decoder_forward': 'run the DepthDecoder forward pass on encoder feature lists to produce multi-scale disparity maps', 'review_depth_decoder_architecture': 'review the DepthDecoder upsampling convolutions and skip connection design for monocular depth estimation', 'refactor_depth_decoder_scales': 'refactor the DepthDecoder scales parameter to control which pyramid levels output disparity predictions', 'summarize_depth_decoder_forward': 'summarize the DepthDecoder forward method that upsamples features through ConvBlocks and applies sigmoid for disparity'}
```

## File: facebookresearch_consistentdepth/monodepth/monodepth2/networks/resnet_encoder.py

Prompts

```
['create a DepthDecoder instance with encoder channel counts and multi-scale output configuration', 'run the DepthDecoder forward pass on encoder feature lists to produce multi-scale disparity maps', 'review the DepthDecoder upsampling convolutions and skip connection design for monocular depth estimation', 'refactor the DepthDecoder scales parameter to control which pyramid levels output disparity predictions', 'summarize the DepthDecoder forward method that upsamples features through ConvBlocks and applies sigmoid for disparity', 'create a ResnetEncoder with 18 or 50 layers for monocular depth estimation feature extraction', 'run the ResnetEncoder forward pass on an input image tensor to extract multi-scale features', 'build a ResNet model with multiple stacked input images for multi-frame depth estimation', 'create a ResNetMultiImageInput model that accepts varying numbers of input image channels', 'review the ResnetEncoder num_ch_enc array to understand feature channel dimensions at each layer']
```

Usage

```
{'create_ResnetEncoder': 'create a ResnetEncoder with 18 or 50 layers for monocular depth estimation feature extraction', 'run_ResnetEncoder_forward': 'run the ResnetEncoder forward pass on an input image tensor to extract multi-scale features', 'build_resnet_multiimage_input': 'build a ResNet model with multiple stacked input images for multi-frame depth estimation', 'create_ResNetMultiImageInput': 'create a ResNetMultiImageInput model that accepts varying numbers of input image channels', 'review_ResnetEncoder_num_ch_enc': 'review the ResnetEncoder num_ch_enc array to understand feature channel dimensions at each layer'}
```

