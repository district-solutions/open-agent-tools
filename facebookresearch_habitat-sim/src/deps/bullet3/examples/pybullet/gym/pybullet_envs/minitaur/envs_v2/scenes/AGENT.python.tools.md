# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/scenes/random_stepstone_scene.py

Prompts

```
['build a RandomStepstoneScene with 50 randomly spaced stepstones for a pybullet minitaur environment', 'create a RandomStepstoneScene with custom stone height, width, and gap length bounds', 'reset the RandomStepstoneScene to rebuild stepstones with new random positions during simulation', 'build the stepstone scene by calling build_scene with a pybullet client to place stones and floor', 'review the RandomStepstoneScene __init__ to understand configurable parameters for stone dimensions and colors', 'build a pybullet scene by calling SceneBase.build_scene with a BulletClient to load and position all objects', 'add a tracked object to the scene with add_object using a pybullet id and ObjectType label', 'remove a tracked object from the scene and pybullet by its unique object id', 'destroy all tracked objects in the scene and reset tracking dictionaries for a fresh build', 'get a WorldAsset proto describing all scene objects with bounding boxes via the world_asset property', 'build a SimpleScene that creates a planar floor with visual and collision shapes in pybullet', 'create visual and collision plane shapes using createVisualShape and createCollisionShape with GEOM_PLANE', 'create a multi-body ground object with zero mass and assigned collision and visual shape indices', 'set the lateral friction of the ground body to 1.0 using changeDynamics', 'get the vectorized map of polygon obstacles which returns an empty list for SimpleScene']
```

Usage

```
{'build_random_stepstone_scene': 'build a RandomStepstoneScene with 50 randomly spaced stepstones for a pybullet minitaur environment', 'create_stepstone_scene_with_custom_params': 'create a RandomStepstoneScene with custom stone height, width, and gap length bounds', 'reset_stepstone_scene': 'reset the RandomStepstoneScene to rebuild stepstones with new random positions during simulation', 'build_scene_with_pybullet_client': 'build the stepstone scene by calling build_scene with a pybullet client to place stones and floor', 'review_random_stepstone_scene_init': 'review the RandomStepstoneScene __init__ to understand configurable parameters for stone dimensions and colors'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/scenes/scene_base.py

Prompts

```
['build a RandomStepstoneScene with 50 randomly spaced stepstones for a pybullet minitaur environment', 'create a RandomStepstoneScene with custom stone height, width, and gap length bounds', 'reset the RandomStepstoneScene to rebuild stepstones with new random positions during simulation', 'build the stepstone scene by calling build_scene with a pybullet client to place stones and floor', 'review the RandomStepstoneScene __init__ to understand configurable parameters for stone dimensions and colors', 'build a pybullet scene by calling SceneBase.build_scene with a BulletClient to load and position all objects', 'add a tracked object to the scene with add_object using a pybullet id and ObjectType label', 'remove a tracked object from the scene and pybullet by its unique object id', 'destroy all tracked objects in the scene and reset tracking dictionaries for a fresh build', 'get a WorldAsset proto describing all scene objects with bounding boxes via the world_asset property', 'build a SimpleScene that creates a planar floor with visual and collision shapes in pybullet', 'create visual and collision plane shapes using createVisualShape and createCollisionShape with GEOM_PLANE', 'create a multi-body ground object with zero mass and assigned collision and visual shape indices', 'set the lateral friction of the ground body to 1.0 using changeDynamics', 'get the vectorized map of polygon obstacles which returns an empty list for SimpleScene']
```

Usage

```
{'build_scene': 'build a pybullet scene by calling SceneBase.build_scene with a BulletClient to load and position all objects', 'add_object': 'add a tracked object to the scene with add_object using a pybullet id and ObjectType label', 'remove_object': 'remove a tracked object from the scene and pybullet by its unique object id', 'destroy_scene': 'destroy all tracked objects in the scene and reset tracking dictionaries for a fresh build', 'get_world_asset': 'get a WorldAsset proto describing all scene objects with bounding boxes via the world_asset property'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/envs_v2/scenes/simple_scene.py

Prompts

```
['build a RandomStepstoneScene with 50 randomly spaced stepstones for a pybullet minitaur environment', 'create a RandomStepstoneScene with custom stone height, width, and gap length bounds', 'reset the RandomStepstoneScene to rebuild stepstones with new random positions during simulation', 'build the stepstone scene by calling build_scene with a pybullet client to place stones and floor', 'review the RandomStepstoneScene __init__ to understand configurable parameters for stone dimensions and colors', 'build a pybullet scene by calling SceneBase.build_scene with a BulletClient to load and position all objects', 'add a tracked object to the scene with add_object using a pybullet id and ObjectType label', 'remove a tracked object from the scene and pybullet by its unique object id', 'destroy all tracked objects in the scene and reset tracking dictionaries for a fresh build', 'get a WorldAsset proto describing all scene objects with bounding boxes via the world_asset property', 'build a SimpleScene that creates a planar floor with visual and collision shapes in pybullet', 'create visual and collision plane shapes using createVisualShape and createCollisionShape with GEOM_PLANE', 'create a multi-body ground object with zero mass and assigned collision and visual shape indices', 'set the lateral friction of the ground body to 1.0 using changeDynamics', 'get the vectorized map of polygon obstacles which returns an empty list for SimpleScene']
```

Usage

```
{'build_simple_scene': 'build a SimpleScene that creates a planar floor with visual and collision shapes in pybullet', 'create_visual_collision_shapes': 'create visual and collision plane shapes using createVisualShape and createCollisionShape with GEOM_PLANE', 'create_multibody_ground': 'create a multi-body ground object with zero mass and assigned collision and visual shape indices', 'set_lateral_friction': 'set the lateral friction of the ground body to 1.0 using changeDynamics', 'get_vectorized_map': 'get the vectorized map of polygon obstacles which returns an empty list for SimpleScene'}
```

