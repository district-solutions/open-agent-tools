# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/safety_modules/identity_safety_module.py

Prompts

```
['create an IdentitySafetyModule instance that passes through action spaces without restriction', 'use filter_action to return the original action space unchanged for a given subjective state', 'call learn on IdentitySafetyModule with a replay buffer and policy learner to do nothing', 'call learn_batch on IdentitySafetyModule with a transition batch to perform no learning', 'compare two IdentitySafetyModule instances using compare to check if they are of the same type', 'create an RCSafetyModuleCostCriticContinuousAction instance with constraint value, state dim, and action space', 'train the cost critic network on a batch of transitions from the replay buffer', 'update the Lagrange multiplier via projected gradient descent using the cost critic Q values', 'compare two RCSafetyModuleCostCriticContinuousAction instances and return a string describing their differences', 'review the twin critic cost Q-network architecture and soft target update mechanism', 'create a RiskNeutralSafetyModule instance to compute Q-values as the expectation of a distributional Q-value network', 'create a QuantileNetworkMeanVarianceSafetyModule with a variance weighting coefficient to compute risk-adjusted Q-values', 'get Q-values under a risk neutral measure by computing the mean of a distributional Q-value network output', 'get variance-adjusted Q-values by computing mean minus beta times variance from a distributional Q-value network', 'implement a concrete SafetyModule subclass that overrides filter_action, learn, learn_batch, and compare methods', 'override the filter_action method to filter unsafe actions given a SubjectiveState and ActionSpace', 'override the learn method to train the safety module using a ReplayBuffer and PolicyLearner', 'override the learn_batch method to update the safety module on a single TransitionBatch', 'override the compare method to return a string describing differences between two SafetyModule instances']
```

Usage

```
{'create_identity_safety_module': 'create an IdentitySafetyModule instance that passes through action spaces without restriction', 'filter_action_identity': 'use filter_action to return the original action space unchanged for a given subjective state', 'learn_identity_safety': 'call learn on IdentitySafetyModule with a replay buffer and policy learner to do nothing', 'learn_batch_identity': 'call learn_batch on IdentitySafetyModule with a transition batch to perform no learning', 'compare_identity_safety': 'compare two IdentitySafetyModule instances using compare to check if they are of the same type'}
```

## File: facebookresearch_pearl/pearl/safety_modules/reward_constrained_safety_module.py

Prompts

```
['create an IdentitySafetyModule instance that passes through action spaces without restriction', 'use filter_action to return the original action space unchanged for a given subjective state', 'call learn on IdentitySafetyModule with a replay buffer and policy learner to do nothing', 'call learn_batch on IdentitySafetyModule with a transition batch to perform no learning', 'compare two IdentitySafetyModule instances using compare to check if they are of the same type', 'create an RCSafetyModuleCostCriticContinuousAction instance with constraint value, state dim, and action space', 'train the cost critic network on a batch of transitions from the replay buffer', 'update the Lagrange multiplier via projected gradient descent using the cost critic Q values', 'compare two RCSafetyModuleCostCriticContinuousAction instances and return a string describing their differences', 'review the twin critic cost Q-network architecture and soft target update mechanism', 'create a RiskNeutralSafetyModule instance to compute Q-values as the expectation of a distributional Q-value network', 'create a QuantileNetworkMeanVarianceSafetyModule with a variance weighting coefficient to compute risk-adjusted Q-values', 'get Q-values under a risk neutral measure by computing the mean of a distributional Q-value network output', 'get variance-adjusted Q-values by computing mean minus beta times variance from a distributional Q-value network', 'implement a concrete SafetyModule subclass that overrides filter_action, learn, learn_batch, and compare methods', 'override the filter_action method to filter unsafe actions given a SubjectiveState and ActionSpace', 'override the learn method to train the safety module using a ReplayBuffer and PolicyLearner', 'override the learn_batch method to update the safety module on a single TransitionBatch', 'override the compare method to return a string describing differences between two SafetyModule instances']
```

Usage

```
{'create_safety_module': 'create an RCSafetyModuleCostCriticContinuousAction instance with constraint value, state dim, and action space', 'train_cost_critic': 'train the cost critic network on a batch of transitions from the replay buffer', 'update_lambda_constraint': 'update the Lagrange multiplier via projected gradient descent using the cost critic Q values', 'compare_safety_modules': 'compare two RCSafetyModuleCostCriticContinuousAction instances and return a string describing their differences', 'review_twin_critic_architecture': 'review the twin critic cost Q-network architecture and soft target update mechanism'}
```

## File: facebookresearch_pearl/pearl/safety_modules/risk_sensitive_safety_modules.py

