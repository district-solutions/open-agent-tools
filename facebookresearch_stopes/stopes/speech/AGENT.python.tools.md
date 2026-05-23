# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/speech/asr.py

Prompts

```
['create a WhisperASR instance and call transcribe on a torch tensor audio waveform to get text', 'use the ASR move_to_device method to transfer a torch tensor to CUDA with optional FP16', 'inherit from the ASR abstract base class and implement the transcribe method for a custom speech model', 'call the validate_model_config method on an ASR instance to check that model configs are valid', 'access the WhisperASR model cached property to lazily load and cache a Whisper model on the device', 'encode an audio waveform torch tensor into discrete units using EncodecSpeechTokenizer', 'decode discrete units back into an audio waveform tensor using EncodecSpeechTokenizer', 'load an EncodecModel from a local checkpoint file or public URL via EncodecSpeechTokenizer', 'configure an EncodecConfig dataclass with checkpoint path, sample rate, and quantizer bins', 'load a public Encodec model from a URL using torch hub and EncodecModel', 'extract wav audio files from a TSV manifest using parallel CPU processing', 'run the extract function via CLI to convert TSV manifest rows into individual wav files', 'extract a limited number of wav files from a TSV manifest by setting num_lines', 'extract wav files from a TSV manifest without skipping the header row', 'review the extract function that reads audio paths from TSV columns and writes PCM_24 wav files', 'load a Kmeans model from an .npy or joblib checkpoint file using Kmeans.load_model', 'encode an audio waveform tensor into discrete speech units using XlsrSpeechTokenizer.encode', 'decode discrete speech units back into a waveform tensor using KMeansHifiGANSpeechTokenizer.decode', 'extract XLSR encoder features from audio using XlsrSpeechTokenizer.extract_features with a specified layer', 'extract HuBERT encoder features from audio using HuBertSpeechTokenizer.extract_features with an output layer', 'build a SpeechTokenizer instance from a Hydra config with _target_ and kwargs', 'sanitize a tensor or module by moving it to CUDA and optionally casting to fp16', 'configure a SpeechTokenizerConfig dataclass with encoder, vocoder, and runtime GPU settings']
```

Usage

```
{'transcribe_audio_with_whisper': 'create a WhisperASR instance and call transcribe on a torch tensor audio waveform to get text', 'move_tensor_to_gpu': 'use the ASR move_to_device method to transfer a torch tensor to CUDA with optional FP16', 'build_custom_asr_model': 'inherit from the ASR abstract base class and implement the transcribe method for a custom speech model', 'validate_asr_model_config': 'call the validate_model_config method on an ASR instance to check that model configs are valid', 'load_whisper_model_cached': 'access the WhisperASR model cached property to lazily load and cache a Whisper model on the device'}
```

## File: facebookresearch_stopes/stopes/speech/encodec.py

Prompts

```
['create a WhisperASR instance and call transcribe on a torch tensor audio waveform to get text', 'use the ASR move_to_device method to transfer a torch tensor to CUDA with optional FP16', 'inherit from the ASR abstract base class and implement the transcribe method for a custom speech model', 'call the validate_model_config method on an ASR instance to check that model configs are valid', 'access the WhisperASR model cached property to lazily load and cache a Whisper model on the device', 'encode an audio waveform torch tensor into discrete units using EncodecSpeechTokenizer', 'decode discrete units back into an audio waveform tensor using EncodecSpeechTokenizer', 'load an EncodecModel from a local checkpoint file or public URL via EncodecSpeechTokenizer', 'configure an EncodecConfig dataclass with checkpoint path, sample rate, and quantizer bins', 'load a public Encodec model from a URL using torch hub and EncodecModel', 'extract wav audio files from a TSV manifest using parallel CPU processing', 'run the extract function via CLI to convert TSV manifest rows into individual wav files', 'extract a limited number of wav files from a TSV manifest by setting num_lines', 'extract wav files from a TSV manifest without skipping the header row', 'review the extract function that reads audio paths from TSV columns and writes PCM_24 wav files', 'load a Kmeans model from an .npy or joblib checkpoint file using Kmeans.load_model', 'encode an audio waveform tensor into discrete speech units using XlsrSpeechTokenizer.encode', 'decode discrete speech units back into a waveform tensor using KMeansHifiGANSpeechTokenizer.decode', 'extract XLSR encoder features from audio using XlsrSpeechTokenizer.extract_features with a specified layer', 'extract HuBERT encoder features from audio using HuBertSpeechTokenizer.extract_features with an output layer', 'build a SpeechTokenizer instance from a Hydra config with _target_ and kwargs', 'sanitize a tensor or module by moving it to CUDA and optionally casting to fp16', 'configure a SpeechTokenizerConfig dataclass with encoder, vocoder, and runtime GPU settings']
```

