# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/tools/test.py

Prompts

```
['test an MMDetection model with a config file and checkpoint using the CLI', 'test a detection model and show prediction results with --show or --show-dir flags', 'test a detection model with test-time augmentation enabled using the --tta flag', 'test a detection model and dump predictions to a pickle file for offline evaluation', 'test a detection model with custom config overrides using --cfg-options key=value pairs', 'run the MMTrack test script to evaluate a tracking model with a config file and checkpoint', 'test a tracking model using a separate detector checkpoint file for detection', 'test a tracking model using a separate reid checkpoint file for re-identification', 'run tracking evaluation with custom config options to override default settings', 'run tracking test with a job launcher like pytorch, slurm, or mpi for distributed testing', 'run the training script with a config file to train an object detector model', 'train a detector model using automatic mixed precision for faster training', 'resume training from a saved checkpoint or auto resume from the latest checkpoint', 'override config settings using command line options in key=value format', 'enable automatic learning rate scaling based on batch size configuration']
```

Usage

```
{'test_detection_model': 'test an MMDetection model with a config file and checkpoint using the CLI', 'test_model_with_visualization': 'test a detection model and show prediction results with --show or --show-dir flags', 'test_model_with_tta': 'test a detection model with test-time augmentation enabled using the --tta flag', 'dump_predictions_to_pickle': 'test a detection model and dump predictions to a pickle file for offline evaluation', 'override_config_options': 'test a detection model with custom config overrides using --cfg-options key=value pairs'}
```

## File: facebookresearch_sapiens/det/tools/test_tracking.py

Prompts

```
['test an MMDetection model with a config file and checkpoint using the CLI', 'test a detection model and show prediction results with --show or --show-dir flags', 'test a detection model with test-time augmentation enabled using the --tta flag', 'test a detection model and dump predictions to a pickle file for offline evaluation', 'test a detection model with custom config overrides using --cfg-options key=value pairs', 'run the MMTrack test script to evaluate a tracking model with a config file and checkpoint', 'test a tracking model using a separate detector checkpoint file for detection', 'test a tracking model using a separate reid checkpoint file for re-identification', 'run tracking evaluation with custom config options to override default settings', 'run tracking test with a job launcher like pytorch, slurm, or mpi for distributed testing', 'run the training script with a config file to train an object detector model', 'train a detector model using automatic mixed precision for faster training', 'resume training from a saved checkpoint or auto resume from the latest checkpoint', 'override config settings using command line options in key=value format', 'enable automatic learning rate scaling based on batch size configuration']
```

Usage

```
{'run_tracking_test': 'run the MMTrack test script to evaluate a tracking model with a config file and checkpoint', 'test_tracking_with_detector': 'test a tracking model using a separate detector checkpoint file for detection', 'test_tracking_with_reid': 'test a tracking model using a separate reid checkpoint file for re-identification', 'run_tracking_with_cfg_options': 'run tracking evaluation with custom config options to override default settings', 'run_tracking_with_launcher': 'run tracking test with a job launcher like pytorch, slurm, or mpi for distributed testing'}
```

## File: facebookresearch_sapiens/det/tools/train.py

Prompts

```
['test an MMDetection model with a config file and checkpoint using the CLI', 'test a detection model and show prediction results with --show or --show-dir flags', 'test a detection model with test-time augmentation enabled using the --tta flag', 'test a detection model and dump predictions to a pickle file for offline evaluation', 'test a detection model with custom config overrides using --cfg-options key=value pairs', 'run the MMTrack test script to evaluate a tracking model with a config file and checkpoint', 'test a tracking model using a separate detector checkpoint file for detection', 'test a tracking model using a separate reid checkpoint file for re-identification', 'run tracking evaluation with custom config options to override default settings', 'run tracking test with a job launcher like pytorch, slurm, or mpi for distributed testing', 'run the training script with a config file to train an object detector model', 'train a detector model using automatic mixed precision for faster training', 'resume training from a saved checkpoint or auto resume from the latest checkpoint', 'override config settings using command line options in key=value format', 'enable automatic learning rate scaling based on batch size configuration']
```

Usage

```
{'run_detector_training': 'run the training script with a config file to train an object detector model', 'train_with_amp': 'train a detector model using automatic mixed precision for faster training', 'resume_training_from_checkpoint': 'resume training from a saved checkpoint or auto resume from the latest checkpoint', 'configure_training_with_options': 'override config settings using command line options in key=value format', 'scale_learning_rate_automatically': 'enable automatic learning rate scaling based on batch size configuration'}
```

