# Agent Python Tools

- repo: google-deepmind/dmenvrpc
- repo_uri: https://github.com/google-deepmind/dm_env_rpc

## File: google-deepmind_dmenvrpc/dm_env_rpc/v1/compliance/create_destroy_world.py

Prompts

```
['create a world with given settings by sending a CreateWorldRequest via the dm_env_rpc connection', 'destroy a world by sending a DestroyWorldRequest with the world name via the dm_env_rpc connection', 'test that a world can be created with required settings and then destroyed without error', 'test that creating a world with invalid settings raises a DmEnvRpcError exception', 'test that two worlds created with the same settings receive unique world names', 'test that a client can successfully join a dm_env_rpc world with valid settings', 'test that a client can leave a joined world or leave without having joined', 'test that joining with an invalid world name or invalid settings raises DmEnvRpcError', 'test that action and observation specs have unique names and consistent tensor shapes', 'test that a client can rejoin a world after leaving it successfully', 'send a ResetRequest to the dm_env_rpc connection and return the environment specs', 'test that calling reset after join_world returns the same specs as joining', 'test that calling reset without joining a world raises a DmEnvRpcError', 'test that calling reset multiple times returns consistent specs equal to join_world specs', 'subclass the Reset abstract base class to implement custom dm_env_rpc reset compliance tests', 'test that ResetWorld raises DmEnvRpcError when called with an invalid world name', 'test that ResetWorld succeeds on a world the client is not currently joined to', 'test that ResetWorld succeeds when the client is already joined to the target world', 'create a subclass of ResetWorld to test dm_env_rpc server compliance for world reset behavior', 'review the ResetWorld abstract base class and its join, reset, and leave world methods', 'test the Step base class to verify dm_env_rpc server step compliance for observations and actions', 'test that requested observations are returned and invalid observation UIDs raise errors', 'test that actions with wrong types, shapes, or out-of-range values raise DmEnvRpcError', 'test that scalar values can be broadcast to match action tensor shapes', 'test that single variable dimension tensors are accepted but multiple variable dimensions are rejected']
```

Usage

```
{'create_world': 'create a world with given settings by sending a CreateWorldRequest via the dm_env_rpc connection', 'destroy_world': 'destroy a world by sending a DestroyWorldRequest with the world name via the dm_env_rpc connection', 'test_create_destroy_world': 'test that a world can be created with required settings and then destroyed without error', 'test_invalid_settings': 'test that creating a world with invalid settings raises a DmEnvRpcError exception', 'test_unique_world_name': 'test that two worlds created with the same settings receive unique world names'}
```

## File: google-deepmind_dmenvrpc/dm_env_rpc/v1/compliance/join_leave_world.py

Prompts

```
['create a world with given settings by sending a CreateWorldRequest via the dm_env_rpc connection', 'destroy a world by sending a DestroyWorldRequest with the world name via the dm_env_rpc connection', 'test that a world can be created with required settings and then destroyed without error', 'test that creating a world with invalid settings raises a DmEnvRpcError exception', 'test that two worlds created with the same settings receive unique world names', 'test that a client can successfully join a dm_env_rpc world with valid settings', 'test that a client can leave a joined world or leave without having joined', 'test that joining with an invalid world name or invalid settings raises DmEnvRpcError', 'test that action and observation specs have unique names and consistent tensor shapes', 'test that a client can rejoin a world after leaving it successfully', 'send a ResetRequest to the dm_env_rpc connection and return the environment specs', 'test that calling reset after join_world returns the same specs as joining', 'test that calling reset without joining a world raises a DmEnvRpcError', 'test that calling reset multiple times returns consistent specs equal to join_world specs', 'subclass the Reset abstract base class to implement custom dm_env_rpc reset compliance tests', 'test that ResetWorld raises DmEnvRpcError when called with an invalid world name', 'test that ResetWorld succeeds on a world the client is not currently joined to', 'test that ResetWorld succeeds when the client is already joined to the target world', 'create a subclass of ResetWorld to test dm_env_rpc server compliance for world reset behavior', 'review the ResetWorld abstract base class and its join, reset, and leave world methods', 'test the Step base class to verify dm_env_rpc server step compliance for observations and actions', 'test that requested observations are returned and invalid observation UIDs raise errors', 'test that actions with wrong types, shapes, or out-of-range values raise DmEnvRpcError', 'test that scalar values can be broadcast to match action tensor shapes', 'test that single variable dimension tensors are accepted but multiple variable dimensions are rejected']
```

