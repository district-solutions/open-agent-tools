# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/taming/lr_scheduler.py

Prompts

```
['create a LambdaWarmUpCosineScheduler with warm_up_steps, lr_min, lr_max, lr_start, and max_decay_steps parameters', 'call the schedule method on LambdaWarmUpCosineScheduler to get the learning rate multiplier for a given step', 'invoke the LambdaWarmUpCosineScheduler instance directly as a callable to compute the learning rate at step n', 'review the LambdaWarmUpCosineScheduler warmup phase that linearly interpolates learning rate from lr_start to lr_max', 'review the LambdaWarmUpCosineScheduler cosine decay phase that schedules learning rate from lr_max down to lr_min', 'download a file from a URL to a local path with a tqdm progress bar', 'compute the MD5 hash of a file given its file path', 'get or download a model checkpoint by name to a root directory with optional MD5 verification', 'retrieve a value from a nested dict or list using a slash-separated key path string', 'raise a KeyNotFoundError exception with cause, keys, and visited path context']
```

Usage

```
{'create_LambdaWarmUpCosineScheduler': 'create a LambdaWarmUpCosineScheduler with warm_up_steps, lr_min, lr_max, lr_start, and max_decay_steps parameters', 'call_LambdaWarmUpCosineScheduler_schedule': 'call the schedule method on LambdaWarmUpCosineScheduler to get the learning rate multiplier for a given step', 'call_LambdaWarmUpCosineScheduler_call': 'invoke the LambdaWarmUpCosineScheduler instance directly as a callable to compute the learning rate at step n', 'review_LambdaWarmUpCosineScheduler_warmup': 'review the LambdaWarmUpCosineScheduler warmup phase that linearly interpolates learning rate from lr_start to lr_max', 'review_LambdaWarmUpCosineScheduler_cosine_decay': 'review the LambdaWarmUpCosineScheduler cosine decay phase that schedules learning rate from lr_max down to lr_min'}
```

## File: facebookresearch_stablesignature/src/taming/util.py

Prompts

```
['create a LambdaWarmUpCosineScheduler with warm_up_steps, lr_min, lr_max, lr_start, and max_decay_steps parameters', 'call the schedule method on LambdaWarmUpCosineScheduler to get the learning rate multiplier for a given step', 'invoke the LambdaWarmUpCosineScheduler instance directly as a callable to compute the learning rate at step n', 'review the LambdaWarmUpCosineScheduler warmup phase that linearly interpolates learning rate from lr_start to lr_max', 'review the LambdaWarmUpCosineScheduler cosine decay phase that schedules learning rate from lr_max down to lr_min', 'download a file from a URL to a local path with a tqdm progress bar', 'compute the MD5 hash of a file given its file path', 'get or download a model checkpoint by name to a root directory with optional MD5 verification', 'retrieve a value from a nested dict or list using a slash-separated key path string', 'raise a KeyNotFoundError exception with cause, keys, and visited path context']
```

Usage

```
{'download_file_with_progress': 'download a file from a URL to a local path with a tqdm progress bar', 'compute_md5_hash': 'compute the MD5 hash of a file given its file path', 'get_checkpoint_path': 'get or download a model checkpoint by name to a root directory with optional MD5 verification', 'retrieve_nested_value': 'retrieve a value from a nested dict or list using a slash-separated key path string', 'handle_key_not_found': 'raise a KeyNotFoundError exception with cause, keys, and visited path context'}
```

