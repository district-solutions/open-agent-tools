# Agent Python Tools

- repo: google-deepmind/alphastar
- repo_uri: https://github.com/google-deepmind/alphastar

## File: google-deepmind_alphastar/alphastar/architectures/dummy/dummy.py

Prompts

```
['build an alphastar dummy architecture component using get_alphastar_dummy with input_spec and action_spec', 'create a vector head component for a scalar argument using _get_vector_head with action_spec and sample_fn', 'create a unit tags head component using _get_unit_tags_head for multi-unit selection arguments', 'review the get_alphastar_dummy function to understand how it assembles encoders and heads into a SequentialComponent', 'summarize how _get_vector_head produces logits and actions for training versus inference modes', 'test the DummyTest class test_forward method to verify the dummy architecture forward pass produces correct output shapes', 'run the DummyTest parameterized test case with absltest to validate both training and inference modes', 'test the dummy get_alphastar_dummy function by constructing input specs and verifying output shapes match expectations', 'test the alphastar initial_state method using haiku transform and vmap to verify batched state initialization', 'test the alphastar unroll method using haiku transform and vmap to verify forward pass outputs and next state shapes']
```

Usage

```
{'build_alphastar_dummy_architecture': 'build an alphastar dummy architecture component using get_alphastar_dummy with input_spec and action_spec', 'create_vector_head_component': 'create a vector head component for a scalar argument using _get_vector_head with action_spec and sample_fn', 'create_unit_tags_head': 'create a unit tags head component using _get_unit_tags_head for multi-unit selection arguments', 'review_get_alphastar_dummy': 'review the get_alphastar_dummy function to understand how it assembles encoders and heads into a SequentialComponent', 'summarize_vector_head_logic': 'summarize how _get_vector_head produces logits and actions for training versus inference modes'}
```

## File: google-deepmind_alphastar/alphastar/architectures/dummy/dummy_test.py

Prompts

```
['build an alphastar dummy architecture component using get_alphastar_dummy with input_spec and action_spec', 'create a vector head component for a scalar argument using _get_vector_head with action_spec and sample_fn', 'create a unit tags head component using _get_unit_tags_head for multi-unit selection arguments', 'review the get_alphastar_dummy function to understand how it assembles encoders and heads into a SequentialComponent', 'summarize how _get_vector_head produces logits and actions for training versus inference modes', 'test the DummyTest class test_forward method to verify the dummy architecture forward pass produces correct output shapes', 'run the DummyTest parameterized test case with absltest to validate both training and inference modes', 'test the dummy get_alphastar_dummy function by constructing input specs and verifying output shapes match expectations', 'test the alphastar initial_state method using haiku transform and vmap to verify batched state initialization', 'test the alphastar unroll method using haiku transform and vmap to verify forward pass outputs and next state shapes']
```

Usage

```
{'test_DummyTest_test_forward': 'test the DummyTest class test_forward method to verify the dummy architecture forward pass produces correct output shapes', 'run_DummyTest': 'run the DummyTest parameterized test case with absltest to validate both training and inference modes', 'test_get_alphastar_dummy': 'test the dummy get_alphastar_dummy function by constructing input specs and verifying output shapes match expectations', 'test_initial_state': 'test the alphastar initial_state method using haiku transform and vmap to verify batched state initialization', 'test_unroll': 'test the alphastar unroll method using haiku transform and vmap to verify forward pass outputs and next state shapes'}
```

