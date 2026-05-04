# Agent Python Tools

- repo: facebookresearch/flowmm
- repo_uri: https://github.com/facebookresearch/flowmm

## File: facebookresearch_flowmm/src/flowmm/old_eval/core.py

Prompts

```
['create a Crystal object from a dictionary containing frac_coords, atom_types, lengths, and angles arrays', 'parse a CIF string into a Crystal object with computed structure, composition, and validity', 'load ground truth crystal structures from a CSV or PT file using parallel CIF parsing', 'get lists of predicted and ground truth Crystal objects from evaluation data files', 'save evaluation metrics to a JSON file, only overwriting newly computed metric keys', 'compute generation metrics for predicted crystals against ground truth and save results to a metrics file', 'get all generation evaluation metrics including validity, density wasserstein distance, and coverage for predicted crystals', 'get validity statistics including composition validity, structural validity, and overall validity of generated crystals', 'compute the wasserstein distance between predicted and ground truth crystal density distributions', 'compute coverage metrics comparing generated crystals to ground truth using structure and composition cutoffs', 'compute lattice metrics and save length and angle histogram plots for crystal structures', 'extract lattice lengths and angles arrays from a list of crystal array dictionaries', 'plot seaborn FacetGrid histograms comparing predicted and ground truth lattice lengths and angles', 'create DataFrames for lattice lengths and angles with optional ground truth comparison data', 'generate a seaborn pairplot histogram comparing predicted and ground truth lattice lengths and angles', 'run compute_reconstruction_metrics to evaluate crystal structure reconstruction quality and save metrics to a file', 'create a RecEval evaluator to compute match rate and RMS distance between predicted and ground truth crystals', 'create a RecEvalBatch evaluator to compute best-match RMS distances across multiple predictions per ground truth crystal', 'review the RecEval process_one method that computes RMS distance between a single predicted and ground truth crystal structure', 'review the RecEval get_match_rate_and_rms method that iterates over all crystal pairs to compute aggregate match rate and mean RMS']
```

Usage

```
{'create_crystal_from_array_dict': 'create a Crystal object from a dictionary containing frac_coords, atom_types, lengths, and angles arrays', 'parse_cif_to_crystal': 'parse a CIF string into a Crystal object with computed structure, composition, and validity', 'load_ground_truth_crystals': 'load ground truth crystal structures from a CSV or PT file using parallel CIF parsing', 'get_crystal_object_lists': 'get lists of predicted and ground truth Crystal objects from evaluation data files', 'save_metrics_incrementally': 'save evaluation metrics to a JSON file, only overwriting newly computed metric keys'}
```

## File: facebookresearch_flowmm/src/flowmm/old_eval/generation_metrics.py

Prompts

```
['create a Crystal object from a dictionary containing frac_coords, atom_types, lengths, and angles arrays', 'parse a CIF string into a Crystal object with computed structure, composition, and validity', 'load ground truth crystal structures from a CSV or PT file using parallel CIF parsing', 'get lists of predicted and ground truth Crystal objects from evaluation data files', 'save evaluation metrics to a JSON file, only overwriting newly computed metric keys', 'compute generation metrics for predicted crystals against ground truth and save results to a metrics file', 'get all generation evaluation metrics including validity, density wasserstein distance, and coverage for predicted crystals', 'get validity statistics including composition validity, structural validity, and overall validity of generated crystals', 'compute the wasserstein distance between predicted and ground truth crystal density distributions', 'compute coverage metrics comparing generated crystals to ground truth using structure and composition cutoffs', 'compute lattice metrics and save length and angle histogram plots for crystal structures', 'extract lattice lengths and angles arrays from a list of crystal array dictionaries', 'plot seaborn FacetGrid histograms comparing predicted and ground truth lattice lengths and angles', 'create DataFrames for lattice lengths and angles with optional ground truth comparison data', 'generate a seaborn pairplot histogram comparing predicted and ground truth lattice lengths and angles', 'run compute_reconstruction_metrics to evaluate crystal structure reconstruction quality and save metrics to a file', 'create a RecEval evaluator to compute match rate and RMS distance between predicted and ground truth crystals', 'create a RecEvalBatch evaluator to compute best-match RMS distances across multiple predictions per ground truth crystal', 'review the RecEval process_one method that computes RMS distance between a single predicted and ground truth crystal structure', 'review the RecEval get_match_rate_and_rms method that iterates over all crystal pairs to compute aggregate match rate and mean RMS']
```

Usage

```
{'compute_generation_metrics': 'compute generation metrics for predicted crystals against ground truth and save results to a metrics file', 'GenEval_get_metrics': 'get all generation evaluation metrics including validity, density wasserstein distance, and coverage for predicted crystals', 'GenEval_get_validity': 'get validity statistics including composition validity, structural validity, and overall validity of generated crystals', 'GenEval_get_density_wdist': 'compute the wasserstein distance between predicted and ground truth crystal density distributions', 'GenEval_get_coverage': 'compute coverage metrics comparing generated crystals to ground truth using structure and composition cutoffs'}
```

