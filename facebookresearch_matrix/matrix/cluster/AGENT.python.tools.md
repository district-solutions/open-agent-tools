# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/cluster/ray_cluster.py

Prompts

```
['start a Ray cluster on Slurm with head and worker nodes using RayCluster.start', 'stop a Ray cluster and cancel all associated Slurm jobs using RayCluster.stop', 'get Ray cluster resources including nodes and available resources using RayCluster.get_resources', 'start a Prometheus and Grafana monitoring dashboard for the Ray cluster using RayCluster.start_grafana', 'parse a SLURM time limit string like DAYS-HH:MM:SS into total minutes using _parse_time_limit', 'start a RayDashboardJob actor to launch Grafana and Prometheus subprocesses for monitoring', 'get the current status of Grafana and Prometheus processes managed by the RayDashboardJob actor', 'cleanup and terminate all Grafana and Prometheus subprocesses managed by the RayDashboardJob actor', 'update the Ray scrape interval in the Prometheus YAML configuration file', 'start a Prometheus subprocess with a custom config file and listen address', 'start the Ray cluster head node on Slurm with auto-allocated ports and cluster info JSON output', 'start a Ray head node with a configurable GCS server request timeout for worker wait', 'start a Ray head node with Prometheus and Grafana monitoring ports configured automatically', 'review the RayHeadJob class start_ray_head method for Ray cluster head node startup logic', 'summarize the RayHeadJob class that manages Ray cluster head node startup and cluster info serialization', 'create a RayWorkerJob instance with cluster info, timeouts, logical resources, and SLURM requirements', 'execute a Ray worker job by calling the RayWorkerJob instance to start a Ray worker', 'configure Ray worker resource allocation using _RayWorkerConfiguration with CPU, GPU, and logical resource settings', 'start a Ray worker subprocess with specified environment variables, CPU count, GPU count, and logical resources', 'checkpoint a RayWorkerJob by returning a submitit DelayedSubmission for deferred execution']
```

Usage

```
{'start_ray_cluster': 'start a Ray cluster on Slurm with head and worker nodes using RayCluster.start', 'stop_ray_cluster': 'stop a Ray cluster and cancel all associated Slurm jobs using RayCluster.stop', 'get_cluster_resources': 'get Ray cluster resources including nodes and available resources using RayCluster.get_resources', 'start_grafana_dashboard': 'start a Prometheus and Grafana monitoring dashboard for the Ray cluster using RayCluster.start_grafana', 'parse_slurm_time_limit': 'parse a SLURM time limit string like DAYS-HH:MM:SS into total minutes using _parse_time_limit'}
```

## File: facebookresearch_matrix/matrix/cluster/ray_dashboard_job.py

Prompts

```
['start a Ray cluster on Slurm with head and worker nodes using RayCluster.start', 'stop a Ray cluster and cancel all associated Slurm jobs using RayCluster.stop', 'get Ray cluster resources including nodes and available resources using RayCluster.get_resources', 'start a Prometheus and Grafana monitoring dashboard for the Ray cluster using RayCluster.start_grafana', 'parse a SLURM time limit string like DAYS-HH:MM:SS into total minutes using _parse_time_limit', 'start a RayDashboardJob actor to launch Grafana and Prometheus subprocesses for monitoring', 'get the current status of Grafana and Prometheus processes managed by the RayDashboardJob actor', 'cleanup and terminate all Grafana and Prometheus subprocesses managed by the RayDashboardJob actor', 'update the Ray scrape interval in the Prometheus YAML configuration file', 'start a Prometheus subprocess with a custom config file and listen address', 'start the Ray cluster head node on Slurm with auto-allocated ports and cluster info JSON output', 'start a Ray head node with a configurable GCS server request timeout for worker wait', 'start a Ray head node with Prometheus and Grafana monitoring ports configured automatically', 'review the RayHeadJob class start_ray_head method for Ray cluster head node startup logic', 'summarize the RayHeadJob class that manages Ray cluster head node startup and cluster info serialization', 'create a RayWorkerJob instance with cluster info, timeouts, logical resources, and SLURM requirements', 'execute a Ray worker job by calling the RayWorkerJob instance to start a Ray worker', 'configure Ray worker resource allocation using _RayWorkerConfiguration with CPU, GPU, and logical resource settings', 'start a Ray worker subprocess with specified environment variables, CPU count, GPU count, and logical resources', 'checkpoint a RayWorkerJob by returning a submitit DelayedSubmission for deferred execution']
```

Usage

```
{'start_ray_dashboard_job': 'start a RayDashboardJob actor to launch Grafana and Prometheus subprocesses for monitoring', 'get_ray_dashboard_status': 'get the current status of Grafana and Prometheus processes managed by the RayDashboardJob actor', 'cleanup_ray_dashboard_job': 'cleanup and terminate all Grafana and Prometheus subprocesses managed by the RayDashboardJob actor', 'update_ray_scrape_interval': 'update the Ray scrape interval in the Prometheus YAML configuration file', 'start_prometheus_subprocess': 'start a Prometheus subprocess with a custom config file and listen address'}
```

