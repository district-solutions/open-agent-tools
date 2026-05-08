# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/textless_nlp/dgslm/vocoder_hifigan/generate_stereo_waveform.py

Prompts

```
['run the vocoder to generate stereo waveform WAV files from discrete speech codes', 'load a CodeHiFiGANVocoder model from a checkpoint path and config JSON file', 'convert discrete speech codes into a waveform tensor using the loaded vocoder', 'write a predicted waveform tensor to a WAV file using soundfile', 'load and parse an input file of discrete speech code samples line by line']
```

Usage

```
{'generate_stereo_waveform': 'run the vocoder to generate stereo waveform WAV files from discrete speech codes', 'load_vocoder': 'load a CodeHiFiGANVocoder model from a checkpoint path and config JSON file', 'code2wav': 'convert discrete speech codes into a waveform tensor using the loaded vocoder', 'dump_result': 'write a predicted waveform tensor to a WAV file using soundfile', 'load_data': 'load and parse an input file of discrete speech code samples line by line'}
```

