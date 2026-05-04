# Agent Python Tools

- repo: facebookresearch/ai4animationpy
- repo_uri: https://github.com/facebookresearch/ai4animationpy

## File: facebookresearch_ai4animationpy/ai4animation/Components/Actor.py

Prompts

```
['create an Actor component from an FBX or GLB 3D model file with optional bone names and GUI toggle', 'get bone transforms, positions, and rotations by name, Bone object, or integer index list', 'set custom bone lengths or restore default bone lengths and alignments on an Actor skeleton', 'traverse the bone parent-child hierarchy using GetChain, PrintSuccessors, and SetParent on Actor.Bone objects', 'sync Actor bone transforms to and from the AI4Animation scene entities with optional root transform', 'create a subclass of Component that overrides Start and Update for custom entity behavior', 'review the Component ABC lifecycle hooks including Start Update Draw and GUI methods', 'refactor the Component class to remove the duplicate Standalone method definition', 'summarize the Component abstract base class and its entity lifecycle hook pattern', 'test a Component subclass to verify Start is called with params during initialization', 'build a python module that registers a 3D model using AI4Animation RenderPipeline RegisterModel with an entity name and model file path', 'create a function that syncs an entity position rotation and scale to a registered 3D model using Vector3 ToRayLib', 'build a python module that converts a quaternion from a rotation matrix to angle and axis using Quaternion ToAngleAxis', 'create a MeshRenderer component subclass that registers a model on Start and updates its transform each frame in Update', 'review the MeshRenderer Update method to understand how entity transforms are synced to the RayLib model each frame', 'build a MotionEditor component that loads motion data and displays an actor with bone transforms', 'create a standalone GUI with sliders and buttons to scrub through motion capture data', 'test the LoadMotion method to load a motion clip from a dataset by index', 'review the WriteActor method that sets bone transformations and velocities on an actor entity', 'refactor the LoadFrame method to support custom timestamp interpolation and module callbacks']
```

Usage

```
{'create_actor_from_fbx_or_glb': 'create an Actor component from an FBX or GLB 3D model file with optional bone names and GUI toggle', 'get_bone_transforms_and_positions': 'get bone transforms, positions, and rotations by name, Bone object, or integer index list', 'set_bone_lengths_and_restore': 'set custom bone lengths or restore default bone lengths and alignments on an Actor skeleton', 'traverse_bone_hierarchy': 'traverse the bone parent-child hierarchy using GetChain, PrintSuccessors, and SetParent on Actor.Bone objects', 'sync_actor_to_scene': 'sync Actor bone transforms to and from the AI4Animation scene entities with optional root transform'}
```

## File: facebookresearch_ai4animationpy/ai4animation/Components/Component.py

Prompts

```
['create an Actor component from an FBX or GLB 3D model file with optional bone names and GUI toggle', 'get bone transforms, positions, and rotations by name, Bone object, or integer index list', 'set custom bone lengths or restore default bone lengths and alignments on an Actor skeleton', 'traverse the bone parent-child hierarchy using GetChain, PrintSuccessors, and SetParent on Actor.Bone objects', 'sync Actor bone transforms to and from the AI4Animation scene entities with optional root transform', 'create a subclass of Component that overrides Start and Update for custom entity behavior', 'review the Component ABC lifecycle hooks including Start Update Draw and GUI methods', 'refactor the Component class to remove the duplicate Standalone method definition', 'summarize the Component abstract base class and its entity lifecycle hook pattern', 'test a Component subclass to verify Start is called with params during initialization', 'build a python module that registers a 3D model using AI4Animation RenderPipeline RegisterModel with an entity name and model file path', 'create a function that syncs an entity position rotation and scale to a registered 3D model using Vector3 ToRayLib', 'build a python module that converts a quaternion from a rotation matrix to angle and axis using Quaternion ToAngleAxis', 'create a MeshRenderer component subclass that registers a model on Start and updates its transform each frame in Update', 'review the MeshRenderer Update method to understand how entity transforms are synced to the RayLib model each frame', 'build a MotionEditor component that loads motion data and displays an actor with bone transforms', 'create a standalone GUI with sliders and buttons to scrub through motion capture data', 'test the LoadMotion method to load a motion clip from a dataset by index', 'review the WriteActor method that sets bone transformations and velocities on an actor entity', 'refactor the LoadFrame method to support custom timestamp interpolation and module callbacks']
```

Usage

```
{'create_component_subclass': 'create a subclass of Component that overrides Start and Update for custom entity behavior', 'review_component_lifecycle': 'review the Component ABC lifecycle hooks including Start Update Draw and GUI methods', 'refactor_component_standalone': 'refactor the Component class to remove the duplicate Standalone method definition', 'summarize_component_abc': 'summarize the Component abstract base class and its entity lifecycle hook pattern', 'test_component_subclass': 'test a Component subclass to verify Start is called with params during initialization'}
```

