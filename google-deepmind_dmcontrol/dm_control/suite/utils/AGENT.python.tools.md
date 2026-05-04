# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/suite/utils/parse_amc.py

Prompts

```
['convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampled timesteps', 'parse an .amc motion capture file and return a list of per-frame joint value arrays', 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'summarize the CMU mocap joint order tuple listing all 61 joint names used in conversion', 'review the Converted namedtuple structure with qpos, qvel, and time fields for mocap data', 'test parse_amc.convert to verify qpos and qvel tensor shapes from an AMC file', 'run the ParseAMCTest class to validate AMC file parsing produces correct dimensions', 'test humanoid_CMU.stand environment instantiation for use with AMC motion capture data', 'review parse_amc.convert behavior when called with different control timestep values', 'summarize the ParseAMCTest class and its test_sizes_of_parsed_data test method', 'randomize the positions of hinge, slide, ball, and free joints in a MuJoCo physics body', 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'sample bounded hinge and slider joints uniformly within their configured range limits', 'sample quaternions for unlimited ball joints uniformly on the unit 3-sphere', 'review the randomization rules for hinge, slide, ball, and free joint types in MuJoCo physics models', 'test randomize_limited_and_rotational_joints to verify MuJoCo physics joint positions are randomized correctly', 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test that multiple hinge joints of the same type receive unique randomized values', 'test that unlimited hinge joint randomization stays within negative pi to positive pi', 'test that limited ball joint randomization respects the configured range constraints']
```

Usage

```
{'convert_amc_to_mujoco_qpos_qvel': 'convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampled timesteps', 'parse_amc_file': 'parse an .amc motion capture file and return a list of per-frame joint value arrays', 'create_amcvals2qpos_transformer': 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'summarize_CMU_MOCAP_JOINT_ORDER': 'summarize the CMU mocap joint order tuple listing all 61 joint names used in conversion', 'review_Converted_namedtuple': 'review the Converted namedtuple structure with qpos, qvel, and time fields for mocap data'}
```

## File: google-deepmind_dmcontrol/dm_control/suite/utils/parse_amc_test.py

Prompts

```
['convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampled timesteps', 'parse an .amc motion capture file and return a list of per-frame joint value arrays', 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'summarize the CMU mocap joint order tuple listing all 61 joint names used in conversion', 'review the Converted namedtuple structure with qpos, qvel, and time fields for mocap data', 'test parse_amc.convert to verify qpos and qvel tensor shapes from an AMC file', 'run the ParseAMCTest class to validate AMC file parsing produces correct dimensions', 'test humanoid_CMU.stand environment instantiation for use with AMC motion capture data', 'review parse_amc.convert behavior when called with different control timestep values', 'summarize the ParseAMCTest class and its test_sizes_of_parsed_data test method', 'randomize the positions of hinge, slide, ball, and free joints in a MuJoCo physics body', 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'sample bounded hinge and slider joints uniformly within their configured range limits', 'sample quaternions for unlimited ball joints uniformly on the unit 3-sphere', 'review the randomization rules for hinge, slide, ball, and free joint types in MuJoCo physics models', 'test randomize_limited_and_rotational_joints to verify MuJoCo physics joint positions are randomized correctly', 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test that multiple hinge joints of the same type receive unique randomized values', 'test that unlimited hinge joint randomization stays within negative pi to positive pi', 'test that limited ball joint randomization respects the configured range constraints']
```

Usage

```
{'test_parse_amc_convert': 'test parse_amc.convert to verify qpos and qvel tensor shapes from an AMC file', 'run_ParseAMCTest': 'run the ParseAMCTest class to validate AMC file parsing produces correct dimensions', 'test_humanoid_CMU_stand': 'test humanoid_CMU.stand environment instantiation for use with AMC motion capture data', 'review_parse_amc_convert_timestep': 'review parse_amc.convert behavior when called with different control timestep values', 'summarize_ParseAMCTest': 'summarize the ParseAMCTest class and its test_sizes_of_parsed_data test method'}
```

## File: google-deepmind_dmcontrol/dm_control/suite/utils/randomizers.py

