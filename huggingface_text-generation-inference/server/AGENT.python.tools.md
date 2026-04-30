# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/server/bounds-from-nix.py

Prompts

```
['run the script to generate poetry add commands from nix package versions', 'check if a poetry dependency entry is marked as optional using is_optional', 'generate poetry add commands by comparing pyproject.toml dependencies against nix pip list output', 'use the SKIP set to exclude attention-kernels marlin-kernels and moe-kernels from version pinning', 'parse pyproject.toml to iterate over poetry dependencies and their optional status']
```

Usage

```
{'run_bounds_from_nix': 'run the script to generate poetry add commands from nix package versions', 'is_optional_check': 'check if a poetry dependency entry is marked as optional using is_optional', 'generate_poetry_commands': 'generate poetry add commands by comparing pyproject.toml dependencies against nix pip list output', 'skip_kernel_packages': 'use the SKIP set to exclude attention-kernels marlin-kernels and moe-kernels from version pinning', 'parse_pyproject_dependencies': 'parse pyproject.toml to iterate over poetry dependencies and their optional status'}
```

