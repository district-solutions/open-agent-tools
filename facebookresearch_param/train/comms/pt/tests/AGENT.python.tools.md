# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/train/comms/pt/tests/commsTraceReplay_tests.py

Prompts

```
['test the prepComms method to verify correct tensor generation for collective communications like wait, barrier, recv, and all_gather', 'test the replayTrace method to ensure warmup and replay runs without failure on a trace of commsArgs entries', 'test the runComms method to verify it returns latency and global_latency for blocking and non-blocking collective operations', 'test the initTraceStat method to verify trace stats and comm blocks are initialized correctly on the first dry run', 'test the rebalanceSplit method to verify equal policy rebalances inMsgSize, outMsgSize, inSplit, and outSplit for all_to_allv communications', 'run the unittest test suite for comms_utils parsing and bandwidth calculation functions', 'test the parsesize function to parse size strings like 2GB or 3MB into bytes', 'test the parseRankList function to parse comma-separated or range rank strings into lists', 'test the getAlgBW function to calculate algorithmic bandwidth from elapsed time and data size', 'test the getSizes function to generate size lists using step factor or step bytes', 'test that the HCCL torchcomms backend is registered as PyTorchMtiaTorchcommsBackend in customized_backend', 'test that mtia is listed in the supportedDevices set after importing the backend module', 'test the get_device method returns the correct mtia device based on local rank and device count', 'test get_new_stream, sync_stream, get_current_stream, and switch_stream methods for mtia device streams', 'test alloc_random and alloc_empty methods for tensor allocation on CPU with various dtypes', 'create a commsArgs object with custom key-value pairs using the createCommsArgs utility function', 'test the testArgs class to verify default values for trace_file, dry_run, and output_path attributes', 'review the commsParamsTest class to understand default network stack, backend, and quantization parameters', 'test the bootstrap_info_test class to verify default global_rank, world_size, and master_ip values', 'refactor the createCommsArgs function to add validation for unsupported keyword arguments']
```

Usage

```
{'test_prepComms_tensor_generation': 'test the prepComms method to verify correct tensor generation for collective communications like wait, barrier, recv, and all_gather', 'test_replayTrace_warmup_and_replay': 'test the replayTrace method to ensure warmup and replay runs without failure on a trace of commsArgs entries', 'test_runComms_latency': 'test the runComms method to verify it returns latency and global_latency for blocking and non-blocking collective operations', 'test_initTraceStat_dry_run': 'test the initTraceStat method to verify trace stats and comm blocks are initialized correctly on the first dry run', 'test_rebalanceSplit_policy': 'test the rebalanceSplit method to verify equal policy rebalances inMsgSize, outMsgSize, inSplit, and outSplit for all_to_allv communications'}
```

## File: facebookresearch_param/train/comms/pt/tests/comms_utils_tests.py

Prompts

```
['test the prepComms method to verify correct tensor generation for collective communications like wait, barrier, recv, and all_gather', 'test the replayTrace method to ensure warmup and replay runs without failure on a trace of commsArgs entries', 'test the runComms method to verify it returns latency and global_latency for blocking and non-blocking collective operations', 'test the initTraceStat method to verify trace stats and comm blocks are initialized correctly on the first dry run', 'test the rebalanceSplit method to verify equal policy rebalances inMsgSize, outMsgSize, inSplit, and outSplit for all_to_allv communications', 'run the unittest test suite for comms_utils parsing and bandwidth calculation functions', 'test the parsesize function to parse size strings like 2GB or 3MB into bytes', 'test the parseRankList function to parse comma-separated or range rank strings into lists', 'test the getAlgBW function to calculate algorithmic bandwidth from elapsed time and data size', 'test the getSizes function to generate size lists using step factor or step bytes', 'test that the HCCL torchcomms backend is registered as PyTorchMtiaTorchcommsBackend in customized_backend', 'test that mtia is listed in the supportedDevices set after importing the backend module', 'test the get_device method returns the correct mtia device based on local rank and device count', 'test get_new_stream, sync_stream, get_current_stream, and switch_stream methods for mtia device streams', 'test alloc_random and alloc_empty methods for tensor allocation on CPU with various dtypes', 'create a commsArgs object with custom key-value pairs using the createCommsArgs utility function', 'test the testArgs class to verify default values for trace_file, dry_run, and output_path attributes', 'review the commsParamsTest class to understand default network stack, backend, and quantization parameters', 'test the bootstrap_info_test class to verify default global_rank, world_size, and master_ip values', 'refactor the createCommsArgs function to add validation for unsupported keyword arguments']
```

Usage

```
{'run_comms_utils_tests': 'run the unittest test suite for comms_utils parsing and bandwidth calculation functions', 'test_parsesize': 'test the parsesize function to parse size strings like 2GB or 3MB into bytes', 'test_parseRankList': 'test the parseRankList function to parse comma-separated or range rank strings into lists', 'test_getAlgBW': 'test the getAlgBW function to calculate algorithmic bandwidth from elapsed time and data size', 'test_getSizes': 'test the getSizes function to generate size lists using step factor or step bytes'}
```

