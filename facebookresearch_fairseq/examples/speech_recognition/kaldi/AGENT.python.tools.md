# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_recognition/kaldi/kaldi_decoder.py

Prompts

```
['create a KaldiDecoderConfig dataclass to configure beam search, lattice decoding, and acoustic scale options', 'build a KaldiDecoder instance with a config, beam width, and optional nbest results for speech recognition', 'run the KaldiDecoder generate method to produce batch inferences from a fairseq model and sample input', 'run the decode_one method to decode single utterance logits into words using Kaldi FST and pykaldi recognizer', 'run the decode method to submit batch emissions for parallel decoding across multiple threads', 'create a Kaldi HLG decoding graph from an ARPA language model and fairseq vocabulary using the initalize_kaldi function', 'create a Kaldi dictionary units file from a fairseq Dictionary vocabulary using the create_units function', 'create a Kaldi lexicon file with disambiguation symbols from a wav2letter lexicon or unit file using create_lexicon', 'create a Kaldi grammar graph FST from an ARPA language model file using the create_G function', 'create a CTC-style HMM graph FST with blank and silence symbols using the create_H function']
```

Usage

```
{'create_KaldiDecoderConfig': 'create a KaldiDecoderConfig dataclass to configure beam search, lattice decoding, and acoustic scale options', 'build_KaldiDecoder': 'build a KaldiDecoder instance with a config, beam width, and optional nbest results for speech recognition', 'run_KaldiDecoder_generate': 'run the KaldiDecoder generate method to produce batch inferences from a fairseq model and sample input', 'run_KaldiDecoder_decode_one': 'run the decode_one method to decode single utterance logits into words using Kaldi FST and pykaldi recognizer', 'run_KaldiDecoder_decode': 'run the decode method to submit batch emissions for parallel decoding across multiple threads'}
```

## File: facebookresearch_fairseq/examples/speech_recognition/kaldi/kaldi_initializer.py

Prompts

```
['create a KaldiDecoderConfig dataclass to configure beam search, lattice decoding, and acoustic scale options', 'build a KaldiDecoder instance with a config, beam width, and optional nbest results for speech recognition', 'run the KaldiDecoder generate method to produce batch inferences from a fairseq model and sample input', 'run the decode_one method to decode single utterance logits into words using Kaldi FST and pykaldi recognizer', 'run the decode method to submit batch emissions for parallel decoding across multiple threads', 'create a Kaldi HLG decoding graph from an ARPA language model and fairseq vocabulary using the initalize_kaldi function', 'create a Kaldi dictionary units file from a fairseq Dictionary vocabulary using the create_units function', 'create a Kaldi lexicon file with disambiguation symbols from a wav2letter lexicon or unit file using create_lexicon', 'create a Kaldi grammar graph FST from an ARPA language model file using the create_G function', 'create a CTC-style HMM graph FST with blank and silence symbols using the create_H function']
```

Usage

```
{'create_kaldi_hlg_graph': 'create a Kaldi HLG decoding graph from an ARPA language model and fairseq vocabulary using the initalize_kaldi function', 'create_units_from_vocab': 'create a Kaldi dictionary units file from a fairseq Dictionary vocabulary using the create_units function', 'create_lexicon_with_disambig': 'create a Kaldi lexicon file with disambiguation symbols from a wav2letter lexicon or unit file using create_lexicon', 'create_grammar_graph': 'create a Kaldi grammar graph FST from an ARPA language model file using the create_G function', 'create_hmm_graph': 'create a CTC-style HMM graph FST with blank and silence symbols using the create_H function'}
```

