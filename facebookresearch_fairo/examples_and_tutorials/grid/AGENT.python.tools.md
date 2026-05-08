# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/examples_and_tutorials/grid/grid_agent.py

Prompts

```
['run the GridAgent main module to start a grid world simulation with bots', 'create a GridAgent instance with a World and options for grid-based task execution', 'test the GridAgent perceive method to update world state and run perception modules', 'refactor the GridAgent controller_step method to manage bot task stacking logic', 'review the GridAgent catch method to verify bot removal when agent is within distance', 'create a GridMemory instance with an in-memory SQLite database and base memory schema', "update a bot's x, y, z position in the ReferenceObjects table by entity ID", 'delete a bot entry from the ReferenceObjects table by its entity ID', 'get all entity IDs of bots stored in the ReferenceObjects table', 'review the GridMemory class and its bot CRUD methods for the Droidlet agent memory system', 'create a BotNode instance from agent memory and a given memory ID', 'create a new bot entry in the ReferenceObjects table using BotNode.create', 'get the current x, y, z position of a bot from memory using get_pos', 'review the BotNode class and its ReferenceObjectNode inheritance and DB schema', 'refactor the BotNode init to handle missing database rows gracefully', 'create a HeuristicPerception instance that tracks bots in the agent world', 'run the perceive method to scan the world and update bot memory nodes', 'create a PlayerNode in memory for a newly perceived bot entity', 'tag bot memory nodes with the bot tag using TripleNode', 'forget bot memory entries for bots that are no longer in the world', 'create a Move task that moves an agent to a target x, y, z coordinate', 'create a Grab task that catches a bot entity by its entity ID', 'create a Catch task that navigates an agent toward a target and grabs it', 'review the Catch class step method that moves one block at a time before grabbing', 'refactor the Move class to support dynamic target coordinate updates before execution', 'create a World instance that spawns N bots at random positions on a 5x5 grid', 'step the World simulation to move all bots one random position on the grid', 'get all bots or filter bots by entity ID from the World instance', 'remove a bot from the World by its entity ID', 'visualize the World grid with bot positions and agent location using matplotlib']
```

Usage

```
{'run_grid_agent': 'run the GridAgent main module to start a grid world simulation with bots', 'create_grid_agent': 'create a GridAgent instance with a World and options for grid-based task execution', 'test_grid_agent_perceive': 'test the GridAgent perceive method to update world state and run perception modules', 'refactor_grid_agent_controller_step': 'refactor the GridAgent controller_step method to manage bot task stacking logic', 'review_grid_agent_catch': 'review the GridAgent catch method to verify bot removal when agent is within distance'}
```

## File: facebookresearch_fairo/examples_and_tutorials/grid/grid_memory.py

Prompts

```
['run the GridAgent main module to start a grid world simulation with bots', 'create a GridAgent instance with a World and options for grid-based task execution', 'test the GridAgent perceive method to update world state and run perception modules', 'refactor the GridAgent controller_step method to manage bot task stacking logic', 'review the GridAgent catch method to verify bot removal when agent is within distance', 'create a GridMemory instance with an in-memory SQLite database and base memory schema', "update a bot's x, y, z position in the ReferenceObjects table by entity ID", 'delete a bot entry from the ReferenceObjects table by its entity ID', 'get all entity IDs of bots stored in the ReferenceObjects table', 'review the GridMemory class and its bot CRUD methods for the Droidlet agent memory system', 'create a BotNode instance from agent memory and a given memory ID', 'create a new bot entry in the ReferenceObjects table using BotNode.create', 'get the current x, y, z position of a bot from memory using get_pos', 'review the BotNode class and its ReferenceObjectNode inheritance and DB schema', 'refactor the BotNode init to handle missing database rows gracefully', 'create a HeuristicPerception instance that tracks bots in the agent world', 'run the perceive method to scan the world and update bot memory nodes', 'create a PlayerNode in memory for a newly perceived bot entity', 'tag bot memory nodes with the bot tag using TripleNode', 'forget bot memory entries for bots that are no longer in the world', 'create a Move task that moves an agent to a target x, y, z coordinate', 'create a Grab task that catches a bot entity by its entity ID', 'create a Catch task that navigates an agent toward a target and grabs it', 'review the Catch class step method that moves one block at a time before grabbing', 'refactor the Move class to support dynamic target coordinate updates before execution', 'create a World instance that spawns N bots at random positions on a 5x5 grid', 'step the World simulation to move all bots one random position on the grid', 'get all bots or filter bots by entity ID from the World instance', 'remove a bot from the World by its entity ID', 'visualize the World grid with bot positions and agent location using matplotlib']
```

Usage

```
{'create_gridmemory_instance': 'create a GridMemory instance with an in-memory SQLite database and base memory schema', 'update_bot_info': "update a bot's x, y, z position in the ReferenceObjects table by entity ID", 'delete_bot': 'delete a bot entry from the ReferenceObjects table by its entity ID', 'get_all_bot_eids': 'get all entity IDs of bots stored in the ReferenceObjects table', 'review_gridmemory_class': 'review the GridMemory class and its bot CRUD methods for the Droidlet agent memory system'}
```

