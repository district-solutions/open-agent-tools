# Agent Python Tools

- repo: huggingface/ai-deadlines
- repo_uri: https://github.com/huggingface/ai-deadlines

## File: huggingface_ai-deadlines/.github/scripts/update_conferences.py

Prompts

```
['fetch all conference YAML files from the ccfddl GitHub repository and parse them', 'parse a date range string into start and end dates in YYYY-MM-DD format', 'transform ccfddl conference data format into a standardized conference dictionary format', 'run the main script to fetch new conferences and update the conferences YAML file', 'merge new conference data with existing conferences while preserving custom fields and avoiding duplicates', 'load all current conferences from individual YAML files in the conferences directory', 'update the TypeScript conference loader file with imports for all conference YAML files']
```

Usage

```
{'fetch_conference_yaml_files': 'fetch all conference YAML files from the ccfddl GitHub repository and parse them', 'parse_date_range': 'parse a date range string into start and end dates in YYYY-MM-DD format', 'transform_conference_data': 'transform ccfddl conference data format into a standardized conference dictionary format', 'update_conferences_main': 'run the main script to fetch new conferences and update the conferences YAML file', 'merge_conferences': 'merge new conference data with existing conferences while preserving custom fields and avoiding duplicates'}
```

## File: huggingface_ai-deadlines/.github/scripts/update_conferences_new.py

Prompts

```
['fetch all conference YAML files from the ccfddl GitHub repository and parse them', 'parse a date range string into start and end dates in YYYY-MM-DD format', 'transform ccfddl conference data format into a standardized conference dictionary format', 'run the main script to fetch new conferences and update the conferences YAML file', 'merge new conference data with existing conferences while preserving custom fields and avoiding duplicates', 'load all current conferences from individual YAML files in the conferences directory', 'update the TypeScript conference loader file with imports for all conference YAML files']
```

Usage

```
{'fetch_conference_yaml_files': 'fetch all conference YAML files from the ccfddl GitHub repository and parse them', 'parse_date_range': 'parse a date range string with various formats into start and end dates', 'transform_conference_data': "transform ccfddl conference format data into the project's internal conference format", 'load_current_conferences': 'load all current conferences from individual YAML files in the conferences directory', 'update_conference_loader': 'update the TypeScript conference loader file with imports for all conference YAML files'}
```

