# Agent Python Tools

- repo: facebookresearch/2.5d-visual-sound
- repo_uri: https://github.com/facebookresearch/2.5d-visual-sound

## File: facebookresearch_2.5d-visual-sound/models/audioVisual_model.py

Prompts

```
['initialize an AudioVisualModel with visual and audio network modules and options', 'run forward pass on frame and audio spectrogram inputs to predict binaural spectrogram', 'get the model name string from an AudioVisualModel instance', 'review the AudioVisualModel forward method complex masking logic for spectrogram prediction', 'refactor the AudioVisualModel forward method to replace deprecated Variable usage with modern tensors', 'create an L1Loss criterion to compute weighted mean absolute error between predictions and targets', 'create an L2Loss criterion to compute weighted mean squared error between predictions and targets', 'create an MSELoss criterion to compute mean squared error between predictions and targets', 'create a BCELoss criterion to compute binary cross entropy with optional weight between predictions and targets', 'create a BCEWithLogitsLoss criterion to compute binary cross entropy with logits and optional weight', 'build a visual feature extraction network using a pretrained ResNet18 backbone', 'build a 5-layer U-Net audio network with configurable feature channels and input/output dimensions', 'build a visual network and load pretrained weights from a specified checkpoint file', 'build an audio U-Net network and load pretrained weights from a specified checkpoint file', 'review the ModelBuilder class and its build_visual and build_audio methods for the 2.5D visual sound model', 'create a U-Net downsampling convolution block with Conv2d, BatchNorm2d, and LeakyReLU', 'create a U-Net upsampling transposed convolution block with ConvTranspose2d and ReLU or Sigmoid', 'create a configurable Conv2d block with optional BatchNorm2d and ReLU activation', 'build a VisualNet module that extracts features from a pretrained ResNet model', 'build an AudioNet U-Net model that generates masks from audio and visual features']
```

Usage

```
{'init_audiovisualmodel': 'initialize an AudioVisualModel with visual and audio network modules and options', 'forward_audiovisualmodel': 'run forward pass on frame and audio spectrogram inputs to predict binaural spectrogram', 'name_audiovisualmodel': 'get the model name string from an AudioVisualModel instance', 'review_audiovisualmodel_forward': 'review the AudioVisualModel forward method complex masking logic for spectrogram prediction', 'refactor_audiovisualmodel_variables': 'refactor the AudioVisualModel forward method to replace deprecated Variable usage with modern tensors'}
```

## File: facebookresearch_2.5d-visual-sound/models/criterion.py

Prompts

```
['initialize an AudioVisualModel with visual and audio network modules and options', 'run forward pass on frame and audio spectrogram inputs to predict binaural spectrogram', 'get the model name string from an AudioVisualModel instance', 'review the AudioVisualModel forward method complex masking logic for spectrogram prediction', 'refactor the AudioVisualModel forward method to replace deprecated Variable usage with modern tensors', 'create an L1Loss criterion to compute weighted mean absolute error between predictions and targets', 'create an L2Loss criterion to compute weighted mean squared error between predictions and targets', 'create an MSELoss criterion to compute mean squared error between predictions and targets', 'create a BCELoss criterion to compute binary cross entropy with optional weight between predictions and targets', 'create a BCEWithLogitsLoss criterion to compute binary cross entropy with logits and optional weight', 'build a visual feature extraction network using a pretrained ResNet18 backbone', 'build a 5-layer U-Net audio network with configurable feature channels and input/output dimensions', 'build a visual network and load pretrained weights from a specified checkpoint file', 'build an audio U-Net network and load pretrained weights from a specified checkpoint file', 'review the ModelBuilder class and its build_visual and build_audio methods for the 2.5D visual sound model', 'create a U-Net downsampling convolution block with Conv2d, BatchNorm2d, and LeakyReLU', 'create a U-Net upsampling transposed convolution block with ConvTranspose2d and ReLU or Sigmoid', 'create a configurable Conv2d block with optional BatchNorm2d and ReLU activation', 'build a VisualNet module that extracts features from a pretrained ResNet model', 'build an AudioNet U-Net model that generates masks from audio and visual features']
```

Usage

```
{'create_L1Loss': 'create an L1Loss criterion to compute weighted mean absolute error between predictions and targets', 'create_L2Loss': 'create an L2Loss criterion to compute weighted mean squared error between predictions and targets', 'create_MSELoss': 'create an MSELoss criterion to compute mean squared error between predictions and targets', 'create_BCELoss': 'create a BCELoss criterion to compute binary cross entropy with optional weight between predictions and targets', 'create_BCEWithLogitsLoss': 'create a BCEWithLogitsLoss criterion to compute binary cross entropy with logits and optional weight'}
```

