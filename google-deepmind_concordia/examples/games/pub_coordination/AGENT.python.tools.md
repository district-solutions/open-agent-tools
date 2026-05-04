# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/examples/games/pub_coordination/pub_coordination_logic_test.py

Prompts

```
['test sample_parameters to verify it returns correct number of venues and people from preferences', 'test action_to_scores when all players choose the same pub and expect equal scores', 'test action_to_scores when one player chooses a different pub and gets zero score', 'test action_to_scores when the chosen pub is closed and all players get zero', 'test PubCoordinationPayoff action_to_scores with partial friendship relational matrix and asymmetric splits', 'run the pub coordination simulation using puppet agents and a no-op language model', 'test that the pub coordination simulation completes and returns focal scores and joint actions', 'test that puppet agents select only valid pubs from venue preferences', 'create a mock embedder function that returns a fixed numpy array for any input text', 'review the PubCoordinationTest class and its puppet agent test methods for correctness', 'run a pub coordination simulation with a config, language model, and embedder to get player scores and joint actions', 'configure conversation and decision scenes for a multi-game pub coordination simulation with venues and players', 'calculate player scores from joint pub choices using preferences, social relationships, and option multipliers', 'generate a symmetric relationship matrix for a group of people with random friendship values', 'sample random venues, people names, and a seeded RNG for a pub coordination simulation', 'get a random personality trait string from the TRAITS tuple using get_trait', 'get a random flowery personality trait description using get_trait with flowery set to True', 'get a random trait using get_trait with a seeded random.Random instance for reproducibility', 'list all 27 personality trait strings from the TRAITS constant tuple', 'list all positive and neutral relationship template statements with player placeholders']
```

Usage

```
{'test_sample_parameters': 'test sample_parameters to verify it returns correct number of venues and people from preferences', 'test_action_to_scores_perfect_consensus': 'test action_to_scores when all players choose the same pub and expect equal scores', 'test_action_to_scores_split_decision': 'test action_to_scores when one player chooses a different pub and gets zero score', 'test_action_to_scores_closed_pub': 'test action_to_scores when the chosen pub is closed and all players get zero', 'test_pubcoordinationpayoff_action_to_scores': 'test PubCoordinationPayoff action_to_scores with partial friendship relational matrix and asymmetric splits'}
```

## File: google-deepmind_concordia/examples/games/pub_coordination/pub_coordination_test.py

Prompts

```
['test sample_parameters to verify it returns correct number of venues and people from preferences', 'test action_to_scores when all players choose the same pub and expect equal scores', 'test action_to_scores when one player chooses a different pub and gets zero score', 'test action_to_scores when the chosen pub is closed and all players get zero', 'test PubCoordinationPayoff action_to_scores with partial friendship relational matrix and asymmetric splits', 'run the pub coordination simulation using puppet agents and a no-op language model', 'test that the pub coordination simulation completes and returns focal scores and joint actions', 'test that puppet agents select only valid pubs from venue preferences', 'create a mock embedder function that returns a fixed numpy array for any input text', 'review the PubCoordinationTest class and its puppet agent test methods for correctness', 'run a pub coordination simulation with a config, language model, and embedder to get player scores and joint actions', 'configure conversation and decision scenes for a multi-game pub coordination simulation with venues and players', 'calculate player scores from joint pub choices using preferences, social relationships, and option multipliers', 'generate a symmetric relationship matrix for a group of people with random friendship values', 'sample random venues, people names, and a seeded RNG for a pub coordination simulation', 'get a random personality trait string from the TRAITS tuple using get_trait', 'get a random flowery personality trait description using get_trait with flowery set to True', 'get a random trait using get_trait with a seeded random.Random instance for reproducibility', 'list all 27 personality trait strings from the TRAITS constant tuple', 'list all positive and neutral relationship template statements with player placeholders']
```

Usage

```
{'run_simulation_with_puppet_agents': 'run the pub coordination simulation using puppet agents and a no-op language model', 'test_simulation_runs_to_completion': 'test that the pub coordination simulation completes and returns focal scores and joint actions', 'test_puppets_choose_valid_pubs': 'test that puppet agents select only valid pubs from venue preferences', 'create_mock_embedder': 'create a mock embedder function that returns a fixed numpy array for any input text', 'review_pub_coordination_test': 'review the PubCoordinationTest class and its puppet agent test methods for correctness'}
```

