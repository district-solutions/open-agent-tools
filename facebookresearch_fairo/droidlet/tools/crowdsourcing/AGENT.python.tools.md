# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/tools/crowdsourcing/sync_whitelists.py

Prompts

```
['run the script to sync Mephisto allowlists and blocklists between the local DB and S3 bucket', 'create a function that downloads allowlist and blocklist text files from an S3 bucket for each task type', 'build a function that adds MTurk workers to Mephisto qualification lists by worker ID', 'create a function that retrieves all qualification worker lists from the local Mephisto database', 'build a function that compares S3 and local qualification lists and returns workers exclusive to each source']
```

Usage

```
{'sync_mephisto_whitelists_from_s3': 'run the script to sync Mephisto allowlists and blocklists between the local DB and S3 bucket', 'import_s3_lists': 'create a function that downloads allowlist and blocklist text files from an S3 bucket for each task type', 'add_workers_to_quals': 'build a function that adds MTurk workers to Mephisto qualification lists by worker ID', 'pull_local_lists': 'create a function that retrieves all qualification worker lists from the local Mephisto database', 'compare_qual_lists': 'build a function that compares S3 and local qualification lists and returns workers exclusive to each source'}
```

