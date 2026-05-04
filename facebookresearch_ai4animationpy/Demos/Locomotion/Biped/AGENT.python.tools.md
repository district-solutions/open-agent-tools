# Agent Python Tools

- repo: facebookresearch/ai4animationpy
- repo_uri: https://github.com/facebookresearch/ai4animationpy

## File: facebookresearch_ai4animationpy/Demos/Locomotion/Biped/Editor.py

Prompts

```
['run the biped motion editor demo by executing Editor.py to launch the AI4Animation scene', 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for biped motion editing', 'add a MotionEditor entity to the AI4Animation scene using Scene.AddEntity', 'configure a ContactModule with ankle and ball joint contact parameters for left and right feet', 'set the standalone camera target to the MotionEditor entity using Camera.SetTarget', 'build a python module to create a LegIK solver with ankle and ball FABRIK chains for bipedal locomotion', 'run the LegIK Solve method to compute inverse kinematics for both ankle and ball contact points', 'create a function that solves ankle IK using contact weight, pole target, and pole weight parameters', 'test the SolveBall method to enforce ankle-ball distance constraints while solving ball IK', 'review the LegIK constructor to understand how baseline positions and target rotations are initialized', 'run the biped locomotion demo program with AI4Animation to animate a bipedal character using neural network predictions', 'create an Actor entity from a GLB model file with full body bone names using AI4Animation Scene', 'build a LegIK solver using FABRIK for hip-to-ankle and ankle-to-ball bone chains to solve foot contact', 'predict a future motion sequence by feeding actor transforms, velocities, and guidance into a PyTorch neural network model', 'animate a bipedal character by blending predicted motion sequences with IK solvers and guidance templates for style control', 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample interpolated 3D positions at a timestamp using Sequence.SamplePositions', 'sample interpolated rotations at a timestamp using Sequence.SampleRotations', 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw the skeleton at all timestamps using Sequence.Draw with an actor']
```

Usage

```
{'run_motion_editor': 'run the biped motion editor demo by executing Editor.py to launch the AI4Animation scene', 'create_dataset_with_modules': 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for biped motion editing', 'add_motion_editor_entity': 'add a MotionEditor entity to the AI4Animation scene using Scene.AddEntity', 'configure_contact_module': 'configure a ContactModule with ankle and ball joint contact parameters for left and right feet', 'set_camera_target': 'set the standalone camera target to the MotionEditor entity using Camera.SetTarget'}
```

## File: facebookresearch_ai4animationpy/Demos/Locomotion/Biped/LegIK.py

Prompts

```
['run the biped motion editor demo by executing Editor.py to launch the AI4Animation scene', 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for biped motion editing', 'add a MotionEditor entity to the AI4Animation scene using Scene.AddEntity', 'configure a ContactModule with ankle and ball joint contact parameters for left and right feet', 'set the standalone camera target to the MotionEditor entity using Camera.SetTarget', 'build a python module to create a LegIK solver with ankle and ball FABRIK chains for bipedal locomotion', 'run the LegIK Solve method to compute inverse kinematics for both ankle and ball contact points', 'create a function that solves ankle IK using contact weight, pole target, and pole weight parameters', 'test the SolveBall method to enforce ankle-ball distance constraints while solving ball IK', 'review the LegIK constructor to understand how baseline positions and target rotations are initialized', 'run the biped locomotion demo program with AI4Animation to animate a bipedal character using neural network predictions', 'create an Actor entity from a GLB model file with full body bone names using AI4Animation Scene', 'build a LegIK solver using FABRIK for hip-to-ankle and ankle-to-ball bone chains to solve foot contact', 'predict a future motion sequence by feeding actor transforms, velocities, and guidance into a PyTorch neural network model', 'animate a bipedal character by blending predicted motion sequences with IK solvers and guidance templates for style control', 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample interpolated 3D positions at a timestamp using Sequence.SamplePositions', 'sample interpolated rotations at a timestamp using Sequence.SampleRotations', 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw the skeleton at all timestamps using Sequence.Draw with an actor']
```

Usage

```
{'build_LegIK_solver': 'build a python module to create a LegIK solver with ankle and ball FABRIK chains for bipedal locomotion', 'run_LegIK_Solve': 'run the LegIK Solve method to compute inverse kinematics for both ankle and ball contact points', 'create_LegIK_SolveAnkle': 'create a function that solves ankle IK using contact weight, pole target, and pole weight parameters', 'test_LegIK_SolveBall': 'test the SolveBall method to enforce ankle-ball distance constraints while solving ball IK', 'review_LegIK_init': 'review the LegIK constructor to understand how baseline positions and target rotations are initialized'}
```

