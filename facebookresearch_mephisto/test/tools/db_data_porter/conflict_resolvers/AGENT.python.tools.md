# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/tools/db_data_porter/conflict_resolvers/test_default_merge_conflict_resolver.py

Prompts

```
['test the DefaultMergeConflictResolver class to verify it resolves merge conflicts between database rows and dump rows correctly', 'test resolving project table merge conflicts by picking the earliest creation date between db and dump rows', 'test resolving granted_qualifications merge conflicts by picking the smaller value and earliest creation date', 'test resolving workers table merge conflicts for prolific datastore by picking the larger is_blocked value', 'review the DefaultMergeConflictResolver strategies_config to understand merge resolution rules for mephisto and prolific providers']
```

Usage

```
{'test_default_merge_conflict_resolver': 'test the DefaultMergeConflictResolver class to verify it resolves merge conflicts between database rows and dump rows correctly', 'test_resolve_project_conflicts': 'test resolving project table merge conflicts by picking the earliest creation date between db and dump rows', 'test_resolve_granted_qualifications_conflicts': 'test resolving granted_qualifications merge conflicts by picking the smaller value and earliest creation date', 'test_resolve_workers_conflicts': 'test resolving workers table merge conflicts for prolific datastore by picking the larger is_blocked value', 'review_default_merge_conflict_resolver_strategies': 'review the DefaultMergeConflictResolver strategies_config to understand merge resolution rules for mephisto and prolific providers'}
```

