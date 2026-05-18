# Agent Python Tools

- repo: facebookresearch/mhr
- repo_uri: https://github.com/facebookresearch/mhr

## File: facebookresearch_mhr/mhr/io.py

Prompts

```
['get the default MHR asset folder path for loading model files', 'get the path to an MHR fbx file for a given LOD level', 'get the path to the MHR model definition file across all LODs', 'build a PyTorch pose correctives predictor from blendshapes and activation data', 'check if loaded data contains pose-dependent corrective blendshapes', 'load an MHR body model from asset files on disk with a specified LOD and device', 'compute mesh vertices and skeleton state from identity coefficients, model parameters, and face expression coefficients', 'create a non-linear pose correctives model that predicts corrective offsets from joint parameters', 'get the number of identity blendshapes supported by the MHR model', 'set parameter sets on a character to discriminate between identity and facial expression blendshapes', 'build a module that converts XYZ-Euler rotation vectors to 6D rotation representation using batch6DFromXYZ', 'build a module that generates a full 3x3 rotation matrix from XYZ-Euler angles using batch6DFromXYZ with return_9D', 'create a SparseLinear PyTorch module with a custom sparse mask for memory-efficient linear transformations', 'test the SparseLinear forward pass by passing input tensors and verifying sparse weight application', 'review the SparseLinear class and its Kaiming uniform initialization based on sparse fan-in']
```

Usage

```
{'get_default_asset_folder': 'get the default MHR asset folder path for loading model files', 'get_mhr_fbx_path': 'get the path to an MHR fbx file for a given LOD level', 'get_mhr_model_path': 'get the path to the MHR model definition file across all LODs', 'load_pose_dirs_predictor': 'build a PyTorch pose correctives predictor from blendshapes and activation data', 'has_pose_corrective_blendshapes': 'check if loaded data contains pose-dependent corrective blendshapes'}
```

## File: facebookresearch_mhr/mhr/mhr.py

Prompts

```
['get the default MHR asset folder path for loading model files', 'get the path to an MHR fbx file for a given LOD level', 'get the path to the MHR model definition file across all LODs', 'build a PyTorch pose correctives predictor from blendshapes and activation data', 'check if loaded data contains pose-dependent corrective blendshapes', 'load an MHR body model from asset files on disk with a specified LOD and device', 'compute mesh vertices and skeleton state from identity coefficients, model parameters, and face expression coefficients', 'create a non-linear pose correctives model that predicts corrective offsets from joint parameters', 'get the number of identity blendshapes supported by the MHR model', 'set parameter sets on a character to discriminate between identity and facial expression blendshapes', 'build a module that converts XYZ-Euler rotation vectors to 6D rotation representation using batch6DFromXYZ', 'build a module that generates a full 3x3 rotation matrix from XYZ-Euler angles using batch6DFromXYZ with return_9D', 'create a SparseLinear PyTorch module with a custom sparse mask for memory-efficient linear transformations', 'test the SparseLinear forward pass by passing input tensors and verifying sparse weight application', 'review the SparseLinear class and its Kaiming uniform initialization based on sparse fan-in']
```

Usage

```
{'load_mhr_model_from_files': 'load an MHR body model from asset files on disk with a specified LOD and device', 'forward_mhr_vertices': 'compute mesh vertices and skeleton state from identity coefficients, model parameters, and face expression coefficients', 'create_pose_correctives_model': 'create a non-linear pose correctives model that predicts corrective offsets from joint parameters', 'get_num_identity_blendshapes': 'get the number of identity blendshapes supported by the MHR model', 'set_blendshape_parameter_sets': 'set parameter sets on a character to discriminate between identity and facial expression blendshapes'}
```

## File: facebookresearch_mhr/mhr/utils.py

Prompts

```
['get the default MHR asset folder path for loading model files', 'get the path to an MHR fbx file for a given LOD level', 'get the path to the MHR model definition file across all LODs', 'build a PyTorch pose correctives predictor from blendshapes and activation data', 'check if loaded data contains pose-dependent corrective blendshapes', 'load an MHR body model from asset files on disk with a specified LOD and device', 'compute mesh vertices and skeleton state from identity coefficients, model parameters, and face expression coefficients', 'create a non-linear pose correctives model that predicts corrective offsets from joint parameters', 'get the number of identity blendshapes supported by the MHR model', 'set parameter sets on a character to discriminate between identity and facial expression blendshapes', 'build a module that converts XYZ-Euler rotation vectors to 6D rotation representation using batch6DFromXYZ', 'build a module that generates a full 3x3 rotation matrix from XYZ-Euler angles using batch6DFromXYZ with return_9D', 'create a SparseLinear PyTorch module with a custom sparse mask for memory-efficient linear transformations', 'test the SparseLinear forward pass by passing input tensors and verifying sparse weight application', 'review the SparseLinear class and its Kaiming uniform initialization based on sparse fan-in']
```

Usage

```
{'build_6D_rotation_from_xyz_euler': 'build a module that converts XYZ-Euler rotation vectors to 6D rotation representation using batch6DFromXYZ', 'build_9D_rotation_matrix_from_xyz': 'build a module that generates a full 3x3 rotation matrix from XYZ-Euler angles using batch6DFromXYZ with return_9D', 'create_sparse_linear_layer': 'create a SparseLinear PyTorch module with a custom sparse mask for memory-efficient linear transformations', 'test_SparseLinear_forward': 'test the SparseLinear forward pass by passing input tensors and verifying sparse weight application', 'review_SparseLinear_initialization': 'review the SparseLinear class and its Kaiming uniform initialization based on sparse fan-in'}
```