## File: facebookresearch_ai4animationpy/Demos/Locomotion/Biped/Program.py

Prompts

```
['run the biped motion editor demo by executing Editor.py to launch the AI4Animation scene', 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for biped motion editing', 'add a MotionEditor entity to the AI4Animation scene using Scene.AddEntity', 'configure a ContactModule with ankle and ball joint contact parameters for left and right feet', 'set the standalone camera target to the MotionEditor entity using Camera.SetTarget', 'build a python module to create a LegIK solver with ankle and ball FABRIK chains for bipedal locomotion', 'run the LegIK Solve method to compute inverse kinematics for both ankle and ball contact points', 'create a function that solves ankle IK using contact weight, pole target, and pole weight parameters', 'test the SolveBall method to enforce ankle-ball distance constraints while solving ball IK', 'review the LegIK constructor to understand how baseline positions and target rotations are initialized', 'run the biped locomotion demo program with AI4Animation to animate a bipedal character using neural network predictions', 'create an Actor entity from a GLB model file with full body bone names using AI4Animation Scene', 'build a LegIK solver using FABRIK for hip-to-ankle and ankle-to-ball bone chains to solve foot contact', 'predict a future motion sequence by feeding actor transforms, velocities, and guidance into a PyTorch neural network model', 'animate a bipedal character by blending predicted motion sequences with IK solvers and guidance templates for style control', 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample interpolated 3D positions at a timestamp using Sequence.SamplePositions', 'sample interpolated rotations at a timestamp using Sequence.SampleRotations', 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw the skeleton at all timestamps using Sequence.Draw with an actor']
```

Usage

```
{'run_biped_locomotion_demo': 'run the biped locomotion demo program with AI4Animation to animate a bipedal character using neural network predictions', 'create_actor_with_model': 'create an Actor entity from a GLB model file with full body bone names using AI4Animation Scene', 'build_leg_ik_solver': 'build a LegIK solver using FABRIK for hip-to-ankle and ankle-to-ball bone chains to solve foot contact', 'predict_motion_sequence': 'predict a future motion sequence by feeding actor transforms, velocities, and guidance into a PyTorch neural network model', 'animate_character_with_guidance': 'animate a bipedal character by blending predicted motion sequences with IK solvers and guidance templates for style control'}
```

## File: facebookresearch_ai4animationpy/Demos/Locomotion/Biped/Sequence.py

Prompts

```
['run the biped motion editor demo by executing Editor.py to launch the AI4Animation scene', 'create a Dataset with RootModule, MotionModule, ContactModule, GuidanceModule, and MirrorModule for biped motion editing', 'add a MotionEditor entity to the AI4Animation scene using Scene.AddEntity', 'configure a ContactModule with ankle and ball joint contact parameters for left and right feet', 'set the standalone camera target to the MotionEditor entity using Camera.SetTarget', 'build a python module to create a LegIK solver with ankle and ball FABRIK chains for bipedal locomotion', 'run the LegIK Solve method to compute inverse kinematics for both ankle and ball contact points', 'create a function that solves ankle IK using contact weight, pole target, and pole weight parameters', 'test the SolveBall method to enforce ankle-ball distance constraints while solving ball IK', 'review the LegIK constructor to understand how baseline positions and target rotations are initialized', 'run the biped locomotion demo program with AI4Animation to animate a bipedal character using neural network predictions', 'create an Actor entity from a GLB model file with full body bone names using AI4Animation Scene', 'build a LegIK solver using FABRIK for hip-to-ankle and ankle-to-ball bone chains to solve foot contact', 'predict a future motion sequence by feeding actor transforms, velocities, and guidance into a PyTorch neural network model', 'animate a bipedal character by blending predicted motion sequences with IK solvers and guidance templates for style control', 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample interpolated 3D positions at a timestamp using Sequence.SamplePositions', 'sample interpolated rotations at a timestamp using Sequence.SampleRotations', 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw the skeleton at all timestamps using Sequence.Draw with an actor']
```

Usage

```
{'sample_root_transform': 'sample the root transform at a given timestamp using Sequence.SampleRoot', 'sample_positions': 'sample interpolated 3D positions at a timestamp using Sequence.SamplePositions', 'sample_rotations': 'sample interpolated rotations at a timestamp using Sequence.SampleRotations', 'sample_velocities': 'sample interpolated velocities at a timestamp using Sequence.SampleVelocities', 'draw_skeleton_sequence': 'draw the skeleton at all timestamps using Sequence.Draw with an actor'}
```

