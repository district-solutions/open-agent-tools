# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/model_managers/discrete/discrete_c51dqn.py

Prompts

```
['build a C51DQN trainer with a categorical Q-network for discrete action reinforcement learning', 'build a TorchScript predictor module from a trained C51DQN model for serving', 'create a DiscreteC51DQN dataclass instance with custom trainer parameters and network builders', 'review the DiscreteC51DQN post-init validation that enforces at least 2 actions and minibatch divisibility', 'summarize how the Categorical net builder constructs Q-networks with num_atoms, qmin, and qmax parameters', 'build a DiscreteCRRTrainer with actor, critic, and optional reward networks for counterfactual regret minimization', 'create an online actor critic policy from a DiscreteCRRTrainer for serving or training mode', 'build serving modules including default_model, dqn, actor_dqn, and optional binary_difference_scorer for inference', 'create an ActorPolicyWrapper that wraps an actor network and uses its forward function as the act method', 'build an ActorDQN wrapper that extracts action output from an actor network for DQN predictor compatibility', 'build a DiscreteDQN trainer with Q-network, target network, and optional CPE reward networks', 'create a TorchScript serving module from a trained DiscreteDQN trainer for inference', 'build a reward prediction module using the CPE network and BanditRewardNetPredictorWrapper', 'get a DiscreteDQNReporter instance configured with action names and target action distribution', 'build a binary difference scorer module for two-action DiscreteDQN models', 'build a DiscreteQRDQN trainer with DuelingQuantile network and CPE reward network for quantile regression DQN training', 'build a TorchScript predictor module from a trained QRDQN trainer for serving quantile DQN predictions', 'create a DiscreteQRDQN model with custom trainer parameters and DuelingQuantile net builder for multi-action RL', 'review the DiscreteQRDQN post init validation that enforces at least 2 actions and minibatch size divisible by 8', 'summarize the DiscreteQRDQN class that extends DiscreteDQNBase with quantile regression DQN training and CPE evaluation support']
```

Usage

```
{'build_discrete_c51dqn_trainer': 'build a C51DQN trainer with a categorical Q-network for discrete action reinforcement learning', 'build_serving_module_c51dqn': 'build a TorchScript predictor module from a trained C51DQN model for serving', 'create_discrete_c51dqn_config': 'create a DiscreteC51DQN dataclass instance with custom trainer parameters and network builders', 'review_discrete_c51dqn_validation': 'review the DiscreteC51DQN post-init validation that enforces at least 2 actions and minibatch divisibility', 'summarize_c51dqn_net_builder': 'summarize how the Categorical net builder constructs Q-networks with num_atoms, qmin, and qmax parameters'}
```

## File: facebookresearch_reagent/reagent/model_managers/discrete/discrete_crr.py

Prompts

```
['build a C51DQN trainer with a categorical Q-network for discrete action reinforcement learning', 'build a TorchScript predictor module from a trained C51DQN model for serving', 'create a DiscreteC51DQN dataclass instance with custom trainer parameters and network builders', 'review the DiscreteC51DQN post-init validation that enforces at least 2 actions and minibatch divisibility', 'summarize how the Categorical net builder constructs Q-networks with num_atoms, qmin, and qmax parameters', 'build a DiscreteCRRTrainer with actor, critic, and optional reward networks for counterfactual regret minimization', 'create an online actor critic policy from a DiscreteCRRTrainer for serving or training mode', 'build serving modules including default_model, dqn, actor_dqn, and optional binary_difference_scorer for inference', 'create an ActorPolicyWrapper that wraps an actor network and uses its forward function as the act method', 'build an ActorDQN wrapper that extracts action output from an actor network for DQN predictor compatibility', 'build a DiscreteDQN trainer with Q-network, target network, and optional CPE reward networks', 'create a TorchScript serving module from a trained DiscreteDQN trainer for inference', 'build a reward prediction module using the CPE network and BanditRewardNetPredictorWrapper', 'get a DiscreteDQNReporter instance configured with action names and target action distribution', 'build a binary difference scorer module for two-action DiscreteDQN models', 'build a DiscreteQRDQN trainer with DuelingQuantile network and CPE reward network for quantile regression DQN training', 'build a TorchScript predictor module from a trained QRDQN trainer for serving quantile DQN predictions', 'create a DiscreteQRDQN model with custom trainer parameters and DuelingQuantile net builder for multi-action RL', 'review the DiscreteQRDQN post init validation that enforces at least 2 actions and minibatch size divisible by 8', 'summarize the DiscreteQRDQN class that extends DiscreteDQNBase with quantile regression DQN training and CPE evaluation support']
```

Usage

```
{'build_DiscreteCRR_trainer': 'build a DiscreteCRRTrainer with actor, critic, and optional reward networks for counterfactual regret minimization', 'create_DiscreteCRR_policy': 'create an online actor critic policy from a DiscreteCRRTrainer for serving or training mode', 'build_DiscreteCRR_serving_modules': 'build serving modules including default_model, dqn, actor_dqn, and optional binary_difference_scorer for inference', 'create_ActorPolicyWrapper': 'create an ActorPolicyWrapper that wraps an actor network and uses its forward function as the act method', 'build_ActorDQN_wrapper': 'build an ActorDQN wrapper that extracts action output from an actor network for DQN predictor compatibility'}
```

