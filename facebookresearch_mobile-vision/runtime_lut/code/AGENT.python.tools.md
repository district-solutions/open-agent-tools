# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/runtime_lut/code/api.py

Prompts

```
['calculate the runtime latency for a Caffe2 model using the operator lookup table database', 'extract the runtime of a single operator from the lookup table database by average max or min', 'extract all operators and their input shapes and dtypes from a Caffe2 model protobuf', 'encode a numpy dtype string to the corresponding Caffe2 core DataType enum value', 'load operator records from a JSON database file and convert them into LUTSchema instances', 'create a LUTSchema instance to define a lookup table schema for Caffe2 operator runtime records', 'load a Caffe2 operator definition into a LUTSchema record with input shapes and data types', 'set a value for a specific key in the LUTSchema record dictionary', 'get the value of a specific key from the LUTSchema record dictionary', 'load LUTSchema record values from a JSON string or dictionary input', 'load a Caffe2 model from protobuf net and init files into the workspace', 'create a Caffe2 fill operator to store a numpy tensor or Int8Tensor blob', 'infer output blob shapes and dtypes by running each operator sequentially in a Caffe2 net', 'infer model output shapes by providing extra input shapes as lists or dicts', 'use a context manager to switch, reset, and restore Caffe2 workspaces safely']
```

Usage

```
{'get_net_runtime': 'calculate the runtime latency for a Caffe2 model using the operator lookup table database', 'get_op_runtime': 'extract the runtime of a single operator from the lookup table database by average max or min', 'get_ops_from_net': 'extract all operators and their input shapes and dtypes from a Caffe2 model protobuf', 'encode_dtype': 'encode a numpy dtype string to the corresponding Caffe2 core DataType enum value', 'OpLut_load': 'load operator records from a JSON database file and convert them into LUTSchema instances'}
```

## File: facebookresearch_mobile-vision/runtime_lut/code/lut_schema.py

Prompts

```
['calculate the runtime latency for a Caffe2 model using the operator lookup table database', 'extract the runtime of a single operator from the lookup table database by average max or min', 'extract all operators and their input shapes and dtypes from a Caffe2 model protobuf', 'encode a numpy dtype string to the corresponding Caffe2 core DataType enum value', 'load operator records from a JSON database file and convert them into LUTSchema instances', 'create a LUTSchema instance to define a lookup table schema for Caffe2 operator runtime records', 'load a Caffe2 operator definition into a LUTSchema record with input shapes and data types', 'set a value for a specific key in the LUTSchema record dictionary', 'get the value of a specific key from the LUTSchema record dictionary', 'load LUTSchema record values from a JSON string or dictionary input', 'load a Caffe2 model from protobuf net and init files into the workspace', 'create a Caffe2 fill operator to store a numpy tensor or Int8Tensor blob', 'infer output blob shapes and dtypes by running each operator sequentially in a Caffe2 net', 'infer model output shapes by providing extra input shapes as lists or dicts', 'use a context manager to switch, reset, and restore Caffe2 workspaces safely']
```

Usage

```
{'create_LUTSchema': 'create a LUTSchema instance to define a lookup table schema for Caffe2 operator runtime records', 'load_caffe2_op': 'load a Caffe2 operator definition into a LUTSchema record with input shapes and data types', 'set_val_LUTSchema': 'set a value for a specific key in the LUTSchema record dictionary', 'get_val_LUTSchema': 'get the value of a specific key from the LUTSchema record dictionary', 'load_from_json_LUTSchema': 'load LUTSchema record values from a JSON string or dictionary input'}
```

## File: facebookresearch_mobile-vision/runtime_lut/code/model_utils.py

Prompts

```
['calculate the runtime latency for a Caffe2 model using the operator lookup table database', 'extract the runtime of a single operator from the lookup table database by average max or min', 'extract all operators and their input shapes and dtypes from a Caffe2 model protobuf', 'encode a numpy dtype string to the corresponding Caffe2 core DataType enum value', 'load operator records from a JSON database file and convert them into LUTSchema instances', 'create a LUTSchema instance to define a lookup table schema for Caffe2 operator runtime records', 'load a Caffe2 operator definition into a LUTSchema record with input shapes and data types', 'set a value for a specific key in the LUTSchema record dictionary', 'get the value of a specific key from the LUTSchema record dictionary', 'load LUTSchema record values from a JSON string or dictionary input', 'load a Caffe2 model from protobuf net and init files into the workspace', 'create a Caffe2 fill operator to store a numpy tensor or Int8Tensor blob', 'infer output blob shapes and dtypes by running each operator sequentially in a Caffe2 net', 'infer model output shapes by providing extra input shapes as lists or dicts', 'use a context manager to switch, reset, and restore Caffe2 workspaces safely']
```

Usage

```
{'load_model_pb': 'load a Caffe2 model from protobuf net and init files into the workspace', 'create_fill_op': 'create a Caffe2 fill operator to store a numpy tensor or Int8Tensor blob', 'infer_model_shape_by_ops': 'infer output blob shapes and dtypes by running each operator sequentially in a Caffe2 net', 'infer_model_shape_by_ops_shape': 'infer model output shapes by providing extra input shapes as lists or dicts', 'ScopedWS': 'use a context manager to switch, reset, and restore Caffe2 workspaces safely'}
```