## File: facebookresearch_flowmm/src/flowmm/old_eval/lattice_metrics.py

Prompts

```
['create a Crystal object from a dictionary containing frac_coords, atom_types, lengths, and angles arrays', 'parse a CIF string into a Crystal object with computed structure, composition, and validity', 'load ground truth crystal structures from a CSV or PT file using parallel CIF parsing', 'get lists of predicted and ground truth Crystal objects from evaluation data files', 'save evaluation metrics to a JSON file, only overwriting newly computed metric keys', 'compute generation metrics for predicted crystals against ground truth and save results to a metrics file', 'get all generation evaluation metrics including validity, density wasserstein distance, and coverage for predicted crystals', 'get validity statistics including composition validity, structural validity, and overall validity of generated crystals', 'compute the wasserstein distance between predicted and ground truth crystal density distributions', 'compute coverage metrics comparing generated crystals to ground truth using structure and composition cutoffs', 'compute lattice metrics and save length and angle histogram plots for crystal structures', 'extract lattice lengths and angles arrays from a list of crystal array dictionaries', 'plot seaborn FacetGrid histograms comparing predicted and ground truth lattice lengths and angles', 'create DataFrames for lattice lengths and angles with optional ground truth comparison data', 'generate a seaborn pairplot histogram comparing predicted and ground truth lattice lengths and angles', 'run compute_reconstruction_metrics to evaluate crystal structure reconstruction quality and save metrics to a file', 'create a RecEval evaluator to compute match rate and RMS distance between predicted and ground truth crystals', 'create a RecEvalBatch evaluator to compute best-match RMS distances across multiple predictions per ground truth crystal', 'review the RecEval process_one method that computes RMS distance between a single predicted and ground truth crystal structure', 'review the RecEval get_match_rate_and_rms method that iterates over all crystal pairs to compute aggregate match rate and mean RMS']
```

Usage

```
{'compute_lattice_metrics': 'compute lattice metrics and save length and angle histogram plots for crystal structures', 'get_lengths_angles': 'extract lattice lengths and angles arrays from a list of crystal array dictionaries', 'plot_lengths_angles_histograms': 'plot seaborn FacetGrid histograms comparing predicted and ground truth lattice lengths and angles', 'get_dfs_lengths_angles': 'create DataFrames for lattice lengths and angles with optional ground truth comparison data', 'pairplot': 'generate a seaborn pairplot histogram comparing predicted and ground truth lattice lengths and angles'}
```

## File: facebookresearch_flowmm/src/flowmm/old_eval/reconstruction_metrics.py

Prompts

```
['create a Crystal object from a dictionary containing frac_coords, atom_types, lengths, and angles arrays', 'parse a CIF string into a Crystal object with computed structure, composition, and validity', 'load ground truth crystal structures from a CSV or PT file using parallel CIF parsing', 'get lists of predicted and ground truth Crystal objects from evaluation data files', 'save evaluation metrics to a JSON file, only overwriting newly computed metric keys', 'compute generation metrics for predicted crystals against ground truth and save results to a metrics file', 'get all generation evaluation metrics including validity, density wasserstein distance, and coverage for predicted crystals', 'get validity statistics including composition validity, structural validity, and overall validity of generated crystals', 'compute the wasserstein distance between predicted and ground truth crystal density distributions', 'compute coverage metrics comparing generated crystals to ground truth using structure and composition cutoffs', 'compute lattice metrics and save length and angle histogram plots for crystal structures', 'extract lattice lengths and angles arrays from a list of crystal array dictionaries', 'plot seaborn FacetGrid histograms comparing predicted and ground truth lattice lengths and angles', 'create DataFrames for lattice lengths and angles with optional ground truth comparison data', 'generate a seaborn pairplot histogram comparing predicted and ground truth lattice lengths and angles', 'run compute_reconstruction_metrics to evaluate crystal structure reconstruction quality and save metrics to a file', 'create a RecEval evaluator to compute match rate and RMS distance between predicted and ground truth crystals', 'create a RecEvalBatch evaluator to compute best-match RMS distances across multiple predictions per ground truth crystal', 'review the RecEval process_one method that computes RMS distance between a single predicted and ground truth crystal structure', 'review the RecEval get_match_rate_and_rms method that iterates over all crystal pairs to compute aggregate match rate and mean RMS']
```

Usage

```
{'run_compute_reconstruction_metrics': 'run compute_reconstruction_metrics to evaluate crystal structure reconstruction quality and save metrics to a file', 'create_ReEval_evaluator': 'create a RecEval evaluator to compute match rate and RMS distance between predicted and ground truth crystals', 'create_ReEvalBatch_evaluator': 'create a RecEvalBatch evaluator to compute best-match RMS distances across multiple predictions per ground truth crystal', 'review_ReEval_process_one': 'review the RecEval process_one method that computes RMS distance between a single predicted and ground truth crystal structure', 'review_ReEval_get_match_rate_and_rms': 'review the RecEval get_match_rate_and_rms method that iterates over all crystal pairs to compute aggregate match rate and mean RMS'}
```

