# Agent Python Tools

- repo: facebookresearch/collaborative-reasoner
- repo_uri: https://github.com/facebookresearch/collaborative-reasoner

## File: facebookresearch_collaborative-reasoner/finetuning/data_creation/filtering_utils.py

Prompts

```
['create a training instance from a specific conversation turn using a tokenizer and chat template', 'generate preference pairs from conversation turns with optional agreement or length discouragement scoring', 'load and aggregate rank-sharded JSONL result files from a results directory with optional matrix sorting', 'compute the average accuracy metric across all conversation results in an example dictionary', 'group rank-sharded results by initial prompt and combine into structured conversation result examples', 'run correctness filtering on sampling results directories to filter training data by correctness metrics', 'run correctness filtering with preference pair generation from conversation turns using a tokenizer', 'run correctness filtering with turn-level filtering to extract correct turns with previous context', 'submit a SLURM job to run correctness filtering on sampling results with configurable parameters', 'run correctness filtering keeping only successful conversations with perfect accuracy metrics']
```

Usage

```
{'get_single_turn_instance': 'create a training instance from a specific conversation turn using a tokenizer and chat template', 'get_preference_pairs_from_turn': 'generate preference pairs from conversation turns with optional agreement or length discouragement scoring', 'get_all_rank_results': 'load and aggregate rank-sharded JSONL result files from a results directory with optional matrix sorting', 'get_acc_at_k': 'compute the average accuracy metric across all conversation results in an example dictionary', 'sort_matrix_results': 'group rank-sharded results by initial prompt and combine into structured conversation result examples'}
```

## File: facebookresearch_collaborative-reasoner/finetuning/data_creation/ts_correctness_filtering.py

Prompts

```
['create a training instance from a specific conversation turn using a tokenizer and chat template', 'generate preference pairs from conversation turns with optional agreement or length discouragement scoring', 'load and aggregate rank-sharded JSONL result files from a results directory with optional matrix sorting', 'compute the average accuracy metric across all conversation results in an example dictionary', 'group rank-sharded results by initial prompt and combine into structured conversation result examples', 'run correctness filtering on sampling results directories to filter training data by correctness metrics', 'run correctness filtering with preference pair generation from conversation turns using a tokenizer', 'run correctness filtering with turn-level filtering to extract correct turns with previous context', 'submit a SLURM job to run correctness filtering on sampling results with configurable parameters', 'run correctness filtering keeping only successful conversations with perfect accuracy metrics']
```

Usage

```
{'run_correctness_filtering': 'run correctness filtering on sampling results directories to filter training data by correctness metrics', 'run_preference_pair_generation': 'run correctness filtering with preference pair generation from conversation turns using a tokenizer', 'run_turn_level_filtering': 'run correctness filtering with turn-level filtering to extract correct turns with previous context', 'submit_filtering_job': 'submit a SLURM job to run correctness filtering on sampling results with configurable parameters', 'run_success_conv_filtering': 'run correctness filtering keeping only successful conversations with perfect accuracy metrics'}
```

