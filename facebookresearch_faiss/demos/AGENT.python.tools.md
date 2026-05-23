# Agent Python Tools

- repo: facebookresearch/faiss
- repo_uri: https://github.com/facebookresearch/faiss.git

## File: facebookresearch_faiss/demos/demo_auto_tune.py

Prompts

```
['run the FAISS auto-tune demo to benchmark index configurations on the SIFT1M dataset', 'create a function that reads FAISS float vector files in fvecs binary format and returns a numpy array', 'create a function that reads FAISS integer vector files in ivecs binary format and returns a numpy array', 'plot recall versus search time operating points for FAISS index configurations using matplotlib', 'explore FAISS index operating points using ParameterSpace to find optimal recall-speed tradeoffs', 'train a FAISS IVF index on SIFT vectors and write the trained index to disk', 'add a shard of base vectors with IDs to a trained FAISS index and save it', 'start a FAISS index server on a given port serving a loaded index block', 'create a ClientIndex across multiple servers and search for nearest neighbors with recall evaluation', 'read a FAISS fvecs binary file into a numpy float32 array using ivecs_read', 'run the distributed k-means demo across multiple GPUs using torch.distributed with NCCL backend', 'create a DatasetAssignDistributedGPU instance to manage sharded dataset assignment across distributed GPU workers', 'review the assign_to method that performs GPU-accelerated k-NN search and reduces centroid sums across workers', 'review the get_subset method that broadcasts indices and selects shard-local data across distributed workers', 'run faiss clustering.kmeans with a distributed DatasetAssign to compute centroids across multiple GPU shards', 'merge four on-disk IVF index blocks into a single populated index using merge_ondisk', 'search the populated IVF index with query vectors and compute recall at 1 against ground truth']
```

Usage

```
{'run_faiss_auto_tune_demo': 'run the FAISS auto-tune demo to benchmark index configurations on the SIFT1M dataset', 'create_fvecs_read_function': 'create a function that reads FAISS float vector files in fvecs binary format and returns a numpy array', 'create_ivecs_read_function': 'create a function that reads FAISS integer vector files in ivecs binary format and returns a numpy array', 'plot_operating_points': 'plot recall versus search time operating points for FAISS index configurations using matplotlib', 'explore_faiss_index_parameters': 'explore FAISS index operating points using ParameterSpace to find optimal recall-speed tradeoffs'}
```

## File: facebookresearch_faiss/demos/demo_client_server_ivf.py

Prompts

```
['run the FAISS auto-tune demo to benchmark index configurations on the SIFT1M dataset', 'create a function that reads FAISS float vector files in fvecs binary format and returns a numpy array', 'create a function that reads FAISS integer vector files in ivecs binary format and returns a numpy array', 'plot recall versus search time operating points for FAISS index configurations using matplotlib', 'explore FAISS index operating points using ParameterSpace to find optimal recall-speed tradeoffs', 'train a FAISS IVF index on SIFT vectors and write the trained index to disk', 'add a shard of base vectors with IDs to a trained FAISS index and save it', 'start a FAISS index server on a given port serving a loaded index block', 'create a ClientIndex across multiple servers and search for nearest neighbors with recall evaluation', 'read a FAISS fvecs binary file into a numpy float32 array using ivecs_read', 'run the distributed k-means demo across multiple GPUs using torch.distributed with NCCL backend', 'create a DatasetAssignDistributedGPU instance to manage sharded dataset assignment across distributed GPU workers', 'review the assign_to method that performs GPU-accelerated k-NN search and reduces centroid sums across workers', 'review the get_subset method that broadcasts indices and selects shard-local data across distributed workers', 'run faiss clustering.kmeans with a distributed DatasetAssign to compute centroids across multiple GPU shards', 'merge four on-disk IVF index blocks into a single populated index using merge_ondisk', 'search the populated IVF index with query vectors and compute recall at 1 against ground truth']
```

Usage

```
{'train_ivf_index': 'train a FAISS IVF index on SIFT vectors and write the trained index to disk', 'add_vectors_to_index': 'add a shard of base vectors with IDs to a trained FAISS index and save it', 'run_index_server': 'start a FAISS index server on a given port serving a loaded index block', 'search_with_client_index': 'create a ClientIndex across multiple servers and search for nearest neighbors with recall evaluation', 'read_fvecs_file': 'read a FAISS fvecs binary file into a numpy float32 array using ivecs_read'}
```

