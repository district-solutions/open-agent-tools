# Agent Python Tools

- repo: facebookresearch/audioseal
- repo_uri: https://github.com/facebookresearch/audioseal

## File: facebookresearch_audioseal/examples/attacks.py

Prompts

```
['apply a random speed change to a batch of audio tensors using AudioEffects.speed', 'apply an echo effect with configurable volume and duration to audio tensors using AudioEffects.echo', 'apply a bandpass filter to audio waveforms using AudioEffects.bandpass_filter with configurable cutoff frequencies', 'add pink background noise to audio waveforms using AudioEffects.pink_noise with configurable noise standard deviation', 'generate a normalized pink noise tensor of a given length using the Voss-McCartney algorithm', 'plot a waveform and spectrogram from a PyTorch audio tensor with a given sample rate and title', 'play a mono or stereo audio waveform tensor in a Jupyter notebook using IPython display', 'review the plot_waveform_and_specgram function that visualizes audio waveforms and spectrograms using matplotlib', 'review the play_audio function that plays mono or stereo audio tensors via IPython display', 'refactor the play_audio function to support more than two audio channels']
```

Usage

```
{'apply_speed_change': 'apply a random speed change to a batch of audio tensors using AudioEffects.speed', 'apply_echo_effect': 'apply an echo effect with configurable volume and duration to audio tensors using AudioEffects.echo', 'apply_bandpass_filter': 'apply a bandpass filter to audio waveforms using AudioEffects.bandpass_filter with configurable cutoff frequencies', 'add_pink_noise': 'add pink background noise to audio waveforms using AudioEffects.pink_noise with configurable noise standard deviation', 'generate_pink_noise_tensor': 'generate a normalized pink noise tensor of a given length using the Voss-McCartney algorithm'}
```

## File: facebookresearch_audioseal/examples/notebook.py

Prompts

```
['apply a random speed change to a batch of audio tensors using AudioEffects.speed', 'apply an echo effect with configurable volume and duration to audio tensors using AudioEffects.echo', 'apply a bandpass filter to audio waveforms using AudioEffects.bandpass_filter with configurable cutoff frequencies', 'add pink background noise to audio waveforms using AudioEffects.pink_noise with configurable noise standard deviation', 'generate a normalized pink noise tensor of a given length using the Voss-McCartney algorithm', 'plot a waveform and spectrogram from a PyTorch audio tensor with a given sample rate and title', 'play a mono or stereo audio waveform tensor in a Jupyter notebook using IPython display', 'review the plot_waveform_and_specgram function that visualizes audio waveforms and spectrograms using matplotlib', 'review the play_audio function that plays mono or stereo audio tensors via IPython display', 'refactor the play_audio function to support more than two audio channels']
```

Usage

```
{'plot_waveform_and_specgram': 'plot a waveform and spectrogram from a PyTorch audio tensor with a given sample rate and title', 'play_audio': 'play a mono or stereo audio waveform tensor in a Jupyter notebook using IPython display', 'review_plot_waveform_and_specgram': 'review the plot_waveform_and_specgram function that visualizes audio waveforms and spectrograms using matplotlib', 'review_play_audio': 'review the play_audio function that plays mono or stereo audio tensors via IPython display', 'refactor_play_audio': 'refactor the play_audio function to support more than two audio channels'}
```

