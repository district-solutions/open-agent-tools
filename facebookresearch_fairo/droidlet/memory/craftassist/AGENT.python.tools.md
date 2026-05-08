# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/memory/craftassist/mc_attributes.py

Prompts

```
['create a VoxelCounter with memory and block_data dicts to count matching voxels', 'run VoxelCounter on a list of memory objects to get voxel counts per object', 'count voxels in BlockObject nodes by filtering against allowed block type triples', 'count voxels in InstSeg nodes by checking triple object tags match desired properties', 'get a string representation of VoxelCounter showing its block_data configuration', 'create an MCAgentMemory instance with a SQLite database and Minecraft block and mob type data', 'update the agent memory with perception output including mobs, players, blocks, and item stacks', 'add a changed block to memory as a new or merged BlockObject based on adjacent blocks', 'load all Minecraft block types with colors and properties into the agent memory triple store', 'load all Minecraft mob types with properties and spawn schematics into the agent memory', 'create a BlockObjectNode entry in memory from a sequence of Minecraft blocks with coordinates and block IDs', 'create a MobNode entry in memory to track a mob entity with position and look direction', 'create a SchematicNode entry in memory from a sequence of blocks representing a build plan', 'create an ItemStackNode entry in memory to track an item entity on the ground', 'create a RewardNode entry in memory to record a positive or negative reward value', 'create a SwarmWorkerMemory instance with send and receive queues for Minecraft agent memory', 'safe pickle a memory object by temporarily removing non-picklable attributes before serialization', 'safe unpickle a blob and reinstate non-picklable attributes from the key-value store', 'tag a memory entity with a descriptive label like AGENT or _physical_object', 'add a subject-predicate-object triple to the memory graph with optional confidence score']
```

Usage

```
{'init_voxelcounter_with_block_data': 'create a VoxelCounter with memory and block_data dicts to count matching voxels', 'call_voxelcounter_on_mems': 'run VoxelCounter on a list of memory objects to get voxel counts per object', 'count_blockobject_voxels': 'count voxels in BlockObject nodes by filtering against allowed block type triples', 'count_instseg_voxels': 'count voxels in InstSeg nodes by checking triple object tags match desired properties', 'repr_voxelcounter': 'get a string representation of VoxelCounter showing its block_data configuration'}
```

## File: facebookresearch_fairo/droidlet/memory/craftassist/mc_memory.py

Prompts

```
['create a VoxelCounter with memory and block_data dicts to count matching voxels', 'run VoxelCounter on a list of memory objects to get voxel counts per object', 'count voxels in BlockObject nodes by filtering against allowed block type triples', 'count voxels in InstSeg nodes by checking triple object tags match desired properties', 'get a string representation of VoxelCounter showing its block_data configuration', 'create an MCAgentMemory instance with a SQLite database and Minecraft block and mob type data', 'update the agent memory with perception output including mobs, players, blocks, and item stacks', 'add a changed block to memory as a new or merged BlockObject based on adjacent blocks', 'load all Minecraft block types with colors and properties into the agent memory triple store', 'load all Minecraft mob types with properties and spawn schematics into the agent memory', 'create a BlockObjectNode entry in memory from a sequence of Minecraft blocks with coordinates and block IDs', 'create a MobNode entry in memory to track a mob entity with position and look direction', 'create a SchematicNode entry in memory from a sequence of blocks representing a build plan', 'create an ItemStackNode entry in memory to track an item entity on the ground', 'create a RewardNode entry in memory to record a positive or negative reward value', 'create a SwarmWorkerMemory instance with send and receive queues for Minecraft agent memory', 'safe pickle a memory object by temporarily removing non-picklable attributes before serialization', 'safe unpickle a blob and reinstate non-picklable attributes from the key-value store', 'tag a memory entity with a descriptive label like AGENT or _physical_object', 'add a subject-predicate-object triple to the memory graph with optional confidence score']
```

Usage

```
{'init_MCAgentMemory': 'create an MCAgentMemory instance with a SQLite database and Minecraft block and mob type data', 'update_perception': 'update the agent memory with perception output including mobs, players, blocks, and item stacks', 'add_block_to_memory': 'add a changed block to memory as a new or merged BlockObject based on adjacent blocks', 'load_block_types': 'load all Minecraft block types with colors and properties into the agent memory triple store', 'load_mob_types': 'load all Minecraft mob types with properties and spawn schematics into the agent memory'}
```

