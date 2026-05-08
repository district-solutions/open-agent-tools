# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/agents/locobot/tests/test_agent.py

Prompts

```
['test connecting to the locobot agent via Socket.IO with retry logic on localhost:8000', 'test sending movement commands like move forward and turn right to the agent', 'test that the agent returns object detection output via the objects event', 'test polling the agent with get_count events until it starts executing', 'test shutting down the agent and disconnecting the Socket.IO client cleanly', 'test the MoveAbsoluteTest class to verify robot forward, right, left, and coordinate movement commands', 'test the MoveRefObjectsTest class to verify robot navigation to and between referenced objects like cubes', 'test the TurnTest class to verify robot left and right turn commands with 90 degree yaw changes', 'test the stop command in MoveAbsoluteTest to verify an in-progress move halts before reaching the target', 'test sequential multi-coordinate movement commands to verify the agent visits waypoints in order', 'run the unittest test suite for LocoAgentMemory detected object and human pose node creation', 'test creating a DetectedObjectNode in LocoAgentMemory and verify class labels and properties are saved as tags', 'test that DetectedObjectNode correctly computes and stores 3D bounding box bounds from an RGBDepth detection', 'test creating a HumanPoseNode in LocoAgentMemory and verify the _human_pose tag is set', 'review the MemoryTests unittest class that validates LocoAgentMemory node creation for objects and human poses']
```

Usage

```
{'test_locobot_agent_connection': 'test connecting to the locobot agent via Socket.IO with retry logic on localhost:8000', 'test_send_command_to_agent': 'test sending movement commands like move forward and turn right to the agent', 'test_agent_object_detection': 'test that the agent returns object detection output via the objects event', 'test_agent_startup_polling': 'test polling the agent with get_count events until it starts executing', 'test_agent_shutdown': 'test shutting down the agent and disconnecting the Socket.IO client cleanly'}
```

## File: facebookresearch_fairo/agents/locobot/tests/test_interpreter_mock.py

Prompts

```
['test connecting to the locobot agent via Socket.IO with retry logic on localhost:8000', 'test sending movement commands like move forward and turn right to the agent', 'test that the agent returns object detection output via the objects event', 'test polling the agent with get_count events until it starts executing', 'test shutting down the agent and disconnecting the Socket.IO client cleanly', 'test the MoveAbsoluteTest class to verify robot forward, right, left, and coordinate movement commands', 'test the MoveRefObjectsTest class to verify robot navigation to and between referenced objects like cubes', 'test the TurnTest class to verify robot left and right turn commands with 90 degree yaw changes', 'test the stop command in MoveAbsoluteTest to verify an in-progress move halts before reaching the target', 'test sequential multi-coordinate movement commands to verify the agent visits waypoints in order', 'run the unittest test suite for LocoAgentMemory detected object and human pose node creation', 'test creating a DetectedObjectNode in LocoAgentMemory and verify class labels and properties are saved as tags', 'test that DetectedObjectNode correctly computes and stores 3D bounding box bounds from an RGBDepth detection', 'test creating a HumanPoseNode in LocoAgentMemory and verify the _human_pose tag is set', 'review the MemoryTests unittest class that validates LocoAgentMemory node creation for objects and human poses']
```

Usage

```
{'test_move_absolute': 'test the MoveAbsoluteTest class to verify robot forward, right, left, and coordinate movement commands', 'test_move_ref_objects': 'test the MoveRefObjectsTest class to verify robot navigation to and between referenced objects like cubes', 'test_turn': 'test the TurnTest class to verify robot left and right turn commands with 90 degree yaw changes', 'test_stop': 'test the stop command in MoveAbsoluteTest to verify an in-progress move halts before reaching the target', 'test_action_sequence_order': 'test sequential multi-coordinate movement commands to verify the agent visits waypoints in order'}
```

## File: facebookresearch_fairo/agents/locobot/tests/test_memory.py

Prompts

```
['test connecting to the locobot agent via Socket.IO with retry logic on localhost:8000', 'test sending movement commands like move forward and turn right to the agent', 'test that the agent returns object detection output via the objects event', 'test polling the agent with get_count events until it starts executing', 'test shutting down the agent and disconnecting the Socket.IO client cleanly', 'test the MoveAbsoluteTest class to verify robot forward, right, left, and coordinate movement commands', 'test the MoveRefObjectsTest class to verify robot navigation to and between referenced objects like cubes', 'test the TurnTest class to verify robot left and right turn commands with 90 degree yaw changes', 'test the stop command in MoveAbsoluteTest to verify an in-progress move halts before reaching the target', 'test sequential multi-coordinate movement commands to verify the agent visits waypoints in order', 'run the unittest test suite for LocoAgentMemory detected object and human pose node creation', 'test creating a DetectedObjectNode in LocoAgentMemory and verify class labels and properties are saved as tags', 'test that DetectedObjectNode correctly computes and stores 3D bounding box bounds from an RGBDepth detection', 'test creating a HumanPoseNode in LocoAgentMemory and verify the _human_pose tag is set', 'review the MemoryTests unittest class that validates LocoAgentMemory node creation for objects and human poses']
```

Usage

```
{'run_memory_tests': 'run the unittest test suite for LocoAgentMemory detected object and human pose node creation', 'test_detected_object_node_creation': 'test creating a DetectedObjectNode in LocoAgentMemory and verify class labels and properties are saved as tags', 'test_detected_object_3dbbox': 'test that DetectedObjectNode correctly computes and stores 3D bounding box bounds from an RGBDepth detection', 'test_humanpose_node_creation': 'test creating a HumanPoseNode in LocoAgentMemory and verify the _human_pose tag is set', 'review_memorytests_class': 'review the MemoryTests unittest class that validates LocoAgentMemory node creation for objects and human poses'}
```

