# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/events/tests/test_event_generator.py

Prompts

```
['test that DeferredMessage stores message type, args, and kwargs without building the message yet', 'test that DeferredMessage.build_message constructs a regular Message instance from stored args and kwargs', 'test that DeferredMessage.build_message constructs a TimestampedMessage with the current time as the first arg', 'test that Event wraps a DeferredMessage with a Topic and default delay and duration of zero', 'test that EventGraph manages events in a heap ordered by accumulated time with parent-child relationships', 'test that get_method_metadata extracts published topics from a BaseEventGeneratorNode publish method', 'test that BaseEventGeneratorNode captures start time on initialization using mocked time', 'test that _time_elapsed_since_start returns the correct elapsed time since node creation', 'test that setup_generator attaches a BaseEventGenerator and generate_events returns its heap', 'test that calling publish_events on a BaseEventGeneratorNode raises NotImplementedError']
```

Usage

```
{'test_deferred_message_init': 'test that DeferredMessage stores message type, args, and kwargs without building the message yet', 'test_deferred_message_build_regular': 'test that DeferredMessage.build_message constructs a regular Message instance from stored args and kwargs', 'test_deferred_message_build_timestamped': 'test that DeferredMessage.build_message constructs a TimestampedMessage with the current time as the first arg', 'test_event_init': 'test that Event wraps a DeferredMessage with a Topic and default delay and duration of zero', 'test_event_graph_accumulated_time': 'test that EventGraph manages events in a heap ordered by accumulated time with parent-child relationships'}
```

## File: facebookresearch_labgraph/labgraph/events/tests/test_event_generator_node.py

Prompts

```
['test that DeferredMessage stores message type, args, and kwargs without building the message yet', 'test that DeferredMessage.build_message constructs a regular Message instance from stored args and kwargs', 'test that DeferredMessage.build_message constructs a TimestampedMessage with the current time as the first arg', 'test that Event wraps a DeferredMessage with a Topic and default delay and duration of zero', 'test that EventGraph manages events in a heap ordered by accumulated time with parent-child relationships', 'test that get_method_metadata extracts published topics from a BaseEventGeneratorNode publish method', 'test that BaseEventGeneratorNode captures start time on initialization using mocked time', 'test that _time_elapsed_since_start returns the correct elapsed time since node creation', 'test that setup_generator attaches a BaseEventGenerator and generate_events returns its heap', 'test that calling publish_events on a BaseEventGeneratorNode raises NotImplementedError']
```

Usage

```
{'test_BaseEventGeneratorNode_metadata': 'test that get_method_metadata extracts published topics from a BaseEventGeneratorNode publish method', 'test_BaseEventGeneratorNode_init': 'test that BaseEventGeneratorNode captures start time on initialization using mocked time', 'test_BaseEventGeneratorNode_elapsed': 'test that _time_elapsed_since_start returns the correct elapsed time since node creation', 'test_BaseEventGeneratorNode_setup_generator': 'test that setup_generator attaches a BaseEventGenerator and generate_events returns its heap', 'test_BaseEventGeneratorNode_publish': 'test that calling publish_events on a BaseEventGeneratorNode raises NotImplementedError'}
```

