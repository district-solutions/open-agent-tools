# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/examples/celeba_example.py

Prompts

```
['run the celeba federated learning example with a config file to train a binary classifier on CelebA', 'create a CelebaDataset instance that loads LEAF CelebA user data and image folders for federated learning', 'build a DataProvider with train and test CelebA datasets using LEAFDataLoader for federated learning', 'create a Resnet18 model with group norm for privacy-preserving federated learning on CelebA', 'create a SimpleConvNet CNN model following the LEAF CelebA architecture for binary classification', 'run the CIFAR10 federated learning example with python3 cifar10_example.py --config-file configs/cifar10_config.json', 'train a SimpleConvNet model using FLSim trainer with a DataProvider and MetricsReporter for CIFAR10 classification', 'test the trained federated learning model using the trainer test method with a DataProvider and STDOUT metrics reporter', 'create an FLModel wrapping a SimpleConvNet with CUDA support for federated learning on CIFAR10 data', 'run the sent140 example with a config file to train a binary sentiment classifier using FLSim', 'build a CharLSTM model with embedding, LSTM layers, and a fully connected layer for character-level classification', 'create a Sent140Dataset that loads LEAF JSON data and processes text into character indices for each user', 'train a federated learning model using FLSim trainer with metrics reporting to TensorBoard and stdout']
```

Usage

```
{'run_celeba_fl_training': 'run the celeba federated learning example with a config file to train a binary classifier on CelebA', 'create_celeba_dataset': 'create a CelebaDataset instance that loads LEAF CelebA user data and image folders for federated learning', 'build_data_provider': 'build a DataProvider with train and test CelebA datasets using LEAFDataLoader for federated learning', 'create_resnet18_model': 'create a Resnet18 model with group norm for privacy-preserving federated learning on CelebA', 'create_simple_convnet': 'create a SimpleConvNet CNN model following the LEAF CelebA architecture for binary classification'}
```

## File: facebookresearch_flsim/examples/cifar10_example.py

Prompts

```
['run the celeba federated learning example with a config file to train a binary classifier on CelebA', 'create a CelebaDataset instance that loads LEAF CelebA user data and image folders for federated learning', 'build a DataProvider with train and test CelebA datasets using LEAFDataLoader for federated learning', 'create a Resnet18 model with group norm for privacy-preserving federated learning on CelebA', 'create a SimpleConvNet CNN model following the LEAF CelebA architecture for binary classification', 'run the CIFAR10 federated learning example with python3 cifar10_example.py --config-file configs/cifar10_config.json', 'train a SimpleConvNet model using FLSim trainer with a DataProvider and MetricsReporter for CIFAR10 classification', 'test the trained federated learning model using the trainer test method with a DataProvider and STDOUT metrics reporter', 'create an FLModel wrapping a SimpleConvNet with CUDA support for federated learning on CIFAR10 data', 'run the sent140 example with a config file to train a binary sentiment classifier using FLSim', 'build a CharLSTM model with embedding, LSTM layers, and a fully connected layer for character-level classification', 'create a Sent140Dataset that loads LEAF JSON data and processes text into character indices for each user', 'train a federated learning model using FLSim trainer with metrics reporting to TensorBoard and stdout']
```

Usage

```
{'run_cifar10_federated_learning': 'run the CIFAR10 federated learning example with python3 cifar10_example.py --config-file configs/cifar10_config.json', 'build_data_provider': 'build a DataProvider for CIFAR10 using SequentialSharder with a specified local batch size and examples per user', 'train_federated_model': 'train a SimpleConvNet model using FLSim trainer with a DataProvider and MetricsReporter for CIFAR10 classification', 'test_federated_model': 'test the trained federated learning model using the trainer test method with a DataProvider and STDOUT metrics reporter', 'create_fl_model': 'create an FLModel wrapping a SimpleConvNet with CUDA support for federated learning on CIFAR10 data'}
```

## File: facebookresearch_flsim/examples/sent140_example.py

Prompts

```
['run the celeba federated learning example with a config file to train a binary classifier on CelebA', 'create a CelebaDataset instance that loads LEAF CelebA user data and image folders for federated learning', 'build a DataProvider with train and test CelebA datasets using LEAFDataLoader for federated learning', 'create a Resnet18 model with group norm for privacy-preserving federated learning on CelebA', 'create a SimpleConvNet CNN model following the LEAF CelebA architecture for binary classification', 'run the CIFAR10 federated learning example with python3 cifar10_example.py --config-file configs/cifar10_config.json', 'train a SimpleConvNet model using FLSim trainer with a DataProvider and MetricsReporter for CIFAR10 classification', 'test the trained federated learning model using the trainer test method with a DataProvider and STDOUT metrics reporter', 'create an FLModel wrapping a SimpleConvNet with CUDA support for federated learning on CIFAR10 data', 'run the sent140 example with a config file to train a binary sentiment classifier using FLSim', 'build a CharLSTM model with embedding, LSTM layers, and a fully connected layer for character-level classification', 'create a Sent140Dataset that loads LEAF JSON data and processes text into character indices for each user', 'train a federated learning model using FLSim trainer with metrics reporting to TensorBoard and stdout']
```

Usage

```
{'run_sent140_training': 'run the sent140 example with a config file to train a binary sentiment classifier using FLSim', 'build_charlstm_model': 'build a CharLSTM model with embedding, LSTM layers, and a fully connected layer for character-level classification', 'create_sent140_dataset': 'create a Sent140Dataset that loads LEAF JSON data and processes text into character indices for each user', 'build_data_provider': 'build a DataProvider with LEAFDataLoader for train and test datasets using configurable batch size', 'train_fl_model': 'train a federated learning model using FLSim trainer with metrics reporting to TensorBoard and stdout'}
```

