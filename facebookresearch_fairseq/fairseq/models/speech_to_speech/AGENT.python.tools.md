# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/models/speech_to_speech/s2s_conformer.py

Prompts

```
['build a S2SConformerEncoder with optional pretrained checkpoint loading from a model path', 'create a forward pass through S2SConformerEncoder with source tokens and target speaker embedding', 'register the s2ut_conformer model for speech-to-speech translation with Conformer encoder and discrete unit decoder', 'register the s2spect_conformer model for speech-to-speech translation with Conformer encoder and TTS decoder', 'configure the s2spect_conformer_fisher architecture with encoder embed dim 256 and prenet dim 32', 'build a speech-to-speech translation model with Conformer encoder and TTS Transformer decoder', 'build a multitask decoder supporting transformer or CTC decoder types for translation tasks', 'build a TTS Transformer decoder for the second-pass synthesizer module', 'run the forward pass through MT decoder, TTS encoder, and TTS decoder stages', 'configure the s2spect2_conformer architecture with Conformer encoder and translation decoder settings', 'build a UnityConformerModel for direct speech-to-speech translation with Conformer encoder and multitask decoders', 'build a TransformerUnitDecoder or AugTransformerUnitDecoder with stacked embeddings for unit decoding', 'run the UnityConformerModel forward pass with source tokens, target tokens, and multitask decoder output', 'configure the unity_conformer architecture base with encoder layers, embed dimensions, and attention heads', 'build a speech-to-speech translation model using S2UTTransformerModel with a Transformer encoder and discrete unit decoder', 'build a speech-to-spectrogram model using S2SpecTTransformerModel with an S2T encoder and TTS Transformer decoder', 'build an S2STransformerEncoder that incorporates target speaker embeddings into the encoder output', 'build a TransformerUnitDecoder that decodes stacked units with configurable frames per step']
```

Usage

