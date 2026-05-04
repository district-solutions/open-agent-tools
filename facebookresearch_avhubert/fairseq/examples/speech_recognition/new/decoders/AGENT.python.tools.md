# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/new/decoders/base_decoder.py

Prompts

```
['generate speech recognition output from a list of fairseq models and a sample input', 'get emissions as log probabilities from a fairseq model encoder output', 'get deduplicated token indices by removing consecutive duplicates and blank tokens', 'review the BaseDecoder class and its abstract decode method for speech recognition', 'summarize the BaseDecoder init method that sets up blank and silence tokens from a dictionary', 'create a ViterbiDecoder by calling Decoder with cfg type set to viterbi and a target dictionary', 'create a KenLMDecoder by calling Decoder with cfg type set to kenlm and a target dictionary', 'create a FairseqLMDecoder by calling Decoder with cfg type set to fairseqlm and a target dictionary', 'review the Decoder factory function that dispatches to ViterbiDecoder, KenLMDecoder, or FairseqLMDecoder based on config type', 'summarize the DecoderConfig dataclass that defines the decoder type choice enum with options viterbi, kenlm, and fairseqlm', 'build a KenLMDecoder with a flashlight config and target dictionary for CTC beam search decoding', 'decode CTC emissions tensor using the KenLMDecoder to get n-best hypothesis results with tokens and scores', 'build a FairseqLM language model wrapper from a fairseq model and dictionary for flashlight integration', 'score a token against the current FairseqLM state and return a new LMState with its log probability', 'build a FairseqLMDecoder using a fairseq checkpoint as the language model for CTC beam search decoding', 'decode CTC emissions tensor to predicted token sequences by taking argmax and removing blanks', 'build a ViterbiDecoder instance from a target dictionary to decode speech recognition emissions', 'get predicted tokens from a single emission tensor by applying argmax and unique consecutive filtering', 'review the ViterbiDecoder decode method that returns token predictions with score zero for each emission', 'summarize the ViterbiDecoder class that extends BaseDecoder for CTC-based speech recognition decoding']
```

Usage

```
{'generate_speech_recognition_output': 'generate speech recognition output from a list of fairseq models and a sample input', 'get_emissions_from_encoder': 'get emissions as log probabilities from a fairseq model encoder output', 'get_tokens_from_indices': 'get deduplicated token indices by removing consecutive duplicates and blank tokens', 'review_basedecoder_class': 'review the BaseDecoder class and its abstract decode method for speech recognition', 'summarize_basedecoder_init': 'summarize the BaseDecoder init method that sets up blank and silence tokens from a dictionary'}
```

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/new/decoders/decoder.py

Prompts

```
['generate speech recognition output from a list of fairseq models and a sample input', 'get emissions as log probabilities from a fairseq model encoder output', 'get deduplicated token indices by removing consecutive duplicates and blank tokens', 'review the BaseDecoder class and its abstract decode method for speech recognition', 'summarize the BaseDecoder init method that sets up blank and silence tokens from a dictionary', 'create a ViterbiDecoder by calling Decoder with cfg type set to viterbi and a target dictionary', 'create a KenLMDecoder by calling Decoder with cfg type set to kenlm and a target dictionary', 'create a FairseqLMDecoder by calling Decoder with cfg type set to fairseqlm and a target dictionary', 'review the Decoder factory function that dispatches to ViterbiDecoder, KenLMDecoder, or FairseqLMDecoder based on config type', 'summarize the DecoderConfig dataclass that defines the decoder type choice enum with options viterbi, kenlm, and fairseqlm', 'build a KenLMDecoder with a flashlight config and target dictionary for CTC beam search decoding', 'decode CTC emissions tensor using the KenLMDecoder to get n-best hypothesis results with tokens and scores', 'build a FairseqLM language model wrapper from a fairseq model and dictionary for flashlight integration', 'score a token against the current FairseqLM state and return a new LMState with its log probability', 'build a FairseqLMDecoder using a fairseq checkpoint as the language model for CTC beam search decoding', 'decode CTC emissions tensor to predicted token sequences by taking argmax and removing blanks', 'build a ViterbiDecoder instance from a target dictionary to decode speech recognition emissions', 'get predicted tokens from a single emission tensor by applying argmax and unique consecutive filtering', 'review the ViterbiDecoder decode method that returns token predictions with score zero for each emission', 'summarize the ViterbiDecoder class that extends BaseDecoder for CTC-based speech recognition decoding']
```

Usage

```
{'create_viterbi_decoder': 'create a ViterbiDecoder by calling Decoder with cfg type set to viterbi and a target dictionary', 'create_kenlm_decoder': 'create a KenLMDecoder by calling Decoder with cfg type set to kenlm and a target dictionary', 'create_fairseqlm_decoder': 'create a FairseqLMDecoder by calling Decoder with cfg type set to fairseqlm and a target dictionary', 'review_Decoder_factory': 'review the Decoder factory function that dispatches to ViterbiDecoder, KenLMDecoder, or FairseqLMDecoder based on config type', 'summarize_DecoderConfig': 'summarize the DecoderConfig dataclass that defines the decoder type choice enum with options viterbi, kenlm, and fairseqlm'}
```

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/new/decoders/flashlight_decoder.py

