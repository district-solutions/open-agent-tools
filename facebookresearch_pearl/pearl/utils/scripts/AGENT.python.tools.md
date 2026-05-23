# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/utils/scripts/benchmark.py

Prompts

```
['run multiple PEARL reinforcement learning experiments in parallel using torch multiprocessing', 'evaluate a single RL method run in a gym environment with a PearlAgent', 'generate learning curve plots with mean and standard error for benchmark results', 'run the Atari benchmark experiments using the benchmark_atari configuration', 'run reward-constrained DDPG, TD3, or SAC benchmarks on MuJoCo environments', 'create a wrapped GymEnvironment from an env name string like CartPole-v0 or PongNoFrameskip-v4', 'use the DQN_method config dictionary to set up Deep Q-Learning with epsilon-greedy exploration', 'use the PPO_method config dictionary to set up Proximal Policy Optimization with 50 training rounds', 'use the SAC_method config dictionary to set up Soft Actor-Critic with entropy coefficient 0.1', 'iterate over all_online_discrete_control_methods to benchmark DQN, PPO, SAC, and other discrete RL algorithms', 'run an offline RL benchmark using Implicit Q Learning on a Gym environment like HalfCheetah', 'evaluate an offline RL agent by training on collected data and running evaluation episodes', 'get episode returns of a random agent to compute baseline for normalized offline RL scores', 'create offline RL training data by collecting transitions from a data collection agent in an environment', 'calculate the normalized score comparing offline agent returns against random and data collection agent baselines', 'run the script to train DQN and SARSA agents on CartPole-v1 and generate a comparison plot', 'run the moving_average function to smooth episode return data with a configurable window size', 'run online learning with a PearlAgent using DeepQLearning policy learner and BasicReplayBuffer on CartPole-v1', 'run online learning with a PearlAgent using DeepSARSA policy learner and SARSAReplayBuffer on CartPole-v1', 'review the main function that trains DQN and SARSA agents and saves a comparison figure']
```

Usage

```
{'run_benchmark_experiments': 'run multiple PEARL reinforcement learning experiments in parallel using torch multiprocessing', 'evaluate_single_experiment': 'evaluate a single RL method run in a gym environment with a PearlAgent', 'generate_learning_curve_plots': 'generate learning curve plots with mean and standard error for benchmark results', 'run_atari_benchmark': 'run the Atari benchmark experiments using the benchmark_atari configuration', 'run_reward_constrained_benchmarks': 'run reward-constrained DDPG, TD3, or SAC benchmarks on MuJoCo environments'}
```

## File: facebookresearch_pearl/pearl/utils/scripts/benchmark_config.py

Prompts

```
['run multiple PEARL reinforcement learning experiments in parallel using torch multiprocessing', 'evaluate a single RL method run in a gym environment with a PearlAgent', 'generate learning curve plots with mean and standard error for benchmark results', 'run the Atari benchmark experiments using the benchmark_atari configuration', 'run reward-constrained DDPG, TD3, or SAC benchmarks on MuJoCo environments', 'create a wrapped GymEnvironment from an env name string like CartPole-v0 or PongNoFrameskip-v4', 'use the DQN_method config dictionary to set up Deep Q-Learning with epsilon-greedy exploration', 'use the PPO_method config dictionary to set up Proximal Policy Optimization with 50 training rounds', 'use the SAC_method config dictionary to set up Soft Actor-Critic with entropy coefficient 0.1', 'iterate over all_online_discrete_control_methods to benchmark DQN, PPO, SAC, and other discrete RL algorithms', 'run an offline RL benchmark using Implicit Q Learning on a Gym environment like HalfCheetah', 'evaluate an offline RL agent by training on collected data and running evaluation episodes', 'get episode returns of a random agent to compute baseline for normalized offline RL scores', 'create offline RL training data by collecting transitions from a data collection agent in an environment', 'calculate the normalized score comparing offline agent returns against random and data collection agent baselines', 'run the script to train DQN and SARSA agents on CartPole-v1 and generate a comparison plot', 'run the moving_average function to smooth episode return data with a configurable window size', 'run online learning with a PearlAgent using DeepQLearning policy learner and BasicReplayBuffer on CartPole-v1', 'run online learning with a PearlAgent using DeepSARSA policy learner and SARSAReplayBuffer on CartPole-v1', 'review the main function that trains DQN and SARSA agents and saves a comparison figure']
```

Usage

```
{'get_env': 'create a wrapped GymEnvironment from an env name string like CartPole-v0 or PongNoFrameskip-v4', 'DQN_method': 'use the DQN_method config dictionary to set up Deep Q-Learning with epsilon-greedy exploration', 'PPO_method': 'use the PPO_method config dictionary to set up Proximal Policy Optimization with 50 training rounds', 'SAC_method': 'use the SAC_method config dictionary to set up Soft Actor-Critic with entropy coefficient 0.1', 'all_online_discrete_control_methods': 'iterate over all_online_discrete_control_methods to benchmark DQN, PPO, SAC, and other discrete RL algorithms'}
```

