# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/common/tests/test_stage_state_instance.py

Prompts

```
['test that StageStateInstance returns container IPs when status is COMPLETED and empty list when UNKNOWN', 'test that StageStateInstance correctly calculates elapsed time from creation_ts to end_ts', 'test that stop_containers calls OneDockerService and raises RuntimeError on failure', 'test that update_status correctly translates container statuses to StageStateInstanceStatus', 'test that update_status only queries running containers and updates their statuses in place']
```

Usage

```
{'test_stage_state_instance_server_ips': 'test that StageStateInstance returns container IPs when status is COMPLETED and empty list when UNKNOWN', 'test_stage_state_instance_elapsed_time': 'test that StageStateInstance correctly calculates elapsed time from creation_ts to end_ts', 'test_stage_state_instance_stop_containers': 'test that stop_containers calls OneDockerService and raises RuntimeError on failure', 'test_stage_state_instance_update_status_translation': 'test that update_status correctly translates container statuses to StageStateInstanceStatus', 'test_stage_state_instance_update_status': 'test that update_status only queries running containers and updates their statuses in place'}
```

