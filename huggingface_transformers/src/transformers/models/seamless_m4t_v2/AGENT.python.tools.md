# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/seamless_m4t_v2/convert_fairseq2_to_hf.py

Prompts

```
['convert Meta SeamlessM4Tv2 checkpoints from seamless_communication to HuggingFace format', "load a SeamlessM4Tv2 model from Meta's Translator and save to HuggingFace with tokenizer and processor", 'convert model weights from fairseq2 to HuggingFace using layer name mapping lists', 'build a SeamlessM4TProcessor with feature extractor, tokenizer, and language code mappings', 'verify parameter counts match between original and converted HuggingFace models', 'generate text translations using SeamlessM4Tv2ForTextToText with target language specified', 'generate speech-to-text transcriptions using SeamlessM4Tv2ForSpeechToText from audio input features', 'generate translated audio waveforms from text input using SeamlessM4Tv2ForTextToSpeech with speaker and language', 'generate speech-to-speech translation using SeamlessM4Tv2ForSpeechToSpeech from audio input with target language', 'generate translated text or audio waveforms using SeamlessM4Tv2Model with multimodal input support']
```

Usage

```
{'convert_seamless_m4t_v2_checkpoint': 'convert Meta SeamlessM4Tv2 checkpoints from seamless_communication to HuggingFace format', 'load_seamless_m4t_v2_model': "load a SeamlessM4Tv2 model from Meta's Translator and save to HuggingFace with tokenizer and processor", 'convert_model_weights': 'convert model weights from fairseq2 to HuggingFace using layer name mapping lists', 'build_seamless_m4t_processor': 'build a SeamlessM4TProcessor with feature extractor, tokenizer, and language code mappings', 'verify_param_count': 'verify parameter counts match between original and converted HuggingFace models'}
```

## File: huggingface_transformers/src/transformers/models/seamless_m4t_v2/modeling_seamless_m4t_v2.py

Prompts

```
['convert Meta SeamlessM4Tv2 checkpoints from seamless_communication to HuggingFace format', "load a SeamlessM4Tv2 model from Meta's Translator and save to HuggingFace with tokenizer and processor", 'convert model weights from fairseq2 to HuggingFace using layer name mapping lists', 'build a SeamlessM4TProcessor with feature extractor, tokenizer, and language code mappings', 'verify parameter counts match between original and converted HuggingFace models', 'generate text translations using SeamlessM4Tv2ForTextToText with target language specified', 'generate speech-to-text transcriptions using SeamlessM4Tv2ForSpeechToText from audio input features', 'generate translated audio waveforms from text input using SeamlessM4Tv2ForTextToSpeech with speaker and language', 'generate speech-to-speech translation using SeamlessM4Tv2ForSpeechToSpeech from audio input with target language', 'generate translated text or audio waveforms using SeamlessM4Tv2Model with multimodal input support']
```

Usage

```
{'generate_text_translation': 'generate text translations using SeamlessM4Tv2ForTextToText with target language specified', 'generate_speech_transcription': 'generate speech-to-text transcriptions using SeamlessM4Tv2ForSpeechToText from audio input features', 'generate_speech_synthesis': 'generate translated audio waveforms from text input using SeamlessM4Tv2ForTextToSpeech with speaker and language', 'generate_speech_translation': 'generate speech-to-speech translation using SeamlessM4Tv2ForSpeechToSpeech from audio input with target language', 'generate_multimodal_output': 'generate translated text or audio waveforms using SeamlessM4Tv2Model with multimodal input support'}
```