## File: facebookresearch_param/train/comms/pt/tests/test_torchcomms_hccl_backend.py

Prompts

```
['test the prepComms method to verify correct tensor generation for collective communications like wait, barrier, recv, and all_gather', 'test the replayTrace method to ensure warmup and replay runs without failure on a trace of commsArgs entries', 'test the runComms method to verify it returns latency and global_latency for blocking and non-blocking collective operations', 'test the initTraceStat method to verify trace stats and comm blocks are initialized correctly on the first dry run', 'test the rebalanceSplit method to verify equal policy rebalances inMsgSize, outMsgSize, inSplit, and outSplit for all_to_allv communications', 'run the unittest test suite for comms_utils parsing and bandwidth calculation functions', 'test the parsesize function to parse size strings like 2GB or 3MB into bytes', 'test the parseRankList function to parse comma-separated or range rank strings into lists', 'test the getAlgBW function to calculate algorithmic bandwidth from elapsed time and data size', 'test the getSizes function to generate size lists using step factor or step bytes', 'test that the HCCL torchcomms backend is registered as PyTorchMtiaTorchcommsBackend in customized_backend', 'test that mtia is listed in the supportedDevices set after importing the backend module', 'test the get_device method returns the correct mtia device based on local rank and device count', 'test get_new_stream, sync_stream, get_current_stream, and switch_stream methods for mtia device streams', 'test alloc_random and alloc_empty methods for tensor allocation on CPU with various dtypes', 'create a commsArgs object with custom key-value pairs using the createCommsArgs utility function', 'test the testArgs class to verify default values for trace_file, dry_run, and output_path attributes', 'review the commsParamsTest class to understand default network stack, backend, and quantization parameters', 'test the bootstrap_info_test class to verify default global_rank, world_size, and master_ip values', 'refactor the createCommsArgs function to add validation for unsupported keyword arguments']
```

Usage

```
{'test_hccl_torchcomms_backend_registration': 'test that the HCCL torchcomms backend is registered as PyTorchMtiaTorchcommsBackend in customized_backend', 'test_mtia_supported_devices': 'test that mtia is listed in the supportedDevices set after importing the backend module', 'test_get_device_mtia': 'test the get_device method returns the correct mtia device based on local rank and device count', 'test_stream_operations_mtia': 'test get_new_stream, sync_stream, get_current_stream, and switch_stream methods for mtia device streams', 'test_memory_allocation': 'test alloc_random and alloc_empty methods for tensor allocation on CPU with various dtypes'}
```

## File: facebookresearch_param/train/comms/pt/tests/test_utils.py

Prompts

```
['test the prepComms method to verify correct tensor generation for collective communications like wait, barrier, recv, and all_gather', 'test the replayTrace method to ensure warmup and replay runs without failure on a trace of commsArgs entries', 'test the runComms method to verify it returns latency and global_latency for blocking and non-blocking collective operations', 'test the initTraceStat method to verify trace stats and comm blocks are initialized correctly on the first dry run', 'test the rebalanceSplit method to verify equal policy rebalances inMsgSize, outMsgSize, inSplit, and outSplit for all_to_allv communications', 'run the unittest test suite for comms_utils parsing and bandwidth calculation functions', 'test the parsesize function to parse size strings like 2GB or 3MB into bytes', 'test the parseRankList function to parse comma-separated or range rank strings into lists', 'test the getAlgBW function to calculate algorithmic bandwidth from elapsed time and data size', 'test the getSizes function to generate size lists using step factor or step bytes', 'test that the HCCL torchcomms backend is registered as PyTorchMtiaTorchcommsBackend in customized_backend', 'test that mtia is listed in the supportedDevices set after importing the backend module', 'test the get_device method returns the correct mtia device based on local rank and device count', 'test get_new_stream, sync_stream, get_current_stream, and switch_stream methods for mtia device streams', 'test alloc_random and alloc_empty methods for tensor allocation on CPU with various dtypes', 'create a commsArgs object with custom key-value pairs using the createCommsArgs utility function', 'test the testArgs class to verify default values for trace_file, dry_run, and output_path attributes', 'review the commsParamsTest class to understand default network stack, backend, and quantization parameters', 'test the bootstrap_info_test class to verify default global_rank, world_size, and master_ip values', 'refactor the createCommsArgs function to add validation for unsupported keyword arguments']
```

Usage

```
{'create_comms_args': 'create a commsArgs object with custom key-value pairs using the createCommsArgs utility function', 'test_testargs_class': 'test the testArgs class to verify default values for trace_file, dry_run, and output_path attributes', 'review_commsparamstest_class': 'review the commsParamsTest class to understand default network stack, backend, and quantization parameters', 'test_bootstrap_info_test': 'test the bootstrap_info_test class to verify default global_rank, world_size, and master_ip values', 'refactor_createCommsArgs': 'refactor the createCommsArgs function to add validation for unsupported keyword arguments'}
```

