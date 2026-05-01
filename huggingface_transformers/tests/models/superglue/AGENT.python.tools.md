# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/superglue/test_image_processing_superglue.py

Prompts

```
['test the SuperGlueImageProcessingTest class to verify image preprocessing with paired image inputs', 'test post_process_keypoint_matching to verify keypoints are filtered and scores are valid', 'test post_process_keypoint_matching with padded match indices that point beyond real keypoints', 'test that the image processor raises ValueError for unpaired or odd-numbered image inputs', 'test that the torchvision backend image processor can be compiled with torch.compile', 'test the SuperGlueForKeypointMatching model with random inputs and verify output shapes', 'test SuperGlueConfig serialization to JSON and loading from pretrained', 'test SuperGlueForKeypointMatching output_hidden_states returns correct hidden state sizes', 'test SuperGlueForKeypointMatching output_attentions returns correct attention shapes', 'test SuperGlueForKeypointMatching batched and single-row outputs produce equivalent results']
```

Usage

```
{'test_superglue_image_processing': 'test the SuperGlueImageProcessingTest class to verify image preprocessing with paired image inputs', 'test_keypoint_matching_post_processing': 'test post_process_keypoint_matching to verify keypoints are filtered and scores are valid', 'test_padded_match_indices_handling': 'test post_process_keypoint_matching with padded match indices that point beyond real keypoints', 'test_image_pair_validation': 'test that the image processor raises ValueError for unpaired or odd-numbered image inputs', 'test_torchvision_backend_compilation': 'test that the torchvision backend image processor can be compiled with torch.compile'}
```

## File: huggingface_transformers/tests/models/superglue/test_modeling_superglue.py

Prompts

```
['test the SuperGlueImageProcessingTest class to verify image preprocessing with paired image inputs', 'test post_process_keypoint_matching to verify keypoints are filtered and scores are valid', 'test post_process_keypoint_matching with padded match indices that point beyond real keypoints', 'test that the image processor raises ValueError for unpaired or odd-numbered image inputs', 'test that the torchvision backend image processor can be compiled with torch.compile', 'test the SuperGlueForKeypointMatching model with random inputs and verify output shapes', 'test SuperGlueConfig serialization to JSON and loading from pretrained', 'test SuperGlueForKeypointMatching output_hidden_states returns correct hidden state sizes', 'test SuperGlueForKeypointMatching output_attentions returns correct attention shapes', 'test SuperGlueForKeypointMatching batched and single-row outputs produce equivalent results']
```

Usage

```
{'test_SuperGlue_model': 'test the SuperGlueForKeypointMatching model with random inputs and verify output shapes', 'test_SuperGlue_config': 'test SuperGlueConfig serialization to JSON and loading from pretrained', 'test_SuperGlue_hidden_states': 'test SuperGlueForKeypointMatching output_hidden_states returns correct hidden state sizes', 'test_SuperGlue_attention': 'test SuperGlueForKeypointMatching output_attentions returns correct attention shapes', 'test_SuperGlue_batching': 'test SuperGlueForKeypointMatching batched and single-row outputs produce equivalent results'}
```

