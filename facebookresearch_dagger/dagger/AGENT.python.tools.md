# Agent Python Tools

- repo: facebookresearch/dagger
- repo_uri: https://github.com/facebookresearch/dagger

## File: facebookresearch_dagger/dagger/experiment.py

Prompts

```
['create an Experiment object with a directory and state class to anchor a DAG of experimental steps', 'spawn a new experiment tree by calling spawn_new_tree with keyword arguments defining the root state', 'run the experiment graph using dask by calling run with a scheduler like single-threaded', 'restore a previously saved experiment from disk using Experiment.restore with a directory path', 'apply a Recipe subclass to an ExperimentState to transition it to a new state in the graph', 'create a StaticExperimentTree with node_map, edge_map, and toposort dicts for static graph analysis', 'filter a NodeSet by tag pattern using fnmatch glob matching with optional negation prefix', 'combine two NodeSets using union or intersection operators to merge or intersect experiment states', 'render a StaticExperimentTree as a graphviz Digraph with colored nodes showing sha, level, and tags', 'draw and save a StaticExperimentTree graph to disk as PDF with optional Jupyter notebook display']
```

Usage

```
{'create_experiment_dag': 'create an Experiment object with a directory and state class to anchor a DAG of experimental steps', 'spawn_experiment_tree': 'spawn a new experiment tree by calling spawn_new_tree with keyword arguments defining the root state', 'run_experiment_with_dask': 'run the experiment graph using dask by calling run with a scheduler like single-threaded', 'restore_experiment_from_disk': 'restore a previously saved experiment from disk using Experiment.restore with a directory path', 'apply_recipe_to_state': 'apply a Recipe subclass to an ExperimentState to transition it to a new state in the graph'}
```

## File: facebookresearch_dagger/dagger/static.py

Prompts

```
['create an Experiment object with a directory and state class to anchor a DAG of experimental steps', 'spawn a new experiment tree by calling spawn_new_tree with keyword arguments defining the root state', 'run the experiment graph using dask by calling run with a scheduler like single-threaded', 'restore a previously saved experiment from disk using Experiment.restore with a directory path', 'apply a Recipe subclass to an ExperimentState to transition it to a new state in the graph', 'create a StaticExperimentTree with node_map, edge_map, and toposort dicts for static graph analysis', 'filter a NodeSet by tag pattern using fnmatch glob matching with optional negation prefix', 'combine two NodeSets using union or intersection operators to merge or intersect experiment states', 'render a StaticExperimentTree as a graphviz Digraph with colored nodes showing sha, level, and tags', 'draw and save a StaticExperimentTree graph to disk as PDF with optional Jupyter notebook display']
```

Usage

```
{'create_experiment_tree': 'create a StaticExperimentTree with node_map, edge_map, and toposort dicts for static graph analysis', 'filter_nodes_by_tag': 'filter a NodeSet by tag pattern using fnmatch glob matching with optional negation prefix', 'combine_nodesets': 'combine two NodeSets using union or intersection operators to merge or intersect experiment states', 'visualize_experiment_graph': 'render a StaticExperimentTree as a graphviz Digraph with colored nodes showing sha, level, and tags', 'draw_experiment_graph': 'draw and save a StaticExperimentTree graph to disk as PDF with optional Jupyter notebook display'}
```

