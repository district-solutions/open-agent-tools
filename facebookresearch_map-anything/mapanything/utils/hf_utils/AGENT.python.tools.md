# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/mapanything/utils/hf_utils/css_and_html.py

Prompts

```
['generate the main header HTML with logo and title for the MapAnything Gradio interface', 'generate the main description and getting started HTML for the MapAnything Gradio interface', 'generate the acknowledgements section HTML with links to MoGe and VGGT projects', 'get the configured Gradio theme with orange primary hue and amber secondary hue', 'use the CSS styles string for customizing the MapAnything Gradio interface appearance', 'initialize a MapAnything model from a HuggingFace repository with three-tier fallback using a high-level config dict and device', 'initialize a MapAnything model entirely from local config and checkpoint files without HuggingFace Hub access', 'load a HuggingFace access token from environment variables HF_TOKEN or HUGGING_FACE_HUB_TOKEN', 'initialize a Hydra configuration from a YAML config file path with optional override strings', 'review the hf_helpers module and its three-tier fallback approach for loading MapAnything models from HuggingFace or local sources', 'convert MapAnything predictions dict to a trimesh Scene with 3D mesh, point cloud, and camera visualization', 'create a triangular or quad mesh from image pixel coordinates with optional binary mask filtering', 'triangulate polygonal mesh faces into triangles using distance-based or fan triangulation strategies', 'remove unreferenced vertices from a mesh and remap face indices to keep only used vertices', 'segment sky regions from an image using an ONNX model and save the binary mask to disk']
```

Usage

```
{'get_header_html': 'generate the main header HTML with logo and title for the MapAnything Gradio interface', 'get_description_html': 'generate the main description and getting started HTML for the MapAnything Gradio interface', 'get_acknowledgements_html': 'generate the acknowledgements section HTML with links to MoGe and VGGT projects', 'get_gradio_theme': 'get the configured Gradio theme with orange primary hue and amber secondary hue', 'GRADIO_CSS': 'use the CSS styles string for customizing the MapAnything Gradio interface appearance'}
```

## File: facebookresearch_map-anything/mapanything/utils/hf_utils/hf_helpers.py

Prompts

```
['generate the main header HTML with logo and title for the MapAnything Gradio interface', 'generate the main description and getting started HTML for the MapAnything Gradio interface', 'generate the acknowledgements section HTML with links to MoGe and VGGT projects', 'get the configured Gradio theme with orange primary hue and amber secondary hue', 'use the CSS styles string for customizing the MapAnything Gradio interface appearance', 'initialize a MapAnything model from a HuggingFace repository with three-tier fallback using a high-level config dict and device', 'initialize a MapAnything model entirely from local config and checkpoint files without HuggingFace Hub access', 'load a HuggingFace access token from environment variables HF_TOKEN or HUGGING_FACE_HUB_TOKEN', 'initialize a Hydra configuration from a YAML config file path with optional override strings', 'review the hf_helpers module and its three-tier fallback approach for loading MapAnything models from HuggingFace or local sources', 'convert MapAnything predictions dict to a trimesh Scene with 3D mesh, point cloud, and camera visualization', 'create a triangular or quad mesh from image pixel coordinates with optional binary mask filtering', 'triangulate polygonal mesh faces into triangles using distance-based or fan triangulation strategies', 'remove unreferenced vertices from a mesh and remap face indices to keep only used vertices', 'segment sky regions from an image using an ONNX model and save the binary mask to disk']
```

Usage

```
{'initialize_mapanything_model_from_hf': 'initialize a MapAnything model from a HuggingFace repository with three-tier fallback using a high-level config dict and device', 'initialize_mapanything_local_from_checkpoint': 'initialize a MapAnything model entirely from local config and checkpoint files without HuggingFace Hub access', 'load_hf_token_from_env': 'load a HuggingFace access token from environment variables HF_TOKEN or HUGGING_FACE_HUB_TOKEN', 'init_hydra_config_from_path': 'initialize a Hydra configuration from a YAML config file path with optional override strings', 'review_hf_helpers_model_loading': 'review the hf_helpers module and its three-tier fallback approach for loading MapAnything models from HuggingFace or local sources'}
```

## File: facebookresearch_map-anything/mapanything/utils/hf_utils/viz.py

Prompts

```
['generate the main header HTML with logo and title for the MapAnything Gradio interface', 'generate the main description and getting started HTML for the MapAnything Gradio interface', 'generate the acknowledgements section HTML with links to MoGe and VGGT projects', 'get the configured Gradio theme with orange primary hue and amber secondary hue', 'use the CSS styles string for customizing the MapAnything Gradio interface appearance', 'initialize a MapAnything model from a HuggingFace repository with three-tier fallback using a high-level config dict and device', 'initialize a MapAnything model entirely from local config and checkpoint files without HuggingFace Hub access', 'load a HuggingFace access token from environment variables HF_TOKEN or HUGGING_FACE_HUB_TOKEN', 'initialize a Hydra configuration from a YAML config file path with optional override strings', 'review the hf_helpers module and its three-tier fallback approach for loading MapAnything models from HuggingFace or local sources', 'convert MapAnything predictions dict to a trimesh Scene with 3D mesh, point cloud, and camera visualization', 'create a triangular or quad mesh from image pixel coordinates with optional binary mask filtering', 'triangulate polygonal mesh faces into triangles using distance-based or fan triangulation strategies', 'remove unreferenced vertices from a mesh and remap face indices to keep only used vertices', 'segment sky regions from an image using an ONNX model and save the binary mask to disk']
```

Usage

```
{'predictions_to_glb': 'convert MapAnything predictions dict to a trimesh Scene with 3D mesh, point cloud, and camera visualization', 'image_mesh': 'create a triangular or quad mesh from image pixel coordinates with optional binary mask filtering', 'triangulate': 'triangulate polygonal mesh faces into triangles using distance-based or fan triangulation strategies', 'remove_unreferenced_vertices': 'remove unreferenced vertices from a mesh and remap face indices to keep only used vertices', 'segment_sky': 'segment sky regions from an image using an ONNX model and save the binary mask to disk'}
```

