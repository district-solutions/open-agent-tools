# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/mrp/src/mrp/life_cycle.py

Prompts

```
['get the current system state with all process info from the MRP life cycle module', 'watch a specific process for state changes using the proc_info_watcher callback function', 'set the state of a named process with optional return code and error info', 'set the ask direction for a named process to UP, DOWN, or NONE', 'deserialize a ProcInfo object from a dictionary using the ProcInfo.fromdict class method', 'create a new process definition using mrp.process with name, runtime, config, and dependencies', 'register a process with environment variables using mrp.process and validate env is dict[str, str]', 'define a process with dependencies on other processes using the deps parameter in mrp.process', 'serialize a ProcDef instance to a dictionary using the asdict method for inspection or storage', 'review the ProcDef dataclass fields including name, root, rule_file, runtime, cfg, deps, and env', 'create a function that recursively updates a nested dictionary with values from another dictionary', 'build a shell command string from items with optional NoEscape segments that skip quoting', 'test the LogPtyPipes class to start and stop async PTY pipe logging for stdout and stderr', 'review the PlainTextLogger class that wraps a0.Logger to send plain text packets with info and err methods', 'summarize the common_env_context context manager that temporarily sets MRP_NAME and A0_TOPIC environment variables']
```

Usage

```
{'get_system_state': 'get the current system state with all process info from the MRP life cycle module', 'watch_proc_info': 'watch a specific process for state changes using the proc_info_watcher callback function', 'set_proc_state': 'set the state of a named process with optional return code and error info', 'set_proc_ask': 'set the ask direction for a named process to UP, DOWN, or NONE', 'deserialize_proc_info': 'deserialize a ProcInfo object from a dictionary using the ProcInfo.fromdict class method'}
```

## File: facebookresearch_fairo/mrp/src/mrp/process_def.py

Prompts

```
['get the current system state with all process info from the MRP life cycle module', 'watch a specific process for state changes using the proc_info_watcher callback function', 'set the state of a named process with optional return code and error info', 'set the ask direction for a named process to UP, DOWN, or NONE', 'deserialize a ProcInfo object from a dictionary using the ProcInfo.fromdict class method', 'create a new process definition using mrp.process with name, runtime, config, and dependencies', 'register a process with environment variables using mrp.process and validate env is dict[str, str]', 'define a process with dependencies on other processes using the deps parameter in mrp.process', 'serialize a ProcDef instance to a dictionary using the asdict method for inspection or storage', 'review the ProcDef dataclass fields including name, root, rule_file, runtime, cfg, deps, and env', 'create a function that recursively updates a nested dictionary with values from another dictionary', 'build a shell command string from items with optional NoEscape segments that skip quoting', 'test the LogPtyPipes class to start and stop async PTY pipe logging for stdout and stderr', 'review the PlainTextLogger class that wraps a0.Logger to send plain text packets with info and err methods', 'summarize the common_env_context context manager that temporarily sets MRP_NAME and A0_TOPIC environment variables']
```

Usage

```
{'create_process_definition': 'create a new process definition using mrp.process with name, runtime, config, and dependencies', 'register_process_with_env': 'register a process with environment variables using mrp.process and validate env is dict[str, str]', 'define_process_with_deps': 'define a process with dependencies on other processes using the deps parameter in mrp.process', 'serialize_procdef_asdict': 'serialize a ProcDef instance to a dictionary using the asdict method for inspection or storage', 'review_procdef_dataclass': 'review the ProcDef dataclass fields including name, root, rule_file, runtime, cfg, deps, and env'}
```

## File: facebookresearch_fairo/mrp/src/mrp/util.py

Prompts

```
['get the current system state with all process info from the MRP life cycle module', 'watch a specific process for state changes using the proc_info_watcher callback function', 'set the state of a named process with optional return code and error info', 'set the ask direction for a named process to UP, DOWN, or NONE', 'deserialize a ProcInfo object from a dictionary using the ProcInfo.fromdict class method', 'create a new process definition using mrp.process with name, runtime, config, and dependencies', 'register a process with environment variables using mrp.process and validate env is dict[str, str]', 'define a process with dependencies on other processes using the deps parameter in mrp.process', 'serialize a ProcDef instance to a dictionary using the asdict method for inspection or storage', 'review the ProcDef dataclass fields including name, root, rule_file, runtime, cfg, deps, and env', 'create a function that recursively updates a nested dictionary with values from another dictionary', 'build a shell command string from items with optional NoEscape segments that skip quoting', 'test the LogPtyPipes class to start and stop async PTY pipe logging for stdout and stderr', 'review the PlainTextLogger class that wraps a0.Logger to send plain text packets with info and err methods', 'summarize the common_env_context context manager that temporarily sets MRP_NAME and A0_TOPIC environment variables']
```

Usage

```
{'create_nested_dict_update': 'create a function that recursively updates a nested dictionary with values from another dictionary', 'build_shell_join': 'build a shell command string from items with optional NoEscape segments that skip quoting', 'test_LogPtyPipes': 'test the LogPtyPipes class to start and stop async PTY pipe logging for stdout and stderr', 'review_PlainTextLogger': 'review the PlainTextLogger class that wraps a0.Logger to send plain text packets with info and err methods', 'summarize_common_env_context': 'summarize the common_env_context context manager that temporarily sets MRP_NAME and A0_TOPIC environment variables'}
```

