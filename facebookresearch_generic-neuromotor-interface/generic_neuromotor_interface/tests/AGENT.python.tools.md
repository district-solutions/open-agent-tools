# Agent Python Tools

- repo: facebookresearch/generic-neuromotor-interface
- repo_uri: https://github.com/facebookresearch/generic-neuromotor-interface

## File: facebookresearch_generic-neuromotor-interface/generic_neuromotor_interface/tests/mock_datasets.py

Prompts

```
['create a mock wrist EMG dataset with wrist angles and save to HDF5', 'create a mock handwriting EMG dataset with text prompts and save to HDF5', 'create a mock discrete gestures EMG dataset with gesture labels and save to HDF5', 'use create_mock_dataset to generate and verify an HDF5 file for any task type', 'verify a saved mock EMG HDF5 file loads correctly via EmgRecording', 'run integration tests to evaluate a neuromotor model from a checkpoint on wrist, handwriting, or discrete gestures tasks', 'run integration tests for the neuromotor model training loop across wrist, handwriting, and discrete gestures tasks', 'create mock EMG datasets for a given task name and output directory using Hydra config and Hydra utils', 'create a mock model checkpoint directory by instantiating a LightningModule and saving a trained checkpoint', 'verify neuromotor model test metrics match expected values for a given task and dataset size', 'build a WristModule with WristArchitecture network and Adam optimizer for neuromotor interface', 'test the WristModule forward pass with randomized hidden dims and LSTM parameters', 'test the WristModule training step and verify L1 loss is positive', 'review the TestWristModule class and its Hypothesis property-based test methods', 'run the test_lightning.py tests to validate WristModule forward pass and step loss', 'test the create_mock_dataset utility function for wrist handwriting and discrete_gestures tasks', 'verify a saved mock dataset HDF5 file can be loaded and validated by EmgRecording', 'test the RotationInvariantMPFMLP constructor validates num_adjacent_cov does not exceed half num_channels', 'test the WristArchitecture forward pass with 16 channels and 500 timesteps produces correct output shape', 'test the MultivariatePowerFrequencyFeatures module returns length 1 output when input equals left_context plus 1', 'test the DiscreteGesturesArchitecture forward pass with 16 channels produces 9-class output with correct shape', 'review the WRIST_MODEL_MPF_PARAMS and HANDWRITING_MODEL_MPF_PARAMS config dicts for window_length stride n_fft and fft_stride']
```

Usage

```
{'create_mock_wrist_dataset': 'create a mock wrist EMG dataset with wrist angles and save to HDF5', 'create_mock_handwriting_dataset': 'create a mock handwriting EMG dataset with text prompts and save to HDF5', 'create_mock_discrete_gestures_dataset': 'create a mock discrete gestures EMG dataset with gesture labels and save to HDF5', 'create_mock_dataset_factory': 'use create_mock_dataset to generate and verify an HDF5 file for any task type', 'verify_mock_hdf5_file': 'verify a saved mock EMG HDF5 file loads correctly via EmgRecording'}
```

## File: facebookresearch_generic-neuromotor-interface/generic_neuromotor_interface/tests/test_integration.py

Prompts

```
['create a mock wrist EMG dataset with wrist angles and save to HDF5', 'create a mock handwriting EMG dataset with text prompts and save to HDF5', 'create a mock discrete gestures EMG dataset with gesture labels and save to HDF5', 'use create_mock_dataset to generate and verify an HDF5 file for any task type', 'verify a saved mock EMG HDF5 file loads correctly via EmgRecording', 'run integration tests to evaluate a neuromotor model from a checkpoint on wrist, handwriting, or discrete gestures tasks', 'run integration tests for the neuromotor model training loop across wrist, handwriting, and discrete gestures tasks', 'create mock EMG datasets for a given task name and output directory using Hydra config and Hydra utils', 'create a mock model checkpoint directory by instantiating a LightningModule and saving a trained checkpoint', 'verify neuromotor model test metrics match expected values for a given task and dataset size', 'build a WristModule with WristArchitecture network and Adam optimizer for neuromotor interface', 'test the WristModule forward pass with randomized hidden dims and LSTM parameters', 'test the WristModule training step and verify L1 loss is positive', 'review the TestWristModule class and its Hypothesis property-based test methods', 'run the test_lightning.py tests to validate WristModule forward pass and step loss', 'test the create_mock_dataset utility function for wrist handwriting and discrete_gestures tasks', 'verify a saved mock dataset HDF5 file can be loaded and validated by EmgRecording', 'test the RotationInvariantMPFMLP constructor validates num_adjacent_cov does not exceed half num_channels', 'test the WristArchitecture forward pass with 16 channels and 500 timesteps produces correct output shape', 'test the MultivariatePowerFrequencyFeatures module returns length 1 output when input equals left_context plus 1', 'test the DiscreteGesturesArchitecture forward pass with 16 channels produces 9-class output with correct shape', 'review the WRIST_MODEL_MPF_PARAMS and HANDWRITING_MODEL_MPF_PARAMS config dicts for window_length stride n_fft and fft_stride']
```

