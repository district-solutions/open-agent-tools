# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/data_manager/tests/test_api.py

Prompts

```
["test the TaskPagination.sync_paginate_queryset method applies .only('id') optimization to defer heavy field loading", "test the TaskPagination.paginate_totals_queryset method applies .only('id') optimization for aggregate count queries", 'test that Prediction and Annotation count queries use the original queryset instead of the id-only version', "test the TestTaskPaginationMemoryOptimization class validates .only('id') prevents loading multi-megabyte task.data fields during pagination", 'test TaskPagination methods using MagicMock and patch to verify queryset filtering and parent paginate_queryset calls', 'test the core field inclusion logic for fields_for_evaluation, all_fields, and excluded_fields_for_evaluation parameters', 'test that None excluded_fields_for_evaluation is handled correctly as an empty list', 'test that expensive fields like annotations_results and predictions_results are excluded while normal fields are included', 'test annotate_queryset with excluded fields to verify only non-excluded annotation functions are called', 'test that get_queryset accepts and passes excluded_fields_for_evaluation parameter to annotate_queryset']
```

Usage

```
{'test_sync_paginate_queryset_uses_only_id': "test the TaskPagination.sync_paginate_queryset method applies .only('id') optimization to defer heavy field loading", 'test_paginate_totals_queryset_uses_only_id': "test the TaskPagination.paginate_totals_queryset method applies .only('id') optimization for aggregate count queries", 'test_count_queries_use_original_queryset': 'test that Prediction and Annotation count queries use the original queryset instead of the id-only version', 'test_TaskPagination_memory_optimization': "test the TestTaskPaginationMemoryOptimization class validates .only('id') prevents loading multi-megabyte task.data fields during pagination", 'test_TaskPagination_with_mocks': 'test TaskPagination methods using MagicMock and patch to verify queryset filtering and parent paginate_queryset calls'}
```

## File: HumanSignal_label-studio/label_studio/data_manager/tests/test_managers.py

Prompts

```
["test the TaskPagination.sync_paginate_queryset method applies .only('id') optimization to defer heavy field loading", "test the TaskPagination.paginate_totals_queryset method applies .only('id') optimization for aggregate count queries", 'test that Prediction and Annotation count queries use the original queryset instead of the id-only version', "test the TestTaskPaginationMemoryOptimization class validates .only('id') prevents loading multi-megabyte task.data fields during pagination", 'test TaskPagination methods using MagicMock and patch to verify queryset filtering and parent paginate_queryset calls', 'test the core field inclusion logic for fields_for_evaluation, all_fields, and excluded_fields_for_evaluation parameters', 'test that None excluded_fields_for_evaluation is handled correctly as an empty list', 'test that expensive fields like annotations_results and predictions_results are excluded while normal fields are included', 'test annotate_queryset with excluded fields to verify only non-excluded annotation functions are called', 'test that get_queryset accepts and passes excluded_fields_for_evaluation parameter to annotate_queryset']
```

Usage

```
{'test_field_inclusion_logic': 'test the core field inclusion logic for fields_for_evaluation, all_fields, and excluded_fields_for_evaluation parameters', 'test_excluded_fields_none_handling': 'test that None excluded_fields_for_evaluation is handled correctly as an empty list', 'test_performance_optimization_fields': 'test that expensive fields like annotations_results and predictions_results are excluded while normal fields are included', 'test_annotate_queryset_with_simple_functions': 'test annotate_queryset with excluded fields to verify only non-excluded annotation functions are called', 'test_get_queryset_parameter_interface': 'test that get_queryset accepts and passes excluded_fields_for_evaluation parameter to annotate_queryset'}
```

