# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/assets/audio.py

Prompts

```
["create an AudioAsset instance with a name like 'winning_call' or 'mary_had_lamb'", 'get the filename property of an AudioAsset instance returning the .ogg filename', 'get the S3 URL of an AudioAsset instance for a given audio asset name', 'get the local filesystem path of an AudioAsset instance from the vLLM public assets', 'load audio data and sample rate from an AudioAsset instance as a numpy array and float', 'create a function that returns the cache directory path for storing downloaded vllm assets', 'create a function that downloads an asset file from the vllm public S3 bucket and returns its local path', 'test the get_cache_dir function returns a valid Path to the vllm assets cache directory', 'test the get_vllm_public_assets function downloads and caches a file from the vllm public S3 bucket', 'summarize the vllm.assets.base module which provides asset caching and S3 download utilities', 'create an ImageAsset instance with a named image like stop_sign or cherry_blossom', 'get the s3 path for a named image asset with a given file extension', 'load a PIL Image from a named image asset as a jpg file', 'load a torch.Tensor of image embeddings from a named image asset for llava 1.5 testing', 'read raw bytes of a named image asset with a given file extension', 'download a video asset from huggingface hub into the local cache directory', 'create a function that reads a video file and returns a numpy array of RGB frames', 'create a function that converts video frames to a list of PIL Image objects', 'create a function that extracts video metadata including frame count, fps, and duration', 'build a VideoAsset dataclass instance to access downloaded video frames, images, and audio']
```

Usage

```
{'create_AudioAsset': "create an AudioAsset instance with a name like 'winning_call' or 'mary_had_lamb'", 'get_AudioAsset_filename': 'get the filename property of an AudioAsset instance returning the .ogg filename', 'get_AudioAsset_url': 'get the S3 URL of an AudioAsset instance for a given audio asset name', 'get_AudioAsset_local_path': 'get the local filesystem path of an AudioAsset instance from the vLLM public assets', 'load_AudioAsset_audio_and_sample_rate': 'load audio data and sample rate from an AudioAsset instance as a numpy array and float'}
```

## File: vllm-project_vllm/vllm/assets/base.py

Prompts

```
["create an AudioAsset instance with a name like 'winning_call' or 'mary_had_lamb'", 'get the filename property of an AudioAsset instance returning the .ogg filename', 'get the S3 URL of an AudioAsset instance for a given audio asset name', 'get the local filesystem path of an AudioAsset instance from the vLLM public assets', 'load audio data and sample rate from an AudioAsset instance as a numpy array and float', 'create a function that returns the cache directory path for storing downloaded vllm assets', 'create a function that downloads an asset file from the vllm public S3 bucket and returns its local path', 'test the get_cache_dir function returns a valid Path to the vllm assets cache directory', 'test the get_vllm_public_assets function downloads and caches a file from the vllm public S3 bucket', 'summarize the vllm.assets.base module which provides asset caching and S3 download utilities', 'create an ImageAsset instance with a named image like stop_sign or cherry_blossom', 'get the s3 path for a named image asset with a given file extension', 'load a PIL Image from a named image asset as a jpg file', 'load a torch.Tensor of image embeddings from a named image asset for llava 1.5 testing', 'read raw bytes of a named image asset with a given file extension', 'download a video asset from huggingface hub into the local cache directory', 'create a function that reads a video file and returns a numpy array of RGB frames', 'create a function that converts video frames to a list of PIL Image objects', 'create a function that extracts video metadata including frame count, fps, and duration', 'build a VideoAsset dataclass instance to access downloaded video frames, images, and audio']
```

Usage

```
{'create_get_cache_dir': 'create a function that returns the cache directory path for storing downloaded vllm assets', 'create_get_vllm_public_assets': 'create a function that downloads an asset file from the vllm public S3 bucket and returns its local path', 'test_get_cache_dir': 'test the get_cache_dir function returns a valid Path to the vllm assets cache directory', 'test_get_vllm_public_assets': 'test the get_vllm_public_assets function downloads and caches a file from the vllm public S3 bucket', 'summarize_base_module': 'summarize the vllm.assets.base module which provides asset caching and S3 download utilities'}
```

