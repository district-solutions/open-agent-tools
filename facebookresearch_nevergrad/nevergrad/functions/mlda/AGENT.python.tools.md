# Agent Python Tools

- repo: facebookresearch/nevergrad
- repo_uri: https://github.com/facebookresearch/nevergrad

## File: facebookresearch_nevergrad/nevergrad/functions/mlda/datasets.py

Prompts

```
['download and load a named dataset like Ruspini or Virus as a numpy array', 'download and cache an external dataset file from a URL by name', 'get the cache folder path for stored downloaded dataset files', 'mock dataset downloads with fake zero-filled data to simplify unit testing', 'generate synthetic perceptron training data using quadratic, sine, abs, or heaviside functions', 'build a Clustering experiment from the Ruspini MLDA dataset with 5 clusters', 'build a Perceptron experiment from the quadratic MLDA dataset for optimization', 'build a SammonMapping experiment from the Virus MLDA dataset for dimensionality reduction', 'build a SammonMapping experiment from a 2D circle with 12 points', 'build a Landscape experiment with a gaussian transform for optimization', 'test the get_dataset_filepath function to verify it downloads and caches datasets by name', 'test the get_data function to verify it parses text files into numpy arrays', 'test the mocked_data context manager to verify all named datasets can be mocked for testing', 'test the make_perceptron_data function to verify it generates 50x2 arrays for quadratic sine abs and heaviside', 'test the get_data function to verify it parses Excel files into pandas DataFrames', 'test the _kmeans_distance function to compute distances between points and cluster centers', 'test the Clustering class to find optimal cluster centroids for a given dataset', 'test the Perceptron class to compute loss for a perceptron model with given parameters', 'test the SammonMapping class to compute Sammon mapping metric for dimensionality reduction', 'test the Landscape class to find minimum pixel values in an image-based optimization problem']
```

Usage

