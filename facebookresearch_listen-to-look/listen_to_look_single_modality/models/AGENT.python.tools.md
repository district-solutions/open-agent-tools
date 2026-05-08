# Agent Python Tools

- repo: facebookresearch/listen-to-look
- repo_uri: https://github.com/facebookresearch/listen-to-look

## File: facebookresearch_listen-to-look/listen_to_look_single_modality/models/audioPreview_model.py

Prompts

```
['build an AudioPreviewModel instance with a net_classifier and args for audio preview prediction', 'run the forward pass of AudioPreviewModel with features, ground truth predictions, and feature masks', 'run a single forward step of AudioPreviewModel using features, feature banks, masks, and hidden state', 'review the AudioPreviewModel forward method to understand the episodic attention-based feature selection loop', 'refactor the AudioPreviewModel LSTMCell to swap weight normalization or change hidden size configuration', 'build a PyTorch ImageAudioClassifyModel with a classifier network and args for image-audio classification', 'run the forward pass of ImageAudioClassifyModel with an image-audio embedding tensor', 'test the ImageAudioClassifyModel forward pass with sample image-audio embedding inputs', 'refactor the ImageAudioClassifyModel forward method to support additional output modes', 'review the ImageAudioClassifyModel class and its feature extraction conditional logic', 'build an AudioPreviewModel LSTM network using a classifier net and optional pretrained weights', 'build an ImageAudioClassifyModel network using a classifier net and optional pretrained weights', 'build a ClassifierNet with configurable input dimensions and number of classes', 'review the ModelBuilder class and its three network builder methods', 'refactor the ModelBuilder class to support additional model types or weight loading strategies', 'build a multi-layer perceptron with configurable hidden dims, batch norm, relu, and dropout', 'create a Conv2d layer with optional batch normalization and relu activation', 'build a VisualNet feature extractor from a pretrained ResNet for image embeddings', 'build an AudioNet feature extractor from a pretrained ResNet for audio spectrogram embeddings', 'build a ClassifierNet linear classifier for finetuning on a specified number of classes']
```

Usage

```
{'build_AudioPreviewModel': 'build an AudioPreviewModel instance with a net_classifier and args for audio preview prediction', 'run_forward_AudioPreviewModel': 'run the forward pass of AudioPreviewModel with features, ground truth predictions, and feature masks', 'run_forwardOne_AudioPreviewModel': 'run a single forward step of AudioPreviewModel using features, feature banks, masks, and hidden state', 'review_AudioPreviewModel_forward': 'review the AudioPreviewModel forward method to understand the episodic attention-based feature selection loop', 'refactor_AudioPreviewModel_LSTMCell': 'refactor the AudioPreviewModel LSTMCell to swap weight normalization or change hidden size configuration'}
```

## File: facebookresearch_listen-to-look/listen_to_look_single_modality/models/imageAudioClassify_model.py

Prompts

```
['build an AudioPreviewModel instance with a net_classifier and args for audio preview prediction', 'run the forward pass of AudioPreviewModel with features, ground truth predictions, and feature masks', 'run a single forward step of AudioPreviewModel using features, feature banks, masks, and hidden state', 'review the AudioPreviewModel forward method to understand the episodic attention-based feature selection loop', 'refactor the AudioPreviewModel LSTMCell to swap weight normalization or change hidden size configuration', 'build a PyTorch ImageAudioClassifyModel with a classifier network and args for image-audio classification', 'run the forward pass of ImageAudioClassifyModel with an image-audio embedding tensor', 'test the ImageAudioClassifyModel forward pass with sample image-audio embedding inputs', 'refactor the ImageAudioClassifyModel forward method to support additional output modes', 'review the ImageAudioClassifyModel class and its feature extraction conditional logic', 'build an AudioPreviewModel LSTM network using a classifier net and optional pretrained weights', 'build an ImageAudioClassifyModel network using a classifier net and optional pretrained weights', 'build a ClassifierNet with configurable input dimensions and number of classes', 'review the ModelBuilder class and its three network builder methods', 'refactor the ModelBuilder class to support additional model types or weight loading strategies', 'build a multi-layer perceptron with configurable hidden dims, batch norm, relu, and dropout', 'create a Conv2d layer with optional batch normalization and relu activation', 'build a VisualNet feature extractor from a pretrained ResNet for image embeddings', 'build an AudioNet feature extractor from a pretrained ResNet for audio spectrogram embeddings', 'build a ClassifierNet linear classifier for finetuning on a specified number of classes']
```

Usage

```
{'build_ImageAudioClassifyModel': 'build a PyTorch ImageAudioClassifyModel with a classifier network and args for image-audio classification', 'run_forward_pass': 'run the forward pass of ImageAudioClassifyModel with an image-audio embedding tensor', 'test_ImageAudioClassifyModel': 'test the ImageAudioClassifyModel forward pass with sample image-audio embedding inputs', 'refactor_ImageAudioClassifyModel': 'refactor the ImageAudioClassifyModel forward method to support additional output modes', 'review_ImageAudioClassifyModel': 'review the ImageAudioClassifyModel class and its feature extraction conditional logic'}
```

