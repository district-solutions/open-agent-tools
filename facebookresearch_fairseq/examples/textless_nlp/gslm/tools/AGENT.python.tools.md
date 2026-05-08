# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/textless_nlp/gslm/tools/resynthesize_speech.py

Prompts

```
['run the GSLM U2S tool to resynthesize speech from an audio file using acoustic features, K-means quantization, Tacotron TTS, and Waveglow vocoder', 'run the main resynthesis loop that extracts features, quantizes units, and synthesizes audio from input to output file paths', 'run get_parser to build an argparse parser for the GSLM U2S tool with acoustic model, TTS, and Waveglow arguments', 'run get_logger to create a configured logging instance with timestamp and level formatting for the GSLM tool', 'run the full speech resynthesis pipeline extracting features with Hubert/W2V2/CPC, quantizing with K-means, and synthesizing with Tacotron and Waveglow']
```

Usage

```
{'run_resynthesize_speech': 'run the GSLM U2S tool to resynthesize speech from an audio file using acoustic features, K-means quantization, Tacotron TTS, and Waveglow vocoder', 'run_main_resynthesis_loop': 'run the main resynthesis loop that extracts features, quantizes units, and synthesizes audio from input to output file paths', 'run_get_parser': 'run get_parser to build an argparse parser for the GSLM U2S tool with acoustic model, TTS, and Waveglow arguments', 'run_get_logger': 'run get_logger to create a configured logging instance with timestamp and level formatting for the GSLM tool', 'run_synthesize_audio_pipeline': 'run the full speech resynthesis pipeline extracting features with Hubert/W2V2/CPC, quantizing with K-means, and synthesizing with Tacotron and Waveglow'}
```

