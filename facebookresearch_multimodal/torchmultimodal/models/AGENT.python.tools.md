# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/models/late_fusion.py

Prompts

```
['build a LateFusion multimodal model with separate encoders, a fusion module, and a head module', 'create a forward pass through LateFusion by passing a dictionary of modality tensors', 'test the LateFusion constructor by initializing it with encoders, fusion_module, and head_module', 'review the LateFusion forward method to understand how it encodes, fuses, and predicts from modalities', 'refactor the LateFusion encoders ModuleDict to add or remove modality-specific encoders', 'build an Omnivore model with a Swin-T encoder and multimodal classification heads', 'build an Omnivore model with a Swin-S encoder and multimodal classification heads', 'build an Omnivore model with a Swin-B encoder and multimodal classification heads', 'run a forward pass through the Omnivore model with a 5D tensor and input type', 'create a PatchEmbedOmnivore module that embeds RGB and depth channels separately then adds them', 'build a TwoTower model with two LateFusion towers and a tower fusion module', 'create a TwoTower model using shared towers with a channel name mapping dict', 'run the TwoTower forward pass with a channel to input tensor dictionary', 'review the TwoTower _get_tower_input method that maps channel names for shared towers', 'summarize the TwoTowerOutput NamedTuple containing the output tensor and tower embeddings dict', 'build a VQVAE model with a custom encoder, decoder, and codebook for vector quantization', 'encode input tensor data into discrete token ids using the VQVAE encode method', 'decode token ids back into reconstructed data using the VQVAE decode method', 'run a forward pass through the VQVAE model to get decoded output and codebook loss', 'lookup quantized embeddings from the codebook given token indices using the VQVAE lookup method']
```

Usage

