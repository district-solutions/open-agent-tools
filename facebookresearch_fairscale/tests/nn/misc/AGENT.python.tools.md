# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/tests/nn/misc/test_flatten_params_wrapper.py

Prompts

```
['test the FlattenParamsWrapper on a basic linear module to verify parameter flattening preserves output', 'test partial flattening of selected transformer layer parameters while leaving others non-flattened', 'test FlattenParamsWrapper with two separate flatten groups on a transformer module', 'test that the unflattened state dict of a wrapped module matches the original module state dict', 'test the unflatten_params context manager to temporarily restore original parameter shapes from flat params', 'test that GradBucket.add_grad preserves original parameter gradient values after bucketing', 'test that GradBucket.shrink releases excess buffer storage to prevent memory leaks', 'test that GradBucket.add_grad raises AssertionError when param exceeds bucket max size', 'test that GradBucket.collapse zeroes the buffer and rebuild restores gradient references', 'review the GradBucket class from fairscale.nn.misc for gradient bucketing and memory management', 'test that ParamBucket conserves parameter values after adding a tensor to the bucket', 'test that ParamBucket raises AssertionError when adding a param exceeding the bucket max size', 'test that ParamBucket raises AssertionError when the same param is added twice to the bucket', 'test that ParamBucket correctly converts its buffer dtype between float16 and float32', 'test the ParamBucket add_param method to check in a torch tensor as a view of the bucket buffer']
```

Usage

```
{'test_flatten_params_wrapper_basic': 'test the FlattenParamsWrapper on a basic linear module to verify parameter flattening preserves output', 'test_flatten_params_wrapper_partial': 'test partial flattening of selected transformer layer parameters while leaving others non-flattened', 'test_flatten_params_wrapper_multi_group': 'test FlattenParamsWrapper with two separate flatten groups on a transformer module', 'test_flatten_params_wrapper_state_dict': 'test that the unflattened state dict of a wrapped module matches the original module state dict', 'test_flatten_params_wrapper_unflatten_context': 'test the unflatten_params context manager to temporarily restore original parameter shapes from flat params'}
```

## File: facebookresearch_fairscale/tests/nn/misc/test_grad_bucket.py

Prompts

```
['test the FlattenParamsWrapper on a basic linear module to verify parameter flattening preserves output', 'test partial flattening of selected transformer layer parameters while leaving others non-flattened', 'test FlattenParamsWrapper with two separate flatten groups on a transformer module', 'test that the unflattened state dict of a wrapped module matches the original module state dict', 'test the unflatten_params context manager to temporarily restore original parameter shapes from flat params', 'test that GradBucket.add_grad preserves original parameter gradient values after bucketing', 'test that GradBucket.shrink releases excess buffer storage to prevent memory leaks', 'test that GradBucket.add_grad raises AssertionError when param exceeds bucket max size', 'test that GradBucket.collapse zeroes the buffer and rebuild restores gradient references', 'review the GradBucket class from fairscale.nn.misc for gradient bucketing and memory management', 'test that ParamBucket conserves parameter values after adding a tensor to the bucket', 'test that ParamBucket raises AssertionError when adding a param exceeding the bucket max size', 'test that ParamBucket raises AssertionError when the same param is added twice to the bucket', 'test that ParamBucket correctly converts its buffer dtype between float16 and float32', 'test the ParamBucket add_param method to check in a torch tensor as a view of the bucket buffer']
```

Usage

```
{'test_grad_bucket_grad_values_conserved': 'test that GradBucket.add_grad preserves original parameter gradient values after bucketing', 'test_grad_bucket_memory_leak': 'test that GradBucket.shrink releases excess buffer storage to prevent memory leaks', 'test_grad_bucket_max_size': 'test that GradBucket.add_grad raises AssertionError when param exceeds bucket max size', 'test_grad_bucket_collapse_and_rebuild': 'test that GradBucket.collapse zeroes the buffer and rebuild restores gradient references', 'review_grad_bucket_class': 'review the GradBucket class from fairscale.nn.misc for gradient bucketing and memory management'}
```

## File: facebookresearch_fairscale/tests/nn/misc/test_param_bucket.py

Prompts

```
['test the FlattenParamsWrapper on a basic linear module to verify parameter flattening preserves output', 'test partial flattening of selected transformer layer parameters while leaving others non-flattened', 'test FlattenParamsWrapper with two separate flatten groups on a transformer module', 'test that the unflattened state dict of a wrapped module matches the original module state dict', 'test the unflatten_params context manager to temporarily restore original parameter shapes from flat params', 'test that GradBucket.add_grad preserves original parameter gradient values after bucketing', 'test that GradBucket.shrink releases excess buffer storage to prevent memory leaks', 'test that GradBucket.add_grad raises AssertionError when param exceeds bucket max size', 'test that GradBucket.collapse zeroes the buffer and rebuild restores gradient references', 'review the GradBucket class from fairscale.nn.misc for gradient bucketing and memory management', 'test that ParamBucket conserves parameter values after adding a tensor to the bucket', 'test that ParamBucket raises AssertionError when adding a param exceeding the bucket max size', 'test that ParamBucket raises AssertionError when the same param is added twice to the bucket', 'test that ParamBucket correctly converts its buffer dtype between float16 and float32', 'test the ParamBucket add_param method to check in a torch tensor as a view of the bucket buffer']
```

Usage

```
{'test_ParamBucket_param_values_conserved': 'test that ParamBucket conserves parameter values after adding a tensor to the bucket', 'test_ParamBucket_max_size': 'test that ParamBucket raises AssertionError when adding a param exceeding the bucket max size', 'test_ParamBucket_double_check_in': 'test that ParamBucket raises AssertionError when the same param is added twice to the bucket', 'test_ParamBucket_type_change': 'test that ParamBucket correctly converts its buffer dtype between float16 and float32', 'test_ParamBucket_add_param': 'test the ParamBucket add_param method to check in a torch tensor as a view of the bucket buffer'}
```

