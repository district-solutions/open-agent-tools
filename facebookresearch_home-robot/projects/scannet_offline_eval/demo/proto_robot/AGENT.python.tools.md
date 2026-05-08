# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/scannet_offline_eval/demo/proto_robot/mock_publisher.py

Prompts

```
['serialize a PyTorch tensor to bytes using io.BytesIO and torch.save', 'convert a PyTorch tensor into a robodata_pb2.RoboTensor protobuf message with dtype and shape', 'build a RobotSummary protobuf message from pickled robot data including RGB, depth, and GPS', 'stream RobotSummary messages to a gRPC server using the ReceiveRobotData stub method', 'send an LLM chat message with an attached image tensor via the gRPC Chat stub', 'run the gRPC RoboData server on port 50051 with a configurable thread pool and message size limits', 'start the RoboData gRPC server with argparse options for VLM config path, GPU ID, and context length', 'send a chat request with conversation history and images to the MiniGPT-4 VLM model via the Chat RPC', 'stream robot observation data to the server via the ReceiveRobotData RPC and get a confirmation response', 'convert a protobuf tensor message back into a PyTorch tensor using torch.load on serialized bytes']
```

Usage

```
{'tensor_to_bytes': 'serialize a PyTorch tensor to bytes using io.BytesIO and torch.save', 'tensor_to_robotensor': 'convert a PyTorch tensor into a robodata_pb2.RoboTensor protobuf message with dtype and shape', 'create_msg_from_file': 'build a RobotSummary protobuf message from pickled robot data including RGB, depth, and GPS', 'send_robot_data': 'stream RobotSummary messages to a gRPC server using the ReceiveRobotData stub method', 'test_conversation': 'send an LLM chat message with an attached image tensor via the gRPC Chat stub'}
```

## File: facebookresearch_home-robot/projects/scannet_offline_eval/demo/proto_robot/robodata_server.py

Prompts

```
['serialize a PyTorch tensor to bytes using io.BytesIO and torch.save', 'convert a PyTorch tensor into a robodata_pb2.RoboTensor protobuf message with dtype and shape', 'build a RobotSummary protobuf message from pickled robot data including RGB, depth, and GPS', 'stream RobotSummary messages to a gRPC server using the ReceiveRobotData stub method', 'send an LLM chat message with an attached image tensor via the gRPC Chat stub', 'run the gRPC RoboData server on port 50051 with a configurable thread pool and message size limits', 'start the RoboData gRPC server with argparse options for VLM config path, GPU ID, and context length', 'send a chat request with conversation history and images to the MiniGPT-4 VLM model via the Chat RPC', 'stream robot observation data to the server via the ReceiveRobotData RPC and get a confirmation response', 'convert a protobuf tensor message back into a PyTorch tensor using torch.load on serialized bytes']
```

Usage

```
{'run_grpc_server': 'run the gRPC RoboData server on port 50051 with a configurable thread pool and message size limits', 'serve_with_args': 'start the RoboData gRPC server with argparse options for VLM config path, GPU ID, and context length', 'chat_with_vlm': 'send a chat request with conversation history and images to the MiniGPT-4 VLM model via the Chat RPC', 'receive_robot_data': 'stream robot observation data to the server via the ReceiveRobotData RPC and get a confirmation response', 'convert_proto_tensor': 'convert a protobuf tensor message back into a PyTorch tensor using torch.load on serialized bytes'}
```