Prompts

```
['generate speech recognition output from a list of fairseq models and a sample input', 'get emissions as log probabilities from a fairseq model encoder output', 'get deduplicated token indices by removing consecutive duplicates and blank tokens', 'review the BaseDecoder class and its abstract decode method for speech recognition', 'summarize the BaseDecoder init method that sets up blank and silence tokens from a dictionary', 'create a ViterbiDecoder by calling Decoder with cfg type set to viterbi and a target dictionary', 'create a KenLMDecoder by calling Decoder with cfg type set to kenlm and a target dictionary', 'create a FairseqLMDecoder by calling Decoder with cfg type set to fairseqlm and a target dictionary', 'review the Decoder factory function that dispatches to ViterbiDecoder, KenLMDecoder, or FairseqLMDecoder based on config type', 'summarize the DecoderConfig dataclass that defines the decoder type choice enum with options viterbi, kenlm, and fairseqlm', 'build a KenLMDecoder with a flashlight config and target dictionary for CTC beam search decoding', 'decode CTC emissions tensor using the KenLMDecoder to get n-best hypothesis results with tokens and scores', 'build a FairseqLM language model wrapper from a fairseq model and dictionary for flashlight integration', 'score a token against the current FairseqLM state and return a new LMState with its log probability', 'build a FairseqLMDecoder using a fairseq checkpoint as the language model for CTC beam search decoding', 'decode CTC emissions tensor to predicted token sequences by taking argmax and removing blanks', 'build a ViterbiDecoder instance from a target dictionary to decode speech recognition emissions', 'get predicted tokens from a single emission tensor by applying argmax and unique consecutive filtering', 'review the ViterbiDecoder decode method that returns token predictions with score zero for each emission', 'summarize the ViterbiDecoder class that extends BaseDecoder for CTC-based speech recognition decoding']
```

Usage

```
{'build_KenLMDecoder': 'build a KenLMDecoder with a flashlight config and target dictionary for CTC beam search decoding', 'decode_KenLMDecoder': 'decode CTC emissions tensor using the KenLMDecoder to get n-best hypothesis results with tokens and scores', 'build_FairseqLM': 'build a FairseqLM language model wrapper from a fairseq model and dictionary for flashlight integration', 'score_FairseqLM': 'score a token against the current FairseqLM state and return a new LMState with its log probability', 'build_FairseqLMDecoder': 'build a FairseqLMDecoder using a fairseq checkpoint as the language model for CTC beam search decoding'}
```

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/new/decoders/viterbi_decoder.py

Prompts

```
['generate speech recognition output from a list of fairseq models and a sample input', 'get emissions as log probabilities from a fairseq model encoder output', 'get deduplicated token indices by removing consecutive duplicates and blank tokens', 'review the BaseDecoder class and its abstract decode method for speech recognition', 'summarize the BaseDecoder init method that sets up blank and silence tokens from a dictionary', 'create a ViterbiDecoder by calling Decoder with cfg type set to viterbi and a target dictionary', 'create a KenLMDecoder by calling Decoder with cfg type set to kenlm and a target dictionary', 'create a FairseqLMDecoder by calling Decoder with cfg type set to fairseqlm and a target dictionary', 'review the Decoder factory function that dispatches to ViterbiDecoder, KenLMDecoder, or FairseqLMDecoder based on config type', 'summarize the DecoderConfig dataclass that defines the decoder type choice enum with options viterbi, kenlm, and fairseqlm', 'build a KenLMDecoder with a flashlight config and target dictionary for CTC beam search decoding', 'decode CTC emissions tensor using the KenLMDecoder to get n-best hypothesis results with tokens and scores', 'build a FairseqLM language model wrapper from a fairseq model and dictionary for flashlight integration', 'score a token against the current FairseqLM state and return a new LMState with its log probability', 'build a FairseqLMDecoder using a fairseq checkpoint as the language model for CTC beam search decoding', 'decode CTC emissions tensor to predicted token sequences by taking argmax and removing blanks', 'build a ViterbiDecoder instance from a target dictionary to decode speech recognition emissions', 'get predicted tokens from a single emission tensor by applying argmax and unique consecutive filtering', 'review the ViterbiDecoder decode method that returns token predictions with score zero for each emission', 'summarize the ViterbiDecoder class that extends BaseDecoder for CTC-based speech recognition decoding']
```

Usage

```
{'decode_emissions_to_tokens': 'decode CTC emissions tensor to predicted token sequences by taking argmax and removing blanks', 'build_viterbi_decoder': 'build a ViterbiDecoder instance from a target dictionary to decode speech recognition emissions', 'get_pred_from_emissions': 'get predicted tokens from a single emission tensor by applying argmax and unique consecutive filtering', 'review_viterbi_decode': 'review the ViterbiDecoder decode method that returns token predictions with score zero for each emission', 'summarize_viterbi_decoder': 'summarize the ViterbiDecoder class that extends BaseDecoder for CTC-based speech recognition decoding'}
```

