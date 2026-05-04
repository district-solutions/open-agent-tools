# Agent Python Tools

- repo: facebookresearch/dci
- repo_uri: https://github.com/facebookresearch/dci

## File: facebookresearch_dci/reproduction/crowdsourcing/annotate/export_data.py

Prompts

```
['run the export_data script to export approved Mephisto task units to the dataset checkpoint location', 'create a function that converts Mephisto-formatted inputs and outputs into a final annotation dict with captions and mask data', 'refactor extract_final_data to merge mask data from outputs into inputs and return structured annotation fields', 'review the main function that queries LocalMephistoDB for approved units and exports images and JSON annotations', 'summarize the export_data script that copies source images and writes formatted annotation JSON files for approved crowdwork units', 'run the main script to collect worker stats and bonus high quality crowdworkers', 'extract mask count, word count, unique words, and duration from Mephisto task data', 'combine short captions, extra captions, and mask labels into a single cleaned word string', 'review the main function worker bonus calculation using target pay rate and cost per unique word', 'refactor extract_stats_data to support additional annotation metrics beyond mask count and word counts', 'run the crowdsourcing annotation task for long captions using mephisto operator and shared static task state', 'build annotation tasks from mask JSON files and images with base64 encoding and area filtering', 'unroll nested mask subgroups into a flat indexed structure with parent and requirement relationships', 'configure a LongCapsConfig dataclass with idx_start, idx_end, and is_pilot fields for task parameters', 'launch a mephisto task run with custom bundle and wait for completion with operator shutdown']
```

Usage

```
{'run_export_data': 'run the export_data script to export approved Mephisto task units to the dataset checkpoint location', 'extract_final_data': 'create a function that converts Mephisto-formatted inputs and outputs into a final annotation dict with captions and mask data', 'refactor_extract_final_data': 'refactor extract_final_data to merge mask data from outputs into inputs and return structured annotation fields', 'review_main': 'review the main function that queries LocalMephistoDB for approved units and exports images and JSON annotations', 'summarize_export_data': 'summarize the export_data script that copies source images and writes formatted annotation JSON files for approved crowdwork units'}
```

## File: facebookresearch_dci/reproduction/crowdsourcing/annotate/get_worker_stats.py

Prompts

```
['run the export_data script to export approved Mephisto task units to the dataset checkpoint location', 'create a function that converts Mephisto-formatted inputs and outputs into a final annotation dict with captions and mask data', 'refactor extract_final_data to merge mask data from outputs into inputs and return structured annotation fields', 'review the main function that queries LocalMephistoDB for approved units and exports images and JSON annotations', 'summarize the export_data script that copies source images and writes formatted annotation JSON files for approved crowdwork units', 'run the main script to collect worker stats and bonus high quality crowdworkers', 'extract mask count, word count, unique words, and duration from Mephisto task data', 'combine short captions, extra captions, and mask labels into a single cleaned word string', 'review the main function worker bonus calculation using target pay rate and cost per unique word', 'refactor extract_stats_data to support additional annotation metrics beyond mask count and word counts', 'run the crowdsourcing annotation task for long captions using mephisto operator and shared static task state', 'build annotation tasks from mask JSON files and images with base64 encoding and area filtering', 'unroll nested mask subgroups into a flat indexed structure with parent and requirement relationships', 'configure a LongCapsConfig dataclass with idx_start, idx_end, and is_pilot fields for task parameters', 'launch a mephisto task run with custom bundle and wait for completion with operator shutdown']
```

Usage

```
{'run_get_worker_stats_main': 'run the main script to collect worker stats and bonus high quality crowdworkers', 'extract_stats_data': 'extract mask count, word count, unique words, and duration from Mephisto task data', 'get_all_words': 'combine short captions, extra captions, and mask labels into a single cleaned word string', 'review_main_worker_bonus_logic': 'review the main function worker bonus calculation using target pay rate and cost per unique word', 'refactor_extract_stats_data': 'refactor extract_stats_data to support additional annotation metrics beyond mask count and word counts'}
```

## File: facebookresearch_dci/reproduction/crowdsourcing/annotate/run_task.py

Prompts

```
['run the export_data script to export approved Mephisto task units to the dataset checkpoint location', 'create a function that converts Mephisto-formatted inputs and outputs into a final annotation dict with captions and mask data', 'refactor extract_final_data to merge mask data from outputs into inputs and return structured annotation fields', 'review the main function that queries LocalMephistoDB for approved units and exports images and JSON annotations', 'summarize the export_data script that copies source images and writes formatted annotation JSON files for approved crowdwork units', 'run the main script to collect worker stats and bonus high quality crowdworkers', 'extract mask count, word count, unique words, and duration from Mephisto task data', 'combine short captions, extra captions, and mask labels into a single cleaned word string', 'review the main function worker bonus calculation using target pay rate and cost per unique word', 'refactor extract_stats_data to support additional annotation metrics beyond mask count and word counts', 'run the crowdsourcing annotation task for long captions using mephisto operator and shared static task state', 'build annotation tasks from mask JSON files and images with base64 encoding and area filtering', 'unroll nested mask subgroups into a flat indexed structure with parent and requirement relationships', 'configure a LongCapsConfig dataclass with idx_start, idx_end, and is_pilot fields for task parameters', 'launch a mephisto task run with custom bundle and wait for completion with operator shutdown']
```

Usage

```
{'run_crowdsourcing_annotation_task': 'run the crowdsourcing annotation task for long captions using mephisto operator and shared static task state', 'build_tasks_from_masks': 'build annotation tasks from mask JSON files and images with base64 encoding and area filtering', 'unroll_mask_hierarchy': 'unroll nested mask subgroups into a flat indexed structure with parent and requirement relationships', 'configure_long_caps_task': 'configure a LongCapsConfig dataclass with idx_start, idx_end, and is_pilot fields for task parameters', 'launch_mephisto_task_run': 'launch a mephisto task run with custom bundle and wait for completion with operator shutdown'}
```

