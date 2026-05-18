# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/tests/models/test_hific_autoencoder.py

Prompts

```
['test the HiFiCAutoencoder forward pass with various latent and hyper feature configurations', 'test the HiFiCAutoencoder compress and decompress methods to verify roundtrip shape preservation', 'test the HiFiCAutoencoder collect_parameters method to verify model and quantile parameter separation', 'test the HiFiCAutoencoder update_tensor_devices method for forward and compress modes', 'test the HiFiCAutoencoder freeze_encoder method to verify encoder parameters are frozen', 'test the HiFiCEncoder forward pass with parametrized latent features 220, 110, and 80', 'create a HiFiCEncoder model with specified in_channels and latent_features parameters', 'run the HiFiCEncoder on a 4D tensor and verify output shape is spatially downsampled by 16x', 'review the test_hific_encoder_forward parametrized test for correctness across multiple latent feature sizes', 'summarize how HiFiCEncoder encodes input images into latent feature representations with 16x spatial reduction', 'test the HiFiCGenerator forward pass with parametrized latent features 220, 110, and 80', 'run pytest on test_hific_generator_forward to verify HiFiCGenerator output shape matches input image shape', 'create a HiFiCGenerator model with specified image channels and latent features for image reconstruction', 'test that HiFiCGenerator produces output with spatial dimensions 16x larger than the latent input', 'review the test_hific_generator_forward parametrized test to understand HiFiCGenerator shape validation', 'test the UnetDiscriminator with various norm types and downsampling factors using pytest', 'test the ConditionalUnetDiscriminator with context tensors and identity normalization using pytest', 'create a UnetDiscriminator model with specified output channels and downsampling factor', 'create a ConditionalUnetDiscriminator model that accepts image and context tensor inputs', 'review the UnetDiscriminator normalization layer types including spectral, instance, and identity']
```

Usage

```
{'test_HiFiCAutoencoder_forward': 'test the HiFiCAutoencoder forward pass with various latent and hyper feature configurations', 'test_HiFiCAutoencoder_compress_decompress': 'test the HiFiCAutoencoder compress and decompress methods to verify roundtrip shape preservation', 'test_HiFiCAutoencoder_collect_parameters': 'test the HiFiCAutoencoder collect_parameters method to verify model and quantile parameter separation', 'test_HiFiCAutoencoder_update_tensor_devices': 'test the HiFiCAutoencoder update_tensor_devices method for forward and compress modes', 'test_HiFiCAutoencoder_freeze_encoder': 'test the HiFiCAutoencoder freeze_encoder method to verify encoder parameters are frozen'}
```

## File: facebookresearch_neuralcompression/tests/models/test_hific_encoder.py

Prompts

```
['test the HiFiCAutoencoder forward pass with various latent and hyper feature configurations', 'test the HiFiCAutoencoder compress and decompress methods to verify roundtrip shape preservation', 'test the HiFiCAutoencoder collect_parameters method to verify model and quantile parameter separation', 'test the HiFiCAutoencoder update_tensor_devices method for forward and compress modes', 'test the HiFiCAutoencoder freeze_encoder method to verify encoder parameters are frozen', 'test the HiFiCEncoder forward pass with parametrized latent features 220, 110, and 80', 'create a HiFiCEncoder model with specified in_channels and latent_features parameters', 'run the HiFiCEncoder on a 4D tensor and verify output shape is spatially downsampled by 16x', 'review the test_hific_encoder_forward parametrized test for correctness across multiple latent feature sizes', 'summarize how HiFiCEncoder encodes input images into latent feature representations with 16x spatial reduction', 'test the HiFiCGenerator forward pass with parametrized latent features 220, 110, and 80', 'run pytest on test_hific_generator_forward to verify HiFiCGenerator output shape matches input image shape', 'create a HiFiCGenerator model with specified image channels and latent features for image reconstruction', 'test that HiFiCGenerator produces output with spatial dimensions 16x larger than the latent input', 'review the test_hific_generator_forward parametrized test to understand HiFiCGenerator shape validation', 'test the UnetDiscriminator with various norm types and downsampling factors using pytest', 'test the ConditionalUnetDiscriminator with context tensors and identity normalization using pytest', 'create a UnetDiscriminator model with specified output channels and downsampling factor', 'create a ConditionalUnetDiscriminator model that accepts image and context tensor inputs', 'review the UnetDiscriminator normalization layer types including spectral, instance, and identity']
```

Usage

```
{'test_hific_encoder_forward': 'test the HiFiCEncoder forward pass with parametrized latent features 220, 110, and 80', 'create_hific_encoder': 'create a HiFiCEncoder model with specified in_channels and latent_features parameters', 'run_hific_encoder_inference': 'run the HiFiCEncoder on a 4D tensor and verify output shape is spatially downsampled by 16x', 'review_hific_encoder_test': 'review the test_hific_encoder_forward parametrized test for correctness across multiple latent feature sizes', 'summarize_hific_encoder_usage': 'summarize how HiFiCEncoder encodes input images into latent feature representations with 16x spatial reduction'}
```

