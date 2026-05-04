# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/manipulation/standard_cell/rgb_basket.py

Prompts

```
['build an RGBBasket arena by instantiating RGBBasket and calling _build to load the MJCF model', 'add collision geometries to the basket model including camera struts, basket struts, and sloped surfaces', 'get the list of basket cameras from the RGBBasket cameras property for rendering views', 'get all collision geometry identifiers from the RGBBasket collision_geom_group property for contact configuration', 'set all mesh geometries in the basket to non-colliding by disabling contype and conaffinity', 'test that RGBBasket initializes and physics.step runs without error', 'test that RGBBasket collision_geom_group is not empty when primitive collisions are enabled', 'run a physics step on an RGBBasket MJCF model to verify simulation works', 'review the RGBBasket class and its collision geometry group properties', 'summarize the RGBBasket test suite covering initialization and collision geometry checks']
```

Usage

```
{'build_rgb_basket_arena': 'build an RGBBasket arena by instantiating RGBBasket and calling _build to load the MJCF model', 'add_collision_geoms': 'add collision geometries to the basket model including camera struts, basket struts, and sloped surfaces', 'get_cameras': 'get the list of basket cameras from the RGBBasket cameras property for rendering views', 'get_collision_geom_group': 'get all collision geometry identifiers from the RGBBasket collision_geom_group property for contact configuration', 'set_non_colliding_geoms': 'set all mesh geometries in the basket to non-colliding by disabling contype and conaffinity'}
```

## File: google-deepmind_dmrobotics/py/manipulation/standard_cell/rgb_basket_test.py

Prompts

```
['build an RGBBasket arena by instantiating RGBBasket and calling _build to load the MJCF model', 'add collision geometries to the basket model including camera struts, basket struts, and sloped surfaces', 'get the list of basket cameras from the RGBBasket cameras property for rendering views', 'get all collision geometry identifiers from the RGBBasket collision_geom_group property for contact configuration', 'set all mesh geometries in the basket to non-colliding by disabling contype and conaffinity', 'test that RGBBasket initializes and physics.step runs without error', 'test that RGBBasket collision_geom_group is not empty when primitive collisions are enabled', 'run a physics step on an RGBBasket MJCF model to verify simulation works', 'review the RGBBasket class and its collision geometry group properties', 'summarize the RGBBasket test suite covering initialization and collision geometry checks']
```

Usage

```
{'test_RGBBasket_initialization': 'test that RGBBasket initializes and physics.step runs without error', 'test_collision_geom_group': 'test that RGBBasket collision_geom_group is not empty when primitive collisions are enabled', 'run_RGBBasket_physics_step': 'run a physics step on an RGBBasket MJCF model to verify simulation works', 'review_RGBBasket_class': 'review the RGBBasket class and its collision geometry group properties', 'summarize_RGBBasket_test': 'summarize the RGBBasket test suite covering initialization and collision geometry checks'}
```