Usage

```
{'encode_audio_waveform_to_discrete_units': 'encode an audio waveform torch tensor into discrete units using EncodecSpeechTokenizer', 'decode_discrete_units_to_waveform': 'decode discrete units back into an audio waveform tensor using EncodecSpeechTokenizer', 'load_encodec_model_from_checkpoint': 'load an EncodecModel from a local checkpoint file or public URL via EncodecSpeechTokenizer', 'configure_encodec_speech_tokenizer': 'configure an EncodecConfig dataclass with checkpoint path, sample rate, and quantizer bins', 'load_public_encodec_model': 'load a public Encodec model from a URL using torch hub and EncodecModel'}
```

## File: facebookresearch_stopes/stopes/speech/extract_wav.py

Prompts

```
['create a WhisperASR instance and call transcribe on a torch tensor audio waveform to get text', 'use the ASR move_to_device method to transfer a torch tensor to CUDA with optional FP16', 'inherit from the ASR abstract base class and implement the transcribe method for a custom speech model', 'call the validate_model_config method on an ASR instance to check that model configs are valid', 'access the WhisperASR model cached property to lazily load and cache a Whisper model on the device', 'encode an audio waveform torch tensor into discrete units using EncodecSpeechTokenizer', 'decode discrete units back into an audio waveform tensor using EncodecSpeechTokenizer', 'load an EncodecModel from a local checkpoint file or public URL via EncodecSpeechTokenizer', 'configure an EncodecConfig dataclass with checkpoint path, sample rate, and quantizer bins', 'load a public Encodec model from a URL using torch hub and EncodecModel', 'extract wav audio files from a TSV manifest using parallel CPU processing', 'run the extract function via CLI to convert TSV manifest rows into individual wav files', 'extract a limited number of wav files from a TSV manifest by setting num_lines', 'extract wav files from a TSV manifest without skipping the header row', 'review the extract function that reads audio paths from TSV columns and writes PCM_24 wav files', 'load a Kmeans model from an .npy or joblib checkpoint file using Kmeans.load_model', 'encode an audio waveform tensor into discrete speech units using XlsrSpeechTokenizer.encode', 'decode discrete speech units back into a waveform tensor using KMeansHifiGANSpeechTokenizer.decode', 'extract XLSR encoder features from audio using XlsrSpeechTokenizer.extract_features with a specified layer', 'extract HuBERT encoder features from audio using HuBertSpeechTokenizer.extract_features with an output layer', 'build a SpeechTokenizer instance from a Hydra config with _target_ and kwargs', 'sanitize a tensor or module by moving it to CUDA and optionally casting to fp16', 'configure a SpeechTokenizerConfig dataclass with encoder, vocoder, and runtime GPU settings']
```

Usage

```
{'extract_wavs_from_tsv': 'extract wav audio files from a TSV manifest using parallel CPU processing', 'run_extract_cli': 'run the extract function via CLI to convert TSV manifest rows into individual wav files', 'extract_with_line_limit': 'extract a limited number of wav files from a TSV manifest by setting num_lines', 'extract_without_header': 'extract wav files from a TSV manifest without skipping the header row', 'review_extract_function': 'review the extract function that reads audio paths from TSV columns and writes PCM_24 wav files'}
```

## File: facebookresearch_stopes/stopes/speech/kmeans.py

Prompts

