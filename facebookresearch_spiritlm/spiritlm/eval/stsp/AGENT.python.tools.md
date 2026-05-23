# Agent Python Tools

- repo: facebookresearch/spiritlm
- repo_uri: https://github.com/facebookresearch/spiritlm

## File: facebookresearch_spiritlm/spiritlm/eval/stsp/few_shot_prompt.py

Prompts

```
['build a few-shot prompt for STSP evaluation with text-to-text, text-to-speech, speech-to-text, or speech-to-speech examples', "create a speech prompt string by tokenizing a wav file using the SpiritLM model's speech tokenizer", "create a text prompt string by prepending the SpiritLM model's text prompt prefix to input text", 'load the first or second half of a wav audio file from the STSP data root as a tensor', 'review the few-shot prompt builder module that concatenates examples for STSP text-speech tasks', 'run distributed STSP prediction for speech-text or text-speech tasks using SpiritLM model', 'get the appropriate emotion or sentiment classifier based on input-output modality type', 'get predicted sentiment from generated speech audio or text using a loaded classifier', 'write a dictionary of predictions to a JSONL file with one record per line', 'write a numpy audio waveform to a WAV file with a random UUID filename', 'run the sanity check script to verify all wav files exist for stsp datasets', 'check that all wav files referenced in stsp jsonl manifests exist on disk', 'validate wav_path, prompt, and generation wav file paths in stsp dataset manifests', 'review the check_all_datasets function that iterates stsp manifests and asserts wav file existence', 'summarize the sanity check script that validates stsp dataset wav file downloads', 'load a sentiment classifier pipeline from a model directory using HuggingFace transformers', 'get the sentiment prediction and confidence score for a given text string', 'extract the highest scoring label and score from sentiment prediction results', 'run sentiment analysis on text using a preloaded RoBERTa-based classifier pipeline', 'review the pred_to_label function that extracts max score and label from prediction scores', 'load an Expresso emotion classification model from a checkpoint path for audio emotion prediction', 'predict the emotion label and logits for an audio file using the loaded emotion classifier', 'classify a WAV audio file or array into a single predicted emotion label', 'classify a WAV audio file into both an emotion label and its mapped sentiment', 'map an Expresso emotion label like happy or angry to a sentiment like positive or negative']
```

Usage

```
{'build_few_shot_prompt': 'build a few-shot prompt for STSP evaluation with text-to-text, text-to-speech, speech-to-text, or speech-to-speech examples', 'wav_prompt': "create a speech prompt string by tokenizing a wav file using the SpiritLM model's speech tokenizer", 'text_prompt': "create a text prompt string by prepending the SpiritLM model's text prompt prefix to input text", 'load_half_wav': 'load the first or second half of a wav audio file from the STSP data root as a tensor', 'review_few_shot_prompt': 'review the few-shot prompt builder module that concatenates examples for STSP text-speech tasks'}
```

## File: facebookresearch_spiritlm/spiritlm/eval/stsp/predict_stsp.py

Prompts

```
['build a few-shot prompt for STSP evaluation with text-to-text, text-to-speech, speech-to-text, or speech-to-speech examples', "create a speech prompt string by tokenizing a wav file using the SpiritLM model's speech tokenizer", "create a text prompt string by prepending the SpiritLM model's text prompt prefix to input text", 'load the first or second half of a wav audio file from the STSP data root as a tensor', 'review the few-shot prompt builder module that concatenates examples for STSP text-speech tasks', 'run distributed STSP prediction for speech-text or text-speech tasks using SpiritLM model', 'get the appropriate emotion or sentiment classifier based on input-output modality type', 'get predicted sentiment from generated speech audio or text using a loaded classifier', 'write a dictionary of predictions to a JSONL file with one record per line', 'write a numpy audio waveform to a WAV file with a random UUID filename', 'run the sanity check script to verify all wav files exist for stsp datasets', 'check that all wav files referenced in stsp jsonl manifests exist on disk', 'validate wav_path, prompt, and generation wav file paths in stsp dataset manifests', 'review the check_all_datasets function that iterates stsp manifests and asserts wav file existence', 'summarize the sanity check script that validates stsp dataset wav file downloads', 'load a sentiment classifier pipeline from a model directory using HuggingFace transformers', 'get the sentiment prediction and confidence score for a given text string', 'extract the highest scoring label and score from sentiment prediction results', 'run sentiment analysis on text using a preloaded RoBERTa-based classifier pipeline', 'review the pred_to_label function that extracts max score and label from prediction scores', 'load an Expresso emotion classification model from a checkpoint path for audio emotion prediction', 'predict the emotion label and logits for an audio file using the loaded emotion classifier', 'classify a WAV audio file or array into a single predicted emotion label', 'classify a WAV audio file into both an emotion label and its mapped sentiment', 'map an Expresso emotion label like happy or angry to a sentiment like positive or negative']
```

