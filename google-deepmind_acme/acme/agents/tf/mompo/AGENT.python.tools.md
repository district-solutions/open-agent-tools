# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/mompo/agent_distributed.py

Prompts

```
['build a multi-objective MPO distributed agent topology using Launchpad with replay, learner, and actor nodes', 'create a multi-objective MPO learner with online and target networks for policy and critic training', 'create a stochastic behavior policy actor that interacts with the environment and adds transitions to replay', 'create a deterministic policy evaluator that assesses agent performance against the environment', 'configure a Reverb replay table with uniform sampling and FIFO removal for N-step transitions', 'create policy and critic networks with configurable layer sizes and distributional critic for MPO agent', 'create a cartpole balance environment wrapped in single precision for reinforcement learning', 'compute Q-values for the action norm objective using L2 norm of action samples', 'define reward and Q-value objectives for multi-objective policy learning with task reward and action norm', 'run integration test for distributed multi-objective MPO agent with parameterized critic types', 'create a Q-value objective that computes the L2 norm of action samples for regularization', 'define reward and Q-value objectives for the multi-objective MPO policy to learn', 'test the multi-objective MPO agent with distributional or vanilla critic in a fake environment', 'run a task reward function that returns the environment reward with stop gradient applied', 'create a RewardObjective dataclass with a name and reward_fn for multi-objective MPO learning', 'create a QValueObjective dataclass with a name and qvalue_fn for direct Q-value computation', 'build a MultiObjectiveMPOLearner with reward objectives, critic network, policy network, and dataset', 'run a single learning step on the MultiObjectiveMPOLearner to update policy and critic networks', 'compute the TD-learning critic loss and sampled Q-values for non-distributional critics']
```

Usage

```
{'build_distributed_mompo_agent': 'build a multi-objective MPO distributed agent topology using Launchpad with replay, learner, and actor nodes', 'create_mompo_learner': 'create a multi-objective MPO learner with online and target networks for policy and critic training', 'create_mompo_actor': 'create a stochastic behavior policy actor that interacts with the environment and adds transitions to replay', 'create_mompo_evaluator': 'create a deterministic policy evaluator that assesses agent performance against the environment', 'configure_mompo_replay': 'configure a Reverb replay table with uniform sampling and FIFO removal for N-step transitions'}
```

## File: google-deepmind_acme/acme/agents/tf/mompo/agent_distributed_test.py

Prompts

```
['build a multi-objective MPO distributed agent topology using Launchpad with replay, learner, and actor nodes', 'create a multi-objective MPO learner with online and target networks for policy and critic training', 'create a stochastic behavior policy actor that interacts with the environment and adds transitions to replay', 'create a deterministic policy evaluator that assesses agent performance against the environment', 'configure a Reverb replay table with uniform sampling and FIFO removal for N-step transitions', 'create policy and critic networks with configurable layer sizes and distributional critic for MPO agent', 'create a cartpole balance environment wrapped in single precision for reinforcement learning', 'compute Q-values for the action norm objective using L2 norm of action samples', 'define reward and Q-value objectives for multi-objective policy learning with task reward and action norm', 'run integration test for distributed multi-objective MPO agent with parameterized critic types', 'create a Q-value objective that computes the L2 norm of action samples for regularization', 'define reward and Q-value objectives for the multi-objective MPO policy to learn', 'test the multi-objective MPO agent with distributional or vanilla critic in a fake environment', 'run a task reward function that returns the environment reward with stop gradient applied', 'create a RewardObjective dataclass with a name and reward_fn for multi-objective MPO learning', 'create a QValueObjective dataclass with a name and qvalue_fn for direct Q-value computation', 'build a MultiObjectiveMPOLearner with reward objectives, critic network, policy network, and dataset', 'run a single learning step on the MultiObjectiveMPOLearner to update policy and critic networks', 'compute the TD-learning critic loss and sampled Q-values for non-distributional critics']
```

Usage

```
{'build_mompo_networks': 'create policy and critic networks with configurable layer sizes and distributional critic for MPO agent', 'create_environment_cartpole': 'create a cartpole balance environment wrapped in single precision for reinforcement learning', 'compute_action_norm_objective': 'compute Q-values for the action norm objective using L2 norm of action samples', 'define_multi_objective_rewards': 'define reward and Q-value objectives for multi-objective policy learning with task reward and action norm', 'test_distributed_mompo_agent': 'run integration test for distributed multi-objective MPO agent with parameterized critic types'}
```

