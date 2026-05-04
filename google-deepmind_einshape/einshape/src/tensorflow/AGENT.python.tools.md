# Agent Python Tools

- repo: google-deepmind/einshape
- repo_uri: https://github.com/google-deepmind/einshape

## File: google-deepmind_einshape/einshape/src/tensorflow/preprocessing.py

Prompts

```
['create a Tile shape op that tiles tensor axes by given multiples', 'check if a Tile op has all integer multiples for static shape inference', 'transform an input shape by multiplying each dimension with its tile multiple', 'execute a Tile op on a TensorFlow backend to tile a tensor', 'preprocess a sequence of shape ops replacing Broadcast ops with Tile and Reshape for TensorFlow', 'use einshape to reshape a TensorFlow tensor according to a shape equation string', 'use einshape to transpose a TensorFlow tensor by reordering its index dimensions', 'use einshape to tile a TensorFlow tensor along specified axes via the Tile preprocessing op', 'use the _TFBackend exec method to run einshape operations on a TensorFlow tensor', 'use the TensorFlow preprocessing function to replace Broadcast ops with Tile and Reshape ops']
```

Usage

```
{'create_tile_op': 'create a Tile shape op that tiles tensor axes by given multiples', 'check_tile_is_static': 'check if a Tile op has all integer multiples for static shape inference', 'transform_shape_with_tile': 'transform an input shape by multiplying each dimension with its tile multiple', 'execute_tile_on_backend': 'execute a Tile op on a TensorFlow backend to tile a tensor', 'preprocess_broadcast_ops': 'preprocess a sequence of shape ops replacing Broadcast ops with Tile and Reshape for TensorFlow'}
```

## File: google-deepmind_einshape/einshape/src/tensorflow/tf_ops.py

Prompts

```
['create a Tile shape op that tiles tensor axes by given multiples', 'check if a Tile op has all integer multiples for static shape inference', 'transform an input shape by multiplying each dimension with its tile multiple', 'execute a Tile op on a TensorFlow backend to tile a tensor', 'preprocess a sequence of shape ops replacing Broadcast ops with Tile and Reshape for TensorFlow', 'use einshape to reshape a TensorFlow tensor according to a shape equation string', 'use einshape to transpose a TensorFlow tensor by reordering its index dimensions', 'use einshape to tile a TensorFlow tensor along specified axes via the Tile preprocessing op', 'use the _TFBackend exec method to run einshape operations on a TensorFlow tensor', 'use the TensorFlow preprocessing function to replace Broadcast ops with Tile and Reshape ops']
```

Usage

```
{'use_einshape_reshape_tensor': 'use einshape to reshape a TensorFlow tensor according to a shape equation string', 'use_einshape_transpose_tensor': 'use einshape to transpose a TensorFlow tensor by reordering its index dimensions', 'use_einshape_tile_tensor': 'use einshape to tile a TensorFlow tensor along specified axes via the Tile preprocessing op', 'use_tfbackend_exec': 'use the _TFBackend exec method to run einshape operations on a TensorFlow tensor', 'use_preprocess_broadcast_ops': 'use the TensorFlow preprocessing function to replace Broadcast ops with Tile and Reshape ops'}
```

