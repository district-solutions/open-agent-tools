# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/zmq_node/zmq_poller_node.py

Prompts

```
['create a ZMQPollerConfig with read_addr, zmq_topic, and optional poll_time for ZMQ polling', 'build a ZMQPollerNode that polls data from a ZMQ SUB socket and publishes ZMQMessages', 'review the ZMQPollerNode setup method that creates an asyncio ZMQ SUB socket and subscribes to a topic', 'test the ZMQPollerNode socket_monitor background task that watches for ZMQ connection events', 'summarize the ZMQPollerNode zmq_publisher async generator that yields ZMQMessage data on the topic', 'create a ZMQSenderConfig with write_addr and zmq_topic fields for ZMQ sender node configuration', 'build a ZMQSenderNode that subscribes to Labgraph messages and forwards them to a ZMQ PUB socket', 'review the ZMQSenderNode setup method that creates an asyncio ZMQ context and binds a PUB socket', 'test the ZMQSenderNode zmq_subscriber method that sends multipart messages to connected ZMQ subscribers', 'summarize the ZMQSenderNode socket monitor background task that tracks subscriber connection and disconnection events']
```

Usage

```
{'create_ZMQPollerConfig': 'create a ZMQPollerConfig with read_addr, zmq_topic, and optional poll_time for ZMQ polling', 'build_ZMQPollerNode': 'build a ZMQPollerNode that polls data from a ZMQ SUB socket and publishes ZMQMessages', 'review_ZMQPollerNode_setup': 'review the ZMQPollerNode setup method that creates an asyncio ZMQ SUB socket and subscribes to a topic', 'test_socket_monitor': 'test the ZMQPollerNode socket_monitor background task that watches for ZMQ connection events', 'summarize_zmq_publisher': 'summarize the ZMQPollerNode zmq_publisher async generator that yields ZMQMessage data on the topic'}
```

## File: facebookresearch_labgraph/labgraph/zmq_node/zmq_sender_node.py

Prompts

```
['create a ZMQPollerConfig with read_addr, zmq_topic, and optional poll_time for ZMQ polling', 'build a ZMQPollerNode that polls data from a ZMQ SUB socket and publishes ZMQMessages', 'review the ZMQPollerNode setup method that creates an asyncio ZMQ SUB socket and subscribes to a topic', 'test the ZMQPollerNode socket_monitor background task that watches for ZMQ connection events', 'summarize the ZMQPollerNode zmq_publisher async generator that yields ZMQMessage data on the topic', 'create a ZMQSenderConfig with write_addr and zmq_topic fields for ZMQ sender node configuration', 'build a ZMQSenderNode that subscribes to Labgraph messages and forwards them to a ZMQ PUB socket', 'review the ZMQSenderNode setup method that creates an asyncio ZMQ context and binds a PUB socket', 'test the ZMQSenderNode zmq_subscriber method that sends multipart messages to connected ZMQ subscribers', 'summarize the ZMQSenderNode socket monitor background task that tracks subscriber connection and disconnection events']
```

Usage

```
{'create_ZMQSenderConfig': 'create a ZMQSenderConfig with write_addr and zmq_topic fields for ZMQ sender node configuration', 'build_ZMQSenderNode': 'build a ZMQSenderNode that subscribes to Labgraph messages and forwards them to a ZMQ PUB socket', 'review_ZMQSenderNode_setup': 'review the ZMQSenderNode setup method that creates an asyncio ZMQ context and binds a PUB socket', 'test_ZMQSenderNode_zmq_subscriber': 'test the ZMQSenderNode zmq_subscriber method that sends multipart messages to connected ZMQ subscribers', 'summarize_ZMQSenderNode_socket_monitor': 'summarize the ZMQSenderNode socket monitor background task that tracks subscriber connection and disconnection events'}
```

