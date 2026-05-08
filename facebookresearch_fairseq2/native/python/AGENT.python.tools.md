# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/native/python/setup.py

Prompts

```
['review the Distribution class that marks the fairseq2n package as a non-pure distribution with extension modules', 'review the install class that overrides finalize_options to set install_lib to install_platlib for non-pure packages', 'review the install_cmake Command class that installs CMake artifacts into the fairseq2n package directory', 'summarize the _should_bundle_lib method that reads CMakeCache.txt to check if FAIRSEQ2N_INSTALL_STANDALONE is enabled', 'summarize the _cmake_install method that spawns cmake --install with optional component and verbose flags']
```

Usage

```
{'review_Distribution_class': 'review the Distribution class that marks the fairseq2n package as a non-pure distribution with extension modules', 'review_install_class': 'review the install class that overrides finalize_options to set install_lib to install_platlib for non-pure packages', 'review_install_cmake_class': 'review the install_cmake Command class that installs CMake artifacts into the fairseq2n package directory', 'summarize_should_bundle_lib': 'summarize the _should_bundle_lib method that reads CMakeCache.txt to check if FAIRSEQ2N_INSTALL_STANDALONE is enabled', 'summarize_cmake_install': 'summarize the _cmake_install method that spawns cmake --install with optional component and verbose flags'}
```

