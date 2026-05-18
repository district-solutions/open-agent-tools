# Agent Python Tools

- repo: facebookresearch/omnilingual-asr
- repo_uri: https://github.com/facebookresearch/omnilingual-asr

## File: facebookresearch_omnilingual-asr/tests/unit/test_audio_cropper.py

Prompts

```
['test the AudioCropper class crop_audios_in_batch method to crop long audio tensors to max length', 'test that AudioCropper instances with the same seed produce identical cropped audio results', 'test AudioCropper with crop_to_batch_minimal_size to crop all audios in a batch to the shortest length', 'create an AudioCropper instance with a max audio length, seed, and audio selector key', 'refactor the add_audio_cropping function to integrate AudioCropper into a fairseq2 DataPipelineBuilder', 'test the apply_audio_normalization function to verify it normalizes a waveform to zero mean and unit variance', 'test the convert_to_mono function to verify it averages stereo channels into a mono waveform', 'run the test_audio_normalization test to validate layer norm produces zero mean and unit std output', 'run the test_convert_to_mono test to validate stereo to mono conversion and mono passthrough behavior', 'review the test_audio_utils test suite covering audio normalization and stereo to mono conversion functions', 'test the supported_langs list has at least 1600 language codes in code_script format', 'review the test_supported_langs function that validates language code format and expected languages', 'run pytest on test_lang_ids.py to verify supported_langs contains expected language codes', 'refactor test_supported_langs to add validation for additional language code formats', 'summarize the test_lang_ids module that validates the supported_langs list from omnilingual_asr']
```

Usage

```
{'test_AudioCropper_crop_audios_in_batch': 'test the AudioCropper class crop_audios_in_batch method to crop long audio tensors to max length', 'test_AudioCropper_reproducibility': 'test that AudioCropper instances with the same seed produce identical cropped audio results', 'test_AudioCropper_batch_minimal_size': 'test AudioCropper with crop_to_batch_minimal_size to crop all audios in a batch to the shortest length', 'create_AudioCropper_instance': 'create an AudioCropper instance with a max audio length, seed, and audio selector key', 'refactor_add_audio_cropping': 'refactor the add_audio_cropping function to integrate AudioCropper into a fairseq2 DataPipelineBuilder'}
```

## File: facebookresearch_omnilingual-asr/tests/unit/test_audio_utils.py

Prompts

```
['test the AudioCropper class crop_audios_in_batch method to crop long audio tensors to max length', 'test that AudioCropper instances with the same seed produce identical cropped audio results', 'test AudioCropper with crop_to_batch_minimal_size to crop all audios in a batch to the shortest length', 'create an AudioCropper instance with a max audio length, seed, and audio selector key', 'refactor the add_audio_cropping function to integrate AudioCropper into a fairseq2 DataPipelineBuilder', 'test the apply_audio_normalization function to verify it normalizes a waveform to zero mean and unit variance', 'test the convert_to_mono function to verify it averages stereo channels into a mono waveform', 'run the test_audio_normalization test to validate layer norm produces zero mean and unit std output', 'run the test_convert_to_mono test to validate stereo to mono conversion and mono passthrough behavior', 'review the test_audio_utils test suite covering audio normalization and stereo to mono conversion functions', 'test the supported_langs list has at least 1600 language codes in code_script format', 'review the test_supported_langs function that validates language code format and expected languages', 'run pytest on test_lang_ids.py to verify supported_langs contains expected language codes', 'refactor test_supported_langs to add validation for additional language code formats', 'summarize the test_lang_ids module that validates the supported_langs list from omnilingual_asr']
```

Usage

```
{'test_audio_normalization': 'test the apply_audio_normalization function to verify it normalizes a waveform to zero mean and unit variance', 'test_convert_to_mono': 'test the convert_to_mono function to verify it averages stereo channels into a mono waveform', 'run_audio_normalization_test': 'run the test_audio_normalization test to validate layer norm produces zero mean and unit std output', 'run_convert_to_mono_test': 'run the test_convert_to_mono test to validate stereo to mono conversion and mono passthrough behavior', 'review_audio_utils_tests': 'review the test_audio_utils test suite covering audio normalization and stereo to mono conversion functions'}
```

## File: facebookresearch_omnilingual-asr/tests/unit/test_lang_ids.py

Prompts

```
['test the AudioCropper class crop_audios_in_batch method to crop long audio tensors to max length', 'test that AudioCropper instances with the same seed produce identical cropped audio results', 'test AudioCropper with crop_to_batch_minimal_size to crop all audios in a batch to the shortest length', 'create an AudioCropper instance with a max audio length, seed, and audio selector key', 'refactor the add_audio_cropping function to integrate AudioCropper into a fairseq2 DataPipelineBuilder', 'test the apply_audio_normalization function to verify it normalizes a waveform to zero mean and unit variance', 'test the convert_to_mono function to verify it averages stereo channels into a mono waveform', 'run the test_audio_normalization test to validate layer norm produces zero mean and unit std output', 'run the test_convert_to_mono test to validate stereo to mono conversion and mono passthrough behavior', 'review the test_audio_utils test suite covering audio normalization and stereo to mono conversion functions', 'test the supported_langs list has at least 1600 language codes in code_script format', 'review the test_supported_langs function that validates language code format and expected languages', 'run pytest on test_lang_ids.py to verify supported_langs contains expected language codes', 'refactor test_supported_langs to add validation for additional language code formats', 'summarize the test_lang_ids module that validates the supported_langs list from omnilingual_asr']
```

Usage

```
{'test_supported_langs': 'test the supported_langs list has at least 1600 language codes in code_script format', 'review_test_supported_langs': 'review the test_supported_langs function that validates language code format and expected languages', 'run_test_lang_ids': 'run pytest on test_lang_ids.py to verify supported_langs contains expected language codes', 'refactor_test_supported_langs': 'refactor test_supported_langs to add validation for additional language code formats', 'summarize_test_lang_ids': 'summarize the test_lang_ids module that validates the supported_langs list from omnilingual_asr'}
```

