# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/f5_tts/eval/ecapa_tdnn.py

Prompts

```
['build an ECAPA-TDNN model for speaker similarity evaluation with custom embedding dimensions', 'create an ECAPA-TDNN SMALL model with 256-dim speaker embeddings for voice comparison', 'test the attentive stats pooling layer that computes weighted mean and standard deviation of features', 'refactor the SE-Res2Block module to support custom bottleneck dimensions and residual connections', 'review the Res2Conv1dReluBn block that splits channels and applies multi-scale convolutions', 'run the eval_librispeech_test_clean module with eval_task=wer to compute word error rate on generated audio', 'run the eval_librispeech_test_clean module with eval_task=sim to compute similarity scores on generated audio', 'parse the gpu_nums argument string into a list of GPU indices for multiprocessing', 'get CLI arguments for the evaluation including eval_task, lang, gen_wav_dir, librispeech path, and gpu_nums', 'run the evaluation across multiple GPUs using multiprocessing pool to compute WER or similarity metrics', 'run the Seed-TTS evaluation script to compute similarity metrics on generated speech audio', 'build a command-line evaluation run with specified language, GPU count, and generated wav directory', 'test the gpu_nums parser with numeric string input and bracketed GPU list input', 'review the main evaluation pipeline that splits test data across GPUs and aggregates WER or similarity results', 'parse a Seed-TTS metalst file and return a list of (utt, prompt_text, prompt_wav, gt_text, gt_wav) tuples', 'generate inference prompts from metainfo with audio resampling, mel spectrogram extraction, and bucketed batching', 'build a GPU-partitioned test set from generated WAV files and a Seed-TTS metalst for evaluation', 'run automatic speech recognition WER evaluation on generated audio using funasr for Chinese or faster-whisper for English', 'compute speaker similarity scores between generated and reference audio using ECAPA-TDNN with WAVLM features']
```

Usage

```
{'build_ecapa_tdnn_model': 'build an ECAPA-TDNN model for speaker similarity evaluation with custom embedding dimensions', 'create_ecapa_tdnn_small': 'create an ECAPA-TDNN SMALL model with 256-dim speaker embeddings for voice comparison', 'test_attentive_stats_pooling': 'test the attentive stats pooling layer that computes weighted mean and standard deviation of features', 'refactor_se_res2block': 'refactor the SE-Res2Block module to support custom bottleneck dimensions and residual connections', 'review_res2conv1d_relu_bn': 'review the Res2Conv1dReluBn block that splits channels and applies multi-scale convolutions'}
```

## File: swivid_f5-tts/src/f5_tts/eval/eval_librispeech_test_clean.py

Prompts

```
['build an ECAPA-TDNN model for speaker similarity evaluation with custom embedding dimensions', 'create an ECAPA-TDNN SMALL model with 256-dim speaker embeddings for voice comparison', 'test the attentive stats pooling layer that computes weighted mean and standard deviation of features', 'refactor the SE-Res2Block module to support custom bottleneck dimensions and residual connections', 'review the Res2Conv1dReluBn block that splits channels and applies multi-scale convolutions', 'run the eval_librispeech_test_clean module with eval_task=wer to compute word error rate on generated audio', 'run the eval_librispeech_test_clean module with eval_task=sim to compute similarity scores on generated audio', 'parse the gpu_nums argument string into a list of GPU indices for multiprocessing', 'get CLI arguments for the evaluation including eval_task, lang, gen_wav_dir, librispeech path, and gpu_nums', 'run the evaluation across multiple GPUs using multiprocessing pool to compute WER or similarity metrics', 'run the Seed-TTS evaluation script to compute similarity metrics on generated speech audio', 'build a command-line evaluation run with specified language, GPU count, and generated wav directory', 'test the gpu_nums parser with numeric string input and bracketed GPU list input', 'review the main evaluation pipeline that splits test data across GPUs and aggregates WER or similarity results', 'parse a Seed-TTS metalst file and return a list of (utt, prompt_text, prompt_wav, gt_text, gt_wav) tuples', 'generate inference prompts from metainfo with audio resampling, mel spectrogram extraction, and bucketed batching', 'build a GPU-partitioned test set from generated WAV files and a Seed-TTS metalst for evaluation', 'run automatic speech recognition WER evaluation on generated audio using funasr for Chinese or faster-whisper for English', 'compute speaker similarity scores between generated and reference audio using ECAPA-TDNN with WAVLM features']
```

Usage

```
{'run_eval_wer': 'run the eval_librispeech_test_clean module with eval_task=wer to compute word error rate on generated audio', 'run_eval_sim': 'run the eval_librispeech_test_clean module with eval_task=sim to compute similarity scores on generated audio', 'parse_gpu_nums': 'parse the gpu_nums argument string into a list of GPU indices for multiprocessing', 'get_args': 'get CLI arguments for the evaluation including eval_task, lang, gen_wav_dir, librispeech path, and gpu_nums', 'run_eval_multiprocessing': 'run the evaluation across multiple GPUs using multiprocessing pool to compute WER or similarity metrics'}
```