```
{'build_late_fusion_model': 'build a LateFusion multimodal model with separate encoders, a fusion module, and a head module', 'create_late_fusion_forward': 'create a forward pass through LateFusion by passing a dictionary of modality tensors', 'test_LateFusion_init': 'test the LateFusion constructor by initializing it with encoders, fusion_module, and head_module', 'review_LateFusion_forward': 'review the LateFusion forward method to understand how it encodes, fuses, and predicts from modalities', 'refactor_LateFusion_encoders': 'refactor the LateFusion encoders ModuleDict to add or remove modality-specific encoders'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/omnivore.py

Prompts

```
['build a LateFusion multimodal model with separate encoders, a fusion module, and a head module', 'create a forward pass through LateFusion by passing a dictionary of modality tensors', 'test the LateFusion constructor by initializing it with encoders, fusion_module, and head_module', 'review the LateFusion forward method to understand how it encodes, fuses, and predicts from modalities', 'refactor the LateFusion encoders ModuleDict to add or remove modality-specific encoders', 'build an Omnivore model with a Swin-T encoder and multimodal classification heads', 'build an Omnivore model with a Swin-S encoder and multimodal classification heads', 'build an Omnivore model with a Swin-B encoder and multimodal classification heads', 'run a forward pass through the Omnivore model with a 5D tensor and input type', 'create a PatchEmbedOmnivore module that embeds RGB and depth channels separately then adds them', 'build a TwoTower model with two LateFusion towers and a tower fusion module', 'create a TwoTower model using shared towers with a channel name mapping dict', 'run the TwoTower forward pass with a channel to input tensor dictionary', 'review the TwoTower _get_tower_input method that maps channel names for shared towers', 'summarize the TwoTowerOutput NamedTuple containing the output tensor and tower embeddings dict', 'build a VQVAE model with a custom encoder, decoder, and codebook for vector quantization', 'encode input tensor data into discrete token ids using the VQVAE encode method', 'decode token ids back into reconstructed data using the VQVAE decode method', 'run a forward pass through the VQVAE model to get decoded output and codebook loss', 'lookup quantized embeddings from the codebook given token indices using the VQVAE lookup method']
```

Usage

```
{'build_omnivore_swin_t': 'build an Omnivore model with a Swin-T encoder and multimodal classification heads', 'build_omnivore_swin_s': 'build an Omnivore model with a Swin-S encoder and multimodal classification heads', 'build_omnivore_swin_b': 'build an Omnivore model with a Swin-B encoder and multimodal classification heads', 'run_Omnivore_forward': 'run a forward pass through the Omnivore model with a 5D tensor and input type', 'create_PatchEmbedOmnivore': 'create a PatchEmbedOmnivore module that embeds RGB and depth channels separately then adds them'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/two_tower.py

Prompts

```
['build a LateFusion multimodal model with separate encoders, a fusion module, and a head module', 'create a forward pass through LateFusion by passing a dictionary of modality tensors', 'test the LateFusion constructor by initializing it with encoders, fusion_module, and head_module', 'review the LateFusion forward method to understand how it encodes, fuses, and predicts from modalities', 'refactor the LateFusion encoders ModuleDict to add or remove modality-specific encoders', 'build an Omnivore model with a Swin-T encoder and multimodal classification heads', 'build an Omnivore model with a Swin-S encoder and multimodal classification heads', 'build an Omnivore model with a Swin-B encoder and multimodal classification heads', 'run a forward pass through the Omnivore model with a 5D tensor and input type', 'create a PatchEmbedOmnivore module that embeds RGB and depth channels separately then adds them', 'build a TwoTower model with two LateFusion towers and a tower fusion module', 'create a TwoTower model using shared towers with a channel name mapping dict', 'run the TwoTower forward pass with a channel to input tensor dictionary', 'review the TwoTower _get_tower_input method that maps channel names for shared towers', 'summarize the TwoTowerOutput NamedTuple containing the output tensor and tower embeddings dict', 'build a VQVAE model with a custom encoder, decoder, and codebook for vector quantization', 'encode input tensor data into discrete token ids using the VQVAE encode method', 'decode token ids back into reconstructed data using the VQVAE decode method', 'run a forward pass through the VQVAE model to get decoded output and codebook loss', 'lookup quantized embeddings from the codebook given token indices using the VQVAE lookup method']
```

Usage

```
{'build_two_tower_model': 'build a TwoTower model with two LateFusion towers and a tower fusion module', 'create_two_tower_with_shared_towers': 'create a TwoTower model using shared towers with a channel name mapping dict', 'run_two_tower_forward': 'run the TwoTower forward pass with a channel to input tensor dictionary', 'review_two_tower_get_tower_input': 'review the TwoTower _get_tower_input method that maps channel names for shared towers', 'summarize_two_tower_output': 'summarize the TwoTowerOutput NamedTuple containing the output tensor and tower embeddings dict'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/vqvae.py

Prompts

```
['build a LateFusion multimodal model with separate encoders, a fusion module, and a head module', 'create a forward pass through LateFusion by passing a dictionary of modality tensors', 'test the LateFusion constructor by initializing it with encoders, fusion_module, and head_module', 'review the LateFusion forward method to understand how it encodes, fuses, and predicts from modalities', 'refactor the LateFusion encoders ModuleDict to add or remove modality-specific encoders', 'build an Omnivore model with a Swin-T encoder and multimodal classification heads', 'build an Omnivore model with a Swin-S encoder and multimodal classification heads', 'build an Omnivore model with a Swin-B encoder and multimodal classification heads', 'run a forward pass through the Omnivore model with a 5D tensor and input type', 'create a PatchEmbedOmnivore module that embeds RGB and depth channels separately then adds them', 'build a TwoTower model with two LateFusion towers and a tower fusion module', 'create a TwoTower model using shared towers with a channel name mapping dict', 'run the TwoTower forward pass with a channel to input tensor dictionary', 'review the TwoTower _get_tower_input method that maps channel names for shared towers', 'summarize the TwoTowerOutput NamedTuple containing the output tensor and tower embeddings dict', 'build a VQVAE model with a custom encoder, decoder, and codebook for vector quantization', 'encode input tensor data into discrete token ids using the VQVAE encode method', 'decode token ids back into reconstructed data using the VQVAE decode method', 'run a forward pass through the VQVAE model to get decoded output and codebook loss', 'lookup quantized embeddings from the codebook given token indices using the VQVAE lookup method']
```

Usage

```
{'build_vqvae_model': 'build a VQVAE model with a custom encoder, decoder, and codebook for vector quantization', 'encode_data_to_tokens': 'encode input tensor data into discrete token ids using the VQVAE encode method', 'decode_tokens_to_data': 'decode token ids back into reconstructed data using the VQVAE decode method', 'run_vqvae_forward_pass': 'run a forward pass through the VQVAE model to get decoded output and codebook loss', 'lookup_codebook_embeddings': 'lookup quantized embeddings from the codebook given token indices using the VQVAE lookup method'}
```

