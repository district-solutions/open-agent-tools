# Agent Python Tools

- repo: facebookresearch/audiodec
- repo_uri: https://github.com/facebookresearch/audiodec

## File: facebookresearch_audiodec/bin/stream.py

Prompts

```
['create a subclass of AudioCodec that implements _load_encoder and _load_decoder abstract methods', 'load a transmitter encoder model from a checkpoint file onto the specified device', 'load both receiver encoder and decoder models from checkpoint files for audio decoding', 'create a subclass of AudioCodecStreamer that implements _encode and _decode abstract methods for streaming', 'run the AudioCodecStreamer to stream audio from input device to output device with encoder and decoder processing', 'run the TestGEN class to encode and decode audio utterances and save output WAV files', 'implement a TestGEN subclass with load_encoder, load_decoder, encode, and decode methods', 'use the TestGEN _save_wav method to write audio data as a PCM_16 WAV file', 'use the TestGEN _load_config method to load a config.yml from a checkpoint directory', 'review the TestGEN abstract class and its required initial_folder, load_dataset, encode, and decode methods', 'run the TrainGAN training loop with optional adversarial training phase and checkpoint saving', 'review the TrainGAN class __init__ method that sets up logging, seeds, config, and device', 'review the TrainGAN run method that executes training and saves checkpoints', 'review the TrainGAN abstract methods for initialize_data_loader, define_model, define_trainer, initialize_model, define_criterion', 'summarize the TrainGAN abstract base class used as a training template for GAN models', 'load a YAML config file from the same directory as a given checkpoint path', "load a YAML config with a custom filename from a checkpoint's directory", 'review the load_config function to understand how it resolves config paths relative to checkpoints', 'refactor load_config to add validation for missing config files or invalid YAML', 'summarize the load_config utility that reads YAML config files alongside model checkpoints']
```

Usage

```
{'create_audio_codec_subclass': 'create a subclass of AudioCodec that implements _load_encoder and _load_decoder abstract methods', 'load_transmitter_encoder': 'load a transmitter encoder model from a checkpoint file onto the specified device', 'load_receiver_models': 'load both receiver encoder and decoder models from checkpoint files for audio decoding', 'create_audio_codec_streamer_subclass': 'create a subclass of AudioCodecStreamer that implements _encode and _decode abstract methods for streaming', 'run_audio_stream': 'run the AudioCodecStreamer to stream audio from input device to output device with encoder and decoder processing'}
```

## File: facebookresearch_audiodec/bin/test.py

Prompts

```
['create a subclass of AudioCodec that implements _load_encoder and _load_decoder abstract methods', 'load a transmitter encoder model from a checkpoint file onto the specified device', 'load both receiver encoder and decoder models from checkpoint files for audio decoding', 'create a subclass of AudioCodecStreamer that implements _encode and _decode abstract methods for streaming', 'run the AudioCodecStreamer to stream audio from input device to output device with encoder and decoder processing', 'run the TestGEN class to encode and decode audio utterances and save output WAV files', 'implement a TestGEN subclass with load_encoder, load_decoder, encode, and decode methods', 'use the TestGEN _save_wav method to write audio data as a PCM_16 WAV file', 'use the TestGEN _load_config method to load a config.yml from a checkpoint directory', 'review the TestGEN abstract class and its required initial_folder, load_dataset, encode, and decode methods', 'run the TrainGAN training loop with optional adversarial training phase and checkpoint saving', 'review the TrainGAN class __init__ method that sets up logging, seeds, config, and device', 'review the TrainGAN run method that executes training and saves checkpoints', 'review the TrainGAN abstract methods for initialize_data_loader, define_model, define_trainer, initialize_model, define_criterion', 'summarize the TrainGAN abstract base class used as a training template for GAN models', 'load a YAML config file from the same directory as a given checkpoint path', "load a YAML config with a custom filename from a checkpoint's directory", 'review the load_config function to understand how it resolves config paths relative to checkpoints', 'refactor load_config to add validation for missing config files or invalid YAML', 'summarize the load_config utility that reads YAML config files alongside model checkpoints']
```

Usage

```
{'run_testGEN_inference': 'run the TestGEN class to encode and decode audio utterances and save output WAV files', 'implement_TestGEN_subclass': 'implement a TestGEN subclass with load_encoder, load_decoder, encode, and decode methods', 'save_wav_with_TestGEN': 'use the TestGEN _save_wav method to write audio data as a PCM_16 WAV file', 'load_config_with_TestGEN': 'use the TestGEN _load_config method to load a config.yml from a checkpoint directory', 'review_TestGEN_abstract_methods': 'review the TestGEN abstract class and its required initial_folder, load_dataset, encode, and decode methods'}
```

