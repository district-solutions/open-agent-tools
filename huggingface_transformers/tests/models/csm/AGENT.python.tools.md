# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/csm/test_modeling_csm.py

Prompts

```
['test the CsmForConditionalGeneration model class with custom input handling for third dimension', 'create a CsmModelTester instance with config, depth_decoder_config, and codec_config for unit testing', 'test the CsmConfig class with common configuration tests from ConfigTester', 'test the CSM 1b model integration generate against expected output tokens', 'test the CSM 1b model integration generate without audio input against expected tokens', 'test CsmProcessor apply_chat_template with text and audio content messages', 'test loading CsmProcessor from pretrained model and verify chat template persistence', 'test that CsmProcessor correctly expands audio input values into audio tokens', 'test CsmProcessor chat template raises error when messages lack required audio content', 'test CsmProcessor batch chat template application with padding and truncation kwargs']
```

Usage

```
{'test_CsmForConditionalGeneration': 'test the CsmForConditionalGeneration model class with custom input handling for third dimension', 'create_CsmModelTester': 'create a CsmModelTester instance with config, depth_decoder_config, and codec_config for unit testing', 'test_CsmConfig': 'test the CsmConfig class with common configuration tests from ConfigTester', 'test_Csm_generate_integration': 'test the CSM 1b model integration generate against expected output tokens', 'test_Csm_generate_no_audio': 'test the CSM 1b model integration generate without audio input against expected tokens'}
```

## File: huggingface_transformers/tests/models/csm/test_processing_csm.py

Prompts

```
['test the CsmForConditionalGeneration model class with custom input handling for third dimension', 'create a CsmModelTester instance with config, depth_decoder_config, and codec_config for unit testing', 'test the CsmConfig class with common configuration tests from ConfigTester', 'test the CSM 1b model integration generate against expected output tokens', 'test the CSM 1b model integration generate without audio input against expected tokens', 'test CsmProcessor apply_chat_template with text and audio content messages', 'test loading CsmProcessor from pretrained model and verify chat template persistence', 'test that CsmProcessor correctly expands audio input values into audio tokens', 'test CsmProcessor chat template raises error when messages lack required audio content', 'test CsmProcessor batch chat template application with padding and truncation kwargs']
```

Usage

```
{'test_CsmProcessor_apply_chat_template': 'test CsmProcessor apply_chat_template with text and audio content messages', 'test_CsmProcessor_from_pretrained': 'test loading CsmProcessor from pretrained model and verify chat template persistence', 'test_CsmProcessor_audio_token_expansion': 'test that CsmProcessor correctly expands audio input values into audio tokens', 'test_CsmProcessor_chat_template_validation': 'test CsmProcessor chat template raises error when messages lack required audio content', 'test_CsmProcessor_batch_processing': 'test CsmProcessor batch chat template application with padding and truncation kwargs'}
```

