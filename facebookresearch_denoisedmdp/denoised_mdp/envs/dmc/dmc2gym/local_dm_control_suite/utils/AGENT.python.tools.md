# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/utils/parse_amc.py

Prompts

```
['convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampling', 'parse an .amc motion capture file and return frame values as a list of numpy arrays', 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'convert euler angles in degrees to a quaternion array using zyx rotation order', 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings', 'test the ParseAMCTest class to verify parse_amc.convert produces correct qpos and qvel tensor shapes', 'run the ParseAMCTest test suite to validate AMC file parsing with different timesteps', 'review the parse_amc.convert function usage for converting AMC motion capture data to MuJoCo state arrays', 'test the humanoid_CMU.stand environment instantiation used as input to parse_amc.convert', 'summarize the ParseAMCTest class which validates AMC parsing output dimensions and timestep interpolation', 'randomize the positions of all joints in a MuJoCo physics model using uniform sampling', 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'randomize hinge joint positions uniformly within their bounded or unbounded range', 'randomize ball joint orientations by sampling quaternions on the unit 3-sphere', 'review the randomizers module to understand joint randomization rules for hinges sliders balls and free joints', 'test the randomize_limited_and_rotational_joints function with a MuJoCo physics object and numpy RandomState', 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test that multiple hinge joints of the same type receive unique randomized positions', 'test that unlimited hinge joint randomization stays within negative pi to positive pi bounds', 'test that limited hinge and slide joints respect their configured range constraints during randomization']
```

Usage

```
{'convert_amc_to_qpos_qvel': 'convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampling', 'parse_amc_file': 'parse an .amc motion capture file and return frame values as a list of numpy arrays', 'create_amcvals2qpos_transformer': 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'convert_euler_to_quat': 'convert euler angles in degrees to a quaternion array using zyx rotation order', 'compute_quat_difference': 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/utils/parse_amc_test.py

Prompts

```
['convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampling', 'parse an .amc motion capture file and return frame values as a list of numpy arrays', 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'convert euler angles in degrees to a quaternion array using zyx rotation order', 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings', 'test the ParseAMCTest class to verify parse_amc.convert produces correct qpos and qvel tensor shapes', 'run the ParseAMCTest test suite to validate AMC file parsing with different timesteps', 'review the parse_amc.convert function usage for converting AMC motion capture data to MuJoCo state arrays', 'test the humanoid_CMU.stand environment instantiation used as input to parse_amc.convert', 'summarize the ParseAMCTest class which validates AMC parsing output dimensions and timestep interpolation', 'randomize the positions of all joints in a MuJoCo physics model using uniform sampling', 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'randomize hinge joint positions uniformly within their bounded or unbounded range', 'randomize ball joint orientations by sampling quaternions on the unit 3-sphere', 'review the randomizers module to understand joint randomization rules for hinges sliders balls and free joints', 'test the randomize_limited_and_rotational_joints function with a MuJoCo physics object and numpy RandomState', 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test that multiple hinge joints of the same type receive unique randomized positions', 'test that unlimited hinge joint randomization stays within negative pi to positive pi bounds', 'test that limited hinge and slide joints respect their configured range constraints during randomization']
```

Usage

```
{'test_parse_amc_convert': 'test the ParseAMCTest class to verify parse_amc.convert produces correct qpos and qvel tensor shapes', 'run_parse_amc_test': 'run the ParseAMCTest test suite to validate AMC file parsing with different timesteps', 'review_parse_amc_convert': 'review the parse_amc.convert function usage for converting AMC motion capture data to MuJoCo state arrays', 'test_humanoid_CMU_stand': 'test the humanoid_CMU.stand environment instantiation used as input to parse_amc.convert', 'summarize_parse_amc_test': 'summarize the ParseAMCTest class which validates AMC parsing output dimensions and timestep interpolation'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/utils/randomizers.py

Prompts

```
['convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampling', 'parse an .amc motion capture file and return frame values as a list of numpy arrays', 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'convert euler angles in degrees to a quaternion array using zyx rotation order', 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings', 'test the ParseAMCTest class to verify parse_amc.convert produces correct qpos and qvel tensor shapes', 'run the ParseAMCTest test suite to validate AMC file parsing with different timesteps', 'review the parse_amc.convert function usage for converting AMC motion capture data to MuJoCo state arrays', 'test the humanoid_CMU.stand environment instantiation used as input to parse_amc.convert', 'summarize the ParseAMCTest class which validates AMC parsing output dimensions and timestep interpolation', 'randomize the positions of all joints in a MuJoCo physics model using uniform sampling', 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'randomize hinge joint positions uniformly within their bounded or unbounded range', 'randomize ball joint orientations by sampling quaternions on the unit 3-sphere', 'review the randomizers module to understand joint randomization rules for hinges sliders balls and free joints', 'test the randomize_limited_and_rotational_joints function with a MuJoCo physics object and numpy RandomState', 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test that multiple hinge joints of the same type receive unique randomized positions', 'test that unlimited hinge joint randomization stays within negative pi to positive pi bounds', 'test that limited hinge and slide joints respect their configured range constraints during randomization']
```

Usage

```
{'randomize_joints_in_physics_model': 'randomize the positions of all joints in a MuJoCo physics model using uniform sampling', 'generate_limited_quaternion': 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'randomize_hinge_joints': 'randomize hinge joint positions uniformly within their bounded or unbounded range', 'randomize_ball_joints': 'randomize ball joint orientations by sampling quaternions on the unit 3-sphere', 'review_randomizer_module': 'review the randomizers module to understand joint randomization rules for hinges sliders balls and free joints'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/dmc/dmc2gym/local_dm_control_suite/utils/randomizers_test.py

Prompts

```
['convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampling', 'parse an .amc motion capture file and return frame values as a list of numpy arrays', 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'convert euler angles in degrees to a quaternion array using zyx rotation order', 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings', 'test the ParseAMCTest class to verify parse_amc.convert produces correct qpos and qvel tensor shapes', 'run the ParseAMCTest test suite to validate AMC file parsing with different timesteps', 'review the parse_amc.convert function usage for converting AMC motion capture data to MuJoCo state arrays', 'test the humanoid_CMU.stand environment instantiation used as input to parse_amc.convert', 'summarize the ParseAMCTest class which validates AMC parsing output dimensions and timestep interpolation', 'randomize the positions of all joints in a MuJoCo physics model using uniform sampling', 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'randomize hinge joint positions uniformly within their bounded or unbounded range', 'randomize ball joint orientations by sampling quaternions on the unit 3-sphere', 'review the randomizers module to understand joint randomization rules for hinges sliders balls and free joints', 'test the randomize_limited_and_rotational_joints function with a MuJoCo physics object and numpy RandomState', 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test that multiple hinge joints of the same type receive unique randomized positions', 'test that unlimited hinge joint randomization stays within negative pi to positive pi bounds', 'test that limited hinge and slide joints respect their configured range constraints during randomization']
```

Usage

```
{'test_randomize_limited_and_rotational_joints': 'test the randomize_limited_and_rotational_joints function with a MuJoCo physics object and numpy RandomState', 'test_single_joint_of_each_type': 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test_multiple_joints_of_same_type': 'test that multiple hinge joints of the same type receive unique randomized positions', 'test_unlimited_hinge_randomization_range': 'test that unlimited hinge joint randomization stays within negative pi to positive pi bounds', 'test_limited_joint_limits': 'test that limited hinge and slide joints respect their configured range constraints during randomization'}
```