## File: facebookresearch_fairo/examples_and_tutorials/grid/grid_memory_nodes.py

Prompts

```
['run the GridAgent main module to start a grid world simulation with bots', 'create a GridAgent instance with a World and options for grid-based task execution', 'test the GridAgent perceive method to update world state and run perception modules', 'refactor the GridAgent controller_step method to manage bot task stacking logic', 'review the GridAgent catch method to verify bot removal when agent is within distance', 'create a GridMemory instance with an in-memory SQLite database and base memory schema', "update a bot's x, y, z position in the ReferenceObjects table by entity ID", 'delete a bot entry from the ReferenceObjects table by its entity ID', 'get all entity IDs of bots stored in the ReferenceObjects table', 'review the GridMemory class and its bot CRUD methods for the Droidlet agent memory system', 'create a BotNode instance from agent memory and a given memory ID', 'create a new bot entry in the ReferenceObjects table using BotNode.create', 'get the current x, y, z position of a bot from memory using get_pos', 'review the BotNode class and its ReferenceObjectNode inheritance and DB schema', 'refactor the BotNode init to handle missing database rows gracefully', 'create a HeuristicPerception instance that tracks bots in the agent world', 'run the perceive method to scan the world and update bot memory nodes', 'create a PlayerNode in memory for a newly perceived bot entity', 'tag bot memory nodes with the bot tag using TripleNode', 'forget bot memory entries for bots that are no longer in the world', 'create a Move task that moves an agent to a target x, y, z coordinate', 'create a Grab task that catches a bot entity by its entity ID', 'create a Catch task that navigates an agent toward a target and grabs it', 'review the Catch class step method that moves one block at a time before grabbing', 'refactor the Move class to support dynamic target coordinate updates before execution', 'create a World instance that spawns N bots at random positions on a 5x5 grid', 'step the World simulation to move all bots one random position on the grid', 'get all bots or filter bots by entity ID from the World instance', 'remove a bot from the World by its entity ID', 'visualize the World grid with bot positions and agent location using matplotlib']
```

Usage

```
{'create_bot_node': 'create a BotNode instance from agent memory and a given memory ID', 'create_bot_in_memory': 'create a new bot entry in the ReferenceObjects table using BotNode.create', 'get_bot_position': 'get the current x, y, z position of a bot from memory using get_pos', 'review_botnode_class': 'review the BotNode class and its ReferenceObjectNode inheritance and DB schema', 'refactor_botnode_init': 'refactor the BotNode init to handle missing database rows gracefully'}
```

## File: facebookresearch_fairo/examples_and_tutorials/grid/heuristic_perception.py

Prompts

```
['run the GridAgent main module to start a grid world simulation with bots', 'create a GridAgent instance with a World and options for grid-based task execution', 'test the GridAgent perceive method to update world state and run perception modules', 'refactor the GridAgent controller_step method to manage bot task stacking logic', 'review the GridAgent catch method to verify bot removal when agent is within distance', 'create a GridMemory instance with an in-memory SQLite database and base memory schema', "update a bot's x, y, z position in the ReferenceObjects table by entity ID", 'delete a bot entry from the ReferenceObjects table by its entity ID', 'get all entity IDs of bots stored in the ReferenceObjects table', 'review the GridMemory class and its bot CRUD methods for the Droidlet agent memory system', 'create a BotNode instance from agent memory and a given memory ID', 'create a new bot entry in the ReferenceObjects table using BotNode.create', 'get the current x, y, z position of a bot from memory using get_pos', 'review the BotNode class and its ReferenceObjectNode inheritance and DB schema', 'refactor the BotNode init to handle missing database rows gracefully', 'create a HeuristicPerception instance that tracks bots in the agent world', 'run the perceive method to scan the world and update bot memory nodes', 'create a PlayerNode in memory for a newly perceived bot entity', 'tag bot memory nodes with the bot tag using TripleNode', 'forget bot memory entries for bots that are no longer in the world', 'create a Move task that moves an agent to a target x, y, z coordinate', 'create a Grab task that catches a bot entity by its entity ID', 'create a Catch task that navigates an agent toward a target and grabs it', 'review the Catch class step method that moves one block at a time before grabbing', 'refactor the Move class to support dynamic target coordinate updates before execution', 'create a World instance that spawns N bots at random positions on a 5x5 grid', 'step the World simulation to move all bots one random position on the grid', 'get all bots or filter bots by entity ID from the World instance', 'remove a bot from the World by its entity ID', 'visualize the World grid with bot positions and agent location using matplotlib']
```

Usage

```
{'create_heuristic_perception_agent': 'create a HeuristicPerception instance that tracks bots in the agent world', 'run_perceive_bots': 'run the perceive method to scan the world and update bot memory nodes', 'create_player_node_for_bot': 'create a PlayerNode in memory for a newly perceived bot entity', 'tag_bot_memory_nodes': 'tag bot memory nodes with the bot tag using TripleNode', 'forget_removed_bots': 'forget bot memory entries for bots that are no longer in the world'}
```

