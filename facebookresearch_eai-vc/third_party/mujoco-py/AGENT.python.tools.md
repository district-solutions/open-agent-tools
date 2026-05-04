# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mujoco-py/setup.py

Prompts

```
['build the mujoco-py package by running setup.py with the custom Build command that forces a rebuild', 'create a function that reads a requirements file and returns a list of stripped dependency lines', 'run the custom Build class that sets MUJOCO_PY_FORCE_REBUILD and MUJOCO_PY_SKIP_ACTIVATE env vars before building', 'review the setuptools setup configuration for the mujoco-py package including packages, dependencies, and classifiers', 'test that all discovered packages start with mujoco_py to prevent global namespace pollution']
```

Usage

```
{'build_mujoco_py_package': 'build the mujoco-py package by running setup.py with the custom Build command that forces a rebuild', 'read_requirements_file': 'create a function that reads a requirements file and returns a list of stripped dependency lines', 'run_custom_build_command': 'run the custom Build class that sets MUJOCO_PY_FORCE_REBUILD and MUJOCO_PY_SKIP_ACTIVATE env vars before building', 'review_setup_configuration': 'review the setuptools setup configuration for the mujoco-py package including packages, dependencies, and classifiers', 'test_package_namespace_assertion': 'test that all discovered packages start with mujoco_py to prevent global namespace pollution'}
```

