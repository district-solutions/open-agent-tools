# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/speech/asr/wav2vec/base_decoder.py

Prompts

```
['generate ASR decoding results from Fairseq models and input samples using BaseDecoder', 'get emissions tensor from Fairseq model encoder output for speech recognition', 'get token tensor from indices by removing blanks and collapsing duplicates', 'review the BaseDecoder class and its CTC decoding methods for ASR tasks', 'create a subclass of BaseDecoder that implements the abstract decode method', 'create a KenLMDecoder with a FlashlightDecoderConfig and target dictionary for CTC beam search decoding', 'decode audio emissions tensor using KenLMDecoder to get n-best hypothesis results with tokens and scores', 'create a FairseqLM wrapper around a FairseqModel to score words during flashlight decoding', 'score a token given the current LM state and return the new state and log probability', 'create a FairseqLMDecoder that uses a Fairseq language model instead of KenLM for ASR decoding', 'decode CTC emissions tensor into token sequences using ViterbiDecoder', 'create a ViterbiDecoder instance with a target dictionary for ASR decoding', 'review the ViterbiDecoder decode method that extracts argmax tokens and filters blanks', 'test the ViterbiDecoder decode method with a sample emissions tensor', 'summarize the ViterbiDecoder class that extends BaseDecoder for wav2vec ASR']
```

Usage

```
{'generate_asr_decoding': 'generate ASR decoding results from Fairseq models and input samples using BaseDecoder', 'get_emissions_from_encoder': 'get emissions tensor from Fairseq model encoder output for speech recognition', 'get_tokens_from_indices': 'get token tensor from indices by removing blanks and collapsing duplicates', 'review_basedecoder_class': 'review the BaseDecoder class and its CTC decoding methods for ASR tasks', 'create_basedecoder_subclass': 'create a subclass of BaseDecoder that implements the abstract decode method'}
```

## File: facebookresearch_stopes/stopes/speech/asr/wav2vec/flashlight_decoder.py

Prompts

```
['generate ASR decoding results from Fairseq models and input samples using BaseDecoder', 'get emissions tensor from Fairseq model encoder output for speech recognition', 'get token tensor from indices by removing blanks and collapsing duplicates', 'review the BaseDecoder class and its CTC decoding methods for ASR tasks', 'create a subclass of BaseDecoder that implements the abstract decode method', 'create a KenLMDecoder with a FlashlightDecoderConfig and target dictionary for CTC beam search decoding', 'decode audio emissions tensor using KenLMDecoder to get n-best hypothesis results with tokens and scores', 'create a FairseqLM wrapper around a FairseqModel to score words during flashlight decoding', 'score a token given the current LM state and return the new state and log probability', 'create a FairseqLMDecoder that uses a Fairseq language model instead of KenLM for ASR decoding', 'decode CTC emissions tensor into token sequences using ViterbiDecoder', 'create a ViterbiDecoder instance with a target dictionary for ASR decoding', 'review the ViterbiDecoder decode method that extracts argmax tokens and filters blanks', 'test the ViterbiDecoder decode method with a sample emissions tensor', 'summarize the ViterbiDecoder class that extends BaseDecoder for wav2vec ASR']
```

Usage

```
{'create_KenLMDecoder': 'create a KenLMDecoder with a FlashlightDecoderConfig and target dictionary for CTC beam search decoding', 'decode_KenLMDecoder': 'decode audio emissions tensor using KenLMDecoder to get n-best hypothesis results with tokens and scores', 'create_FairseqLM': 'create a FairseqLM wrapper around a FairseqModel to score words during flashlight decoding', 'score_FairseqLM': 'score a token given the current LM state and return the new state and log probability', 'create_FairseqLMDecoder': 'create a FairseqLMDecoder that uses a Fairseq language model instead of KenLM for ASR decoding'}
```

## File: facebookresearch_stopes/stopes/speech/asr/wav2vec/viterbi_decoder.py

Prompts

```
['generate ASR decoding results from Fairseq models and input samples using BaseDecoder', 'get emissions tensor from Fairseq model encoder output for speech recognition', 'get token tensor from indices by removing blanks and collapsing duplicates', 'review the BaseDecoder class and its CTC decoding methods for ASR tasks', 'create a subclass of BaseDecoder that implements the abstract decode method', 'create a KenLMDecoder with a FlashlightDecoderConfig and target dictionary for CTC beam search decoding', 'decode audio emissions tensor using KenLMDecoder to get n-best hypothesis results with tokens and scores', 'create a FairseqLM wrapper around a FairseqModel to score words during flashlight decoding', 'score a token given the current LM state and return the new state and log probability', 'create a FairseqLMDecoder that uses a Fairseq language model instead of KenLM for ASR decoding', 'decode CTC emissions tensor into token sequences using ViterbiDecoder', 'create a ViterbiDecoder instance with a target dictionary for ASR decoding', 'review the ViterbiDecoder decode method that extracts argmax tokens and filters blanks', 'test the ViterbiDecoder decode method with a sample emissions tensor', 'summarize the ViterbiDecoder class that extends BaseDecoder for wav2vec ASR']
```

Usage

```
{'decode_emissions_with_viterbi': 'decode CTC emissions tensor into token sequences using ViterbiDecoder', 'create_viterbi_decoder_instance': 'create a ViterbiDecoder instance with a target dictionary for ASR decoding', 'review_viterbi_decode_method': 'review the ViterbiDecoder decode method that extracts argmax tokens and filters blanks', 'test_viterbi_decoder_decode': 'test the ViterbiDecoder decode method with a sample emissions tensor', 'summarize_viterbi_decoder_class': 'summarize the ViterbiDecoder class that extends BaseDecoder for wav2vec ASR'}
```

