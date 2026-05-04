# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/data_processing/service/id_spine_combiner.py

Prompts

```
['build command-line arguments for each shard to combine spine and data files in private computation', 'create an IdSpineCombinerService instance to run sharded spine and data combination via binary execution', 'run the IdSpineCombinerService build_args method to generate per-shard command arguments for spine data merging', 'review the IdSpineCombinerService build_args method to understand how sharded file paths and protocol args are constructed', 'refactor the IdSpineCombinerService build_args method to use async primitives instead of a ThreadPoolExecutor', 'build command-line arguments for the PID preparer binary with input and output paths', 'build command-line arguments for the PID preparer binary including an optional run ID', 'get the OneDocker binary name for the union PID preparer service', 'run the PID preparer binary by starting containers via the base service', 'review the PIDPrepareBinaryService class and its build_args and get_binary_name methods', 'build command line arguments string for a PID protocol binary with input output and TLS options', 'get the OneDocker binary name for a given PID protocol and private computation role', 'create a TlsArgs dataclass instance with use_tls flag and optional certificate paths', 'review the PIDRunProtocolBinaryService class and its static methods for building binary arguments', 'summarize how TlsArgs dataclass is used to configure TLS settings for PID protocol binaries', 'build command-line arguments for the sharding service with input filepath, output path, and number of output files', 'get the binary name string for a given ShardType enum value like ROUND_ROBIN or HASHED_FOR_PID', 'create a ShardType enum value to choose between ROUND_ROBIN, HASHED_FOR_PID, or SECURE_RANDOM sharding strategies', 'run the ShardingService to shard input data files into multiple output files using a C++ binary', 'review the ShardingService class and its build_args and get_binary_name static methods for sharding logic']
```

Usage

```
{'build_args_for_sharded_spine_combiner': 'build command-line arguments for each shard to combine spine and data files in private computation', 'create_id_spine_combiner_service': 'create an IdSpineCombinerService instance to run sharded spine and data combination via binary execution', 'run_sharded_spine_data_combination': 'run the IdSpineCombinerService build_args method to generate per-shard command arguments for spine data merging', 'review_id_spine_combiner_build_args': 'review the IdSpineCombinerService build_args method to understand how sharded file paths and protocol args are constructed', 'refactor_id_spine_combiner_to_async': 'refactor the IdSpineCombinerService build_args method to use async primitives instead of a ThreadPoolExecutor'}
```

## File: facebookresearch_fbpcs/fbpcs/data_processing/service/pid_prepare_binary_service.py

Prompts

```
['build command-line arguments for each shard to combine spine and data files in private computation', 'create an IdSpineCombinerService instance to run sharded spine and data combination via binary execution', 'run the IdSpineCombinerService build_args method to generate per-shard command arguments for spine data merging', 'review the IdSpineCombinerService build_args method to understand how sharded file paths and protocol args are constructed', 'refactor the IdSpineCombinerService build_args method to use async primitives instead of a ThreadPoolExecutor', 'build command-line arguments for the PID preparer binary with input and output paths', 'build command-line arguments for the PID preparer binary including an optional run ID', 'get the OneDocker binary name for the union PID preparer service', 'run the PID preparer binary by starting containers via the base service', 'review the PIDPrepareBinaryService class and its build_args and get_binary_name methods', 'build command line arguments string for a PID protocol binary with input output and TLS options', 'get the OneDocker binary name for a given PID protocol and private computation role', 'create a TlsArgs dataclass instance with use_tls flag and optional certificate paths', 'review the PIDRunProtocolBinaryService class and its static methods for building binary arguments', 'summarize how TlsArgs dataclass is used to configure TLS settings for PID protocol binaries', 'build command-line arguments for the sharding service with input filepath, output path, and number of output files', 'get the binary name string for a given ShardType enum value like ROUND_ROBIN or HASHED_FOR_PID', 'create a ShardType enum value to choose between ROUND_ROBIN, HASHED_FOR_PID, or SECURE_RANDOM sharding strategies', 'run the ShardingService to shard input data files into multiple output files using a C++ binary', 'review the ShardingService class and its build_args and get_binary_name static methods for sharding logic']
```

Usage

```
{'build_PIDPrepareBinaryService_args': 'build command-line arguments for the PID preparer binary with input and output paths', 'build_PIDPrepareBinaryService_args_with_run_id': 'build command-line arguments for the PID preparer binary including an optional run ID', 'get_PIDPrepareBinaryService_binary_name': 'get the OneDocker binary name for the union PID preparer service', 'run_PIDPrepareBinaryService_start_containers': 'run the PID preparer binary by starting containers via the base service', 'review_PIDPrepareBinaryService_class': 'review the PIDPrepareBinaryService class and its build_args and get_binary_name methods'}
```

