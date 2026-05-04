# Agent Python Tools

- repo: google-deepmind/alphastar
- repo_uri: https://github.com/google-deepmind/alphastar

## File: google-deepmind_alphastar/alphastar/unplugged/losses/loss_base.py

Prompts

```
['create a subclass of Loss that implements input_spec and _loss for a custom AlphaStar loss function', 'compute the loss on unbatched unrolled inputs using the loss method with a StreamDict', 'compute the loss on batched inputs using batched_loss which applies vmap over the batch dimension', 'review the Loss class input validation logic that checks tree shape prefix and log structure', 'implement a LossBuilder callable that takes an ActionSpec and returns a configured Loss instance', 'create a Supervised loss instance with action spec, weights, burnin length, and overlap length', 'compute the cross-entropy loss for a single action argument using logits, action, mask, and weight', 'get the input specification dict describing expected shapes for logits, actions, and masks', 'compute the total supervised loss across all action arguments with per-argument logging metrics', 'review the Supervised class behavior cloning loss implementation with masking and unit tag support', 'test the supervised loss computation with random actions, logits, and masks over an unroll sequence', 'create a supervised.Supervised loss instance with action_spec, weights, overlap_len, burnin_len, and name parameters', 'build an action_spec dictionary with BoundedArray specs for function, delay, queued, repeat, unit_tags, target_unit_tag, and world', 'run the supervised loss forward pass by calling loss() on a StreamDict containing action, logits, masks, argument_masks, and step_type', 'verify per-step cross-entropy matches expected weighted masked cross-entropy computed via log_softmax and take_along_axis', 'build a python module that computes global loss masks for RL trajectory steps using get_global_loss_masks', 'create a function that returns masked data and counts for logging using get_masked_log', 'test the get_global_loss_masks function with step_type arrays and argument masks to verify burn-in and bootstrapping logic', 'test the get_masked_log function with sample data and mask arrays to verify masked aggregation output', 'refactor get_global_loss_masks to support additional step filtering conditions beyond terminal states and trajectory boundaries']
```

Usage

```
{'create_custom_loss_subclass': 'create a subclass of Loss that implements input_spec and _loss for a custom AlphaStar loss function', 'compute_unbatched_loss': 'compute the loss on unbatched unrolled inputs using the loss method with a StreamDict', 'compute_batched_loss': 'compute the loss on batched inputs using batched_loss which applies vmap over the batch dimension', 'review_loss_input_validation': 'review the Loss class input validation logic that checks tree shape prefix and log structure', 'implement_loss_builder': 'implement a LossBuilder callable that takes an ActionSpec and returns a configured Loss instance'}
```

## File: google-deepmind_alphastar/alphastar/unplugged/losses/supervised.py

Prompts

```
['create a subclass of Loss that implements input_spec and _loss for a custom AlphaStar loss function', 'compute the loss on unbatched unrolled inputs using the loss method with a StreamDict', 'compute the loss on batched inputs using batched_loss which applies vmap over the batch dimension', 'review the Loss class input validation logic that checks tree shape prefix and log structure', 'implement a LossBuilder callable that takes an ActionSpec and returns a configured Loss instance', 'create a Supervised loss instance with action spec, weights, burnin length, and overlap length', 'compute the cross-entropy loss for a single action argument using logits, action, mask, and weight', 'get the input specification dict describing expected shapes for logits, actions, and masks', 'compute the total supervised loss across all action arguments with per-argument logging metrics', 'review the Supervised class behavior cloning loss implementation with masking and unit tag support', 'test the supervised loss computation with random actions, logits, and masks over an unroll sequence', 'create a supervised.Supervised loss instance with action_spec, weights, overlap_len, burnin_len, and name parameters', 'build an action_spec dictionary with BoundedArray specs for function, delay, queued, repeat, unit_tags, target_unit_tag, and world', 'run the supervised loss forward pass by calling loss() on a StreamDict containing action, logits, masks, argument_masks, and step_type', 'verify per-step cross-entropy matches expected weighted masked cross-entropy computed via log_softmax and take_along_axis', 'build a python module that computes global loss masks for RL trajectory steps using get_global_loss_masks', 'create a function that returns masked data and counts for logging using get_masked_log', 'test the get_global_loss_masks function with step_type arrays and argument masks to verify burn-in and bootstrapping logic', 'test the get_masked_log function with sample data and mask arrays to verify masked aggregation output', 'refactor get_global_loss_masks to support additional step filtering conditions beyond terminal states and trajectory boundaries']
```

Usage

```
{'create_supervised_loss': 'create a Supervised loss instance with action spec, weights, burnin length, and overlap length', 'compute_single_arg_loss': 'compute the cross-entropy loss for a single action argument using logits, action, mask, and weight', 'get_input_spec': 'get the input specification dict describing expected shapes for logits, actions, and masks', 'compute_supervised_loss': 'compute the total supervised loss across all action arguments with per-argument logging metrics', 'review_supervised_class': 'review the Supervised class behavior cloning loss implementation with masking and unit tag support'}
```

