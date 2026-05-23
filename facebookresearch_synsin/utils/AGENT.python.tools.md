# Agent Python Tools

- repo: facebookresearch/synsin
- repo_uri: https://github.com/facebookresearch/synsin

## File: facebookresearch_synsin/utils/geometry.py

Prompts

```
['compute the angular and translational difference between two 3x4 transformation matrices', 'compare two camera poses by calculating their relative rotation angle and translation distance', 'evaluate the difference between two 4x4 transformation matrices in degrees and Euclidean distance', 'calculate the relative pose between two matrices including rotation angle and translation magnitude', 'measure the deviation between two transformation matrices in terms of rotation and translation', 'run jitter_quaternions to add random rotational noise to a quaternion with a configurable angle', 'test jitter_quaternions by passing a quaternion and random number generator to verify noisy output', 'refactor jitter_quaternions to support vectorized input of multiple quaternions at once', 'review jitter_quaternions to understand how Euler angle jitter is applied per axis', 'summarize jitter_quaternions which converts a quaternion to Euler angles, adds random noise, and converts back']
```

Usage

```
{'get_deltas_compute_angle_and_translation': 'compute the angular and translational difference between two 3x4 transformation matrices', 'get_deltas_compare_poses': 'compare two camera poses by calculating their relative rotation angle and translation distance', 'get_deltas_evaluate_transforms': 'evaluate the difference between two 4x4 transformation matrices in degrees and Euclidean distance', 'get_deltas_calculate_relative_pose': 'calculate the relative pose between two matrices including rotation angle and translation magnitude', 'get_deltas_measure_transform_deviation': 'measure the deviation between two transformation matrices in terms of rotation and translation'}
```

## File: facebookresearch_synsin/utils/jitter.py

Prompts

```
['compute the angular and translational difference between two 3x4 transformation matrices', 'compare two camera poses by calculating their relative rotation angle and translation distance', 'evaluate the difference between two 4x4 transformation matrices in degrees and Euclidean distance', 'calculate the relative pose between two matrices including rotation angle and translation magnitude', 'measure the deviation between two transformation matrices in terms of rotation and translation', 'run jitter_quaternions to add random rotational noise to a quaternion with a configurable angle', 'test jitter_quaternions by passing a quaternion and random number generator to verify noisy output', 'refactor jitter_quaternions to support vectorized input of multiple quaternions at once', 'review jitter_quaternions to understand how Euler angle jitter is applied per axis', 'summarize jitter_quaternions which converts a quaternion to Euler angles, adds random noise, and converts back']
```

Usage

```
{'run_jitter_quaternions': 'run jitter_quaternions to add random rotational noise to a quaternion with a configurable angle', 'test_jitter_quaternions': 'test jitter_quaternions by passing a quaternion and random number generator to verify noisy output', 'refactor_jitter_quaternions': 'refactor jitter_quaternions to support vectorized input of multiple quaternions at once', 'review_jitter_quaternions': 'review jitter_quaternions to understand how Euler angle jitter is applied per axis', 'summarize_jitter_quaternions': 'summarize jitter_quaternions which converts a quaternion to Euler angles, adds random noise, and converts back'}
```

