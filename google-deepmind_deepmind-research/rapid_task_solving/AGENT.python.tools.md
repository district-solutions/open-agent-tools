# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/rapid_task_solving/memory_planning_game.py

Prompts

```
['create a MemoryPlanningGame environment with a configurable maze size and reward settings', 'reset the MemoryPlanningGame environment to start a new episode with randomized node labels', 'step the agent by taking an Up, Down, Left, Right, or Collect action in the maze', 'run a random agent by calling take_random_action to sample actions from the environment', 'draw and visualize the maze grid showing agent position, goal, and episode reward', 'create a OneShotStreetLearn environment from a GEXF graph dataset with configurable max steps and junctions', 'run a StreetLearn episode by calling step with Forward, Left, Right, or Collect actions', 'draw the current subgraph with agent position and goal markers using matplotlib', 'reset the OneShotStreetLearn environment to generate a new random subgraph and starting position', 'extract a random subgraph with a target number of junctions from the full road network graph']
```

Usage

```
{'create_memory_planning_game_env': 'create a MemoryPlanningGame environment with a configurable maze size and reward settings', 'reset_episode': 'reset the MemoryPlanningGame environment to start a new episode with randomized node labels', 'step_agent_action': 'step the agent by taking an Up, Down, Left, Right, or Collect action in the maze', 'run_random_agent': 'run a random agent by calling take_random_action to sample actions from the environment', 'visualize_maze': 'draw and visualize the maze grid showing agent position, goal, and episode reward'}
```

## File: google-deepmind_deepmind-research/rapid_task_solving/one_shot_streetlearn.py

Prompts

```
['create a MemoryPlanningGame environment with a configurable maze size and reward settings', 'reset the MemoryPlanningGame environment to start a new episode with randomized node labels', 'step the agent by taking an Up, Down, Left, Right, or Collect action in the maze', 'run a random agent by calling take_random_action to sample actions from the environment', 'draw and visualize the maze grid showing agent position, goal, and episode reward', 'create a OneShotStreetLearn environment from a GEXF graph dataset with configurable max steps and junctions', 'run a StreetLearn episode by calling step with Forward, Left, Right, or Collect actions', 'draw the current subgraph with agent position and goal markers using matplotlib', 'reset the OneShotStreetLearn environment to generate a new random subgraph and starting position', 'extract a random subgraph with a target number of junctions from the full road network graph']
```

Usage

```
{'create_oneshotstreetlearn_env': 'create a OneShotStreetLearn environment from a GEXF graph dataset with configurable max steps and junctions', 'run_streetlearn_episode': 'run a StreetLearn episode by calling step with Forward, Left, Right, or Collect actions', 'draw_streetlearn_subgraph': 'draw the current subgraph with agent position and goal markers using matplotlib', 'reset_streetlearn_env': 'reset the OneShotStreetLearn environment to generate a new random subgraph and starting position', 'get_random_subgraph': 'extract a random subgraph with a target number of junctions from the full road network graph'}
```

