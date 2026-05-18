# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/charades/_utils.py

Prompts

```
['build a pandas DataFrame from a CSV, video directory, and classes file for the Charades dataset', 'create an animated GIF from a list of PIL images and save it to a temporary path', 'select evenly spaced frames from a video using presentation timestamps and a target frame count', 'compute video clips with a specified number of frames and frame rate for all loaded videos', 'get a subclip tensor, audio tensor, and metadata dict by index from a CharadesVideoClips instance', 'build a CharadesBuilder instance to prepare the Charades dataset for multimodal learning tasks', 'create a CharadesBuilder with a custom dataset_name and dataset_class for flexible dataset configuration', 'get the default YAML config path for the Charades dataset using the config_path classmethod', 'register the CharadesBuilder with the MMF registry using the register_builder decorator for the charades key', 'review the CharadesBuilder class to understand how it extends MMFDatasetBuilder for Charades dataset support', 'load the Charades dataset CSV annotations and video directory into a processed DataFrame with video clips', 'process a DataFrame to extract labels, text, video paths, and create CharadesVideoClips with configurable frames per clip', 'format model prediction scores into binary action labels using a configurable sigmoid threshold', 'display a video clip as a GIF with audio, labels, and text for a given dataset index']
```

Usage

```
{'build_charades_dataframe': 'build a pandas DataFrame from a CSV, video directory, and classes file for the Charades dataset', 'create_gif_from_images': 'create an animated GIF from a list of PIL images and save it to a temporary path', 'select_clips_from_video': 'select evenly spaced frames from a video using presentation timestamps and a target frame count', 'compute_video_clips': 'compute video clips with a specified number of frames and frame rate for all loaded videos', 'get_video_clip': 'get a subclip tensor, audio tensor, and metadata dict by index from a CharadesVideoClips instance'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/charades/builder.py

Prompts

```
['build a pandas DataFrame from a CSV, video directory, and classes file for the Charades dataset', 'create an animated GIF from a list of PIL images and save it to a temporary path', 'select evenly spaced frames from a video using presentation timestamps and a target frame count', 'compute video clips with a specified number of frames and frame rate for all loaded videos', 'get a subclip tensor, audio tensor, and metadata dict by index from a CharadesVideoClips instance', 'build a CharadesBuilder instance to prepare the Charades dataset for multimodal learning tasks', 'create a CharadesBuilder with a custom dataset_name and dataset_class for flexible dataset configuration', 'get the default YAML config path for the Charades dataset using the config_path classmethod', 'register the CharadesBuilder with the MMF registry using the register_builder decorator for the charades key', 'review the CharadesBuilder class to understand how it extends MMFDatasetBuilder for Charades dataset support', 'load the Charades dataset CSV annotations and video directory into a processed DataFrame with video clips', 'process a DataFrame to extract labels, text, video paths, and create CharadesVideoClips with configurable frames per clip', 'format model prediction scores into binary action labels using a configurable sigmoid threshold', 'display a video clip as a GIF with audio, labels, and text for a given dataset index']
```

Usage

```
{'build_charades_dataset': 'build a CharadesBuilder instance to prepare the Charades dataset for multimodal learning tasks', 'create_charades_builder': 'create a CharadesBuilder with a custom dataset_name and dataset_class for flexible dataset configuration', 'get_config_path': 'get the default YAML config path for the Charades dataset using the config_path classmethod', 'register_charades_builder': 'register the CharadesBuilder with the MMF registry using the register_builder decorator for the charades key', 'review_charades_builder': 'review the CharadesBuilder class to understand how it extends MMFDatasetBuilder for Charades dataset support'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/charades/dataset.py

Prompts

```
['build a pandas DataFrame from a CSV, video directory, and classes file for the Charades dataset', 'create an animated GIF from a list of PIL images and save it to a temporary path', 'select evenly spaced frames from a video using presentation timestamps and a target frame count', 'compute video clips with a specified number of frames and frame rate for all loaded videos', 'get a subclip tensor, audio tensor, and metadata dict by index from a CharadesVideoClips instance', 'build a CharadesBuilder instance to prepare the Charades dataset for multimodal learning tasks', 'create a CharadesBuilder with a custom dataset_name and dataset_class for flexible dataset configuration', 'get the default YAML config path for the Charades dataset using the config_path classmethod', 'register the CharadesBuilder with the MMF registry using the register_builder decorator for the charades key', 'review the CharadesBuilder class to understand how it extends MMFDatasetBuilder for Charades dataset support', 'load the Charades dataset CSV annotations and video directory into a processed DataFrame with video clips', 'process a DataFrame to extract labels, text, video paths, and create CharadesVideoClips with configurable frames per clip', 'format model prediction scores into binary action labels using a configurable sigmoid threshold', 'display a video clip as a GIF with audio, labels, and text for a given dataset index']
```

Usage

```
{'build_charades_dataset': 'build a CharadesDataset instance with config, dataset_type, and imdb_file_index to load video clips and labels', 'load_df_charades': 'load the Charades dataset CSV annotations and video directory into a processed DataFrame with video clips', 'process_df_charades': 'process a DataFrame to extract labels, text, video paths, and create CharadesVideoClips with configurable frames per clip', 'format_for_prediction_charades': 'format model prediction scores into binary action labels using a configurable sigmoid threshold', 'show_clip_charades': 'display a video clip as a GIF with audio, labels, and text for a given dataset index'}
```

