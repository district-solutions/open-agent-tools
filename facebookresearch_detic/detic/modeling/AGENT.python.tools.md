# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/detic/modeling/debug.py

Prompts

```
['visualize training heatmaps, ground truth boxes, and positive sample markers on images using debug_train', 'visualize predicted heatmaps and detection results with bounding boxes and class labels using debug_test', 'visualize second stage detection results with optional proposal overlays and save debug images to disk', 'create a color map image from a heatmap tensor using _get_color_image for visualization', 'blend multiple heatmap color maps onto an image with configurable alpha transparency using _blend_image_heatmaps', 'load class frequency weights from an LVIS category info JSON file with configurable frequency exponent', 'sample category indices for frequency enhanced detection loss by combining appeared classes with weighted random sampling', "reset a DETR model's classification head with zero-shot weights from a numpy file for testing", 'summarize the load_class_freq function which reads category image counts and returns frequency-weighted tensors', 'review the get_fed_loss_inds function which samples category indices using multinomial distribution for fed loss']
```

Usage

```
{'debug_train_visualize': 'visualize training heatmaps, ground truth boxes, and positive sample markers on images using debug_train', 'debug_test_visualize': 'visualize predicted heatmaps and detection results with bounding boxes and class labels using debug_test', 'debug_second_stage_visualize': 'visualize second stage detection results with optional proposal overlays and save debug images to disk', 'create_color_map_from_heatmap': 'create a color map image from a heatmap tensor using _get_color_image for visualization', 'blend_heatmaps_on_image': 'blend multiple heatmap color maps onto an image with configurable alpha transparency using _blend_image_heatmaps'}
```

## File: facebookresearch_detic/detic/modeling/utils.py

Prompts

```
['visualize training heatmaps, ground truth boxes, and positive sample markers on images using debug_train', 'visualize predicted heatmaps and detection results with bounding boxes and class labels using debug_test', 'visualize second stage detection results with optional proposal overlays and save debug images to disk', 'create a color map image from a heatmap tensor using _get_color_image for visualization', 'blend multiple heatmap color maps onto an image with configurable alpha transparency using _blend_image_heatmaps', 'load class frequency weights from an LVIS category info JSON file with configurable frequency exponent', 'sample category indices for frequency enhanced detection loss by combining appeared classes with weighted random sampling', "reset a DETR model's classification head with zero-shot weights from a numpy file for testing", 'summarize the load_class_freq function which reads category image counts and returns frequency-weighted tensors', 'review the get_fed_loss_inds function which samples category indices using multinomial distribution for fed loss']
```

Usage

```
{'load_class_freq': 'load class frequency weights from an LVIS category info JSON file with configurable frequency exponent', 'get_fed_loss_inds': 'sample category indices for frequency enhanced detection loss by combining appeared classes with weighted random sampling', 'reset_cls_test': "reset a DETR model's classification head with zero-shot weights from a numpy file for testing", 'summarize_load_class_freq': 'summarize the load_class_freq function which reads category image counts and returns frequency-weighted tensors', 'review_get_fed_loss_inds': 'review the get_fed_loss_inds function which samples category indices using multinomial distribution for fed loss'}
```

