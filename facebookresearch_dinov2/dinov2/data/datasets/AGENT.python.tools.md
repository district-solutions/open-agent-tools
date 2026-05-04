# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/data/datasets/decoders.py

Prompts

```
['create a python module that uses ImageDataDecoder to decode raw image bytes into an RGB PIL Image', 'create a python module that uses XChannelsDecoder to decode image bytes into a PyTorch tensor with channel-first format', 'create a python module that uses XChannelsTIFFDecoder to decode TIFF image bytes into a PyTorch tensor with configurable channels', 'create a python module that uses ChannelSelectDecoder to decode image bytes and select a specific color channel as a tensor', 'create a python module that uses DecoderType enum to resolve and instantiate the correct decoder class by name', 'create a subclass of ExtendedVisionDataset that implements get_image_data, get_target, and __len__ methods', 'build a custom vision dataset using ExtendedVisionDataset with a configurable image_decoder_type and decoder params', 'test the ExtendedVisionDataset __getitem__ method to verify image decoding and target retrieval work correctly', 'review the ExtendedVisionDataset __init__ to understand how image_decoder_type and image_decoder_params kwargs are handled', 'refactor the ExtendedVisionDataset __getitem__ error handling to add custom logging or fallback behavior for corrupted images', 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump ImageNet dataset entries and class metadata to numpy cache files for fast loading', 'get raw image bytes from an ImageNet dataset sample by its index', 'get the class ID or class name for an ImageNet sample by its index', 'parse an ImageNet image relative path to extract the class ID and actual index', 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get raw image bytes for a sample by index using memory-mapped tarball access', 'get the class index label for a given sample index in the dataset', 'dump entries and class IDs to numpy arrays for faster subsequent dataset loading', 'find the class ID string for a given class index in the dataset']
```

Usage

```
{'decode_image_bytes_to_rgb': 'create a python module that uses ImageDataDecoder to decode raw image bytes into an RGB PIL Image', 'decode_image_to_tensor': 'create a python module that uses XChannelsDecoder to decode image bytes into a PyTorch tensor with channel-first format', 'decode_tiff_to_tensor': 'create a python module that uses XChannelsTIFFDecoder to decode TIFF image bytes into a PyTorch tensor with configurable channels', 'select_channel_from_image': 'create a python module that uses ChannelSelectDecoder to decode image bytes and select a specific color channel as a tensor', 'get_decoder_class_by_type': 'create a python module that uses DecoderType enum to resolve and instantiate the correct decoder class by name'}
```

## File: facebookresearch_dinov2/dinov2/data/datasets/extended.py

Prompts

```
['create a python module that uses ImageDataDecoder to decode raw image bytes into an RGB PIL Image', 'create a python module that uses XChannelsDecoder to decode image bytes into a PyTorch tensor with channel-first format', 'create a python module that uses XChannelsTIFFDecoder to decode TIFF image bytes into a PyTorch tensor with configurable channels', 'create a python module that uses ChannelSelectDecoder to decode image bytes and select a specific color channel as a tensor', 'create a python module that uses DecoderType enum to resolve and instantiate the correct decoder class by name', 'create a subclass of ExtendedVisionDataset that implements get_image_data, get_target, and __len__ methods', 'build a custom vision dataset using ExtendedVisionDataset with a configurable image_decoder_type and decoder params', 'test the ExtendedVisionDataset __getitem__ method to verify image decoding and target retrieval work correctly', 'review the ExtendedVisionDataset __init__ to understand how image_decoder_type and image_decoder_params kwargs are handled', 'refactor the ExtendedVisionDataset __getitem__ error handling to add custom logging or fallback behavior for corrupted images', 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump ImageNet dataset entries and class metadata to numpy cache files for fast loading', 'get raw image bytes from an ImageNet dataset sample by its index', 'get the class ID or class name for an ImageNet sample by its index', 'parse an ImageNet image relative path to extract the class ID and actual index', 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get raw image bytes for a sample by index using memory-mapped tarball access', 'get the class index label for a given sample index in the dataset', 'dump entries and class IDs to numpy arrays for faster subsequent dataset loading', 'find the class ID string for a given class index in the dataset']
```

Usage

```
{'create_subclass_extended_vision_dataset': 'create a subclass of ExtendedVisionDataset that implements get_image_data, get_target, and __len__ methods', 'build_custom_vision_dataset_with_decoder': 'build a custom vision dataset using ExtendedVisionDataset with a configurable image_decoder_type and decoder params', 'test_extended_vision_dataset_getitem': 'test the ExtendedVisionDataset __getitem__ method to verify image decoding and target retrieval work correctly', 'review_extended_vision_dataset_init': 'review the ExtendedVisionDataset __init__ to understand how image_decoder_type and image_decoder_params kwargs are handled', 'refactor_extended_vision_dataset_error_handling': 'refactor the ExtendedVisionDataset __getitem__ error handling to add custom logging or fallback behavior for corrupted images'}
```

