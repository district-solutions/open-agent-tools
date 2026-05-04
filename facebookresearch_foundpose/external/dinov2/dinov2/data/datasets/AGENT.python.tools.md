# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/data/datasets/decoders.py

Prompts

```
['create an ImageDataDecoder from raw image bytes and decode to an RGB PIL Image', 'create a TargetDecoder that returns any target object unchanged when decode is called', 'build a custom Decoder subclass by implementing the abstract decode method', 'decode raw image bytes into an RGB PIL Image using ImageDataDecoder', 'review the Decoder base class and its abstract decode method interface', 'create a subclass of ExtendedVisionDataset implementing get_image_data, get_target, and __len__ methods', 'implement the get_image_data method in a subclass to return raw image bytes for a given index', 'implement the get_target method in a subclass to return target labels for a given index', 'use __getitem__ on an ExtendedVisionDataset subclass to retrieve decoded image and target tuples with optional transforms', 'implement the __len__ method in a subclass to return the total number of samples in the dataset', 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump ImageNet entries, class IDs, and class names to numpy cache files for fast loading', 'get the raw image bytes for a sample at a given index from the ImageNet dataset', 'get the class ID or class name for a sample at a given index in the ImageNet dataset', 'parse an ImageNet image relative path to extract the class ID and actual index', 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get raw image bytes from the ImageNet22k dataset by sample index using memory-mapped tarballs', 'get the class index label for a given sample index in the ImageNet22k dataset', 'dump precomputed entries and class IDs to numpy arrays for faster ImageNet22k dataset loading', 'find the class ID string for a given class index in the ImageNet22k dataset']
```

Usage