Usage

```
{'run_stsp_prediction': 'run distributed STSP prediction for speech-text or text-speech tasks using SpiritLM model', 'get_eval_classifier': 'get the appropriate emotion or sentiment classifier based on input-output modality type', 'get_sentiment': 'get predicted sentiment from generated speech audio or text using a loaded classifier', 'write_jsonl': 'write a dictionary of predictions to a JSONL file with one record per line', 'write_wav': 'write a numpy audio waveform to a WAV file with a random UUID filename'}
```

## File: facebookresearch_spiritlm/spiritlm/eval/stsp/sanity_check_download.py

Prompts

```
['build a few-shot prompt for STSP evaluation with text-to-text, text-to-speech, speech-to-text, or speech-to-speech examples', "create a speech prompt string by tokenizing a wav file using the SpiritLM model's speech tokenizer", "create a text prompt string by prepending the SpiritLM model's text prompt prefix to input text", 'load the first or second half of a wav audio file from the STSP data root as a tensor', 'review the few-shot prompt builder module that concatenates examples for STSP text-speech tasks', 'run distributed STSP prediction for speech-text or text-speech tasks using SpiritLM model', 'get the appropriate emotion or sentiment classifier based on input-output modality type', 'get predicted sentiment from generated speech audio or text using a loaded classifier', 'write a dictionary of predictions to a JSONL file with one record per line', 'write a numpy audio waveform to a WAV file with a random UUID filename', 'run the sanity check script to verify all wav files exist for stsp datasets', 'check that all wav files referenced in stsp jsonl manifests exist on disk', 'validate wav_path, prompt, and generation wav file paths in stsp dataset manifests', 'review the check_all_datasets function that iterates stsp manifests and asserts wav file existence', 'summarize the sanity check script that validates stsp dataset wav file downloads', 'load a sentiment classifier pipeline from a model directory using HuggingFace transformers', 'get the sentiment prediction and confidence score for a given text string', 'extract the highest scoring label and score from sentiment prediction results', 'run sentiment analysis on text using a preloaded RoBERTa-based classifier pipeline', 'review the pred_to_label function that extracts max score and label from prediction scores', 'load an Expresso emotion classification model from a checkpoint path for audio emotion prediction', 'predict the emotion label and logits for an audio file using the loaded emotion classifier', 'classify a WAV audio file or array into a single predicted emotion label', 'classify a WAV audio file into both an emotion label and its mapped sentiment', 'map an Expresso emotion label like happy or angry to a sentiment like positive or negative']
```

Usage

```
{'run_check_all_datasets': 'run the sanity check script to verify all wav files exist for stsp datasets', 'check_dataset_integrity': 'check that all wav files referenced in stsp jsonl manifests exist on disk', 'validate_wav_paths': 'validate wav_path, prompt, and generation wav file paths in stsp dataset manifests', 'review_check_all_datasets': 'review the check_all_datasets function that iterates stsp manifests and asserts wav file existence', 'summarize_sanity_check': 'summarize the sanity check script that validates stsp dataset wav file downloads'}
```

## File: facebookresearch_spiritlm/spiritlm/eval/stsp/sentiment_classifiers.py

Prompts

