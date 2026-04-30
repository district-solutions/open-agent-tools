# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/zoedepth/test_image_processing_zoedepth.py

Prompts

```
['test the ZoeDepthImageProcessingTest class verifies image processor attributes like image_mean, image_std, do_normalize, do_resize, size, ensure_multiple_of, do_rescale, rescale_factor, and do_pad', 'test the ensure_multiple_of parameter pads or resizes images so height and width are multiples of a given value like 32', 'test the keep_aspect_ratio parameter preserves image proportions during resize instead of stretching to exact target dimensions', 'test creating ZoeDepth image processors from configuration dictionaries with size specified as dict or integer', 'test that torchvision and pil backends produce equivalent depth estimation post-processing results', 'test the ZoeDepthForDepthEstimation model forward pass returns predicted_depth with correct shape', 'test ZoeDepthModelTester.prepare_config_and_inputs generates valid config, pixel values, and labels', 'test ZoeDepthForDepthEstimation inference with image processor post-processing and flip augmentation', 'test ZoeDepthForDepthEstimation inference with Intel/zoedepth-nyu-kitti model for multiple heads', 'test ZoeDepth image processor post_process_depth_estimation resizes outputs to target sizes correctly']
```

Usage

```
{'test_image_processor_properties': 'test the ZoeDepthImageProcessingTest class verifies image processor attributes like image_mean, image_std, do_normalize, do_resize, size, ensure_multiple_of, do_rescale, rescale_factor, and do_pad', 'test_ensure_multiple_of': 'test the ensure_multiple_of parameter pads or resizes images so height and width are multiples of a given value like 32', 'test_keep_aspect_ratio': 'test the keep_aspect_ratio parameter preserves image proportions during resize instead of stretching to exact target dimensions', 'test_image_processor_from_dict_with_kwargs': 'test creating ZoeDepth image processors from configuration dictionaries with size specified as dict or integer', 'test_post_processing_equivalence': 'test that torchvision and pil backends produce equivalent depth estimation post-processing results'}
```

## File: huggingface_transformers/tests/models/zoedepth/test_modeling_zoedepth.py

Prompts

```
['test the ZoeDepthImageProcessingTest class verifies image processor attributes like image_mean, image_std, do_normalize, do_resize, size, ensure_multiple_of, do_rescale, rescale_factor, and do_pad', 'test the ensure_multiple_of parameter pads or resizes images so height and width are multiples of a given value like 32', 'test the keep_aspect_ratio parameter preserves image proportions during resize instead of stretching to exact target dimensions', 'test creating ZoeDepth image processors from configuration dictionaries with size specified as dict or integer', 'test that torchvision and pil backends produce equivalent depth estimation post-processing results', 'test the ZoeDepthForDepthEstimation model forward pass returns predicted_depth with correct shape', 'test ZoeDepthModelTester.prepare_config_and_inputs generates valid config, pixel values, and labels', 'test ZoeDepthForDepthEstimation inference with image processor post-processing and flip augmentation', 'test ZoeDepthForDepthEstimation inference with Intel/zoedepth-nyu-kitti model for multiple heads', 'test ZoeDepth image processor post_process_depth_estimation resizes outputs to target sizes correctly']
```

Usage

```
{'test_ZoeDepthForDepthEstimation_depth_output_shape': 'test the ZoeDepthForDepthEstimation model forward pass returns predicted_depth with correct shape', 'test_ZoeDepthModelTester_config_and_inputs': 'test ZoeDepthModelTester.prepare_config_and_inputs generates valid config, pixel values, and labels', 'test_ZoeDepthModelIntegrationTest_inference_with_post_processing': 'test ZoeDepthForDepthEstimation inference with image processor post-processing and flip augmentation', 'test_ZoeDepthModelIntegrationTest_multiple_heads': 'test ZoeDepthForDepthEstimation inference with Intel/zoedepth-nyu-kitti model for multiple heads', 'test_ZoeDepthModelIntegrationTest_check_target_size': 'test ZoeDepth image processor post_process_depth_estimation resizes outputs to target sizes correctly'}
```