## File: google-deepmind_acme/acme/agents/tf/mompo/agent_test.py

Prompts

```
['build a multi-objective MPO distributed agent topology using Launchpad with replay, learner, and actor nodes', 'create a multi-objective MPO learner with online and target networks for policy and critic training', 'create a stochastic behavior policy actor that interacts with the environment and adds transitions to replay', 'create a deterministic policy evaluator that assesses agent performance against the environment', 'configure a Reverb replay table with uniform sampling and FIFO removal for N-step transitions', 'create policy and critic networks with configurable layer sizes and distributional critic for MPO agent', 'create a cartpole balance environment wrapped in single precision for reinforcement learning', 'compute Q-values for the action norm objective using L2 norm of action samples', 'define reward and Q-value objectives for multi-objective policy learning with task reward and action norm', 'run integration test for distributed multi-objective MPO agent with parameterized critic types', 'create a Q-value objective that computes the L2 norm of action samples for regularization', 'define reward and Q-value objectives for the multi-objective MPO policy to learn', 'test the multi-objective MPO agent with distributional or vanilla critic in a fake environment', 'run a task reward function that returns the environment reward with stop gradient applied', 'create a RewardObjective dataclass with a name and reward_fn for multi-objective MPO learning', 'create a QValueObjective dataclass with a name and qvalue_fn for direct Q-value computation', 'build a MultiObjectiveMPOLearner with reward objectives, critic network, policy network, and dataset', 'run a single learning step on the MultiObjectiveMPOLearner to update policy and critic networks', 'compute the TD-learning critic loss and sampled Q-values for non-distributional critics']
```

Usage

```
{'build_mompo_networks': 'build policy and critic networks for the multi-objective MPO agent using sonnet and TensorFlow', 'create_action_norm_objective': 'create a Q-value objective that computes the L2 norm of action samples for regularization', 'define_mompo_objectives': 'define reward and Q-value objectives for the multi-objective MPO policy to learn', 'test_mompo_agent': 'test the multi-objective MPO agent with distributional or vanilla critic in a fake environment', 'run_task_reward_function': 'run a task reward function that returns the environment reward with stop gradient applied'}
```

## File: google-deepmind_acme/acme/agents/tf/mompo/learning.py

Prompts

```
['build a multi-objective MPO distributed agent topology using Launchpad with replay, learner, and actor nodes', 'create a multi-objective MPO learner with online and target networks for policy and critic training', 'create a stochastic behavior policy actor that interacts with the environment and adds transitions to replay', 'create a deterministic policy evaluator that assesses agent performance against the environment', 'configure a Reverb replay table with uniform sampling and FIFO removal for N-step transitions', 'create policy and critic networks with configurable layer sizes and distributional critic for MPO agent', 'create a cartpole balance environment wrapped in single precision for reinforcement learning', 'compute Q-values for the action norm objective using L2 norm of action samples', 'define reward and Q-value objectives for multi-objective policy learning with task reward and action norm', 'run integration test for distributed multi-objective MPO agent with parameterized critic types', 'create a Q-value objective that computes the L2 norm of action samples for regularization', 'define reward and Q-value objectives for the multi-objective MPO policy to learn', 'test the multi-objective MPO agent with distributional or vanilla critic in a fake environment', 'run a task reward function that returns the environment reward with stop gradient applied', 'create a RewardObjective dataclass with a name and reward_fn for multi-objective MPO learning', 'create a QValueObjective dataclass with a name and qvalue_fn for direct Q-value computation', 'build a MultiObjectiveMPOLearner with reward objectives, critic network, policy network, and dataset', 'run a single learning step on the MultiObjectiveMPOLearner to update policy and critic networks', 'compute the TD-learning critic loss and sampled Q-values for non-distributional critics']
```

Usage

```
{'create_reward_objective': 'create a RewardObjective dataclass with a name and reward_fn for multi-objective MPO learning', 'create_qvalue_objective': 'create a QValueObjective dataclass with a name and qvalue_fn for direct Q-value computation', 'build_multi_objective_mpo_learner': 'build a MultiObjectiveMPOLearner with reward objectives, critic network, policy network, and dataset', 'run_learner_step': 'run a single learning step on the MultiObjectiveMPOLearner to update policy and critic networks', 'compute_critic_loss': 'compute the TD-learning critic loss and sampled Q-values for non-distributional critics'}
```

