# Agent Python Tools

- repo: facebookresearch/textlesslib
- repo_uri: https://github.com/facebookresearch/textlesslib

## File: facebookresearch_textlesslib/tests/test_checkpoint_manager.py

Prompts

```
['test the CHECKPOINT_MANAGER get_by_name method to retrieve a checkpoint by its registered name', 'test the CHECKPOINT_MANAGER set_root method to change the checkpoint storage root directory', 'test the CHECKPOINT_MANAGER storage attribute to access checkpoint metadata by name', 'test the CHECKPOINT_MANAGER get_by_name with download_if_needed to fetch missing checkpoints automatically', 'test the CHECKPOINT_MANAGER get_by_name raises KeyError for an unregistered checkpoint name', 'test dispatching a dense model like hubert-base-ls960 using dispatch_dense_model', 'test dispatching a kmeans quantizer with a given vocab size using dispatch_quantizer', 'test encoding a waveform through SpeechEncoder.by_name with a dense model and quantizer', 'test looking up a TacotronVocoder by name with a dense model and quantizer config', 'test the full model dispatch pipeline including dense model, quantizer, and vocoder lookup', 'test the QuantizedLibriSpeech dataset by creating a SpeechEncoder and verifying item invariants', 'run SpeechEncoder.by_name to create a quantized encoder with hubert-base-ls960 and kmeans quantizer', 'create a QuantizedLibriSpeech dataset using a SpeechEncoder and download the dev-clean split', 'test that dataset item units, durations, and f0 tensors share the same sequence length', 'review the SpeechEncoder configuration with hubert-base-ls960, kmeans quantizer, and vocab size 100']
```

Usage

```
{'test_CHECKPOINT_MANAGER_get_by_name': 'test the CHECKPOINT_MANAGER get_by_name method to retrieve a checkpoint by its registered name', 'test_CHECKPOINT_MANAGER_set_root': 'test the CHECKPOINT_MANAGER set_root method to change the checkpoint storage root directory', 'test_CHECKPOINT_MANAGER_storage_access': 'test the CHECKPOINT_MANAGER storage attribute to access checkpoint metadata by name', 'test_CHECKPOINT_MANAGER_download': 'test the CHECKPOINT_MANAGER get_by_name with download_if_needed to fetch missing checkpoints automatically', 'test_CHECKPOINT_MANAGER_key_error': 'test the CHECKPOINT_MANAGER get_by_name raises KeyError for an unregistered checkpoint name'}
```

## File: facebookresearch_textlesslib/tests/test_model_handling.py

Prompts

```
['test the CHECKPOINT_MANAGER get_by_name method to retrieve a checkpoint by its registered name', 'test the CHECKPOINT_MANAGER set_root method to change the checkpoint storage root directory', 'test the CHECKPOINT_MANAGER storage attribute to access checkpoint metadata by name', 'test the CHECKPOINT_MANAGER get_by_name with download_if_needed to fetch missing checkpoints automatically', 'test the CHECKPOINT_MANAGER get_by_name raises KeyError for an unregistered checkpoint name', 'test dispatching a dense model like hubert-base-ls960 using dispatch_dense_model', 'test dispatching a kmeans quantizer with a given vocab size using dispatch_quantizer', 'test encoding a waveform through SpeechEncoder.by_name with a dense model and quantizer', 'test looking up a TacotronVocoder by name with a dense model and quantizer config', 'test the full model dispatch pipeline including dense model, quantizer, and vocoder lookup', 'test the QuantizedLibriSpeech dataset by creating a SpeechEncoder and verifying item invariants', 'run SpeechEncoder.by_name to create a quantized encoder with hubert-base-ls960 and kmeans quantizer', 'create a QuantizedLibriSpeech dataset using a SpeechEncoder and download the dev-clean split', 'test that dataset item units, durations, and f0 tensors share the same sequence length', 'review the SpeechEncoder configuration with hubert-base-ls960, kmeans quantizer, and vocab size 100']
```

Usage

```
{'test_dispatch_dense_model': 'test dispatching a dense model like hubert-base-ls960 using dispatch_dense_model', 'test_dispatch_quantizer': 'test dispatching a kmeans quantizer with a given vocab size using dispatch_quantizer', 'test_speech_encoder': 'test encoding a waveform through SpeechEncoder.by_name with a dense model and quantizer', 'test_vocoder_lookup': 'test looking up a TacotronVocoder by name with a dense model and quantizer config', 'test_model_dispatch_full': 'test the full model dispatch pipeline including dense model, quantizer, and vocoder lookup'}
```

## File: facebookresearch_textlesslib/tests/test_quantized_dataset.py

Prompts

```
['test the CHECKPOINT_MANAGER get_by_name method to retrieve a checkpoint by its registered name', 'test the CHECKPOINT_MANAGER set_root method to change the checkpoint storage root directory', 'test the CHECKPOINT_MANAGER storage attribute to access checkpoint metadata by name', 'test the CHECKPOINT_MANAGER get_by_name with download_if_needed to fetch missing checkpoints automatically', 'test the CHECKPOINT_MANAGER get_by_name raises KeyError for an unregistered checkpoint name', 'test dispatching a dense model like hubert-base-ls960 using dispatch_dense_model', 'test dispatching a kmeans quantizer with a given vocab size using dispatch_quantizer', 'test encoding a waveform through SpeechEncoder.by_name with a dense model and quantizer', 'test looking up a TacotronVocoder by name with a dense model and quantizer config', 'test the full model dispatch pipeline including dense model, quantizer, and vocoder lookup', 'test the QuantizedLibriSpeech dataset by creating a SpeechEncoder and verifying item invariants', 'run SpeechEncoder.by_name to create a quantized encoder with hubert-base-ls960 and kmeans quantizer', 'create a QuantizedLibriSpeech dataset using a SpeechEncoder and download the dev-clean split', 'test that dataset item units, durations, and f0 tensors share the same sequence length', 'review the SpeechEncoder configuration with hubert-base-ls960, kmeans quantizer, and vocab size 100']
```

Usage

```
{'test_quantized_librispeech': 'test the QuantizedLibriSpeech dataset by creating a SpeechEncoder and verifying item invariants', 'run_SpeechEncoder_by_name': 'run SpeechEncoder.by_name to create a quantized encoder with hubert-base-ls960 and kmeans quantizer', 'create_QuantizedLibriSpeech_dataset': 'create a QuantizedLibriSpeech dataset using a SpeechEncoder and download the dev-clean split', 'test_dataset_item_invariants': 'test that dataset item units, durations, and f0 tensors share the same sequence length', 'review_SpeechEncoder_config': 'review the SpeechEncoder configuration with hubert-base-ls960, kmeans quantizer, and vocab size 100'}
```