Usage

```
{'test_task_evaluate_from_checkpoint': 'run integration tests to evaluate a neuromotor model from a checkpoint on wrist, handwriting, or discrete gestures tasks', 'test_task_training_loop': 'run integration tests for the neuromotor model training loop across wrist, handwriting, and discrete gestures tasks', 'get_mock_datasets': 'create mock EMG datasets for a given task name and output directory using Hydra config and Hydra utils', 'get_mock_checkpoint_dir': 'create a mock model checkpoint directory by instantiating a LightningModule and saving a trained checkpoint', 'check_expected_results': 'verify neuromotor model test metrics match expected values for a given task and dataset size'}
```

## File: facebookresearch_generic-neuromotor-interface/generic_neuromotor_interface/tests/test_lightning.py

Prompts

```
['create a mock wrist EMG dataset with wrist angles and save to HDF5', 'create a mock handwriting EMG dataset with text prompts and save to HDF5', 'create a mock discrete gestures EMG dataset with gesture labels and save to HDF5', 'use create_mock_dataset to generate and verify an HDF5 file for any task type', 'verify a saved mock EMG HDF5 file loads correctly via EmgRecording', 'run integration tests to evaluate a neuromotor model from a checkpoint on wrist, handwriting, or discrete gestures tasks', 'run integration tests for the neuromotor model training loop across wrist, handwriting, and discrete gestures tasks', 'create mock EMG datasets for a given task name and output directory using Hydra config and Hydra utils', 'create a mock model checkpoint directory by instantiating a LightningModule and saving a trained checkpoint', 'verify neuromotor model test metrics match expected values for a given task and dataset size', 'build a WristModule with WristArchitecture network and Adam optimizer for neuromotor interface', 'test the WristModule forward pass with randomized hidden dims and LSTM parameters', 'test the WristModule training step and verify L1 loss is positive', 'review the TestWristModule class and its Hypothesis property-based test methods', 'run the test_lightning.py tests to validate WristModule forward pass and step loss', 'test the create_mock_dataset utility function for wrist handwriting and discrete_gestures tasks', 'verify a saved mock dataset HDF5 file can be loaded and validated by EmgRecording', 'test the RotationInvariantMPFMLP constructor validates num_adjacent_cov does not exceed half num_channels', 'test the WristArchitecture forward pass with 16 channels and 500 timesteps produces correct output shape', 'test the MultivariatePowerFrequencyFeatures module returns length 1 output when input equals left_context plus 1', 'test the DiscreteGesturesArchitecture forward pass with 16 channels produces 9-class output with correct shape', 'review the WRIST_MODEL_MPF_PARAMS and HANDWRITING_MODEL_MPF_PARAMS config dicts for window_length stride n_fft and fft_stride']
```

Usage

```
{'build_WristModule': 'build a WristModule with WristArchitecture network and Adam optimizer for neuromotor interface', 'test_test_forward': 'test the WristModule forward pass with randomized hidden dims and LSTM parameters', 'test_test_step': 'test the WristModule training step and verify L1 loss is positive', 'review_TestWristModule': 'review the TestWristModule class and its Hypothesis property-based test methods', 'run_test_lightning': 'run the test_lightning.py tests to validate WristModule forward pass and step loss'}
```

## File: facebookresearch_generic-neuromotor-interface/generic_neuromotor_interface/tests/test_mock_datasets.py

Prompts

