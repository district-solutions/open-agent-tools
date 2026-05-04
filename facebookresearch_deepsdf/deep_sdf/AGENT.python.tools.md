# Agent Python Tools

- repo: facebookresearch/deepsdf
- repo_uri: https://github.com/facebookresearch/deepsdf

## File: facebookresearch_deepsdf/deep_sdf/data.py

Prompts

```
['get instance filenames from a data source and split configuration dictionary', 'find the single OBJ mesh file in a shape directory and raise on zero or multiple', 'remove rows with NaN values in the fourth column of a PyTorch tensor', 'unpack and randomly subsample positive and negative SDF samples from an NPZ file', 'create a PyTorch Dataset that yields subsampled SDF samples from NPZ files on disk or in RAM', 'create a 3D mesh from a DeepSDF decoder and latent vector, saving the result as a PLY file', 'convert a 3D SDF tensor into a PLY mesh file using marching cubes and save to disk', 'review the create_mesh function that samples an N x N x N voxel grid and decodes SDF values in batches', 'review the convert_sdf_samples_to_ply function that uses marching_cubes_lewiner to extract mesh vertices and faces', 'refactor the create_mesh function to adjust the max_batch parameter for GPU memory constraints', 'add debug, quiet, and log arguments to an argparse ArgumentParser for DeepSDF CLI tools', 'configure the root logger with debug, quiet, or info level and optional file output', 'decode signed distance field values from a decoder network given latent vectors and query points', 'review the add_common_args function to see what CLI arguments it adds to an ArgumentParser', 'summarize the decode_sdf function that concatenates latent vectors with queries before passing to a decoder', 'load experiment specifications from a specs.json file in the given experiment directory', 'load a trained decoder model and its epoch from a checkpoint in the experiment directory', 'build a new decoder network from experiment specifications using the specified architecture and code length', 'load latent code vectors from a checkpoint file for the given experiment directory', 'get or create the evaluation output directory path for a specific checkpoint in the experiment']
```

Usage

```
{'get_instance_filenames': 'get instance filenames from a data source and split configuration dictionary', 'find_mesh_in_directory': 'find the single OBJ mesh file in a shape directory and raise on zero or multiple', 'remove_nans': 'remove rows with NaN values in the fourth column of a PyTorch tensor', 'unpack_sdf_samples': 'unpack and randomly subsample positive and negative SDF samples from an NPZ file', 'SDFSamples': 'create a PyTorch Dataset that yields subsampled SDF samples from NPZ files on disk or in RAM'}
```

## File: facebookresearch_deepsdf/deep_sdf/mesh.py

Prompts

```
['get instance filenames from a data source and split configuration dictionary', 'find the single OBJ mesh file in a shape directory and raise on zero or multiple', 'remove rows with NaN values in the fourth column of a PyTorch tensor', 'unpack and randomly subsample positive and negative SDF samples from an NPZ file', 'create a PyTorch Dataset that yields subsampled SDF samples from NPZ files on disk or in RAM', 'create a 3D mesh from a DeepSDF decoder and latent vector, saving the result as a PLY file', 'convert a 3D SDF tensor into a PLY mesh file using marching cubes and save to disk', 'review the create_mesh function that samples an N x N x N voxel grid and decodes SDF values in batches', 'review the convert_sdf_samples_to_ply function that uses marching_cubes_lewiner to extract mesh vertices and faces', 'refactor the create_mesh function to adjust the max_batch parameter for GPU memory constraints', 'add debug, quiet, and log arguments to an argparse ArgumentParser for DeepSDF CLI tools', 'configure the root logger with debug, quiet, or info level and optional file output', 'decode signed distance field values from a decoder network given latent vectors and query points', 'review the add_common_args function to see what CLI arguments it adds to an ArgumentParser', 'summarize the decode_sdf function that concatenates latent vectors with queries before passing to a decoder', 'load experiment specifications from a specs.json file in the given experiment directory', 'load a trained decoder model and its epoch from a checkpoint in the experiment directory', 'build a new decoder network from experiment specifications using the specified architecture and code length', 'load latent code vectors from a checkpoint file for the given experiment directory', 'get or create the evaluation output directory path for a specific checkpoint in the experiment']
```

Usage

```
{'create_mesh_from_decoder': 'create a 3D mesh from a DeepSDF decoder and latent vector, saving the result as a PLY file', 'convert_sdf_samples_to_ply': 'convert a 3D SDF tensor into a PLY mesh file using marching cubes and save to disk', 'review_create_mesh': 'review the create_mesh function that samples an N x N x N voxel grid and decodes SDF values in batches', 'review_convert_sdf_samples_to_ply': 'review the convert_sdf_samples_to_ply function that uses marching_cubes_lewiner to extract mesh vertices and faces', 'refactor_create_mesh_batching': 'refactor the create_mesh function to adjust the max_batch parameter for GPU memory constraints'}
```

