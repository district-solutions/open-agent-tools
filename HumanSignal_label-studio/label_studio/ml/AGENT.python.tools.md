# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/ml/api.py

Prompts

```
['create an ML backend for a Label Studio project by sending a POST request with URL and project ID', 'list all configured ML backends for a specific Label Studio project by project ID', 'update an existing ML backend connection parameters by its ID using a PATCH request', 'start training an ML backend on already-labeled tasks by sending a POST request with the ML backend ID', 'run a test prediction on a random task using an ML backend by providing random=true query parameter', 'build an ML API connector class that handles HTTP requests with retry, timeout, and basic auth to a machine learning backend', 'create an MLApi instance with a URL, timeout, and optional basic auth credentials for communicating with an ML backend', 'run training on an ML backend by sending annotated tasks, label config, and project UID to the train endpoint', 'test ML backend health by sending a GET request to the health endpoint and checking the response status', 'review the MLApi make_predictions method that sends tasks and label config to the predict endpoint for inference', 'review the InteractiveMixin class and its to_representation method', 'summarize the to_representation method of InteractiveMixin', 'refactor the to_representation method to support optional user context', 'test the InteractiveMixin class and its draft serialization behavior', 'review the to_representation method that enriches task data with annotation drafts', 'build an ML backend model to connect a machine learning server URL to a labeling project', 'test the ML backend healthcheck method to verify connectivity to the ML server', 'run the ML backend predict_tasks method to generate predictions for a list of tasks', 'review the ML backend interactive_annotating method for real-time preannotation support', 'summarize the ML backend train method that triggers model training and creates train jobs', 'create an MLBackendSerializer that validates ML backend configuration with basic auth and healthcheck', 'validate an ML backend URL with optional blocking of local IP addresses', 'review the MLInteractiveAnnotatingRequest serializer for task and context validation', 'summarize the MLBackendSerializer authentication validation for basic auth username and password']
```

Usage

```
{'create_ml_backend': 'create an ML backend for a Label Studio project by sending a POST request with URL and project ID', 'list_ml_backends': 'list all configured ML backends for a specific Label Studio project by project ID', 'update_ml_backend': 'update an existing ML backend connection parameters by its ID using a PATCH request', 'train_ml_model': 'start training an ML backend on already-labeled tasks by sending a POST request with the ML backend ID', 'test_ml_prediction': 'run a test prediction on a random task using an ML backend by providing random=true query parameter'}
```

## File: HumanSignal_label-studio/label_studio/ml/api_connector.py

Prompts

```
['create an ML backend for a Label Studio project by sending a POST request with URL and project ID', 'list all configured ML backends for a specific Label Studio project by project ID', 'update an existing ML backend connection parameters by its ID using a PATCH request', 'start training an ML backend on already-labeled tasks by sending a POST request with the ML backend ID', 'run a test prediction on a random task using an ML backend by providing random=true query parameter', 'build an ML API connector class that handles HTTP requests with retry, timeout, and basic auth to a machine learning backend', 'create an MLApi instance with a URL, timeout, and optional basic auth credentials for communicating with an ML backend', 'run training on an ML backend by sending annotated tasks, label config, and project UID to the train endpoint', 'test ML backend health by sending a GET request to the health endpoint and checking the response status', 'review the MLApi make_predictions method that sends tasks and label config to the predict endpoint for inference', 'review the InteractiveMixin class and its to_representation method', 'summarize the to_representation method of InteractiveMixin', 'refactor the to_representation method to support optional user context', 'test the InteractiveMixin class and its draft serialization behavior', 'review the to_representation method that enriches task data with annotation drafts', 'build an ML backend model to connect a machine learning server URL to a labeling project', 'test the ML backend healthcheck method to verify connectivity to the ML server', 'run the ML backend predict_tasks method to generate predictions for a list of tasks', 'review the ML backend interactive_annotating method for real-time preannotation support', 'summarize the ML backend train method that triggers model training and creates train jobs', 'create an MLBackendSerializer that validates ML backend configuration with basic auth and healthcheck', 'validate an ML backend URL with optional blocking of local IP addresses', 'review the MLInteractiveAnnotatingRequest serializer for task and context validation', 'summarize the MLBackendSerializer authentication validation for basic auth username and password']
```

