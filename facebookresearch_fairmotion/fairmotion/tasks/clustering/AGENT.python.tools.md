# Agent Python Tools

- repo: facebookresearch/fairmotion
- repo_uri: https://github.com/facebookresearch/fairmotion

## File: facebookresearch_fairmotion/fairmotion/tasks/clustering/clustering.py

Prompts

```
['run k-means clustering on features and return clusters with names and scores', 'run agglomerative hierarchical clustering with configurable linkage on features and names', 'run DBSCAN density-based clustering on features with eps 3 and min_samples 2', 'run OPTICS clustering on features with min_samples 10 and return scored clusters', 'normalize features by subtracting mean and dividing by standard deviation', 'run the CLI to extract manual pose features from BVH motion capture files', 'run the CLI to extract kinetic energy features from BVH motion capture files', 'run the multiprocessing wrapper to extract and write features to a TSV file', 'refactor extract_manual_features to add or remove pose feature metrics like f_angle or f_fast', 'review extract_kinetic_features to understand how kinetic energy and position stats are computed per joint', 'run the split_bvh CLI to split BVH motion files into overlapping time window clips', 'run the split_bvh tool on a folder of BVH files with a specified time window', 'create a function that splits a single BVH motion file into overlapping clips by time window', 'create a main function that walks a folder and splits all BVH files into clips', 'refactor the split_bvh function to customize the overlap stride between motion clips', 'test the velocity_above_threshold utility to check if 3D velocity exceeds a given threshold', 'test the angle_within_range utility to verify the angle between two 3D vectors falls within a range', 'test the distance_from_plane_normal utility to check if a point is within a threshold distance from a plane', 'test the distance_from_plane utility to verify a point is within a threshold distance from a plane defined by three points', 'run the Test3DGeometryUtils unit test suite to validate all 3D geometry utility functions']
```

Usage

```
{'run_kmeans_clustering': 'run k-means clustering on features and return clusters with names and scores', 'run_hierarchical_clustering': 'run agglomerative hierarchical clustering with configurable linkage on features and names', 'run_dbscan_clustering': 'run DBSCAN density-based clustering on features with eps 3 and min_samples 2', 'run_optics_clustering': 'run OPTICS clustering on features with min_samples 10 and return scored clusters', 'normalize_features': 'normalize features by subtracting mean and dividing by standard deviation'}
```

## File: facebookresearch_fairmotion/fairmotion/tasks/clustering/generate_features.py

Prompts

```
['run k-means clustering on features and return clusters with names and scores', 'run agglomerative hierarchical clustering with configurable linkage on features and names', 'run DBSCAN density-based clustering on features with eps 3 and min_samples 2', 'run OPTICS clustering on features with min_samples 10 and return scored clusters', 'normalize features by subtracting mean and dividing by standard deviation', 'run the CLI to extract manual pose features from BVH motion capture files', 'run the CLI to extract kinetic energy features from BVH motion capture files', 'run the multiprocessing wrapper to extract and write features to a TSV file', 'refactor extract_manual_features to add or remove pose feature metrics like f_angle or f_fast', 'review extract_kinetic_features to understand how kinetic energy and position stats are computed per joint', 'run the split_bvh CLI to split BVH motion files into overlapping time window clips', 'run the split_bvh tool on a folder of BVH files with a specified time window', 'create a function that splits a single BVH motion file into overlapping clips by time window', 'create a main function that walks a folder and splits all BVH files into clips', 'refactor the split_bvh function to customize the overlap stride between motion clips', 'test the velocity_above_threshold utility to check if 3D velocity exceeds a given threshold', 'test the angle_within_range utility to verify the angle between two 3D vectors falls within a range', 'test the distance_from_plane_normal utility to check if a point is within a threshold distance from a plane', 'test the distance_from_plane utility to verify a point is within a threshold distance from a plane defined by three points', 'run the Test3DGeometryUtils unit test suite to validate all 3D geometry utility functions']
```

Usage

```
{'run_extract_manual_features': 'run the CLI to extract manual pose features from BVH motion capture files', 'run_extract_kinetic_features': 'run the CLI to extract kinetic energy features from BVH motion capture files', 'run_wrapper_extract_features': 'run the multiprocessing wrapper to extract and write features to a TSV file', 'refactor_extract_manual_features': 'refactor extract_manual_features to add or remove pose feature metrics like f_angle or f_fast', 'review_extract_kinetic_features': 'review extract_kinetic_features to understand how kinetic energy and position stats are computed per joint'}
```

