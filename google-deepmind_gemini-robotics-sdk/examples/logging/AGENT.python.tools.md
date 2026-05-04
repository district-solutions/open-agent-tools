# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/examples/logging/example_logger_usage.py

Prompts

```
['create an EpisodicLogger with agent_id, task_id, action_spec, and timestep_spec config', 'record robot timesteps and actions to an MCAP file using EpisodicLogger', 'write a complete robotics episode with observations and actions to an MCAP file', 'read back logged timesteps, actions, and policy extra data from an MCAP file', 'define timestep_spec and action_spec for logging robot observations and joint actions', 'test the ExampleLoggerUsageTest to verify example logger writes MCAP files without error', 'test the ExampleLoggerUsageTest to confirm expected number of timesteps and actions in MCAP output', 'run the absltest unit test for the example logger MCAP writing and reading workflow', 'review the ExampleLoggerUsageTest class and its test_example_runs_without_error method for MCAP validation', 'summarize the test_example_runs_without_error method that validates MCAP file creation and proto data counts', 'run the script to convert a LeRobot dataset to MCAP format using --lerobot_dataset_name', 'validate the episode_start_time_ns flag format using the validate_episode_start_time_ns_format function', 'check that dataset_start_time and episode_start_time_ns flags are mutually exclusive', 'validate that max_workers is set to 1 using the _validate_max_workers function', 'run the conversion script with a custom ISO 8601 dataset start time via --dataset_start_time', 'upload an MCAP log file to the Google DeepMind data ingestion service via HTTP POST', 'recursively walk a directory and upload all MCAP files to the data ingestion endpoint', 'build a multipart HTTP request with metadata and file body for Google Cloud upload protocol', 'run the sample data upload script with an agent ID, API key, and data directory', 'review the upload function that constructs multipart requests and calls the data ingestion API']
```

Usage

```
{'create_episodic_logger': 'create an EpisodicLogger with agent_id, task_id, action_spec, and timestep_spec config', 'record_timesteps_and_actions': 'record robot timesteps and actions to an MCAP file using EpisodicLogger', 'write_mcap_episode': 'write a complete robotics episode with observations and actions to an MCAP file', 'read_mcap_proto_data': 'read back logged timesteps, actions, and policy extra data from an MCAP file', 'define_timestep_and_action_specs': 'define timestep_spec and action_spec for logging robot observations and joint actions'}
```

## File: google-deepmind_gemini-robotics-sdk/examples/logging/example_logger_usage_test.py

Prompts

```
['create an EpisodicLogger with agent_id, task_id, action_spec, and timestep_spec config', 'record robot timesteps and actions to an MCAP file using EpisodicLogger', 'write a complete robotics episode with observations and actions to an MCAP file', 'read back logged timesteps, actions, and policy extra data from an MCAP file', 'define timestep_spec and action_spec for logging robot observations and joint actions', 'test the ExampleLoggerUsageTest to verify example logger writes MCAP files without error', 'test the ExampleLoggerUsageTest to confirm expected number of timesteps and actions in MCAP output', 'run the absltest unit test for the example logger MCAP writing and reading workflow', 'review the ExampleLoggerUsageTest class and its test_example_runs_without_error method for MCAP validation', 'summarize the test_example_runs_without_error method that validates MCAP file creation and proto data counts', 'run the script to convert a LeRobot dataset to MCAP format using --lerobot_dataset_name', 'validate the episode_start_time_ns flag format using the validate_episode_start_time_ns_format function', 'check that dataset_start_time and episode_start_time_ns flags are mutually exclusive', 'validate that max_workers is set to 1 using the _validate_max_workers function', 'run the conversion script with a custom ISO 8601 dataset start time via --dataset_start_time', 'upload an MCAP log file to the Google DeepMind data ingestion service via HTTP POST', 'recursively walk a directory and upload all MCAP files to the data ingestion endpoint', 'build a multipart HTTP request with metadata and file body for Google Cloud upload protocol', 'run the sample data upload script with an agent ID, API key, and data directory', 'review the upload function that constructs multipart requests and calls the data ingestion API']
```

Usage

```
{'test_example_logger_runs': 'test the ExampleLoggerUsageTest to verify example logger writes MCAP files without error', 'test_mcap_timestep_count': 'test the ExampleLoggerUsageTest to confirm expected number of timesteps and actions in MCAP output', 'run_example_logger_test': 'run the absltest unit test for the example logger MCAP writing and reading workflow', 'review_ExampleLoggerUsageTest': 'review the ExampleLoggerUsageTest class and its test_example_runs_without_error method for MCAP validation', 'summarize_test_example_runs_without_error': 'summarize the test_example_runs_without_error method that validates MCAP file creation and proto data counts'}
```

