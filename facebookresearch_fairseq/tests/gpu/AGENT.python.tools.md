# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/tests/gpu/test_binaries_gpu.py

Prompts

```
['test resuming multilingual language model training from a saved checkpoint on multiple GPUs', 'test resuming translation model training from a checkpoint using fully sharded data parallel backend', 'test training a translation model with fp16 precision across multiple GPUs', 'test scalar and iterative PQ quantization on a transformer language model', 'test adafactor optimizer compatibility with fp16 flat gradients on GPU', 'test the EMA GPU module by running test_ema to verify exponential moving average updates on CUDA', 'test the EMA GPU module with fp32 precision to verify EMA updates are closer to fp32 than fp16', 'test the EMA GPU module with fp16 precision to verify EMA updates are closer to fp16 than fp32', 'review the EMAConfig dataclass to understand ema_decay, ema_start_update, ema_fp32, and ema_update_freq settings', 'review the DummyModule torch.nn.Module used as a test fixture with two linear layers for EMA testing']
```

Usage

```
{'test_resume_multilingual_training': 'test resuming multilingual language model training from a saved checkpoint on multiple GPUs', 'test_resume_training_fsdp': 'test resuming translation model training from a checkpoint using fully sharded data parallel backend', 'test_fp16_multigpu': 'test training a translation model with fp16 precision across multiple GPUs', 'test_quantization': 'test scalar and iterative PQ quantization on a transformer language model', 'test_flat_grads': 'test adafactor optimizer compatibility with fp16 flat gradients on GPU'}
```

## File: facebookresearch_fairseq/tests/gpu/test_ema_gpu.py

Prompts

```
['test resuming multilingual language model training from a saved checkpoint on multiple GPUs', 'test resuming translation model training from a checkpoint using fully sharded data parallel backend', 'test training a translation model with fp16 precision across multiple GPUs', 'test scalar and iterative PQ quantization on a transformer language model', 'test adafactor optimizer compatibility with fp16 flat gradients on GPU', 'test the EMA GPU module by running test_ema to verify exponential moving average updates on CUDA', 'test the EMA GPU module with fp32 precision to verify EMA updates are closer to fp32 than fp16', 'test the EMA GPU module with fp16 precision to verify EMA updates are closer to fp16 than fp32', 'review the EMAConfig dataclass to understand ema_decay, ema_start_update, ema_fp32, and ema_update_freq settings', 'review the DummyModule torch.nn.Module used as a test fixture with two linear layers for EMA testing']
```

Usage

```
{'test_ema_gpu': 'test the EMA GPU module by running test_ema to verify exponential moving average updates on CUDA', 'test_ema_fp32': 'test the EMA GPU module with fp32 precision to verify EMA updates are closer to fp32 than fp16', 'test_ema_fp16': 'test the EMA GPU module with fp16 precision to verify EMA updates are closer to fp16 than fp32', 'review_EMAConfig': 'review the EMAConfig dataclass to understand ema_decay, ema_start_update, ema_fp32, and ema_update_freq settings', 'review_DummyModule': 'review the DummyModule torch.nn.Module used as a test fixture with two linear layers for EMA testing'}
```

