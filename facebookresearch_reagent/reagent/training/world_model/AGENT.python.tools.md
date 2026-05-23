# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/training/world_model/compress_model_trainer.py

Prompts

```
['build a CompressModelTrainer with a FloatFeatureFullyConnected network, Seq2RewardNetwork, and Seq2RewardTrainerParameters', 'run the train_step_gen method to compute MSE loss and accuracy for a training batch', 'run the validation_step method to evaluate MSE, accuracy, Q-values, and action distribution on a batch', 'review the get_loss method that computes MSE loss between compress model output and target Q-values', 'test the extract_state_first_step static method to extract the first step state features from a batch', 'create an MDNRNNTrainer instance with a MemoryNetwork and MDNRNNTrainerParameters for training', 'configure Adam optimizers for the MDNRNNTrainer memory network parameters with a learning rate', 'compute GMM, BCE, and MSE losses from a MemoryNetworkInput batch and return a loss dictionary', 'build a Seq2RewardTrainer with a Seq2RewardNetwork and Seq2RewardTrainerParameters to train world model', 'run get_Q to compute max accumulated reward across all action permutations for a state', 'run get_step_prediction to get softmax step probabilities from a FullyConnectedNetwork', 'test the get_mse_loss method to compute MSE between predicted and target accumulated rewards', 'test the get_step_entropy_loss method to compute cross-entropy loss for step predictions']
```

Usage

```
{'build_compress_model_trainer': 'build a CompressModelTrainer with a FloatFeatureFullyConnected network, Seq2RewardNetwork, and Seq2RewardTrainerParameters', 'run_train_step_gen': 'run the train_step_gen method to compute MSE loss and accuracy for a training batch', 'run_validation_step': 'run the validation_step method to evaluate MSE, accuracy, Q-values, and action distribution on a batch', 'review_get_loss': 'review the get_loss method that computes MSE loss between compress model output and target Q-values', 'test_extract_state_first_step': 'test the extract_state_first_step static method to extract the first step state features from a batch'}
```

## File: facebookresearch_reagent/reagent/training/world_model/mdnrnn_trainer.py

Prompts

```
['build a CompressModelTrainer with a FloatFeatureFullyConnected network, Seq2RewardNetwork, and Seq2RewardTrainerParameters', 'run the train_step_gen method to compute MSE loss and accuracy for a training batch', 'run the validation_step method to evaluate MSE, accuracy, Q-values, and action distribution on a batch', 'review the get_loss method that computes MSE loss between compress model output and target Q-values', 'test the extract_state_first_step static method to extract the first step state features from a batch', 'create an MDNRNNTrainer instance with a MemoryNetwork and MDNRNNTrainerParameters for training', 'configure Adam optimizers for the MDNRNNTrainer memory network parameters with a learning rate', 'compute GMM, BCE, and MSE losses from a MemoryNetworkInput batch and return a loss dictionary', 'build a Seq2RewardTrainer with a Seq2RewardNetwork and Seq2RewardTrainerParameters to train world model', 'run get_Q to compute max accumulated reward across all action permutations for a state', 'run get_step_prediction to get softmax step probabilities from a FullyConnectedNetwork', 'test the get_mse_loss method to compute MSE between predicted and target accumulated rewards', 'test the get_step_entropy_loss method to compute cross-entropy loss for step predictions']
```

Usage

```
{'create_MDNRNNTrainer': 'create an MDNRNNTrainer instance with a MemoryNetwork and MDNRNNTrainerParameters for training', 'configure_optimizers_MDNRNNTrainer': 'configure Adam optimizers for the MDNRNNTrainer memory network parameters with a learning rate', 'run_train_step_gen': 'run a training step generator that computes GMM, BCE, and MSE losses for a batch', 'run_validation_step': 'run a validation step that computes and logs evaluation losses for a batch', 'run_get_loss': 'compute GMM, BCE, and MSE losses from a MemoryNetworkInput batch and return a loss dictionary'}
```

## File: facebookresearch_reagent/reagent/training/world_model/seq2reward_trainer.py

Prompts

```
['build a CompressModelTrainer with a FloatFeatureFullyConnected network, Seq2RewardNetwork, and Seq2RewardTrainerParameters', 'run the train_step_gen method to compute MSE loss and accuracy for a training batch', 'run the validation_step method to evaluate MSE, accuracy, Q-values, and action distribution on a batch', 'review the get_loss method that computes MSE loss between compress model output and target Q-values', 'test the extract_state_first_step static method to extract the first step state features from a batch', 'create an MDNRNNTrainer instance with a MemoryNetwork and MDNRNNTrainerParameters for training', 'configure Adam optimizers for the MDNRNNTrainer memory network parameters with a learning rate', 'compute GMM, BCE, and MSE losses from a MemoryNetworkInput batch and return a loss dictionary', 'build a Seq2RewardTrainer with a Seq2RewardNetwork and Seq2RewardTrainerParameters to train world model', 'run get_Q to compute max accumulated reward across all action permutations for a state', 'run get_step_prediction to get softmax step probabilities from a FullyConnectedNetwork', 'test the get_mse_loss method to compute MSE between predicted and target accumulated rewards', 'test the get_step_entropy_loss method to compute cross-entropy loss for step predictions']
```

Usage

```
{'build_seq2reward_trainer': 'build a Seq2RewardTrainer with a Seq2RewardNetwork and Seq2RewardTrainerParameters to train world model', 'run_get_Q': 'run get_Q to compute max accumulated reward across all action permutations for a state', 'run_get_step_prediction': 'run get_step_prediction to get softmax step probabilities from a FullyConnectedNetwork', 'test_get_mse_loss': 'test the get_mse_loss method to compute MSE between predicted and target accumulated rewards', 'test_get_step_entropy_loss': 'test the get_step_entropy_loss method to compute cross-entropy loss for step predictions'}
```

