# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/datasets/preprocessing/stanford/stanford.py

Prompts

```
['convert Stanford3D dataset TXT files to PLY or PTH format with sparse quantization', 'read a Stanford3D TXT file and parse XYZ coordinates and RGB values into numpy arrays', 'generate train val test split TXT files for each Stanford3D area from preprocessed output', 'quantize point cloud coordinates to 1cm grid using MinkowskiEngine sparse quantization', 'map Stanford3D dataset class labels to SegCloud label indices using the label mapping dictionary']
```

Usage

```
{'convert_stanford3d_to_ply': 'convert Stanford3D dataset TXT files to PLY or PTH format with sparse quantization', 'read_txt_pointcloud': 'read a Stanford3D TXT file and parse XYZ coordinates and RGB values into numpy arrays', 'generate_area_splits': 'generate train val test split TXT files for each Stanford3D area from preprocessed output', 'quantize_pointcloud': 'quantize point cloud coordinates to 1cm grid using MinkowskiEngine sparse quantization', 'map_stanford_labels': 'map Stanford3D dataset class labels to SegCloud label indices using the label mapping dictionary'}
```

