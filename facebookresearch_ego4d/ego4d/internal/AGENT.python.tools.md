# Agent Python Tools

- repo: facebookresearch/ego4d
- repo_uri: https://github.com/facebookresearch/ego4d

## File: facebookresearch_ego4d/ego4d/internal/downscale.py

Prompts

```
['run the main function to downscale ego4d take videos across a SLURM cluster', 'run call_ffmpeg to downscale a single video from source to target path using ffmpeg', 'run process_all to downscale a batch of videos in parallel using ThreadPoolExecutor', 'review the call_ffmpeg function that builds and executes an ffmpeg command for video downscaling', 'review the main function that batches video paths and submits jobs via submitit AutoExecutor', 'build a python module that creates an S3 client for a given bucket using get_client', 'list S3 objects in a bucket prefix using S3Downloader.ls with recursive option', 'download an S3 file to a local path using S3Downloader.copy with an optional callback', 'generate a presigned URL for an S3 object using StreamPathMgr.open with expiration', 'get file metadata for an S3 object using S3Downloader.file_desc to retrieve size and path']
```

Usage

```
{'run_downscale_main': 'run the main function to downscale ego4d take videos across a SLURM cluster', 'run_call_ffmpeg': 'run call_ffmpeg to downscale a single video from source to target path using ffmpeg', 'run_process_all': 'run process_all to downscale a batch of videos in parallel using ThreadPoolExecutor', 'review_call_ffmpeg': 'review the call_ffmpeg function that builds and executes an ffmpeg command for video downscaling', 'review_main': 'review the main function that batches video paths and submits jobs via submitit AutoExecutor'}
```

## File: facebookresearch_ego4d/ego4d/internal/s3.py

Prompts

```
['run the main function to downscale ego4d take videos across a SLURM cluster', 'run call_ffmpeg to downscale a single video from source to target path using ffmpeg', 'run process_all to downscale a batch of videos in parallel using ThreadPoolExecutor', 'review the call_ffmpeg function that builds and executes an ffmpeg command for video downscaling', 'review the main function that batches video paths and submits jobs via submitit AutoExecutor', 'build a python module that creates an S3 client for a given bucket using get_client', 'list S3 objects in a bucket prefix using S3Downloader.ls with recursive option', 'download an S3 file to a local path using S3Downloader.copy with an optional callback', 'generate a presigned URL for an S3 object using StreamPathMgr.open with expiration', 'get file metadata for an S3 object using S3Downloader.file_desc to retrieve size and path']
```

Usage

```
{'build_s3_client': 'build a python module that creates an S3 client for a given bucket using get_client', 'list_s3_objects': 'list S3 objects in a bucket prefix using S3Downloader.ls with recursive option', 'download_s3_file': 'download an S3 file to a local path using S3Downloader.copy with an optional callback', 'generate_presigned_url': 'generate a presigned URL for an S3 object using StreamPathMgr.open with expiration', 'get_s3_file_desc': 'get file metadata for an S3 object using S3Downloader.file_desc to retrieve size and path'}
```