Usage

```
{'test_join_world_compliance': 'test that a client can successfully join a dm_env_rpc world with valid settings', 'test_leave_world_compliance': 'test that a client can leave a joined world or leave without having joined', 'test_join_world_error_handling': 'test that joining with an invalid world name or invalid settings raises DmEnvRpcError', 'test_action_observation_specs': 'test that action and observation specs have unique names and consistent tensor shapes', 'test_rejoin_world_after_leaving': 'test that a client can rejoin a world after leaving it successfully'}
```

## File: google-deepmind_dmenvrpc/dm_env_rpc/v1/compliance/reset.py

Prompts

```
['create a world with given settings by sending a CreateWorldRequest via the dm_env_rpc connection', 'destroy a world by sending a DestroyWorldRequest with the world name via the dm_env_rpc connection', 'test that a world can be created with required settings and then destroyed without error', 'test that creating a world with invalid settings raises a DmEnvRpcError exception', 'test that two worlds created with the same settings receive unique world names', 'test that a client can successfully join a dm_env_rpc world with valid settings', 'test that a client can leave a joined world or leave without having joined', 'test that joining with an invalid world name or invalid settings raises DmEnvRpcError', 'test that action and observation specs have unique names and consistent tensor shapes', 'test that a client can rejoin a world after leaving it successfully', 'send a ResetRequest to the dm_env_rpc connection and return the environment specs', 'test that calling reset after join_world returns the same specs as joining', 'test that calling reset without joining a world raises a DmEnvRpcError', 'test that calling reset multiple times returns consistent specs equal to join_world specs', 'subclass the Reset abstract base class to implement custom dm_env_rpc reset compliance tests', 'test that ResetWorld raises DmEnvRpcError when called with an invalid world name', 'test that ResetWorld succeeds on a world the client is not currently joined to', 'test that ResetWorld succeeds when the client is already joined to the target world', 'create a subclass of ResetWorld to test dm_env_rpc server compliance for world reset behavior', 'review the ResetWorld abstract base class and its join, reset, and leave world methods', 'test the Step base class to verify dm_env_rpc server step compliance for observations and actions', 'test that requested observations are returned and invalid observation UIDs raise errors', 'test that actions with wrong types, shapes, or out-of-range values raise DmEnvRpcError', 'test that scalar values can be broadcast to match action tensor shapes', 'test that single variable dimension tensors are accepted but multiple variable dimensions are rejected']
```

Usage

```
{'reset_environment_via_rpc': 'send a ResetRequest to the dm_env_rpc connection and return the environment specs', 'test_reset_resends_specs': 'test that calling reset after join_world returns the same specs as joining', 'test_cannot_reset_without_join': 'test that calling reset without joining a world raises a DmEnvRpcError', 'test_multiple_resets': 'test that calling reset multiple times returns consistent specs equal to join_world specs', 'extend_reset_compliance_tests': 'subclass the Reset abstract base class to implement custom dm_env_rpc reset compliance tests'}
```

## File: google-deepmind_dmenvrpc/dm_env_rpc/v1/compliance/reset_world.py

Prompts

