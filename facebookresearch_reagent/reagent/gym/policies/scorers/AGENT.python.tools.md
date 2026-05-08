# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/gym/policies/scorers/continuous_scorer.py

Prompts

```
['create a SAC scorer function from an actor network model for continuous action scoring', "build a GaussianSamplerScore with loc and scale_log from an actor network's output", 'test the sac_scorer function by passing a ModelBase actor network and verifying the returned scorer', 'review the sac_scorer function to understand how it extracts loc and scale_log from the actor network', 'refactor the sac_scorer to use a public API instead of the private _get_loc_and_scale_log method', 'create a DQN scorer function from a Q-network model to score preprocessed observations', 'create a serving DQN scorer from a torch module to score states with action masking', 'apply a boolean mask to set invalid action scores to negative infinity', 'create a parametric DQN scorer that tiles state and action inputs for scoring', 'create a parametric serving scorer that scores tiled state-action pairs with presence masks', 'create a scorer function that scores candidate documents using a Q-network and softmax selection probabilities', 'create a serving scorer that scores candidates using a torch module Q-network with float features', 'review the slate_q_scorer function that tiles state, runs Q-network inference, and returns weighted scores', 'review the slate_q_serving_scorer function that scores candidates using a serving Q-network with attention masks', 'summarize the slate Q-scorer functions that compute weighted Q-values for candidate document selection']
```

Usage

```
{'create_sac_scorer': 'create a SAC scorer function from an actor network model for continuous action scoring', 'build_gaussian_sampler_score': "build a GaussianSamplerScore with loc and scale_log from an actor network's output", 'test_sac_scorer': 'test the sac_scorer function by passing a ModelBase actor network and verifying the returned scorer', 'review_sac_scorer': 'review the sac_scorer function to understand how it extracts loc and scale_log from the actor network', 'refactor_sac_scorer': 'refactor the sac_scorer to use a public API instead of the private _get_loc_and_scale_log method'}
```

## File: facebookresearch_reagent/reagent/gym/policies/scorers/discrete_scorer.py

Prompts

```
['create a SAC scorer function from an actor network model for continuous action scoring', "build a GaussianSamplerScore with loc and scale_log from an actor network's output", 'test the sac_scorer function by passing a ModelBase actor network and verifying the returned scorer', 'review the sac_scorer function to understand how it extracts loc and scale_log from the actor network', 'refactor the sac_scorer to use a public API instead of the private _get_loc_and_scale_log method', 'create a DQN scorer function from a Q-network model to score preprocessed observations', 'create a serving DQN scorer from a torch module to score states with action masking', 'apply a boolean mask to set invalid action scores to negative infinity', 'create a parametric DQN scorer that tiles state and action inputs for scoring', 'create a parametric serving scorer that scores tiled state-action pairs with presence masks', 'create a scorer function that scores candidate documents using a Q-network and softmax selection probabilities', 'create a serving scorer that scores candidates using a torch module Q-network with float features', 'review the slate_q_scorer function that tiles state, runs Q-network inference, and returns weighted scores', 'review the slate_q_serving_scorer function that scores candidates using a serving Q-network with attention masks', 'summarize the slate Q-scorer functions that compute weighted Q-values for candidate document selection']
```

Usage

```
{'create_discrete_dqn_scorer': 'create a DQN scorer function from a Q-network model to score preprocessed observations', 'create_discrete_dqn_serving_scorer': 'create a serving DQN scorer from a torch module to score states with action masking', 'apply_possible_actions_mask': 'apply a boolean mask to set invalid action scores to negative infinity', 'create_parametric_dqn_scorer': 'create a parametric DQN scorer that tiles state and action inputs for scoring', 'create_parametric_dqn_serving_scorer': 'create a parametric serving scorer that scores tiled state-action pairs with presence masks'}
```

## File: facebookresearch_reagent/reagent/gym/policies/scorers/slate_q_scorer.py

Prompts

```
['create a SAC scorer function from an actor network model for continuous action scoring', "build a GaussianSamplerScore with loc and scale_log from an actor network's output", 'test the sac_scorer function by passing a ModelBase actor network and verifying the returned scorer', 'review the sac_scorer function to understand how it extracts loc and scale_log from the actor network', 'refactor the sac_scorer to use a public API instead of the private _get_loc_and_scale_log method', 'create a DQN scorer function from a Q-network model to score preprocessed observations', 'create a serving DQN scorer from a torch module to score states with action masking', 'apply a boolean mask to set invalid action scores to negative infinity', 'create a parametric DQN scorer that tiles state and action inputs for scoring', 'create a parametric serving scorer that scores tiled state-action pairs with presence masks', 'create a scorer function that scores candidate documents using a Q-network and softmax selection probabilities', 'create a serving scorer that scores candidates using a torch module Q-network with float features', 'review the slate_q_scorer function that tiles state, runs Q-network inference, and returns weighted scores', 'review the slate_q_serving_scorer function that scores candidates using a serving Q-network with attention masks', 'summarize the slate Q-scorer functions that compute weighted Q-values for candidate document selection']
```

Usage

```
{'create_slate_q_scorer': 'create a scorer function that scores candidate documents using a Q-network and softmax selection probabilities', 'create_slate_q_serving_scorer': 'create a serving scorer that scores candidates using a torch module Q-network with float features', 'review_slate_q_scorer': 'review the slate_q_scorer function that tiles state, runs Q-network inference, and returns weighted scores', 'review_slate_q_serving_scorer': 'review the slate_q_serving_scorer function that scores candidates using a serving Q-network with attention masks', 'summarize_scorer_functions': 'summarize the slate Q-scorer functions that compute weighted Q-values for candidate document selection'}
```

