# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/_export/serde/serialize.py

Prompts

```
['serialize a torch ExportedProgram into a SerializedArtifact with JSON graph, state dict, and constants bytes', 'deserialize a SerializedArtifact back into a torch ExportedProgram with graph module and signature', 'build a GraphModuleSerializer to serialize an FX graph module into a serialized Graph with inputs, outputs, and nodes', 'build a GraphModuleDeserializer to deserialize a serialized Graph back into an FX graph module with placeholder and call nodes', 'canonicalize an ExportedProgram by sorting inputs, outputs, and nodes for deterministic serialization output', 'create a discriminated union dataclass using _Union as base class with typed fields', 'build a union instance using Union.create with a single keyword argument specifying the active variant', 'test the union type property returns the active variant name as a string', 'test the union value property returns the value of the active variant field', 'review _UnionTag.create validates tag names against dataclass field names at equality check time', 'run the GraphModuleOpUpgrader to upgrade an exported program from an older opset version to a newer one', 'create a function that retrieves available operator upgraders and their old schemas from PyTorch', 'test the get_target_version function to extract the target version from a versioned upgrader name', 'refactor a graph module by replacing old operator versions with upgraded implementations via UpgraderPass', 'build an opset version upgrade pipeline by parsing upgraders and populating transformation passes']
```

Usage

```
{'serialize_exported_program': 'serialize a torch ExportedProgram into a SerializedArtifact with JSON graph, state dict, and constants bytes', 'deserialize_exported_program': 'deserialize a SerializedArtifact back into a torch ExportedProgram with graph module and signature', 'build_graph_module_serializer': 'build a GraphModuleSerializer to serialize an FX graph module into a serialized Graph with inputs, outputs, and nodes', 'build_graph_module_deserializer': 'build a GraphModuleDeserializer to deserialize a serialized Graph back into an FX graph module with placeholder and call nodes', 'canonicalize_exported_program': 'canonicalize an ExportedProgram by sorting inputs, outputs, and nodes for deterministic serialization output'}
```

## File: pytorch_pytorch/torch/_export/serde/union.py

Prompts

```
['serialize a torch ExportedProgram into a SerializedArtifact with JSON graph, state dict, and constants bytes', 'deserialize a SerializedArtifact back into a torch ExportedProgram with graph module and signature', 'build a GraphModuleSerializer to serialize an FX graph module into a serialized Graph with inputs, outputs, and nodes', 'build a GraphModuleDeserializer to deserialize a serialized Graph back into an FX graph module with placeholder and call nodes', 'canonicalize an ExportedProgram by sorting inputs, outputs, and nodes for deterministic serialization output', 'create a discriminated union dataclass using _Union as base class with typed fields', 'build a union instance using Union.create with a single keyword argument specifying the active variant', 'test the union type property returns the active variant name as a string', 'test the union value property returns the value of the active variant field', 'review _UnionTag.create validates tag names against dataclass field names at equality check time', 'run the GraphModuleOpUpgrader to upgrade an exported program from an older opset version to a newer one', 'create a function that retrieves available operator upgraders and their old schemas from PyTorch', 'test the get_target_version function to extract the target version from a versioned upgrader name', 'refactor a graph module by replacing old operator versions with upgraded implementations via UpgraderPass', 'build an opset version upgrade pipeline by parsing upgraders and populating transformation passes']
```

Usage

```
{'create_union_type': 'create a discriminated union dataclass using _Union as base class with typed fields', 'build_union_instance': 'build a union instance using Union.create with a single keyword argument specifying the active variant', 'test_union_type_property': 'test the union type property returns the active variant name as a string', 'test_union_value_property': 'test the union value property returns the value of the active variant field', 'review_union_tag_validation': 'review _UnionTag.create validates tag names against dataclass field names at equality check time'}
```

## File: pytorch_pytorch/torch/_export/serde/upgrade.py

Prompts

```
['serialize a torch ExportedProgram into a SerializedArtifact with JSON graph, state dict, and constants bytes', 'deserialize a SerializedArtifact back into a torch ExportedProgram with graph module and signature', 'build a GraphModuleSerializer to serialize an FX graph module into a serialized Graph with inputs, outputs, and nodes', 'build a GraphModuleDeserializer to deserialize a serialized Graph back into an FX graph module with placeholder and call nodes', 'canonicalize an ExportedProgram by sorting inputs, outputs, and nodes for deterministic serialization output', 'create a discriminated union dataclass using _Union as base class with typed fields', 'build a union instance using Union.create with a single keyword argument specifying the active variant', 'test the union type property returns the active variant name as a string', 'test the union value property returns the value of the active variant field', 'review _UnionTag.create validates tag names against dataclass field names at equality check time', 'run the GraphModuleOpUpgrader to upgrade an exported program from an older opset version to a newer one', 'create a function that retrieves available operator upgraders and their old schemas from PyTorch', 'test the get_target_version function to extract the target version from a versioned upgrader name', 'refactor a graph module by replacing old operator versions with upgraded implementations via UpgraderPass', 'build an opset version upgrade pipeline by parsing upgraders and populating transformation passes']
```

Usage

```
{'run_upgrade_exported_program': 'run the GraphModuleOpUpgrader to upgrade an exported program from an older opset version to a newer one', 'create_function_get_upgraders': 'create a function that retrieves available operator upgraders and their old schemas from PyTorch', 'test_get_target_version': 'test the get_target_version function to extract the target version from a versioned upgrader name', 'refactor_graph_module_ops': 'refactor a graph module by replacing old operator versions with upgraded implementations via UpgraderPass', 'build_opset_version_upgrade': 'build an opset version upgrade pipeline by parsing upgraders and populating transformation passes'}
```

