# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/extensions/graphviz_support/graphviz_support/tests/demo_graph/amplifier.py

Prompts

```
['create an AmplifierConfig with an out_in_ratio float value for the Amplifier node', 'build a labgraph Amplifier node that subscribes to input messages and publishes amplified output', 'run the Amplifier amplify method to multiply input message data by the configured out_in_ratio', 'test the Amplifier output method to verify it multiplies input by the out_in_ratio config value', 'review the Amplifier AMPLIFIER_INPUT and AMPLIFIER_OUTPUT topic definitions for RandomMessage types', 'create a labgraph Attenuator node that applies signal attenuation to incoming RandomMessage data', 'create an AttenuatorConfig with a float attenuation value for the Attenuator node', 'run the async attenuate method to process RandomMessage data through the attenuation formula', 'test the output method to verify attenuation calculation using pow(10, attenuation/20) formula', 'review the Attenuator class subscriber-publisher pattern for labgraph node signal processing', 'create a labgraph Demo graph that wires NoiseGenerator, RollingAverager, Amplifier, Attenuator, and Sink modules together', 'run the Demo setup method to configure all modules with their respective config objects', 'review the Demo connections method that defines data flow between module inputs and outputs', 'summarize the Demo process_modules method that returns all modules in the graph as a tuple', 'test the Demo class to verify it correctly extends lg.Graph and configures its five processing modules', 'create a SinkState class with optional numpy array fields data_1, data_2, and data_3', 'create a Sink labgraph Node with three input topics for RandomMessage', 'review the Sink got_message subscriber method that stores message data into state', 'review the Sink do_something main method that raises NormalTermination', 'summarize the three Sink subscriber methods that route RandomMessage data to state fields']
```

Usage

```
{'create_AmplifierConfig': 'create an AmplifierConfig with an out_in_ratio float value for the Amplifier node', 'build_Amplifier_node': 'build a labgraph Amplifier node that subscribes to input messages and publishes amplified output', 'run_Amplifier_amplify': 'run the Amplifier amplify method to multiply input message data by the configured out_in_ratio', 'test_Amplifier_output': 'test the Amplifier output method to verify it multiplies input by the out_in_ratio config value', 'review_Amplifier_AMPLIFIER_INPUT': 'review the Amplifier AMPLIFIER_INPUT and AMPLIFIER_OUTPUT topic definitions for RandomMessage types'}
```

## File: facebookresearch_labgraph/extensions/graphviz_support/graphviz_support/tests/demo_graph/attenuator.py

Prompts

```
['create an AmplifierConfig with an out_in_ratio float value for the Amplifier node', 'build a labgraph Amplifier node that subscribes to input messages and publishes amplified output', 'run the Amplifier amplify method to multiply input message data by the configured out_in_ratio', 'test the Amplifier output method to verify it multiplies input by the out_in_ratio config value', 'review the Amplifier AMPLIFIER_INPUT and AMPLIFIER_OUTPUT topic definitions for RandomMessage types', 'create a labgraph Attenuator node that applies signal attenuation to incoming RandomMessage data', 'create an AttenuatorConfig with a float attenuation value for the Attenuator node', 'run the async attenuate method to process RandomMessage data through the attenuation formula', 'test the output method to verify attenuation calculation using pow(10, attenuation/20) formula', 'review the Attenuator class subscriber-publisher pattern for labgraph node signal processing', 'create a labgraph Demo graph that wires NoiseGenerator, RollingAverager, Amplifier, Attenuator, and Sink modules together', 'run the Demo setup method to configure all modules with their respective config objects', 'review the Demo connections method that defines data flow between module inputs and outputs', 'summarize the Demo process_modules method that returns all modules in the graph as a tuple', 'test the Demo class to verify it correctly extends lg.Graph and configures its five processing modules', 'create a SinkState class with optional numpy array fields data_1, data_2, and data_3', 'create a Sink labgraph Node with three input topics for RandomMessage', 'review the Sink got_message subscriber method that stores message data into state', 'review the Sink do_something main method that raises NormalTermination', 'summarize the three Sink subscriber methods that route RandomMessage data to state fields']
```

Usage

```
{'create_attenuator_node': 'create a labgraph Attenuator node that applies signal attenuation to incoming RandomMessage data', 'create_attenuator_config': 'create an AttenuatorConfig with a float attenuation value for the Attenuator node', 'run_attenuate_method': 'run the async attenuate method to process RandomMessage data through the attenuation formula', 'test_output_method': 'test the output method to verify attenuation calculation using pow(10, attenuation/20) formula', 'review_attenuator_class': 'review the Attenuator class subscriber-publisher pattern for labgraph node signal processing'}
```

