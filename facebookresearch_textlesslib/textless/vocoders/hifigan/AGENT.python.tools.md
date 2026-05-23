# Agent Python Tools

- repo: facebookresearch/textlesslib
- repo_uri: https://github.com/facebookresearch/textlesslib

## File: facebookresearch_textlesslib/textless/vocoders/hifigan/generator.py

Prompts

```
['build a HiFi-GAN Generator from a config dict to synthesize waveforms from mel spectrograms', 'build a CodeGenerator from a config dict to generate waveforms from discrete speech codes', 'run the Generator forward pass on a mel spectrogram tensor to produce a waveform', 'run the CodeGenerator forward pass with speaker and style embeddings for multi-speaker synthesis', 'remove weight normalization from a trained Generator model before inference to speed up forward passes', 'create a ResBlock instance with 64 channels and default kernel size 3', 'run the ResBlock forward pass on a tensor to apply residual convolution', 'remove weight normalization from all conv layers in a ResBlock instance', 'initialize convolution layer weights with a normal distribution using init_weights', 'calculate the padding value for a given kernel size and dilation factor', 'create a CodeHiFiGANVocoder instance from a model path and config file', 'run the CodeHiFiGANVocoder forward pass with discrete codes to synthesize audio', 'load a CodeHiFiGANVocoder by dense model name, quantizer name, and vocab size', 'load speaker and style metadata from text files for a vocoder', 'preprocess discrete codes from string, list, or numpy array into a torch long tensor']
```

Usage

```
{'build_hifigan_generator': 'build a HiFi-GAN Generator from a config dict to synthesize waveforms from mel spectrograms', 'build_code_generator': 'build a CodeGenerator from a config dict to generate waveforms from discrete speech codes', 'run_generator_forward': 'run the Generator forward pass on a mel spectrogram tensor to produce a waveform', 'run_code_generator_multispkr': 'run the CodeGenerator forward pass with speaker and style embeddings for multi-speaker synthesis', 'remove_weight_norm_generator': 'remove weight normalization from a trained Generator model before inference to speed up forward passes'}
```

## File: facebookresearch_textlesslib/textless/vocoders/hifigan/resblock.py

Prompts

```
['build a HiFi-GAN Generator from a config dict to synthesize waveforms from mel spectrograms', 'build a CodeGenerator from a config dict to generate waveforms from discrete speech codes', 'run the Generator forward pass on a mel spectrogram tensor to produce a waveform', 'run the CodeGenerator forward pass with speaker and style embeddings for multi-speaker synthesis', 'remove weight normalization from a trained Generator model before inference to speed up forward passes', 'create a ResBlock instance with 64 channels and default kernel size 3', 'run the ResBlock forward pass on a tensor to apply residual convolution', 'remove weight normalization from all conv layers in a ResBlock instance', 'initialize convolution layer weights with a normal distribution using init_weights', 'calculate the padding value for a given kernel size and dilation factor', 'create a CodeHiFiGANVocoder instance from a model path and config file', 'run the CodeHiFiGANVocoder forward pass with discrete codes to synthesize audio', 'load a CodeHiFiGANVocoder by dense model name, quantizer name, and vocab size', 'load speaker and style metadata from text files for a vocoder', 'preprocess discrete codes from string, list, or numpy array into a torch long tensor']
```

Usage

```
{'create_resblock_instance': 'create a ResBlock instance with 64 channels and default kernel size 3', 'run_resblock_forward': 'run the ResBlock forward pass on a tensor to apply residual convolution', 'remove_weight_norm_resblock': 'remove weight normalization from all conv layers in a ResBlock instance', 'init_conv_weights': 'initialize convolution layer weights with a normal distribution using init_weights', 'calculate_padding': 'calculate the padding value for a given kernel size and dilation factor'}
```

## File: facebookresearch_textlesslib/textless/vocoders/hifigan/vocoder.py

Prompts

```
['build a HiFi-GAN Generator from a config dict to synthesize waveforms from mel spectrograms', 'build a CodeGenerator from a config dict to generate waveforms from discrete speech codes', 'run the Generator forward pass on a mel spectrogram tensor to produce a waveform', 'run the CodeGenerator forward pass with speaker and style embeddings for multi-speaker synthesis', 'remove weight normalization from a trained Generator model before inference to speed up forward passes', 'create a ResBlock instance with 64 channels and default kernel size 3', 'run the ResBlock forward pass on a tensor to apply residual convolution', 'remove weight normalization from all conv layers in a ResBlock instance', 'initialize convolution layer weights with a normal distribution using init_weights', 'calculate the padding value for a given kernel size and dilation factor', 'create a CodeHiFiGANVocoder instance from a model path and config file', 'run the CodeHiFiGANVocoder forward pass with discrete codes to synthesize audio', 'load a CodeHiFiGANVocoder by dense model name, quantizer name, and vocab size', 'load speaker and style metadata from text files for a vocoder', 'preprocess discrete codes from string, list, or numpy array into a torch long tensor']
```

Usage

```
{'create_CodeHiFiGANVocoder': 'create a CodeHiFiGANVocoder instance from a model path and config file', 'run_CodeHiFiGANVocoder_forward': 'run the CodeHiFiGANVocoder forward pass with discrete codes to synthesize audio', 'load_CodeHiFiGANVocoder_by_name': 'load a CodeHiFiGANVocoder by dense model name, quantizer name, and vocab size', 'load_vocoder_meta': 'load speaker and style metadata from text files for a vocoder', 'preprocess_code': 'preprocess discrete codes from string, list, or numpy array into a torch long tensor'}
```

