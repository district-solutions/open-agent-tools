# Agent Python Tools

- repo: facebookresearch/audioseal
- repo_uri: https://github.com/facebookresearch/audioseal

## File: facebookresearch_audioseal/src/audioseal/builder.py

Prompts

```
['create an AudioSealWM watermark generator from an AudioSealWMConfig with optional device and dtype', 'create an AudioSealDetector from an AudioSealDetectorConfig with optional device and dtype', 'convert a dataclass or OmegaConf DictConfig object to a plain Python dictionary using as_dict', 'build a SEANetConfig dataclass with encoder and decoder hyperparameters like channels, filters, and ratios', 'build an AudioSealWMConfig dataclass with nbits, SEANetConfig, and DecoderConfig for watermark generation', 'load an AudioSeal watermark generator model from a model card or checkpoint path', 'load an AudioSeal detector model from a model card or checkpoint path', 'load a model checkpoint from a local file, Hugging Face repo, or HTTPS URL', 'parse a model card or checkpoint path to extract the config and state dict', 'convert a legacy state dict to be compatible with TorchScripted SEANet models on Python 3.10+', 'apply a watermark to an audio tensor using AudioSealWM forward method with a secret message', 'detect watermark presence and extract the secret message from an audio tensor using AudioSealDetector', 'generate a watermark tensor from an audio signal using AudioSealWM get_watermark method', 'normalize audio signal loudness to a reference RMS level using NormalizationProcessor loudness_normalization', 'normalize a watermark signal to fit inside the envelope of the original audio using fit_inside_envelope']
```

Usage

```
{'create_generator_from_config': 'create an AudioSealWM watermark generator from an AudioSealWMConfig with optional device and dtype', 'create_detector_from_config': 'create an AudioSealDetector from an AudioSealDetectorConfig with optional device and dtype', 'convert_config_to_dict': 'convert a dataclass or OmegaConf DictConfig object to a plain Python dictionary using as_dict', 'build_seanet_config': 'build a SEANetConfig dataclass with encoder and decoder hyperparameters like channels, filters, and ratios', 'build_audiosealwm_config': 'build an AudioSealWMConfig dataclass with nbits, SEANetConfig, and DecoderConfig for watermark generation'}
```

## File: facebookresearch_audioseal/src/audioseal/loader.py

Prompts

```
['create an AudioSealWM watermark generator from an AudioSealWMConfig with optional device and dtype', 'create an AudioSealDetector from an AudioSealDetectorConfig with optional device and dtype', 'convert a dataclass or OmegaConf DictConfig object to a plain Python dictionary using as_dict', 'build a SEANetConfig dataclass with encoder and decoder hyperparameters like channels, filters, and ratios', 'build an AudioSealWMConfig dataclass with nbits, SEANetConfig, and DecoderConfig for watermark generation', 'load an AudioSeal watermark generator model from a model card or checkpoint path', 'load an AudioSeal detector model from a model card or checkpoint path', 'load a model checkpoint from a local file, Hugging Face repo, or HTTPS URL', 'parse a model card or checkpoint path to extract the config and state dict', 'convert a legacy state dict to be compatible with TorchScripted SEANet models on Python 3.10+', 'apply a watermark to an audio tensor using AudioSealWM forward method with a secret message', 'detect watermark presence and extract the secret message from an audio tensor using AudioSealDetector', 'generate a watermark tensor from an audio signal using AudioSealWM get_watermark method', 'normalize audio signal loudness to a reference RMS level using NormalizationProcessor loudness_normalization', 'normalize a watermark signal to fit inside the envelope of the original audio using fit_inside_envelope']
```

Usage

```
{'load_generator_model': 'load an AudioSeal watermark generator model from a model card or checkpoint path', 'load_detector_model': 'load an AudioSeal detector model from a model card or checkpoint path', 'load_model_checkpoint': 'load a model checkpoint from a local file, Hugging Face repo, or HTTPS URL', 'parse_model_config': 'parse a model card or checkpoint path to extract the config and state dict', 'convert_state_dict_for_scriptable_model': 'convert a legacy state dict to be compatible with TorchScripted SEANet models on Python 3.10+'}
```

## File: facebookresearch_audioseal/src/audioseal/models.py

Prompts

```
['create an AudioSealWM watermark generator from an AudioSealWMConfig with optional device and dtype', 'create an AudioSealDetector from an AudioSealDetectorConfig with optional device and dtype', 'convert a dataclass or OmegaConf DictConfig object to a plain Python dictionary using as_dict', 'build a SEANetConfig dataclass with encoder and decoder hyperparameters like channels, filters, and ratios', 'build an AudioSealWMConfig dataclass with nbits, SEANetConfig, and DecoderConfig for watermark generation', 'load an AudioSeal watermark generator model from a model card or checkpoint path', 'load an AudioSeal detector model from a model card or checkpoint path', 'load a model checkpoint from a local file, Hugging Face repo, or HTTPS URL', 'parse a model card or checkpoint path to extract the config and state dict', 'convert a legacy state dict to be compatible with TorchScripted SEANet models on Python 3.10+', 'apply a watermark to an audio tensor using AudioSealWM forward method with a secret message', 'detect watermark presence and extract the secret message from an audio tensor using AudioSealDetector', 'generate a watermark tensor from an audio signal using AudioSealWM get_watermark method', 'normalize audio signal loudness to a reference RMS level using NormalizationProcessor loudness_normalization', 'normalize a watermark signal to fit inside the envelope of the original audio using fit_inside_envelope']
```

Usage

```
{'apply_watermark_to_audio': 'apply a watermark to an audio tensor using AudioSealWM forward method with a secret message', 'detect_watermark_in_audio': 'detect watermark presence and extract the secret message from an audio tensor using AudioSealDetector', 'generate_watermark_tensor': 'generate a watermark tensor from an audio signal using AudioSealWM get_watermark method', 'normalize_audio_loudness': 'normalize audio signal loudness to a reference RMS level using NormalizationProcessor loudness_normalization', 'fit_watermark_inside_envelope': 'normalize a watermark signal to fit inside the envelope of the original audio using fit_inside_envelope'}
```

