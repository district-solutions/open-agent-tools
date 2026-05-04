# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/orchestrator/helpers/orchestrator_helper.py

Prompts

```
['create an OrchestratorHelper instance and call connect to establish a connection to the orchestrator server', 'request a work unit from the server then complete it with an outcome and note', 'create visual overlay renderers for the current work unit and render overlays onto camera images', 'upload a text log artifact to the orchestrator server with a source file name and bytes', 'get the current robot information and assigned work unit details from the orchestrator server', 'get current robot info, set the operator ID, update hardware config, and record operator events like battery level', 'upload a text log artifact, retrieve artifact metadata by ID, and load or set the RUI workcell state for a robot']
```

Usage

```
{'connect_orchestrator_helper': 'create an OrchestratorHelper instance and call connect to establish a connection to the orchestrator server', 'request_and_complete_work_unit': 'request a work unit from the server then complete it with an outcome and note', 'render_visual_overlay': 'create visual overlay renderers for the current work unit and render overlays onto camera images', 'upload_text_log_artifact': 'upload a text log artifact to the orchestrator server with a source file name and bytes', 'get_robot_info_and_work_unit': 'get the current robot information and assigned work unit details from the orchestrator server'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/orchestrator/helpers/orchestrator_helper_test.py

Prompts

```
['create an OrchestratorHelper instance and call connect to establish a connection to the orchestrator server', 'request a work unit from the server then complete it with an outcome and note', 'create visual overlay renderers for the current work unit and render overlays onto camera images', 'upload a text log artifact to the orchestrator server with a source file name and bytes', 'get the current robot information and assigned work unit details from the orchestrator server', 'get current robot info, set the operator ID, update hardware config, and record operator events like battery level', 'upload a text log artifact, retrieve artifact metadata by ID, and load or set the RUI workcell state for a robot']
```

Usage

```
{'connect_orchestrator_helper': 'create an OrchestratorHelper instance and call connect to establish a connection to the orchestrator server using robot_id or hostname', 'request_and_complete_work_unit': 'request a work unit from the orchestrator server, start execution, then complete it with an outcome and optional success score', 'render_visual_overlay': 'create visual overlay renderers for a work unit, add overlay objects like circles, and render the overlay onto an image', 'manage_robot_info_and_events': 'get current robot info, set the operator ID, update hardware config, and record operator events like battery level', 'upload_artifact_and_manage_workcell_state': 'upload a text log artifact, retrieve artifact metadata by ID, and load or set the RUI workcell state for a robot'}
```

