# Agent Python Tools

- repo: facebookresearch/eft
- repo_uri: https://github.com/facebookresearch/eft

## File: facebookresearch_eft/bodymocap/models/body_models.py

Prompts

```
['create an SMPL body model from a model path with configurable betas and pose parameters', 'create an SMPLH body model with hand pose PCA components and left and right hand joints', 'create an SMPLX expressive body model with face expression coefficients jaw and eye poses', 'run the SMPL forward pass to compute mesh vertices and joints from pose and shape parameters', 'use the create factory function to instantiate SMPL SMPLH or SMPLX models by type and path', 'build an HMR model with ResNet50 backbone for human mesh recovery from images', 'create a Bottleneck residual block for use in ResNet-style convolutional neural networks', 'run a forward pass through the HMR model to predict pose, shape, and camera parameters', 'test the HMR model construction with custom SMPL mean parameters and iteration count', 'review the HMR iterative regression loop that refines pose, shape, and camera predictions', 'build a python module to instantiate an SMPL body model with extra joint regressors and run forward pass', 'build a python module to instantiate an SMPLX body model with hand joints and run forward pass', 'test the SMPL class forward method to compute vertices, joints, and pose from body parameters', 'test the SMPLX class forward method to compute body joints plus left and right hand joints', 'review the SMPL class joint mapping logic that combines base joints with extra regressor joints']
```

Usage

```
{'create_smpl_model': 'create an SMPL body model from a model path with configurable betas and pose parameters', 'create_smplh_model': 'create an SMPLH body model with hand pose PCA components and left and right hand joints', 'create_smplx_model': 'create an SMPLX expressive body model with face expression coefficients jaw and eye poses', 'forward_smpl_vertices': 'run the SMPL forward pass to compute mesh vertices and joints from pose and shape parameters', 'factory_create_model': 'use the create factory function to instantiate SMPL SMPLH or SMPLX models by type and path'}
```

## File: facebookresearch_eft/bodymocap/models/hmr.py

Prompts

```
['create an SMPL body model from a model path with configurable betas and pose parameters', 'create an SMPLH body model with hand pose PCA components and left and right hand joints', 'create an SMPLX expressive body model with face expression coefficients jaw and eye poses', 'run the SMPL forward pass to compute mesh vertices and joints from pose and shape parameters', 'use the create factory function to instantiate SMPL SMPLH or SMPLX models by type and path', 'build an HMR model with ResNet50 backbone for human mesh recovery from images', 'create a Bottleneck residual block for use in ResNet-style convolutional neural networks', 'run a forward pass through the HMR model to predict pose, shape, and camera parameters', 'test the HMR model construction with custom SMPL mean parameters and iteration count', 'review the HMR iterative regression loop that refines pose, shape, and camera predictions', 'build a python module to instantiate an SMPL body model with extra joint regressors and run forward pass', 'build a python module to instantiate an SMPLX body model with hand joints and run forward pass', 'test the SMPL class forward method to compute vertices, joints, and pose from body parameters', 'test the SMPLX class forward method to compute body joints plus left and right hand joints', 'review the SMPL class joint mapping logic that combines base joints with extra regressor joints']
```

Usage

```
{'build_hmr_model': 'build an HMR model with ResNet50 backbone for human mesh recovery from images', 'create_bottleneck_block': 'create a Bottleneck residual block for use in ResNet-style convolutional neural networks', 'run_hmr_forward_pass': 'run a forward pass through the HMR model to predict pose, shape, and camera parameters', 'test_hmr_model_construction': 'test the HMR model construction with custom SMPL mean parameters and iteration count', 'review_hmr_iterative_regression': 'review the HMR iterative regression loop that refines pose, shape, and camera predictions'}
```

## File: facebookresearch_eft/bodymocap/models/smpl.py

Prompts

```
['create an SMPL body model from a model path with configurable betas and pose parameters', 'create an SMPLH body model with hand pose PCA components and left and right hand joints', 'create an SMPLX expressive body model with face expression coefficients jaw and eye poses', 'run the SMPL forward pass to compute mesh vertices and joints from pose and shape parameters', 'use the create factory function to instantiate SMPL SMPLH or SMPLX models by type and path', 'build an HMR model with ResNet50 backbone for human mesh recovery from images', 'create a Bottleneck residual block for use in ResNet-style convolutional neural networks', 'run a forward pass through the HMR model to predict pose, shape, and camera parameters', 'test the HMR model construction with custom SMPL mean parameters and iteration count', 'review the HMR iterative regression loop that refines pose, shape, and camera predictions', 'build a python module to instantiate an SMPL body model with extra joint regressors and run forward pass', 'build a python module to instantiate an SMPLX body model with hand joints and run forward pass', 'test the SMPL class forward method to compute vertices, joints, and pose from body parameters', 'test the SMPLX class forward method to compute body joints plus left and right hand joints', 'review the SMPL class joint mapping logic that combines base joints with extra regressor joints']
```

Usage

```
{'build_smpl_model': 'build a python module to instantiate an SMPL body model with extra joint regressors and run forward pass', 'build_smplx_model': 'build a python module to instantiate an SMPLX body model with hand joints and run forward pass', 'test_smpl_forward': 'test the SMPL class forward method to compute vertices, joints, and pose from body parameters', 'test_smplx_forward': 'test the SMPLX class forward method to compute body joints plus left and right hand joints', 'review_smpl_joint_mapping': 'review the SMPL class joint mapping logic that combines base joints with extra regressor joints'}
```

