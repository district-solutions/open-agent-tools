# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/devices/protocols/lsl/lsl_poller_node.py

Prompts

```
['create an LSLPollerConfig with a custom stream type and poll time for labgraph', 'build an LSLPollerNode that resolves an LSL stream and creates a StreamInlet in setup', 'run the async lsl_subscriber publisher loop to pull samples and yield LSLMessages', 'review the LSLPollerNode setup method to resolve streams by type and create an inlet', 'summarize the LSLPollerNode class that polls LSL streams and publishes samples as LSLMessages', 'create an LSLSenderConfig with stream_name, stream_type, n_channels, unique_identifier, and sample_rate fields', 'setup an LSLSenderNode that creates a StreamInfo and StreamOutlet using the config parameters', 'publish LSLMessage data samples to an LSL stream outlet via the lsl_publisher subscriber method', 'review the LSLSenderNode class that forwards LabGraph topic messages to an LSL stream outlet', 'refactor the lsl_publisher async method to handle sample pushing with configurable POLL_TIME intervals']
```

Usage

```
{'create_lsl_poller_config': 'create an LSLPollerConfig with a custom stream type and poll time for labgraph', 'build_lsl_poller_node': 'build an LSLPollerNode that resolves an LSL stream and creates a StreamInlet in setup', 'run_lsl_subscriber': 'run the async lsl_subscriber publisher loop to pull samples and yield LSLMessages', 'review_lsl_poller_node_setup': 'review the LSLPollerNode setup method to resolve streams by type and create an inlet', 'summarize_lsl_poller_node': 'summarize the LSLPollerNode class that polls LSL streams and publishes samples as LSLMessages'}
```

## File: facebookresearch_labgraph/labgraph/devices/protocols/lsl/lsl_sender_node.py

Prompts

```
['create an LSLPollerConfig with a custom stream type and poll time for labgraph', 'build an LSLPollerNode that resolves an LSL stream and creates a StreamInlet in setup', 'run the async lsl_subscriber publisher loop to pull samples and yield LSLMessages', 'review the LSLPollerNode setup method to resolve streams by type and create an inlet', 'summarize the LSLPollerNode class that polls LSL streams and publishes samples as LSLMessages', 'create an LSLSenderConfig with stream_name, stream_type, n_channels, unique_identifier, and sample_rate fields', 'setup an LSLSenderNode that creates a StreamInfo and StreamOutlet using the config parameters', 'publish LSLMessage data samples to an LSL stream outlet via the lsl_publisher subscriber method', 'review the LSLSenderNode class that forwards LabGraph topic messages to an LSL stream outlet', 'refactor the lsl_publisher async method to handle sample pushing with configurable POLL_TIME intervals']
```

Usage

```
{'create_LSLSenderConfig': 'create an LSLSenderConfig with stream_name, stream_type, n_channels, unique_identifier, and sample_rate fields', 'setup_LSLSenderNode': 'setup an LSLSenderNode that creates a StreamInfo and StreamOutlet using the config parameters', 'publish_LSLMessage': 'publish LSLMessage data samples to an LSL stream outlet via the lsl_publisher subscriber method', 'review_LSLSenderNode': 'review the LSLSenderNode class that forwards LabGraph topic messages to an LSL stream outlet', 'refactor_lsl_publisher': 'refactor the lsl_publisher async method to handle sample pushing with configurable POLL_TIME intervals'}
```

