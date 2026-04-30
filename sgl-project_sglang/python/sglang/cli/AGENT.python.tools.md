# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/cli/generate.py

Prompts

```
['run the SGLang generate CLI subcommand with a model path and generation arguments', 'add multimodal generation CLI arguments to an argparse parser', 'run the multimodal generation command with parsed CLI arguments', 'extract the model path from a list of CLI arguments', 'detect whether a given model path points to a diffusion model', 'run the sglang CLI serve subcommand to launch an SGLang server', 'run the sglang CLI version subcommand to show version and git revision information', 'build the sglang CLI entry point with argparse subparsers for serve, generate, and version commands', 'test the main CLI function routing logic for serve, generate, and version subcommands', 'run the sglang serve command to launch an LLM or diffusion model server', 'extract and filter the --model-type argument from extra argv for server dispatch', 'test auto detection of diffusion vs LLM model type from a model path', 'run the sglang serve command with --model-type diffusion to launch a diffusion model server', 'run the sglang serve command to launch a standard language model server', 'test the get_is_diffusion_model function to detect whether a model path points to a diffusion model', 'run get_model_path to extract the --model-path argument from a list of command-line arguments', 'get the cached git commit hash string for the current sglang installation', 'test the _is_diffusers_model_dir function to check if a local directory contains a valid diffusers model_index.json', 'test the _is_gated_diffusion_repo function to query HF model card metadata for gated diffusers repos']
```

Usage

```
{'run_generate_subcommand': 'run the SGLang generate CLI subcommand with a model path and generation arguments', 'add_multimodal_gen_generate_args': 'add multimodal generation CLI arguments to an argparse parser', 'run_generate_cmd': 'run the multimodal generation command with parsed CLI arguments', 'get_model_path': 'extract the model path from a list of CLI arguments', 'get_is_diffusion_model': 'detect whether a given model path points to a diffusion model'}
```

## File: sgl-project_sglang/python/sglang/cli/main.py

Prompts

```
['run the SGLang generate CLI subcommand with a model path and generation arguments', 'add multimodal generation CLI arguments to an argparse parser', 'run the multimodal generation command with parsed CLI arguments', 'extract the model path from a list of CLI arguments', 'detect whether a given model path points to a diffusion model', 'run the sglang CLI serve subcommand to launch an SGLang server', 'run the sglang CLI version subcommand to show version and git revision information', 'build the sglang CLI entry point with argparse subparsers for serve, generate, and version commands', 'test the main CLI function routing logic for serve, generate, and version subcommands', 'run the sglang serve command to launch an LLM or diffusion model server', 'extract and filter the --model-type argument from extra argv for server dispatch', 'test auto detection of diffusion vs LLM model type from a model path', 'run the sglang serve command with --model-type diffusion to launch a diffusion model server', 'run the sglang serve command to launch a standard language model server', 'test the get_is_diffusion_model function to detect whether a model path points to a diffusion model', 'run get_model_path to extract the --model-path argument from a list of command-line arguments', 'get the cached git commit hash string for the current sglang installation', 'test the _is_diffusers_model_dir function to check if a local directory contains a valid diffusers model_index.json', 'test the _is_gated_diffusion_repo function to query HF model card metadata for gated diffusers repos']
```

Usage

```
{'run_serve_subcommand': 'run the sglang CLI serve subcommand to launch an SGLang server', 'run_generate_subcommand': 'run the sglang CLI generate subcommand to run inference on a multimodal model', 'run_version_subcommand': 'run the sglang CLI version subcommand to show version and git revision information', 'build_sgl_cli_entry_point': 'build the sglang CLI entry point with argparse subparsers for serve, generate, and version commands', 'test_main_cli_routing': 'test the main CLI function routing logic for serve, generate, and version subcommands'}
```

## File: sgl-project_sglang/python/sglang/cli/serve.py

Prompts

```
['run the SGLang generate CLI subcommand with a model path and generation arguments', 'add multimodal generation CLI arguments to an argparse parser', 'run the multimodal generation command with parsed CLI arguments', 'extract the model path from a list of CLI arguments', 'detect whether a given model path points to a diffusion model', 'run the sglang CLI serve subcommand to launch an SGLang server', 'run the sglang CLI version subcommand to show version and git revision information', 'build the sglang CLI entry point with argparse subparsers for serve, generate, and version commands', 'test the main CLI function routing logic for serve, generate, and version subcommands', 'run the sglang serve command to launch an LLM or diffusion model server', 'extract and filter the --model-type argument from extra argv for server dispatch', 'test auto detection of diffusion vs LLM model type from a model path', 'run the sglang serve command with --model-type diffusion to launch a diffusion model server', 'run the sglang serve command to launch a standard language model server', 'test the get_is_diffusion_model function to detect whether a model path points to a diffusion model', 'run get_model_path to extract the --model-path argument from a list of command-line arguments', 'get the cached git commit hash string for the current sglang installation', 'test the _is_diffusers_model_dir function to check if a local directory contains a valid diffusers model_index.json', 'test the _is_gated_diffusion_repo function to query HF model card metadata for gated diffusers repos']
```

Usage

```
{'run_serve_command': 'run the sglang serve command to launch an LLM or diffusion model server', 'extract_model_type_override': 'extract and filter the --model-type argument from extra argv for server dispatch', 'test_model_type_detection': 'test auto detection of diffusion vs LLM model type from a model path', 'run_diffusion_server': 'run the sglang serve command with --model-type diffusion to launch a diffusion model server', 'run_llm_server': 'run the sglang serve command to launch a standard language model server'}
```

## File: sgl-project_sglang/python/sglang/cli/utils.py

Prompts

```
['run the SGLang generate CLI subcommand with a model path and generation arguments', 'add multimodal generation CLI arguments to an argparse parser', 'run the multimodal generation command with parsed CLI arguments', 'extract the model path from a list of CLI arguments', 'detect whether a given model path points to a diffusion model', 'run the sglang CLI serve subcommand to launch an SGLang server', 'run the sglang CLI version subcommand to show version and git revision information', 'build the sglang CLI entry point with argparse subparsers for serve, generate, and version commands', 'test the main CLI function routing logic for serve, generate, and version subcommands', 'run the sglang serve command to launch an LLM or diffusion model server', 'extract and filter the --model-type argument from extra argv for server dispatch', 'test auto detection of diffusion vs LLM model type from a model path', 'run the sglang serve command with --model-type diffusion to launch a diffusion model server', 'run the sglang serve command to launch a standard language model server', 'test the get_is_diffusion_model function to detect whether a model path points to a diffusion model', 'run get_model_path to extract the --model-path argument from a list of command-line arguments', 'get the cached git commit hash string for the current sglang installation', 'test the _is_diffusers_model_dir function to check if a local directory contains a valid diffusers model_index.json', 'test the _is_gated_diffusion_repo function to query HF model card metadata for gated diffusers repos']
```

Usage

```
{'test_get_is_diffusion_model': 'test the get_is_diffusion_model function to detect whether a model path points to a diffusion model', 'run_get_model_path': 'run get_model_path to extract the --model-path argument from a list of command-line arguments', 'get_get_git_commit_hash': 'get the cached git commit hash string for the current sglang installation', 'test_is_diffusers_model_dir': 'test the _is_diffusers_model_dir function to check if a local directory contains a valid diffusers model_index.json', 'test_is_gated_diffusion_repo': 'test the _is_gated_diffusion_repo function to query HF model card metadata for gated diffusers repos'}
```

