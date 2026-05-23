# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/fastmri/models/adaptive_varnet.py

Prompts

```
['build an AdaptiveVarNet model with configurable cascades, budget, and policy for MRI reconstruction', 'build an AdaptiveSensitivityModel with a NormUnet to estimate coil sensitivities from k-space data', 'build an AdaptiveVarNetBlock with soft or hard data consistency and a U-Net regularizer', 'review the AdaptiveVarNet forward pass that runs cascades with policy-based adaptive acquisition', 'refactor the AdaptiveVarNetBlock forward method to switch dc_mode between first, last, or simul', 'build a LOUPEPolicy model with num_actions and budget parameters for k-space sampling', 'build a StraightThroughPolicy model with budget and crop_size for active acquisition', 'build a LineConvSampler with convolutional feature extractor and fully connected layers', 'test the ThresholdSigmoidMask straight-through estimator for stochastic binarization of probability masks', 'review the LOUPEPolicy forward method that returns mask, masked kspace, and probability mask', 'build a U-Net model with configurable input channels, output channels, and pool layers for image segmentation', 'run a forward pass through the U-Net model on a 4D input tensor to get segmentation output', 'create a ConvBlock with two convolution layers, instance normalization, LeakyReLU, and dropout for feature extraction', 'create a TransposeConvBlock with transposed convolution, instance normalization, and LeakyReLU for upsampling features', 'review the U-Net encoder-decoder architecture with skip connections and reflect padding for odd dimensions', 'build a VarNet model with configurable cascades and sensitivity map U-Net for MRI reconstruction', 'create a NormUnet model with normalization applied to input for numerically stable U-Net training', 'run a SensitivityModel to estimate coil sensitivities from multichannel k-space MRI data', 'test a VarNetBlock that applies soft data consistency with a U-Net regularizer', 'review the NormUnet forward pass that normalizes, pads, runs U-Net, then unnormalizes output']
```

Usage

```
{'build_adaptive_varnet_model': 'build an AdaptiveVarNet model with configurable cascades, budget, and policy for MRI reconstruction', 'build_adaptive_sensitivity_model': 'build an AdaptiveSensitivityModel with a NormUnet to estimate coil sensitivities from k-space data', 'build_adaptive_varnet_block': 'build an AdaptiveVarNetBlock with soft or hard data consistency and a U-Net regularizer', 'review_adaptive_varnet_forward': 'review the AdaptiveVarNet forward pass that runs cascades with policy-based adaptive acquisition', 'refactor_adaptive_varnet_dc_mode': 'refactor the AdaptiveVarNetBlock forward method to switch dc_mode between first, last, or simul'}
```

## File: facebookresearch_fastmri/fastmri/models/policy.py

Prompts

```
['build an AdaptiveVarNet model with configurable cascades, budget, and policy for MRI reconstruction', 'build an AdaptiveSensitivityModel with a NormUnet to estimate coil sensitivities from k-space data', 'build an AdaptiveVarNetBlock with soft or hard data consistency and a U-Net regularizer', 'review the AdaptiveVarNet forward pass that runs cascades with policy-based adaptive acquisition', 'refactor the AdaptiveVarNetBlock forward method to switch dc_mode between first, last, or simul', 'build a LOUPEPolicy model with num_actions and budget parameters for k-space sampling', 'build a StraightThroughPolicy model with budget and crop_size for active acquisition', 'build a LineConvSampler with convolutional feature extractor and fully connected layers', 'test the ThresholdSigmoidMask straight-through estimator for stochastic binarization of probability masks', 'review the LOUPEPolicy forward method that returns mask, masked kspace, and probability mask', 'build a U-Net model with configurable input channels, output channels, and pool layers for image segmentation', 'run a forward pass through the U-Net model on a 4D input tensor to get segmentation output', 'create a ConvBlock with two convolution layers, instance normalization, LeakyReLU, and dropout for feature extraction', 'create a TransposeConvBlock with transposed convolution, instance normalization, and LeakyReLU for upsampling features', 'review the U-Net encoder-decoder architecture with skip connections and reflect padding for odd dimensions', 'build a VarNet model with configurable cascades and sensitivity map U-Net for MRI reconstruction', 'create a NormUnet model with normalization applied to input for numerically stable U-Net training', 'run a SensitivityModel to estimate coil sensitivities from multichannel k-space MRI data', 'test a VarNetBlock that applies soft data consistency with a U-Net regularizer', 'review the NormUnet forward pass that normalizes, pads, runs U-Net, then unnormalizes output']
```

Usage

```
{'build_LOUPEPolicy': 'build a LOUPEPolicy model with num_actions and budget parameters for k-space sampling', 'build_StraightThroughPolicy': 'build a StraightThroughPolicy model with budget and crop_size for active acquisition', 'build_LineConvSampler': 'build a LineConvSampler with convolutional feature extractor and fully connected layers', 'test_ThresholdSigmoidMask': 'test the ThresholdSigmoidMask straight-through estimator for stochastic binarization of probability masks', 'review_LOUPEPolicy_forward': 'review the LOUPEPolicy forward method that returns mask, masked kspace, and probability mask'}
```

