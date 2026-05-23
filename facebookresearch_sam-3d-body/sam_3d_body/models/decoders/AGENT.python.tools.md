# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/models/decoders/keypoint_prompt_sampler.py

Prompts

```
['build a KeypointSamplerV1 instance from a DictConfig with prompt keypoints and keybody index lists', 'sample prompt keypoints from ground truth and predicted 2D keypoints using KeypointSamplerV1', 'get the worst keypoint index from a distance tensor filtered by a keypoint list', 'get a random valid keypoint index from candidates with positive distances in a keypoint list', 'compute pairwise squared distances between two tensors with optional masking for ignored elements', 'build a PromptEncoder module to encode keypoints and mask prompts for SAM body segmentation', 'create a PositionEmbeddingRandom module to generate sinusoidal positional encodings for normalized coordinates', 'test the _embed_keypoints method to embed normalized point prompts with joint labels', 'review the PromptEncoder forward method that returns sparse and dense embeddings from keypoints', 'refactor the mask_downscaling conv layers to support custom mask embedding types v1 or v2', 'build a PromptableDecoder with specified dims, depth, and num_heads for cross-attention transformer decoding', 'run a forward pass through PromptableDecoder with token and image embeddings to get pose output', 'freeze all PromptableDecoder parameters by setting frozen flag to prevent gradient updates', 'review the forward method to enable intermediate pose predictions across decoder layers', 'test PromptableDecoder forward pass with hand embeddings concatenated to image context features']
```

Usage

```
{'build_keypoint_sampler': 'build a KeypointSamplerV1 instance from a DictConfig with prompt keypoints and keybody index lists', 'sample_keypoints_v1': 'sample prompt keypoints from ground truth and predicted 2D keypoints using KeypointSamplerV1', 'get_worst_keypoint': 'get the worst keypoint index from a distance tensor filtered by a keypoint list', 'get_random_keypoint': 'get a random valid keypoint index from candidates with positive distances in a keypoint list', 'compute_masked_distance': 'compute pairwise squared distances between two tensors with optional masking for ignored elements'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/models/decoders/prompt_encoder.py

Prompts

```
['build a KeypointSamplerV1 instance from a DictConfig with prompt keypoints and keybody index lists', 'sample prompt keypoints from ground truth and predicted 2D keypoints using KeypointSamplerV1', 'get the worst keypoint index from a distance tensor filtered by a keypoint list', 'get a random valid keypoint index from candidates with positive distances in a keypoint list', 'compute pairwise squared distances between two tensors with optional masking for ignored elements', 'build a PromptEncoder module to encode keypoints and mask prompts for SAM body segmentation', 'create a PositionEmbeddingRandom module to generate sinusoidal positional encodings for normalized coordinates', 'test the _embed_keypoints method to embed normalized point prompts with joint labels', 'review the PromptEncoder forward method that returns sparse and dense embeddings from keypoints', 'refactor the mask_downscaling conv layers to support custom mask embedding types v1 or v2', 'build a PromptableDecoder with specified dims, depth, and num_heads for cross-attention transformer decoding', 'run a forward pass through PromptableDecoder with token and image embeddings to get pose output', 'freeze all PromptableDecoder parameters by setting frozen flag to prevent gradient updates', 'review the forward method to enable intermediate pose predictions across decoder layers', 'test PromptableDecoder forward pass with hand embeddings concatenated to image context features']
```

Usage

```
{'build_prompt_encoder': 'build a PromptEncoder module to encode keypoints and mask prompts for SAM body segmentation', 'create_positional_encoding': 'create a PositionEmbeddingRandom module to generate sinusoidal positional encodings for normalized coordinates', 'test_embed_keypoints': 'test the _embed_keypoints method to embed normalized point prompts with joint labels', 'review_forward_method': 'review the PromptEncoder forward method that returns sparse and dense embeddings from keypoints', 'refactor_mask_downscaling': 'refactor the mask_downscaling conv layers to support custom mask embedding types v1 or v2'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/models/decoders/promptable_decoder.py

Prompts

```
['build a KeypointSamplerV1 instance from a DictConfig with prompt keypoints and keybody index lists', 'sample prompt keypoints from ground truth and predicted 2D keypoints using KeypointSamplerV1', 'get the worst keypoint index from a distance tensor filtered by a keypoint list', 'get a random valid keypoint index from candidates with positive distances in a keypoint list', 'compute pairwise squared distances between two tensors with optional masking for ignored elements', 'build a PromptEncoder module to encode keypoints and mask prompts for SAM body segmentation', 'create a PositionEmbeddingRandom module to generate sinusoidal positional encodings for normalized coordinates', 'test the _embed_keypoints method to embed normalized point prompts with joint labels', 'review the PromptEncoder forward method that returns sparse and dense embeddings from keypoints', 'refactor the mask_downscaling conv layers to support custom mask embedding types v1 or v2', 'build a PromptableDecoder with specified dims, depth, and num_heads for cross-attention transformer decoding', 'run a forward pass through PromptableDecoder with token and image embeddings to get pose output', 'freeze all PromptableDecoder parameters by setting frozen flag to prevent gradient updates', 'review the forward method to enable intermediate pose predictions across decoder layers', 'test PromptableDecoder forward pass with hand embeddings concatenated to image context features']
```

Usage

```
{'build_promptable_decoder': 'build a PromptableDecoder with specified dims, depth, and num_heads for cross-attention transformer decoding', 'run_forward_pass': 'run a forward pass through PromptableDecoder with token and image embeddings to get pose output', 'freeze_decoder_stages': 'freeze all PromptableDecoder parameters by setting frozen flag to prevent gradient updates', 'review_forward_with_interm_preds': 'review the forward method to enable intermediate pose predictions across decoder layers', 'test_decoder_with_hand_embeddings': 'test PromptableDecoder forward pass with hand embeddings concatenated to image context features'}
```

