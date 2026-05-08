# Agent Python Tools

- repo: facebookresearch/hanabisad
- repo_uri: https://github.com/facebookresearch/hanabi_sad

## File: facebookresearch_hanabisad/pyhanabi/tools/action_matrix.py

Prompts

```
['run the action_matrix CLI tool to generate an action matrix plot from a SAD or OP Hanabi agent model', 'create a replay buffer dataset by running 100 parallel Hanabi game actors with an R2D2 runner', 'analyze a replay buffer dataset to compute a 20x20 joint action probability matrix for two players', 'plot a 20x20 or 30x30 action matrix heatmap with labeled axes for Hanabi actions', 'review the create_dataset function to understand how R2D2 actors and replay buffers are configured for data collection', 'run the python module to convert a PyTorch model to TorchScript format using the --model argument', 'create an LSTMNet TorchScript module with configurable input dimension, hidden dimension, output dimension, and LSTM layers', 'run the LSTMNet forward pass with an observation dictionary containing state, hidden, and cell tensors', 'load a PyTorch state dict, load weights into an LSTMNet model, and save as a TorchScript .sparta file', 'review the LSTMNet class which combines a linear layer, ReLU, LSTM, and two fully connected output layers', 'run the eval_model CLI to evaluate SAD/OP/OBL Hanabi agents over 5000 games', 'run evaluate_agents to compute mean score, SEM, and perfect rate for a list of Hanabi agents', 'run the eval_model CLI with --paper sad to evaluate a SAD paper model using a weight file', 'run the eval_model CLI with --paper op to evaluate an OP paper model by method and index', 'run the eval_model CLI with --paper obl to evaluate an OBL model from a given path', 'load the OBL pretrained Hanabi SAD model from a .pthw checkpoint file', 'create an R2D2Agent with online and target LSTM networks for Hanabi reinforcement learning', 'run greedy action selection on private and public state tensors using the online network', 'run epsilon-greedy action selection on observation dict with private state, public state, and legal moves', 'review the duel Q-value computation that combines value and advantage networks with legal move masking']
```

Usage

```
{'run_action_matrix_cli': 'run the action_matrix CLI tool to generate an action matrix plot from a SAD or OP Hanabi agent model', 'create_dataset': 'create a replay buffer dataset by running 100 parallel Hanabi game actors with an R2D2 runner', 'analyze_dataset': 'analyze a replay buffer dataset to compute a 20x20 joint action probability matrix for two players', 'plot_action_matrix': 'plot a 20x20 or 30x30 action matrix heatmap with labeled axes for Hanabi actions', 'review_create_dataset': 'review the create_dataset function to understand how R2D2 actors and replay buffers are configured for data collection'}
```

## File: facebookresearch_hanabisad/pyhanabi/tools/convert_model.py

Prompts

```
['run the action_matrix CLI tool to generate an action matrix plot from a SAD or OP Hanabi agent model', 'create a replay buffer dataset by running 100 parallel Hanabi game actors with an R2D2 runner', 'analyze a replay buffer dataset to compute a 20x20 joint action probability matrix for two players', 'plot a 20x20 or 30x30 action matrix heatmap with labeled axes for Hanabi actions', 'review the create_dataset function to understand how R2D2 actors and replay buffers are configured for data collection', 'run the python module to convert a PyTorch model to TorchScript format using the --model argument', 'create an LSTMNet TorchScript module with configurable input dimension, hidden dimension, output dimension, and LSTM layers', 'run the LSTMNet forward pass with an observation dictionary containing state, hidden, and cell tensors', 'load a PyTorch state dict, load weights into an LSTMNet model, and save as a TorchScript .sparta file', 'review the LSTMNet class which combines a linear layer, ReLU, LSTM, and two fully connected output layers', 'run the eval_model CLI to evaluate SAD/OP/OBL Hanabi agents over 5000 games', 'run evaluate_agents to compute mean score, SEM, and perfect rate for a list of Hanabi agents', 'run the eval_model CLI with --paper sad to evaluate a SAD paper model using a weight file', 'run the eval_model CLI with --paper op to evaluate an OP paper model by method and index', 'run the eval_model CLI with --paper obl to evaluate an OBL model from a given path', 'load the OBL pretrained Hanabi SAD model from a .pthw checkpoint file', 'create an R2D2Agent with online and target LSTM networks for Hanabi reinforcement learning', 'run greedy action selection on private and public state tensors using the online network', 'run epsilon-greedy action selection on observation dict with private state, public state, and legal moves', 'review the duel Q-value computation that combines value and advantage networks with legal move masking']
```

Usage

```
{'convert_model_to_torchscript': 'run the python module to convert a PyTorch model to TorchScript format using the --model argument', 'create_LSTMNet_model': 'create an LSTMNet TorchScript module with configurable input dimension, hidden dimension, output dimension, and LSTM layers', 'run_LSTMNet_forward': 'run the LSTMNet forward pass with an observation dictionary containing state, hidden, and cell tensors', 'load_and_save_torchscript': 'load a PyTorch state dict, load weights into an LSTMNet model, and save as a TorchScript .sparta file', 'review_LSTMNet_architecture': 'review the LSTMNet class which combines a linear layer, ReLU, LSTM, and two fully connected output layers'}
```

