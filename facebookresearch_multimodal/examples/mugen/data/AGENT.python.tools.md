# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/mugen/data/audio_utils.py

Prompts

```
['load audio from a media file at a given sample rate with offset and duration', 'load and resample audio from a file to stereo float32 at a target sample rate', 'load audio from a file using approximate offset when the requested range exceeds file duration', 'load audio from a file using seconds as the time base for offset and duration', 'load audio from a file without resampling when the file sample rate matches the target rate', 'create a MUGENDataModule with dataset args and optional text, video, and audio transforms', 'build a training dataloader for the MUGEN dataset using MUGENDataModule train_dataloader method', 'build a validation dataloader for the MUGEN dataset using MUGENDataModule val_dataloader method', 'build a test dataloader for the MUGEN dataset using MUGENDataModule test_dataloader method', 'review the _custom_collate_fn method that stacks video, text, and audio batches with transforms', 'create a MUGENDatasetArgs dataclass to configure dataset paths, resolution, and annotation settings', 'build a PyTorch Dataset that loads MUGEN game video, audio, and text data from JSON metadata', 'review the MUGENDataset __getitem__ method to understand how video, audio, and text are returned per sample', 'test the MUGENDataset get_game_video method to render game frames as a tensor sequence', 'summarize the MUGENDataset init_game_assets method that loads theme-specific game assets and semantic color maps', 'convert a grayscale label tensor to a color tensor using the label color map', 'review the label color map dictionary that maps integer labels to RGB color tensors', 'refactor convert_grayscale_to_color_label to use vectorized indexing instead of a Python loop', 'test convert_grayscale_to_color_label with a sample batch tensor of shape B T H W', 'summarize the label color map containing 23 RGB color entries for segmentation labels']
```

Usage

```
{'load_audio_from_file': 'load audio from a media file at a given sample rate with offset and duration', 'load_audio_with_resampling': 'load and resample audio from a file to stereo float32 at a target sample rate', 'load_audio_with_approx_offset': 'load audio from a file using approximate offset when the requested range exceeds file duration', 'load_audio_seconds_timebase': 'load audio from a file using seconds as the time base for offset and duration', 'load_audio_without_resampling': 'load audio from a file without resampling when the file sample rate matches the target rate'}
```

## File: facebookresearch_multimodal/examples/mugen/data/mugen_datamodules.py

Prompts

```
['load audio from a media file at a given sample rate with offset and duration', 'load and resample audio from a file to stereo float32 at a target sample rate', 'load audio from a file using approximate offset when the requested range exceeds file duration', 'load audio from a file using seconds as the time base for offset and duration', 'load audio from a file without resampling when the file sample rate matches the target rate', 'create a MUGENDataModule with dataset args and optional text, video, and audio transforms', 'build a training dataloader for the MUGEN dataset using MUGENDataModule train_dataloader method', 'build a validation dataloader for the MUGEN dataset using MUGENDataModule val_dataloader method', 'build a test dataloader for the MUGEN dataset using MUGENDataModule test_dataloader method', 'review the _custom_collate_fn method that stacks video, text, and audio batches with transforms', 'create a MUGENDatasetArgs dataclass to configure dataset paths, resolution, and annotation settings', 'build a PyTorch Dataset that loads MUGEN game video, audio, and text data from JSON metadata', 'review the MUGENDataset __getitem__ method to understand how video, audio, and text are returned per sample', 'test the MUGENDataset get_game_video method to render game frames as a tensor sequence', 'summarize the MUGENDataset init_game_assets method that loads theme-specific game assets and semantic color maps', 'convert a grayscale label tensor to a color tensor using the label color map', 'review the label color map dictionary that maps integer labels to RGB color tensors', 'refactor convert_grayscale_to_color_label to use vectorized indexing instead of a Python loop', 'test convert_grayscale_to_color_label with a sample batch tensor of shape B T H W', 'summarize the label color map containing 23 RGB color entries for segmentation labels']
```

Usage

```
{'create_MUGENDataModule': 'create a MUGENDataModule with dataset args and optional text, video, and audio transforms', 'build_train_dataloader': 'build a training dataloader for the MUGEN dataset using MUGENDataModule train_dataloader method', 'build_val_dataloader': 'build a validation dataloader for the MUGEN dataset using MUGENDataModule val_dataloader method', 'build_test_dataloader': 'build a test dataloader for the MUGEN dataset using MUGENDataModule test_dataloader method', 'review_custom_collate_fn': 'review the _custom_collate_fn method that stacks video, text, and audio batches with transforms'}
```

## File: facebookresearch_multimodal/examples/mugen/data/mugen_dataset.py

