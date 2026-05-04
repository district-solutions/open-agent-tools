# Agent Python Tools

- repo: facebookresearch/2.5d-visual-sound
- repo_uri: https://github.com/facebookresearch/2.5d-visual-sound

## File: facebookresearch_2.5d-visual-sound/demo.py

Prompts

```
['run the demo script to spatialize binaural audio from a video using the trained model', 'run audio_normalize to normalize audio samples to a desired RMS level and return the normalizer factor', 'run ModelBuilder to build visual and audio neural network components with pretrained weights', 'run the AudioVisualModel forward pass with audio spectrograms and video frames to predict binaural audio', 'run generate_spectrogram to convert a mono audio signal segment into a spectrogram tensor', 'run the training script to train an audio-visual model for binaural sound synthesis', 'create an optimizer for visual and audio networks using SGD or Adam with separate learning rates', 'decrease the learning rate of all optimizer param groups by a specified decay factor', 'display and compute the average validation loss over a set number of validation batches', 'save visual and audio model checkpoints as latest, best, or epoch-specific PyTorch state dicts']
```

Usage

```
{'run_2.5d_visual_sound_demo': 'run the demo script to spatialize binaural audio from a video using the trained model', 'run_audio_normalize': 'run audio_normalize to normalize audio samples to a desired RMS level and return the normalizer factor', 'run_model_builder': 'run ModelBuilder to build visual and audio neural network components with pretrained weights', 'run_audiovisual_model': 'run the AudioVisualModel forward pass with audio spectrograms and video frames to predict binaural audio', 'run_generate_spectrogram': 'run generate_spectrogram to convert a mono audio signal segment into a spectrogram tensor'}
```

## File: facebookresearch_2.5d-visual-sound/train.py

Prompts

```
['run the demo script to spatialize binaural audio from a video using the trained model', 'run audio_normalize to normalize audio samples to a desired RMS level and return the normalizer factor', 'run ModelBuilder to build visual and audio neural network components with pretrained weights', 'run the AudioVisualModel forward pass with audio spectrograms and video frames to predict binaural audio', 'run generate_spectrogram to convert a mono audio signal segment into a spectrogram tensor', 'run the training script to train an audio-visual model for binaural sound synthesis', 'create an optimizer for visual and audio networks using SGD or Adam with separate learning rates', 'decrease the learning rate of all optimizer param groups by a specified decay factor', 'display and compute the average validation loss over a set number of validation batches', 'save visual and audio model checkpoints as latest, best, or epoch-specific PyTorch state dicts']
```

Usage

```
{'run_train_audiovisual_model': 'run the training script to train an audio-visual model for binaural sound synthesis', 'create_optimizer_for_nets': 'create an optimizer for visual and audio networks using SGD or Adam with separate learning rates', 'decrease_learning_rate_optimizer': 'decrease the learning rate of all optimizer param groups by a specified decay factor', 'display_validation_loss': 'display and compute the average validation loss over a set number of validation batches', 'save_model_checkpoints': 'save visual and audio model checkpoints as latest, best, or epoch-specific PyTorch state dicts'}
```

