# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/encoder_decoder/test_modeling_encoder_decoder.py

Prompts

```
['test the EncoderDecoderModel by combining a BERT encoder with a BERT decoder and verifying output shapes', 'test loading an EncoderDecoderModel from pretrained encoder and decoder model paths using from_encoder_decoder_pretrained', 'test the generate method on an EncoderDecoderModel to produce autoregressive output sequences up to a max length', 'test that the EncoderDecoderModel returns encoder attentions, decoder attentions, and cross attentions when output_attentions is enabled', 'test saving an EncoderDecoderModel to disk and reloading it to verify outputs remain numerically identical']
```

Usage

```
{'test_encoder_decoder_model': 'test the EncoderDecoderModel by combining a BERT encoder with a BERT decoder and verifying output shapes', 'test_encoder_decoder_model_from_pretrained': 'test loading an EncoderDecoderModel from pretrained encoder and decoder model paths using from_encoder_decoder_pretrained', 'test_encoder_decoder_model_generate': 'test the generate method on an EncoderDecoderModel to produce autoregressive output sequences up to a max length', 'test_encoder_decoder_model_output_attentions': 'test that the EncoderDecoderModel returns encoder attentions, decoder attentions, and cross attentions when output_attentions is enabled', 'test_encoder_decoder_model_save_and_load': 'test saving an EncoderDecoderModel to disk and reloading it to verify outputs remain numerically identical'}
```

