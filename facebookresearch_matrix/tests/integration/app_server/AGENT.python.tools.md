# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/tests/integration/app_server/test_concurrent_deployment.py

Prompts

```
['test concurrent application add and remove operations using multiprocessing with ProcessPoolExecutor', 'perform multiple deploy and remove cycles for applications with unique names per worker', 'wait for an application to reach RUNNING state with a configurable timeout', 'wait for an application to be removed from the cluster', 'start and stop a Ray cluster for the duration of integration tests', 'test deploying a hello application on a Matrix cluster and verify it reaches success status', 'create a pytest fixture that starts a Matrix CLI cluster with one worker and no GPUs', 'run the Matrix CLI to deploy a named application with a specified app type', 'check the deployment status and health of a Matrix application using app_status and check_health', 'review the status_is_pending and status_is_success utility functions for checking Ray task status', 'encode an image or video file to a base64 data URL string with proper MIME type', 'run batch inference with text-only prompts against a deployed Qwen3-VL model and verify responses', 'run batch inference with image inputs using OpenAI style image_url content and verify receipt keywords', 'run batch inference with video inputs using OpenAI style video_url content and verify video keywords', 'deploy a Qwen3-VL model cluster with four replicas and load test media files as base64']
```

Usage

```
{'test_concurrent_add_remove_multiprocessing': 'test concurrent application add and remove operations using multiprocessing with ProcessPoolExecutor', 'deploy_and_remove_cycle': 'perform multiple deploy and remove cycles for applications with unique names per worker', 'wait_for_running': 'wait for an application to reach RUNNING state with a configurable timeout', 'wait_for_removal': 'wait for an application to be removed from the cluster', 'matrix_cluster_fixture': 'start and stop a Ray cluster for the duration of integration tests'}
```

## File: facebookresearch_matrix/tests/integration/app_server/test_deploy_hello.py

Prompts

```
['test concurrent application add and remove operations using multiprocessing with ProcessPoolExecutor', 'perform multiple deploy and remove cycles for applications with unique names per worker', 'wait for an application to reach RUNNING state with a configurable timeout', 'wait for an application to be removed from the cluster', 'start and stop a Ray cluster for the duration of integration tests', 'test deploying a hello application on a Matrix cluster and verify it reaches success status', 'create a pytest fixture that starts a Matrix CLI cluster with one worker and no GPUs', 'run the Matrix CLI to deploy a named application with a specified app type', 'check the deployment status and health of a Matrix application using app_status and check_health', 'review the status_is_pending and status_is_success utility functions for checking Ray task status', 'encode an image or video file to a base64 data URL string with proper MIME type', 'run batch inference with text-only prompts against a deployed Qwen3-VL model and verify responses', 'run batch inference with image inputs using OpenAI style image_url content and verify receipt keywords', 'run batch inference with video inputs using OpenAI style video_url content and verify video keywords', 'deploy a Qwen3-VL model cluster with four replicas and load test media files as base64']
```

Usage

```
{'test_deploy_hello_app': 'test deploying a hello application on a Matrix cluster and verify it reaches success status', 'create_matrix_cluster_fixture': 'create a pytest fixture that starts a Matrix CLI cluster with one worker and no GPUs', 'run_cli_deploy_applications': 'run the Matrix CLI to deploy a named application with a specified app type', 'check_app_status_and_health': 'check the deployment status and health of a Matrix application using app_status and check_health', 'review_status_utility_functions': 'review the status_is_pending and status_is_success utility functions for checking Ray task status'}
```

## File: facebookresearch_matrix/tests/integration/app_server/test_qwen3vl_batch_generate.py

Prompts

```
['test concurrent application add and remove operations using multiprocessing with ProcessPoolExecutor', 'perform multiple deploy and remove cycles for applications with unique names per worker', 'wait for an application to reach RUNNING state with a configurable timeout', 'wait for an application to be removed from the cluster', 'start and stop a Ray cluster for the duration of integration tests', 'test deploying a hello application on a Matrix cluster and verify it reaches success status', 'create a pytest fixture that starts a Matrix CLI cluster with one worker and no GPUs', 'run the Matrix CLI to deploy a named application with a specified app type', 'check the deployment status and health of a Matrix application using app_status and check_health', 'review the status_is_pending and status_is_success utility functions for checking Ray task status', 'encode an image or video file to a base64 data URL string with proper MIME type', 'run batch inference with text-only prompts against a deployed Qwen3-VL model and verify responses', 'run batch inference with image inputs using OpenAI style image_url content and verify receipt keywords', 'run batch inference with video inputs using OpenAI style video_url content and verify video keywords', 'deploy a Qwen3-VL model cluster with four replicas and load test media files as base64']
```

Usage

```
{'encode_file_to_base64': 'encode an image or video file to a base64 data URL string with proper MIME type', 'test_batch_generate_text': 'run batch inference with text-only prompts against a deployed Qwen3-VL model and verify responses', 'test_batch_generate_images_openai_style': 'run batch inference with image inputs using OpenAI style image_url content and verify receipt keywords', 'test_batch_generate_videos_openai_style': 'run batch inference with video inputs using OpenAI style video_url content and verify video keywords', 'qwen3vl_cluster_fixture': 'deploy a Qwen3-VL model cluster with four replicas and load test media files as base64'}
```

