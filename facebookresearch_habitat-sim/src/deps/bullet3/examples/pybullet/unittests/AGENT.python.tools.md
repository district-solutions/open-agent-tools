# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/unittests/saveRestoreStateTest.py

Prompts

```
['test the pybullet simulation state save and restore using saveBullet and restoreState', 'create a pybullet physics world with a plane, kuka robot, and 50 cubes', 'dump all body positions, orientations, and velocities to a text file', 'compare two state dump files using difflib unified diff and assert zero differences', 'save a pybullet simulation to a file and restore it to verify identical state', 'test the pybullet API version is greater than 201700000 using getAPIVersion', 'test connecting to pybullet in DIRECT mode and verify the connection ID equals zero', 'test loading a URDF robot model like r2d2.urdf in pybullet DIRECT mode', 'test rolling friction by simulating a sphere on a plane with gravity and stepSimulation', 'test calculating robot end-effector Jacobians and verifying translational and rotational velocity match', 'test adding user data key-value pairs to a pybullet body using addUserData', 'test retrieving user data values from a pybullet body by user data ID', 'test counting the number of user data entries attached to a pybullet body', 'test removing a user data entry from a pybullet body by its user data ID', 'test syncing user data changes across multiple pybullet clients using syncUserData', 'run a dot product between a 2D matrix and a 1D vector using the dot function', 'test whether all elements of two vectors are close within a tolerance using allclose', 'summarize the dot function that computes a matrix-vector dot product returning a list of sums', 'summarize the allclose function that checks if two vectors are element-wise close within a tolerance', 'refactor the allclose function to support a configurable default tolerance value']
```

Usage

