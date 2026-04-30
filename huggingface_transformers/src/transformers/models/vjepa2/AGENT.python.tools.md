# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vjepa2/convert_vjepa2_classifier_to_hf.py

Prompts

```
['convert a Facebook VJEPA2 video classification checkpoint to HuggingFace transformers format using argparse', 'run verification on a converted VJEPA2 video classification model against a test video', 'split concatenated qkv weights in a model state dict into separate q, k, v tensors', 'rename state dict keys from original Facebook VJEPA2 format to HuggingFace transformers format', 'fetch the id-to-label mapping JSON file for a dataset from huggingface/label-files', "convert a VJEPA2 checkpoint from Facebook's implementation to Hugging Face format", 'test VJEPA2 model conversion by comparing encoder and predictor outputs against original weights', 'upload original VJEPA2 checkpoints to a Hugging Face Hub repository', 'build a VJEPA2Config object for vit_large, vit_huge, vit_giant, or vit_giant_384 model architectures', 'run the VJEPA2 conversion script via argparse with model_name, output path, and push_to_hub flags', 'initialize a VJEPA2Model with VJEPA2Config for video joint embedding and prediction', 'run VJEPA2Model forward pass with pixel_values_videos, context_mask, and target_mask tensors', 'extract vision features from VJEPA2Model encoder outputs without running the predictor', 'configure the VJEPA2Predictor with context and target masks for masked token prediction', 'create a VJEPA2ForVideoClassification model with attentive pooler and classifier head for video classification']
```

Usage

```
{'convert_vjepa2_classifier_to_hf': 'convert a Facebook VJEPA2 video classification checkpoint to HuggingFace transformers format using argparse', 'run_vjepa2_classification_verification': 'run verification on a converted VJEPA2 video classification model against a test video', 'split_qkv_state_dict': 'split concatenated qkv weights in a model state dict into separate q, k, v tensors', 'convert_old_keys_to_new_keys': 'rename state dict keys from original Facebook VJEPA2 format to HuggingFace transformers format', 'get_id2label_mapping': 'fetch the id-to-label mapping JSON file for a dataset from huggingface/label-files'}
```

## File: huggingface_transformers/src/transformers/models/vjepa2/convert_vjepa2_to_hf.py

Prompts

```
['convert a Facebook VJEPA2 video classification checkpoint to HuggingFace transformers format using argparse', 'run verification on a converted VJEPA2 video classification model against a test video', 'split concatenated qkv weights in a model state dict into separate q, k, v tensors', 'rename state dict keys from original Facebook VJEPA2 format to HuggingFace transformers format', 'fetch the id-to-label mapping JSON file for a dataset from huggingface/label-files', "convert a VJEPA2 checkpoint from Facebook's implementation to Hugging Face format", 'test VJEPA2 model conversion by comparing encoder and predictor outputs against original weights', 'upload original VJEPA2 checkpoints to a Hugging Face Hub repository', 'build a VJEPA2Config object for vit_large, vit_huge, vit_giant, or vit_giant_384 model architectures', 'run the VJEPA2 conversion script via argparse with model_name, output path, and push_to_hub flags', 'initialize a VJEPA2Model with VJEPA2Config for video joint embedding and prediction', 'run VJEPA2Model forward pass with pixel_values_videos, context_mask, and target_mask tensors', 'extract vision features from VJEPA2Model encoder outputs without running the predictor', 'configure the VJEPA2Predictor with context and target masks for masked token prediction', 'create a VJEPA2ForVideoClassification model with attentive pooler and classifier head for video classification']
```

Usage

```
{'convert_vjepa2_checkpoint': "convert a VJEPA2 checkpoint from Facebook's implementation to Hugging Face format", 'test_vjepa2_conversion': 'test VJEPA2 model conversion by comparing encoder and predictor outputs against original weights', 'upload_original_checkpoints': 'upload original VJEPA2 checkpoints to a Hugging Face Hub repository', 'build_vjepa2_config': 'build a VJEPA2Config object for vit_large, vit_huge, vit_giant, or vit_giant_384 model architectures', 'run_vjepa2_conversion_cli': 'run the VJEPA2 conversion script via argparse with model_name, output path, and push_to_hub flags'}
```

## File: huggingface_transformers/src/transformers/models/vjepa2/modeling_vjepa2.py

Prompts

```
['convert a Facebook VJEPA2 video classification checkpoint to HuggingFace transformers format using argparse', 'run verification on a converted VJEPA2 video classification model against a test video', 'split concatenated qkv weights in a model state dict into separate q, k, v tensors', 'rename state dict keys from original Facebook VJEPA2 format to HuggingFace transformers format', 'fetch the id-to-label mapping JSON file for a dataset from huggingface/label-files', "convert a VJEPA2 checkpoint from Facebook's implementation to Hugging Face format", 'test VJEPA2 model conversion by comparing encoder and predictor outputs against original weights', 'upload original VJEPA2 checkpoints to a Hugging Face Hub repository', 'build a VJEPA2Config object for vit_large, vit_huge, vit_giant, or vit_giant_384 model architectures', 'run the VJEPA2 conversion script via argparse with model_name, output path, and push_to_hub flags', 'initialize a VJEPA2Model with VJEPA2Config for video joint embedding and prediction', 'run VJEPA2Model forward pass with pixel_values_videos, context_mask, and target_mask tensors', 'extract vision features from VJEPA2Model encoder outputs without running the predictor', 'configure the VJEPA2Predictor with context and target masks for masked token prediction', 'create a VJEPA2ForVideoClassification model with attentive pooler and classifier head for video classification']
```

Usage

```
{'initialize_vjepa2_model': 'initialize a VJEPA2Model with VJEPA2Config for video joint embedding and prediction', 'run_vjepa2_forward': 'run VJEPA2Model forward pass with pixel_values_videos, context_mask, and target_mask tensors', 'get_vision_features': 'extract vision features from VJEPA2Model encoder outputs without running the predictor', 'configure_vjepa2_predictor': 'configure the VJEPA2Predictor with context and target masks for masked token prediction', 'create_vjepa2_video_classifier': 'create a VJEPA2ForVideoClassification model with attentive pooler and classifier head for video classification'}
```