## File: facebookresearch_hanabisad/pyhanabi/tools/eval_model.py

Prompts

```
['run the action_matrix CLI tool to generate an action matrix plot from a SAD or OP Hanabi agent model', 'create a replay buffer dataset by running 100 parallel Hanabi game actors with an R2D2 runner', 'analyze a replay buffer dataset to compute a 20x20 joint action probability matrix for two players', 'plot a 20x20 or 30x30 action matrix heatmap with labeled axes for Hanabi actions', 'review the create_dataset function to understand how R2D2 actors and replay buffers are configured for data collection', 'run the python module to convert a PyTorch model to TorchScript format using the --model argument', 'create an LSTMNet TorchScript module with configurable input dimension, hidden dimension, output dimension, and LSTM layers', 'run the LSTMNet forward pass with an observation dictionary containing state, hidden, and cell tensors', 'load a PyTorch state dict, load weights into an LSTMNet model, and save as a TorchScript .sparta file', 'review the LSTMNet class which combines a linear layer, ReLU, LSTM, and two fully connected output layers', 'run the eval_model CLI to evaluate SAD/OP/OBL Hanabi agents over 5000 games', 'run evaluate_agents to compute mean score, SEM, and perfect rate for a list of Hanabi agents', 'run the eval_model CLI with --paper sad to evaluate a SAD paper model using a weight file', 'run the eval_model CLI with --paper op to evaluate an OP paper model by method and index', 'run the eval_model CLI with --paper obl to evaluate an OBL model from a given path', 'load the OBL pretrained Hanabi SAD model from a .pthw checkpoint file', 'create an R2D2Agent with online and target LSTM networks for Hanabi reinforcement learning', 'run greedy action selection on private and public state tensors using the online network', 'run epsilon-greedy action selection on observation dict with private state, public state, and legal moves', 'review the duel Q-value computation that combines value and advantage networks with legal move masking']
```

Usage

```
{'run_eval_model_cli': 'run the eval_model CLI to evaluate SAD/OP/OBL Hanabi agents over 5000 games', 'run_evaluate_agents': 'run evaluate_agents to compute mean score, SEM, and perfect rate for a list of Hanabi agents', 'run_sad_model_eval': 'run the eval_model CLI with --paper sad to evaluate a SAD paper model using a weight file', 'run_op_model_eval': 'run the eval_model CLI with --paper op to evaluate an OP paper model by method and index', 'run_obl_model_eval': 'run the eval_model CLI with --paper obl to evaluate an OBL model from a given path'}
```

## File: facebookresearch_hanabisad/pyhanabi/tools/obl_model.py

Prompts

```
['run the action_matrix CLI tool to generate an action matrix plot from a SAD or OP Hanabi agent model', 'create a replay buffer dataset by running 100 parallel Hanabi game actors with an R2D2 runner', 'analyze a replay buffer dataset to compute a 20x20 joint action probability matrix for two players', 'plot a 20x20 or 30x30 action matrix heatmap with labeled axes for Hanabi actions', 'review the create_dataset function to understand how R2D2 actors and replay buffers are configured for data collection', 'run the python module to convert a PyTorch model to TorchScript format using the --model argument', 'create an LSTMNet TorchScript module with configurable input dimension, hidden dimension, output dimension, and LSTM layers', 'run the LSTMNet forward pass with an observation dictionary containing state, hidden, and cell tensors', 'load a PyTorch state dict, load weights into an LSTMNet model, and save as a TorchScript .sparta file', 'review the LSTMNet class which combines a linear layer, ReLU, LSTM, and two fully connected output layers', 'run the eval_model CLI to evaluate SAD/OP/OBL Hanabi agents over 5000 games', 'run evaluate_agents to compute mean score, SEM, and perfect rate for a list of Hanabi agents', 'run the eval_model CLI with --paper sad to evaluate a SAD paper model using a weight file', 'run the eval_model CLI with --paper op to evaluate an OP paper model by method and index', 'run the eval_model CLI with --paper obl to evaluate an OBL model from a given path', 'load the OBL pretrained Hanabi SAD model from a .pthw checkpoint file', 'create an R2D2Agent with online and target LSTM networks for Hanabi reinforcement learning', 'run greedy action selection on private and public state tensors using the online network', 'run epsilon-greedy action selection on observation dict with private state, public state, and legal moves', 'review the duel Q-value computation that combines value and advantage networks with legal move masking']
```

Usage

```
{'load_obl_model': 'load the OBL pretrained Hanabi SAD model from a .pthw checkpoint file', 'create_R2D2Agent': 'create an R2D2Agent with online and target LSTM networks for Hanabi reinforcement learning', 'run_greedy_act': 'run greedy action selection on private and public state tensors using the online network', 'run_act_eps_greedy': 'run epsilon-greedy action selection on observation dict with private state, public state, and legal moves', 'review_duel_q_value': 'review the duel Q-value computation that combines value and advantage networks with legal move masking'}
```

