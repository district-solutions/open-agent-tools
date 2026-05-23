# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/taming/modules/transformer/mingpt.py

Prompts

```
['build a GPT language model with configurable layers, heads, and embedding dimensions for sequence modeling', 'sample token sequences from a trained GPT model using top-k filtering and temperature scaling', 'sample from GPT using cached key-value states for efficient autoregressive generation without reprocessing context', 'build a CodeGPT model that takes continuous semi-embeddings as input instead of discrete token indices', 'train a KMeans codebook to quantize image patches into discrete cluster indices for vector quantization', 'create an AlternateParsing permuter that reverses every other row of a 2D grid for token shuffling', 'create a ZCurve permuter using Morton codes to interleave 2D spatial indices into a 1D sequence', 'create a SpiralOut permuter that orders tokens from the center of a square grid outward in a spiral', 'create a Subsample permuter that reorders tokens by recursively subsampling and interleaving quadrants of a grid', 'test any permuter class by forwarding a tensor and reversing to verify the original is recovered']
```

Usage

```
{'build_gpt_model': 'build a GPT language model with configurable layers, heads, and embedding dimensions for sequence modeling', 'sample_from_gpt': 'sample token sequences from a trained GPT model using top-k filtering and temperature scaling', 'sample_with_past': 'sample from GPT using cached key-value states for efficient autoregressive generation without reprocessing context', 'build_code_gpt': 'build a CodeGPT model that takes continuous semi-embeddings as input instead of discrete token indices', 'train_kmeans_codebook': 'train a KMeans codebook to quantize image patches into discrete cluster indices for vector quantization'}
```

## File: facebookresearch_stablesignature/src/taming/modules/transformer/permuter.py

Prompts

```
['build a GPT language model with configurable layers, heads, and embedding dimensions for sequence modeling', 'sample token sequences from a trained GPT model using top-k filtering and temperature scaling', 'sample from GPT using cached key-value states for efficient autoregressive generation without reprocessing context', 'build a CodeGPT model that takes continuous semi-embeddings as input instead of discrete token indices', 'train a KMeans codebook to quantize image patches into discrete cluster indices for vector quantization', 'create an AlternateParsing permuter that reverses every other row of a 2D grid for token shuffling', 'create a ZCurve permuter using Morton codes to interleave 2D spatial indices into a 1D sequence', 'create a SpiralOut permuter that orders tokens from the center of a square grid outward in a spiral', 'create a Subsample permuter that reorders tokens by recursively subsampling and interleaving quadrants of a grid', 'test any permuter class by forwarding a tensor and reversing to verify the original is recovered']
```

Usage

```
{'create_alternate_parsing_permuter': 'create an AlternateParsing permuter that reverses every other row of a 2D grid for token shuffling', 'create_zcurve_permuter': 'create a ZCurve permuter using Morton codes to interleave 2D spatial indices into a 1D sequence', 'create_spiral_out_permuter': 'create a SpiralOut permuter that orders tokens from the center of a square grid outward in a spiral', 'create_subsample_permuter': 'create a Subsample permuter that reorders tokens by recursively subsampling and interleaving quadrants of a grid', 'test_permuter_forward_backward': 'test any permuter class by forwarding a tensor and reversing to verify the original is recovered'}
```

