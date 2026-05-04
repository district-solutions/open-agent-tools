# Agent Python Tools

- repo: facebookresearch/dci
- repo_uri: https://github.com/facebookresearch/dci

## File: facebookresearch_dci/reproduction/densely_captioned_images/repro/reporting/get_all_scores.py

Prompts

```
['extract evaluation scores from a single DCI model evaluation log file and print them as CSV', 'iterate over an eval sweep output directory and extract scores from each subdirectory log file', 'use the FORMAT_STRING parse template to match and extract metrics from DCI evaluation output logs', 'review the extract_numbers function to understand how it parses VG-Relation, VG-Attribution, COCO, Flickr, VLC, Winoground, and Dense Cap scores', 'refactor print_all_scores to accept a directory path argument instead of using interactive input', 'run the script to print CLIP token length statistics for COCO train and valid splits', 'get the total tokens, caption count, average tokens per caption, and image count for a COCO split', 'get and print CLIP token length statistics for both COCO train and valid splits', 'review the get_clip_token_lengths_for_coco_split function that computes token statistics for a COCO annotation split', 'refactor get_clip_token_lengths_for_coco_split to support additional COCO splits or custom annotation paths', 'run the script to compute CLIP token lengths for localized narratives on train and valid splits', 'get CLIP token lengths and caption counts for a specific localized narratives data split', 'summarize token statistics for localized narratives captions filtered by a 76 token threshold', 'review the split mapping logic that converts train/valid to coco_train/coco_val dataset names', 'test the token length filtering that skips captions exceeding 76 tokens in localized narratives', 'run the script to print all elevater scores from a sweep logs directory', 'summarize the elevater scores across models and shot directories from prediction JSON files', 'review the elevater score reporting script that parses prediction JSON files and prints average accuracy', 'test the elevater scores script by providing a directory path with model prediction JSON files', 'refactor the elevater scores script to accept a directory path argument instead of interactive input']
```

Usage

```
{'extract_numbers_from_log': 'extract evaluation scores from a single DCI model evaluation log file and print them as CSV', 'print_all_scores_in_dir': 'iterate over an eval sweep output directory and extract scores from each subdirectory log file', 'parse_FORMAT_STRING_template': 'use the FORMAT_STRING parse template to match and extract metrics from DCI evaluation output logs', 'review_extract_numbers': 'review the extract_numbers function to understand how it parses VG-Relation, VG-Attribution, COCO, Flickr, VLC, Winoground, and Dense Cap scores', 'refactor_print_all_scores': 'refactor print_all_scores to accept a directory path argument instead of using interactive input'}
```

## File: facebookresearch_dci/reproduction/densely_captioned_images/repro/reporting/get_clip_length_for_coco.py

Prompts

```
['extract evaluation scores from a single DCI model evaluation log file and print them as CSV', 'iterate over an eval sweep output directory and extract scores from each subdirectory log file', 'use the FORMAT_STRING parse template to match and extract metrics from DCI evaluation output logs', 'review the extract_numbers function to understand how it parses VG-Relation, VG-Attribution, COCO, Flickr, VLC, Winoground, and Dense Cap scores', 'refactor print_all_scores to accept a directory path argument instead of using interactive input', 'run the script to print CLIP token length statistics for COCO train and valid splits', 'get the total tokens, caption count, average tokens per caption, and image count for a COCO split', 'get and print CLIP token length statistics for both COCO train and valid splits', 'review the get_clip_token_lengths_for_coco_split function that computes token statistics for a COCO annotation split', 'refactor get_clip_token_lengths_for_coco_split to support additional COCO splits or custom annotation paths', 'run the script to compute CLIP token lengths for localized narratives on train and valid splits', 'get CLIP token lengths and caption counts for a specific localized narratives data split', 'summarize token statistics for localized narratives captions filtered by a 76 token threshold', 'review the split mapping logic that converts train/valid to coco_train/coco_val dataset names', 'test the token length filtering that skips captions exceeding 76 tokens in localized narratives', 'run the script to print all elevater scores from a sweep logs directory', 'summarize the elevater scores across models and shot directories from prediction JSON files', 'review the elevater score reporting script that parses prediction JSON files and prints average accuracy', 'test the elevater scores script by providing a directory path with model prediction JSON files', 'refactor the elevater scores script to accept a directory path argument instead of interactive input']
```

Usage

```
{'run_clip_token_lengths_for_coco': 'run the script to print CLIP token length statistics for COCO train and valid splits', 'get_clip_token_lengths_for_coco_split': 'get the total tokens, caption count, average tokens per caption, and image count for a COCO split', 'get_clip_token_lengths_for_coco': 'get and print CLIP token length statistics for both COCO train and valid splits', 'review_get_clip_token_lengths_for_coco_split': 'review the get_clip_token_lengths_for_coco_split function that computes token statistics for a COCO annotation split', 'refactor_get_clip_token_lengths_for_coco_split': 'refactor get_clip_token_lengths_for_coco_split to support additional COCO splits or custom annotation paths'}
```

