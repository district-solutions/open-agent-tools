# Agent Python Tools

- repo: facebookresearch/phyre
- repo_uri: https://github.com/facebookresearch/phyre

## File: facebookresearch_phyre/data/task_scripts/tests/task_validation/task00001.py

Prompts

```
['use the define_task decorator to register a build_task function that creates a PHYRE physics task', 'call C.add_box(width, height) to create a box body and chain set_bottom and set_left to position it', 'use C.update_task with body1, body2, and C.SpatialRelationship.LEFT_OF to define a spatial relationship task', 'chain set_bottom, set_left, set_top, set_right on a Body to position it in the 256x256 scene', 'pass a description string to C.update_task to describe the task goal for the agent', 'use @define_task_template to generate multiple task variants from a parameterized build_task function', 'call C.update_task with body1, body2, and SpatialRelationship enum to define the task goal', 'review the build_task function to understand how boxes are positioned and spatial relationships are defined', 'use the define_task decorator to register a build_task function that creates a PHYRE spatial reasoning task', 'position a body by setting its bottom edge coordinate using the set_bottom method', 'position a body by setting its left edge coordinate using the set_left method', 'finalize a task by setting body references, spatial relationships, and a description string', 'call C.update_task with body1, body2, and a SpatialRelationship enum to define the task goal', 'use C.SpatialRelationship.TOUCHING to specify that two bodies should be touching in the task', 'chain set_bottom and set_left on a body to position it at specific coordinates in the scene', 'create boxes in a phyre scene using add_box with width and height parameters', 'position a body in the scene by setting its bottom coordinate relative to another body', 'position a body in the scene by setting its left coordinate to a specific value', 'define a task goal using update_task with two bodies and a NOT_TOUCHING spatial relationship']
```

Usage

```
{'build_task_with_define_task': 'use the define_task decorator to register a build_task function that creates a PHYRE physics task', 'create_box_with_add_box': 'call C.add_box(width, height) to create a box body and chain set_bottom and set_left to position it', 'set_spatial_relationship': 'use C.update_task with body1, body2, and C.SpatialRelationship.LEFT_OF to define a spatial relationship task', 'position_body_with_setters': 'chain set_bottom, set_left, set_top, set_right on a Body to position it in the 256x256 scene', 'define_task_description': 'pass a description string to C.update_task to describe the task goal for the agent'}
```

## File: facebookresearch_phyre/data/task_scripts/tests/task_validation/task00002.py

Prompts

```
['use the define_task decorator to register a build_task function that creates a PHYRE physics task', 'call C.add_box(width, height) to create a box body and chain set_bottom and set_left to position it', 'use C.update_task with body1, body2, and C.SpatialRelationship.LEFT_OF to define a spatial relationship task', 'chain set_bottom, set_left, set_top, set_right on a Body to position it in the 256x256 scene', 'pass a description string to C.update_task to describe the task goal for the agent', 'use @define_task_template to generate multiple task variants from a parameterized build_task function', 'call C.update_task with body1, body2, and SpatialRelationship enum to define the task goal', 'review the build_task function to understand how boxes are positioned and spatial relationships are defined', 'use the define_task decorator to register a build_task function that creates a PHYRE spatial reasoning task', 'position a body by setting its bottom edge coordinate using the set_bottom method', 'position a body by setting its left edge coordinate using the set_left method', 'finalize a task by setting body references, spatial relationships, and a description string', 'call C.update_task with body1, body2, and a SpatialRelationship enum to define the task goal', 'use C.SpatialRelationship.TOUCHING to specify that two bodies should be touching in the task', 'chain set_bottom and set_left on a body to position it at specific coordinates in the scene', 'create boxes in a phyre scene using add_box with width and height parameters', 'position a body in the scene by setting its bottom coordinate relative to another body', 'position a body in the scene by setting its left coordinate to a specific value', 'define a task goal using update_task with two bodies and a NOT_TOUCHING spatial relationship']
```

Usage

```
{'build_task_with_define_task': 'use @define_task decorator to register a build_task function that creates a PHYRE spatial reasoning task', 'create_box_with_add_box': 'call C.add_box(width, height) to create a box body and chain set_bottom and set_left for positioning', 'set_spatial_relationship': 'use C.update_task with SpatialRelationship.RIGHT_OF to define a spatial relationship between two bodies', 'position_body_with_setters': 'chain set_bottom, set_left, set_top, set_right on a Body to position it in the 256x256 scene', 'define_task_template': 'use @define_task_template to generate multiple task variants from a parameterized build_task function'}
```

