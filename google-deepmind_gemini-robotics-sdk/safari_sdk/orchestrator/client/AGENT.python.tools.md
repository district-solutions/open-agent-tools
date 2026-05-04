# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/orchestrator/client/interface.py

Prompts

```
['connect an OrchestratorInterface to the orchestrator server using robot_id and job_type', 'request a robot job work unit from the orchestrator and start working on it', 'complete the current work unit with an outcome, success score, and optional session notes', 'create visual overlay renderers from the current work unit scene preset reference images', 'upload a text log artifact to the orchestrator for the current robot job', 'create an OrchestratorInterface instance and connect to the orchestrator server with a robot_id and job_type', 'create a visual overlay renderer for rendering scene objects and reference images as PIL or numpy arrays', 'load an artifact by its ID and retrieve its URI, metadata, tags, and object type']
```

Usage

```
{'connect_orchestrator': 'connect an OrchestratorInterface to the orchestrator server using robot_id and job_type', 'request_robot_job_work_unit': 'request a robot job work unit from the orchestrator and start working on it', 'complete_work_unit': 'complete the current work unit with an outcome, success score, and optional session notes', 'create_visual_overlays': 'create visual overlay renderers from the current work unit scene preset reference images', 'upload_text_log_artifact': 'upload a text log artifact to the orchestrator for the current robot job'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/orchestrator/client/interface_test.py

Prompts

```
['connect an OrchestratorInterface to the orchestrator server using robot_id and job_type', 'request a robot job work unit from the orchestrator and start working on it', 'complete the current work unit with an outcome, success score, and optional session notes', 'create visual overlay renderers from the current work unit scene preset reference images', 'upload a text log artifact to the orchestrator for the current robot job', 'create an OrchestratorInterface instance and connect to the orchestrator server with a robot_id and job_type', 'create a visual overlay renderer for rendering scene objects and reference images as PIL or numpy arrays', 'load an artifact by its ID and retrieve its URI, metadata, tags, and object type']
```

Usage

```
{'connect_orchestrator_interface': 'create an OrchestratorInterface instance and connect to the orchestrator server with a robot_id and job_type', 'request_robot_job_work_unit': 'request a robot job work unit from the orchestrator to get the next task for the robot', 'complete_work_unit': 'complete the current work unit with outcome, success score, session info, and answers to questions', 'create_visual_overlay_renderer': 'create a visual overlay renderer for rendering scene objects and reference images as PIL or numpy arrays', 'get_artifact': 'load an artifact by its ID and retrieve its URI, metadata, tags, and object type'}
```

