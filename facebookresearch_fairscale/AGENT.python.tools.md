# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/release_utils.py

Prompts

```
['run the release utils script with --release-type patch to bump the patch version', 'run the release utils script with --release-type minor to bump the minor version', 'run the release utils script with --release-type major to bump the major version', 'run the release utils script with --update-version to write the new version to version.py', 'call get_next_version with a release type to compute the next version tuple and tag string', 'build the fairscale python package using setuptools with python setup.py install', 'build the fairscale CUDA fused adam extension by setting BUILD_CUDA_EXTENSIONS=1', 'fetch the package requirements from requirements.txt and return them as a list', 'find and parse the version tuple from fairscale/version.py using regex', 'install the wgit console script entry point from fairscale.experimental.wgit']
```

Usage

```
{'run_release_patch': 'run the release utils script with --release-type patch to bump the patch version', 'run_release_minor': 'run the release utils script with --release-type minor to bump the minor version', 'run_release_major': 'run the release utils script with --release-type major to bump the major version', 'run_release_update_version': 'run the release utils script with --update-version to write the new version to version.py', 'get_next_version': 'call get_next_version with a release type to compute the next version tuple and tag string'}
```

## File: facebookresearch_fairscale/setup.py

Prompts

```
['run the release utils script with --release-type patch to bump the patch version', 'run the release utils script with --release-type minor to bump the minor version', 'run the release utils script with --release-type major to bump the major version', 'run the release utils script with --update-version to write the new version to version.py', 'call get_next_version with a release type to compute the next version tuple and tag string', 'build the fairscale python package using setuptools with python setup.py install', 'build the fairscale CUDA fused adam extension by setting BUILD_CUDA_EXTENSIONS=1', 'fetch the package requirements from requirements.txt and return them as a list', 'find and parse the version tuple from fairscale/version.py using regex', 'install the wgit console script entry point from fairscale.experimental.wgit']
```

Usage

```
{'build_fairscale_package': 'build the fairscale python package using setuptools with python setup.py install', 'build_cuda_extensions': 'build the fairscale CUDA fused adam extension by setting BUILD_CUDA_EXTENSIONS=1', 'fetch_requirements': 'fetch the package requirements from requirements.txt and return them as a list', 'find_version': 'find and parse the version tuple from fairscale/version.py using regex', 'install_wgit_entry_point': 'install the wgit console script entry point from fairscale.experimental.wgit'}
```

