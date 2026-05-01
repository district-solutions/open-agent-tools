# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/unispeech_sat/test_modeling_unispeech_sat.py

Prompts

```
['test the UniSpeechSatModel by creating config and inputs then verifying output hidden state shape', 'test CTC loss inference by running UniSpeechSatForCTC with masked and unmasked inputs and checking loss values', 'test sequence classification training by freezing the base model and running a backward pass on the loss', 'test XVector speaker verification by running UniSpeechSatForXVector and computing cosine similarity between embeddings', 'test audio diarization inference by running UniSpeechSatForAudioFrameClassification and verifying speaker frame logits']
```

Usage

```
{'test_unispeechsat_model': 'test the UniSpeechSatModel by creating config and inputs then verifying output hidden state shape', 'test_ctc_loss_inference': 'test CTC loss inference by running UniSpeechSatForCTC with masked and unmasked inputs and checking loss values', 'test_sequence_classifier_training': 'test sequence classification training by freezing the base model and running a backward pass on the loss', 'test_xvector_speaker_verification': 'test XVector speaker verification by running UniSpeechSatForXVector and computing cosine similarity between embeddings', 'test_audio_diarization_inference': 'test audio diarization inference by running UniSpeechSatForAudioFrameClassification and verifying speaker frame logits'}
```