## File: facebookresearch_matrix/matrix/cluster/ray_head_job.py

Prompts

```
['start a Ray cluster on Slurm with head and worker nodes using RayCluster.start', 'stop a Ray cluster and cancel all associated Slurm jobs using RayCluster.stop', 'get Ray cluster resources including nodes and available resources using RayCluster.get_resources', 'start a Prometheus and Grafana monitoring dashboard for the Ray cluster using RayCluster.start_grafana', 'parse a SLURM time limit string like DAYS-HH:MM:SS into total minutes using _parse_time_limit', 'start a RayDashboardJob actor to launch Grafana and Prometheus subprocesses for monitoring', 'get the current status of Grafana and Prometheus processes managed by the RayDashboardJob actor', 'cleanup and terminate all Grafana and Prometheus subprocesses managed by the RayDashboardJob actor', 'update the Ray scrape interval in the Prometheus YAML configuration file', 'start a Prometheus subprocess with a custom config file and listen address', 'start the Ray cluster head node on Slurm with auto-allocated ports and cluster info JSON output', 'start a Ray head node with a configurable GCS server request timeout for worker wait', 'start a Ray head node with Prometheus and Grafana monitoring ports configured automatically', 'review the RayHeadJob class start_ray_head method for Ray cluster head node startup logic', 'summarize the RayHeadJob class that manages Ray cluster head node startup and cluster info serialization', 'create a RayWorkerJob instance with cluster info, timeouts, logical resources, and SLURM requirements', 'execute a Ray worker job by calling the RayWorkerJob instance to start a Ray worker', 'configure Ray worker resource allocation using _RayWorkerConfiguration with CPU, GPU, and logical resource settings', 'start a Ray worker subprocess with specified environment variables, CPU count, GPU count, and logical resources', 'checkpoint a RayWorkerJob by returning a submitit DelayedSubmission for deferred execution']
```

Usage

```
{'start_ray_head_node': 'start the Ray cluster head node on Slurm with auto-allocated ports and cluster info JSON output', 'start_ray_head_with_timeout': 'start a Ray head node with a configurable GCS server request timeout for worker wait', 'start_ray_head_with_monitoring': 'start a Ray head node with Prometheus and Grafana monitoring ports configured automatically', 'review_RayHeadJob_start_ray_head': 'review the RayHeadJob class start_ray_head method for Ray cluster head node startup logic', 'summarize_RayHeadJob': 'summarize the RayHeadJob class that manages Ray cluster head node startup and cluster info serialization'}
```

## File: facebookresearch_matrix/matrix/cluster/ray_worker_job.py

Prompts

```
['start a Ray cluster on Slurm with head and worker nodes using RayCluster.start', 'stop a Ray cluster and cancel all associated Slurm jobs using RayCluster.stop', 'get Ray cluster resources including nodes and available resources using RayCluster.get_resources', 'start a Prometheus and Grafana monitoring dashboard for the Ray cluster using RayCluster.start_grafana', 'parse a SLURM time limit string like DAYS-HH:MM:SS into total minutes using _parse_time_limit', 'start a RayDashboardJob actor to launch Grafana and Prometheus subprocesses for monitoring', 'get the current status of Grafana and Prometheus processes managed by the RayDashboardJob actor', 'cleanup and terminate all Grafana and Prometheus subprocesses managed by the RayDashboardJob actor', 'update the Ray scrape interval in the Prometheus YAML configuration file', 'start a Prometheus subprocess with a custom config file and listen address', 'start the Ray cluster head node on Slurm with auto-allocated ports and cluster info JSON output', 'start a Ray head node with a configurable GCS server request timeout for worker wait', 'start a Ray head node with Prometheus and Grafana monitoring ports configured automatically', 'review the RayHeadJob class start_ray_head method for Ray cluster head node startup logic', 'summarize the RayHeadJob class that manages Ray cluster head node startup and cluster info serialization', 'create a RayWorkerJob instance with cluster info, timeouts, logical resources, and SLURM requirements', 'execute a Ray worker job by calling the RayWorkerJob instance to start a Ray worker', 'configure Ray worker resource allocation using _RayWorkerConfiguration with CPU, GPU, and logical resource settings', 'start a Ray worker subprocess with specified environment variables, CPU count, GPU count, and logical resources', 'checkpoint a RayWorkerJob by returning a submitit DelayedSubmission for deferred execution']
```

Usage

```
{'create_ray_worker_job': 'create a RayWorkerJob instance with cluster info, timeouts, logical resources, and SLURM requirements', 'execute_ray_worker_job': 'execute a Ray worker job by calling the RayWorkerJob instance to start a Ray worker', 'configure_ray_worker_resources': 'configure Ray worker resource allocation using _RayWorkerConfiguration with CPU, GPU, and logical resource settings', 'start_ray_worker_subprocess': 'start a Ray worker subprocess with specified environment variables, CPU count, GPU count, and logical resources', 'checkpoint_ray_worker_job': 'checkpoint a RayWorkerJob by returning a submitit DelayedSubmission for deferred execution'}
```

