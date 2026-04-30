# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/compilation/passes/fx_utils.py

Prompts

```
['test the is_func utility to check if an fx.Node matches a given target function', 'test the find_auto_fn utility to locate the first auto_functionalized node for a given op in a node list', 'test the find_getitem utility to find the getitem node that extracts the idx-th element from a node', 'test the find_op_nodes utility to iterate over all fx.Graph nodes matching a given OpOverload or OpOverloadPacket', 'test the get_only_user utility to assert a node has exactly one user and return it', 'build a custom Inductor graph pass that generates a UUID from source hashing for Inductor code cache', 'create a CallableInductorPass wrapper that applies a callable to an FX graph with automatic UUID generation', 'test the pass_context context manager that sets and restores a global PassContext with a compile range', 'run hash_source to compute a SHA-256 hash from strings, functions, types, or object instances', 'refactor a function with enable_fake_mode decorator to run under FakeTensorMode without real tensors', 'build a PostGradPassManager to configure and run compilation passes on a torch fx graph', 'run PostGradPassManager on a torch fx graph to apply configured compilation passes in order', 'configure PostGradPassManager from a VllmConfig to enable fusion, noop elimination, and sequence parallelism passes', 'add a custom InductorPass to the PostGradPassManager pass list for graph transformation', 'generate a deterministic uuid from PostGradPassManager passes and config for Inductor code cache', 'create a VllmInductorPass subclass with timing, logging, and graph dumping utilities for inductor compilation', 'register VllmPatternReplacement pattern/replacement pairs in a VllmFusionPatternMatcherPass for FX graph fusion', 'run a VllmFusionPatternMatcherPass on a torch fx.Graph to apply registered pattern replacements', 'build a VllmPatternReplacement with pattern, replacement, and get_inputs methods for defining FX subgraph substitutions', 'get a snapshot of the global match table mapping pass names to their total pattern match counts']
```

Usage

```
{'test_is_func': 'test the is_func utility to check if an fx.Node matches a given target function', 'test_find_auto_fn': 'test the find_auto_fn utility to locate the first auto_functionalized node for a given op in a node list', 'test_find_getitem': 'test the find_getitem utility to find the getitem node that extracts the idx-th element from a node', 'test_find_op_nodes': 'test the find_op_nodes utility to iterate over all fx.Graph nodes matching a given OpOverload or OpOverloadPacket', 'test_get_only_user': 'test the get_only_user utility to assert a node has exactly one user and return it'}
```

## File: vllm-project_vllm/vllm/compilation/passes/inductor_pass.py

Prompts

```
['test the is_func utility to check if an fx.Node matches a given target function', 'test the find_auto_fn utility to locate the first auto_functionalized node for a given op in a node list', 'test the find_getitem utility to find the getitem node that extracts the idx-th element from a node', 'test the find_op_nodes utility to iterate over all fx.Graph nodes matching a given OpOverload or OpOverloadPacket', 'test the get_only_user utility to assert a node has exactly one user and return it', 'build a custom Inductor graph pass that generates a UUID from source hashing for Inductor code cache', 'create a CallableInductorPass wrapper that applies a callable to an FX graph with automatic UUID generation', 'test the pass_context context manager that sets and restores a global PassContext with a compile range', 'run hash_source to compute a SHA-256 hash from strings, functions, types, or object instances', 'refactor a function with enable_fake_mode decorator to run under FakeTensorMode without real tensors', 'build a PostGradPassManager to configure and run compilation passes on a torch fx graph', 'run PostGradPassManager on a torch fx graph to apply configured compilation passes in order', 'configure PostGradPassManager from a VllmConfig to enable fusion, noop elimination, and sequence parallelism passes', 'add a custom InductorPass to the PostGradPassManager pass list for graph transformation', 'generate a deterministic uuid from PostGradPassManager passes and config for Inductor code cache', 'create a VllmInductorPass subclass with timing, logging, and graph dumping utilities for inductor compilation', 'register VllmPatternReplacement pattern/replacement pairs in a VllmFusionPatternMatcherPass for FX graph fusion', 'run a VllmFusionPatternMatcherPass on a torch fx.Graph to apply registered pattern replacements', 'build a VllmPatternReplacement with pattern, replacement, and get_inputs methods for defining FX subgraph substitutions', 'get a snapshot of the global match table mapping pass names to their total pattern match counts']
```

Usage

```
{'build_inductor_pass': 'build a custom Inductor graph pass that generates a UUID from source hashing for Inductor code cache', 'create_callable_inductor_pass': 'create a CallableInductorPass wrapper that applies a callable to an FX graph with automatic UUID generation', 'test_pass_context_manager': 'test the pass_context context manager that sets and restores a global PassContext with a compile range', 'run_hash_source': 'run hash_source to compute a SHA-256 hash from strings, functions, types, or object instances', 'refactor_enable_fake_mode': 'refactor a function with enable_fake_mode decorator to run under FakeTensorMode without real tensors'}
```

## File: vllm-project_vllm/vllm/compilation/passes/pass_manager.py

Prompts

