# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/instantiate/test_helpers.py

Prompts

```
['test the _locate function to dynamically resolve a dotted path string to a Python object', 'test that _locate raises ValueError when given a relative import path with leading dots', 'test the get_method function to resolve a dotted path to a callable method or function', 'test the get_class function to resolve a dotted path to a Python class', 'test the get_object function to resolve a dotted path to any Python object including modules', 'test hydra instantiate to create objects from config dicts with _target_ and keyword arguments', 'test hydra instantiate to recursively create nested objects from config with nested _target_ entries', 'test hydra instantiate with _partial_ flag to create functools.partial objects instead of full instances', 'test hydra instantiate to override the _target_ at call time and instantiate a different class', 'test hydra instantiate _convert_ modes to control conversion of nested DictConfig and ListConfig to primitives', 'test hydra instantiate with positional args and keyword arguments from config', 'test that instantiate raises InstantiationException when _args_ is a dict instead of a list', 'test hydra instantiate with config interpolation references in _args_ and kwargs', 'test hydra instantiate with runtime positional and keyword argument overrides', 'test recursive hydra instantiate with nested _args_ overrides on child configs', 'test that hydra instantiate correctly passes positional-only arguments via config _args_ or override args', 'run hydra utils instantiate with a config dict containing _target_ and _args_ for positional-only parameters', 'test instantiate when positional-only args are provided in the config _args_ list', 'test instantiate when positional-only args are passed as override arguments instead of config', 'test that override args take precedence over config _args_ when both are provided to instantiate']
```

Usage

```
{'test_locate': 'test the _locate function to dynamically resolve a dotted path string to a Python object', 'test_locate_relative_import_fails': 'test that _locate raises ValueError when given a relative import path with leading dots', 'test_get_method': 'test the get_method function to resolve a dotted path to a callable method or function', 'test_get_class': 'test the get_class function to resolve a dotted path to a Python class', 'test_get_object': 'test the get_object function to resolve a dotted path to any Python object including modules'}
```

## File: facebookresearch_hydra/tests/instantiate/test_instantiate.py

Prompts

```
['test the _locate function to dynamically resolve a dotted path string to a Python object', 'test that _locate raises ValueError when given a relative import path with leading dots', 'test the get_method function to resolve a dotted path to a callable method or function', 'test the get_class function to resolve a dotted path to a Python class', 'test the get_object function to resolve a dotted path to any Python object including modules', 'test hydra instantiate to create objects from config dicts with _target_ and keyword arguments', 'test hydra instantiate to recursively create nested objects from config with nested _target_ entries', 'test hydra instantiate with _partial_ flag to create functools.partial objects instead of full instances', 'test hydra instantiate to override the _target_ at call time and instantiate a different class', 'test hydra instantiate _convert_ modes to control conversion of nested DictConfig and ListConfig to primitives', 'test hydra instantiate with positional args and keyword arguments from config', 'test that instantiate raises InstantiationException when _args_ is a dict instead of a list', 'test hydra instantiate with config interpolation references in _args_ and kwargs', 'test hydra instantiate with runtime positional and keyword argument overrides', 'test recursive hydra instantiate with nested _args_ overrides on child configs', 'test that hydra instantiate correctly passes positional-only arguments via config _args_ or override args', 'run hydra utils instantiate with a config dict containing _target_ and _args_ for positional-only parameters', 'test instantiate when positional-only args are provided in the config _args_ list', 'test instantiate when positional-only args are passed as override arguments instead of config', 'test that override args take precedence over config _args_ when both are provided to instantiate']
```

Usage

```
{'test_class_instantiate': 'test hydra instantiate to create objects from config dicts with _target_ and keyword arguments', 'test_recursive_instantiation': 'test hydra instantiate to recursively create nested objects from config with nested _target_ entries', 'test_partial_instantiate': 'test hydra instantiate with _partial_ flag to create functools.partial objects instead of full instances', 'test_override_target': 'test hydra instantiate to override the _target_ at call time and instantiate a different class', 'test_convert_params': 'test hydra instantiate _convert_ modes to control conversion of nested DictConfig and ListConfig to primitives'}
```

## File: facebookresearch_hydra/tests/instantiate/test_positional.py

Prompts

