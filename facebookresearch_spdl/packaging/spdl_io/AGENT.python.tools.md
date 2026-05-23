# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/packaging/spdl_io/setup.py

Prompts

```
['build the spdl_io Python package with CMake and Ninja using python setup.py bdist_wheel', 'build the spdl_io package with CUDA support by setting SPDL_USE_CUDA=1 before running setup.py', 'build the spdl_io package targeting a specific FFmpeg version by setting SPDL_USE_FFMPEG_VERSION to 4 5 6 7 or 8', 'review the CMakeBuild class that extends setuptools build_ext to run CMake configure and build steps', 'test the _get_ext_modules function that generates Extension objects for FFmpeg versions 4 through 8']
```

Usage

```
{'build_spdl_io_package': 'build the spdl_io Python package with CMake and Ninja using python setup.py bdist_wheel', 'build_spdl_io_with_cuda': 'build the spdl_io package with CUDA support by setting SPDL_USE_CUDA=1 before running setup.py', 'build_spdl_io_ffmpeg_version': 'build the spdl_io package targeting a specific FFmpeg version by setting SPDL_USE_FFMPEG_VERSION to 4 5 6 7 or 8', 'review_CMakeBuild_class': 'review the CMakeBuild class that extends setuptools build_ext to run CMake configure and build steps', 'test_get_ext_modules': 'test the _get_ext_modules function that generates Extension objects for FFmpeg versions 4 through 8'}
```