## File: facebookresearch_fbpcs/fbpcs/data_processing/service/pid_run_protocol_binary_service.py

Prompts

```
['build command-line arguments for each shard to combine spine and data files in private computation', 'create an IdSpineCombinerService instance to run sharded spine and data combination via binary execution', 'run the IdSpineCombinerService build_args method to generate per-shard command arguments for spine data merging', 'review the IdSpineCombinerService build_args method to understand how sharded file paths and protocol args are constructed', 'refactor the IdSpineCombinerService build_args method to use async primitives instead of a ThreadPoolExecutor', 'build command-line arguments for the PID preparer binary with input and output paths', 'build command-line arguments for the PID preparer binary including an optional run ID', 'get the OneDocker binary name for the union PID preparer service', 'run the PID preparer binary by starting containers via the base service', 'review the PIDPrepareBinaryService class and its build_args and get_binary_name methods', 'build command line arguments string for a PID protocol binary with input output and TLS options', 'get the OneDocker binary name for a given PID protocol and private computation role', 'create a TlsArgs dataclass instance with use_tls flag and optional certificate paths', 'review the PIDRunProtocolBinaryService class and its static methods for building binary arguments', 'summarize how TlsArgs dataclass is used to configure TLS settings for PID protocol binaries', 'build command-line arguments for the sharding service with input filepath, output path, and number of output files', 'get the binary name string for a given ShardType enum value like ROUND_ROBIN or HASHED_FOR_PID', 'create a ShardType enum value to choose between ROUND_ROBIN, HASHED_FOR_PID, or SECURE_RANDOM sharding strategies', 'run the ShardingService to shard input data files into multiple output files using a C++ binary', 'review the ShardingService class and its build_args and get_binary_name static methods for sharding logic']
```

Usage

```
{'build_args_for_pid_protocol': 'build command line arguments string for a PID protocol binary with input output and TLS options', 'get_binary_name_for_role': 'get the OneDocker binary name for a given PID protocol and private computation role', 'create_tls_args_dataclass': 'create a TlsArgs dataclass instance with use_tls flag and optional certificate paths', 'review_pid_run_protocol_binary_service': 'review the PIDRunProtocolBinaryService class and its static methods for building binary arguments', 'summarize_tls_args_usage': 'summarize how TlsArgs dataclass is used to configure TLS settings for PID protocol binaries'}
```

## File: facebookresearch_fbpcs/fbpcs/data_processing/service/sharding_service.py

Prompts

```
['build command-line arguments for each shard to combine spine and data files in private computation', 'create an IdSpineCombinerService instance to run sharded spine and data combination via binary execution', 'run the IdSpineCombinerService build_args method to generate per-shard command arguments for spine data merging', 'review the IdSpineCombinerService build_args method to understand how sharded file paths and protocol args are constructed', 'refactor the IdSpineCombinerService build_args method to use async primitives instead of a ThreadPoolExecutor', 'build command-line arguments for the PID preparer binary with input and output paths', 'build command-line arguments for the PID preparer binary including an optional run ID', 'get the OneDocker binary name for the union PID preparer service', 'run the PID preparer binary by starting containers via the base service', 'review the PIDPrepareBinaryService class and its build_args and get_binary_name methods', 'build command line arguments string for a PID protocol binary with input output and TLS options', 'get the OneDocker binary name for a given PID protocol and private computation role', 'create a TlsArgs dataclass instance with use_tls flag and optional certificate paths', 'review the PIDRunProtocolBinaryService class and its static methods for building binary arguments', 'summarize how TlsArgs dataclass is used to configure TLS settings for PID protocol binaries', 'build command-line arguments for the sharding service with input filepath, output path, and number of output files', 'get the binary name string for a given ShardType enum value like ROUND_ROBIN or HASHED_FOR_PID', 'create a ShardType enum value to choose between ROUND_ROBIN, HASHED_FOR_PID, or SECURE_RANDOM sharding strategies', 'run the ShardingService to shard input data files into multiple output files using a C++ binary', 'review the ShardingService class and its build_args and get_binary_name static methods for sharding logic']
```

Usage

```
{'build_args_for_sharding': 'build command-line arguments for the sharding service with input filepath, output path, and number of output files', 'get_binary_name_for_shard_type': 'get the binary name string for a given ShardType enum value like ROUND_ROBIN or HASHED_FOR_PID', 'create_shardtype_enum': 'create a ShardType enum value to choose between ROUND_ROBIN, HASHED_FOR_PID, or SECURE_RANDOM sharding strategies', 'run_sharding_service': 'run the ShardingService to shard input data files into multiple output files using a C++ binary', 'review_sharding_service': 'review the ShardingService class and its build_args and get_binary_name static methods for sharding logic'}
```