## File: facebookresearch_labgraph/extensions/graphviz_support/graphviz_support/tests/demo_graph/demo.py

Prompts

```
['create an AmplifierConfig with an out_in_ratio float value for the Amplifier node', 'build a labgraph Amplifier node that subscribes to input messages and publishes amplified output', 'run the Amplifier amplify method to multiply input message data by the configured out_in_ratio', 'test the Amplifier output method to verify it multiplies input by the out_in_ratio config value', 'review the Amplifier AMPLIFIER_INPUT and AMPLIFIER_OUTPUT topic definitions for RandomMessage types', 'create a labgraph Attenuator node that applies signal attenuation to incoming RandomMessage data', 'create an AttenuatorConfig with a float attenuation value for the Attenuator node', 'run the async attenuate method to process RandomMessage data through the attenuation formula', 'test the output method to verify attenuation calculation using pow(10, attenuation/20) formula', 'review the Attenuator class subscriber-publisher pattern for labgraph node signal processing', 'create a labgraph Demo graph that wires NoiseGenerator, RollingAverager, Amplifier, Attenuator, and Sink modules together', 'run the Demo setup method to configure all modules with their respective config objects', 'review the Demo connections method that defines data flow between module inputs and outputs', 'summarize the Demo process_modules method that returns all modules in the graph as a tuple', 'test the Demo class to verify it correctly extends lg.Graph and configures its five processing modules', 'create a SinkState class with optional numpy array fields data_1, data_2, and data_3', 'create a Sink labgraph Node with three input topics for RandomMessage', 'review the Sink got_message subscriber method that stores message data into state', 'review the Sink do_something main method that raises NormalTermination', 'summarize the three Sink subscriber methods that route RandomMessage data to state fields']
```

Usage

```
{'create_Demo_graph': 'create a labgraph Demo graph that wires NoiseGenerator, RollingAverager, Amplifier, Attenuator, and Sink modules together', 'run_Demo_setup': 'run the Demo setup method to configure all modules with their respective config objects', 'review_Demo_connections': 'review the Demo connections method that defines data flow between module inputs and outputs', 'summarize_Demo_process_modules': 'summarize the Demo process_modules method that returns all modules in the graph as a tuple', 'test_Demo_class': 'test the Demo class to verify it correctly extends lg.Graph and configures its five processing modules'}
```

## File: facebookresearch_labgraph/extensions/graphviz_support/graphviz_support/tests/demo_graph/sink.py

Prompts

```
['create an AmplifierConfig with an out_in_ratio float value for the Amplifier node', 'build a labgraph Amplifier node that subscribes to input messages and publishes amplified output', 'run the Amplifier amplify method to multiply input message data by the configured out_in_ratio', 'test the Amplifier output method to verify it multiplies input by the out_in_ratio config value', 'review the Amplifier AMPLIFIER_INPUT and AMPLIFIER_OUTPUT topic definitions for RandomMessage types', 'create a labgraph Attenuator node that applies signal attenuation to incoming RandomMessage data', 'create an AttenuatorConfig with a float attenuation value for the Attenuator node', 'run the async attenuate method to process RandomMessage data through the attenuation formula', 'test the output method to verify attenuation calculation using pow(10, attenuation/20) formula', 'review the Attenuator class subscriber-publisher pattern for labgraph node signal processing', 'create a labgraph Demo graph that wires NoiseGenerator, RollingAverager, Amplifier, Attenuator, and Sink modules together', 'run the Demo setup method to configure all modules with their respective config objects', 'review the Demo connections method that defines data flow between module inputs and outputs', 'summarize the Demo process_modules method that returns all modules in the graph as a tuple', 'test the Demo class to verify it correctly extends lg.Graph and configures its five processing modules', 'create a SinkState class with optional numpy array fields data_1, data_2, and data_3', 'create a Sink labgraph Node with three input topics for RandomMessage', 'review the Sink got_message subscriber method that stores message data into state', 'review the Sink do_something main method that raises NormalTermination', 'summarize the three Sink subscriber methods that route RandomMessage data to state fields']
```

Usage

```
{'create_SinkState': 'create a SinkState class with optional numpy array fields data_1, data_2, and data_3', 'create_Sink_node': 'create a Sink labgraph Node with three input topics for RandomMessage', 'review_Sink_got_message': 'review the Sink got_message subscriber method that stores message data into state', 'review_Sink_do_something': 'review the Sink do_something main method that raises NormalTermination', 'summarize_Sink_subscribers': 'summarize the three Sink subscriber methods that route RandomMessage data to state fields'}
```

