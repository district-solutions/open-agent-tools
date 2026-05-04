# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/dmpo/agent_distributed.py

Prompts

```
['build a distributed distributional MPO agent topology using the build method with environment and network factories', 'create a Reverb replay table with uniform sampling and FIFO removal for the DMPO agent', 'create a distributional MPO learner with online and target networks connected to a Reverb dataset', 'create a feed-forward actor with a stochastic policy network and N-step transition adder for replay', 'create an evaluator with a stochastic mean head policy network for evaluating agent performance', 'create a network factory function that returns policy and critic networks with LayerNormMLP and DiscreteValuedHead', 'test the distributed DMPO agent by launching it with launchpad and stepping the learner', 'build a launchpad program from the distributed agent using the build method', 'run multiple steps on the learner handle obtained from the distributed agent program', 'create policy and critic Sonnet networks for the DMPO agent using make_networks with configurable layer sizes', 'run the DMPOTest test_dmpo method to verify the DistributionalMPO agent works end to end', 'build a fake continuous environment with fakes.ContinuousEnvironment for testing the DMPO agent', 'construct an acme EnvironmentLoop with a DMPO agent and run it for a set number of episodes', 'review the DMPOTest class to understand how the DistributionalMPO agent is configured and tested', 'build a DistributionalMPOLearner with policy and critic networks for reinforcement learning', 'run a learning step on the DistributionalMPOLearner to update policy and critic networks', 'create an MPO policy loss module with custom epsilon and temperature parameters', 'review the target policy and critic network update logic in the learner step', 'summarize how critic and policy gradients are computed and applied with clipping']
```

Usage

```
{'build_distributed_dmpo_agent': 'build a distributed distributional MPO agent topology using the build method with environment and network factories', 'create_replay_storage': 'create a Reverb replay table with uniform sampling and FIFO removal for the DMPO agent', 'create_learner': 'create a distributional MPO learner with online and target networks connected to a Reverb dataset', 'create_actor': 'create a feed-forward actor with a stochastic policy network and N-step transition adder for replay', 'create_evaluator': 'create an evaluator with a stochastic mean head policy network for evaluating agent performance'}
```

## File: google-deepmind_acme/acme/agents/tf/dmpo/agent_distributed_test.py

Prompts

```
['build a distributed distributional MPO agent topology using the build method with environment and network factories', 'create a Reverb replay table with uniform sampling and FIFO removal for the DMPO agent', 'create a distributional MPO learner with online and target networks connected to a Reverb dataset', 'create a feed-forward actor with a stochastic policy network and N-step transition adder for replay', 'create an evaluator with a stochastic mean head policy network for evaluating agent performance', 'create a network factory function that returns policy and critic networks with LayerNormMLP and DiscreteValuedHead', 'test the distributed DMPO agent by launching it with launchpad and stepping the learner', 'build a launchpad program from the distributed agent using the build method', 'run multiple steps on the learner handle obtained from the distributed agent program', 'create policy and critic Sonnet networks for the DMPO agent using make_networks with configurable layer sizes', 'run the DMPOTest test_dmpo method to verify the DistributionalMPO agent works end to end', 'build a fake continuous environment with fakes.ContinuousEnvironment for testing the DMPO agent', 'construct an acme EnvironmentLoop with a DMPO agent and run it for a set number of episodes', 'review the DMPOTest class to understand how the DistributionalMPO agent is configured and tested', 'build a DistributionalMPOLearner with policy and critic networks for reinforcement learning', 'run a learning step on the DistributionalMPOLearner to update policy and critic networks', 'create an MPO policy loss module with custom epsilon and temperature parameters', 'review the target policy and critic network update logic in the learner step', 'summarize how critic and policy gradients are computed and applied with clipping']
```

Usage

```
{'build_distributed_dmpo_agent': 'build a DistributedDistributionalMPO agent with environment and network factories for distributed reinforcement learning', 'create_network_factory': 'create a network factory function that returns policy and critic networks with LayerNormMLP and DiscreteValuedHead', 'test_distributed_agent': 'test the distributed DMPO agent by launching it with launchpad and stepping the learner', 'build_agent_program': 'build a launchpad program from the distributed agent using the build method', 'run_learner_steps': 'run multiple steps on the learner handle obtained from the distributed agent program'}
```

