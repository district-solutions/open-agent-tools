# Agent Python Tools

- repo: facebookresearch/speech-resynthesis
- repo_uri: https://github.com/facebookresearch/speech-resynthesis

## File: facebookresearch_speech-resynthesis/examples/speech_to_speech_translation/inference.py

Prompts

```
['run speech-to-speech translation inference from discrete codes to generate audio wav files using a checkpoint', 'run parallel multi-GPU inference on a dataset of speech codes using multiprocessing pool workers', 'run single speaker speech synthesis inference with duration prediction on a code file', 'run multi-speaker speech synthesis inference generating audio for multiple random speakers from codes', 'run debug mode inference on a limited number of samples with a progress bar', 'build a VariancePredictor module that predicts duration from encoder embeddings using convolutional layers', 'create a DurationCodeGenerator that synthesizes speech from discrete codes with duration prediction', 'test the process_duration function to extract unique code counts and features from batched sequences', 'review the DurationCodeGenerator forward pass that handles training duration loss and inference duration prediction', 'summarize the VariancePredictor forward method that transforms BxTxC input through conv layers to BxT output', 'run the speech-to-speech translation training loop with a config file and checkpoint path', 'run multi-GPU distributed training for the DurationCodeGenerator vocoder model', 'run fine-tuning of the speech resynthesis model from a saved checkpoint', 'review the train function that orchestrates generator and discriminator training with HiFi-GAN loss', 'review the main entry point that parses CLI args and loads the JSON config']
```

Usage

```
{'run_speech_synthesis_inference': 'run speech-to-speech translation inference from discrete codes to generate audio wav files using a checkpoint', 'run_multi_gpu_inference': 'run parallel multi-GPU inference on a dataset of speech codes using multiprocessing pool workers', 'run_single_speaker_inference': 'run single speaker speech synthesis inference with duration prediction on a code file', 'run_multi_speaker_inference': 'run multi-speaker speech synthesis inference generating audio for multiple random speakers from codes', 'run_debug_inference': 'run debug mode inference on a limited number of samples with a progress bar'}
```

## File: facebookresearch_speech-resynthesis/examples/speech_to_speech_translation/models.py

Prompts

```
['run speech-to-speech translation inference from discrete codes to generate audio wav files using a checkpoint', 'run parallel multi-GPU inference on a dataset of speech codes using multiprocessing pool workers', 'run single speaker speech synthesis inference with duration prediction on a code file', 'run multi-speaker speech synthesis inference generating audio for multiple random speakers from codes', 'run debug mode inference on a limited number of samples with a progress bar', 'build a VariancePredictor module that predicts duration from encoder embeddings using convolutional layers', 'create a DurationCodeGenerator that synthesizes speech from discrete codes with duration prediction', 'test the process_duration function to extract unique code counts and features from batched sequences', 'review the DurationCodeGenerator forward pass that handles training duration loss and inference duration prediction', 'summarize the VariancePredictor forward method that transforms BxTxC input through conv layers to BxT output', 'run the speech-to-speech translation training loop with a config file and checkpoint path', 'run multi-GPU distributed training for the DurationCodeGenerator vocoder model', 'run fine-tuning of the speech resynthesis model from a saved checkpoint', 'review the train function that orchestrates generator and discriminator training with HiFi-GAN loss', 'review the main entry point that parses CLI args and loads the JSON config']
```

Usage

```
{'build_VariancePredictor': 'build a VariancePredictor module that predicts duration from encoder embeddings using convolutional layers', 'create_DurationCodeGenerator': 'create a DurationCodeGenerator that synthesizes speech from discrete codes with duration prediction', 'test_process_duration': 'test the process_duration function to extract unique code counts and features from batched sequences', 'review_DurationCodeGenerator_forward': 'review the DurationCodeGenerator forward pass that handles training duration loss and inference duration prediction', 'summarize_VariancePredictor_forward': 'summarize the VariancePredictor forward method that transforms BxTxC input through conv layers to BxT output'}
```

## File: facebookresearch_speech-resynthesis/examples/speech_to_speech_translation/train.py

Prompts

```
['run speech-to-speech translation inference from discrete codes to generate audio wav files using a checkpoint', 'run parallel multi-GPU inference on a dataset of speech codes using multiprocessing pool workers', 'run single speaker speech synthesis inference with duration prediction on a code file', 'run multi-speaker speech synthesis inference generating audio for multiple random speakers from codes', 'run debug mode inference on a limited number of samples with a progress bar', 'build a VariancePredictor module that predicts duration from encoder embeddings using convolutional layers', 'create a DurationCodeGenerator that synthesizes speech from discrete codes with duration prediction', 'test the process_duration function to extract unique code counts and features from batched sequences', 'review the DurationCodeGenerator forward pass that handles training duration loss and inference duration prediction', 'summarize the VariancePredictor forward method that transforms BxTxC input through conv layers to BxT output', 'run the speech-to-speech translation training loop with a config file and checkpoint path', 'run multi-GPU distributed training for the DurationCodeGenerator vocoder model', 'run fine-tuning of the speech resynthesis model from a saved checkpoint', 'review the train function that orchestrates generator and discriminator training with HiFi-GAN loss', 'review the main entry point that parses CLI args and loads the JSON config']
```

Usage

```
{'run_train_speech_translation': 'run the speech-to-speech translation training loop with a config file and checkpoint path', 'run_distributed_training': 'run multi-GPU distributed training for the DurationCodeGenerator vocoder model', 'run_fine_tuning': 'run fine-tuning of the speech resynthesis model from a saved checkpoint', 'review_train_function': 'review the train function that orchestrates generator and discriminator training with HiFi-GAN loss', 'review_main_entry': 'review the main entry point that parses CLI args and loads the JSON config'}
```