## File: facebookresearch_phyre/data/task_scripts/tests/task_validation/task00003.py

Prompts

```
['use the define_task decorator to register a build_task function that creates a PHYRE physics task', 'call C.add_box(width, height) to create a box body and chain set_bottom and set_left to position it', 'use C.update_task with body1, body2, and C.SpatialRelationship.LEFT_OF to define a spatial relationship task', 'chain set_bottom, set_left, set_top, set_right on a Body to position it in the 256x256 scene', 'pass a description string to C.update_task to describe the task goal for the agent', 'use @define_task_template to generate multiple task variants from a parameterized build_task function', 'call C.update_task with body1, body2, and SpatialRelationship enum to define the task goal', 'review the build_task function to understand how boxes are positioned and spatial relationships are defined', 'use the define_task decorator to register a build_task function that creates a PHYRE spatial reasoning task', 'position a body by setting its bottom edge coordinate using the set_bottom method', 'position a body by setting its left edge coordinate using the set_left method', 'finalize a task by setting body references, spatial relationships, and a description string', 'call C.update_task with body1, body2, and a SpatialRelationship enum to define the task goal', 'use C.SpatialRelationship.TOUCHING to specify that two bodies should be touching in the task', 'chain set_bottom and set_left on a body to position it at specific coordinates in the scene', 'create boxes in a phyre scene using add_box with width and height parameters', 'position a body in the scene by setting its bottom coordinate relative to another body', 'position a body in the scene by setting its left coordinate to a specific value', 'define a task goal using update_task with two bodies and a NOT_TOUCHING spatial relationship']
```

Usage

```
{'build_task_with_define_task': 'use the define_task decorator to register a build_task function that creates a PHYRE spatial reasoning task', 'create_box_with_add_box': 'call C.add_box with width and height to create a box body in the PHYRE scene', 'position_body_with_setters': 'chain set_bottom and set_left on a body to position it in the PHYRE scene', 'define_task_relationships': 'call C.update_task with body1, body2, and SpatialRelationship enum to define the task goal', 'review_build_task_function': 'review the build_task function to understand how boxes are positioned and spatial relationships are defined'}
```

## File: facebookresearch_phyre/data/task_scripts/tests/task_validation/task00004.py

Prompts

```
['use the define_task decorator to register a build_task function that creates a PHYRE physics task', 'call C.add_box(width, height) to create a box body and chain set_bottom and set_left to position it', 'use C.update_task with body1, body2, and C.SpatialRelationship.LEFT_OF to define a spatial relationship task', 'chain set_bottom, set_left, set_top, set_right on a Body to position it in the 256x256 scene', 'pass a description string to C.update_task to describe the task goal for the agent', 'use @define_task_template to generate multiple task variants from a parameterized build_task function', 'call C.update_task with body1, body2, and SpatialRelationship enum to define the task goal', 'review the build_task function to understand how boxes are positioned and spatial relationships are defined', 'use the define_task decorator to register a build_task function that creates a PHYRE spatial reasoning task', 'position a body by setting its bottom edge coordinate using the set_bottom method', 'position a body by setting its left edge coordinate using the set_left method', 'finalize a task by setting body references, spatial relationships, and a description string', 'call C.update_task with body1, body2, and a SpatialRelationship enum to define the task goal', 'use C.SpatialRelationship.TOUCHING to specify that two bodies should be touching in the task', 'chain set_bottom and set_left on a body to position it at specific coordinates in the scene', 'create boxes in a phyre scene using add_box with width and height parameters', 'position a body in the scene by setting its bottom coordinate relative to another body', 'position a body in the scene by setting its left coordinate to a specific value', 'define a task goal using update_task with two bodies and a NOT_TOUCHING spatial relationship']
```

Usage

```
{'build_task_with_define_task_decorator': 'use the define_task decorator to register a build_task function that creates a PHYRE spatial reasoning task', 'create_box_with_add_box': 'create a box body with specified width and height using the TaskCreator add_box method', 'position_body_with_set_bottom': 'position a body by setting its bottom edge coordinate using the set_bottom method', 'position_body_with_set_left': 'position a body by setting its left edge coordinate using the set_left method', 'finalize_task_with_update_task': 'finalize a task by setting body references, spatial relationships, and a description string'}
```

