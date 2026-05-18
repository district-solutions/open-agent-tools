# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/neuralcompression/zoo/_msillm.py

Prompts

```
['build a HiFiCAutoencoder model with optional pretrained MS-ILLM weights from a target bpp checkpoint', 'create a pretrained MS-ILLM quality level 1 autoencoder model targeting 0.035 bits per pixel', 'create a pretrained MS-ILLM quality level 6 autoencoder model targeting 0.9 bits per pixel', 'create a pretrained MS-ILLM very low quality level 1 autoencoder model targeting 0.00218 bits per pixel', 'review the list of valid MS-ILLM weight checkpoint names from target 0.00218bpp to target 0.9bpp', 'build a VQ-VAE XCiT autoencoder model with 1024 codebook size and 8-dim latent vectors', 'build a pretrained VQ-VAE XCiT autoencoder by passing pretrained=True to load MS-ILLM weights', 'build an MS-ILLM VQ-VAE model by calling _build_msillm_vqvae with a model and valid weights string', 'review the VQ-VAE XCiT autoencoder architecture with channel mult [1,2,2,4] and 256 embed dimension', 'summarize the VALID_WEIGHTS list containing available pretrained weight identifiers for MS-ILLM VQ-VAE models', 'build a NoGAN-MS HiFiCAutoencoder model with optional pretrained weights from a target bpp checkpoint', 'run the noganms_quality_1 function to create a model targeting 0.035 bits per pixel', 'run the noganms_quality_6 function to create a model targeting 0.9 bits per pixel', 'test the _build_noganms function by passing an invalid weights string and verifying it raises ValueError', 'summarize the NoGAN-MS model zoo functions that provide 6 quality tiers from 0.035 to 0.9 bpp']
```

Usage

```
{'build_msillm_model': 'build a HiFiCAutoencoder model with optional pretrained MS-ILLM weights from a target bpp checkpoint', 'create_msillm_quality_1': 'create a pretrained MS-ILLM quality level 1 autoencoder model targeting 0.035 bits per pixel', 'create_msillm_quality_6': 'create a pretrained MS-ILLM quality level 6 autoencoder model targeting 0.9 bits per pixel', 'create_msillm_quality_vlo1': 'create a pretrained MS-ILLM very low quality level 1 autoencoder model targeting 0.00218 bits per pixel', 'review_VALID_WEIGHTS': 'review the list of valid MS-ILLM weight checkpoint names from target 0.00218bpp to target 0.9bpp'}
```

## File: facebookresearch_neuralcompression/neuralcompression/zoo/_msillm_vqvae.py

Prompts

```
['build a HiFiCAutoencoder model with optional pretrained MS-ILLM weights from a target bpp checkpoint', 'create a pretrained MS-ILLM quality level 1 autoencoder model targeting 0.035 bits per pixel', 'create a pretrained MS-ILLM quality level 6 autoencoder model targeting 0.9 bits per pixel', 'create a pretrained MS-ILLM very low quality level 1 autoencoder model targeting 0.00218 bits per pixel', 'review the list of valid MS-ILLM weight checkpoint names from target 0.00218bpp to target 0.9bpp', 'build a VQ-VAE XCiT autoencoder model with 1024 codebook size and 8-dim latent vectors', 'build a pretrained VQ-VAE XCiT autoencoder by passing pretrained=True to load MS-ILLM weights', 'build an MS-ILLM VQ-VAE model by calling _build_msillm_vqvae with a model and valid weights string', 'review the VQ-VAE XCiT autoencoder architecture with channel mult [1,2,2,4] and 256 embed dimension', 'summarize the VALID_WEIGHTS list containing available pretrained weight identifiers for MS-ILLM VQ-VAE models', 'build a NoGAN-MS HiFiCAutoencoder model with optional pretrained weights from a target bpp checkpoint', 'run the noganms_quality_1 function to create a model targeting 0.035 bits per pixel', 'run the noganms_quality_6 function to create a model targeting 0.9 bits per pixel', 'test the _build_noganms function by passing an invalid weights string and verifying it raises ValueError', 'summarize the NoGAN-MS model zoo functions that provide 6 quality tiers from 0.035 to 0.9 bpp']
```

Usage

```
{'build_vqvae_xcit_autoencoder': 'build a VQ-VAE XCiT autoencoder model with 1024 codebook size and 8-dim latent vectors', 'build_pretrained_vqvae_xcit': 'build a pretrained VQ-VAE XCiT autoencoder by passing pretrained=True to load MS-ILLM weights', 'build_msillm_vqvae_with_custom_weights': 'build an MS-ILLM VQ-VAE model by calling _build_msillm_vqvae with a model and valid weights string', 'review_vqvae_xcit_architecture': 'review the VQ-VAE XCiT autoencoder architecture with channel mult [1,2,2,4] and 256 embed dimension', 'summarize_valid_weights': 'summarize the VALID_WEIGHTS list containing available pretrained weight identifiers for MS-ILLM VQ-VAE models'}
```

## File: facebookresearch_neuralcompression/neuralcompression/zoo/_noganms.py

Prompts

```
['build a HiFiCAutoencoder model with optional pretrained MS-ILLM weights from a target bpp checkpoint', 'create a pretrained MS-ILLM quality level 1 autoencoder model targeting 0.035 bits per pixel', 'create a pretrained MS-ILLM quality level 6 autoencoder model targeting 0.9 bits per pixel', 'create a pretrained MS-ILLM very low quality level 1 autoencoder model targeting 0.00218 bits per pixel', 'review the list of valid MS-ILLM weight checkpoint names from target 0.00218bpp to target 0.9bpp', 'build a VQ-VAE XCiT autoencoder model with 1024 codebook size and 8-dim latent vectors', 'build a pretrained VQ-VAE XCiT autoencoder by passing pretrained=True to load MS-ILLM weights', 'build an MS-ILLM VQ-VAE model by calling _build_msillm_vqvae with a model and valid weights string', 'review the VQ-VAE XCiT autoencoder architecture with channel mult [1,2,2,4] and 256 embed dimension', 'summarize the VALID_WEIGHTS list containing available pretrained weight identifiers for MS-ILLM VQ-VAE models', 'build a NoGAN-MS HiFiCAutoencoder model with optional pretrained weights from a target bpp checkpoint', 'run the noganms_quality_1 function to create a model targeting 0.035 bits per pixel', 'run the noganms_quality_6 function to create a model targeting 0.9 bits per pixel', 'test the _build_noganms function by passing an invalid weights string and verifying it raises ValueError', 'summarize the NoGAN-MS model zoo functions that provide 6 quality tiers from 0.035 to 0.9 bpp']
```

Usage

```
{'build_noganms_model': 'build a NoGAN-MS HiFiCAutoencoder model with optional pretrained weights from a target bpp checkpoint', 'run_noganms_quality_1': 'run the noganms_quality_1 function to create a model targeting 0.035 bits per pixel', 'run_noganms_quality_6': 'run the noganms_quality_6 function to create a model targeting 0.9 bits per pixel', 'test_build_noganms_invalid_weights': 'test the _build_noganms function by passing an invalid weights string and verifying it raises ValueError', 'summarize_noganms_zoo': 'summarize the NoGAN-MS model zoo functions that provide 6 quality tiers from 0.035 to 0.9 bpp'}
```

