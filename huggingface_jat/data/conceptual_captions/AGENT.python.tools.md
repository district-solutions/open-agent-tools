# Agent Python Tools

- repo: huggingface/jat
- repo_uri: https://github.com/huggingface/jat

## File: huggingface_jat/data/conceptual_captions/generate_conceptual_caption.py

Prompts

```
['fetch an image from a URL and return it as a PIL Image object', 'resize a PIL image so the larger dimension is at most 352 pixels and remove metadata', 'fetch an image from a URL, resize it, and return the result or None on error', 'process a batch of image URLs with multiprocessing and pair them with their captions', 'download the conceptual_captions dataset, fetch and resize images, and push the processed dataset to the Hugging Face Hub']
```

Usage

```
{'fetch_image_from_url': 'fetch an image from a URL and return it as a PIL Image object', 'resize_image_to_max_352': 'resize a PIL image so the larger dimension is at most 352 pixels and remove metadata', 'fetch_and_resize_image': 'fetch an image from a URL, resize it, and return the result or None on error', 'process_batch_of_images': 'process a batch of image URLs with multiprocessing and pair them with their captions', 'run_conceptual_captions_pipeline': 'download the conceptual_captions dataset, fetch and resize images, and push the processed dataset to the Hugging Face Hub'}
```

