# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/neuralcompression/data/_clic_2020_image.py

Prompts

```
['create a CLIC2020Image dataset instance using the train split with a specified root directory', 'create a CLIC2020Image dataset instance using the val split for validation purposes', 'create a CLIC2020Image dataset instance using the test split for evaluation', 'download and extract the CLIC2020 dataset images from the internet into the root directory', 'retrieve a PIL image from the CLIC2020Image dataset by index with optional transform applied', 'create a CLIC2020Video dataset instance with a clip sampler and root directory for video compression training', 'download the CLIC 2020 video dataset from Google Storage using the CLIC2020Video download method', 'iterate over video clips in the CLIC2020Video dataset using its iterable interface and clip sampler', 'sample a fixed number of frames per clip from video using the _sample_frames static method', 'retrieve a video clip sample with metadata by index from the CLIC2020Video dataset', 'create a Vimeo90kSeptuplet dataset using the train split with all 7 frames per septuplet', 'create a Vimeo90kSeptuplet dataset in video mode that returns stacked tensors of consecutive frames', 'create a Vimeo90kSeptuplet dataset with a custom number of frames per group between 1 and 7', 'load a single image from a septuplet folder by frame number using the load_image method', 'get an item from the Vimeo90kSeptuplet dataset by index returning either a single image or stacked video frames']
```

Usage

```
{'create_CLIC2020Image_train': 'create a CLIC2020Image dataset instance using the train split with a specified root directory', 'create_CLIC2020Image_val': 'create a CLIC2020Image dataset instance using the val split for validation purposes', 'create_CLIC2020Image_test': 'create a CLIC2020Image dataset instance using the test split for evaluation', 'download_CLIC2020Image': 'download and extract the CLIC2020 dataset images from the internet into the root directory', 'getitem_CLIC2020Image': 'retrieve a PIL image from the CLIC2020Image dataset by index with optional transform applied'}
```

## File: facebookresearch_neuralcompression/neuralcompression/data/_clic_2020_video.py

Prompts

```
['create a CLIC2020Image dataset instance using the train split with a specified root directory', 'create a CLIC2020Image dataset instance using the val split for validation purposes', 'create a CLIC2020Image dataset instance using the test split for evaluation', 'download and extract the CLIC2020 dataset images from the internet into the root directory', 'retrieve a PIL image from the CLIC2020Image dataset by index with optional transform applied', 'create a CLIC2020Video dataset instance with a clip sampler and root directory for video compression training', 'download the CLIC 2020 video dataset from Google Storage using the CLIC2020Video download method', 'iterate over video clips in the CLIC2020Video dataset using its iterable interface and clip sampler', 'sample a fixed number of frames per clip from video using the _sample_frames static method', 'retrieve a video clip sample with metadata by index from the CLIC2020Video dataset', 'create a Vimeo90kSeptuplet dataset using the train split with all 7 frames per septuplet', 'create a Vimeo90kSeptuplet dataset in video mode that returns stacked tensors of consecutive frames', 'create a Vimeo90kSeptuplet dataset with a custom number of frames per group between 1 and 7', 'load a single image from a septuplet folder by frame number using the load_image method', 'get an item from the Vimeo90kSeptuplet dataset by index returning either a single image or stacked video frames']
```

Usage

```
{'create_CLIC2020Video_dataset': 'create a CLIC2020Video dataset instance with a clip sampler and root directory for video compression training', 'download_CLIC2020Video': 'download the CLIC 2020 video dataset from Google Storage using the CLIC2020Video download method', 'iterate_CLIC2020Video_clips': 'iterate over video clips in the CLIC2020Video dataset using its iterable interface and clip sampler', 'sample_frames_CLIC2020Video': 'sample a fixed number of frames per clip from video using the _sample_frames static method', 'getitem_CLIC2020Video': 'retrieve a video clip sample with metadata by index from the CLIC2020Video dataset'}
```

## File: facebookresearch_neuralcompression/neuralcompression/data/_vimeo_90k_septuplet.py

Prompts

```
['create a CLIC2020Image dataset instance using the train split with a specified root directory', 'create a CLIC2020Image dataset instance using the val split for validation purposes', 'create a CLIC2020Image dataset instance using the test split for evaluation', 'download and extract the CLIC2020 dataset images from the internet into the root directory', 'retrieve a PIL image from the CLIC2020Image dataset by index with optional transform applied', 'create a CLIC2020Video dataset instance with a clip sampler and root directory for video compression training', 'download the CLIC 2020 video dataset from Google Storage using the CLIC2020Video download method', 'iterate over video clips in the CLIC2020Video dataset using its iterable interface and clip sampler', 'sample a fixed number of frames per clip from video using the _sample_frames static method', 'retrieve a video clip sample with metadata by index from the CLIC2020Video dataset', 'create a Vimeo90kSeptuplet dataset using the train split with all 7 frames per septuplet', 'create a Vimeo90kSeptuplet dataset in video mode that returns stacked tensors of consecutive frames', 'create a Vimeo90kSeptuplet dataset with a custom number of frames per group between 1 and 7', 'load a single image from a septuplet folder by frame number using the load_image method', 'get an item from the Vimeo90kSeptuplet dataset by index returning either a single image or stacked video frames']
```

Usage

```
{'create_vimeo90k_dataset_train': 'create a Vimeo90kSeptuplet dataset using the train split with all 7 frames per septuplet', 'create_vimeo90k_dataset_video_mode': 'create a Vimeo90kSeptuplet dataset in video mode that returns stacked tensors of consecutive frames', 'create_vimeo90k_dataset_custom_frames': 'create a Vimeo90kSeptuplet dataset with a custom number of frames per group between 1 and 7', 'load_image_from_septuplet': 'load a single image from a septuplet folder by frame number using the load_image method', 'getitem_vimeo90k_dataset': 'get an item from the Vimeo90kSeptuplet dataset by index returning either a single image or stacked video frames'}
```

