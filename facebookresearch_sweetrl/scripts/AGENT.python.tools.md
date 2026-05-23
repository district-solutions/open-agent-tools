# Agent Python Tools

- repo: facebookresearch/sweetrl
- repo_uri: https://github.com/facebookresearch/sweet_rl

## File: facebookresearch_sweetrl/scripts/generate_random_pairs_from_ranks.py

Prompts

```
['run the script to generate preference pairs from judge results and write them to a JSONL output file', 'run the script with get_sft flag to generate SFT-style preference pairs from random output sampling', 'run the script with no_prompt flag to generate preference pairs without separate prompt fields', 'extract chosen and rejected indices by randomly sampling from the best and worst halves of judge results', 'extract the best and worst indices from judge results by selecting the top and bottom ranked outputs', 'run the script to rank best of N LLM outputs using a judge model and logprobs', 'run main with a custom model_id to judge and rerank dialogue outputs from a JSONL file', 'run main with no_use_ground_truth to rank outputs without referencing the ground truth answer', 'run main with use_sum to use summed logprobs instead of averaged logprobs for judging', 'run formatting_func to build a reward model prompt from input and output dialogue text', 'run the main function to simulate LLM agent interactions with human simulator environments in batch', 'run batch interactions between an agent and multiple environments for a list of tasks', 'simulate code collaboration tasks using a VLLMAgent and HumanInteractionEnv with configurable batch size', 'simulate HTML design collaboration tasks using a VLLMAgent and HumanDesignInteractionEnv with browser drivers', 'continue a previous interaction trajectory from an output JSONL file using the to_continue flag']
```

Usage

```
{'run_main_generate_pairs': 'run the script to generate preference pairs from judge results and write them to a JSONL output file', 'run_main_generate_sft_pairs': 'run the script with get_sft flag to generate SFT-style preference pairs from random output sampling', 'run_main_generate_no_prompt_pairs': 'run the script with no_prompt flag to generate preference pairs without separate prompt fields', 'extract_indices': 'extract chosen and rejected indices by randomly sampling from the best and worst halves of judge results', 'extract_indices_bestworst': 'extract the best and worst indices from judge results by selecting the top and bottom ranked outputs'}
```

## File: facebookresearch_sweetrl/scripts/rank_best_of_n.py

Prompts

```
['run the script to generate preference pairs from judge results and write them to a JSONL output file', 'run the script with get_sft flag to generate SFT-style preference pairs from random output sampling', 'run the script with no_prompt flag to generate preference pairs without separate prompt fields', 'extract chosen and rejected indices by randomly sampling from the best and worst halves of judge results', 'extract the best and worst indices from judge results by selecting the top and bottom ranked outputs', 'run the script to rank best of N LLM outputs using a judge model and logprobs', 'run main with a custom model_id to judge and rerank dialogue outputs from a JSONL file', 'run main with no_use_ground_truth to rank outputs without referencing the ground truth answer', 'run main with use_sum to use summed logprobs instead of averaged logprobs for judging', 'run formatting_func to build a reward model prompt from input and output dialogue text', 'run the main function to simulate LLM agent interactions with human simulator environments in batch', 'run batch interactions between an agent and multiple environments for a list of tasks', 'simulate code collaboration tasks using a VLLMAgent and HumanInteractionEnv with configurable batch size', 'simulate HTML design collaboration tasks using a VLLMAgent and HumanDesignInteractionEnv with browser drivers', 'continue a previous interaction trajectory from an output JSONL file using the to_continue flag']
```

Usage

```
{'run_rank_best_of_n': 'run the script to rank best of N LLM outputs using a judge model and logprobs', 'run_main_with_model': 'run main with a custom model_id to judge and rerank dialogue outputs from a JSONL file', 'run_main_no_ground_truth': 'run main with no_use_ground_truth to rank outputs without referencing the ground truth answer', 'run_main_use_sum': 'run main with use_sum to use summed logprobs instead of averaged logprobs for judging', 'run_formatting_func': 'run formatting_func to build a reward model prompt from input and output dialogue text'}
```

## File: facebookresearch_sweetrl/scripts/simulate_interactions.py

Prompts

```
['run the script to generate preference pairs from judge results and write them to a JSONL output file', 'run the script with get_sft flag to generate SFT-style preference pairs from random output sampling', 'run the script with no_prompt flag to generate preference pairs without separate prompt fields', 'extract chosen and rejected indices by randomly sampling from the best and worst halves of judge results', 'extract the best and worst indices from judge results by selecting the top and bottom ranked outputs', 'run the script to rank best of N LLM outputs using a judge model and logprobs', 'run main with a custom model_id to judge and rerank dialogue outputs from a JSONL file', 'run main with no_use_ground_truth to rank outputs without referencing the ground truth answer', 'run main with use_sum to use summed logprobs instead of averaged logprobs for judging', 'run formatting_func to build a reward model prompt from input and output dialogue text', 'run the main function to simulate LLM agent interactions with human simulator environments in batch', 'run batch interactions between an agent and multiple environments for a list of tasks', 'simulate code collaboration tasks using a VLLMAgent and HumanInteractionEnv with configurable batch size', 'simulate HTML design collaboration tasks using a VLLMAgent and HumanDesignInteractionEnv with browser drivers', 'continue a previous interaction trajectory from an output JSONL file using the to_continue flag']
```

Usage

```
{'run_simulate_interactions': 'run the main function to simulate LLM agent interactions with human simulator environments in batch', 'run_batch_interact_environment': 'run batch interactions between an agent and multiple environments for a list of tasks', 'simulate_code_collaboration': 'simulate code collaboration tasks using a VLLMAgent and HumanInteractionEnv with configurable batch size', 'simulate_html_collaboration': 'simulate HTML design collaboration tasks using a VLLMAgent and HumanDesignInteractionEnv with browser drivers', 'continue_trajectory_from_file': 'continue a previous interaction trajectory from an output JSONL file using the to_continue flag'}
```

