# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/core/anchor/builder.py

Prompts

```
['build a prior generator from a config dict using the PRIOR_GENERATORS registry', 'build an anchor generator from a config dict using the deprecated build_anchor_generator function', 'register a new anchor or points generator class with the PRIOR_GENERATORS registry', 'review the PRIOR_GENERATORS registry to list all registered anchor and points generator types', 'refactor code that uses build_anchor_generator to use build_prior_generator instead', 'build a multi-level point generator for 2D points-based detectors with configurable strides and offset', 'create grid points across multiple feature map levels with optional stride concatenation', 'generate grid points for a single feature map level with specified size and stride', 'compute valid flags for points across multiple feature levels based on padded image shape', 'generate sparse points from prior indices for a specific feature map level']
```

Usage

```
{'build_prior_generator': 'build a prior generator from a config dict using the PRIOR_GENERATORS registry', 'build_anchor_generator': 'build an anchor generator from a config dict using the deprecated build_anchor_generator function', 'register_prior_generator': 'register a new anchor or points generator class with the PRIOR_GENERATORS registry', 'review_PRIOR_GENERATORS': 'review the PRIOR_GENERATORS registry to list all registered anchor and points generator types', 'refactor_build_anchor_generator': 'refactor code that uses build_anchor_generator to use build_prior_generator instead'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/core/anchor/point_generator.py

Prompts

```
['build a prior generator from a config dict using the PRIOR_GENERATORS registry', 'build an anchor generator from a config dict using the deprecated build_anchor_generator function', 'register a new anchor or points generator class with the PRIOR_GENERATORS registry', 'review the PRIOR_GENERATORS registry to list all registered anchor and points generator types', 'refactor code that uses build_anchor_generator to use build_prior_generator instead', 'build a multi-level point generator for 2D points-based detectors with configurable strides and offset', 'create grid points across multiple feature map levels with optional stride concatenation', 'generate grid points for a single feature map level with specified size and stride', 'compute valid flags for points across multiple feature levels based on padded image shape', 'generate sparse points from prior indices for a specific feature map level']
```

Usage

```
{'build_MlvlPointGenerator': 'build a multi-level point generator for 2D points-based detectors with configurable strides and offset', 'create_grid_priors': 'create grid points across multiple feature map levels with optional stride concatenation', 'generate_single_level_grid_priors': 'generate grid points for a single feature map level with specified size and stride', 'compute_valid_flags': 'compute valid flags for points across multiple feature levels based on padded image shape', 'generate_sparse_priors': 'generate sparse points from prior indices for a specific feature map level'}
```

