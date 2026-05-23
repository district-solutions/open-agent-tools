# Agent Python Tools

- repo: facebookresearch/fashionplus
- repo_uri: https://github.com/facebookresearch/fashionplus

## File: facebookresearch_fashionplus/separate_vae/models/pix2pixhd_networks.py

Prompts

```
['build an E_Resnet encoder and D_NLayers decoder pair with define_ED for image generation', 'build multiple paired encoder-decoder networks with define_paired_EDs for multi-domain image translation', 'build multiple encoders sharing a single decoder with define_Es_shareD for multi-encoder image synthesis', 'build separate and together encoders with a shared decoder using define_separate_Es_and_D', 'build a GlobalGenerator U-Net model with ResnetBlock for image-to-image translation tasks', 'create a VAE model instance with separate clothing encoders and a shared decoder using create_model', 'encode an input label map into concatenated latent codes for each clothing category at inference time', 'forward a one-hot encoded label map through separate clothing encoders and compute MSE and KL losses', 'generate a decoded image from a randomly sampled or pre-encoded latent code z using the decoder', 'load a pretrained network state dict from a checkpoint file with fallback for mismatched layers']
```

Usage

```
{'build_encoder_decoder': 'build an E_Resnet encoder and D_NLayers decoder pair with define_ED for image generation', 'build_paired_encoders_decoders': 'build multiple paired encoder-decoder networks with define_paired_EDs for multi-domain image translation', 'build_shared_decoder': 'build multiple encoders sharing a single decoder with define_Es_shareD for multi-encoder image synthesis', 'build_separate_encoders_decoder': 'build separate and together encoders with a shared decoder using define_separate_Es_and_D', 'build_global_generator': 'build a GlobalGenerator U-Net model with ResnetBlock for image-to-image translation tasks'}
```

## File: facebookresearch_fashionplus/separate_vae/models/separate_clothing_encoder_models.py

Prompts

```
['build an E_Resnet encoder and D_NLayers decoder pair with define_ED for image generation', 'build multiple paired encoder-decoder networks with define_paired_EDs for multi-domain image translation', 'build multiple encoders sharing a single decoder with define_Es_shareD for multi-encoder image synthesis', 'build separate and together encoders with a shared decoder using define_separate_Es_and_D', 'build a GlobalGenerator U-Net model with ResnetBlock for image-to-image translation tasks', 'create a VAE model instance with separate clothing encoders and a shared decoder using create_model', 'encode an input label map into concatenated latent codes for each clothing category at inference time', 'forward a one-hot encoded label map through separate clothing encoders and compute MSE and KL losses', 'generate a decoded image from a randomly sampled or pre-encoded latent code z using the decoder', 'load a pretrained network state dict from a checkpoint file with fallback for mismatched layers']
```

Usage

```
{'create_VAE_MODEL': 'create a VAE model instance with separate clothing encoders and a shared decoder using create_model', 'encode_features_VAE_MODEL': 'encode an input label map into concatenated latent codes for each clothing category at inference time', 'forward_VAE_MODEL': 'forward a one-hot encoded label map through separate clothing encoders and compute MSE and KL losses', 'generate_from_random_VAE_MODEL': 'generate a decoded image from a randomly sampled or pre-encoded latent code z using the decoder', 'load_network_VAE_MODEL': 'load a pretrained network state dict from a checkpoint file with fallback for mismatched layers'}
```

