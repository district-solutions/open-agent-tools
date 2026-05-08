# Agent Python Tools

- repo: facebookresearch/hgnn
- repo_uri: https://github.com/facebookresearch/hgnn

## File: facebookresearch_hgnn/data/synthetic/generate_graphs.py

Prompts

```
['run the script to generate synthetic Erdos-Renyi, Small-World, and Barabasi-Albert graphs and save train/dev/test pickle files', 'run the graph generation script to create 6000 graphs per type with random node counts between 200 and 500', 'create a pickle_dump function that serializes any Python object to a file using the highest pickle protocol', 'create a graph_to_edges function that converts a NetworkX graph into a list of (src, weight, dst) tuples', 'refactor the graph generation script to accept command-line arguments for node count ranges, graph count, and split sizes']
```

Usage

```
{'run_generate_graphs': 'run the script to generate synthetic Erdos-Renyi, Small-World, and Barabasi-Albert graphs and save train/dev/test pickle files', 'run_graph_generation': 'run the graph generation script to create 6000 graphs per type with random node counts between 200 and 500', 'create_pickle_dump': 'create a pickle_dump function that serializes any Python object to a file using the highest pickle protocol', 'create_graph_to_edges': 'create a graph_to_edges function that converts a NetworkX graph into a list of (src, weight, dst) tuples', 'refactor_graph_generation': 'refactor the graph generation script to accept command-line arguments for node count ranges, graph count, and split sizes'}
```

