# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_to_speech/asr_bleu/compute_asr_bleu.py

Prompts

```
['run the ASR-BLEU evaluation script to compute BLEU scores between generated audio and text references', 'compose an evaluation data manifest pairing predicted audio files with reference text sentences', 'extract and sort predicted audio WAV files from a directory for ASR evaluation', 'post-process Hokkien ASR hypotheses by merging syllable tokens and removing NULLINIT markers', 'remove tone markers from Hokkien text for tone-less evaluation', 'transcribe an audio file to text using the ASRGenerator with a HuggingFace or Fairseq ASR model', 'load an audio file and apply resampling and layer normalization for ASR model input', 'compute CTC emission logits from an audio waveform tensor using a Fairseq or HuggingFace ASR model', 'decode CTC emission logits into a text transcription string using a torchaudio CTC decoder', 'retrieve an ASR model configuration dict from a JSON config file by language key and version']
```

Usage

```
{'run_asr_bleu_evaluation': 'run the ASR-BLEU evaluation script to compute BLEU scores between generated audio and text references', 'compose_eval_data_manifest': 'compose an evaluation data manifest pairing predicted audio files with reference text sentences', 'extract_audio_for_eval': 'extract and sort predicted audio WAV files from a directory for ASR evaluation', 'merge_tailo_init_final': 'post-process Hokkien ASR hypotheses by merging syllable tokens and removing NULLINIT markers', 'remove_tone': 'remove tone markers from Hokkien text for tone-less evaluation'}
```

## File: facebookresearch_fairseq/examples/speech_to_speech/asr_bleu/utils.py

Prompts

```
['run the ASR-BLEU evaluation script to compute BLEU scores between generated audio and text references', 'compose an evaluation data manifest pairing predicted audio files with reference text sentences', 'extract and sort predicted audio WAV files from a directory for ASR evaluation', 'post-process Hokkien ASR hypotheses by merging syllable tokens and removing NULLINIT markers', 'remove tone markers from Hokkien text for tone-less evaluation', 'transcribe an audio file to text using the ASRGenerator with a HuggingFace or Fairseq ASR model', 'load an audio file and apply resampling and layer normalization for ASR model input', 'compute CTC emission logits from an audio waveform tensor using a Fairseq or HuggingFace ASR model', 'decode CTC emission logits into a text transcription string using a torchaudio CTC decoder', 'retrieve an ASR model configuration dict from a JSON config file by language key and version']
```

Usage

```
{'transcribe_audiofile': 'transcribe an audio file to text using the ASRGenerator with a HuggingFace or Fairseq ASR model', 'load_audiofile': 'load an audio file and apply resampling and layer normalization for ASR model input', 'compute_emissions': 'compute CTC emission logits from an audio waveform tensor using a Fairseq or HuggingFace ASR model', 'decode_emissions': 'decode CTC emission logits into a text transcription string using a torchaudio CTC decoder', 'retrieve_asr_config': 'retrieve an ASR model configuration dict from a JSON config file by language key and version'}
```

