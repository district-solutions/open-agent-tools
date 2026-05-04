# Agent Python Tools

- repo: facebookresearch/2.5d-visual-sound
- repo_uri: https://github.com/facebookresearch/2.5d-visual-sound

## File: facebookresearch_2.5d-visual-sound/data/audioVisual_dataset.py

Prompts

```
['normalize audio samples to a desired RMS level using numpy', 'generate a two-channel spectrogram from audio using librosa STFT with real and imaginary components', 'process an image by resizing, random cropping, and optional brightness and color augmentation', 'initialize the AudioVisualDataset by loading audio paths from an HDF5 file and setting up vision transforms', 'get a dataset item containing a frame tensor, audio difference spectrogram, and audio mix spectrogram', 'review the BaseDataset class which extends torch.utils.data.Dataset as a base for PyTorch datasets', 'review the BaseDataset name method that returns the string BaseDataset as the dataset identifier', 'review the BaseDataset initialize method which accepts an opt parameter and serves as a subclass hook', 'review the BaseDataset init method that calls super to initialize the parent torch.utils.data.Dataset class', 'summarize the BaseDataset class a minimal PyTorch Dataset base class with name and initialize stub methods', 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual', 'initialize a CustomDatasetDataLoader with opt to create a PyTorch DataLoader for the audioVisual dataset', 'load data by calling load_data on CustomDatasetDataLoader to return the dataloader instance', 'iterate over dataset batches using the CustomDatasetDataLoader iterator to yield batched data', 'get the total number of samples in the dataset by calling len on CustomDatasetDataLoader', 'create a data loader by calling CreateDataLoader with an opt configuration object', 'initialize the CustomDatasetDataLoader with opt settings including batchSize and nThreads', 'load audiovisual dataset batches by iterating over the returned data loader', 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual']
```

Usage

```
{'normalize_audio_samples': 'normalize audio samples to a desired RMS level using numpy', 'generate_spectrogram_from_audio': 'generate a two-channel spectrogram from audio using librosa STFT with real and imaginary components', 'process_image_with_augmentation': 'process an image by resizing, random cropping, and optional brightness and color augmentation', 'initialize_audiovisual_dataset': 'initialize the AudioVisualDataset by loading audio paths from an HDF5 file and setting up vision transforms', 'get_audiovisual_dataset_item': 'get a dataset item containing a frame tensor, audio difference spectrogram, and audio mix spectrogram'}
```

## File: facebookresearch_2.5d-visual-sound/data/base_dataset.py

Prompts

```
['normalize audio samples to a desired RMS level using numpy', 'generate a two-channel spectrogram from audio using librosa STFT with real and imaginary components', 'process an image by resizing, random cropping, and optional brightness and color augmentation', 'initialize the AudioVisualDataset by loading audio paths from an HDF5 file and setting up vision transforms', 'get a dataset item containing a frame tensor, audio difference spectrogram, and audio mix spectrogram', 'review the BaseDataset class which extends torch.utils.data.Dataset as a base for PyTorch datasets', 'review the BaseDataset name method that returns the string BaseDataset as the dataset identifier', 'review the BaseDataset initialize method which accepts an opt parameter and serves as a subclass hook', 'review the BaseDataset init method that calls super to initialize the parent torch.utils.data.Dataset class', 'summarize the BaseDataset class a minimal PyTorch Dataset base class with name and initialize stub methods', 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual', 'initialize a CustomDatasetDataLoader with opt to create a PyTorch DataLoader for the audioVisual dataset', 'load data by calling load_data on CustomDatasetDataLoader to return the dataloader instance', 'iterate over dataset batches using the CustomDatasetDataLoader iterator to yield batched data', 'get the total number of samples in the dataset by calling len on CustomDatasetDataLoader', 'create a data loader by calling CreateDataLoader with an opt configuration object', 'initialize the CustomDatasetDataLoader with opt settings including batchSize and nThreads', 'load audiovisual dataset batches by iterating over the returned data loader', 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual']
```

Usage

```
{'review_Basedataset_class': 'review the BaseDataset class which extends torch.utils.data.Dataset as a base for PyTorch datasets', 'review_Basedataset_name_method': 'review the BaseDataset name method that returns the string BaseDataset as the dataset identifier', 'review_Basedataset_initialize_method': 'review the BaseDataset initialize method which accepts an opt parameter and serves as a subclass hook', 'review_Basedataset_init_method': 'review the BaseDataset init method that calls super to initialize the parent torch.utils.data.Dataset class', 'summarize_Basedataset_class': 'summarize the BaseDataset class a minimal PyTorch Dataset base class with name and initialize stub methods'}
```

