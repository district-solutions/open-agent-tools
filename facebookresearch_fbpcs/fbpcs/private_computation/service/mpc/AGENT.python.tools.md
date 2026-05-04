# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/private_computation/service/mpc/mpc.py

Prompts

```
['initialize an MPCService instance with a container service, task definition, and MPC game service', 'convert MPC game arguments to Onedocker-compatible command arguments for a given game name and party role', 'map a PrivateComputationRole like PUBLISHER or PARTNER to its corresponding MPCParty like SERVER or CLIENT', 'review the MPCService convert_cmd_args_list method to understand how game args are transformed into Onedocker cmd args', 'refactor the MPCService class to add support for additional MPC game argument types or validation logic', 'build onedocker command arguments for a named MPC game with a given party role and server IP', 'build a command string from an MPC game config, party role, and optional server IP and port', 'prepare and validate a dictionary of arguments for an MPC game including party, server IP, and game-specific kwargs', 'review the MPCGameService class and its methods for building onedocker command arguments for MPC games', 'refactor the MPCGameService class to support additional argument validation or new game configuration options']
```

Usage

```
{'init_MPCService': 'initialize an MPCService instance with a container service, task definition, and MPC game service', 'convert_cmd_args_list': 'convert MPC game arguments to Onedocker-compatible command arguments for a given game name and party role', 'map_private_computation_role_to_mpc_party': 'map a PrivateComputationRole like PUBLISHER or PARTNER to its corresponding MPCParty like SERVER or CLIENT', 'review_MPCService_convert_cmd_args_list': 'review the MPCService convert_cmd_args_list method to understand how game args are transformed into Onedocker cmd args', 'refactor_MPCService': 'refactor the MPCService class to add support for additional MPC game argument types or validation logic'}
```

## File: facebookresearch_fbpcs/fbpcs/private_computation/service/mpc/mpc_game.py

Prompts

```
['initialize an MPCService instance with a container service, task definition, and MPC game service', 'convert MPC game arguments to Onedocker-compatible command arguments for a given game name and party role', 'map a PrivateComputationRole like PUBLISHER or PARTNER to its corresponding MPCParty like SERVER or CLIENT', 'review the MPCService convert_cmd_args_list method to understand how game args are transformed into Onedocker cmd args', 'refactor the MPCService class to add support for additional MPC game argument types or validation logic', 'build onedocker command arguments for a named MPC game with a given party role and server IP', 'build a command string from an MPC game config, party role, and optional server IP and port', 'prepare and validate a dictionary of arguments for an MPC game including party, server IP, and game-specific kwargs', 'review the MPCGameService class and its methods for building onedocker command arguments for MPC games', 'refactor the MPCGameService class to support additional argument validation or new game configuration options']
```

Usage

```
{'build_onedocker_args': 'build onedocker command arguments for a named MPC game with a given party role and server IP', 'build_cmd_from_config': 'build a command string from an MPC game config, party role, and optional server IP and port', 'prepare_args_for_game': 'prepare and validate a dictionary of arguments for an MPC game including party, server IP, and game-specific kwargs', 'review_MPCGameService': 'review the MPCGameService class and its methods for building onedocker command arguments for MPC games', 'refactor_MPCGameService': 'refactor the MPCGameService class to support additional argument validation or new game configuration options'}
```

