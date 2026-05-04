# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/simultaneous_translation/utils/data_utils.py

Prompts

```
['calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the data utilities module for mean-variance normalization and padding mask conversion functions', 'create a function that computes exclusive cumulative product of a PyTorch tensor along a given dimension', 'build a numerically stable cumulative product using log-exp trick to prevent precision issues', 'test the lengths_to_mask function to convert a tensor of sequence lengths into a boolean attention mask', 'refactor the moving_sum function to compute windowed sums over a 2D tensor using 1D convolution', 'summarize the utility functions module providing exclusive cumprod, safe cumprod, length masking, and moving sum operations', 'calculate the average proportion latency metric for simultaneous translation delays using AverageProportion', 'calculate the average lagging latency metric for simultaneous translation using AverageLagging class', 'calculate the differentiable average lagging metric for simultaneous machine translation using DifferentiableAverageLagging', 'compute the variance of delays across attention heads and layers using VarianceDelay', 'compute the combined average and variance latency loss from attention weights using LatencyTraining', 'build a wait-k policy matrix for simultaneous translation with a fixed lagging offset', 'create step-wise read-write probabilities from attention energy using sigmoid activation', 'test the waitk function to generate a diagonal p_choose matrix for a given lagging value', 'review the hard_aligned function and its noise injection strategy for training discreteness', 'summarize the p_choose strategy module and its wait-k and hard-aligned policy functions']
```

Usage

```
{'calc_mean_invstddev': 'calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply_mv_norm': 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'lengths_to_encoder_padding_mask': 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'encoder_padding_mask_to_lengths': 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review_data_utils': 'review the data utilities module for mean-variance normalization and padding mask conversion functions'}
```

## File: facebookresearch_avhubert/fairseq/examples/simultaneous_translation/utils/functions.py

Prompts

```
['calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the data utilities module for mean-variance normalization and padding mask conversion functions', 'create a function that computes exclusive cumulative product of a PyTorch tensor along a given dimension', 'build a numerically stable cumulative product using log-exp trick to prevent precision issues', 'test the lengths_to_mask function to convert a tensor of sequence lengths into a boolean attention mask', 'refactor the moving_sum function to compute windowed sums over a 2D tensor using 1D convolution', 'summarize the utility functions module providing exclusive cumprod, safe cumprod, length masking, and moving sum operations', 'calculate the average proportion latency metric for simultaneous translation delays using AverageProportion', 'calculate the average lagging latency metric for simultaneous translation using AverageLagging class', 'calculate the differentiable average lagging metric for simultaneous machine translation using DifferentiableAverageLagging', 'compute the variance of delays across attention heads and layers using VarianceDelay', 'compute the combined average and variance latency loss from attention weights using LatencyTraining', 'build a wait-k policy matrix for simultaneous translation with a fixed lagging offset', 'create step-wise read-write probabilities from attention energy using sigmoid activation', 'test the waitk function to generate a diagonal p_choose matrix for a given lagging value', 'review the hard_aligned function and its noise injection strategy for training discreteness', 'summarize the p_choose strategy module and its wait-k and hard-aligned policy functions']
```

Usage

```
{'create_exclusive_cumprod': 'create a function that computes exclusive cumulative product of a PyTorch tensor along a given dimension', 'build_safe_cumprod': 'build a numerically stable cumulative product using log-exp trick to prevent precision issues', 'test_lengths_to_mask': 'test the lengths_to_mask function to convert a tensor of sequence lengths into a boolean attention mask', 'refactor_moving_sum': 'refactor the moving_sum function to compute windowed sums over a 2D tensor using 1D convolution', 'summarize_functions_module': 'summarize the utility functions module providing exclusive cumprod, safe cumprod, length masking, and moving sum operations'}
```

## File: facebookresearch_avhubert/fairseq/examples/simultaneous_translation/utils/latency.py

Prompts

