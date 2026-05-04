# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/heyhi/bin/patch_protos.py

Prompts

```
['patch generated protobuf _pb2.py files to add extra fields like to_dict and to_frozen', 'patch protobuf .pyi stub files to add type hints for frozen config classes', 'create a frozen read-only wrapper class from a protobuf message class', 'add to_dict, to_frozen, to_editable, and is_frozen methods to proto messages', 'use _FrozenConf to create immutable config objects from protobuf messages with field access']
```

Usage

```
{'patch_proto_files': 'patch generated protobuf _pb2.py files to add extra fields like to_dict and to_frozen', 'patch_pb2_pyi_files': 'patch protobuf .pyi stub files to add type hints for frozen config classes', 'create_frozen_class': 'create a frozen read-only wrapper class from a protobuf message class', 'extra_fields_methods': 'add to_dict, to_frozen, to_editable, and is_frozen methods to proto messages', 'frozen_conf_usage': 'use _FrozenConf to create immutable config objects from protobuf messages with field access'}
```

