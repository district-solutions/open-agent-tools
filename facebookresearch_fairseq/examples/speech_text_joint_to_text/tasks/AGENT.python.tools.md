# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/tasks/pair_denoising.py

Prompts

```
['build a PairedDenoisingTask for multilingual speech-text joint denoising with configurable masking and language pairs', 'create a whole word mask tensor from a fairseq dictionary using gen_whole_word_mask', 'configure denoising task arguments including mask fraction, insert ratio, poisson lambda, and mask length strategy', 'load a language pair denoising dataset with optional masking for a given split and language pair', 'resample multilingual datasets with smoothed sampling probabilities to upsample low-resource language pairs', 'build a fairseq task to jointly denoise speech and text data with configurable modality ratios', 'setup the speech text joint denoising task by loading source and target dictionaries from data paths', 'load a multi-modality dataset combining text, bitext, supervised speech, and unsupervised speech for training', 'configure per-epoch sample ratios for supervised speech, unsupervised speech, text, and bitext modalities', 'create a grouped epoch batch iterator with modality-specific sampling ratios for multi-modal training', 'setup a SpeechTextJointToTextTask by loading source and target dictionaries from a data directory and config YAML', 'load a joint speech and text dataset split with optional parallel text data and source masking', 'load parallel text datasets for multiple language pairs with optional resampling and target language tags', 'configure a GroupedEpochBatchIterator for multi-modality datasets with speech and text sampling ratios', 'run inference on a speech-text joint model with an optional target language BOS token']
```

Usage

```
{'build_paired_denoising_task': 'build a PairedDenoisingTask for multilingual speech-text joint denoising with configurable masking and language pairs', 'create_whole_word_mask': 'create a whole word mask tensor from a fairseq dictionary using gen_whole_word_mask', 'configure_denoising_args': 'configure denoising task arguments including mask fraction, insert ratio, poisson lambda, and mask length strategy', 'load_language_pair_dataset': 'load a language pair denoising dataset with optional masking for a given split and language pair', 'resample_multilingual_datasets': 'resample multilingual datasets with smoothed sampling probabilities to upsample low-resource language pairs'}
```

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/tasks/speech_text_denoise_pretrain.py

Prompts

```
['build a PairedDenoisingTask for multilingual speech-text joint denoising with configurable masking and language pairs', 'create a whole word mask tensor from a fairseq dictionary using gen_whole_word_mask', 'configure denoising task arguments including mask fraction, insert ratio, poisson lambda, and mask length strategy', 'load a language pair denoising dataset with optional masking for a given split and language pair', 'resample multilingual datasets with smoothed sampling probabilities to upsample low-resource language pairs', 'build a fairseq task to jointly denoise speech and text data with configurable modality ratios', 'setup the speech text joint denoising task by loading source and target dictionaries from data paths', 'load a multi-modality dataset combining text, bitext, supervised speech, and unsupervised speech for training', 'configure per-epoch sample ratios for supervised speech, unsupervised speech, text, and bitext modalities', 'create a grouped epoch batch iterator with modality-specific sampling ratios for multi-modal training', 'setup a SpeechTextJointToTextTask by loading source and target dictionaries from a data directory and config YAML', 'load a joint speech and text dataset split with optional parallel text data and source masking', 'load parallel text datasets for multiple language pairs with optional resampling and target language tags', 'configure a GroupedEpochBatchIterator for multi-modality datasets with speech and text sampling ratios', 'run inference on a speech-text joint model with an optional target language BOS token']
```

Usage

```
{'build_joint_denoising_task': 'build a fairseq task to jointly denoise speech and text data with configurable modality ratios', 'setup_task_load_dictionaries': 'setup the speech text joint denoising task by loading source and target dictionaries from data paths', 'load_multimodal_dataset': 'load a multi-modality dataset combining text, bitext, supervised speech, and unsupervised speech for training', 'configure_sample_ratios': 'configure per-epoch sample ratios for supervised speech, unsupervised speech, text, and bitext modalities', 'create_batch_iterator': 'create a grouped epoch batch iterator with modality-specific sampling ratios for multi-modal training'}
```

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/tasks/speech_text_joint.py

Prompts

```
['build a PairedDenoisingTask for multilingual speech-text joint denoising with configurable masking and language pairs', 'create a whole word mask tensor from a fairseq dictionary using gen_whole_word_mask', 'configure denoising task arguments including mask fraction, insert ratio, poisson lambda, and mask length strategy', 'load a language pair denoising dataset with optional masking for a given split and language pair', 'resample multilingual datasets with smoothed sampling probabilities to upsample low-resource language pairs', 'build a fairseq task to jointly denoise speech and text data with configurable modality ratios', 'setup the speech text joint denoising task by loading source and target dictionaries from data paths', 'load a multi-modality dataset combining text, bitext, supervised speech, and unsupervised speech for training', 'configure per-epoch sample ratios for supervised speech, unsupervised speech, text, and bitext modalities', 'create a grouped epoch batch iterator with modality-specific sampling ratios for multi-modal training', 'setup a SpeechTextJointToTextTask by loading source and target dictionaries from a data directory and config YAML', 'load a joint speech and text dataset split with optional parallel text data and source masking', 'load parallel text datasets for multiple language pairs with optional resampling and target language tags', 'configure a GroupedEpochBatchIterator for multi-modality datasets with speech and text sampling ratios', 'run inference on a speech-text joint model with an optional target language BOS token']
```

Usage

```
{'setup_speech_text_joint_task': 'setup a SpeechTextJointToTextTask by loading source and target dictionaries from a data directory and config YAML', 'load_joint_dataset': 'load a joint speech and text dataset split with optional parallel text data and source masking', 'load_langpair_dataset': 'load parallel text datasets for multiple language pairs with optional resampling and target language tags', 'configure_batch_iterator': 'configure a GroupedEpochBatchIterator for multi-modality datasets with speech and text sampling ratios', 'run_inference_step': 'run inference on a speech-text joint model with an optional target language BOS token'}
```

