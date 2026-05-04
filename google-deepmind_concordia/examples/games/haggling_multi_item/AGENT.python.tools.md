# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/examples/games/haggling_multi_item/haggling_multi_item_logic_test.py

Prompts

```
["test parse_item_and_price to extract item name and price from action strings like 'apple for 3 coins'", 'test MultiItemHagglingPayoff action_to_scores to compute buyer and seller scores from joint actions', 'test generate_price_options to create all item-price combinations for haggling game actions', 'test create_player_pairs to randomly pair players as buyer and seller for haggling rounds', 'test MultiItemHagglingPayoff handles missing players and unknown items by returning zero or negative scores', 'run the haggling multi-item simulation using puppet agents and a mock embedder to verify completion', 'test that the haggling simulation returns scores, joint actions, and players when using puppet agents', 'test that puppet agents choose valid actions containing coins or accept or reject', 'test that all computed scores in the haggling simulation are numeric int or float values', 'review the mock embedder function that returns a fixed three-element numpy array of ones', 'run a multi-item haggling simulation with buyers and sellers negotiating prices for fruit items', "parse an action string like 'apple for 3 coins' into an item name and price tuple", 'map joint buyer and seller actions to numerical scores for each player in a bargaining game', 'convert numerical scores into descriptive text observations for each player after a bargaining round', 'configure negotiation and decision scenes for a multi-item haggling simulation with buyer seller pairs']
```

Usage

```
{'test_parse_item_and_price': "test parse_item_and_price to extract item name and price from action strings like 'apple for 3 coins'", 'test_MultiItemHagglingPayoff_action_to_scores': 'test MultiItemHagglingPayoff action_to_scores to compute buyer and seller scores from joint actions', 'test_generate_price_options': 'test generate_price_options to create all item-price combinations for haggling game actions', 'test_create_player_pairs': 'test create_player_pairs to randomly pair players as buyer and seller for haggling rounds', 'test_MultiItemHagglingPayoff_edge_cases': 'test MultiItemHagglingPayoff handles missing players and unknown items by returning zero or negative scores'}
```

## File: google-deepmind_concordia/examples/games/haggling_multi_item/haggling_multi_item_test.py

Prompts

```
["test parse_item_and_price to extract item name and price from action strings like 'apple for 3 coins'", 'test MultiItemHagglingPayoff action_to_scores to compute buyer and seller scores from joint actions', 'test generate_price_options to create all item-price combinations for haggling game actions', 'test create_player_pairs to randomly pair players as buyer and seller for haggling rounds', 'test MultiItemHagglingPayoff handles missing players and unknown items by returning zero or negative scores', 'run the haggling multi-item simulation using puppet agents and a mock embedder to verify completion', 'test that the haggling simulation returns scores, joint actions, and players when using puppet agents', 'test that puppet agents choose valid actions containing coins or accept or reject', 'test that all computed scores in the haggling simulation are numeric int or float values', 'review the mock embedder function that returns a fixed three-element numpy array of ones', 'run a multi-item haggling simulation with buyers and sellers negotiating prices for fruit items', "parse an action string like 'apple for 3 coins' into an item name and price tuple", 'map joint buyer and seller actions to numerical scores for each player in a bargaining game', 'convert numerical scores into descriptive text observations for each player after a bargaining round', 'configure negotiation and decision scenes for a multi-item haggling simulation with buyer seller pairs']
```

Usage

```
{'run_simulation_with_puppet_agents': 'run the haggling multi-item simulation using puppet agents and a mock embedder to verify completion', 'test_simulation_runs_to_completion': 'test that the haggling simulation returns scores, joint actions, and players when using puppet agents', 'test_puppets_choose_valid_options': 'test that puppet agents choose valid actions containing coins or accept or reject', 'test_scoring_is_consistent': 'test that all computed scores in the haggling simulation are numeric int or float values', 'review_mock_embedder': 'review the mock embedder function that returns a fixed three-element numpy array of ones'}
```

## File: google-deepmind_concordia/examples/games/haggling_multi_item/simulation.py

Prompts

```
["test parse_item_and_price to extract item name and price from action strings like 'apple for 3 coins'", 'test MultiItemHagglingPayoff action_to_scores to compute buyer and seller scores from joint actions', 'test generate_price_options to create all item-price combinations for haggling game actions', 'test create_player_pairs to randomly pair players as buyer and seller for haggling rounds', 'test MultiItemHagglingPayoff handles missing players and unknown items by returning zero or negative scores', 'run the haggling multi-item simulation using puppet agents and a mock embedder to verify completion', 'test that the haggling simulation returns scores, joint actions, and players when using puppet agents', 'test that puppet agents choose valid actions containing coins or accept or reject', 'test that all computed scores in the haggling simulation are numeric int or float values', 'review the mock embedder function that returns a fixed three-element numpy array of ones', 'run a multi-item haggling simulation with buyers and sellers negotiating prices for fruit items', "parse an action string like 'apple for 3 coins' into an item name and price tuple", 'map joint buyer and seller actions to numerical scores for each player in a bargaining game', 'convert numerical scores into descriptive text observations for each player after a bargaining round', 'configure negotiation and decision scenes for a multi-item haggling simulation with buyer seller pairs']
```

Usage

```
{'run_simulation': 'run a multi-item haggling simulation with buyers and sellers negotiating prices for fruit items', 'parse_item_and_price': "parse an action string like 'apple for 3 coins' into an item name and price tuple", 'MultiItemHagglingPayoff_action_to_scores': 'map joint buyer and seller actions to numerical scores for each player in a bargaining game', 'MultiItemHagglingPayoff_scores_to_observation': 'convert numerical scores into descriptive text observations for each player after a bargaining round', 'configure_scenes': 'configure negotiation and decision scenes for a multi-item haggling simulation with buyer seller pairs'}
```