## File: facebookresearch_fairo/examples_and_tutorials/grid/tasks.py

Prompts

```
['run the GridAgent main module to start a grid world simulation with bots', 'create a GridAgent instance with a World and options for grid-based task execution', 'test the GridAgent perceive method to update world state and run perception modules', 'refactor the GridAgent controller_step method to manage bot task stacking logic', 'review the GridAgent catch method to verify bot removal when agent is within distance', 'create a GridMemory instance with an in-memory SQLite database and base memory schema', "update a bot's x, y, z position in the ReferenceObjects table by entity ID", 'delete a bot entry from the ReferenceObjects table by its entity ID', 'get all entity IDs of bots stored in the ReferenceObjects table', 'review the GridMemory class and its bot CRUD methods for the Droidlet agent memory system', 'create a BotNode instance from agent memory and a given memory ID', 'create a new bot entry in the ReferenceObjects table using BotNode.create', 'get the current x, y, z position of a bot from memory using get_pos', 'review the BotNode class and its ReferenceObjectNode inheritance and DB schema', 'refactor the BotNode init to handle missing database rows gracefully', 'create a HeuristicPerception instance that tracks bots in the agent world', 'run the perceive method to scan the world and update bot memory nodes', 'create a PlayerNode in memory for a newly perceived bot entity', 'tag bot memory nodes with the bot tag using TripleNode', 'forget bot memory entries for bots that are no longer in the world', 'create a Move task that moves an agent to a target x, y, z coordinate', 'create a Grab task that catches a bot entity by its entity ID', 'create a Catch task that navigates an agent toward a target and grabs it', 'review the Catch class step method that moves one block at a time before grabbing', 'refactor the Move class to support dynamic target coordinate updates before execution', 'create a World instance that spawns N bots at random positions on a 5x5 grid', 'step the World simulation to move all bots one random position on the grid', 'get all bots or filter bots by entity ID from the World instance', 'remove a bot from the World by its entity ID', 'visualize the World grid with bot positions and agent location using matplotlib']
```

Usage

```
{'create_Move_task': 'create a Move task that moves an agent to a target x, y, z coordinate', 'create_Grab_task': 'create a Grab task that catches a bot entity by its entity ID', 'create_Catch_task': 'create a Catch task that navigates an agent toward a target and grabs it', 'review_Catch_step_logic': 'review the Catch class step method that moves one block at a time before grabbing', 'refactor_Move_target': 'refactor the Move class to support dynamic target coordinate updates before execution'}
```

## File: facebookresearch_fairo/examples_and_tutorials/grid/world.py

Prompts

```
['run the GridAgent main module to start a grid world simulation with bots', 'create a GridAgent instance with a World and options for grid-based task execution', 'test the GridAgent perceive method to update world state and run perception modules', 'refactor the GridAgent controller_step method to manage bot task stacking logic', 'review the GridAgent catch method to verify bot removal when agent is within distance', 'create a GridMemory instance with an in-memory SQLite database and base memory schema', "update a bot's x, y, z position in the ReferenceObjects table by entity ID", 'delete a bot entry from the ReferenceObjects table by its entity ID', 'get all entity IDs of bots stored in the ReferenceObjects table', 'review the GridMemory class and its bot CRUD methods for the Droidlet agent memory system', 'create a BotNode instance from agent memory and a given memory ID', 'create a new bot entry in the ReferenceObjects table using BotNode.create', 'get the current x, y, z position of a bot from memory using get_pos', 'review the BotNode class and its ReferenceObjectNode inheritance and DB schema', 'refactor the BotNode init to handle missing database rows gracefully', 'create a HeuristicPerception instance that tracks bots in the agent world', 'run the perceive method to scan the world and update bot memory nodes', 'create a PlayerNode in memory for a newly perceived bot entity', 'tag bot memory nodes with the bot tag using TripleNode', 'forget bot memory entries for bots that are no longer in the world', 'create a Move task that moves an agent to a target x, y, z coordinate', 'create a Grab task that catches a bot entity by its entity ID', 'create a Catch task that navigates an agent toward a target and grabs it', 'review the Catch class step method that moves one block at a time before grabbing', 'refactor the Move class to support dynamic target coordinate updates before execution', 'create a World instance that spawns N bots at random positions on a 5x5 grid', 'step the World simulation to move all bots one random position on the grid', 'get all bots or filter bots by entity ID from the World instance', 'remove a bot from the World by its entity ID', 'visualize the World grid with bot positions and agent location using matplotlib']
```

Usage

```
{'create_world_with_bots': 'create a World instance that spawns N bots at random positions on a 5x5 grid', 'step_world_simulation': 'step the World simulation to move all bots one random position on the grid', 'get_bots_by_entity_id': 'get all bots or filter bots by entity ID from the World instance', 'remove_bot_from_world': 'remove a bot from the World by its entity ID', 'visualize_world_grid': 'visualize the World grid with bot positions and agent location using matplotlib'}
```