## File: facebookresearch_listen-to-look/listen_to_look_single_modality/models/models.py

Prompts

```
['build an AudioPreviewModel instance with a net_classifier and args for audio preview prediction', 'run the forward pass of AudioPreviewModel with features, ground truth predictions, and feature masks', 'run a single forward step of AudioPreviewModel using features, feature banks, masks, and hidden state', 'review the AudioPreviewModel forward method to understand the episodic attention-based feature selection loop', 'refactor the AudioPreviewModel LSTMCell to swap weight normalization or change hidden size configuration', 'build a PyTorch ImageAudioClassifyModel with a classifier network and args for image-audio classification', 'run the forward pass of ImageAudioClassifyModel with an image-audio embedding tensor', 'test the ImageAudioClassifyModel forward pass with sample image-audio embedding inputs', 'refactor the ImageAudioClassifyModel forward method to support additional output modes', 'review the ImageAudioClassifyModel class and its feature extraction conditional logic', 'build an AudioPreviewModel LSTM network using a classifier net and optional pretrained weights', 'build an ImageAudioClassifyModel network using a classifier net and optional pretrained weights', 'build a ClassifierNet with configurable input dimensions and number of classes', 'review the ModelBuilder class and its three network builder methods', 'refactor the ModelBuilder class to support additional model types or weight loading strategies', 'build a multi-layer perceptron with configurable hidden dims, batch norm, relu, and dropout', 'create a Conv2d layer with optional batch normalization and relu activation', 'build a VisualNet feature extractor from a pretrained ResNet for image embeddings', 'build an AudioNet feature extractor from a pretrained ResNet for audio spectrogram embeddings', 'build a ClassifierNet linear classifier for finetuning on a specified number of classes']
```

Usage

```
{'build_audioPreviewLSTM': 'build an AudioPreviewModel LSTM network using a classifier net and optional pretrained weights', 'build_imageAudioClassifierNet': 'build an ImageAudioClassifyModel network using a classifier net and optional pretrained weights', 'build_classifierNet': 'build a ClassifierNet with configurable input dimensions and number of classes', 'review_ModelBuilder': 'review the ModelBuilder class and its three network builder methods', 'refactor_ModelBuilder': 'refactor the ModelBuilder class to support additional model types or weight loading strategies'}
```

## File: facebookresearch_listen-to-look/listen_to_look_single_modality/models/networks.py

Prompts

```
['build an AudioPreviewModel instance with a net_classifier and args for audio preview prediction', 'run the forward pass of AudioPreviewModel with features, ground truth predictions, and feature masks', 'run a single forward step of AudioPreviewModel using features, feature banks, masks, and hidden state', 'review the AudioPreviewModel forward method to understand the episodic attention-based feature selection loop', 'refactor the AudioPreviewModel LSTMCell to swap weight normalization or change hidden size configuration', 'build a PyTorch ImageAudioClassifyModel with a classifier network and args for image-audio classification', 'run the forward pass of ImageAudioClassifyModel with an image-audio embedding tensor', 'test the ImageAudioClassifyModel forward pass with sample image-audio embedding inputs', 'refactor the ImageAudioClassifyModel forward method to support additional output modes', 'review the ImageAudioClassifyModel class and its feature extraction conditional logic', 'build an AudioPreviewModel LSTM network using a classifier net and optional pretrained weights', 'build an ImageAudioClassifyModel network using a classifier net and optional pretrained weights', 'build a ClassifierNet with configurable input dimensions and number of classes', 'review the ModelBuilder class and its three network builder methods', 'refactor the ModelBuilder class to support additional model types or weight loading strategies', 'build a multi-layer perceptron with configurable hidden dims, batch norm, relu, and dropout', 'create a Conv2d layer with optional batch normalization and relu activation', 'build a VisualNet feature extractor from a pretrained ResNet for image embeddings', 'build an AudioNet feature extractor from a pretrained ResNet for audio spectrogram embeddings', 'build a ClassifierNet linear classifier for finetuning on a specified number of classes']
```

Usage

```
{'build_mlp': 'build a multi-layer perceptron with configurable hidden dims, batch norm, relu, and dropout', 'create_conv': 'create a Conv2d layer with optional batch normalization and relu activation', 'build_visualnet': 'build a VisualNet feature extractor from a pretrained ResNet for image embeddings', 'build_audionet': 'build an AudioNet feature extractor from a pretrained ResNet for audio spectrogram embeddings', 'build_classifiernet': 'build a ClassifierNet linear classifier for finetuning on a specified number of classes'}
```

