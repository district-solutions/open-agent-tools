# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/signal_game/archs.py

Prompts

```
['build an InformedSender neural network module for signal game sender with configurable game size and vocab size', 'build a Receiver neural network module for signal game receiver with reinforce or non-reinforce mode', 'run the InformedSender forward pass to produce log-softmax logits over vocab from game features', 'run the Receiver forward pass to produce log-softmax probabilities over game items from a signal', 'review the InformedSender return_embeddings method that embeds and concatenates per-item feature vectors', 'create an ImageNetFeat dataset that loads and normalizes ImageNet features from an HDF5 file', 'build an ImagenetLoader DataLoader that iterates over batches using a configurable seed and batch count', 'review the _BatchIterator get_batch method that generates sender and receiver image tensors with random permutations', 'test the ImageNetFeat create_obj2id method that maps concept labels to lists of image indices', 'summarize the ImageNetFeat __getitem__ method that returns a normalized feature tensor and its index', 'run the signal game training loop with Reinforce or Gumbel-Softmax mode on ImageNet features', 'build a SymbolGameReinforce or SymbolGameGS game with an InformedSender and Receiver for communication learning', 'create an accuracy-based loss or NLL loss function for the signal game receiver output', 'parse command line arguments for signal game training including game size, embedding size, and mode', 'review the get_game function that constructs sender, receiver, and game objects based on training mode']
```

Usage

```
{'build_informed_sender': 'build an InformedSender neural network module for signal game sender with configurable game size and vocab size', 'build_receiver': 'build a Receiver neural network module for signal game receiver with reinforce or non-reinforce mode', 'run_informed_sender_forward': 'run the InformedSender forward pass to produce log-softmax logits over vocab from game features', 'run_receiver_forward': 'run the Receiver forward pass to produce log-softmax probabilities over game items from a signal', 'review_informed_sender_return_embeddings': 'review the InformedSender return_embeddings method that embeds and concatenates per-item feature vectors'}
```

## File: facebookresearch_egg/egg/zoo/signal_game/features.py

Prompts

```
['build an InformedSender neural network module for signal game sender with configurable game size and vocab size', 'build a Receiver neural network module for signal game receiver with reinforce or non-reinforce mode', 'run the InformedSender forward pass to produce log-softmax logits over vocab from game features', 'run the Receiver forward pass to produce log-softmax probabilities over game items from a signal', 'review the InformedSender return_embeddings method that embeds and concatenates per-item feature vectors', 'create an ImageNetFeat dataset that loads and normalizes ImageNet features from an HDF5 file', 'build an ImagenetLoader DataLoader that iterates over batches using a configurable seed and batch count', 'review the _BatchIterator get_batch method that generates sender and receiver image tensors with random permutations', 'test the ImageNetFeat create_obj2id method that maps concept labels to lists of image indices', 'summarize the ImageNetFeat __getitem__ method that returns a normalized feature tensor and its index', 'run the signal game training loop with Reinforce or Gumbel-Softmax mode on ImageNet features', 'build a SymbolGameReinforce or SymbolGameGS game with an InformedSender and Receiver for communication learning', 'create an accuracy-based loss or NLL loss function for the signal game receiver output', 'parse command line arguments for signal game training including game size, embedding size, and mode', 'review the get_game function that constructs sender, receiver, and game objects based on training mode']
```

Usage

```
{'create_ImageNetFeat_dataset': 'create an ImageNetFeat dataset that loads and normalizes ImageNet features from an HDF5 file', 'build_ImagenetLoader_dataloader': 'build an ImagenetLoader DataLoader that iterates over batches using a configurable seed and batch count', 'review_BatchIterator_get_batch': 'review the _BatchIterator get_batch method that generates sender and receiver image tensors with random permutations', 'test_ImageNetFeat_create_obj2id': 'test the ImageNetFeat create_obj2id method that maps concept labels to lists of image indices', 'summarize_ImageNetFeat_getitem': 'summarize the ImageNetFeat __getitem__ method that returns a normalized feature tensor and its index'}
```

## File: facebookresearch_egg/egg/zoo/signal_game/train.py

Prompts

```
['build an InformedSender neural network module for signal game sender with configurable game size and vocab size', 'build a Receiver neural network module for signal game receiver with reinforce or non-reinforce mode', 'run the InformedSender forward pass to produce log-softmax logits over vocab from game features', 'run the Receiver forward pass to produce log-softmax probabilities over game items from a signal', 'review the InformedSender return_embeddings method that embeds and concatenates per-item feature vectors', 'create an ImageNetFeat dataset that loads and normalizes ImageNet features from an HDF5 file', 'build an ImagenetLoader DataLoader that iterates over batches using a configurable seed and batch count', 'review the _BatchIterator get_batch method that generates sender and receiver image tensors with random permutations', 'test the ImageNetFeat create_obj2id method that maps concept labels to lists of image indices', 'summarize the ImageNetFeat __getitem__ method that returns a normalized feature tensor and its index', 'run the signal game training loop with Reinforce or Gumbel-Softmax mode on ImageNet features', 'build a SymbolGameReinforce or SymbolGameGS game with an InformedSender and Receiver for communication learning', 'create an accuracy-based loss or NLL loss function for the signal game receiver output', 'parse command line arguments for signal game training including game size, embedding size, and mode', 'review the get_game function that constructs sender, receiver, and game objects based on training mode']
```

Usage

```
{'run_signal_game_training': 'run the signal game training loop with Reinforce or Gumbel-Softmax mode on ImageNet features', 'build_symbol_game': 'build a SymbolGameReinforce or SymbolGameGS game with an InformedSender and Receiver for communication learning', 'create_loss_function': 'create an accuracy-based loss or NLL loss function for the signal game receiver output', 'parse_training_arguments': 'parse command line arguments for signal game training including game size, embedding size, and mode', 'review_get_game': 'review the get_game function that constructs sender, receiver, and game objects based on training mode'}
```