## File: facebookresearch_neuralcompression/tests/models/test_hific_generator.py

Prompts

```
['test the HiFiCAutoencoder forward pass with various latent and hyper feature configurations', 'test the HiFiCAutoencoder compress and decompress methods to verify roundtrip shape preservation', 'test the HiFiCAutoencoder collect_parameters method to verify model and quantile parameter separation', 'test the HiFiCAutoencoder update_tensor_devices method for forward and compress modes', 'test the HiFiCAutoencoder freeze_encoder method to verify encoder parameters are frozen', 'test the HiFiCEncoder forward pass with parametrized latent features 220, 110, and 80', 'create a HiFiCEncoder model with specified in_channels and latent_features parameters', 'run the HiFiCEncoder on a 4D tensor and verify output shape is spatially downsampled by 16x', 'review the test_hific_encoder_forward parametrized test for correctness across multiple latent feature sizes', 'summarize how HiFiCEncoder encodes input images into latent feature representations with 16x spatial reduction', 'test the HiFiCGenerator forward pass with parametrized latent features 220, 110, and 80', 'run pytest on test_hific_generator_forward to verify HiFiCGenerator output shape matches input image shape', 'create a HiFiCGenerator model with specified image channels and latent features for image reconstruction', 'test that HiFiCGenerator produces output with spatial dimensions 16x larger than the latent input', 'review the test_hific_generator_forward parametrized test to understand HiFiCGenerator shape validation', 'test the UnetDiscriminator with various norm types and downsampling factors using pytest', 'test the ConditionalUnetDiscriminator with context tensors and identity normalization using pytest', 'create a UnetDiscriminator model with specified output channels and downsampling factor', 'create a ConditionalUnetDiscriminator model that accepts image and context tensor inputs', 'review the UnetDiscriminator normalization layer types including spectral, instance, and identity']
```

Usage

```
{'test_hific_generator_forward': 'test the HiFiCGenerator forward pass with parametrized latent features 220, 110, and 80', 'run_hific_generator_test': 'run pytest on test_hific_generator_forward to verify HiFiCGenerator output shape matches input image shape', 'create_hific_generator_model': 'create a HiFiCGenerator model with specified image channels and latent features for image reconstruction', 'test_hific_generator_latent_shape': 'test that HiFiCGenerator produces output with spatial dimensions 16x larger than the latent input', 'review_hific_generator_test': 'review the test_hific_generator_forward parametrized test to understand HiFiCGenerator shape validation'}
```

## File: facebookresearch_neuralcompression/tests/models/test_unet_discriminator.py

Prompts

```
['test the HiFiCAutoencoder forward pass with various latent and hyper feature configurations', 'test the HiFiCAutoencoder compress and decompress methods to verify roundtrip shape preservation', 'test the HiFiCAutoencoder collect_parameters method to verify model and quantile parameter separation', 'test the HiFiCAutoencoder update_tensor_devices method for forward and compress modes', 'test the HiFiCAutoencoder freeze_encoder method to verify encoder parameters are frozen', 'test the HiFiCEncoder forward pass with parametrized latent features 220, 110, and 80', 'create a HiFiCEncoder model with specified in_channels and latent_features parameters', 'run the HiFiCEncoder on a 4D tensor and verify output shape is spatially downsampled by 16x', 'review the test_hific_encoder_forward parametrized test for correctness across multiple latent feature sizes', 'summarize how HiFiCEncoder encodes input images into latent feature representations with 16x spatial reduction', 'test the HiFiCGenerator forward pass with parametrized latent features 220, 110, and 80', 'run pytest on test_hific_generator_forward to verify HiFiCGenerator output shape matches input image shape', 'create a HiFiCGenerator model with specified image channels and latent features for image reconstruction', 'test that HiFiCGenerator produces output with spatial dimensions 16x larger than the latent input', 'review the test_hific_generator_forward parametrized test to understand HiFiCGenerator shape validation', 'test the UnetDiscriminator with various norm types and downsampling factors using pytest', 'test the ConditionalUnetDiscriminator with context tensors and identity normalization using pytest', 'create a UnetDiscriminator model with specified output channels and downsampling factor', 'create a ConditionalUnetDiscriminator model that accepts image and context tensor inputs', 'review the UnetDiscriminator normalization layer types including spectral, instance, and identity']
```

Usage

```
{'test_unet_discriminator': 'test the UnetDiscriminator with various norm types and downsampling factors using pytest', 'test_conditional_unet_discriminator': 'test the ConditionalUnetDiscriminator with context tensors and identity normalization using pytest', 'create_unet_discriminator': 'create a UnetDiscriminator model with specified output channels and downsampling factor', 'create_conditional_unet_discriminator': 'create a ConditionalUnetDiscriminator model that accepts image and context tensor inputs', 'review_unet_discriminator_norm_layers': 'review the UnetDiscriminator normalization layer types including spectral, instance, and identity'}
```

