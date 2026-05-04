# Agent Python Tools

- repo: facebookresearch/distributed-faiss
- repo_uri: https://github.com/facebookresearch/distributed-faiss

## File: facebookresearch_distributed-faiss/scripts/load_data.py

Prompts

```
['run the load_data script to batch load vectors from a memmap into a distributed FAISS index', 'create a memory-mapped numpy file from an existing array using array_to_memmap', 'create a random float16 memmap file in chunks using save_random_mmap', 'review the get_args function that parses CLI arguments for mmap path, dimension, batch size, and config', 'refactor the main function to customize index creation, batch loading, training, and search workflows', 'run multiple distributed FAISS index servers across Slurm nodes using submitit executor', 'run a single FAISS IndexServer on a computed port and register it in the discovery config', 'acquire an NFS-safe file lock using os.link with polling and timeout support', 'safely append a hostname and port entry to the discovery config file using NFS-safe locking', 'submit distributed FAISS server jobs to a Slurm cluster with configurable nodes, memory, and CPUs']
```

Usage

```
{'run_load_data_cli': 'run the load_data script to batch load vectors from a memmap into a distributed FAISS index', 'create_array_to_memmap': 'create a memory-mapped numpy file from an existing array using array_to_memmap', 'create_save_random_mmap': 'create a random float16 memmap file in chunks using save_random_mmap', 'review_get_args': 'review the get_args function that parses CLI arguments for mmap path, dimension, batch size, and config', 'refactor_main': 'refactor the main function to customize index creation, batch loading, training, and search workflows'}
```

## File: facebookresearch_distributed-faiss/scripts/server_launcher.py

Prompts

```
['run the load_data script to batch load vectors from a memmap into a distributed FAISS index', 'create a memory-mapped numpy file from an existing array using array_to_memmap', 'create a random float16 memmap file in chunks using save_random_mmap', 'review the get_args function that parses CLI arguments for mmap path, dimension, batch size, and config', 'refactor the main function to customize index creation, batch loading, training, and search workflows', 'run multiple distributed FAISS index servers across Slurm nodes using submitit executor', 'run a single FAISS IndexServer on a computed port and register it in the discovery config', 'acquire an NFS-safe file lock using os.link with polling and timeout support', 'safely append a hostname and port entry to the discovery config file using NFS-safe locking', 'submit distributed FAISS server jobs to a Slurm cluster with configurable nodes, memory, and CPUs']
```

Usage

```
{'run_distributed_faiss_servers': 'run multiple distributed FAISS index servers across Slurm nodes using submitit executor', 'run_server_function': 'run a single FAISS IndexServer on a computed port and register it in the discovery config', 'lockfile_nfs_safe': 'acquire an NFS-safe file lock using os.link with polling and timeout support', 'append_to_discovery_config_safe': 'safely append a hostname and port entry to the discovery config file using NFS-safe locking', 'submit_servers_with_submitit': 'submit distributed FAISS server jobs to a Slurm cluster with configurable nodes, memory, and CPUs'}
```

