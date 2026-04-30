# Agent Python Tools

- repo: huggingface/community-events
- repo_uri: https://github.com/huggingface/community-events

## File: huggingface_community-events/whisper-fine-tuning-event/run_eval_whisper_streaming.py

Prompts

```
['run a streaming WER evaluation of a Whisper ASR model on a Hugging Face dataset', 'extract transcript text from a dataset sample by checking multiple column names', 'normalize a batch of text using the Whisper BasicTextNormalizer for consistent scoring', 'filter out empty or ignored text segments from the dataset before evaluation', 'yield audio and normalized reference pairs from a dataset for streaming inference', 'run the Whisper seq2seq speech recognition fine-tuning script with streaming dataset mode', 'load a HuggingFace dataset in streaming mode with optional split interleaving', 'configure model arguments including model path, tokenizer, and feature extractor settings', 'configure data training arguments including dataset name, audio column, and duration filters', 'create a dynamic padding data collator for speech seq2seq model inputs and labels']
```

Usage

```
{'run_whisper_streaming_eval': 'run a streaming WER evaluation of a Whisper ASR model on a Hugging Face dataset', 'get_text_from_sample': 'extract transcript text from a dataset sample by checking multiple column names', 'normalise_batch_text': 'normalize a batch of text using the Whisper BasicTextNormalizer for consistent scoring', 'filter_target_text': 'filter out empty or ignored text segments from the dataset before evaluation', 'yield_audio_reference_pairs': 'yield audio and normalized reference pairs from a dataset for streaming inference'}
```

## File: huggingface_community-events/whisper-fine-tuning-event/run_speech_recognition_seq2seq_streaming.py

Prompts

```
['run a streaming WER evaluation of a Whisper ASR model on a Hugging Face dataset', 'extract transcript text from a dataset sample by checking multiple column names', 'normalize a batch of text using the Whisper BasicTextNormalizer for consistent scoring', 'filter out empty or ignored text segments from the dataset before evaluation', 'yield audio and normalized reference pairs from a dataset for streaming inference', 'run the Whisper seq2seq speech recognition fine-tuning script with streaming dataset mode', 'load a HuggingFace dataset in streaming mode with optional split interleaving', 'configure model arguments including model path, tokenizer, and feature extractor settings', 'configure data training arguments including dataset name, audio column, and duration filters', 'create a dynamic padding data collator for speech seq2seq model inputs and labels']
```

Usage

```
{'run_whisper_finetuning': 'run the Whisper seq2seq speech recognition fine-tuning script with streaming dataset mode', 'load_streaming_dataset': 'load a HuggingFace dataset in streaming mode with optional split interleaving', 'configure_model_arguments': 'configure model arguments including model path, tokenizer, and feature extractor settings', 'configure_data_training_arguments': 'configure data training arguments including dataset name, audio column, and duration filters', 'create_data_collator': 'create a dynamic padding data collator for speech seq2seq model inputs and labels'}
```

