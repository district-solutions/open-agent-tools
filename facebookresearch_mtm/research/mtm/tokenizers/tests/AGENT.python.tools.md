# Agent Python Tools

- repo: facebookresearch/mtm
- repo_uri: https://github.com/facebookresearch/mtm

## File: facebookresearch_mtm/research/mtm/tokenizers/tests/test_continuous_binned.py

Prompts

```
['test the ContinuousBinnedTokenizer encode and decode round-trip with a simple binning boundary list', 'test the ContinuousBinnedTokenizer encode and decode round-trip with extended binning boundaries including negative values', 'test the ContinuousBinnedTokenizer decode method with scaled token logits multiplied by a factor', 'review the ContinuousBinnedTokenizer class encode and decode methods for trajectory tokenization using nearest-value binning', 'summarize the test suite for ContinuousBinnedTokenizer covering simple binning, extended boundaries, and logit-based decoding', 'test the DiscreteIdentity tokenizer by encoding and decoding torch tensors with one-hot tokens', 'run the test_di_simple function to verify DiscreteIdentity encode and decode roundtrip accuracy', 'test the DiscreteIdentity tokenizer decode method with noisy one-hot token tensors', 'review the test_di_simple function that validates DiscreteIdentity reconstruction with noisy inputs', 'summarize the test_di_simple function that tests DiscreteIdentity encode decode roundtrip', 'test the PatchifyTokenizer encode and decode round-trip on random image data', 'run extract_patches to reshape a tensor into non-overlapping spatial patches of a given size', 'run merge_patches to reconstruct a spatial tensor from flattened patch sequences', 'create a PatchifyTokenizer instance with a specified patch size for encoding image trajectories', 'test that encoding then decoding with PatchifyTokenizer produces the original tensor values', 'test UniformBinningTokenizer encode and decode with small random uniform data and 2 bins', 'test UniformBinningTokenizer encode and decode with 10000 samples and 10 bins for reconstruction accuracy', 'test UniformBinningTokenizer with random normal data and data-derived min max bounds', 'test UniformBinningTokenizer encode and decode with 1024x8x5 tensor and 11 bins for large data', 'review UniformBinningTokenizer class encode and decode methods for uniform binning tokenization of trajectory data']
```

Usage

```
{'test_continuous_binned_simple': 'test the ContinuousBinnedTokenizer encode and decode round-trip with a simple binning boundary list', 'test_continuous_binned_with_others': 'test the ContinuousBinnedTokenizer encode and decode round-trip with extended binning boundaries including negative values', 'test_continuous_binned_logits': 'test the ContinuousBinnedTokenizer decode method with scaled token logits multiplied by a factor', 'review_continuous_binned_tokenizer': 'review the ContinuousBinnedTokenizer class encode and decode methods for trajectory tokenization using nearest-value binning', 'summarize_continuous_binned_tests': 'summarize the test suite for ContinuousBinnedTokenizer covering simple binning, extended boundaries, and logit-based decoding'}
```

## File: facebookresearch_mtm/research/mtm/tokenizers/tests/test_discrete_identity.py

Prompts

```
['test the ContinuousBinnedTokenizer encode and decode round-trip with a simple binning boundary list', 'test the ContinuousBinnedTokenizer encode and decode round-trip with extended binning boundaries including negative values', 'test the ContinuousBinnedTokenizer decode method with scaled token logits multiplied by a factor', 'review the ContinuousBinnedTokenizer class encode and decode methods for trajectory tokenization using nearest-value binning', 'summarize the test suite for ContinuousBinnedTokenizer covering simple binning, extended boundaries, and logit-based decoding', 'test the DiscreteIdentity tokenizer by encoding and decoding torch tensors with one-hot tokens', 'run the test_di_simple function to verify DiscreteIdentity encode and decode roundtrip accuracy', 'test the DiscreteIdentity tokenizer decode method with noisy one-hot token tensors', 'review the test_di_simple function that validates DiscreteIdentity reconstruction with noisy inputs', 'summarize the test_di_simple function that tests DiscreteIdentity encode decode roundtrip', 'test the PatchifyTokenizer encode and decode round-trip on random image data', 'run extract_patches to reshape a tensor into non-overlapping spatial patches of a given size', 'run merge_patches to reconstruct a spatial tensor from flattened patch sequences', 'create a PatchifyTokenizer instance with a specified patch size for encoding image trajectories', 'test that encoding then decoding with PatchifyTokenizer produces the original tensor values', 'test UniformBinningTokenizer encode and decode with small random uniform data and 2 bins', 'test UniformBinningTokenizer encode and decode with 10000 samples and 10 bins for reconstruction accuracy', 'test UniformBinningTokenizer with random normal data and data-derived min max bounds', 'test UniformBinningTokenizer encode and decode with 1024x8x5 tensor and 11 bins for large data', 'review UniformBinningTokenizer class encode and decode methods for uniform binning tokenization of trajectory data']
```

Usage

```
{'test_discrete_identity_simple': 'test the DiscreteIdentity tokenizer by encoding and decoding torch tensors with one-hot tokens', 'run_test_di_simple': 'run the test_di_simple function to verify DiscreteIdentity encode and decode roundtrip accuracy', 'test_discrete_identity_noise': 'test the DiscreteIdentity tokenizer decode method with noisy one-hot token tensors', 'review_discrete_identity_test': 'review the test_di_simple function that validates DiscreteIdentity reconstruction with noisy inputs', 'summarize_test_di_simple': 'summarize the test_di_simple function that tests DiscreteIdentity encode decode roundtrip'}
```

