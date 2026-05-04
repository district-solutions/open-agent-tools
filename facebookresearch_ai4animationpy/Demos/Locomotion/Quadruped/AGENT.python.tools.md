# Agent Python Tools

- repo: facebookresearch/ai4animationpy
- repo_uri: https://github.com/facebookresearch/ai4animationpy

## File: facebookresearch_ai4animationpy/Demos/Locomotion/Quadruped/Editor.py

Prompts

```
['run the quadruped motion editor demo with a dog GLB model and motion dataset', 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for quadruped animation', 'configure a RootModule with QUADRUPED topology using hip, shoulder, and neck bone names', 'setup a ContactModule with hand and foot site names, radius, and weight parameters', 'add a MotionEditor component to an entity with a dataset, GLB model, and full body bone names', 'create a LegIK solver from a FABRIK IK chain for quadruped leg inverse kinematics', 'solve the LegIK chain with a contact weight, max iterations, and accuracy threshold', 'review the LegIK class and how it stores the end effector baseline Y position', 'refactor the LegIK Solve method to support additional bone constraints or damping parameters', 'test the LegIK class by interpolating target position with Vector3.Lerp during contact phases', 'run the quadruped locomotion demo with AI-driven motion control for dog and wolf characters', 'create an actor entity from a GLB model file using AI4Animation Scene and Actor components', 'copy bone transforms and velocities from a source actor to a target actor in the scene', 'configure FABRIK inverse kinematics solvers for the left and right hand and foot bones of an actor', 'switch between dog and wolf character models while preserving the current actor pose and state', 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample interpolated joint positions at a timestamp using Sequence.SamplePositions', 'sample interpolated joint rotations at a timestamp using Sequence.SampleRotations', 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw all skeleton frames in a sequence using Sequence.Draw with an actor']
```

Usage

```
{'run_quadruped_motion_editor': 'run the quadruped motion editor demo with a dog GLB model and motion dataset', 'create_dataset_with_modules': 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for quadruped animation', 'configure_root_module_quadruped': 'configure a RootModule with QUADRUPED topology using hip, shoulder, and neck bone names', 'setup_contact_module': 'setup a ContactModule with hand and foot site names, radius, and weight parameters', 'add_motion_editor_component': 'add a MotionEditor component to an entity with a dataset, GLB model, and full body bone names'}
```

## File: facebookresearch_ai4animationpy/Demos/Locomotion/Quadruped/LegIK.py

Prompts

```
['run the quadruped motion editor demo with a dog GLB model and motion dataset', 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for quadruped animation', 'configure a RootModule with QUADRUPED topology using hip, shoulder, and neck bone names', 'setup a ContactModule with hand and foot site names, radius, and weight parameters', 'add a MotionEditor component to an entity with a dataset, GLB model, and full body bone names', 'create a LegIK solver from a FABRIK IK chain for quadruped leg inverse kinematics', 'solve the LegIK chain with a contact weight, max iterations, and accuracy threshold', 'review the LegIK class and how it stores the end effector baseline Y position', 'refactor the LegIK Solve method to support additional bone constraints or damping parameters', 'test the LegIK class by interpolating target position with Vector3.Lerp during contact phases', 'run the quadruped locomotion demo with AI-driven motion control for dog and wolf characters', 'create an actor entity from a GLB model file using AI4Animation Scene and Actor components', 'copy bone transforms and velocities from a source actor to a target actor in the scene', 'configure FABRIK inverse kinematics solvers for the left and right hand and foot bones of an actor', 'switch between dog and wolf character models while preserving the current actor pose and state', 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample interpolated joint positions at a timestamp using Sequence.SamplePositions', 'sample interpolated joint rotations at a timestamp using Sequence.SampleRotations', 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw all skeleton frames in a sequence using Sequence.Draw with an actor']
```

Usage

```
{'create_LegIK_solver': 'create a LegIK solver from a FABRIK IK chain for quadruped leg inverse kinematics', 'solve_LegIK_with_contact': 'solve the LegIK chain with a contact weight, max iterations, and accuracy threshold', 'review_LegIK_EEBaseline': 'review the LegIK class and how it stores the end effector baseline Y position', 'refactor_LegIK_Solve': 'refactor the LegIK Solve method to support additional bone constraints or damping parameters', 'test_LegIK_target_interpolation': 'test the LegIK class by interpolating target position with Vector3.Lerp during contact phases'}
```

