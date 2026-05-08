# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/nn/fsdp/common.py

Prompts

```
['build a python module that creates an FSDPParameterInitializer to move parameters from meta device to CUDA', 'create a python module implementing the FSDPWrapper protocol for wrapping modules with reshard_after_forward', 'test the FSDPParameterInitializer class by initializing parameters on a target device with skip_init option', 'refactor the FSDPApplier protocol to support custom module wrapping strategies', 'review the load_with_sdp_gang function that returns a context manager for SDP gang process group loading', 'wrap a PyTorch module with FSDP1 using gangs, applier, and mixed precision settings', 'get the local state dictionary from an FSDP1 module with sharded tensor handling', 'load a local state dictionary into an FSDP1 module with sharded tensor support', 'summon full parameters of an FSDP1 module using a context manager for inference', 'configure FSDP1 sharding strategy with hybrid shard or full shard based on gang size', 'convert a PyTorch module to FSDP2 with mixed precision and CPU offload using to_fsdp2', 'extract the local state dictionary from an FSDP2 module using fsdp2_local_state_dict', 'load a local state dictionary into an FSDP2 module using fsdp2_load_local_state_dict', 'disable gradient synchronization for an FSDP2 module using the fsdp2_no_sync context manager', 'temporarily unshard and access full parameters of an FSDP2 module using fsdp2_summon_full_parameters', 'wrap a PyTorch module with FSDP v1 or v2 using to_fsdp with gangs and applier', 'get the local state dict of an FSDP1 or FSDP2 module using fsdp_local_state_dict', 'load a state dict into an FSDP1 or FSDP2 module using fsdp_load_local_state_dict', 'disable gradient synchronization for an FSDP module using fsdp_no_sync context manager', 'unshard and summon full parameters of an FSDP module using fsdp_summon_full_parameters for evaluation']
```

Usage

```
{'build_fsdp_param_initializer': 'build a python module that creates an FSDPParameterInitializer to move parameters from meta device to CUDA', 'create_fsdp_wrapper_protocol': 'create a python module implementing the FSDPWrapper protocol for wrapping modules with reshard_after_forward', 'test_fsdp_parameter_initializer': 'test the FSDPParameterInitializer class by initializing parameters on a target device with skip_init option', 'refactor_fsdp_applier': 'refactor the FSDPApplier protocol to support custom module wrapping strategies', 'review_load_with_sdp_gang': 'review the load_with_sdp_gang function that returns a context manager for SDP gang process group loading'}
```

## File: facebookresearch_fairseq2/src/fairseq2/nn/fsdp/fsdp1.py

Prompts

```
['build a python module that creates an FSDPParameterInitializer to move parameters from meta device to CUDA', 'create a python module implementing the FSDPWrapper protocol for wrapping modules with reshard_after_forward', 'test the FSDPParameterInitializer class by initializing parameters on a target device with skip_init option', 'refactor the FSDPApplier protocol to support custom module wrapping strategies', 'review the load_with_sdp_gang function that returns a context manager for SDP gang process group loading', 'wrap a PyTorch module with FSDP1 using gangs, applier, and mixed precision settings', 'get the local state dictionary from an FSDP1 module with sharded tensor handling', 'load a local state dictionary into an FSDP1 module with sharded tensor support', 'summon full parameters of an FSDP1 module using a context manager for inference', 'configure FSDP1 sharding strategy with hybrid shard or full shard based on gang size', 'convert a PyTorch module to FSDP2 with mixed precision and CPU offload using to_fsdp2', 'extract the local state dictionary from an FSDP2 module using fsdp2_local_state_dict', 'load a local state dictionary into an FSDP2 module using fsdp2_load_local_state_dict', 'disable gradient synchronization for an FSDP2 module using the fsdp2_no_sync context manager', 'temporarily unshard and access full parameters of an FSDP2 module using fsdp2_summon_full_parameters', 'wrap a PyTorch module with FSDP v1 or v2 using to_fsdp with gangs and applier', 'get the local state dict of an FSDP1 or FSDP2 module using fsdp_local_state_dict', 'load a state dict into an FSDP1 or FSDP2 module using fsdp_load_local_state_dict', 'disable gradient synchronization for an FSDP module using fsdp_no_sync context manager', 'unshard and summon full parameters of an FSDP module using fsdp_summon_full_parameters for evaluation']
```

Usage

```
{'wrap_module_with_fsdp1': 'wrap a PyTorch module with FSDP1 using gangs, applier, and mixed precision settings', 'get_fsdp1_local_state_dict': 'get the local state dictionary from an FSDP1 module with sharded tensor handling', 'load_fsdp1_local_state_dict': 'load a local state dictionary into an FSDP1 module with sharded tensor support', 'summon_full_fsdp1_parameters': 'summon full parameters of an FSDP1 module using a context manager for inference', 'configure_fsdp1_sharding_strategy': 'configure FSDP1 sharding strategy with hybrid shard or full shard based on gang size'}
```

## File: facebookresearch_fairseq2/src/fairseq2/nn/fsdp/fsdp2.py

