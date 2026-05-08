# Agent Python Tools

- repo: facebookresearch/isc2021
- repo_uri: https://github.com/facebookresearch/isc2021

## File: facebookresearch_isc2021/baselines/GeM_baseline.py

Prompts

```
['run the GeM baseline CLI to extract image descriptors from a file list using ResNet50', 'run PCA training on extracted descriptors and save the PCA matrix to a file', 'run the GeM baseline with a pre-trained PCA file to apply dimensionality reduction to descriptors', 'review the load_model function that loads zoo_resnet50 or multigrain_resnet50 checkpoints', 'review the gem_npy function that computes Generalized Mean pooling on numpy arrays', 'run the gist baseline script to extract GIST features from a list of images and save descriptors to HDF5', 'run GIST feature extraction across multiple subprocesses using the nproc argument for parallel processing', 'review the GISTFeatures class that preprocesses images and calls the external GIST executable via subprocess', 'summarize the fvecs_read function that reads FAISS fvecs binary files into a numpy float32 array', 'run the CLI to find best image-pair matches from HOW method results and write predictions to CSV', 'run load_list_file to read image names from a text file into a Python list', 'run load_results to load and merge search results from multiple pickle files into numpy arrays', 'run store_predictions to write a list of query-reference-score tuples to a CSV file', 'review the find_matches function that normalizes scores and extracts top image-pair predictions']
```

Usage

```
{'run_gem_feature_extraction': 'run the GeM baseline CLI to extract image descriptors from a file list using ResNet50', 'run_pca_training': 'run PCA training on extracted descriptors and save the PCA matrix to a file', 'run_pca_application': 'run the GeM baseline with a pre-trained PCA file to apply dimensionality reduction to descriptors', 'review_load_model': 'review the load_model function that loads zoo_resnet50 or multigrain_resnet50 checkpoints', 'review_gem_npy': 'review the gem_npy function that computes Generalized Mean pooling on numpy arrays'}
```

## File: facebookresearch_isc2021/baselines/gist_baseline.py

Prompts

```
['run the GeM baseline CLI to extract image descriptors from a file list using ResNet50', 'run PCA training on extracted descriptors and save the PCA matrix to a file', 'run the GeM baseline with a pre-trained PCA file to apply dimensionality reduction to descriptors', 'review the load_model function that loads zoo_resnet50 or multigrain_resnet50 checkpoints', 'review the gem_npy function that computes Generalized Mean pooling on numpy arrays', 'run the gist baseline script to extract GIST features from a list of images and save descriptors to HDF5', 'run GIST feature extraction across multiple subprocesses using the nproc argument for parallel processing', 'review the GISTFeatures class that preprocesses images and calls the external GIST executable via subprocess', 'summarize the fvecs_read function that reads FAISS fvecs binary files into a numpy float32 array', 'run the CLI to find best image-pair matches from HOW method results and write predictions to CSV', 'run load_list_file to read image names from a text file into a Python list', 'run load_results to load and merge search results from multiple pickle files into numpy arrays', 'run store_predictions to write a list of query-reference-score tuples to a CSV file', 'review the find_matches function that normalizes scores and extracts top image-pair predictions']
```

Usage

```
{'run_gist_feature_extraction': 'run the gist baseline script to extract GIST features from a list of images and save descriptors to HDF5', 'run_pca_training': 'run PCA training on a subsample of GIST descriptors and save the PCA transform to a file', 'run_gist_multiprocess': 'run GIST feature extraction across multiple subprocesses using the nproc argument for parallel processing', 'review_GISTFeatures_class': 'review the GISTFeatures class that preprocesses images and calls the external GIST executable via subprocess', 'summarize_fvecs_read': 'summarize the fvecs_read function that reads FAISS fvecs binary files into a numpy float32 array'}
```

## File: facebookresearch_isc2021/baselines/how_find_matches.py

Prompts

```
['run the GeM baseline CLI to extract image descriptors from a file list using ResNet50', 'run PCA training on extracted descriptors and save the PCA matrix to a file', 'run the GeM baseline with a pre-trained PCA file to apply dimensionality reduction to descriptors', 'review the load_model function that loads zoo_resnet50 or multigrain_resnet50 checkpoints', 'review the gem_npy function that computes Generalized Mean pooling on numpy arrays', 'run the gist baseline script to extract GIST features from a list of images and save descriptors to HDF5', 'run GIST feature extraction across multiple subprocesses using the nproc argument for parallel processing', 'review the GISTFeatures class that preprocesses images and calls the external GIST executable via subprocess', 'summarize the fvecs_read function that reads FAISS fvecs binary files into a numpy float32 array', 'run the CLI to find best image-pair matches from HOW method results and write predictions to CSV', 'run load_list_file to read image names from a text file into a Python list', 'run load_results to load and merge search results from multiple pickle files into numpy arrays', 'run store_predictions to write a list of query-reference-score tuples to a CSV file', 'review the find_matches function that normalizes scores and extracts top image-pair predictions']
```

Usage

```
{'run_find_matches': 'run the CLI to find best image-pair matches from HOW method results and write predictions to CSV', 'run_load_list_file': 'run load_list_file to read image names from a text file into a Python list', 'run_load_results': 'run load_results to load and merge search results from multiple pickle files into numpy arrays', 'run_store_predictions': 'run store_predictions to write a list of query-reference-score tuples to a CSV file', 'review_find_matches': 'review the find_matches function that normalizes scores and extracts top image-pair predictions'}
```

