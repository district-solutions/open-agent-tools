# Agent Python Tools

- repo: google-deepmind/envlogger
- repo_uri: https://github.com/google-deepmind/envlogger

## File: google-deepmind_envlogger/envlogger/converters/codec.py

Prompts

```
['encode a numpy array into a storage_pb2.Data protobuf object for serialization to disk', 'encode Python lists, tuples, dicts, or scalars into storage_pb2.Data protobuf objects', 'decode a storage_pb2.Data protobuf back into numpy arrays, lists, tuples, or dicts', 'decode a single Datum protobuf into a numpy scalar or reshaped numpy array', 'encode a Python integer into a signed big-endian byte string without losing precision', 'encode Python scalars, numpy arrays, lists, tuples, and dicts into storage_pb2.Data protobuf objects', 'decode storage_pb2.Data protobuf objects back into Python scalars, numpy arrays, lists, tuples, and dicts', 'encode multidimensional numpy arrays of any supported dtype into protobuf with preserved shape and dtype', 'encode nested dicts, lists of numpy arrays, and tuples into protobuf with mixed key types', 'test that encoding then decoding preserves values for scalars, arrays, lists, tuples, and dicts', 'encode all observation, action, reward, and discount specs from a dm_env.Environment into a serializable dictionary', 'decode a dictionary of encoded environment specs back into dm_env.specs.Array objects', 'encode a dm_env.specs.Array, list, tuple, or dict of specs into plain Python objects for serialization', 'decode a serialized dict, list, or tuple back into dm_env.specs.Array, BoundedArray, or DiscreteArray objects', 'convert a single dm_env.specs.Array including BoundedArray and DiscreteArray into a dictionary with shape, dtype, and bounds', 'test encoding a dm_env specs.Array into a serializable dictionary with shape dtype and name', 'test encoding a dm_env specs.BoundedArray including minimum and maximum bounds into a dictionary', 'test encoding a dm_env specs.DiscreteArray with num_values into a serializable dictionary', 'test decoding a serialized spec dictionary back into a dm_env specs.Array object', 'test that encoding then decoding a spec structure returns an equal spec to the original']
```

Usage

```
{'encode_numpy_array_to_proto': 'encode a numpy array into a storage_pb2.Data protobuf object for serialization to disk', 'encode_python_data_to_proto': 'encode Python lists, tuples, dicts, or scalars into storage_pb2.Data protobuf objects', 'decode_proto_to_python': 'decode a storage_pb2.Data protobuf back into numpy arrays, lists, tuples, or dicts', 'decode_datum_to_scalar_or_array': 'decode a single Datum protobuf into a numpy scalar or reshaped numpy array', 'encode_arbitrary_int_to_bytes': 'encode a Python integer into a signed big-endian byte string without losing precision'}
```

## File: google-deepmind_envlogger/envlogger/converters/codec_test.py

Prompts

```
['encode a numpy array into a storage_pb2.Data protobuf object for serialization to disk', 'encode Python lists, tuples, dicts, or scalars into storage_pb2.Data protobuf objects', 'decode a storage_pb2.Data protobuf back into numpy arrays, lists, tuples, or dicts', 'decode a single Datum protobuf into a numpy scalar or reshaped numpy array', 'encode a Python integer into a signed big-endian byte string without losing precision', 'encode Python scalars, numpy arrays, lists, tuples, and dicts into storage_pb2.Data protobuf objects', 'decode storage_pb2.Data protobuf objects back into Python scalars, numpy arrays, lists, tuples, and dicts', 'encode multidimensional numpy arrays of any supported dtype into protobuf with preserved shape and dtype', 'encode nested dicts, lists of numpy arrays, and tuples into protobuf with mixed key types', 'test that encoding then decoding preserves values for scalars, arrays, lists, tuples, and dicts', 'encode all observation, action, reward, and discount specs from a dm_env.Environment into a serializable dictionary', 'decode a dictionary of encoded environment specs back into dm_env.specs.Array objects', 'encode a dm_env.specs.Array, list, tuple, or dict of specs into plain Python objects for serialization', 'decode a serialized dict, list, or tuple back into dm_env.specs.Array, BoundedArray, or DiscreteArray objects', 'convert a single dm_env.specs.Array including BoundedArray and DiscreteArray into a dictionary with shape, dtype, and bounds', 'test encoding a dm_env specs.Array into a serializable dictionary with shape dtype and name', 'test encoding a dm_env specs.BoundedArray including minimum and maximum bounds into a dictionary', 'test encoding a dm_env specs.DiscreteArray with num_values into a serializable dictionary', 'test decoding a serialized spec dictionary back into a dm_env specs.Array object', 'test that encoding then decoding a spec structure returns an equal spec to the original']
```

Usage

```
{'encode_python_values_to_proto': 'encode Python scalars, numpy arrays, lists, tuples, and dicts into storage_pb2.Data protobuf objects', 'decode_proto_to_python_values': 'decode storage_pb2.Data protobuf objects back into Python scalars, numpy arrays, lists, tuples, and dicts', 'encode_numpy_arrays_to_proto': 'encode multidimensional numpy arrays of any supported dtype into protobuf with preserved shape and dtype', 'encode_nested_structures_to_proto': 'encode nested dicts, lists of numpy arrays, and tuples into protobuf with mixed key types', 'test_codec_roundtrip_identity': 'test that encoding then decoding preserves values for scalars, arrays, lists, tuples, and dicts'}
```

