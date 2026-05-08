# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/zmq_node/tests/test_zmq_node.py

Prompts

```
['test the ZMQPollerNode reads samples from a ZMQ PUB socket and echoes them through a labgraph graph', 'test the ZMQSenderNode reads samples from a labgraph source node and writes them to a ZMQ socket', 'test ZMQSenderNode and ZMQPollerNode work together in a graph using ParallelRunner for send and receive', 'create a labgraph Node subclass with a publisher method that yields ZMQMessage samples to a topic', 'create a labgraph Node subclass with a subscriber method that receives ZMQMessage samples and writes them to a file']
```

Usage

```
{'test_zmq_poller_node': 'test the ZMQPollerNode reads samples from a ZMQ PUB socket and echoes them through a labgraph graph', 'test_zmq_sender_node': 'test the ZMQSenderNode reads samples from a labgraph source node and writes them to a ZMQ socket', 'test_zmq_send_and_poll': 'test ZMQSenderNode and ZMQPollerNode work together in a graph using ParallelRunner for send and receive', 'create_zmq_source_node': 'create a labgraph Node subclass with a publisher method that yields ZMQMessage samples to a topic', 'create_zmq_sink_node': 'create a labgraph Node subclass with a subscriber method that receives ZMQMessage samples and writes them to a file'}
```

