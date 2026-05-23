# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/TensoRF/extra/auto_run_paramsets.py

Prompts

```
['generate all combinations of hyperparameter values from a parameter dictionary for grid search experiments', 'format a single hyperparameter key and value into a command line argument string', 'acquire a directory-based file lock by creating a lock folder with retry logic', 'release a directory-based file lock by removing the lock folder', 'check if a stop signal folder exists to halt experiment execution', 'run the compute_metrics script with --exp and --paramStr args to evaluate PSNR, SSIM, and LPIPS metrics', 'run rgb_ssim to compute the structural similarity index between two RGB images', 'run rgb_lpips to compute the LPIPS distance between two RGB images using alex or vgg network', 'run init_lpips to initialize an LPIPS model with alex or vgg network on a device', 'run findItem to search a list of strings for an item that starts with a target prefix']
```

Usage

```
{'get_param_list': 'generate all combinations of hyperparameter values from a parameter dictionary for grid search experiments', 'get_param_str': 'format a single hyperparameter key and value into a command line argument string', 'getFolderLocker': 'acquire a directory-based file lock by creating a lock folder with retry logic', 'releaseFolderLocker': 'release a directory-based file lock by removing the lock folder', 'getStopFolder': 'check if a stop signal folder exists to halt experiment execution'}
```

## File: facebookresearch_omnimatterf/third_party/TensoRF/extra/compute_metrics.py

Prompts

```
['generate all combinations of hyperparameter values from a parameter dictionary for grid search experiments', 'format a single hyperparameter key and value into a command line argument string', 'acquire a directory-based file lock by creating a lock folder with retry logic', 'release a directory-based file lock by removing the lock folder', 'check if a stop signal folder exists to halt experiment execution', 'run the compute_metrics script with --exp and --paramStr args to evaluate PSNR, SSIM, and LPIPS metrics', 'run rgb_ssim to compute the structural similarity index between two RGB images', 'run rgb_lpips to compute the LPIPS distance between two RGB images using alex or vgg network', 'run init_lpips to initialize an LPIPS model with alex or vgg network on a device', 'run findItem to search a list of strings for an item that starts with a target prefix']
```

Usage

```
{'run_compute_metrics': 'run the compute_metrics script with --exp and --paramStr args to evaluate PSNR, SSIM, and LPIPS metrics', 'run_rgb_ssim': 'run rgb_ssim to compute the structural similarity index between two RGB images', 'run_rgb_lpips': 'run rgb_lpips to compute the LPIPS distance between two RGB images using alex or vgg network', 'run_init_lpips': 'run init_lpips to initialize an LPIPS model with alex or vgg network on a device', 'run_findItem': 'run findItem to search a list of strings for an item that starts with a target prefix'}
```