Prompts

```
['create an IdentitySafetyModule instance that passes through action spaces without restriction', 'use filter_action to return the original action space unchanged for a given subjective state', 'call learn on IdentitySafetyModule with a replay buffer and policy learner to do nothing', 'call learn_batch on IdentitySafetyModule with a transition batch to perform no learning', 'compare two IdentitySafetyModule instances using compare to check if they are of the same type', 'create an RCSafetyModuleCostCriticContinuousAction instance with constraint value, state dim, and action space', 'train the cost critic network on a batch of transitions from the replay buffer', 'update the Lagrange multiplier via projected gradient descent using the cost critic Q values', 'compare two RCSafetyModuleCostCriticContinuousAction instances and return a string describing their differences', 'review the twin critic cost Q-network architecture and soft target update mechanism', 'create a RiskNeutralSafetyModule instance to compute Q-values as the expectation of a distributional Q-value network', 'create a QuantileNetworkMeanVarianceSafetyModule with a variance weighting coefficient to compute risk-adjusted Q-values', 'get Q-values under a risk neutral measure by computing the mean of a distributional Q-value network output', 'get variance-adjusted Q-values by computing mean minus beta times variance from a distributional Q-value network', 'implement a concrete SafetyModule subclass that overrides filter_action, learn, learn_batch, and compare methods', 'override the filter_action method to filter unsafe actions given a SubjectiveState and ActionSpace', 'override the learn method to train the safety module using a ReplayBuffer and PolicyLearner', 'override the learn_batch method to update the safety module on a single TransitionBatch', 'override the compare method to return a string describing differences between two SafetyModule instances']
```

Usage

```
{'create_risk_neutral_safety_module': 'create a RiskNeutralSafetyModule instance to compute Q-values as the expectation of a distributional Q-value network', 'create_mean_variance_safety_module': 'create a QuantileNetworkMeanVarianceSafetyModule with a variance weighting coefficient to compute risk-adjusted Q-values', 'get_q_values_risk_neutral': 'get Q-values under a risk neutral measure by computing the mean of a distributional Q-value network output', 'get_q_values_mean_variance': 'get variance-adjusted Q-values by computing mean minus beta times variance from a distributional Q-value network', 'compare_safety_modules': 'compare two safety module instances to check type equality and attribute differences'}
```

## File: facebookresearch_pearl/pearl/safety_modules/safety_module.py

Prompts

```
['create an IdentitySafetyModule instance that passes through action spaces without restriction', 'use filter_action to return the original action space unchanged for a given subjective state', 'call learn on IdentitySafetyModule with a replay buffer and policy learner to do nothing', 'call learn_batch on IdentitySafetyModule with a transition batch to perform no learning', 'compare two IdentitySafetyModule instances using compare to check if they are of the same type', 'create an RCSafetyModuleCostCriticContinuousAction instance with constraint value, state dim, and action space', 'train the cost critic network on a batch of transitions from the replay buffer', 'update the Lagrange multiplier via projected gradient descent using the cost critic Q values', 'compare two RCSafetyModuleCostCriticContinuousAction instances and return a string describing their differences', 'review the twin critic cost Q-network architecture and soft target update mechanism', 'create a RiskNeutralSafetyModule instance to compute Q-values as the expectation of a distributional Q-value network', 'create a QuantileNetworkMeanVarianceSafetyModule with a variance weighting coefficient to compute risk-adjusted Q-values', 'get Q-values under a risk neutral measure by computing the mean of a distributional Q-value network output', 'get variance-adjusted Q-values by computing mean minus beta times variance from a distributional Q-value network', 'implement a concrete SafetyModule subclass that overrides filter_action, learn, learn_batch, and compare methods', 'override the filter_action method to filter unsafe actions given a SubjectiveState and ActionSpace', 'override the learn method to train the safety module using a ReplayBuffer and PolicyLearner', 'override the learn_batch method to update the safety module on a single TransitionBatch', 'override the compare method to return a string describing differences between two SafetyModule instances']
```

Usage

```
{'implement_SafetyModule_subclass': 'implement a concrete SafetyModule subclass that overrides filter_action, learn, learn_batch, and compare methods', 'override_filter_action': 'override the filter_action method to filter unsafe actions given a SubjectiveState and ActionSpace', 'override_learn': 'override the learn method to train the safety module using a ReplayBuffer and PolicyLearner', 'override_learn_batch': 'override the learn_batch method to update the safety module on a single TransitionBatch', 'override_compare': 'override the compare method to return a string describing differences between two SafetyModule instances'}
```

