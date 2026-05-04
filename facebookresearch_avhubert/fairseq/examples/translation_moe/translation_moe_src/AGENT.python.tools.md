# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/translation_moe/translation_moe_src/logsumexp_moe.py

Prompts

```
['use LogSumExpMoE to compute log-sum-exp forward pass with posterior-based backward for MoE translation', 'use LogSumExpMoE backward pass to compute gradients using posterior probabilities instead of softmax', 'create a mixture of experts layer using LogSumExpMoE for diverse machine translation tasks', 'test the LogSumExpMoE class forward and backward passes with torch tensors', 'review the LogSumExpMoE class implementation for mixture of experts translation models', 'build a MeanPoolGatingNetwork with a given embed_dim and num_experts for MoE expert selection', 'create a MeanPoolGatingNetwork with dropout regularization for robust expert gating in translation models', 'run a forward pass on the MeanPoolGatingNetwork with encoder_out to get expert responsibilities', 'review the MeanPoolGatingNetwork class and its mean pooling logic for expert selection', 'test the MeanPoolGatingNetwork forward method with encoder output and padding mask inputs', 'build a TranslationMoETask with source and target dictionaries for mixture of experts translation', 'configure TranslationMoEConfig with method num_experts and mean_pool_gating_network settings', 'run a training step for the MoE translation task with sample model and criterion', 'run inference with a specific expert using the MoE translation task generator', 'review the _get_loss method to understand soft and hard MoE loss computation']
```

Usage

```
{'use_logsumexp_moe_forward': 'use LogSumExpMoE to compute log-sum-exp forward pass with posterior-based backward for MoE translation', 'use_logsumexp_moe_backward': 'use LogSumExpMoE backward pass to compute gradients using posterior probabilities instead of softmax', 'create_moe_layer': 'create a mixture of experts layer using LogSumExpMoE for diverse machine translation tasks', 'test_logsumexp_moe': 'test the LogSumExpMoE class forward and backward passes with torch tensors', 'review_logsumexp_moe': 'review the LogSumExpMoE class implementation for mixture of experts translation models'}
```

## File: facebookresearch_avhubert/fairseq/examples/translation_moe/translation_moe_src/mean_pool_gating_network.py

Prompts

```
['use LogSumExpMoE to compute log-sum-exp forward pass with posterior-based backward for MoE translation', 'use LogSumExpMoE backward pass to compute gradients using posterior probabilities instead of softmax', 'create a mixture of experts layer using LogSumExpMoE for diverse machine translation tasks', 'test the LogSumExpMoE class forward and backward passes with torch tensors', 'review the LogSumExpMoE class implementation for mixture of experts translation models', 'build a MeanPoolGatingNetwork with a given embed_dim and num_experts for MoE expert selection', 'create a MeanPoolGatingNetwork with dropout regularization for robust expert gating in translation models', 'run a forward pass on the MeanPoolGatingNetwork with encoder_out to get expert responsibilities', 'review the MeanPoolGatingNetwork class and its mean pooling logic for expert selection', 'test the MeanPoolGatingNetwork forward method with encoder output and padding mask inputs', 'build a TranslationMoETask with source and target dictionaries for mixture of experts translation', 'configure TranslationMoEConfig with method num_experts and mean_pool_gating_network settings', 'run a training step for the MoE translation task with sample model and criterion', 'run inference with a specific expert using the MoE translation task generator', 'review the _get_loss method to understand soft and hard MoE loss computation']
```

Usage

```
{'build_mean_pool_gating_network': 'build a MeanPoolGatingNetwork with a given embed_dim and num_experts for MoE expert selection', 'create_gating_network_with_dropout': 'create a MeanPoolGatingNetwork with dropout regularization for robust expert gating in translation models', 'run_forward_pass_gating_network': 'run a forward pass on the MeanPoolGatingNetwork with encoder_out to get expert responsibilities', 'review_mean_pool_gating_network': 'review the MeanPoolGatingNetwork class and its mean pooling logic for expert selection', 'test_gating_network_forward': 'test the MeanPoolGatingNetwork forward method with encoder output and padding mask inputs'}
```

## File: facebookresearch_avhubert/fairseq/examples/translation_moe/translation_moe_src/translation_moe.py

Prompts

```
['use LogSumExpMoE to compute log-sum-exp forward pass with posterior-based backward for MoE translation', 'use LogSumExpMoE backward pass to compute gradients using posterior probabilities instead of softmax', 'create a mixture of experts layer using LogSumExpMoE for diverse machine translation tasks', 'test the LogSumExpMoE class forward and backward passes with torch tensors', 'review the LogSumExpMoE class implementation for mixture of experts translation models', 'build a MeanPoolGatingNetwork with a given embed_dim and num_experts for MoE expert selection', 'create a MeanPoolGatingNetwork with dropout regularization for robust expert gating in translation models', 'run a forward pass on the MeanPoolGatingNetwork with encoder_out to get expert responsibilities', 'review the MeanPoolGatingNetwork class and its mean pooling logic for expert selection', 'test the MeanPoolGatingNetwork forward method with encoder output and padding mask inputs', 'build a TranslationMoETask with source and target dictionaries for mixture of experts translation', 'configure TranslationMoEConfig with method num_experts and mean_pool_gating_network settings', 'run a training step for the MoE translation task with sample model and criterion', 'run inference with a specific expert using the MoE translation task generator', 'review the _get_loss method to understand soft and hard MoE loss computation']
```

Usage

```
{'build_translation_moe_task': 'build a TranslationMoETask with source and target dictionaries for mixture of experts translation', 'configure_translation_moe_config': 'configure TranslationMoEConfig with method num_experts and mean_pool_gating_network settings', 'run_train_step_moe': 'run a training step for the MoE translation task with sample model and criterion', 'run_inference_step_moe': 'run inference with a specific expert using the MoE translation task generator', 'review_get_loss_moe': 'review the _get_loss method to understand soft and hard MoE loss computation'}
```

