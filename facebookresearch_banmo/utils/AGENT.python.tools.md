# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/utils/colors.py

Prompts

```
['get a numpy array of 64 RGB color triplets for visualizing bones', 'visualize bone segmentation labels using the label_colormap function with distinct RGB colors', 'create a color lookup table by calling label_colormap to index colors by label ID', 'render a segmentation map by mapping label indices to colors from label_colormap', 'review the label_colormap function that returns 64 unique RGB colors for bone visualization', 'create a DensePose CSE model from a config file and pretrained weights path', 'run CSE inference on an image with a mask to get closest vertex assignments and embeddings', 'build a DensePose embedder and mesh vertex embeddings for all classes from the config', 'review the run_cse function that performs DensePose inference and returns vertex assignments and visualizations', 'summarize the create_cse function that loads a Detectron2 model with DensePose configuration and weights', 'create a 3D mesh of bone ellipsoids from pose parameters and export to OBJ file path', 'draw colored lines between pairs of 2D point coordinates on a PyTorch tensor image', 'save a list of numpy frame arrays as a GIF or video file with configurable FPS', 'create a trimesh visualization of a list of 4x4 camera poses with colored axes', 'query a NeRF model to get RGB vertex colors for a 3D mesh at a given frame']
```

Usage

```
{'get_label_colormap': 'get a numpy array of 64 RGB color triplets for visualizing bones', 'visualize_bone_labels': 'visualize bone segmentation labels using the label_colormap function with distinct RGB colors', 'create_color_lookup': 'create a color lookup table by calling label_colormap to index colors by label ID', 'render_segmentation_map': 'render a segmentation map by mapping label indices to colors from label_colormap', 'review_label_colormap': 'review the label_colormap function that returns 64 unique RGB colors for bone visualization'}
```

## File: facebookresearch_banmo/utils/cselib.py

Prompts

```
['get a numpy array of 64 RGB color triplets for visualizing bones', 'visualize bone segmentation labels using the label_colormap function with distinct RGB colors', 'create a color lookup table by calling label_colormap to index colors by label ID', 'render a segmentation map by mapping label indices to colors from label_colormap', 'review the label_colormap function that returns 64 unique RGB colors for bone visualization', 'create a DensePose CSE model from a config file and pretrained weights path', 'run CSE inference on an image with a mask to get closest vertex assignments and embeddings', 'build a DensePose embedder and mesh vertex embeddings for all classes from the config', 'review the run_cse function that performs DensePose inference and returns vertex assignments and visualizations', 'summarize the create_cse function that loads a Detectron2 model with DensePose configuration and weights', 'create a 3D mesh of bone ellipsoids from pose parameters and export to OBJ file path', 'draw colored lines between pairs of 2D point coordinates on a PyTorch tensor image', 'save a list of numpy frame arrays as a GIF or video file with configurable FPS', 'create a trimesh visualization of a list of 4x4 camera poses with colored axes', 'query a NeRF model to get RGB vertex colors for a 3D mesh at a given frame']
```

Usage

```
{'create_cse_model': 'create a DensePose CSE model from a config file and pretrained weights path', 'run_cse_inference': 'run CSE inference on an image with a mask to get closest vertex assignments and embeddings', 'build_densepose_embedder': 'build a DensePose embedder and mesh vertex embeddings for all classes from the config', 'review_run_cse': 'review the run_cse function that performs DensePose inference and returns vertex assignments and visualizations', 'summarize_create_cse': 'summarize the create_cse function that loads a Detectron2 model with DensePose configuration and weights'}
```

## File: facebookresearch_banmo/utils/io.py

Prompts

```
['get a numpy array of 64 RGB color triplets for visualizing bones', 'visualize bone segmentation labels using the label_colormap function with distinct RGB colors', 'create a color lookup table by calling label_colormap to index colors by label ID', 'render a segmentation map by mapping label indices to colors from label_colormap', 'review the label_colormap function that returns 64 unique RGB colors for bone visualization', 'create a DensePose CSE model from a config file and pretrained weights path', 'run CSE inference on an image with a mask to get closest vertex assignments and embeddings', 'build a DensePose embedder and mesh vertex embeddings for all classes from the config', 'review the run_cse function that performs DensePose inference and returns vertex assignments and visualizations', 'summarize the create_cse function that loads a Detectron2 model with DensePose configuration and weights', 'create a 3D mesh of bone ellipsoids from pose parameters and export to OBJ file path', 'draw colored lines between pairs of 2D point coordinates on a PyTorch tensor image', 'save a list of numpy frame arrays as a GIF or video file with configurable FPS', 'create a trimesh visualization of a list of 4x4 camera poses with colored axes', 'query a NeRF model to get RGB vertex colors for a 3D mesh at a given frame']
```

Usage

```
{'save_bones': 'create a 3D mesh of bone ellipsoids from pose parameters and export to OBJ file path', 'draw_lines': 'draw colored lines between pairs of 2D point coordinates on a PyTorch tensor image', 'save_vid': 'save a list of numpy frame arrays as a GIF or video file with configurable FPS', 'draw_cams': 'create a trimesh visualization of a list of 4x4 camera poses with colored axes', 'get_vertex_colors': 'query a NeRF model to get RGB vertex colors for a 3D mesh at a given frame'}
```