Usage

```
{'build_ml_api_connector': 'build an ML API connector class that handles HTTP requests with retry, timeout, and basic auth to a machine learning backend', 'create_mlapi_instance': 'create an MLApi instance with a URL, timeout, and optional basic auth credentials for communicating with an ML backend', 'run_ml_train': 'run training on an ML backend by sending annotated tasks, label config, and project UID to the train endpoint', 'test_ml_health': 'test ML backend health by sending a GET request to the health endpoint and checking the response status', 'review_mlapi_make_predictions': 'review the MLApi make_predictions method that sends tasks and label config to the predict endpoint for inference'}
```

## File: HumanSignal_label-studio/label_studio/ml/mixins.py

Prompts

```
['create an ML backend for a Label Studio project by sending a POST request with URL and project ID', 'list all configured ML backends for a specific Label Studio project by project ID', 'update an existing ML backend connection parameters by its ID using a PATCH request', 'start training an ML backend on already-labeled tasks by sending a POST request with the ML backend ID', 'run a test prediction on a random task using an ML backend by providing random=true query parameter', 'build an ML API connector class that handles HTTP requests with retry, timeout, and basic auth to a machine learning backend', 'create an MLApi instance with a URL, timeout, and optional basic auth credentials for communicating with an ML backend', 'run training on an ML backend by sending annotated tasks, label config, and project UID to the train endpoint', 'test ML backend health by sending a GET request to the health endpoint and checking the response status', 'review the MLApi make_predictions method that sends tasks and label config to the predict endpoint for inference', 'review the InteractiveMixin class and its to_representation method', 'summarize the to_representation method of InteractiveMixin', 'refactor the to_representation method to support optional user context', 'test the InteractiveMixin class and its draft serialization behavior', 'review the to_representation method that enriches task data with annotation drafts', 'build an ML backend model to connect a machine learning server URL to a labeling project', 'test the ML backend healthcheck method to verify connectivity to the ML server', 'run the ML backend predict_tasks method to generate predictions for a list of tasks', 'review the ML backend interactive_annotating method for real-time preannotation support', 'summarize the ML backend train method that triggers model training and creates train jobs', 'create an MLBackendSerializer that validates ML backend configuration with basic auth and healthcheck', 'validate an ML backend URL with optional blocking of local IP addresses', 'review the MLInteractiveAnnotatingRequest serializer for task and context validation', 'summarize the MLBackendSerializer authentication validation for basic auth username and password']
```

Usage

```
{'review_InteractiveMixin': 'review the InteractiveMixin class and its to_representation method', 'summarize_to_representation': 'summarize the to_representation method of InteractiveMixin', 'refactor_to_representation': 'refactor the to_representation method to support optional user context', 'test_InteractiveMixin': 'test the InteractiveMixin class and its draft serialization behavior', 'review_InteractiveMixin_to_representation': 'review the to_representation method that enriches task data with annotation drafts'}
```

## File: HumanSignal_label-studio/label_studio/ml/models.py

Prompts

