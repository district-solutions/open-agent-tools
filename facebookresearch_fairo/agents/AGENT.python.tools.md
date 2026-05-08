# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/agents/argument_parser.py

Prompts

```
['create an ArgumentParser instance for a Minecraft agent with base path and parse CLI args', 'create an ArgumentParser instance for a Locobot agent with base path and parse CLI args', 'parse Neural Semantic Parser arguments including model paths, data directories, and ground truth settings', 'fix path arguments by resolving relative paths to absolute paths using the base path', 'add Minecraft-specific arguments like backend type, port, semantic segmentation model path, and map update ticks', 'create a subclass of BaseAgent that implements perceive, controller_step, task_step, and handle_exception methods', 'run the BaseAgent start method to begin the perpetual step loop until shutdown', 'implement the perceive method to gather world information and store it in agent memory', 'implement the controller_step method to interpret commands and place tasks on the task stack', 'implement the task_step method to execute the topmost task and interact with the world', 'create a DroidletAgent instance with opts and optional name for a scripted interpreter agent', 'initialize SocketIO event handlers for dashboard communication, command saving, and agent termination', 'run the language understanding perception module to process incoming chats and semantic parsing', 'step the dialogue manager to process incoming chats and modify the task stack', 'execute priority-ordered tasks from memory that meet their init conditions and are not paused']
```

Usage

```
{'create_argument_parser_for_minecraft_agent': 'create an ArgumentParser instance for a Minecraft agent with base path and parse CLI args', 'create_argument_parser_for_locobot_agent': 'create an ArgumentParser instance for a Locobot agent with base path and parse CLI args', 'parse_nsp_args': 'parse Neural Semantic Parser arguments including model paths, data directories, and ground truth settings', 'fix_path_on_parsed_opts': 'fix path arguments by resolving relative paths to absolute paths using the base path', 'add_minecraft_specific_args': 'add Minecraft-specific arguments like backend type, port, semantic segmentation model path, and map update ticks'}
```

## File: facebookresearch_fairo/agents/core.py

Prompts

```
['create an ArgumentParser instance for a Minecraft agent with base path and parse CLI args', 'create an ArgumentParser instance for a Locobot agent with base path and parse CLI args', 'parse Neural Semantic Parser arguments including model paths, data directories, and ground truth settings', 'fix path arguments by resolving relative paths to absolute paths using the base path', 'add Minecraft-specific arguments like backend type, port, semantic segmentation model path, and map update ticks', 'create a subclass of BaseAgent that implements perceive, controller_step, task_step, and handle_exception methods', 'run the BaseAgent start method to begin the perpetual step loop until shutdown', 'implement the perceive method to gather world information and store it in agent memory', 'implement the controller_step method to interpret commands and place tasks on the task stack', 'implement the task_step method to execute the topmost task and interact with the world', 'create a DroidletAgent instance with opts and optional name for a scripted interpreter agent', 'initialize SocketIO event handlers for dashboard communication, command saving, and agent termination', 'run the language understanding perception module to process incoming chats and semantic parsing', 'step the dialogue manager to process incoming chats and modify the task stack', 'execute priority-ordered tasks from memory that meet their init conditions and are not paused']
```

Usage

```
{'create_agent_subclass': 'create a subclass of BaseAgent that implements perceive, controller_step, task_step, and handle_exception methods', 'run_agent_loop': 'run the BaseAgent start method to begin the perpetual step loop until shutdown', 'implement_perceive_method': 'implement the perceive method to gather world information and store it in agent memory', 'implement_controller_step': 'implement the controller_step method to interpret commands and place tasks on the task stack', 'implement_task_step': 'implement the task_step method to execute the topmost task and interact with the world'}
```

## File: facebookresearch_fairo/agents/droidlet_agent.py

Prompts

```
['create an ArgumentParser instance for a Minecraft agent with base path and parse CLI args', 'create an ArgumentParser instance for a Locobot agent with base path and parse CLI args', 'parse Neural Semantic Parser arguments including model paths, data directories, and ground truth settings', 'fix path arguments by resolving relative paths to absolute paths using the base path', 'add Minecraft-specific arguments like backend type, port, semantic segmentation model path, and map update ticks', 'create a subclass of BaseAgent that implements perceive, controller_step, task_step, and handle_exception methods', 'run the BaseAgent start method to begin the perpetual step loop until shutdown', 'implement the perceive method to gather world information and store it in agent memory', 'implement the controller_step method to interpret commands and place tasks on the task stack', 'implement the task_step method to execute the topmost task and interact with the world', 'create a DroidletAgent instance with opts and optional name for a scripted interpreter agent', 'initialize SocketIO event handlers for dashboard communication, command saving, and agent termination', 'run the language understanding perception module to process incoming chats and semantic parsing', 'step the dialogue manager to process incoming chats and modify the task stack', 'execute priority-ordered tasks from memory that meet their init conditions and are not paused']
```

Usage

```
{'create_DroidletAgent': 'create a DroidletAgent instance with opts and optional name for a scripted interpreter agent', 'init_event_handlers_DroidletAgent': 'initialize SocketIO event handlers for dashboard communication, command saving, and agent termination', 'perceive_DroidletAgent': 'run the language understanding perception module to process incoming chats and semantic parsing', 'controller_step_DroidletAgent': 'step the dialogue manager to process incoming chats and modify the task stack', 'task_step_DroidletAgent': 'execute priority-ordered tasks from memory that meet their init conditions and are not paused'}
```

