# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/tasks/tests/factories.py

Prompts

```
['create a test Task instance with random text data and a linked project', 'create a test Annotation instance linked to a Task and completed by a user', 'create an Annotation with hypertext labels result containing HTML label annotations', 'create a test Prediction instance linked to a Task with an empty result', 'create a test FailedPrediction instance with random error message and model version', 'test the TestTaskAPI.test_get_task method retrieves a task by ID and validates response fields', 'test the TestTaskAPI.test_patch_task method updates task data via PATCH request and verifies changes', 'test the TestTaskAPI.test_create_task methods validate creating tasks with and without project ID', 'test the TestTaskAPIResolveUri class validates resolve_uri query parameter preserves or converts storage URLs', 'test the TestTaskAgreementAPI class validates the agreement endpoint for annotation distributions across label types', 'test the AnnotationStubSerializer excludes result field and includes is_stub flag', 'test the TaskAPI endpoint returns stub annotations when annotations_stub query parameter is enabled', 'test the single annotation endpoint returns full annotation data with result field', 'test the task agreement endpoint aggregates label annotations and calculates distributions', 'test the agreement endpoint correctly handles taxonomy labels and aggregates leaf nodes', 'test resolving multiple s3:// URIs in a single field using one storage backend', 'test resolving mixed s3:// and gs:// URIs across multiple storage backends', 'test fallback storage resolution when no import storage objects are configured', 'test that fallback storage is not called twice when it matches an import storage object', 'test credential-based file-proxy URL rewriting when task_data_login and task_data_password are set']
```

Usage

```
{'create_task': 'create a test Task instance with random text data and a linked project', 'create_annotation': 'create a test Annotation instance linked to a Task and completed by a user', 'create_hypertextlabels': 'create an Annotation with hypertext labels result containing HTML label annotations', 'create_prediction': 'create a test Prediction instance linked to a Task with an empty result', 'create_failed_prediction': 'create a test FailedPrediction instance with random error message and model version'}
```

## File: HumanSignal_label-studio/label_studio/tasks/tests/test_api.py

Prompts

```
['create a test Task instance with random text data and a linked project', 'create a test Annotation instance linked to a Task and completed by a user', 'create an Annotation with hypertext labels result containing HTML label annotations', 'create a test Prediction instance linked to a Task with an empty result', 'create a test FailedPrediction instance with random error message and model version', 'test the TestTaskAPI.test_get_task method retrieves a task by ID and validates response fields', 'test the TestTaskAPI.test_patch_task method updates task data via PATCH request and verifies changes', 'test the TestTaskAPI.test_create_task methods validate creating tasks with and without project ID', 'test the TestTaskAPIResolveUri class validates resolve_uri query parameter preserves or converts storage URLs', 'test the TestTaskAgreementAPI class validates the agreement endpoint for annotation distributions across label types', 'test the AnnotationStubSerializer excludes result field and includes is_stub flag', 'test the TaskAPI endpoint returns stub annotations when annotations_stub query parameter is enabled', 'test the single annotation endpoint returns full annotation data with result field', 'test the task agreement endpoint aggregates label annotations and calculates distributions', 'test the agreement endpoint correctly handles taxonomy labels and aggregates leaf nodes', 'test resolving multiple s3:// URIs in a single field using one storage backend', 'test resolving mixed s3:// and gs:// URIs across multiple storage backends', 'test fallback storage resolution when no import storage objects are configured', 'test that fallback storage is not called twice when it matches an import storage object', 'test credential-based file-proxy URL rewriting when task_data_login and task_data_password are set']
```

Usage

```
{'test_get_task': 'test the TestTaskAPI.test_get_task method retrieves a task by ID and validates response fields', 'test_patch_task': 'test the TestTaskAPI.test_patch_task method updates task data via PATCH request and verifies changes', 'test_create_task': 'test the TestTaskAPI.test_create_task methods validate creating tasks with and without project ID', 'test_resolve_uri': 'test the TestTaskAPIResolveUri class validates resolve_uri query parameter preserves or converts storage URLs', 'test_task_agreement': 'test the TestTaskAgreementAPI class validates the agreement endpoint for annotation distributions across label types'}
```

## File: HumanSignal_label-studio/label_studio/tasks/tests/test_lazy_load_annotations.py

