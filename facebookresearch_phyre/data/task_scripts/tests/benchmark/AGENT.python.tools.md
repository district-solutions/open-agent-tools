# Agent Python Tools

- repo: facebookresearch/phyre
- repo_uri: https://github.com/facebookresearch/phyre

## File: facebookresearch_phyre/data/task_scripts/tests/benchmark/task00048.py

Prompts

```
['build a PhyRE task using the define_task decorator to register a physics simulation scenario', 'create dynamic and static physics objects like jars, bars, and balls using C.add', 'position physics objects using set_center_x, set_bottom, set_angle, set_right, and set_left methods', 'define the task goal by calling update_task with body1, body2, and SpatialRelationship.INSIDE', 'get phantom vertices from a jar object to check if a ball falls inside it']
```

Usage

```
{'build_task_with_define_task_decorator': 'build a PhyRE task using the define_task decorator to register a physics simulation scenario', 'create_physics_objects_with_C_add': 'create dynamic and static physics objects like jars, bars, and balls using C.add', 'position_objects_with_setters': 'position physics objects using set_center_x, set_bottom, set_angle, set_right, and set_left methods', 'define_task_goal_with_update_task': 'define the task goal by calling update_task with body1, body2, and SpatialRelationship.INSIDE', 'get_phantom_vertices_for_containment': 'get phantom vertices from a jar object to check if a ball falls inside it'}
```

