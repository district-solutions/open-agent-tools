# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/modules/speech/wav2vec/asr.py

Prompts

```
['run Wav2vecASR module to transcribe audio files from a manifest into text using a Wav2Vec encoder model', 'load a Wav2Vec encoder model and ASR task from a checkpoint file for speech recognition inference', 'perform batch inference on audio waveforms to generate transcribed sentences using a Wav2Vec model and decoder', 'extract transcribed sentences from decoded hypotheses by joining words or post-processing tokens', 'create an ASRConfig dataclass to configure Wav2Vec ASR with shards, encoder model path, and runtime requirements', 'load a wav2vec speech encoder model from a checkpoint directory and checkpoint file using fairseq', 'load a speech encoder with fallback methods including Wav2VecLaser and patched config loading', 'create a WavesDataset from a list of audio waveforms and their sizes for batch processing', 'create a WavesDataset with fbank features enabled to extract audio features from waveform data', 'review the WavesDataset getitem method that returns audio features with optional fbank extraction']
```

Usage

```
{'run_wav2vec_asr': 'run Wav2vecASR module to transcribe audio files from a manifest into text using a Wav2Vec encoder model', 'load_model_and_task': 'load a Wav2Vec encoder model and ASR task from a checkpoint file for speech recognition inference', 'infer_batch_audio': 'perform batch inference on audio waveforms to generate transcribed sentences using a Wav2Vec model and decoder', 'generate_sentences_from_hypos': 'extract transcribed sentences from decoded hypotheses by joining words or post-processing tokens', 'create_asr_config': 'create an ASRConfig dataclass to configure Wav2Vec ASR with shards, encoder model path, and runtime requirements'}
```

## File: facebookresearch_stopes/stopes/modules/speech/wav2vec/utils.py

Prompts

```
['run Wav2vecASR module to transcribe audio files from a manifest into text using a Wav2Vec encoder model', 'load a Wav2Vec encoder model and ASR task from a checkpoint file for speech recognition inference', 'perform batch inference on audio waveforms to generate transcribed sentences using a Wav2Vec model and decoder', 'extract transcribed sentences from decoded hypotheses by joining words or post-processing tokens', 'create an ASRConfig dataclass to configure Wav2Vec ASR with shards, encoder model path, and runtime requirements', 'load a wav2vec speech encoder model from a checkpoint directory and checkpoint file using fairseq', 'load a speech encoder with fallback methods including Wav2VecLaser and patched config loading', 'create a WavesDataset from a list of audio waveforms and their sizes for batch processing', 'create a WavesDataset with fbank features enabled to extract audio features from waveform data', 'review the WavesDataset getitem method that returns audio features with optional fbank extraction']
```

Usage

```
{'load_speech_encoder_from_checkpoint': 'load a wav2vec speech encoder model from a checkpoint directory and checkpoint file using fairseq', 'load_speech_encoder_with_fallback': 'load a speech encoder with fallback methods including Wav2VecLaser and patched config loading', 'create_waves_dataset_from_waveforms': 'create a WavesDataset from a list of audio waveforms and their sizes for batch processing', 'create_waves_dataset_with_fbank': 'create a WavesDataset with fbank features enabled to extract audio features from waveform data', 'review_waves_dataset_getitem': 'review the WavesDataset getitem method that returns audio features with optional fbank extraction'}
```

