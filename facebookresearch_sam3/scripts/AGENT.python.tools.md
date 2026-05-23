# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/scripts/extract_odinw_results.py

Prompts

```
['run the script to aggregate ODinW validation results from a results directory', 'run parse_args to configure the argparse CLI with the required res_dir argument', 'run main to process val_stats.json files across 13 ODinW dataset subsets and print average bbox AP', 'review the main function that iterates over VAL13_SET subsets and extracts coco_eval_bbox_AP metrics', 'summarize the VAL13_SET constant listing 13 ODinW benchmark dataset names for evaluation', 'run the script to extract and analyze Roboflow VL100 training results from experiment directories', 'create a function that loads the last row from a JSONL file and extracts specific keys', 'build a function that recursively finds configuration files with a specific filename in a directory tree', 'create a function that extracts specific parameters from a YAML configuration file including computed batch size', 'build a function that extracts bbox AP results for specific categories from experiment log files', 'run the SAM3 speed test script to measure FPS for video propagation with text prompts', 'run the SAM3.1 multiplex speed test with auto-downloaded HuggingFace checkpoints and torch compile', 'create a synthetic video directory with moving colored circles for SAM3 benchmarking', 'run the SAM3 speed test with torch profiling enabled to save performance traces', 'run the SAM3 speed test with torch compile disabled and custom object count and frame settings', 'run the SAM3 qualitative test with text prompt detection and video propagation', 'run the SAM3 qualitative test on a custom video file with a specific text prompt', 'run the SAM3 qualitative test using the SAM3 version instead of SAM3.1', 'create a function that extracts frames from a video file and saves them as JPEG images', 'build a synthetic video with moving colored circles for testing SAM3 object detection']
```

Usage

```
{'run_extract_odinw_results': 'run the script to aggregate ODinW validation results from a results directory', 'run_parse_args': 'run parse_args to configure the argparse CLI with the required res_dir argument', 'run_main': 'run main to process val_stats.json files across 13 ODinW dataset subsets and print average bbox AP', 'review_main': 'review the main function that iterates over VAL13_SET subsets and extracts coco_eval_bbox_AP metrics', 'summarize_VAL13_SET': 'summarize the VAL13_SET constant listing 13 ODinW benchmark dataset names for evaluation'}
```

## File: facebookresearch_sam3/scripts/extract_roboflow_vl100_results.py

Prompts

```
['run the script to aggregate ODinW validation results from a results directory', 'run parse_args to configure the argparse CLI with the required res_dir argument', 'run main to process val_stats.json files across 13 ODinW dataset subsets and print average bbox AP', 'review the main function that iterates over VAL13_SET subsets and extracts coco_eval_bbox_AP metrics', 'summarize the VAL13_SET constant listing 13 ODinW benchmark dataset names for evaluation', 'run the script to extract and analyze Roboflow VL100 training results from experiment directories', 'create a function that loads the last row from a JSONL file and extracts specific keys', 'build a function that recursively finds configuration files with a specific filename in a directory tree', 'create a function that extracts specific parameters from a YAML configuration file including computed batch size', 'build a function that extracts bbox AP results for specific categories from experiment log files', 'run the SAM3 speed test script to measure FPS for video propagation with text prompts', 'run the SAM3.1 multiplex speed test with auto-downloaded HuggingFace checkpoints and torch compile', 'create a synthetic video directory with moving colored circles for SAM3 benchmarking', 'run the SAM3 speed test with torch profiling enabled to save performance traces', 'run the SAM3 speed test with torch compile disabled and custom object count and frame settings', 'run the SAM3 qualitative test with text prompt detection and video propagation', 'run the SAM3 qualitative test on a custom video file with a specific text prompt', 'run the SAM3 qualitative test using the SAM3 version instead of SAM3.1', 'create a function that extracts frames from a video file and saves them as JPEG images', 'build a synthetic video with moving colored circles for testing SAM3 object detection']
```

Usage

```
{'extract_roboflow_vl100_results': 'run the script to extract and analyze Roboflow VL100 training results from experiment directories', 'load_jsonl_last_row': 'create a function that loads the last row from a JSONL file and extracts specific keys', 'find_config_files': 'build a function that recursively finds configuration files with a specific filename in a directory tree', 'extract_config_parameters': 'create a function that extracts specific parameters from a YAML configuration file including computed batch size', 'extract_category_results': 'build a function that extracts bbox AP results for specific categories from experiment log files'}
```

