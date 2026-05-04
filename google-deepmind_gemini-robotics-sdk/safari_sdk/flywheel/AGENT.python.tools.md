# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/flywheel/flywheel_cli.py

Prompts

```
['run the flywheel CLI to train a robotics model with a specified recipe, task id, and date range', 'run the flywheel CLI to serve a trained model via Docker for on-device inference', 'run the flywheel CLI to download training artifacts or Docker images from a completed training job', 'run the flywheel CLI to upload robot demonstration data from a local directory to the ingestion service', 'run the flywheel CLI to list available training data stats by robot, task, and date', 'test the flywheel CLI train command with various training recipes and data filters', 'test the flywheel CLI serve command for gemini robotics v1 and on device v1 recipes', 'test the flywheel CLI download command for training artifacts and docker artifact IDs', 'test the flywheel CLI list training jobs and list serving jobs commands with JSON output', 'test the flywheel CLI data stats command to retrieve and display training data statistics', 'upload all MCAP files from a data directory to the flywheel API endpoint for a robot', 'validate an MCAP file to ensure session messages do not exceed the 1 MiB size limit', 'upload a single MCAP file to the data ingestion service with metadata and multipart encoding', 'rename successfully uploaded MCAP files by appending the .uploaded suffix to track completion', 'retrieve the API key from the safari_sdk auth module to authenticate data upload requests', 'test the upload_data_directory function to upload all .mcap files in a directory and rename them', 'test the _check_session_size function to validate an MCAP file does not exceed the size limit', 'test the _upload_file function to POST a single MCAP file to an API endpoint', 'test the upload_data_directory function handling mixed success and failure responses from the upload API', 'test the upload_data_directory function to skip files already marked with the .uploaded suffix']
```

Usage

