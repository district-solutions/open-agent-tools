# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/audio/source_separation/loss/si_sdr.py

Prompts

```
['compute the scale-invariant SDR loss between estimated and reference source signals using a validity mask', 'build a loss function for audio source separation that centers signals and applies permutation-invariant SDR', 'test the si_sdr_loss function with batched speaker audio tensors and a padding mask', 'refactor the si_sdr_loss function to support additional normalization strategies beyond mean centering', 'review the si_sdr_loss implementation for correctness of mean subtraction and sdr_pit utility usage', 'compute the source-to-distortion ratio between estimated and reference audio signals', 'compute the permutation-invariant source-to-distortion ratio for multi-speaker audio separation', 'compute the SDR improvement by comparing estimated signals against the original mixture', 'build a permutation invariant training module that optimizes speaker alignment across utterances', 'test the SDR function using a binary mask to exclude padded time frames']
```

Usage

```
{'compute_si_sdr_loss': 'compute the scale-invariant SDR loss between estimated and reference source signals using a validity mask', 'build_source_separation_loss': 'build a loss function for audio source separation that centers signals and applies permutation-invariant SDR', 'test_si_sdr_loss': 'test the si_sdr_loss function with batched speaker audio tensors and a padding mask', 'refactor_si_sdr_loss': 'refactor the si_sdr_loss function to support additional normalization strategies beyond mean centering', 'review_si_sdr_loss': 'review the si_sdr_loss implementation for correctness of mean subtraction and sdr_pit utility usage'}
```

## File: facebookresearch_recipes/torchrecipes/audio/source_separation/loss/utils.py

Prompts

```
['compute the scale-invariant SDR loss between estimated and reference source signals using a validity mask', 'build a loss function for audio source separation that centers signals and applies permutation-invariant SDR', 'test the si_sdr_loss function with batched speaker audio tensors and a padding mask', 'refactor the si_sdr_loss function to support additional normalization strategies beyond mean centering', 'review the si_sdr_loss implementation for correctness of mean subtraction and sdr_pit utility usage', 'compute the source-to-distortion ratio between estimated and reference audio signals', 'compute the permutation-invariant source-to-distortion ratio for multi-speaker audio separation', 'compute the SDR improvement by comparing estimated signals against the original mixture', 'build a permutation invariant training module that optimizes speaker alignment across utterances', 'test the SDR function using a binary mask to exclude padded time frames']
```

Usage

```
{'compute_sdr': 'compute the source-to-distortion ratio between estimated and reference audio signals', 'compute_sdr_pit': 'compute the permutation-invariant source-to-distortion ratio for multi-speaker audio separation', 'compute_sdri': 'compute the SDR improvement by comparing estimated signals against the original mixture', 'build_PIT_module': 'build a permutation invariant training module that optimizes speaker alignment across utterances', 'test_sdr_with_mask': 'test the SDR function using a binary mask to exclude padded time frames'}
```

