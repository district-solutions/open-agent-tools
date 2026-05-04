# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/kaldi/kaldi_decoder.py

Prompts

```
['build a KaldiDecoder instance with a config, beam size, and optional nbest count for speech recognition', 'run the KaldiDecoder generate method to decode a batch of audio samples using fairseq models', 'run get_emissions on a KaldiDecoder to extract normalized log-probability emissions from encoder models', "run decode_one on a KaldiDecoder to decode a single utterance's logits into words using Kaldi FST", 'run decode on a KaldiDecoder to submit a batch of emissions for parallel decoding via ThreadPoolExecutor', 'run the kaldi initializer CLI to build HLG FST graphs for speech recognition decoding', 'create a Kaldi input units file from a Fairseq Dictionary vocabulary', 'create a Kaldi lexicon file with disambiguation symbols from wav2letter or identity mapping', 'create the final HLG FST graph by composing H, L, and G graphs for CTC decoding', 'create the H FST graph mapping output symbols to input labels with blank and silence handling']
```

Usage

```
{'build_KaldiDecoder': 'build a KaldiDecoder instance with a config, beam size, and optional nbest count for speech recognition', 'run_KaldiDecoder_generate': 'run the KaldiDecoder generate method to decode a batch of audio samples using fairseq models', 'run_KaldiDecoder_get_emissions': 'run get_emissions on a KaldiDecoder to extract normalized log-probability emissions from encoder models', 'run_KaldiDecoder_decode_one': "run decode_one on a KaldiDecoder to decode a single utterance's logits into words using Kaldi FST", 'run_KaldiDecoder_decode': 'run decode on a KaldiDecoder to submit a batch of emissions for parallel decoding via ThreadPoolExecutor'}
```

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/kaldi/kaldi_initializer.py

Prompts

```
['build a KaldiDecoder instance with a config, beam size, and optional nbest count for speech recognition', 'run the KaldiDecoder generate method to decode a batch of audio samples using fairseq models', 'run get_emissions on a KaldiDecoder to extract normalized log-probability emissions from encoder models', "run decode_one on a KaldiDecoder to decode a single utterance's logits into words using Kaldi FST", 'run decode on a KaldiDecoder to submit a batch of emissions for parallel decoding via ThreadPoolExecutor', 'run the kaldi initializer CLI to build HLG FST graphs for speech recognition decoding', 'create a Kaldi input units file from a Fairseq Dictionary vocabulary', 'create a Kaldi lexicon file with disambiguation symbols from wav2letter or identity mapping', 'create the final HLG FST graph by composing H, L, and G graphs for CTC decoding', 'create the H FST graph mapping output symbols to input labels with blank and silence handling']
```

Usage

```
{'run_kaldi_initializer_cli': 'run the kaldi initializer CLI to build HLG FST graphs for speech recognition decoding', 'create_units_from_vocab': 'create a Kaldi input units file from a Fairseq Dictionary vocabulary', 'create_lexicon_with_disambig': 'create a Kaldi lexicon file with disambiguation symbols from wav2letter or identity mapping', 'create_HLG_graph': 'create the final HLG FST graph by composing H, L, and G graphs for CTC decoding', 'create_H_graph': 'create the H FST graph mapping output symbols to input labels with blank and silence handling'}
```

