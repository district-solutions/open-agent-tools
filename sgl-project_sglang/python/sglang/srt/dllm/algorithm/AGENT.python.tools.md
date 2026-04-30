# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/dllm/algorithm/base.py

Prompts

```
['create a DllmAlgorithm instance by passing a DllmConfig with block_size and mask_id', 'build a DllmAlgorithm instance from ServerArgs using the from_server_args factory method', 'test the DllmAlgorithm constructor initializes block_size and mask_id from DllmConfig', 'review the DllmAlgorithm.from_server_args static method that creates an algorithm from ServerArgs', 'summarize the get_algorithm function that returns a DllmAlgorithm instance from a DllmConfig', 'create a JointThreshold algorithm instance with a DllmConfig for mask-based token generation', 'run the JointThreshold algorithm on a model runner and forward batch to generate tokens', 'build mask-to-token conversion by replacing masked positions with highest-confidence tokens above threshold', 'build token-to-token editing by replacing low-confidence tokens with higher-probability alternatives', 'review the JointThreshold run method for iterative post-editing with penalty and convergence control', 'create a LowConfidence DLLM algorithm instance with a configurable confidence threshold', 'run the LowConfidence algorithm to resolve masked tokens using logits confidence scoring', 'build per-block masked token resolution with iterative forward passes until all masks are replaced', 'test the LowConfidence algorithm with a custom confidence threshold to control token transfer decisions', 'summarize the LowConfidence fast path that skips forward passes when no mask tokens are present']
```

Usage

```
{'create_dllm_algorithm_from_config': 'create a DllmAlgorithm instance by passing a DllmConfig with block_size and mask_id', 'build_dllm_algorithm_from_server_args': 'build a DllmAlgorithm instance from ServerArgs using the from_server_args factory method', 'test_dllm_algorithm_init': 'test the DllmAlgorithm constructor initializes block_size and mask_id from DllmConfig', 'review_dllm_algorithm_from_server_args': 'review the DllmAlgorithm.from_server_args static method that creates an algorithm from ServerArgs', 'summarize_get_algorithm': 'summarize the get_algorithm function that returns a DllmAlgorithm instance from a DllmConfig'}
```

## File: sgl-project_sglang/python/sglang/srt/dllm/algorithm/joint_threshold.py

Prompts

```
['create a DllmAlgorithm instance by passing a DllmConfig with block_size and mask_id', 'build a DllmAlgorithm instance from ServerArgs using the from_server_args factory method', 'test the DllmAlgorithm constructor initializes block_size and mask_id from DllmConfig', 'review the DllmAlgorithm.from_server_args static method that creates an algorithm from ServerArgs', 'summarize the get_algorithm function that returns a DllmAlgorithm instance from a DllmConfig', 'create a JointThreshold algorithm instance with a DllmConfig for mask-based token generation', 'run the JointThreshold algorithm on a model runner and forward batch to generate tokens', 'build mask-to-token conversion by replacing masked positions with highest-confidence tokens above threshold', 'build token-to-token editing by replacing low-confidence tokens with higher-probability alternatives', 'review the JointThreshold run method for iterative post-editing with penalty and convergence control', 'create a LowConfidence DLLM algorithm instance with a configurable confidence threshold', 'run the LowConfidence algorithm to resolve masked tokens using logits confidence scoring', 'build per-block masked token resolution with iterative forward passes until all masks are replaced', 'test the LowConfidence algorithm with a custom confidence threshold to control token transfer decisions', 'summarize the LowConfidence fast path that skips forward passes when no mask tokens are present']
```

Usage

```
{'create_JointThreshold': 'create a JointThreshold algorithm instance with a DllmConfig for mask-based token generation', 'run_JointThreshold': 'run the JointThreshold algorithm on a model runner and forward batch to generate tokens', 'build_mask_to_token': 'build mask-to-token conversion by replacing masked positions with highest-confidence tokens above threshold', 'build_token_to_token': 'build token-to-token editing by replacing low-confidence tokens with higher-probability alternatives', 'review_JointThreshold_run': 'review the JointThreshold run method for iterative post-editing with penalty and convergence control'}
```

## File: sgl-project_sglang/python/sglang/srt/dllm/algorithm/low_confidence.py

Prompts

```
['create a DllmAlgorithm instance by passing a DllmConfig with block_size and mask_id', 'build a DllmAlgorithm instance from ServerArgs using the from_server_args factory method', 'test the DllmAlgorithm constructor initializes block_size and mask_id from DllmConfig', 'review the DllmAlgorithm.from_server_args static method that creates an algorithm from ServerArgs', 'summarize the get_algorithm function that returns a DllmAlgorithm instance from a DllmConfig', 'create a JointThreshold algorithm instance with a DllmConfig for mask-based token generation', 'run the JointThreshold algorithm on a model runner and forward batch to generate tokens', 'build mask-to-token conversion by replacing masked positions with highest-confidence tokens above threshold', 'build token-to-token editing by replacing low-confidence tokens with higher-probability alternatives', 'review the JointThreshold run method for iterative post-editing with penalty and convergence control', 'create a LowConfidence DLLM algorithm instance with a configurable confidence threshold', 'run the LowConfidence algorithm to resolve masked tokens using logits confidence scoring', 'build per-block masked token resolution with iterative forward passes until all masks are replaced', 'test the LowConfidence algorithm with a custom confidence threshold to control token transfer decisions', 'summarize the LowConfidence fast path that skips forward passes when no mask tokens are present']
```

Usage

```
{'create_low_confidence_algorithm': 'create a LowConfidence DLLM algorithm instance with a configurable confidence threshold', 'run_low_confidence_forward': 'run the LowConfidence algorithm to resolve masked tokens using logits confidence scoring', 'build_low_confidence_block_processing': 'build per-block masked token resolution with iterative forward passes until all masks are replaced', 'test_low_confidence_threshold': 'test the LowConfidence algorithm with a custom confidence threshold to control token transfer decisions', 'summarize_low_confidence_fast_path': 'summarize the LowConfidence fast path that skips forward passes when no mask tokens are present'}
```

