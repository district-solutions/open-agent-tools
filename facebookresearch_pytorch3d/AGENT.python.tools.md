# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/setup.py

Prompts

```
['run setup.py to build and install the pytorch3d package with C++ and CUDA extensions', 'set PYTORCH3D_FORCE_NO_CUDA=1 to build pytorch3d without CUDA support', 'set PYTORCH3D_NO_NINJA=1 to build pytorch3d using setuptools instead of ninja', 'review the get_existing_ccbin function that parses nvcc args to extract the -ccbin compiler path', 'review the get_extensions function that discovers C++ and CUDA source files and configures compile flags']
```

Usage

```
{'build_pytorch3d_package': 'run setup.py to build and install the pytorch3d package with C++ and CUDA extensions', 'build_pytorch3d_no_cuda': 'set PYTORCH3D_FORCE_NO_CUDA=1 to build pytorch3d without CUDA support', 'build_pytorch3d_no_ninja': 'set PYTORCH3D_NO_NINJA=1 to build pytorch3d using setuptools instead of ninja', 'review_get_existing_ccbin': 'review the get_existing_ccbin function that parses nvcc args to extract the -ccbin compiler path', 'review_get_extensions': 'review the get_extensions function that discovers C++ and CUDA source files and configures compile flags'}
```

