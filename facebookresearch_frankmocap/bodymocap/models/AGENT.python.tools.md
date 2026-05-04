# Agent Python Tools

- repo: facebookresearch/frankmocap
- repo_uri: https://github.com/facebookresearch/frankmocap

## File: facebookresearch_frankmocap/bodymocap/models/hmr.py

Prompts

```
['build an HMR model with ResNet50 backbone for SMPL human mesh recovery from images', 'create a Bottleneck residual block with 1x1, 3x3, 1x1 convolutions and batch normalization', 'run a forward pass through HMR to predict pose, shape, and camera parameters iteratively', 'test the hmr factory function to construct a pretrained ResNet50-based HMR model', 'review the HMR forward method iterative regression loop that refines pose, shape, and camera predictions', 'create an SMPL body model instance with extra joint regressor support for 33 joints', 'run the SMPL model forward pass to compute vertices and joints from pose and beta parameters', 'create an SMPLX body model instance with hand joints and extra joint regressor support', 'run the SMPLX model forward pass to compute vertices, body joints, and left and right hand joints', 'review the ModelOutput namedtuple fields including vertices, joints, full_pose, betas, and hand joints']
```

Usage

```
{'build_hmr_model': 'build an HMR model with ResNet50 backbone for SMPL human mesh recovery from images', 'create_bottleneck_block': 'create a Bottleneck residual block with 1x1, 3x3, 1x1 convolutions and batch normalization', 'run_forward_pass': 'run a forward pass through HMR to predict pose, shape, and camera parameters iteratively', 'test_hmr_factory': 'test the hmr factory function to construct a pretrained ResNet50-based HMR model', 'review_forward_iteration': 'review the HMR forward method iterative regression loop that refines pose, shape, and camera predictions'}
```

## File: facebookresearch_frankmocap/bodymocap/models/smpl.py

Prompts

```
['build an HMR model with ResNet50 backbone for SMPL human mesh recovery from images', 'create a Bottleneck residual block with 1x1, 3x3, 1x1 convolutions and batch normalization', 'run a forward pass through HMR to predict pose, shape, and camera parameters iteratively', 'test the hmr factory function to construct a pretrained ResNet50-based HMR model', 'review the HMR forward method iterative regression loop that refines pose, shape, and camera predictions', 'create an SMPL body model instance with extra joint regressor support for 33 joints', 'run the SMPL model forward pass to compute vertices and joints from pose and beta parameters', 'create an SMPLX body model instance with hand joints and extra joint regressor support', 'run the SMPLX model forward pass to compute vertices, body joints, and left and right hand joints', 'review the ModelOutput namedtuple fields including vertices, joints, full_pose, betas, and hand joints']
```

Usage

```
{'create_smpl_model': 'create an SMPL body model instance with extra joint regressor support for 33 joints', 'run_smpl_forward': 'run the SMPL model forward pass to compute vertices and joints from pose and beta parameters', 'create_smplx_model': 'create an SMPLX body model instance with hand joints and extra joint regressor support', 'run_smplx_forward': 'run the SMPLX model forward pass to compute vertices, body joints, and left and right hand joints', 'review_modeloutput_namedtuple': 'review the ModelOutput namedtuple fields including vertices, joints, full_pose, betas, and hand joints'}
```

