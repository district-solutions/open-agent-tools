# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/rts/engine/common_loader.py

Prompts

```
['create a CommonLoader subclass and call initialize to set up the RTS game context with actor and train specs', 'call initialize_selfplay on a CommonLoader subclass to set up a two-player self-play game context with reference and train actors', 'call initialize_reduced_service on a CommonLoader subclass to set up a reduced service context with project, forward, and predict specs', 'call _parse_players on a CommonLoader instance to parse semicolon-separated player info strings into AIOptions objects', 'override the _define_args method in a CommonLoader subclass to add custom argument definitions for the RTS engine', 'generate a C++ header file from a command definition file using --def_file and --name args', 'parse CMD_IMMEDIATE and CMD_DURATIVE macro definitions from a .def file into C++ classes', 'build a C++ command class template with accessors, serializers, and clone methods from parsed definitions', 'convert a camelCase command name to a SCREAMING_SNAKE_CASE enum name using get_class_and_enum_name', 'register generated command types and serializer anchors in the output C++ header file']
```

Usage

```
{'initialize_CommonLoader': 'create a CommonLoader subclass and call initialize to set up the RTS game context with actor and train specs', 'initialize_selfplay_CommonLoader': 'call initialize_selfplay on a CommonLoader subclass to set up a two-player self-play game context with reference and train actors', 'initialize_reduced_service_CommonLoader': 'call initialize_reduced_service on a CommonLoader subclass to set up a reduced service context with project, forward, and predict specs', 'parse_players_CommonLoader': 'call _parse_players on a CommonLoader instance to parse semicolon-separated player info strings into AIOptions objects', 'define_args_CommonLoader': 'override the _define_args method in a CommonLoader subclass to add custom argument definitions for the RTS engine'}
```

## File: facebookresearch_elf/rts/engine/compile_cmds.py

Prompts

```
['create a CommonLoader subclass and call initialize to set up the RTS game context with actor and train specs', 'call initialize_selfplay on a CommonLoader subclass to set up a two-player self-play game context with reference and train actors', 'call initialize_reduced_service on a CommonLoader subclass to set up a reduced service context with project, forward, and predict specs', 'call _parse_players on a CommonLoader instance to parse semicolon-separated player info strings into AIOptions objects', 'override the _define_args method in a CommonLoader subclass to add custom argument definitions for the RTS engine', 'generate a C++ header file from a command definition file using --def_file and --name args', 'parse CMD_IMMEDIATE and CMD_DURATIVE macro definitions from a .def file into C++ classes', 'build a C++ command class template with accessors, serializers, and clone methods from parsed definitions', 'convert a camelCase command name to a SCREAMING_SNAKE_CASE enum name using get_class_and_enum_name', 'register generated command types and serializer anchors in the output C++ header file']
```

Usage

```
{'generate_cpp_header_from_def': 'generate a C++ header file from a command definition file using --def_file and --name args', 'parse_cmd_definitions': 'parse CMD_IMMEDIATE and CMD_DURATIVE macro definitions from a .def file into C++ classes', 'build_cmd_class_template': 'build a C++ command class template with accessors, serializers, and clone methods from parsed definitions', 'convert_camel_to_enum': 'convert a camelCase command name to a SCREAMING_SNAKE_CASE enum name using get_class_and_enum_name', 'register_cmd_types': 'register generated command types and serializer anchors in the output C++ header file'}
```