```
['create an ML backend for a Label Studio project by sending a POST request with URL and project ID', 'list all configured ML backends for a specific Label Studio project by project ID', 'update an existing ML backend connection parameters by its ID using a PATCH request', 'start training an ML backend on already-labeled tasks by sending a POST request with the ML backend ID', 'run a test prediction on a random task using an ML backend by providing random=true query parameter', 'build an ML API connector class that handles HTTP requests with retry, timeout, and basic auth to a machine learning backend', 'create an MLApi instance with a URL, timeout, and optional basic auth credentials for communicating with an ML backend', 'run training on an ML backend by sending annotated tasks, label config, and project UID to the train endpoint', 'test ML backend health by sending a GET request to the health endpoint and checking the response status', 'review the MLApi make_predictions method that sends tasks and label config to the predict endpoint for inference', 'review the InteractiveMixin class and its to_representation method', 'summarize the to_representation method of InteractiveMixin', 'refactor the to_representation method to support optional user context', 'test the InteractiveMixin class and its draft serialization behavior', 'review the to_representation method that enriches task data with annotation drafts', 'build an ML backend model to connect a machine learning server URL to a labeling project', 'test the ML backend healthcheck method to verify connectivity to the ML server', 'run the ML backend predict_tasks method to generate predictions for a list of tasks', 'review the ML backend interactive_annotating method for real-time preannotation support', 'summarize the ML backend train method that triggers model training and creates train jobs', 'create an MLBackendSerializer that validates ML backend configuration with basic auth and healthcheck', 'validate an ML backend URL with optional blocking of local IP addresses', 'review the MLInteractiveAnnotatingRequest serializer for task and context validation', 'summarize the MLBackendSerializer authentication validation for basic auth username and password']
```

Usage

```
{'build_ml_backend': 'build an ML backend model to connect a machine learning server URL to a labeling project', 'test_ml_backend_healthcheck': 'test the ML backend healthcheck method to verify connectivity to the ML server', 'run_ml_backend_predict_tasks': 'run the ML backend predict_tasks method to generate predictions for a list of tasks', 'review_ml_backend_interactive_annotating': 'review the ML backend interactive_annotating method for real-time preannotation support', 'summarize_ml_backend_train': 'summarize the ML backend train method that triggers model training and creates train jobs'}
```

## File: HumanSignal_label-studio/label_studio/ml/serializers.py

Prompts

```
['create an ML backend for a Label Studio project by sending a POST request with URL and project ID', 'list all configured ML backends for a specific Label Studio project by project ID', 'update an existing ML backend connection parameters by its ID using a PATCH request', 'start training an ML backend on already-labeled tasks by sending a POST request with the ML backend ID', 'run a test prediction on a random task using an ML backend by providing random=true query parameter', 'build an ML API connector class that handles HTTP requests with retry, timeout, and basic auth to a machine learning backend', 'create an MLApi instance with a URL, timeout, and optional basic auth credentials for communicating with an ML backend', 'run training on an ML backend by sending annotated tasks, label config, and project UID to the train endpoint', 'test ML backend health by sending a GET request to the health endpoint and checking the response status', 'review the MLApi make_predictions method that sends tasks and label config to the predict endpoint for inference', 'review the InteractiveMixin class and its to_representation method', 'summarize the to_representation method of InteractiveMixin', 'refactor the to_representation method to support optional user context', 'test the InteractiveMixin class and its draft serialization behavior', 'review the to_representation method that enriches task data with annotation drafts', 'build an ML backend model to connect a machine learning server URL to a labeling project', 'test the ML backend healthcheck method to verify connectivity to the ML server', 'run the ML backend predict_tasks method to generate predictions for a list of tasks', 'review the ML backend interactive_annotating method for real-time preannotation support', 'summarize the ML backend train method that triggers model training and creates train jobs', 'create an MLBackendSerializer that validates ML backend configuration with basic auth and healthcheck', 'validate an ML backend URL with optional blocking of local IP addresses', 'review the MLInteractiveAnnotatingRequest serializer for task and context validation', 'summarize the MLBackendSerializer authentication validation for basic auth username and password']
```

Usage

```
{'create_ml_backend_serializer': 'create an MLBackendSerializer that validates ML backend configuration with basic auth and healthcheck', 'validate_ml_backend_url': 'validate an ML backend URL with optional blocking of local IP addresses', 'test_ml_backend_healthcheck': 'test an ML backend healthcheck with authentication parameters and connection verification', 'review_ml_interactive_annotating_request': 'review the MLInteractiveAnnotatingRequest serializer for task and context validation', 'summarize_ml_backend_authentication': 'summarize the MLBackendSerializer authentication validation for basic auth username and password'}
```

