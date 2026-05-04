# Agent Python Tools

- repo: google-deepmind/einshape
- repo_uri: https://github.com/google-deepmind/einshape

## File: google-deepmind_einshape/einshape/tests/abstract_ops_test.py

Prompts

```
['test the Reshape class transform_shape method to reshape a tensor to a new shape', 'test the Transpose class transform_shape method to reorder tensor axes using a permutation', 'test the Broadcast class transform_shape method to insert new axes into a tensor shape', 'run the absltest suite for einshape abstract_ops to verify reshape, transpose, and broadcast', 'review the Reshape, Transpose, and Broadcast ShapeOp subclasses and their transform_shape methods', "generate reshape ops for a no-op einshape equation like 'i->i' with a given input shape", "generate transpose ops to reorder tensor axes using an einshape equation like 'ij->ji'", 'generate ops to convert NHWC tensor layout to NCHW using the einshape engine', "generate ops to squeeze unit dimensions or expand dims using einshape equations like 'j1k->jk'", "generate broadcast ops to tile a tensor along new axes using an einshape equation like 'j->nj'", 'test that the optimizer skips redundant consecutive reshape operations on a given input shape', 'test that the optimizer retains non-redundant reshape operations separated by a transpose', 'test that the optimizer removes a no-op reshape when the target shape matches the input shape', 'test that the optimizer skips a no-op reshape that follows a transpose operation', 'test that the optimizer skips a no-op reshape that follows a broadcast operation']
```

Usage

```
{'test_reshape_transform': 'test the Reshape class transform_shape method to reshape a tensor to a new shape', 'test_transpose_transform': 'test the Transpose class transform_shape method to reorder tensor axes using a permutation', 'test_broadcast_transform': 'test the Broadcast class transform_shape method to insert new axes into a tensor shape', 'run_abstract_ops_test': 'run the absltest suite for einshape abstract_ops to verify reshape, transpose, and broadcast', 'review_shapeop_classes': 'review the Reshape, Transpose, and Broadcast ShapeOp subclasses and their transform_shape methods'}
```

## File: google-deepmind_einshape/einshape/tests/engine_test.py

Prompts

```
['test the Reshape class transform_shape method to reshape a tensor to a new shape', 'test the Transpose class transform_shape method to reorder tensor axes using a permutation', 'test the Broadcast class transform_shape method to insert new axes into a tensor shape', 'run the absltest suite for einshape abstract_ops to verify reshape, transpose, and broadcast', 'review the Reshape, Transpose, and Broadcast ShapeOp subclasses and their transform_shape methods', "generate reshape ops for a no-op einshape equation like 'i->i' with a given input shape", "generate transpose ops to reorder tensor axes using an einshape equation like 'ij->ji'", 'generate ops to convert NHWC tensor layout to NCHW using the einshape engine', "generate ops to squeeze unit dimensions or expand dims using einshape equations like 'j1k->jk'", "generate broadcast ops to tile a tensor along new axes using an einshape equation like 'j->nj'", 'test that the optimizer skips redundant consecutive reshape operations on a given input shape', 'test that the optimizer retains non-redundant reshape operations separated by a transpose', 'test that the optimizer removes a no-op reshape when the target shape matches the input shape', 'test that the optimizer skips a no-op reshape that follows a transpose operation', 'test that the optimizer skips a no-op reshape that follows a broadcast operation']
```

Usage

```
{'generate_reshape_noop': "generate reshape ops for a no-op einshape equation like 'i->i' with a given input shape", 'generate_transpose_ops': "generate transpose ops to reorder tensor axes using an einshape equation like 'ij->ji'", 'generate_nchw_transpose': 'generate ops to convert NHWC tensor layout to NCHW using the einshape engine', 'generate_squeeze_expand': "generate ops to squeeze unit dimensions or expand dims using einshape equations like 'j1k->jk'", 'generate_broadcast_tile': "generate broadcast ops to tile a tensor along new axes using an einshape equation like 'j->nj'"}
```

## File: google-deepmind_einshape/einshape/tests/optimizer_test.py

Prompts

```
['test the Reshape class transform_shape method to reshape a tensor to a new shape', 'test the Transpose class transform_shape method to reorder tensor axes using a permutation', 'test the Broadcast class transform_shape method to insert new axes into a tensor shape', 'run the absltest suite for einshape abstract_ops to verify reshape, transpose, and broadcast', 'review the Reshape, Transpose, and Broadcast ShapeOp subclasses and their transform_shape methods', "generate reshape ops for a no-op einshape equation like 'i->i' with a given input shape", "generate transpose ops to reorder tensor axes using an einshape equation like 'ij->ji'", 'generate ops to convert NHWC tensor layout to NCHW using the einshape engine', "generate ops to squeeze unit dimensions or expand dims using einshape equations like 'j1k->jk'", "generate broadcast ops to tile a tensor along new axes using an einshape equation like 'j->nj'", 'test that the optimizer skips redundant consecutive reshape operations on a given input shape', 'test that the optimizer retains non-redundant reshape operations separated by a transpose', 'test that the optimizer removes a no-op reshape when the target shape matches the input shape', 'test that the optimizer skips a no-op reshape that follows a transpose operation', 'test that the optimizer skips a no-op reshape that follows a broadcast operation']
```

Usage

```
{'test_optimizer_redundant_reshape': 'test that the optimizer skips redundant consecutive reshape operations on a given input shape', 'test_optimizer_nonredundant_reshape': 'test that the optimizer retains non-redundant reshape operations separated by a transpose', 'test_optimizer_noop_reshape': 'test that the optimizer removes a no-op reshape when the target shape matches the input shape', 'test_optimizer_noop_after_transpose': 'test that the optimizer skips a no-op reshape that follows a transpose operation', 'test_optimizer_noop_after_broadcast': 'test that the optimizer skips a no-op reshape that follows a broadcast operation'}
```

