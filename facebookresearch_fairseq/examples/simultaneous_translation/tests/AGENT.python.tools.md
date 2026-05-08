# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/simultaneous_translation/tests/test_alignment_train.py

Prompts

```
['run the hypothesis-based test that validates alignment training on CPU and CUDA devices', 'test the alignment training custom operator produces matching results on CUDA versus CPU', 'review the reference alignment training implementation using exclusive cumprod and cumulative sum', 'test the custom alignment training CUDA and CPU binding operators against the reference', 'summarize the AlignmentTrainTest class that property-based tests alignment training with random tensor shapes', 'build a transformer model with monotonic attention for simultaneous translation using specified simul_type config', 'generate a config dictionary by merging overrides into the default monotonic attention config values', 'create a test sample dictionary with padded source and target token tensors for model input', 'compute the expected monotonic alignment alpha values from p_choose probabilities following the BAT formula', 'apply mass preservation to ensure alignment values sum to one across the source dimension']
```

Usage

```
{'run_alignment_train_test': 'run the hypothesis-based test that validates alignment training on CPU and CUDA devices', 'test_alignment_train_cuda_vs_cpu': 'test the alignment training custom operator produces matching results on CUDA versus CPU', 'review_alignment_train_ref_implementation': 'review the reference alignment training implementation using exclusive cumprod and cumulative sum', 'test_alignment_train_custom_operator': 'test the custom alignment training CUDA and CPU binding operators against the reference', 'summarize_alignment_train_test_class': 'summarize the AlignmentTrainTest class that property-based tests alignment training with random tensor shapes'}
```

## File: facebookresearch_fairseq/examples/simultaneous_translation/tests/test_text_models.py

Prompts

```
['run the hypothesis-based test that validates alignment training on CPU and CUDA devices', 'test the alignment training custom operator produces matching results on CUDA versus CPU', 'review the reference alignment training implementation using exclusive cumprod and cumulative sum', 'test the custom alignment training CUDA and CPU binding operators against the reference', 'summarize the AlignmentTrainTest class that property-based tests alignment training with random tensor shapes', 'build a transformer model with monotonic attention for simultaneous translation using specified simul_type config', 'generate a config dictionary by merging overrides into the default monotonic attention config values', 'create a test sample dictionary with padded source and target token tensors for model input', 'compute the expected monotonic alignment alpha values from p_choose probabilities following the BAT formula', 'apply mass preservation to ensure alignment values sum to one across the source dimension']
```

Usage

```
{'build_transformer_monotonic_attention': 'build a transformer model with monotonic attention for simultaneous translation using specified simul_type config', 'generate_config': 'generate a config dictionary by merging overrides into the default monotonic attention config values', 'make_sample_with_padding': 'create a test sample dictionary with padded source and target token tensors for model input', 'expected_alignment_formula': 'compute the expected monotonic alignment alpha values from p_choose probabilities following the BAT formula', 'mass_perservation_formula': 'apply mass preservation to ensure alignment values sum to one across the source dimension'}
```

