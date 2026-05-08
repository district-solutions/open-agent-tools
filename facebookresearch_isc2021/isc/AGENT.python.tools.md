# Agent Python Tools

- repo: facebookresearch/isc2021
- repo_uri: https://github.com/facebookresearch/isc2021

## File: facebookresearch_isc2021/isc/descriptor_matching.py

Prompts

```
['search query descriptors against a database with a capped total number of results using FAISS', 'match query descriptors to database descriptors and return PredictedMatch objects with scores', 'perform k-nearest-neighbor matching of query descriptors against a database and return predictions', 'read a binary range search result file and return per-query result counts and indices', 'find a radius threshold that reduces inner product search results to a target count', 'create an HTML figure with a base64-embedded JPEG thumbnail of an image from a given ID and URI mapping', 'create an HTML table row with side-by-side query and database image thumbnails and a retrieval score', 'create a full HTML page with a table of image retrieval pairs showing query, database, and score columns', 'review the ImagePair dataclass that holds query ID, database ID, score, and correctness for image retrieval results', 'refactor create_html_img_embed to support additional image formats or custom thumbnail sizing options', 'read a ground truth CSV file with query and database image ID pairs into GroundTruthMatch objects', 'read a predictions CSV file with query ID, database ID, and score into PredictedMatch objects', 'write an iterable of PredictedMatch objects to a CSV file with query, database, and score columns', 'write FAISS nearest neighbor scores and indices arrays to a CSV predictions file with optional nmax and score filtering', 'write image descriptor vectors and image names to an HDF5 file with vectors and image_names datasets', 'evaluate ground truth matches against predicted matches and return precision, recall, and rank metrics', 'compute precision, recall, and threshold arrays from binary labels and prediction scores', 'compute the micro average-precision score from sorted recall and precision arrays', 'find the highest recall value at a required precision threshold from precision-recall curves', 'find the rank of each ground truth match within the predicted results for its query']
```

Usage

```
{'search_with_capped_res': 'search query descriptors against a database with a capped total number of results using FAISS', 'match_and_make_predictions': 'match query descriptors to database descriptors and return PredictedMatch objects with scores', 'knn_match_and_make_predictions': 'perform k-nearest-neighbor matching of query descriptors against a database and return predictions', 'range_result_read': 'read a binary range search result file and return per-query result counts and indices', 'apply_maxres_IP': 'find a radius threshold that reduces inner product search results to a target count'}
```

## File: facebookresearch_isc2021/isc/html.py

Prompts

```
['search query descriptors against a database with a capped total number of results using FAISS', 'match query descriptors to database descriptors and return PredictedMatch objects with scores', 'perform k-nearest-neighbor matching of query descriptors against a database and return predictions', 'read a binary range search result file and return per-query result counts and indices', 'find a radius threshold that reduces inner product search results to a target count', 'create an HTML figure with a base64-embedded JPEG thumbnail of an image from a given ID and URI mapping', 'create an HTML table row with side-by-side query and database image thumbnails and a retrieval score', 'create a full HTML page with a table of image retrieval pairs showing query, database, and score columns', 'review the ImagePair dataclass that holds query ID, database ID, score, and correctness for image retrieval results', 'refactor create_html_img_embed to support additional image formats or custom thumbnail sizing options', 'read a ground truth CSV file with query and database image ID pairs into GroundTruthMatch objects', 'read a predictions CSV file with query ID, database ID, and score into PredictedMatch objects', 'write an iterable of PredictedMatch objects to a CSV file with query, database, and score columns', 'write FAISS nearest neighbor scores and indices arrays to a CSV predictions file with optional nmax and score filtering', 'write image descriptor vectors and image names to an HDF5 file with vectors and image_names datasets', 'evaluate ground truth matches against predicted matches and return precision, recall, and rank metrics', 'compute precision, recall, and threshold arrays from binary labels and prediction scores', 'compute the micro average-precision score from sorted recall and precision arrays', 'find the highest recall value at a required precision threshold from precision-recall curves', 'find the rank of each ground truth match within the predicted results for its query']
```

Usage

```
{'create_html_img_embed': 'create an HTML figure with a base64-embedded JPEG thumbnail of an image from a given ID and URI mapping', 'create_html_pair': 'create an HTML table row with side-by-side query and database image thumbnails and a retrieval score', 'create_pairs_html': 'create a full HTML page with a table of image retrieval pairs showing query, database, and score columns', 'review_ImagePair': 'review the ImagePair dataclass that holds query ID, database ID, score, and correctness for image retrieval results', 'refactor_create_html_img_embed': 'refactor create_html_img_embed to support additional image formats or custom thumbnail sizing options'}
```

