# Agent Python Tools

- repo: facebookresearch/madgrad
- repo_uri: https://github.com/facebookresearch/madgrad

## File: facebookresearch_madgrad/madgrad/fairseq_madgrad.py

Prompts

```
['build a FairseqMADGRAD optimizer instance with args and model parameters for training', 'create an optimizer config dictionary with lr, momentum, weight_decay, eps, and decouple_decay', 'register the MADGRAD optimizer with Fairseq using the register_optimizer decorator', 'add optimizer-specific CLI arguments for weight decay, momentum, eps, and decouple_decay to a parser', 'review the FairseqMADGRAD class that wraps MADGRAD as a Fairseq optimizer', 'create a FairSeqMirrorMADGRAD optimizer instance with args and model parameters for training', 'register the mirror_madgrad optimizer with fairseq using the register_optimizer decorator', 'add optimizer-specific CLI arguments like weight-decay momentum eps and decouple_decay to a parser', 'review the optimizer_config property that returns lr momentum weight_decay eps and decouple_decay kwargs', 'summarize the FairSeqMirrorMADGRAD class which wraps MirrorMADGRAD as a fairseq optimizer for large model training', 'create a MADGRAD optimizer instance with custom learning rate and momentum for model training', 'perform a single optimization step using the MADGRAD optimizer to update model parameters', 'configure the MADGRAD optimizer with momentum values in the range [0,1) for stochastic optimization', 'enable AdamW style decoupled weight decay on the MADGRAD optimizer for better regularization', 'check if the MADGRAD optimizer supports memory efficient fp16 and flat params for GPU training', 'create a MirrorMADGRAD optimizer instance with custom learning rate, momentum, and weight decay parameters', 'run a single optimization step using the MirrorMADGRAD optimizer to update model parameters', 'configure the MirrorMADGRAD optimizer with AdamW style decoupled weight decay enabled', 'review the MirrorMADGRAD optimizer memory efficient fp16 and flat params support properties', 'test the MirrorMADGRAD optimizer constructor validation for momentum, learning rate, weight decay, and eps bounds']
```

Usage

```
{'build_fairseq_optimizer': 'build a FairseqMADGRAD optimizer instance with args and model parameters for training', 'create_optimizer_config': 'create an optimizer config dictionary with lr, momentum, weight_decay, eps, and decouple_decay', 'register_optimizer_madgrad': 'register the MADGRAD optimizer with Fairseq using the register_optimizer decorator', 'add_args_parser': 'add optimizer-specific CLI arguments for weight decay, momentum, eps, and decouple_decay to a parser', 'review_fairseqmadgrad_class': 'review the FairseqMADGRAD class that wraps MADGRAD as a Fairseq optimizer'}
```

## File: facebookresearch_madgrad/madgrad/fairseq_mirror_madgrad.py

Prompts

```
['build a FairseqMADGRAD optimizer instance with args and model parameters for training', 'create an optimizer config dictionary with lr, momentum, weight_decay, eps, and decouple_decay', 'register the MADGRAD optimizer with Fairseq using the register_optimizer decorator', 'add optimizer-specific CLI arguments for weight decay, momentum, eps, and decouple_decay to a parser', 'review the FairseqMADGRAD class that wraps MADGRAD as a Fairseq optimizer', 'create a FairSeqMirrorMADGRAD optimizer instance with args and model parameters for training', 'register the mirror_madgrad optimizer with fairseq using the register_optimizer decorator', 'add optimizer-specific CLI arguments like weight-decay momentum eps and decouple_decay to a parser', 'review the optimizer_config property that returns lr momentum weight_decay eps and decouple_decay kwargs', 'summarize the FairSeqMirrorMADGRAD class which wraps MirrorMADGRAD as a fairseq optimizer for large model training', 'create a MADGRAD optimizer instance with custom learning rate and momentum for model training', 'perform a single optimization step using the MADGRAD optimizer to update model parameters', 'configure the MADGRAD optimizer with momentum values in the range [0,1) for stochastic optimization', 'enable AdamW style decoupled weight decay on the MADGRAD optimizer for better regularization', 'check if the MADGRAD optimizer supports memory efficient fp16 and flat params for GPU training', 'create a MirrorMADGRAD optimizer instance with custom learning rate, momentum, and weight decay parameters', 'run a single optimization step using the MirrorMADGRAD optimizer to update model parameters', 'configure the MirrorMADGRAD optimizer with AdamW style decoupled weight decay enabled', 'review the MirrorMADGRAD optimizer memory efficient fp16 and flat params support properties', 'test the MirrorMADGRAD optimizer constructor validation for momentum, learning rate, weight decay, and eps bounds']
```

Usage

```
{'create_optimizer': 'create a FairSeqMirrorMADGRAD optimizer instance with args and model parameters for training', 'register_optimizer': 'register the mirror_madgrad optimizer with fairseq using the register_optimizer decorator', 'add_args': 'add optimizer-specific CLI arguments like weight-decay momentum eps and decouple_decay to a parser', 'review_optimizer_config': 'review the optimizer_config property that returns lr momentum weight_decay eps and decouple_decay kwargs', 'summarize_FairSeqMirrorMADGRAD': 'summarize the FairSeqMirrorMADGRAD class which wraps MirrorMADGRAD as a fairseq optimizer for large model training'}
```

