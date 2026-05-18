# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/blotto/evaluate.py

Prompts

```
['run a Monte-Carlo simulation to compute mean score estimates for two Blotto game strategies', 'run an iterated Colonel Blotto game for a given number of rounds with strategy functions', 'calculate payoffs for two strategies by comparing soldier allocations across battlefields', 'compute final average scores for both players from a list of game history rounds', 'validate a Blotto strategy to ensure non-negative integers and a total of at most 120 soldiers', 'run the row_strategy function to generate a random soldier allocation for 6 battlefields', 'test the row_strategy function to verify it returns exactly 120 total soldiers across 6 battlefields', 'refactor the row_strategy function to accept configurable total soldiers and battlefield count parameters', 'review the row_strategy function for edge cases where all soldiers are allocated to prioritized battlefields', 'summarize the row_strategy function which generates randomized Colonel Blotto game allocations with prioritized battlefields', 'run target_column_strategy to generate a random soldier allocation across 6 battlefields totaling 120', 'test target_column_strategy returns a list of 6 integers that sum to exactly 120', 'review target_column_strategy normalization logic to ensure rounding errors are corrected', 'refactor target_column_strategy to accept configurable total_soldiers and num_battlefields parameters', 'summarize target_column_strategy which generates a randomized Blotto game column player allocation strategy']
```

Usage

```
{'run_simulation_mean_scores': 'run a Monte-Carlo simulation to compute mean score estimates for two Blotto game strategies', 'run_iterated_game': 'run an iterated Colonel Blotto game for a given number of rounds with strategy functions', 'calculate_payoffs': 'calculate payoffs for two strategies by comparing soldier allocations across battlefields', 'compute_overall_scores': 'compute final average scores for both players from a list of game history rounds', 'validate_strategy': 'validate a Blotto strategy to ensure non-negative integers and a total of at most 120 soldiers'}
```

## File: facebookresearch_mlgym/data/blotto/strategy.py

Prompts

```
['run a Monte-Carlo simulation to compute mean score estimates for two Blotto game strategies', 'run an iterated Colonel Blotto game for a given number of rounds with strategy functions', 'calculate payoffs for two strategies by comparing soldier allocations across battlefields', 'compute final average scores for both players from a list of game history rounds', 'validate a Blotto strategy to ensure non-negative integers and a total of at most 120 soldiers', 'run the row_strategy function to generate a random soldier allocation for 6 battlefields', 'test the row_strategy function to verify it returns exactly 120 total soldiers across 6 battlefields', 'refactor the row_strategy function to accept configurable total soldiers and battlefield count parameters', 'review the row_strategy function for edge cases where all soldiers are allocated to prioritized battlefields', 'summarize the row_strategy function which generates randomized Colonel Blotto game allocations with prioritized battlefields', 'run target_column_strategy to generate a random soldier allocation across 6 battlefields totaling 120', 'test target_column_strategy returns a list of 6 integers that sum to exactly 120', 'review target_column_strategy normalization logic to ensure rounding errors are corrected', 'refactor target_column_strategy to accept configurable total_soldiers and num_battlefields parameters', 'summarize target_column_strategy which generates a randomized Blotto game column player allocation strategy']
```

Usage

```
{'run_row_strategy': 'run the row_strategy function to generate a random soldier allocation for 6 battlefields', 'test_row_strategy': 'test the row_strategy function to verify it returns exactly 120 total soldiers across 6 battlefields', 'refactor_row_strategy': 'refactor the row_strategy function to accept configurable total soldiers and battlefield count parameters', 'review_row_strategy': 'review the row_strategy function for edge cases where all soldiers are allocated to prioritized battlefields', 'summarize_row_strategy': 'summarize the row_strategy function which generates randomized Colonel Blotto game allocations with prioritized battlefields'}
```

## File: facebookresearch_mlgym/data/blotto/target.py

Prompts

```
['run a Monte-Carlo simulation to compute mean score estimates for two Blotto game strategies', 'run an iterated Colonel Blotto game for a given number of rounds with strategy functions', 'calculate payoffs for two strategies by comparing soldier allocations across battlefields', 'compute final average scores for both players from a list of game history rounds', 'validate a Blotto strategy to ensure non-negative integers and a total of at most 120 soldiers', 'run the row_strategy function to generate a random soldier allocation for 6 battlefields', 'test the row_strategy function to verify it returns exactly 120 total soldiers across 6 battlefields', 'refactor the row_strategy function to accept configurable total soldiers and battlefield count parameters', 'review the row_strategy function for edge cases where all soldiers are allocated to prioritized battlefields', 'summarize the row_strategy function which generates randomized Colonel Blotto game allocations with prioritized battlefields', 'run target_column_strategy to generate a random soldier allocation across 6 battlefields totaling 120', 'test target_column_strategy returns a list of 6 integers that sum to exactly 120', 'review target_column_strategy normalization logic to ensure rounding errors are corrected', 'refactor target_column_strategy to accept configurable total_soldiers and num_battlefields parameters', 'summarize target_column_strategy which generates a randomized Blotto game column player allocation strategy']
```

Usage

```
{'run_target_column_strategy': 'run target_column_strategy to generate a random soldier allocation across 6 battlefields totaling 120', 'test_target_column_strategy': 'test target_column_strategy returns a list of 6 integers that sum to exactly 120', 'review_target_column_strategy': 'review target_column_strategy normalization logic to ensure rounding errors are corrected', 'refactor_target_column_strategy': 'refactor target_column_strategy to accept configurable total_soldiers and num_battlefields parameters', 'summarize_target_column_strategy': 'summarize target_column_strategy which generates a randomized Blotto game column player allocation strategy'}
```

