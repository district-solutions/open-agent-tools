# Agent Python Tools

- repo: huggingface/jat
- repo_uri: https://github.com/huggingface/jat

## File: huggingface_jat/data/envs/atari/create_atari_dataset.py

Prompts

```
['create an Atari dataset by running a trained actor-critic policy and collecting episodes', 'push a local dataset folder to a Hugging Face Hub repository', 'run the script to generate an Atari dataset from a trained RL checkpoint', 'create a public Hugging Face dataset repository using the HfApi', 'upload a Hugging Face Dataset to a specific branch and config name on the Hub', 'run the script to generate random agent baseline scores for all Atari tasks using multiprocessing', 'run generate_random_score for a single Atari task to collect 100 episode random rewards', 'review the generate_random_score function that runs random actions in Atari envs and saves mean and std rewards', 'refactor generate_random_score to support a configurable number of episodes instead of the hardcoded 100', 'summarize the TASK_NAMES list containing 58 Atari game identifiers used for random score generation']
```

Usage

```
{'create_atari_dataset': 'create an Atari dataset by running a trained actor-critic policy and collecting episodes', 'push_to_hf': 'push a local dataset folder to a Hugging Face Hub repository', 'run_atari_dataset_script': 'run the script to generate an Atari dataset from a trained RL checkpoint', 'create_hf_repo': 'create a public Hugging Face dataset repository using the HfApi', 'upload_dataset_to_hub': 'upload a Hugging Face Dataset to a specific branch and config name on the Hub'}
```

## File: huggingface_jat/data/envs/atari/generate_random_score.py

Prompts

```
['create an Atari dataset by running a trained actor-critic policy and collecting episodes', 'push a local dataset folder to a Hugging Face Hub repository', 'run the script to generate an Atari dataset from a trained RL checkpoint', 'create a public Hugging Face dataset repository using the HfApi', 'upload a Hugging Face Dataset to a specific branch and config name on the Hub', 'run the script to generate random agent baseline scores for all Atari tasks using multiprocessing', 'run generate_random_score for a single Atari task to collect 100 episode random rewards', 'review the generate_random_score function that runs random actions in Atari envs and saves mean and std rewards', 'refactor generate_random_score to support a configurable number of episodes instead of the hardcoded 100', 'summarize the TASK_NAMES list containing 58 Atari game identifiers used for random score generation']
```

Usage

```
{'run_generate_random_score': 'run the script to generate random agent baseline scores for all Atari tasks using multiprocessing', 'run_generate_random_score_single_task': 'run generate_random_score for a single Atari task to collect 100 episode random rewards', 'review_generate_random_score': 'review the generate_random_score function that runs random actions in Atari envs and saves mean and std rewards', 'refactor_generate_random_score': 'refactor generate_random_score to support a configurable number of episodes instead of the hardcoded 100', 'summarize_TASK_NAMES': 'summarize the TASK_NAMES list containing 58 Atari game identifiers used for random score generation'}
```

