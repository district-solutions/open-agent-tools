# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/gym/policies/policy.py

Prompts

```
['create a Policy instance by composing a Scorer and Sampler to generate actions', 'call act on a Policy with an observation to sample an action via scorer and sampler', 'call act on a Policy with an observation and possible_actions_mask to constrain sampled actions', 'review the Policy class that composes a Scorer and Sampler to produce ActorOutput actions', 'summarize the Policy act method that scores observations and samples actions for the replay buffer', 'create a Policy from a serving module for DiscreteDQN, Actor, or ParametricDQN predictor wrappers', 'build a DiscreteDQNPredictorPolicy with a wrapped DQN predictor and optional softmax sampling via RLParameters', 'build an ActorPredictorPolicy that selects actions using an unwrapped actor predictor model', 'run the DiscreteDQNPredictorPolicy act method to score and sample an action from observation features', 'run the ActorPredictorPolicy act method to get an action and log probability from observation features', 'create a random policy for a gym environment using make_random_policy_for_env', 'create a DiscreteRandomPolicy for a gym environment with a discrete action space', 'create a ContinuousRandomPolicy for a gym environment with a continuous Box action space', 'create a MultiDiscreteRandomPolicy for a gym environment with a MultiDiscrete action space', 'sample a random action from a random policy using the act method']
```

Usage

```
{'create_policy_with_scorer_and_sampler': 'create a Policy instance by composing a Scorer and Sampler to generate actions', 'act_policy_on_observation': 'call act on a Policy with an observation to sample an action via scorer and sampler', 'act_policy_with_action_mask': 'call act on a Policy with an observation and possible_actions_mask to constrain sampled actions', 'review_policy_class': 'review the Policy class that composes a Scorer and Sampler to produce ActorOutput actions', 'summarize_policy_act_method': 'summarize the Policy act method that scores observations and samples actions for the replay buffer'}
```

## File: facebookresearch_reagent/reagent/gym/policies/predictor_policies.py

Prompts

```
['create a Policy instance by composing a Scorer and Sampler to generate actions', 'call act on a Policy with an observation to sample an action via scorer and sampler', 'call act on a Policy with an observation and possible_actions_mask to constrain sampled actions', 'review the Policy class that composes a Scorer and Sampler to produce ActorOutput actions', 'summarize the Policy act method that scores observations and samples actions for the replay buffer', 'create a Policy from a serving module for DiscreteDQN, Actor, or ParametricDQN predictor wrappers', 'build a DiscreteDQNPredictorPolicy with a wrapped DQN predictor and optional softmax sampling via RLParameters', 'build an ActorPredictorPolicy that selects actions using an unwrapped actor predictor model', 'run the DiscreteDQNPredictorPolicy act method to score and sample an action from observation features', 'run the ActorPredictorPolicy act method to get an action and log probability from observation features', 'create a random policy for a gym environment using make_random_policy_for_env', 'create a DiscreteRandomPolicy for a gym environment with a discrete action space', 'create a ContinuousRandomPolicy for a gym environment with a continuous Box action space', 'create a MultiDiscreteRandomPolicy for a gym environment with a MultiDiscrete action space', 'sample a random action from a random policy using the act method']
```

Usage

```
{'create_predictor_policy_from_model': 'create a Policy from a serving module for DiscreteDQN, Actor, or ParametricDQN predictor wrappers', 'build_discrete_dqn_predictor_policy': 'build a DiscreteDQNPredictorPolicy with a wrapped DQN predictor and optional softmax sampling via RLParameters', 'build_actor_predictor_policy': 'build an ActorPredictorPolicy that selects actions using an unwrapped actor predictor model', 'run_discrete_dqn_act': 'run the DiscreteDQNPredictorPolicy act method to score and sample an action from observation features', 'run_actor_predictor_act': 'run the ActorPredictorPolicy act method to get an action and log probability from observation features'}
```

## File: facebookresearch_reagent/reagent/gym/policies/random_policies.py

Prompts

```
['create a Policy instance by composing a Scorer and Sampler to generate actions', 'call act on a Policy with an observation to sample an action via scorer and sampler', 'call act on a Policy with an observation and possible_actions_mask to constrain sampled actions', 'review the Policy class that composes a Scorer and Sampler to produce ActorOutput actions', 'summarize the Policy act method that scores observations and samples actions for the replay buffer', 'create a Policy from a serving module for DiscreteDQN, Actor, or ParametricDQN predictor wrappers', 'build a DiscreteDQNPredictorPolicy with a wrapped DQN predictor and optional softmax sampling via RLParameters', 'build an ActorPredictorPolicy that selects actions using an unwrapped actor predictor model', 'run the DiscreteDQNPredictorPolicy act method to score and sample an action from observation features', 'run the ActorPredictorPolicy act method to get an action and log probability from observation features', 'create a random policy for a gym environment using make_random_policy_for_env', 'create a DiscreteRandomPolicy for a gym environment with a discrete action space', 'create a ContinuousRandomPolicy for a gym environment with a continuous Box action space', 'create a MultiDiscreteRandomPolicy for a gym environment with a MultiDiscrete action space', 'sample a random action from a random policy using the act method']
```

Usage

```
{'create_random_policy_for_env': 'create a random policy for a gym environment using make_random_policy_for_env', 'create_discrete_random_policy': 'create a DiscreteRandomPolicy for a gym environment with a discrete action space', 'create_continuous_random_policy': 'create a ContinuousRandomPolicy for a gym environment with a continuous Box action space', 'create_multidiscrete_random_policy': 'create a MultiDiscreteRandomPolicy for a gym environment with a MultiDiscrete action space', 'act_random_policy': 'sample a random action from a random policy using the act method'}
```

