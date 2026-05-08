# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/simulations/function_generator.py

Prompts

```
['create a FunctionChannelConfig dataclass with a shape tuple to configure generator channels', 'create a FunctionGeneratorMessage with a numpy ndarray data field for experiment samples', 'review the FunctionGenerator set_channel_config method to configure data generation across channels', 'review the FunctionGenerator abstract next_sample method that returns the next experiment sample', 'review the FunctionGenerator next_n_samples method that returns a list of n experiment samples', 'create a FunctionGeneratorNode instance that generates samples to the graph based on user-specified functions', 'set a FunctionGenerator on a FunctionGeneratorNode to configure sample generation for the simulation graph', 'review the FunctionGeneratorNode class that extends Node and uses ExperimentClock for time tracking in simulations', 'summarize the FunctionGeneratorNode constructor that initializes an ExperimentClock for time-based sample generation', 'test the FunctionGeneratorNode set_generator method to verify a FunctionGenerator is properly assigned to the node']
```

Usage

```
{'create_FunctionChannelConfig': 'create a FunctionChannelConfig dataclass with a shape tuple to configure generator channels', 'create_FunctionGeneratorMessage': 'create a FunctionGeneratorMessage with a numpy ndarray data field for experiment samples', 'review_FunctionGenerator_set_channel_config': 'review the FunctionGenerator set_channel_config method to configure data generation across channels', 'review_FunctionGenerator_next_sample': 'review the FunctionGenerator abstract next_sample method that returns the next experiment sample', 'review_FunctionGenerator_next_n_samples': 'review the FunctionGenerator next_n_samples method that returns a list of n experiment samples'}
```

## File: facebookresearch_labgraph/labgraph/simulations/function_generator_node.py

Prompts

```
['create a FunctionChannelConfig dataclass with a shape tuple to configure generator channels', 'create a FunctionGeneratorMessage with a numpy ndarray data field for experiment samples', 'review the FunctionGenerator set_channel_config method to configure data generation across channels', 'review the FunctionGenerator abstract next_sample method that returns the next experiment sample', 'review the FunctionGenerator next_n_samples method that returns a list of n experiment samples', 'create a FunctionGeneratorNode instance that generates samples to the graph based on user-specified functions', 'set a FunctionGenerator on a FunctionGeneratorNode to configure sample generation for the simulation graph', 'review the FunctionGeneratorNode class that extends Node and uses ExperimentClock for time tracking in simulations', 'summarize the FunctionGeneratorNode constructor that initializes an ExperimentClock for time-based sample generation', 'test the FunctionGeneratorNode set_generator method to verify a FunctionGenerator is properly assigned to the node']
```

Usage

```
{'create_FunctionGeneratorNode': 'create a FunctionGeneratorNode instance that generates samples to the graph based on user-specified functions', 'set_generator_on_FunctionGeneratorNode': 'set a FunctionGenerator on a FunctionGeneratorNode to configure sample generation for the simulation graph', 'review_FunctionGeneratorNode_class': 'review the FunctionGeneratorNode class that extends Node and uses ExperimentClock for time tracking in simulations', 'summarize_FunctionGeneratorNode_init': 'summarize the FunctionGeneratorNode constructor that initializes an ExperimentClock for time-based sample generation', 'test_FunctionGeneratorNode_set_generator': 'test the FunctionGeneratorNode set_generator method to verify a FunctionGenerator is properly assigned to the node'}
```

