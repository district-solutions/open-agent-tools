# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/failures/detect_new_failures.py

Prompts

```
['run the script to detect new test flakes from BigQuery and report them', 'create GitHub issues for newly detected test failures with assignees and labels', 'search GitHub for preexisting issues matching a test name before creating new ones', 'query BigQuery using SQL to retrieve new test failures within calibration and reporting date ranges', 'output detected test flakes in CSV format with test name, timestamp, and Kokoro URL']
```

Usage

```
{'detect_new_test_failures': 'run the script to detect new test flakes from BigQuery and report them', 'create_github_issues_for_flakes': 'create GitHub issues for newly detected test failures with assignees and labels', 'search_github_issues': 'search GitHub for preexisting issues matching a test name before creating new ones', 'query_bigquery_for_failures': 'query BigQuery using SQL to retrieve new test failures within calibration and reporting date ranges', 'output_flakes_as_csv': 'output detected test flakes in CSV format with test name, timestamp, and Kokoro URL'}
```

