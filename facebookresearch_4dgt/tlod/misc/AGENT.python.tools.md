# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/misc/dist_helper.py

Prompts

```
['init a torch distributed process group with the specified backend and init method kwargs', 'get the current process rank in a torch distributed training setup', 'get the total number of processes in the distributed training world size', 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training on a given device', 'synchronize all processes with a distributed barrier during multi-process training', 'initialize PyTorch DDP distributed training mode from argparse args with NCCL backend and environment setup', 'fix random seeds for Python, PyTorch, CUDA, and NumPy to a specified integer value for reproducibility', 'parse a SLURM job node list string with bracket ranges into a flat list of individual node names', 'setup distributed printing to disable output on non-master processes by setting the is_master global flag', 'create a TorchDistributedEnvironment to read SLURM or torch env variables and export them as process group env vars', 'create a PathManager to copy files or directories recursively from source to target path', 'create a PathManager to make nested directories with an exist_ok flag', 'create a PathManager to remove a file or recursively delete a directory', 'create a PathManager to cache a file or directory to a local cache directory', 'create a distributed-safe mkdirs helper that only creates directories on rank 0', 'create a cosine learning rate schedule with warmup iterations for training epochs', 'create a linear learning rate schedule with warmup iterations for training epochs', 'save a 3D Gaussian splat point cloud with xyz, rgb, opacity, scale, and rotation to PLY', 'extract and save a 3D mesh from a volume using marching cubes with a threshold', 'create orbiting camera poses and rays for rendering a video around a scene']
```

Usage

```
{'init_process_group': 'init a torch distributed process group with the specified backend and init method kwargs', 'get_rank': 'get the current process rank in a torch distributed training setup', 'get_world_size': 'get the total number of processes in the distributed training world size', 'get_parallel_model': 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training on a given device', 'synchronize': 'synchronize all processes with a distributed barrier during multi-process training'}
```

## File: facebookresearch_4dgt/tlod/misc/env_utils.py

Prompts

```
['init a torch distributed process group with the specified backend and init method kwargs', 'get the current process rank in a torch distributed training setup', 'get the total number of processes in the distributed training world size', 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training on a given device', 'synchronize all processes with a distributed barrier during multi-process training', 'initialize PyTorch DDP distributed training mode from argparse args with NCCL backend and environment setup', 'fix random seeds for Python, PyTorch, CUDA, and NumPy to a specified integer value for reproducibility', 'parse a SLURM job node list string with bracket ranges into a flat list of individual node names', 'setup distributed printing to disable output on non-master processes by setting the is_master global flag', 'create a TorchDistributedEnvironment to read SLURM or torch env variables and export them as process group env vars', 'create a PathManager to copy files or directories recursively from source to target path', 'create a PathManager to make nested directories with an exist_ok flag', 'create a PathManager to remove a file or recursively delete a directory', 'create a PathManager to cache a file or directory to a local cache directory', 'create a distributed-safe mkdirs helper that only creates directories on rank 0', 'create a cosine learning rate schedule with warmup iterations for training epochs', 'create a linear learning rate schedule with warmup iterations for training epochs', 'save a 3D Gaussian splat point cloud with xyz, rgb, opacity, scale, and rotation to PLY', 'extract and save a 3D mesh from a volume using marching cubes with a threshold', 'create orbiting camera poses and rays for rendering a video around a scene']
```

Usage

```
{'init_distributed_mode': 'initialize PyTorch DDP distributed training mode from argparse args with NCCL backend and environment setup', 'fix_random_seeds': 'fix random seeds for Python, PyTorch, CUDA, and NumPy to a specified integer value for reproducibility', 'parse_slurm_node_list': 'parse a SLURM job node list string with bracket ranges into a flat list of individual node names', 'setup_for_distributed': 'setup distributed printing to disable output on non-master processes by setting the is_master global flag', 'TorchDistributedEnvironment': 'create a TorchDistributedEnvironment to read SLURM or torch env variables and export them as process group env vars'}
```

## File: facebookresearch_4dgt/tlod/misc/io_helper.py

