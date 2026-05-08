# Agent Python Tools

- repo: facebookresearch/ov-seg
- repo_uri: https://github.com/facebookresearch/ov-seg

## File: facebookresearch_ov-seg/open_vocab_seg/utils/events.py

Prompts

```
['initialize wandb with detectron2 config and args for experiment tracking on the main process', 'create a WandbWriter instance to log scalars, images, and histograms from detectron2 event storage to wandb', 'call write on WandbWriter to flush latest scalars, images, and histograms to wandb with grouping rules', 'use the IsIn rule class to check if a keyword is present in a scalar name string', 'use the Prefix rule class to prepend a keyword prefix to a scalar name with a slash separator', 'create a NestedTensor from a list of 3D image tensors with automatic padding and masking', 'build an ONNX-compatible NestedTensor from a list of 3D tensors using functional padding', 'check if PyTorch distributed is available and initialized for multi-GPU training', 'extract binary masks for each unique class ID from a ground truth semantic segmentation tensor', 'decompose a NestedTensor object into its underlying tensors and mask components', 'run dense crf post processing on segmentation logits and an image to refine predictions', 'create refined segmentation logits by applying dense crf inference with configurable iteration count', 'build a post processing pipeline that takes torch tensor logits and an image for crf refinement', 'test the dense crf inference function with softmax logits and a 3 channel image', 'refactor the dense crf post process function to customize bilateral and gaussian kernel parameters', 'run the OVSegPredictor class to predict semantic segmentation on an image with custom class names', 'create an OVSegVisualizer instance to draw semantic segmentation masks with labeled class names on an image', 'run the VisualizationDemo class to perform open-vocabulary semantic segmentation and visualization on an image', 'review the OVSegPredictor __call__ method that preprocesses BGR images and runs model inference with class names', 'review the OVSegVisualizer draw_sem_seg method that draws labeled segmentation masks sorted by area size']
```

Usage

