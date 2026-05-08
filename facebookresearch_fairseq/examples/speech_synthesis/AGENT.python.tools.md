# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_synthesis/data_utils.py

Prompts

```
['extract a log-mel spectrogram from a waveform tensor and optionally save it to a numpy file', 'extract pitch contour from a waveform using PyWORLD dio and stonemask with optional phoneme duration alignment', 'extract energy features from a waveform using STFT magnitude and optionally align to phoneme durations', 'compute global cepstral mean and variance normalization statistics from a directory of numpy feature files', 'get Montreal Forced Aligner phone-level alignment info from a TextGrid zip file for a list of sample IDs', 'run a fairseq TTS model to generate audio waveforms from text input and save as wav files', 'run the TTS generation script with --dump-features to save predicted mel-spectrogram features as numpy arrays', 'run the TTS generation script with --dump-attentions to save attention weight matrices for each sample', 'run the TTS generation script with --dump-plots to generate alignment and output visualization PNG images', 'run postprocess_results to extract sample IDs, attention, EOS probabilities, features, and waveforms from generator hypotheses', 'compute the mel spectral distortion between two batches of audio waveforms using log-mel spectrograms', 'compute the gross pitch error rate between ground truth and estimated F0 pitch contours', 'compute the F0 frame error rate combining gross pitch errors and voicing decision errors', 'compute the voicing decision error rate between ground truth and estimated F0 pitch contours', 'review the pitch evaluation metric functions for gross pitch error, F0 frame error, and voicing decision error']
```

Usage

```
{'extract_logmel_spectrogram': 'extract a log-mel spectrogram from a waveform tensor and optionally save it to a numpy file', 'extract_pitch': 'extract pitch contour from a waveform using PyWORLD dio and stonemask with optional phoneme duration alignment', 'extract_energy': 'extract energy features from a waveform using STFT magnitude and optionally align to phoneme durations', 'get_global_cmvn': 'compute global cepstral mean and variance normalization statistics from a directory of numpy feature files', 'get_mfa_alignment': 'get Montreal Forced Aligner phone-level alignment info from a TextGrid zip file for a list of sample IDs'}
```

## File: facebookresearch_fairseq/examples/speech_synthesis/generate_waveform.py

Prompts

```
['extract a log-mel spectrogram from a waveform tensor and optionally save it to a numpy file', 'extract pitch contour from a waveform using PyWORLD dio and stonemask with optional phoneme duration alignment', 'extract energy features from a waveform using STFT magnitude and optionally align to phoneme durations', 'compute global cepstral mean and variance normalization statistics from a directory of numpy feature files', 'get Montreal Forced Aligner phone-level alignment info from a TextGrid zip file for a list of sample IDs', 'run a fairseq TTS model to generate audio waveforms from text input and save as wav files', 'run the TTS generation script with --dump-features to save predicted mel-spectrogram features as numpy arrays', 'run the TTS generation script with --dump-attentions to save attention weight matrices for each sample', 'run the TTS generation script with --dump-plots to generate alignment and output visualization PNG images', 'run postprocess_results to extract sample IDs, attention, EOS probabilities, features, and waveforms from generator hypotheses', 'compute the mel spectral distortion between two batches of audio waveforms using log-mel spectrograms', 'compute the gross pitch error rate between ground truth and estimated F0 pitch contours', 'compute the F0 frame error rate combining gross pitch errors and voicing decision errors', 'compute the voicing decision error rate between ground truth and estimated F0 pitch contours', 'review the pitch evaluation metric functions for gross pitch error, F0 frame error, and voicing decision error']
```

Usage

```
{'generate_waveforms_from_tts_model': 'run a fairseq TTS model to generate audio waveforms from text input and save as wav files', 'dump_tts_features': 'run the TTS generation script with --dump-features to save predicted mel-spectrogram features as numpy arrays', 'dump_tts_attentions': 'run the TTS generation script with --dump-attentions to save attention weight matrices for each sample', 'dump_tts_plots': 'run the TTS generation script with --dump-plots to generate alignment and output visualization PNG images', 'postprocess_tts_results': 'run postprocess_results to extract sample IDs, attention, EOS probabilities, features, and waveforms from generator hypotheses'}
```

## File: facebookresearch_fairseq/examples/speech_synthesis/utils.py

Prompts

```
['extract a log-mel spectrogram from a waveform tensor and optionally save it to a numpy file', 'extract pitch contour from a waveform using PyWORLD dio and stonemask with optional phoneme duration alignment', 'extract energy features from a waveform using STFT magnitude and optionally align to phoneme durations', 'compute global cepstral mean and variance normalization statistics from a directory of numpy feature files', 'get Montreal Forced Aligner phone-level alignment info from a TextGrid zip file for a list of sample IDs', 'run a fairseq TTS model to generate audio waveforms from text input and save as wav files', 'run the TTS generation script with --dump-features to save predicted mel-spectrogram features as numpy arrays', 'run the TTS generation script with --dump-attentions to save attention weight matrices for each sample', 'run the TTS generation script with --dump-plots to generate alignment and output visualization PNG images', 'run postprocess_results to extract sample IDs, attention, EOS probabilities, features, and waveforms from generator hypotheses', 'compute the mel spectral distortion between two batches of audio waveforms using log-mel spectrograms', 'compute the gross pitch error rate between ground truth and estimated F0 pitch contours', 'compute the F0 frame error rate combining gross pitch errors and voicing decision errors', 'compute the voicing decision error rate between ground truth and estimated F0 pitch contours', 'review the pitch evaluation metric functions for gross pitch error, F0 frame error, and voicing decision error']
```

Usage

```
{'compute_batch_mel_spectral_distortion': 'compute the mel spectral distortion between two batches of audio waveforms using log-mel spectrograms', 'compute_gross_pitch_error': 'compute the gross pitch error rate between ground truth and estimated F0 pitch contours', 'compute_f0_frame_error': 'compute the F0 frame error rate combining gross pitch errors and voicing decision errors', 'compute_voicing_decision_error': 'compute the voicing decision error rate between ground truth and estimated F0 pitch contours', 'review_pitch_evaluation_metrics': 'review the pitch evaluation metric functions for gross pitch error, F0 frame error, and voicing decision error'}
```

