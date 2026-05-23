# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/omnimatte/options/base_options.py

Prompts

```
['parse command line arguments for the omnimatte model training or testing configuration', 'gather command line options including model-specific and dataset-specific arguments from argv', 'initialize an argparse parser with common training and test options like dataroot and gpu_ids', 'print parsed options to console and save them to a text file in the checkpoints directory', 'set the active CUDA GPU device based on the gpu_ids command line argument', 'parse command-line test options including results_dir, aspect_ratio, phase, num_test, and use_eval flags', 'run the test phase saving results to a custom directory using the --results_dir argument', 'test a specific number of images by setting the --num_test argument to a finite integer', 'configure the output image aspect ratio for test results using the --aspect_ratio float argument', 'enable model evaluation mode before running tests by passing the --use_eval flag', 'parse training options including learning rate, display frequency, and checkpoint settings for the omnimatte model', 'configure the initial learning rate and decay policy for adam optimizer during training', 'set visdom display frequency, server, port, and environment for training result visualization', 'configure checkpoint save frequency and epoch-based saving for model training results', 'initialize an argparse parser with all training-specific arguments extending base options']
```

Usage

```
{'parse_base_options': 'parse command line arguments for the omnimatte model training or testing configuration', 'gather_options_with_model': 'gather command line options including model-specific and dataset-specific arguments from argv', 'initialize_parser_arguments': 'initialize an argparse parser with common training and test options like dataroot and gpu_ids', 'print_and_save_options': 'print parsed options to console and save them to a text file in the checkpoints directory', 'set_gpu_device': 'set the active CUDA GPU device based on the gpu_ids command line argument'}
```

## File: facebookresearch_omnimatterf/third_party/omnimatte/options/test_options.py

Prompts

```
['parse command line arguments for the omnimatte model training or testing configuration', 'gather command line options including model-specific and dataset-specific arguments from argv', 'initialize an argparse parser with common training and test options like dataroot and gpu_ids', 'print parsed options to console and save them to a text file in the checkpoints directory', 'set the active CUDA GPU device based on the gpu_ids command line argument', 'parse command-line test options including results_dir, aspect_ratio, phase, num_test, and use_eval flags', 'run the test phase saving results to a custom directory using the --results_dir argument', 'test a specific number of images by setting the --num_test argument to a finite integer', 'configure the output image aspect ratio for test results using the --aspect_ratio float argument', 'enable model evaluation mode before running tests by passing the --use_eval flag', 'parse training options including learning rate, display frequency, and checkpoint settings for the omnimatte model', 'configure the initial learning rate and decay policy for adam optimizer during training', 'set visdom display frequency, server, port, and environment for training result visualization', 'configure checkpoint save frequency and epoch-based saving for model training results', 'initialize an argparse parser with all training-specific arguments extending base options']
```

Usage

```
{'parse_test_options': 'parse command-line test options including results_dir, aspect_ratio, phase, num_test, and use_eval flags', 'run_test_with_custom_results_dir': 'run the test phase saving results to a custom directory using the --results_dir argument', 'test_with_specific_num_images': 'test a specific number of images by setting the --num_test argument to a finite integer', 'configure_test_aspect_ratio': 'configure the output image aspect ratio for test results using the --aspect_ratio float argument', 'enable_eval_mode_before_test': 'enable model evaluation mode before running tests by passing the --use_eval flag'}
```

## File: facebookresearch_omnimatterf/third_party/omnimatte/options/train_options.py

Prompts

```
['parse command line arguments for the omnimatte model training or testing configuration', 'gather command line options including model-specific and dataset-specific arguments from argv', 'initialize an argparse parser with common training and test options like dataroot and gpu_ids', 'print parsed options to console and save them to a text file in the checkpoints directory', 'set the active CUDA GPU device based on the gpu_ids command line argument', 'parse command-line test options including results_dir, aspect_ratio, phase, num_test, and use_eval flags', 'run the test phase saving results to a custom directory using the --results_dir argument', 'test a specific number of images by setting the --num_test argument to a finite integer', 'configure the output image aspect ratio for test results using the --aspect_ratio float argument', 'enable model evaluation mode before running tests by passing the --use_eval flag', 'parse training options including learning rate, display frequency, and checkpoint settings for the omnimatte model', 'configure the initial learning rate and decay policy for adam optimizer during training', 'set visdom display frequency, server, port, and environment for training result visualization', 'configure checkpoint save frequency and epoch-based saving for model training results', 'initialize an argparse parser with all training-specific arguments extending base options']
```

Usage

```
{'parse_train_options': 'parse training options including learning rate, display frequency, and checkpoint settings for the omnimatte model', 'configure_learning_rate': 'configure the initial learning rate and decay policy for adam optimizer during training', 'set_display_parameters': 'set visdom display frequency, server, port, and environment for training result visualization', 'configure_checkpoint_saving': 'configure checkpoint save frequency and epoch-based saving for model training results', 'initialize_training_parser': 'initialize an argparse parser with all training-specific arguments extending base options'}
```

