# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/tests/test_agent_wrappers.py

Prompts

```
['test a ToyAgent wrapped with GumbelSoftmaxWrapper for differentiable discrete sampling and training', 'test a SymbolGameGS with a GumbelSoftmax sender and Receiver trained via cross-entropy loss', 'test a ToyAgent wrapped with ReinforceWrapper for policy gradient training with log probabilities', 'test a SymbolGameReinforce with Reinforce sender and ReinforceDeterministic receiver trained via REINFORCE', 'test a SymbolReceiverWrapper that handles both long id and one-hot encoded message inputs', 'run an EGG zoo game module by dynamically importing it and passing CLI-style parameters', 'test the simple autoencoder game with a small vocabulary and feature set for one epoch', 'test the objects game with perceptual dimensions and distractors for communication learning', 'test the compositional versus generalization game to evaluate emergent language compositionality', 'test compositional efficiency with discrete and continuous language variants for one epoch', 'create a ToyDataset that generates 256 binary vectors and their bit-count sums as labels', 'build a ToyAgent neural network with a single linear layer mapping 8 inputs to 1 output', 'build a ToyGame that wraps a ToyAgent with MSELoss and returns loss and empty Interaction', 'test training a ToyAgent over 10000 epochs to learn bit counting via gradient descent', 'run a core.Trainer with a ToyGame, optimizer, and ToyDataset to train for a specified number of epochs', 'test the TemperatureUpdater callback to decay the sender agent temperature during training', 'test the CheckpointSaver callback to save model checkpoints at each training epoch', 'test the CheckpointSaver with max_checkpoints to limit the number of saved checkpoint files', 'test the EarlyStopperAccuracy callback to stop training when accuracy threshold is reached', 'test the Trainer class with various callbacks for temperature updates, checkpointing, and early stopping']
```

Usage

```
{'test_GumbelSoftmaxWrapper': 'test a ToyAgent wrapped with GumbelSoftmaxWrapper for differentiable discrete sampling and training', 'test_SymbolGameGS': 'test a SymbolGameGS with a GumbelSoftmax sender and Receiver trained via cross-entropy loss', 'test_ReinforceWrapper': 'test a ToyAgent wrapped with ReinforceWrapper for policy gradient training with log probabilities', 'test_SymbolGameReinforce': 'test a SymbolGameReinforce with Reinforce sender and ReinforceDeterministic receiver trained via REINFORCE', 'test_SymbolReceiverWrapper': 'test a SymbolReceiverWrapper that handles both long id and one-hot encoded message inputs'}
```

## File: facebookresearch_egg/tests/test_games_do_not_fail.py

Prompts

```
['test a ToyAgent wrapped with GumbelSoftmaxWrapper for differentiable discrete sampling and training', 'test a SymbolGameGS with a GumbelSoftmax sender and Receiver trained via cross-entropy loss', 'test a ToyAgent wrapped with ReinforceWrapper for policy gradient training with log probabilities', 'test a SymbolGameReinforce with Reinforce sender and ReinforceDeterministic receiver trained via REINFORCE', 'test a SymbolReceiverWrapper that handles both long id and one-hot encoded message inputs', 'run an EGG zoo game module by dynamically importing it and passing CLI-style parameters', 'test the simple autoencoder game with a small vocabulary and feature set for one epoch', 'test the objects game with perceptual dimensions and distractors for communication learning', 'test the compositional versus generalization game to evaluate emergent language compositionality', 'test compositional efficiency with discrete and continuous language variants for one epoch', 'create a ToyDataset that generates 256 binary vectors and their bit-count sums as labels', 'build a ToyAgent neural network with a single linear layer mapping 8 inputs to 1 output', 'build a ToyGame that wraps a ToyAgent with MSELoss and returns loss and empty Interaction', 'test training a ToyAgent over 10000 epochs to learn bit counting via gradient descent', 'run a core.Trainer with a ToyGame, optimizer, and ToyDataset to train for a specified number of epochs', 'test the TemperatureUpdater callback to decay the sender agent temperature during training', 'test the CheckpointSaver callback to save model checkpoints at each training epoch', 'test the CheckpointSaver with max_checkpoints to limit the number of saved checkpoint files', 'test the EarlyStopperAccuracy callback to stop training when accuracy threshold is reached', 'test the Trainer class with various callbacks for temperature updates, checkpointing, and early stopping']
```

Usage

```
{'run_game': 'run an EGG zoo game module by dynamically importing it and passing CLI-style parameters', 'test_simple_autoenc': 'test the simple autoencoder game with a small vocabulary and feature set for one epoch', 'test_objects_game': 'test the objects game with perceptual dimensions and distractors for communication learning', 'test_compo_generalization': 'test the compositional versus generalization game to evaluate emergent language compositionality', 'test_compositional_efficiency': 'test compositional efficiency with discrete and continuous language variants for one epoch'}
```

