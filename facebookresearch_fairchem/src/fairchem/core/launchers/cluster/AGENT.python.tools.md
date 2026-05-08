# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/launchers/cluster/ray_cluster.py

Prompts

```
['start a Ray cluster head and worker nodes on SLURM using RayCluster.start_head_and_workers with resource requirements', 'start a Ray cluster head node on SLURM using RayCluster.start_head with qos and gpu requirements', 'start Ray cluster worker nodes on SLURM using RayCluster.start_workers after the head node is running', 'shutdown a Ray cluster and cancel all SLURM jobs using RayCluster.shutdown to clean up resources', 'manage Ray cluster state with RayClusterState to track head node info and job IDs via rendezvous directory']
```

Usage

```
{'start_ray_cluster_head_and_workers': 'start a Ray cluster head and worker nodes on SLURM using RayCluster.start_head_and_workers with resource requirements', 'start_ray_cluster_head': 'start a Ray cluster head node on SLURM using RayCluster.start_head with qos and gpu requirements', 'start_ray_cluster_workers': 'start Ray cluster worker nodes on SLURM using RayCluster.start_workers after the head node is running', 'shutdown_ray_cluster': 'shutdown a Ray cluster and cancel all SLURM jobs using RayCluster.shutdown to clean up resources', 'manage_ray_cluster_state': 'manage Ray cluster state with RayClusterState to track head node info and job IDs via rendezvous directory'}
```

