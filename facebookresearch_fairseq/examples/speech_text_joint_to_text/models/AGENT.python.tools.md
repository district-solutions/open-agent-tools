# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/models/joint_speech_text_pretrain_transformer.py

Prompts

```
['build a SpeechTextPreTrainModel with encoder and decoder for joint speech-text pretraining', 'build a SpeechTextPreTrainEncoder with supervised and unsupervised speech encoders plus text encoder', 'build a SpeechTextPreTrainDecoder with dummy speech decoder and transformer text decoder', 'share transformer layer parameters between speech and text encoder layers', 'configure speech_text_pretrain_bart_base or large architecture with speech masking and transformer args', 'build a dual input speech and text transformer model using DualInputS2TTransformerModel.build_model', 'build a speech encoder with S2TTransformerEncoder using DualInputEncoder.build_spch_encoder', 'build a text encoder with TransformerEncoder using DualInputEncoder.build_text_encoder', 'share decoder layers between speech and text decoders using TransformerMultiInputDecoder.share_spchdecoder', 'compute cross attentive loss between teacher and student encoder states using TransformerMultiInputDecoder.cross_attentive_loss', 'build a DualInputWavTransformerModel with a speech encoder and text encoder for speech-to-text', 'build a TransformerMultiInputDecoder with cross attentive loss support for decoding', 'load pretrained speech text encoder components from a checkpoint file', 'build a DualInputXMTransformerModel with wav2vec speech encoder and mbart text encoder for joint speech-text to text', 'build a DualInputEncoder combining wav2vec speech encoder and mbart text encoder for dual input processing', 'build a TransformerMultiInputDecoder for decoding with cross-attention to both speech and text encoder outputs', 'create a SharedEncoder that shares transformer layers between wav2vec and mbart encoders for parameter efficiency', 'create a StackedWav2VecEncoderWithAdaptor that stacks wav2vec features through mbart encoder layers']
```

Usage

```
{'build_speech_text_pretrain_model': 'build a SpeechTextPreTrainModel with encoder and decoder for joint speech-text pretraining', 'build_speech_text_encoder': 'build a SpeechTextPreTrainEncoder with supervised and unsupervised speech encoders plus text encoder', 'build_speech_text_decoder': 'build a SpeechTextPreTrainDecoder with dummy speech decoder and transformer text decoder', 'share_encoder_layers': 'share transformer layer parameters between speech and text encoder layers', 'configure_bart_architecture': 'configure speech_text_pretrain_bart_base or large architecture with speech masking and transformer args'}
```

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/models/s2t_dualinputtransformer.py

Prompts

```
['build a SpeechTextPreTrainModel with encoder and decoder for joint speech-text pretraining', 'build a SpeechTextPreTrainEncoder with supervised and unsupervised speech encoders plus text encoder', 'build a SpeechTextPreTrainDecoder with dummy speech decoder and transformer text decoder', 'share transformer layer parameters between speech and text encoder layers', 'configure speech_text_pretrain_bart_base or large architecture with speech masking and transformer args', 'build a dual input speech and text transformer model using DualInputS2TTransformerModel.build_model', 'build a speech encoder with S2TTransformerEncoder using DualInputEncoder.build_spch_encoder', 'build a text encoder with TransformerEncoder using DualInputEncoder.build_text_encoder', 'share decoder layers between speech and text decoders using TransformerMultiInputDecoder.share_spchdecoder', 'compute cross attentive loss between teacher and student encoder states using TransformerMultiInputDecoder.cross_attentive_loss', 'build a DualInputWavTransformerModel with a speech encoder and text encoder for speech-to-text', 'build a TransformerMultiInputDecoder with cross attentive loss support for decoding', 'load pretrained speech text encoder components from a checkpoint file', 'build a DualInputXMTransformerModel with wav2vec speech encoder and mbart text encoder for joint speech-text to text', 'build a DualInputEncoder combining wav2vec speech encoder and mbart text encoder for dual input processing', 'build a TransformerMultiInputDecoder for decoding with cross-attention to both speech and text encoder outputs', 'create a SharedEncoder that shares transformer layers between wav2vec and mbart encoders for parameter efficiency', 'create a StackedWav2VecEncoderWithAdaptor that stacks wav2vec features through mbart encoder layers']
```

Usage

```
{'build_dual_input_s2t_transformer': 'build a dual input speech and text transformer model using DualInputS2TTransformerModel.build_model', 'build_speech_encoder': 'build a speech encoder with S2TTransformerEncoder using DualInputEncoder.build_spch_encoder', 'build_text_encoder': 'build a text encoder with TransformerEncoder using DualInputEncoder.build_text_encoder', 'share_decoder_layers': 'share decoder layers between speech and text decoders using TransformerMultiInputDecoder.share_spchdecoder', 'compute_cross_attentive_loss': 'compute cross attentive loss between teacher and student encoder states using TransformerMultiInputDecoder.cross_attentive_loss'}
```

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/models/s2t_dualinputwavtransformer.py

