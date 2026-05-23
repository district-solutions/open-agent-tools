# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/theseus/utils/examples/bundle_adjustment/data.py

Prompts

```
['generate a synthetic bundle adjustment dataset with random cameras, points, and observations', 'load a BUNDLE file and return cameras, points, and observations lists', 'save cameras, points, and observations to a BUNDLE format file on disk', 'project a 3D point through a camera pose to get 2D image coordinates', 'compute a reprojection error histogram string for a bundle adjustment problem', 'create a function that computes the Cauchy soft loss value and derivative for a given tensor and radius', 'create a function that computes the Huber-like soft loss value and derivative for a given tensor and radius', 'generate a uniformly random 3D point on the 2-sphere using spherical coordinate sampling', 'generate a uniformly random 4D point on the 3-sphere using Marsaglia sampling', 'generate a random quaternion with rotation angle bounded between min and max degrees']
```

Usage

```
{'generate_synthetic_bundle_adjustment_dataset': 'generate a synthetic bundle adjustment dataset with random cameras, points, and observations', 'load_bal_dataset_from_file': 'load a BUNDLE file and return cameras, points, and observations lists', 'save_bundle_adjustment_to_bal_file': 'save cameras, points, and observations to a BUNDLE format file on disk', 'project_3d_point_to_image': 'project a 3D point through a camera pose to get 2D image coordinates', 'compute_bundle_adjustment_histogram': 'compute a reprojection error histogram string for a bundle adjustment problem'}
```

## File: facebookresearch_theseus/theseus/utils/examples/bundle_adjustment/util.py

Prompts

```
['generate a synthetic bundle adjustment dataset with random cameras, points, and observations', 'load a BUNDLE file and return cameras, points, and observations lists', 'save cameras, points, and observations to a BUNDLE format file on disk', 'project a 3D point through a camera pose to get 2D image coordinates', 'compute a reprojection error histogram string for a bundle adjustment problem', 'create a function that computes the Cauchy soft loss value and derivative for a given tensor and radius', 'create a function that computes the Huber-like soft loss value and derivative for a given tensor and radius', 'generate a uniformly random 3D point on the 2-sphere using spherical coordinate sampling', 'generate a uniformly random 4D point on the 3-sphere using Marsaglia sampling', 'generate a random quaternion with rotation angle bounded between min and max degrees']
```

Usage

```
{'create_soft_loss_cauchy': 'create a function that computes the Cauchy soft loss value and derivative for a given tensor and radius', 'create_soft_loss_huber_like': 'create a function that computes the Huber-like soft loss value and derivative for a given tensor and radius', 'generate_random_s2_point': 'generate a uniformly random 3D point on the 2-sphere using spherical coordinate sampling', 'generate_random_s3_point': 'generate a uniformly random 4D point on the 3-sphere using Marsaglia sampling', 'generate_random_small_quaternion': 'generate a random quaternion with rotation angle bounded between min and max degrees'}
```

