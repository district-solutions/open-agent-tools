# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/vc_models/src/vc_models/models/vit/model_utils.py

Prompts

```
['load a pretrained EAI-VC model by name using hydra and omegaconf configuration', 'download a model checkpoint file from the EAI-VC base URL if it does not exist locally', 'download a file from a URL to a destination path with a progress bar hook', 'report download progress to stdout with a text progress bar showing percentage and file size', 'review the VC1_BASE_NAME and VC1_LARGE_NAME constants and the EAI-VC base download URL', 'build a VisionTransformer small model with patch size 16 and 384 embedding dimensions', 'build a VisionTransformer base model with patch size 16 and 768 embedding dimensions', 'build a VisionTransformer large model with patch size 16 and 1024 embedding dimensions', 'load a MAE encoder checkpoint into a VisionTransformer model with positional embedding resizing', 'load a contrastive learning checkpoint into a VisionTransformer model filtering base_encoder keys']
```

Usage

```
{'load_model_vc1': 'load a pretrained EAI-VC model by name using hydra and omegaconf configuration', 'download_model_if_needed': 'download a model checkpoint file from the EAI-VC base URL if it does not exist locally', 'download_url_with_progress': 'download a file from a URL to a destination path with a progress bar hook', 'report_download_progress': 'report download progress to stdout with a text progress bar showing percentage and file size', 'review_model_constants': 'review the VC1_BASE_NAME and VC1_LARGE_NAME constants and the EAI-VC base download URL'}
```

## File: facebookresearch_eai-vc/vc_models/src/vc_models/models/vit/vit.py

Prompts

```
['load a pretrained EAI-VC model by name using hydra and omegaconf configuration', 'download a model checkpoint file from the EAI-VC base URL if it does not exist locally', 'download a file from a URL to a destination path with a progress bar hook', 'report download progress to stdout with a text progress bar showing percentage and file size', 'review the VC1_BASE_NAME and VC1_LARGE_NAME constants and the EAI-VC base download URL', 'build a VisionTransformer small model with patch size 16 and 384 embedding dimensions', 'build a VisionTransformer base model with patch size 16 and 768 embedding dimensions', 'build a VisionTransformer large model with patch size 16 and 1024 embedding dimensions', 'load a MAE encoder checkpoint into a VisionTransformer model with positional embedding resizing', 'load a contrastive learning checkpoint into a VisionTransformer model filtering base_encoder keys']
```

Usage

```
{'build_vit_small': 'build a VisionTransformer small model with patch size 16 and 384 embedding dimensions', 'build_vit_base': 'build a VisionTransformer base model with patch size 16 and 768 embedding dimensions', 'build_vit_large': 'build a VisionTransformer large model with patch size 16 and 1024 embedding dimensions', 'load_mae_encoder': 'load a MAE encoder checkpoint into a VisionTransformer model with positional embedding resizing', 'load_contrastive_vit': 'load a contrastive learning checkpoint into a VisionTransformer model filtering base_encoder keys'}
```