```
{'run_flywheel_cli_train': 'run the flywheel CLI to train a robotics model with a specified recipe, task id, and date range', 'run_flywheel_cli_serve': 'run the flywheel CLI to serve a trained model via Docker for on-device inference', 'run_flywheel_cli_download': 'run the flywheel CLI to download training artifacts or Docker images from a completed training job', 'run_flywheel_cli_upload_data': 'run the flywheel CLI to upload robot demonstration data from a local directory to the ingestion service', 'run_flywheel_cli_data_stats': 'run the flywheel CLI to list available training data stats by robot, task, and date'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/flywheel/flywheel_cli_test.py

Prompts

```
['run the flywheel CLI to train a robotics model with a specified recipe, task id, and date range', 'run the flywheel CLI to serve a trained model via Docker for on-device inference', 'run the flywheel CLI to download training artifacts or Docker images from a completed training job', 'run the flywheel CLI to upload robot demonstration data from a local directory to the ingestion service', 'run the flywheel CLI to list available training data stats by robot, task, and date', 'test the flywheel CLI train command with various training recipes and data filters', 'test the flywheel CLI serve command for gemini robotics v1 and on device v1 recipes', 'test the flywheel CLI download command for training artifacts and docker artifact IDs', 'test the flywheel CLI list training jobs and list serving jobs commands with JSON output', 'test the flywheel CLI data stats command to retrieve and display training data statistics', 'upload all MCAP files from a data directory to the flywheel API endpoint for a robot', 'validate an MCAP file to ensure session messages do not exceed the 1 MiB size limit', 'upload a single MCAP file to the data ingestion service with metadata and multipart encoding', 'rename successfully uploaded MCAP files by appending the .uploaded suffix to track completion', 'retrieve the API key from the safari_sdk auth module to authenticate data upload requests', 'test the upload_data_directory function to upload all .mcap files in a directory and rename them', 'test the _check_session_size function to validate an MCAP file does not exceed the size limit', 'test the _upload_file function to POST a single MCAP file to an API endpoint', 'test the upload_data_directory function handling mixed success and failure responses from the upload API', 'test the upload_data_directory function to skip files already marked with the .uploaded suffix']
```

Usage

```
{'test_flywheel_cli_train': 'test the flywheel CLI train command with various training recipes and data filters', 'test_flywheel_cli_serve': 'test the flywheel CLI serve command for gemini robotics v1 and on device v1 recipes', 'test_flywheel_cli_download': 'test the flywheel CLI download command for training artifacts and docker artifact IDs', 'test_flywheel_cli_list_jobs': 'test the flywheel CLI list training jobs and list serving jobs commands with JSON output', 'test_flywheel_cli_data_stats': 'test the flywheel CLI data stats command to retrieve and display training data statistics'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/flywheel/upload_data.py

Prompts

```
['run the flywheel CLI to train a robotics model with a specified recipe, task id, and date range', 'run the flywheel CLI to serve a trained model via Docker for on-device inference', 'run the flywheel CLI to download training artifacts or Docker images from a completed training job', 'run the flywheel CLI to upload robot demonstration data from a local directory to the ingestion service', 'run the flywheel CLI to list available training data stats by robot, task, and date', 'test the flywheel CLI train command with various training recipes and data filters', 'test the flywheel CLI serve command for gemini robotics v1 and on device v1 recipes', 'test the flywheel CLI download command for training artifacts and docker artifact IDs', 'test the flywheel CLI list training jobs and list serving jobs commands with JSON output', 'test the flywheel CLI data stats command to retrieve and display training data statistics', 'upload all MCAP files from a data directory to the flywheel API endpoint for a robot', 'validate an MCAP file to ensure session messages do not exceed the 1 MiB size limit', 'upload a single MCAP file to the data ingestion service with metadata and multipart encoding', 'rename successfully uploaded MCAP files by appending the .uploaded suffix to track completion', 'retrieve the API key from the safari_sdk auth module to authenticate data upload requests', 'test the upload_data_directory function to upload all .mcap files in a directory and rename them', 'test the _check_session_size function to validate an MCAP file does not exceed the size limit', 'test the _upload_file function to POST a single MCAP file to an API endpoint', 'test the upload_data_directory function handling mixed success and failure responses from the upload API', 'test the upload_data_directory function to skip files already marked with the .uploaded suffix']
```

Usage

```
{'upload_mcap_data_directory': 'upload all MCAP files from a data directory to the flywheel API endpoint for a robot', 'check_session_size_validation': 'validate an MCAP file to ensure session messages do not exceed the 1 MiB size limit', 'upload_single_mcap_file': 'upload a single MCAP file to the data ingestion service with metadata and multipart encoding', 'rename_uploaded_mcap_files': 'rename successfully uploaded MCAP files by appending the .uploaded suffix to track completion', 'get_api_key_for_upload': 'retrieve the API key from the safari_sdk auth module to authenticate data upload requests'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/flywheel/upload_data_test.py

Prompts

```
['run the flywheel CLI to train a robotics model with a specified recipe, task id, and date range', 'run the flywheel CLI to serve a trained model via Docker for on-device inference', 'run the flywheel CLI to download training artifacts or Docker images from a completed training job', 'run the flywheel CLI to upload robot demonstration data from a local directory to the ingestion service', 'run the flywheel CLI to list available training data stats by robot, task, and date', 'test the flywheel CLI train command with various training recipes and data filters', 'test the flywheel CLI serve command for gemini robotics v1 and on device v1 recipes', 'test the flywheel CLI download command for training artifacts and docker artifact IDs', 'test the flywheel CLI list training jobs and list serving jobs commands with JSON output', 'test the flywheel CLI data stats command to retrieve and display training data statistics', 'upload all MCAP files from a data directory to the flywheel API endpoint for a robot', 'validate an MCAP file to ensure session messages do not exceed the 1 MiB size limit', 'upload a single MCAP file to the data ingestion service with metadata and multipart encoding', 'rename successfully uploaded MCAP files by appending the .uploaded suffix to track completion', 'retrieve the API key from the safari_sdk auth module to authenticate data upload requests', 'test the upload_data_directory function to upload all .mcap files in a directory and rename them', 'test the _check_session_size function to validate an MCAP file does not exceed the size limit', 'test the _upload_file function to POST a single MCAP file to an API endpoint', 'test the upload_data_directory function handling mixed success and failure responses from the upload API', 'test the upload_data_directory function to skip files already marked with the .uploaded suffix']
```

Usage

```
{'test_upload_data_directory': 'test the upload_data_directory function to upload all .mcap files in a directory and rename them', 'test_check_session_size': 'test the _check_session_size function to validate an MCAP file does not exceed the size limit', 'test_upload_file': 'test the _upload_file function to POST a single MCAP file to an API endpoint', 'test_upload_data_directory_mixed_success_failure': 'test the upload_data_directory function handling mixed success and failure responses from the upload API', 'test_upload_data_directory_already_uploaded': 'test the upload_data_directory function to skip files already marked with the .uploaded suffix'}
```

