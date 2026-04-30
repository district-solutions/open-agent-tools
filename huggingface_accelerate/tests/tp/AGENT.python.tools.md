# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/tests/tp/fsdp2_tp_preparation.py

Prompts

```
['run the FSDP2 with tensor parallelism preparation script for Qwen3-0.6B model', 'build a simple wikitext dataloader with tokenization and padding for sequence length 64', 'create a PyTorch module wrapper that wraps an lm_head layer for FSDP compatibility', 'review the FSDP2 plugin configuration with transformer-based auto wrap policy and sharded state dict', 'test the accelerator prepare function with model, optimizer, and dataloader under FSDP2 and TP', 'run the TPIntegrationTest class to test tensor parallelism with TinyLlama model', 'test tensor parallelism by launching test_performance.py with tp_size 2 and auto tp_plan', 'test tensor parallelism combined with FSDP using fsdp2_tp_preparation.py and its config', 'review the TPIntegrationTest class for tensor parallelism integration test setup and decorators', 'summarize the test_working_of_tp method that runs TP tests with get_launch_command and patch_environment']
```

Usage

```
{'run_fsdp2_tp_preparation': 'run the FSDP2 with tensor parallelism preparation script for Qwen3-0.6B model', 'build_simple_dataloader': 'build a simple wikitext dataloader with tokenization and padding for sequence length 64', 'create_LmHeadWrapper': 'create a PyTorch module wrapper that wraps an lm_head layer for FSDP compatibility', 'review_FullyShardedDataParallelPlugin': 'review the FSDP2 plugin configuration with transformer-based auto wrap policy and sharded state dict', 'test_accelerator_prepare': 'test the accelerator prepare function with model, optimizer, and dataloader under FSDP2 and TP'}
```

## File: huggingface_accelerate/tests/tp/test_tp.py

Prompts

```
['run the FSDP2 with tensor parallelism preparation script for Qwen3-0.6B model', 'build a simple wikitext dataloader with tokenization and padding for sequence length 64', 'create a PyTorch module wrapper that wraps an lm_head layer for FSDP compatibility', 'review the FSDP2 plugin configuration with transformer-based auto wrap policy and sharded state dict', 'test the accelerator prepare function with model, optimizer, and dataloader under FSDP2 and TP', 'run the TPIntegrationTest class to test tensor parallelism with TinyLlama model', 'test tensor parallelism by launching test_performance.py with tp_size 2 and auto tp_plan', 'test tensor parallelism combined with FSDP using fsdp2_tp_preparation.py and its config', 'review the TPIntegrationTest class for tensor parallelism integration test setup and decorators', 'summarize the test_working_of_tp method that runs TP tests with get_launch_command and patch_environment']
```

Usage

```
{'run_TPIntegrationTest': 'run the TPIntegrationTest class to test tensor parallelism with TinyLlama model', 'test_working_of_tp': 'test tensor parallelism by launching test_performance.py with tp_size 2 and auto tp_plan', 'test_working_of_tp_and_fsdp': 'test tensor parallelism combined with FSDP using fsdp2_tp_preparation.py and its config', 'review_TPIntegrationTest': 'review the TPIntegrationTest class for tensor parallelism integration test setup and decorators', 'summarize_test_working_of_tp': 'summarize the test_working_of_tp method that runs TP tests with get_launch_command and patch_environment'}
```