## File: facebookresearch_audiodec/bin/train.py

Prompts

```
['create a subclass of AudioCodec that implements _load_encoder and _load_decoder abstract methods', 'load a transmitter encoder model from a checkpoint file onto the specified device', 'load both receiver encoder and decoder models from checkpoint files for audio decoding', 'create a subclass of AudioCodecStreamer that implements _encode and _decode abstract methods for streaming', 'run the AudioCodecStreamer to stream audio from input device to output device with encoder and decoder processing', 'run the TestGEN class to encode and decode audio utterances and save output WAV files', 'implement a TestGEN subclass with load_encoder, load_decoder, encode, and decode methods', 'use the TestGEN _save_wav method to write audio data as a PCM_16 WAV file', 'use the TestGEN _load_config method to load a config.yml from a checkpoint directory', 'review the TestGEN abstract class and its required initial_folder, load_dataset, encode, and decode methods', 'run the TrainGAN training loop with optional adversarial training phase and checkpoint saving', 'review the TrainGAN class __init__ method that sets up logging, seeds, config, and device', 'review the TrainGAN run method that executes training and saves checkpoints', 'review the TrainGAN abstract methods for initialize_data_loader, define_model, define_trainer, initialize_model, define_criterion', 'summarize the TrainGAN abstract base class used as a training template for GAN models', 'load a YAML config file from the same directory as a given checkpoint path', "load a YAML config with a custom filename from a checkpoint's directory", 'review the load_config function to understand how it resolves config paths relative to checkpoints', 'refactor load_config to add validation for missing config files or invalid YAML', 'summarize the load_config utility that reads YAML config files alongside model checkpoints']
```

Usage

```
{'run_train_gan': 'run the TrainGAN training loop with optional adversarial training phase and checkpoint saving', 'review_TrainGAN_init': 'review the TrainGAN class __init__ method that sets up logging, seeds, config, and device', 'review_TrainGAN_run': 'review the TrainGAN run method that executes training and saves checkpoints', 'review_TrainGAN_abstract_methods': 'review the TrainGAN abstract methods for initialize_data_loader, define_model, define_trainer, initialize_model, define_criterion', 'summarize_TrainGAN': 'summarize the TrainGAN abstract base class used as a training template for GAN models'}
```

## File: facebookresearch_audiodec/bin/utils.py

Prompts

```
['create a subclass of AudioCodec that implements _load_encoder and _load_decoder abstract methods', 'load a transmitter encoder model from a checkpoint file onto the specified device', 'load both receiver encoder and decoder models from checkpoint files for audio decoding', 'create a subclass of AudioCodecStreamer that implements _encode and _decode abstract methods for streaming', 'run the AudioCodecStreamer to stream audio from input device to output device with encoder and decoder processing', 'run the TestGEN class to encode and decode audio utterances and save output WAV files', 'implement a TestGEN subclass with load_encoder, load_decoder, encode, and decode methods', 'use the TestGEN _save_wav method to write audio data as a PCM_16 WAV file', 'use the TestGEN _load_config method to load a config.yml from a checkpoint directory', 'review the TestGEN abstract class and its required initial_folder, load_dataset, encode, and decode methods', 'run the TrainGAN training loop with optional adversarial training phase and checkpoint saving', 'review the TrainGAN class __init__ method that sets up logging, seeds, config, and device', 'review the TrainGAN run method that executes training and saves checkpoints', 'review the TrainGAN abstract methods for initialize_data_loader, define_model, define_trainer, initialize_model, define_criterion', 'summarize the TrainGAN abstract base class used as a training template for GAN models', 'load a YAML config file from the same directory as a given checkpoint path', "load a YAML config with a custom filename from a checkpoint's directory", 'review the load_config function to understand how it resolves config paths relative to checkpoints', 'refactor load_config to add validation for missing config files or invalid YAML', 'summarize the load_config utility that reads YAML config files alongside model checkpoints']
```

Usage

```
{'load_config_from_checkpoint': 'load a YAML config file from the same directory as a given checkpoint path', 'load_config_with_custom_name': "load a YAML config with a custom filename from a checkpoint's directory", 'review_load_config': 'review the load_config function to understand how it resolves config paths relative to checkpoints', 'refactor_load_config': 'refactor load_config to add validation for missing config files or invalid YAML', 'summarize_load_config': 'summarize the load_config utility that reads YAML config files alongside model checkpoints'}
```

