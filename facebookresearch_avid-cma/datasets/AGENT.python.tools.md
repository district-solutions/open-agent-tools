# Agent Python Tools

- repo: facebookresearch/avid-cma
- repo_uri: https://github.com/facebookresearch/avid-cma

## File: facebookresearch_avid-cma/datasets/audioset.py

Prompts

```
['create an AudiosetClasses instance to load AudioSet class labels and display names from a CSV cache file', 'use AudiosetClasses class2index method to convert a class string like a mid to its integer index', 'iterate over an AudiosetClasses instance to get display names by index using getitem and len', 'create an AudioSet dataset instance with a subset name and optional video and audio clip parameters', 'access AudioSet properties like num_videos, num_classes, sample_id, root, and subset after initialization', 'create a VideoDataset in clip mode to sample random video and audio clips from a dataset', 'create a VideoDataset in sequence mode to load entire videos split into overlapping chunks', 'use VideoDataset getitem to retrieve a video clip with optional audio and labels by index', 'use the _sample_snippet method to randomly sample synchronized video and audio start times and durations', 'use the chararray helper function to convert a list of filenames into a numpy chararray']
```

Usage

```
{'create_audioset_classes': 'create an AudiosetClasses instance to load AudioSet class labels and display names from a CSV cache file', 'lookup_class_index': 'use AudiosetClasses class2index method to convert a class string like a mid to its integer index', 'iterate_classes': 'iterate over an AudiosetClasses instance to get display names by index using getitem and len', 'create_audioset_dataset': 'create an AudioSet dataset instance with a subset name and optional video and audio clip parameters', 'access_audioset_metadata': 'access AudioSet properties like num_videos, num_classes, sample_id, root, and subset after initialization'}
```

## File: facebookresearch_avid-cma/datasets/video_db.py

Prompts

```
['create an AudiosetClasses instance to load AudioSet class labels and display names from a CSV cache file', 'use AudiosetClasses class2index method to convert a class string like a mid to its integer index', 'iterate over an AudiosetClasses instance to get display names by index using getitem and len', 'create an AudioSet dataset instance with a subset name and optional video and audio clip parameters', 'access AudioSet properties like num_videos, num_classes, sample_id, root, and subset after initialization', 'create a VideoDataset in clip mode to sample random video and audio clips from a dataset', 'create a VideoDataset in sequence mode to load entire videos split into overlapping chunks', 'use VideoDataset getitem to retrieve a video clip with optional audio and labels by index', 'use the _sample_snippet method to randomly sample synchronized video and audio start times and durations', 'use the chararray helper function to convert a list of filenames into a numpy chararray']
```

Usage

```
{'create_VideoDataset_for_clip_mode': 'create a VideoDataset in clip mode to sample random video and audio clips from a dataset', 'create_VideoDataset_for_sequence_mode': 'create a VideoDataset in sequence mode to load entire videos split into overlapping chunks', 'use_VideoDataset_getitem': 'use VideoDataset getitem to retrieve a video clip with optional audio and labels by index', 'use_VideoDataset_sample_snippet': 'use the _sample_snippet method to randomly sample synchronized video and audio start times and durations', 'use_chararray_helper': 'use the chararray helper function to convert a list of filenames into a numpy chararray'}
```

