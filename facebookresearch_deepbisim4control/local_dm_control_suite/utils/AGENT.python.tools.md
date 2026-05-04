# Agent Python Tools

- repo: facebookresearch/deepbisim4control
- repo_uri: https://github.com/facebookresearch/deep_bisim4control

## File: facebookresearch_deepbisim4control/local_dm_control_suite/utils/parse_amc.py

Prompts

```
['convert an AMC motion capture file to MuJoCo qpos and qvel values with resampling', 'parse an AMC motion capture file and return frame values as numpy arrays', 'create an Amcvals2qpos callable to convert AMC frame values to MuJoCo qpos format', 'convert euler angles in degrees to a quaternion using zyx rotation order', 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings', 'test the parse_amc.convert function to verify qpos and qvel array shapes for a humanoid AMC clip', 'run the ParseAMCTest unit test suite to validate AMC motion capture data parsing and conversion', 'test parse_amc.convert with a smaller timestep to verify doubled frame count in parsed data', 'review the ParseAMCTest class and its test_sizes_of_parsed_data method for AMC parsing assertions', 'summarize how parse_amc.convert is called with an AMC file path, physics model, and control timestep', 'generate a random quaternion limited to a specified rotation angle using a random state and limit', 'randomize the positions of all joints in a MuJoCo physics body including hinges sliders balls and free joints', 'test the random_limited_quaternion function by generating quaternions with various angle limits and verifying norms', 'test the randomize_limited_and_rotational_joints function on a MuJoCo physics model with mixed joint types', 'refactor the randomize_limited_and_rotational_joints function to support additional joint types or custom randomization distributions', 'run the randomizers test suite to validate joint randomization for hinge, slide, ball, and free joint types', 'review the RandomizeUnlimitedJointsTest class to understand how limited and rotational joint randomization is tested', 'test that limited hinge and slide joints respect their configured range constraints during randomization', 'test that limited ball joints respect angular range constraints using quaternion rotation verification']
```

Usage

```
{'convert_amc_to_mujoco': 'convert an AMC motion capture file to MuJoCo qpos and qvel values with resampling', 'parse_amc_file': 'parse an AMC motion capture file and return frame values as numpy arrays', 'create_amcvals2qpos_transformer': 'create an Amcvals2qpos callable to convert AMC frame values to MuJoCo qpos format', 'convert_euler_to_quaternion': 'convert euler angles in degrees to a quaternion using zyx rotation order', 'compute_quaternion_difference': 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings'}
```

## File: facebookresearch_deepbisim4control/local_dm_control_suite/utils/parse_amc_test.py

Prompts

```
['convert an AMC motion capture file to MuJoCo qpos and qvel values with resampling', 'parse an AMC motion capture file and return frame values as numpy arrays', 'create an Amcvals2qpos callable to convert AMC frame values to MuJoCo qpos format', 'convert euler angles in degrees to a quaternion using zyx rotation order', 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings', 'test the parse_amc.convert function to verify qpos and qvel array shapes for a humanoid AMC clip', 'run the ParseAMCTest unit test suite to validate AMC motion capture data parsing and conversion', 'test parse_amc.convert with a smaller timestep to verify doubled frame count in parsed data', 'review the ParseAMCTest class and its test_sizes_of_parsed_data method for AMC parsing assertions', 'summarize how parse_amc.convert is called with an AMC file path, physics model, and control timestep', 'generate a random quaternion limited to a specified rotation angle using a random state and limit', 'randomize the positions of all joints in a MuJoCo physics body including hinges sliders balls and free joints', 'test the random_limited_quaternion function by generating quaternions with various angle limits and verifying norms', 'test the randomize_limited_and_rotational_joints function on a MuJoCo physics model with mixed joint types', 'refactor the randomize_limited_and_rotational_joints function to support additional joint types or custom randomization distributions', 'run the randomizers test suite to validate joint randomization for hinge, slide, ball, and free joint types', 'review the RandomizeUnlimitedJointsTest class to understand how limited and rotational joint randomization is tested', 'test that limited hinge and slide joints respect their configured range constraints during randomization', 'test that limited ball joints respect angular range constraints using quaternion rotation verification']
```

Usage

```
{'test_parse_amc_convert': 'test the parse_amc.convert function to verify qpos and qvel array shapes for a humanoid AMC clip', 'run_parse_amc_test': 'run the ParseAMCTest unit test suite to validate AMC motion capture data parsing and conversion', 'test_different_timesteps': 'test parse_amc.convert with a smaller timestep to verify doubled frame count in parsed data', 'review_ParseAMCTest_class': 'review the ParseAMCTest class and its test_sizes_of_parsed_data method for AMC parsing assertions', 'summarize_parse_amc_convert_usage': 'summarize how parse_amc.convert is called with an AMC file path, physics model, and control timestep'}
```

