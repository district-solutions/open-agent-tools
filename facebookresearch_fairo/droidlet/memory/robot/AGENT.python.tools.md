# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/memory/robot/loco_memory.py

Prompts

```
['create a LocoAgentMemory instance with an in-memory or file-backed SQLite database and schema paths', 'update the agent memory world model with new objects, updated objects, humans, and obstacle map from perception', 'update or create player nodes in memory from a list of player structs with entity IDs', 'get detected object memory IDs that match all provided tags using triple store intersection', 'clear and forget all non-self objects from memory by their memory IDs', 'create a DetectedObjectNode in agent memory from a detected object with position, features, and tags', 'update an existing DetectedObjectNode position and feature blob in the agent memory database', 'retrieve all DetectedObjectNode entries from the agent memory with labels, colors, and bounds', 'create a HumanPoseNode in agent memory from a human pose with keypoints and xyz position', 'create a DanceNode in agent memory with a dance function, optional name, and tags']
```

Usage

```
{'init_LocoAgentMemory': 'create a LocoAgentMemory instance with an in-memory or file-backed SQLite database and schema paths', 'update_perception': 'update the agent memory world model with new objects, updated objects, humans, and obstacle map from perception', 'update_other_players': 'update or create player nodes in memory from a list of player structs with entity IDs', 'get_detected_objects_tagged': 'get detected object memory IDs that match all provided tags using triple store intersection', 'clear_objects': 'clear and forget all non-self objects from memory by their memory IDs'}
```

## File: facebookresearch_fairo/droidlet/memory/robot/loco_memory_nodes.py

Prompts

```
['create a LocoAgentMemory instance with an in-memory or file-backed SQLite database and schema paths', 'update the agent memory world model with new objects, updated objects, humans, and obstacle map from perception', 'update or create player nodes in memory from a list of player structs with entity IDs', 'get detected object memory IDs that match all provided tags using triple store intersection', 'clear and forget all non-self objects from memory by their memory IDs', 'create a DetectedObjectNode in agent memory from a detected object with position, features, and tags', 'update an existing DetectedObjectNode position and feature blob in the agent memory database', 'retrieve all DetectedObjectNode entries from the agent memory with labels, colors, and bounds', 'create a HumanPoseNode in agent memory from a human pose with keypoints and xyz position', 'create a DanceNode in agent memory with a dance function, optional name, and tags']
```

Usage

```
{'create_detected_object': 'create a DetectedObjectNode in agent memory from a detected object with position, features, and tags', 'update_detected_object': 'update an existing DetectedObjectNode position and feature blob in the agent memory database', 'get_all_detected_objects': 'retrieve all DetectedObjectNode entries from the agent memory with labels, colors, and bounds', 'create_human_pose': 'create a HumanPoseNode in agent memory from a human pose with keypoints and xyz position', 'create_dance': 'create a DanceNode in agent memory with a dance function, optional name, and tags'}
```