```
['create a mock wrist EMG dataset with wrist angles and save to HDF5', 'create a mock handwriting EMG dataset with text prompts and save to HDF5', 'create a mock discrete gestures EMG dataset with gesture labels and save to HDF5', 'use create_mock_dataset to generate and verify an HDF5 file for any task type', 'verify a saved mock EMG HDF5 file loads correctly via EmgRecording', 'run integration tests to evaluate a neuromotor model from a checkpoint on wrist, handwriting, or discrete gestures tasks', 'run integration tests for the neuromotor model training loop across wrist, handwriting, and discrete gestures tasks', 'create mock EMG datasets for a given task name and output directory using Hydra config and Hydra utils', 'create a mock model checkpoint directory by instantiating a LightningModule and saving a trained checkpoint', 'verify neuromotor model test metrics match expected values for a given task and dataset size', 'build a WristModule with WristArchitecture network and Adam optimizer for neuromotor interface', 'test the WristModule forward pass with randomized hidden dims and LSTM parameters', 'test the WristModule training step and verify L1 loss is positive', 'review the TestWristModule class and its Hypothesis property-based test methods', 'run the test_lightning.py tests to validate WristModule forward pass and step loss', 'test the create_mock_dataset utility function for wrist handwriting and discrete_gestures tasks', 'verify a saved mock dataset HDF5 file can be loaded and validated by EmgRecording', 'test the RotationInvariantMPFMLP constructor validates num_adjacent_cov does not exceed half num_channels', 'test the WristArchitecture forward pass with 16 channels and 500 timesteps produces correct output shape', 'test the MultivariatePowerFrequencyFeatures module returns length 1 output when input equals left_context plus 1', 'test the DiscreteGesturesArchitecture forward pass with 16 channels produces 9-class output with correct shape', 'review the WRIST_MODEL_MPF_PARAMS and HANDWRITING_MODEL_MPF_PARAMS config dicts for window_length stride n_fft and fft_stride']
```

Usage

```
{'create_mock_wrist_dataset': 'create a MockWristEmgDataset with 500 samples and 8 channels then save to HDF5', 'create_mock_discrete_gestures_dataset': 'create a MockDiscreteGesturesEmgDataset with gesture labels pinch point and fist then save to HDF5', 'create_mock_handwriting_dataset': 'create a MockHandwritingEmgDataset with 3 text prompts and 500 samples then save to HDF5', 'test_create_mock_dataset_utility': 'test the create_mock_dataset utility function for wrist handwriting and discrete_gestures tasks', 'verify_mock_dataset_with_emgrecording': 'verify a saved mock dataset HDF5 file can be loaded and validated by EmgRecording'}
```

## File: facebookresearch_generic-neuromotor-interface/generic_neuromotor_interface/tests/test_networks.py

Prompts

```
['create a mock wrist EMG dataset with wrist angles and save to HDF5', 'create a mock handwriting EMG dataset with text prompts and save to HDF5', 'create a mock discrete gestures EMG dataset with gesture labels and save to HDF5', 'use create_mock_dataset to generate and verify an HDF5 file for any task type', 'verify a saved mock EMG HDF5 file loads correctly via EmgRecording', 'run integration tests to evaluate a neuromotor model from a checkpoint on wrist, handwriting, or discrete gestures tasks', 'run integration tests for the neuromotor model training loop across wrist, handwriting, and discrete gestures tasks', 'create mock EMG datasets for a given task name and output directory using Hydra config and Hydra utils', 'create a mock model checkpoint directory by instantiating a LightningModule and saving a trained checkpoint', 'verify neuromotor model test metrics match expected values for a given task and dataset size', 'build a WristModule with WristArchitecture network and Adam optimizer for neuromotor interface', 'test the WristModule forward pass with randomized hidden dims and LSTM parameters', 'test the WristModule training step and verify L1 loss is positive', 'review the TestWristModule class and its Hypothesis property-based test methods', 'run the test_lightning.py tests to validate WristModule forward pass and step loss', 'test the create_mock_dataset utility function for wrist handwriting and discrete_gestures tasks', 'verify a saved mock dataset HDF5 file can be loaded and validated by EmgRecording', 'test the RotationInvariantMPFMLP constructor validates num_adjacent_cov does not exceed half num_channels', 'test the WristArchitecture forward pass with 16 channels and 500 timesteps produces correct output shape', 'test the MultivariatePowerFrequencyFeatures module returns length 1 output when input equals left_context plus 1', 'test the DiscreteGesturesArchitecture forward pass with 16 channels produces 9-class output with correct shape', 'review the WRIST_MODEL_MPF_PARAMS and HANDWRITING_MODEL_MPF_PARAMS config dicts for window_length stride n_fft and fft_stride']
```

Usage

```
{'test_RotationInvariantMPFMLP': 'test the RotationInvariantMPFMLP constructor validates num_adjacent_cov does not exceed half num_channels', 'test_WristArchitecture': 'test the WristArchitecture forward pass with 16 channels and 500 timesteps produces correct output shape', 'test_MultivariatePowerFrequencyFeatures': 'test the MultivariatePowerFrequencyFeatures module returns length 1 output when input equals left_context plus 1', 'test_DiscreteGesturesArchitecture': 'test the DiscreteGesturesArchitecture forward pass with 16 channels produces 9-class output with correct shape', 'review_MPF_PARAMS': 'review the WRIST_MODEL_MPF_PARAMS and HANDWRITING_MODEL_MPF_PARAMS config dicts for window_length stride n_fft and fft_stride'}
```

