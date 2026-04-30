# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/eomt_dinov3/convert_eomt_dinov3_to_hf.py

Prompts

```
['run the conversion script to convert an EoMT-DINOv3 checkpoint from the official repo to Hugging Face Transformers format', 'list all supported EoMT-DINOv3 checkpoint model IDs and their backbone configurations', 'verify the converted Hugging Face model matches the original EoMT-DINOv3 model outputs within tolerance', 'push the converted EoMT-DINOv3 model and processor to the Hugging Face Hub', 'resolve an EoMT-DINOv3 checkpoint spec by model ID to get backbone repo and image size', 'run EomtDinov3ForUniversalSegmentation to perform instance, semantic, or panoptic image segmentation', 'create an EomtDinov3HungarianMatcher to compute bipartite matching between predicted and ground-truth masks', 'build an EomtDinov3ForUniversalSegmentation model with query-based mask and class prediction heads', 'test EomtDinov3Loss to compute cross-entropy, mask, and dice losses for segmentation training', 'review EomtDinov3RotaryEmbedding to apply rotary position embeddings to patch tokens with augmentation', 'create an EomtDinov3Config with custom segmentation head parameters like num_queries and num_blocks', 'build an EomtDinov3ForUniversalSegmentation model from a config for instance and panoptic segmentation', 'run the EomtDinov3ForUniversalSegmentation forward pass with pixel values and optional mask and class labels', 'configure EomtDinov3RotaryEmbedding with default RoPE inverse frequencies for transformer position encoding', 'compute EomtDinov3Loss using mask predictions, class predictions, and ground truth mask and class labels']
```

Usage

```
{'run_convert_checkpoint': 'run the conversion script to convert an EoMT-DINOv3 checkpoint from the official repo to Hugging Face Transformers format', 'list_supported_models': 'list all supported EoMT-DINOv3 checkpoint model IDs and their backbone configurations', 'verify_conversion': 'verify the converted Hugging Face model matches the original EoMT-DINOv3 model outputs within tolerance', 'push_converted_model': 'push the converted EoMT-DINOv3 model and processor to the Hugging Face Hub', 'resolve_checkpoint_spec': 'resolve an EoMT-DINOv3 checkpoint spec by model ID to get backbone repo and image size'}
```

## File: huggingface_transformers/src/transformers/models/eomt_dinov3/modeling_eomt_dinov3.py

Prompts

```
['run the conversion script to convert an EoMT-DINOv3 checkpoint from the official repo to Hugging Face Transformers format', 'list all supported EoMT-DINOv3 checkpoint model IDs and their backbone configurations', 'verify the converted Hugging Face model matches the original EoMT-DINOv3 model outputs within tolerance', 'push the converted EoMT-DINOv3 model and processor to the Hugging Face Hub', 'resolve an EoMT-DINOv3 checkpoint spec by model ID to get backbone repo and image size', 'run EomtDinov3ForUniversalSegmentation to perform instance, semantic, or panoptic image segmentation', 'create an EomtDinov3HungarianMatcher to compute bipartite matching between predicted and ground-truth masks', 'build an EomtDinov3ForUniversalSegmentation model with query-based mask and class prediction heads', 'test EomtDinov3Loss to compute cross-entropy, mask, and dice losses for segmentation training', 'review EomtDinov3RotaryEmbedding to apply rotary position embeddings to patch tokens with augmentation', 'create an EomtDinov3Config with custom segmentation head parameters like num_queries and num_blocks', 'build an EomtDinov3ForUniversalSegmentation model from a config for instance and panoptic segmentation', 'run the EomtDinov3ForUniversalSegmentation forward pass with pixel values and optional mask and class labels', 'configure EomtDinov3RotaryEmbedding with default RoPE inverse frequencies for transformer position encoding', 'compute EomtDinov3Loss using mask predictions, class predictions, and ground truth mask and class labels']
```

Usage

```
{'run_eomt_dinov3_segmentation': 'run EomtDinov3ForUniversalSegmentation to perform instance, semantic, or panoptic image segmentation', 'create_hungarian_matcher': 'create an EomtDinov3HungarianMatcher to compute bipartite matching between predicted and ground-truth masks', 'build_universal_segmentation_model': 'build an EomtDinov3ForUniversalSegmentation model with query-based mask and class prediction heads', 'test_loss_computation': 'test EomtDinov3Loss to compute cross-entropy, mask, and dice losses for segmentation training', 'review_rotary_embedding': 'review EomtDinov3RotaryEmbedding to apply rotary position embeddings to patch tokens with augmentation'}
```

## File: huggingface_transformers/src/transformers/models/eomt_dinov3/modular_eomt_dinov3.py

Prompts

```
['run the conversion script to convert an EoMT-DINOv3 checkpoint from the official repo to Hugging Face Transformers format', 'list all supported EoMT-DINOv3 checkpoint model IDs and their backbone configurations', 'verify the converted Hugging Face model matches the original EoMT-DINOv3 model outputs within tolerance', 'push the converted EoMT-DINOv3 model and processor to the Hugging Face Hub', 'resolve an EoMT-DINOv3 checkpoint spec by model ID to get backbone repo and image size', 'run EomtDinov3ForUniversalSegmentation to perform instance, semantic, or panoptic image segmentation', 'create an EomtDinov3HungarianMatcher to compute bipartite matching between predicted and ground-truth masks', 'build an EomtDinov3ForUniversalSegmentation model with query-based mask and class prediction heads', 'test EomtDinov3Loss to compute cross-entropy, mask, and dice losses for segmentation training', 'review EomtDinov3RotaryEmbedding to apply rotary position embeddings to patch tokens with augmentation', 'create an EomtDinov3Config with custom segmentation head parameters like num_queries and num_blocks', 'build an EomtDinov3ForUniversalSegmentation model from a config for instance and panoptic segmentation', 'run the EomtDinov3ForUniversalSegmentation forward pass with pixel values and optional mask and class labels', 'configure EomtDinov3RotaryEmbedding with default RoPE inverse frequencies for transformer position encoding', 'compute EomtDinov3Loss using mask predictions, class predictions, and ground truth mask and class labels']
```

Usage

```
{'create_eomt_dinov3_config': 'create an EomtDinov3Config with custom segmentation head parameters like num_queries and num_blocks', 'build_eomt_dinov3_model': 'build an EomtDinov3ForUniversalSegmentation model from a config for instance and panoptic segmentation', 'run_eomt_dinov3_forward': 'run the EomtDinov3ForUniversalSegmentation forward pass with pixel values and optional mask and class labels', 'configure_eomt_dinov3_rope': 'configure EomtDinov3RotaryEmbedding with default RoPE inverse frequencies for transformer position encoding', 'compute_eomt_dinov3_loss': 'compute EomtDinov3Loss using mask predictions, class predictions, and ground truth mask and class labels'}
```

