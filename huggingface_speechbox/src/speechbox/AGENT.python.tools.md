# Agent Python Tools

- repo: huggingface/speechbox
- repo_uri: https://github.com/huggingface/speechbox

## File: huggingface_speechbox/src/speechbox/diarize.py

Prompts

```
['build a speaker diarization pipeline using ASRDiarizationPipeline.from_pretrained with whisper and pyannote models', 'run the ASRDiarizationPipeline on an audio file to get speaker-labeled transcriptions with timestamps', 'transcribe audio and group consecutive utterances by speaker using the group_by_speaker parameter', 'preprocess audio inputs from file paths bytes or numpy arrays for ASR and diarization', 'configure ASR and diarization parameters using asr_ and diarization_ prefixed keyword arguments', 'restore punctuation and capitalization in a speech transcript using a Whisper model and audio input', 'load a PunctuationRestorer from a pretrained Whisper model checkpoint path', 'set the language for the PunctuationRestorer model using forced decoder IDs', 'get the list of punctuation token IDs from the Whisper tokenizer', 'convert a list of words into their corresponding Whisper tokenizer token IDs']
```

Usage

```
{'build_asr_diarization_pipeline': 'build a speaker diarization pipeline using ASRDiarizationPipeline.from_pretrained with whisper and pyannote models', 'run_speaker_transcription': 'run the ASRDiarizationPipeline on an audio file to get speaker-labeled transcriptions with timestamps', 'transcribe_audio_with_speakers': 'transcribe audio and group consecutive utterances by speaker using the group_by_speaker parameter', 'preprocess_audio_input': 'preprocess audio inputs from file paths bytes or numpy arrays for ASR and diarization', 'configure_asr_diarization_kwargs': 'configure ASR and diarization parameters using asr_ and diarization_ prefixed keyword arguments'}
```

## File: huggingface_speechbox/src/speechbox/restore.py

Prompts

```
['build a speaker diarization pipeline using ASRDiarizationPipeline.from_pretrained with whisper and pyannote models', 'run the ASRDiarizationPipeline on an audio file to get speaker-labeled transcriptions with timestamps', 'transcribe audio and group consecutive utterances by speaker using the group_by_speaker parameter', 'preprocess audio inputs from file paths bytes or numpy arrays for ASR and diarization', 'configure ASR and diarization parameters using asr_ and diarization_ prefixed keyword arguments', 'restore punctuation and capitalization in a speech transcript using a Whisper model and audio input', 'load a PunctuationRestorer from a pretrained Whisper model checkpoint path', 'set the language for the PunctuationRestorer model using forced decoder IDs', 'get the list of punctuation token IDs from the Whisper tokenizer', 'convert a list of words into their corresponding Whisper tokenizer token IDs']
```

Usage

```
{'restore_punctuation_audio_transcript': 'restore punctuation and capitalization in a speech transcript using a Whisper model and audio input', 'load_punctuation_restorer_pretrained': 'load a PunctuationRestorer from a pretrained Whisper model checkpoint path', 'set_language_punctuation_restorer': 'set the language for the PunctuationRestorer model using forced decoder IDs', 'get_punctuation_tokens': 'get the list of punctuation token IDs from the Whisper tokenizer', 'convert_words_to_tokens': 'convert a list of words into their corresponding Whisper tokenizer token IDs'}
```