```
['calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the data utilities module for mean-variance normalization and padding mask conversion functions', 'create a function that computes exclusive cumulative product of a PyTorch tensor along a given dimension', 'build a numerically stable cumulative product using log-exp trick to prevent precision issues', 'test the lengths_to_mask function to convert a tensor of sequence lengths into a boolean attention mask', 'refactor the moving_sum function to compute windowed sums over a 2D tensor using 1D convolution', 'summarize the utility functions module providing exclusive cumprod, safe cumprod, length masking, and moving sum operations', 'calculate the average proportion latency metric for simultaneous translation delays using AverageProportion', 'calculate the average lagging latency metric for simultaneous translation using AverageLagging class', 'calculate the differentiable average lagging metric for simultaneous machine translation using DifferentiableAverageLagging', 'compute the variance of delays across attention heads and layers using VarianceDelay', 'compute the combined average and variance latency loss from attention weights using LatencyTraining', 'build a wait-k policy matrix for simultaneous translation with a fixed lagging offset', 'create step-wise read-write probabilities from attention energy using sigmoid activation', 'test the waitk function to generate a diagonal p_choose matrix for a given lagging value', 'review the hard_aligned function and its noise injection strategy for training discreteness', 'summarize the p_choose strategy module and its wait-k and hard-aligned policy functions']
```

Usage

```
{'calculate_average_proportion_latency': 'calculate the average proportion latency metric for simultaneous translation delays using AverageProportion', 'calculate_average_lagging_latency': 'calculate the average lagging latency metric for simultaneous translation using AverageLagging class', 'calculate_differentiable_average_lagging': 'calculate the differentiable average lagging metric for simultaneous machine translation using DifferentiableAverageLagging', 'compute_variance_delay': 'compute the variance of delays across attention heads and layers using VarianceDelay', 'compute_latency_training_loss': 'compute the combined average and variance latency loss from attention weights using LatencyTraining'}
```

## File: facebookresearch_avhubert/fairseq/examples/simultaneous_translation/utils/p_choose_strategy.py

Prompts

```
['calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the data utilities module for mean-variance normalization and padding mask conversion functions', 'create a function that computes exclusive cumulative product of a PyTorch tensor along a given dimension', 'build a numerically stable cumulative product using log-exp trick to prevent precision issues', 'test the lengths_to_mask function to convert a tensor of sequence lengths into a boolean attention mask', 'refactor the moving_sum function to compute windowed sums over a 2D tensor using 1D convolution', 'summarize the utility functions module providing exclusive cumprod, safe cumprod, length masking, and moving sum operations', 'calculate the average proportion latency metric for simultaneous translation delays using AverageProportion', 'calculate the average lagging latency metric for simultaneous translation using AverageLagging class', 'calculate the differentiable average lagging metric for simultaneous machine translation using DifferentiableAverageLagging', 'compute the variance of delays across attention heads and layers using VarianceDelay', 'compute the combined average and variance latency loss from attention weights using LatencyTraining', 'build a wait-k policy matrix for simultaneous translation with a fixed lagging offset', 'create step-wise read-write probabilities from attention energy using sigmoid activation', 'test the waitk function to generate a diagonal p_choose matrix for a given lagging value', 'review the hard_aligned function and its noise injection strategy for training discreteness', 'summarize the p_choose strategy module and its wait-k and hard-aligned policy functions']
```

Usage

```
{'build_waitk_policy': 'build a wait-k policy matrix for simultaneous translation with a fixed lagging offset', 'create_hard_aligned_probs': 'create step-wise read-write probabilities from attention energy using sigmoid activation', 'test_waitk_function': 'test the waitk function to generate a diagonal p_choose matrix for a given lagging value', 'review_hard_aligned_noise': 'review the hard_aligned function and its noise injection strategy for training discreteness', 'summarize_p_choose_strategy': 'summarize the p_choose strategy module and its wait-k and hard-aligned policy functions'}
```

