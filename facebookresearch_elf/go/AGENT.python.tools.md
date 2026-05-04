# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/go/df_model.py

Prompts

```
['build a Model_Policy convolutional neural network for Go game policy prediction with configurable layers and dimensions', 'create a forward pass through the Model_Policy conv layers to predict action probabilities for Go board states', 'test the Model_Policy get_define_args method to retrieve argparse configuration options for batch norm and layer count', 'review the Models dictionary registry that maps df_policy key to Model_Policy and MultiplePrediction classes', 'refactor the Model_Policy forward method to reshape and apply softmax across multiple future action predictions', 'build a Model_PolicyValue instance with args containing board_size, num_future_actions, and num_planes params', 'create a conv layer with configurable input/output channels, kernel size, and optional batch norm', 'run a forward pass on state tensor x returning policy pi and value V predictions', 'review the get_define_args method to see argparse flags for no_bn, no_leaky_relu, num_block, and dim', 'test the Models dictionary registry that maps key df to Model_PolicyValue and MultiplePrediction', 'run a Go game simulation with MCTS and collect board statistics over multiple iterations', 'create a Loader instance that configures Go game arguments including mode, data augmentation, and GPU settings', 'initialize a GCWrapper with GameContext options for online, selfplay, or train modes', 'register a train callback function to collect board state statistics during game replay', 'run the Go game loop for a specified number of iterations and print performance summary', 'create a MultiplePrediction instance with NLLLoss and MSELoss criteria for policy and value losses', 'update model predictions using a batch of experience data and compute policy loss with top-k accuracy', 'compute negative log-likelihood policy loss for multi-step action predictions with numerical stability epsilon', 'track top-1 and top-5 accuracy metrics for the first prediction step during training updates', 'perform backward pass on total loss unless multipred_no_backprop flag is set to skip backpropagation']
```

Usage

```
{'build_Model_Policy': 'build a Model_Policy convolutional neural network for Go game policy prediction with configurable layers and dimensions', 'create_forward_pass': 'create a forward pass through the Model_Policy conv layers to predict action probabilities for Go board states', 'test_get_define_args': 'test the Model_Policy get_define_args method to retrieve argparse configuration options for batch norm and layer count', 'review_Models_registry': 'review the Models dictionary registry that maps df_policy key to Model_Policy and MultiplePrediction classes', 'refactor_softmax_output': 'refactor the Model_Policy forward method to reshape and apply softmax across multiple future action predictions'}
```

## File: facebookresearch_elf/go/df_model2.py

Prompts

```
['build a Model_Policy convolutional neural network for Go game policy prediction with configurable layers and dimensions', 'create a forward pass through the Model_Policy conv layers to predict action probabilities for Go board states', 'test the Model_Policy get_define_args method to retrieve argparse configuration options for batch norm and layer count', 'review the Models dictionary registry that maps df_policy key to Model_Policy and MultiplePrediction classes', 'refactor the Model_Policy forward method to reshape and apply softmax across multiple future action predictions', 'build a Model_PolicyValue instance with args containing board_size, num_future_actions, and num_planes params', 'create a conv layer with configurable input/output channels, kernel size, and optional batch norm', 'run a forward pass on state tensor x returning policy pi and value V predictions', 'review the get_define_args method to see argparse flags for no_bn, no_leaky_relu, num_block, and dim', 'test the Models dictionary registry that maps key df to Model_PolicyValue and MultiplePrediction', 'run a Go game simulation with MCTS and collect board statistics over multiple iterations', 'create a Loader instance that configures Go game arguments including mode, data augmentation, and GPU settings', 'initialize a GCWrapper with GameContext options for online, selfplay, or train modes', 'register a train callback function to collect board state statistics during game replay', 'run the Go game loop for a specified number of iterations and print performance summary', 'create a MultiplePrediction instance with NLLLoss and MSELoss criteria for policy and value losses', 'update model predictions using a batch of experience data and compute policy loss with top-k accuracy', 'compute negative log-likelihood policy loss for multi-step action predictions with numerical stability epsilon', 'track top-1 and top-5 accuracy metrics for the first prediction step during training updates', 'perform backward pass on total loss unless multipred_no_backprop flag is set to skip backpropagation']
```

Usage

```
{'build_Model_PolicyValue': 'build a Model_PolicyValue instance with args containing board_size, num_future_actions, and num_planes params', 'create_conv_layer': 'create a conv layer with configurable input/output channels, kernel size, and optional batch norm', 'run_forward_pass': 'run a forward pass on state tensor x returning policy pi and value V predictions', 'review_get_define_args': 'review the get_define_args method to see argparse flags for no_bn, no_leaky_relu, num_block, and dim', 'test_Models_registry': 'test the Models dictionary registry that maps key df to Model_PolicyValue and MultiplePrediction'}
```