## File: facebookresearch_fairo/droidlet/memory/craftassist/mc_memory_nodes.py

Prompts

```
['create a VoxelCounter with memory and block_data dicts to count matching voxels', 'run VoxelCounter on a list of memory objects to get voxel counts per object', 'count voxels in BlockObject nodes by filtering against allowed block type triples', 'count voxels in InstSeg nodes by checking triple object tags match desired properties', 'get a string representation of VoxelCounter showing its block_data configuration', 'create an MCAgentMemory instance with a SQLite database and Minecraft block and mob type data', 'update the agent memory with perception output including mobs, players, blocks, and item stacks', 'add a changed block to memory as a new or merged BlockObject based on adjacent blocks', 'load all Minecraft block types with colors and properties into the agent memory triple store', 'load all Minecraft mob types with properties and spawn schematics into the agent memory', 'create a BlockObjectNode entry in memory from a sequence of Minecraft blocks with coordinates and block IDs', 'create a MobNode entry in memory to track a mob entity with position and look direction', 'create a SchematicNode entry in memory from a sequence of blocks representing a build plan', 'create an ItemStackNode entry in memory to track an item entity on the ground', 'create a RewardNode entry in memory to record a positive or negative reward value', 'create a SwarmWorkerMemory instance with send and receive queues for Minecraft agent memory', 'safe pickle a memory object by temporarily removing non-picklable attributes before serialization', 'safe unpickle a blob and reinstate non-picklable attributes from the key-value store', 'tag a memory entity with a descriptive label like AGENT or _physical_object', 'add a subject-predicate-object triple to the memory graph with optional confidence score']
```

Usage

```
{'create_block_object': 'create a BlockObjectNode entry in memory from a sequence of Minecraft blocks with coordinates and block IDs', 'create_mob_node': 'create a MobNode entry in memory to track a mob entity with position and look direction', 'create_schematic_node': 'create a SchematicNode entry in memory from a sequence of blocks representing a build plan', 'create_item_stack_node': 'create an ItemStackNode entry in memory to track an item entity on the ground', 'create_reward_node': 'create a RewardNode entry in memory to record a positive or negative reward value'}
```

## File: facebookresearch_fairo/droidlet/memory/craftassist/swarm_worker_memory.py

Prompts

```
['create a VoxelCounter with memory and block_data dicts to count matching voxels', 'run VoxelCounter on a list of memory objects to get voxel counts per object', 'count voxels in BlockObject nodes by filtering against allowed block type triples', 'count voxels in InstSeg nodes by checking triple object tags match desired properties', 'get a string representation of VoxelCounter showing its block_data configuration', 'create an MCAgentMemory instance with a SQLite database and Minecraft block and mob type data', 'update the agent memory with perception output including mobs, players, blocks, and item stacks', 'add a changed block to memory as a new or merged BlockObject based on adjacent blocks', 'load all Minecraft block types with colors and properties into the agent memory triple store', 'load all Minecraft mob types with properties and spawn schematics into the agent memory', 'create a BlockObjectNode entry in memory from a sequence of Minecraft blocks with coordinates and block IDs', 'create a MobNode entry in memory to track a mob entity with position and look direction', 'create a SchematicNode entry in memory from a sequence of blocks representing a build plan', 'create an ItemStackNode entry in memory to track an item entity on the ground', 'create a RewardNode entry in memory to record a positive or negative reward value', 'create a SwarmWorkerMemory instance with send and receive queues for Minecraft agent memory', 'safe pickle a memory object by temporarily removing non-picklable attributes before serialization', 'safe unpickle a blob and reinstate non-picklable attributes from the key-value store', 'tag a memory entity with a descriptive label like AGENT or _physical_object', 'add a subject-predicate-object triple to the memory graph with optional confidence score']
```

Usage

```
{'create_swarm_worker_memory': 'create a SwarmWorkerMemory instance with send and receive queues for Minecraft agent memory', 'safe_pickle_object': 'safe pickle a memory object by temporarily removing non-picklable attributes before serialization', 'safe_unpickle_blob': 'safe unpickle a blob and reinstate non-picklable attributes from the key-value store', 'tag_memory_entity': 'tag a memory entity with a descriptive label like AGENT or _physical_object', 'add_triple_to_memory': 'add a subject-predicate-object triple to the memory graph with optional confidence score'}
```

