# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/extensions/yaml_support/labgraph_monitor/generate_lg_monitor/generate_lg_monitor.py

Prompts

```
['identify all nodes and their input output edges from a labgraph computational graph instance', 'serialize a labgraph computational graph topology into a dictionary with nodes and upstream connections', 'connect graph nodes to their upstream nodes by mapping streams and published topic paths', 'match subscriber nodes with their publisher nodes and return a topic path grouping dictionary', 'serialize graph topology and set it on the graph instance for LabGraph Monitor WebSocket messaging']
```

Usage

```
{'identify_graph_nodes': 'identify all nodes and their input output edges from a labgraph computational graph instance', 'serialize_graph': 'serialize a labgraph computational graph topology into a dictionary with nodes and upstream connections', 'connect_to_upstream': 'connect graph nodes to their upstream nodes by mapping streams and published topic paths', 'sub_pub_grouping_map': 'match subscriber nodes with their publisher nodes and return a topic path grouping dictionary', 'set_graph_topology': 'serialize graph topology and set it on the graph instance for LabGraph Monitor WebSocket messaging'}
```

