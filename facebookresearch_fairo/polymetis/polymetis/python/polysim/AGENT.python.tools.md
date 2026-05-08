# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polysim/grpc_sim_client.py

Prompts

```
['run the GrpcSimulationClient in a background thread with a specified time horizon using run_no_wait', 'stop the background simulation thread by calling kill_run on the GrpcSimulationClient', 'execute a gRPC call with round trip time logging via execute_rpc_call on GrpcSimulationClient', 'sync the simulation client state to a real robot using the sync method on GrpcSimulationClient', 'set the robot state in the simulation environment using set_robot_state on GrpcSimulationClient', 'create a SimInterface instance with a target control frequency in Hz', 'register arm control with a gRPC server address, state and action callbacks, and joint gains', 'register gripper control with a gRPC server address, state and action callbacks, and max width', 'register a step callback function that runs each simulation loop iteration', 'run the simulation loop for a given time horizon with optional fast-forward mode', 'create a FakeMetadata instance with a specified hz value for testing robot client metadata', 'create a FakeEnv with a given number of dimensions for testing controlled simulation environments', 'test the FakeConnection ControlUpdate method to verify it returns a TorqueCommand protobuf message', 'test the FakeEnv get_current_joint_pos_vel method to verify it returns zero numpy arrays', 'mock gRPC insecure_channel and PolymetisControllerServerStub using FakeChannel and FakeConnection for unit testing']
```

Usage

```
{'run_simulation_background': 'run the GrpcSimulationClient in a background thread with a specified time horizon using run_no_wait', 'stop_simulation_background': 'stop the background simulation thread by calling kill_run on the GrpcSimulationClient', 'execute_rpc_call': 'execute a gRPC call with round trip time logging via execute_rpc_call on GrpcSimulationClient', 'sync_mirror_simulator': 'sync the simulation client state to a real robot using the sync method on GrpcSimulationClient', 'set_robot_state': 'set the robot state in the simulation environment using set_robot_state on GrpcSimulationClient'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polysim/sim_interface.py

Prompts

```
['run the GrpcSimulationClient in a background thread with a specified time horizon using run_no_wait', 'stop the background simulation thread by calling kill_run on the GrpcSimulationClient', 'execute a gRPC call with round trip time logging via execute_rpc_call on GrpcSimulationClient', 'sync the simulation client state to a real robot using the sync method on GrpcSimulationClient', 'set the robot state in the simulation environment using set_robot_state on GrpcSimulationClient', 'create a SimInterface instance with a target control frequency in Hz', 'register arm control with a gRPC server address, state and action callbacks, and joint gains', 'register gripper control with a gRPC server address, state and action callbacks, and max width', 'register a step callback function that runs each simulation loop iteration', 'run the simulation loop for a given time horizon with optional fast-forward mode', 'create a FakeMetadata instance with a specified hz value for testing robot client metadata', 'create a FakeEnv with a given number of dimensions for testing controlled simulation environments', 'test the FakeConnection ControlUpdate method to verify it returns a TorqueCommand protobuf message', 'test the FakeEnv get_current_joint_pos_vel method to verify it returns zero numpy arrays', 'mock gRPC insecure_channel and PolymetisControllerServerStub using FakeChannel and FakeConnection for unit testing']
```

Usage

```
{'create_sim_interface': 'create a SimInterface instance with a target control frequency in Hz', 'register_arm_control': 'register arm control with a gRPC server address, state and action callbacks, and joint gains', 'register_gripper_control': 'register gripper control with a gRPC server address, state and action callbacks, and max width', 'register_step_callback': 'register a step callback function that runs each simulation loop iteration', 'run_simulation': 'run the simulation loop for a given time horizon with optional fast-forward mode'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polysim/test_utils.py

Prompts

```
['run the GrpcSimulationClient in a background thread with a specified time horizon using run_no_wait', 'stop the background simulation thread by calling kill_run on the GrpcSimulationClient', 'execute a gRPC call with round trip time logging via execute_rpc_call on GrpcSimulationClient', 'sync the simulation client state to a real robot using the sync method on GrpcSimulationClient', 'set the robot state in the simulation environment using set_robot_state on GrpcSimulationClient', 'create a SimInterface instance with a target control frequency in Hz', 'register arm control with a gRPC server address, state and action callbacks, and joint gains', 'register gripper control with a gRPC server address, state and action callbacks, and max width', 'register a step callback function that runs each simulation loop iteration', 'run the simulation loop for a given time horizon with optional fast-forward mode', 'create a FakeMetadata instance with a specified hz value for testing robot client metadata', 'create a FakeEnv with a given number of dimensions for testing controlled simulation environments', 'test the FakeConnection ControlUpdate method to verify it returns a TorqueCommand protobuf message', 'test the FakeEnv get_current_joint_pos_vel method to verify it returns zero numpy arrays', 'mock gRPC insecure_channel and PolymetisControllerServerStub using FakeChannel and FakeConnection for unit testing']
```

Usage

```
{'create_fake_metadata': 'create a FakeMetadata instance with a specified hz value for testing robot client metadata', 'create_fake_env': 'create a FakeEnv with a given number of dimensions for testing controlled simulation environments', 'test_fake_connection_control_update': 'test the FakeConnection ControlUpdate method to verify it returns a TorqueCommand protobuf message', 'test_fake_env_joint_pos_vel': 'test the FakeEnv get_current_joint_pos_vel method to verify it returns zero numpy arrays', 'mock_grpc_channel': 'mock gRPC insecure_channel and PolymetisControllerServerStub using FakeChannel and FakeConnection for unit testing'}
```