## File: google-deepmind_acme/acme/agents/tf/dmpo/agent_test.py

Prompts

```
['build a distributed distributional MPO agent topology using the build method with environment and network factories', 'create a Reverb replay table with uniform sampling and FIFO removal for the DMPO agent', 'create a distributional MPO learner with online and target networks connected to a Reverb dataset', 'create a feed-forward actor with a stochastic policy network and N-step transition adder for replay', 'create an evaluator with a stochastic mean head policy network for evaluating agent performance', 'create a network factory function that returns policy and critic networks with LayerNormMLP and DiscreteValuedHead', 'test the distributed DMPO agent by launching it with launchpad and stepping the learner', 'build a launchpad program from the distributed agent using the build method', 'run multiple steps on the learner handle obtained from the distributed agent program', 'create policy and critic Sonnet networks for the DMPO agent using make_networks with configurable layer sizes', 'run the DMPOTest test_dmpo method to verify the DistributionalMPO agent works end to end', 'build a fake continuous environment with fakes.ContinuousEnvironment for testing the DMPO agent', 'construct an acme EnvironmentLoop with a DMPO agent and run it for a set number of episodes', 'review the DMPOTest class to understand how the DistributionalMPO agent is configured and tested', 'build a DistributionalMPOLearner with policy and critic networks for reinforcement learning', 'run a learning step on the DistributionalMPOLearner to update policy and critic networks', 'create an MPO policy loss module with custom epsilon and temperature parameters', 'review the target policy and critic network update logic in the learner step', 'summarize how critic and policy gradients are computed and applied with clipping']
```

Usage

```
{'build_policy_and_critic_networks': 'create policy and critic Sonnet networks for the DMPO agent using make_networks with configurable layer sizes', 'test_dmpo_agent_integration': 'run the DMPOTest test_dmpo method to verify the DistributionalMPO agent works end to end', 'create_fake_continuous_environment': 'build a fake continuous environment with fakes.ContinuousEnvironment for testing the DMPO agent', 'run_environment_loop_with_dmpo': 'construct an acme EnvironmentLoop with a DMPO agent and run it for a set number of episodes', 'review_dmpo_test_setup': 'review the DMPOTest class to understand how the DistributionalMPO agent is configured and tested'}
```

## File: google-deepmind_acme/acme/agents/tf/dmpo/learning.py

Prompts

```
['build a distributed distributional MPO agent topology using the build method with environment and network factories', 'create a Reverb replay table with uniform sampling and FIFO removal for the DMPO agent', 'create a distributional MPO learner with online and target networks connected to a Reverb dataset', 'create a feed-forward actor with a stochastic policy network and N-step transition adder for replay', 'create an evaluator with a stochastic mean head policy network for evaluating agent performance', 'create a network factory function that returns policy and critic networks with LayerNormMLP and DiscreteValuedHead', 'test the distributed DMPO agent by launching it with launchpad and stepping the learner', 'build a launchpad program from the distributed agent using the build method', 'run multiple steps on the learner handle obtained from the distributed agent program', 'create policy and critic Sonnet networks for the DMPO agent using make_networks with configurable layer sizes', 'run the DMPOTest test_dmpo method to verify the DistributionalMPO agent works end to end', 'build a fake continuous environment with fakes.ContinuousEnvironment for testing the DMPO agent', 'construct an acme EnvironmentLoop with a DMPO agent and run it for a set number of episodes', 'review the DMPOTest class to understand how the DistributionalMPO agent is configured and tested', 'build a DistributionalMPOLearner with policy and critic networks for reinforcement learning', 'run a learning step on the DistributionalMPOLearner to update policy and critic networks', 'create an MPO policy loss module with custom epsilon and temperature parameters', 'review the target policy and critic network update logic in the learner step', 'summarize how critic and policy gradients are computed and applied with clipping']
```

Usage

```
{'build_distributional_mpo_learner': 'build a DistributionalMPOLearner with policy and critic networks for reinforcement learning', 'run_learner_step': 'run a learning step on the DistributionalMPOLearner to update policy and critic networks', 'create_mpo_loss_module': 'create an MPO policy loss module with custom epsilon and temperature parameters', 'review_target_network_updates': 'review the target policy and critic network update logic in the learner step', 'summarize_gradient_computation': 'summarize how critic and policy gradients are computed and applied with clipping'}
```