Prompts

```
['build a SpeechTextPreTrainModel with encoder and decoder for joint speech-text pretraining', 'build a SpeechTextPreTrainEncoder with supervised and unsupervised speech encoders plus text encoder', 'build a SpeechTextPreTrainDecoder with dummy speech decoder and transformer text decoder', 'share transformer layer parameters between speech and text encoder layers', 'configure speech_text_pretrain_bart_base or large architecture with speech masking and transformer args', 'build a dual input speech and text transformer model using DualInputS2TTransformerModel.build_model', 'build a speech encoder with S2TTransformerEncoder using DualInputEncoder.build_spch_encoder', 'build a text encoder with TransformerEncoder using DualInputEncoder.build_text_encoder', 'share decoder layers between speech and text decoders using TransformerMultiInputDecoder.share_spchdecoder', 'compute cross attentive loss between teacher and student encoder states using TransformerMultiInputDecoder.cross_attentive_loss', 'build a DualInputWavTransformerModel with a speech encoder and text encoder for speech-to-text', 'build a TransformerMultiInputDecoder with cross attentive loss support for decoding', 'load pretrained speech text encoder components from a checkpoint file', 'build a DualInputXMTransformerModel with wav2vec speech encoder and mbart text encoder for joint speech-text to text', 'build a DualInputEncoder combining wav2vec speech encoder and mbart text encoder for dual input processing', 'build a TransformerMultiInputDecoder for decoding with cross-attention to both speech and text encoder outputs', 'create a SharedEncoder that shares transformer layers between wav2vec and mbart encoders for parameter efficiency', 'create a StackedWav2VecEncoderWithAdaptor that stacks wav2vec features through mbart encoder layers']
```

Usage

```
{'build_dual_input_wav_transformer_model': 'build a DualInputWavTransformerModel with a speech encoder and text encoder for speech-to-text', 'build_speech_encoder': 'build a SpeechWavTransformerEncoder from args for processing speech input features', 'build_text_encoder': 'build a TransformerEncoder text encoder from args and source dictionary', 'build_decoder': 'build a TransformerMultiInputDecoder with cross attentive loss support for decoding', 'load_pretrained_speech_text_components': 'load pretrained speech text encoder components from a checkpoint file'}
```

## File: facebookresearch_fairseq/examples/speech_text_joint_to_text/models/s2t_dualinputxmtransformer.py

Prompts

```
['build a SpeechTextPreTrainModel with encoder and decoder for joint speech-text pretraining', 'build a SpeechTextPreTrainEncoder with supervised and unsupervised speech encoders plus text encoder', 'build a SpeechTextPreTrainDecoder with dummy speech decoder and transformer text decoder', 'share transformer layer parameters between speech and text encoder layers', 'configure speech_text_pretrain_bart_base or large architecture with speech masking and transformer args', 'build a dual input speech and text transformer model using DualInputS2TTransformerModel.build_model', 'build a speech encoder with S2TTransformerEncoder using DualInputEncoder.build_spch_encoder', 'build a text encoder with TransformerEncoder using DualInputEncoder.build_text_encoder', 'share decoder layers between speech and text decoders using TransformerMultiInputDecoder.share_spchdecoder', 'compute cross attentive loss between teacher and student encoder states using TransformerMultiInputDecoder.cross_attentive_loss', 'build a DualInputWavTransformerModel with a speech encoder and text encoder for speech-to-text', 'build a TransformerMultiInputDecoder with cross attentive loss support for decoding', 'load pretrained speech text encoder components from a checkpoint file', 'build a DualInputXMTransformerModel with wav2vec speech encoder and mbart text encoder for joint speech-text to text', 'build a DualInputEncoder combining wav2vec speech encoder and mbart text encoder for dual input processing', 'build a TransformerMultiInputDecoder for decoding with cross-attention to both speech and text encoder outputs', 'create a SharedEncoder that shares transformer layers between wav2vec and mbart encoders for parameter efficiency', 'create a StackedWav2VecEncoderWithAdaptor that stacks wav2vec features through mbart encoder layers']
```

Usage

```
{'build_dualinputxmtransformer_model': 'build a DualInputXMTransformerModel with wav2vec speech encoder and mbart text encoder for joint speech-text to text', 'build_dualinputxmtransformer_encoder': 'build a DualInputEncoder combining wav2vec speech encoder and mbart text encoder for dual input processing', 'build_dualinputxmtransformer_decoder': 'build a TransformerMultiInputDecoder for decoding with cross-attention to both speech and text encoder outputs', 'create_sharedencoder': 'create a SharedEncoder that shares transformer layers between wav2vec and mbart encoders for parameter efficiency', 'create_stackedwav2vecencoder': 'create a StackedWav2VecEncoderWithAdaptor that stacks wav2vec features through mbart encoder layers'}
```

