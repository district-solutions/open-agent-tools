# Agent Python Tools

- repo: facebookresearch/consistentdepth
- repo_uri: https://github.com/facebookresearch/consistent_depth

## File: facebookresearch_consistentdepth/monodepth/mannequin_challenge/options/base_options.py

Prompts

```
['create a BaseOptions instance to build an argparse parser for monocular depth estimation CLI arguments', 'initialize the BaseOptions parser with all default arguments for input type, model, GPU, and batch config', 'parse command line arguments using BaseOptions to get a namespace with all experiment configuration options', 'configure GPU device IDs by passing a comma-separated string like 0,1,2,3 to the gpu_ids argument', 'review the BaseOptions class to understand the argparse arguments for single_view, two_view, and two_view_k input modes', 'parse command line arguments to configure GAN training hyperparameters and save options to disk', 'set the initial learning rate, beta1 momentum, and lr_policy for the Adam optimizer', 'configure niter, niter_decay, and lr_decay_epoch to control training iterations and learning rate decay', 'set lambda_A and lambda_B weights for cycle consistency loss in cycle GAN training', 'configure display_freq, print_freq, save_latest_freq, and save_epoch_freq for training output and checkpoint frequency']
```

Usage

```
{'create_BaseOptions_parser': 'create a BaseOptions instance to build an argparse parser for monocular depth estimation CLI arguments', 'initialize_BaseOptions_arguments': 'initialize the BaseOptions parser with all default arguments for input type, model, GPU, and batch config', 'parse_BaseOptions_cli': 'parse command line arguments using BaseOptions to get a namespace with all experiment configuration options', 'configure_BaseOptions_gpu_ids': 'configure GPU device IDs by passing a comma-separated string like 0,1,2,3 to the gpu_ids argument', 'review_BaseOptions_class': 'review the BaseOptions class to understand the argparse arguments for single_view, two_view, and two_view_k input modes'}
```

## File: facebookresearch_consistentdepth/monodepth/mannequin_challenge/options/train_options.py

Prompts

```
['create a BaseOptions instance to build an argparse parser for monocular depth estimation CLI arguments', 'initialize the BaseOptions parser with all default arguments for input type, model, GPU, and batch config', 'parse command line arguments using BaseOptions to get a namespace with all experiment configuration options', 'configure GPU device IDs by passing a comma-separated string like 0,1,2,3 to the gpu_ids argument', 'review the BaseOptions class to understand the argparse arguments for single_view, two_view, and two_view_k input modes', 'parse command line arguments to configure GAN training hyperparameters and save options to disk', 'set the initial learning rate, beta1 momentum, and lr_policy for the Adam optimizer', 'configure niter, niter_decay, and lr_decay_epoch to control training iterations and learning rate decay', 'set lambda_A and lambda_B weights for cycle consistency loss in cycle GAN training', 'configure display_freq, print_freq, save_latest_freq, and save_epoch_freq for training output and checkpoint frequency']
```

Usage

```
{'parse_train_options': 'parse command line arguments to configure GAN training hyperparameters and save options to disk', 'configure_learning_rate': 'set the initial learning rate, beta1 momentum, and lr_policy for the Adam optimizer', 'set_training_schedule': 'configure niter, niter_decay, and lr_decay_epoch to control training iterations and learning rate decay', 'configure_cycle_gan_loss': 'set lambda_A and lambda_B weights for cycle consistency loss in cycle GAN training', 'customize_display_and_saving': 'configure display_freq, print_freq, save_latest_freq, and save_epoch_freq for training output and checkpoint frequency'}
```

