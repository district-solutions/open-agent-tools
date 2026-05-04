# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/orchestrator/example_client_sdk_integration.py

Prompts

```
['run a mock evaluation loop that requests work units and executes episodes via the orchestrator client SDK', 'connect an OrchestratorHelper client to the orchestrator service using a robot ID and job type', 'request the next work unit from the orchestrator client and check for available robot jobs', 'complete a work unit by reporting outcome, success score, session timestamps, and questionnaire responses', 'create visual overlays for the current work unit and render them with camera images as PIL images', 'run the orchestrator client SDK in observer mode with a robot ID flag', 'connect an OrchestratorHelper client in observer mode and read robot release configs', 'call observe_latest_work_unit to fetch and inspect the latest work unit data', 'print detailed work unit info including scene details, policy, and success scores', 'disconnect the orchestrator client after completing the observer mode loop', 'run the orchestrator example to get robot info and set operator ID using --robot_id flag', 'call get_current_robot_info on the orchestrator client to retrieve the robot ID, operator ID, and work unit stage', 'call set_current_robot_operator_id on the orchestrator client to set or clear the operator ID for a robot', 'use _print_robot_info_response to display robot ID, operational status, operator ID, job ID, and release configs', 'run the example client to connect to orchestrator and upload a mock log file artifact', 'review the main function that initializes the orchestrator client, runs the eval loop, and disconnects', 'refactor the run_mock_eval_loop function to handle additional response fields from the orchestrator client']
```

Usage