Prompts

```
['load audio from a media file at a given sample rate with offset and duration', 'load and resample audio from a file to stereo float32 at a target sample rate', 'load audio from a file using approximate offset when the requested range exceeds file duration', 'load audio from a file using seconds as the time base for offset and duration', 'load audio from a file without resampling when the file sample rate matches the target rate', 'create a MUGENDataModule with dataset args and optional text, video, and audio transforms', 'build a training dataloader for the MUGEN dataset using MUGENDataModule train_dataloader method', 'build a validation dataloader for the MUGEN dataset using MUGENDataModule val_dataloader method', 'build a test dataloader for the MUGEN dataset using MUGENDataModule test_dataloader method', 'review the _custom_collate_fn method that stacks video, text, and audio batches with transforms', 'create a MUGENDatasetArgs dataclass to configure dataset paths, resolution, and annotation settings', 'build a PyTorch Dataset that loads MUGEN game video, audio, and text data from JSON metadata', 'review the MUGENDataset __getitem__ method to understand how video, audio, and text are returned per sample', 'test the MUGENDataset get_game_video method to render game frames as a tensor sequence', 'summarize the MUGENDataset init_game_assets method that loads theme-specific game assets and semantic color maps', 'convert a grayscale label tensor to a color tensor using the label color map', 'review the label color map dictionary that maps integer labels to RGB color tensors', 'refactor convert_grayscale_to_color_label to use vectorized indexing instead of a Python loop', 'test convert_grayscale_to_color_label with a sample batch tensor of shape B T H W', 'summarize the label color map containing 23 RGB color entries for segmentation labels']
```

Usage

```
{'create_MUGENDatasetArgs': 'create a MUGENDatasetArgs dataclass to configure dataset paths, resolution, and annotation settings', 'build_MUGENDataset': 'build a PyTorch Dataset that loads MUGEN game video, audio, and text data from JSON metadata', 'review_MUGENDataset_getitem': 'review the MUGENDataset __getitem__ method to understand how video, audio, and text are returned per sample', 'test_MUGENDataset_get_game_video': 'test the MUGENDataset get_game_video method to render game frames as a tensor sequence', 'summarize_MUGENDataset_init_game_assets': 'summarize the MUGENDataset init_game_assets method that loads theme-specific game assets and semantic color maps'}
```

## File: facebookresearch_multimodal/examples/mugen/data/video_utils.py

Prompts

```
['load audio from a media file at a given sample rate with offset and duration', 'load and resample audio from a file to stereo float32 at a target sample rate', 'load audio from a file using approximate offset when the requested range exceeds file duration', 'load audio from a file using seconds as the time base for offset and duration', 'load audio from a file without resampling when the file sample rate matches the target rate', 'create a MUGENDataModule with dataset args and optional text, video, and audio transforms', 'build a training dataloader for the MUGEN dataset using MUGENDataModule train_dataloader method', 'build a validation dataloader for the MUGEN dataset using MUGENDataModule val_dataloader method', 'build a test dataloader for the MUGEN dataset using MUGENDataModule test_dataloader method', 'review the _custom_collate_fn method that stacks video, text, and audio batches with transforms', 'create a MUGENDatasetArgs dataclass to configure dataset paths, resolution, and annotation settings', 'build a PyTorch Dataset that loads MUGEN game video, audio, and text data from JSON metadata', 'review the MUGENDataset __getitem__ method to understand how video, audio, and text are returned per sample', 'test the MUGENDataset get_game_video method to render game frames as a tensor sequence', 'summarize the MUGENDataset init_game_assets method that loads theme-specific game assets and semantic color maps', 'convert a grayscale label tensor to a color tensor using the label color map', 'review the label color map dictionary that maps integer labels to RGB color tensors', 'refactor convert_grayscale_to_color_label to use vectorized indexing instead of a Python loop', 'test convert_grayscale_to_color_label with a sample batch tensor of shape B T H W', 'summarize the label color map containing 23 RGB color entries for segmentation labels']
```

Usage

```
{'convert_grayscale_to_color_label': 'convert a grayscale label tensor to a color tensor using the label color map', 'review_label_color_map': 'review the label color map dictionary that maps integer labels to RGB color tensors', 'refactor_convert_grayscale_to_color_label': 'refactor convert_grayscale_to_color_label to use vectorized indexing instead of a Python loop', 'test_convert_grayscale_to_color_label': 'test convert_grayscale_to_color_label with a sample batch tensor of shape B T H W', 'summarize_label_color_map': 'summarize the label color map containing 23 RGB color entries for segmentation labels'}
```

