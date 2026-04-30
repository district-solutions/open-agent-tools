# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/swin2sr/convert_swin2sr_original_to_pytorch.py

Prompts

```
['convert a Swin2SR checkpoint from the original repository to a PyTorch model and save it locally', 'convert a Swin2SR state dict from the original repository format to HuggingFace Transformers format', 'rename a Swin2SR checkpoint key from the original repository naming to HuggingFace Transformers naming', 'get a Swin2SRConfig from a checkpoint URL by detecting the model variant', 'summarize the convert_swin2sr_checkpoint function that downloads, converts, and verifies a Swin2SR checkpoint', 'create a Swin2SRImageProcessorPil instance for image preprocessing with configurable size_divisor', 'build a padded image from a numpy array by making dimensions divisible by size_divisor using symmetric padding', 'run preprocessing on input images with rescaling, padding, and tensor conversion for Swin2SR models', 'test the Swin2SRImageProcessorKwargs type definition for valid preprocessing keyword arguments', 'review the _preprocess method that rescales and pads images then returns a BatchFeature with pixel_values', 'create a Swin2SRImageProcessor instance with custom size_divisor for padding images', 'preprocess images with Swin2SRImageProcessor to produce batched pixel values tensor', 'pad torch tensor images with Swin2SRImageProcessor to make dimensions divisible by size_divisor', 'run internal preprocessing pipeline on grouped images with rescale and pad operations', 'define Swin2SRImageProcessorKwargs type with size_divisor parameter for image padding configuration', 'create a Swin2SRForImageSuperResolution model to upscale low-resolution images with configurable scale factors', 'run the Swin2SRModel encoder to extract hierarchical feature representations from input images', 'build a window partition function to split input features into overlapping windows for self-attention computation', 'test the PixelShuffleUpsampler module that upsamples features using convolution and pixel shuffle layers', 'review the Swin2SRSelfAttention class with cosine attention and continuous relative position bias']
```

Usage

```
{'convert_swin2sr_checkpoint': 'convert a Swin2SR checkpoint from the original repository to a PyTorch model and save it locally', 'convert_state_dict': 'convert a Swin2SR state dict from the original repository format to HuggingFace Transformers format', 'rename_key': 'rename a Swin2SR checkpoint key from the original repository naming to HuggingFace Transformers naming', 'get_config': 'get a Swin2SRConfig from a checkpoint URL by detecting the model variant', 'summarize_convert_swin2sr_checkpoint': 'summarize the convert_swin2sr_checkpoint function that downloads, converts, and verifies a Swin2SR checkpoint'}
```

## File: huggingface_transformers/src/transformers/models/swin2sr/image_processing_pil_swin2sr.py

Prompts

```
['convert a Swin2SR checkpoint from the original repository to a PyTorch model and save it locally', 'convert a Swin2SR state dict from the original repository format to HuggingFace Transformers format', 'rename a Swin2SR checkpoint key from the original repository naming to HuggingFace Transformers naming', 'get a Swin2SRConfig from a checkpoint URL by detecting the model variant', 'summarize the convert_swin2sr_checkpoint function that downloads, converts, and verifies a Swin2SR checkpoint', 'create a Swin2SRImageProcessorPil instance for image preprocessing with configurable size_divisor', 'build a padded image from a numpy array by making dimensions divisible by size_divisor using symmetric padding', 'run preprocessing on input images with rescaling, padding, and tensor conversion for Swin2SR models', 'test the Swin2SRImageProcessorKwargs type definition for valid preprocessing keyword arguments', 'review the _preprocess method that rescales and pads images then returns a BatchFeature with pixel_values', 'create a Swin2SRImageProcessor instance with custom size_divisor for padding images', 'preprocess images with Swin2SRImageProcessor to produce batched pixel values tensor', 'pad torch tensor images with Swin2SRImageProcessor to make dimensions divisible by size_divisor', 'run internal preprocessing pipeline on grouped images with rescale and pad operations', 'define Swin2SRImageProcessorKwargs type with size_divisor parameter for image padding configuration', 'create a Swin2SRForImageSuperResolution model to upscale low-resolution images with configurable scale factors', 'run the Swin2SRModel encoder to extract hierarchical feature representations from input images', 'build a window partition function to split input features into overlapping windows for self-attention computation', 'test the PixelShuffleUpsampler module that upsamples features using convolution and pixel shuffle layers', 'review the Swin2SRSelfAttention class with cosine attention and continuous relative position bias']
```

Usage

```
{'create_Swin2SRImageProcessorPil': 'create a Swin2SRImageProcessorPil instance for image preprocessing with configurable size_divisor', 'build_image_pad': 'build a padded image from a numpy array by making dimensions divisible by size_divisor using symmetric padding', 'run_image_preprocess': 'run preprocessing on input images with rescaling, padding, and tensor conversion for Swin2SR models', 'test_Swin2SRImageProcessorKwargs': 'test the Swin2SRImageProcessorKwargs type definition for valid preprocessing keyword arguments', 'review_Swin2SRImageProcessorPil__preprocess': 'review the _preprocess method that rescales and pads images then returns a BatchFeature with pixel_values'}
```