## File: google-deepmind_concordia/examples/games/pub_coordination/simulation.py

Prompts

```
['test sample_parameters to verify it returns correct number of venues and people from preferences', 'test action_to_scores when all players choose the same pub and expect equal scores', 'test action_to_scores when one player chooses a different pub and gets zero score', 'test action_to_scores when the chosen pub is closed and all players get zero', 'test PubCoordinationPayoff action_to_scores with partial friendship relational matrix and asymmetric splits', 'run the pub coordination simulation using puppet agents and a no-op language model', 'test that the pub coordination simulation completes and returns focal scores and joint actions', 'test that puppet agents select only valid pubs from venue preferences', 'create a mock embedder function that returns a fixed numpy array for any input text', 'review the PubCoordinationTest class and its puppet agent test methods for correctness', 'run a pub coordination simulation with a config, language model, and embedder to get player scores and joint actions', 'configure conversation and decision scenes for a multi-game pub coordination simulation with venues and players', 'calculate player scores from joint pub choices using preferences, social relationships, and option multipliers', 'generate a symmetric relationship matrix for a group of people with random friendship values', 'sample random venues, people names, and a seeded RNG for a pub coordination simulation', 'get a random personality trait string from the TRAITS tuple using get_trait', 'get a random flowery personality trait description using get_trait with flowery set to True', 'get a random trait using get_trait with a seeded random.Random instance for reproducibility', 'list all 27 personality trait strings from the TRAITS constant tuple', 'list all positive and neutral relationship template statements with player placeholders']
```

Usage

```
{'run_pub_coordination_simulation': 'run a pub coordination simulation with a config, language model, and embedder to get player scores and joint actions', 'configure_simulation_scenes': 'configure conversation and decision scenes for a multi-game pub coordination simulation with venues and players', 'calculate_payoff_scores': 'calculate player scores from joint pub choices using preferences, social relationships, and option multipliers', 'generate_relationship_matrix': 'generate a symmetric relationship matrix for a group of people with random friendship values', 'sample_simulation_parameters': 'sample random venues, people names, and a seeded RNG for a pub coordination simulation'}
```

## File: google-deepmind_concordia/examples/games/pub_coordination/social_data.py

Prompts

```
['test sample_parameters to verify it returns correct number of venues and people from preferences', 'test action_to_scores when all players choose the same pub and expect equal scores', 'test action_to_scores when one player chooses a different pub and gets zero score', 'test action_to_scores when the chosen pub is closed and all players get zero', 'test PubCoordinationPayoff action_to_scores with partial friendship relational matrix and asymmetric splits', 'run the pub coordination simulation using puppet agents and a no-op language model', 'test that the pub coordination simulation completes and returns focal scores and joint actions', 'test that puppet agents select only valid pubs from venue preferences', 'create a mock embedder function that returns a fixed numpy array for any input text', 'review the PubCoordinationTest class and its puppet agent test methods for correctness', 'run a pub coordination simulation with a config, language model, and embedder to get player scores and joint actions', 'configure conversation and decision scenes for a multi-game pub coordination simulation with venues and players', 'calculate player scores from joint pub choices using preferences, social relationships, and option multipliers', 'generate a symmetric relationship matrix for a group of people with random friendship values', 'sample random venues, people names, and a seeded RNG for a pub coordination simulation', 'get a random personality trait string from the TRAITS tuple using get_trait', 'get a random flowery personality trait description using get_trait with flowery set to True', 'get a random trait using get_trait with a seeded random.Random instance for reproducibility', 'list all 27 personality trait strings from the TRAITS constant tuple', 'list all positive and neutral relationship template statements with player placeholders']
```

Usage

```
{'get_random_trait': 'get a random personality trait string from the TRAITS tuple using get_trait', 'get_flowery_trait': 'get a random flowery personality trait description using get_trait with flowery set to True', 'get_trait_with_rng': 'get a random trait using get_trait with a seeded random.Random instance for reproducibility', 'list_personality_traits': 'list all 27 personality trait strings from the TRAITS constant tuple', 'list_relationship_statements': 'list all positive and neutral relationship template statements with player placeholders'}
```

