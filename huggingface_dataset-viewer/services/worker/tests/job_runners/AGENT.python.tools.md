# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/worker/tests/job_runners/test__job_runner_with_cache.py

Prompts

```
['test the parametrized cache subdirectory hash generation for different dataset config and split combinations', 'test the pre_compute and post_compute cache directory creation and cleanup lifecycle', 'test the DummyJobRunner compute method that returns a CompleteJobResult with a sample column', 'test the get_job_runner pytest fixture that creates DummyJobRunner instances with job info params', 'test the helper function that asserts a cache path exists or does not exist', 'test that set_datasets_cache redirects HF_DATASETS_CACHE, HF_HUB_CACHE, and HF_XET_CACHE to a custom path', 'assert a datasets cache path exists or not and validate its datasets, hub, and xet subdirectories', "get the job type string 'dummy-job-runner' from the DummyJobRunner test class", 'compute and return a CompleteJobResult with a simple dictionary payload for testing']
```

Usage

```
{'test_get_cache_subdirectory': 'test the parametrized cache subdirectory hash generation for different dataset config and split combinations', 'test_pre_compute_post_compute': 'test the pre_compute and post_compute cache directory creation and cleanup lifecycle', 'test_DummyJobRunner_compute': 'test the DummyJobRunner compute method that returns a CompleteJobResult with a sample column', 'test_get_job_runner_fixture': 'test the get_job_runner pytest fixture that creates DummyJobRunner instances with job info params', 'test_assert_datasets_cache_path': 'test the helper function that asserts a cache path exists or does not exist'}
```

## File: huggingface_dataset-viewer/services/worker/tests/job_runners/test__job_runner_with_datasets_cache.py

Prompts

```
['test the parametrized cache subdirectory hash generation for different dataset config and split combinations', 'test the pre_compute and post_compute cache directory creation and cleanup lifecycle', 'test the DummyJobRunner compute method that returns a CompleteJobResult with a sample column', 'test the get_job_runner pytest fixture that creates DummyJobRunner instances with job info params', 'test the helper function that asserts a cache path exists or does not exist', 'test that set_datasets_cache redirects HF_DATASETS_CACHE, HF_HUB_CACHE, and HF_XET_CACHE to a custom path', 'assert a datasets cache path exists or not and validate its datasets, hub, and xet subdirectories', "get the job type string 'dummy-job-runner' from the DummyJobRunner test class", 'compute and return a CompleteJobResult with a simple dictionary payload for testing']
```

Usage

```
{'test_set_datasets_cache': 'test that set_datasets_cache redirects HF_DATASETS_CACHE, HF_HUB_CACHE, and HF_XET_CACHE to a custom path', 'test_pre_compute_post_compute': 'test that pre_compute creates a per-job cache subdirectory and post_compute cleans it up', 'assert_datasets_cache_path': 'assert a datasets cache path exists or not and validate its datasets, hub, and xet subdirectories', 'DummyJobRunner_get_job_type': "get the job type string 'dummy-job-runner' from the DummyJobRunner test class", 'DummyJobRunner_compute': 'compute and return a CompleteJobResult with a simple dictionary payload for testing'}
```

