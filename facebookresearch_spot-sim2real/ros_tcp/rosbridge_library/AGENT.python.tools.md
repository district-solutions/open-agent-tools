# Agent Python Tools

- repo: facebookresearch/spot-sim2real
- repo_uri: https://github.com/facebookresearch/spot-sim2real

## File: facebookresearch_spot-sim2real/ros_tcp/rosbridge_library/protocol.py

Prompts

```
['process an incoming JSON or BSON message from a rosbridge client and route to the correct operation handler', 'send a message to a client with automatic fragmentation if the message exceeds the configured fragment size', 'register a callback handler for a specific rosbridge opcode so incoming messages with that op are dispatched correctly', 'serialize a message dictionary to JSON or BSON and deserialize wire-level messages back into dictionaries', 'add a capability class to the protocol instance to extend its functionality with new rosbridge operations']
```

Usage

```
{'process_incoming_client_message': 'process an incoming JSON or BSON message from a rosbridge client and route to the correct operation handler', 'send_message_with_fragmentation': 'send a message to a client with automatic fragmentation if the message exceeds the configured fragment size', 'register_operation_handler': 'register a callback handler for a specific rosbridge opcode so incoming messages with that op are dispatched correctly', 'serialize_deserialize_messages': 'serialize a message dictionary to JSON or BSON and deserialize wire-level messages back into dictionaries', 'add_protocol_capability': 'add a capability class to the protocol instance to extend its functionality with new rosbridge operations'}
```

