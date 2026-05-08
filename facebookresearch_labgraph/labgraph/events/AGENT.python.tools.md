# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/events/event_generator.py

Prompts

```
['create a DeferredMessage that lazily builds a Message with auto-injected timestamps on access', 'build an Event dataclass with a DeferredMessage, topic, delay, and optional duration fields', 'create an EventGraph from a start event and add subsequent events at start or end boundaries', "add an event to the EventGraph heap scheduled after the previous event's duration ends", 'implement a BaseEventGenerator subclass with generate_events and set_topics abstract methods', 'create a subclass of BaseEventGeneratorNode that publishes timed events to Labgraph topics', 'call setup_generator on a BaseEventGeneratorNode to attach a BaseEventGenerator instance', 'call generate_events on a BaseEventGeneratorNode to get an EventPublishingHeap of scheduled events', 'implement the abstract publish_events async method on a BaseEventGeneratorNode subclass to publish timed events', 'review how BaseEventGeneratorNodeMeta filters out WaitEndMessage topics and populates published_topics metadata']
```

Usage

```
{'create_deferred_message': 'create a DeferredMessage that lazily builds a Message with auto-injected timestamps on access', 'build_event_dataclass': 'build an Event dataclass with a DeferredMessage, topic, delay, and optional duration fields', 'create_event_graph': 'create an EventGraph from a start event and add subsequent events at start or end boundaries', 'add_event_at_end': "add an event to the EventGraph heap scheduled after the previous event's duration ends", 'implement_base_event_generator': 'implement a BaseEventGenerator subclass with generate_events and set_topics abstract methods'}
```

## File: facebookresearch_labgraph/labgraph/events/event_generator_node.py

Prompts

```
['create a DeferredMessage that lazily builds a Message with auto-injected timestamps on access', 'build an Event dataclass with a DeferredMessage, topic, delay, and optional duration fields', 'create an EventGraph from a start event and add subsequent events at start or end boundaries', "add an event to the EventGraph heap scheduled after the previous event's duration ends", 'implement a BaseEventGenerator subclass with generate_events and set_topics abstract methods', 'create a subclass of BaseEventGeneratorNode that publishes timed events to Labgraph topics', 'call setup_generator on a BaseEventGeneratorNode to attach a BaseEventGenerator instance', 'call generate_events on a BaseEventGeneratorNode to get an EventPublishingHeap of scheduled events', 'implement the abstract publish_events async method on a BaseEventGeneratorNode subclass to publish timed events', 'review how BaseEventGeneratorNodeMeta filters out WaitEndMessage topics and populates published_topics metadata']
```

Usage

```
{'create_event_generator_node': 'create a subclass of BaseEventGeneratorNode that publishes timed events to Labgraph topics', 'setup_generator_on_node': 'call setup_generator on a BaseEventGeneratorNode to attach a BaseEventGenerator instance', 'generate_events_from_node': 'call generate_events on a BaseEventGeneratorNode to get an EventPublishingHeap of scheduled events', 'implement_publish_events': 'implement the abstract publish_events async method on a BaseEventGeneratorNode subclass to publish timed events', 'review_metaclass_topic_filtering': 'review how BaseEventGeneratorNodeMeta filters out WaitEndMessage topics and populates published_topics metadata'}
```

