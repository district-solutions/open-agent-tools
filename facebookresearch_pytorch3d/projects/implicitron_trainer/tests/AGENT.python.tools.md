# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/projects/implicitron_trainer/tests/test_experiment.py

Prompts

```
['test the Experiment class with default config values and verify multistep learning rate milestones', 'test the Experiment class with an exponential LR policy and verify gamma decay across epochs', 'test that the default Experiment config values match the expected experiment.yaml file contents', 'test that all pre-prepared Hydra YAML config files in the configs directory are valid and composable', 'test the ImplicitronOptimizerFactory to create Adam, SGD, and Adagrad optimizers with their learning rate schedulers', 'test the ImplicitronOptimizerFactory to verify parameter group assignment for PyTorch model modules', 'test that all parameters are assigned to the default group when no param_groups are defined', 'test that a parent module param_groups member key overrides default group assignment for child parameters', 'test that a module self param_groups key overrides a parent member key assignment', 'test complex tree assignment with parameter level, self level, member level, and default group resolution', 'test the visualize_reconstruction module by running it with default camera and render size arguments', 'run the TestVisualize unit test class to validate reconstruction visualization with interactive testing', 'test visualize_reconstruction.main with custom exp_dir, n_eval_cameras, render_size, and video_size arguments', 'review the TestVisualize test_from_defaults method to understand interactive testing and environment variable usage', 'summarize the test_visualize module that tests Implicitron reconstruction visualization via visualize_reconstruction.main', 'use the intercept_logs context manager to capture log messages matching a regex pattern from a named logger', 'test the intercept_logs function by capturing warning messages from a specific logger using a regex filter', 'create a log interceptor that captures all error-level messages from a logger using a regex pattern', 'check if interactive testing mode is enabled by calling interactive_testing_requested which reads the PYTORCH3D_INTERACTIVE_TESTING env var', 'review the intercept_logs context manager to verify the logger filter is properly removed in the finally block']
```

Usage

```
{'test_experiment_from_defaults': 'test the Experiment class with default config values and verify multistep learning rate milestones', 'test_exponential_lr_schedule': 'test the Experiment class with an exponential LR policy and verify gamma decay across epochs', 'test_yaml_config_contents': 'test that the default Experiment config values match the expected experiment.yaml file contents', 'test_load_hydra_configs': 'test that all pre-prepared Hydra YAML config files in the configs directory are valid and composable', 'test_optimizer_factory': 'test the ImplicitronOptimizerFactory to create Adam, SGD, and Adagrad optimizers with their learning rate schedulers'}
```

## File: facebookresearch_pytorch3d/projects/implicitron_trainer/tests/test_optimizer_factory.py

Prompts

```
['test the Experiment class with default config values and verify multistep learning rate milestones', 'test the Experiment class with an exponential LR policy and verify gamma decay across epochs', 'test that the default Experiment config values match the expected experiment.yaml file contents', 'test that all pre-prepared Hydra YAML config files in the configs directory are valid and composable', 'test the ImplicitronOptimizerFactory to create Adam, SGD, and Adagrad optimizers with their learning rate schedulers', 'test the ImplicitronOptimizerFactory to verify parameter group assignment for PyTorch model modules', 'test that all parameters are assigned to the default group when no param_groups are defined', 'test that a parent module param_groups member key overrides default group assignment for child parameters', 'test that a module self param_groups key overrides a parent member key assignment', 'test complex tree assignment with parameter level, self level, member level, and default group resolution', 'test the visualize_reconstruction module by running it with default camera and render size arguments', 'run the TestVisualize unit test class to validate reconstruction visualization with interactive testing', 'test visualize_reconstruction.main with custom exp_dir, n_eval_cameras, render_size, and video_size arguments', 'review the TestVisualize test_from_defaults method to understand interactive testing and environment variable usage', 'summarize the test_visualize module that tests Implicitron reconstruction visualization via visualize_reconstruction.main', 'use the intercept_logs context manager to capture log messages matching a regex pattern from a named logger', 'test the intercept_logs function by capturing warning messages from a specific logger using a regex filter', 'create a log interceptor that captures all error-level messages from a logger using a regex pattern', 'check if interactive testing mode is enabled by calling interactive_testing_requested which reads the PYTORCH3D_INTERACTIVE_TESTING env var', 'review the intercept_logs context manager to verify the logger filter is properly removed in the finally block']
```

Usage

```
{'test_ImplicitronOptimizerFactory_param_groups': 'test the ImplicitronOptimizerFactory to verify parameter group assignment for PyTorch model modules', 'test_default_param_group_assignment': 'test that all parameters are assigned to the default group when no param_groups are defined', 'test_member_overrides_default': 'test that a parent module param_groups member key overrides default group assignment for child parameters', 'test_self_overrides_member': 'test that a module self param_groups key overrides a parent member key assignment', 'test_tree_param_groups': 'test complex tree assignment with parameter level, self level, member level, and default group resolution'}
```

