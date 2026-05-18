# Agent Python Tools

- repo: facebookresearch/momentum
- repo_uri: https://github.com/facebookresearch/momentum

## File: facebookresearch_momentum/pymomentum/backend/skel_state_backend.py

Prompts

```
['create a function that converts 7-parameter joint params with euler angles and log-scale into 8-parameter local skeleton state tensors', 'build a forward kinematics pipeline that computes global joint transformations from local skeleton states using prefix multiplication', 'build a linear blend skinning module that deforms template vertex positions using global skeleton state transformations and skinning weights', 'create a Gaussian splatting skinning function that blends both point positions and orientations using skeleton state transformations', 'build an inverse skinning function that unposes deformed vertices back to rest pose using global joint state and bind pose', 'compute global joint translations, rotations, and scales from local TRS states using forward kinematics', 'apply linear blend skinning to a mesh template using global joint TRS transformations and skin weights', 'inverse skin a posed mesh back to its template pose using joint TRS states and skin weights', 'convert 7-parameter joint parameters into local translation, rotation, and scale tensors for a skeleton', 'apply linear blend skinning to a batch of meshes with different topologies using flattened skin indices', 'calculate prefix multiplication indices for forward kinematics from a joint parents tensor', 'flatten LBS skinning weights and indices tensors by removing zero-weight entries', 'create an LBSAdapter from a pymomentum Character to expose LBS-compatible tensor properties', 'assemble pose and scale parameters into a combined model parameters tensor using LBSAdapter', 'move an LBSAdapter and all its tensors to a specified device like cuda']
```

Usage

```
{'local_skel_state_from_joint_params': 'create a function that converts 7-parameter joint params with euler angles and log-scale into 8-parameter local skeleton state tensors', 'global_skel_state_from_local_skel_state': 'build a forward kinematics pipeline that computes global joint transformations from local skeleton states using prefix multiplication', 'skin_points_from_skel_state': 'build a linear blend skinning module that deforms template vertex positions using global skeleton state transformations and skinning weights', 'skin_oriented_points_from_skel_state': 'create a Gaussian splatting skinning function that blends both point positions and orientations using skeleton state transformations', 'unpose_from_momentum_global_joint_state': 'build an inverse skinning function that unposes deformed vertices back to rest pose using global joint state and bind pose'}
```

## File: facebookresearch_momentum/pymomentum/backend/trs_backend.py

Prompts

```
['create a function that converts 7-parameter joint params with euler angles and log-scale into 8-parameter local skeleton state tensors', 'build a forward kinematics pipeline that computes global joint transformations from local skeleton states using prefix multiplication', 'build a linear blend skinning module that deforms template vertex positions using global skeleton state transformations and skinning weights', 'create a Gaussian splatting skinning function that blends both point positions and orientations using skeleton state transformations', 'build an inverse skinning function that unposes deformed vertices back to rest pose using global joint state and bind pose', 'compute global joint translations, rotations, and scales from local TRS states using forward kinematics', 'apply linear blend skinning to a mesh template using global joint TRS transformations and skin weights', 'inverse skin a posed mesh back to its template pose using joint TRS states and skin weights', 'convert 7-parameter joint parameters into local translation, rotation, and scale tensors for a skeleton', 'apply linear blend skinning to a batch of meshes with different topologies using flattened skin indices', 'calculate prefix multiplication indices for forward kinematics from a joint parents tensor', 'flatten LBS skinning weights and indices tensors by removing zero-weight entries', 'create an LBSAdapter from a pymomentum Character to expose LBS-compatible tensor properties', 'assemble pose and scale parameters into a combined model parameters tensor using LBSAdapter', 'move an LBSAdapter and all its tensors to a specified device like cuda']
```

Usage

```
{'global_trs_state_from_local_trs_state': 'compute global joint translations, rotations, and scales from local TRS states using forward kinematics', 'skin_points_from_trs_state': 'apply linear blend skinning to a mesh template using global joint TRS transformations and skin weights', 'unpose_from_global_joint_state': 'inverse skin a posed mesh back to its template pose using joint TRS states and skin weights', 'get_local_state_from_joint_params': 'convert 7-parameter joint parameters into local translation, rotation, and scale tensors for a skeleton', 'multi_topology_skinning': 'apply linear blend skinning to a batch of meshes with different topologies using flattened skin indices'}
```

## File: facebookresearch_momentum/pymomentum/backend/utils.py

Prompts

```
['create a function that converts 7-parameter joint params with euler angles and log-scale into 8-parameter local skeleton state tensors', 'build a forward kinematics pipeline that computes global joint transformations from local skeleton states using prefix multiplication', 'build a linear blend skinning module that deforms template vertex positions using global skeleton state transformations and skinning weights', 'create a Gaussian splatting skinning function that blends both point positions and orientations using skeleton state transformations', 'build an inverse skinning function that unposes deformed vertices back to rest pose using global joint state and bind pose', 'compute global joint translations, rotations, and scales from local TRS states using forward kinematics', 'apply linear blend skinning to a mesh template using global joint TRS transformations and skin weights', 'inverse skin a posed mesh back to its template pose using joint TRS states and skin weights', 'convert 7-parameter joint parameters into local translation, rotation, and scale tensors for a skeleton', 'apply linear blend skinning to a batch of meshes with different topologies using flattened skin indices', 'calculate prefix multiplication indices for forward kinematics from a joint parents tensor', 'flatten LBS skinning weights and indices tensors by removing zero-weight entries', 'create an LBSAdapter from a pymomentum Character to expose LBS-compatible tensor properties', 'assemble pose and scale parameters into a combined model parameters tensor using LBSAdapter', 'move an LBSAdapter and all its tensors to a specified device like cuda']
```

Usage

```
{'calc_fk_prefix_multiplication_indices': 'calculate prefix multiplication indices for forward kinematics from a joint parents tensor', 'flatten_skinning_weights_and_indices': 'flatten LBS skinning weights and indices tensors by removing zero-weight entries', 'create_LBSAdapter': 'create an LBSAdapter from a pymomentum Character to expose LBS-compatible tensor properties', 'LBSAdapter_assemble_pose_and_scale': 'assemble pose and scale parameters into a combined model parameters tensor using LBSAdapter', 'LBSAdapter_to_device': 'move an LBSAdapter and all its tensors to a specified device like cuda'}
```