## File: facebookresearch_dci/reproduction/densely_captioned_images/repro/reporting/get_clip_length_for_localized_narratives.py

Prompts

```
['extract evaluation scores from a single DCI model evaluation log file and print them as CSV', 'iterate over an eval sweep output directory and extract scores from each subdirectory log file', 'use the FORMAT_STRING parse template to match and extract metrics from DCI evaluation output logs', 'review the extract_numbers function to understand how it parses VG-Relation, VG-Attribution, COCO, Flickr, VLC, Winoground, and Dense Cap scores', 'refactor print_all_scores to accept a directory path argument instead of using interactive input', 'run the script to print CLIP token length statistics for COCO train and valid splits', 'get the total tokens, caption count, average tokens per caption, and image count for a COCO split', 'get and print CLIP token length statistics for both COCO train and valid splits', 'review the get_clip_token_lengths_for_coco_split function that computes token statistics for a COCO annotation split', 'refactor get_clip_token_lengths_for_coco_split to support additional COCO splits or custom annotation paths', 'run the script to compute CLIP token lengths for localized narratives on train and valid splits', 'get CLIP token lengths and caption counts for a specific localized narratives data split', 'summarize token statistics for localized narratives captions filtered by a 76 token threshold', 'review the split mapping logic that converts train/valid to coco_train/coco_val dataset names', 'test the token length filtering that skips captions exceeding 76 tokens in localized narratives', 'run the script to print all elevater scores from a sweep logs directory', 'summarize the elevater scores across models and shot directories from prediction JSON files', 'review the elevater score reporting script that parses prediction JSON files and prints average accuracy', 'test the elevater scores script by providing a directory path with model prediction JSON files', 'refactor the elevater scores script to accept a directory path argument instead of interactive input']
```

Usage

```
{'run_clip_token_lengths': 'run the script to compute CLIP token lengths for localized narratives on train and valid splits', 'get_clip_token_lengths_split': 'get CLIP token lengths and caption counts for a specific localized narratives data split', 'summarize_token_stats': 'summarize token statistics for localized narratives captions filtered by a 76 token threshold', 'review_split_mapping': 'review the split mapping logic that converts train/valid to coco_train/coco_val dataset names', 'test_token_filtering': 'test the token length filtering that skips captions exceeding 76 tokens in localized narratives'}
```

## File: facebookresearch_dci/reproduction/densely_captioned_images/repro/reporting/get_elevater_scores.py

Prompts

```
['extract evaluation scores from a single DCI model evaluation log file and print them as CSV', 'iterate over an eval sweep output directory and extract scores from each subdirectory log file', 'use the FORMAT_STRING parse template to match and extract metrics from DCI evaluation output logs', 'review the extract_numbers function to understand how it parses VG-Relation, VG-Attribution, COCO, Flickr, VLC, Winoground, and Dense Cap scores', 'refactor print_all_scores to accept a directory path argument instead of using interactive input', 'run the script to print CLIP token length statistics for COCO train and valid splits', 'get the total tokens, caption count, average tokens per caption, and image count for a COCO split', 'get and print CLIP token length statistics for both COCO train and valid splits', 'review the get_clip_token_lengths_for_coco_split function that computes token statistics for a COCO annotation split', 'refactor get_clip_token_lengths_for_coco_split to support additional COCO splits or custom annotation paths', 'run the script to compute CLIP token lengths for localized narratives on train and valid splits', 'get CLIP token lengths and caption counts for a specific localized narratives data split', 'summarize token statistics for localized narratives captions filtered by a 76 token threshold', 'review the split mapping logic that converts train/valid to coco_train/coco_val dataset names', 'test the token length filtering that skips captions exceeding 76 tokens in localized narratives', 'run the script to print all elevater scores from a sweep logs directory', 'summarize the elevater scores across models and shot directories from prediction JSON files', 'review the elevater score reporting script that parses prediction JSON files and prints average accuracy', 'test the elevater scores script by providing a directory path with model prediction JSON files', 'refactor the elevater scores script to accept a directory path argument instead of interactive input']
```

Usage

```
{'run_print_all_elevater_scores': 'run the script to print all elevater scores from a sweep logs directory', 'summarize_print_all_elevater_scores': 'summarize the elevater scores across models and shot directories from prediction JSON files', 'review_print_all_elevater_scores': 'review the elevater score reporting script that parses prediction JSON files and prints average accuracy', 'test_print_all_elevater_scores': 'test the elevater scores script by providing a directory path with model prediction JSON files', 'refactor_print_all_elevater_scores': 'refactor the elevater scores script to accept a directory path argument instead of interactive input'}
```