```
{'run_mock_eval_loop': 'run a mock evaluation loop that requests work units and executes episodes via the orchestrator client SDK', 'connect_orchestrator_client': 'connect an OrchestratorHelper client to the orchestrator service using a robot ID and job type', 'request_work_unit': 'request the next work unit from the orchestrator client and check for available robot jobs', 'complete_work_unit': 'complete a work unit by reporting outcome, success score, session timestamps, and questionnaire responses', 'create_visual_overlays': 'create visual overlays for the current work unit and render them with camera images as PIL images'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/orchestrator/example_client_sdk_observer_mode.py

Prompts

```
['run a mock evaluation loop that requests work units and executes episodes via the orchestrator client SDK', 'connect an OrchestratorHelper client to the orchestrator service using a robot ID and job type', 'request the next work unit from the orchestrator client and check for available robot jobs', 'complete a work unit by reporting outcome, success score, session timestamps, and questionnaire responses', 'create visual overlays for the current work unit and render them with camera images as PIL images', 'run the orchestrator client SDK in observer mode with a robot ID flag', 'connect an OrchestratorHelper client in observer mode and read robot release configs', 'call observe_latest_work_unit to fetch and inspect the latest work unit data', 'print detailed work unit info including scene details, policy, and success scores', 'disconnect the orchestrator client after completing the observer mode loop', 'run the orchestrator example to get robot info and set operator ID using --robot_id flag', 'call get_current_robot_info on the orchestrator client to retrieve the robot ID, operator ID, and work unit stage', 'call set_current_robot_operator_id on the orchestrator client to set or clear the operator ID for a robot', 'use _print_robot_info_response to display robot ID, operational status, operator ID, job ID, and release configs', 'run the example client to connect to orchestrator and upload a mock log file artifact', 'review the main function that initializes the orchestrator client, runs the eval loop, and disconnects', 'refactor the run_mock_eval_loop function to handle additional response fields from the orchestrator client']
```

Usage

```
{'run_observer_mode_client': 'run the orchestrator client SDK in observer mode with a robot ID flag', 'connect_orchestrator_helper': 'connect an OrchestratorHelper client in observer mode and read robot release configs', 'observe_latest_work_unit': 'call observe_latest_work_unit to fetch and inspect the latest work unit data', 'print_work_unit_info': 'print detailed work unit info including scene details, policy, and success scores', 'disconnect_orchestrator_client': 'disconnect the orchestrator client after completing the observer mode loop'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/orchestrator/example_client_sdk_robot_and_operator_info.py

Prompts

```
['run a mock evaluation loop that requests work units and executes episodes via the orchestrator client SDK', 'connect an OrchestratorHelper client to the orchestrator service using a robot ID and job type', 'request the next work unit from the orchestrator client and check for available robot jobs', 'complete a work unit by reporting outcome, success score, session timestamps, and questionnaire responses', 'create visual overlays for the current work unit and render them with camera images as PIL images', 'run the orchestrator client SDK in observer mode with a robot ID flag', 'connect an OrchestratorHelper client in observer mode and read robot release configs', 'call observe_latest_work_unit to fetch and inspect the latest work unit data', 'print detailed work unit info including scene details, policy, and success scores', 'disconnect the orchestrator client after completing the observer mode loop', 'run the orchestrator example to get robot info and set operator ID using --robot_id flag', 'call get_current_robot_info on the orchestrator client to retrieve the robot ID, operator ID, and work unit stage', 'call set_current_robot_operator_id on the orchestrator client to set or clear the operator ID for a robot', 'use _print_robot_info_response to display robot ID, operational status, operator ID, job ID, and release configs', 'run the example client to connect to orchestrator and upload a mock log file artifact', 'review the main function that initializes the orchestrator client, runs the eval loop, and disconnects', 'refactor the run_mock_eval_loop function to handle additional response fields from the orchestrator client']
```

Usage

```
{'run_orchestrator_robot_info_example': 'run the orchestrator example to get robot info and set operator ID using --robot_id flag', 'get_current_robot_info': 'call get_current_robot_info on the orchestrator client to retrieve the robot ID, operator ID, and work unit stage', 'set_current_robot_operator_id': 'call set_current_robot_operator_id on the orchestrator client to set or clear the operator ID for a robot', 'connect_orchestrator_helper': 'initialize an OrchestratorHelper with robot_id and job_type then call connect to start the session', 'print_robot_info_response': 'use _print_robot_info_response to display robot ID, operational status, operator ID, job ID, and release configs'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/orchestrator/example_client_sdk_upload_log_file.py

Prompts

```
['run a mock evaluation loop that requests work units and executes episodes via the orchestrator client SDK', 'connect an OrchestratorHelper client to the orchestrator service using a robot ID and job type', 'request the next work unit from the orchestrator client and check for available robot jobs', 'complete a work unit by reporting outcome, success score, session timestamps, and questionnaire responses', 'create visual overlays for the current work unit and render them with camera images as PIL images', 'run the orchestrator client SDK in observer mode with a robot ID flag', 'connect an OrchestratorHelper client in observer mode and read robot release configs', 'call observe_latest_work_unit to fetch and inspect the latest work unit data', 'print detailed work unit info including scene details, policy, and success scores', 'disconnect the orchestrator client after completing the observer mode loop', 'run the orchestrator example to get robot info and set operator ID using --robot_id flag', 'call get_current_robot_info on the orchestrator client to retrieve the robot ID, operator ID, and work unit stage', 'call set_current_robot_operator_id on the orchestrator client to set or clear the operator ID for a robot', 'use _print_robot_info_response to display robot ID, operational status, operator ID, job ID, and release configs', 'run the example client to connect to orchestrator and upload a mock log file artifact', 'review the main function that initializes the orchestrator client, runs the eval loop, and disconnects', 'refactor the run_mock_eval_loop function to handle additional response fields from the orchestrator client']
```

Usage

```
{'run_upload_log_file': 'run the example client to connect to orchestrator and upload a mock log file artifact', 'run_mock_eval_loop': 'run the mock eval loop that requests a work unit and prints current work unit info', 'print_work_unit_info': 'print the robot job ID, work unit ID, stage, outcome, and note for a work unit', 'review_main': 'review the main function that initializes the orchestrator client, runs the eval loop, and disconnects', 'refactor_run_mock_eval_loop': 'refactor the run_mock_eval_loop function to handle additional response fields from the orchestrator client'}
```