```
['create a WhisperASR instance and call transcribe on a torch tensor audio waveform to get text', 'use the ASR move_to_device method to transfer a torch tensor to CUDA with optional FP16', 'inherit from the ASR abstract base class and implement the transcribe method for a custom speech model', 'call the validate_model_config method on an ASR instance to check that model configs are valid', 'access the WhisperASR model cached property to lazily load and cache a Whisper model on the device', 'encode an audio waveform torch tensor into discrete units using EncodecSpeechTokenizer', 'decode discrete units back into an audio waveform tensor using EncodecSpeechTokenizer', 'load an EncodecModel from a local checkpoint file or public URL via EncodecSpeechTokenizer', 'configure an EncodecConfig dataclass with checkpoint path, sample rate, and quantizer bins', 'load a public Encodec model from a URL using torch hub and EncodecModel', 'extract wav audio files from a TSV manifest using parallel CPU processing', 'run the extract function via CLI to convert TSV manifest rows into individual wav files', 'extract a limited number of wav files from a TSV manifest by setting num_lines', 'extract wav files from a TSV manifest without skipping the header row', 'review the extract function that reads audio paths from TSV columns and writes PCM_24 wav files', 'load a Kmeans model from an .npy or joblib checkpoint file using Kmeans.load_model', 'encode an audio waveform tensor into discrete speech units using XlsrSpeechTokenizer.encode', 'decode discrete speech units back into a waveform tensor using KMeansHifiGANSpeechTokenizer.decode', 'extract XLSR encoder features from audio using XlsrSpeechTokenizer.extract_features with a specified layer', 'extract HuBERT encoder features from audio using HuBertSpeechTokenizer.extract_features with an output layer', 'build a SpeechTokenizer instance from a Hydra config with _target_ and kwargs', 'sanitize a tensor or module by moving it to CUDA and optionally casting to fp16', 'configure a SpeechTokenizerConfig dataclass with encoder, vocoder, and runtime GPU settings']
```

Usage

```
{'load_kmeans_model': 'load a Kmeans model from an .npy or joblib checkpoint file using Kmeans.load_model', 'encode_audio_to_units': 'encode an audio waveform tensor into discrete speech units using XlsrSpeechTokenizer.encode', 'decode_units_to_waveform': 'decode discrete speech units back into a waveform tensor using KMeansHifiGANSpeechTokenizer.decode', 'extract_xlsr_features': 'extract XLSR encoder features from audio using XlsrSpeechTokenizer.extract_features with a specified layer', 'extract_hubert_features': 'extract HuBERT encoder features from audio using HuBertSpeechTokenizer.extract_features with an output layer'}
```

## File: facebookresearch_stopes/stopes/speech/tokenizers.py

Prompts

```
['create a WhisperASR instance and call transcribe on a torch tensor audio waveform to get text', 'use the ASR move_to_device method to transfer a torch tensor to CUDA with optional FP16', 'inherit from the ASR abstract base class and implement the transcribe method for a custom speech model', 'call the validate_model_config method on an ASR instance to check that model configs are valid', 'access the WhisperASR model cached property to lazily load and cache a Whisper model on the device', 'encode an audio waveform torch tensor into discrete units using EncodecSpeechTokenizer', 'decode discrete units back into an audio waveform tensor using EncodecSpeechTokenizer', 'load an EncodecModel from a local checkpoint file or public URL via EncodecSpeechTokenizer', 'configure an EncodecConfig dataclass with checkpoint path, sample rate, and quantizer bins', 'load a public Encodec model from a URL using torch hub and EncodecModel', 'extract wav audio files from a TSV manifest using parallel CPU processing', 'run the extract function via CLI to convert TSV manifest rows into individual wav files', 'extract a limited number of wav files from a TSV manifest by setting num_lines', 'extract wav files from a TSV manifest without skipping the header row', 'review the extract function that reads audio paths from TSV columns and writes PCM_24 wav files', 'load a Kmeans model from an .npy or joblib checkpoint file using Kmeans.load_model', 'encode an audio waveform tensor into discrete speech units using XlsrSpeechTokenizer.encode', 'decode discrete speech units back into a waveform tensor using KMeansHifiGANSpeechTokenizer.decode', 'extract XLSR encoder features from audio using XlsrSpeechTokenizer.extract_features with a specified layer', 'extract HuBERT encoder features from audio using HuBertSpeechTokenizer.extract_features with an output layer', 'build a SpeechTokenizer instance from a Hydra config with _target_ and kwargs', 'sanitize a tensor or module by moving it to CUDA and optionally casting to fp16', 'configure a SpeechTokenizerConfig dataclass with encoder, vocoder, and runtime GPU settings']
```

Usage

```
{'build_SpeechTokenizer': 'build a SpeechTokenizer instance from a Hydra config with _target_ and kwargs', 'encode_audio_to_units': 'encode an audio tensor into a stream of discrete units using SpeechTokenizer', 'decode_units_to_waveform': 'decode a stream of discrete units back into a waveform tensor', 'sanitize_tensor_for_cuda': 'sanitize a tensor or module by moving it to CUDA and optionally casting to fp16', 'configure_SpeechTokenizerConfig': 'configure a SpeechTokenizerConfig dataclass with encoder, vocoder, and runtime GPU settings'}
```

