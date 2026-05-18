# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/prisonersDilemma/evaluate.py

Prompts

```
["run the evaluate function to simulate 10000 Monte-Carlo rounds of the Prisoner's Dilemma game and print the row player score", "run an iterated Prisoner's Dilemma game for a given number of rounds with custom row and column strategy functions", 'compute the mean payoff scores for both players from a game history using a payoff matrix', 'get the payoff tuple for a single round given a payoff matrix and the strategies chosen by both players', "run a Monte-Carlo simulation of the iterated Prisoner's Dilemma and return mean score estimates for both players", 'run the row_strategy function with a list of previous turn tuples to get the next move', 'test the row_strategy function with empty history to verify it returns 0 or 1 randomly', 'refactor the row_strategy function to use a different probability threshold for cooperation decisions', 'review the row_strategy function logic for handling cooperation and defection responses based on opponent history', "summarize the row_strategy function which selects cooperate or defect based on opponent's last move and random probability", "run the target_column_strategy function to randomly select and execute a prisoner's dilemma strategy given game history", "test the tit_for_tat strategy function that copies the opponent's last move in a prisoner's dilemma game", 'review the grim_trigger strategy that cooperates until the opponent defects then defects forever', 'summarize the pavlov strategy that cooperates if both players matched last round and defects otherwise', 'create a forgiving tit for tat strategy that forgives after two consecutive opponent defections']
```

Usage

```
{'run_evaluate_prisoners_dilemma': "run the evaluate function to simulate 10000 Monte-Carlo rounds of the Prisoner's Dilemma game and print the row player score", 'run_iterated_game': "run an iterated Prisoner's Dilemma game for a given number of rounds with custom row and column strategy functions", 'compute_overall_scores': 'compute the mean payoff scores for both players from a game history using a payoff matrix', 'get_game_payoffs': 'get the payoff tuple for a single round given a payoff matrix and the strategies chosen by both players', 'run_simulation_mean_scores': "run a Monte-Carlo simulation of the iterated Prisoner's Dilemma and return mean score estimates for both players"}
```

## File: facebookresearch_mlgym/data/prisonersDilemma/strategy.py

Prompts

```
["run the evaluate function to simulate 10000 Monte-Carlo rounds of the Prisoner's Dilemma game and print the row player score", "run an iterated Prisoner's Dilemma game for a given number of rounds with custom row and column strategy functions", 'compute the mean payoff scores for both players from a game history using a payoff matrix', 'get the payoff tuple for a single round given a payoff matrix and the strategies chosen by both players', "run a Monte-Carlo simulation of the iterated Prisoner's Dilemma and return mean score estimates for both players", 'run the row_strategy function with a list of previous turn tuples to get the next move', 'test the row_strategy function with empty history to verify it returns 0 or 1 randomly', 'refactor the row_strategy function to use a different probability threshold for cooperation decisions', 'review the row_strategy function logic for handling cooperation and defection responses based on opponent history', "summarize the row_strategy function which selects cooperate or defect based on opponent's last move and random probability", "run the target_column_strategy function to randomly select and execute a prisoner's dilemma strategy given game history", "test the tit_for_tat strategy function that copies the opponent's last move in a prisoner's dilemma game", 'review the grim_trigger strategy that cooperates until the opponent defects then defects forever', 'summarize the pavlov strategy that cooperates if both players matched last round and defects otherwise', 'create a forgiving tit for tat strategy that forgives after two consecutive opponent defections']
```

Usage

```
{'run_row_strategy': 'run the row_strategy function with a list of previous turn tuples to get the next move', 'test_row_strategy': 'test the row_strategy function with empty history to verify it returns 0 or 1 randomly', 'refactor_row_strategy': 'refactor the row_strategy function to use a different probability threshold for cooperation decisions', 'review_row_strategy': 'review the row_strategy function logic for handling cooperation and defection responses based on opponent history', 'summarize_row_strategy': "summarize the row_strategy function which selects cooperate or defect based on opponent's last move and random probability"}
```

## File: facebookresearch_mlgym/data/prisonersDilemma/target.py

Prompts

```
["run the evaluate function to simulate 10000 Monte-Carlo rounds of the Prisoner's Dilemma game and print the row player score", "run an iterated Prisoner's Dilemma game for a given number of rounds with custom row and column strategy functions", 'compute the mean payoff scores for both players from a game history using a payoff matrix', 'get the payoff tuple for a single round given a payoff matrix and the strategies chosen by both players', "run a Monte-Carlo simulation of the iterated Prisoner's Dilemma and return mean score estimates for both players", 'run the row_strategy function with a list of previous turn tuples to get the next move', 'test the row_strategy function with empty history to verify it returns 0 or 1 randomly', 'refactor the row_strategy function to use a different probability threshold for cooperation decisions', 'review the row_strategy function logic for handling cooperation and defection responses based on opponent history', "summarize the row_strategy function which selects cooperate or defect based on opponent's last move and random probability", "run the target_column_strategy function to randomly select and execute a prisoner's dilemma strategy given game history", "test the tit_for_tat strategy function that copies the opponent's last move in a prisoner's dilemma game", 'review the grim_trigger strategy that cooperates until the opponent defects then defects forever', 'summarize the pavlov strategy that cooperates if both players matched last round and defects otherwise', 'create a forgiving tit for tat strategy that forgives after two consecutive opponent defections']
```

Usage

```
{'run_target_column_strategy': "run the target_column_strategy function to randomly select and execute a prisoner's dilemma strategy given game history", 'test_tit_for_tat': "test the tit_for_tat strategy function that copies the opponent's last move in a prisoner's dilemma game", 'review_grim_trigger': 'review the grim_trigger strategy that cooperates until the opponent defects then defects forever', 'summarize_pavlov': 'summarize the pavlov strategy that cooperates if both players matched last round and defects otherwise', 'create_forgiving_tit_for_tat': 'create a forgiving tit for tat strategy that forgives after two consecutive opponent defections'}
```