Prompts

```
['convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampled timesteps', 'parse an .amc motion capture file and return a list of per-frame joint value arrays', 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'summarize the CMU mocap joint order tuple listing all 61 joint names used in conversion', 'review the Converted namedtuple structure with qpos, qvel, and time fields for mocap data', 'test parse_amc.convert to verify qpos and qvel tensor shapes from an AMC file', 'run the ParseAMCTest class to validate AMC file parsing produces correct dimensions', 'test humanoid_CMU.stand environment instantiation for use with AMC motion capture data', 'review parse_amc.convert behavior when called with different control timestep values', 'summarize the ParseAMCTest class and its test_sizes_of_parsed_data test method', 'randomize the positions of hinge, slide, ball, and free joints in a MuJoCo physics body', 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'sample bounded hinge and slider joints uniformly within their configured range limits', 'sample quaternions for unlimited ball joints uniformly on the unit 3-sphere', 'review the randomization rules for hinge, slide, ball, and free joint types in MuJoCo physics models', 'test randomize_limited_and_rotational_joints to verify MuJoCo physics joint positions are randomized correctly', 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test that multiple hinge joints of the same type receive unique randomized values', 'test that unlimited hinge joint randomization stays within negative pi to positive pi', 'test that limited ball joint randomization respects the configured range constraints']
```

Usage

```
{'randomize_joint_positions': 'randomize the positions of hinge, slide, ball, and free joints in a MuJoCo physics body', 'generate_limited_quaternion': 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'sample_bounded_joints': 'sample bounded hinge and slider joints uniformly within their configured range limits', 'sample_unlimited_ball_joints': 'sample quaternions for unlimited ball joints uniformly on the unit 3-sphere', 'review_randomization_rules': 'review the randomization rules for hinge, slide, ball, and free joint types in MuJoCo physics models'}
```

## File: google-deepmind_dmcontrol/dm_control/suite/utils/randomizers_test.py

Prompts

```
['convert an .amc motion capture file into MuJoCo qpos and qvel arrays with resampled timesteps', 'parse an .amc motion capture file and return a list of per-frame joint value arrays', 'create an Amcvals2qpos callable that converts a single .amc frame to MuJoCo qpos format', 'summarize the CMU mocap joint order tuple listing all 61 joint names used in conversion', 'review the Converted namedtuple structure with qpos, qvel, and time fields for mocap data', 'test parse_amc.convert to verify qpos and qvel tensor shapes from an AMC file', 'run the ParseAMCTest class to validate AMC file parsing produces correct dimensions', 'test humanoid_CMU.stand environment instantiation for use with AMC motion capture data', 'review parse_amc.convert behavior when called with different control timestep values', 'summarize the ParseAMCTest class and its test_sizes_of_parsed_data test method', 'randomize the positions of hinge, slide, ball, and free joints in a MuJoCo physics body', 'generate a random quaternion limited to a specified rotation angle using axis-angle conversion', 'sample bounded hinge and slider joints uniformly within their configured range limits', 'sample quaternions for unlimited ball joints uniformly on the unit 3-sphere', 'review the randomization rules for hinge, slide, ball, and free joint types in MuJoCo physics models', 'test randomize_limited_and_rotational_joints to verify MuJoCo physics joint positions are randomized correctly', 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test that multiple hinge joints of the same type receive unique randomized values', 'test that unlimited hinge joint randomization stays within negative pi to positive pi', 'test that limited ball joint randomization respects the configured range constraints']
```

Usage

```
{'test_randomize_limited_and_rotational_joints': 'test randomize_limited_and_rotational_joints to verify MuJoCo physics joint positions are randomized correctly', 'test_single_joint_of_each_type': 'test randomization of free, hinge, slide, and ball joint types in a MuJoCo physics model', 'test_multiple_joints_of_same_type': 'test that multiple hinge joints of the same type receive unique randomized values', 'test_unlimited_hinge_randomization_range': 'test that unlimited hinge joint randomization stays within negative pi to positive pi', 'test_limited_ball_joint_are_respected': 'test that limited ball joint randomization respects the configured range constraints'}
```

