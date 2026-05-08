# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/release_utils.py

Prompts

```
['run the release utils CLI with --release-type major to compute the next version', 'run the release utils CLI with --release-type patch --update-version to update version.txt', 'get the next semantic version tuple, version string, and tag for a given release type', 'find and read the current version string from a version file path', 'update the fairseq version.txt file with a new version string', 'build the fairseq package with C++ and CUDA extensions using python setup.py install', 'build the fairseq C++ extensions including libbleu and data_utils_fast with python setup.py build_ext', 'clean compiled .so and .pyd files from the fairseq package with python setup.py clean', 'install fairseq CLI tools like fairseq-train and fairseq-generate via pip install', 'configure a NumpyExtension subclass to auto-include numpy headers for Cython C++ extensions']
```

Usage

```
{'run_release_utils_cli': 'run the release utils CLI with --release-type major to compute the next version', 'run_release_utils_update': 'run the release utils CLI with --release-type patch --update-version to update version.txt', 'get_next_version': 'get the next semantic version tuple, version string, and tag for a given release type', 'find_version': 'find and read the current version string from a version file path', 'update_version': 'update the fairseq version.txt file with a new version string'}
```

## File: facebookresearch_fairseq/setup.py

Prompts

```
['run the release utils CLI with --release-type major to compute the next version', 'run the release utils CLI with --release-type patch --update-version to update version.txt', 'get the next semantic version tuple, version string, and tag for a given release type', 'find and read the current version string from a version file path', 'update the fairseq version.txt file with a new version string', 'build the fairseq package with C++ and CUDA extensions using python setup.py install', 'build the fairseq C++ extensions including libbleu and data_utils_fast with python setup.py build_ext', 'clean compiled .so and .pyd files from the fairseq package with python setup.py clean', 'install fairseq CLI tools like fairseq-train and fairseq-generate via pip install', 'configure a NumpyExtension subclass to auto-include numpy headers for Cython C++ extensions']
```

Usage

```
{'build_fairseq_package': 'build the fairseq package with C++ and CUDA extensions using python setup.py install', 'build_fairseq_extensions': 'build the fairseq C++ extensions including libbleu and data_utils_fast with python setup.py build_ext', 'clean_fairseq_compiled_files': 'clean compiled .so and .pyd files from the fairseq package with python setup.py clean', 'setup_fairseq_entry_points': 'install fairseq CLI tools like fairseq-train and fairseq-generate via pip install', 'configure_numpy_extension': 'configure a NumpyExtension subclass to auto-include numpy headers for Cython C++ extensions'}
```

