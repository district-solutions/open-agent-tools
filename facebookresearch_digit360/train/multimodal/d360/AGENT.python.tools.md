# Agent Python Tools

- repo: facebookresearch/digit360
- repo_uri: https://github.com/facebookresearch/digit360

## File: facebookresearch_digit360/train/multimodal/d360/model.py

Prompts

```
['build a Net multimodal model with RGB, IMU, mic, specgram, and pressure encoders for action and material classification', 'create a BasicBlock residual block with two conv layers and GroupNorm for use in ResNet architectures', 'create a ResNet feature extractor with configurable block types and layer depths for image encoding', 'create a ModelInput dataclass to hold RGB, IMU, mic, spectrogram, and pressure tensor inputs', 'run a forward pass through the Net model with a ModelInput to get action and material predictions', 'run the Trainer train method to execute 200 epochs of multimodal action and material classification training', 'run a single training epoch over the train loader computing dual action and material classification loss', 'run validation on the val loader saving model checkpoint and confusion matrix info to disk', 'review the _prepare_inputs method that constructs a ModelInput from raw data dict with RGB IMU spectrogram mic and pressure modalities', 'review the _adjust_learning_rate method that applies cosine annealing schedule based on current epoch index', 'create a python module that normalizes numerical data to the range [-1, 1] using min-max scaling', 'build a script that takes a numpy array and normalizes each feature to [-1, 1]', 'test the normalize_data function with a sample numpy array and verify output is in [-1, 1]', 'review the normalize_data function to understand its min-max normalization approach with epsilon safeguard', 'refactor the normalize_data function to support configurable output ranges beyond [-1, 1]']
```

Usage

```
{'build_Net_multimodal_model': 'build a Net multimodal model with RGB, IMU, mic, specgram, and pressure encoders for action and material classification', 'create_BasicBlock_resnet_block': 'create a BasicBlock residual block with two conv layers and GroupNorm for use in ResNet architectures', 'create_ResNet_feature_extractor': 'create a ResNet feature extractor with configurable block types and layer depths for image encoding', 'create_ModelInput_dataclass': 'create a ModelInput dataclass to hold RGB, IMU, mic, spectrogram, and pressure tensor inputs', 'run_Net_forward_pass': 'run a forward pass through the Net model with a ModelInput to get action and material predictions'}
```

## File: facebookresearch_digit360/train/multimodal/d360/trainer.py

Prompts

```
['build a Net multimodal model with RGB, IMU, mic, specgram, and pressure encoders for action and material classification', 'create a BasicBlock residual block with two conv layers and GroupNorm for use in ResNet architectures', 'create a ResNet feature extractor with configurable block types and layer depths for image encoding', 'create a ModelInput dataclass to hold RGB, IMU, mic, spectrogram, and pressure tensor inputs', 'run a forward pass through the Net model with a ModelInput to get action and material predictions', 'run the Trainer train method to execute 200 epochs of multimodal action and material classification training', 'run a single training epoch over the train loader computing dual action and material classification loss', 'run validation on the val loader saving model checkpoint and confusion matrix info to disk', 'review the _prepare_inputs method that constructs a ModelInput from raw data dict with RGB IMU spectrogram mic and pressure modalities', 'review the _adjust_learning_rate method that applies cosine annealing schedule based on current epoch index', 'create a python module that normalizes numerical data to the range [-1, 1] using min-max scaling', 'build a script that takes a numpy array and normalizes each feature to [-1, 1]', 'test the normalize_data function with a sample numpy array and verify output is in [-1, 1]', 'review the normalize_data function to understand its min-max normalization approach with epsilon safeguard', 'refactor the normalize_data function to support configurable output ranges beyond [-1, 1]']
```

Usage

```
{'run_Trainer_train': 'run the Trainer train method to execute 200 epochs of multimodal action and material classification training', 'run_Trainer_train_epoch': 'run a single training epoch over the train loader computing dual action and material classification loss', 'run_Trainer_val': 'run validation on the val loader saving model checkpoint and confusion matrix info to disk', 'review_Trainer_prepare_inputs': 'review the _prepare_inputs method that constructs a ModelInput from raw data dict with RGB IMU spectrogram mic and pressure modalities', 'review_Trainer_adjust_learning_rate': 'review the _adjust_learning_rate method that applies cosine annealing schedule based on current epoch index'}
```

## File: facebookresearch_digit360/train/multimodal/d360/utils.py

Prompts

```
['build a Net multimodal model with RGB, IMU, mic, specgram, and pressure encoders for action and material classification', 'create a BasicBlock residual block with two conv layers and GroupNorm for use in ResNet architectures', 'create a ResNet feature extractor with configurable block types and layer depths for image encoding', 'create a ModelInput dataclass to hold RGB, IMU, mic, spectrogram, and pressure tensor inputs', 'run a forward pass through the Net model with a ModelInput to get action and material predictions', 'run the Trainer train method to execute 200 epochs of multimodal action and material classification training', 'run a single training epoch over the train loader computing dual action and material classification loss', 'run validation on the val loader saving model checkpoint and confusion matrix info to disk', 'review the _prepare_inputs method that constructs a ModelInput from raw data dict with RGB IMU spectrogram mic and pressure modalities', 'review the _adjust_learning_rate method that applies cosine annealing schedule based on current epoch index', 'create a python module that normalizes numerical data to the range [-1, 1] using min-max scaling', 'build a script that takes a numpy array and normalizes each feature to [-1, 1]', 'test the normalize_data function with a sample numpy array and verify output is in [-1, 1]', 'review the normalize_data function to understand its min-max normalization approach with epsilon safeguard', 'refactor the normalize_data function to support configurable output ranges beyond [-1, 1]']
```

Usage

```
{'normalize_data_to_range': 'create a python module that normalizes numerical data to the range [-1, 1] using min-max scaling', 'normalize_numpy_array': 'build a script that takes a numpy array and normalizes each feature to [-1, 1]', 'test_normalize_data': 'test the normalize_data function with a sample numpy array and verify output is in [-1, 1]', 'review_normalize_data': 'review the normalize_data function to understand its min-max normalization approach with epsilon safeguard', 'refactor_normalize_data': 'refactor the normalize_data function to support configurable output ranges beyond [-1, 1]'}
```

