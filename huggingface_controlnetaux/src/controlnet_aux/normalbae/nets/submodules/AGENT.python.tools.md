# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/normalbae/nets/submodules/decoder.py

Prompts

```
['build a Decoder with BN architecture for multi-resolution surface normal prediction', 'build a Decoder with GN architecture for multi-resolution surface normal prediction', 'run the Decoder forward pass in test mode with encoder features', 'run the Decoder forward pass in train mode with features and ground truth mask', 'review the Decoder forward method for multi-resolution output generation', 'build a python module to create an Encoder that loads tf_efficientnet_b5_ap as a feature extractor', 'create a function that runs the Encoder forward pass to extract multi-scale features from input tensor x', 'test the Encoder class by instantiating it and verifying it loads the efficientnet base model correctly', 'refactor the Encoder __init__ to accept a configurable base model name instead of hardcoding tf_efficientnet_b5_ap', 'review the Encoder forward method that iterates through model blocks to collect intermediate feature maps', 'build a UpSampleBN module that upsamples and concatenates tensors with BatchNorm', 'build a UpSampleGN module that upsamples and concatenates tensors with GroupNorm and weight standardization', 'create a Conv2d layer that applies weight standardization during the forward pass', 'summarize the norm_normalize function that normalizes normal vectors and applies ELU to kappa', 'review the sample_points function that performs uncertainty-guided importance sampling for training']
```

Usage

```
{'build_Decoder_BN': 'build a Decoder with BN architecture for multi-resolution surface normal prediction', 'build_Decoder_GN': 'build a Decoder with GN architecture for multi-resolution surface normal prediction', 'run_Decoder_forward_test': 'run the Decoder forward pass in test mode with encoder features', 'run_Decoder_forward_train': 'run the Decoder forward pass in train mode with features and ground truth mask', 'review_Decoder_forward': 'review the Decoder forward method for multi-resolution output generation'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/normalbae/nets/submodules/encoder.py

Prompts

```
['build a Decoder with BN architecture for multi-resolution surface normal prediction', 'build a Decoder with GN architecture for multi-resolution surface normal prediction', 'run the Decoder forward pass in test mode with encoder features', 'run the Decoder forward pass in train mode with features and ground truth mask', 'review the Decoder forward method for multi-resolution output generation', 'build a python module to create an Encoder that loads tf_efficientnet_b5_ap as a feature extractor', 'create a function that runs the Encoder forward pass to extract multi-scale features from input tensor x', 'test the Encoder class by instantiating it and verifying it loads the efficientnet base model correctly', 'refactor the Encoder __init__ to accept a configurable base model name instead of hardcoding tf_efficientnet_b5_ap', 'review the Encoder forward method that iterates through model blocks to collect intermediate feature maps', 'build a UpSampleBN module that upsamples and concatenates tensors with BatchNorm', 'build a UpSampleGN module that upsamples and concatenates tensors with GroupNorm and weight standardization', 'create a Conv2d layer that applies weight standardization during the forward pass', 'summarize the norm_normalize function that normalizes normal vectors and applies ELU to kappa', 'review the sample_points function that performs uncertainty-guided importance sampling for training']
```

Usage

```
{'build_encoder': 'build a python module to create an Encoder that loads tf_efficientnet_b5_ap as a feature extractor', 'create_encoder_forward': 'create a function that runs the Encoder forward pass to extract multi-scale features from input tensor x', 'test_Encoder': 'test the Encoder class by instantiating it and verifying it loads the efficientnet base model correctly', 'refactor_Encoder_init': 'refactor the Encoder __init__ to accept a configurable base model name instead of hardcoding tf_efficientnet_b5_ap', 'review_Encoder_forward': 'review the Encoder forward method that iterates through model blocks to collect intermediate feature maps'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/normalbae/nets/submodules/submodules.py

Prompts

```
['build a Decoder with BN architecture for multi-resolution surface normal prediction', 'build a Decoder with GN architecture for multi-resolution surface normal prediction', 'run the Decoder forward pass in test mode with encoder features', 'run the Decoder forward pass in train mode with features and ground truth mask', 'review the Decoder forward method for multi-resolution output generation', 'build a python module to create an Encoder that loads tf_efficientnet_b5_ap as a feature extractor', 'create a function that runs the Encoder forward pass to extract multi-scale features from input tensor x', 'test the Encoder class by instantiating it and verifying it loads the efficientnet base model correctly', 'refactor the Encoder __init__ to accept a configurable base model name instead of hardcoding tf_efficientnet_b5_ap', 'review the Encoder forward method that iterates through model blocks to collect intermediate feature maps', 'build a UpSampleBN module that upsamples and concatenates tensors with BatchNorm', 'build a UpSampleGN module that upsamples and concatenates tensors with GroupNorm and weight standardization', 'create a Conv2d layer that applies weight standardization during the forward pass', 'summarize the norm_normalize function that normalizes normal vectors and applies ELU to kappa', 'review the sample_points function that performs uncertainty-guided importance sampling for training']
```

Usage

```
{'build_upsamplebn_module': 'build a UpSampleBN module that upsamples and concatenates tensors with BatchNorm', 'build_upsamplegn_module': 'build a UpSampleGN module that upsamples and concatenates tensors with GroupNorm and weight standardization', 'create_conv2d_with_weight_std': 'create a Conv2d layer that applies weight standardization during the forward pass', 'summarize_norm_normalize': 'summarize the norm_normalize function that normalizes normal vectors and applies ELU to kappa', 'review_sample_points': 'review the sample_points function that performs uncertainty-guided importance sampling for training'}
```

