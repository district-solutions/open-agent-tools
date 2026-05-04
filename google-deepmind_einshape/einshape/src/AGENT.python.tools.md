# Agent Python Tools

- repo: google-deepmind/einshape
- repo_uri: https://github.com/google-deepmind/einshape

## File: google-deepmind_einshape/einshape/src/abstract_ops.py

Prompts

```
['create a Reshape dataclass instance with a target shape to reshape a tensor without reordering elements', 'create a Transpose dataclass instance with a permutation list to reorder tensor axes', 'create a Broadcast dataclass instance with axis_sizes dict to insert new axes into a tensor shape', 'review the Reshape class transform_shape method which returns the target shape ignoring input shape', 'review the Transpose class transform_shape method which permutes input shape dimensions by the perm list', 'create a subclass of Backend that implements reshape, transpose, and broadcast methods', 'run the exec method on a Backend instance with an equation string and tensor value', 'implement the abstract reshape method in a Backend subclass to handle Reshape operations', 'implement the abstract transpose method in a Backend subclass to handle Transpose operations', 'override the _preprocess method in a Backend subclass to add backend-specific optimization', 'generate reshape and transpose ops from an einshape equation and input tensor shape', 'generate ops from a shape equation with explicit index size hints for ungrouping dimensions', 'generate ops from an einshape equation using the ellipsis wildcard to match arbitrary trailing dimensions', 'generate ops that broadcast new axes into the output shape using index size hints', 'generate ops to transpose tensor axes by reordering indices in the einshape equation RHS', 'optimize a sequence of abstract ShapeOps by eliding intermediate and noop reshapes', 'elide contiguous reshape operations from a sequence of shaping ops', 'elide reshape operations that produce no change to the input shape', 'check if a sequence of ops are all contiguous Reshape instances', 'check if a reshape operation is a no-op given a static input shape']
```

Usage

```
{'create_reshape_op': 'create a Reshape dataclass instance with a target shape to reshape a tensor without reordering elements', 'create_transpose_op': 'create a Transpose dataclass instance with a permutation list to reorder tensor axes', 'create_broadcast_op': 'create a Broadcast dataclass instance with axis_sizes dict to insert new axes into a tensor shape', 'review_reshape_transform_shape': 'review the Reshape class transform_shape method which returns the target shape ignoring input shape', 'review_transpose_transform_shape': 'review the Transpose class transform_shape method which permutes input shape dimensions by the perm list'}
```

## File: google-deepmind_einshape/einshape/src/backend.py

Prompts

```
['create a Reshape dataclass instance with a target shape to reshape a tensor without reordering elements', 'create a Transpose dataclass instance with a permutation list to reorder tensor axes', 'create a Broadcast dataclass instance with axis_sizes dict to insert new axes into a tensor shape', 'review the Reshape class transform_shape method which returns the target shape ignoring input shape', 'review the Transpose class transform_shape method which permutes input shape dimensions by the perm list', 'create a subclass of Backend that implements reshape, transpose, and broadcast methods', 'run the exec method on a Backend instance with an equation string and tensor value', 'implement the abstract reshape method in a Backend subclass to handle Reshape operations', 'implement the abstract transpose method in a Backend subclass to handle Transpose operations', 'override the _preprocess method in a Backend subclass to add backend-specific optimization', 'generate reshape and transpose ops from an einshape equation and input tensor shape', 'generate ops from a shape equation with explicit index size hints for ungrouping dimensions', 'generate ops from an einshape equation using the ellipsis wildcard to match arbitrary trailing dimensions', 'generate ops that broadcast new axes into the output shape using index size hints', 'generate ops to transpose tensor axes by reordering indices in the einshape equation RHS', 'optimize a sequence of abstract ShapeOps by eliding intermediate and noop reshapes', 'elide contiguous reshape operations from a sequence of shaping ops', 'elide reshape operations that produce no change to the input shape', 'check if a sequence of ops are all contiguous Reshape instances', 'check if a reshape operation is a no-op given a static input shape']
```

Usage

```
{'create_backend_subclass': 'create a subclass of Backend that implements reshape, transpose, and broadcast methods', 'run_einshape_exec': 'run the exec method on a Backend instance with an equation string and tensor value', 'implement_reshape_method': 'implement the abstract reshape method in a Backend subclass to handle Reshape operations', 'implement_transpose_method': 'implement the abstract transpose method in a Backend subclass to handle Transpose operations', 'override_preprocess_hook': 'override the _preprocess method in a Backend subclass to add backend-specific optimization'}
```

