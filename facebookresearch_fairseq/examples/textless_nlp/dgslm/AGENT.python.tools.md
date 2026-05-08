# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/textless_nlp/dgslm/dgslm_utils.py

Prompts

```
['use HubertTokenizer to convert a WAV audio file path into discrete speech unit codes', 'use HubertTokenizer to extract speech unit codes from both channels of a stereo WAV file', 'use HifiganVocoder to synthesize a WAV audio waveform from a sequence of discrete speech codes', 'use HifiganVocoder to synthesize a stereo WAV waveform from two sets of speech codes with speaker IDs', 'initialize a HubertTokenizer with a HuBERT model path, layer index, and k-means cluster path', 'run the SpeechDLM model to generate speech unit sequences from an input file with a checkpoint', 'run the SpeechDLM model with beam search to generate speech unit sequences from input data', 'run the SpeechDLM model with top-k and top-p sampling to generate speech unit sequences', 'review the load_data function that reads a file and parses each line with ast.literal_eval', 'review the write_data function that writes a list of dictionaries to a file line by line']
```

Usage

```
{'wav2code_HubertTokenizer': 'use HubertTokenizer to convert a WAV audio file path into discrete speech unit codes', 'wav2codes_HubertTokenizer': 'use HubertTokenizer to extract speech unit codes from both channels of a stereo WAV file', 'code2wav_HifiganVocoder': 'use HifiganVocoder to synthesize a WAV audio waveform from a sequence of discrete speech codes', 'codes2wav_HifiganVocoder': 'use HifiganVocoder to synthesize a stereo WAV waveform from two sets of speech codes with speaker IDs', 'init_HubertTokenizer': 'initialize a HubertTokenizer with a HuBERT model path, layer index, and k-means cluster path'}
```

## File: facebookresearch_fairseq/examples/textless_nlp/dgslm/sample_speech_dlm.py

Prompts

```
['use HubertTokenizer to convert a WAV audio file path into discrete speech unit codes', 'use HubertTokenizer to extract speech unit codes from both channels of a stereo WAV file', 'use HifiganVocoder to synthesize a WAV audio waveform from a sequence of discrete speech codes', 'use HifiganVocoder to synthesize a stereo WAV waveform from two sets of speech codes with speaker IDs', 'initialize a HubertTokenizer with a HuBERT model path, layer index, and k-means cluster path', 'run the SpeechDLM model to generate speech unit sequences from an input file with a checkpoint', 'run the SpeechDLM model with beam search to generate speech unit sequences from input data', 'run the SpeechDLM model with top-k and top-p sampling to generate speech unit sequences', 'review the load_data function that reads a file and parses each line with ast.literal_eval', 'review the write_data function that writes a list of dictionaries to a file line by line']
```

Usage

```
{'run_sample_speech_dlm': 'run the SpeechDLM model to generate speech unit sequences from an input file with a checkpoint', 'run_sample_speech_dlm_beam_search': 'run the SpeechDLM model with beam search to generate speech unit sequences from input data', 'run_sample_speech_dlm_sampling': 'run the SpeechDLM model with top-k and top-p sampling to generate speech unit sequences', 'review_load_data': 'review the load_data function that reads a file and parses each line with ast.literal_eval', 'review_write_data': 'review the write_data function that writes a list of dictionaries to a file line by line'}
```

