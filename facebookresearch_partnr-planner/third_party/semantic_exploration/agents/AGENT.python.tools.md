# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/semantic_exploration/agents/sem_exp.py

Prompts

```
['create a Sem_Exp_Env_Agent instance with a config to initialize semantic prediction and planning', 'reset the Sem_Exp_Env_Agent for a new episode with a goal name and observation size', 'run the agent planning loop to compute actions from map predictions and pose data', 'get a short-term goal using FMM planner with obstacle dilation and collision avoidance', 'preprocess RGB-D observations with semantic segmentation prediction for the agent state']
```

Usage

```
{'init_sem_exp_agent': 'create a Sem_Exp_Env_Agent instance with a config to initialize semantic prediction and planning', 'reset_agent_episode': 'reset the Sem_Exp_Env_Agent for a new episode with a goal name and observation size', 'plan_act_and_preprocess': 'run the agent planning loop to compute actions from map predictions and pose data', 'get_short_term_goal': 'get a short-term goal using FMM planner with obstacle dilation and collision avoidance', 'preprocess_observations': 'preprocess RGB-D observations with semantic segmentation prediction for the agent state'}
```