## File: facebookresearch_reagent/reagent/model_managers/discrete/discrete_dqn.py

Prompts

```
['build a C51DQN trainer with a categorical Q-network for discrete action reinforcement learning', 'build a TorchScript predictor module from a trained C51DQN model for serving', 'create a DiscreteC51DQN dataclass instance with custom trainer parameters and network builders', 'review the DiscreteC51DQN post-init validation that enforces at least 2 actions and minibatch divisibility', 'summarize how the Categorical net builder constructs Q-networks with num_atoms, qmin, and qmax parameters', 'build a DiscreteCRRTrainer with actor, critic, and optional reward networks for counterfactual regret minimization', 'create an online actor critic policy from a DiscreteCRRTrainer for serving or training mode', 'build serving modules including default_model, dqn, actor_dqn, and optional binary_difference_scorer for inference', 'create an ActorPolicyWrapper that wraps an actor network and uses its forward function as the act method', 'build an ActorDQN wrapper that extracts action output from an actor network for DQN predictor compatibility', 'build a DiscreteDQN trainer with Q-network, target network, and optional CPE reward networks', 'create a TorchScript serving module from a trained DiscreteDQN trainer for inference', 'build a reward prediction module using the CPE network and BanditRewardNetPredictorWrapper', 'get a DiscreteDQNReporter instance configured with action names and target action distribution', 'build a binary difference scorer module for two-action DiscreteDQN models', 'build a DiscreteQRDQN trainer with DuelingQuantile network and CPE reward network for quantile regression DQN training', 'build a TorchScript predictor module from a trained QRDQN trainer for serving quantile DQN predictions', 'create a DiscreteQRDQN model with custom trainer parameters and DuelingQuantile net builder for multi-action RL', 'review the DiscreteQRDQN post init validation that enforces at least 2 actions and minibatch size divisible by 8', 'summarize the DiscreteQRDQN class that extends DiscreteDQNBase with quantile regression DQN training and CPE evaluation support']
```

Usage

```
{'build_discrete_dqn_trainer': 'build a DiscreteDQN trainer with Q-network, target network, and optional CPE reward networks', 'create_discrete_dqn_serving_module': 'create a TorchScript serving module from a trained DiscreteDQN trainer for inference', 'build_discrete_dqn_reward_module': 'build a reward prediction module using the CPE network and BanditRewardNetPredictorWrapper', 'get_discrete_dqn_reporter': 'get a DiscreteDQNReporter instance configured with action names and target action distribution', 'build_discrete_dqn_binary_scorer': 'build a binary difference scorer module for two-action DiscreteDQN models'}
```

## File: facebookresearch_reagent/reagent/model_managers/discrete/discrete_qrdqn.py

Prompts

```
['build a C51DQN trainer with a categorical Q-network for discrete action reinforcement learning', 'build a TorchScript predictor module from a trained C51DQN model for serving', 'create a DiscreteC51DQN dataclass instance with custom trainer parameters and network builders', 'review the DiscreteC51DQN post-init validation that enforces at least 2 actions and minibatch divisibility', 'summarize how the Categorical net builder constructs Q-networks with num_atoms, qmin, and qmax parameters', 'build a DiscreteCRRTrainer with actor, critic, and optional reward networks for counterfactual regret minimization', 'create an online actor critic policy from a DiscreteCRRTrainer for serving or training mode', 'build serving modules including default_model, dqn, actor_dqn, and optional binary_difference_scorer for inference', 'create an ActorPolicyWrapper that wraps an actor network and uses its forward function as the act method', 'build an ActorDQN wrapper that extracts action output from an actor network for DQN predictor compatibility', 'build a DiscreteDQN trainer with Q-network, target network, and optional CPE reward networks', 'create a TorchScript serving module from a trained DiscreteDQN trainer for inference', 'build a reward prediction module using the CPE network and BanditRewardNetPredictorWrapper', 'get a DiscreteDQNReporter instance configured with action names and target action distribution', 'build a binary difference scorer module for two-action DiscreteDQN models', 'build a DiscreteQRDQN trainer with DuelingQuantile network and CPE reward network for quantile regression DQN training', 'build a TorchScript predictor module from a trained QRDQN trainer for serving quantile DQN predictions', 'create a DiscreteQRDQN model with custom trainer parameters and DuelingQuantile net builder for multi-action RL', 'review the DiscreteQRDQN post init validation that enforces at least 2 actions and minibatch size divisible by 8', 'summarize the DiscreteQRDQN class that extends DiscreteDQNBase with quantile regression DQN training and CPE evaluation support']
```

Usage

```
{'build_DiscreteQRDQN_trainer': 'build a DiscreteQRDQN trainer with DuelingQuantile network and CPE reward network for quantile regression DQN training', 'build_DiscreteQRDQN_serving_module': 'build a TorchScript predictor module from a trained QRDQN trainer for serving quantile DQN predictions', 'create_DiscreteQRDQN_model': 'create a DiscreteQRDQN model with custom trainer parameters and DuelingQuantile net builder for multi-action RL', 'review_DiscreteQRDQN_post_init': 'review the DiscreteQRDQN post init validation that enforces at least 2 actions and minibatch size divisible by 8', 'summarize_DiscreteQRDQN_class': 'summarize the DiscreteQRDQN class that extends DiscreteDQNBase with quantile regression DQN training and CPE evaluation support'}
```

