# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/parakeet/test_modeling_parakeet.py

Prompts

```
['test the ParakeetEncoder model with config and input features to verify output shape', 'test the ParakeetForCTC model with encoder config and input features to verify logits shape', 'test the ParakeetCTCConfig and ParakeetEncoderConfig creation and common configuration tests', 'test that ParakeetForCTC composite model supports SDPA attention dispatch with eager fallback', 'test the nvidia/parakeet-ctc-1.1b model integration with expected token IDs and transcriptions']
```

Usage

```
{'test_ParakeetEncoder_model': 'test the ParakeetEncoder model with config and input features to verify output shape', 'test_ParakeetForCTC_model': 'test the ParakeetForCTC model with encoder config and input features to verify logits shape', 'test_ParakeetForCTC_config': 'test the ParakeetCTCConfig and ParakeetEncoderConfig creation and common configuration tests', 'test_sdpa_can_dispatch_composite_models': 'test that ParakeetForCTC composite model supports SDPA attention dispatch with eager fallback', 'test_1b_model_integration': 'test the nvidia/parakeet-ctc-1.1b model integration with expected token IDs and transcriptions'}
```