## File: facebookresearch_phyre/data/task_scripts/tests/task_validation/task00005.py

Prompts

```
['use the define_task decorator to register a build_task function that creates a PHYRE physics task', 'call C.add_box(width, height) to create a box body and chain set_bottom and set_left to position it', 'use C.update_task with body1, body2, and C.SpatialRelationship.LEFT_OF to define a spatial relationship task', 'chain set_bottom, set_left, set_top, set_right on a Body to position it in the 256x256 scene', 'pass a description string to C.update_task to describe the task goal for the agent', 'use @define_task_template to generate multiple task variants from a parameterized build_task function', 'call C.update_task with body1, body2, and SpatialRelationship enum to define the task goal', 'review the build_task function to understand how boxes are positioned and spatial relationships are defined', 'use the define_task decorator to register a build_task function that creates a PHYRE spatial reasoning task', 'position a body by setting its bottom edge coordinate using the set_bottom method', 'position a body by setting its left edge coordinate using the set_left method', 'finalize a task by setting body references, spatial relationships, and a description string', 'call C.update_task with body1, body2, and a SpatialRelationship enum to define the task goal', 'use C.SpatialRelationship.TOUCHING to specify that two bodies should be touching in the task', 'chain set_bottom and set_left on a body to position it at specific coordinates in the scene', 'create boxes in a phyre scene using add_box with width and height parameters', 'position a body in the scene by setting its bottom coordinate relative to another body', 'position a body in the scene by setting its left coordinate to a specific value', 'define a task goal using update_task with two bodies and a NOT_TOUCHING spatial relationship']
```

Usage

```
{'build_task_with_define_task': 'use the define_task decorator to register a build_task function that creates a PHYRE physics task', 'create_box_with_add_box': 'call C.add_box(width, height) to create a box body and chain set_bottom and set_left for positioning', 'update_task_with_relationships': 'call C.update_task with body1, body2, and a SpatialRelationship enum to define the task goal', 'create_task_with_spatial_relationship': 'use C.SpatialRelationship.TOUCHING to specify that two bodies should be touching in the task', 'position_bodies_with_setters': 'chain set_bottom and set_left on a body to position it at specific coordinates in the scene'}
```

## File: facebookresearch_phyre/data/task_scripts/tests/task_validation/task00006.py

Prompts

```
['use the define_task decorator to register a build_task function that creates a PHYRE physics task', 'call C.add_box(width, height) to create a box body and chain set_bottom and set_left to position it', 'use C.update_task with body1, body2, and C.SpatialRelationship.LEFT_OF to define a spatial relationship task', 'chain set_bottom, set_left, set_top, set_right on a Body to position it in the 256x256 scene', 'pass a description string to C.update_task to describe the task goal for the agent', 'use @define_task_template to generate multiple task variants from a parameterized build_task function', 'call C.update_task with body1, body2, and SpatialRelationship enum to define the task goal', 'review the build_task function to understand how boxes are positioned and spatial relationships are defined', 'use the define_task decorator to register a build_task function that creates a PHYRE spatial reasoning task', 'position a body by setting its bottom edge coordinate using the set_bottom method', 'position a body by setting its left edge coordinate using the set_left method', 'finalize a task by setting body references, spatial relationships, and a description string', 'call C.update_task with body1, body2, and a SpatialRelationship enum to define the task goal', 'use C.SpatialRelationship.TOUCHING to specify that two bodies should be touching in the task', 'chain set_bottom and set_left on a body to position it at specific coordinates in the scene', 'create boxes in a phyre scene using add_box with width and height parameters', 'position a body in the scene by setting its bottom coordinate relative to another body', 'position a body in the scene by setting its left coordinate to a specific value', 'define a task goal using update_task with two bodies and a NOT_TOUCHING spatial relationship']
```

Usage

```
{'build_task_with_define_task': 'build a phyre task using the define_task decorator to create a spatial reasoning scenario', 'create_boxes_with_add_box': 'create boxes in a phyre scene using add_box with width and height parameters', 'position_bodies_with_set_bottom': 'position a body in the scene by setting its bottom coordinate relative to another body', 'position_bodies_with_set_left': 'position a body in the scene by setting its left coordinate to a specific value', 'define_goal_with_update_task': 'define a task goal using update_task with two bodies and a NOT_TOUCHING spatial relationship'}
```