## File: google-deepmind_gemini-robotics-sdk/examples/logging/lerobot_data_conversion_script.py

Prompts

```
['create an EpisodicLogger with agent_id, task_id, action_spec, and timestep_spec config', 'record robot timesteps and actions to an MCAP file using EpisodicLogger', 'write a complete robotics episode with observations and actions to an MCAP file', 'read back logged timesteps, actions, and policy extra data from an MCAP file', 'define timestep_spec and action_spec for logging robot observations and joint actions', 'test the ExampleLoggerUsageTest to verify example logger writes MCAP files without error', 'test the ExampleLoggerUsageTest to confirm expected number of timesteps and actions in MCAP output', 'run the absltest unit test for the example logger MCAP writing and reading workflow', 'review the ExampleLoggerUsageTest class and its test_example_runs_without_error method for MCAP validation', 'summarize the test_example_runs_without_error method that validates MCAP file creation and proto data counts', 'run the script to convert a LeRobot dataset to MCAP format using --lerobot_dataset_name', 'validate the episode_start_time_ns flag format using the validate_episode_start_time_ns_format function', 'check that dataset_start_time and episode_start_time_ns flags are mutually exclusive', 'validate that max_workers is set to 1 using the _validate_max_workers function', 'run the conversion script with a custom ISO 8601 dataset start time via --dataset_start_time', 'upload an MCAP log file to the Google DeepMind data ingestion service via HTTP POST', 'recursively walk a directory and upload all MCAP files to the data ingestion endpoint', 'build a multipart HTTP request with metadata and file body for Google Cloud upload protocol', 'run the sample data upload script with an agent ID, API key, and data directory', 'review the upload function that constructs multipart requests and calls the data ingestion API']
```

Usage

```
{'convert_lerobot_to_mcap': 'run the script to convert a LeRobot dataset to MCAP format using --lerobot_dataset_name', 'validate_episode_timestamps': 'validate the episode_start_time_ns flag format using the validate_episode_start_time_ns_format function', 'check_mutually_exclusive_flags': 'check that dataset_start_time and episode_start_time_ns flags are mutually exclusive', 'validate_max_workers': 'validate that max_workers is set to 1 using the _validate_max_workers function', 'run_with_dataset_start_time': 'run the conversion script with a custom ISO 8601 dataset start time via --dataset_start_time'}
```

## File: google-deepmind_gemini-robotics-sdk/examples/logging/sample_data_upload_script.py

Prompts

```
['create an EpisodicLogger with agent_id, task_id, action_spec, and timestep_spec config', 'record robot timesteps and actions to an MCAP file using EpisodicLogger', 'write a complete robotics episode with observations and actions to an MCAP file', 'read back logged timesteps, actions, and policy extra data from an MCAP file', 'define timestep_spec and action_spec for logging robot observations and joint actions', 'test the ExampleLoggerUsageTest to verify example logger writes MCAP files without error', 'test the ExampleLoggerUsageTest to confirm expected number of timesteps and actions in MCAP output', 'run the absltest unit test for the example logger MCAP writing and reading workflow', 'review the ExampleLoggerUsageTest class and its test_example_runs_without_error method for MCAP validation', 'summarize the test_example_runs_without_error method that validates MCAP file creation and proto data counts', 'run the script to convert a LeRobot dataset to MCAP format using --lerobot_dataset_name', 'validate the episode_start_time_ns flag format using the validate_episode_start_time_ns_format function', 'check that dataset_start_time and episode_start_time_ns flags are mutually exclusive', 'validate that max_workers is set to 1 using the _validate_max_workers function', 'run the conversion script with a custom ISO 8601 dataset start time via --dataset_start_time', 'upload an MCAP log file to the Google DeepMind data ingestion service via HTTP POST', 'recursively walk a directory and upload all MCAP files to the data ingestion endpoint', 'build a multipart HTTP request with metadata and file body for Google Cloud upload protocol', 'run the sample data upload script with an agent ID, API key, and data directory', 'review the upload function that constructs multipart requests and calls the data ingestion API']
```

Usage

```
{'upload_mcap_file': 'upload an MCAP log file to the Google DeepMind data ingestion service via HTTP POST', 'walk_and_upload_directory': 'recursively walk a directory and upload all MCAP files to the data ingestion endpoint', 'build_multipart_request': 'build a multipart HTTP request with metadata and file body for Google Cloud upload protocol', 'run_upload_script': 'run the sample data upload script with an agent ID, API key, and data directory', 'review_upload_function': 'review the upload function that constructs multipart requests and calls the data ingestion API'}
```

