# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_synthesis/evaluation/eval_asr.py

Prompts

```
['run the ASR evaluation pipeline on a raw manifest using a wav2vec checkpoint and compute error rates', 'prepare wav2vec data files by copying the dictionary, writing TSV audio paths, and preprocessing text labels', 'run ASR inference via subprocess using a wav2vec checkpoint with viterbi decoder and CTC criterion', 'compute word or character error rates by comparing hypothesis and reference text files using edit distance', 'preprocess text by uppercasing, removing non-alphabetic characters, and joining tokens with spaces', 'run the eval_f0 CLI to compute gross pitch error, voicing decision error, and F0 frame error on speech synthesis samples', 'compute fundamental frequency and harmonic rate from an audio signal using the Yin pitch detection algorithm', 'extract F0 contours from pairs of reference and synthesized speech waveform files using Yin', 'evaluate gross pitch error between reference and synthesized speech F0 contours', 'evaluate voicing decision error between reference and synthesized speech F0 contours', 'run the eval_sp CLI with --mcd to evaluate mean cepstral distortion on a TSV eval spec file', 'run the eval_sp CLI with --msd to evaluate mean spectral distortion on a TSV eval spec file', 'run the eval_sp CLI with --show-bin to print binned distortion results by reference frame count', 'load a tab-separated evaluation spec CSV file into a list of sample dictionaries with ref and syn paths', 'evaluate waveform distortion between reference and synthetic audio samples using a custom distortion function']
```

Usage

```
{'run_asr_evaluation': 'run the ASR evaluation pipeline on a raw manifest using a wav2vec checkpoint and compute error rates', 'prepare_w2v_data': 'prepare wav2vec data files by copying the dictionary, writing TSV audio paths, and preprocessing text labels', 'run_asr_inference': 'run ASR inference via subprocess using a wav2vec checkpoint with viterbi decoder and CTC criterion', 'compute_error_rate': 'compute word or character error rates by comparing hypothesis and reference text files using edit distance', 'preprocess_text': 'preprocess text by uppercasing, removing non-alphabetic characters, and joining tokens with spaces'}
```

## File: facebookresearch_fairseq/examples/speech_synthesis/evaluation/eval_f0.py

Prompts

```
['run the ASR evaluation pipeline on a raw manifest using a wav2vec checkpoint and compute error rates', 'prepare wav2vec data files by copying the dictionary, writing TSV audio paths, and preprocessing text labels', 'run ASR inference via subprocess using a wav2vec checkpoint with viterbi decoder and CTC criterion', 'compute word or character error rates by comparing hypothesis and reference text files using edit distance', 'preprocess text by uppercasing, removing non-alphabetic characters, and joining tokens with spaces', 'run the eval_f0 CLI to compute gross pitch error, voicing decision error, and F0 frame error on speech synthesis samples', 'compute fundamental frequency and harmonic rate from an audio signal using the Yin pitch detection algorithm', 'extract F0 contours from pairs of reference and synthesized speech waveform files using Yin', 'evaluate gross pitch error between reference and synthesized speech F0 contours', 'evaluate voicing decision error between reference and synthesized speech F0 contours', 'run the eval_sp CLI with --mcd to evaluate mean cepstral distortion on a TSV eval spec file', 'run the eval_sp CLI with --msd to evaluate mean spectral distortion on a TSV eval spec file', 'run the eval_sp CLI with --show-bin to print binned distortion results by reference frame count', 'load a tab-separated evaluation spec CSV file into a list of sample dictionaries with ref and syn paths', 'evaluate waveform distortion between reference and synthetic audio samples using a custom distortion function']
```

Usage

```
{'run_eval_f0_cli': 'run the eval_f0 CLI to compute gross pitch error, voicing decision error, and F0 frame error on speech synthesis samples', 'compute_yin_f0': 'compute fundamental frequency and harmonic rate from an audio signal using the Yin pitch detection algorithm', 'extract_f0_from_waveforms': 'extract F0 contours from pairs of reference and synthesized speech waveform files using Yin', 'eval_gross_pitch_error': 'evaluate gross pitch error between reference and synthesized speech F0 contours', 'eval_voicing_decision_error': 'evaluate voicing decision error between reference and synthesized speech F0 contours'}
```

## File: facebookresearch_fairseq/examples/speech_synthesis/evaluation/eval_sp.py

Prompts

```
['run the ASR evaluation pipeline on a raw manifest using a wav2vec checkpoint and compute error rates', 'prepare wav2vec data files by copying the dictionary, writing TSV audio paths, and preprocessing text labels', 'run ASR inference via subprocess using a wav2vec checkpoint with viterbi decoder and CTC criterion', 'compute word or character error rates by comparing hypothesis and reference text files using edit distance', 'preprocess text by uppercasing, removing non-alphabetic characters, and joining tokens with spaces', 'run the eval_f0 CLI to compute gross pitch error, voicing decision error, and F0 frame error on speech synthesis samples', 'compute fundamental frequency and harmonic rate from an audio signal using the Yin pitch detection algorithm', 'extract F0 contours from pairs of reference and synthesized speech waveform files using Yin', 'evaluate gross pitch error between reference and synthesized speech F0 contours', 'evaluate voicing decision error between reference and synthesized speech F0 contours', 'run the eval_sp CLI with --mcd to evaluate mean cepstral distortion on a TSV eval spec file', 'run the eval_sp CLI with --msd to evaluate mean spectral distortion on a TSV eval spec file', 'run the eval_sp CLI with --show-bin to print binned distortion results by reference frame count', 'load a tab-separated evaluation spec CSV file into a list of sample dictionaries with ref and syn paths', 'evaluate waveform distortion between reference and synthetic audio samples using a custom distortion function']
```

Usage

```
{'run_eval_mcd': 'run the eval_sp CLI with --mcd to evaluate mean cepstral distortion on a TSV eval spec file', 'run_eval_msd': 'run the eval_sp CLI with --msd to evaluate mean spectral distortion on a TSV eval spec file', 'run_eval_with_bins': 'run the eval_sp CLI with --show-bin to print binned distortion results by reference frame count', 'load_eval_spec': 'load a tab-separated evaluation spec CSV file into a list of sample dictionaries with ref and syn paths', 'eval_distortion': 'evaluate waveform distortion between reference and synthetic audio samples using a custom distortion function'}
```