Prompts

```
['create a test Task instance with random text data and a linked project', 'create a test Annotation instance linked to a Task and completed by a user', 'create an Annotation with hypertext labels result containing HTML label annotations', 'create a test Prediction instance linked to a Task with an empty result', 'create a test FailedPrediction instance with random error message and model version', 'test the TestTaskAPI.test_get_task method retrieves a task by ID and validates response fields', 'test the TestTaskAPI.test_patch_task method updates task data via PATCH request and verifies changes', 'test the TestTaskAPI.test_create_task methods validate creating tasks with and without project ID', 'test the TestTaskAPIResolveUri class validates resolve_uri query parameter preserves or converts storage URLs', 'test the TestTaskAgreementAPI class validates the agreement endpoint for annotation distributions across label types', 'test the AnnotationStubSerializer excludes result field and includes is_stub flag', 'test the TaskAPI endpoint returns stub annotations when annotations_stub query parameter is enabled', 'test the single annotation endpoint returns full annotation data with result field', 'test the task agreement endpoint aggregates label annotations and calculates distributions', 'test the agreement endpoint correctly handles taxonomy labels and aggregates leaf nodes', 'test resolving multiple s3:// URIs in a single field using one storage backend', 'test resolving mixed s3:// and gs:// URIs across multiple storage backends', 'test fallback storage resolution when no import storage objects are configured', 'test that fallback storage is not called twice when it matches an import storage object', 'test credential-based file-proxy URL rewriting when task_data_login and task_data_password are set']
```

Usage

```
{'test_annotation_stub_serializer': 'test the AnnotationStubSerializer excludes result field and includes is_stub flag', 'test_task_api_annotations_stub': 'test the TaskAPI endpoint returns stub annotations when annotations_stub query parameter is enabled', 'test_single_annotation_endpoint': 'test the single annotation endpoint returns full annotation data with result field', 'test_agreement_endpoint': 'test the task agreement endpoint aggregates label annotations and calculates distributions', 'test_agreement_taxonomy': 'test the agreement endpoint correctly handles taxonomy labels and aggregates leaf nodes'}
```

## File: HumanSignal_label-studio/label_studio/tasks/tests/test_models.py

Prompts

```
['create a test Task instance with random text data and a linked project', 'create a test Annotation instance linked to a Task and completed by a user', 'create an Annotation with hypertext labels result containing HTML label annotations', 'create a test Prediction instance linked to a Task with an empty result', 'create a test FailedPrediction instance with random error message and model version', 'test the TestTaskAPI.test_get_task method retrieves a task by ID and validates response fields', 'test the TestTaskAPI.test_patch_task method updates task data via PATCH request and verifies changes', 'test the TestTaskAPI.test_create_task methods validate creating tasks with and without project ID', 'test the TestTaskAPIResolveUri class validates resolve_uri query parameter preserves or converts storage URLs', 'test the TestTaskAgreementAPI class validates the agreement endpoint for annotation distributions across label types', 'test the AnnotationStubSerializer excludes result field and includes is_stub flag', 'test the TaskAPI endpoint returns stub annotations when annotations_stub query parameter is enabled', 'test the single annotation endpoint returns full annotation data with result field', 'test the task agreement endpoint aggregates label annotations and calculates distributions', 'test the agreement endpoint correctly handles taxonomy labels and aggregates leaf nodes', 'test resolving multiple s3:// URIs in a single field using one storage backend', 'test resolving mixed s3:// and gs:// URIs across multiple storage backends', 'test fallback storage resolution when no import storage objects are configured', 'test that fallback storage is not called twice when it matches an import storage object', 'test credential-based file-proxy URL rewriting when task_data_login and task_data_password are set']
```

Usage

```
{'test_resolve_single_field_multiple_uris': 'test resolving multiple s3:// URIs in a single field using one storage backend', 'test_resolve_cross_storage_uris': 'test resolving mixed s3:// and gs:// URIs across multiple storage backends', 'test_resolve_fallback_storage': 'test fallback storage resolution when no import storage objects are configured', 'test_resolve_no_duplicate_fallback': 'test that fallback storage is not called twice when it matches an import storage object', 'test_resolve_credential_proxy': 'test credential-based file-proxy URL rewriting when task_data_login and task_data_password are set'}
```