## File: vllm-project_vllm/vllm/assets/image.py

Prompts

```
["create an AudioAsset instance with a name like 'winning_call' or 'mary_had_lamb'", 'get the filename property of an AudioAsset instance returning the .ogg filename', 'get the S3 URL of an AudioAsset instance for a given audio asset name', 'get the local filesystem path of an AudioAsset instance from the vLLM public assets', 'load audio data and sample rate from an AudioAsset instance as a numpy array and float', 'create a function that returns the cache directory path for storing downloaded vllm assets', 'create a function that downloads an asset file from the vllm public S3 bucket and returns its local path', 'test the get_cache_dir function returns a valid Path to the vllm assets cache directory', 'test the get_vllm_public_assets function downloads and caches a file from the vllm public S3 bucket', 'summarize the vllm.assets.base module which provides asset caching and S3 download utilities', 'create an ImageAsset instance with a named image like stop_sign or cherry_blossom', 'get the s3 path for a named image asset with a given file extension', 'load a PIL Image from a named image asset as a jpg file', 'load a torch.Tensor of image embeddings from a named image asset for llava 1.5 testing', 'read raw bytes of a named image asset with a given file extension', 'download a video asset from huggingface hub into the local cache directory', 'create a function that reads a video file and returns a numpy array of RGB frames', 'create a function that converts video frames to a list of PIL Image objects', 'create a function that extracts video metadata including frame count, fps, and duration', 'build a VideoAsset dataclass instance to access downloaded video frames, images, and audio']
```

Usage

```
{'create_ImageAsset': 'create an ImageAsset instance with a named image like stop_sign or cherry_blossom', 'get_path_ImageAsset': 'get the s3 path for a named image asset with a given file extension', 'load_pil_image': 'load a PIL Image from a named image asset as a jpg file', 'load_image_embeds': 'load a torch.Tensor of image embeddings from a named image asset for llava 1.5 testing', 'read_image_bytes': 'read raw bytes of a named image asset with a given file extension'}
```

## File: vllm-project_vllm/vllm/assets/video.py

Prompts

```
["create an AudioAsset instance with a name like 'winning_call' or 'mary_had_lamb'", 'get the filename property of an AudioAsset instance returning the .ogg filename', 'get the S3 URL of an AudioAsset instance for a given audio asset name', 'get the local filesystem path of an AudioAsset instance from the vLLM public assets', 'load audio data and sample rate from an AudioAsset instance as a numpy array and float', 'create a function that returns the cache directory path for storing downloaded vllm assets', 'create a function that downloads an asset file from the vllm public S3 bucket and returns its local path', 'test the get_cache_dir function returns a valid Path to the vllm assets cache directory', 'test the get_vllm_public_assets function downloads and caches a file from the vllm public S3 bucket', 'summarize the vllm.assets.base module which provides asset caching and S3 download utilities', 'create an ImageAsset instance with a named image like stop_sign or cherry_blossom', 'get the s3 path for a named image asset with a given file extension', 'load a PIL Image from a named image asset as a jpg file', 'load a torch.Tensor of image embeddings from a named image asset for llava 1.5 testing', 'read raw bytes of a named image asset with a given file extension', 'download a video asset from huggingface hub into the local cache directory', 'create a function that reads a video file and returns a numpy array of RGB frames', 'create a function that converts video frames to a list of PIL Image objects', 'create a function that extracts video metadata including frame count, fps, and duration', 'build a VideoAsset dataclass instance to access downloaded video frames, images, and audio']
```

Usage

```
{'download_video_asset': 'download a video asset from huggingface hub into the local cache directory', 'create_video_to_ndarrays': 'create a function that reads a video file and returns a numpy array of RGB frames', 'create_video_to_pil_images_list': 'create a function that converts video frames to a list of PIL Image objects', 'create_video_get_metadata': 'create a function that extracts video metadata including frame count, fps, and duration', 'build_video_asset': 'build a VideoAsset dataclass instance to access downloaded video frames, images, and audio'}
```

