# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/speech_recognition/infer.py

Prompts

```
['run speech recognition inference on pre-processed data with a trained fairseq model', 'run the infer CLI to decode speech audio using a fairseq ASR model checkpoint', 'run inference to dump model emissions to a numpy file for offline decoding', 'run inference to dump encoder features from the model for external processing', 'run speech recognition using a viterbi, kenlm, or fairseqlm w2l decoder', 'build a W2lViterbiDecoder to decode CTC emissions using the CpuViterbiPath algorithm for speech recognition', 'build a W2lKenLMDecoder with a KenLM language model and lexicon trie for beam search decoding', 'build a W2lFairseqLMDecoder that uses a FairseqLM model for language model assisted speech decoding', 'review the FairseqLM score method to understand how it evaluates tokens and manages incremental state caching', 'refactor the W2lDecoder get_tokens method to handle CTC blank filtering and ASG replabel unpacking']
```

Usage

```
{'run_asr_inference': 'run speech recognition inference on pre-processed data with a trained fairseq model', 'run_infer_cli': 'run the infer CLI to decode speech audio using a fairseq ASR model checkpoint', 'run_dump_emissions': 'run inference to dump model emissions to a numpy file for offline decoding', 'run_dump_features': 'run inference to dump encoder features from the model for external processing', 'run_w2l_decoder': 'run speech recognition using a viterbi, kenlm, or fairseqlm w2l decoder'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/speech_recognition/w2l_decoder.py

Prompts

```
['run speech recognition inference on pre-processed data with a trained fairseq model', 'run the infer CLI to decode speech audio using a fairseq ASR model checkpoint', 'run inference to dump model emissions to a numpy file for offline decoding', 'run inference to dump encoder features from the model for external processing', 'run speech recognition using a viterbi, kenlm, or fairseqlm w2l decoder', 'build a W2lViterbiDecoder to decode CTC emissions using the CpuViterbiPath algorithm for speech recognition', 'build a W2lKenLMDecoder with a KenLM language model and lexicon trie for beam search decoding', 'build a W2lFairseqLMDecoder that uses a FairseqLM model for language model assisted speech decoding', 'review the FairseqLM score method to understand how it evaluates tokens and manages incremental state caching', 'refactor the W2lDecoder get_tokens method to handle CTC blank filtering and ASG replabel unpacking']
```

Usage

```
{'build_W2lViterbiDecoder': 'build a W2lViterbiDecoder to decode CTC emissions using the CpuViterbiPath algorithm for speech recognition', 'build_W2lKenLMDecoder': 'build a W2lKenLMDecoder with a KenLM language model and lexicon trie for beam search decoding', 'build_W2lFairseqLMDecoder': 'build a W2lFairseqLMDecoder that uses a FairseqLM model for language model assisted speech decoding', 'review_FairseqLM_score': 'review the FairseqLM score method to understand how it evaluates tokens and manages incremental state caching', 'refactor_W2lDecoder_get_tokens': 'refactor the W2lDecoder get_tokens method to handle CTC blank filtering and ASG replabel unpacking'}
```

