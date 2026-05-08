# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/tests/smoke_test.py

Prompts

```
['run the smoke test to fetch RGB and depth images from a LoCoBot robot over Pyro4', 'create a LoCoBotMover instance that connects to a remote LoCoBot via Pyro4 at a given IP', 'get RGB and depth image arrays from a remote LoCoBot using the get_rgb_depth method', 'review the LoCoBotMover class and its Pyro4 proxy initialization for remote robot communication', 'test the Pyro4 connection to a LoCoBot by fetching RGB and depth images five times with timing', 'test the NavigationTests class to verify the robot navigates to an absolute position in the habitat environment', 'test the NavigationTests test_turn method to verify the robot turns at specified angles using go_to_relative', 'run the assert_image function to compare a robot camera image against an expected saved image file', 'run the assert_visual function to capture and compare the robot RGB camera output against an expected PNG asset', "run the assert_turn_degree function to verify a robot's final orientation matches an expected turn in degrees", 'test the MoverTests class to verify LoCoBotMover moves correctly by relative task positions', 'test the MoverTests class to verify LoCoBotMover turns correctly at various angles in degrees', 'run the unittest test suite for LoCoBotMover relative movement and turning functionality', 'review the MoverTests class and its setUp, test_move_relative, and test_turn methods', 'refactor the MoverTests class to add new test cases for LoCoBotMover movement and turning', 'test the assert_turn_degree function to verify robot yaw rotation between initial and final angles', 'test the assert_distance_moved function to verify robot movement distance between two positions', 'test the xyz_pyrobot_to_canonical_coords function to convert pyrobot coordinates to canonical coordinates', 'test the xyz_canonical_coords_to_pyrobot_coords function to convert canonical coordinates to pyrobot coordinates', 'test the get_move_target_for_point function to compute robot move targets for point targets with epsilon']
```

Usage