## File: facebookresearch_deepbisim4control/local_dm_control_suite/utils/randomizers.py

Prompts

```
['convert an AMC motion capture file to MuJoCo qpos and qvel values with resampling', 'parse an AMC motion capture file and return frame values as numpy arrays', 'create an Amcvals2qpos callable to convert AMC frame values to MuJoCo qpos format', 'convert euler angles in degrees to a quaternion using zyx rotation order', 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings', 'test the parse_amc.convert function to verify qpos and qvel array shapes for a humanoid AMC clip', 'run the ParseAMCTest unit test suite to validate AMC motion capture data parsing and conversion', 'test parse_amc.convert with a smaller timestep to verify doubled frame count in parsed data', 'review the ParseAMCTest class and its test_sizes_of_parsed_data method for AMC parsing assertions', 'summarize how parse_amc.convert is called with an AMC file path, physics model, and control timestep', 'generate a random quaternion limited to a specified rotation angle using a random state and limit', 'randomize the positions of all joints in a MuJoCo physics body including hinges sliders balls and free joints', 'test the random_limited_quaternion function by generating quaternions with various angle limits and verifying norms', 'test the randomize_limited_and_rotational_joints function on a MuJoCo physics model with mixed joint types', 'refactor the randomize_limited_and_rotational_joints function to support additional joint types or custom randomization distributions', 'run the randomizers test suite to validate joint randomization for hinge, slide, ball, and free joint types', 'review the RandomizeUnlimitedJointsTest class to understand how limited and rotational joint randomization is tested', 'test that limited hinge and slide joints respect their configured range constraints during randomization', 'test that limited ball joints respect angular range constraints using quaternion rotation verification']
```

Usage

```
{'random_limited_quaternion': 'generate a random quaternion limited to a specified rotation angle using a random state and limit', 'randomize_limited_and_rotational_joints': 'randomize the positions of all joints in a MuJoCo physics body including hinges sliders balls and free joints', 'test_random_limited_quaternion': 'test the random_limited_quaternion function by generating quaternions with various angle limits and verifying norms', 'test_randomize_limited_and_rotational_joints': 'test the randomize_limited_and_rotational_joints function on a MuJoCo physics model with mixed joint types', 'refactor_randomize_limited_and_rotational_joints': 'refactor the randomize_limited_and_rotational_joints function to support additional joint types or custom randomization distributions'}
```

## File: facebookresearch_deepbisim4control/local_dm_control_suite/utils/randomizers_test.py

Prompts

```
['convert an AMC motion capture file to MuJoCo qpos and qvel values with resampling', 'parse an AMC motion capture file and return frame values as numpy arrays', 'create an Amcvals2qpos callable to convert AMC frame values to MuJoCo qpos format', 'convert euler angles in degrees to a quaternion using zyx rotation order', 'compute the quaternion difference between a source and target quaternion using MuJoCo bindings', 'test the parse_amc.convert function to verify qpos and qvel array shapes for a humanoid AMC clip', 'run the ParseAMCTest unit test suite to validate AMC motion capture data parsing and conversion', 'test parse_amc.convert with a smaller timestep to verify doubled frame count in parsed data', 'review the ParseAMCTest class and its test_sizes_of_parsed_data method for AMC parsing assertions', 'summarize how parse_amc.convert is called with an AMC file path, physics model, and control timestep', 'generate a random quaternion limited to a specified rotation angle using a random state and limit', 'randomize the positions of all joints in a MuJoCo physics body including hinges sliders balls and free joints', 'test the random_limited_quaternion function by generating quaternions with various angle limits and verifying norms', 'test the randomize_limited_and_rotational_joints function on a MuJoCo physics model with mixed joint types', 'refactor the randomize_limited_and_rotational_joints function to support additional joint types or custom randomization distributions', 'run the randomizers test suite to validate joint randomization for hinge, slide, ball, and free joint types', 'review the RandomizeUnlimitedJointsTest class to understand how limited and rotational joint randomization is tested', 'test that limited hinge and slide joints respect their configured range constraints during randomization', 'test that limited ball joints respect angular range constraints using quaternion rotation verification']
```

Usage

```
{'test_randomize_limited_and_rotational_joints': 'test randomize_limited_and_rotational_joints to verify MuJoCo joint positions are randomized within expected bounds', 'run_randomizers_test': 'run the randomizers test suite to validate joint randomization for hinge, slide, ball, and free joint types', 'review_randomize_unlimited_joints_test': 'review the RandomizeUnlimitedJointsTest class to understand how limited and rotational joint randomization is tested', 'test_joint_limit_respect': 'test that limited hinge and slide joints respect their configured range constraints during randomization', 'test_ball_joint_limits': 'test that limited ball joints respect angular range constraints using quaternion rotation verification'}
```