```
{'setup_wandb': 'initialize wandb with detectron2 config and args for experiment tracking on the main process', 'create_wandb_writer': 'create a WandbWriter instance to log scalars, images, and histograms from detectron2 event storage to wandb', 'use_wandb_writer_write': 'call write on WandbWriter to flush latest scalars, images, and histograms to wandb with grouping rules', 'use_isin_rule': 'use the IsIn rule class to check if a keyword is present in a scalar name string', 'use_prefix_rule': 'use the Prefix rule class to prepend a keyword prefix to a scalar name with a slash separator'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/utils/misc.py

Prompts

```
['initialize wandb with detectron2 config and args for experiment tracking on the main process', 'create a WandbWriter instance to log scalars, images, and histograms from detectron2 event storage to wandb', 'call write on WandbWriter to flush latest scalars, images, and histograms to wandb with grouping rules', 'use the IsIn rule class to check if a keyword is present in a scalar name string', 'use the Prefix rule class to prepend a keyword prefix to a scalar name with a slash separator', 'create a NestedTensor from a list of 3D image tensors with automatic padding and masking', 'build an ONNX-compatible NestedTensor from a list of 3D tensors using functional padding', 'check if PyTorch distributed is available and initialized for multi-GPU training', 'extract binary masks for each unique class ID from a ground truth semantic segmentation tensor', 'decompose a NestedTensor object into its underlying tensors and mask components', 'run dense crf post processing on segmentation logits and an image to refine predictions', 'create refined segmentation logits by applying dense crf inference with configurable iteration count', 'build a post processing pipeline that takes torch tensor logits and an image for crf refinement', 'test the dense crf inference function with softmax logits and a 3 channel image', 'refactor the dense crf post process function to customize bilateral and gaussian kernel parameters', 'run the OVSegPredictor class to predict semantic segmentation on an image with custom class names', 'create an OVSegVisualizer instance to draw semantic segmentation masks with labeled class names on an image', 'run the VisualizationDemo class to perform open-vocabulary semantic segmentation and visualization on an image', 'review the OVSegPredictor __call__ method that preprocesses BGR images and runs model inference with class names', 'review the OVSegVisualizer draw_sem_seg method that draws labeled segmentation masks sorted by area size']
```

Usage

```
{'create_nested_tensor_from_images': 'create a NestedTensor from a list of 3D image tensors with automatic padding and masking', 'build_onnx_nested_tensor': 'build an ONNX-compatible NestedTensor from a list of 3D tensors using functional padding', 'check_distributed_initialized': 'check if PyTorch distributed is available and initialized for multi-GPU training', 'extract_binary_masks_from_semseg': 'extract binary masks for each unique class ID from a ground truth semantic segmentation tensor', 'decompose_nested_tensor': 'decompose a NestedTensor object into its underlying tensors and mask components'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/utils/post_process_utils.py

Prompts

```
['initialize wandb with detectron2 config and args for experiment tracking on the main process', 'create a WandbWriter instance to log scalars, images, and histograms from detectron2 event storage to wandb', 'call write on WandbWriter to flush latest scalars, images, and histograms to wandb with grouping rules', 'use the IsIn rule class to check if a keyword is present in a scalar name string', 'use the Prefix rule class to prepend a keyword prefix to a scalar name with a slash separator', 'create a NestedTensor from a list of 3D image tensors with automatic padding and masking', 'build an ONNX-compatible NestedTensor from a list of 3D tensors using functional padding', 'check if PyTorch distributed is available and initialized for multi-GPU training', 'extract binary masks for each unique class ID from a ground truth semantic segmentation tensor', 'decompose a NestedTensor object into its underlying tensors and mask components', 'run dense crf post processing on segmentation logits and an image to refine predictions', 'create refined segmentation logits by applying dense crf inference with configurable iteration count', 'build a post processing pipeline that takes torch tensor logits and an image for crf refinement', 'test the dense crf inference function with softmax logits and a 3 channel image', 'refactor the dense crf post process function to customize bilateral and gaussian kernel parameters', 'run the OVSegPredictor class to predict semantic segmentation on an image with custom class names', 'create an OVSegVisualizer instance to draw semantic segmentation masks with labeled class names on an image', 'run the VisualizationDemo class to perform open-vocabulary semantic segmentation and visualization on an image', 'review the OVSegPredictor __call__ method that preprocesses BGR images and runs model inference with class names', 'review the OVSegVisualizer draw_sem_seg method that draws labeled segmentation masks sorted by area size']
```

Usage

```
{'run_dense_crf_post_process': 'run dense crf post processing on segmentation logits and an image to refine predictions', 'create_crf_refined_logits': 'create refined segmentation logits by applying dense crf inference with configurable iteration count', 'build_post_process_pipeline': 'build a post processing pipeline that takes torch tensor logits and an image for crf refinement', 'test_dense_crf_inference': 'test the dense crf inference function with softmax logits and a 3 channel image', 'refactor_crf_parameters': 'refactor the dense crf post process function to customize bilateral and gaussian kernel parameters'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/utils/predictor.py

Prompts

```
['initialize wandb with detectron2 config and args for experiment tracking on the main process', 'create a WandbWriter instance to log scalars, images, and histograms from detectron2 event storage to wandb', 'call write on WandbWriter to flush latest scalars, images, and histograms to wandb with grouping rules', 'use the IsIn rule class to check if a keyword is present in a scalar name string', 'use the Prefix rule class to prepend a keyword prefix to a scalar name with a slash separator', 'create a NestedTensor from a list of 3D image tensors with automatic padding and masking', 'build an ONNX-compatible NestedTensor from a list of 3D tensors using functional padding', 'check if PyTorch distributed is available and initialized for multi-GPU training', 'extract binary masks for each unique class ID from a ground truth semantic segmentation tensor', 'decompose a NestedTensor object into its underlying tensors and mask components', 'run dense crf post processing on segmentation logits and an image to refine predictions', 'create refined segmentation logits by applying dense crf inference with configurable iteration count', 'build a post processing pipeline that takes torch tensor logits and an image for crf refinement', 'test the dense crf inference function with softmax logits and a 3 channel image', 'refactor the dense crf post process function to customize bilateral and gaussian kernel parameters', 'run the OVSegPredictor class to predict semantic segmentation on an image with custom class names', 'create an OVSegVisualizer instance to draw semantic segmentation masks with labeled class names on an image', 'run the VisualizationDemo class to perform open-vocabulary semantic segmentation and visualization on an image', 'review the OVSegPredictor __call__ method that preprocesses BGR images and runs model inference with class names', 'review the OVSegVisualizer draw_sem_seg method that draws labeled segmentation masks sorted by area size']
```

Usage

```
{'run_OVSegPredictor': 'run the OVSegPredictor class to predict semantic segmentation on an image with custom class names', 'create_OVSegVisualizer': 'create an OVSegVisualizer instance to draw semantic segmentation masks with labeled class names on an image', 'run_VisualizationDemo': 'run the VisualizationDemo class to perform open-vocabulary semantic segmentation and visualization on an image', 'review_OVSegPredictor_call': 'review the OVSegPredictor __call__ method that preprocesses BGR images and runs model inference with class names', 'review_OVSegVisualizer_draw_sem_seg': 'review the OVSegVisualizer draw_sem_seg method that draws labeled segmentation masks sorted by area size'}
```

