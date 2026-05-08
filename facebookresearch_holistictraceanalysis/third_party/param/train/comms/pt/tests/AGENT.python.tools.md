# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/third_party/param/train/comms/pt/tests/commsTraceReplay_tests.py

Prompts

```
['test prepComms to verify correct tensors are generated for different collective communications like wait, barrier, recv, all_to_allv, and all_gather', 'test replayTrace to run warmup and replay of communication traces without failure using a mock backend', 'test runComms to verify latency and global latency are returned correctly for blocking and non-blocking collective operations', 'test initTraceStat to verify trace statistics and communication blocks are initialized properly on the first dry run', 'test rebalanceSplit to verify message sizes and splits are rebalanced equally across ranks using the equal policy', 'test the parsesize function to parse size strings like 2GB 3MB 5KB into bytes', 'test the parseRankList function to parse comma separated or range formatted rank strings', 'test the getAlgBW function to calculate algorithmic bandwidth from elapsed time and data size', 'test the getSizes function to generate size lists with step factor or step bytes', 'test the fixBeginSize function to adjust begin size for all_to_all and all_reduce collectives', 'create a commsArgs object with custom key-value pairs using the createCommsArgs utility function', 'test the testArgs class to verify default values for trace file, dry run, and output path settings', 'test the commsParamsTest class to verify default network stack, backend, device, and quantization parameters', 'test the bootstrap_info_test class to verify default global rank, world size, master IP, and TPU core settings', 'refactor the createCommsArgs function to add validation for accepted keyword arguments before setting attributes']
```

Usage

```
{'test_prepComms_tensor_generation': 'test prepComms to verify correct tensors are generated for different collective communications like wait, barrier, recv, all_to_allv, and all_gather', 'test_replayTrace_warmup_and_replay': 'test replayTrace to run warmup and replay of communication traces without failure using a mock backend', 'test_runComms_blocking_and_nonblocking': 'test runComms to verify latency and global latency are returned correctly for blocking and non-blocking collective operations', 'test_initTraceStat_dry_run': 'test initTraceStat to verify trace statistics and communication blocks are initialized properly on the first dry run', 'test_rebalanceSplit_equal_policy': 'test rebalanceSplit to verify message sizes and splits are rebalanced equally across ranks using the equal policy'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/train/comms/pt/tests/comms_utils_tests.py

Prompts

```
['test prepComms to verify correct tensors are generated for different collective communications like wait, barrier, recv, all_to_allv, and all_gather', 'test replayTrace to run warmup and replay of communication traces without failure using a mock backend', 'test runComms to verify latency and global latency are returned correctly for blocking and non-blocking collective operations', 'test initTraceStat to verify trace statistics and communication blocks are initialized properly on the first dry run', 'test rebalanceSplit to verify message sizes and splits are rebalanced equally across ranks using the equal policy', 'test the parsesize function to parse size strings like 2GB 3MB 5KB into bytes', 'test the parseRankList function to parse comma separated or range formatted rank strings', 'test the getAlgBW function to calculate algorithmic bandwidth from elapsed time and data size', 'test the getSizes function to generate size lists with step factor or step bytes', 'test the fixBeginSize function to adjust begin size for all_to_all and all_reduce collectives', 'create a commsArgs object with custom key-value pairs using the createCommsArgs utility function', 'test the testArgs class to verify default values for trace file, dry run, and output path settings', 'test the commsParamsTest class to verify default network stack, backend, device, and quantization parameters', 'test the bootstrap_info_test class to verify default global rank, world size, master IP, and TPU core settings', 'refactor the createCommsArgs function to add validation for accepted keyword arguments before setting attributes']
```

Usage

```
{'test_parsesize': 'test the parsesize function to parse size strings like 2GB 3MB 5KB into bytes', 'test_parseRankList': 'test the parseRankList function to parse comma separated or range formatted rank strings', 'test_getAlgBW': 'test the getAlgBW function to calculate algorithmic bandwidth from elapsed time and data size', 'test_getSizes': 'test the getSizes function to generate size lists with step factor or step bytes', 'test_fixBeginSize': 'test the fixBeginSize function to adjust begin size for all_to_all and all_reduce collectives'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/train/comms/pt/tests/test_utils.py

Prompts

```
['test prepComms to verify correct tensors are generated for different collective communications like wait, barrier, recv, all_to_allv, and all_gather', 'test replayTrace to run warmup and replay of communication traces without failure using a mock backend', 'test runComms to verify latency and global latency are returned correctly for blocking and non-blocking collective operations', 'test initTraceStat to verify trace statistics and communication blocks are initialized properly on the first dry run', 'test rebalanceSplit to verify message sizes and splits are rebalanced equally across ranks using the equal policy', 'test the parsesize function to parse size strings like 2GB 3MB 5KB into bytes', 'test the parseRankList function to parse comma separated or range formatted rank strings', 'test the getAlgBW function to calculate algorithmic bandwidth from elapsed time and data size', 'test the getSizes function to generate size lists with step factor or step bytes', 'test the fixBeginSize function to adjust begin size for all_to_all and all_reduce collectives', 'create a commsArgs object with custom key-value pairs using the createCommsArgs utility function', 'test the testArgs class to verify default values for trace file, dry run, and output path settings', 'test the commsParamsTest class to verify default network stack, backend, device, and quantization parameters', 'test the bootstrap_info_test class to verify default global rank, world size, master IP, and TPU core settings', 'refactor the createCommsArgs function to add validation for accepted keyword arguments before setting attributes']
```

Usage

```
{'create_comms_args': 'create a commsArgs object with custom key-value pairs using the createCommsArgs utility function', 'test_testargs_defaults': 'test the testArgs class to verify default values for trace file, dry run, and output path settings', 'test_commsparamstest_defaults': 'test the commsParamsTest class to verify default network stack, backend, device, and quantization parameters', 'test_bootstrap_info_test': 'test the bootstrap_info_test class to verify default global rank, world size, master IP, and TPU core settings', 'refactor_createCommsArgs': 'refactor the createCommsArgs function to add validation for accepted keyword arguments before setting attributes'}
```

