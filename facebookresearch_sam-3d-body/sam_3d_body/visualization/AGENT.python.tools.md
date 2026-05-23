# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/visualization/renderer.py

Prompts

```
['create a Renderer instance with a focal length and optional mesh faces for 3D rendering', 'call the Renderer to overlay a 3D mesh onto an input image with camera translation', 'render a 3D mesh as RGBA output with configurable camera position, rotation, and scene background', 'render multiple 3D meshes with different colors and camera translations in a single RGBA image', 'create a list of pyrender directional light nodes arranged in a Raymond lighting setup', 'create a SkeletonVisualizer instance with custom keypoint colors, link colors, and line width', 'call set_pose_meta to configure skeleton links and keypoint colors from a pose metadata dict', 'draw keypoints and skeleton links on an image using draw_skeleton with a confidence threshold', 'draw skeleton analysis with green for correct and red for incorrect keypoints using draw_skeleton_analysis', 'review the SkeletonVisualizer class to understand how keypoints and skeleton links are rendered on images', 'draw text on a numpy image array at specified x,y positions with configurable font size and color', 'draw a bounding box rectangle on an image with an optional multi-line text label overlay', 'parse a pose dataset metainfo dict into keypoint names, skeleton links, flip pairs, and colors', 'parse a pose dataset metainfo config file path into structured keypoint and skeleton metadata', 'review the parse_pose_metainfo function to understand how keypoint flip indices and skeleton links are mapped']
```

Usage

```
{'create_renderer_instance': 'create a Renderer instance with a focal length and optional mesh faces for 3D rendering', 'render_mesh_on_image': 'call the Renderer to overlay a 3D mesh onto an input image with camera translation', 'render_rgba_mesh': 'render a 3D mesh as RGBA output with configurable camera position, rotation, and scene background', 'render_multiple_meshes_rgba': 'render multiple 3D meshes with different colors and camera translations in a single RGBA image', 'create_raymond_lights': 'create a list of pyrender directional light nodes arranged in a Raymond lighting setup'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/visualization/skeleton_visualizer.py

Prompts

```
['create a Renderer instance with a focal length and optional mesh faces for 3D rendering', 'call the Renderer to overlay a 3D mesh onto an input image with camera translation', 'render a 3D mesh as RGBA output with configurable camera position, rotation, and scene background', 'render multiple 3D meshes with different colors and camera translations in a single RGBA image', 'create a list of pyrender directional light nodes arranged in a Raymond lighting setup', 'create a SkeletonVisualizer instance with custom keypoint colors, link colors, and line width', 'call set_pose_meta to configure skeleton links and keypoint colors from a pose metadata dict', 'draw keypoints and skeleton links on an image using draw_skeleton with a confidence threshold', 'draw skeleton analysis with green for correct and red for incorrect keypoints using draw_skeleton_analysis', 'review the SkeletonVisualizer class to understand how keypoints and skeleton links are rendered on images', 'draw text on a numpy image array at specified x,y positions with configurable font size and color', 'draw a bounding box rectangle on an image with an optional multi-line text label overlay', 'parse a pose dataset metainfo dict into keypoint names, skeleton links, flip pairs, and colors', 'parse a pose dataset metainfo config file path into structured keypoint and skeleton metadata', 'review the parse_pose_metainfo function to understand how keypoint flip indices and skeleton links are mapped']
```

Usage

```
{'create_skeleton_visualizer': 'create a SkeletonVisualizer instance with custom keypoint colors, link colors, and line width', 'set_pose_meta': 'call set_pose_meta to configure skeleton links and keypoint colors from a pose metadata dict', 'draw_skeleton': 'draw keypoints and skeleton links on an image using draw_skeleton with a confidence threshold', 'draw_skeleton_analysis': 'draw skeleton analysis with green for correct and red for incorrect keypoints using draw_skeleton_analysis', 'review_SkeletonVisualizer': 'review the SkeletonVisualizer class to understand how keypoints and skeleton links are rendered on images'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/visualization/utils.py

Prompts

```
['create a Renderer instance with a focal length and optional mesh faces for 3D rendering', 'call the Renderer to overlay a 3D mesh onto an input image with camera translation', 'render a 3D mesh as RGBA output with configurable camera position, rotation, and scene background', 'render multiple 3D meshes with different colors and camera translations in a single RGBA image', 'create a list of pyrender directional light nodes arranged in a Raymond lighting setup', 'create a SkeletonVisualizer instance with custom keypoint colors, link colors, and line width', 'call set_pose_meta to configure skeleton links and keypoint colors from a pose metadata dict', 'draw keypoints and skeleton links on an image using draw_skeleton with a confidence threshold', 'draw skeleton analysis with green for correct and red for incorrect keypoints using draw_skeleton_analysis', 'review the SkeletonVisualizer class to understand how keypoints and skeleton links are rendered on images', 'draw text on a numpy image array at specified x,y positions with configurable font size and color', 'draw a bounding box rectangle on an image with an optional multi-line text label overlay', 'parse a pose dataset metainfo dict into keypoint names, skeleton links, flip pairs, and colors', 'parse a pose dataset metainfo config file path into structured keypoint and skeleton metadata', 'review the parse_pose_metainfo function to understand how keypoint flip indices and skeleton links are mapped']
```

Usage

```
{'draw_text_on_image': 'draw text on a numpy image array at specified x,y positions with configurable font size and color', 'draw_bbox_with_label': 'draw a bounding box rectangle on an image with an optional multi-line text label overlay', 'parse_pose_metainfo_from_dict': 'parse a pose dataset metainfo dict into keypoint names, skeleton links, flip pairs, and colors', 'parse_pose_metainfo_from_file': 'parse a pose dataset metainfo config file path into structured keypoint and skeleton metadata', 'review_parse_pose_metainfo': 'review the parse_pose_metainfo function to understand how keypoint flip indices and skeleton links are mapped'}
```

