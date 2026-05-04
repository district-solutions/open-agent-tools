# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/private_computation/repository/private_computation_game.py

Prompts

```
['use PrivateComputationGameRepository get_game to retrieve an MPCGameConfig for a supported game name like lift', 'inspect the GameNames enum to list all supported private computation game types such as pcf2_lift', 'review the PRIVATE_COMPUTATION_GAME_CONFIG dictionary to see onedocker package names and arguments for each game', 'check the OneDockerArgument dataclass to understand the name and required fields for game arguments', 'validate a game name by calling get_game and catching ValueError for unsupported game names', 'create a PrivateComputationInstance and persist it via the repository create method', 'read a PrivateComputationInstance from the repository by its instance ID string', 'update an existing PrivateComputationInstance in the repository with new values', 'delete a PrivateComputationInstance from the repository by its instance ID string', 'implement a concrete subclass of PrivateComputationInstanceRepository with all four abstract CRUD methods', 'create a LocalPrivateComputationInstanceRepository instance with a base directory path for local file storage']
```

Usage

```
{'get_game_config': 'use PrivateComputationGameRepository get_game to retrieve an MPCGameConfig for a supported game name like lift', 'list_game_names': 'inspect the GameNames enum to list all supported private computation game types such as pcf2_lift', 'review_game_config_dict': 'review the PRIVATE_COMPUTATION_GAME_CONFIG dictionary to see onedocker package names and arguments for each game', 'check_one_docker_argument': 'check the OneDockerArgument dataclass to understand the name and required fields for game arguments', 'validate_game_support': 'validate a game name by calling get_game and catching ValueError for unsupported game names'}
```

## File: facebookresearch_fbpcs/fbpcs/private_computation/repository/private_computation_instance.py

Prompts

```
['use PrivateComputationGameRepository get_game to retrieve an MPCGameConfig for a supported game name like lift', 'inspect the GameNames enum to list all supported private computation game types such as pcf2_lift', 'review the PRIVATE_COMPUTATION_GAME_CONFIG dictionary to see onedocker package names and arguments for each game', 'check the OneDockerArgument dataclass to understand the name and required fields for game arguments', 'validate a game name by calling get_game and catching ValueError for unsupported game names', 'create a PrivateComputationInstance and persist it via the repository create method', 'read a PrivateComputationInstance from the repository by its instance ID string', 'update an existing PrivateComputationInstance in the repository with new values', 'delete a PrivateComputationInstance from the repository by its instance ID string', 'implement a concrete subclass of PrivateComputationInstanceRepository with all four abstract CRUD methods', 'create a LocalPrivateComputationInstanceRepository instance with a base directory path for local file storage']
```

Usage

```
{'create_private_computation_instance': 'create a PrivateComputationInstance and persist it via the repository create method', 'read_private_computation_instance': 'read a PrivateComputationInstance from the repository by its instance ID string', 'update_private_computation_instance': 'update an existing PrivateComputationInstance in the repository with new values', 'delete_private_computation_instance': 'delete a PrivateComputationInstance from the repository by its instance ID string', 'implement_private_computation_instance_repository': 'implement a concrete subclass of PrivateComputationInstanceRepository with all four abstract CRUD methods'}
```

## File: facebookresearch_fbpcs/fbpcs/private_computation/repository/private_computation_instance_local.py

Prompts

```
['use PrivateComputationGameRepository get_game to retrieve an MPCGameConfig for a supported game name like lift', 'inspect the GameNames enum to list all supported private computation game types such as pcf2_lift', 'review the PRIVATE_COMPUTATION_GAME_CONFIG dictionary to see onedocker package names and arguments for each game', 'check the OneDockerArgument dataclass to understand the name and required fields for game arguments', 'validate a game name by calling get_game and catching ValueError for unsupported game names', 'create a PrivateComputationInstance and persist it via the repository create method', 'read a PrivateComputationInstance from the repository by its instance ID string', 'update an existing PrivateComputationInstance in the repository with new values', 'delete a PrivateComputationInstance from the repository by its instance ID string', 'implement a concrete subclass of PrivateComputationInstanceRepository with all four abstract CRUD methods', 'create a LocalPrivateComputationInstanceRepository instance with a base directory path for local file storage']
```

Usage

```
{'create_LocalPrivateComputationInstanceRepository': 'create a LocalPrivateComputationInstanceRepository instance with a base directory path for local file storage', 'create_private_computation_instance': 'create a new PrivateComputationInstance and persist it to the local filesystem repository', 'read_private_computation_instance': 'read a PrivateComputationInstance from the local repository by its instance ID string', 'update_private_computation_instance': 'update an existing PrivateComputationInstance in the local filesystem repository with new data', 'delete_private_computation_instance': 'delete a PrivateComputationInstance from the local repository by its instance ID string'}
```

