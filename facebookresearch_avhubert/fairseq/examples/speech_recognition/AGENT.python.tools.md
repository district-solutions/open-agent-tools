# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/infer.py

Prompts

```
['run speech recognition inference on pre-processed data with a trained fairseq model', 'run ASR inference using the viterbi w2l decoder for speech recognition', 'dump model emissions to a numpy file for later offline decoding', 'dump encoder features from the model to a numpy file for analysis', 'run ASR inference using pre-saved emissions loaded from a numpy file', 'build a W2lViterbiDecoder to decode CTC emissions using CPU Viterbi path search', 'build a W2lKenLMDecoder with a KenLM and optional lexicon for beam search decoding', 'build a W2lFairseqLMDecoder that uses a fairseq model as the language model for decoding', 'review the FairseqLM score method to evaluate language model probability for a given token', 'review the W2lDecoder get_tokens method to normalize tokens by removing CTC blanks and duplicates']
```

Usage

```
{'run_asr_inference': 'run speech recognition inference on pre-processed data with a trained fairseq model', 'run_inference_with_viterbi_decoder': 'run ASR inference using the viterbi w2l decoder for speech recognition', 'dump_model_emissions': 'dump model emissions to a numpy file for later offline decoding', 'dump_model_features': 'dump encoder features from the model to a numpy file for analysis', 'run_inference_with_loaded_emissions': 'run ASR inference using pre-saved emissions loaded from a numpy file'}
```

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/w2l_decoder.py

Prompts

```
['run speech recognition inference on pre-processed data with a trained fairseq model', 'run ASR inference using the viterbi w2l decoder for speech recognition', 'dump model emissions to a numpy file for later offline decoding', 'dump encoder features from the model to a numpy file for analysis', 'run ASR inference using pre-saved emissions loaded from a numpy file', 'build a W2lViterbiDecoder to decode CTC emissions using CPU Viterbi path search', 'build a W2lKenLMDecoder with a KenLM and optional lexicon for beam search decoding', 'build a W2lFairseqLMDecoder that uses a fairseq model as the language model for decoding', 'review the FairseqLM score method to evaluate language model probability for a given token', 'review the W2lDecoder get_tokens method to normalize tokens by removing CTC blanks and duplicates']
```

Usage

```
{'build_W2lViterbiDecoder': 'build a W2lViterbiDecoder to decode CTC emissions using CPU Viterbi path search', 'build_W2lKenLMDecoder': 'build a W2lKenLMDecoder with a KenLM and optional lexicon for beam search decoding', 'build_W2lFairseqLMDecoder': 'build a W2lFairseqLMDecoder that uses a fairseq model as the language model for decoding', 'review_FairseqLM_score': 'review the FairseqLM score method to evaluate language model probability for a given token', 'review_W2lDecoder_get_tokens': 'review the W2lDecoder get_tokens method to normalize tokens by removing CTC blanks and duplicates'}
```

