# Agent Python Tools

- repo: facebookresearch/flowdec
- repo_uri: https://github.com/facebookresearch/flowdec

## File: facebookresearch_flowdec/flowdec/util/hydra.py

Prompts

```
['instantiate a PyTorch Lightning model, datamodule, and optimizer from a Hydra config', 'convert a Hydra config into a loggable dictionary with W&B compatible list formatting', 'recursively convert all lists of dictionaries in a config to a dictionary of dictionaries', 'review the instantiate_core_objects function to understand how it creates model and datamodule instances', 'refactor the get_loggable_cfg function to customize the W&B list fix workaround behavior', 'load an audio file from a path and resample it to 48kHz using torchaudio', 'pad a spectrogram tensor to a multiple of 64 along the time dimension with reflection padding', 'normalize noisy audio tensors by their maximum absolute value to prevent NaN values', 'compute the mean and confidence interval of a NumPy array using scipy statistics', 'detect whether an audio file is music, sound, or speech based on its filename prefix', 'create a new Registry instance to manage SDE, Predictor, or Corrector subclasses by string key', 'use the register decorator to register a subclass under a unique name in the Registry', 'retrieve a registered class from the Registry by its unique string name', 'get a list of all registered names currently stored in the Registry', 'review the Registry class and its register, get_by_name, and get_all_names methods', 'plot a spectrogram from a complex STFT tensor using log normalization on a matplotlib axis', 'compute the short-time Fourier transform of an audio tensor with configurable window and hop parameters', 'display an audio tensor as a spectrogram plot with time and frequency axis labels', 'play back an audio tensor as an IPython Audio widget in a Jupyter notebook', 'map a complex numpy array to RGBA values encoding phase as hue and amplitude as brightness']
```

Usage

```
{'instantiate_core_objects': 'instantiate a PyTorch Lightning model, datamodule, and optimizer from a Hydra config', 'get_loggable_cfg': 'convert a Hydra config into a loggable dictionary with W&B compatible list formatting', 'convert_list_of_dicts': 'recursively convert all lists of dictionaries in a config to a dictionary of dictionaries', 'review_instantiate_core_objects': 'review the instantiate_core_objects function to understand how it creates model and datamodule instances', 'refactor_get_loggable_cfg': 'refactor the get_loggable_cfg function to customize the W&B list fix workaround behavior'}
```

## File: facebookresearch_flowdec/flowdec/util/other.py

Prompts

```
['instantiate a PyTorch Lightning model, datamodule, and optimizer from a Hydra config', 'convert a Hydra config into a loggable dictionary with W&B compatible list formatting', 'recursively convert all lists of dictionaries in a config to a dictionary of dictionaries', 'review the instantiate_core_objects function to understand how it creates model and datamodule instances', 'refactor the get_loggable_cfg function to customize the W&B list fix workaround behavior', 'load an audio file from a path and resample it to 48kHz using torchaudio', 'pad a spectrogram tensor to a multiple of 64 along the time dimension with reflection padding', 'normalize noisy audio tensors by their maximum absolute value to prevent NaN values', 'compute the mean and confidence interval of a NumPy array using scipy statistics', 'detect whether an audio file is music, sound, or speech based on its filename prefix', 'create a new Registry instance to manage SDE, Predictor, or Corrector subclasses by string key', 'use the register decorator to register a subclass under a unique name in the Registry', 'retrieve a registered class from the Registry by its unique string name', 'get a list of all registered names currently stored in the Registry', 'review the Registry class and its register, get_by_name, and get_all_names methods', 'plot a spectrogram from a complex STFT tensor using log normalization on a matplotlib axis', 'compute the short-time Fourier transform of an audio tensor with configurable window and hop parameters', 'display an audio tensor as a spectrogram plot with time and frequency axis labels', 'play back an audio tensor as an IPython Audio widget in a Jupyter notebook', 'map a complex numpy array to RGBA values encoding phase as hue and amplitude as brightness']
```

Usage

```
{'load_audio_to_48khz': 'load an audio file from a path and resample it to 48kHz using torchaudio', 'pad_spectrogram': 'pad a spectrogram tensor to a multiple of 64 along the time dimension with reflection padding', 'normalize_noisy_audio': 'normalize noisy audio tensors by their maximum absolute value to prevent NaN values', 'compute_mean_confidence_interval': 'compute the mean and confidence interval of a NumPy array using scipy statistics', 'detect_audio_type_from_filename': 'detect whether an audio file is music, sound, or speech based on its filename prefix'}
```

