# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/runtime/config_registry.py

Prompts

```
['create a ConfigRegistrar to register named config providers with a DependencyContainer', 'use the ConfigRegistrar decorator to register a config provider function by name', 'register an advanced config provider that receives a DependencyResolver via the decorator', 'retrieve a registered configuration by name using get_config with a DependencyResolver', 'handle ConfigNotFoundError exceptions when a named configuration cannot be found', 'create a DependencyContainer to register and resolve dependencies by type with optional keys', 'register a type or subclass in a DependencyContainer for automatic instantiation with dependency injection', 'resolve a registered dependency from a DependencyContainer by type and optional key', 'use wire_object to auto-wire a class instance by resolving typed constructor arguments from a resolver', 'register multiple providers for the same type using the collection resolver on a DependencyContainer', 'create a Lazy instance with a factory callable that returns a value on first access', 'use the Lazy get method to retrieve the lazily computed value from a factory', 'implement lazy evaluation by wrapping an expensive computation in a Lazy factory callable', 'review the Lazy class to understand its single-call factory pattern and value caching behavior', 'refactor the Lazy class to add thread safety for concurrent access to the get method', 'create a concrete subclass of Lookup that implements maybe_get, iter_keys, and the kls property', 'review the Lookup abstract base class and its maybe_get, iter_keys, and kls abstract members', 'summarize the Lookup ABC which defines a generic interface for key-based value retrieval', 'refactor an existing Lookup subclass to use a different internal storage strategy for maybe_get', 'test a concrete Lookup subclass to verify maybe_get returns values and iter_keys yields all keys']
```

Usage

```
{'create_config_registrar': 'create a ConfigRegistrar to register named config providers with a DependencyContainer', 'register_config_decorator': 'use the ConfigRegistrar decorator to register a config provider function by name', 'register_advanced_config': 'register an advanced config provider that receives a DependencyResolver via the decorator', 'get_config_by_name': 'retrieve a registered configuration by name using get_config with a DependencyResolver', 'handle_config_not_found': 'handle ConfigNotFoundError exceptions when a named configuration cannot be found'}
```

## File: facebookresearch_fairseq2/src/fairseq2/runtime/dependency.py

Prompts

```
['create a ConfigRegistrar to register named config providers with a DependencyContainer', 'use the ConfigRegistrar decorator to register a config provider function by name', 'register an advanced config provider that receives a DependencyResolver via the decorator', 'retrieve a registered configuration by name using get_config with a DependencyResolver', 'handle ConfigNotFoundError exceptions when a named configuration cannot be found', 'create a DependencyContainer to register and resolve dependencies by type with optional keys', 'register a type or subclass in a DependencyContainer for automatic instantiation with dependency injection', 'resolve a registered dependency from a DependencyContainer by type and optional key', 'use wire_object to auto-wire a class instance by resolving typed constructor arguments from a resolver', 'register multiple providers for the same type using the collection resolver on a DependencyContainer', 'create a Lazy instance with a factory callable that returns a value on first access', 'use the Lazy get method to retrieve the lazily computed value from a factory', 'implement lazy evaluation by wrapping an expensive computation in a Lazy factory callable', 'review the Lazy class to understand its single-call factory pattern and value caching behavior', 'refactor the Lazy class to add thread safety for concurrent access to the get method', 'create a concrete subclass of Lookup that implements maybe_get, iter_keys, and the kls property', 'review the Lookup abstract base class and its maybe_get, iter_keys, and kls abstract members', 'summarize the Lookup ABC which defines a generic interface for key-based value retrieval', 'refactor an existing Lookup subclass to use a different internal storage strategy for maybe_get', 'test a concrete Lookup subclass to verify maybe_get returns values and iter_keys yields all keys']
```

Usage

```
{'create_dependency_container': 'create a DependencyContainer to register and resolve dependencies by type with optional keys', 'register_type_in_container': 'register a type or subclass in a DependencyContainer for automatic instantiation with dependency injection', 'resolve_dependencies': 'resolve a registered dependency from a DependencyContainer by type and optional key', 'wire_object': 'use wire_object to auto-wire a class instance by resolving typed constructor arguments from a resolver', 'register_collection_dependencies': 'register multiple providers for the same type using the collection resolver on a DependencyContainer'}
```

## File: facebookresearch_fairseq2/src/fairseq2/runtime/lazy.py

