# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/language_bottleneck/mnist_overfit/archs.py

Prompts

```
['build a LeNet CNN model with two conv layers and a fully connected layer for MNIST feature extraction', 'create a Sender module with LeNet vision encoder and configurable linear or softmax channel output', 'create a Receiver module with relaxed embedding and linear layers to classify messages into n_classes', 'test the Sender forward pass with image input and aux input to produce vocabulary logits', 'review the Receiver class and its RelaxedEmbedding usage for message-to-class classification', 'corrupt a percentage of labels in a PyTorch dataset using a random seed', 'test the corrupt_labels_ function with a MNIST dataset and 30 percent corruption rate', 'refactor the corrupt_labels_ function to remove the duplicate label assignment block', 'review the corrupt_labels_ function for handling both targets and train_labels attributes', 'summarize the corrupt_labels_ function that shuffles a fraction of dataset labels randomly', 'run the MNIST overfit training loop with a sender receiver game and Gumbel-Softmax channel', 'build a negative log-likelihood loss function that returns loss and accuracy for the receiver output', 'get command-line parsed arguments for temperature, corruption probability, and channel type options', 'test the Sender and Receiver network architectures with configurable vocab size and deeper layers', 'refactor the sender using AlwaysRelaxedWrapper or GumbelSoftmaxWrapper based on channel configuration flags']
```

Usage

```
{'build_LeNet_CNN': 'build a LeNet CNN model with two conv layers and a fully connected layer for MNIST feature extraction', 'create_Sender_with_channel': 'create a Sender module with LeNet vision encoder and configurable linear or softmax channel output', 'create_Receiver_classifier': 'create a Receiver module with relaxed embedding and linear layers to classify messages into n_classes', 'test_Sender_forward_pass': 'test the Sender forward pass with image input and aux input to produce vocabulary logits', 'review_Receiver_embedding': 'review the Receiver class and its RelaxedEmbedding usage for message-to-class classification'}
```

## File: facebookresearch_egg/egg/zoo/language_bottleneck/mnist_overfit/data.py

Prompts

```
['build a LeNet CNN model with two conv layers and a fully connected layer for MNIST feature extraction', 'create a Sender module with LeNet vision encoder and configurable linear or softmax channel output', 'create a Receiver module with relaxed embedding and linear layers to classify messages into n_classes', 'test the Sender forward pass with image input and aux input to produce vocabulary logits', 'review the Receiver class and its RelaxedEmbedding usage for message-to-class classification', 'corrupt a percentage of labels in a PyTorch dataset using a random seed', 'test the corrupt_labels_ function with a MNIST dataset and 30 percent corruption rate', 'refactor the corrupt_labels_ function to remove the duplicate label assignment block', 'review the corrupt_labels_ function for handling both targets and train_labels attributes', 'summarize the corrupt_labels_ function that shuffles a fraction of dataset labels randomly', 'run the MNIST overfit training loop with a sender receiver game and Gumbel-Softmax channel', 'build a negative log-likelihood loss function that returns loss and accuracy for the receiver output', 'get command-line parsed arguments for temperature, corruption probability, and channel type options', 'test the Sender and Receiver network architectures with configurable vocab size and deeper layers', 'refactor the sender using AlwaysRelaxedWrapper or GumbelSoftmaxWrapper based on channel configuration flags']
```

Usage

```
{'corrupt_labels_dataset': 'corrupt a percentage of labels in a PyTorch dataset using a random seed', 'test_corrupt_labels_': 'test the corrupt_labels_ function with a MNIST dataset and 30 percent corruption rate', 'refactor_corrupt_labels_': 'refactor the corrupt_labels_ function to remove the duplicate label assignment block', 'review_corrupt_labels_': 'review the corrupt_labels_ function for handling both targets and train_labels attributes', 'summarize_corrupt_labels_': 'summarize the corrupt_labels_ function that shuffles a fraction of dataset labels randomly'}
```

## File: facebookresearch_egg/egg/zoo/language_bottleneck/mnist_overfit/train.py

Prompts

```
['build a LeNet CNN model with two conv layers and a fully connected layer for MNIST feature extraction', 'create a Sender module with LeNet vision encoder and configurable linear or softmax channel output', 'create a Receiver module with relaxed embedding and linear layers to classify messages into n_classes', 'test the Sender forward pass with image input and aux input to produce vocabulary logits', 'review the Receiver class and its RelaxedEmbedding usage for message-to-class classification', 'corrupt a percentage of labels in a PyTorch dataset using a random seed', 'test the corrupt_labels_ function with a MNIST dataset and 30 percent corruption rate', 'refactor the corrupt_labels_ function to remove the duplicate label assignment block', 'review the corrupt_labels_ function for handling both targets and train_labels attributes', 'summarize the corrupt_labels_ function that shuffles a fraction of dataset labels randomly', 'run the MNIST overfit training loop with a sender receiver game and Gumbel-Softmax channel', 'build a negative log-likelihood loss function that returns loss and accuracy for the receiver output', 'get command-line parsed arguments for temperature, corruption probability, and channel type options', 'test the Sender and Receiver network architectures with configurable vocab size and deeper layers', 'refactor the sender using AlwaysRelaxedWrapper or GumbelSoftmaxWrapper based on channel configuration flags']
```

Usage

```
{'run_mnist_overfit_training': 'run the MNIST overfit training loop with a sender receiver game and Gumbel-Softmax channel', 'build_diff_loss_symbol': 'build a negative log-likelihood loss function that returns loss and accuracy for the receiver output', 'get_params_cli': 'get command-line parsed arguments for temperature, corruption probability, and channel type options', 'test_Sender_Receiver_archs': 'test the Sender and Receiver network architectures with configurable vocab size and deeper layers', 'refactor_AlwaysRelaxedWrapper': 'refactor the sender using AlwaysRelaxedWrapper or GumbelSoftmaxWrapper based on channel configuration flags'}
```

