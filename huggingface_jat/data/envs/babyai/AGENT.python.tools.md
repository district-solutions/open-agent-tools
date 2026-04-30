# Agent Python Tools

- repo: huggingface/jat
- repo_uri: https://github.com/huggingface/jat

## File: huggingface_jat/data/envs/babyai/bot_agent.py

Prompts

```
['create a BabyAIBot instance with a BabyAI mission environment to solve tasks', 'run the BabyAIBot replan method to get the next suggested action for the mission', 'create a GoNextToSubgoal to navigate the agent to a target position or object', 'create an OpenSubgoal to open a door with optional key handling and drop logic', 'create an ExploreSubgoal to explore unseen areas and unopened doors in the environment', 'create a BabyAI dataset for a given task name and save it to disk and push to HuggingFace Hub', 'generate a single episode of text observations, discrete observations, actions, and rewards from a BabyAI gym environment', 'reset a BabyAI gym environment and initialize a BabyAIBot policy agent', 'call a function with a configurable timeout duration using SIGALRM signals', 'run the CLI to generate a BabyAI dataset by passing task name and max episodes as arguments', 'run generate_random_score to evaluate a random agent on a BabyAI Gymnasium environment for 1M timesteps', 'run the script with 32 parallel workers to generate random agent scores for all BabyAI tasks', 'review the generate_random_score function that collects episode rewards and saves mean and std to JSON', 'refactor generate_random_score to support a configurable number of timesteps instead of the hardcoded 1 million', 'summarize the TASK_NAME_TO_ENV_NAME mapping of 40 BabyAI task names to Gymnasium environment identifiers']
```

Usage

```
{'create_BabyAIBot': 'create a BabyAIBot instance with a BabyAI mission environment to solve tasks', 'run_BabyAIBot_replan': 'run the BabyAIBot replan method to get the next suggested action for the mission', 'create_GoNextToSubgoal': 'create a GoNextToSubgoal to navigate the agent to a target position or object', 'create_OpenSubgoal': 'create an OpenSubgoal to open a door with optional key handling and drop logic', 'create_ExploreSubgoal': 'create an ExploreSubgoal to explore unseen areas and unopened doors in the environment'}
```

## File: huggingface_jat/data/envs/babyai/create_babyai_dataset.py

Prompts

```
['create a BabyAIBot instance with a BabyAI mission environment to solve tasks', 'run the BabyAIBot replan method to get the next suggested action for the mission', 'create a GoNextToSubgoal to navigate the agent to a target position or object', 'create an OpenSubgoal to open a door with optional key handling and drop logic', 'create an ExploreSubgoal to explore unseen areas and unopened doors in the environment', 'create a BabyAI dataset for a given task name and save it to disk and push to HuggingFace Hub', 'generate a single episode of text observations, discrete observations, actions, and rewards from a BabyAI gym environment', 'reset a BabyAI gym environment and initialize a BabyAIBot policy agent', 'call a function with a configurable timeout duration using SIGALRM signals', 'run the CLI to generate a BabyAI dataset by passing task name and max episodes as arguments', 'run generate_random_score to evaluate a random agent on a BabyAI Gymnasium environment for 1M timesteps', 'run the script with 32 parallel workers to generate random agent scores for all BabyAI tasks', 'review the generate_random_score function that collects episode rewards and saves mean and std to JSON', 'refactor generate_random_score to support a configurable number of timesteps instead of the hardcoded 1 million', 'summarize the TASK_NAME_TO_ENV_NAME mapping of 40 BabyAI task names to Gymnasium environment identifiers']
```

Usage

```
{'create_babyai_dataset': 'create a BabyAI dataset for a given task name and save it to disk and push to HuggingFace Hub', 'generate_episode': 'generate a single episode of text observations, discrete observations, actions, and rewards from a BabyAI gym environment', 'reset_env_and_policy': 'reset a BabyAI gym environment and initialize a BabyAIBot policy agent', 'call_with_timeout': 'call a function with a configurable timeout duration using SIGALRM signals', 'run_babyai_dataset_cli': 'run the CLI to generate a BabyAI dataset by passing task name and max episodes as arguments'}
```

## File: huggingface_jat/data/envs/babyai/generate_random_score.py

Prompts

```
['create a BabyAIBot instance with a BabyAI mission environment to solve tasks', 'run the BabyAIBot replan method to get the next suggested action for the mission', 'create a GoNextToSubgoal to navigate the agent to a target position or object', 'create an OpenSubgoal to open a door with optional key handling and drop logic', 'create an ExploreSubgoal to explore unseen areas and unopened doors in the environment', 'create a BabyAI dataset for a given task name and save it to disk and push to HuggingFace Hub', 'generate a single episode of text observations, discrete observations, actions, and rewards from a BabyAI gym environment', 'reset a BabyAI gym environment and initialize a BabyAIBot policy agent', 'call a function with a configurable timeout duration using SIGALRM signals', 'run the CLI to generate a BabyAI dataset by passing task name and max episodes as arguments', 'run generate_random_score to evaluate a random agent on a BabyAI Gymnasium environment for 1M timesteps', 'run the script with 32 parallel workers to generate random agent scores for all BabyAI tasks', 'review the generate_random_score function that collects episode rewards and saves mean and std to JSON', 'refactor generate_random_score to support a configurable number of timesteps instead of the hardcoded 1 million', 'summarize the TASK_NAME_TO_ENV_NAME mapping of 40 BabyAI task names to Gymnasium environment identifiers']
```

Usage

```
{'run_generate_random_score': 'run generate_random_score to evaluate a random agent on a BabyAI Gymnasium environment for 1M timesteps', 'run_script_all_tasks': 'run the script with 32 parallel workers to generate random agent scores for all BabyAI tasks', 'review_generate_random_score': 'review the generate_random_score function that collects episode rewards and saves mean and std to JSON', 'refactor_generate_random_score': 'refactor generate_random_score to support a configurable number of timesteps instead of the hardcoded 1 million', 'summarize_TASK_NAME_TO_ENV_NAME': 'summarize the TASK_NAME_TO_ENV_NAME mapping of 40 BabyAI task names to Gymnasium environment identifiers'}
```