## File: facebookresearch_fairmotion/fairmotion/tasks/clustering/split_bvh.py

Prompts

```
['run k-means clustering on features and return clusters with names and scores', 'run agglomerative hierarchical clustering with configurable linkage on features and names', 'run DBSCAN density-based clustering on features with eps 3 and min_samples 2', 'run OPTICS clustering on features with min_samples 10 and return scored clusters', 'normalize features by subtracting mean and dividing by standard deviation', 'run the CLI to extract manual pose features from BVH motion capture files', 'run the CLI to extract kinetic energy features from BVH motion capture files', 'run the multiprocessing wrapper to extract and write features to a TSV file', 'refactor extract_manual_features to add or remove pose feature metrics like f_angle or f_fast', 'review extract_kinetic_features to understand how kinetic energy and position stats are computed per joint', 'run the split_bvh CLI to split BVH motion files into overlapping time window clips', 'run the split_bvh tool on a folder of BVH files with a specified time window', 'create a function that splits a single BVH motion file into overlapping clips by time window', 'create a main function that walks a folder and splits all BVH files into clips', 'refactor the split_bvh function to customize the overlap stride between motion clips', 'test the velocity_above_threshold utility to check if 3D velocity exceeds a given threshold', 'test the angle_within_range utility to verify the angle between two 3D vectors falls within a range', 'test the distance_from_plane_normal utility to check if a point is within a threshold distance from a plane', 'test the distance_from_plane utility to verify a point is within a threshold distance from a plane defined by three points', 'run the Test3DGeometryUtils unit test suite to validate all 3D geometry utility functions']
```

Usage

```
{'run_split_bvh_cli': 'run the split_bvh CLI to split BVH motion files into overlapping time window clips', 'run_split_bvh_folder': 'run the split_bvh tool on a folder of BVH files with a specified time window', 'create_split_bvh_function': 'create a function that splits a single BVH motion file into overlapping clips by time window', 'create_main_batch_split': 'create a main function that walks a folder and splits all BVH files into clips', 'refactor_split_bvh_overlap': 'refactor the split_bvh function to customize the overlap stride between motion clips'}
```

## File: facebookresearch_fairmotion/fairmotion/tasks/clustering/test_generate_features.py

Prompts

```
['run k-means clustering on features and return clusters with names and scores', 'run agglomerative hierarchical clustering with configurable linkage on features and names', 'run DBSCAN density-based clustering on features with eps 3 and min_samples 2', 'run OPTICS clustering on features with min_samples 10 and return scored clusters', 'normalize features by subtracting mean and dividing by standard deviation', 'run the CLI to extract manual pose features from BVH motion capture files', 'run the CLI to extract kinetic energy features from BVH motion capture files', 'run the multiprocessing wrapper to extract and write features to a TSV file', 'refactor extract_manual_features to add or remove pose feature metrics like f_angle or f_fast', 'review extract_kinetic_features to understand how kinetic energy and position stats are computed per joint', 'run the split_bvh CLI to split BVH motion files into overlapping time window clips', 'run the split_bvh tool on a folder of BVH files with a specified time window', 'create a function that splits a single BVH motion file into overlapping clips by time window', 'create a main function that walks a folder and splits all BVH files into clips', 'refactor the split_bvh function to customize the overlap stride between motion clips', 'test the velocity_above_threshold utility to check if 3D velocity exceeds a given threshold', 'test the angle_within_range utility to verify the angle between two 3D vectors falls within a range', 'test the distance_from_plane_normal utility to check if a point is within a threshold distance from a plane', 'test the distance_from_plane utility to verify a point is within a threshold distance from a plane defined by three points', 'run the Test3DGeometryUtils unit test suite to validate all 3D geometry utility functions']
```

Usage

```
{'test_velocity_above_threshold': 'test the velocity_above_threshold utility to check if 3D velocity exceeds a given threshold', 'test_angle_within_range': 'test the angle_within_range utility to verify the angle between two 3D vectors falls within a range', 'test_distance_from_plane_normal': 'test the distance_from_plane_normal utility to check if a point is within a threshold distance from a plane', 'test_distance_from_plane': 'test the distance_from_plane utility to verify a point is within a threshold distance from a plane defined by three points', 'run_test_3d_geometry_utils': 'run the Test3DGeometryUtils unit test suite to validate all 3D geometry utility functions'}
```