## File: swivid_f5-tts/src/f5_tts/eval/eval_seedtts_testset.py

Prompts

```
['build an ECAPA-TDNN model for speaker similarity evaluation with custom embedding dimensions', 'create an ECAPA-TDNN SMALL model with 256-dim speaker embeddings for voice comparison', 'test the attentive stats pooling layer that computes weighted mean and standard deviation of features', 'refactor the SE-Res2Block module to support custom bottleneck dimensions and residual connections', 'review the Res2Conv1dReluBn block that splits channels and applies multi-scale convolutions', 'run the eval_librispeech_test_clean module with eval_task=wer to compute word error rate on generated audio', 'run the eval_librispeech_test_clean module with eval_task=sim to compute similarity scores on generated audio', 'parse the gpu_nums argument string into a list of GPU indices for multiprocessing', 'get CLI arguments for the evaluation including eval_task, lang, gen_wav_dir, librispeech path, and gpu_nums', 'run the evaluation across multiple GPUs using multiprocessing pool to compute WER or similarity metrics', 'run the Seed-TTS evaluation script to compute similarity metrics on generated speech audio', 'build a command-line evaluation run with specified language, GPU count, and generated wav directory', 'test the gpu_nums parser with numeric string input and bracketed GPU list input', 'review the main evaluation pipeline that splits test data across GPUs and aggregates WER or similarity results', 'parse a Seed-TTS metalst file and return a list of (utt, prompt_text, prompt_wav, gt_text, gt_wav) tuples', 'generate inference prompts from metainfo with audio resampling, mel spectrogram extraction, and bucketed batching', 'build a GPU-partitioned test set from generated WAV files and a Seed-TTS metalst for evaluation', 'run automatic speech recognition WER evaluation on generated audio using funasr for Chinese or faster-whisper for English', 'compute speaker similarity scores between generated and reference audio using ECAPA-TDNN with WAVLM features']
```

Usage

```
{'run_eval_wer': 'run the Seed-TTS evaluation script to compute WER metrics on generated speech audio', 'run_eval_similarity': 'run the Seed-TTS evaluation script to compute similarity metrics on generated speech audio', 'build_eval_command': 'build a command-line evaluation run with specified language, GPU count, and generated wav directory', 'test_parse_gpu_nums': 'test the gpu_nums parser with numeric string input and bracketed GPU list input', 'review_main_pipeline': 'review the main evaluation pipeline that splits test data across GPUs and aggregates WER or similarity results'}
```

## File: swivid_f5-tts/src/f5_tts/eval/utils_eval.py

Prompts

```
['build an ECAPA-TDNN model for speaker similarity evaluation with custom embedding dimensions', 'create an ECAPA-TDNN SMALL model with 256-dim speaker embeddings for voice comparison', 'test the attentive stats pooling layer that computes weighted mean and standard deviation of features', 'refactor the SE-Res2Block module to support custom bottleneck dimensions and residual connections', 'review the Res2Conv1dReluBn block that splits channels and applies multi-scale convolutions', 'run the eval_librispeech_test_clean module with eval_task=wer to compute word error rate on generated audio', 'run the eval_librispeech_test_clean module with eval_task=sim to compute similarity scores on generated audio', 'parse the gpu_nums argument string into a list of GPU indices for multiprocessing', 'get CLI arguments for the evaluation including eval_task, lang, gen_wav_dir, librispeech path, and gpu_nums', 'run the evaluation across multiple GPUs using multiprocessing pool to compute WER or similarity metrics', 'run the Seed-TTS evaluation script to compute similarity metrics on generated speech audio', 'build a command-line evaluation run with specified language, GPU count, and generated wav directory', 'test the gpu_nums parser with numeric string input and bracketed GPU list input', 'review the main evaluation pipeline that splits test data across GPUs and aggregates WER or similarity results', 'parse a Seed-TTS metalst file and return a list of (utt, prompt_text, prompt_wav, gt_text, gt_wav) tuples', 'generate inference prompts from metainfo with audio resampling, mel spectrogram extraction, and bucketed batching', 'build a GPU-partitioned test set from generated WAV files and a Seed-TTS metalst for evaluation', 'run automatic speech recognition WER evaluation on generated audio using funasr for Chinese or faster-whisper for English', 'compute speaker similarity scores between generated and reference audio using ECAPA-TDNN with WAVLM features']
```

Usage

```
{'get_seedtts_testset_metainfo': 'parse a Seed-TTS metalst file and return a list of (utt, prompt_text, prompt_wav, gt_text, gt_wav) tuples', 'get_inference_prompt': 'generate inference prompts from metainfo with audio resampling, mel spectrogram extraction, and bucketed batching', 'get_seed_tts_test': 'build a GPU-partitioned test set from generated WAV files and a Seed-TTS metalst for evaluation', 'run_asr_wer': 'run automatic speech recognition WER evaluation on generated audio using funasr for Chinese or faster-whisper for English', 'run_sim': 'compute speaker similarity scores between generated and reference audio using ECAPA-TDNN with WAVLM features'}
```

