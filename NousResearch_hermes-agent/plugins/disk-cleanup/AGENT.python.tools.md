# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/plugins/disk-cleanup/disk_cleanup.py

Prompts

```
['track a file for cleanup by path and category in the disk-cleanup system', 'run deterministic cleanup of tracked test, temp, and cron-output files and remove empty directories', 'run interactive deep cleanup with confirm callable for research, chrome-profile, and large files', 'test which tracked files would be auto-deleted and which need user prompt without touching any files', 'summarize tracked files by category and list the top 10 largest tracked files']
```

Usage

```
{'create_function_track_file': 'track a file for cleanup by path and category in the disk-cleanup system', 'run_function_quick_cleanup': 'run deterministic cleanup of tracked test, temp, and cron-output files and remove empty directories', 'run_function_deep_cleanup': 'run interactive deep cleanup with confirm callable for research, chrome-profile, and large files', 'test_function_dry_run': 'test which tracked files would be auto-deleted and which need user prompt without touching any files', 'summarize_function_status': 'summarize tracked files by category and list the top 10 largest tracked files'}
```

