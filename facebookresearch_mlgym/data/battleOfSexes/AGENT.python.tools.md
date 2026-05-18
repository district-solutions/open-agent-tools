# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/battleOfSexes/evaluate.py

Prompts

```
['run a Monte-Carlo simulation to compute mean score estimates for both players over multiple rounds', 'run an iterated game contest for a given number of rounds with specified strategy functions', 'compute final average scores for both row and column players from game history', 'get the payoff tuple for a given row and column strategy from a payoff matrix', 'get the Battle of the Sexes game payoff matrix with row and column player rewards', 'run the row_strategy function with a list of previous turn tuples to get the next move', 'test the row_strategy function with empty history to verify it returns default strategy 0', 'refactor the row_strategy function to use a different probabilistic decision-making approach', 'review the row_strategy function logic for the Battle of the Sexes game strategy selection', 'summarize the row_strategy function that selects moves based on game history and random probability', 'run target_column_strategy with a list of (row, col) tuples to get the next column player strategy', 'test target_column_strategy with an empty history list to verify it returns 1', 'test target_column_strategy with a history containing row strategy 1 to check probabilistic return', 'review target_column_strategy to understand the 80/20 probabilistic decision logic for column player moves', 'refactor target_column_strategy to replace the loop-based logic with a direct lookup on the last history entry']
```

Usage

```
{'run_simulation_mean_scores': 'run a Monte-Carlo simulation to compute mean score estimates for both players over multiple rounds', 'run_iterated_game': 'run an iterated game contest for a given number of rounds with specified strategy functions', 'compute_overall_scores': 'compute final average scores for both row and column players from game history', 'get_game_payoffs': 'get the payoff tuple for a given row and column strategy from a payoff matrix', 'get_bos_payoff_matrix': 'get the Battle of the Sexes game payoff matrix with row and column player rewards'}
```

## File: facebookresearch_mlgym/data/battleOfSexes/strategy.py

Prompts

```
['run a Monte-Carlo simulation to compute mean score estimates for both players over multiple rounds', 'run an iterated game contest for a given number of rounds with specified strategy functions', 'compute final average scores for both row and column players from game history', 'get the payoff tuple for a given row and column strategy from a payoff matrix', 'get the Battle of the Sexes game payoff matrix with row and column player rewards', 'run the row_strategy function with a list of previous turn tuples to get the next move', 'test the row_strategy function with empty history to verify it returns default strategy 0', 'refactor the row_strategy function to use a different probabilistic decision-making approach', 'review the row_strategy function logic for the Battle of the Sexes game strategy selection', 'summarize the row_strategy function that selects moves based on game history and random probability', 'run target_column_strategy with a list of (row, col) tuples to get the next column player strategy', 'test target_column_strategy with an empty history list to verify it returns 1', 'test target_column_strategy with a history containing row strategy 1 to check probabilistic return', 'review target_column_strategy to understand the 80/20 probabilistic decision logic for column player moves', 'refactor target_column_strategy to replace the loop-based logic with a direct lookup on the last history entry']
```

Usage

```
{'run_row_strategy': 'run the row_strategy function with a list of previous turn tuples to get the next move', 'test_row_strategy': 'test the row_strategy function with empty history to verify it returns default strategy 0', 'refactor_row_strategy': 'refactor the row_strategy function to use a different probabilistic decision-making approach', 'review_row_strategy': 'review the row_strategy function logic for the Battle of the Sexes game strategy selection', 'summarize_row_strategy': 'summarize the row_strategy function that selects moves based on game history and random probability'}
```

## File: facebookresearch_mlgym/data/battleOfSexes/target.py

Prompts

```
['run a Monte-Carlo simulation to compute mean score estimates for both players over multiple rounds', 'run an iterated game contest for a given number of rounds with specified strategy functions', 'compute final average scores for both row and column players from game history', 'get the payoff tuple for a given row and column strategy from a payoff matrix', 'get the Battle of the Sexes game payoff matrix with row and column player rewards', 'run the row_strategy function with a list of previous turn tuples to get the next move', 'test the row_strategy function with empty history to verify it returns default strategy 0', 'refactor the row_strategy function to use a different probabilistic decision-making approach', 'review the row_strategy function logic for the Battle of the Sexes game strategy selection', 'summarize the row_strategy function that selects moves based on game history and random probability', 'run target_column_strategy with a list of (row, col) tuples to get the next column player strategy', 'test target_column_strategy with an empty history list to verify it returns 1', 'test target_column_strategy with a history containing row strategy 1 to check probabilistic return', 'review target_column_strategy to understand the 80/20 probabilistic decision logic for column player moves', 'refactor target_column_strategy to replace the loop-based logic with a direct lookup on the last history entry']
```

Usage

```
{'run_target_column_strategy': 'run target_column_strategy with a list of (row, col) tuples to get the next column player strategy', 'test_target_column_strategy_empty_history': 'test target_column_strategy with an empty history list to verify it returns 1', 'test_target_column_strategy_with_history': 'test target_column_strategy with a history containing row strategy 1 to check probabilistic return', 'review_target_column_strategy': 'review target_column_strategy to understand the 80/20 probabilistic decision logic for column player moves', 'refactor_target_column_strategy': 'refactor target_column_strategy to replace the loop-based logic with a direct lookup on the last history entry'}
```

