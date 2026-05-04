# Agent Python Tools

- repo: google-deepmind/alohasim
- repo_uri: https://github.com/google-deepmind/aloha_sim

## File: google-deepmind_alohasim/aloha_sim/utils/oobb_utils.py

Prompts

```
['get an oriented bounding box for a given MuJoCo body index from a model and data', 'test whether two oriented bounding boxes overlap using the separating axis theorem', 'test whether an axis-aligned bounding box and an oriented bounding box overlap', 'apply a translation and rotation transform to an oriented bounding box', 'get the 8 corner vertices of an oriented bounding box as a numpy array', 'check if any MuJoCo props are moving above a velocity tolerance threshold', 'get the velocity of a MuJoCo prop object using its get_velocity method', 'set the qvel tolerance threshold for detecting prop movement in success detection', 'review the any_props_moving function to understand how it checks prop velocities', 'refactor the any_props_moving function to use a configurable qvel tolerance parameter']
```

Usage

```
{'get_oobb_from_mujoco_body': 'get an oriented bounding box for a given MuJoCo body index from a model and data', 'overlap_oobb_oobb': 'test whether two oriented bounding boxes overlap using the separating axis theorem', 'overlap_aabb_oobb': 'test whether an axis-aligned bounding box and an oriented bounding box overlap', 'transform_oobb': 'apply a translation and rotation transform to an oriented bounding box', 'get_vertices_oobb': 'get the 8 corner vertices of an oriented bounding box as a numpy array'}
```

## File: google-deepmind_alohasim/aloha_sim/utils/success_detector_utils.py

Prompts

```
['get an oriented bounding box for a given MuJoCo body index from a model and data', 'test whether two oriented bounding boxes overlap using the separating axis theorem', 'test whether an axis-aligned bounding box and an oriented bounding box overlap', 'apply a translation and rotation transform to an oriented bounding box', 'get the 8 corner vertices of an oriented bounding box as a numpy array', 'check if any MuJoCo props are moving above a velocity tolerance threshold', 'get the velocity of a MuJoCo prop object using its get_velocity method', 'set the qvel tolerance threshold for detecting prop movement in success detection', 'review the any_props_moving function to understand how it checks prop velocities', 'refactor the any_props_moving function to use a configurable qvel tolerance parameter']
```

Usage

```
{'check_props_moving': 'check if any MuJoCo props are moving above a velocity tolerance threshold', 'get_prop_velocity': 'get the velocity of a MuJoCo prop object using its get_velocity method', 'set_qvel_tolerance': 'set the qvel tolerance threshold for detecting prop movement in success detection', 'review_any_props_moving': 'review the any_props_moving function to understand how it checks prop velocities', 'refactor_qvel_tol': 'refactor the any_props_moving function to use a configurable qvel tolerance parameter'}
```

