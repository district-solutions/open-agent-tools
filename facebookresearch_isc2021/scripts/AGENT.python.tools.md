# Agent Python Tools

- repo: facebookresearch/isc2021
- repo_uri: https://github.com/facebookresearch/isc2021

## File: facebookresearch_isc2021/scripts/compute_metrics.py

Prompts

```
['run the compute_metrics function to evaluate Track 1 predicted matches against ground truth CSV', 'run the compute_metrics_track2 function to match descriptors and evaluate Track 2 results against ground truth', 'run the plot_pr_curve function to generate and save a precision-recall curve plot', 'run the script with --track2 to match query descriptors against database descriptors using FAISS', 'run the script with --track2 and --knn to perform k-nearest neighbor descriptor matching using FAISS', 'run the script to convert database and query descriptors into official ISC track 2 HDF5 submission format', 'run sort_descriptors to sort image IDs alphabetically and cast descriptors to float32 for HDF5 compatibility', 'run read_descriptors from isc.io to load database or query descriptor files in HDF5 format', 'review sort_descriptors which converts string IDs to ASCII bytes and sorts them for official evaluation compatibility', 'review the CLI tool that validates descriptor dimensions and writes query/reference datasets to an HDF5 output file', 'run the score normalization script to compute normalized image matching predictions from HDF5 descriptors', 'compute normalization factors by matching query descriptors against training descriptors using FAISS inner-product search', 'match query descriptors against database descriptors with score normalization using min or mean reduction', 'write computed normalization factors to a numpy file for debugging or reuse in later runs', 'read image descriptors and image IDs from HDF5 format files for image retrieval matching']
```

Usage

```
{'run_compute_metrics_track1': 'run the compute_metrics function to evaluate Track 1 predicted matches against ground truth CSV', 'run_compute_metrics_track2': 'run the compute_metrics_track2 function to match descriptors and evaluate Track 2 results against ground truth', 'run_plot_pr_curve': 'run the plot_pr_curve function to generate and save a precision-recall curve plot', 'run_match_descriptors_faiss': 'run the script with --track2 to match query descriptors against database descriptors using FAISS', 'run_knn_match_descriptors': 'run the script with --track2 and --knn to perform k-nearest neighbor descriptor matching using FAISS'}
```

## File: facebookresearch_isc2021/scripts/convert_track2_format.py

Prompts

```
['run the compute_metrics function to evaluate Track 1 predicted matches against ground truth CSV', 'run the compute_metrics_track2 function to match descriptors and evaluate Track 2 results against ground truth', 'run the plot_pr_curve function to generate and save a precision-recall curve plot', 'run the script with --track2 to match query descriptors against database descriptors using FAISS', 'run the script with --track2 and --knn to perform k-nearest neighbor descriptor matching using FAISS', 'run the script to convert database and query descriptors into official ISC track 2 HDF5 submission format', 'run sort_descriptors to sort image IDs alphabetically and cast descriptors to float32 for HDF5 compatibility', 'run read_descriptors from isc.io to load database or query descriptor files in HDF5 format', 'review sort_descriptors which converts string IDs to ASCII bytes and sorts them for official evaluation compatibility', 'review the CLI tool that validates descriptor dimensions and writes query/reference datasets to an HDF5 output file', 'run the score normalization script to compute normalized image matching predictions from HDF5 descriptors', 'compute normalization factors by matching query descriptors against training descriptors using FAISS inner-product search', 'match query descriptors against database descriptors with score normalization using min or mean reduction', 'write computed normalization factors to a numpy file for debugging or reuse in later runs', 'read image descriptors and image IDs from HDF5 format files for image retrieval matching']
```

Usage

```
{'run_convert_track2_format': 'run the script to convert database and query descriptors into official ISC track 2 HDF5 submission format', 'run_sort_descriptors': 'run sort_descriptors to sort image IDs alphabetically and cast descriptors to float32 for HDF5 compatibility', 'run_read_descriptors': 'run read_descriptors from isc.io to load database or query descriptor files in HDF5 format', 'review_sort_descriptors': 'review sort_descriptors which converts string IDs to ASCII bytes and sorts them for official evaluation compatibility', 'review_convert_track2_format': 'review the CLI tool that validates descriptor dimensions and writes query/reference datasets to an HDF5 output file'}
```

## File: facebookresearch_isc2021/scripts/score_normalization.py

Prompts

```
['run the compute_metrics function to evaluate Track 1 predicted matches against ground truth CSV', 'run the compute_metrics_track2 function to match descriptors and evaluate Track 2 results against ground truth', 'run the plot_pr_curve function to generate and save a precision-recall curve plot', 'run the script with --track2 to match query descriptors against database descriptors using FAISS', 'run the script with --track2 and --knn to perform k-nearest neighbor descriptor matching using FAISS', 'run the script to convert database and query descriptors into official ISC track 2 HDF5 submission format', 'run sort_descriptors to sort image IDs alphabetically and cast descriptors to float32 for HDF5 compatibility', 'run read_descriptors from isc.io to load database or query descriptor files in HDF5 format', 'review sort_descriptors which converts string IDs to ASCII bytes and sorts them for official evaluation compatibility', 'review the CLI tool that validates descriptor dimensions and writes query/reference datasets to an HDF5 output file', 'run the score normalization script to compute normalized image matching predictions from HDF5 descriptors', 'compute normalization factors by matching query descriptors against training descriptors using FAISS inner-product search', 'match query descriptors against database descriptors with score normalization using min or mean reduction', 'write computed normalization factors to a numpy file for debugging or reuse in later runs', 'read image descriptors and image IDs from HDF5 format files for image retrieval matching']
```

Usage

```
{'run_score_normalization': 'run the score normalization script to compute normalized image matching predictions from HDF5 descriptors', 'compute_normalization_factors': 'compute normalization factors by matching query descriptors against training descriptors using FAISS inner-product search', 'match_descriptors_with_normalization': 'match query descriptors against database descriptors with score normalization using min or mean reduction', 'write_normalization_factors': 'write computed normalization factors to a numpy file for debugging or reuse in later runs', 'read_hdf5_descriptors': 'read image descriptors and image IDs from HDF5 format files for image retrieval matching'}
```

