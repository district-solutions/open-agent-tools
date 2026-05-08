# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_recognition/infer.py

Prompts

```
['run speech recognition inference on pre-processed audio data with a trained fairseq model', 'run ASR inference using a viterbi, kenlm, or fairseqlm w2l decoder for decoding', 'dump model emissions to a numpy file for later offline decoding with load-emissions', 'dump encoder features from the model to a numpy file for external analysis', 'process hypothesis predictions against target tokens and compute edit distance for WER', 'build a W2lViterbiDecoder to decode CTC emissions using CPU Viterbi path search', 'build a W2lKenLMDecoder with a KenLM and optional lexicon for beam search decoding', 'build a W2lFairseqLMDecoder that uses a fairseq model as the language model for decoding', 'review the FairseqLM score method to evaluate language model scores for a given token and state', 'refactor the W2lDecoder get_tokens method to normalize tokens by removing CTC blanks and duplicates']
```

Usage

```
{'run_asr_inference': 'run speech recognition inference on pre-processed audio data with a trained fairseq model', 'run_inference_with_w2l_decoder': 'run ASR inference using a viterbi, kenlm, or fairseqlm w2l decoder for decoding', 'dump_model_emissions': 'dump model emissions to a numpy file for later offline decoding with load-emissions', 'dump_encoder_features': 'dump encoder features from the model to a numpy file for external analysis', 'process_asr_predictions': 'process hypothesis predictions against target tokens and compute edit distance for WER'}
```

## File: facebookresearch_fairseq/examples/speech_recognition/w2l_decoder.py

Prompts

```
['run speech recognition inference on pre-processed audio data with a trained fairseq model', 'run ASR inference using a viterbi, kenlm, or fairseqlm w2l decoder for decoding', 'dump model emissions to a numpy file for later offline decoding with load-emissions', 'dump encoder features from the model to a numpy file for external analysis', 'process hypothesis predictions against target tokens and compute edit distance for WER', 'build a W2lViterbiDecoder to decode CTC emissions using CPU Viterbi path search', 'build a W2lKenLMDecoder with a KenLM and optional lexicon for beam search decoding', 'build a W2lFairseqLMDecoder that uses a fairseq model as the language model for decoding', 'review the FairseqLM score method to evaluate language model scores for a given token and state', 'refactor the W2lDecoder get_tokens method to normalize tokens by removing CTC blanks and duplicates']
```

Usage

```
{'build_W2lViterbiDecoder': 'build a W2lViterbiDecoder to decode CTC emissions using CPU Viterbi path search', 'build_W2lKenLMDecoder': 'build a W2lKenLMDecoder with a KenLM and optional lexicon for beam search decoding', 'build_W2lFairseqLMDecoder': 'build a W2lFairseqLMDecoder that uses a fairseq model as the language model for decoding', 'review_FairseqLM_score': 'review the FairseqLM score method to evaluate language model scores for a given token and state', 'refactor_W2lDecoder_get_tokens': 'refactor the W2lDecoder get_tokens method to normalize tokens by removing CTC blanks and duplicates'}
```