## File: facebookresearch_pytorch3d/projects/implicitron_trainer/tests/test_visualize.py

Prompts

```
['test the Experiment class with default config values and verify multistep learning rate milestones', 'test the Experiment class with an exponential LR policy and verify gamma decay across epochs', 'test that the default Experiment config values match the expected experiment.yaml file contents', 'test that all pre-prepared Hydra YAML config files in the configs directory are valid and composable', 'test the ImplicitronOptimizerFactory to create Adam, SGD, and Adagrad optimizers with their learning rate schedulers', 'test the ImplicitronOptimizerFactory to verify parameter group assignment for PyTorch model modules', 'test that all parameters are assigned to the default group when no param_groups are defined', 'test that a parent module param_groups member key overrides default group assignment for child parameters', 'test that a module self param_groups key overrides a parent member key assignment', 'test complex tree assignment with parameter level, self level, member level, and default group resolution', 'test the visualize_reconstruction module by running it with default camera and render size arguments', 'run the TestVisualize unit test class to validate reconstruction visualization with interactive testing', 'test visualize_reconstruction.main with custom exp_dir, n_eval_cameras, render_size, and video_size arguments', 'review the TestVisualize test_from_defaults method to understand interactive testing and environment variable usage', 'summarize the test_visualize module that tests Implicitron reconstruction visualization via visualize_reconstruction.main', 'use the intercept_logs context manager to capture log messages matching a regex pattern from a named logger', 'test the intercept_logs function by capturing warning messages from a specific logger using a regex filter', 'create a log interceptor that captures all error-level messages from a logger using a regex pattern', 'check if interactive testing mode is enabled by calling interactive_testing_requested which reads the PYTORCH3D_INTERACTIVE_TESTING env var', 'review the intercept_logs context manager to verify the logger filter is properly removed in the finally block']
```

Usage

```
{'test_visualize_reconstruction_from_defaults': 'test the visualize_reconstruction module by running it with default camera and render size arguments', 'run_test_visualize_class': 'run the TestVisualize unit test class to validate reconstruction visualization with interactive testing', 'test_visualize_with_custom_argv': 'test visualize_reconstruction.main with custom exp_dir, n_eval_cameras, render_size, and video_size arguments', 'review_test_visualize_test_from_defaults': 'review the TestVisualize test_from_defaults method to understand interactive testing and environment variable usage', 'summarize_test_visualize_module': 'summarize the test_visualize module that tests Implicitron reconstruction visualization via visualize_reconstruction.main'}
```

## File: facebookresearch_pytorch3d/projects/implicitron_trainer/tests/utils.py

Prompts

```
['test the Experiment class with default config values and verify multistep learning rate milestones', 'test the Experiment class with an exponential LR policy and verify gamma decay across epochs', 'test that the default Experiment config values match the expected experiment.yaml file contents', 'test that all pre-prepared Hydra YAML config files in the configs directory are valid and composable', 'test the ImplicitronOptimizerFactory to create Adam, SGD, and Adagrad optimizers with their learning rate schedulers', 'test the ImplicitronOptimizerFactory to verify parameter group assignment for PyTorch model modules', 'test that all parameters are assigned to the default group when no param_groups are defined', 'test that a parent module param_groups member key overrides default group assignment for child parameters', 'test that a module self param_groups key overrides a parent member key assignment', 'test complex tree assignment with parameter level, self level, member level, and default group resolution', 'test the visualize_reconstruction module by running it with default camera and render size arguments', 'run the TestVisualize unit test class to validate reconstruction visualization with interactive testing', 'test visualize_reconstruction.main with custom exp_dir, n_eval_cameras, render_size, and video_size arguments', 'review the TestVisualize test_from_defaults method to understand interactive testing and environment variable usage', 'summarize the test_visualize module that tests Implicitron reconstruction visualization via visualize_reconstruction.main', 'use the intercept_logs context manager to capture log messages matching a regex pattern from a named logger', 'test the intercept_logs function by capturing warning messages from a specific logger using a regex filter', 'create a log interceptor that captures all error-level messages from a logger using a regex pattern', 'check if interactive testing mode is enabled by calling interactive_testing_requested which reads the PYTORCH3D_INTERACTIVE_TESTING env var', 'review the intercept_logs context manager to verify the logger filter is properly removed in the finally block']
```

Usage

```
{'intercept_logs_context_manager': 'use the intercept_logs context manager to capture log messages matching a regex pattern from a named logger', 'test_intercept_logs': 'test the intercept_logs function by capturing warning messages from a specific logger using a regex filter', 'create_log_interceptor': 'create a log interceptor that captures all error-level messages from a logger using a regex pattern', 'interactive_testing_requested_check': 'check if interactive testing mode is enabled by calling interactive_testing_requested which reads the PYTORCH3D_INTERACTIVE_TESTING env var', 'review_intercept_logs_cleanup': 'review the intercept_logs context manager to verify the logger filter is properly removed in the finally block'}
```

