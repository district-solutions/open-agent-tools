# Agent Python Tools

- repo: facebookresearch/orienternet
- repo_uri: https://github.com/facebookresearch/orienternet

## File: facebookresearch_orienternet/maploc/demo.py

Prompts

```
['run the Demo class localize method to predict camera position and yaw from an image and map canvas', 'create a Demo instance that loads a pretrained OrienterNet model for visual localization inference', 'run the ImageCalibrator class to estimate camera roll, pitch, and focal length from an RGB image', 'parse a location prior from EXIF metadata, explicit lat/lon coordinates, or a geocoded address string', 'run the Demo read_input_image method to load an image, extract EXIF, calibrate camera, and compute a bounding box', 'create a GenericModule LightningModule instance from a config to run training and validation steps', 'run a training step on a batch and log loss metrics to the progress bar', 'run a validation step on a batch and compute metrics and loss values', 'configure an Adam optimizer with an optional learning rate scheduler for the model', 'load a GenericModule from a checkpoint file with optional config overrides and best model selection', 'run the train function to start training an OrienterNet model with a Hydra DictConfig', 'run the main entry point to train an OrienterNet model using Hydra configuration', 'create a SeedingCallback class to reseed PyTorch Lightning workers at each epoch start', 'create a ConsoleLogger callback to log training epoch starts and validation results', 'prepare an experiment directory by saving config and finding the last checkpoint path']
```

Usage

```
{'run_Demo_localize': 'run the Demo class localize method to predict camera position and yaw from an image and map canvas', 'create_Demo_instance': 'create a Demo instance that loads a pretrained OrienterNet model for visual localization inference', 'run_ImageCalibrator': 'run the ImageCalibrator class to estimate camera roll, pitch, and focal length from an RGB image', 'parse_location_prior': 'parse a location prior from EXIF metadata, explicit lat/lon coordinates, or a geocoded address string', 'run_Demo_read_input_image': 'run the Demo read_input_image method to load an image, extract EXIF, calibrate camera, and compute a bounding box'}
```

## File: facebookresearch_orienternet/maploc/module.py

Prompts

```
['run the Demo class localize method to predict camera position and yaw from an image and map canvas', 'create a Demo instance that loads a pretrained OrienterNet model for visual localization inference', 'run the ImageCalibrator class to estimate camera roll, pitch, and focal length from an RGB image', 'parse a location prior from EXIF metadata, explicit lat/lon coordinates, or a geocoded address string', 'run the Demo read_input_image method to load an image, extract EXIF, calibrate camera, and compute a bounding box', 'create a GenericModule LightningModule instance from a config to run training and validation steps', 'run a training step on a batch and log loss metrics to the progress bar', 'run a validation step on a batch and compute metrics and loss values', 'configure an Adam optimizer with an optional learning rate scheduler for the model', 'load a GenericModule from a checkpoint file with optional config overrides and best model selection', 'run the train function to start training an OrienterNet model with a Hydra DictConfig', 'run the main entry point to train an OrienterNet model using Hydra configuration', 'create a SeedingCallback class to reseed PyTorch Lightning workers at each epoch start', 'create a ConsoleLogger callback to log training epoch starts and validation results', 'prepare an experiment directory by saving config and finding the last checkpoint path']
```

Usage

```
{'create_GenericModule': 'create a GenericModule LightningModule instance from a config to run training and validation steps', 'run_training_step': 'run a training step on a batch and log loss metrics to the progress bar', 'run_validation_step': 'run a validation step on a batch and compute metrics and loss values', 'configure_optimizers': 'configure an Adam optimizer with an optional learning rate scheduler for the model', 'load_from_checkpoint': 'load a GenericModule from a checkpoint file with optional config overrides and best model selection'}
```

## File: facebookresearch_orienternet/maploc/train.py

Prompts

```
['run the Demo class localize method to predict camera position and yaw from an image and map canvas', 'create a Demo instance that loads a pretrained OrienterNet model for visual localization inference', 'run the ImageCalibrator class to estimate camera roll, pitch, and focal length from an RGB image', 'parse a location prior from EXIF metadata, explicit lat/lon coordinates, or a geocoded address string', 'run the Demo read_input_image method to load an image, extract EXIF, calibrate camera, and compute a bounding box', 'create a GenericModule LightningModule instance from a config to run training and validation steps', 'run a training step on a batch and log loss metrics to the progress bar', 'run a validation step on a batch and compute metrics and loss values', 'configure an Adam optimizer with an optional learning rate scheduler for the model', 'load a GenericModule from a checkpoint file with optional config overrides and best model selection', 'run the train function to start training an OrienterNet model with a Hydra DictConfig', 'run the main entry point to train an OrienterNet model using Hydra configuration', 'create a SeedingCallback class to reseed PyTorch Lightning workers at each epoch start', 'create a ConsoleLogger callback to log training epoch starts and validation results', 'prepare an experiment directory by saving config and finding the last checkpoint path']
```

Usage

```
{'run_train': 'run the train function to start training an OrienterNet model with a Hydra DictConfig', 'run_main': 'run the main entry point to train an OrienterNet model using Hydra configuration', 'create_seeding_callback': 'create a SeedingCallback class to reseed PyTorch Lightning workers at each epoch start', 'create_console_logger': 'create a ConsoleLogger callback to log training epoch starts and validation results', 'prepare_experiment_dir': 'prepare an experiment directory by saving config and finding the last checkpoint path'}
```

