# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/extensions/psychopy_example/psychopy_example/__main__.py

Prompts

```
['run the PsychopyExample labgraph graph using lg.run to start the Controller and Display modules', 'create a labgraph Graph subclass like PsychopyExample with Controller and Display module attributes', 'define the process_modules method to return a sequence of lg.Module instances for the graph', 'define the connections method to wire Controller and Display topics together as tuples', 'configure the logging method to return a dict mapping topic names to lg.Topic instances', 'create a labgraph Controller node that subscribes to keys and publishes display messages in round robin order', 'create a labgraph Display node that sets up psychopy stims and flips frames in the main thread', 'create a KeysMessage labgraph message class that carries a list of display key strings', 'create a DisplayMessage labgraph message class that carries a single display key string', 'setup psychopy ImageStim and TextStim objects mapped to keys for display in a labgraph node']
```

Usage

```
{'run_psychopy_example_graph': 'run the PsychopyExample labgraph graph using lg.run to start the Controller and Display modules', 'create_labgraph_graph_subclass': 'create a labgraph Graph subclass like PsychopyExample with Controller and Display module attributes', 'define_process_modules': 'define the process_modules method to return a sequence of lg.Module instances for the graph', 'define_graph_connections': 'define the connections method to wire Controller and Display topics together as tuples', 'configure_graph_logging': 'configure the logging method to return a dict mapping topic names to lg.Topic instances'}
```

## File: facebookresearch_labgraph/extensions/psychopy_example/psychopy_example/components.py

Prompts

```
['run the PsychopyExample labgraph graph using lg.run to start the Controller and Display modules', 'create a labgraph Graph subclass like PsychopyExample with Controller and Display module attributes', 'define the process_modules method to return a sequence of lg.Module instances for the graph', 'define the connections method to wire Controller and Display topics together as tuples', 'configure the logging method to return a dict mapping topic names to lg.Topic instances', 'create a labgraph Controller node that subscribes to keys and publishes display messages in round robin order', 'create a labgraph Display node that sets up psychopy stims and flips frames in the main thread', 'create a KeysMessage labgraph message class that carries a list of display key strings', 'create a DisplayMessage labgraph message class that carries a single display key string', 'setup psychopy ImageStim and TextStim objects mapped to keys for display in a labgraph node']
```

Usage

```
{'create_controller_node': 'create a labgraph Controller node that subscribes to keys and publishes display messages in round robin order', 'create_display_node': 'create a labgraph Display node that sets up psychopy stims and flips frames in the main thread', 'create_keys_message': 'create a KeysMessage labgraph message class that carries a list of display key strings', 'create_display_message': 'create a DisplayMessage labgraph message class that carries a single display key string', 'setup_psychopy_stims': 'setup psychopy ImageStim and TextStim objects mapped to keys for display in a labgraph node'}
```

