# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/openai/protocol.py

Prompts

```
['create an ImageGenerationsRequest with a prompt, size, and optional upscaling parameters for image generation', 'create a VideoGenerationsRequest with a prompt, duration in seconds, and optional frame interpolation settings for video generation', 'create a MeshGenerationsRequest with a prompt and optional input image for 3D mesh generation', 'build a VideoResponse model with status, progress, url, and metadata fields for tracking async video generation jobs', 'build a MeshResponse model with status, progress, url, and file metadata fields for tracking async 3D mesh generation jobs', 'create a CloudStorage instance configured with S3 credentials from environment variables', 'upload a local file to an S3 bucket with auto-detected content type and return the object URL', 'upload a local file to S3 and automatically delete the local copy after successful upload', 'test whether CloudStorage is enabled by checking S3 configuration and boto3 availability', 'create the global cloud_storage singleton instance for use across the application', 'build SamplingParams from request kwargs with automatic size parsing, quality resolution, and None filtering', 'save an image from URL, base64 data, or UploadFile to a target file path', 'process a generation batch via scheduler client and return output file paths and result metadata', 'merge multiple image input sources into a single flattened list of non-None items', 'adjust output quality string like maximum high medium low or default to a numeric compression value']
```

Usage

```
{'create_image_generation_request': 'create an ImageGenerationsRequest with a prompt, size, and optional upscaling parameters for image generation', 'create_video_generation_request': 'create a VideoGenerationsRequest with a prompt, duration in seconds, and optional frame interpolation settings for video generation', 'create_mesh_generation_request': 'create a MeshGenerationsRequest with a prompt and optional input image for 3D mesh generation', 'build_video_response_model': 'build a VideoResponse model with status, progress, url, and metadata fields for tracking async video generation jobs', 'build_mesh_response_model': 'build a MeshResponse model with status, progress, url, and file metadata fields for tracking async 3D mesh generation jobs'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/openai/storage.py

Prompts

```
['create an ImageGenerationsRequest with a prompt, size, and optional upscaling parameters for image generation', 'create a VideoGenerationsRequest with a prompt, duration in seconds, and optional frame interpolation settings for video generation', 'create a MeshGenerationsRequest with a prompt and optional input image for 3D mesh generation', 'build a VideoResponse model with status, progress, url, and metadata fields for tracking async video generation jobs', 'build a MeshResponse model with status, progress, url, and file metadata fields for tracking async 3D mesh generation jobs', 'create a CloudStorage instance configured with S3 credentials from environment variables', 'upload a local file to an S3 bucket with auto-detected content type and return the object URL', 'upload a local file to S3 and automatically delete the local copy after successful upload', 'test whether CloudStorage is enabled by checking S3 configuration and boto3 availability', 'create the global cloud_storage singleton instance for use across the application', 'build SamplingParams from request kwargs with automatic size parsing, quality resolution, and None filtering', 'save an image from URL, base64 data, or UploadFile to a target file path', 'process a generation batch via scheduler client and return output file paths and result metadata', 'merge multiple image input sources into a single flattened list of non-None items', 'adjust output quality string like maximum high medium low or default to a numeric compression value']
```

Usage

```
{'create_CloudStorage': 'create a CloudStorage instance configured with S3 credentials from environment variables', 'upload_file_S3': 'upload a local file to an S3 bucket with auto-detected content type and return the object URL', 'upload_and_cleanup_S3': 'upload a local file to S3 and automatically delete the local copy after successful upload', 'test_is_enabled': 'test whether CloudStorage is enabled by checking S3 configuration and boto3 availability', 'create_cloud_storage_global': 'create the global cloud_storage singleton instance for use across the application'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/openai/utils.py

Prompts

```
['create an ImageGenerationsRequest with a prompt, size, and optional upscaling parameters for image generation', 'create a VideoGenerationsRequest with a prompt, duration in seconds, and optional frame interpolation settings for video generation', 'create a MeshGenerationsRequest with a prompt and optional input image for 3D mesh generation', 'build a VideoResponse model with status, progress, url, and metadata fields for tracking async video generation jobs', 'build a MeshResponse model with status, progress, url, and file metadata fields for tracking async 3D mesh generation jobs', 'create a CloudStorage instance configured with S3 credentials from environment variables', 'upload a local file to an S3 bucket with auto-detected content type and return the object URL', 'upload a local file to S3 and automatically delete the local copy after successful upload', 'test whether CloudStorage is enabled by checking S3 configuration and boto3 availability', 'create the global cloud_storage singleton instance for use across the application', 'build SamplingParams from request kwargs with automatic size parsing, quality resolution, and None filtering', 'save an image from URL, base64 data, or UploadFile to a target file path', 'process a generation batch via scheduler client and return output file paths and result metadata', 'merge multiple image input sources into a single flattened list of non-None items', 'adjust output quality string like maximum high medium low or default to a numeric compression value']
```

Usage

```
{'build_sampling_params': 'build SamplingParams from request kwargs with automatic size parsing, quality resolution, and None filtering', 'save_image_to_path': 'save an image from URL, base64 data, or UploadFile to a target file path', 'process_generation_batch': 'process a generation batch via scheduler client and return output file paths and result metadata', 'merge_image_input_list': 'merge multiple image input sources into a single flattened list of non-None items', 'adjust_output_quality': 'adjust output quality string like maximum high medium low or default to a numeric compression value'}
```

