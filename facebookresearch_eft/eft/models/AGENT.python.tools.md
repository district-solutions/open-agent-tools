# Agent Python Tools

- repo: facebookresearch/eft
- repo_uri: https://github.com/facebookresearch/eft

## File: facebookresearch_eft/eft/models/hmr.py

Prompts

```
['build an HMR model with ResNet50 backbone using the hmr factory function and smpl_mean_params path', 'run the HMR model forward pass on an image tensor to predict pose, shape, and camera parameters', 'create a Bottleneck residual block with configurable inplanes, planes, stride, and downsample for ResNet layers', 'test the HMR forward pass that converts 6D pose predictions to 3x3 rotation matrices via rot6d_to_rotmat', 'review the HMR iterative regression loop that refines pose, shape, and camera predictions over n_iter steps', 'build a SMPL_19 model that reorders SMPL45 joints to OpenPose18 format via forward pass', 'build a SMPL model that regresses extra joints from mesh vertices using J_regressor_extra', 'review the SMPL_19 forward method that remaps 45 SMPL joints to 19 OpenPose joints', 'review the SMPL forward method that concatenates original and extra joints then remaps them', 'summarize the SMPL and SMPL_19 classes that extend smplx SMPL for custom joint outputs']
```

Usage

```
{'build_hmr_model': 'build an HMR model with ResNet50 backbone using the hmr factory function and smpl_mean_params path', 'run_hmr_forward': 'run the HMR model forward pass on an image tensor to predict pose, shape, and camera parameters', 'create_bottleneck_block': 'create a Bottleneck residual block with configurable inplanes, planes, stride, and downsample for ResNet layers', 'test_hmr_rot6d_to_rotmat': 'test the HMR forward pass that converts 6D pose predictions to 3x3 rotation matrices via rot6d_to_rotmat', 'review_hmr_iterative_regression': 'review the HMR iterative regression loop that refines pose, shape, and camera predictions over n_iter steps'}
```

## File: facebookresearch_eft/eft/models/smpl.py

Prompts

```
['build an HMR model with ResNet50 backbone using the hmr factory function and smpl_mean_params path', 'run the HMR model forward pass on an image tensor to predict pose, shape, and camera parameters', 'create a Bottleneck residual block with configurable inplanes, planes, stride, and downsample for ResNet layers', 'test the HMR forward pass that converts 6D pose predictions to 3x3 rotation matrices via rot6d_to_rotmat', 'review the HMR iterative regression loop that refines pose, shape, and camera predictions over n_iter steps', 'build a SMPL_19 model that reorders SMPL45 joints to OpenPose18 format via forward pass', 'build a SMPL model that regresses extra joints from mesh vertices using J_regressor_extra', 'review the SMPL_19 forward method that remaps 45 SMPL joints to 19 OpenPose joints', 'review the SMPL forward method that concatenates original and extra joints then remaps them', 'summarize the SMPL and SMPL_19 classes that extend smplx SMPL for custom joint outputs']
```

Usage

```
{'build_SMPL_19_model': 'build a SMPL_19 model that reorders SMPL45 joints to OpenPose18 format via forward pass', 'build_SMPL_model': 'build a SMPL model that regresses extra joints from mesh vertices using J_regressor_extra', 'review_SMPL_19_forward': 'review the SMPL_19 forward method that remaps 45 SMPL joints to 19 OpenPose joints', 'review_SMPL_forward': 'review the SMPL forward method that concatenates original and extra joints then remaps them', 'summarize_SMPL_classes': 'summarize the SMPL and SMPL_19 classes that extend smplx SMPL for custom joint outputs'}
```

