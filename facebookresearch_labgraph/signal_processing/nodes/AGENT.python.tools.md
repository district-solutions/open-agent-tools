# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/signal_processing/nodes/function_to_node.py

Prompts

```
['convert a typed Python function into a Labgraph node with auto-generated ArgumentMessage and ReturnMessage classes', 'parse function parameter and return type annotations to determine which fields go into Labgraph message classes', 'generate a dynamic Labgraph message class from a dictionary of field names and type annotations', 'create a decorator that collects multiple validation errors and raises them together as a single exception', 'parse a function return annotation and optionally deconstruct a dataclass return type into individual message fields', 'create a Labgraph node that buffers a message stream and emits windows when a trigger predicate fires', 'create a WindowTriggerMessage class that holds a list of sample messages from a buffered stream', 'configure a WindowTriggerConfig with a window length specifying how many messages to buffer', 'review the _WindowEmitter class that maintains a sliding window deque and evaluates a trigger predicate on each message', 'refactor the WindowTriggerNode run method to customize how buffered windows are yielded as output messages']
```

Usage

```
{'convert_function_to_labgraph_node': 'convert a typed Python function into a Labgraph node with auto-generated ArgumentMessage and ReturnMessage classes', 'parse_function_annotations_for_labgraph': 'parse function parameter and return type annotations to determine which fields go into Labgraph message classes', 'generate_message_class_from_types': 'generate a dynamic Labgraph message class from a dictionary of field names and type annotations', 'create_error_collecting_decorator': 'create a decorator that collects multiple validation errors and raises them together as a single exception', 'parse_return_annotation_for_dataclass_unpacking': 'parse a function return annotation and optionally deconstruct a dataclass return type into individual message fields'}
```

## File: facebookresearch_labgraph/signal_processing/nodes/window_trigger.py

Prompts

```
['convert a typed Python function into a Labgraph node with auto-generated ArgumentMessage and ReturnMessage classes', 'parse function parameter and return type annotations to determine which fields go into Labgraph message classes', 'generate a dynamic Labgraph message class from a dictionary of field names and type annotations', 'create a decorator that collects multiple validation errors and raises them together as a single exception', 'parse a function return annotation and optionally deconstruct a dataclass return type into individual message fields', 'create a Labgraph node that buffers a message stream and emits windows when a trigger predicate fires', 'create a WindowTriggerMessage class that holds a list of sample messages from a buffered stream', 'configure a WindowTriggerConfig with a window length specifying how many messages to buffer', 'review the _WindowEmitter class that maintains a sliding window deque and evaluates a trigger predicate on each message', 'refactor the WindowTriggerNode run method to customize how buffered windows are yielded as output messages']
```

Usage

```
{'create_window_trigger_node': 'create a Labgraph node that buffers a message stream and emits windows when a trigger predicate fires', 'create_window_trigger_message': 'create a WindowTriggerMessage class that holds a list of sample messages from a buffered stream', 'configure_window_trigger_config': 'configure a WindowTriggerConfig with a window length specifying how many messages to buffer', 'review_WindowEmitter_call': 'review the _WindowEmitter class that maintains a sliding window deque and evaluates a trigger predicate on each message', 'refactor_WindowTriggerNode_run': 'refactor the WindowTriggerNode run method to customize how buffered windows are yielded as output messages'}
```