## File: facebookresearch_isc2021/isc/io.py

Prompts

```
['search query descriptors against a database with a capped total number of results using FAISS', 'match query descriptors to database descriptors and return PredictedMatch objects with scores', 'perform k-nearest-neighbor matching of query descriptors against a database and return predictions', 'read a binary range search result file and return per-query result counts and indices', 'find a radius threshold that reduces inner product search results to a target count', 'create an HTML figure with a base64-embedded JPEG thumbnail of an image from a given ID and URI mapping', 'create an HTML table row with side-by-side query and database image thumbnails and a retrieval score', 'create a full HTML page with a table of image retrieval pairs showing query, database, and score columns', 'review the ImagePair dataclass that holds query ID, database ID, score, and correctness for image retrieval results', 'refactor create_html_img_embed to support additional image formats or custom thumbnail sizing options', 'read a ground truth CSV file with query and database image ID pairs into GroundTruthMatch objects', 'read a predictions CSV file with query ID, database ID, and score into PredictedMatch objects', 'write an iterable of PredictedMatch objects to a CSV file with query, database, and score columns', 'write FAISS nearest neighbor scores and indices arrays to a CSV predictions file with optional nmax and score filtering', 'write image descriptor vectors and image names to an HDF5 file with vectors and image_names datasets', 'evaluate ground truth matches against predicted matches and return precision, recall, and rank metrics', 'compute precision, recall, and threshold arrays from binary labels and prediction scores', 'compute the micro average-precision score from sorted recall and precision arrays', 'find the highest recall value at a required precision threshold from precision-recall curves', 'find the rank of each ground truth match within the predicted results for its query']
```

Usage

```
{'read_ground_truth_csv': 'read a ground truth CSV file with query and database image ID pairs into GroundTruthMatch objects', 'read_predictions_csv': 'read a predictions CSV file with query ID, database ID, and score into PredictedMatch objects', 'write_predictions_csv': 'write an iterable of PredictedMatch objects to a CSV file with query, database, and score columns', 'write_predictions_from_faiss_arrays': 'write FAISS nearest neighbor scores and indices arrays to a CSV predictions file with optional nmax and score filtering', 'write_hdf5_descriptors': 'write image descriptor vectors and image names to an HDF5 file with vectors and image_names datasets'}
```

## File: facebookresearch_isc2021/isc/metrics.py

Prompts

```
['search query descriptors against a database with a capped total number of results using FAISS', 'match query descriptors to database descriptors and return PredictedMatch objects with scores', 'perform k-nearest-neighbor matching of query descriptors against a database and return predictions', 'read a binary range search result file and return per-query result counts and indices', 'find a radius threshold that reduces inner product search results to a target count', 'create an HTML figure with a base64-embedded JPEG thumbnail of an image from a given ID and URI mapping', 'create an HTML table row with side-by-side query and database image thumbnails and a retrieval score', 'create a full HTML page with a table of image retrieval pairs showing query, database, and score columns', 'review the ImagePair dataclass that holds query ID, database ID, score, and correctness for image retrieval results', 'refactor create_html_img_embed to support additional image formats or custom thumbnail sizing options', 'read a ground truth CSV file with query and database image ID pairs into GroundTruthMatch objects', 'read a predictions CSV file with query ID, database ID, and score into PredictedMatch objects', 'write an iterable of PredictedMatch objects to a CSV file with query, database, and score columns', 'write FAISS nearest neighbor scores and indices arrays to a CSV predictions file with optional nmax and score filtering', 'write image descriptor vectors and image names to an HDF5 file with vectors and image_names datasets', 'evaluate ground truth matches against predicted matches and return precision, recall, and rank metrics', 'compute precision, recall, and threshold arrays from binary labels and prediction scores', 'compute the micro average-precision score from sorted recall and precision arrays', 'find the highest recall value at a required precision threshold from precision-recall curves', 'find the rank of each ground truth match within the predicted results for its query']
```

Usage

```
{'evaluate_predictions': 'evaluate ground truth matches against predicted matches and return precision, recall, and rank metrics', 'compute_precision_recall': 'compute precision, recall, and threshold arrays from binary labels and prediction scores', 'compute_average_precision': 'compute the micro average-precision score from sorted recall and precision arrays', 'find_operating_point': 'find the highest recall value at a required precision threshold from precision-recall curves', 'find_tp_ranks': 'find the rank of each ground truth match within the predicted results for its query'}
```

