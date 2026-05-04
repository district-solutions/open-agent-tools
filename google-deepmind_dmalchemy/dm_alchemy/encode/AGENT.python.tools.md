# Agent Python Tools

- repo: google-deepmind/dmalchemy
- repo_uri: https://github.com/google-deepmind/dm_alchemy

## File: google-deepmind_dmalchemy/dm_alchemy/encode/chemistries_proto_conversion.py

Prompts

```
['convert a Chemistry object to a protobuf message for serialization', 'convert a Chemistry protobuf message back to a Chemistry object', 'write a sequence of chemistry and episode items tuples to a file as serialized protobuf', 'load chemistry and episode items from a serialized protobuf file', 'convert TrialItems containing stones and potions to a protobuf message', 'write a numpy int array to a serialized protobuf file in a given folder', 'load a serialized protobuf int array file from a folder into a numpy array', 'write a numpy bitfield array to a base64-encoded protobuf file in a folder', 'load a base64-encoded protobuf bitfield array file from a folder into a numpy array', 'convert a dm_alchemy Graph object to a protobuf GraphArray entry for serialization', 'convert a MatrixEventTracker trial events object into a precomputed_maps_pb2 IntArray proto message', 'convert an IntArray proto message back into a MatrixEventTracker trial events object', 'convert a sequence of MatrixEventTracker trial events into a symbolic_actions_pb2 EpisodeEvents proto', 'convert an EpisodeEvents proto back into a list of MatrixEventTracker trial events objects', 'convert a nested sequence of MatrixEventTracker events into a symbolic_actions_pb2 EvaluationSetEvents proto']
```

Usage

```
{'convert_chemistry_to_proto': 'convert a Chemistry object to a protobuf message for serialization', 'convert_proto_to_chemistry': 'convert a Chemistry protobuf message back to a Chemistry object', 'write_chemistries_and_items': 'write a sequence of chemistry and episode items tuples to a file as serialized protobuf', 'load_chemistries_and_items': 'load chemistry and episode items from a serialized protobuf file', 'convert_trial_items_to_proto': 'convert TrialItems containing stones and potions to a protobuf message'}
```

## File: google-deepmind_dmalchemy/dm_alchemy/encode/precomputed_maps_proto_conversion.py

Prompts

```
['convert a Chemistry object to a protobuf message for serialization', 'convert a Chemistry protobuf message back to a Chemistry object', 'write a sequence of chemistry and episode items tuples to a file as serialized protobuf', 'load chemistry and episode items from a serialized protobuf file', 'convert TrialItems containing stones and potions to a protobuf message', 'write a numpy int array to a serialized protobuf file in a given folder', 'load a serialized protobuf int array file from a folder into a numpy array', 'write a numpy bitfield array to a base64-encoded protobuf file in a folder', 'load a base64-encoded protobuf bitfield array file from a folder into a numpy array', 'convert a dm_alchemy Graph object to a protobuf GraphArray entry for serialization', 'convert a MatrixEventTracker trial events object into a precomputed_maps_pb2 IntArray proto message', 'convert an IntArray proto message back into a MatrixEventTracker trial events object', 'convert a sequence of MatrixEventTracker trial events into a symbolic_actions_pb2 EpisodeEvents proto', 'convert an EpisodeEvents proto back into a list of MatrixEventTracker trial events objects', 'convert a nested sequence of MatrixEventTracker events into a symbolic_actions_pb2 EvaluationSetEvents proto']
```

Usage

```
{'write_int_array': 'write a numpy int array to a serialized protobuf file in a given folder', 'load_int_array': 'load a serialized protobuf int array file from a folder into a numpy array', 'write_bitfield_array': 'write a numpy bitfield array to a base64-encoded protobuf file in a folder', 'load_bitfield_array': 'load a base64-encoded protobuf bitfield array file from a folder into a numpy array', 'graph_to_proto': 'convert a dm_alchemy Graph object to a protobuf GraphArray entry for serialization'}
```

## File: google-deepmind_dmalchemy/dm_alchemy/encode/symbolic_actions_proto_conversion.py

Prompts

```
['convert a Chemistry object to a protobuf message for serialization', 'convert a Chemistry protobuf message back to a Chemistry object', 'write a sequence of chemistry and episode items tuples to a file as serialized protobuf', 'load chemistry and episode items from a serialized protobuf file', 'convert TrialItems containing stones and potions to a protobuf message', 'write a numpy int array to a serialized protobuf file in a given folder', 'load a serialized protobuf int array file from a folder into a numpy array', 'write a numpy bitfield array to a base64-encoded protobuf file in a folder', 'load a base64-encoded protobuf bitfield array file from a folder into a numpy array', 'convert a dm_alchemy Graph object to a protobuf GraphArray entry for serialization', 'convert a MatrixEventTracker trial events object into a precomputed_maps_pb2 IntArray proto message', 'convert an IntArray proto message back into a MatrixEventTracker trial events object', 'convert a sequence of MatrixEventTracker trial events into a symbolic_actions_pb2 EpisodeEvents proto', 'convert an EpisodeEvents proto back into a list of MatrixEventTracker trial events objects', 'convert a nested sequence of MatrixEventTracker events into a symbolic_actions_pb2 EvaluationSetEvents proto']
```

Usage

```
{'convert_trial_events_to_proto': 'convert a MatrixEventTracker trial events object into a precomputed_maps_pb2 IntArray proto message', 'convert_proto_to_trial_events': 'convert an IntArray proto message back into a MatrixEventTracker trial events object', 'convert_episode_events_to_proto': 'convert a sequence of MatrixEventTracker trial events into a symbolic_actions_pb2 EpisodeEvents proto', 'convert_proto_to_episode_events': 'convert an EpisodeEvents proto back into a list of MatrixEventTracker trial events objects', 'convert_evaluation_set_to_proto': 'convert a nested sequence of MatrixEventTracker events into a symbolic_actions_pb2 EvaluationSetEvents proto'}
```