## File: facebookresearch_sam3/scripts/measure_speed.py

Prompts

```
['run the script to aggregate ODinW validation results from a results directory', 'run parse_args to configure the argparse CLI with the required res_dir argument', 'run main to process val_stats.json files across 13 ODinW dataset subsets and print average bbox AP', 'review the main function that iterates over VAL13_SET subsets and extracts coco_eval_bbox_AP metrics', 'summarize the VAL13_SET constant listing 13 ODinW benchmark dataset names for evaluation', 'run the script to extract and analyze Roboflow VL100 training results from experiment directories', 'create a function that loads the last row from a JSONL file and extracts specific keys', 'build a function that recursively finds configuration files with a specific filename in a directory tree', 'create a function that extracts specific parameters from a YAML configuration file including computed batch size', 'build a function that extracts bbox AP results for specific categories from experiment log files', 'run the SAM3 speed test script to measure FPS for video propagation with text prompts', 'run the SAM3.1 multiplex speed test with auto-downloaded HuggingFace checkpoints and torch compile', 'create a synthetic video directory with moving colored circles for SAM3 benchmarking', 'run the SAM3 speed test with torch profiling enabled to save performance traces', 'run the SAM3 speed test with torch compile disabled and custom object count and frame settings', 'run the SAM3 qualitative test with text prompt detection and video propagation', 'run the SAM3 qualitative test on a custom video file with a specific text prompt', 'run the SAM3 qualitative test using the SAM3 version instead of SAM3.1', 'create a function that extracts frames from a video file and saves them as JPEG images', 'build a synthetic video with moving colored circles for testing SAM3 object detection']
```

Usage

```
{'run_speed_test_sam3': 'run the SAM3 speed test script to measure FPS for video propagation with text prompts', 'run_speed_test_sam3_1': 'run the SAM3.1 multiplex speed test with auto-downloaded HuggingFace checkpoints and torch compile', 'synthesize_video_data': 'create a synthetic video directory with moving colored circles for SAM3 benchmarking', 'run_profiling': 'run the SAM3 speed test with torch profiling enabled to save performance traces', 'run_test_no_compile': 'run the SAM3 speed test with torch compile disabled and custom object count and frame settings'}
```

## File: facebookresearch_sam3/scripts/qualitative_test.py

Prompts

```
['run the script to aggregate ODinW validation results from a results directory', 'run parse_args to configure the argparse CLI with the required res_dir argument', 'run main to process val_stats.json files across 13 ODinW dataset subsets and print average bbox AP', 'review the main function that iterates over VAL13_SET subsets and extracts coco_eval_bbox_AP metrics', 'summarize the VAL13_SET constant listing 13 ODinW benchmark dataset names for evaluation', 'run the script to extract and analyze Roboflow VL100 training results from experiment directories', 'create a function that loads the last row from a JSONL file and extracts specific keys', 'build a function that recursively finds configuration files with a specific filename in a directory tree', 'create a function that extracts specific parameters from a YAML configuration file including computed batch size', 'build a function that extracts bbox AP results for specific categories from experiment log files', 'run the SAM3 speed test script to measure FPS for video propagation with text prompts', 'run the SAM3.1 multiplex speed test with auto-downloaded HuggingFace checkpoints and torch compile', 'create a synthetic video directory with moving colored circles for SAM3 benchmarking', 'run the SAM3 speed test with torch profiling enabled to save performance traces', 'run the SAM3 speed test with torch compile disabled and custom object count and frame settings', 'run the SAM3 qualitative test with text prompt detection and video propagation', 'run the SAM3 qualitative test on a custom video file with a specific text prompt', 'run the SAM3 qualitative test using the SAM3 version instead of SAM3.1', 'create a function that extracts frames from a video file and saves them as JPEG images', 'build a synthetic video with moving colored circles for testing SAM3 object detection']
```

Usage

```
{'run_qualitative_test': 'run the SAM3 qualitative test with text prompt detection and video propagation', 'run_qualitative_test_with_video': 'run the SAM3 qualitative test on a custom video file with a specific text prompt', 'run_qualitative_test_sam3': 'run the SAM3 qualitative test using the SAM3 version instead of SAM3.1', 'extract_frames': 'create a function that extracts frames from a video file and saves them as JPEG images', 'synthesize_video': 'build a synthetic video with moving colored circles for testing SAM3 object detection'}
```

