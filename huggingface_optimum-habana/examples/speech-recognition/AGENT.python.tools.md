# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/examples/speech-recognition/run_speech_recognition_ctc.py

Prompts

```
['run a CTC-based speech recognition model fine-tuning on Habana Gaudi using GaudiTrainer and a Hugging Face dataset', "create a character-level vocabulary dictionary from a dataset's target text column for CTC tokenization", 'configure a dynamic padding data collator for CTC speech recognition inputs and labels with a processor', 'preprocess an audio dataset by extracting features with a feature extractor and tokenizing target text labels', 'evaluate a fine-tuned CTC speech recognition model using word error rate and character error rate metrics', 'run the seq2seq speech recognition fine-tuning script on Habana Gaudi with a HuggingFace dataset', 'create a DataCollatorSpeechSeq2SeqWithPadding to dynamically pad audio inputs and text labels for batch training', 'configure ModelArguments to set the pretrained model path, tokenizer, and feature extractor for speech recognition', 'configure DataTrainingArguments to set dataset name, audio column, max duration, and preprocessing options', 'prepare an audio dataset by resampling, converting to mono, and extracting features using the feature extractor']
```

Usage

```
{'run_ctc_speech_recognition_training': 'run a CTC-based speech recognition model fine-tuning on Habana Gaudi using GaudiTrainer and a Hugging Face dataset', 'create_vocabulary_from_dataset': "create a character-level vocabulary dictionary from a dataset's target text column for CTC tokenization", 'configure_data_collator_ctc_padding': 'configure a dynamic padding data collator for CTC speech recognition inputs and labels with a processor', 'preprocess_audio_dataset_for_ctc': 'preprocess an audio dataset by extracting features with a feature extractor and tokenizing target text labels', 'evaluate_speech_recognition_model': 'evaluate a fine-tuned CTC speech recognition model using word error rate and character error rate metrics'}
```

## File: huggingface_optimum-habana/examples/speech-recognition/run_speech_recognition_seq2seq.py

Prompts

```
['run a CTC-based speech recognition model fine-tuning on Habana Gaudi using GaudiTrainer and a Hugging Face dataset', "create a character-level vocabulary dictionary from a dataset's target text column for CTC tokenization", 'configure a dynamic padding data collator for CTC speech recognition inputs and labels with a processor', 'preprocess an audio dataset by extracting features with a feature extractor and tokenizing target text labels', 'evaluate a fine-tuned CTC speech recognition model using word error rate and character error rate metrics', 'run the seq2seq speech recognition fine-tuning script on Habana Gaudi with a HuggingFace dataset', 'create a DataCollatorSpeechSeq2SeqWithPadding to dynamically pad audio inputs and text labels for batch training', 'configure ModelArguments to set the pretrained model path, tokenizer, and feature extractor for speech recognition', 'configure DataTrainingArguments to set dataset name, audio column, max duration, and preprocessing options', 'prepare an audio dataset by resampling, converting to mono, and extracting features using the feature extractor']
```

Usage

```
{'run_speech_recognition_finetuning': 'run the seq2seq speech recognition fine-tuning script on Habana Gaudi with a HuggingFace dataset', 'create_data_collator_speech_seq2seq': 'create a DataCollatorSpeechSeq2SeqWithPadding to dynamically pad audio inputs and text labels for batch training', 'configure_model_arguments': 'configure ModelArguments to set the pretrained model path, tokenizer, and feature extractor for speech recognition', 'configure_data_training_arguments': 'configure DataTrainingArguments to set dataset name, audio column, max duration, and preprocessing options', 'prepare_audio_dataset': 'prepare an audio dataset by resampling, converting to mono, and extracting features using the feature extractor'}
```