## File: facebookresearch_2.5d-visual-sound/data/custom_dataset_data_loader.py

Prompts

```
['normalize audio samples to a desired RMS level using numpy', 'generate a two-channel spectrogram from audio using librosa STFT with real and imaginary components', 'process an image by resizing, random cropping, and optional brightness and color augmentation', 'initialize the AudioVisualDataset by loading audio paths from an HDF5 file and setting up vision transforms', 'get a dataset item containing a frame tensor, audio difference spectrogram, and audio mix spectrogram', 'review the BaseDataset class which extends torch.utils.data.Dataset as a base for PyTorch datasets', 'review the BaseDataset name method that returns the string BaseDataset as the dataset identifier', 'review the BaseDataset initialize method which accepts an opt parameter and serves as a subclass hook', 'review the BaseDataset init method that calls super to initialize the parent torch.utils.data.Dataset class', 'summarize the BaseDataset class a minimal PyTorch Dataset base class with name and initialize stub methods', 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual', 'initialize a CustomDatasetDataLoader with opt to create a PyTorch DataLoader for the audioVisual dataset', 'load data by calling load_data on CustomDatasetDataLoader to return the dataloader instance', 'iterate over dataset batches using the CustomDatasetDataLoader iterator to yield batched data', 'get the total number of samples in the dataset by calling len on CustomDatasetDataLoader', 'create a data loader by calling CreateDataLoader with an opt configuration object', 'initialize the CustomDatasetDataLoader with opt settings including batchSize and nThreads', 'load audiovisual dataset batches by iterating over the returned data loader', 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual']
```

Usage

```
{'create_dataset_audiovisual': 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual', 'initialize_custom_dataloader': 'initialize a CustomDatasetDataLoader with opt to create a PyTorch DataLoader for the audioVisual dataset', 'load_data_dataloader': 'load data by calling load_data on CustomDatasetDataLoader to return the dataloader instance', 'iterate_dataset_batches': 'iterate over dataset batches using the CustomDatasetDataLoader iterator to yield batched data', 'get_dataset_length': 'get the total number of samples in the dataset by calling len on CustomDatasetDataLoader'}
```

## File: facebookresearch_2.5d-visual-sound/data/data_loader.py

Prompts

```
['normalize audio samples to a desired RMS level using numpy', 'generate a two-channel spectrogram from audio using librosa STFT with real and imaginary components', 'process an image by resizing, random cropping, and optional brightness and color augmentation', 'initialize the AudioVisualDataset by loading audio paths from an HDF5 file and setting up vision transforms', 'get a dataset item containing a frame tensor, audio difference spectrogram, and audio mix spectrogram', 'review the BaseDataset class which extends torch.utils.data.Dataset as a base for PyTorch datasets', 'review the BaseDataset name method that returns the string BaseDataset as the dataset identifier', 'review the BaseDataset initialize method which accepts an opt parameter and serves as a subclass hook', 'review the BaseDataset init method that calls super to initialize the parent torch.utils.data.Dataset class', 'summarize the BaseDataset class a minimal PyTorch Dataset base class with name and initialize stub methods', 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual', 'initialize a CustomDatasetDataLoader with opt to create a PyTorch DataLoader for the audioVisual dataset', 'load data by calling load_data on CustomDatasetDataLoader to return the dataloader instance', 'iterate over dataset batches using the CustomDatasetDataLoader iterator to yield batched data', 'get the total number of samples in the dataset by calling len on CustomDatasetDataLoader', 'create a data loader by calling CreateDataLoader with an opt configuration object', 'initialize the CustomDatasetDataLoader with opt settings including batchSize and nThreads', 'load audiovisual dataset batches by iterating over the returned data loader', 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual']
```

Usage

```
{'create_dataloader': 'create a data loader by calling CreateDataLoader with an opt configuration object', 'initialize_dataloader': 'initialize the CustomDatasetDataLoader with opt settings including batchSize and nThreads', 'load_audiovisual_data': 'load audiovisual dataset batches by iterating over the returned data loader', 'get_dataset_length': 'get the total number of samples in the dataset using len on the data loader', 'create_dataset': 'create an AudioVisualDataset by calling CreateDataset with opt.model set to audioVisual'}
```

