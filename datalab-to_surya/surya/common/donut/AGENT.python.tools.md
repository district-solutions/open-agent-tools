# Agent Python Tools

- repo: datalab-to/surya
- repo_uri: https://github.com/datalab-to/surya

## File: datalab-to_surya/surya/common/donut/encoder.py

Prompts

```
['build a DonutSwinEncoder that processes image patches through stacked stages with shifted window attention', 'create DonutSwinEmbeddings to convert pixel values into patch embeddings with position encoding support', 'test the window_partition function that splits 2D feature maps into fixed-size windows for local attention', 'refactor DonutSwinSelfAttention to use grouped query attention with configurable kv_heads for efficiency', 'summarize the DonutSwinStage class that combines transformer blocks with patch merging for hierarchical feature extraction', 'create a SuryaEncoderImageProcessor to preprocess images for transformer-based document recognition', 'process a list of numpy RGB images by resizing, padding, rescaling, and normalizing them for model input', 'pad a numpy image to a target size with centered whitespace padding for batch processing', 'rotate a numpy image 90 degrees if its aspect ratio is inverted relative to the target output dimensions', 'normalize a numpy image array using custom mean and standard deviation values per channel']
```

Usage

```
{'build_donut_swin_encoder': 'build a DonutSwinEncoder that processes image patches through stacked stages with shifted window attention', 'create_donut_swin_embeddings': 'create DonutSwinEmbeddings to convert pixel values into patch embeddings with position encoding support', 'test_window_partition': 'test the window_partition function that splits 2D feature maps into fixed-size windows for local attention', 'refactor_donut_swin_attention': 'refactor DonutSwinSelfAttention to use grouped query attention with configurable kv_heads for efficiency', 'summarize_donut_swin_stage': 'summarize the DonutSwinStage class that combines transformer blocks with patch merging for hierarchical feature extraction'}
```

## File: datalab-to_surya/surya/common/donut/processor.py

Prompts

```
['build a DonutSwinEncoder that processes image patches through stacked stages with shifted window attention', 'create DonutSwinEmbeddings to convert pixel values into patch embeddings with position encoding support', 'test the window_partition function that splits 2D feature maps into fixed-size windows for local attention', 'refactor DonutSwinSelfAttention to use grouped query attention with configurable kv_heads for efficiency', 'summarize the DonutSwinStage class that combines transformer blocks with patch merging for hierarchical feature extraction', 'create a SuryaEncoderImageProcessor to preprocess images for transformer-based document recognition', 'process a list of numpy RGB images by resizing, padding, rescaling, and normalizing them for model input', 'pad a numpy image to a target size with centered whitespace padding for batch processing', 'rotate a numpy image 90 degrees if its aspect ratio is inverted relative to the target output dimensions', 'normalize a numpy image array using custom mean and standard deviation values per channel']
```

Usage

```
{'create_surya_image_processor': 'create a SuryaEncoderImageProcessor to preprocess images for transformer-based document recognition', 'process_inner_images': 'process a list of numpy RGB images by resizing, padding, rescaling, and normalizing them for model input', 'pad_image_to_max_size': 'pad a numpy image to a target size with centered whitespace padding for batch processing', 'align_long_axis_image': 'rotate a numpy image 90 degrees if its aspect ratio is inverted relative to the target output dimensions', 'normalize_image_values': 'normalize a numpy image array using custom mean and standard deviation values per channel'}
```

