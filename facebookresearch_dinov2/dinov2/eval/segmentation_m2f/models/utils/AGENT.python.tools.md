# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/models/utils/assigner.py

Prompts

```
['build a MaskHungarianAssigner with custom classification, dice, and mask cost weights for mask matching', 'run the MaskHungarianAssigner assign method to match predicted masks to ground truth masks using Hungarian algorithm', 'create an AssignResult object storing the number of ground truths, assigned ground truth indices, and labels', 'review the AssignResult info property to inspect assigned ground truth indices and labels as a dictionary', 'test a custom subclass of BaseAssigner by implementing the abstract assign method for mask assignment', 'build a python module that estimates mask prediction uncertainty scores from logits using L1 distance to zero', 'create a function that samples uncertain and random point coordinates from mask predictions for training', 'test the get_uncertainty function with mask prediction logits and class labels to verify uncertainty scores', 'refactor the get_uncertain_point_coords_with_randomness function to support custom uncertainty metrics instead of L1 distance', 'review the point_sample module for mask prediction uncertainty estimation and point coordinate sampling logic', 'build a SinePositionalEncoding module with sine and cosine position embeddings for a transformer model', 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for a transformer', 'test the SinePositionalEncoding forward pass with a boolean mask tensor and verify output shape', 'test the LearnedPositionalEncoding forward pass with a mask tensor and verify the learned embeddings', 'refactor the SinePositionalEncoding forward method to support a custom normalization scale factor', 'build a DeformableDetrTransformer for multi-level feature object detection with deformable attention', 'create a DETR Transformer with encoder and decoder for end-to-end object detection', 'build a PatchMerging layer to downsample and merge patch feature maps using nn.Unfold', 'create a DynamicConv module that generates per-sample convolution parameters using bmm', 'test the FFN feedforward network with configurable activation and dropout layers']
```

Usage