## File: facebookresearch_flowdec/flowdec/util/registry.py

Prompts

```
['instantiate a PyTorch Lightning model, datamodule, and optimizer from a Hydra config', 'convert a Hydra config into a loggable dictionary with W&B compatible list formatting', 'recursively convert all lists of dictionaries in a config to a dictionary of dictionaries', 'review the instantiate_core_objects function to understand how it creates model and datamodule instances', 'refactor the get_loggable_cfg function to customize the W&B list fix workaround behavior', 'load an audio file from a path and resample it to 48kHz using torchaudio', 'pad a spectrogram tensor to a multiple of 64 along the time dimension with reflection padding', 'normalize noisy audio tensors by their maximum absolute value to prevent NaN values', 'compute the mean and confidence interval of a NumPy array using scipy statistics', 'detect whether an audio file is music, sound, or speech based on its filename prefix', 'create a new Registry instance to manage SDE, Predictor, or Corrector subclasses by string key', 'use the register decorator to register a subclass under a unique name in the Registry', 'retrieve a registered class from the Registry by its unique string name', 'get a list of all registered names currently stored in the Registry', 'review the Registry class and its register, get_by_name, and get_all_names methods', 'plot a spectrogram from a complex STFT tensor using log normalization on a matplotlib axis', 'compute the short-time Fourier transform of an audio tensor with configurable window and hop parameters', 'display an audio tensor as a spectrogram plot with time and frequency axis labels', 'play back an audio tensor as an IPython Audio widget in a Jupyter notebook', 'map a complex numpy array to RGBA values encoding phase as hue and amplitude as brightness']
```

Usage

```
{'create_registry': 'create a new Registry instance to manage SDE, Predictor, or Corrector subclasses by string key', 'register_class': 'use the register decorator to register a subclass under a unique name in the Registry', 'get_by_name': 'retrieve a registered class from the Registry by its unique string name', 'get_all_names': 'get a list of all registered names currently stored in the Registry', 'review_registry_class': 'review the Registry class and its register, get_by_name, and get_all_names methods'}
```

## File: facebookresearch_flowdec/flowdec/util/viz.py

Prompts

```
['instantiate a PyTorch Lightning model, datamodule, and optimizer from a Hydra config', 'convert a Hydra config into a loggable dictionary with W&B compatible list formatting', 'recursively convert all lists of dictionaries in a config to a dictionary of dictionaries', 'review the instantiate_core_objects function to understand how it creates model and datamodule instances', 'refactor the get_loggable_cfg function to customize the W&B list fix workaround behavior', 'load an audio file from a path and resample it to 48kHz using torchaudio', 'pad a spectrogram tensor to a multiple of 64 along the time dimension with reflection padding', 'normalize noisy audio tensors by their maximum absolute value to prevent NaN values', 'compute the mean and confidence interval of a NumPy array using scipy statistics', 'detect whether an audio file is music, sound, or speech based on its filename prefix', 'create a new Registry instance to manage SDE, Predictor, or Corrector subclasses by string key', 'use the register decorator to register a subclass under a unique name in the Registry', 'retrieve a registered class from the Registry by its unique string name', 'get a list of all registered names currently stored in the Registry', 'review the Registry class and its register, get_by_name, and get_all_names methods', 'plot a spectrogram from a complex STFT tensor using log normalization on a matplotlib axis', 'compute the short-time Fourier transform of an audio tensor with configurable window and hop parameters', 'display an audio tensor as a spectrogram plot with time and frequency axis labels', 'play back an audio tensor as an IPython Audio widget in a Jupyter notebook', 'map a complex numpy array to RGBA values encoding phase as hue and amplitude as brightness']
```

Usage

```
{'plot_spec_spectrogram': 'plot a spectrogram from a complex STFT tensor using log normalization on a matplotlib axis', 'get_spec_stft': 'compute the short-time Fourier transform of an audio tensor with configurable window and hop parameters', 'show_as_spec_audio': 'display an audio tensor as a spectrogram plot with time and frequency axis labels', 'show_as_audio_playback': 'play back an audio tensor as an IPython Audio widget in a Jupyter notebook', 'ccmap_img_complex_rgba': 'map a complex numpy array to RGBA values encoding phase as hue and amplitude as brightness'}
```