```
['build a few-shot prompt for STSP evaluation with text-to-text, text-to-speech, speech-to-text, or speech-to-speech examples', "create a speech prompt string by tokenizing a wav file using the SpiritLM model's speech tokenizer", "create a text prompt string by prepending the SpiritLM model's text prompt prefix to input text", 'load the first or second half of a wav audio file from the STSP data root as a tensor', 'review the few-shot prompt builder module that concatenates examples for STSP text-speech tasks', 'run distributed STSP prediction for speech-text or text-speech tasks using SpiritLM model', 'get the appropriate emotion or sentiment classifier based on input-output modality type', 'get predicted sentiment from generated speech audio or text using a loaded classifier', 'write a dictionary of predictions to a JSONL file with one record per line', 'write a numpy audio waveform to a WAV file with a random UUID filename', 'run the sanity check script to verify all wav files exist for stsp datasets', 'check that all wav files referenced in stsp jsonl manifests exist on disk', 'validate wav_path, prompt, and generation wav file paths in stsp dataset manifests', 'review the check_all_datasets function that iterates stsp manifests and asserts wav file existence', 'summarize the sanity check script that validates stsp dataset wav file downloads', 'load a sentiment classifier pipeline from a model directory using HuggingFace transformers', 'get the sentiment prediction and confidence score for a given text string', 'extract the highest scoring label and score from sentiment prediction results', 'run sentiment analysis on text using a preloaded RoBERTa-based classifier pipeline', 'review the pred_to_label function that extracts max score and label from prediction scores', 'load an Expresso emotion classification model from a checkpoint path for audio emotion prediction', 'predict the emotion label and logits for an audio file using the loaded emotion classifier', 'classify a WAV audio file or array into a single predicted emotion label', 'classify a WAV audio file into both an emotion label and its mapped sentiment', 'map an Expresso emotion label like happy or angry to a sentiment like positive or negative']
```

Usage

```
{'load_sentiment_classifier': 'load a sentiment classifier pipeline from a model directory using HuggingFace transformers', 'get_text_sentiment_prediction': 'get the sentiment prediction and confidence score for a given text string', 'pred_to_label': 'extract the highest scoring label and score from sentiment prediction results', 'run_sentiment_analysis': 'run sentiment analysis on text using a preloaded RoBERTa-based classifier pipeline', 'review_pred_to_label': 'review the pred_to_label function that extracts max score and label from prediction scores'}
```

## File: facebookresearch_spiritlm/spiritlm/eval/stsp/utils.py

Prompts

```
['build a few-shot prompt for STSP evaluation with text-to-text, text-to-speech, speech-to-text, or speech-to-speech examples', "create a speech prompt string by tokenizing a wav file using the SpiritLM model's speech tokenizer", "create a text prompt string by prepending the SpiritLM model's text prompt prefix to input text", 'load the first or second half of a wav audio file from the STSP data root as a tensor', 'review the few-shot prompt builder module that concatenates examples for STSP text-speech tasks', 'run distributed STSP prediction for speech-text or text-speech tasks using SpiritLM model', 'get the appropriate emotion or sentiment classifier based on input-output modality type', 'get predicted sentiment from generated speech audio or text using a loaded classifier', 'write a dictionary of predictions to a JSONL file with one record per line', 'write a numpy audio waveform to a WAV file with a random UUID filename', 'run the sanity check script to verify all wav files exist for stsp datasets', 'check that all wav files referenced in stsp jsonl manifests exist on disk', 'validate wav_path, prompt, and generation wav file paths in stsp dataset manifests', 'review the check_all_datasets function that iterates stsp manifests and asserts wav file existence', 'summarize the sanity check script that validates stsp dataset wav file downloads', 'load a sentiment classifier pipeline from a model directory using HuggingFace transformers', 'get the sentiment prediction and confidence score for a given text string', 'extract the highest scoring label and score from sentiment prediction results', 'run sentiment analysis on text using a preloaded RoBERTa-based classifier pipeline', 'review the pred_to_label function that extracts max score and label from prediction scores', 'load an Expresso emotion classification model from a checkpoint path for audio emotion prediction', 'predict the emotion label and logits for an audio file using the loaded emotion classifier', 'classify a WAV audio file or array into a single predicted emotion label', 'classify a WAV audio file into both an emotion label and its mapped sentiment', 'map an Expresso emotion label like happy or angry to a sentiment like positive or negative']
```

Usage

```
{'load_emotion_classifier': 'load an Expresso emotion classification model from a checkpoint path for audio emotion prediction', 'predict_audio': 'predict the emotion label and logits for an audio file using the loaded emotion classifier', 'wav2emotion': 'classify a WAV audio file or array into a single predicted emotion label', 'wav2emotion_and_sentiment': 'classify a WAV audio file into both an emotion label and its mapped sentiment', 'expresso_emotion2_sentiment': 'map an Expresso emotion label like happy or angry to a sentiment like positive or negative'}
```

