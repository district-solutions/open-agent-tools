# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/tools/db_data_porter/conflict_resolvers/base_merge_conflict_resolver.py

Prompts

```
['resolve merge conflicts between database rows and dump rows using configurable strategies', 'create a custom conflict resolver class inheriting from BaseMergeConflictResolver with tailored strategies_config', 'use the pick_row_from_db strategy to always prefer existing database rows during merge conflicts', 'pick the row with the earlier creation_date value when resolving merge conflicts between rows', 'merge resolved rows by preserving the database primary key and selecting earliest creation and latest update dates', 'review the ExampleMergeConflictResolver class and its strategies_config for custom merge conflict resolution', 'test the pick_row_from_db_and_set_creation_date_to_y2k method that returns the DB row with creation_date set to year 2000', 'test the concatenate_values method that merges two row field values with a custom separator string', 'refactor the strategies_config dictionary to add new provider types or table-level merge strategies']
```

Usage

```
{'resolve_merge_conflict': 'resolve merge conflicts between database rows and dump rows using configurable strategies', 'create_custom_conflict_resolver': 'create a custom conflict resolver class inheriting from BaseMergeConflictResolver with tailored strategies_config', 'pick_row_from_db_strategy': 'use the pick_row_from_db strategy to always prefer existing database rows during merge conflicts', 'pick_row_with_earlier_value': 'pick the row with the earlier creation_date value when resolving merge conflicts between rows', 'merge_rows_after_resolving': 'merge resolved rows by preserving the database primary key and selecting earliest creation and latest update dates'}
```

## File: facebookresearch_mephisto/mephisto/tools/db_data_porter/conflict_resolvers/example_merge_conflict_resolver.py

Prompts

```
['resolve merge conflicts between database rows and dump rows using configurable strategies', 'create a custom conflict resolver class inheriting from BaseMergeConflictResolver with tailored strategies_config', 'use the pick_row_from_db strategy to always prefer existing database rows during merge conflicts', 'pick the row with the earlier creation_date value when resolving merge conflicts between rows', 'merge resolved rows by preserving the database primary key and selecting earliest creation and latest update dates', 'review the ExampleMergeConflictResolver class and its strategies_config for custom merge conflict resolution', 'test the pick_row_from_db_and_set_creation_date_to_y2k method that returns the DB row with creation_date set to year 2000', 'test the concatenate_values method that merges two row field values with a custom separator string', 'refactor the strategies_config dictionary to add new provider types or table-level merge strategies']
```

Usage

```
{'review_ExampleMergeConflictResolver': 'review the ExampleMergeConflictResolver class and its strategies_config for custom merge conflict resolution', 'create_custom_conflict_resolver': 'create a custom conflict resolver class inheriting from BaseMergeConflictResolver with tailored strategies_config', 'test_pick_row_from_db_and_set_creation_date_to_y2k': 'test the pick_row_from_db_and_set_creation_date_to_y2k method that returns the DB row with creation_date set to year 2000', 'test_concatenate_values': 'test the concatenate_values method that merges two row field values with a custom separator string', 'refactor_strategies_config': 'refactor the strategies_config dictionary to add new provider types or table-level merge strategies'}
```