```
{'run_locobot_smoke_test': 'run the smoke test to fetch RGB and depth images from a LoCoBot robot over Pyro4', 'create_locobot_mover_proxy': 'create a LoCoBotMover instance that connects to a remote LoCoBot via Pyro4 at a given IP', 'get_rgb_depth_images': 'get RGB and depth image arrays from a remote LoCoBot using the get_rgb_depth method', 'review_locobot_mover_class': 'review the LoCoBotMover class and its Pyro4 proxy initialization for remote robot communication', 'test_locobot_pyro4_connection': 'test the Pyro4 connection to a LoCoBot by fetching RGB and depth images five times with timing'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/tests/test_habitat.py

Prompts

```
['run the smoke test to fetch RGB and depth images from a LoCoBot robot over Pyro4', 'create a LoCoBotMover instance that connects to a remote LoCoBot via Pyro4 at a given IP', 'get RGB and depth image arrays from a remote LoCoBot using the get_rgb_depth method', 'review the LoCoBotMover class and its Pyro4 proxy initialization for remote robot communication', 'test the Pyro4 connection to a LoCoBot by fetching RGB and depth images five times with timing', 'test the NavigationTests class to verify the robot navigates to an absolute position in the habitat environment', 'test the NavigationTests test_turn method to verify the robot turns at specified angles using go_to_relative', 'run the assert_image function to compare a robot camera image against an expected saved image file', 'run the assert_visual function to capture and compare the robot RGB camera output against an expected PNG asset', "run the assert_turn_degree function to verify a robot's final orientation matches an expected turn in degrees", 'test the MoverTests class to verify LoCoBotMover moves correctly by relative task positions', 'test the MoverTests class to verify LoCoBotMover turns correctly at various angles in degrees', 'run the unittest test suite for LoCoBotMover relative movement and turning functionality', 'review the MoverTests class and its setUp, test_move_relative, and test_turn methods', 'refactor the MoverTests class to add new test cases for LoCoBotMover movement and turning', 'test the assert_turn_degree function to verify robot yaw rotation between initial and final angles', 'test the assert_distance_moved function to verify robot movement distance between two positions', 'test the xyz_pyrobot_to_canonical_coords function to convert pyrobot coordinates to canonical coordinates', 'test the xyz_canonical_coords_to_pyrobot_coords function to convert canonical coordinates to pyrobot coordinates', 'test the get_move_target_for_point function to compute robot move targets for point targets with epsilon']
```

Usage

```
{'test_navigation_go_to_absolute': 'test the NavigationTests class to verify the robot navigates to an absolute position in the habitat environment', 'test_navigation_turn': 'test the NavigationTests test_turn method to verify the robot turns at specified angles using go_to_relative', 'run_assert_image': 'run the assert_image function to compare a robot camera image against an expected saved image file', 'run_assert_visual': 'run the assert_visual function to capture and compare the robot RGB camera output against an expected PNG asset', 'run_assert_turn_degree': "run the assert_turn_degree function to verify a robot's final orientation matches an expected turn in degrees"}
```

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/tests/test_mover.py

Prompts

```
['run the smoke test to fetch RGB and depth images from a LoCoBot robot over Pyro4', 'create a LoCoBotMover instance that connects to a remote LoCoBot via Pyro4 at a given IP', 'get RGB and depth image arrays from a remote LoCoBot using the get_rgb_depth method', 'review the LoCoBotMover class and its Pyro4 proxy initialization for remote robot communication', 'test the Pyro4 connection to a LoCoBot by fetching RGB and depth images five times with timing', 'test the NavigationTests class to verify the robot navigates to an absolute position in the habitat environment', 'test the NavigationTests test_turn method to verify the robot turns at specified angles using go_to_relative', 'run the assert_image function to compare a robot camera image against an expected saved image file', 'run the assert_visual function to capture and compare the robot RGB camera output against an expected PNG asset', "run the assert_turn_degree function to verify a robot's final orientation matches an expected turn in degrees", 'test the MoverTests class to verify LoCoBotMover moves correctly by relative task positions', 'test the MoverTests class to verify LoCoBotMover turns correctly at various angles in degrees', 'run the unittest test suite for LoCoBotMover relative movement and turning functionality', 'review the MoverTests class and its setUp, test_move_relative, and test_turn methods', 'refactor the MoverTests class to add new test cases for LoCoBotMover movement and turning', 'test the assert_turn_degree function to verify robot yaw rotation between initial and final angles', 'test the assert_distance_moved function to verify robot movement distance between two positions', 'test the xyz_pyrobot_to_canonical_coords function to convert pyrobot coordinates to canonical coordinates', 'test the xyz_canonical_coords_to_pyrobot_coords function to convert canonical coordinates to pyrobot coordinates', 'test the get_move_target_for_point function to compute robot move targets for point targets with epsilon']
```

Usage

```
{'test_move_relative': 'test the MoverTests class to verify LoCoBotMover moves correctly by relative task positions', 'test_turn': 'test the MoverTests class to verify LoCoBotMover turns correctly at various angles in degrees', 'run_mover_tests': 'run the unittest test suite for LoCoBotMover relative movement and turning functionality', 'review_MoverTests': 'review the MoverTests class and its setUp, test_move_relative, and test_turn methods', 'refactor_MoverTests': 'refactor the MoverTests class to add new test cases for LoCoBotMover movement and turning'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/tests/test_utils.py

Prompts

```
['run the smoke test to fetch RGB and depth images from a LoCoBot robot over Pyro4', 'create a LoCoBotMover instance that connects to a remote LoCoBot via Pyro4 at a given IP', 'get RGB and depth image arrays from a remote LoCoBot using the get_rgb_depth method', 'review the LoCoBotMover class and its Pyro4 proxy initialization for remote robot communication', 'test the Pyro4 connection to a LoCoBot by fetching RGB and depth images five times with timing', 'test the NavigationTests class to verify the robot navigates to an absolute position in the habitat environment', 'test the NavigationTests test_turn method to verify the robot turns at specified angles using go_to_relative', 'run the assert_image function to compare a robot camera image against an expected saved image file', 'run the assert_visual function to capture and compare the robot RGB camera output against an expected PNG asset', "run the assert_turn_degree function to verify a robot's final orientation matches an expected turn in degrees", 'test the MoverTests class to verify LoCoBotMover moves correctly by relative task positions', 'test the MoverTests class to verify LoCoBotMover turns correctly at various angles in degrees', 'run the unittest test suite for LoCoBotMover relative movement and turning functionality', 'review the MoverTests class and its setUp, test_move_relative, and test_turn methods', 'refactor the MoverTests class to add new test cases for LoCoBotMover movement and turning', 'test the assert_turn_degree function to verify robot yaw rotation between initial and final angles', 'test the assert_distance_moved function to verify robot movement distance between two positions', 'test the xyz_pyrobot_to_canonical_coords function to convert pyrobot coordinates to canonical coordinates', 'test the xyz_canonical_coords_to_pyrobot_coords function to convert canonical coordinates to pyrobot coordinates', 'test the get_move_target_for_point function to compute robot move targets for point targets with epsilon']
```

Usage

```
{'test_assert_turn_degree': 'test the assert_turn_degree function to verify robot yaw rotation between initial and final angles', 'test_assert_distance_moved': 'test the assert_distance_moved function to verify robot movement distance between two positions', 'test_xyz_pyrobot_to_canonical_coords': 'test the xyz_pyrobot_to_canonical_coords function to convert pyrobot coordinates to canonical coordinates', 'test_xyz_canonical_coords_to_pyrobot_coords': 'test the xyz_canonical_coords_to_pyrobot_coords function to convert canonical coordinates to pyrobot coordinates', 'test_get_move_target_for_point': 'test the get_move_target_for_point function to compute robot move targets for point targets with epsilon'}
```

