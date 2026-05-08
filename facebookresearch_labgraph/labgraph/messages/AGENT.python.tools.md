# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/messages/message.py

Prompts

```
['create a Labgraph Message subclass with typed fields for shared memory IPC communication', 'create a TimestampedMessage subclass with a timestamp field for time-aligned data', 'serialize a Labgraph Message instance to an OrderedDict using the asdict method', 'deserialize a Labgraph Message from a dictionary using the fromdict class method', 'create a new Labgraph Message with selected fields replaced using the replace method', 'get a FieldType instance for a Python type like int, float, str, bool, bytes, numpy.ndarray, Enum, List, Dict, or dataclass', 'pack a Python value into bytes using a FieldType for serialization with struct or pickle', 'unpack bytes back into a Python value using a FieldType with struct or pickle deserialization', 'encode the length of an object as a zero-padded 10-byte ASCII length prefix', 'read a length-prefixed chunk of bytes from a byte stream and return the raw bytes and updated cursor position']
```

Usage

```
{'create_Message_subclass': 'create a Labgraph Message subclass with typed fields for shared memory IPC communication', 'create_TimestampedMessage_subclass': 'create a TimestampedMessage subclass with a timestamp field for time-aligned data', 'serialize_message_asdict': 'serialize a Labgraph Message instance to an OrderedDict using the asdict method', 'deserialize_message_fromdict': 'deserialize a Labgraph Message from a dictionary using the fromdict class method', 'replace_message_fields': 'create a new Labgraph Message with selected fields replaced using the replace method'}
```

## File: facebookresearch_labgraph/labgraph/messages/types.py

Prompts

```
['create a Labgraph Message subclass with typed fields for shared memory IPC communication', 'create a TimestampedMessage subclass with a timestamp field for time-aligned data', 'serialize a Labgraph Message instance to an OrderedDict using the asdict method', 'deserialize a Labgraph Message from a dictionary using the fromdict class method', 'create a new Labgraph Message with selected fields replaced using the replace method', 'get a FieldType instance for a Python type like int, float, str, bool, bytes, numpy.ndarray, Enum, List, Dict, or dataclass', 'pack a Python value into bytes using a FieldType for serialization with struct or pickle', 'unpack bytes back into a Python value using a FieldType with struct or pickle deserialization', 'encode the length of an object as a zero-padded 10-byte ASCII length prefix', 'read a length-prefixed chunk of bytes from a byte stream and return the raw bytes and updated cursor position']
```

Usage

```
{'get_field_type': 'get a FieldType instance for a Python type like int, float, str, bool, bytes, numpy.ndarray, Enum, List, Dict, or dataclass', 'get_packed_value': 'pack a Python value into bytes using a FieldType for serialization with struct or pickle', 'get_unpacked_value': 'unpack bytes back into a Python value using a FieldType with struct or pickle deserialization', 'get_len_bytes': 'encode the length of an object as a zero-padded 10-byte ASCII length prefix', 'get_next_bytes': 'read a length-prefixed chunk of bytes from a byte stream and return the raw bytes and updated cursor position'}
```