## File: facebookresearch_faiss/demos/demo_distributed_kmeans_torch.py

Prompts

```
['run the FAISS auto-tune demo to benchmark index configurations on the SIFT1M dataset', 'create a function that reads FAISS float vector files in fvecs binary format and returns a numpy array', 'create a function that reads FAISS integer vector files in ivecs binary format and returns a numpy array', 'plot recall versus search time operating points for FAISS index configurations using matplotlib', 'explore FAISS index operating points using ParameterSpace to find optimal recall-speed tradeoffs', 'train a FAISS IVF index on SIFT vectors and write the trained index to disk', 'add a shard of base vectors with IDs to a trained FAISS index and save it', 'start a FAISS index server on a given port serving a loaded index block', 'create a ClientIndex across multiple servers and search for nearest neighbors with recall evaluation', 'read a FAISS fvecs binary file into a numpy float32 array using ivecs_read', 'run the distributed k-means demo across multiple GPUs using torch.distributed with NCCL backend', 'create a DatasetAssignDistributedGPU instance to manage sharded dataset assignment across distributed GPU workers', 'review the assign_to method that performs GPU-accelerated k-NN search and reduces centroid sums across workers', 'review the get_subset method that broadcasts indices and selects shard-local data across distributed workers', 'run faiss clustering.kmeans with a distributed DatasetAssign to compute centroids across multiple GPU shards', 'merge four on-disk IVF index blocks into a single populated index using merge_ondisk', 'search the populated IVF index with query vectors and compute recall at 1 against ground truth']
```

Usage

```
{'run_distributed_kmeans_demo': 'run the distributed k-means demo across multiple GPUs using torch.distributed with NCCL backend', 'create_DatasetAssignDistributedGPU': 'create a DatasetAssignDistributedGPU instance to manage sharded dataset assignment across distributed GPU workers', 'review_assign_to_method': 'review the assign_to method that performs GPU-accelerated k-NN search and reduces centroid sums across workers', 'review_get_subset_method': 'review the get_subset method that broadcasts indices and selects shard-local data across distributed workers', 'run_clustering_kmeans': 'run faiss clustering.kmeans with a distributed DatasetAssign to compute centroids across multiple GPU shards'}
```

## File: facebookresearch_faiss/demos/demo_ondisk_ivf.py

Prompts

```
['run the FAISS auto-tune demo to benchmark index configurations on the SIFT1M dataset', 'create a function that reads FAISS float vector files in fvecs binary format and returns a numpy array', 'create a function that reads FAISS integer vector files in ivecs binary format and returns a numpy array', 'plot recall versus search time operating points for FAISS index configurations using matplotlib', 'explore FAISS index operating points using ParameterSpace to find optimal recall-speed tradeoffs', 'train a FAISS IVF index on SIFT vectors and write the trained index to disk', 'add a shard of base vectors with IDs to a trained FAISS index and save it', 'start a FAISS index server on a given port serving a loaded index block', 'create a ClientIndex across multiple servers and search for nearest neighbors with recall evaluation', 'read a FAISS fvecs binary file into a numpy float32 array using ivecs_read', 'run the distributed k-means demo across multiple GPUs using torch.distributed with NCCL backend', 'create a DatasetAssignDistributedGPU instance to manage sharded dataset assignment across distributed GPU workers', 'review the assign_to method that performs GPU-accelerated k-NN search and reduces centroid sums across workers', 'review the get_subset method that broadcasts indices and selects shard-local data across distributed workers', 'run faiss clustering.kmeans with a distributed DatasetAssign to compute centroids across multiple GPU shards', 'merge four on-disk IVF index blocks into a single populated index using merge_ondisk', 'search the populated IVF index with query vectors and compute recall at 1 against ground truth']
```

Usage

```
{'train_ivf_index': 'train a Faiss IVF4096 Flat index on SIFT1M learning vectors and write it to disk', 'add_vectors_to_index': 'add a quarter of the SIFT1M base vectors to an independent IVF index block with IDs', 'merge_ondisk_indexes': 'merge four on-disk IVF index blocks into a single populated index using merge_ondisk', 'search_index_and_compute_recall': 'search the populated IVF index with query vectors and compute recall at 1 against ground truth', 'read_fvecs_file': 'read a float vector file in fvecs format and return a numpy array of float32 vectors'}
```

