# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/signal_processing/synthetic/generators/noise_generator.py

Prompts

```
['create a NoiseChannelConfig dataclass with amplitudes, offsets, and sample_rate for noise generation', 'build a NoiseGenerator instance that produces uniformly distributed random noise on each channel', 'run the next_sample method to generate a FunctionGeneratorMessage with random noise data', 'review the NoiseChannelConfig __post_init__ validation that asserts shape consistency across amplitudes and offsets', 'summarize the NoiseGenerator class that generates random noise samples with configurable amplitude, offset, and sample rate', 'create a SineWaveChannelConfig with amplitude, frequency, phase shift, midline arrays and sample rate', 'create a SineWaveGenerator instance initialized with a SineWaveChannelConfig for multi-channel sinusoid generation', 'call next_sample on a SineWaveGenerator to produce the next FunctionGeneratorMessage with sinusoid values', 'review the SineWaveChannelConfig post-init validation that asserts matching array shapes and positive sample rate', 'refactor the SineWaveGenerator to use a different time tracking approach instead of incrementing by inverse sample rate']
```

Usage

```
{'create_NoiseChannelConfig': 'create a NoiseChannelConfig dataclass with amplitudes, offsets, and sample_rate for noise generation', 'build_NoiseGenerator': 'build a NoiseGenerator instance that produces uniformly distributed random noise on each channel', 'run_next_sample': 'run the next_sample method to generate a FunctionGeneratorMessage with random noise data', 'review_NoiseChannelConfig_post_init': 'review the NoiseChannelConfig __post_init__ validation that asserts shape consistency across amplitudes and offsets', 'summarize_NoiseGenerator': 'summarize the NoiseGenerator class that generates random noise samples with configurable amplitude, offset, and sample rate'}
```

## File: facebookresearch_labgraph/signal_processing/synthetic/generators/sine_wave_generator.py

Prompts

```
['create a NoiseChannelConfig dataclass with amplitudes, offsets, and sample_rate for noise generation', 'build a NoiseGenerator instance that produces uniformly distributed random noise on each channel', 'run the next_sample method to generate a FunctionGeneratorMessage with random noise data', 'review the NoiseChannelConfig __post_init__ validation that asserts shape consistency across amplitudes and offsets', 'summarize the NoiseGenerator class that generates random noise samples with configurable amplitude, offset, and sample rate', 'create a SineWaveChannelConfig with amplitude, frequency, phase shift, midline arrays and sample rate', 'create a SineWaveGenerator instance initialized with a SineWaveChannelConfig for multi-channel sinusoid generation', 'call next_sample on a SineWaveGenerator to produce the next FunctionGeneratorMessage with sinusoid values', 'review the SineWaveChannelConfig post-init validation that asserts matching array shapes and positive sample rate', 'refactor the SineWaveGenerator to use a different time tracking approach instead of incrementing by inverse sample rate']
```

Usage

```
{'create_sine_wave_channel_config': 'create a SineWaveChannelConfig with amplitude, frequency, phase shift, midline arrays and sample rate', 'create_sine_wave_generator': 'create a SineWaveGenerator instance initialized with a SineWaveChannelConfig for multi-channel sinusoid generation', 'generate_next_sample': 'call next_sample on a SineWaveGenerator to produce the next FunctionGeneratorMessage with sinusoid values', 'review_sine_wave_channel_config_validation': 'review the SineWaveChannelConfig post-init validation that asserts matching array shapes and positive sample rate', 'refactor_sine_wave_generator_time_tracking': 'refactor the SineWaveGenerator to use a different time tracking approach instead of incrementing by inverse sample rate'}
```

