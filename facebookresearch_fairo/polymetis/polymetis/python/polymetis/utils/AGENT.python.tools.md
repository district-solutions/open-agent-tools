# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/utils/continuous_grasper.py

Prompts

```
['create a ManipulatorSystem instance with robot and gripper IP addresses to control a Franka arm', 'run move_to on a ManipulatorSystem to plan and execute a Cartesian trajectory to a target pose', 'run grasp on a ManipulatorSystem to pick from one pose and release at another with full trajectory logging', 'run continuously_grasp to repeatedly sample random grasp and release poses and execute pick-and-place cycles', 'run uniform_sample to generate a random pose within given lower and upper bound tensors', 'get the absolute path to a URDF file relative to the polymetis data directory', 'find the full path of an executable program in the system PATH environment variable', 'review the polymetis DATA_DIR constant that points to the package data directory', 'review the polymetis BUILD_DIR constant that points to the build output directory', 'review the polymetis PKG_ROOT_DIR constant that stores the package root path', 'check if a server is listening on a given IP address and port using a TCP socket connection', 'test the check_server_exists function by verifying connectivity to a known server IP and port', 'review the check_server_exists function to understand how it uses socket connect_ex to detect server availability', 'summarize the check_server_exists function which returns a boolean indicating whether a server exists at the given address', 'refactor the check_server_exists function to add a timeout parameter for the socket connection attempt', 'create a Spinner instance with a target Hz to control loop frequency', 'call spin in a loop to sleep and maintain a specific execution frequency', 'review the Spinner class that sleeps to maintain a target Hz frequency', 'refactor the Spinner spin method to log a warning when computation exceeds loop time', 'summarize the Spinner class used to throttle loop iterations to a target frequency']
```

Usage

