# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/tests/ml/test_api.py

Prompts

```
['test the ML backend API to set a model version for prelabeling on a project', 'test that ML backend is not set for prelabeling when a model version is already assigned', 'test that the project model version updates when an ML backend title is changed', 'test that the project model version resets when an ML backend is deleted', 'test that ML backend password fields are write-only and never returned in API responses', 'test retrieving a single ML prediction on a labeling task via the /api/projects/{id}/next endpoint', 'test retrieving multiple ML predictions on a labeling task via the /api/projects/{id}/next endpoint', 'create a label studio project with a label config and optional ML backend for testing', 'create a labeling task with data payload and associate it with a project for testing', 'register an ML backend by posting to /api/ml/ with project id, title, and url for testing']
```

Usage

```
{'test_ml_backend_set_for_prelabeling': 'test the ML backend API to set a model version for prelabeling on a project', 'test_ml_backend_not_set_for_prelabeling': 'test that ML backend is not set for prelabeling when a model version is already assigned', 'test_model_version_on_save': 'test that the project model version updates when an ML backend title is changed', 'test_model_version_on_delete': 'test that the project model version resets when an ML backend is deleted', 'test_security_write_only_payload': 'test that ML backend password fields are write-only and never returned in API responses'}
```

## File: HumanSignal_label-studio/label_studio/tests/ml/test_predict.py

Prompts

```
['test the ML backend API to set a model version for prelabeling on a project', 'test that ML backend is not set for prelabeling when a model version is already assigned', 'test that the project model version updates when an ML backend title is changed', 'test that the project model version resets when an ML backend is deleted', 'test that ML backend password fields are write-only and never returned in API responses', 'test retrieving a single ML prediction on a labeling task via the /api/projects/{id}/next endpoint', 'test retrieving multiple ML predictions on a labeling task via the /api/projects/{id}/next endpoint', 'create a label studio project with a label config and optional ML backend for testing', 'create a labeling task with data payload and associate it with a project for testing', 'register an ML backend by posting to /api/ml/ with project id, title, and url for testing']
```

Usage

```
{'test_get_single_prediction_on_task': 'test retrieving a single ML prediction on a labeling task via the /api/projects/{id}/next endpoint', 'test_get_multiple_predictions_on_task': 'test retrieving multiple ML predictions on a labeling task via the /api/projects/{id}/next endpoint', 'make_project': 'create a label studio project with a label config and optional ML backend for testing', 'make_task': 'create a labeling task with data payload and associate it with a project for testing', 'ml_backend_registration': 'register an ML backend by posting to /api/ml/ with project id, title, and url for testing'}
```

