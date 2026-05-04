# Agent Python Tools

- repo: google-deepmind/alohasim
- repo_uri: https://github.com/google-deepmind/aloha_sim

## File: google-deepmind_alohasim/aloha_sim/run_eval.py

Prompts

```
['run simulation evaluation episodes for ALOHA robotics tasks using Gemini Robotics policy and save videos', 'run a single robotics simulation episode with a given policy and save the resulting video', 'append a task instruction string to a dm_env timestep observation dictionary', 'create a GeminiRoboticsPolicy with synchronous inference mode and local robotics API connection', 'evaluate success rates across multiple ALOHA robotics tasks and episodes using the task suite', 'create an Aloha sim task environment by calling create_task_env with a task name and time limit', 'list all available task names by inspecting the TASK_FACTORIES dictionary keys', 'create a DrawerOpen task environment using create_task_env with task_name DrawerOpen and a time limit', 'create a BlocksSpelling task environment using create_task_env with task_name BlocksSpelling and a time limit', 'create a ToolsPlaceScrewdriverInLeftCompartment task environment using create_task_env with a task name and time limit', 'run the aloha sim viewer with a specified task and policy for interactive robot control', 'create a NoPolicy instance that returns a fixed initial action for 14 DOF robot joints', 'handle keyboard input in the viewer to pause, reset, single step, or change instructions', 'initialize a GeminiRoboticsPolicy with camera and proprioceptive observation keys for robot inference']
```

Usage

```
{'run_eval_episodes': 'run simulation evaluation episodes for ALOHA robotics tasks using Gemini Robotics policy and save videos', 'run_episode_function': 'run a single robotics simulation episode with a given policy and save the resulting video', 'append_task_instruction': 'append a task instruction string to a dm_env timestep observation dictionary', 'create_gemini_robotics_policy': 'create a GeminiRoboticsPolicy with synchronous inference mode and local robotics API connection', 'evaluate_task_success_rates': 'evaluate success rates across multiple ALOHA robotics tasks and episodes using the task suite'}
```

## File: google-deepmind_alohasim/aloha_sim/task_suite.py

Prompts

```
['run simulation evaluation episodes for ALOHA robotics tasks using Gemini Robotics policy and save videos', 'run a single robotics simulation episode with a given policy and save the resulting video', 'append a task instruction string to a dm_env timestep observation dictionary', 'create a GeminiRoboticsPolicy with synchronous inference mode and local robotics API connection', 'evaluate success rates across multiple ALOHA robotics tasks and episodes using the task suite', 'create an Aloha sim task environment by calling create_task_env with a task name and time limit', 'list all available task names by inspecting the TASK_FACTORIES dictionary keys', 'create a DrawerOpen task environment using create_task_env with task_name DrawerOpen and a time limit', 'create a BlocksSpelling task environment using create_task_env with task_name BlocksSpelling and a time limit', 'create a ToolsPlaceScrewdriverInLeftCompartment task environment using create_task_env with a task name and time limit', 'run the aloha sim viewer with a specified task and policy for interactive robot control', 'create a NoPolicy instance that returns a fixed initial action for 14 DOF robot joints', 'handle keyboard input in the viewer to pause, reset, single step, or change instructions', 'initialize a GeminiRoboticsPolicy with camera and proprioceptive observation keys for robot inference']
```

Usage

```
{'create_task_env': 'create an Aloha sim task environment by calling create_task_env with a task name and time limit', 'list_available_tasks': 'list all available task names by inspecting the TASK_FACTORIES dictionary keys', 'create_drawer_open_env': 'create a DrawerOpen task environment using create_task_env with task_name DrawerOpen and a time limit', 'create_blocks_spelling_env': 'create a BlocksSpelling task environment using create_task_env with task_name BlocksSpelling and a time limit', 'create_tools_caddy_env': 'create a ToolsPlaceScrewdriverInLeftCompartment task environment using create_task_env with a task name and time limit'}
```

## File: google-deepmind_alohasim/aloha_sim/viewer.py

Prompts

```
['run simulation evaluation episodes for ALOHA robotics tasks using Gemini Robotics policy and save videos', 'run a single robotics simulation episode with a given policy and save the resulting video', 'append a task instruction string to a dm_env timestep observation dictionary', 'create a GeminiRoboticsPolicy with synchronous inference mode and local robotics API connection', 'evaluate success rates across multiple ALOHA robotics tasks and episodes using the task suite', 'create an Aloha sim task environment by calling create_task_env with a task name and time limit', 'list all available task names by inspecting the TASK_FACTORIES dictionary keys', 'create a DrawerOpen task environment using create_task_env with task_name DrawerOpen and a time limit', 'create a BlocksSpelling task environment using create_task_env with task_name BlocksSpelling and a time limit', 'create a ToolsPlaceScrewdriverInLeftCompartment task environment using create_task_env with a task name and time limit', 'run the aloha sim viewer with a specified task and policy for interactive robot control', 'create a NoPolicy instance that returns a fixed initial action for 14 DOF robot joints', 'handle keyboard input in the viewer to pause, reset, single step, or change instructions', 'initialize a GeminiRoboticsPolicy with camera and proprioceptive observation keys for robot inference']
```

Usage

```
{'run_interactive_viewer': 'run the aloha sim viewer with a specified task and policy for interactive robot control', 'create_no_policy': 'create a NoPolicy instance that returns a fixed initial action for 14 DOF robot joints', 'handle_key_callback': 'handle keyboard input in the viewer to pause, reset, single step, or change instructions', 'append_task_instruction': 'append a task instruction string to a dm_env timestep observation dictionary', 'initialize_gemini_policy': 'initialize a GeminiRoboticsPolicy with camera and proprioceptive observation keys for robot inference'}
```