## File: facebookresearch_pearl/pearl/utils/scripts/benchmark_offline_rl.py

Prompts

```
['run multiple PEARL reinforcement learning experiments in parallel using torch multiprocessing', 'evaluate a single RL method run in a gym environment with a PearlAgent', 'generate learning curve plots with mean and standard error for benchmark results', 'run the Atari benchmark experiments using the benchmark_atari configuration', 'run reward-constrained DDPG, TD3, or SAC benchmarks on MuJoCo environments', 'create a wrapped GymEnvironment from an env name string like CartPole-v0 or PongNoFrameskip-v4', 'use the DQN_method config dictionary to set up Deep Q-Learning with epsilon-greedy exploration', 'use the PPO_method config dictionary to set up Proximal Policy Optimization with 50 training rounds', 'use the SAC_method config dictionary to set up Soft Actor-Critic with entropy coefficient 0.1', 'iterate over all_online_discrete_control_methods to benchmark DQN, PPO, SAC, and other discrete RL algorithms', 'run an offline RL benchmark using Implicit Q Learning on a Gym environment like HalfCheetah', 'evaluate an offline RL agent by training on collected data and running evaluation episodes', 'get episode returns of a random agent to compute baseline for normalized offline RL scores', 'create offline RL training data by collecting transitions from a data collection agent in an environment', 'calculate the normalized score comparing offline agent returns against random and data collection agent baselines', 'run the script to train DQN and SARSA agents on CartPole-v1 and generate a comparison plot', 'run the moving_average function to smooth episode return data with a configurable window size', 'run online learning with a PearlAgent using DeepQLearning policy learner and BasicReplayBuffer on CartPole-v1', 'run online learning with a PearlAgent using DeepSARSA policy learner and SARSAReplayBuffer on CartPole-v1', 'review the main function that trains DQN and SARSA agents and saves a comparison figure']
```

Usage

```
{'run_offline_rl_benchmark': 'run an offline RL benchmark using Implicit Q Learning on a Gym environment like HalfCheetah', 'evaluate_offline_rl_agent': 'evaluate an offline RL agent by training on collected data and running evaluation episodes', 'get_random_agent_returns': 'get episode returns of a random agent to compute baseline for normalized offline RL scores', 'create_offline_data': 'create offline RL training data by collecting transitions from a data collection agent in an environment', 'calculate_normalized_score': 'calculate the normalized score comparing offline agent returns against random and data collection agent baselines'}
```

## File: facebookresearch_pearl/pearl/utils/scripts/figure_gen.py

Prompts

```
['run multiple PEARL reinforcement learning experiments in parallel using torch multiprocessing', 'evaluate a single RL method run in a gym environment with a PearlAgent', 'generate learning curve plots with mean and standard error for benchmark results', 'run the Atari benchmark experiments using the benchmark_atari configuration', 'run reward-constrained DDPG, TD3, or SAC benchmarks on MuJoCo environments', 'create a wrapped GymEnvironment from an env name string like CartPole-v0 or PongNoFrameskip-v4', 'use the DQN_method config dictionary to set up Deep Q-Learning with epsilon-greedy exploration', 'use the PPO_method config dictionary to set up Proximal Policy Optimization with 50 training rounds', 'use the SAC_method config dictionary to set up Soft Actor-Critic with entropy coefficient 0.1', 'iterate over all_online_discrete_control_methods to benchmark DQN, PPO, SAC, and other discrete RL algorithms', 'run an offline RL benchmark using Implicit Q Learning on a Gym environment like HalfCheetah', 'evaluate an offline RL agent by training on collected data and running evaluation episodes', 'get episode returns of a random agent to compute baseline for normalized offline RL scores', 'create offline RL training data by collecting transitions from a data collection agent in an environment', 'calculate the normalized score comparing offline agent returns against random and data collection agent baselines', 'run the script to train DQN and SARSA agents on CartPole-v1 and generate a comparison plot', 'run the moving_average function to smooth episode return data with a configurable window size', 'run online learning with a PearlAgent using DeepQLearning policy learner and BasicReplayBuffer on CartPole-v1', 'run online learning with a PearlAgent using DeepSARSA policy learner and SARSAReplayBuffer on CartPole-v1', 'review the main function that trains DQN and SARSA agents and saves a comparison figure']
```

Usage

```
{'run_figure_gen': 'run the script to train DQN and SARSA agents on CartPole-v1 and generate a comparison plot', 'run_moving_average': 'run the moving_average function to smooth episode return data with a configurable window size', 'run_online_learning_dqn': 'run online learning with a PearlAgent using DeepQLearning policy learner and BasicReplayBuffer on CartPole-v1', 'run_online_learning_sarsa': 'run online learning with a PearlAgent using DeepSARSA policy learner and SARSAReplayBuffer on CartPole-v1', 'review_main': 'review the main function that trains DQN and SARSA agents and saves a comparison figure'}
```

