# Agent Python Tools

- repo: facebookresearch/humenv
- repo_uri: https://github.com/facebookresearch/humenv

## File: facebookresearch_humenv/humenv/bench/goal_evaluation.py

Prompts

```
['run the GoalEvaluation class with an agent to evaluate performance across multiple goal poses', 'create a GoalEvaluation dataclass with goal poses, motion paths, and environment parameters for benchmarking', 'run goal inference on an agent by passing a goal pose through the GoalEvaluation run method', 'review the GoalEvaluation run method to understand how it iterates over goals and collects episode statistics', 'summarize the GoalEvaluation class which evaluates agents against target poses using rollout and metrics', 'run reward evaluation for an agent across multiple tasks using RewardEvaluation and collect metrics', 'create a RewardEvaluation dataclass with tasks, num_envs, vectorization_mode, and env_kwargs parameters', "evaluate an agent's reward_inference method across tasks by running rollouts in a Humenv environment", 'run a rollout in the Humenv environment with agent-derived context for reward evaluation', 'review the RewardEvaluation class and its run method for agent reward inference and metrics collection', 'run a TrackingEvaluation instance with an agent to evaluate motion tracking metrics across multiple motions', 'create a TrackingEvaluation dataclass with motion files, environment parameters, and optional multiprocessing workers', 'run the async tracking worker function to evaluate an agent on a batch of motion IDs', 'calculate distance proximity, EMD, and PHC metrics comparing agent observations against tracking targets', 'close a TrackingEvaluation instance to shut down the multiprocessing manager and free resources']
```

Usage

```
{'run_goal_evaluation': 'run the GoalEvaluation class with an agent to evaluate performance across multiple goal poses', 'create_goal_evaluation': 'create a GoalEvaluation dataclass with goal poses, motion paths, and environment parameters for benchmarking', 'run_goal_inference': 'run goal inference on an agent by passing a goal pose through the GoalEvaluation run method', 'review_goal_evaluation_run': 'review the GoalEvaluation run method to understand how it iterates over goals and collects episode statistics', 'summarize_goal_evaluation': 'summarize the GoalEvaluation class which evaluates agents against target poses using rollout and metrics'}
```

## File: facebookresearch_humenv/humenv/bench/reward_evaluation.py

Prompts

```
['run the GoalEvaluation class with an agent to evaluate performance across multiple goal poses', 'create a GoalEvaluation dataclass with goal poses, motion paths, and environment parameters for benchmarking', 'run goal inference on an agent by passing a goal pose through the GoalEvaluation run method', 'review the GoalEvaluation run method to understand how it iterates over goals and collects episode statistics', 'summarize the GoalEvaluation class which evaluates agents against target poses using rollout and metrics', 'run reward evaluation for an agent across multiple tasks using RewardEvaluation and collect metrics', 'create a RewardEvaluation dataclass with tasks, num_envs, vectorization_mode, and env_kwargs parameters', "evaluate an agent's reward_inference method across tasks by running rollouts in a Humenv environment", 'run a rollout in the Humenv environment with agent-derived context for reward evaluation', 'review the RewardEvaluation class and its run method for agent reward inference and metrics collection', 'run a TrackingEvaluation instance with an agent to evaluate motion tracking metrics across multiple motions', 'create a TrackingEvaluation dataclass with motion files, environment parameters, and optional multiprocessing workers', 'run the async tracking worker function to evaluate an agent on a batch of motion IDs', 'calculate distance proximity, EMD, and PHC metrics comparing agent observations against tracking targets', 'close a TrackingEvaluation instance to shut down the multiprocessing manager and free resources']
```

Usage

```
{'run_reward_evaluation': 'run reward evaluation for an agent across multiple tasks using RewardEvaluation and collect metrics', 'create_reward_evaluation_config': 'create a RewardEvaluation dataclass with tasks, num_envs, vectorization_mode, and env_kwargs parameters', 'evaluate_agent_reward_inference': "evaluate an agent's reward_inference method across tasks by running rollouts in a Humenv environment", 'run_rollout_with_context': 'run a rollout in the Humenv environment with agent-derived context for reward evaluation', 'review_reward_evaluation_class': 'review the RewardEvaluation class and its run method for agent reward inference and metrics collection'}
```

## File: facebookresearch_humenv/humenv/bench/tracking_evaluation.py

Prompts

```
['run the GoalEvaluation class with an agent to evaluate performance across multiple goal poses', 'create a GoalEvaluation dataclass with goal poses, motion paths, and environment parameters for benchmarking', 'run goal inference on an agent by passing a goal pose through the GoalEvaluation run method', 'review the GoalEvaluation run method to understand how it iterates over goals and collects episode statistics', 'summarize the GoalEvaluation class which evaluates agents against target poses using rollout and metrics', 'run reward evaluation for an agent across multiple tasks using RewardEvaluation and collect metrics', 'create a RewardEvaluation dataclass with tasks, num_envs, vectorization_mode, and env_kwargs parameters', "evaluate an agent's reward_inference method across tasks by running rollouts in a Humenv environment", 'run a rollout in the Humenv environment with agent-derived context for reward evaluation', 'review the RewardEvaluation class and its run method for agent reward inference and metrics collection', 'run a TrackingEvaluation instance with an agent to evaluate motion tracking metrics across multiple motions', 'create a TrackingEvaluation dataclass with motion files, environment parameters, and optional multiprocessing workers', 'run the async tracking worker function to evaluate an agent on a batch of motion IDs', 'calculate distance proximity, EMD, and PHC metrics comparing agent observations against tracking targets', 'close a TrackingEvaluation instance to shut down the multiprocessing manager and free resources']
```

Usage

```
{'run_tracking_evaluation': 'run a TrackingEvaluation instance with an agent to evaluate motion tracking metrics across multiple motions', 'create_tracking_evaluation': 'create a TrackingEvaluation dataclass with motion files, environment parameters, and optional multiprocessing workers', 'run_async_tracking_worker': 'run the async tracking worker function to evaluate an agent on a batch of motion IDs', 'calc_metrics': 'calculate distance proximity, EMD, and PHC metrics comparing agent observations against tracking targets', 'close_tracking_evaluation': 'close a TrackingEvaluation instance to shut down the multiprocessing manager and free resources'}
```