## File: google-deepmind_envlogger/envlogger/converters/spec_codec.py

Prompts

```
['encode a numpy array into a storage_pb2.Data protobuf object for serialization to disk', 'encode Python lists, tuples, dicts, or scalars into storage_pb2.Data protobuf objects', 'decode a storage_pb2.Data protobuf back into numpy arrays, lists, tuples, or dicts', 'decode a single Datum protobuf into a numpy scalar or reshaped numpy array', 'encode a Python integer into a signed big-endian byte string without losing precision', 'encode Python scalars, numpy arrays, lists, tuples, and dicts into storage_pb2.Data protobuf objects', 'decode storage_pb2.Data protobuf objects back into Python scalars, numpy arrays, lists, tuples, and dicts', 'encode multidimensional numpy arrays of any supported dtype into protobuf with preserved shape and dtype', 'encode nested dicts, lists of numpy arrays, and tuples into protobuf with mixed key types', 'test that encoding then decoding preserves values for scalars, arrays, lists, tuples, and dicts', 'encode all observation, action, reward, and discount specs from a dm_env.Environment into a serializable dictionary', 'decode a dictionary of encoded environment specs back into dm_env.specs.Array objects', 'encode a dm_env.specs.Array, list, tuple, or dict of specs into plain Python objects for serialization', 'decode a serialized dict, list, or tuple back into dm_env.specs.Array, BoundedArray, or DiscreteArray objects', 'convert a single dm_env.specs.Array including BoundedArray and DiscreteArray into a dictionary with shape, dtype, and bounds', 'test encoding a dm_env specs.Array into a serializable dictionary with shape dtype and name', 'test encoding a dm_env specs.BoundedArray including minimum and maximum bounds into a dictionary', 'test encoding a dm_env specs.DiscreteArray with num_values into a serializable dictionary', 'test decoding a serialized spec dictionary back into a dm_env specs.Array object', 'test that encoding then decoding a spec structure returns an equal spec to the original']
```

Usage

```
{'encode_environment_specs': 'encode all observation, action, reward, and discount specs from a dm_env.Environment into a serializable dictionary', 'decode_environment_specs': 'decode a dictionary of encoded environment specs back into dm_env.specs.Array objects', 'encode_spec': 'encode a dm_env.specs.Array, list, tuple, or dict of specs into plain Python objects for serialization', 'decode_spec': 'decode a serialized dict, list, or tuple back into dm_env.specs.Array, BoundedArray, or DiscreteArray objects', 'array_spec_to_dict': 'convert a single dm_env.specs.Array including BoundedArray and DiscreteArray into a dictionary with shape, dtype, and bounds'}
```

## File: google-deepmind_envlogger/envlogger/converters/spec_codec_test.py

Prompts

```
['encode a numpy array into a storage_pb2.Data protobuf object for serialization to disk', 'encode Python lists, tuples, dicts, or scalars into storage_pb2.Data protobuf objects', 'decode a storage_pb2.Data protobuf back into numpy arrays, lists, tuples, or dicts', 'decode a single Datum protobuf into a numpy scalar or reshaped numpy array', 'encode a Python integer into a signed big-endian byte string without losing precision', 'encode Python scalars, numpy arrays, lists, tuples, and dicts into storage_pb2.Data protobuf objects', 'decode storage_pb2.Data protobuf objects back into Python scalars, numpy arrays, lists, tuples, and dicts', 'encode multidimensional numpy arrays of any supported dtype into protobuf with preserved shape and dtype', 'encode nested dicts, lists of numpy arrays, and tuples into protobuf with mixed key types', 'test that encoding then decoding preserves values for scalars, arrays, lists, tuples, and dicts', 'encode all observation, action, reward, and discount specs from a dm_env.Environment into a serializable dictionary', 'decode a dictionary of encoded environment specs back into dm_env.specs.Array objects', 'encode a dm_env.specs.Array, list, tuple, or dict of specs into plain Python objects for serialization', 'decode a serialized dict, list, or tuple back into dm_env.specs.Array, BoundedArray, or DiscreteArray objects', 'convert a single dm_env.specs.Array including BoundedArray and DiscreteArray into a dictionary with shape, dtype, and bounds', 'test encoding a dm_env specs.Array into a serializable dictionary with shape dtype and name', 'test encoding a dm_env specs.BoundedArray including minimum and maximum bounds into a dictionary', 'test encoding a dm_env specs.DiscreteArray with num_values into a serializable dictionary', 'test decoding a serialized spec dictionary back into a dm_env specs.Array object', 'test that encoding then decoding a spec structure returns an equal spec to the original']
```

Usage

```
{'test_encode_array_spec': 'test encoding a dm_env specs.Array into a serializable dictionary with shape dtype and name', 'test_encode_bounded_array_spec': 'test encoding a dm_env specs.BoundedArray including minimum and maximum bounds into a dictionary', 'test_encode_discrete_array_spec': 'test encoding a dm_env specs.DiscreteArray with num_values into a serializable dictionary', 'test_decode_array_spec': 'test decoding a serialized spec dictionary back into a dm_env specs.Array object', 'test_roundtrip_encode_decode': 'test that encoding then decoding a spec structure returns an equal spec to the original'}
```