```
{'get_data_named_dataset': 'download and load a named dataset like Ruspini or Virus as a numpy array', 'get_dataset_filepath_download': 'download and cache an external dataset file from a URL by name', 'get_cache_folder_path': 'get the cache folder path for stored downloaded dataset files', 'mocked_data_testing': 'mock dataset downloads with fake zero-filled data to simplify unit testing', 'make_perceptron_data_generate': 'generate synthetic perceptron training data using quadratic, sine, abs, or heaviside functions'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/mlda/problems.py

Prompts

```
['download and load a named dataset like Ruspini or Virus as a numpy array', 'download and cache an external dataset file from a URL by name', 'get the cache folder path for stored downloaded dataset files', 'mock dataset downloads with fake zero-filled data to simplify unit testing', 'generate synthetic perceptron training data using quadratic, sine, abs, or heaviside functions', 'build a Clustering experiment from the Ruspini MLDA dataset with 5 clusters', 'build a Perceptron experiment from the quadratic MLDA dataset for optimization', 'build a SammonMapping experiment from the Virus MLDA dataset for dimensionality reduction', 'build a SammonMapping experiment from a 2D circle with 12 points', 'build a Landscape experiment with a gaussian transform for optimization', 'test the get_dataset_filepath function to verify it downloads and caches datasets by name', 'test the get_data function to verify it parses text files into numpy arrays', 'test the mocked_data context manager to verify all named datasets can be mocked for testing', 'test the make_perceptron_data function to verify it generates 50x2 arrays for quadratic sine abs and heaviside', 'test the get_data function to verify it parses Excel files into pandas DataFrames', 'test the _kmeans_distance function to compute distances between points and cluster centers', 'test the Clustering class to find optimal cluster centroids for a given dataset', 'test the Perceptron class to compute loss for a perceptron model with given parameters', 'test the SammonMapping class to compute Sammon mapping metric for dimensionality reduction', 'test the Landscape class to find minimum pixel values in an image-based optimization problem']
```

Usage

```
{'build_clustering_from_mlda': 'build a Clustering experiment from the Ruspini MLDA dataset with 5 clusters', 'build_perceptron_from_mlda': 'build a Perceptron experiment from the quadratic MLDA dataset for optimization', 'build_sammon_mapping_from_mlda': 'build a SammonMapping experiment from the Virus MLDA dataset for dimensionality reduction', 'build_sammon_mapping_circle': 'build a SammonMapping experiment from a 2D circle with 12 points', 'build_landscape_with_transform': 'build a Landscape experiment with a gaussian transform for optimization'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/mlda/test_datasets.py

Prompts

```
['download and load a named dataset like Ruspini or Virus as a numpy array', 'download and cache an external dataset file from a URL by name', 'get the cache folder path for stored downloaded dataset files', 'mock dataset downloads with fake zero-filled data to simplify unit testing', 'generate synthetic perceptron training data using quadratic, sine, abs, or heaviside functions', 'build a Clustering experiment from the Ruspini MLDA dataset with 5 clusters', 'build a Perceptron experiment from the quadratic MLDA dataset for optimization', 'build a SammonMapping experiment from the Virus MLDA dataset for dimensionality reduction', 'build a SammonMapping experiment from a 2D circle with 12 points', 'build a Landscape experiment with a gaussian transform for optimization', 'test the get_dataset_filepath function to verify it downloads and caches datasets by name', 'test the get_data function to verify it parses text files into numpy arrays', 'test the mocked_data context manager to verify all named datasets can be mocked for testing', 'test the make_perceptron_data function to verify it generates 50x2 arrays for quadratic sine abs and heaviside', 'test the get_data function to verify it parses Excel files into pandas DataFrames', 'test the _kmeans_distance function to compute distances between points and cluster centers', 'test the Clustering class to find optimal cluster centroids for a given dataset', 'test the Perceptron class to compute loss for a perceptron model with given parameters', 'test the SammonMapping class to compute Sammon mapping metric for dimensionality reduction', 'test the Landscape class to find minimum pixel values in an image-based optimization problem']
```

Usage

```
{'test_get_dataset_filepath': 'test the get_dataset_filepath function to verify it downloads and caches datasets by name', 'test_get_data': 'test the get_data function to verify it parses text files into numpy arrays', 'test_mocked_data': 'test the mocked_data context manager to verify all named datasets can be mocked for testing', 'test_make_perceptron_data': 'test the make_perceptron_data function to verify it generates 50x2 arrays for quadratic sine abs and heaviside', 'test_xls_get_data': 'test the get_data function to verify it parses Excel files into pandas DataFrames'}
```

## File: facebookresearch_nevergrad/nevergrad/functions/mlda/test_problems.py

Prompts

```
['download and load a named dataset like Ruspini or Virus as a numpy array', 'download and cache an external dataset file from a URL by name', 'get the cache folder path for stored downloaded dataset files', 'mock dataset downloads with fake zero-filled data to simplify unit testing', 'generate synthetic perceptron training data using quadratic, sine, abs, or heaviside functions', 'build a Clustering experiment from the Ruspini MLDA dataset with 5 clusters', 'build a Perceptron experiment from the quadratic MLDA dataset for optimization', 'build a SammonMapping experiment from the Virus MLDA dataset for dimensionality reduction', 'build a SammonMapping experiment from a 2D circle with 12 points', 'build a Landscape experiment with a gaussian transform for optimization', 'test the get_dataset_filepath function to verify it downloads and caches datasets by name', 'test the get_data function to verify it parses text files into numpy arrays', 'test the mocked_data context manager to verify all named datasets can be mocked for testing', 'test the make_perceptron_data function to verify it generates 50x2 arrays for quadratic sine abs and heaviside', 'test the get_data function to verify it parses Excel files into pandas DataFrames', 'test the _kmeans_distance function to compute distances between points and cluster centers', 'test the Clustering class to find optimal cluster centroids for a given dataset', 'test the Perceptron class to compute loss for a perceptron model with given parameters', 'test the SammonMapping class to compute Sammon mapping metric for dimensionality reduction', 'test the Landscape class to find minimum pixel values in an image-based optimization problem']
```

Usage

```
{'test_kmeans_distance': 'test the _kmeans_distance function to compute distances between points and cluster centers', 'test_clustering': 'test the Clustering class to find optimal cluster centroids for a given dataset', 'test_perceptron': 'test the Perceptron class to compute loss for a perceptron model with given parameters', 'test_sammon_mapping': 'test the SammonMapping class to compute Sammon mapping metric for dimensionality reduction', 'test_landscape': 'test the Landscape class to find minimum pixel values in an image-based optimization problem'}
```

