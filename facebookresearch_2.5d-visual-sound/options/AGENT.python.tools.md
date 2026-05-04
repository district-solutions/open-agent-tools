# Agent Python Tools

- repo: facebookresearch/2.5d-visual-sound
- repo_uri: https://github.com/facebookresearch/2.5d-visual-sound

## File: facebookresearch_2.5d-visual-sound/options/base_options.py

Prompts

```
['create a BaseOptions instance to set up an argparse parser for the 2.5D visual sound experiment', 'initialize the BaseOptions class to add CLI arguments for GPU IDs, batch size, and audio settings', 'parse command line arguments using BaseOptions to configure GPU devices, model name, and checkpoint directory', 'review the BaseOptions parse method to understand how GPU IDs are processed and options are saved to disk', 'refactor the BaseOptions parse method to handle GPU ID parsing and torch CUDA device selection', 'run TestOptions to parse command-line arguments for audio spatialization testing with input audio and video paths', 'create a TestOptions instance that configures argparse with required input_audio_path and video_frame_path arguments', 'test the TestOptions parser by passing input audio path, video frame path, and output directory arguments', 'review the TestOptions initialize method to understand test-specific argparse arguments like hop_size and unet channel dimensions', 'summarize the TestOptions class which extends BaseOptions to add test-mode arguments for 2.5D visual sound inference', 'run TrainOptions parse to get training CLI arguments with defaults for niter, learning rate, and optimizer', 'create a TrainOptions instance and call parse to configure training with custom batch size and GPU IDs', 'configure learning rate decay by setting decay_factor and learning_rate_decrease_itr via CLI arguments', 'set validation options by passing validation_on, validation_freq, and validation_batches flags during training', 'review the TrainOptions class to understand all training CLI arguments including model and optimizer settings']
```

Usage

```
{'create_BaseOptions_instance': 'create a BaseOptions instance to set up an argparse parser for the 2.5D visual sound experiment', 'initialize_BaseOptions_arguments': 'initialize the BaseOptions class to add CLI arguments for GPU IDs, batch size, and audio settings', 'parse_BaseOptions_cli': 'parse command line arguments using BaseOptions to configure GPU devices, model name, and checkpoint directory', 'review_BaseOptions_parse': 'review the BaseOptions parse method to understand how GPU IDs are processed and options are saved to disk', 'refactor_BaseOptions_gpu_ids': 'refactor the BaseOptions parse method to handle GPU ID parsing and torch CUDA device selection'}
```

## File: facebookresearch_2.5d-visual-sound/options/test_options.py

Prompts

```
['create a BaseOptions instance to set up an argparse parser for the 2.5D visual sound experiment', 'initialize the BaseOptions class to add CLI arguments for GPU IDs, batch size, and audio settings', 'parse command line arguments using BaseOptions to configure GPU devices, model name, and checkpoint directory', 'review the BaseOptions parse method to understand how GPU IDs are processed and options are saved to disk', 'refactor the BaseOptions parse method to handle GPU ID parsing and torch CUDA device selection', 'run TestOptions to parse command-line arguments for audio spatialization testing with input audio and video paths', 'create a TestOptions instance that configures argparse with required input_audio_path and video_frame_path arguments', 'test the TestOptions parser by passing input audio path, video frame path, and output directory arguments', 'review the TestOptions initialize method to understand test-specific argparse arguments like hop_size and unet channel dimensions', 'summarize the TestOptions class which extends BaseOptions to add test-mode arguments for 2.5D visual sound inference', 'run TrainOptions parse to get training CLI arguments with defaults for niter, learning rate, and optimizer', 'create a TrainOptions instance and call parse to configure training with custom batch size and GPU IDs', 'configure learning rate decay by setting decay_factor and learning_rate_decrease_itr via CLI arguments', 'set validation options by passing validation_on, validation_freq, and validation_batches flags during training', 'review the TrainOptions class to understand all training CLI arguments including model and optimizer settings']
```

Usage

```
{'run_test_options_parse': 'run TestOptions to parse command-line arguments for audio spatialization testing with input audio and video paths', 'create_test_options_instance': 'create a TestOptions instance that configures argparse with required input_audio_path and video_frame_path arguments', 'test_audio_spatialization_args': 'test the TestOptions parser by passing input audio path, video frame path, and output directory arguments', 'review_test_options_initialize': 'review the TestOptions initialize method to understand test-specific argparse arguments like hop_size and unet channel dimensions', 'summarize_test_options_class': 'summarize the TestOptions class which extends BaseOptions to add test-mode arguments for 2.5D visual sound inference'}
```

## File: facebookresearch_2.5d-visual-sound/options/train_options.py

Prompts

```
['create a BaseOptions instance to set up an argparse parser for the 2.5D visual sound experiment', 'initialize the BaseOptions class to add CLI arguments for GPU IDs, batch size, and audio settings', 'parse command line arguments using BaseOptions to configure GPU devices, model name, and checkpoint directory', 'review the BaseOptions parse method to understand how GPU IDs are processed and options are saved to disk', 'refactor the BaseOptions parse method to handle GPU ID parsing and torch CUDA device selection', 'run TestOptions to parse command-line arguments for audio spatialization testing with input audio and video paths', 'create a TestOptions instance that configures argparse with required input_audio_path and video_frame_path arguments', 'test the TestOptions parser by passing input audio path, video frame path, and output directory arguments', 'review the TestOptions initialize method to understand test-specific argparse arguments like hop_size and unet channel dimensions', 'summarize the TestOptions class which extends BaseOptions to add test-mode arguments for 2.5D visual sound inference', 'run TrainOptions parse to get training CLI arguments with defaults for niter, learning rate, and optimizer', 'create a TrainOptions instance and call parse to configure training with custom batch size and GPU IDs', 'configure learning rate decay by setting decay_factor and learning_rate_decrease_itr via CLI arguments', 'set validation options by passing validation_on, validation_freq, and validation_batches flags during training', 'review the TrainOptions class to understand all training CLI arguments including model and optimizer settings']
```

Usage

```
{'run_train_options_parse': 'run TrainOptions parse to get training CLI arguments with defaults for niter, learning rate, and optimizer', 'create_train_options_instance': 'create a TrainOptions instance and call parse to configure training with custom batch size and GPU IDs', 'configure_learning_rate_decay': 'configure learning rate decay by setting decay_factor and learning_rate_decrease_itr via CLI arguments', 'set_validation_options': 'set validation options by passing validation_on, validation_freq, and validation_batches flags during training', 'review_train_options_class': 'review the TrainOptions class to understand all training CLI arguments including model and optimizer settings'}
```

