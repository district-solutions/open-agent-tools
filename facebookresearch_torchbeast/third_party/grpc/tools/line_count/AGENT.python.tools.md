# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/line_count/collect-history.py

Prompts

```
['run the script to bootstrap line count data for each date in a git history range', 'create a generator that yields each date between a start and end date using datetime.timedelta', 'checkout git commits for each date in a range using git rev-list with --before flag', 'run cloc to generate a YAML line count report for each checked-out commit', 'summarize the daterange function which yields dates between a start and end date']
```

Usage

```
{'run_collect_history': 'run the script to bootstrap line count data for each date in a git history range', 'create_daterange_generator': 'create a generator that yields each date between a start and end date using datetime.timedelta', 'checkout_git_commits_by_date': 'checkout git commits for each date in a range using git rev-list with --before flag', 'run_cloc_line_count': 'run cloc to generate a YAML line count report for each checked-out commit', 'summarize_daterange': 'summarize the daterange function which yields dates between a start and end date'}
```

