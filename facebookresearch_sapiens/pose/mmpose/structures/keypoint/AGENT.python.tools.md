# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/structures/keypoint/transforms.py

Prompts

```
['flip keypoints horizontally by swapping symmetric pairs and mirroring x coordinates across image width', 'flip keypoints vertically by swapping symmetric pairs and mirroring y coordinates across image height', 'flip keypoints diagonally by swapping symmetric pairs and mirroring both x and y coordinates', 'flip human joints horizontally around a static x-axis center value using symmetric keypoint indices', "flip human joints horizontally around a root joint's x location using symmetric keypoint indices"]
```

Usage

```
{'flip_keypoints_horizontal': 'flip keypoints horizontally by swapping symmetric pairs and mirroring x coordinates across image width', 'flip_keypoints_vertical': 'flip keypoints vertically by swapping symmetric pairs and mirroring y coordinates across image height', 'flip_keypoints_diagonal': 'flip keypoints diagonally by swapping symmetric pairs and mirroring both x and y coordinates', 'flip_keypoints_custom_center_static': 'flip human joints horizontally around a static x-axis center value using symmetric keypoint indices', 'flip_keypoints_custom_center_root': "flip human joints horizontally around a root joint's x location using symmetric keypoint indices"}
```