## File: facebookresearch_ai4animationpy/Demos/Locomotion/Quadruped/Program.py

Prompts

```
['run the quadruped motion editor demo with a dog GLB model and motion dataset', 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for quadruped animation', 'configure a RootModule with QUADRUPED topology using hip, shoulder, and neck bone names', 'setup a ContactModule with hand and foot site names, radius, and weight parameters', 'add a MotionEditor component to an entity with a dataset, GLB model, and full body bone names', 'create a LegIK solver from a FABRIK IK chain for quadruped leg inverse kinematics', 'solve the LegIK chain with a contact weight, max iterations, and accuracy threshold', 'review the LegIK class and how it stores the end effector baseline Y position', 'refactor the LegIK Solve method to support additional bone constraints or damping parameters', 'test the LegIK class by interpolating target position with Vector3.Lerp during contact phases', 'run the quadruped locomotion demo with AI-driven motion control for dog and wolf characters', 'create an actor entity from a GLB model file using AI4Animation Scene and Actor components', 'copy bone transforms and velocities from a source actor to a target actor in the scene', 'configure FABRIK inverse kinematics solvers for the left and right hand and foot bones of an actor', 'switch between dog and wolf character models while preserving the current actor pose and state', 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample interpolated joint positions at a timestamp using Sequence.SamplePositions', 'sample interpolated joint rotations at a timestamp using Sequence.SampleRotations', 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw all skeleton frames in a sequence using Sequence.Draw with an actor']
```

Usage

```
{'run_quadruped_locomotion_demo': 'run the quadruped locomotion demo with AI-driven motion control for dog and wolf characters', 'create_actor_with_model': 'create an actor entity from a GLB model file using AI4Animation Scene and Actor components', 'copy_actor_state': 'copy bone transforms and velocities from a source actor to a target actor in the scene', 'configure_actor_ik_bindings': 'configure FABRIK inverse kinematics solvers for the left and right hand and foot bones of an actor', 'switch_character_model': 'switch between dog and wolf character models while preserving the current actor pose and state'}
```

## File: facebookresearch_ai4animationpy/Demos/Locomotion/Quadruped/Sequence.py

Prompts

```
['run the quadruped motion editor demo with a dog GLB model and motion dataset', 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for quadruped animation', 'configure a RootModule with QUADRUPED topology using hip, shoulder, and neck bone names', 'setup a ContactModule with hand and foot site names, radius, and weight parameters', 'add a MotionEditor component to an entity with a dataset, GLB model, and full body bone names', 'create a LegIK solver from a FABRIK IK chain for quadruped leg inverse kinematics', 'solve the LegIK chain with a contact weight, max iterations, and accuracy threshold', 'review the LegIK class and how it stores the end effector baseline Y position', 'refactor the LegIK Solve method to support additional bone constraints or damping parameters', 'test the LegIK class by interpolating target position with Vector3.Lerp during contact phases', 'run the quadruped locomotion demo with AI-driven motion control for dog and wolf characters', 'create an actor entity from a GLB model file using AI4Animation Scene and Actor components', 'copy bone transforms and velocities from a source actor to a target actor in the scene', 'configure FABRIK inverse kinematics solvers for the left and right hand and foot bones of an actor', 'switch between dog and wolf character models while preserving the current actor pose and state', 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample interpolated joint positions at a timestamp using Sequence.SamplePositions', 'sample interpolated joint rotations at a timestamp using Sequence.SampleRotations', 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw all skeleton frames in a sequence using Sequence.Draw with an actor']
```

Usage

```
{'sample_root_transform': 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample_positions': 'sample interpolated joint positions at a timestamp using Sequence.SamplePositions', 'sample_rotations': 'sample interpolated joint rotations at a timestamp using Sequence.SampleRotations', 'sample_velocities': 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw_skeleton_sequence': 'draw all skeleton frames in a sequence using Sequence.Draw with an actor'}
```

