# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vit_mae/convert_vit_mae_to_pytorch.py

Prompts

```
["convert a ViT MAE checkpoint from Facebook's repository to a HuggingFace PyTorch model", 'rename state dict keys from Facebook MAE naming to HuggingFace ViT MAE naming convention', 'convert a state dict from the original MAE checkpoint format to HuggingFace transformers format', 'run the CLI script to convert a ViT MAE checkpoint from a URL to a local PyTorch model directory', 'test the checkpoint conversion by verifying logits match expected values within tolerance', 'create a ViTMAEForPreTraining model for self-supervised image reconstruction pre-training', 'build a ViTMAEModel encoder that extracts hidden states from masked image patches', 'run masked autoencoder forward pass to reconstruct pixel values from masked patches', 'test per-sample random masking of image patches using argsort noise shuffling', 'summarize how ViTMAEDecoder restores masked tokens and predicts pixel reconstruction logits']
```

Usage

```
{'convert_vit_mae_checkpoint': "convert a ViT MAE checkpoint from Facebook's repository to a HuggingFace PyTorch model", 'rename_key': 'rename state dict keys from Facebook MAE naming to HuggingFace ViT MAE naming convention', 'convert_state_dict': 'convert a state dict from the original MAE checkpoint format to HuggingFace transformers format', 'run_convert_cli': 'run the CLI script to convert a ViT MAE checkpoint from a URL to a local PyTorch model directory', 'test_conversion_accuracy': 'test the checkpoint conversion by verifying logits match expected values within tolerance'}
```

## File: huggingface_transformers/src/transformers/models/vit_mae/modeling_vit_mae.py

Prompts

```
["convert a ViT MAE checkpoint from Facebook's repository to a HuggingFace PyTorch model", 'rename state dict keys from Facebook MAE naming to HuggingFace ViT MAE naming convention', 'convert a state dict from the original MAE checkpoint format to HuggingFace transformers format', 'run the CLI script to convert a ViT MAE checkpoint from a URL to a local PyTorch model directory', 'test the checkpoint conversion by verifying logits match expected values within tolerance', 'create a ViTMAEForPreTraining model for self-supervised image reconstruction pre-training', 'build a ViTMAEModel encoder that extracts hidden states from masked image patches', 'run masked autoencoder forward pass to reconstruct pixel values from masked patches', 'test per-sample random masking of image patches using argsort noise shuffling', 'summarize how ViTMAEDecoder restores masked tokens and predicts pixel reconstruction logits']
```

Usage

```
{'create_vitmae_pretraining_model': 'create a ViTMAEForPreTraining model for self-supervised image reconstruction pre-training', 'build_vitmae_encoder': 'build a ViTMAEModel encoder that extracts hidden states from masked image patches', 'run_masked_image_reconstruction': 'run masked autoencoder forward pass to reconstruct pixel values from masked patches', 'test_random_patch_masking': 'test per-sample random masking of image patches using argsort noise shuffling', 'summarize_decoder_reconstruction': 'summarize how ViTMAEDecoder restores masked tokens and predicts pixel reconstruction logits'}
```