```
{'build_mask_hungarian_assigner': 'build a MaskHungarianAssigner with custom classification, dice, and mask cost weights for mask matching', 'run_hungarian_assignment': 'run the MaskHungarianAssigner assign method to match predicted masks to ground truth masks using Hungarian algorithm', 'create_assign_result': 'create an AssignResult object storing the number of ground truths, assigned ground truth indices, and labels', 'review_assign_result_info': 'review the AssignResult info property to inspect assigned ground truth indices and labels as a dictionary', 'test_base_assigner_subclass': 'test a custom subclass of BaseAssigner by implementing the abstract assign method for mask assignment'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/models/utils/point_sample.py

Prompts

```
['build a MaskHungarianAssigner with custom classification, dice, and mask cost weights for mask matching', 'run the MaskHungarianAssigner assign method to match predicted masks to ground truth masks using Hungarian algorithm', 'create an AssignResult object storing the number of ground truths, assigned ground truth indices, and labels', 'review the AssignResult info property to inspect assigned ground truth indices and labels as a dictionary', 'test a custom subclass of BaseAssigner by implementing the abstract assign method for mask assignment', 'build a python module that estimates mask prediction uncertainty scores from logits using L1 distance to zero', 'create a function that samples uncertain and random point coordinates from mask predictions for training', 'test the get_uncertainty function with mask prediction logits and class labels to verify uncertainty scores', 'refactor the get_uncertain_point_coords_with_randomness function to support custom uncertainty metrics instead of L1 distance', 'review the point_sample module for mask prediction uncertainty estimation and point coordinate sampling logic', 'build a SinePositionalEncoding module with sine and cosine position embeddings for a transformer model', 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for a transformer', 'test the SinePositionalEncoding forward pass with a boolean mask tensor and verify output shape', 'test the LearnedPositionalEncoding forward pass with a mask tensor and verify the learned embeddings', 'refactor the SinePositionalEncoding forward method to support a custom normalization scale factor', 'build a DeformableDetrTransformer for multi-level feature object detection with deformable attention', 'create a DETR Transformer with encoder and decoder for end-to-end object detection', 'build a PatchMerging layer to downsample and merge patch feature maps using nn.Unfold', 'create a DynamicConv module that generates per-sample convolution parameters using bmm', 'test the FFN feedforward network with configurable activation and dropout layers']
```

Usage

```
{'build_mask_uncertainty_estimator': 'build a python module that estimates mask prediction uncertainty scores from logits using L1 distance to zero', 'create_point_sampler': 'create a function that samples uncertain and random point coordinates from mask predictions for training', 'test_get_uncertainty': 'test the get_uncertainty function with mask prediction logits and class labels to verify uncertainty scores', 'refactor_point_sampling': 'refactor the get_uncertain_point_coords_with_randomness function to support custom uncertainty metrics instead of L1 distance', 'review_point_sample_module': 'review the point_sample module for mask prediction uncertainty estimation and point coordinate sampling logic'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/models/utils/positional_encoding.py

Prompts

```
['build a MaskHungarianAssigner with custom classification, dice, and mask cost weights for mask matching', 'run the MaskHungarianAssigner assign method to match predicted masks to ground truth masks using Hungarian algorithm', 'create an AssignResult object storing the number of ground truths, assigned ground truth indices, and labels', 'review the AssignResult info property to inspect assigned ground truth indices and labels as a dictionary', 'test a custom subclass of BaseAssigner by implementing the abstract assign method for mask assignment', 'build a python module that estimates mask prediction uncertainty scores from logits using L1 distance to zero', 'create a function that samples uncertain and random point coordinates from mask predictions for training', 'test the get_uncertainty function with mask prediction logits and class labels to verify uncertainty scores', 'refactor the get_uncertain_point_coords_with_randomness function to support custom uncertainty metrics instead of L1 distance', 'review the point_sample module for mask prediction uncertainty estimation and point coordinate sampling logic', 'build a SinePositionalEncoding module with sine and cosine position embeddings for a transformer model', 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for a transformer', 'test the SinePositionalEncoding forward pass with a boolean mask tensor and verify output shape', 'test the LearnedPositionalEncoding forward pass with a mask tensor and verify the learned embeddings', 'refactor the SinePositionalEncoding forward method to support a custom normalization scale factor', 'build a DeformableDetrTransformer for multi-level feature object detection with deformable attention', 'create a DETR Transformer with encoder and decoder for end-to-end object detection', 'build a PatchMerging layer to downsample and merge patch feature maps using nn.Unfold', 'create a DynamicConv module that generates per-sample convolution parameters using bmm', 'test the FFN feedforward network with configurable activation and dropout layers']
```

Usage

```
{'build_sine_positional_encoding': 'build a SinePositionalEncoding module with sine and cosine position embeddings for a transformer model', 'build_learned_positional_encoding': 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for a transformer', 'test_sine_positional_encoding_forward': 'test the SinePositionalEncoding forward pass with a boolean mask tensor and verify output shape', 'test_learned_positional_encoding_forward': 'test the LearnedPositionalEncoding forward pass with a mask tensor and verify the learned embeddings', 'refactor_sine_positional_encoding_normalize': 'refactor the SinePositionalEncoding forward method to support a custom normalization scale factor'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/models/utils/transformer.py

Prompts

```
['build a MaskHungarianAssigner with custom classification, dice, and mask cost weights for mask matching', 'run the MaskHungarianAssigner assign method to match predicted masks to ground truth masks using Hungarian algorithm', 'create an AssignResult object storing the number of ground truths, assigned ground truth indices, and labels', 'review the AssignResult info property to inspect assigned ground truth indices and labels as a dictionary', 'test a custom subclass of BaseAssigner by implementing the abstract assign method for mask assignment', 'build a python module that estimates mask prediction uncertainty scores from logits using L1 distance to zero', 'create a function that samples uncertain and random point coordinates from mask predictions for training', 'test the get_uncertainty function with mask prediction logits and class labels to verify uncertainty scores', 'refactor the get_uncertain_point_coords_with_randomness function to support custom uncertainty metrics instead of L1 distance', 'review the point_sample module for mask prediction uncertainty estimation and point coordinate sampling logic', 'build a SinePositionalEncoding module with sine and cosine position embeddings for a transformer model', 'build a LearnedPositionalEncoding module with learnable row and column embedding weights for a transformer', 'test the SinePositionalEncoding forward pass with a boolean mask tensor and verify output shape', 'test the LearnedPositionalEncoding forward pass with a mask tensor and verify the learned embeddings', 'refactor the SinePositionalEncoding forward method to support a custom normalization scale factor', 'build a DeformableDetrTransformer for multi-level feature object detection with deformable attention', 'create a DETR Transformer with encoder and decoder for end-to-end object detection', 'build a PatchMerging layer to downsample and merge patch feature maps using nn.Unfold', 'create a DynamicConv module that generates per-sample convolution parameters using bmm', 'test the FFN feedforward network with configurable activation and dropout layers']
```

Usage

```
{'build_deformable_detr_transformer': 'build a DeformableDetrTransformer for multi-level feature object detection with deformable attention', 'create_transformer_encoder_decoder': 'create a DETR Transformer with encoder and decoder for end-to-end object detection', 'build_patch_merging_layer': 'build a PatchMerging layer to downsample and merge patch feature maps using nn.Unfold', 'create_dynamic_conv_module': 'create a DynamicConv module that generates per-sample convolution parameters using bmm', 'test_ffn_feedforward_network': 'test the FFN feedforward network with configurable activation and dropout layers'}
```