## File: google-deepmind_alphastar/alphastar/unplugged/losses/supervised_test.py

Prompts

```
['create a subclass of Loss that implements input_spec and _loss for a custom AlphaStar loss function', 'compute the loss on unbatched unrolled inputs using the loss method with a StreamDict', 'compute the loss on batched inputs using batched_loss which applies vmap over the batch dimension', 'review the Loss class input validation logic that checks tree shape prefix and log structure', 'implement a LossBuilder callable that takes an ActionSpec and returns a configured Loss instance', 'create a Supervised loss instance with action spec, weights, burnin length, and overlap length', 'compute the cross-entropy loss for a single action argument using logits, action, mask, and weight', 'get the input specification dict describing expected shapes for logits, actions, and masks', 'compute the total supervised loss across all action arguments with per-argument logging metrics', 'review the Supervised class behavior cloning loss implementation with masking and unit tag support', 'test the supervised loss computation with random actions, logits, and masks over an unroll sequence', 'create a supervised.Supervised loss instance with action_spec, weights, overlap_len, burnin_len, and name parameters', 'build an action_spec dictionary with BoundedArray specs for function, delay, queued, repeat, unit_tags, target_unit_tag, and world', 'run the supervised loss forward pass by calling loss() on a StreamDict containing action, logits, masks, argument_masks, and step_type', 'verify per-step cross-entropy matches expected weighted masked cross-entropy computed via log_softmax and take_along_axis', 'build a python module that computes global loss masks for RL trajectory steps using get_global_loss_masks', 'create a function that returns masked data and counts for logging using get_masked_log', 'test the get_global_loss_masks function with step_type arrays and argument masks to verify burn-in and bootstrapping logic', 'test the get_masked_log function with sample data and mask arrays to verify masked aggregation output', 'refactor get_global_loss_masks to support additional step filtering conditions beyond terminal states and trajectory boundaries']
```

Usage

```
{'test_supervised_loss': 'test the supervised loss computation with random actions, logits, and masks over an unroll sequence', 'create_supervised_loss_instance': 'create a supervised.Supervised loss instance with action_spec, weights, overlap_len, burnin_len, and name parameters', 'build_action_spec': 'build an action_spec dictionary with BoundedArray specs for function, delay, queued, repeat, unit_tags, target_unit_tag, and world', 'run_supervised_loss_forward': 'run the supervised loss forward pass by calling loss() on a StreamDict containing action, logits, masks, argument_masks, and step_type', 'verify_cross_entropy_computation': 'verify per-step cross-entropy matches expected weighted masked cross-entropy computed via log_softmax and take_along_axis'}
```

## File: google-deepmind_alphastar/alphastar/unplugged/losses/util.py

Prompts

```
['create a subclass of Loss that implements input_spec and _loss for a custom AlphaStar loss function', 'compute the loss on unbatched unrolled inputs using the loss method with a StreamDict', 'compute the loss on batched inputs using batched_loss which applies vmap over the batch dimension', 'review the Loss class input validation logic that checks tree shape prefix and log structure', 'implement a LossBuilder callable that takes an ActionSpec and returns a configured Loss instance', 'create a Supervised loss instance with action spec, weights, burnin length, and overlap length', 'compute the cross-entropy loss for a single action argument using logits, action, mask, and weight', 'get the input specification dict describing expected shapes for logits, actions, and masks', 'compute the total supervised loss across all action arguments with per-argument logging metrics', 'review the Supervised class behavior cloning loss implementation with masking and unit tag support', 'test the supervised loss computation with random actions, logits, and masks over an unroll sequence', 'create a supervised.Supervised loss instance with action_spec, weights, overlap_len, burnin_len, and name parameters', 'build an action_spec dictionary with BoundedArray specs for function, delay, queued, repeat, unit_tags, target_unit_tag, and world', 'run the supervised loss forward pass by calling loss() on a StreamDict containing action, logits, masks, argument_masks, and step_type', 'verify per-step cross-entropy matches expected weighted masked cross-entropy computed via log_softmax and take_along_axis', 'build a python module that computes global loss masks for RL trajectory steps using get_global_loss_masks', 'create a function that returns masked data and counts for logging using get_masked_log', 'test the get_global_loss_masks function with step_type arrays and argument masks to verify burn-in and bootstrapping logic', 'test the get_masked_log function with sample data and mask arrays to verify masked aggregation output', 'refactor get_global_loss_masks to support additional step filtering conditions beyond terminal states and trajectory boundaries']
```

Usage

```
{'build_loss_mask_for_trajectory': 'build a python module that computes global loss masks for RL trajectory steps using get_global_loss_masks', 'create_masked_log_dict': 'create a function that returns masked data and counts for logging using get_masked_log', 'test_get_global_loss_masks': 'test the get_global_loss_masks function with step_type arrays and argument masks to verify burn-in and bootstrapping logic', 'test_get_masked_log': 'test the get_masked_log function with sample data and mask arrays to verify masked aggregation output', 'refactor_get_global_loss_masks': 'refactor get_global_loss_masks to support additional step filtering conditions beyond terminal states and trajectory boundaries'}
```

