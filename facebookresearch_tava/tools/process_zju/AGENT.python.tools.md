# Agent Python Tools

- repo: facebookresearch/tava
- repo_uri: https://github.com/facebookresearch/tava

## File: facebookresearch_tava/tools/process_zju/body_model.py

Prompts

```
['create an SMPLlayer instance from a SMPL model pkl file path with a specified gender', 'run the SMPLlayer forward pass with poses and shapes to get vertices and joints', 'test the to_tensor function to convert a numpy array to a PyTorch tensor', 'test the to_np function to convert a scipy sparse matrix or array to numpy', 'review the SMPLlayer forward method to understand how vertices and joints are computed', 'run SMPL linear blend skinning to compute posed vertices and joint locations from shape and pose parameters', 'run blend shape calculation to compute vertex displacements from shape betas and shape displacement directions', 'run joint regression to compute joint locations from mesh vertices using a joint regressor matrix', 'run conversion of rotation matrices and translation vectors to 4x4 SE(4) transformation matrices', 'run forward kinematics to compute posed joint locations and bone transformations along a kinematic chain', 'run the cli function to process SMPL pose data for a given ZJU subject ID', 'run the main module to process SMPL pose data for all nine ZJU subjects', 'load rest pose vertices, joints, and bone transforms for a ZJU subject using SMPL', 'load pose vertices, joints, transforms, and parameters for a specific frame of a ZJU subject', 'review the cli function that processes ZJU subject data and saves pose_data.pt files']
```

Usage

```
{'create_SMPLlayer': 'create an SMPLlayer instance from a SMPL model pkl file path with a specified gender', 'run_SMPLlayer_forward': 'run the SMPLlayer forward pass with poses and shapes to get vertices and joints', 'test_to_tensor': 'test the to_tensor function to convert a numpy array to a PyTorch tensor', 'test_to_np': 'test the to_np function to convert a scipy sparse matrix or array to numpy', 'review_SMPLlayer_forward': 'review the SMPLlayer forward method to understand how vertices and joints are computed'}
```

## File: facebookresearch_tava/tools/process_zju/lbs.py

Prompts

```
['create an SMPLlayer instance from a SMPL model pkl file path with a specified gender', 'run the SMPLlayer forward pass with poses and shapes to get vertices and joints', 'test the to_tensor function to convert a numpy array to a PyTorch tensor', 'test the to_np function to convert a scipy sparse matrix or array to numpy', 'review the SMPLlayer forward method to understand how vertices and joints are computed', 'run SMPL linear blend skinning to compute posed vertices and joint locations from shape and pose parameters', 'run blend shape calculation to compute vertex displacements from shape betas and shape displacement directions', 'run joint regression to compute joint locations from mesh vertices using a joint regressor matrix', 'run conversion of rotation matrices and translation vectors to 4x4 SE(4) transformation matrices', 'run forward kinematics to compute posed joint locations and bone transformations along a kinematic chain', 'run the cli function to process SMPL pose data for a given ZJU subject ID', 'run the main module to process SMPL pose data for all nine ZJU subjects', 'load rest pose vertices, joints, and bone transforms for a ZJU subject using SMPL', 'load pose vertices, joints, transforms, and parameters for a specific frame of a ZJU subject', 'review the cli function that processes ZJU subject data and saves pose_data.pt files']
```

Usage

```
{'run_lbs_skinning': 'run SMPL linear blend skinning to compute posed vertices and joint locations from shape and pose parameters', 'run_blend_shapes': 'run blend shape calculation to compute vertex displacements from shape betas and shape displacement directions', 'run_vertices2joints': 'run joint regression to compute joint locations from mesh vertices using a joint regressor matrix', 'run_to_se4': 'run conversion of rotation matrices and translation vectors to 4x4 SE(4) transformation matrices', 'run_batch_rigid_transform': 'run forward kinematics to compute posed joint locations and bone transformations along a kinematic chain'}
```

## File: facebookresearch_tava/tools/process_zju/main.py

Prompts

```
['create an SMPLlayer instance from a SMPL model pkl file path with a specified gender', 'run the SMPLlayer forward pass with poses and shapes to get vertices and joints', 'test the to_tensor function to convert a numpy array to a PyTorch tensor', 'test the to_np function to convert a scipy sparse matrix or array to numpy', 'review the SMPLlayer forward method to understand how vertices and joints are computed', 'run SMPL linear blend skinning to compute posed vertices and joint locations from shape and pose parameters', 'run blend shape calculation to compute vertex displacements from shape betas and shape displacement directions', 'run joint regression to compute joint locations from mesh vertices using a joint regressor matrix', 'run conversion of rotation matrices and translation vectors to 4x4 SE(4) transformation matrices', 'run forward kinematics to compute posed joint locations and bone transformations along a kinematic chain', 'run the cli function to process SMPL pose data for a given ZJU subject ID', 'run the main module to process SMPL pose data for all nine ZJU subjects', 'load rest pose vertices, joints, and bone transforms for a ZJU subject using SMPL', 'load pose vertices, joints, transforms, and parameters for a specific frame of a ZJU subject', 'review the cli function that processes ZJU subject data and saves pose_data.pt files']
```

Usage

```
{'run_cli_process_subject': 'run the cli function to process SMPL pose data for a given ZJU subject ID', 'run_main_process_all_subjects': 'run the main module to process SMPL pose data for all nine ZJU subjects', 'load_rest_pose_info': 'load rest pose vertices, joints, and bone transforms for a ZJU subject using SMPL', 'load_pose_info': 'load pose vertices, joints, transforms, and parameters for a specific frame of a ZJU subject', 'review_cli_smpl_processing': 'review the cli function that processes ZJU subject data and saves pose_data.pt files'}
```

