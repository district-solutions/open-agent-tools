# Agent Python Tools

- repo: google-deepmind/alphastar
- repo_uri: https://github.com/google-deepmind/alphastar

## File: google-deepmind_alphastar/alphastar/collections/jax.py

Prompts

```
['call register_struct to register Struct as a JAX PyTree node for pytree flattening', 'review the register_struct function that registers Struct with jax.tree_util.register_pytree_node', 'summarize how register_struct flattens Struct values and keys for JAX tracer compatibility', 'test that calling register_struct multiple times logs info instead of raising ValueError', 'refactor the register_struct flatten_func to customize how Struct values and keys are serialized for JAX', 'create an immutable dict with sorted keys using Struct(key1=value1, key2=value2)', 'create a new Struct by overriding fields from an existing Struct instance', 'access Struct values as attributes using dot notation like struct.my_key', 'iterate over Struct keys in sorted order using a for loop', 'hash an immutable Struct instance to use as a dictionary key', 'test the Struct class attribute access and bracket notation for reading values', 'test that Struct instances reject modifications like pop, clear, update, and setdefault', 'test extending a Struct with new keys or overriding existing keys with new values', 'test that Struct keys, values, and items iterate in sorted key order', 'test pickling, shallow copy, and deep copy of nested Struct instances']
```

Usage

```
{'register_struct_as_jax_pytree': 'call register_struct to register Struct as a JAX PyTree node for pytree flattening', 'review_register_struct_function': 'review the register_struct function that registers Struct with jax.tree_util.register_pytree_node', 'summarize_jax_pytree_registration': 'summarize how register_struct flattens Struct values and keys for JAX tracer compatibility', 'test_register_struct_idempotency': 'test that calling register_struct multiple times logs info instead of raising ValueError', 'refactor_struct_pytree_flatten': 'refactor the register_struct flatten_func to customize how Struct values and keys are serialized for JAX'}
```

## File: google-deepmind_alphastar/alphastar/collections/structure.py

Prompts

```
['call register_struct to register Struct as a JAX PyTree node for pytree flattening', 'review the register_struct function that registers Struct with jax.tree_util.register_pytree_node', 'summarize how register_struct flattens Struct values and keys for JAX tracer compatibility', 'test that calling register_struct multiple times logs info instead of raising ValueError', 'refactor the register_struct flatten_func to customize how Struct values and keys are serialized for JAX', 'create an immutable dict with sorted keys using Struct(key1=value1, key2=value2)', 'create a new Struct by overriding fields from an existing Struct instance', 'access Struct values as attributes using dot notation like struct.my_key', 'iterate over Struct keys in sorted order using a for loop', 'hash an immutable Struct instance to use as a dictionary key', 'test the Struct class attribute access and bracket notation for reading values', 'test that Struct instances reject modifications like pop, clear, update, and setdefault', 'test extending a Struct with new keys or overriding existing keys with new values', 'test that Struct keys, values, and items iterate in sorted key order', 'test pickling, shallow copy, and deep copy of nested Struct instances']
```

Usage

```
{'create_struct_immutable_dict': 'create an immutable dict with sorted keys using Struct(key1=value1, key2=value2)', 'create_struct_with_existing': 'create a new Struct by overriding fields from an existing Struct instance', 'access_struct_attributes': 'access Struct values as attributes using dot notation like struct.my_key', 'iterate_struct_sorted_keys': 'iterate over Struct keys in sorted order using a for loop', 'hash_struct_instance': 'hash an immutable Struct instance to use as a dictionary key'}
```

## File: google-deepmind_alphastar/alphastar/collections/structure_test.py

Prompts

```
['call register_struct to register Struct as a JAX PyTree node for pytree flattening', 'review the register_struct function that registers Struct with jax.tree_util.register_pytree_node', 'summarize how register_struct flattens Struct values and keys for JAX tracer compatibility', 'test that calling register_struct multiple times logs info instead of raising ValueError', 'refactor the register_struct flatten_func to customize how Struct values and keys are serialized for JAX', 'create an immutable dict with sorted keys using Struct(key1=value1, key2=value2)', 'create a new Struct by overriding fields from an existing Struct instance', 'access Struct values as attributes using dot notation like struct.my_key', 'iterate over Struct keys in sorted order using a for loop', 'hash an immutable Struct instance to use as a dictionary key', 'test the Struct class attribute access and bracket notation for reading values', 'test that Struct instances reject modifications like pop, clear, update, and setdefault', 'test extending a Struct with new keys or overriding existing keys with new values', 'test that Struct keys, values, and items iterate in sorted key order', 'test pickling, shallow copy, and deep copy of nested Struct instances']
```

Usage

```
{'test_struct_attribute_access': 'test the Struct class attribute access and bracket notation for reading values', 'test_struct_immutability': 'test that Struct instances reject modifications like pop, clear, update, and setdefault', 'test_struct_extension_and_override': 'test extending a Struct with new keys or overriding existing keys with new values', 'test_struct_sorted_iteration': 'test that Struct keys, values, and items iterate in sorted key order', 'test_struct_pickle_and_copy': 'test pickling, shallow copy, and deep copy of nested Struct instances'}
```

