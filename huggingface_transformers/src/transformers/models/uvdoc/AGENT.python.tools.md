# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/uvdoc/image_processing_uvdoc.py

Prompts

```
['create a UVDocImageProcessor instance for preprocessing document images with resize and normalization', 'run the _preprocess method to group, rescale, normalize, resize, and reorder batch document images into pixel values', 'run post_process_document_rectification to apply predicted Bezier mesh coordinates and rectify warped document images', 'group document images by their spatial dimensions for efficient batch processing', 'reorder processed image batches back to their original input order after grouping by shape', 'create a UVDocModel instance from a UVDocConfig to rectify document images', 'build a UVDocBackbone for extracting multi-scale feature maps from document images', 'run a UVDocModel forward pass with pixel values to predict spatial transformation parameters', 'configure a UVDocResNet with head layers and residual stages for document feature extraction', 'build a UVDocBridge module with dilated convolution blocks for long-range dependencies', 'run UVDocImageProcessor to preprocess document images with resizing, rescaling, and RGB-to-BGR conversion', 'test UVDocImageProcessor.post_process_document_rectification to convert predicted mesh into rectified document images', 'summarize UVDocResNetStage which contains multiple UVDocResidualBlock layers with dilation and downsampling support']
```

Usage

```
{'create_uvdoc_image_processor': 'create a UVDocImageProcessor instance for preprocessing document images with resize and normalization', 'run_preprocess_images': 'run the _preprocess method to group, rescale, normalize, resize, and reorder batch document images into pixel values', 'run_post_process_document_rectification': 'run post_process_document_rectification to apply predicted Bezier mesh coordinates and rectify warped document images', 'group_images_by_shape': 'group document images by their spatial dimensions for efficient batch processing', 'reorder_images': 'reorder processed image batches back to their original input order after grouping by shape'}
```

## File: huggingface_transformers/src/transformers/models/uvdoc/modeling_uvdoc.py

Prompts

```
['create a UVDocImageProcessor instance for preprocessing document images with resize and normalization', 'run the _preprocess method to group, rescale, normalize, resize, and reorder batch document images into pixel values', 'run post_process_document_rectification to apply predicted Bezier mesh coordinates and rectify warped document images', 'group document images by their spatial dimensions for efficient batch processing', 'reorder processed image batches back to their original input order after grouping by shape', 'create a UVDocModel instance from a UVDocConfig to rectify document images', 'build a UVDocBackbone for extracting multi-scale feature maps from document images', 'run a UVDocModel forward pass with pixel values to predict spatial transformation parameters', 'configure a UVDocResNet with head layers and residual stages for document feature extraction', 'build a UVDocBridge module with dilated convolution blocks for long-range dependencies', 'run UVDocImageProcessor to preprocess document images with resizing, rescaling, and RGB-to-BGR conversion', 'test UVDocImageProcessor.post_process_document_rectification to convert predicted mesh into rectified document images', 'summarize UVDocResNetStage which contains multiple UVDocResidualBlock layers with dilation and downsampling support']
```

Usage

```
{'create_uvdoc_model': 'create a UVDocModel instance from a UVDocConfig to rectify document images', 'build_uvdoc_backbone': 'build a UVDocBackbone for extracting multi-scale feature maps from document images', 'run_uvdoc_forward': 'run a UVDocModel forward pass with pixel values to predict spatial transformation parameters', 'configure_uvdoc_resnet': 'configure a UVDocResNet with head layers and residual stages for document feature extraction', 'build_uvdoc_bridge': 'build a UVDocBridge module with dilated convolution blocks for long-range dependencies'}
```

## File: huggingface_transformers/src/transformers/models/uvdoc/modular_uvdoc.py

Prompts

```
['create a UVDocImageProcessor instance for preprocessing document images with resize and normalization', 'run the _preprocess method to group, rescale, normalize, resize, and reorder batch document images into pixel values', 'run post_process_document_rectification to apply predicted Bezier mesh coordinates and rectify warped document images', 'group document images by their spatial dimensions for efficient batch processing', 'reorder processed image batches back to their original input order after grouping by shape', 'create a UVDocModel instance from a UVDocConfig to rectify document images', 'build a UVDocBackbone for extracting multi-scale feature maps from document images', 'run a UVDocModel forward pass with pixel values to predict spatial transformation parameters', 'configure a UVDocResNet with head layers and residual stages for document feature extraction', 'build a UVDocBridge module with dilated convolution blocks for long-range dependencies', 'run UVDocImageProcessor to preprocess document images with resizing, rescaling, and RGB-to-BGR conversion', 'test UVDocImageProcessor.post_process_document_rectification to convert predicted mesh into rectified document images', 'summarize UVDocResNetStage which contains multiple UVDocResidualBlock layers with dilation and downsampling support']
```

Usage

```
{'create_uvdoc_model': 'create a UVDocModel instance from a UVDocConfig to predict 2D Bezier mesh coordinates for document rectification', 'build_uvdoc_backbone': 'build a UVDocBackbone with UVDocBackboneConfig for feature extraction from document images', 'run_uvdoc_image_processor': 'run UVDocImageProcessor to preprocess document images with resizing, rescaling, and RGB-to-BGR conversion', 'test_uvdoc_image_post_process': 'test UVDocImageProcessor.post_process_document_rectification to convert predicted mesh into rectified document images', 'summarize_uvdoc_resnet_stage': 'summarize UVDocResNetStage which contains multiple UVDocResidualBlock layers with dilation and downsampling support'}
```

