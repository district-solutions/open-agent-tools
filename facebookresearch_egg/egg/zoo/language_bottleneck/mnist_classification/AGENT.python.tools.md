# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/language_bottleneck/mnist_classification/archs.py

Prompts

```
['build a LeNet CNN model with two conv layers and a fully connected layer for MNIST feature extraction', 'create a Sender module that encodes MNIST images into messages using LeNet and a vocabulary-sized output', 'create a Receiver module that decodes messages into class predictions using relaxed embeddings and hidden layers', 'test the LeNet forward pass by passing an image tensor and verifying the 400-dimensional output shape', 'review the Sender and Receiver modules for language bottleneck MNIST classification game architecture', 'run the MNIST classification training loop with sender and receiver models using Gumbel-Softmax', 'build a SymbolGameGS with a Sender and Receiver model using GumbelSoftmaxWrapper for communication', 'create a loss function that computes NLL loss and accuracy from receiver output and labels', 'test the CallbackEvaluator intervention on a test loader with Gumbel-Softmax game loss', 'review the EarlyStopperAccuracy callback that stops training when accuracy exceeds a threshold']
```

Usage

```
{'build_LeNet_CNN': 'build a LeNet CNN model with two conv layers and a fully connected layer for MNIST feature extraction', 'create_Sender_module': 'create a Sender module that encodes MNIST images into messages using LeNet and a vocabulary-sized output', 'create_Receiver_module': 'create a Receiver module that decodes messages into class predictions using relaxed embeddings and hidden layers', 'test_LeNet_forward': 'test the LeNet forward pass by passing an image tensor and verifying the 400-dimensional output shape', 'review_Sender_Receiver': 'review the Sender and Receiver modules for language bottleneck MNIST classification game architecture'}
```

## File: facebookresearch_egg/egg/zoo/language_bottleneck/mnist_classification/train.py

Prompts

```
['build a LeNet CNN model with two conv layers and a fully connected layer for MNIST feature extraction', 'create a Sender module that encodes MNIST images into messages using LeNet and a vocabulary-sized output', 'create a Receiver module that decodes messages into class predictions using relaxed embeddings and hidden layers', 'test the LeNet forward pass by passing an image tensor and verifying the 400-dimensional output shape', 'review the Sender and Receiver modules for language bottleneck MNIST classification game architecture', 'run the MNIST classification training loop with sender and receiver models using Gumbel-Softmax', 'build a SymbolGameGS with a Sender and Receiver model using GumbelSoftmaxWrapper for communication', 'create a loss function that computes NLL loss and accuracy from receiver output and labels', 'test the CallbackEvaluator intervention on a test loader with Gumbel-Softmax game loss', 'review the EarlyStopperAccuracy callback that stops training when accuracy exceeds a threshold']
```

Usage

```
{'run_mnist_classification_training': 'run the MNIST classification training loop with sender and receiver models using Gumbel-Softmax', 'build_symbolgamegs_with_sender_receiver': 'build a SymbolGameGS with a Sender and Receiver model using GumbelSoftmaxWrapper for communication', 'create_diff_loss_symbol': 'create a loss function that computes NLL loss and accuracy from receiver output and labels', 'test_callback_evaluator_intervention': 'test the CallbackEvaluator intervention on a test loader with Gumbel-Softmax game loss', 'review_early_stopper_accuracy': 'review the EarlyStopperAccuracy callback that stops training when accuracy exceeds a threshold'}
```

