# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/eval/depth/datasets/datasets_utils.py

Prompts

```
['create an EvalCropType enum with NYU_EIGEN and FULL crop type values for depth evaluation', 'build a valid evaluation mask for a BxCxHxW tensor using full image coverage with ignored value filtering', 'build a valid evaluation mask using NYU Eigen crop region for depth estimation on a BxCxHxW tensor', 'test make_valid_mask to correctly exclude regions where all channels equal the ignored value', 'review make_valid_mask to verify NYU Eigen crop coordinates scale proportionally to input tensor height and width']
```

Usage

```
{'create_eval_crop_type_enum': 'create an EvalCropType enum with NYU_EIGEN and FULL crop type values for depth evaluation', 'build_make_valid_mask_full': 'build a valid evaluation mask for a BxCxHxW tensor using full image coverage with ignored value filtering', 'build_make_valid_mask_nyu_eigen': 'build a valid evaluation mask using NYU Eigen crop region for depth estimation on a BxCxHxW tensor', 'test_make_valid_mask_ignored_value': 'test make_valid_mask to correctly exclude regions where all channels equal the ignored value', 'review_make_valid_mask_crop_scaling': 'review make_valid_mask to verify NYU Eigen crop coordinates scale proportionally to input tensor height and width'}
```

