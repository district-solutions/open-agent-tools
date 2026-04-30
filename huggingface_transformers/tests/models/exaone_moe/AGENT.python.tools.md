# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/exaone_moe/test_modeling_exaone_moe.py

Prompts

```
['test the ExaoneMoeIntegrationTest.test_model_logits method to verify model output logits match expected values on CUDA and XPU devices', 'test the ExaoneMoeIntegrationTest.test_model_generation_sdpa method to verify autoregressive text generation with SDPA attention implementation', 'test the ExaoneMoeIntegrationTest.test_model_generation_beyond_sliding_window_flash method to verify generation beyond sliding window with flash attention 2', 'test the ExaoneMoeModelTest.test_tp_generation_quantized method for tensor parallelism with quantized generation (currently skipped)', 'build an ExaoneMoeModelTester subclass that provides a CausalLMModelTester with ExaoneMoeModel as the base model class']
```

Usage

```
{'test_model_logits': 'test the ExaoneMoeIntegrationTest.test_model_logits method to verify model output logits match expected values on CUDA and XPU devices', 'test_model_generation_sdpa': 'test the ExaoneMoeIntegrationTest.test_model_generation_sdpa method to verify autoregressive text generation with SDPA attention implementation', 'test_model_generation_beyond_sliding_window_flash': 'test the ExaoneMoeIntegrationTest.test_model_generation_beyond_sliding_window_flash method to verify generation beyond sliding window with flash attention 2', 'test_tp_generation_quantized': 'test the ExaoneMoeModelTest.test_tp_generation_quantized method for tensor parallelism with quantized generation (currently skipped)', 'build_model_tester': 'build an ExaoneMoeModelTester subclass that provides a CausalLMModelTester with ExaoneMoeModel as the base model class'}
```

