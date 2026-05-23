# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/policy_learners/exploration_modules/contextual_bandits/squarecb_exploration.py

Prompts

```
['build a SquareCBExploration instance with gamma to control exploration-exploitation tradeoff for contextual bandits', 'build a FastCBExploration instance with gamma and bounded rewards for improved contextual bandit performance', 'test the SquareCBExploration act method to sample actions from a probability distribution over discrete actions', 'review the FastCBExploration get_unnormalize_prob method that computes improved unnormalized probabilities for action selection', 'test the SquareCBExploration compare method to check equality of gamma reward bounds and clamp settings', 'build a ThompsonSamplingExplorationLinear module for joint linear bandits with efficient sampling enabled', 'build a ThompsonSamplingExplorationLinearDisjoint module for disjoint linear bandits exploration', 'test the get_scores method of ThompsonSamplingExplorationLinear to compute predicted scores from sampled parameters', 'test the get_scores method of ThompsonSamplingExplorationLinearDisjoint to compute per-action scores from separate models', 'review the compare method of ThompsonSamplingExplorationLinear to check attribute equality between two instances', 'build a UCBExploration module with alpha parameter for upper confidence bound exploration in RL', 'create a DisjointUCBExploration module with separate bandit models for each action arm', 'test the VanillaUCBExploration sigma method to compute exploration bonus using action execution counts', 'refactor the UCBExploration get_scores method to compute UCB scores from values and sigma', 'review the UCBExploration compare method to check attribute differences between two instances']
```

Usage

```
{'build_squarecb_exploration': 'build a SquareCBExploration instance with gamma to control exploration-exploitation tradeoff for contextual bandits', 'build_fastcb_exploration': 'build a FastCBExploration instance with gamma and bounded rewards for improved contextual bandit performance', 'test_squarecb_act': 'test the SquareCBExploration act method to sample actions from a probability distribution over discrete actions', 'review_fastcb_get_unnormalize_prob': 'review the FastCBExploration get_unnormalize_prob method that computes improved unnormalized probabilities for action selection', 'test_squarecb_compare': 'test the SquareCBExploration compare method to check equality of gamma reward bounds and clamp settings'}
```

## File: facebookresearch_pearl/pearl/policy_learners/exploration_modules/contextual_bandits/thompson_sampling_exploration.py

Prompts

```
['build a SquareCBExploration instance with gamma to control exploration-exploitation tradeoff for contextual bandits', 'build a FastCBExploration instance with gamma and bounded rewards for improved contextual bandit performance', 'test the SquareCBExploration act method to sample actions from a probability distribution over discrete actions', 'review the FastCBExploration get_unnormalize_prob method that computes improved unnormalized probabilities for action selection', 'test the SquareCBExploration compare method to check equality of gamma reward bounds and clamp settings', 'build a ThompsonSamplingExplorationLinear module for joint linear bandits with efficient sampling enabled', 'build a ThompsonSamplingExplorationLinearDisjoint module for disjoint linear bandits exploration', 'test the get_scores method of ThompsonSamplingExplorationLinear to compute predicted scores from sampled parameters', 'test the get_scores method of ThompsonSamplingExplorationLinearDisjoint to compute per-action scores from separate models', 'review the compare method of ThompsonSamplingExplorationLinear to check attribute equality between two instances', 'build a UCBExploration module with alpha parameter for upper confidence bound exploration in RL', 'create a DisjointUCBExploration module with separate bandit models for each action arm', 'test the VanillaUCBExploration sigma method to compute exploration bonus using action execution counts', 'refactor the UCBExploration get_scores method to compute UCB scores from values and sigma', 'review the UCBExploration compare method to check attribute differences between two instances']
```

Usage

```
{'build_thompson_sampling_exploration_linear': 'build a ThompsonSamplingExplorationLinear module for joint linear bandits with efficient sampling enabled', 'build_thompson_sampling_exploration_disjoint': 'build a ThompsonSamplingExplorationLinearDisjoint module for disjoint linear bandits exploration', 'test_get_scores_joint': 'test the get_scores method of ThompsonSamplingExplorationLinear to compute predicted scores from sampled parameters', 'test_get_scores_disjoint': 'test the get_scores method of ThompsonSamplingExplorationLinearDisjoint to compute per-action scores from separate models', 'review_compare_method': 'review the compare method of ThompsonSamplingExplorationLinear to check attribute equality between two instances'}
```

## File: facebookresearch_pearl/pearl/policy_learners/exploration_modules/contextual_bandits/ucb_exploration.py

Prompts

```
['build a SquareCBExploration instance with gamma to control exploration-exploitation tradeoff for contextual bandits', 'build a FastCBExploration instance with gamma and bounded rewards for improved contextual bandit performance', 'test the SquareCBExploration act method to sample actions from a probability distribution over discrete actions', 'review the FastCBExploration get_unnormalize_prob method that computes improved unnormalized probabilities for action selection', 'test the SquareCBExploration compare method to check equality of gamma reward bounds and clamp settings', 'build a ThompsonSamplingExplorationLinear module for joint linear bandits with efficient sampling enabled', 'build a ThompsonSamplingExplorationLinearDisjoint module for disjoint linear bandits exploration', 'test the get_scores method of ThompsonSamplingExplorationLinear to compute predicted scores from sampled parameters', 'test the get_scores method of ThompsonSamplingExplorationLinearDisjoint to compute per-action scores from separate models', 'review the compare method of ThompsonSamplingExplorationLinear to check attribute equality between two instances', 'build a UCBExploration module with alpha parameter for upper confidence bound exploration in RL', 'create a DisjointUCBExploration module with separate bandit models for each action arm', 'test the VanillaUCBExploration sigma method to compute exploration bonus using action execution counts', 'refactor the UCBExploration get_scores method to compute UCB scores from values and sigma', 'review the UCBExploration compare method to check attribute differences between two instances']
```

Usage

```
{'build_ucb_exploration_module': 'build a UCBExploration module with alpha parameter for upper confidence bound exploration in RL', 'create_disjoint_ucb_exploration': 'create a DisjointUCBExploration module with separate bandit models for each action arm', 'test_vanilla_ucb_sigma': 'test the VanillaUCBExploration sigma method to compute exploration bonus using action execution counts', 'refactor_ucb_get_scores': 'refactor the UCBExploration get_scores method to compute UCB scores from values and sigma', 'review_ucb_compare': 'review the UCBExploration compare method to check attribute differences between two instances'}
```

