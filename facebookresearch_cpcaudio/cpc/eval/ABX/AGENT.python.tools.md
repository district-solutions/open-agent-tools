# Agent Python Tools

- repo: facebookresearch/cpcaudio
- repo_uri: https://github.com/facebookresearch/cpc_audio

## File: facebookresearch_cpcaudio/cpc/eval/ABX/abx_group_computation.py

Prompts

```
['get the distance function by name such as euclidian or cosine for batch computation', 'compute cosine distance between two batched sequence tensors with shape batch seq channel', 'compute euclidean distance between two batched sequence tensors with shape batch seq channel', 'compute DTW distance matrix between two groups of sequences using a specified distance function', 'compute the ABX theta score using DTW distances between groups a, b, and x', 'load an ABX .item file and parse triplets with phone, context, and speaker mappings', 'normalize a 3D tensor across the channel dimension and handle null vectors with a border vector', 'group and sort feature data by a specified index order for hierarchical ABX triplet organization', 'create an ABXFeatureLoader to load and manage audio features from an item file with optional normalization', 'iterate over ABX within-group triplets comparing phone instances from the same speaker and context', 'run the unit tests for DTW distance computation on batched PyTorch tensors', 'run the symmetric theta DTW function test using euclidian distance on tensor groups', 'run the singularity normalization and cosine distance batch tests on PyTorch tensors', 'run the 1D, 2D, and 3D feature grouping tests using get_features_group', 'run the ABXFeatureLoader base and within iterator tests on dummy item files']
```

Usage

```
{'get_distance_function_from_name': 'get the distance function by name such as euclidian or cosine for batch computation', 'get_cosine_distance_batch': 'compute cosine distance between two batched sequence tensors with shape batch seq channel', 'get_euclidian_distance_batch': 'compute euclidean distance between two batched sequence tensors with shape batch seq channel', 'get_distance_group_dtw': 'compute DTW distance matrix between two groups of sequences using a specified distance function', 'get_theta_group_dtw': 'compute the ABX theta score using DTW distances between groups a, b, and x'}
```

## File: facebookresearch_cpcaudio/cpc/eval/ABX/abx_iterators.py

Prompts

```
['get the distance function by name such as euclidian or cosine for batch computation', 'compute cosine distance between two batched sequence tensors with shape batch seq channel', 'compute euclidean distance between two batched sequence tensors with shape batch seq channel', 'compute DTW distance matrix between two groups of sequences using a specified distance function', 'compute the ABX theta score using DTW distances between groups a, b, and x', 'load an ABX .item file and parse triplets with phone, context, and speaker mappings', 'normalize a 3D tensor across the channel dimension and handle null vectors with a border vector', 'group and sort feature data by a specified index order for hierarchical ABX triplet organization', 'create an ABXFeatureLoader to load and manage audio features from an item file with optional normalization', 'iterate over ABX within-group triplets comparing phone instances from the same speaker and context', 'run the unit tests for DTW distance computation on batched PyTorch tensors', 'run the symmetric theta DTW function test using euclidian distance on tensor groups', 'run the singularity normalization and cosine distance batch tests on PyTorch tensors', 'run the 1D, 2D, and 3D feature grouping tests using get_features_group', 'run the ABXFeatureLoader base and within iterator tests on dummy item files']
```

Usage

```
{'load_item_file': 'load an ABX .item file and parse triplets with phone, context, and speaker mappings', 'normalize_with_singularity': 'normalize a 3D tensor across the channel dimension and handle null vectors with a border vector', 'get_features_group': 'group and sort feature data by a specified index order for hierarchical ABX triplet organization', 'ABXFeatureLoader_init': 'create an ABXFeatureLoader to load and manage audio features from an item file with optional normalization', 'ABXWithinGroupIterator': 'iterate over ABX within-group triplets comparing phone instances from the same speaker and context'}
```

## File: facebookresearch_cpcaudio/cpc/eval/ABX/unit_tests.py

Prompts

```
['get the distance function by name such as euclidian or cosine for batch computation', 'compute cosine distance between two batched sequence tensors with shape batch seq channel', 'compute euclidean distance between two batched sequence tensors with shape batch seq channel', 'compute DTW distance matrix between two groups of sequences using a specified distance function', 'compute the ABX theta score using DTW distances between groups a, b, and x', 'load an ABX .item file and parse triplets with phone, context, and speaker mappings', 'normalize a 3D tensor across the channel dimension and handle null vectors with a border vector', 'group and sort feature data by a specified index order for hierarchical ABX triplet organization', 'create an ABXFeatureLoader to load and manage audio features from an item file with optional normalization', 'iterate over ABX within-group triplets comparing phone instances from the same speaker and context', 'run the unit tests for DTW distance computation on batched PyTorch tensors', 'run the symmetric theta DTW function test using euclidian distance on tensor groups', 'run the singularity normalization and cosine distance batch tests on PyTorch tensors', 'run the 1D, 2D, and 3D feature grouping tests using get_features_group', 'run the ABXFeatureLoader base and within iterator tests on dummy item files']
```

Usage

```
{'run_dtw_distance_tests': 'run the unit tests for DTW distance computation on batched PyTorch tensors', 'run_theta_dtw_symetric_test': 'run the symmetric theta DTW function test using euclidian distance on tensor groups', 'run_cosine_normalization_tests': 'run the singularity normalization and cosine distance batch tests on PyTorch tensors', 'run_group_maker_tests': 'run the 1D, 2D, and 3D feature grouping tests using get_features_group', 'run_abx_feature_loader_tests': 'run the ABXFeatureLoader base and within iterator tests on dummy item files'}
```

