# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/src/beanmachine/ppl/model/rv_identifier.py

Prompts

```
['create an RVIdentifier dataclass instance with a wrapper callable and arguments tuple for a Bean Machine random variable', 'check if an RVIdentifier wrapper has the is_functional attribute to determine if it is a functional random variable', 'check if an RVIdentifier wrapper has the is_random_variable attribute to determine if it represents a random variable', 'get the underlying wrapped function from an RVIdentifier instance using the function property', 'compare two RVIdentifier instances using less-than comparison to sort them by their string representation', 'create a stochastic random variable in a Bean Machine model using the random_variable decorator', 'create a deterministic functional query in a Bean Machine model using the functional decorator', 'create a variational inference parameter in a Bean Machine model using the param decorator', 'get a unique RVIdentifier key for a random variable using get_func_key with wrapper and arguments', 'review the StatisticalModel class and its decorators for defining probabilistic models in Bean Machine', 'create a beanmachine logger with console and file handlers at configurable log levels', 'create a beanmachine logger with DEBUG_UPDATES console level and INFO file level for detailed debugging', 'use the LogLevel enum to set custom logging levels like DEBUG_GRAPH or DEBUG_PROPOSER', 'check if a tensor is one of the supported float types using the float_types tuple', 'create a beanmachine logger with WARNING console level and INFO file level using defaults']
```

Usage

```
{'create_RVIdentifier': 'create an RVIdentifier dataclass instance with a wrapper callable and arguments tuple for a Bean Machine random variable', 'check_is_functional': 'check if an RVIdentifier wrapper has the is_functional attribute to determine if it is a functional random variable', 'check_is_random_variable': 'check if an RVIdentifier wrapper has the is_random_variable attribute to determine if it represents a random variable', 'get_wrapped_function': 'get the underlying wrapped function from an RVIdentifier instance using the function property', 'compare_RVIdentifier': 'compare two RVIdentifier instances using less-than comparison to sort them by their string representation'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/model/statistical_model.py

Prompts

```
['create an RVIdentifier dataclass instance with a wrapper callable and arguments tuple for a Bean Machine random variable', 'check if an RVIdentifier wrapper has the is_functional attribute to determine if it is a functional random variable', 'check if an RVIdentifier wrapper has the is_random_variable attribute to determine if it represents a random variable', 'get the underlying wrapped function from an RVIdentifier instance using the function property', 'compare two RVIdentifier instances using less-than comparison to sort them by their string representation', 'create a stochastic random variable in a Bean Machine model using the random_variable decorator', 'create a deterministic functional query in a Bean Machine model using the functional decorator', 'create a variational inference parameter in a Bean Machine model using the param decorator', 'get a unique RVIdentifier key for a random variable using get_func_key with wrapper and arguments', 'review the StatisticalModel class and its decorators for defining probabilistic models in Bean Machine', 'create a beanmachine logger with console and file handlers at configurable log levels', 'create a beanmachine logger with DEBUG_UPDATES console level and INFO file level for detailed debugging', 'use the LogLevel enum to set custom logging levels like DEBUG_GRAPH or DEBUG_PROPOSER', 'check if a tensor is one of the supported float types using the float_types tuple', 'create a beanmachine logger with WARNING console level and INFO file level using defaults']
```

Usage

```
{'create_random_variable': 'create a stochastic random variable in a Bean Machine model using the random_variable decorator', 'create_functional': 'create a deterministic functional query in a Bean Machine model using the functional decorator', 'create_param': 'create a variational inference parameter in a Bean Machine model using the param decorator', 'get_func_key': 'get a unique RVIdentifier key for a random variable using get_func_key with wrapper and arguments', 'review_statistical_model': 'review the StatisticalModel class and its decorators for defining probabilistic models in Bean Machine'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/model/utils.py

Prompts

```
['create an RVIdentifier dataclass instance with a wrapper callable and arguments tuple for a Bean Machine random variable', 'check if an RVIdentifier wrapper has the is_functional attribute to determine if it is a functional random variable', 'check if an RVIdentifier wrapper has the is_random_variable attribute to determine if it represents a random variable', 'get the underlying wrapped function from an RVIdentifier instance using the function property', 'compare two RVIdentifier instances using less-than comparison to sort them by their string representation', 'create a stochastic random variable in a Bean Machine model using the random_variable decorator', 'create a deterministic functional query in a Bean Machine model using the functional decorator', 'create a variational inference parameter in a Bean Machine model using the param decorator', 'get a unique RVIdentifier key for a random variable using get_func_key with wrapper and arguments', 'review the StatisticalModel class and its decorators for defining probabilistic models in Bean Machine', 'create a beanmachine logger with console and file handlers at configurable log levels', 'create a beanmachine logger with DEBUG_UPDATES console level and INFO file level for detailed debugging', 'use the LogLevel enum to set custom logging levels like DEBUG_GRAPH or DEBUG_PROPOSER', 'check if a tensor is one of the supported float types using the float_types tuple', 'create a beanmachine logger with WARNING console level and INFO file level using defaults']
```

Usage

```
{'get_beanmachine_logger': 'create a beanmachine logger with console and file handlers at configurable log levels', 'get_beanmachine_logger_debug': 'create a beanmachine logger with DEBUG_UPDATES console level and INFO file level for detailed debugging', 'LogLevel_enum': 'use the LogLevel enum to set custom logging levels like DEBUG_GRAPH or DEBUG_PROPOSER', 'float_types_tuple': 'check if a tensor is one of the supported float types using the float_types tuple', 'get_beanmachine_logger_minimal': 'create a beanmachine logger with WARNING console level and INFO file level using defaults'}
```