```
{'create_manipulator_system': 'create a ManipulatorSystem instance with robot and gripper IP addresses to control a Franka arm', 'run_move_to': 'run move_to on a ManipulatorSystem to plan and execute a Cartesian trajectory to a target pose', 'run_grasp': 'run grasp on a ManipulatorSystem to pick from one pose and release at another with full trajectory logging', 'run_continuously_grasp': 'run continuously_grasp to repeatedly sample random grasp and release poses and execute pick-and-place cycles', 'run_uniform_sample': 'run uniform_sample to generate a random pose within given lower and upper bound tensors'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/utils/data_dir.py

Prompts

```
['create a ManipulatorSystem instance with robot and gripper IP addresses to control a Franka arm', 'run move_to on a ManipulatorSystem to plan and execute a Cartesian trajectory to a target pose', 'run grasp on a ManipulatorSystem to pick from one pose and release at another with full trajectory logging', 'run continuously_grasp to repeatedly sample random grasp and release poses and execute pick-and-place cycles', 'run uniform_sample to generate a random pose within given lower and upper bound tensors', 'get the absolute path to a URDF file relative to the polymetis data directory', 'find the full path of an executable program in the system PATH environment variable', 'review the polymetis DATA_DIR constant that points to the package data directory', 'review the polymetis BUILD_DIR constant that points to the build output directory', 'review the polymetis PKG_ROOT_DIR constant that stores the package root path', 'check if a server is listening on a given IP address and port using a TCP socket connection', 'test the check_server_exists function by verifying connectivity to a known server IP and port', 'review the check_server_exists function to understand how it uses socket connect_ex to detect server availability', 'summarize the check_server_exists function which returns a boolean indicating whether a server exists at the given address', 'refactor the check_server_exists function to add a timeout parameter for the socket connection attempt', 'create a Spinner instance with a target Hz to control loop frequency', 'call spin in a loop to sleep and maintain a specific execution frequency', 'review the Spinner class that sleeps to maintain a target Hz frequency', 'refactor the Spinner spin method to log a warning when computation exceeds loop time', 'summarize the Spinner class used to throttle loop iterations to a target frequency']
```

Usage

```
{'get_full_path_to_urdf': 'get the absolute path to a URDF file relative to the polymetis data directory', 'which_program': 'find the full path of an executable program in the system PATH environment variable', 'review_DATA_DIR': 'review the polymetis DATA_DIR constant that points to the package data directory', 'review_BUILD_DIR': 'review the polymetis BUILD_DIR constant that points to the build output directory', 'review_PKG_ROOT_DIR': 'review the polymetis PKG_ROOT_DIR constant that stores the package root path'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/utils/grpc_utils.py

Prompts

```
['create a ManipulatorSystem instance with robot and gripper IP addresses to control a Franka arm', 'run move_to on a ManipulatorSystem to plan and execute a Cartesian trajectory to a target pose', 'run grasp on a ManipulatorSystem to pick from one pose and release at another with full trajectory logging', 'run continuously_grasp to repeatedly sample random grasp and release poses and execute pick-and-place cycles', 'run uniform_sample to generate a random pose within given lower and upper bound tensors', 'get the absolute path to a URDF file relative to the polymetis data directory', 'find the full path of an executable program in the system PATH environment variable', 'review the polymetis DATA_DIR constant that points to the package data directory', 'review the polymetis BUILD_DIR constant that points to the build output directory', 'review the polymetis PKG_ROOT_DIR constant that stores the package root path', 'check if a server is listening on a given IP address and port using a TCP socket connection', 'test the check_server_exists function by verifying connectivity to a known server IP and port', 'review the check_server_exists function to understand how it uses socket connect_ex to detect server availability', 'summarize the check_server_exists function which returns a boolean indicating whether a server exists at the given address', 'refactor the check_server_exists function to add a timeout parameter for the socket connection attempt', 'create a Spinner instance with a target Hz to control loop frequency', 'call spin in a loop to sleep and maintain a specific execution frequency', 'review the Spinner class that sleeps to maintain a target Hz frequency', 'refactor the Spinner spin method to log a warning when computation exceeds loop time', 'summarize the Spinner class used to throttle loop iterations to a target frequency']
```

Usage

```
{'check_server_exists': 'check if a server is listening on a given IP address and port using a TCP socket connection', 'test_check_server_exists': 'test the check_server_exists function by verifying connectivity to a known server IP and port', 'review_check_server_exists': 'review the check_server_exists function to understand how it uses socket connect_ex to detect server availability', 'summarize_check_server_exists': 'summarize the check_server_exists function which returns a boolean indicating whether a server exists at the given address', 'refactor_check_server_exists': 'refactor the check_server_exists function to add a timeout parameter for the socket connection attempt'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/utils/spinner.py

Prompts

```
['create a ManipulatorSystem instance with robot and gripper IP addresses to control a Franka arm', 'run move_to on a ManipulatorSystem to plan and execute a Cartesian trajectory to a target pose', 'run grasp on a ManipulatorSystem to pick from one pose and release at another with full trajectory logging', 'run continuously_grasp to repeatedly sample random grasp and release poses and execute pick-and-place cycles', 'run uniform_sample to generate a random pose within given lower and upper bound tensors', 'get the absolute path to a URDF file relative to the polymetis data directory', 'find the full path of an executable program in the system PATH environment variable', 'review the polymetis DATA_DIR constant that points to the package data directory', 'review the polymetis BUILD_DIR constant that points to the build output directory', 'review the polymetis PKG_ROOT_DIR constant that stores the package root path', 'check if a server is listening on a given IP address and port using a TCP socket connection', 'test the check_server_exists function by verifying connectivity to a known server IP and port', 'review the check_server_exists function to understand how it uses socket connect_ex to detect server availability', 'summarize the check_server_exists function which returns a boolean indicating whether a server exists at the given address', 'refactor the check_server_exists function to add a timeout parameter for the socket connection attempt', 'create a Spinner instance with a target Hz to control loop frequency', 'call spin in a loop to sleep and maintain a specific execution frequency', 'review the Spinner class that sleeps to maintain a target Hz frequency', 'refactor the Spinner spin method to log a warning when computation exceeds loop time', 'summarize the Spinner class used to throttle loop iterations to a target frequency']
```

Usage

```
{'create_spinner_for_loop_frequency': 'create a Spinner instance with a target Hz to control loop frequency', 'spin_maintain_frequency': 'call spin in a loop to sleep and maintain a specific execution frequency', 'review_spinner_class': 'review the Spinner class that sleeps to maintain a target Hz frequency', 'refactor_spinner_warning_logging': 'refactor the Spinner spin method to log a warning when computation exceeds loop time', 'summarize_spinner_usage': 'summarize the Spinner class used to throttle loop iterations to a target frequency'}
```