## File: huggingface_transformers/src/transformers/models/swin2sr/image_processing_swin2sr.py

Prompts

```
['convert a Swin2SR checkpoint from the original repository to a PyTorch model and save it locally', 'convert a Swin2SR state dict from the original repository format to HuggingFace Transformers format', 'rename a Swin2SR checkpoint key from the original repository naming to HuggingFace Transformers naming', 'get a Swin2SRConfig from a checkpoint URL by detecting the model variant', 'summarize the convert_swin2sr_checkpoint function that downloads, converts, and verifies a Swin2SR checkpoint', 'create a Swin2SRImageProcessorPil instance for image preprocessing with configurable size_divisor', 'build a padded image from a numpy array by making dimensions divisible by size_divisor using symmetric padding', 'run preprocessing on input images with rescaling, padding, and tensor conversion for Swin2SR models', 'test the Swin2SRImageProcessorKwargs type definition for valid preprocessing keyword arguments', 'review the _preprocess method that rescales and pads images then returns a BatchFeature with pixel_values', 'create a Swin2SRImageProcessor instance with custom size_divisor for padding images', 'preprocess images with Swin2SRImageProcessor to produce batched pixel values tensor', 'pad torch tensor images with Swin2SRImageProcessor to make dimensions divisible by size_divisor', 'run internal preprocessing pipeline on grouped images with rescale and pad operations', 'define Swin2SRImageProcessorKwargs type with size_divisor parameter for image padding configuration', 'create a Swin2SRForImageSuperResolution model to upscale low-resolution images with configurable scale factors', 'run the Swin2SRModel encoder to extract hierarchical feature representations from input images', 'build a window partition function to split input features into overlapping windows for self-attention computation', 'test the PixelShuffleUpsampler module that upsamples features using convolution and pixel shuffle layers', 'review the Swin2SRSelfAttention class with cosine attention and continuous relative position bias']
```

Usage

```
{'create_Swin2SRImageProcessor': 'create a Swin2SRImageProcessor instance with custom size_divisor for padding images', 'preprocess_Swin2SRImageProcessor': 'preprocess images with Swin2SRImageProcessor to produce batched pixel values tensor', 'pad_Swin2SRImageProcessor': 'pad torch tensor images with Swin2SRImageProcessor to make dimensions divisible by size_divisor', '_preprocess_Swin2SRImageProcessor': 'run internal preprocessing pipeline on grouped images with rescale and pad operations', 'Swin2SRImageProcessorKwargs': 'define Swin2SRImageProcessorKwargs type with size_divisor parameter for image padding configuration'}
```

## File: huggingface_transformers/src/transformers/models/swin2sr/modeling_swin2sr.py

Prompts

```
['convert a Swin2SR checkpoint from the original repository to a PyTorch model and save it locally', 'convert a Swin2SR state dict from the original repository format to HuggingFace Transformers format', 'rename a Swin2SR checkpoint key from the original repository naming to HuggingFace Transformers naming', 'get a Swin2SRConfig from a checkpoint URL by detecting the model variant', 'summarize the convert_swin2sr_checkpoint function that downloads, converts, and verifies a Swin2SR checkpoint', 'create a Swin2SRImageProcessorPil instance for image preprocessing with configurable size_divisor', 'build a padded image from a numpy array by making dimensions divisible by size_divisor using symmetric padding', 'run preprocessing on input images with rescaling, padding, and tensor conversion for Swin2SR models', 'test the Swin2SRImageProcessorKwargs type definition for valid preprocessing keyword arguments', 'review the _preprocess method that rescales and pads images then returns a BatchFeature with pixel_values', 'create a Swin2SRImageProcessor instance with custom size_divisor for padding images', 'preprocess images with Swin2SRImageProcessor to produce batched pixel values tensor', 'pad torch tensor images with Swin2SRImageProcessor to make dimensions divisible by size_divisor', 'run internal preprocessing pipeline on grouped images with rescale and pad operations', 'define Swin2SRImageProcessorKwargs type with size_divisor parameter for image padding configuration', 'create a Swin2SRForImageSuperResolution model to upscale low-resolution images with configurable scale factors', 'run the Swin2SRModel encoder to extract hierarchical feature representations from input images', 'build a window partition function to split input features into overlapping windows for self-attention computation', 'test the PixelShuffleUpsampler module that upsamples features using convolution and pixel shuffle layers', 'review the Swin2SRSelfAttention class with cosine attention and continuous relative position bias']
```

Usage

```
{'create_swin2sr_super_resolution': 'create a Swin2SRForImageSuperResolution model to upscale low-resolution images with configurable scale factors', 'run_swin2sr_encoder': 'run the Swin2SRModel encoder to extract hierarchical feature representations from input images', 'build_window_partition': 'build a window partition function to split input features into overlapping windows for self-attention computation', 'test_pixel_shuffle_upsampler': 'test the PixelShuffleUpsampler module that upsamples features using convolution and pixel shuffle layers', 'review_swin2sr_self_attention': 'review the Swin2SRSelfAttention class with cosine attention and continuous relative position bias'}
```

