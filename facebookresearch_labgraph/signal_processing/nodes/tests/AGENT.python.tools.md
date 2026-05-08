# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/signal_processing/nodes/tests/test_function_to_node.py

Prompts

```
['parse function type annotations to extract input output message schemas and dataclass deconstruction flags', 'convert a typed python function into a labgraph node with auto generated input and output message classes', 'convert a function to a labgraph node and pass keyword arguments via FunctionConfig kwargs override', 'convert a function returning a dataclass to a labgraph node with deconstructed return message fields', 'wire a function converted to a labgraph node into a graph with generator and consumer nodes', 'test the make_window_trigger_node factory function with a SampleMessage and trigger predicate', 'test the predict_state method to verify expected window trigger stream state', 'test the Generator, Consumer, and Graph classes in a labgraph ParallelRunner pipeline', 'test the window trigger node end-to-end inside a labgraph Graph with ParallelRunner', 'review the SampleMessage class extending lg.TimestampedMessage with sample and equality logic']
```

Usage

```
{'parse_function_annotations': 'parse function type annotations to extract input output message schemas and dataclass deconstruction flags', 'function_to_node_basic': 'convert a typed python function into a labgraph node with auto generated input and output message classes', 'function_to_node_kwargs': 'convert a function to a labgraph node and pass keyword arguments via FunctionConfig kwargs override', 'function_to_node_dataclass': 'convert a function returning a dataclass to a labgraph node with deconstructed return message fields', 'function_to_node_graph': 'wire a function converted to a labgraph node into a graph with generator and consumer nodes'}
```

## File: facebookresearch_labgraph/signal_processing/nodes/tests/test_window_trigger.py

Prompts

```
['parse function type annotations to extract input output message schemas and dataclass deconstruction flags', 'convert a typed python function into a labgraph node with auto generated input and output message classes', 'convert a function to a labgraph node and pass keyword arguments via FunctionConfig kwargs override', 'convert a function returning a dataclass to a labgraph node with deconstructed return message fields', 'wire a function converted to a labgraph node into a graph with generator and consumer nodes', 'test the make_window_trigger_node factory function with a SampleMessage and trigger predicate', 'test the predict_state method to verify expected window trigger stream state', 'test the Generator, Consumer, and Graph classes in a labgraph ParallelRunner pipeline', 'test the window trigger node end-to-end inside a labgraph Graph with ParallelRunner', 'review the SampleMessage class extending lg.TimestampedMessage with sample and equality logic']
```

Usage

```
{'test_make_window_trigger_node': 'test the make_window_trigger_node factory function with a SampleMessage and trigger predicate', 'test_predict_state': 'test the predict_state method to verify expected window trigger stream state', 'test_generator_consumer_graph': 'test the Generator, Consumer, and Graph classes in a labgraph ParallelRunner pipeline', 'test_in_graph': 'test the window trigger node end-to-end inside a labgraph Graph with ParallelRunner', 'review_sample_message_class': 'review the SampleMessage class extending lg.TimestampedMessage with sample and equality logic'}
```

