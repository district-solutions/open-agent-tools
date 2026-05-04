# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/basic_games/architectures.py

Prompts

```
['build a RecoReceiver module that maps RNN output to n_features dimensional reconstruction', 'build a DiscriReceiver module that computes dot products between RNN output and input vectors', 'build a Sender module that maps input target vectors to hidden representations for RNN initialization', 'review the RecoReceiver forward method that applies a linear layer to produce reconstructed output', 'review the DiscriReceiver forward method that embeds inputs and computes dot product scores', 'create an AttValRecoDataset from a text file with space-delimited attribute-value vectors for the reconstruction game', 'create an AttValDiscriDataset from a text file with period-delimited vectors for the discrimination game', 'get the number of one-hot features from an AttValRecoDataset instance', 'get the number of one-hot features from an AttValDiscriDataset instance', 'retrieve the idx-th sender input and label pair from an AttValRecoDataset', 'run a reconstruction game training a Sender and Receiver to communicate attribute-value vectors via CLI', 'run a discrimination game training a Sender and Receiver to identify target positions via CLI', 'run Gumbel-Softmax training mode with temperature decay for the Sender-Receiver communication game', 'run Reinforce training mode with entropy regularization for the Sender-Receiver communication game', 'run training with print_validation_events flag to log Sender messages and Receiver outputs after training']
```

Usage

```
{'build_RecoReceiver': 'build a RecoReceiver module that maps RNN output to n_features dimensional reconstruction', 'build_DiscriReceiver': 'build a DiscriReceiver module that computes dot products between RNN output and input vectors', 'build_Sender': 'build a Sender module that maps input target vectors to hidden representations for RNN initialization', 'review_RecoReceiver_forward': 'review the RecoReceiver forward method that applies a linear layer to produce reconstructed output', 'review_DiscriReceiver_forward': 'review the DiscriReceiver forward method that embeds inputs and computes dot product scores'}
```

## File: facebookresearch_egg/egg/zoo/basic_games/data_readers.py

Prompts

```
['build a RecoReceiver module that maps RNN output to n_features dimensional reconstruction', 'build a DiscriReceiver module that computes dot products between RNN output and input vectors', 'build a Sender module that maps input target vectors to hidden representations for RNN initialization', 'review the RecoReceiver forward method that applies a linear layer to produce reconstructed output', 'review the DiscriReceiver forward method that embeds inputs and computes dot product scores', 'create an AttValRecoDataset from a text file with space-delimited attribute-value vectors for the reconstruction game', 'create an AttValDiscriDataset from a text file with period-delimited vectors for the discrimination game', 'get the number of one-hot features from an AttValRecoDataset instance', 'get the number of one-hot features from an AttValDiscriDataset instance', 'retrieve the idx-th sender input and label pair from an AttValRecoDataset', 'run a reconstruction game training a Sender and Receiver to communicate attribute-value vectors via CLI', 'run a discrimination game training a Sender and Receiver to identify target positions via CLI', 'run Gumbel-Softmax training mode with temperature decay for the Sender-Receiver communication game', 'run Reinforce training mode with entropy regularization for the Sender-Receiver communication game', 'run training with print_validation_events flag to log Sender messages and Receiver outputs after training']
```

Usage

```
{'create_AttValRecoDataset': 'create an AttValRecoDataset from a text file with space-delimited attribute-value vectors for the reconstruction game', 'create_AttValDiscriDataset': 'create an AttValDiscriDataset from a text file with period-delimited vectors for the discrimination game', 'get_n_features_AttValRecoDataset': 'get the number of one-hot features from an AttValRecoDataset instance', 'get_n_features_AttValDiscriDataset': 'get the number of one-hot features from an AttValDiscriDataset instance', 'getitem_AttValRecoDataset': 'retrieve the idx-th sender input and label pair from an AttValRecoDataset'}
```

## File: facebookresearch_egg/egg/zoo/basic_games/play.py

Prompts

```
['build a RecoReceiver module that maps RNN output to n_features dimensional reconstruction', 'build a DiscriReceiver module that computes dot products between RNN output and input vectors', 'build a Sender module that maps input target vectors to hidden representations for RNN initialization', 'review the RecoReceiver forward method that applies a linear layer to produce reconstructed output', 'review the DiscriReceiver forward method that embeds inputs and computes dot product scores', 'create an AttValRecoDataset from a text file with space-delimited attribute-value vectors for the reconstruction game', 'create an AttValDiscriDataset from a text file with period-delimited vectors for the discrimination game', 'get the number of one-hot features from an AttValRecoDataset instance', 'get the number of one-hot features from an AttValDiscriDataset instance', 'retrieve the idx-th sender input and label pair from an AttValRecoDataset', 'run a reconstruction game training a Sender and Receiver to communicate attribute-value vectors via CLI', 'run a discrimination game training a Sender and Receiver to identify target positions via CLI', 'run Gumbel-Softmax training mode with temperature decay for the Sender-Receiver communication game', 'run Reinforce training mode with entropy regularization for the Sender-Receiver communication game', 'run training with print_validation_events flag to log Sender messages and Receiver outputs after training']
```

Usage

```
{'run_reco_game': 'run a reconstruction game training a Sender and Receiver to communicate attribute-value vectors via CLI', 'run_discri_game': 'run a discrimination game training a Sender and Receiver to identify target positions via CLI', 'run_gumbel_softmax_training': 'run Gumbel-Softmax training mode with temperature decay for the Sender-Receiver communication game', 'run_reinforce_training': 'run Reinforce training mode with entropy regularization for the Sender-Receiver communication game', 'run_validation_events': 'run training with print_validation_events flag to log Sender messages and Receiver outputs after training'}
```