## File: facebookresearch_2.5d-visual-sound/models/models.py

Prompts

```
['initialize an AudioVisualModel with visual and audio network modules and options', 'run forward pass on frame and audio spectrogram inputs to predict binaural spectrogram', 'get the model name string from an AudioVisualModel instance', 'review the AudioVisualModel forward method complex masking logic for spectrogram prediction', 'refactor the AudioVisualModel forward method to replace deprecated Variable usage with modern tensors', 'create an L1Loss criterion to compute weighted mean absolute error between predictions and targets', 'create an L2Loss criterion to compute weighted mean squared error between predictions and targets', 'create an MSELoss criterion to compute mean squared error between predictions and targets', 'create a BCELoss criterion to compute binary cross entropy with optional weight between predictions and targets', 'create a BCEWithLogitsLoss criterion to compute binary cross entropy with logits and optional weight', 'build a visual feature extraction network using a pretrained ResNet18 backbone', 'build a 5-layer U-Net audio network with configurable feature channels and input/output dimensions', 'build a visual network and load pretrained weights from a specified checkpoint file', 'build an audio U-Net network and load pretrained weights from a specified checkpoint file', 'review the ModelBuilder class and its build_visual and build_audio methods for the 2.5D visual sound model', 'create a U-Net downsampling convolution block with Conv2d, BatchNorm2d, and LeakyReLU', 'create a U-Net upsampling transposed convolution block with ConvTranspose2d and ReLU or Sigmoid', 'create a configurable Conv2d block with optional BatchNorm2d and ReLU activation', 'build a VisualNet module that extracts features from a pretrained ResNet model', 'build an AudioNet U-Net model that generates masks from audio and visual features']
```

Usage

```
{'build_visual_net': 'build a visual feature extraction network using a pretrained ResNet18 backbone', 'build_audio_net': 'build a 5-layer U-Net audio network with configurable feature channels and input/output dimensions', 'build_visual_with_weights': 'build a visual network and load pretrained weights from a specified checkpoint file', 'build_audio_with_weights': 'build an audio U-Net network and load pretrained weights from a specified checkpoint file', 'review_modelbuilder_class': 'review the ModelBuilder class and its build_visual and build_audio methods for the 2.5D visual sound model'}
```

## File: facebookresearch_2.5d-visual-sound/models/networks.py

Prompts

```
['initialize an AudioVisualModel with visual and audio network modules and options', 'run forward pass on frame and audio spectrogram inputs to predict binaural spectrogram', 'get the model name string from an AudioVisualModel instance', 'review the AudioVisualModel forward method complex masking logic for spectrogram prediction', 'refactor the AudioVisualModel forward method to replace deprecated Variable usage with modern tensors', 'create an L1Loss criterion to compute weighted mean absolute error between predictions and targets', 'create an L2Loss criterion to compute weighted mean squared error between predictions and targets', 'create an MSELoss criterion to compute mean squared error between predictions and targets', 'create a BCELoss criterion to compute binary cross entropy with optional weight between predictions and targets', 'create a BCEWithLogitsLoss criterion to compute binary cross entropy with logits and optional weight', 'build a visual feature extraction network using a pretrained ResNet18 backbone', 'build a 5-layer U-Net audio network with configurable feature channels and input/output dimensions', 'build a visual network and load pretrained weights from a specified checkpoint file', 'build an audio U-Net network and load pretrained weights from a specified checkpoint file', 'review the ModelBuilder class and its build_visual and build_audio methods for the 2.5D visual sound model', 'create a U-Net downsampling convolution block with Conv2d, BatchNorm2d, and LeakyReLU', 'create a U-Net upsampling transposed convolution block with ConvTranspose2d and ReLU or Sigmoid', 'create a configurable Conv2d block with optional BatchNorm2d and ReLU activation', 'build a VisualNet module that extracts features from a pretrained ResNet model', 'build an AudioNet U-Net model that generates masks from audio and visual features']
```

Usage

```
{'create_unet_conv_block': 'create a U-Net downsampling convolution block with Conv2d, BatchNorm2d, and LeakyReLU', 'create_unet_upconv_block': 'create a U-Net upsampling transposed convolution block with ConvTranspose2d and ReLU or Sigmoid', 'create_conv_block': 'create a configurable Conv2d block with optional BatchNorm2d and ReLU activation', 'build_visualnet': 'build a VisualNet module that extracts features from a pretrained ResNet model', 'build_audionet': 'build an AudioNet U-Net model that generates masks from audio and visual features'}
```