## File: facebookresearch_mtm/research/mtm/tokenizers/tests/test_patchify.py

Prompts

```
['test the ContinuousBinnedTokenizer encode and decode round-trip with a simple binning boundary list', 'test the ContinuousBinnedTokenizer encode and decode round-trip with extended binning boundaries including negative values', 'test the ContinuousBinnedTokenizer decode method with scaled token logits multiplied by a factor', 'review the ContinuousBinnedTokenizer class encode and decode methods for trajectory tokenization using nearest-value binning', 'summarize the test suite for ContinuousBinnedTokenizer covering simple binning, extended boundaries, and logit-based decoding', 'test the DiscreteIdentity tokenizer by encoding and decoding torch tensors with one-hot tokens', 'run the test_di_simple function to verify DiscreteIdentity encode and decode roundtrip accuracy', 'test the DiscreteIdentity tokenizer decode method with noisy one-hot token tensors', 'review the test_di_simple function that validates DiscreteIdentity reconstruction with noisy inputs', 'summarize the test_di_simple function that tests DiscreteIdentity encode decode roundtrip', 'test the PatchifyTokenizer encode and decode round-trip on random image data', 'run extract_patches to reshape a tensor into non-overlapping spatial patches of a given size', 'run merge_patches to reconstruct a spatial tensor from flattened patch sequences', 'create a PatchifyTokenizer instance with a specified patch size for encoding image trajectories', 'test that encoding then decoding with PatchifyTokenizer produces the original tensor values', 'test UniformBinningTokenizer encode and decode with small random uniform data and 2 bins', 'test UniformBinningTokenizer encode and decode with 10000 samples and 10 bins for reconstruction accuracy', 'test UniformBinningTokenizer with random normal data and data-derived min max bounds', 'test UniformBinningTokenizer encode and decode with 1024x8x5 tensor and 11 bins for large data', 'review UniformBinningTokenizer class encode and decode methods for uniform binning tokenization of trajectory data']
```

Usage

```
{'test_patchify_simple': 'test the PatchifyTokenizer encode and decode round-trip on random image data', 'run_extract_patches': 'run extract_patches to reshape a tensor into non-overlapping spatial patches of a given size', 'run_merge_patches': 'run merge_patches to reconstruct a spatial tensor from flattened patch sequences', 'create_PatchifyTokenizer': 'create a PatchifyTokenizer instance with a specified patch size for encoding image trajectories', 'test_encode_decode_roundtrip': 'test that encoding then decoding with PatchifyTokenizer produces the original tensor values'}
```

## File: facebookresearch_mtm/research/mtm/tokenizers/tests/test_uniform_bins_new.py

Prompts

```
['test the ContinuousBinnedTokenizer encode and decode round-trip with a simple binning boundary list', 'test the ContinuousBinnedTokenizer encode and decode round-trip with extended binning boundaries including negative values', 'test the ContinuousBinnedTokenizer decode method with scaled token logits multiplied by a factor', 'review the ContinuousBinnedTokenizer class encode and decode methods for trajectory tokenization using nearest-value binning', 'summarize the test suite for ContinuousBinnedTokenizer covering simple binning, extended boundaries, and logit-based decoding', 'test the DiscreteIdentity tokenizer by encoding and decoding torch tensors with one-hot tokens', 'run the test_di_simple function to verify DiscreteIdentity encode and decode roundtrip accuracy', 'test the DiscreteIdentity tokenizer decode method with noisy one-hot token tensors', 'review the test_di_simple function that validates DiscreteIdentity reconstruction with noisy inputs', 'summarize the test_di_simple function that tests DiscreteIdentity encode decode roundtrip', 'test the PatchifyTokenizer encode and decode round-trip on random image data', 'run extract_patches to reshape a tensor into non-overlapping spatial patches of a given size', 'run merge_patches to reconstruct a spatial tensor from flattened patch sequences', 'create a PatchifyTokenizer instance with a specified patch size for encoding image trajectories', 'test that encoding then decoding with PatchifyTokenizer produces the original tensor values', 'test UniformBinningTokenizer encode and decode with small random uniform data and 2 bins', 'test UniformBinningTokenizer encode and decode with 10000 samples and 10 bins for reconstruction accuracy', 'test UniformBinningTokenizer with random normal data and data-derived min max bounds', 'test UniformBinningTokenizer encode and decode with 1024x8x5 tensor and 11 bins for large data', 'review UniformBinningTokenizer class encode and decode methods for uniform binning tokenization of trajectory data']
```

Usage

```
{'test_uniform_binning_simple': 'test UniformBinningTokenizer encode and decode with small random uniform data and 2 bins', 'test_uniform_binning_big': 'test UniformBinningTokenizer encode and decode with 10000 samples and 10 bins for reconstruction accuracy', 'test_uniform_binning_random': 'test UniformBinningTokenizer with random normal data and data-derived min max bounds', 'test_uniform_binning_large': 'test UniformBinningTokenizer encode and decode with 1024x8x5 tensor and 11 bins for large data', 'review_uniform_binning_tokenizer': 'review UniformBinningTokenizer class encode and decode methods for uniform binning tokenization of trajectory data'}
```

