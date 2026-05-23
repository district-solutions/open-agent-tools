# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/test/world_model/simulated_world_model.py

Prompts

```
['create a SimulatedWorldModel with specified action_dim, state_dim, num_gaussians, and LSTM hidden layer parameters', 'run forward pass on SimulatedWorldModel with action and state tensors to get mixture means and rewards', 'initialize the LSTM and GMM linear layers inside SimulatedWorldModel with configured dimensions', 'initialize all LSTM and linear layer weights with normal distribution using a fixed random seed', 'initialize the LSTM hidden state tensors to zeros for a given batch size', 'test the gmm_loss function by computing Gaussian Mixture Model loss against manually calculated probabilities', 'test the MDNRNN trainer by simulating episodes in a world model and training over multiple epochs', 'create a Gaussian Mixture Model loss computation from mus, sigmas, logpi, and batch tensors', 'build an MDNRNNTrainer with a MemoryNetwork and parameters to train on replay buffer samples', 'review the TestMDNRNN unittest class and its test_gmm_loss and test_mdnrnn_simulate_world methods', 'create training and evaluation DataLoaders from StringGame-v0 replay buffer data for seq2reward model training', 'train a Seq2RewardNetwork model using PyTorch Lightning on provided training data with configurable learning rate and epochs', 'evaluate a trained seq2reward model on evaluation data and return initial state Q values, MSE loss, and action distribution', 'train a compress model using FullyConnected network to approximate a trained seq2reward model on provided data', 'generate all action permutations for a given sequence length and number of actions as a tensor']
```

Usage

```
{'create_SimulatedWorldModel': 'create a SimulatedWorldModel with specified action_dim, state_dim, num_gaussians, and LSTM hidden layer parameters', 'run_forward_SimulatedWorldModel': 'run forward pass on SimulatedWorldModel with action and state tensors to get mixture means and rewards', 'init_lstm_SimulatedWorldModel': 'initialize the LSTM and GMM linear layers inside SimulatedWorldModel with configured dimensions', 'init_weight_SimulatedWorldModel': 'initialize all LSTM and linear layer weights with normal distribution using a fixed random seed', 'init_hidden_SimulatedWorldModel': 'initialize the LSTM hidden state tensors to zeros for a given batch size'}
```

## File: facebookresearch_reagent/reagent/test/world_model/test_mdnrnn.py

Prompts

```
['create a SimulatedWorldModel with specified action_dim, state_dim, num_gaussians, and LSTM hidden layer parameters', 'run forward pass on SimulatedWorldModel with action and state tensors to get mixture means and rewards', 'initialize the LSTM and GMM linear layers inside SimulatedWorldModel with configured dimensions', 'initialize all LSTM and linear layer weights with normal distribution using a fixed random seed', 'initialize the LSTM hidden state tensors to zeros for a given batch size', 'test the gmm_loss function by computing Gaussian Mixture Model loss against manually calculated probabilities', 'test the MDNRNN trainer by simulating episodes in a world model and training over multiple epochs', 'create a Gaussian Mixture Model loss computation from mus, sigmas, logpi, and batch tensors', 'build an MDNRNNTrainer with a MemoryNetwork and parameters to train on replay buffer samples', 'review the TestMDNRNN unittest class and its test_gmm_loss and test_mdnrnn_simulate_world methods', 'create training and evaluation DataLoaders from StringGame-v0 replay buffer data for seq2reward model training', 'train a Seq2RewardNetwork model using PyTorch Lightning on provided training data with configurable learning rate and epochs', 'evaluate a trained seq2reward model on evaluation data and return initial state Q values, MSE loss, and action distribution', 'train a compress model using FullyConnected network to approximate a trained seq2reward model on provided data', 'generate all action permutations for a given sequence length and number of actions as a tensor']
```

Usage

```
{'test_gmm_loss': 'test the gmm_loss function by computing Gaussian Mixture Model loss against manually calculated probabilities', 'test_mdnrnn_simulate_world': 'test the MDNRNN trainer by simulating episodes in a world model and training over multiple epochs', 'create_gmm_loss': 'create a Gaussian Mixture Model loss computation from mus, sigmas, logpi, and batch tensors', 'build_mdnrnn_trainer': 'build an MDNRNNTrainer with a MemoryNetwork and parameters to train on replay buffer samples', 'review_TestMDNRNN': 'review the TestMDNRNN unittest class and its test_gmm_loss and test_mdnrnn_simulate_world methods'}
```

## File: facebookresearch_reagent/reagent/test/world_model/test_seq2reward.py

Prompts

```
['create a SimulatedWorldModel with specified action_dim, state_dim, num_gaussians, and LSTM hidden layer parameters', 'run forward pass on SimulatedWorldModel with action and state tensors to get mixture means and rewards', 'initialize the LSTM and GMM linear layers inside SimulatedWorldModel with configured dimensions', 'initialize all LSTM and linear layer weights with normal distribution using a fixed random seed', 'initialize the LSTM hidden state tensors to zeros for a given batch size', 'test the gmm_loss function by computing Gaussian Mixture Model loss against manually calculated probabilities', 'test the MDNRNN trainer by simulating episodes in a world model and training over multiple epochs', 'create a Gaussian Mixture Model loss computation from mus, sigmas, logpi, and batch tensors', 'build an MDNRNNTrainer with a MemoryNetwork and parameters to train on replay buffer samples', 'review the TestMDNRNN unittest class and its test_gmm_loss and test_mdnrnn_simulate_world methods', 'create training and evaluation DataLoaders from StringGame-v0 replay buffer data for seq2reward model training', 'train a Seq2RewardNetwork model using PyTorch Lightning on provided training data with configurable learning rate and epochs', 'evaluate a trained seq2reward model on evaluation data and return initial state Q values, MSE loss, and action distribution', 'train a compress model using FullyConnected network to approximate a trained seq2reward model on provided data', 'generate all action permutations for a given sequence length and number of actions as a tensor']
```

Usage

```
{'create_string_game_data': 'create training and evaluation DataLoaders from StringGame-v0 replay buffer data for seq2reward model training', 'train_seq2reward_model': 'train a Seq2RewardNetwork model using PyTorch Lightning on provided training data with configurable learning rate and epochs', 'eval_seq2reward_model': 'evaluate a trained seq2reward model on evaluation data and return initial state Q values, MSE loss, and action distribution', 'train_seq2reward_compress_model': 'train a compress model using FullyConnected network to approximate a trained seq2reward model on provided data', 'gen_permutations': 'generate all action permutations for a given sequence length and number of actions as a tensor'}
```

