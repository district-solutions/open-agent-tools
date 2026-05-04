# Agent Python Tools

- repo: google-deepmind/ai-foundations
- repo_uri: https://github.com/google-deepmind/ai-foundations

## File: google-deepmind_ai-foundations/ai_foundations/feedback/course_4/counting_parameters/reference_implementations.py

Prompts

```
['compute the total trainable parameters for an entire transformer model given hyperparameters', 'compute the trainable parameters for a single transformer block including attention and MLP', 'compute the trainable parameters for a multi-head attention sublayer with QKV projections', 'compute the trainable parameters for an MLP sublayer with two dense projections', 'compute the trainable parameters for a token embedding matrix given vocabulary size', 'test a learner solution against correct answers with near-miss error messages and optional hints', 'display an HTML error message with details when a learner solution does not match the correct answer', 'show the reference implementation as a hint when the learner requests to see the solution', 'detect if a learner has hard-coded the number of parameters instead of computing from hyperparams', 'handle undefined variable errors by suggesting the learner execute the previous notebook cell', 'test a learner implementation of the multi-head attention parameter count function', 'test a learner implementation of the embedding layer parameter count function', 'test a learner implementation of the layer normalization parameter count function', 'test a learner implementation of the MLP component parameter count function', 'test a learner implementation of the full transformer model parameter count function']
```

Usage

```
{'count_transformer_parameters': 'compute the total trainable parameters for an entire transformer model given hyperparameters', 'count_transformer_block_parameters': 'compute the trainable parameters for a single transformer block including attention and MLP', 'count_attention_parameters': 'compute the trainable parameters for a multi-head attention sublayer with QKV projections', 'count_mlp_parameters': 'compute the trainable parameters for an MLP sublayer with two dense projections', 'count_embedding_parameters': 'compute the trainable parameters for a token embedding matrix given vocabulary size'}
```

## File: google-deepmind_ai-foundations/ai_foundations/feedback/course_4/counting_parameters/test_framework.py

Prompts

```
['compute the total trainable parameters for an entire transformer model given hyperparameters', 'compute the trainable parameters for a single transformer block including attention and MLP', 'compute the trainable parameters for a multi-head attention sublayer with QKV projections', 'compute the trainable parameters for an MLP sublayer with two dense projections', 'compute the trainable parameters for a token embedding matrix given vocabulary size', 'test a learner solution against correct answers with near-miss error messages and optional hints', 'display an HTML error message with details when a learner solution does not match the correct answer', 'show the reference implementation as a hint when the learner requests to see the solution', 'detect if a learner has hard-coded the number of parameters instead of computing from hyperparams', 'handle undefined variable errors by suggesting the learner execute the previous notebook cell', 'test a learner implementation of the multi-head attention parameter count function', 'test a learner implementation of the embedding layer parameter count function', 'test a learner implementation of the layer normalization parameter count function', 'test a learner implementation of the MLP component parameter count function', 'test a learner implementation of the full transformer model parameter count function']
```

Usage

```
{'test_framework_validate_learner_solution': 'test a learner solution against correct answers with near-miss error messages and optional hints', 'test_framework_display_error_feedback': 'display an HTML error message with details when a learner solution does not match the correct answer', 'test_framework_show_reference_solution': 'show the reference implementation as a hint when the learner requests to see the solution', 'test_framework_check_hardcoded_values': 'detect if a learner has hard-coded the number of parameters instead of computing from hyperparams', 'test_framework_handle_undefined_variable_errors': 'handle undefined variable errors by suggesting the learner execute the previous notebook cell'}
```

## File: google-deepmind_ai-foundations/ai_foundations/feedback/course_4/counting_parameters/test_parameter_counts.py

Prompts

```
['compute the total trainable parameters for an entire transformer model given hyperparameters', 'compute the trainable parameters for a single transformer block including attention and MLP', 'compute the trainable parameters for a multi-head attention sublayer with QKV projections', 'compute the trainable parameters for an MLP sublayer with two dense projections', 'compute the trainable parameters for a token embedding matrix given vocabulary size', 'test a learner solution against correct answers with near-miss error messages and optional hints', 'display an HTML error message with details when a learner solution does not match the correct answer', 'show the reference implementation as a hint when the learner requests to see the solution', 'detect if a learner has hard-coded the number of parameters instead of computing from hyperparams', 'handle undefined variable errors by suggesting the learner execute the previous notebook cell', 'test a learner implementation of the multi-head attention parameter count function', 'test a learner implementation of the embedding layer parameter count function', 'test a learner implementation of the layer normalization parameter count function', 'test a learner implementation of the MLP component parameter count function', 'test a learner implementation of the full transformer model parameter count function']
```

Usage

```
{'test_parameter_count_attention': 'test a learner implementation of the multi-head attention parameter count function', 'test_parameter_count_embedding': 'test a learner implementation of the embedding layer parameter count function', 'test_parameter_count_layer_norm': 'test a learner implementation of the layer normalization parameter count function', 'test_parameter_count_mlp': 'test a learner implementation of the MLP component parameter count function', 'test_parameter_count_transformer': 'test a learner implementation of the full transformer model parameter count function'}
```

