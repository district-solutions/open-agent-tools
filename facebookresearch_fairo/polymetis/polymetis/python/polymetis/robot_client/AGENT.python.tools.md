# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_client/abstract_robot_client.py

Prompts

```
['review the AbstractRobotClient abstract base class and its interface for RobotClient subclasses', 'review the AbstractRobotClient constructor that instantiates RobotClientMetadata from a Hydra DictConfig', 'review the abstract run method that subclasses must override to connect to the gRPC server', 'create a subclass of AbstractRobotClient that overrides the run method to connect to a gRPC server', 'refactor the AbstractRobotClient class to add additional abstract methods for robot client lifecycle management', 'run the ExecutableRobotClient to launch a robot executable as a subprocess with config', 'create an ExecutableRobotClient instance with an OmegaConf config and real-time flag', 'review the ExecutableRobotClient run method that spawns a subprocess with temp config files', 'refactor the ExecutableRobotClient to customize the sudo command list for real-time execution', 'summarize the ExecutableRobotClient class that runs robot executables as subprocesses with metadata', 'create a RobotClientMetadata instance with default controller gains and robot model config', 'serialize a RobotClientMetadata protobuf message to bytes for network transmission', 'get the underlying protobuf message from a RobotClientMetadata instance', 'create an EmptyRobotClientMetadata instance with an empty protobuf message', 'build a RobotModelConfig dataclass with joint limits, rest pose, and URDF path']
```

Usage

```
{'review_AbstractRobotClient': 'review the AbstractRobotClient abstract base class and its interface for RobotClient subclasses', 'review_AbstractRobotClient_init': 'review the AbstractRobotClient constructor that instantiates RobotClientMetadata from a Hydra DictConfig', 'review_AbstractRobotClient_run': 'review the abstract run method that subclasses must override to connect to the gRPC server', 'create_robot_client_subclass': 'create a subclass of AbstractRobotClient that overrides the run method to connect to a gRPC server', 'refactor_AbstractRobotClient': 'refactor the AbstractRobotClient class to add additional abstract methods for robot client lifecycle management'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_client/executable_robot_client.py

Prompts

```
['review the AbstractRobotClient abstract base class and its interface for RobotClient subclasses', 'review the AbstractRobotClient constructor that instantiates RobotClientMetadata from a Hydra DictConfig', 'review the abstract run method that subclasses must override to connect to the gRPC server', 'create a subclass of AbstractRobotClient that overrides the run method to connect to a gRPC server', 'refactor the AbstractRobotClient class to add additional abstract methods for robot client lifecycle management', 'run the ExecutableRobotClient to launch a robot executable as a subprocess with config', 'create an ExecutableRobotClient instance with an OmegaConf config and real-time flag', 'review the ExecutableRobotClient run method that spawns a subprocess with temp config files', 'refactor the ExecutableRobotClient to customize the sudo command list for real-time execution', 'summarize the ExecutableRobotClient class that runs robot executables as subprocesses with metadata', 'create a RobotClientMetadata instance with default controller gains and robot model config', 'serialize a RobotClientMetadata protobuf message to bytes for network transmission', 'get the underlying protobuf message from a RobotClientMetadata instance', 'create an EmptyRobotClientMetadata instance with an empty protobuf message', 'build a RobotModelConfig dataclass with joint limits, rest pose, and URDF path']
```

Usage

```
{'run_executable_robot_client': 'run the ExecutableRobotClient to launch a robot executable as a subprocess with config', 'create_executable_robot_client': 'create an ExecutableRobotClient instance with an OmegaConf config and real-time flag', 'review_executable_robot_client_run': 'review the ExecutableRobotClient run method that spawns a subprocess with temp config files', 'refactor_executable_robot_client_sudo': 'refactor the ExecutableRobotClient to customize the sudo command list for real-time execution', 'summarize_executable_robot_client': 'summarize the ExecutableRobotClient class that runs robot executables as subprocesses with metadata'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_client/metadata.py

Prompts

```
['review the AbstractRobotClient abstract base class and its interface for RobotClient subclasses', 'review the AbstractRobotClient constructor that instantiates RobotClientMetadata from a Hydra DictConfig', 'review the abstract run method that subclasses must override to connect to the gRPC server', 'create a subclass of AbstractRobotClient that overrides the run method to connect to a gRPC server', 'refactor the AbstractRobotClient class to add additional abstract methods for robot client lifecycle management', 'run the ExecutableRobotClient to launch a robot executable as a subprocess with config', 'create an ExecutableRobotClient instance with an OmegaConf config and real-time flag', 'review the ExecutableRobotClient run method that spawns a subprocess with temp config files', 'refactor the ExecutableRobotClient to customize the sudo command list for real-time execution', 'summarize the ExecutableRobotClient class that runs robot executables as subprocesses with metadata', 'create a RobotClientMetadata instance with default controller gains and robot model config', 'serialize a RobotClientMetadata protobuf message to bytes for network transmission', 'get the underlying protobuf message from a RobotClientMetadata instance', 'create an EmptyRobotClientMetadata instance with an empty protobuf message', 'build a RobotModelConfig dataclass with joint limits, rest pose, and URDF path']
```

Usage

```
{'create_robot_client_metadata': 'create a RobotClientMetadata instance with default controller gains and robot model config', 'serialize_robot_metadata': 'serialize a RobotClientMetadata protobuf message to bytes for network transmission', 'get_robot_metadata_proto': 'get the underlying protobuf message from a RobotClientMetadata instance', 'create_empty_robot_metadata': 'create an EmptyRobotClientMetadata instance with an empty protobuf message', 'build_robot_model_config': 'build a RobotModelConfig dataclass with joint limits, rest pose, and URDF path'}
```

