# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/engine/optimizers/adan_t.py

Prompts

```
['create an Adan optimizer instance with custom learning rate and beta parameters for deep model training', 'perform a single optimization step using the Adan optimizer to update model parameters', 'restart the Adan optimizer by resetting step counter and zeroing all exponential moving average states', 'configure the Adan optimizer with decoupled weight decay and optional prox or no_prox mode', 'review the single tensor Adan update function that computes gradient EMA, squared EMA, and difference EMA', 'create a Lamb optimizer instance with custom learning rate and weight decay for model training', 'step the Lamb optimizer to perform a single optimization update on model parameters', 'configure the Lamb optimizer betas for controlling gradient and squared gradient running averages', 'enable LAMBC trust ratio clipping in the Lamb optimizer to cap the trust ratio at one', 'set gradient averaging in the Lamb optimizer to apply beta1 scaling when computing running averages', 'create a LARS optimizer instance with model parameters, learning rate, momentum, and eta coefficient', 'perform a single optimization step with the LARS optimizer using the step method', 'configure LARS optimizer with Nesterov momentum and dampening for improved convergence', 'set weight decay and LARS coefficient eta for layer-wise adaptive rate scaling', 'exclude specific parameter groups from LARS adaptive learning rate scaling using lars_exclude flag', 'build an optimizer wrapper constructor that applies layer-wise learning rate decay for backbone training', 'create a paramwise config dict with layer_decay_rate, norm_decay_mult, and custom_keys for parameter-wise settings', 'test the add_params method to verify parameters are grouped by layer depth with correct learning rates', 'review the LearningRateDecayOptimWrapperConstructor class and its parameter grouping logic for custom decay rules', 'summarize how the get_layer_depth callable determines layer IDs and computes learning rate scaling per parameter']
```

Usage