```
{'create_imagedecoder_from_bytes': 'create an ImageDataDecoder from raw image bytes and decode to an RGB PIL Image', 'create_targetdecoder_passthrough': 'create a TargetDecoder that returns any target object unchanged when decode is called', 'build_decoder_subclass': 'build a custom Decoder subclass by implementing the abstract decode method', 'decode_image_rgb': 'decode raw image bytes into an RGB PIL Image using ImageDataDecoder', 'review_decoder_base_class': 'review the Decoder base class and its abstract decode method interface'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/data/datasets/extended.py

Prompts

```
['create an ImageDataDecoder from raw image bytes and decode to an RGB PIL Image', 'create a TargetDecoder that returns any target object unchanged when decode is called', 'build a custom Decoder subclass by implementing the abstract decode method', 'decode raw image bytes into an RGB PIL Image using ImageDataDecoder', 'review the Decoder base class and its abstract decode method interface', 'create a subclass of ExtendedVisionDataset implementing get_image_data, get_target, and __len__ methods', 'implement the get_image_data method in a subclass to return raw image bytes for a given index', 'implement the get_target method in a subclass to return target labels for a given index', 'use __getitem__ on an ExtendedVisionDataset subclass to retrieve decoded image and target tuples with optional transforms', 'implement the __len__ method in a subclass to return the total number of samples in the dataset', 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump ImageNet entries, class IDs, and class names to numpy cache files for fast loading', 'get the raw image bytes for a sample at a given index from the ImageNet dataset', 'get the class ID or class name for a sample at a given index in the ImageNet dataset', 'parse an ImageNet image relative path to extract the class ID and actual index', 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get raw image bytes from the ImageNet22k dataset by sample index using memory-mapped tarballs', 'get the class index label for a given sample index in the ImageNet22k dataset', 'dump precomputed entries and class IDs to numpy arrays for faster ImageNet22k dataset loading', 'find the class ID string for a given class index in the ImageNet22k dataset']
```

Usage

```
{'create_subclass_extended_vision_dataset': 'create a subclass of ExtendedVisionDataset implementing get_image_data, get_target, and __len__ methods', 'implement_get_image_data': 'implement the get_image_data method in a subclass to return raw image bytes for a given index', 'implement_get_target': 'implement the get_target method in a subclass to return target labels for a given index', 'use_getitem_with_transforms': 'use __getitem__ on an ExtendedVisionDataset subclass to retrieve decoded image and target tuples with optional transforms', 'implement_len_method': 'implement the __len__ method in a subclass to return the total number of samples in the dataset'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/data/datasets/image_net.py

Prompts

```
['create an ImageDataDecoder from raw image bytes and decode to an RGB PIL Image', 'create a TargetDecoder that returns any target object unchanged when decode is called', 'build a custom Decoder subclass by implementing the abstract decode method', 'decode raw image bytes into an RGB PIL Image using ImageDataDecoder', 'review the Decoder base class and its abstract decode method interface', 'create a subclass of ExtendedVisionDataset implementing get_image_data, get_target, and __len__ methods', 'implement the get_image_data method in a subclass to return raw image bytes for a given index', 'implement the get_target method in a subclass to return target labels for a given index', 'use __getitem__ on an ExtendedVisionDataset subclass to retrieve decoded image and target tuples with optional transforms', 'implement the __len__ method in a subclass to return the total number of samples in the dataset', 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump ImageNet entries, class IDs, and class names to numpy cache files for fast loading', 'get the raw image bytes for a sample at a given index from the ImageNet dataset', 'get the class ID or class name for a sample at a given index in the ImageNet dataset', 'parse an ImageNet image relative path to extract the class ID and actual index', 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get raw image bytes from the ImageNet22k dataset by sample index using memory-mapped tarballs', 'get the class index label for a given sample index in the ImageNet22k dataset', 'dump precomputed entries and class IDs to numpy arrays for faster ImageNet22k dataset loading', 'find the class ID string for a given class index in the ImageNet22k dataset']
```

Usage

```
{'create_imagenet_dataset': 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump_imagenet_extra': 'dump ImageNet entries, class IDs, and class names to numpy cache files for fast loading', 'get_imagenet_image_data': 'get the raw image bytes for a sample at a given index from the ImageNet dataset', 'get_imagenet_class_info': 'get the class ID or class name for a sample at a given index in the ImageNet dataset', 'parse_imagenet_image_path': 'parse an ImageNet image relative path to extract the class ID and actual index'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/data/datasets/image_net_22k.py

Prompts

```
['create an ImageDataDecoder from raw image bytes and decode to an RGB PIL Image', 'create a TargetDecoder that returns any target object unchanged when decode is called', 'build a custom Decoder subclass by implementing the abstract decode method', 'decode raw image bytes into an RGB PIL Image using ImageDataDecoder', 'review the Decoder base class and its abstract decode method interface', 'create a subclass of ExtendedVisionDataset implementing get_image_data, get_target, and __len__ methods', 'implement the get_image_data method in a subclass to return raw image bytes for a given index', 'implement the get_target method in a subclass to return target labels for a given index', 'use __getitem__ on an ExtendedVisionDataset subclass to retrieve decoded image and target tuples with optional transforms', 'implement the __len__ method in a subclass to return the total number of samples in the dataset', 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump ImageNet entries, class IDs, and class names to numpy cache files for fast loading', 'get the raw image bytes for a sample at a given index from the ImageNet dataset', 'get the class ID or class name for a sample at a given index in the ImageNet dataset', 'parse an ImageNet image relative path to extract the class ID and actual index', 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get raw image bytes from the ImageNet22k dataset by sample index using memory-mapped tarballs', 'get the class index label for a given sample index in the ImageNet22k dataset', 'dump precomputed entries and class IDs to numpy arrays for faster ImageNet22k dataset loading', 'find the class ID string for a given class index in the ImageNet22k dataset']
```

Usage

```
{'create_ImageNet22k_dataset': 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get_image_data_by_index': 'get raw image bytes from the ImageNet22k dataset by sample index using memory-mapped tarballs', 'get_target_class_index': 'get the class index label for a given sample index in the ImageNet22k dataset', 'dump_extra_index_files': 'dump precomputed entries and class IDs to numpy arrays for faster ImageNet22k dataset loading', 'find_class_id_by_index': 'find the class ID string for a given class index in the ImageNet22k dataset'}
```

