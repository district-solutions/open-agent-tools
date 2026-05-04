# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/.azure-pipelines/scripts/cuda_unit_test/azure_agent.py

Prompts

```
['wait for an Azure DevOps agent to come online in a specified agent pool', 'deregister and remove an Azure DevOps agent from its agent pool', 'get the numeric pool ID for a named Azure DevOps agent pool', 'build a Basic auth header dictionary from an Azure DevOps personal access token', 'run the CLI to wait for or deregister an Azure DevOps agent by name', 'create a RunPod GPU pod with specified name, GPU count, and environment variables via the CLI', 'terminate a RunPod GPU pod by name or pod ID using the RunPod REST API', 'wait for a named RunPod GPU pod to become available by polling every 10 seconds', 'get the pod ID and status of a named RunPod GPU pod via the REST API', 'run a RunPod pod creation request with up to 3 retries on 400/500 errors']
```

Usage

```
{'wait_for_agent': 'wait for an Azure DevOps agent to come online in a specified agent pool', 'deregister_agent': 'deregister and remove an Azure DevOps agent from its agent pool', 'get_pool_id': 'get the numeric pool ID for a named Azure DevOps agent pool', 'get_auth_header': 'build a Basic auth header dictionary from an Azure DevOps personal access token', 'run_cli': 'run the CLI to wait for or deregister an Azure DevOps agent by name'}
```

## File: intel_auto-round/.azure-pipelines/scripts/cuda_unit_test/runpod_manager.py

Prompts

```
['wait for an Azure DevOps agent to come online in a specified agent pool', 'deregister and remove an Azure DevOps agent from its agent pool', 'get the numeric pool ID for a named Azure DevOps agent pool', 'build a Basic auth header dictionary from an Azure DevOps personal access token', 'run the CLI to wait for or deregister an Azure DevOps agent by name', 'create a RunPod GPU pod with specified name, GPU count, and environment variables via the CLI', 'terminate a RunPod GPU pod by name or pod ID using the RunPod REST API', 'wait for a named RunPod GPU pod to become available by polling every 10 seconds', 'get the pod ID and status of a named RunPod GPU pod via the REST API', 'run a RunPod pod creation request with up to 3 retries on 400/500 errors']
```

Usage

```
{'create_runpod_pod': 'create a RunPod GPU pod with specified name, GPU count, and environment variables via the CLI', 'terminate_runpod_pod': 'terminate a RunPod GPU pod by name or pod ID using the RunPod REST API', 'wait_for_runpod_pod': 'wait for a named RunPod GPU pod to become available by polling every 10 seconds', 'get_runpod_pod_id': 'get the pod ID and status of a named RunPod GPU pod via the REST API', 'run_create_pod_with_retry': 'run a RunPod pod creation request with up to 3 retries on 400/500 errors'}
```

