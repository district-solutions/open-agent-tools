# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/language_bottleneck/mnist_adv/archs.py

Prompts

```
['build a LeNet CNN model with two conv layers and a fully connected layer for MNIST image feature extraction', 'create a Sender module that encodes MNIST images into messages using LeNet and a configurable output channel', 'create a Receiver module that decodes messages into class predictions using RelaxedEmbedding and a linear layer', 'test the Sender forward pass with image input and aux input to verify log_softmax or linear output', 'test the Receiver forward pass with a message tensor to verify class prediction log_softmax output', 'run the MNIST adversarial language bottleneck training with sender and receiver networks', 'build a negative log likelihood loss function that returns accuracy metrics for the receiver', 'create an argument parser for temperature, early stopping, softmax, and linear channel options', 'test the SymbolGameGS game with a sender, receiver, and custom loss function', 'review the AlwaysRelaxedWrapper sender wrapper used for Gumbel-Softmax temperature control']
```

Usage

```
{'build_LeNet_CNN': 'build a LeNet CNN model with two conv layers and a fully connected layer for MNIST image feature extraction', 'create_Sender_module': 'create a Sender module that encodes MNIST images into messages using LeNet and a configurable output channel', 'create_Receiver_module': 'create a Receiver module that decodes messages into class predictions using RelaxedEmbedding and a linear layer', 'test_Sender_forward': 'test the Sender forward pass with image input and aux input to verify log_softmax or linear output', 'test_Receiver_forward': 'test the Receiver forward pass with a message tensor to verify class prediction log_softmax output'}
```

## File: facebookresearch_egg/egg/zoo/language_bottleneck/mnist_adv/train.py

Prompts

```
['build a LeNet CNN model with two conv layers and a fully connected layer for MNIST image feature extraction', 'create a Sender module that encodes MNIST images into messages using LeNet and a configurable output channel', 'create a Receiver module that decodes messages into class predictions using RelaxedEmbedding and a linear layer', 'test the Sender forward pass with image input and aux input to verify log_softmax or linear output', 'test the Receiver forward pass with a message tensor to verify class prediction log_softmax output', 'run the MNIST adversarial language bottleneck training with sender and receiver networks', 'build a negative log likelihood loss function that returns accuracy metrics for the receiver', 'create an argument parser for temperature, early stopping, softmax, and linear channel options', 'test the SymbolGameGS game with a sender, receiver, and custom loss function', 'review the AlwaysRelaxedWrapper sender wrapper used for Gumbel-Softmax temperature control']
```

Usage

```
{'run_mnist_adv_training': 'run the MNIST adversarial language bottleneck training with sender and receiver networks', 'build_diff_loss_symbol': 'build a negative log likelihood loss function that returns accuracy metrics for the receiver', 'create_get_params': 'create an argument parser for temperature, early stopping, softmax, and linear channel options', 'test_SymbolGameGS': 'test the SymbolGameGS game with a sender, receiver, and custom loss function', 'review_AlwaysRelaxedWrapper': 'review the AlwaysRelaxedWrapper sender wrapper used for Gumbel-Softmax temperature control'}
```