Prompts

```
['create a ConfigRegistrar to register named config providers with a DependencyContainer', 'use the ConfigRegistrar decorator to register a config provider function by name', 'register an advanced config provider that receives a DependencyResolver via the decorator', 'retrieve a registered configuration by name using get_config with a DependencyResolver', 'handle ConfigNotFoundError exceptions when a named configuration cannot be found', 'create a DependencyContainer to register and resolve dependencies by type with optional keys', 'register a type or subclass in a DependencyContainer for automatic instantiation with dependency injection', 'resolve a registered dependency from a DependencyContainer by type and optional key', 'use wire_object to auto-wire a class instance by resolving typed constructor arguments from a resolver', 'register multiple providers for the same type using the collection resolver on a DependencyContainer', 'create a Lazy instance with a factory callable that returns a value on first access', 'use the Lazy get method to retrieve the lazily computed value from a factory', 'implement lazy evaluation by wrapping an expensive computation in a Lazy factory callable', 'review the Lazy class to understand its single-call factory pattern and value caching behavior', 'refactor the Lazy class to add thread safety for concurrent access to the get method', 'create a concrete subclass of Lookup that implements maybe_get, iter_keys, and the kls property', 'review the Lookup abstract base class and its maybe_get, iter_keys, and kls abstract members', 'summarize the Lookup ABC which defines a generic interface for key-based value retrieval', 'refactor an existing Lookup subclass to use a different internal storage strategy for maybe_get', 'test a concrete Lookup subclass to verify maybe_get returns values and iter_keys yields all keys']
```

Usage

```
{'create_Lazy_instance': 'create a Lazy instance with a factory callable that returns a value on first access', 'use_Lazy_get': 'use the Lazy get method to retrieve the lazily computed value from a factory', 'implement_lazy_evaluation': 'implement lazy evaluation by wrapping an expensive computation in a Lazy factory callable', 'review_Lazy_class': 'review the Lazy class to understand its single-call factory pattern and value caching behavior', 'refactor_Lazy_for_thread_safety': 'refactor the Lazy class to add thread safety for concurrent access to the get method'}
```

## File: facebookresearch_fairseq2/src/fairseq2/runtime/lookup.py

Prompts

```
['create a ConfigRegistrar to register named config providers with a DependencyContainer', 'use the ConfigRegistrar decorator to register a config provider function by name', 'register an advanced config provider that receives a DependencyResolver via the decorator', 'retrieve a registered configuration by name using get_config with a DependencyResolver', 'handle ConfigNotFoundError exceptions when a named configuration cannot be found', 'create a DependencyContainer to register and resolve dependencies by type with optional keys', 'register a type or subclass in a DependencyContainer for automatic instantiation with dependency injection', 'resolve a registered dependency from a DependencyContainer by type and optional key', 'use wire_object to auto-wire a class instance by resolving typed constructor arguments from a resolver', 'register multiple providers for the same type using the collection resolver on a DependencyContainer', 'create a Lazy instance with a factory callable that returns a value on first access', 'use the Lazy get method to retrieve the lazily computed value from a factory', 'implement lazy evaluation by wrapping an expensive computation in a Lazy factory callable', 'review the Lazy class to understand its single-call factory pattern and value caching behavior', 'refactor the Lazy class to add thread safety for concurrent access to the get method', 'create a concrete subclass of Lookup that implements maybe_get, iter_keys, and the kls property', 'review the Lookup abstract base class and its maybe_get, iter_keys, and kls abstract members', 'summarize the Lookup ABC which defines a generic interface for key-based value retrieval', 'refactor an existing Lookup subclass to use a different internal storage strategy for maybe_get', 'test a concrete Lookup subclass to verify maybe_get returns values and iter_keys yields all keys']
```

Usage

```
{'implement_lookup_subclass': 'create a concrete subclass of Lookup that implements maybe_get, iter_keys, and the kls property', 'review_lookup_abc': 'review the Lookup abstract base class and its maybe_get, iter_keys, and kls abstract members', 'summarize_lookup_class': 'summarize the Lookup ABC which defines a generic interface for key-based value retrieval', 'refactor_lookup_subclass': 'refactor an existing Lookup subclass to use a different internal storage strategy for maybe_get', 'test_lookup_subclass': 'test a concrete Lookup subclass to verify maybe_get returns values and iter_keys yields all keys'}
```

