# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_cl/scenarios/brax/ant.py

Prompts

```
['build a Brax Ant environment with a specified task variant like moon gravity or disabled feet', 'create an observation vector from the ant body position, orientation, and joint velocities', 'run one timestep of the ant environment dynamics and compute forward and health rewards', 'refactor the Ant constructor to support custom environment task specs for gravity, friction, or body mass', 'review the env_tasks dictionary to understand predefined task variants like hugefoot, rainfall, and inverted actions', 'create a Halfcheetah Brax environment with a specified task like moon or rainfall', 'reset the Halfcheetah environment to an initial state with noisy joint positions', 'run one timestep of Halfcheetah dynamics and compute forward reward minus control cost', 'get the observation vector from joint angles and velocities with an applied obs_mask', 'get the full history of joint positions recorded during a Halfcheetah episode']
```

Usage

```
{'build_ant_env': 'build a Brax Ant environment with a specified task variant like moon gravity or disabled feet', 'create_ant_observation': 'create an observation vector from the ant body position, orientation, and joint velocities', 'run_ant_step': 'run one timestep of the ant environment dynamics and compute forward and health rewards', 'refactor_ant_init': 'refactor the Ant constructor to support custom environment task specs for gravity, friction, or body mass', 'review_env_tasks': 'review the env_tasks dictionary to understand predefined task variants like hugefoot, rainfall, and inverted actions'}
```

## File: facebookresearch_salina/salina_cl/scenarios/brax/halfcheetah.py

Prompts

```
['build a Brax Ant environment with a specified task variant like moon gravity or disabled feet', 'create an observation vector from the ant body position, orientation, and joint velocities', 'run one timestep of the ant environment dynamics and compute forward and health rewards', 'refactor the Ant constructor to support custom environment task specs for gravity, friction, or body mass', 'review the env_tasks dictionary to understand predefined task variants like hugefoot, rainfall, and inverted actions', 'create a Halfcheetah Brax environment with a specified task like moon or rainfall', 'reset the Halfcheetah environment to an initial state with noisy joint positions', 'run one timestep of Halfcheetah dynamics and compute forward reward minus control cost', 'get the observation vector from joint angles and velocities with an applied obs_mask', 'get the full history of joint positions recorded during a Halfcheetah episode']
```

Usage

```
{'create_halfcheetah_env': 'create a Halfcheetah Brax environment with a specified task like moon or rainfall', 'reset_halfcheetah_state': 'reset the Halfcheetah environment to an initial state with noisy joint positions', 'step_halfcheetah_dynamics': 'run one timestep of Halfcheetah dynamics and compute forward reward minus control cost', 'get_observation_mask': 'get the observation vector from joint angles and velocities with an applied obs_mask', 'get_qps_history': 'get the full history of joint positions recorded during a Halfcheetah episode'}
```