## File: facebookresearch_deepsdf/deep_sdf/utils.py

Prompts

```
['get instance filenames from a data source and split configuration dictionary', 'find the single OBJ mesh file in a shape directory and raise on zero or multiple', 'remove rows with NaN values in the fourth column of a PyTorch tensor', 'unpack and randomly subsample positive and negative SDF samples from an NPZ file', 'create a PyTorch Dataset that yields subsampled SDF samples from NPZ files on disk or in RAM', 'create a 3D mesh from a DeepSDF decoder and latent vector, saving the result as a PLY file', 'convert a 3D SDF tensor into a PLY mesh file using marching cubes and save to disk', 'review the create_mesh function that samples an N x N x N voxel grid and decodes SDF values in batches', 'review the convert_sdf_samples_to_ply function that uses marching_cubes_lewiner to extract mesh vertices and faces', 'refactor the create_mesh function to adjust the max_batch parameter for GPU memory constraints', 'add debug, quiet, and log arguments to an argparse ArgumentParser for DeepSDF CLI tools', 'configure the root logger with debug, quiet, or info level and optional file output', 'decode signed distance field values from a decoder network given latent vectors and query points', 'review the add_common_args function to see what CLI arguments it adds to an ArgumentParser', 'summarize the decode_sdf function that concatenates latent vectors with queries before passing to a decoder', 'load experiment specifications from a specs.json file in the given experiment directory', 'load a trained decoder model and its epoch from a checkpoint in the experiment directory', 'build a new decoder network from experiment specifications using the specified architecture and code length', 'load latent code vectors from a checkpoint file for the given experiment directory', 'get or create the evaluation output directory path for a specific checkpoint in the experiment']
```

Usage

```
{'add_common_args': 'add debug, quiet, and log arguments to an argparse ArgumentParser for DeepSDF CLI tools', 'configure_logging': 'configure the root logger with debug, quiet, or info level and optional file output', 'decode_sdf': 'decode signed distance field values from a decoder network given latent vectors and query points', 'review_add_common_args': 'review the add_common_args function to see what CLI arguments it adds to an ArgumentParser', 'summarize_decode_sdf': 'summarize the decode_sdf function that concatenates latent vectors with queries before passing to a decoder'}
```

## File: facebookresearch_deepsdf/deep_sdf/workspace.py

Prompts

```
['get instance filenames from a data source and split configuration dictionary', 'find the single OBJ mesh file in a shape directory and raise on zero or multiple', 'remove rows with NaN values in the fourth column of a PyTorch tensor', 'unpack and randomly subsample positive and negative SDF samples from an NPZ file', 'create a PyTorch Dataset that yields subsampled SDF samples from NPZ files on disk or in RAM', 'create a 3D mesh from a DeepSDF decoder and latent vector, saving the result as a PLY file', 'convert a 3D SDF tensor into a PLY mesh file using marching cubes and save to disk', 'review the create_mesh function that samples an N x N x N voxel grid and decodes SDF values in batches', 'review the convert_sdf_samples_to_ply function that uses marching_cubes_lewiner to extract mesh vertices and faces', 'refactor the create_mesh function to adjust the max_batch parameter for GPU memory constraints', 'add debug, quiet, and log arguments to an argparse ArgumentParser for DeepSDF CLI tools', 'configure the root logger with debug, quiet, or info level and optional file output', 'decode signed distance field values from a decoder network given latent vectors and query points', 'review the add_common_args function to see what CLI arguments it adds to an ArgumentParser', 'summarize the decode_sdf function that concatenates latent vectors with queries before passing to a decoder', 'load experiment specifications from a specs.json file in the given experiment directory', 'load a trained decoder model and its epoch from a checkpoint in the experiment directory', 'build a new decoder network from experiment specifications using the specified architecture and code length', 'load latent code vectors from a checkpoint file for the given experiment directory', 'get or create the evaluation output directory path for a specific checkpoint in the experiment']
```

Usage

```
{'load_experiment_specifications': 'load experiment specifications from a specs.json file in the given experiment directory', 'load_decoder': 'load a trained decoder model and its epoch from a checkpoint in the experiment directory', 'build_decoder': 'build a new decoder network from experiment specifications using the specified architecture and code length', 'load_latent_vectors': 'load latent code vectors from a checkpoint file for the given experiment directory', 'get_evaluation_dir': 'get or create the evaluation output directory path for a specific checkpoint in the experiment'}
```