```
{'create_adan_optimizer': 'create an Adan optimizer instance with custom learning rate and beta parameters for deep model training', 'step_adan_optimizer': 'perform a single optimization step using the Adan optimizer to update model parameters', 'restart_adan_optimizer': 'restart the Adan optimizer by resetting step counter and zeroing all exponential moving average states', 'configure_adan_weight_decay': 'configure the Adan optimizer with decoupled weight decay and optional prox or no_prox mode', 'review_adan_single_tensor': 'review the single tensor Adan update function that computes gradient EMA, squared EMA, and difference EMA'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/engine/optimizers/lamb.py

Prompts

```
['create an Adan optimizer instance with custom learning rate and beta parameters for deep model training', 'perform a single optimization step using the Adan optimizer to update model parameters', 'restart the Adan optimizer by resetting step counter and zeroing all exponential moving average states', 'configure the Adan optimizer with decoupled weight decay and optional prox or no_prox mode', 'review the single tensor Adan update function that computes gradient EMA, squared EMA, and difference EMA', 'create a Lamb optimizer instance with custom learning rate and weight decay for model training', 'step the Lamb optimizer to perform a single optimization update on model parameters', 'configure the Lamb optimizer betas for controlling gradient and squared gradient running averages', 'enable LAMBC trust ratio clipping in the Lamb optimizer to cap the trust ratio at one', 'set gradient averaging in the Lamb optimizer to apply beta1 scaling when computing running averages', 'create a LARS optimizer instance with model parameters, learning rate, momentum, and eta coefficient', 'perform a single optimization step with the LARS optimizer using the step method', 'configure LARS optimizer with Nesterov momentum and dampening for improved convergence', 'set weight decay and LARS coefficient eta for layer-wise adaptive rate scaling', 'exclude specific parameter groups from LARS adaptive learning rate scaling using lars_exclude flag', 'build an optimizer wrapper constructor that applies layer-wise learning rate decay for backbone training', 'create a paramwise config dict with layer_decay_rate, norm_decay_mult, and custom_keys for parameter-wise settings', 'test the add_params method to verify parameters are grouped by layer depth with correct learning rates', 'review the LearningRateDecayOptimWrapperConstructor class and its parameter grouping logic for custom decay rules', 'summarize how the get_layer_depth callable determines layer IDs and computes learning rate scaling per parameter']
```

Usage

```
{'create_Lamb_optimizer': 'create a Lamb optimizer instance with custom learning rate and weight decay for model training', 'step_Lamb_optimizer': 'step the Lamb optimizer to perform a single optimization update on model parameters', 'configure_Lamb_betas': 'configure the Lamb optimizer betas for controlling gradient and squared gradient running averages', 'enable_Lamb_trust_clip': 'enable LAMBC trust ratio clipping in the Lamb optimizer to cap the trust ratio at one', 'set_Lamb_grad_averaging': 'set gradient averaging in the Lamb optimizer to apply beta1 scaling when computing running averages'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/engine/optimizers/lars.py

Prompts

```
['create an Adan optimizer instance with custom learning rate and beta parameters for deep model training', 'perform a single optimization step using the Adan optimizer to update model parameters', 'restart the Adan optimizer by resetting step counter and zeroing all exponential moving average states', 'configure the Adan optimizer with decoupled weight decay and optional prox or no_prox mode', 'review the single tensor Adan update function that computes gradient EMA, squared EMA, and difference EMA', 'create a Lamb optimizer instance with custom learning rate and weight decay for model training', 'step the Lamb optimizer to perform a single optimization update on model parameters', 'configure the Lamb optimizer betas for controlling gradient and squared gradient running averages', 'enable LAMBC trust ratio clipping in the Lamb optimizer to cap the trust ratio at one', 'set gradient averaging in the Lamb optimizer to apply beta1 scaling when computing running averages', 'create a LARS optimizer instance with model parameters, learning rate, momentum, and eta coefficient', 'perform a single optimization step with the LARS optimizer using the step method', 'configure LARS optimizer with Nesterov momentum and dampening for improved convergence', 'set weight decay and LARS coefficient eta for layer-wise adaptive rate scaling', 'exclude specific parameter groups from LARS adaptive learning rate scaling using lars_exclude flag', 'build an optimizer wrapper constructor that applies layer-wise learning rate decay for backbone training', 'create a paramwise config dict with layer_decay_rate, norm_decay_mult, and custom_keys for parameter-wise settings', 'test the add_params method to verify parameters are grouped by layer depth with correct learning rates', 'review the LearningRateDecayOptimWrapperConstructor class and its parameter grouping logic for custom decay rules', 'summarize how the get_layer_depth callable determines layer IDs and computes learning rate scaling per parameter']
```

Usage

```
{'create_lars_optimizer': 'create a LARS optimizer instance with model parameters, learning rate, momentum, and eta coefficient', 'step_lars_optimizer': 'perform a single optimization step with the LARS optimizer using the step method', 'configure_lars_momentum': 'configure LARS optimizer with Nesterov momentum and dampening for improved convergence', 'set_lars_weight_decay': 'set weight decay and LARS coefficient eta for layer-wise adaptive rate scaling', 'exclude_lars_adaptive_lr': 'exclude specific parameter groups from LARS adaptive learning rate scaling using lars_exclude flag'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/engine/optimizers/layer_decay_optim_wrapper_constructor.py

Prompts

```
['create an Adan optimizer instance with custom learning rate and beta parameters for deep model training', 'perform a single optimization step using the Adan optimizer to update model parameters', 'restart the Adan optimizer by resetting step counter and zeroing all exponential moving average states', 'configure the Adan optimizer with decoupled weight decay and optional prox or no_prox mode', 'review the single tensor Adan update function that computes gradient EMA, squared EMA, and difference EMA', 'create a Lamb optimizer instance with custom learning rate and weight decay for model training', 'step the Lamb optimizer to perform a single optimization update on model parameters', 'configure the Lamb optimizer betas for controlling gradient and squared gradient running averages', 'enable LAMBC trust ratio clipping in the Lamb optimizer to cap the trust ratio at one', 'set gradient averaging in the Lamb optimizer to apply beta1 scaling when computing running averages', 'create a LARS optimizer instance with model parameters, learning rate, momentum, and eta coefficient', 'perform a single optimization step with the LARS optimizer using the step method', 'configure LARS optimizer with Nesterov momentum and dampening for improved convergence', 'set weight decay and LARS coefficient eta for layer-wise adaptive rate scaling', 'exclude specific parameter groups from LARS adaptive learning rate scaling using lars_exclude flag', 'build an optimizer wrapper constructor that applies layer-wise learning rate decay for backbone training', 'create a paramwise config dict with layer_decay_rate, norm_decay_mult, and custom_keys for parameter-wise settings', 'test the add_params method to verify parameters are grouped by layer depth with correct learning rates', 'review the LearningRateDecayOptimWrapperConstructor class and its parameter grouping logic for custom decay rules', 'summarize how the get_layer_depth callable determines layer IDs and computes learning rate scaling per parameter']
```

Usage

```
{'build_layer_decay_optimizer': 'build an optimizer wrapper constructor that applies layer-wise learning rate decay for backbone training', 'create_paramwise_cfg': 'create a paramwise config dict with layer_decay_rate, norm_decay_mult, and custom_keys for parameter-wise settings', 'test_add_params': 'test the add_params method to verify parameters are grouped by layer depth with correct learning rates', 'review_LearningRateDecayOptimWrapperConstructor': 'review the LearningRateDecayOptimWrapperConstructor class and its parameter grouping logic for custom decay rules', 'summarize_get_layer_depth': 'summarize how the get_layer_depth callable determines layer IDs and computes learning rate scaling per parameter'}
```

