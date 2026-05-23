# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/registry/build_functions.py

Prompts

```
['build a module or call a function from a config dict using a mmengine Registry', 'build a Runner object from a config dict using the runners Registry', 'build a PyTorch nn.Module from a config dict, wrapping lists in nn.Sequential', 'build a ParamScheduler from config, supporting epoch to iter conversion', 'review the mmengine build functions for config-driven object instantiation patterns', 'create a DefaultScope instance with a name and scope_name for global registry access', 'get the latest created DefaultScope instance globally using get_current_instance class method', 'overwrite the current default scope temporarily using the overwrite_default_scope context manager', 'review the DefaultScope class and its scope_name property for registry scoping behavior', 'summarize the DefaultScope class methods including get_current_instance and overwrite_default_scope', 'create a Registry instance with a name, optional parent registry, scope, and auto-import locations', 'register a class or function to a Registry using the register_module decorator pattern', 'build an instance from a config dict by calling Registry.build with a type key', 'get a registered class from a Registry by its name using Registry.get with scope resolution', 'use Registry.switch_scope_and_registry as a context manager to temporarily switch the default scope', "traverse a Registry node's full tree and collect all registered module statistics into a list", 'scan all MMEngine root and child registries and optionally dump module statistics to a JSON file', 'initialize a named DefaultScope instance or force-switch the current default scope to a new one', 'review the traverse_registry_tree function to understand how it performs DFS traversal of the registry tree', 'summarize the count_registered_modules function which imports MMEngine submodules and aggregates registry statistics']
```

Usage

```
{'build_from_cfg': 'build a module or call a function from a config dict using a mmengine Registry', 'build_runner_from_cfg': 'build a Runner object from a config dict using the runners Registry', 'build_model_from_cfg': 'build a PyTorch nn.Module from a config dict, wrapping lists in nn.Sequential', 'build_scheduler_from_cfg': 'build a ParamScheduler from config, supporting epoch to iter conversion', 'review_build_functions': 'review the mmengine build functions for config-driven object instantiation patterns'}
```

## File: facebookresearch_sapiens/engine/mmengine/registry/default_scope.py

Prompts

```
['build a module or call a function from a config dict using a mmengine Registry', 'build a Runner object from a config dict using the runners Registry', 'build a PyTorch nn.Module from a config dict, wrapping lists in nn.Sequential', 'build a ParamScheduler from config, supporting epoch to iter conversion', 'review the mmengine build functions for config-driven object instantiation patterns', 'create a DefaultScope instance with a name and scope_name for global registry access', 'get the latest created DefaultScope instance globally using get_current_instance class method', 'overwrite the current default scope temporarily using the overwrite_default_scope context manager', 'review the DefaultScope class and its scope_name property for registry scoping behavior', 'summarize the DefaultScope class methods including get_current_instance and overwrite_default_scope', 'create a Registry instance with a name, optional parent registry, scope, and auto-import locations', 'register a class or function to a Registry using the register_module decorator pattern', 'build an instance from a config dict by calling Registry.build with a type key', 'get a registered class from a Registry by its name using Registry.get with scope resolution', 'use Registry.switch_scope_and_registry as a context manager to temporarily switch the default scope', "traverse a Registry node's full tree and collect all registered module statistics into a list", 'scan all MMEngine root and child registries and optionally dump module statistics to a JSON file', 'initialize a named DefaultScope instance or force-switch the current default scope to a new one', 'review the traverse_registry_tree function to understand how it performs DFS traversal of the registry tree', 'summarize the count_registered_modules function which imports MMEngine submodules and aggregates registry statistics']
```

Usage

```
{'create_default_scope_instance': 'create a DefaultScope instance with a name and scope_name for global registry access', 'get_current_default_scope': 'get the latest created DefaultScope instance globally using get_current_instance class method', 'overwrite_default_scope_context': 'overwrite the current default scope temporarily using the overwrite_default_scope context manager', 'review_default_scope_class': 'review the DefaultScope class and its scope_name property for registry scoping behavior', 'summarize_default_scope_methods': 'summarize the DefaultScope class methods including get_current_instance and overwrite_default_scope'}
```

