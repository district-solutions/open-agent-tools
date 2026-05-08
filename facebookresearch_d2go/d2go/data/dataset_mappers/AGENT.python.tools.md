# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/data/dataset_mappers/build.py

Prompts

```
['build a dataset mapper from a config using the D2GO_DATA_MAPPER_REGISTRY factory function', 'register a custom dataset mapper function with the D2GO_DATA_MAPPER_REGISTRY registry', 'review the D2GO_DATA_MAPPER_REGISTRY to see which dataset mappers are registered', 'refactor the build_dataset_mapper function to support additional config options or default mappers', 'test the build_dataset_mapper function with a mock config and registered mapper', 'read an image file with optional prefetched tensor data and return a numpy array', 'read an image file from disk using detectron2 utils when no prefetched data is provided', 'read an image from a prefetched tensor, apply EXIF orientation, and convert to numpy', 'read a PNG semantic segmentation mask file with optional prefetched data and return grayscale numpy array', 'read an NPY semantic segmentation mask file from disk or prefetched tensor and return the numpy array']
```

Usage

```
{'build_dataset_mapper': 'build a dataset mapper from a config using the D2GO_DATA_MAPPER_REGISTRY factory function', 'register_dataset_mapper': 'register a custom dataset mapper function with the D2GO_DATA_MAPPER_REGISTRY registry', 'review_D2GO_DATA_MAPPER_REGISTRY': 'review the D2GO_DATA_MAPPER_REGISTRY to see which dataset mappers are registered', 'refactor_build_dataset_mapper': 'refactor the build_dataset_mapper function to support additional config options or default mappers', 'test_build_dataset_mapper': 'test the build_dataset_mapper function with a mock config and registered mapper'}
```

## File: facebookresearch_d2go/d2go/data/dataset_mappers/data_reading.py

Prompts

```
['build a dataset mapper from a config using the D2GO_DATA_MAPPER_REGISTRY factory function', 'register a custom dataset mapper function with the D2GO_DATA_MAPPER_REGISTRY registry', 'review the D2GO_DATA_MAPPER_REGISTRY to see which dataset mappers are registered', 'refactor the build_dataset_mapper function to support additional config options or default mappers', 'test the build_dataset_mapper function with a mock config and registered mapper', 'read an image file with optional prefetched tensor data and return a numpy array', 'read an image file from disk using detectron2 utils when no prefetched data is provided', 'read an image from a prefetched tensor, apply EXIF orientation, and convert to numpy', 'read a PNG semantic segmentation mask file with optional prefetched data and return grayscale numpy array', 'read an NPY semantic segmentation mask file from disk or prefetched tensor and return the numpy array']
```

Usage

```
{'read_image_with_prefetch': 'read an image file with optional prefetched tensor data and return a numpy array', 'read_image_with_prefetch_no_prefetch': 'read an image file from disk using detectron2 utils when no prefetched data is provided', 'read_image_with_prefetch_pillow_exif': 'read an image from a prefetched tensor, apply EXIF orientation, and convert to numpy', 'read_sem_seg_file_with_prefetch_png': 'read a PNG semantic segmentation mask file with optional prefetched data and return grayscale numpy array', 'read_sem_seg_file_with_prefetch_npy': 'read an NPY semantic segmentation mask file from disk or prefetched tensor and return the numpy array'}
```

