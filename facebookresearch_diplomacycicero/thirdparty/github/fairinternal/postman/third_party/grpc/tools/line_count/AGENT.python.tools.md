# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/line_count/collect-history.py

Prompts

```
['run the script to bootstrap historical line count data by checking out git commits per date and running cloc', 'create a generator that yields each date between a start and end datetime.date using timedelta', 'run git rev-list to find the latest commit before a given date and checkout that commit', 'run cloc with vcs git and by-file options to generate a YAML line count report', 'refactor the daterange function to accept string date formats instead of datetime.date objects']
```

Usage

```
{'run_collect_history': 'run the script to bootstrap historical line count data by checking out git commits per date and running cloc', 'create_daterange_generator': 'create a generator that yields each date between a start and end datetime.date using timedelta', 'run_git_checkout_by_date': 'run git rev-list to find the latest commit before a given date and checkout that commit', 'run_cloc_line_count': 'run cloc with vcs git and by-file options to generate a YAML line count report', 'refactor_daterange': 'refactor the daterange function to accept string date formats instead of datetime.date objects'}
```