Prompts

```
['init a torch distributed process group with the specified backend and init method kwargs', 'get the current process rank in a torch distributed training setup', 'get the total number of processes in the distributed training world size', 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training on a given device', 'synchronize all processes with a distributed barrier during multi-process training', 'initialize PyTorch DDP distributed training mode from argparse args with NCCL backend and environment setup', 'fix random seeds for Python, PyTorch, CUDA, and NumPy to a specified integer value for reproducibility', 'parse a SLURM job node list string with bracket ranges into a flat list of individual node names', 'setup distributed printing to disable output on non-master processes by setting the is_master global flag', 'create a TorchDistributedEnvironment to read SLURM or torch env variables and export them as process group env vars', 'create a PathManager to copy files or directories recursively from source to target path', 'create a PathManager to make nested directories with an exist_ok flag', 'create a PathManager to remove a file or recursively delete a directory', 'create a PathManager to cache a file or directory to a local cache directory', 'create a distributed-safe mkdirs helper that only creates directories on rank 0', 'create a cosine learning rate schedule with warmup iterations for training epochs', 'create a linear learning rate schedule with warmup iterations for training epochs', 'save a 3D Gaussian splat point cloud with xyz, rgb, opacity, scale, and rotation to PLY', 'extract and save a 3D mesh from a volume using marching cubes with a threshold', 'create orbiting camera poses and rays for rendering a video around a scene']
```

Usage

```
{'create_PathManager_copy': 'create a PathManager to copy files or directories recursively from source to target path', 'create_PathManager_mkdirs': 'create a PathManager to make nested directories with an exist_ok flag', 'create_PathManager_rm': 'create a PathManager to remove a file or recursively delete a directory', 'create_PathManager_get_local_path': 'create a PathManager to cache a file or directory to a local cache directory', 'create_mkdirs_helper': 'create a distributed-safe mkdirs helper that only creates directories on rank 0'}
```

## File: facebookresearch_4dgt/tlod/misc/utils.py

Prompts

```
['init a torch distributed process group with the specified backend and init method kwargs', 'get the current process rank in a torch distributed training setup', 'get the total number of processes in the distributed training world size', 'wrap a PyTorch model with DistributedDataParallel for multi-GPU training on a given device', 'synchronize all processes with a distributed barrier during multi-process training', 'initialize PyTorch DDP distributed training mode from argparse args with NCCL backend and environment setup', 'fix random seeds for Python, PyTorch, CUDA, and NumPy to a specified integer value for reproducibility', 'parse a SLURM job node list string with bracket ranges into a flat list of individual node names', 'setup distributed printing to disable output on non-master processes by setting the is_master global flag', 'create a TorchDistributedEnvironment to read SLURM or torch env variables and export them as process group env vars', 'create a PathManager to copy files or directories recursively from source to target path', 'create a PathManager to make nested directories with an exist_ok flag', 'create a PathManager to remove a file or recursively delete a directory', 'create a PathManager to cache a file or directory to a local cache directory', 'create a distributed-safe mkdirs helper that only creates directories on rank 0', 'create a cosine learning rate schedule with warmup iterations for training epochs', 'create a linear learning rate schedule with warmup iterations for training epochs', 'save a 3D Gaussian splat point cloud with xyz, rgb, opacity, scale, and rotation to PLY', 'extract and save a 3D mesh from a volume using marching cubes with a threshold', 'create orbiting camera poses and rays for rendering a video around a scene']
```

Usage

```
{'create_cosine_scheduler': 'create a cosine learning rate schedule with warmup iterations for training epochs', 'create_linear_scheduler': 'create a linear learning rate schedule with warmup iterations for training epochs', 'save_ply_point_cloud': 'save a 3D Gaussian splat point cloud with xyz, rgb, opacity, scale, and rotation to PLY', 'save_mesh_marching_cubes': 'extract and save a 3D mesh from a volume using marching cubes with a threshold', 'create_video_cameras': 'create orbiting camera poses and rays for rendering a video around a scene'}
```