```
['test the _locate function to dynamically resolve a dotted path string to a Python object', 'test that _locate raises ValueError when given a relative import path with leading dots', 'test the get_method function to resolve a dotted path to a callable method or function', 'test the get_class function to resolve a dotted path to a Python class', 'test the get_object function to resolve a dotted path to any Python object including modules', 'test hydra instantiate to create objects from config dicts with _target_ and keyword arguments', 'test hydra instantiate to recursively create nested objects from config with nested _target_ entries', 'test hydra instantiate with _partial_ flag to create functools.partial objects instead of full instances', 'test hydra instantiate to override the _target_ at call time and instantiate a different class', 'test hydra instantiate _convert_ modes to control conversion of nested DictConfig and ListConfig to primitives', 'test hydra instantiate with positional args and keyword arguments from config', 'test that instantiate raises InstantiationException when _args_ is a dict instead of a list', 'test hydra instantiate with config interpolation references in _args_ and kwargs', 'test hydra instantiate with runtime positional and keyword argument overrides', 'test recursive hydra instantiate with nested _args_ overrides on child configs', 'test that hydra instantiate correctly passes positional-only arguments via config _args_ or override args', 'run hydra utils instantiate with a config dict containing _target_ and _args_ for positional-only parameters', 'test instantiate when positional-only args are provided in the config _args_ list', 'test instantiate when positional-only args are passed as override arguments instead of config', 'test that override args take precedence over config _args_ when both are provided to instantiate']
```

Usage

```
{'test_instantiate_args_kwargs': 'test hydra instantiate with positional args and keyword arguments from config', 'test_instantiate_unsupported_args_type': 'test that instantiate raises InstantiationException when _args_ is a dict instead of a list', 'test_instantiate_args_kwargs_with_interpolation': 'test hydra instantiate with config interpolation references in _args_ and kwargs', 'test_instantiate_args_kwargs_with_override': 'test hydra instantiate with runtime positional and keyword argument overrides', 'test_recursive_instantiate_args_kwargs_with_override': 'test recursive hydra instantiate with nested _args_ overrides on child configs'}
```

## File: facebookresearch_hydra/tests/instantiate/test_positional_only_arguments.py

Prompts

```
['test the _locate function to dynamically resolve a dotted path string to a Python object', 'test that _locate raises ValueError when given a relative import path with leading dots', 'test the get_method function to resolve a dotted path to a callable method or function', 'test the get_class function to resolve a dotted path to a Python class', 'test the get_object function to resolve a dotted path to any Python object including modules', 'test hydra instantiate to create objects from config dicts with _target_ and keyword arguments', 'test hydra instantiate to recursively create nested objects from config with nested _target_ entries', 'test hydra instantiate with _partial_ flag to create functools.partial objects instead of full instances', 'test hydra instantiate to override the _target_ at call time and instantiate a different class', 'test hydra instantiate _convert_ modes to control conversion of nested DictConfig and ListConfig to primitives', 'test hydra instantiate with positional args and keyword arguments from config', 'test that instantiate raises InstantiationException when _args_ is a dict instead of a list', 'test hydra instantiate with config interpolation references in _args_ and kwargs', 'test hydra instantiate with runtime positional and keyword argument overrides', 'test recursive hydra instantiate with nested _args_ overrides on child configs', 'test that hydra instantiate correctly passes positional-only arguments via config _args_ or override args', 'run hydra utils instantiate with a config dict containing _target_ and _args_ for positional-only parameters', 'test instantiate when positional-only args are provided in the config _args_ list', 'test instantiate when positional-only args are passed as override arguments instead of config', 'test that override args take precedence over config _args_ when both are provided to instantiate']
```

Usage

```
{'test_positional_only_arguments': 'test that hydra instantiate correctly passes positional-only arguments via config _args_ or override args', 'run_hydra_instantiate_with_pos_only': 'run hydra utils instantiate with a config dict containing _target_ and _args_ for positional-only parameters', 'test_instantiate_pos_only_in_config': 'test instantiate when positional-only args are provided in the config _args_ list', 'test_instantiate_pos_only_in_override': 'test instantiate when positional-only args are passed as override arguments instead of config', 'test_instantiate_pos_only_override_precedence': 'test that override args take precedence over config _args_ when both are provided to instantiate'}
```

