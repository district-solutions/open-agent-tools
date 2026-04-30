# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/docker/provisioner/app.py

Prompts

```
['create a FastAPI service that dynamically creates and manages per-sandbox Kubernetes Pods with NodePort Services', 'create a Pydantic request model with sandbox_id and thread_id fields validated against a safe pattern', 'create a Pydantic response model returning sandbox_id, sandbox_url, and pod status', 'build a Kubernetes V1Pod manifest for a sandbox with probes, resource limits, and volume mounts', 'build a Kubernetes V1NodePort Service manifest that auto-allocates a port and selects sandbox pods by label']
```

Usage

```
{'create_sandbox': 'create a FastAPI service that dynamically creates and manages per-sandbox Kubernetes Pods with NodePort Services', 'create_create_sandbox_request': 'create a Pydantic request model with sandbox_id and thread_id fields validated against a safe pattern', 'create_sandbox_response': 'create a Pydantic response model returning sandbox_id, sandbox_url, and pod status', 'build_k8s_pod_manifest': 'build a Kubernetes V1Pod manifest for a sandbox with probes, resource limits, and volume mounts', 'build_k8s_service': 'build a Kubernetes V1NodePort Service manifest that auto-allocates a port and selects sandbox pods by label'}
```