## File: facebookresearch_egg/tests/test_toy_counting.py

Prompts

```
['test a ToyAgent wrapped with GumbelSoftmaxWrapper for differentiable discrete sampling and training', 'test a SymbolGameGS with a GumbelSoftmax sender and Receiver trained via cross-entropy loss', 'test a ToyAgent wrapped with ReinforceWrapper for policy gradient training with log probabilities', 'test a SymbolGameReinforce with Reinforce sender and ReinforceDeterministic receiver trained via REINFORCE', 'test a SymbolReceiverWrapper that handles both long id and one-hot encoded message inputs', 'run an EGG zoo game module by dynamically importing it and passing CLI-style parameters', 'test the simple autoencoder game with a small vocabulary and feature set for one epoch', 'test the objects game with perceptual dimensions and distractors for communication learning', 'test the compositional versus generalization game to evaluate emergent language compositionality', 'test compositional efficiency with discrete and continuous language variants for one epoch', 'create a ToyDataset that generates 256 binary vectors and their bit-count sums as labels', 'build a ToyAgent neural network with a single linear layer mapping 8 inputs to 1 output', 'build a ToyGame that wraps a ToyAgent with MSELoss and returns loss and empty Interaction', 'test training a ToyAgent over 10000 epochs to learn bit counting via gradient descent', 'run a core.Trainer with a ToyGame, optimizer, and ToyDataset to train for a specified number of epochs', 'test the TemperatureUpdater callback to decay the sender agent temperature during training', 'test the CheckpointSaver callback to save model checkpoints at each training epoch', 'test the CheckpointSaver with max_checkpoints to limit the number of saved checkpoint files', 'test the EarlyStopperAccuracy callback to stop training when accuracy threshold is reached', 'test the Trainer class with various callbacks for temperature updates, checkpointing, and early stopping']
```

Usage

```
{'create_ToyDataset': 'create a ToyDataset that generates 256 binary vectors and their bit-count sums as labels', 'build_ToyAgent': 'build a ToyAgent neural network with a single linear layer mapping 8 inputs to 1 output', 'build_ToyGame': 'build a ToyGame that wraps a ToyAgent with MSELoss and returns loss and empty Interaction', 'test_toy_counting_gradient': 'test training a ToyAgent over 10000 epochs to learn bit counting via gradient descent', 'run_trainer': 'run a core.Trainer with a ToyGame, optimizer, and ToyDataset to train for a specified number of epochs'}
```

## File: facebookresearch_egg/tests/test_trainer.py

Prompts

```
['test a ToyAgent wrapped with GumbelSoftmaxWrapper for differentiable discrete sampling and training', 'test a SymbolGameGS with a GumbelSoftmax sender and Receiver trained via cross-entropy loss', 'test a ToyAgent wrapped with ReinforceWrapper for policy gradient training with log probabilities', 'test a SymbolGameReinforce with Reinforce sender and ReinforceDeterministic receiver trained via REINFORCE', 'test a SymbolReceiverWrapper that handles both long id and one-hot encoded message inputs', 'run an EGG zoo game module by dynamically importing it and passing CLI-style parameters', 'test the simple autoencoder game with a small vocabulary and feature set for one epoch', 'test the objects game with perceptual dimensions and distractors for communication learning', 'test the compositional versus generalization game to evaluate emergent language compositionality', 'test compositional efficiency with discrete and continuous language variants for one epoch', 'create a ToyDataset that generates 256 binary vectors and their bit-count sums as labels', 'build a ToyAgent neural network with a single linear layer mapping 8 inputs to 1 output', 'build a ToyGame that wraps a ToyAgent with MSELoss and returns loss and empty Interaction', 'test training a ToyAgent over 10000 epochs to learn bit counting via gradient descent', 'run a core.Trainer with a ToyGame, optimizer, and ToyDataset to train for a specified number of epochs', 'test the TemperatureUpdater callback to decay the sender agent temperature during training', 'test the CheckpointSaver callback to save model checkpoints at each training epoch', 'test the CheckpointSaver with max_checkpoints to limit the number of saved checkpoint files', 'test the EarlyStopperAccuracy callback to stop training when accuracy threshold is reached', 'test the Trainer class with various callbacks for temperature updates, checkpointing, and early stopping']
```

Usage

```
{'test_temperature_updater_callback': 'test the TemperatureUpdater callback to decay the sender agent temperature during training', 'test_checkpoint_saver_callback': 'test the CheckpointSaver callback to save model checkpoints at each training epoch', 'test_max_checkpoint_saver': 'test the CheckpointSaver with max_checkpoints to limit the number of saved checkpoint files', 'test_early_stopping_callback': 'test the EarlyStopperAccuracy callback to stop training when accuracy threshold is reached', 'test_trainer_with_callbacks': 'test the Trainer class with various callbacks for temperature updates, checkpointing, and early stopping'}
```

