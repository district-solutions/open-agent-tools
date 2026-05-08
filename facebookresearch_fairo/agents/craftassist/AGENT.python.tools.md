# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/agents/craftassist/craftassist_agent.py

Prompts

```
['run the CraftAssistAgent as a standalone Minecraft assistant bot via python craftassist_agent.py', 'review the CraftAssistAgent perceive method that runs low level, heuristic, and semantic segmentation perception modules', 'review the CraftAssistAgent init_perception method that sets up NLU, low level, heuristic, and dashboard perception modules', 'review the CraftAssistAgent init_controller method that initializes the dialogue manager with interpreter and memory handlers', 'review the CraftAssistAgent send_chat method that sends agent replies to the player and dashboard via socket events', 'run the CraftAssistSwarmMaster agent to orchestrate multiple Minecraft swarm workers via command line', 'initialize the CraftAssistSwarmMaster dialogue manager with bot capabilities, interpreter, and memory handlers', 'assign a named task with data to a specific swarm worker or execute it directly on the master', 'handle memory queries from swarm workers by routing them to the appropriate memory node handler', 'step through and assign new priority tasks to available swarm workers based on their tags', 'create a CraftAssistSwarmWorker agent with opts, index, and multiprocessing queues for task management', 'run a CraftAssistSwarmWorker_Wrapper process that perceives, handles input tasks, and steps through tasks in a loop', 'handle incoming Minecraft tasks like move, build, destroy, or dig from the input_tasks queue', 'handle master agent queries to stop or resume all running tasks in the swarm worker', 'step through all tasks in the task_stacks checking init, run, and stop conditions and returning queries']
```

Usage

```
{'run_craftassist_agent': 'run the CraftAssistAgent as a standalone Minecraft assistant bot via python craftassist_agent.py', 'review_CraftAssistAgent_perceive': 'review the CraftAssistAgent perceive method that runs low level, heuristic, and semantic segmentation perception modules', 'review_CraftAssistAgent_init_perception': 'review the CraftAssistAgent init_perception method that sets up NLU, low level, heuristic, and dashboard perception modules', 'review_CraftAssistAgent_init_controller': 'review the CraftAssistAgent init_controller method that initializes the dialogue manager with interpreter and memory handlers', 'review_CraftAssistAgent_send_chat': 'review the CraftAssistAgent send_chat method that sends agent replies to the player and dashboard via socket events'}
```

## File: facebookresearch_fairo/agents/craftassist/craftassist_swarm_master.py

Prompts

```
['run the CraftAssistAgent as a standalone Minecraft assistant bot via python craftassist_agent.py', 'review the CraftAssistAgent perceive method that runs low level, heuristic, and semantic segmentation perception modules', 'review the CraftAssistAgent init_perception method that sets up NLU, low level, heuristic, and dashboard perception modules', 'review the CraftAssistAgent init_controller method that initializes the dialogue manager with interpreter and memory handlers', 'review the CraftAssistAgent send_chat method that sends agent replies to the player and dashboard via socket events', 'run the CraftAssistSwarmMaster agent to orchestrate multiple Minecraft swarm workers via command line', 'initialize the CraftAssistSwarmMaster dialogue manager with bot capabilities, interpreter, and memory handlers', 'assign a named task with data to a specific swarm worker or execute it directly on the master', 'handle memory queries from swarm workers by routing them to the appropriate memory node handler', 'step through and assign new priority tasks to available swarm workers based on their tags', 'create a CraftAssistSwarmWorker agent with opts, index, and multiprocessing queues for task management', 'run a CraftAssistSwarmWorker_Wrapper process that perceives, handles input tasks, and steps through tasks in a loop', 'handle incoming Minecraft tasks like move, build, destroy, or dig from the input_tasks queue', 'handle master agent queries to stop or resume all running tasks in the swarm worker', 'step through all tasks in the task_stacks checking init, run, and stop conditions and returning queries']
```

Usage

```
{'run_craftassist_swarm_master': 'run the CraftAssistSwarmMaster agent to orchestrate multiple Minecraft swarm workers via command line', 'init_controller_swarm_master': 'initialize the CraftAssistSwarmMaster dialogue manager with bot capabilities, interpreter, and memory handlers', 'assign_task_to_worker': 'assign a named task with data to a specific swarm worker or execute it directly on the master', 'handle_memory_query': 'handle memory queries from swarm workers by routing them to the appropriate memory node handler', 'step_assign_new_tasks_to_workers': 'step through and assign new priority tasks to available swarm workers based on their tags'}
```

## File: facebookresearch_fairo/agents/craftassist/craftassist_swarm_worker.py

Prompts

```
['run the CraftAssistAgent as a standalone Minecraft assistant bot via python craftassist_agent.py', 'review the CraftAssistAgent perceive method that runs low level, heuristic, and semantic segmentation perception modules', 'review the CraftAssistAgent init_perception method that sets up NLU, low level, heuristic, and dashboard perception modules', 'review the CraftAssistAgent init_controller method that initializes the dialogue manager with interpreter and memory handlers', 'review the CraftAssistAgent send_chat method that sends agent replies to the player and dashboard via socket events', 'run the CraftAssistSwarmMaster agent to orchestrate multiple Minecraft swarm workers via command line', 'initialize the CraftAssistSwarmMaster dialogue manager with bot capabilities, interpreter, and memory handlers', 'assign a named task with data to a specific swarm worker or execute it directly on the master', 'handle memory queries from swarm workers by routing them to the appropriate memory node handler', 'step through and assign new priority tasks to available swarm workers based on their tags', 'create a CraftAssistSwarmWorker agent with opts, index, and multiprocessing queues for task management', 'run a CraftAssistSwarmWorker_Wrapper process that perceives, handles input tasks, and steps through tasks in a loop', 'handle incoming Minecraft tasks like move, build, destroy, or dig from the input_tasks queue', 'handle master agent queries to stop or resume all running tasks in the swarm worker', 'step through all tasks in the task_stacks checking init, run, and stop conditions and returning queries']
```

Usage

```
{'create_swarm_worker': 'create a CraftAssistSwarmWorker agent with opts, index, and multiprocessing queues for task management', 'run_swarm_worker_wrapper': 'run a CraftAssistSwarmWorker_Wrapper process that perceives, handles input tasks, and steps through tasks in a loop', 'handle_input_task': 'handle incoming Minecraft tasks like move, build, destroy, or dig from the input_tasks queue', 'handle_master_query': 'handle master agent queries to stop or resume all running tasks in the swarm worker', 'task_step': 'step through all tasks in the task_stacks checking init, run, and stop conditions and returning queries'}
```

