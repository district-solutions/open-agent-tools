# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/examples/inference/distributed/distributed_image_generation.py

Prompts

```
['run distributed image generation using a diffusion pipeline with accelerate across multiple GPUs', 'run distributed image generation with low memory mode enabled for large models like SD3', 'run distributed image generation with a custom checkpoint ID and specified batch size', 'run distributed image generation with custom inference steps, guidance scale, and dtype settings', 'build a function that splits a list of items into evenly sized batches for iteration', 'run distributed speech generation using the VITS model with accelerate for multi-GPU inference', 'create a dataloader that preprocesses text samples and batches them with proper padding for distributed inference', 'load pokemon description text data from the svjack/pokemon-blip-captions-en-zh dataset with configurable split and max length', 'save generated audio waveforms to wav files with corresponding json metadata using a background thread pool', 'filter out already-processed items by checking existing wav files in the output directory', 'run distributed image captioning with Florence-2 model on a webdataset using accelerate launch', 'create a webdataset pipeline that decodes PIL images, preprocesses them with a Florence-2 processor, and batches for inference', 'test the ExistsFilter class that skips already-processed images by checking output directory hashes', 'refactor the preprocess_fn to accept a custom prompt and return input_ids, pixel_values, image, img_hash, and original_caption', 'summarize the collate_fn that stacks input_ids and pixel_values tensors and collects images, hashes, and captions into a batch dict', 'run distributed video inference with LLaVA-NeXT-Video model using accelerate launch', 'process a batch of video files and prepare inputs for the LLaVA-NeXT-Video model', 'read and decode specific video frames from a PyAV container into a numpy array', 'save inference results including prompts, video paths, and generated text to JSON files', 'split a batch of video inputs across distributed processes for parallel inference']
```

Usage

```
{'run_distributed_image_generation': 'run distributed image generation using a diffusion pipeline with accelerate across multiple GPUs', 'run_distributed_image_generation_low_mem': 'run distributed image generation with low memory mode enabled for large models like SD3', 'run_distributed_image_generation_custom_ckpt': 'run distributed image generation with a custom checkpoint ID and specified batch size', 'run_distributed_image_generation_custom_params': 'run distributed image generation with custom inference steps, guidance scale, and dtype settings', 'build_get_batches': 'build a function that splits a list of items into evenly sized batches for iteration'}
```

## File: huggingface_accelerate/examples/inference/distributed/distributed_speech_generation.py

Prompts

```
['run distributed image generation using a diffusion pipeline with accelerate across multiple GPUs', 'run distributed image generation with low memory mode enabled for large models like SD3', 'run distributed image generation with a custom checkpoint ID and specified batch size', 'run distributed image generation with custom inference steps, guidance scale, and dtype settings', 'build a function that splits a list of items into evenly sized batches for iteration', 'run distributed speech generation using the VITS model with accelerate for multi-GPU inference', 'create a dataloader that preprocesses text samples and batches them with proper padding for distributed inference', 'load pokemon description text data from the svjack/pokemon-blip-captions-en-zh dataset with configurable split and max length', 'save generated audio waveforms to wav files with corresponding json metadata using a background thread pool', 'filter out already-processed items by checking existing wav files in the output directory', 'run distributed image captioning with Florence-2 model on a webdataset using accelerate launch', 'create a webdataset pipeline that decodes PIL images, preprocesses them with a Florence-2 processor, and batches for inference', 'test the ExistsFilter class that skips already-processed images by checking output directory hashes', 'refactor the preprocess_fn to accept a custom prompt and return input_ids, pixel_values, image, img_hash, and original_caption', 'summarize the collate_fn that stacks input_ids and pixel_values tensors and collects images, hashes, and captions into a batch dict', 'run distributed video inference with LLaVA-NeXT-Video model using accelerate launch', 'process a batch of video files and prepare inputs for the LLaVA-NeXT-Video model', 'read and decode specific video frames from a PyAV container into a numpy array', 'save inference results including prompts, video paths, and generated text to JSON files', 'split a batch of video inputs across distributed processes for parallel inference']
```

Usage

```
{'run_distributed_speech_generation': 'run distributed speech generation using the VITS model with accelerate for multi-GPU inference', 'create_dataloader': 'create a dataloader that preprocesses text samples and batches them with proper padding for distributed inference', 'load_pokemon_data': 'load pokemon description text data from the svjack/pokemon-blip-captions-en-zh dataset with configurable split and max length', 'save_distributed_results': 'save generated audio waveforms to wav files with corresponding json metadata using a background thread pool', 'filter_existing_files': 'filter out already-processed items by checking existing wav files in the output directory'}
```