```
['test the is_func utility to check if an fx.Node matches a given target function', 'test the find_auto_fn utility to locate the first auto_functionalized node for a given op in a node list', 'test the find_getitem utility to find the getitem node that extracts the idx-th element from a node', 'test the find_op_nodes utility to iterate over all fx.Graph nodes matching a given OpOverload or OpOverloadPacket', 'test the get_only_user utility to assert a node has exactly one user and return it', 'build a custom Inductor graph pass that generates a UUID from source hashing for Inductor code cache', 'create a CallableInductorPass wrapper that applies a callable to an FX graph with automatic UUID generation', 'test the pass_context context manager that sets and restores a global PassContext with a compile range', 'run hash_source to compute a SHA-256 hash from strings, functions, types, or object instances', 'refactor a function with enable_fake_mode decorator to run under FakeTensorMode without real tensors', 'build a PostGradPassManager to configure and run compilation passes on a torch fx graph', 'run PostGradPassManager on a torch fx graph to apply configured compilation passes in order', 'configure PostGradPassManager from a VllmConfig to enable fusion, noop elimination, and sequence parallelism passes', 'add a custom InductorPass to the PostGradPassManager pass list for graph transformation', 'generate a deterministic uuid from PostGradPassManager passes and config for Inductor code cache', 'create a VllmInductorPass subclass with timing, logging, and graph dumping utilities for inductor compilation', 'register VllmPatternReplacement pattern/replacement pairs in a VllmFusionPatternMatcherPass for FX graph fusion', 'run a VllmFusionPatternMatcherPass on a torch fx.Graph to apply registered pattern replacements', 'build a VllmPatternReplacement with pattern, replacement, and get_inputs methods for defining FX subgraph substitutions', 'get a snapshot of the global match table mapping pass names to their total pattern match counts']
```

Usage

```
{'build_post_grad_pass_manager': 'build a PostGradPassManager to configure and run compilation passes on a torch fx graph', 'run_passes_on_graph': 'run PostGradPassManager on a torch fx graph to apply configured compilation passes in order', 'configure_passes_from_config': 'configure PostGradPassManager from a VllmConfig to enable fusion, noop elimination, and sequence parallelism passes', 'add_custom_pass': 'add a custom InductorPass to the PostGradPassManager pass list for graph transformation', 'generate_pass_manager_uuid': 'generate a deterministic uuid from PostGradPassManager passes and config for Inductor code cache'}
```

## File: vllm-project_vllm/vllm/compilation/passes/vllm_inductor_pass.py

Prompts

```
['test the is_func utility to check if an fx.Node matches a given target function', 'test the find_auto_fn utility to locate the first auto_functionalized node for a given op in a node list', 'test the find_getitem utility to find the getitem node that extracts the idx-th element from a node', 'test the find_op_nodes utility to iterate over all fx.Graph nodes matching a given OpOverload or OpOverloadPacket', 'test the get_only_user utility to assert a node has exactly one user and return it', 'build a custom Inductor graph pass that generates a UUID from source hashing for Inductor code cache', 'create a CallableInductorPass wrapper that applies a callable to an FX graph with automatic UUID generation', 'test the pass_context context manager that sets and restores a global PassContext with a compile range', 'run hash_source to compute a SHA-256 hash from strings, functions, types, or object instances', 'refactor a function with enable_fake_mode decorator to run under FakeTensorMode without real tensors', 'build a PostGradPassManager to configure and run compilation passes on a torch fx graph', 'run PostGradPassManager on a torch fx graph to apply configured compilation passes in order', 'configure PostGradPassManager from a VllmConfig to enable fusion, noop elimination, and sequence parallelism passes', 'add a custom InductorPass to the PostGradPassManager pass list for graph transformation', 'generate a deterministic uuid from PostGradPassManager passes and config for Inductor code cache', 'create a VllmInductorPass subclass with timing, logging, and graph dumping utilities for inductor compilation', 'register VllmPatternReplacement pattern/replacement pairs in a VllmFusionPatternMatcherPass for FX graph fusion', 'run a VllmFusionPatternMatcherPass on a torch fx.Graph to apply registered pattern replacements', 'build a VllmPatternReplacement with pattern, replacement, and get_inputs methods for defining FX subgraph substitutions', 'get a snapshot of the global match table mapping pass names to their total pattern match counts']
```

Usage

```
{'create_VllmInductorPass': 'create a VllmInductorPass subclass with timing, logging, and graph dumping utilities for inductor compilation', 'register_VllmFusionPatternMatcherPass': 'register VllmPatternReplacement pattern/replacement pairs in a VllmFusionPatternMatcherPass for FX graph fusion', 'run_VllmFusionPatternMatcherPass': 'run a VllmFusionPatternMatcherPass on a torch fx.Graph to apply registered pattern replacements', 'build_VllmPatternReplacement': 'build a VllmPatternReplacement with pattern, replacement, and get_inputs methods for defining FX subgraph substitutions', 'get_match_table': 'get a snapshot of the global match table mapping pass names to their total pattern match counts'}
```

