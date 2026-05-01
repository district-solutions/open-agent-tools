# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/musicflamingo/test_modeling_musicflamingo.py

Prompts

```
['test the MusicFlamingoModelTester to build a MusicFlamingoConfig with text and audio sub-configs', 'test the MusicFlamingoModelTester to prepare synthetic audio features and token IDs for model inputs', 'test the rotary embedding window axis resets correctly for each audio segment in MusicFlamingo', 'test that audio timestamps are correctly reconstructed from input IDs and post-pool lengths', 'test that SDPA attention implementation dispatches correctly to both text and audio submodules', 'test that MusicFlamingoProcessor can be loaded from pretrained checkpoint and saved to a directory', 'test that slow and fast tokenizers produce identical token outputs for a MusicFlamingo prompt', 'test applying a chat template with audio content to a MusicFlamingo processor conversation', 'test that MusicFlamingoProcessor does not expose transcription helper methods', 'test applying chat template with audio inputs using PyTorch tensors for batched MusicFlamingo processing']
```

Usage

```
{'test_MusicFlamingoModelTester_get_config': 'test the MusicFlamingoModelTester to build a MusicFlamingoConfig with text and audio sub-configs', 'test_MusicFlamingoModelTester_prepare_inputs': 'test the MusicFlamingoModelTester to prepare synthetic audio features and token IDs for model inputs', 'test_rotary_window_axis_resets_per_audio': 'test the rotary embedding window axis resets correctly for each audio segment in MusicFlamingo', 'test_build_audio_timestamps_reconstructs_windows': 'test that audio timestamps are correctly reconstructed from input IDs and post-pool lengths', 'test_sdpa_dispatch_composite_models': 'test that SDPA attention implementation dispatches correctly to both text and audio submodules'}
```

## File: huggingface_transformers/tests/models/musicflamingo/test_processing_musicflamingo.py

Prompts

```
['test the MusicFlamingoModelTester to build a MusicFlamingoConfig with text and audio sub-configs', 'test the MusicFlamingoModelTester to prepare synthetic audio features and token IDs for model inputs', 'test the rotary embedding window axis resets correctly for each audio segment in MusicFlamingo', 'test that audio timestamps are correctly reconstructed from input IDs and post-pool lengths', 'test that SDPA attention implementation dispatches correctly to both text and audio submodules', 'test that MusicFlamingoProcessor can be loaded from pretrained checkpoint and saved to a directory', 'test that slow and fast tokenizers produce identical token outputs for a MusicFlamingo prompt', 'test applying a chat template with audio content to a MusicFlamingo processor conversation', 'test that MusicFlamingoProcessor does not expose transcription helper methods', 'test applying chat template with audio inputs using PyTorch tensors for batched MusicFlamingo processing']
```

Usage

```
{'test_MusicFlamingoProcessor_load_save': 'test that MusicFlamingoProcessor can be loaded from pretrained checkpoint and saved to a directory', 'test_tokenizer_integration': 'test that slow and fast tokenizers produce identical token outputs for a MusicFlamingo prompt', 'test_chat_template_audio': 'test applying a chat template with audio content to a MusicFlamingo processor conversation', 'test_transcription_helpers_not_supported': 'test that MusicFlamingoProcessor does not expose transcription helper methods', 'test_apply_chat_template_audio_pytorch': 'test applying chat template with audio inputs using PyTorch tensors for batched MusicFlamingo processing'}
```