## File: facebookresearch_fastmri/fastmri/models/unet.py

Prompts

```
['build an AdaptiveVarNet model with configurable cascades, budget, and policy for MRI reconstruction', 'build an AdaptiveSensitivityModel with a NormUnet to estimate coil sensitivities from k-space data', 'build an AdaptiveVarNetBlock with soft or hard data consistency and a U-Net regularizer', 'review the AdaptiveVarNet forward pass that runs cascades with policy-based adaptive acquisition', 'refactor the AdaptiveVarNetBlock forward method to switch dc_mode between first, last, or simul', 'build a LOUPEPolicy model with num_actions and budget parameters for k-space sampling', 'build a StraightThroughPolicy model with budget and crop_size for active acquisition', 'build a LineConvSampler with convolutional feature extractor and fully connected layers', 'test the ThresholdSigmoidMask straight-through estimator for stochastic binarization of probability masks', 'review the LOUPEPolicy forward method that returns mask, masked kspace, and probability mask', 'build a U-Net model with configurable input channels, output channels, and pool layers for image segmentation', 'run a forward pass through the U-Net model on a 4D input tensor to get segmentation output', 'create a ConvBlock with two convolution layers, instance normalization, LeakyReLU, and dropout for feature extraction', 'create a TransposeConvBlock with transposed convolution, instance normalization, and LeakyReLU for upsampling features', 'review the U-Net encoder-decoder architecture with skip connections and reflect padding for odd dimensions', 'build a VarNet model with configurable cascades and sensitivity map U-Net for MRI reconstruction', 'create a NormUnet model with normalization applied to input for numerically stable U-Net training', 'run a SensitivityModel to estimate coil sensitivities from multichannel k-space MRI data', 'test a VarNetBlock that applies soft data consistency with a U-Net regularizer', 'review the NormUnet forward pass that normalizes, pads, runs U-Net, then unnormalizes output']
```

Usage

```
{'build_unet_model': 'build a U-Net model with configurable input channels, output channels, and pool layers for image segmentation', 'run_unet_forward_pass': 'run a forward pass through the U-Net model on a 4D input tensor to get segmentation output', 'create_conv_block': 'create a ConvBlock with two convolution layers, instance normalization, LeakyReLU, and dropout for feature extraction', 'create_transpose_conv_block': 'create a TransposeConvBlock with transposed convolution, instance normalization, and LeakyReLU for upsampling features', 'review_unet_architecture': 'review the U-Net encoder-decoder architecture with skip connections and reflect padding for odd dimensions'}
```

## File: facebookresearch_fastmri/fastmri/models/varnet.py

Prompts

```
['build an AdaptiveVarNet model with configurable cascades, budget, and policy for MRI reconstruction', 'build an AdaptiveSensitivityModel with a NormUnet to estimate coil sensitivities from k-space data', 'build an AdaptiveVarNetBlock with soft or hard data consistency and a U-Net regularizer', 'review the AdaptiveVarNet forward pass that runs cascades with policy-based adaptive acquisition', 'refactor the AdaptiveVarNetBlock forward method to switch dc_mode between first, last, or simul', 'build a LOUPEPolicy model with num_actions and budget parameters for k-space sampling', 'build a StraightThroughPolicy model with budget and crop_size for active acquisition', 'build a LineConvSampler with convolutional feature extractor and fully connected layers', 'test the ThresholdSigmoidMask straight-through estimator for stochastic binarization of probability masks', 'review the LOUPEPolicy forward method that returns mask, masked kspace, and probability mask', 'build a U-Net model with configurable input channels, output channels, and pool layers for image segmentation', 'run a forward pass through the U-Net model on a 4D input tensor to get segmentation output', 'create a ConvBlock with two convolution layers, instance normalization, LeakyReLU, and dropout for feature extraction', 'create a TransposeConvBlock with transposed convolution, instance normalization, and LeakyReLU for upsampling features', 'review the U-Net encoder-decoder architecture with skip connections and reflect padding for odd dimensions', 'build a VarNet model with configurable cascades and sensitivity map U-Net for MRI reconstruction', 'create a NormUnet model with normalization applied to input for numerically stable U-Net training', 'run a SensitivityModel to estimate coil sensitivities from multichannel k-space MRI data', 'test a VarNetBlock that applies soft data consistency with a U-Net regularizer', 'review the NormUnet forward pass that normalizes, pads, runs U-Net, then unnormalizes output']
```

Usage

```
{'build_varnet_model': 'build a VarNet model with configurable cascades and sensitivity map U-Net for MRI reconstruction', 'create_normunet': 'create a NormUnet model with normalization applied to input for numerically stable U-Net training', 'run_sensitivity_model': 'run a SensitivityModel to estimate coil sensitivities from multichannel k-space MRI data', 'test_varnetblock': 'test a VarNetBlock that applies soft data consistency with a U-Net regularizer', 'review_normunet_forward': 'review the NormUnet forward pass that normalizes, pads, runs U-Net, then unnormalizes output'}
```

