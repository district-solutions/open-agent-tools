# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/signal_processing/synthetic/nodes/mixer_two_input_node.py

Prompts

```
['create a MixerTwoInputConfig with left and right numpy weight matrices for signal mixing', 'build a MixerTwoInputNode labgraph node that mixes two input signals using configurable weight matrices', 'test the mix_samples async publisher method that combines left and right signal samples into a weighted output', 'review the left_input subscriber method that validates and queues incoming left signal samples', 'refactor the MixerTwoInputNode setup method to validate weight matrix dimensions and initialize input queues', 'create a SignalCaptureConfig with num_capture to set how many samples the node should capture', 'build a SignalCaptureNode labgraph node that captures SignalSampleMessage samples and terminates after num_capture', 'test the sample_sink subscriber method to verify it appends samples and raises NormalTermination after num_capture', 'review the SignalCaptureNode samples property to retrieve captured SignalSampleMessage samples from the node', 'summarize the SignalCaptureNode class that captures SignalSampleMessage samples on SAMPLE_TOPIC and terminates after reaching num_capture', 'create a SignalGeneratorNode subclass to generate custom signal samples using a FunctionGenerator', 'run the publish_samples async publisher to yield SignalSampleMessage samples at regular intervals', 'setup the SignalGeneratorNode by initializing an asyncio shutdown event for lifecycle management', 'cleanup the SignalGeneratorNode by setting the shutdown event to stop sample publishing', 'review the SignalGeneratorNode class and its async publisher pattern for LabGraph signal generation']
```

Usage

```
{'create_MixerTwoInputConfig': 'create a MixerTwoInputConfig with left and right numpy weight matrices for signal mixing', 'build_MixerTwoInputNode': 'build a MixerTwoInputNode labgraph node that mixes two input signals using configurable weight matrices', 'test_mix_samples': 'test the mix_samples async publisher method that combines left and right signal samples into a weighted output', 'review_left_input_subscriber': 'review the left_input subscriber method that validates and queues incoming left signal samples', 'refactor_MixerTwoInputNode_setup': 'refactor the MixerTwoInputNode setup method to validate weight matrix dimensions and initialize input queues'}
```

## File: facebookresearch_labgraph/signal_processing/synthetic/nodes/signal_capture_node.py

Prompts

```
['create a MixerTwoInputConfig with left and right numpy weight matrices for signal mixing', 'build a MixerTwoInputNode labgraph node that mixes two input signals using configurable weight matrices', 'test the mix_samples async publisher method that combines left and right signal samples into a weighted output', 'review the left_input subscriber method that validates and queues incoming left signal samples', 'refactor the MixerTwoInputNode setup method to validate weight matrix dimensions and initialize input queues', 'create a SignalCaptureConfig with num_capture to set how many samples the node should capture', 'build a SignalCaptureNode labgraph node that captures SignalSampleMessage samples and terminates after num_capture', 'test the sample_sink subscriber method to verify it appends samples and raises NormalTermination after num_capture', 'review the SignalCaptureNode samples property to retrieve captured SignalSampleMessage samples from the node', 'summarize the SignalCaptureNode class that captures SignalSampleMessage samples on SAMPLE_TOPIC and terminates after reaching num_capture', 'create a SignalGeneratorNode subclass to generate custom signal samples using a FunctionGenerator', 'run the publish_samples async publisher to yield SignalSampleMessage samples at regular intervals', 'setup the SignalGeneratorNode by initializing an asyncio shutdown event for lifecycle management', 'cleanup the SignalGeneratorNode by setting the shutdown event to stop sample publishing', 'review the SignalGeneratorNode class and its async publisher pattern for LabGraph signal generation']
```

Usage

```
{'create_signal_capture_config': 'create a SignalCaptureConfig with num_capture to set how many samples the node should capture', 'build_signal_capture_node': 'build a SignalCaptureNode labgraph node that captures SignalSampleMessage samples and terminates after num_capture', 'test_sample_sink': 'test the sample_sink subscriber method to verify it appends samples and raises NormalTermination after num_capture', 'review_signal_capture_node_samples': 'review the SignalCaptureNode samples property to retrieve captured SignalSampleMessage samples from the node', 'summarize_signal_capture_node': 'summarize the SignalCaptureNode class that captures SignalSampleMessage samples on SAMPLE_TOPIC and terminates after reaching num_capture'}
```

## File: facebookresearch_labgraph/signal_processing/synthetic/nodes/signal_generator_node.py

Prompts

```
['create a MixerTwoInputConfig with left and right numpy weight matrices for signal mixing', 'build a MixerTwoInputNode labgraph node that mixes two input signals using configurable weight matrices', 'test the mix_samples async publisher method that combines left and right signal samples into a weighted output', 'review the left_input subscriber method that validates and queues incoming left signal samples', 'refactor the MixerTwoInputNode setup method to validate weight matrix dimensions and initialize input queues', 'create a SignalCaptureConfig with num_capture to set how many samples the node should capture', 'build a SignalCaptureNode labgraph node that captures SignalSampleMessage samples and terminates after num_capture', 'test the sample_sink subscriber method to verify it appends samples and raises NormalTermination after num_capture', 'review the SignalCaptureNode samples property to retrieve captured SignalSampleMessage samples from the node', 'summarize the SignalCaptureNode class that captures SignalSampleMessage samples on SAMPLE_TOPIC and terminates after reaching num_capture', 'create a SignalGeneratorNode subclass to generate custom signal samples using a FunctionGenerator', 'run the publish_samples async publisher to yield SignalSampleMessage samples at regular intervals', 'setup the SignalGeneratorNode by initializing an asyncio shutdown event for lifecycle management', 'cleanup the SignalGeneratorNode by setting the shutdown event to stop sample publishing', 'review the SignalGeneratorNode class and its async publisher pattern for LabGraph signal generation']
```

Usage

```
{'create_signal_generator_node': 'create a SignalGeneratorNode subclass to generate custom signal samples using a FunctionGenerator', 'run_publish_samples': 'run the publish_samples async publisher to yield SignalSampleMessage samples at regular intervals', 'setup_signal_generator': 'setup the SignalGeneratorNode by initializing an asyncio shutdown event for lifecycle management', 'cleanup_signal_generator': 'cleanup the SignalGeneratorNode by setting the shutdown event to stop sample publishing', 'review_signal_generator_node': 'review the SignalGeneratorNode class and its async publisher pattern for LabGraph signal generation'}
```

