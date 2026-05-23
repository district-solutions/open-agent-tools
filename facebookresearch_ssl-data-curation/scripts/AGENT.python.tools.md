# Agent Python Tools

- repo: facebookresearch/ssl-data-curation
- repo_uri: https://github.com/facebookresearch/ssl-data-curation

## File: facebookresearch_ssl-data-curation/scripts/hierarchical_kmeans_launcher.py

Prompts

```
['run the hierarchical k-means launcher with --exp_dir, --embeddings_path, and --config_file arguments', 'write a SLURM and local bash script for a single level of distributed k-means clustering', 'write a SLURM and local bash script to split pre-clusters into smaller clusters for a k-means level', 'write SLURM scripts for all hierarchical k-means levels including optional cluster splitting scripts', 'write a bash launcher script that chains SLURM jobs across all hierarchical k-means levels with dependencies', 'run distributed k-means clustering on GPU with multi-step hierarchical sampling and resampling', 'run distributed k-means on a subset of data using provided subset indices path', 'run distributed k-means with random sampling strategy instead of closest-to-centroid sampling', 'run multi-step distributed k-means with resampling between steps to refine cluster assignments', 'run distributed k-means with periodic checkpointing for k-means++ initialization and sorting', 'run the split_clusters script to subdivide existing clusters using distributed GPU k-means++', 'run split_clusters on a subset of data by providing subset indices path', 'run split_clusters with torchrun for multi-GPU distributed processing across nodes', 'review the split_clusters function that performs k-means++ on each pre-cluster with checkpointing', 'review how kmeans_gpu.kmeans and sort_cluster_by_distance are used to split and sort clusters']
```

Usage

```
{'run_hierarchical_kmeans_launcher': 'run the hierarchical k-means launcher with --exp_dir, --embeddings_path, and --config_file arguments', 'write_main_script': 'write a SLURM and local bash script for a single level of distributed k-means clustering', 'write_split_clusters_script': 'write a SLURM and local bash script to split pre-clusters into smaller clusters for a k-means level', 'write_slurm_scripts': 'write SLURM scripts for all hierarchical k-means levels including optional cluster splitting scripts', 'write_launcher': 'write a bash launcher script that chains SLURM jobs across all hierarchical k-means levels with dependencies'}
```

## File: facebookresearch_ssl-data-curation/scripts/run_distributed_kmeans.py

Prompts

```
['run the hierarchical k-means launcher with --exp_dir, --embeddings_path, and --config_file arguments', 'write a SLURM and local bash script for a single level of distributed k-means clustering', 'write a SLURM and local bash script to split pre-clusters into smaller clusters for a k-means level', 'write SLURM scripts for all hierarchical k-means levels including optional cluster splitting scripts', 'write a bash launcher script that chains SLURM jobs across all hierarchical k-means levels with dependencies', 'run distributed k-means clustering on GPU with multi-step hierarchical sampling and resampling', 'run distributed k-means on a subset of data using provided subset indices path', 'run distributed k-means with random sampling strategy instead of closest-to-centroid sampling', 'run multi-step distributed k-means with resampling between steps to refine cluster assignments', 'run distributed k-means with periodic checkpointing for k-means++ initialization and sorting', 'run the split_clusters script to subdivide existing clusters using distributed GPU k-means++', 'run split_clusters on a subset of data by providing subset indices path', 'run split_clusters with torchrun for multi-GPU distributed processing across nodes', 'review the split_clusters function that performs k-means++ on each pre-cluster with checkpointing', 'review how kmeans_gpu.kmeans and sort_cluster_by_distance are used to split and sort clusters']
```

Usage

```
{'run_distributed_kmeans': 'run distributed k-means clustering on GPU with multi-step hierarchical sampling and resampling', 'run_kmeans_with_subset': 'run distributed k-means on a subset of data using provided subset indices path', 'run_kmeans_with_random_sampling': 'run distributed k-means with random sampling strategy instead of closest-to-centroid sampling', 'run_kmeans_multi_step': 'run multi-step distributed k-means with resampling between steps to refine cluster assignments', 'run_kmeans_with_checkpoints': 'run distributed k-means with periodic checkpointing for k-means++ initialization and sorting'}
```

## File: facebookresearch_ssl-data-curation/scripts/split_clusters.py

Prompts

```
['run the hierarchical k-means launcher with --exp_dir, --embeddings_path, and --config_file arguments', 'write a SLURM and local bash script for a single level of distributed k-means clustering', 'write a SLURM and local bash script to split pre-clusters into smaller clusters for a k-means level', 'write SLURM scripts for all hierarchical k-means levels including optional cluster splitting scripts', 'write a bash launcher script that chains SLURM jobs across all hierarchical k-means levels with dependencies', 'run distributed k-means clustering on GPU with multi-step hierarchical sampling and resampling', 'run distributed k-means on a subset of data using provided subset indices path', 'run distributed k-means with random sampling strategy instead of closest-to-centroid sampling', 'run multi-step distributed k-means with resampling between steps to refine cluster assignments', 'run distributed k-means with periodic checkpointing for k-means++ initialization and sorting', 'run the split_clusters script to subdivide existing clusters using distributed GPU k-means++', 'run split_clusters on a subset of data by providing subset indices path', 'run split_clusters with torchrun for multi-GPU distributed processing across nodes', 'review the split_clusters function that performs k-means++ on each pre-cluster with checkpointing', 'review how kmeans_gpu.kmeans and sort_cluster_by_distance are used to split and sort clusters']
```

Usage

```
{'run_split_clusters': 'run the split_clusters script to subdivide existing clusters using distributed GPU k-means++', 'run_split_clusters_with_subset': 'run split_clusters on a subset of data by providing subset indices path', 'run_split_clusters_torchrun': 'run split_clusters with torchrun for multi-GPU distributed processing across nodes', 'review_split_clusters_function': 'review the split_clusters function that performs k-means++ on each pre-cluster with checkpointing', 'review_kmeans_integration': 'review how kmeans_gpu.kmeans and sort_cluster_by_distance are used to split and sort clusters'}
```

