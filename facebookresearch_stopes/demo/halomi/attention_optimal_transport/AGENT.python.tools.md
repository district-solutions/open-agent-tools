# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/demo/halomi/attention_optimal_transport/att_maps_compute.py

Prompts

```
['run the AttentionScoreModule to compute attention maps from TSV files using an NLLB model', 'run get_attention_maps to extract attention matrices from source-target sentence pairs via NLLB forward pass', 'run the CLI module with input/output dirs and NLLB model paths to schedule attention map computation', 'review the ScoreConfig dataclass that defines input files, output dir, and NLLB model path fields', 'review the AttentionScoreModule class that extends StopesModule to process TSV files and save attention maps as numpy arrays', 'compute the Wasserstein distance from an attention map to a uniform distribution', "compute the Earth Mover's Distance between two attention distribution vectors", 'find the best matching distance for a query attention map against reference maps', 'compute a combined Wasserstein score from uniform and data distance values', 'compute optimal threshold and rescale parameters for the combo scoring function']
```

Usage

```
{'run_attention_score_module': 'run the AttentionScoreModule to compute attention maps from TSV files using an NLLB model', 'run_get_attention_maps': 'run get_attention_maps to extract attention matrices from source-target sentence pairs via NLLB forward pass', 'run_main_cli': 'run the CLI module with input/output dirs and NLLB model paths to schedule attention map computation', 'review_ScoreConfig': 'review the ScoreConfig dataclass that defines input files, output dir, and NLLB model path fields', 'review_AttentionScoreModule': 'review the AttentionScoreModule class that extends StopesModule to process TSV files and save attention maps as numpy arrays'}
```

## File: facebookresearch_stopes/demo/halomi/attention_optimal_transport/optimal_transport_scoring.py

Prompts

```
['run the AttentionScoreModule to compute attention maps from TSV files using an NLLB model', 'run get_attention_maps to extract attention matrices from source-target sentence pairs via NLLB forward pass', 'run the CLI module with input/output dirs and NLLB model paths to schedule attention map computation', 'review the ScoreConfig dataclass that defines input files, output dir, and NLLB model path fields', 'review the AttentionScoreModule class that extends StopesModule to process TSV files and save attention maps as numpy arrays', 'compute the Wasserstein distance from an attention map to a uniform distribution', "compute the Earth Mover's Distance between two attention distribution vectors", 'find the best matching distance for a query attention map against reference maps', 'compute a combined Wasserstein score from uniform and data distance values', 'compute optimal threshold and rescale parameters for the combo scoring function']
```

Usage

```
{'compute_wass2unif': 'compute the Wasserstein distance from an attention map to a uniform distribution', 'compute_get_emd': "compute the Earth Mover's Distance between two attention distribution vectors", 'compute_get_best_dist': 'find the best matching distance for a query attention map against reference maps', 'compute_get_combo_score': 'compute a combined Wasserstein score from uniform and data distance values', 'compute_compute_combo_parameters': 'compute optimal threshold and rescale parameters for the combo scoring function'}
```

