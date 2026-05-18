# Agent Python Tools

- repo: facebookresearch/mmbt
- repo_uri: https://github.com/facebookresearch/mmbt

## File: facebookresearch_mmbt/scripts/food_101.py

Prompts

```
['run the food101 dataset formatter on a given dataset root path directory', 'run the food101 script via command line with a dataset root path argument', 'create a function that sanitizes text by removing special characters and collapsing whitespace', 'parse the food101 dataset directory structure and extract image text label tuples', 'save parsed dataset splits to JSONL files in the target directory', 'run the script to format the MMIMDB dataset from a given root path into JSONL split files', 'create train, validation, and test JSONL split files from the MMIMDB dataset directory', 'filter out samples with the News genre label when formatting the MMIMDB dataset', 'select the longest plot summary for each movie sample using numpy argmax on plot lengths', 'review the format_mmimdb_dataset function that converts MMIMDB JSON files into structured JSONL split files', 'run the CLI script to create test_hard_gt.jsonl from test.jsonl using hard ground truth IDs', 'run get_hard_gt to filter test.jsonl entries by hard ground truth IDs for a task', 'run get_args to configure argparse with task, path, and hard_gt_ids arguments', 'run cli_main to parse CLI arguments and generate the filtered hard ground truth JSONL file', 'run the script to filter mmimdb or food101 test data by hard ground truth IDs']
```

Usage

```
{'run_format_food101_dataset': 'run the food101 dataset formatter on a given dataset root path directory', 'run_cli_food101': 'run the food101 script via command line with a dataset root path argument', 'create_format_txt_file': 'create a function that sanitizes text by removing special characters and collapsing whitespace', 'parse_food101_data': 'parse the food101 dataset directory structure and extract image text label tuples', 'save_data_to_jsonl': 'save parsed dataset splits to JSONL files in the target directory'}
```

## File: facebookresearch_mmbt/scripts/mmimdb.py

Prompts

```
['run the food101 dataset formatter on a given dataset root path directory', 'run the food101 script via command line with a dataset root path argument', 'create a function that sanitizes text by removing special characters and collapsing whitespace', 'parse the food101 dataset directory structure and extract image text label tuples', 'save parsed dataset splits to JSONL files in the target directory', 'run the script to format the MMIMDB dataset from a given root path into JSONL split files', 'create train, validation, and test JSONL split files from the MMIMDB dataset directory', 'filter out samples with the News genre label when formatting the MMIMDB dataset', 'select the longest plot summary for each movie sample using numpy argmax on plot lengths', 'review the format_mmimdb_dataset function that converts MMIMDB JSON files into structured JSONL split files', 'run the CLI script to create test_hard_gt.jsonl from test.jsonl using hard ground truth IDs', 'run get_hard_gt to filter test.jsonl entries by hard ground truth IDs for a task', 'run get_args to configure argparse with task, path, and hard_gt_ids arguments', 'run cli_main to parse CLI arguments and generate the filtered hard ground truth JSONL file', 'run the script to filter mmimdb or food101 test data by hard ground truth IDs']
```

Usage

```
{'run_format_mmimdb_dataset': 'run the script to format the MMIMDB dataset from a given root path into JSONL split files', 'create_jsonl_splits': 'create train, validation, and test JSONL split files from the MMIMDB dataset directory', 'filter_news_genre': 'filter out samples with the News genre label when formatting the MMIMDB dataset', 'select_longest_plot': 'select the longest plot summary for each movie sample using numpy argmax on plot lengths', 'review_format_mmimdb_dataset': 'review the format_mmimdb_dataset function that converts MMIMDB JSON files into structured JSONL split files'}
```

## File: facebookresearch_mmbt/scripts/test_hard_gt.py

Prompts

```
['run the food101 dataset formatter on a given dataset root path directory', 'run the food101 script via command line with a dataset root path argument', 'create a function that sanitizes text by removing special characters and collapsing whitespace', 'parse the food101 dataset directory structure and extract image text label tuples', 'save parsed dataset splits to JSONL files in the target directory', 'run the script to format the MMIMDB dataset from a given root path into JSONL split files', 'create train, validation, and test JSONL split files from the MMIMDB dataset directory', 'filter out samples with the News genre label when formatting the MMIMDB dataset', 'select the longest plot summary for each movie sample using numpy argmax on plot lengths', 'review the format_mmimdb_dataset function that converts MMIMDB JSON files into structured JSONL split files', 'run the CLI script to create test_hard_gt.jsonl from test.jsonl using hard ground truth IDs', 'run get_hard_gt to filter test.jsonl entries by hard ground truth IDs for a task', 'run get_args to configure argparse with task, path, and hard_gt_ids arguments', 'run cli_main to parse CLI arguments and generate the filtered hard ground truth JSONL file', 'run the script to filter mmimdb or food101 test data by hard ground truth IDs']
```

Usage

```
{'run_test_hard_gt_cli': 'run the CLI script to create test_hard_gt.jsonl from test.jsonl using hard ground truth IDs', 'run_get_hard_gt': 'run get_hard_gt to filter test.jsonl entries by hard ground truth IDs for a task', 'run_get_args': 'run get_args to configure argparse with task, path, and hard_gt_ids arguments', 'run_cli_main': 'run cli_main to parse CLI arguments and generate the filtered hard ground truth JSONL file', 'run_test_hard_gt_filter': 'run the script to filter mmimdb or food101 test data by hard ground truth IDs'}
```

