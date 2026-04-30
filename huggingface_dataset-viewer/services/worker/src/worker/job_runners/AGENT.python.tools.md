# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/worker/src/worker/job_runners/_job_runner_with_cache.py

Prompts

```
['create a JobRunnerWithCache instance with job_info, app_config, and a cache_directory Path', 'generate a unique cache subdirectory name using get_cache_subdirectory with a configurable number of random digits', 'call pre_compute to create a temporary cache directory before running a job', 'call post_compute to remove the temporary cache directory and free storage after a job finishes', 'review the JobRunnerWithCache base class and its cache directory lifecycle management methods', 'create a JobRunnerWithDatasetsCache instance with job info, app config, and a datasets cache path', 'refactor set_datasets_cache to support additional cache directories beyond datasets, hub, and xet', 'review the pre_compute method that sets the datasets cache to the job subdirectory before computation', 'review the post_compute method that resets the datasets cache to the base directory after computation', 'test set_datasets_cache to verify HF_DATASETS_CACHE, HF_HUB_CACHE, and HF_XET_CACHE are set correctly']
```

Usage

```
{'create_job_runner_with_cache': 'create a JobRunnerWithCache instance with job_info, app_config, and a cache_directory Path', 'generate_cache_subdirectory': 'generate a unique cache subdirectory name using get_cache_subdirectory with a configurable number of random digits', 'init_cache_before_compute': 'call pre_compute to create a temporary cache directory before running a job', 'cleanup_cache_after_compute': 'call post_compute to remove the temporary cache directory and free storage after a job finishes', 'review_job_runner_with_cache_class': 'review the JobRunnerWithCache base class and its cache directory lifecycle management methods'}
```

## File: huggingface_dataset-viewer/services/worker/src/worker/job_runners/_job_runner_with_datasets_cache.py

Prompts

```
['create a JobRunnerWithCache instance with job_info, app_config, and a cache_directory Path', 'generate a unique cache subdirectory name using get_cache_subdirectory with a configurable number of random digits', 'call pre_compute to create a temporary cache directory before running a job', 'call post_compute to remove the temporary cache directory and free storage after a job finishes', 'review the JobRunnerWithCache base class and its cache directory lifecycle management methods', 'create a JobRunnerWithDatasetsCache instance with job info, app config, and a datasets cache path', 'refactor set_datasets_cache to support additional cache directories beyond datasets, hub, and xet', 'review the pre_compute method that sets the datasets cache to the job subdirectory before computation', 'review the post_compute method that resets the datasets cache to the base directory after computation', 'test set_datasets_cache to verify HF_DATASETS_CACHE, HF_HUB_CACHE, and HF_XET_CACHE are set correctly']
```

Usage

```
{'create_JOB_RUNNER_WITH_DATASETS_CACHE': 'create a JobRunnerWithDatasetsCache instance with job info, app config, and a datasets cache path', 'refactor_SET_DATASETS_CACHE': 'refactor set_datasets_cache to support additional cache directories beyond datasets, hub, and xet', 'review_PRE_COMPUTE': 'review the pre_compute method that sets the datasets cache to the job subdirectory before computation', 'review_POST_COMPUTE': 'review the post_compute method that resets the datasets cache to the base directory after computation', 'test_SET_DATASETS_CACHE': 'test set_datasets_cache to verify HF_DATASETS_CACHE, HF_HUB_CACHE, and HF_XET_CACHE are set correctly'}
```

