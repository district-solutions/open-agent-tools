# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/parlai_diplomacy/tasks/sleep_classifier/agents.py

Prompts

```
['build a ParlaI teacher that classifies sleep times from Diplomacy game message history into binned time intervals', 'build a ParlaI teacher that classifies sleep times with multi-recipient support for all alive powers in a phase', "test the cached function that maps time strings like '>50' or 'inf' to classification labels from a bin list", 'review the SleepClassifierChunkTeacher method that parses sleep messages and generates labeled example tuples from game data', 'refactor the SleepSixChunkTeacher method to handle inbound outbound and infinite sleep messages with per-recipient label generation']
```

Usage

```
{'build_sleep_classifier_teacher': 'build a ParlaI teacher that classifies sleep times from Diplomacy game message history into binned time intervals', 'build_sleep_six_chunk_teacher': 'build a ParlaI teacher that classifies sleep times with multi-recipient support for all alive powers in a phase', 'test_get_labels_for_time': "test the cached function that maps time strings like '>50' or 'inf' to classification labels from a bin list", 'review_sleepclassifierchunkteacher_generate_example_tuples': 'review the SleepClassifierChunkTeacher method that parses sleep messages and generates labeled example tuples from game data', 'refactor_sleepsixchunkteacher_generate_example_tuples': 'refactor the SleepSixChunkTeacher method to handle inbound outbound and infinite sleep messages with per-recipient label generation'}
```