Prompts

```
['build a python module that creates an FSDPParameterInitializer to move parameters from meta device to CUDA', 'create a python module implementing the FSDPWrapper protocol for wrapping modules with reshard_after_forward', 'test the FSDPParameterInitializer class by initializing parameters on a target device with skip_init option', 'refactor the FSDPApplier protocol to support custom module wrapping strategies', 'review the load_with_sdp_gang function that returns a context manager for SDP gang process group loading', 'wrap a PyTorch module with FSDP1 using gangs, applier, and mixed precision settings', 'get the local state dictionary from an FSDP1 module with sharded tensor handling', 'load a local state dictionary into an FSDP1 module with sharded tensor support', 'summon full parameters of an FSDP1 module using a context manager for inference', 'configure FSDP1 sharding strategy with hybrid shard or full shard based on gang size', 'convert a PyTorch module to FSDP2 with mixed precision and CPU offload using to_fsdp2', 'extract the local state dictionary from an FSDP2 module using fsdp2_local_state_dict', 'load a local state dictionary into an FSDP2 module using fsdp2_load_local_state_dict', 'disable gradient synchronization for an FSDP2 module using the fsdp2_no_sync context manager', 'temporarily unshard and access full parameters of an FSDP2 module using fsdp2_summon_full_parameters', 'wrap a PyTorch module with FSDP v1 or v2 using to_fsdp with gangs and applier', 'get the local state dict of an FSDP1 or FSDP2 module using fsdp_local_state_dict', 'load a state dict into an FSDP1 or FSDP2 module using fsdp_load_local_state_dict', 'disable gradient synchronization for an FSDP module using fsdp_no_sync context manager', 'unshard and summon full parameters of an FSDP module using fsdp_summon_full_parameters for evaluation']
```

Usage

```
{'convert_module_to_fsdp2': 'convert a PyTorch module to FSDP2 with mixed precision and CPU offload using to_fsdp2', 'extract_fsdp2_local_state_dict': 'extract the local state dictionary from an FSDP2 module using fsdp2_local_state_dict', 'load_fsdp2_local_state_dict': 'load a local state dictionary into an FSDP2 module using fsdp2_load_local_state_dict', 'disable_fsdp2_gradient_sync': 'disable gradient synchronization for an FSDP2 module using the fsdp2_no_sync context manager', 'summon_full_fsdp2_parameters': 'temporarily unshard and access full parameters of an FSDP2 module using fsdp2_summon_full_parameters'}
```

## File: facebookresearch_fairseq2/src/fairseq2/nn/fsdp/unified.py

Prompts

```
['build a python module that creates an FSDPParameterInitializer to move parameters from meta device to CUDA', 'create a python module implementing the FSDPWrapper protocol for wrapping modules with reshard_after_forward', 'test the FSDPParameterInitializer class by initializing parameters on a target device with skip_init option', 'refactor the FSDPApplier protocol to support custom module wrapping strategies', 'review the load_with_sdp_gang function that returns a context manager for SDP gang process group loading', 'wrap a PyTorch module with FSDP1 using gangs, applier, and mixed precision settings', 'get the local state dictionary from an FSDP1 module with sharded tensor handling', 'load a local state dictionary into an FSDP1 module with sharded tensor support', 'summon full parameters of an FSDP1 module using a context manager for inference', 'configure FSDP1 sharding strategy with hybrid shard or full shard based on gang size', 'convert a PyTorch module to FSDP2 with mixed precision and CPU offload using to_fsdp2', 'extract the local state dictionary from an FSDP2 module using fsdp2_local_state_dict', 'load a local state dictionary into an FSDP2 module using fsdp2_load_local_state_dict', 'disable gradient synchronization for an FSDP2 module using the fsdp2_no_sync context manager', 'temporarily unshard and access full parameters of an FSDP2 module using fsdp2_summon_full_parameters', 'wrap a PyTorch module with FSDP v1 or v2 using to_fsdp with gangs and applier', 'get the local state dict of an FSDP1 or FSDP2 module using fsdp_local_state_dict', 'load a state dict into an FSDP1 or FSDP2 module using fsdp_load_local_state_dict', 'disable gradient synchronization for an FSDP module using fsdp_no_sync context manager', 'unshard and summon full parameters of an FSDP module using fsdp_summon_full_parameters for evaluation']
```

Usage

```
{'wrap_module_with_fsdp': 'wrap a PyTorch module with FSDP v1 or v2 using to_fsdp with gangs and applier', 'get_fsdp_local_state_dict': 'get the local state dict of an FSDP1 or FSDP2 module using fsdp_local_state_dict', 'load_fsdp_local_state_dict': 'load a state dict into an FSDP1 or FSDP2 module using fsdp_load_local_state_dict', 'disable_fsdp_gradient_sync': 'disable gradient synchronization for an FSDP module using fsdp_no_sync context manager', 'summon_full_fsdp_parameters': 'unshard and summon full parameters of an FSDP module using fsdp_summon_full_parameters for evaluation'}
```