## File: google-deepmind_einshape/einshape/src/engine.py

Prompts

```
['create a Reshape dataclass instance with a target shape to reshape a tensor without reordering elements', 'create a Transpose dataclass instance with a permutation list to reorder tensor axes', 'create a Broadcast dataclass instance with axis_sizes dict to insert new axes into a tensor shape', 'review the Reshape class transform_shape method which returns the target shape ignoring input shape', 'review the Transpose class transform_shape method which permutes input shape dimensions by the perm list', 'create a subclass of Backend that implements reshape, transpose, and broadcast methods', 'run the exec method on a Backend instance with an equation string and tensor value', 'implement the abstract reshape method in a Backend subclass to handle Reshape operations', 'implement the abstract transpose method in a Backend subclass to handle Transpose operations', 'override the _preprocess method in a Backend subclass to add backend-specific optimization', 'generate reshape and transpose ops from an einshape equation and input tensor shape', 'generate ops from a shape equation with explicit index size hints for ungrouping dimensions', 'generate ops from an einshape equation using the ellipsis wildcard to match arbitrary trailing dimensions', 'generate ops that broadcast new axes into the output shape using index size hints', 'generate ops to transpose tensor axes by reordering indices in the einshape equation RHS', 'optimize a sequence of abstract ShapeOps by eliding intermediate and noop reshapes', 'elide contiguous reshape operations from a sequence of shaping ops', 'elide reshape operations that produce no change to the input shape', 'check if a sequence of ops are all contiguous Reshape instances', 'check if a reshape operation is a no-op given a static input shape']
```

Usage

```
{'generate_ops_compile_equation': 'generate reshape and transpose ops from an einshape equation and input tensor shape', 'generate_ops_with_index_sizes': 'generate ops from a shape equation with explicit index size hints for ungrouping dimensions', 'generate_ops_wildcard': 'generate ops from an einshape equation using the ellipsis wildcard to match arbitrary trailing dimensions', 'generate_ops_broadcast': 'generate ops that broadcast new axes into the output shape using index size hints', 'generate_ops_transpose': 'generate ops to transpose tensor axes by reordering indices in the einshape equation RHS'}
```

## File: google-deepmind_einshape/einshape/src/optimizer.py

Prompts

```
['create a Reshape dataclass instance with a target shape to reshape a tensor without reordering elements', 'create a Transpose dataclass instance with a permutation list to reorder tensor axes', 'create a Broadcast dataclass instance with axis_sizes dict to insert new axes into a tensor shape', 'review the Reshape class transform_shape method which returns the target shape ignoring input shape', 'review the Transpose class transform_shape method which permutes input shape dimensions by the perm list', 'create a subclass of Backend that implements reshape, transpose, and broadcast methods', 'run the exec method on a Backend instance with an equation string and tensor value', 'implement the abstract reshape method in a Backend subclass to handle Reshape operations', 'implement the abstract transpose method in a Backend subclass to handle Transpose operations', 'override the _preprocess method in a Backend subclass to add backend-specific optimization', 'generate reshape and transpose ops from an einshape equation and input tensor shape', 'generate ops from a shape equation with explicit index size hints for ungrouping dimensions', 'generate ops from an einshape equation using the ellipsis wildcard to match arbitrary trailing dimensions', 'generate ops that broadcast new axes into the output shape using index size hints', 'generate ops to transpose tensor axes by reordering indices in the einshape equation RHS', 'optimize a sequence of abstract ShapeOps by eliding intermediate and noop reshapes', 'elide contiguous reshape operations from a sequence of shaping ops', 'elide reshape operations that produce no change to the input shape', 'check if a sequence of ops are all contiguous Reshape instances', 'check if a reshape operation is a no-op given a static input shape']
```

Usage

```
{'optimize_shape_ops': 'optimize a sequence of abstract ShapeOps by eliding intermediate and noop reshapes', 'elide_intermediate_reshapes': 'elide contiguous reshape operations from a sequence of shaping ops', 'elide_noop_reshapes': 'elide reshape operations that produce no change to the input shape', 'are_contiguous_reshapes': 'check if a sequence of ops are all contiguous Reshape instances', 'is_noop_reshape': 'check if a reshape operation is a no-op given a static input shape'}
```