## File: facebookresearch_ai4animationpy/ai4animation/Components/MeshRenderer.py

Prompts

```
['create an Actor component from an FBX or GLB 3D model file with optional bone names and GUI toggle', 'get bone transforms, positions, and rotations by name, Bone object, or integer index list', 'set custom bone lengths or restore default bone lengths and alignments on an Actor skeleton', 'traverse the bone parent-child hierarchy using GetChain, PrintSuccessors, and SetParent on Actor.Bone objects', 'sync Actor bone transforms to and from the AI4Animation scene entities with optional root transform', 'create a subclass of Component that overrides Start and Update for custom entity behavior', 'review the Component ABC lifecycle hooks including Start Update Draw and GUI methods', 'refactor the Component class to remove the duplicate Standalone method definition', 'summarize the Component abstract base class and its entity lifecycle hook pattern', 'test a Component subclass to verify Start is called with params during initialization', 'build a python module that registers a 3D model using AI4Animation RenderPipeline RegisterModel with an entity name and model file path', 'create a function that syncs an entity position rotation and scale to a registered 3D model using Vector3 ToRayLib', 'build a python module that converts a quaternion from a rotation matrix to angle and axis using Quaternion ToAngleAxis', 'create a MeshRenderer component subclass that registers a model on Start and updates its transform each frame in Update', 'review the MeshRenderer Update method to understand how entity transforms are synced to the RayLib model each frame', 'build a MotionEditor component that loads motion data and displays an actor with bone transforms', 'create a standalone GUI with sliders and buttons to scrub through motion capture data', 'test the LoadMotion method to load a motion clip from a dataset by index', 'review the WriteActor method that sets bone transformations and velocities on an actor entity', 'refactor the LoadFrame method to support custom timestamp interpolation and module callbacks']
```

Usage

```
{'register_3d_model': 'build a python module that registers a 3D model using AI4Animation RenderPipeline RegisterModel with an entity name and model file path', 'sync_entity_transform_to_model': 'create a function that syncs an entity position rotation and scale to a registered 3D model using Vector3 ToRayLib', 'convert_quaternion_to_angle_axis': 'build a python module that converts a quaternion from a rotation matrix to angle and axis using Quaternion ToAngleAxis', 'create_mesh_renderer_component': 'create a MeshRenderer component subclass that registers a model on Start and updates its transform each frame in Update', 'review_MeshRenderer_Update': 'review the MeshRenderer Update method to understand how entity transforms are synced to the RayLib model each frame'}
```

## File: facebookresearch_ai4animationpy/ai4animation/Components/MotionEditor.py

Prompts

```
['create an Actor component from an FBX or GLB 3D model file with optional bone names and GUI toggle', 'get bone transforms, positions, and rotations by name, Bone object, or integer index list', 'set custom bone lengths or restore default bone lengths and alignments on an Actor skeleton', 'traverse the bone parent-child hierarchy using GetChain, PrintSuccessors, and SetParent on Actor.Bone objects', 'sync Actor bone transforms to and from the AI4Animation scene entities with optional root transform', 'create a subclass of Component that overrides Start and Update for custom entity behavior', 'review the Component ABC lifecycle hooks including Start Update Draw and GUI methods', 'refactor the Component class to remove the duplicate Standalone method definition', 'summarize the Component abstract base class and its entity lifecycle hook pattern', 'test a Component subclass to verify Start is called with params during initialization', 'build a python module that registers a 3D model using AI4Animation RenderPipeline RegisterModel with an entity name and model file path', 'create a function that syncs an entity position rotation and scale to a registered 3D model using Vector3 ToRayLib', 'build a python module that converts a quaternion from a rotation matrix to angle and axis using Quaternion ToAngleAxis', 'create a MeshRenderer component subclass that registers a model on Start and updates its transform each frame in Update', 'review the MeshRenderer Update method to understand how entity transforms are synced to the RayLib model each frame', 'build a MotionEditor component that loads motion data and displays an actor with bone transforms', 'create a standalone GUI with sliders and buttons to scrub through motion capture data', 'test the LoadMotion method to load a motion clip from a dataset by index', 'review the WriteActor method that sets bone transformations and velocities on an actor entity', 'refactor the LoadFrame method to support custom timestamp interpolation and module callbacks']
```

Usage

```
{'build_motion_editor_component': 'build a MotionEditor component that loads motion data and displays an actor with bone transforms', 'create_motion_editor_gui': 'create a standalone GUI with sliders and buttons to scrub through motion capture data', 'test_LoadMotion': 'test the LoadMotion method to load a motion clip from a dataset by index', 'review_WriteActor': 'review the WriteActor method that sets bone transformations and velocities on an actor entity', 'refactor_LoadFrame': 'refactor the LoadFrame method to support custom timestamp interpolation and module callbacks'}
```

