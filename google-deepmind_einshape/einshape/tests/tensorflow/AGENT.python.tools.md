# Agent Python Tools

- repo: google-deepmind/einshape
- repo_uri: https://github.com/google-deepmind/einshape

## File: google-deepmind_einshape/einshape/tests/tensorflow/preprocessing_test.py

Prompts

```
['test that Reshape and Transpose ops are preserved unchanged by preprocessing.preprocess', 'test that Broadcast ops expand to a Tile followed by a Reshape operation', 'test that broadcasting a trailing dimension generates an initial Reshape before Tile', 'test that broadcasting multiple dimensions groups and tiles them correctly', 'run the absltest suite for TensorFlow preprocessing einshape ops', 'test einshape to reshape a 1D TensorFlow tensor into a 2D column vector using the i->i1 equation', 'test einshape to transpose a 2D TensorFlow tensor using the ij->ji equation notation', 'test einshape to ungroup a flat tensor into a 2D shape using the (ij)->ij equation with a size hint', 'test einshape to group a 2D tensor into a flat 1D tensor using the ij->(ij) equation', 'test einshape to tile a 1D tensor along a new dimension using the j->nj equation with a size hint']
```

Usage

```
{'test_preprocessing_reshapes_and_transposes': 'test that Reshape and Transpose ops are preserved unchanged by preprocessing.preprocess', 'test_broadcast_expands_to_tile': 'test that Broadcast ops expand to a Tile followed by a Reshape operation', 'test_broadcast_trailing_dimension': 'test that broadcasting a trailing dimension generates an initial Reshape before Tile', 'test_broadcast_multiple_dimensions': 'test that broadcasting multiple dimensions groups and tiles them correctly', 'run_preprocessing_test_suite': 'run the absltest suite for TensorFlow preprocessing einshape ops'}
```

## File: google-deepmind_einshape/einshape/tests/tensorflow/tf_ops_test.py

Prompts

```
['test that Reshape and Transpose ops are preserved unchanged by preprocessing.preprocess', 'test that Broadcast ops expand to a Tile followed by a Reshape operation', 'test that broadcasting a trailing dimension generates an initial Reshape before Tile', 'test that broadcasting multiple dimensions groups and tiles them correctly', 'run the absltest suite for TensorFlow preprocessing einshape ops', 'test einshape to reshape a 1D TensorFlow tensor into a 2D column vector using the i->i1 equation', 'test einshape to transpose a 2D TensorFlow tensor using the ij->ji equation notation', 'test einshape to ungroup a flat tensor into a 2D shape using the (ij)->ij equation with a size hint', 'test einshape to group a 2D tensor into a flat 1D tensor using the ij->(ij) equation', 'test einshape to tile a 1D tensor along a new dimension using the j->nj equation with a size hint']
```

Usage

```
{'test_einshape_simple_reshape': 'test einshape to reshape a 1D TensorFlow tensor into a 2D column vector using the i->i1 equation', 'test_einshape_simple_transpose': 'test einshape to transpose a 2D TensorFlow tensor using the ij->ji equation notation', 'test_einshape_ungroup': 'test einshape to ungroup a flat tensor into a 2D shape using the (ij)->ij equation with a size hint', 'test_einshape_group': 'test einshape to group a 2D tensor into a flat 1D tensor using the ij->(ij) equation', 'test_einshape_tile': 'test einshape to tile a 1D tensor along a new dimension using the j->nj equation with a size hint'}
```