```
['create a world with given settings by sending a CreateWorldRequest via the dm_env_rpc connection', 'destroy a world by sending a DestroyWorldRequest with the world name via the dm_env_rpc connection', 'test that a world can be created with required settings and then destroyed without error', 'test that creating a world with invalid settings raises a DmEnvRpcError exception', 'test that two worlds created with the same settings receive unique world names', 'test that a client can successfully join a dm_env_rpc world with valid settings', 'test that a client can leave a joined world or leave without having joined', 'test that joining with an invalid world name or invalid settings raises DmEnvRpcError', 'test that action and observation specs have unique names and consistent tensor shapes', 'test that a client can rejoin a world after leaving it successfully', 'send a ResetRequest to the dm_env_rpc connection and return the environment specs', 'test that calling reset after join_world returns the same specs as joining', 'test that calling reset without joining a world raises a DmEnvRpcError', 'test that calling reset multiple times returns consistent specs equal to join_world specs', 'subclass the Reset abstract base class to implement custom dm_env_rpc reset compliance tests', 'test that ResetWorld raises DmEnvRpcError when called with an invalid world name', 'test that ResetWorld succeeds on a world the client is not currently joined to', 'test that ResetWorld succeeds when the client is already joined to the target world', 'create a subclass of ResetWorld to test dm_env_rpc server compliance for world reset behavior', 'review the ResetWorld abstract base class and its join, reset, and leave world methods', 'test the Step base class to verify dm_env_rpc server step compliance for observations and actions', 'test that requested observations are returned and invalid observation UIDs raise errors', 'test that actions with wrong types, shapes, or out-of-range values raise DmEnvRpcError', 'test that scalar values can be broadcast to match action tensor shapes', 'test that single variable dimension tensors are accepted but multiple variable dimensions are rejected']
```

Usage

```
{'test_reset_invalid_world': 'test that ResetWorld raises DmEnvRpcError when called with an invalid world name', 'test_reset_world_not_joined': 'test that ResetWorld succeeds on a world the client is not currently joined to', 'test_reset_world_when_joined': 'test that ResetWorld succeeds when the client is already joined to the target world', 'create_reset_world_compliance_test': 'create a subclass of ResetWorld to test dm_env_rpc server compliance for world reset behavior', 'review_reset_world_base_class': 'review the ResetWorld abstract base class and its join, reset, and leave world methods'}
```

## File: google-deepmind_dmenvrpc/dm_env_rpc/v1/compliance/step.py

Prompts

```
['create a world with given settings by sending a CreateWorldRequest via the dm_env_rpc connection', 'destroy a world by sending a DestroyWorldRequest with the world name via the dm_env_rpc connection', 'test that a world can be created with required settings and then destroyed without error', 'test that creating a world with invalid settings raises a DmEnvRpcError exception', 'test that two worlds created with the same settings receive unique world names', 'test that a client can successfully join a dm_env_rpc world with valid settings', 'test that a client can leave a joined world or leave without having joined', 'test that joining with an invalid world name or invalid settings raises DmEnvRpcError', 'test that action and observation specs have unique names and consistent tensor shapes', 'test that a client can rejoin a world after leaving it successfully', 'send a ResetRequest to the dm_env_rpc connection and return the environment specs', 'test that calling reset after join_world returns the same specs as joining', 'test that calling reset without joining a world raises a DmEnvRpcError', 'test that calling reset multiple times returns consistent specs equal to join_world specs', 'subclass the Reset abstract base class to implement custom dm_env_rpc reset compliance tests', 'test that ResetWorld raises DmEnvRpcError when called with an invalid world name', 'test that ResetWorld succeeds on a world the client is not currently joined to', 'test that ResetWorld succeeds when the client is already joined to the target world', 'create a subclass of ResetWorld to test dm_env_rpc server compliance for world reset behavior', 'review the ResetWorld abstract base class and its join, reset, and leave world methods', 'test the Step base class to verify dm_env_rpc server step compliance for observations and actions', 'test that requested observations are returned and invalid observation UIDs raise errors', 'test that actions with wrong types, shapes, or out-of-range values raise DmEnvRpcError', 'test that scalar values can be broadcast to match action tensor shapes', 'test that single variable dimension tensors are accepted but multiple variable dimensions are rejected']
```

Usage

```
{'test_Step_class_compliance': 'test the Step base class to verify dm_env_rpc server step compliance for observations and actions', 'test_observation_request_handling': 'test that requested observations are returned and invalid observation UIDs raise errors', 'test_action_validation': 'test that actions with wrong types, shapes, or out-of-range values raise DmEnvRpcError', 'test_broadcastable_actions': 'test that scalar values can be broadcast to match action tensor shapes', 'test_variable_dimension_tensors': 'test that single variable dimension tensors are accepted but multiple variable dimensions are rejected'}
```