## File: facebookresearch_elf/go/game.py

Prompts

```
['build a Model_Policy convolutional neural network for Go game policy prediction with configurable layers and dimensions', 'create a forward pass through the Model_Policy conv layers to predict action probabilities for Go board states', 'test the Model_Policy get_define_args method to retrieve argparse configuration options for batch norm and layer count', 'review the Models dictionary registry that maps df_policy key to Model_Policy and MultiplePrediction classes', 'refactor the Model_Policy forward method to reshape and apply softmax across multiple future action predictions', 'build a Model_PolicyValue instance with args containing board_size, num_future_actions, and num_planes params', 'create a conv layer with configurable input/output channels, kernel size, and optional batch norm', 'run a forward pass on state tensor x returning policy pi and value V predictions', 'review the get_define_args method to see argparse flags for no_bn, no_leaky_relu, num_block, and dim', 'test the Models dictionary registry that maps key df to Model_PolicyValue and MultiplePrediction', 'run a Go game simulation with MCTS and collect board statistics over multiple iterations', 'create a Loader instance that configures Go game arguments including mode, data augmentation, and GPU settings', 'initialize a GCWrapper with GameContext options for online, selfplay, or train modes', 'register a train callback function to collect board state statistics during game replay', 'run the Go game loop for a specified number of iterations and print performance summary', 'create a MultiplePrediction instance with NLLLoss and MSELoss criteria for policy and value losses', 'update model predictions using a batch of experience data and compute policy loss with top-k accuracy', 'compute negative log-likelihood policy loss for multi-step action predictions with numerical stability epsilon', 'track top-1 and top-5 accuracy metrics for the first prediction step during training updates', 'perform backward pass on total loss unless multipred_no_backprop flag is set to skip backpropagation']
```

Usage

```
{'run_go_game_simulation': 'run a Go game simulation with MCTS and collect board statistics over multiple iterations', 'create_loader_with_args': 'create a Loader instance that configures Go game arguments including mode, data augmentation, and GPU settings', 'initialize_game_context': 'initialize a GCWrapper with GameContext options for online, selfplay, or train modes', 'register_train_callback': 'register a train callback function to collect board state statistics during game replay', 'run_game_loop': 'run the Go game loop for a specified number of iterations and print performance summary'}
```

## File: facebookresearch_elf/go/multiple_prediction.py

Prompts

```
['build a Model_Policy convolutional neural network for Go game policy prediction with configurable layers and dimensions', 'create a forward pass through the Model_Policy conv layers to predict action probabilities for Go board states', 'test the Model_Policy get_define_args method to retrieve argparse configuration options for batch norm and layer count', 'review the Models dictionary registry that maps df_policy key to Model_Policy and MultiplePrediction classes', 'refactor the Model_Policy forward method to reshape and apply softmax across multiple future action predictions', 'build a Model_PolicyValue instance with args containing board_size, num_future_actions, and num_planes params', 'create a conv layer with configurable input/output channels, kernel size, and optional batch norm', 'run a forward pass on state tensor x returning policy pi and value V predictions', 'review the get_define_args method to see argparse flags for no_bn, no_leaky_relu, num_block, and dim', 'test the Models dictionary registry that maps key df to Model_PolicyValue and MultiplePrediction', 'run a Go game simulation with MCTS and collect board statistics over multiple iterations', 'create a Loader instance that configures Go game arguments including mode, data augmentation, and GPU settings', 'initialize a GCWrapper with GameContext options for online, selfplay, or train modes', 'register a train callback function to collect board state statistics during game replay', 'run the Go game loop for a specified number of iterations and print performance summary', 'create a MultiplePrediction instance with NLLLoss and MSELoss criteria for policy and value losses', 'update model predictions using a batch of experience data and compute policy loss with top-k accuracy', 'compute negative log-likelihood policy loss for multi-step action predictions with numerical stability epsilon', 'track top-1 and top-5 accuracy metrics for the first prediction step during training updates', 'perform backward pass on total loss unless multipred_no_backprop flag is set to skip backpropagation']
```

Usage

```
{'init_MultiplePrediction': 'create a MultiplePrediction instance with NLLLoss and MSELoss criteria for policy and value losses', 'update_MultiplePrediction': 'update model predictions using a batch of experience data and compute policy loss with top-k accuracy', 'compute_policy_loss': 'compute negative log-likelihood policy loss for multi-step action predictions with numerical stability epsilon', 'track_topk_accuracy': 'track top-1 and top-5 accuracy metrics for the first prediction step during training updates', 'backward_pass_MultiplePrediction': 'perform backward pass on total loss unless multipred_no_backprop flag is set to skip backpropagation'}
```