```
{'test_save_restore_state': 'test the pybullet simulation state save and restore using saveBullet and restoreState', 'setup_world': 'create a pybullet physics world with a plane, kuka robot, and 50 cubes', 'dump_state_to_file': 'dump all body positions, orientations, and velocities to a text file', 'compare_files': 'compare two state dump files using difflib unified diff and assert zero differences', 'save_and_restore_bullet_state': 'save a pybullet simulation to a file and restore it to verify identical state'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/unittests/unittests.py

Prompts

```
['test the pybullet simulation state save and restore using saveBullet and restoreState', 'create a pybullet physics world with a plane, kuka robot, and 50 cubes', 'dump all body positions, orientations, and velocities to a text file', 'compare two state dump files using difflib unified diff and assert zero differences', 'save a pybullet simulation to a file and restore it to verify identical state', 'test the pybullet API version is greater than 201700000 using getAPIVersion', 'test connecting to pybullet in DIRECT mode and verify the connection ID equals zero', 'test loading a URDF robot model like r2d2.urdf in pybullet DIRECT mode', 'test rolling friction by simulating a sphere on a plane with gravity and stepSimulation', 'test calculating robot end-effector Jacobians and verifying translational and rotational velocity match', 'test adding user data key-value pairs to a pybullet body using addUserData', 'test retrieving user data values from a pybullet body by user data ID', 'test counting the number of user data entries attached to a pybullet body', 'test removing a user data entry from a pybullet body by its user data ID', 'test syncing user data changes across multiple pybullet clients using syncUserData', 'run a dot product between a 2D matrix and a 1D vector using the dot function', 'test whether all elements of two vectors are close within a tolerance using allclose', 'summarize the dot function that computes a matrix-vector dot product returning a list of sums', 'summarize the allclose function that checks if two vectors are element-wise close within a tolerance', 'refactor the allclose function to support a configurable default tolerance value']
```

Usage

```
{'test_pybullet_api_version': 'test the pybullet API version is greater than 201700000 using getAPIVersion', 'test_pybullet_direct_connect': 'test connecting to pybullet in DIRECT mode and verify the connection ID equals zero', 'test_load_urdf_model': 'test loading a URDF robot model like r2d2.urdf in pybullet DIRECT mode', 'test_rolling_friction_simulation': 'test rolling friction by simulating a sphere on a plane with gravity and stepSimulation', 'test_robot_jacobian_calculation': 'test calculating robot end-effector Jacobians and verifying translational and rotational velocity match'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/unittests/userDataTest.py

Prompts

```
['test the pybullet simulation state save and restore using saveBullet and restoreState', 'create a pybullet physics world with a plane, kuka robot, and 50 cubes', 'dump all body positions, orientations, and velocities to a text file', 'compare two state dump files using difflib unified diff and assert zero differences', 'save a pybullet simulation to a file and restore it to verify identical state', 'test the pybullet API version is greater than 201700000 using getAPIVersion', 'test connecting to pybullet in DIRECT mode and verify the connection ID equals zero', 'test loading a URDF robot model like r2d2.urdf in pybullet DIRECT mode', 'test rolling friction by simulating a sphere on a plane with gravity and stepSimulation', 'test calculating robot end-effector Jacobians and verifying translational and rotational velocity match', 'test adding user data key-value pairs to a pybullet body using addUserData', 'test retrieving user data values from a pybullet body by user data ID', 'test counting the number of user data entries attached to a pybullet body', 'test removing a user data entry from a pybullet body by its user data ID', 'test syncing user data changes across multiple pybullet clients using syncUserData', 'run a dot product between a 2D matrix and a 1D vector using the dot function', 'test whether all elements of two vectors are close within a tolerance using allclose', 'summarize the dot function that computes a matrix-vector dot product returning a list of sums', 'summarize the allclose function that checks if two vectors are element-wise close within a tolerance', 'refactor the allclose function to support a configurable default tolerance value']
```

Usage

```
{'test_add_userdata': 'test adding user data key-value pairs to a pybullet body using addUserData', 'test_get_userdata': 'test retrieving user data values from a pybullet body by user data ID', 'test_get_num_userdata': 'test counting the number of user data entries attached to a pybullet body', 'test_remove_userdata': 'test removing a user data entry from a pybullet body by its user data ID', 'test_sync_userdata': 'test syncing user data changes across multiple pybullet clients using syncUserData'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/unittests/utils.py

Prompts

```
['test the pybullet simulation state save and restore using saveBullet and restoreState', 'create a pybullet physics world with a plane, kuka robot, and 50 cubes', 'dump all body positions, orientations, and velocities to a text file', 'compare two state dump files using difflib unified diff and assert zero differences', 'save a pybullet simulation to a file and restore it to verify identical state', 'test the pybullet API version is greater than 201700000 using getAPIVersion', 'test connecting to pybullet in DIRECT mode and verify the connection ID equals zero', 'test loading a URDF robot model like r2d2.urdf in pybullet DIRECT mode', 'test rolling friction by simulating a sphere on a plane with gravity and stepSimulation', 'test calculating robot end-effector Jacobians and verifying translational and rotational velocity match', 'test adding user data key-value pairs to a pybullet body using addUserData', 'test retrieving user data values from a pybullet body by user data ID', 'test counting the number of user data entries attached to a pybullet body', 'test removing a user data entry from a pybullet body by its user data ID', 'test syncing user data changes across multiple pybullet clients using syncUserData', 'run a dot product between a 2D matrix and a 1D vector using the dot function', 'test whether all elements of two vectors are close within a tolerance using allclose', 'summarize the dot function that computes a matrix-vector dot product returning a list of sums', 'summarize the allclose function that checks if two vectors are element-wise close within a tolerance', 'refactor the allclose function to support a configurable default tolerance value']
```

Usage

```
{'run_dot_product': 'run a dot product between a 2D matrix and a 1D vector using the dot function', 'test_allclose': 'test whether all elements of two vectors are close within a tolerance using allclose', 'summarize_dot': 'summarize the dot function that computes a matrix-vector dot product returning a list of sums', 'summarize_allclose': 'summarize the allclose function that checks if two vectors are element-wise close within a tolerance', 'refactor_allclose': 'refactor the allclose function to support a configurable default tolerance value'}
```