```
{'build_s2s_conformer_encoder': 'build a S2SConformerEncoder with optional pretrained checkpoint loading from a model path', 'create_s2s_conformer_encoder_forward': 'create a forward pass through S2SConformerEncoder with source tokens and target speaker embedding', 'register_s2ut_conformer_model': 'register the s2ut_conformer model for speech-to-speech translation with Conformer encoder and discrete unit decoder', 'register_s2spect_conformer_model': 'register the s2spect_conformer model for speech-to-speech translation with Conformer encoder and TTS decoder', 'configure_s2spect_conformer_fisher_architecture': 'configure the s2spect_conformer_fisher architecture with encoder embed dim 256 and prenet dim 32'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_to_speech/s2s_conformer_translatotron2.py

Prompts

```
['build a S2SConformerEncoder with optional pretrained checkpoint loading from a model path', 'create a forward pass through S2SConformerEncoder with source tokens and target speaker embedding', 'register the s2ut_conformer model for speech-to-speech translation with Conformer encoder and discrete unit decoder', 'register the s2spect_conformer model for speech-to-speech translation with Conformer encoder and TTS decoder', 'configure the s2spect_conformer_fisher architecture with encoder embed dim 256 and prenet dim 32', 'build a speech-to-speech translation model with Conformer encoder and TTS Transformer decoder', 'build a multitask decoder supporting transformer or CTC decoder types for translation tasks', 'build a TTS Transformer decoder for the second-pass synthesizer module', 'run the forward pass through MT decoder, TTS encoder, and TTS decoder stages', 'configure the s2spect2_conformer architecture with Conformer encoder and translation decoder settings', 'build a UnityConformerModel for direct speech-to-speech translation with Conformer encoder and multitask decoders', 'build a TransformerUnitDecoder or AugTransformerUnitDecoder with stacked embeddings for unit decoding', 'run the UnityConformerModel forward pass with source tokens, target tokens, and multitask decoder output', 'configure the unity_conformer architecture base with encoder layers, embed dimensions, and attention heads', 'build a speech-to-speech translation model using S2UTTransformerModel with a Transformer encoder and discrete unit decoder', 'build a speech-to-spectrogram model using S2SpecTTransformerModel with an S2T encoder and TTS Transformer decoder', 'build an S2STransformerEncoder that incorporates target speaker embeddings into the encoder output', 'build a TransformerUnitDecoder that decodes stacked units with configurable frames per step']
```

Usage

```
{'build_s2spect2_conformer_model': 'build a speech-to-speech translation model with Conformer encoder and TTS Transformer decoder', 'build_multitask_decoder': 'build a multitask decoder supporting transformer or CTC decoder types for translation tasks', 'build_tts_decoder': 'build a TTS Transformer decoder for the second-pass synthesizer module', 'forward_s2spect2_conformer': 'run the forward pass through MT decoder, TTS encoder, and TTS decoder stages', 'configure_s2spect2_conformer_architecture': 'configure the s2spect2_conformer architecture with Conformer encoder and translation decoder settings'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_to_speech/s2s_conformer_unity.py

Prompts

```
['build a S2SConformerEncoder with optional pretrained checkpoint loading from a model path', 'create a forward pass through S2SConformerEncoder with source tokens and target speaker embedding', 'register the s2ut_conformer model for speech-to-speech translation with Conformer encoder and discrete unit decoder', 'register the s2spect_conformer model for speech-to-speech translation with Conformer encoder and TTS decoder', 'configure the s2spect_conformer_fisher architecture with encoder embed dim 256 and prenet dim 32', 'build a speech-to-speech translation model with Conformer encoder and TTS Transformer decoder', 'build a multitask decoder supporting transformer or CTC decoder types for translation tasks', 'build a TTS Transformer decoder for the second-pass synthesizer module', 'run the forward pass through MT decoder, TTS encoder, and TTS decoder stages', 'configure the s2spect2_conformer architecture with Conformer encoder and translation decoder settings', 'build a UnityConformerModel for direct speech-to-speech translation with Conformer encoder and multitask decoders', 'build a TransformerUnitDecoder or AugTransformerUnitDecoder with stacked embeddings for unit decoding', 'run the UnityConformerModel forward pass with source tokens, target tokens, and multitask decoder output', 'configure the unity_conformer architecture base with encoder layers, embed dimensions, and attention heads', 'build a speech-to-speech translation model using S2UTTransformerModel with a Transformer encoder and discrete unit decoder', 'build a speech-to-spectrogram model using S2SpecTTransformerModel with an S2T encoder and TTS Transformer decoder', 'build an S2STransformerEncoder that incorporates target speaker embeddings into the encoder output', 'build a TransformerUnitDecoder that decodes stacked units with configurable frames per step']
```

Usage

```
{'build_unity_conformer_model': 'build a UnityConformerModel for direct speech-to-speech translation with Conformer encoder and multitask decoders', 'build_multitask_decoder': 'build a multitask decoder with transformer or CTC type for the UnityConformerModel', 'build_decoder': 'build a TransformerUnitDecoder or AugTransformerUnitDecoder with stacked embeddings for unit decoding', 'forward_unity_conformer': 'run the UnityConformerModel forward pass with source tokens, target tokens, and multitask decoder output', 'configure_unity_conformer_architecture': 'configure the unity_conformer architecture base with encoder layers, embed dimensions, and attention heads'}
```

## File: facebookresearch_fairseq/fairseq/models/speech_to_speech/s2s_transformer.py

Prompts

```
['build a S2SConformerEncoder with optional pretrained checkpoint loading from a model path', 'create a forward pass through S2SConformerEncoder with source tokens and target speaker embedding', 'register the s2ut_conformer model for speech-to-speech translation with Conformer encoder and discrete unit decoder', 'register the s2spect_conformer model for speech-to-speech translation with Conformer encoder and TTS decoder', 'configure the s2spect_conformer_fisher architecture with encoder embed dim 256 and prenet dim 32', 'build a speech-to-speech translation model with Conformer encoder and TTS Transformer decoder', 'build a multitask decoder supporting transformer or CTC decoder types for translation tasks', 'build a TTS Transformer decoder for the second-pass synthesizer module', 'run the forward pass through MT decoder, TTS encoder, and TTS decoder stages', 'configure the s2spect2_conformer architecture with Conformer encoder and translation decoder settings', 'build a UnityConformerModel for direct speech-to-speech translation with Conformer encoder and multitask decoders', 'build a TransformerUnitDecoder or AugTransformerUnitDecoder with stacked embeddings for unit decoding', 'run the UnityConformerModel forward pass with source tokens, target tokens, and multitask decoder output', 'configure the unity_conformer architecture base with encoder layers, embed dimensions, and attention heads', 'build a speech-to-speech translation model using S2UTTransformerModel with a Transformer encoder and discrete unit decoder', 'build a speech-to-spectrogram model using S2SpecTTransformerModel with an S2T encoder and TTS Transformer decoder', 'build an S2STransformerEncoder that incorporates target speaker embeddings into the encoder output', 'build a TransformerUnitDecoder that decodes stacked units with configurable frames per step']
```

Usage

```
{'build_s2ut_transformer_model': 'build a speech-to-speech translation model using S2UTTransformerModel with a Transformer encoder and discrete unit decoder', 'build_s2spect_transformer_model': 'build a speech-to-spectrogram model using S2SpecTTransformerModel with an S2T encoder and TTS Transformer decoder', 'build_s2s_transformer_encoder': 'build an S2STransformerEncoder that incorporates target speaker embeddings into the encoder output', 'build_transformer_unit_decoder': 'build a TransformerUnitDecoder that decodes stacked units with configurable frames per step', 'build_multitask_decoder': 'build a multitask decoder using S2STransformerMultitaskModelBase for transformer or CTC decoder types'}
```