## File: huggingface_accelerate/examples/inference/distributed/florence2.py

Prompts

```
['run distributed image generation using a diffusion pipeline with accelerate across multiple GPUs', 'run distributed image generation with low memory mode enabled for large models like SD3', 'run distributed image generation with a custom checkpoint ID and specified batch size', 'run distributed image generation with custom inference steps, guidance scale, and dtype settings', 'build a function that splits a list of items into evenly sized batches for iteration', 'run distributed speech generation using the VITS model with accelerate for multi-GPU inference', 'create a dataloader that preprocesses text samples and batches them with proper padding for distributed inference', 'load pokemon description text data from the svjack/pokemon-blip-captions-en-zh dataset with configurable split and max length', 'save generated audio waveforms to wav files with corresponding json metadata using a background thread pool', 'filter out already-processed items by checking existing wav files in the output directory', 'run distributed image captioning with Florence-2 model on a webdataset using accelerate launch', 'create a webdataset pipeline that decodes PIL images, preprocesses them with a Florence-2 processor, and batches for inference', 'test the ExistsFilter class that skips already-processed images by checking output directory hashes', 'refactor the preprocess_fn to accept a custom prompt and return input_ids, pixel_values, image, img_hash, and original_caption', 'summarize the collate_fn that stacks input_ids and pixel_values tensors and collects images, hashes, and captions into a batch dict', 'run distributed video inference with LLaVA-NeXT-Video model using accelerate launch', 'process a batch of video files and prepare inputs for the LLaVA-NeXT-Video model', 'read and decode specific video frames from a PyAV container into a numpy array', 'save inference results including prompts, video paths, and generated text to JSON files', 'split a batch of video inputs across distributed processes for parallel inference']
```

Usage

```
{'run_distributed_image_captioning': 'run distributed image captioning with Florence-2 model on a webdataset using accelerate launch', 'create_webdataset_pipeline': 'create a webdataset pipeline that decodes PIL images, preprocesses them with a Florence-2 processor, and batches for inference', 'test_exists_filter': 'test the ExistsFilter class that skips already-processed images by checking output directory hashes', 'refactor_preprocess_fn': 'refactor the preprocess_fn to accept a custom prompt and return input_ids, pixel_values, image, img_hash, and original_caption', 'summarize_collate_fn': 'summarize the collate_fn that stacks input_ids and pixel_values tensors and collects images, hashes, and captions into a batch dict'}
```

## File: huggingface_accelerate/examples/inference/distributed/llava_next_video.py

Prompts

```
['run distributed image generation using a diffusion pipeline with accelerate across multiple GPUs', 'run distributed image generation with low memory mode enabled for large models like SD3', 'run distributed image generation with a custom checkpoint ID and specified batch size', 'run distributed image generation with custom inference steps, guidance scale, and dtype settings', 'build a function that splits a list of items into evenly sized batches for iteration', 'run distributed speech generation using the VITS model with accelerate for multi-GPU inference', 'create a dataloader that preprocesses text samples and batches them with proper padding for distributed inference', 'load pokemon description text data from the svjack/pokemon-blip-captions-en-zh dataset with configurable split and max length', 'save generated audio waveforms to wav files with corresponding json metadata using a background thread pool', 'filter out already-processed items by checking existing wav files in the output directory', 'run distributed image captioning with Florence-2 model on a webdataset using accelerate launch', 'create a webdataset pipeline that decodes PIL images, preprocesses them with a Florence-2 processor, and batches for inference', 'test the ExistsFilter class that skips already-processed images by checking output directory hashes', 'refactor the preprocess_fn to accept a custom prompt and return input_ids, pixel_values, image, img_hash, and original_caption', 'summarize the collate_fn that stacks input_ids and pixel_values tensors and collects images, hashes, and captions into a batch dict', 'run distributed video inference with LLaVA-NeXT-Video model using accelerate launch', 'process a batch of video files and prepare inputs for the LLaVA-NeXT-Video model', 'read and decode specific video frames from a PyAV container into a numpy array', 'save inference results including prompts, video paths, and generated text to JSON files', 'split a batch of video inputs across distributed processes for parallel inference']
```

Usage

```
{'run_distributed_video_inference': 'run distributed video inference with LLaVA-NeXT-Video model using accelerate launch', 'process_videos_batch': 'process a batch of video files and prepare inputs for the LLaVA-NeXT-Video model', 'read_video_frames_pyav': 'read and decode specific video frames from a PyAV container into a numpy array', 'save_inference_results': 'save inference results including prompts, video paths, and generated text to JSON files', 'split_batches_between_processes': 'split a batch of video inputs across distributed processes for parallel inference'}
```

