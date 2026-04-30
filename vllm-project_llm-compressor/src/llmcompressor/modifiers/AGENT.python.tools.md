# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/factory.py

Prompts

```
['create a modifier instance by type name with keyword arguments and registry flags', 'register a custom modifier class with the factory by type name for later instantiation', 'refresh the factory by reloading all modifier classes from the main and experimental packages', 'load modifier classes from a given package path and return a mapping of name to class', 'review the ModifierFactory class and its registry-based modifier instantiation pattern', 'create a subclass of ModifierInterface implementing its abstract lifecycle methods', 'test the initialized property of a ModifierInterface subclass returns True after initialize is called', 'test the finalized property of a ModifierInterface subclass returns True after finalize is called', 'run initialize on a ModifierInterface subclass with a State object and optional kwargs', 'run finalize on a ModifierInterface subclass with a State object and optional kwargs', 'run update_event on a ModifierInterface subclass with a State and Event object', 'create a subclass of Modifier that implements on_initialize and on_update for model compression', 'initialize a Modifier instance with a State object and trigger its lifecycle setup', 'update a Modifier with an Event to trigger on_start, on_update, or on_end based on start/end steps', 'finalize an initialized Modifier to clean up resources and mark it as finalized', 'check whether a Modifier is initialized, finalized, started, or ended via lifecycle properties']
```

Usage

```
{'create_modifier': 'create a modifier instance by type name with keyword arguments and registry flags', 'register_modifier': 'register a custom modifier class with the factory by type name for later instantiation', 'refresh_modifiers': 'refresh the factory by reloading all modifier classes from the main and experimental packages', 'load_from_package': 'load modifier classes from a given package path and return a mapping of name to class', 'review_modifier_factory': 'review the ModifierFactory class and its registry-based modifier instantiation pattern'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/interface.py

Prompts

```
['create a modifier instance by type name with keyword arguments and registry flags', 'register a custom modifier class with the factory by type name for later instantiation', 'refresh the factory by reloading all modifier classes from the main and experimental packages', 'load modifier classes from a given package path and return a mapping of name to class', 'review the ModifierFactory class and its registry-based modifier instantiation pattern', 'create a subclass of ModifierInterface implementing its abstract lifecycle methods', 'test the initialized property of a ModifierInterface subclass returns True after initialize is called', 'test the finalized property of a ModifierInterface subclass returns True after finalize is called', 'run initialize on a ModifierInterface subclass with a State object and optional kwargs', 'run finalize on a ModifierInterface subclass with a State object and optional kwargs', 'run update_event on a ModifierInterface subclass with a State and Event object', 'create a subclass of Modifier that implements on_initialize and on_update for model compression', 'initialize a Modifier instance with a State object and trigger its lifecycle setup', 'update a Modifier with an Event to trigger on_start, on_update, or on_end based on start/end steps', 'finalize an initialized Modifier to clean up resources and mark it as finalized', 'check whether a Modifier is initialized, finalized, started, or ended via lifecycle properties']
```

Usage

```
{'create_ModifierInterface_subclass': 'create a subclass of ModifierInterface implementing its abstract lifecycle methods', 'test_initialized_property': 'test the initialized property of a ModifierInterface subclass returns True after initialize is called', 'test_finalized_property': 'test the finalized property of a ModifierInterface subclass returns True after finalize is called', 'run_initialize_modifier': 'run initialize on a ModifierInterface subclass with a State object and optional kwargs', 'run_finalize_modifier': 'run finalize on a ModifierInterface subclass with a State object and optional kwargs', 'run_update_event_modifier': 'run update_event on a ModifierInterface subclass with a State and Event object'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/modifier.py

Prompts

```
['create a modifier instance by type name with keyword arguments and registry flags', 'register a custom modifier class with the factory by type name for later instantiation', 'refresh the factory by reloading all modifier classes from the main and experimental packages', 'load modifier classes from a given package path and return a mapping of name to class', 'review the ModifierFactory class and its registry-based modifier instantiation pattern', 'create a subclass of ModifierInterface implementing its abstract lifecycle methods', 'test the initialized property of a ModifierInterface subclass returns True after initialize is called', 'test the finalized property of a ModifierInterface subclass returns True after finalize is called', 'run initialize on a ModifierInterface subclass with a State object and optional kwargs', 'run finalize on a ModifierInterface subclass with a State object and optional kwargs', 'run update_event on a ModifierInterface subclass with a State and Event object', 'create a subclass of Modifier that implements on_initialize and on_update for model compression', 'initialize a Modifier instance with a State object and trigger its lifecycle setup', 'update a Modifier with an Event to trigger on_start, on_update, or on_end based on start/end steps', 'finalize an initialized Modifier to clean up resources and mark it as finalized', 'check whether a Modifier is initialized, finalized, started, or ended via lifecycle properties']
```

Usage

```
{'create_modifier_subclass': 'create a subclass of Modifier that implements on_initialize and on_update for model compression', 'initialize_modifier': 'initialize a Modifier instance with a State object and trigger its lifecycle setup', 'update_modifier_event': 'update a Modifier with an Event to trigger on_start, on_update, or on_end based on start/end steps', 'finalize_modifier': 'finalize an initialized Modifier to clean up resources and mark it as finalized', 'check_modifier_lifecycle': 'check whether a Modifier is initialized, finalized, started, or ended via lifecycle properties'}
```