## File: facebookresearch_madgrad/madgrad/madgrad.py

Prompts

```
['build a FairseqMADGRAD optimizer instance with args and model parameters for training', 'create an optimizer config dictionary with lr, momentum, weight_decay, eps, and decouple_decay', 'register the MADGRAD optimizer with Fairseq using the register_optimizer decorator', 'add optimizer-specific CLI arguments for weight decay, momentum, eps, and decouple_decay to a parser', 'review the FairseqMADGRAD class that wraps MADGRAD as a Fairseq optimizer', 'create a FairSeqMirrorMADGRAD optimizer instance with args and model parameters for training', 'register the mirror_madgrad optimizer with fairseq using the register_optimizer decorator', 'add optimizer-specific CLI arguments like weight-decay momentum eps and decouple_decay to a parser', 'review the optimizer_config property that returns lr momentum weight_decay eps and decouple_decay kwargs', 'summarize the FairSeqMirrorMADGRAD class which wraps MirrorMADGRAD as a fairseq optimizer for large model training', 'create a MADGRAD optimizer instance with custom learning rate and momentum for model training', 'perform a single optimization step using the MADGRAD optimizer to update model parameters', 'configure the MADGRAD optimizer with momentum values in the range [0,1) for stochastic optimization', 'enable AdamW style decoupled weight decay on the MADGRAD optimizer for better regularization', 'check if the MADGRAD optimizer supports memory efficient fp16 and flat params for GPU training', 'create a MirrorMADGRAD optimizer instance with custom learning rate, momentum, and weight decay parameters', 'run a single optimization step using the MirrorMADGRAD optimizer to update model parameters', 'configure the MirrorMADGRAD optimizer with AdamW style decoupled weight decay enabled', 'review the MirrorMADGRAD optimizer memory efficient fp16 and flat params support properties', 'test the MirrorMADGRAD optimizer constructor validation for momentum, learning rate, weight decay, and eps bounds']
```

Usage

```
{'create_optimizer_madgrad': 'create a MADGRAD optimizer instance with custom learning rate and momentum for model training', 'step_optimizer_madgrad': 'perform a single optimization step using the MADGRAD optimizer to update model parameters', 'configure_momentum_madgrad': 'configure the MADGRAD optimizer with momentum values in the range [0,1) for stochastic optimization', 'enable_decoupled_decay_madgrad': 'enable AdamW style decoupled weight decay on the MADGRAD optimizer for better regularization', 'check_fp16_support_madgrad': 'check if the MADGRAD optimizer supports memory efficient fp16 and flat params for GPU training'}
```

## File: facebookresearch_madgrad/madgrad/mirror_madgrad.py

Prompts

```
['build a FairseqMADGRAD optimizer instance with args and model parameters for training', 'create an optimizer config dictionary with lr, momentum, weight_decay, eps, and decouple_decay', 'register the MADGRAD optimizer with Fairseq using the register_optimizer decorator', 'add optimizer-specific CLI arguments for weight decay, momentum, eps, and decouple_decay to a parser', 'review the FairseqMADGRAD class that wraps MADGRAD as a Fairseq optimizer', 'create a FairSeqMirrorMADGRAD optimizer instance with args and model parameters for training', 'register the mirror_madgrad optimizer with fairseq using the register_optimizer decorator', 'add optimizer-specific CLI arguments like weight-decay momentum eps and decouple_decay to a parser', 'review the optimizer_config property that returns lr momentum weight_decay eps and decouple_decay kwargs', 'summarize the FairSeqMirrorMADGRAD class which wraps MirrorMADGRAD as a fairseq optimizer for large model training', 'create a MADGRAD optimizer instance with custom learning rate and momentum for model training', 'perform a single optimization step using the MADGRAD optimizer to update model parameters', 'configure the MADGRAD optimizer with momentum values in the range [0,1) for stochastic optimization', 'enable AdamW style decoupled weight decay on the MADGRAD optimizer for better regularization', 'check if the MADGRAD optimizer supports memory efficient fp16 and flat params for GPU training', 'create a MirrorMADGRAD optimizer instance with custom learning rate, momentum, and weight decay parameters', 'run a single optimization step using the MirrorMADGRAD optimizer to update model parameters', 'configure the MirrorMADGRAD optimizer with AdamW style decoupled weight decay enabled', 'review the MirrorMADGRAD optimizer memory efficient fp16 and flat params support properties', 'test the MirrorMADGRAD optimizer constructor validation for momentum, learning rate, weight decay, and eps bounds']
```

Usage

```
{'create_MirrorMADGRAD_optimizer': 'create a MirrorMADGRAD optimizer instance with custom learning rate, momentum, and weight decay parameters', 'run_MirrorMADGRAD_step': 'run a single optimization step using the MirrorMADGRAD optimizer to update model parameters', 'configure_MirrorMADGRAD_decouple_decay': 'configure the MirrorMADGRAD optimizer with AdamW style decoupled weight decay enabled', 'review_MirrorMADGRAD_fp16_support': 'review the MirrorMADGRAD optimizer memory efficient fp16 and flat params support properties', 'test_MirrorMADGRAD_validation': 'test the MirrorMADGRAD optimizer constructor validation for momentum, learning rate, weight decay, and eps bounds'}
```

