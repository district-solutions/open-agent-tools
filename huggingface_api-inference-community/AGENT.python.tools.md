# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/build_docker.py

Prompts

```
['build a docker image for a specific ML framework and push it to the container registry', 'build and push docker images for all available ML frameworks in the docker_images directory', 'build a GPU variant of a framework docker image using the --gpu flag', 'run a shell command via subprocess and exit on failure using the run helper function', 'write framework build tags to an output file using the --out argument', 'start a local model inference server using uvicorn on port 8000 for a given Hugging Face model', 'run a Docker container for model inference with optional GPU support for a Hugging Face model', 'show all available Docker frameworks and their supported pipeline tasks from the docker_images directory', 'create a Docker image with a random tag for a given framework from the docker_images directory', 'resolve the task and framework for a Hugging Face model by querying the Hugging Face Hub API']
```

Usage

```
{'build_docker_image_for_framework': 'build a docker image for a specific ML framework and push it to the container registry', 'build_all_framework_images': 'build and push docker images for all available ML frameworks in the docker_images directory', 'build_gpu_variant': 'build a GPU variant of a framework docker image using the --gpu flag', 'run_subprocess_command': 'run a shell command via subprocess and exit on failure using the run helper function', 'output_build_tags_to_file': 'write framework build tags to an output file using the --out argument'}
```

## File: huggingface_api-inference-community/manage.py

Prompts

```
['build a docker image for a specific ML framework and push it to the container registry', 'build and push docker images for all available ML frameworks in the docker_images directory', 'build a GPU variant of a framework docker image using the --gpu flag', 'run a shell command via subprocess and exit on failure using the run helper function', 'write framework build tags to an output file using the --out argument', 'start a local model inference server using uvicorn on port 8000 for a given Hugging Face model', 'run a Docker container for model inference with optional GPU support for a Hugging Face model', 'show all available Docker frameworks and their supported pipeline tasks from the docker_images directory', 'create a Docker image with a random tag for a given framework from the docker_images directory', 'resolve the task and framework for a Hugging Face model by querying the Hugging Face Hub API']
```

Usage

```
{'start_local_inference': 'start a local model inference server using uvicorn on port 8000 for a given Hugging Face model', 'run_docker_inference': 'run a Docker container for model inference with optional GPU support for a Hugging Face model', 'show_available_frameworks': 'show all available Docker frameworks and their supported pipeline tasks from the docker_images directory', 'create_docker_image': 'create a Docker image with a random tag for a given framework from the docker_images directory', 'resolve_model_task_framework': 'resolve the task and framework for a Hugging Face model by querying the Hugging Face Hub API'}
```