## File: facebookresearch_sapiens/engine/mmengine/registry/registry.py

Prompts

```
['build a module or call a function from a config dict using a mmengine Registry', 'build a Runner object from a config dict using the runners Registry', 'build a PyTorch nn.Module from a config dict, wrapping lists in nn.Sequential', 'build a ParamScheduler from config, supporting epoch to iter conversion', 'review the mmengine build functions for config-driven object instantiation patterns', 'create a DefaultScope instance with a name and scope_name for global registry access', 'get the latest created DefaultScope instance globally using get_current_instance class method', 'overwrite the current default scope temporarily using the overwrite_default_scope context manager', 'review the DefaultScope class and its scope_name property for registry scoping behavior', 'summarize the DefaultScope class methods including get_current_instance and overwrite_default_scope', 'create a Registry instance with a name, optional parent registry, scope, and auto-import locations', 'register a class or function to a Registry using the register_module decorator pattern', 'build an instance from a config dict by calling Registry.build with a type key', 'get a registered class from a Registry by its name using Registry.get with scope resolution', 'use Registry.switch_scope_and_registry as a context manager to temporarily switch the default scope', "traverse a Registry node's full tree and collect all registered module statistics into a list", 'scan all MMEngine root and child registries and optionally dump module statistics to a JSON file', 'initialize a named DefaultScope instance or force-switch the current default scope to a new one', 'review the traverse_registry_tree function to understand how it performs DFS traversal of the registry tree', 'summarize the count_registered_modules function which imports MMEngine submodules and aggregates registry statistics']
```

Usage

```
{'create_registry_instance': 'create a Registry instance with a name, optional parent registry, scope, and auto-import locations', 'register_module_decorator': 'register a class or function to a Registry using the register_module decorator pattern', 'build_from_registry': 'build an instance from a config dict by calling Registry.build with a type key', 'get_registered_class': 'get a registered class from a Registry by its name using Registry.get with scope resolution', 'switch_scope_context': 'use Registry.switch_scope_and_registry as a context manager to temporarily switch the default scope'}
```

## File: facebookresearch_sapiens/engine/mmengine/registry/utils.py

Prompts

```
['build a module or call a function from a config dict using a mmengine Registry', 'build a Runner object from a config dict using the runners Registry', 'build a PyTorch nn.Module from a config dict, wrapping lists in nn.Sequential', 'build a ParamScheduler from config, supporting epoch to iter conversion', 'review the mmengine build functions for config-driven object instantiation patterns', 'create a DefaultScope instance with a name and scope_name for global registry access', 'get the latest created DefaultScope instance globally using get_current_instance class method', 'overwrite the current default scope temporarily using the overwrite_default_scope context manager', 'review the DefaultScope class and its scope_name property for registry scoping behavior', 'summarize the DefaultScope class methods including get_current_instance and overwrite_default_scope', 'create a Registry instance with a name, optional parent registry, scope, and auto-import locations', 'register a class or function to a Registry using the register_module decorator pattern', 'build an instance from a config dict by calling Registry.build with a type key', 'get a registered class from a Registry by its name using Registry.get with scope resolution', 'use Registry.switch_scope_and_registry as a context manager to temporarily switch the default scope', "traverse a Registry node's full tree and collect all registered module statistics into a list", 'scan all MMEngine root and child registries and optionally dump module statistics to a JSON file', 'initialize a named DefaultScope instance or force-switch the current default scope to a new one', 'review the traverse_registry_tree function to understand how it performs DFS traversal of the registry tree', 'summarize the count_registered_modules function which imports MMEngine submodules and aggregates registry statistics']
```

Usage

```
{'traverse_registry_tree': "traverse a Registry node's full tree and collect all registered module statistics into a list", 'count_registered_modules': 'scan all MMEngine root and child registries and optionally dump module statistics to a JSON file', 'init_default_scope': 'initialize a named DefaultScope instance or force-switch the current default scope to a new one', 'review_traverse_registry_tree': 'review the traverse_registry_tree function to understand how it performs DFS traversal of the registry tree', 'summarize_count_registered_modules': 'summarize the count_registered_modules function which imports MMEngine submodules and aggregates registry statistics'}
```

