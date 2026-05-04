# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/language_bottleneck/intervention.py

Prompts

```
['compute the Shannon entropy in bits of a list of message tensors using frequency counting', 'calculate the mutual information between two lists of tensors by combining their individual and joint entropies', 'evaluate a game by shuffling messages across examples and measuring accuracy and mutual information with labels', 'evaluate a game by shuffling receiver inputs across examples and measuring the resulting accuracy', 'run the CallbackEvaluator callback to log intervention and validation metrics at the end of each training epoch', 'create an AlwaysRelaxedWrapper instance wrapping an agent with a configurable temperature parameter', 'build a PyTorch module wrapper that applies relaxed one-hot categorical sampling to agent logits', 'test the AlwaysRelaxedWrapper forward pass in training mode using reparameterized relaxed sampling', 'test the AlwaysRelaxedWrapper forward pass in eval mode using softmax of temperature-scaled logits', 'review how RelaxedOneHotCategorical is used for differentiable discrete sampling in the wrapper']
```

Usage

```
{'compute_entropy_from_messages': 'compute the Shannon entropy in bits of a list of message tensors using frequency counting', 'calculate_mutual_information': 'calculate the mutual information between two lists of tensors by combining their individual and joint entropies', 'evaluate_intervention_message': 'evaluate a game by shuffling messages across examples and measuring accuracy and mutual information with labels', 'evaluate_intervention_input': 'evaluate a game by shuffling receiver inputs across examples and measuring the resulting accuracy', 'run_callback_evaluator': 'run the CallbackEvaluator callback to log intervention and validation metrics at the end of each training epoch'}
```

## File: facebookresearch_egg/egg/zoo/language_bottleneck/relaxed_channel.py

Prompts

```
['compute the Shannon entropy in bits of a list of message tensors using frequency counting', 'calculate the mutual information between two lists of tensors by combining their individual and joint entropies', 'evaluate a game by shuffling messages across examples and measuring accuracy and mutual information with labels', 'evaluate a game by shuffling receiver inputs across examples and measuring the resulting accuracy', 'run the CallbackEvaluator callback to log intervention and validation metrics at the end of each training epoch', 'create an AlwaysRelaxedWrapper instance wrapping an agent with a configurable temperature parameter', 'build a PyTorch module wrapper that applies relaxed one-hot categorical sampling to agent logits', 'test the AlwaysRelaxedWrapper forward pass in training mode using reparameterized relaxed sampling', 'test the AlwaysRelaxedWrapper forward pass in eval mode using softmax of temperature-scaled logits', 'review how RelaxedOneHotCategorical is used for differentiable discrete sampling in the wrapper']
```

Usage

```
{'create_AlwaysRelaxedWrapper': 'create an AlwaysRelaxedWrapper instance wrapping an agent with a configurable temperature parameter', 'build_relaxed_channel_wrapper': 'build a PyTorch module wrapper that applies relaxed one-hot categorical sampling to agent logits', 'test_AlwaysRelaxedWrapper_training_mode': 'test the AlwaysRelaxedWrapper forward pass in training mode using reparameterized relaxed sampling', 'test_AlwaysRelaxedWrapper_eval_mode': 'test the AlwaysRelaxedWrapper forward pass in eval mode using softmax of temperature-scaled logits', 'review_RelaxedOneHotCategorical_usage': 'review how RelaxedOneHotCategorical is used for differentiable discrete sampling in the wrapper'}
```

