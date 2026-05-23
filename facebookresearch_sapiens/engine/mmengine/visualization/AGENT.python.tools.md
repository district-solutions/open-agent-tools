# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/visualization/utils.py

Prompts

```
['convert a PyTorch tensor to a NumPy ndarray using tensor2ndarray', 'convert a feature map to a color heatmap and overlay it on an image with convert_overlay_heatmap', 'convert RGB color tuples to normalized matplotlib color values with color_val_matplotlib', 'extract an RGB numpy array from a matplotlib FigureCanvasAgg using img_from_canvas', 'validate that a value matches an expected type and minimum list length with check_type_and_length', 'create a LocalVisBackend instance to save images, scalars, and configs to local disk', 'create a WandbVisBackend instance to log images, scalars, and configs to Weights and Biases', 'create a TensorboardVisBackend instance to write images, scalars, and configs to TensorBoard', 'create an MLflowVisBackend instance to log images, scalars, and configs to MLflow', 'create a ClearMLVisBackend instance to report images, scalars, and configs to ClearML', 'draw single or multiple bounding boxes on an image with customizable colors and line styles', 'draw text labels at specified positions on an image with configurable font size and color', 'overlay binary segmentation masks on an image with adjustable transparency and colors', 'visualize neural network feature maps as heatmaps overlaid on an image with channel reduction', 'record scalar metrics like loss or accuracy to visualization backends for tracking over steps']
```

Usage

```
{'convert_tensor_to_numpy': 'convert a PyTorch tensor to a NumPy ndarray using tensor2ndarray', 'convert_featmap_to_heatmap': 'convert a feature map to a color heatmap and overlay it on an image with convert_overlay_heatmap', 'normalize_color_for_matplotlib': 'convert RGB color tuples to normalized matplotlib color values with color_val_matplotlib', 'extract_rgb_from_canvas': 'extract an RGB numpy array from a matplotlib FigureCanvasAgg using img_from_canvas', 'validate_type_and_length': 'validate that a value matches an expected type and minimum list length with check_type_and_length'}
```

## File: facebookresearch_sapiens/engine/mmengine/visualization/vis_backend.py

Prompts

```
['convert a PyTorch tensor to a NumPy ndarray using tensor2ndarray', 'convert a feature map to a color heatmap and overlay it on an image with convert_overlay_heatmap', 'convert RGB color tuples to normalized matplotlib color values with color_val_matplotlib', 'extract an RGB numpy array from a matplotlib FigureCanvasAgg using img_from_canvas', 'validate that a value matches an expected type and minimum list length with check_type_and_length', 'create a LocalVisBackend instance to save images, scalars, and configs to local disk', 'create a WandbVisBackend instance to log images, scalars, and configs to Weights and Biases', 'create a TensorboardVisBackend instance to write images, scalars, and configs to TensorBoard', 'create an MLflowVisBackend instance to log images, scalars, and configs to MLflow', 'create a ClearMLVisBackend instance to report images, scalars, and configs to ClearML', 'draw single or multiple bounding boxes on an image with customizable colors and line styles', 'draw text labels at specified positions on an image with configurable font size and color', 'overlay binary segmentation masks on an image with adjustable transparency and colors', 'visualize neural network feature maps as heatmaps overlaid on an image with channel reduction', 'record scalar metrics like loss or accuracy to visualization backends for tracking over steps']
```

Usage

```
{'create_LocalVisBackend': 'create a LocalVisBackend instance to save images, scalars, and configs to local disk', 'create_WandbVisBackend': 'create a WandbVisBackend instance to log images, scalars, and configs to Weights and Biases', 'create_TensorboardVisBackend': 'create a TensorboardVisBackend instance to write images, scalars, and configs to TensorBoard', 'create_MLflowVisBackend': 'create an MLflowVisBackend instance to log images, scalars, and configs to MLflow', 'create_ClearMLVisBackend': 'create a ClearMLVisBackend instance to report images, scalars, and configs to ClearML'}
```

## File: facebookresearch_sapiens/engine/mmengine/visualization/visualizer.py

Prompts

```
['convert a PyTorch tensor to a NumPy ndarray using tensor2ndarray', 'convert a feature map to a color heatmap and overlay it on an image with convert_overlay_heatmap', 'convert RGB color tuples to normalized matplotlib color values with color_val_matplotlib', 'extract an RGB numpy array from a matplotlib FigureCanvasAgg using img_from_canvas', 'validate that a value matches an expected type and minimum list length with check_type_and_length', 'create a LocalVisBackend instance to save images, scalars, and configs to local disk', 'create a WandbVisBackend instance to log images, scalars, and configs to Weights and Biases', 'create a TensorboardVisBackend instance to write images, scalars, and configs to TensorBoard', 'create an MLflowVisBackend instance to log images, scalars, and configs to MLflow', 'create a ClearMLVisBackend instance to report images, scalars, and configs to ClearML', 'draw single or multiple bounding boxes on an image with customizable colors and line styles', 'draw text labels at specified positions on an image with configurable font size and color', 'overlay binary segmentation masks on an image with adjustable transparency and colors', 'visualize neural network feature maps as heatmaps overlaid on an image with channel reduction', 'record scalar metrics like loss or accuracy to visualization backends for tracking over steps']
```

Usage

```
{'draw_bounding_boxes': 'draw single or multiple bounding boxes on an image with customizable colors and line styles', 'draw_text_labels': 'draw text labels at specified positions on an image with configurable font size and color', 'draw_binary_masks': 'overlay binary segmentation masks on an image with adjustable transparency and colors', 'draw_feature_maps': 'visualize neural network feature maps as heatmaps overlaid on an image with channel reduction', 'add_scalar_metrics': 'record scalar metrics like loss or accuracy to visualization backends for tracking over steps'}
```

