# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_recognition/new/decoders/base_decoder.py

Prompts

```
['generate speech recognition output by running models on encoder input and decoding emissions', 'get emissions from a fairseq model by calling get_logits or get_normalized_probs on encoder output', 'get tokens from a sequence of indices by deduplicating consecutive values and filtering blanks', 'review the BaseDecoder class and its methods for CTC-based speech recognition decoding', 'summarize the BaseDecoder init method that sets up blank and silence tokens from the target dictionary', 'create a ViterbiDecoder instance by calling Decoder with a viterbi config and target dictionary', 'create a KenLMDecoder instance by calling Decoder with a kenlm config and target dictionary', 'create a FairseqLMDecoder instance by calling Decoder with a fairseqlm config and target dictionary', 'review the Decoder factory function that returns a BaseDecoder based on config type', 'summarize the Decoder factory function that supports viterbi, kenlm, and fairseqlm decoder types', 'build a KenLMDecoder with a lexicon and KenLM for CTC beam search decoding', 'decode audio emissions using KenLMDecoder to get n-best hypotheses with tokens and words', 'build a FairseqLM wrapper around a FairseqModel for language model scoring during decoding', 'score a token given the current LM state and return the new state and log probability', 'build a FairseqLMDecoder that uses a Fairseq model as the language model for speech decoding', 'decode CTC emission probabilities into token sequences using Viterbi greedy decoding', 'compute the sum of max log-softmax scores from emission probabilities for each timestep', 'extract unique consecutive token predictions from emission argmax results', 'filter out CTC blank tokens from the predicted token sequence', 'review the ViterbiDecoder decode method and its CTC greedy decoding logic']
```

Usage

```
{'generate_decoder_output': 'generate speech recognition output by running models on encoder input and decoding emissions', 'get_emissions_from_model': 'get emissions from a fairseq model by calling get_logits or get_normalized_probs on encoder output', 'get_tokens_from_indices': 'get tokens from a sequence of indices by deduplicating consecutive values and filtering blanks', 'review_basedecoder_class': 'review the BaseDecoder class and its methods for CTC-based speech recognition decoding', 'summarize_basedecoder_init': 'summarize the BaseDecoder init method that sets up blank and silence tokens from the target dictionary'}
```

## File: facebookresearch_fairseq/examples/speech_recognition/new/decoders/decoder.py

Prompts

```
['generate speech recognition output by running models on encoder input and decoding emissions', 'get emissions from a fairseq model by calling get_logits or get_normalized_probs on encoder output', 'get tokens from a sequence of indices by deduplicating consecutive values and filtering blanks', 'review the BaseDecoder class and its methods for CTC-based speech recognition decoding', 'summarize the BaseDecoder init method that sets up blank and silence tokens from the target dictionary', 'create a ViterbiDecoder instance by calling Decoder with a viterbi config and target dictionary', 'create a KenLMDecoder instance by calling Decoder with a kenlm config and target dictionary', 'create a FairseqLMDecoder instance by calling Decoder with a fairseqlm config and target dictionary', 'review the Decoder factory function that returns a BaseDecoder based on config type', 'summarize the Decoder factory function that supports viterbi, kenlm, and fairseqlm decoder types', 'build a KenLMDecoder with a lexicon and KenLM for CTC beam search decoding', 'decode audio emissions using KenLMDecoder to get n-best hypotheses with tokens and words', 'build a FairseqLM wrapper around a FairseqModel for language model scoring during decoding', 'score a token given the current LM state and return the new state and log probability', 'build a FairseqLMDecoder that uses a Fairseq model as the language model for speech decoding', 'decode CTC emission probabilities into token sequences using Viterbi greedy decoding', 'compute the sum of max log-softmax scores from emission probabilities for each timestep', 'extract unique consecutive token predictions from emission argmax results', 'filter out CTC blank tokens from the predicted token sequence', 'review the ViterbiDecoder decode method and its CTC greedy decoding logic']
```

Usage

```
{'create_viterbi_decoder': 'create a ViterbiDecoder instance by calling Decoder with a viterbi config and target dictionary', 'create_kenlm_decoder': 'create a KenLMDecoder instance by calling Decoder with a kenlm config and target dictionary', 'create_fairseqlm_decoder': 'create a FairseqLMDecoder instance by calling Decoder with a fairseqlm config and target dictionary', 'review_Decoder_factory': 'review the Decoder factory function that returns a BaseDecoder based on config type', 'summarize_Decoder': 'summarize the Decoder factory function that supports viterbi, kenlm, and fairseqlm decoder types'}
```

