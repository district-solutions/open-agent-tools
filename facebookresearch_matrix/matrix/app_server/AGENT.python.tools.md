# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/app_server/app_api.py

Prompts

```
['deploy Ray Serve applications using a YAML config or application list with add, replace, or remove actions', 'get application metadata including endpoints, ports, route prefix, model name, and deployment type for a named app', 'run LLM inference against a deployed app using JSONL input files or a Hugging Face dataset', 'check the current status and running replica count of a deployed Ray Serve or SGLang application', 'cleanup dangling containers for a stateful container application by releasing all containers', 'generate a YAML config string for deploying LLM, OpenAI, Gemini, or SageMaker applications on Ray Serve', 'compute the CPU and GPU resource requirements for an application config based on app type and replica count', 'fill in default vLLM model parameters from llm_model_default_parameters for a given app config dictionary', 'validate that model paths exist locally or on S3 and have required config files before deployment', 'delete specified Ray Serve applications and their associated Matrix actors from the cluster']
```

Usage

```
{'deploy_ray_serve_applications': 'deploy Ray Serve applications using a YAML config or application list with add, replace, or remove actions', 'get_app_metadata': 'get application metadata including endpoints, ports, route prefix, model name, and deployment type for a named app', 'run_llm_inference': 'run LLM inference against a deployed app using JSONL input files or a Hugging Face dataset', 'check_app_status': 'check the current status and running replica count of a deployed Ray Serve or SGLang application', 'cleanup_container_app': 'cleanup dangling containers for a stateful container application by releasing all containers'}
```

## File: facebookresearch_matrix/matrix/app_server/deploy_utils.py

Prompts

```
['deploy Ray Serve applications using a YAML config or application list with add, replace, or remove actions', 'get application metadata including endpoints, ports, route prefix, model name, and deployment type for a named app', 'run LLM inference against a deployed app using JSONL input files or a Hugging Face dataset', 'check the current status and running replica count of a deployed Ray Serve or SGLang application', 'cleanup dangling containers for a stateful container application by releasing all containers', 'generate a YAML config string for deploying LLM, OpenAI, Gemini, or SageMaker applications on Ray Serve', 'compute the CPU and GPU resource requirements for an application config based on app type and replica count', 'fill in default vLLM model parameters from llm_model_default_parameters for a given app config dictionary', 'validate that model paths exist locally or on S3 and have required config files before deployment', 'delete specified Ray Serve applications and their associated Matrix actors from the cluster']
```

Usage

```
{'get_yaml_for_deployment': 'generate a YAML config string for deploying LLM, OpenAI, Gemini, or SageMaker applications on Ray Serve', 'get_resource_requirements': 'compute the CPU and GPU resource requirements for an application config based on app type and replica count', 'update_vllm_app_params': 'fill in default vLLM model parameters from llm_model_default_parameters for a given app config dictionary', 'validate_applications': 'validate that model paths exist locally or on S3 and have required config files before deployment', 'delete_apps': 'delete specified Ray Serve applications and their associated Matrix actors from the cluster'}
```