## File: facebookresearch_dinov2/dinov2/data/datasets/image_net.py

Prompts

```
['create a python module that uses ImageDataDecoder to decode raw image bytes into an RGB PIL Image', 'create a python module that uses XChannelsDecoder to decode image bytes into a PyTorch tensor with channel-first format', 'create a python module that uses XChannelsTIFFDecoder to decode TIFF image bytes into a PyTorch tensor with configurable channels', 'create a python module that uses ChannelSelectDecoder to decode image bytes and select a specific color channel as a tensor', 'create a python module that uses DecoderType enum to resolve and instantiate the correct decoder class by name', 'create a subclass of ExtendedVisionDataset that implements get_image_data, get_target, and __len__ methods', 'build a custom vision dataset using ExtendedVisionDataset with a configurable image_decoder_type and decoder params', 'test the ExtendedVisionDataset __getitem__ method to verify image decoding and target retrieval work correctly', 'review the ExtendedVisionDataset __init__ to understand how image_decoder_type and image_decoder_params kwargs are handled', 'refactor the ExtendedVisionDataset __getitem__ error handling to add custom logging or fallback behavior for corrupted images', 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump ImageNet dataset entries and class metadata to numpy cache files for fast loading', 'get raw image bytes from an ImageNet dataset sample by its index', 'get the class ID or class name for an ImageNet sample by its index', 'parse an ImageNet image relative path to extract the class ID and actual index', 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get raw image bytes for a sample by index using memory-mapped tarball access', 'get the class index label for a given sample index in the dataset', 'dump entries and class IDs to numpy arrays for faster subsequent dataset loading', 'find the class ID string for a given class index in the dataset']
```

Usage

```
{'create_imagenet_dataset': 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump_imagenet_extra': 'dump ImageNet dataset entries and class metadata to numpy cache files for fast loading', 'get_imagenet_image_data': 'get raw image bytes from an ImageNet dataset sample by its index', 'get_imagenet_class_info': 'get the class ID or class name for an ImageNet sample by its index', 'parse_imagenet_image_path': 'parse an ImageNet image relative path to extract the class ID and actual index'}
```

## File: facebookresearch_dinov2/dinov2/data/datasets/image_net_22k.py

Prompts

```
['create a python module that uses ImageDataDecoder to decode raw image bytes into an RGB PIL Image', 'create a python module that uses XChannelsDecoder to decode image bytes into a PyTorch tensor with channel-first format', 'create a python module that uses XChannelsTIFFDecoder to decode TIFF image bytes into a PyTorch tensor with configurable channels', 'create a python module that uses ChannelSelectDecoder to decode image bytes and select a specific color channel as a tensor', 'create a python module that uses DecoderType enum to resolve and instantiate the correct decoder class by name', 'create a subclass of ExtendedVisionDataset that implements get_image_data, get_target, and __len__ methods', 'build a custom vision dataset using ExtendedVisionDataset with a configurable image_decoder_type and decoder params', 'test the ExtendedVisionDataset __getitem__ method to verify image decoding and target retrieval work correctly', 'review the ExtendedVisionDataset __init__ to understand how image_decoder_type and image_decoder_params kwargs are handled', 'refactor the ExtendedVisionDataset __getitem__ error handling to add custom logging or fallback behavior for corrupted images', 'create an ImageNet dataset instance with a specified split, root directory, and extra cache path', 'dump ImageNet dataset entries and class metadata to numpy cache files for fast loading', 'get raw image bytes from an ImageNet dataset sample by its index', 'get the class ID or class name for an ImageNet sample by its index', 'parse an ImageNet image relative path to extract the class ID and actual index', 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get raw image bytes for a sample by index using memory-mapped tarball access', 'get the class index label for a given sample index in the dataset', 'dump entries and class IDs to numpy arrays for faster subsequent dataset loading', 'find the class ID string for a given class index in the dataset']
```

Usage

```
{'create_ImageNet22k_dataset': 'create an ImageNet22k dataset instance with root and extra paths for memory-mapped image access', 'get_image_data_by_index': 'get raw image bytes for a sample by index using memory-mapped tarball access', 'get_target_class_index': 'get the class index label for a given sample index in the dataset', 'dump_extra_index_files': 'dump entries and class IDs to numpy arrays for faster subsequent dataset loading', 'find_class_id_by_index': 'find the class ID string for a given class index in the dataset'}
```

