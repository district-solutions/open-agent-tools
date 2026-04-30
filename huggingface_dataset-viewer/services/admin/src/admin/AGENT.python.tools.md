# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/admin/src/admin/app.py

Prompts

```
['create a Starlette app with CORS, GZip, and Prometheus middleware for the admin service', 'run the admin service on a configured host and port using uvicorn', 'create a healthcheck endpoint for ALB and Kubernetes liveness probes', 'create an endpoint to list pending jobs in the processing queue', 'create a POST endpoint to recreate a dataset by re-queuing all its jobs', 'create a UvicornConfig instance from environment variables using the from_env classmethod', 'create an AdminConfig instance from environment variables and a CommonConfig using from_env', 'create an AppConfig instance that aggregates all sub-configs from environment variables', 'review the UvicornConfig dataclass default values for hostname, num_workers, and port', 'review the AdminConfig dataclass default values for cache reports, auth URL, and timeout']
```

Usage

```
{'create_starlette_app': 'create a Starlette app with CORS, GZip, and Prometheus middleware for the admin service', 'run_admin_server': 'run the admin service on a configured host and port using uvicorn', 'create_healthcheck_endpoint': 'create a healthcheck endpoint for ALB and Kubernetes liveness probes', 'create_pending_jobs_endpoint': 'create an endpoint to list pending jobs in the processing queue', 'create_recreate_dataset_endpoint': 'create a POST endpoint to recreate a dataset by re-queuing all its jobs'}
```

## File: huggingface_dataset-viewer/services/admin/src/admin/config.py

Prompts

```
['create a Starlette app with CORS, GZip, and Prometheus middleware for the admin service', 'run the admin service on a configured host and port using uvicorn', 'create a healthcheck endpoint for ALB and Kubernetes liveness probes', 'create an endpoint to list pending jobs in the processing queue', 'create a POST endpoint to recreate a dataset by re-queuing all its jobs', 'create a UvicornConfig instance from environment variables using the from_env classmethod', 'create an AdminConfig instance from environment variables and a CommonConfig using from_env', 'create an AppConfig instance that aggregates all sub-configs from environment variables', 'review the UvicornConfig dataclass default values for hostname, num_workers, and port', 'review the AdminConfig dataclass default values for cache reports, auth URL, and timeout']
```

Usage

```
{'create_UvicornConfig_from_env': 'create a UvicornConfig instance from environment variables using the from_env classmethod', 'create_AdminConfig_from_env': 'create an AdminConfig instance from environment variables and a CommonConfig using from_env', 'create_AppConfig_from_env': 'create an AppConfig instance that aggregates all sub-configs from environment variables', 'review_UvicornConfig_defaults': 'review the UvicornConfig dataclass default values for hostname, num_workers, and port', 'review_AdminConfig_defaults': 'review the AdminConfig dataclass default values for cache reports, auth URL, and timeout'}
```

