# Agent Python Tools

- repo: facebookresearch/mcc
- repo_uri: https://github.com/facebookresearch/mcc

## File: facebookresearch_mcc/scripts/prepare_hypersim.py

Prompts

```
['run the prepare_hypersim script with --hypersim_path to preprocess Hypersim dataset into train and val ground truth files', 'run load_scene_names to extract and filter scene names from the Hypersim metadata CSV by train or test split', 'refactor the main function to change the bilinear interpolation resolution from 112x112 to a configurable size', 'review the load_scene_names function CSV parsing logic for edge cases like missing fields or malformed lines', 'summarize the main function pipeline that loads XYZ geometry and RGB images, interpolates, concatenates, and saves as PyTorch tensors']
```

Usage

```
{'run_prepare_hypersim': 'run the prepare_hypersim script with --hypersim_path to preprocess Hypersim dataset into train and val ground truth files', 'run_load_scene_names': 'run load_scene_names to extract and filter scene names from the Hypersim metadata CSV by train or test split', 'refactor_main_interpolation': 'refactor the main function to change the bilinear interpolation resolution from 112x112 to a configurable size', 'review_load_scene_names_csv_parsing': 'review the load_scene_names function CSV parsing logic for edge cases like missing fields or malformed lines', 'summarize_main_gt_pipeline': 'summarize the main function pipeline that loads XYZ geometry and RGB images, interpolates, concatenates, and saves as PyTorch tensors'}
```

