# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/app_server/container/container_deployment.py

Prompts

```
['build a Ray Serve deployment that manages Apptainer container actors with auto-scaling replicas', 'create a detached Ray actor registry to track container actors and their ownership by replica', 'acquire an idle container actor from the registry and start an Apptainer instance with a given image', 'execute a shell command inside a running Apptainer container instance and capture stdout output', 'release all active containers and clean up their associated actors in the registry']
```

Usage

```
{'build_ray_serve_container_deployment': 'build a Ray Serve deployment that manages Apptainer container actors with auto-scaling replicas', 'create_container_registry_actor': 'create a detached Ray actor registry to track container actors and their ownership by replica', 'acquire_and_start_container': 'acquire an idle container actor from the registry and start an Apptainer instance with a given image', 'execute_command_in_container': 'execute a shell command inside a running Apptainer container instance and capture stdout output', 'release_all_containers': 'release all active containers and clean up their associated actors in the registry'}
```

