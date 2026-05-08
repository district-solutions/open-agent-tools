# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/translation_moe/translation_moe_src/logsumexp_moe.py

Prompts

```
['use LogSumExpMoE forward pass to compute log-sum-exp of log probabilities along a dimension', 'use LogSumExpMoE backward pass to compute gradients using posterior probabilities instead of softmax', 'create a custom PyTorch autograd function that uses posterior probabilities for gradient computation', 'implement a Mixture of Experts loss function with standard LogSumExp forward and posterior-based backward', 'apply the LogSumExpMoE autograd function to diverse machine translation models with mixture-of-experts routing', 'create a MeanPoolGatingNetwork with a given embed_dim and number of experts for MoE routing', 'build a MeanPoolGatingNetwork with dropout regularization between the two linear layers', 'run the forward pass of MeanPoolGatingNetwork on a TransformerEncoder output dictionary', 'review the MeanPoolGatingNetwork forward method and its padding-aware mean pooling logic', 'test the MeanPoolGatingNetwork forward method to validate encoder_out format and dimension checks', 'build a TranslationMoETask with fairseq to train a Mixture of Experts translation model', 'configure TranslationMoEConfig to set MoE method, number of experts, and gating network options', 'run a training step for the TranslationMoETask using the _get_loss method with hard or soft selection', 'run inference with TranslationMoETask inference_step to generate translations using a specific expert', 'review the MeanPoolGatingNetwork gating network used for learned prior MoE methods in translation_moe']
```

Usage

```
{'use_logsumexpmoe_forward': 'use LogSumExpMoE forward pass to compute log-sum-exp of log probabilities along a dimension', 'use_logsumexpmoe_backward': 'use LogSumExpMoE backward pass to compute gradients using posterior probabilities instead of softmax', 'create_custom_autograd_function': 'create a custom PyTorch autograd function that uses posterior probabilities for gradient computation', 'implement_moe_loss': 'implement a Mixture of Experts loss function with standard LogSumExp forward and posterior-based backward', 'apply_logsumexp_moe_to_translation': 'apply the LogSumExpMoE autograd function to diverse machine translation models with mixture-of-experts routing'}
```

## File: facebookresearch_fairseq/examples/translation_moe/translation_moe_src/mean_pool_gating_network.py

Prompts

```
['use LogSumExpMoE forward pass to compute log-sum-exp of log probabilities along a dimension', 'use LogSumExpMoE backward pass to compute gradients using posterior probabilities instead of softmax', 'create a custom PyTorch autograd function that uses posterior probabilities for gradient computation', 'implement a Mixture of Experts loss function with standard LogSumExp forward and posterior-based backward', 'apply the LogSumExpMoE autograd function to diverse machine translation models with mixture-of-experts routing', 'create a MeanPoolGatingNetwork with a given embed_dim and number of experts for MoE routing', 'build a MeanPoolGatingNetwork with dropout regularization between the two linear layers', 'run the forward pass of MeanPoolGatingNetwork on a TransformerEncoder output dictionary', 'review the MeanPoolGatingNetwork forward method and its padding-aware mean pooling logic', 'test the MeanPoolGatingNetwork forward method to validate encoder_out format and dimension checks', 'build a TranslationMoETask with fairseq to train a Mixture of Experts translation model', 'configure TranslationMoEConfig to set MoE method, number of experts, and gating network options', 'run a training step for the TranslationMoETask using the _get_loss method with hard or soft selection', 'run inference with TranslationMoETask inference_step to generate translations using a specific expert', 'review the MeanPoolGatingNetwork gating network used for learned prior MoE methods in translation_moe']
```

Usage

```
{'create_MeanPoolGatingNetwork': 'create a MeanPoolGatingNetwork with a given embed_dim and number of experts for MoE routing', 'build_MeanPoolGatingNetwork_with_dropout': 'build a MeanPoolGatingNetwork with dropout regularization between the two linear layers', 'run_MeanPoolGatingNetwork_forward': 'run the forward pass of MeanPoolGatingNetwork on a TransformerEncoder output dictionary', 'review_MeanPoolGatingNetwork_mean_pooling': 'review the MeanPoolGatingNetwork forward method and its padding-aware mean pooling logic', 'test_MeanPoolGatingNetwork_validation': 'test the MeanPoolGatingNetwork forward method to validate encoder_out format and dimension checks'}
```

## File: facebookresearch_fairseq/examples/translation_moe/translation_moe_src/translation_moe.py

Prompts

```
['use LogSumExpMoE forward pass to compute log-sum-exp of log probabilities along a dimension', 'use LogSumExpMoE backward pass to compute gradients using posterior probabilities instead of softmax', 'create a custom PyTorch autograd function that uses posterior probabilities for gradient computation', 'implement a Mixture of Experts loss function with standard LogSumExp forward and posterior-based backward', 'apply the LogSumExpMoE autograd function to diverse machine translation models with mixture-of-experts routing', 'create a MeanPoolGatingNetwork with a given embed_dim and number of experts for MoE routing', 'build a MeanPoolGatingNetwork with dropout regularization between the two linear layers', 'run the forward pass of MeanPoolGatingNetwork on a TransformerEncoder output dictionary', 'review the MeanPoolGatingNetwork forward method and its padding-aware mean pooling logic', 'test the MeanPoolGatingNetwork forward method to validate encoder_out format and dimension checks', 'build a TranslationMoETask with fairseq to train a Mixture of Experts translation model', 'configure TranslationMoEConfig to set MoE method, number of experts, and gating network options', 'run a training step for the TranslationMoETask using the _get_loss method with hard or soft selection', 'run inference with TranslationMoETask inference_step to generate translations using a specific expert', 'review the MeanPoolGatingNetwork gating network used for learned prior MoE methods in translation_moe']
```

Usage

```
{'build_translation_moe_task': 'build a TranslationMoETask with fairseq to train a Mixture of Experts translation model', 'configure_translation_moe_config': 'configure TranslationMoEConfig to set MoE method, number of experts, and gating network options', 'run_train_step_moe': 'run a training step for the TranslationMoETask using the _get_loss method with hard or soft selection', 'run_inference_step_moe': 'run inference with TranslationMoETask inference_step to generate translations using a specific expert', 'review_gating_network': 'review the MeanPoolGatingNetwork gating network used for learned prior MoE methods in translation_moe'}
```

