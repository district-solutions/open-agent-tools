# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/dialogue_bias/agents.py

Prompts

```
['create a NoBiasStyleGenAgent subclass that appends no_bias to every example context', 'override get_temp_history to return STYLE_SEP_TOKEN plus no_bias string', 'review the NoBiasStyleGenAgent class and its get_temp_history override method', 'refactor NoBiasStyleGenAgent to support configurable bias labels instead of hardcoded no_bias', 'test NoBiasStyleGenAgent get_temp_history returns STYLE_SEP_TOKEN plus no_bias for any observation', 'create a function that reads a CSV of names and filters by gender to return a list of names', 'build a module that splits name lists by both race/ethnicity and gender using baby name data', 'create a function that parses 100 years of SSA baby name files and returns counts by gender', 'build a module that loads Tzioumis data and returns name lists for each race/ethnicity category', 'create a function that selects top names for a given race/ethnicity from Tzioumis data and deduplicates']
```

Usage

```
{'create_NoBiasStyleGenAgent': 'create a NoBiasStyleGenAgent subclass that appends no_bias to every example context', 'override_get_temp_history': 'override get_temp_history to return STYLE_SEP_TOKEN plus no_bias string', 'review_NoBiasStyleGenAgent': 'review the NoBiasStyleGenAgent class and its get_temp_history override method', 'refactor_NoBiasStyleGenAgent': 'refactor NoBiasStyleGenAgent to support configurable bias labels instead of hardcoded no_bias', 'test_NoBiasStyleGenAgent': 'test NoBiasStyleGenAgent get_temp_history returns STYLE_SEP_TOKEN plus no_bias for any observation'}
```

## File: facebookresearch_parlai/projects/dialogue_bias/util.py

Prompts

```
['create a NoBiasStyleGenAgent subclass that appends no_bias to every example context', 'override get_temp_history to return STYLE_SEP_TOKEN plus no_bias string', 'review the NoBiasStyleGenAgent class and its get_temp_history override method', 'refactor NoBiasStyleGenAgent to support configurable bias labels instead of hardcoded no_bias', 'test NoBiasStyleGenAgent get_temp_history returns STYLE_SEP_TOKEN plus no_bias for any observation', 'create a function that reads a CSV of names and filters by gender to return a list of names', 'build a module that splits name lists by both race/ethnicity and gender using baby name data', 'create a function that parses 100 years of SSA baby name files and returns counts by gender', 'build a module that loads Tzioumis data and returns name lists for each race/ethnicity category', 'create a function that selects top names for a given race/ethnicity from Tzioumis data and deduplicates']
```

Usage

```
{'get_gender_name_list': 'create a function that reads a CSV of names and filters by gender to return a list of names', 'get_race_ethnicity_gender_name_list': 'build a module that splits name lists by both race/ethnicity and gender using baby name data', 'get_baby_name_counts_by_gender': 'create a function that parses 100 years of SSA baby name files and returns counts by gender', 'get_tzioumis_name_lists': 'build a module that loads Tzioumis data and returns name lists for each race/ethnicity category', 'get_race_ethnicity_name_list_given_tzioumis_data': 'create a function that selects top names for a given race/ethnicity from Tzioumis data and deduplicates'}
```