## File: facebookresearch_fairseq/examples/speech_recognition/new/decoders/flashlight_decoder.py

Prompts

```
['generate speech recognition output by running models on encoder input and decoding emissions', 'get emissions from a fairseq model by calling get_logits or get_normalized_probs on encoder output', 'get tokens from a sequence of indices by deduplicating consecutive values and filtering blanks', 'review the BaseDecoder class and its methods for CTC-based speech recognition decoding', 'summarize the BaseDecoder init method that sets up blank and silence tokens from the target dictionary', 'create a ViterbiDecoder instance by calling Decoder with a viterbi config and target dictionary', 'create a KenLMDecoder instance by calling Decoder with a kenlm config and target dictionary', 'create a FairseqLMDecoder instance by calling Decoder with a fairseqlm config and target dictionary', 'review the Decoder factory function that returns a BaseDecoder based on config type', 'summarize the Decoder factory function that supports viterbi, kenlm, and fairseqlm decoder types', 'build a KenLMDecoder with a lexicon and KenLM for CTC beam search decoding', 'decode audio emissions using KenLMDecoder to get n-best hypotheses with tokens and words', 'build a FairseqLM wrapper around a FairseqModel for language model scoring during decoding', 'score a token given the current LM state and return the new state and log probability', 'build a FairseqLMDecoder that uses a Fairseq model as the language model for speech decoding', 'decode CTC emission probabilities into token sequences using Viterbi greedy decoding', 'compute the sum of max log-softmax scores from emission probabilities for each timestep', 'extract unique consecutive token predictions from emission argmax results', 'filter out CTC blank tokens from the predicted token sequence', 'review the ViterbiDecoder decode method and its CTC greedy decoding logic']
```

Usage

```
{'build_KenLMDecoder': 'build a KenLMDecoder with a lexicon and KenLM for CTC beam search decoding', 'decode_KenLMDecoder': 'decode audio emissions using KenLMDecoder to get n-best hypotheses with tokens and words', 'build_FairseqLM': 'build a FairseqLM wrapper around a FairseqModel for language model scoring during decoding', 'score_FairseqLM': 'score a token given the current LM state and return the new state and log probability', 'build_FairseqLMDecoder': 'build a FairseqLMDecoder that uses a Fairseq model as the language model for speech decoding'}
```

## File: facebookresearch_fairseq/examples/speech_recognition/new/decoders/viterbi_decoder.py

Prompts

```
['generate speech recognition output by running models on encoder input and decoding emissions', 'get emissions from a fairseq model by calling get_logits or get_normalized_probs on encoder output', 'get tokens from a sequence of indices by deduplicating consecutive values and filtering blanks', 'review the BaseDecoder class and its methods for CTC-based speech recognition decoding', 'summarize the BaseDecoder init method that sets up blank and silence tokens from the target dictionary', 'create a ViterbiDecoder instance by calling Decoder with a viterbi config and target dictionary', 'create a KenLMDecoder instance by calling Decoder with a kenlm config and target dictionary', 'create a FairseqLMDecoder instance by calling Decoder with a fairseqlm config and target dictionary', 'review the Decoder factory function that returns a BaseDecoder based on config type', 'summarize the Decoder factory function that supports viterbi, kenlm, and fairseqlm decoder types', 'build a KenLMDecoder with a lexicon and KenLM for CTC beam search decoding', 'decode audio emissions using KenLMDecoder to get n-best hypotheses with tokens and words', 'build a FairseqLM wrapper around a FairseqModel for language model scoring during decoding', 'score a token given the current LM state and return the new state and log probability', 'build a FairseqLMDecoder that uses a Fairseq model as the language model for speech decoding', 'decode CTC emission probabilities into token sequences using Viterbi greedy decoding', 'compute the sum of max log-softmax scores from emission probabilities for each timestep', 'extract unique consecutive token predictions from emission argmax results', 'filter out CTC blank tokens from the predicted token sequence', 'review the ViterbiDecoder decode method and its CTC greedy decoding logic']
```

Usage

```
{'decode_ctc_emissions': 'decode CTC emission probabilities into token sequences using Viterbi greedy decoding', 'compute_log_softmax_score': 'compute the sum of max log-softmax scores from emission probabilities for each timestep', 'extract_unique_consecutive_tokens': 'extract unique consecutive token predictions from emission argmax results', 'filter_blank_tokens': 'filter out CTC blank tokens from the predicted token sequence', 'review_ViterbiDecoder_decode': 'review the ViterbiDecoder decode method and its CTC greedy decoding logic'}
```

