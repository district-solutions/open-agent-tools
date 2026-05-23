# Agent Python Tools

- repo: facebookresearch/sscd-copy-detection
- repo_uri: https://github.com/facebookresearch/sscd-copy-detection

## File: facebookresearch_sscd-copy-detection/sscd/datasets/isc/descriptor_matching.py

Prompts

```
['run a capped result search of query descriptors against a database using FAISS', 'run descriptor matching and produce PredictedMatch objects from query and database image descriptors', 'run k-nearest-neighbor descriptor matching and produce PredictedMatch objects with optional GPU acceleration', 'run a reader that parses binary range search result files into numpy arrays', 'run a batch iterator that yields progressively larger batches of query descriptors', 'read a ground truth CSV file containing query and database image ID pairs', 'parse a CSV file with query_id and reference_id columns into GroundTruthMatch objects', 'load ground truth match pairs from a CSV file skipping headers and empty entries', 'review the read_ground_truth function that parses CSV files into GroundTruthMatch lists', 'test the read_ground_truth function with a CSV file containing query and database image IDs', 'evaluate ground truth matches against predicted matches to compute average precision, recall at P90, and rank-based recall metrics', 'compute precision, recall, and threshold arrays from binary labels and prediction scores for copy detection evaluation', 'compute the micro average-precision score from sorted recall and precision arrays for retrieval evaluation', 'find the highest recall value at or above a required precision threshold from precision-recall curves', 'find the rank of each ground truth match in the predicted results list for copy detection queries']
```

Usage

```
{'run_search_with_capped_res': 'run a capped result search of query descriptors against a database using FAISS', 'run_match_and_make_predictions': 'run descriptor matching and produce PredictedMatch objects from query and database image descriptors', 'run_knn_match_and_make_predictions': 'run k-nearest-neighbor descriptor matching and produce PredictedMatch objects with optional GPU acceleration', 'run_range_result_read': 'run a reader that parses binary range search result files into numpy arrays', 'run_query_iterator': 'run a batch iterator that yields progressively larger batches of query descriptors'}
```

## File: facebookresearch_sscd-copy-detection/sscd/datasets/isc/io.py

Prompts

```
['run a capped result search of query descriptors against a database using FAISS', 'run descriptor matching and produce PredictedMatch objects from query and database image descriptors', 'run k-nearest-neighbor descriptor matching and produce PredictedMatch objects with optional GPU acceleration', 'run a reader that parses binary range search result files into numpy arrays', 'run a batch iterator that yields progressively larger batches of query descriptors', 'read a ground truth CSV file containing query and database image ID pairs', 'parse a CSV file with query_id and reference_id columns into GroundTruthMatch objects', 'load ground truth match pairs from a CSV file skipping headers and empty entries', 'review the read_ground_truth function that parses CSV files into GroundTruthMatch lists', 'test the read_ground_truth function with a CSV file containing query and database image IDs', 'evaluate ground truth matches against predicted matches to compute average precision, recall at P90, and rank-based recall metrics', 'compute precision, recall, and threshold arrays from binary labels and prediction scores for copy detection evaluation', 'compute the micro average-precision score from sorted recall and precision arrays for retrieval evaluation', 'find the highest recall value at or above a required precision threshold from precision-recall curves', 'find the rank of each ground truth match in the predicted results list for copy detection queries']
```

Usage

```
{'read_ground_truth_csv': 'read a ground truth CSV file containing query and database image ID pairs', 'parse_ground_truth_pairs': 'parse a CSV file with query_id and reference_id columns into GroundTruthMatch objects', 'load_gt_matches': 'load ground truth match pairs from a CSV file skipping headers and empty entries', 'review_read_ground_truth': 'review the read_ground_truth function that parses CSV files into GroundTruthMatch lists', 'test_read_ground_truth': 'test the read_ground_truth function with a CSV file containing query and database image IDs'}
```

## File: facebookresearch_sscd-copy-detection/sscd/datasets/isc/metrics.py

Prompts

```
['run a capped result search of query descriptors against a database using FAISS', 'run descriptor matching and produce PredictedMatch objects from query and database image descriptors', 'run k-nearest-neighbor descriptor matching and produce PredictedMatch objects with optional GPU acceleration', 'run a reader that parses binary range search result files into numpy arrays', 'run a batch iterator that yields progressively larger batches of query descriptors', 'read a ground truth CSV file containing query and database image ID pairs', 'parse a CSV file with query_id and reference_id columns into GroundTruthMatch objects', 'load ground truth match pairs from a CSV file skipping headers and empty entries', 'review the read_ground_truth function that parses CSV files into GroundTruthMatch lists', 'test the read_ground_truth function with a CSV file containing query and database image IDs', 'evaluate ground truth matches against predicted matches to compute average precision, recall at P90, and rank-based recall metrics', 'compute precision, recall, and threshold arrays from binary labels and prediction scores for copy detection evaluation', 'compute the micro average-precision score from sorted recall and precision arrays for retrieval evaluation', 'find the highest recall value at or above a required precision threshold from precision-recall curves', 'find the rank of each ground truth match in the predicted results list for copy detection queries']
```

Usage

```
{'evaluate_copy_detection_metrics': 'evaluate ground truth matches against predicted matches to compute average precision, recall at P90, and rank-based recall metrics', 'compute_precision_recall_curves': 'compute precision, recall, and threshold arrays from binary labels and prediction scores for copy detection evaluation', 'compute_average_precision': 'compute the micro average-precision score from sorted recall and precision arrays for retrieval evaluation', 'find_operating_point': 'find the highest recall value at or above a required precision threshold from precision-recall curves', 'find_true_positive_ranks': 'find the rank of each ground truth match in the predicted results list for copy detection queries'}
```

