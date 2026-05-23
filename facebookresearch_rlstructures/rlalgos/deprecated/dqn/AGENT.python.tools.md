# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/deprecated/dqn/agent.py

Prompts

```
['create a QAgent with a model and number of actions for discrete action selection', 'run one step of the QAgent to select an epsilon-greedy action from observations', 'update the QAgent model by loading a new state dictionary', 'create a QMLP neural network with linear layers for action scoring from observations', 'create a DQMLP network with dueling architecture separating value and advantage streams', 'create a ReplayBuffer with capacity N to store TemporalDictTensor transitions for experience replay', 'push trajectory data into the ReplayBuffer using the push method to add transitions', 'sample n random transitions from the ReplayBuffer using the sample method for training batches', 'run the DQN algorithm with config, create_env, and create_agent to train a dueling DQN agent', 'compute the DQN loss by sampling transitions and calculating TD error between target and current Q-values', 'run the DQN experiment on CartPole using Hydra config and the Experiment class', 'create a Gym environment from a config dict specifying the environment name', 'create a list of Gym environments wrapped with TimeLimit and GymEnvInf or GymEnv', 'create a QAgent instance with a given model and number of actions', 'flatten a nested DictConfig or dict into a flat dict with slash-separated keys']
```

Usage

```
{'create_QAgent': 'create a QAgent with a model and number of actions for discrete action selection', 'run_QAgent_call': 'run one step of the QAgent to select an epsilon-greedy action from observations', 'update_QAgent_model': 'update the QAgent model by loading a new state dictionary', 'create_QMLP_network': 'create a QMLP neural network with linear layers for action scoring from observations', 'create_DQMLP_network': 'create a DQMLP network with dueling architecture separating value and advantage streams'}
```

## File: facebookresearch_rlstructures/rlalgos/deprecated/dqn/duelling_dqn.py

Prompts

```
['create a QAgent with a model and number of actions for discrete action selection', 'run one step of the QAgent to select an epsilon-greedy action from observations', 'update the QAgent model by loading a new state dictionary', 'create a QMLP neural network with linear layers for action scoring from observations', 'create a DQMLP network with dueling architecture separating value and advantage streams', 'create a ReplayBuffer with capacity N to store TemporalDictTensor transitions for experience replay', 'push trajectory data into the ReplayBuffer using the push method to add transitions', 'sample n random transitions from the ReplayBuffer using the sample method for training batches', 'run the DQN algorithm with config, create_env, and create_agent to train a dueling DQN agent', 'compute the DQN loss by sampling transitions and calculating TD error between target and current Q-values', 'run the DQN experiment on CartPole using Hydra config and the Experiment class', 'create a Gym environment from a config dict specifying the environment name', 'create a list of Gym environments wrapped with TimeLimit and GymEnvInf or GymEnv', 'create a QAgent instance with a given model and number of actions', 'flatten a nested DictConfig or dict into a flat dict with slash-separated keys']
```

Usage

```
{'create_ReplayBuffer': 'create a ReplayBuffer with capacity N to store TemporalDictTensor transitions for experience replay', 'push_trajectories_to_ReplayBuffer': 'push trajectory data into the ReplayBuffer using the push method to add transitions', 'sample_from_ReplayBuffer': 'sample n random transitions from the ReplayBuffer using the sample method for training batches', 'run_DQN_training': 'run the DQN algorithm with config, create_env, and create_agent to train a dueling DQN agent', 'compute_DQN_loss': 'compute the DQN loss by sampling transitions and calculating TD error between target and current Q-values'}
```

## File: facebookresearch_rlstructures/rlalgos/deprecated/dqn/run_q_cartpole.py

Prompts

```
['create a QAgent with a model and number of actions for discrete action selection', 'run one step of the QAgent to select an epsilon-greedy action from observations', 'update the QAgent model by loading a new state dictionary', 'create a QMLP neural network with linear layers for action scoring from observations', 'create a DQMLP network with dueling architecture separating value and advantage streams', 'create a ReplayBuffer with capacity N to store TemporalDictTensor transitions for experience replay', 'push trajectory data into the ReplayBuffer using the push method to add transitions', 'sample n random transitions from the ReplayBuffer using the sample method for training batches', 'run the DQN algorithm with config, create_env, and create_agent to train a dueling DQN agent', 'compute the DQN loss by sampling transitions and calculating TD error between target and current Q-values', 'run the DQN experiment on CartPole using Hydra config and the Experiment class', 'create a Gym environment from a config dict specifying the environment name', 'create a list of Gym environments wrapped with TimeLimit and GymEnvInf or GymEnv', 'create a QAgent instance with a given model and number of actions', 'flatten a nested DictConfig or dict into a flat dict with slash-separated keys']
```

Usage

```
{'run_dqn_cartpole_experiment': 'run the DQN experiment on CartPole using Hydra config and the Experiment class', 'create_gym_environment': 'create a Gym environment from a config dict specifying the environment name', 'create_env_wrapper': 'create a list of Gym environments wrapped with TimeLimit and GymEnvInf or GymEnv', 'create_q_agent': 'create a QAgent instance with a given model and number of actions', 'flatten_dict_config': 'flatten a nested DictConfig or dict into a flat dict with slash-separated keys'}
```

