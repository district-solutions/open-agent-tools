# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/banding_removal/fastmri/common/evaluate.py

Prompts

```
['run the evaluate CLI to compute MSE, NMSE, PSNR, and SSIM metrics on MRI reconstruction HDF5 files', 'run the mse function to compute mean squared error between ground truth and predicted arrays', 'run the nmse function to compute normalized mean squared error between ground truth and predicted arrays', 'run the psnr function to compute peak signal to noise ratio between ground truth and predicted arrays', 'review the Metrics class that maintains running statistics for MSE, NMSE, PSNR, and SSIM across multiple samples', 'create a grid of image blocks arranged side by side with optional loss captions', 'create an image grid with a header showing training args and epoch loss history', 'create an image grid with per-image loss values displayed as captions below each block', 'review the grid function that arranges tensor image blocks into a composite PIL image', 'test the grid function with image blocks to verify correct layout and caption rendering', 'create a RandomMask instance to generate random k-space undersampling masks with configurable acceleration factors', 'create an EquiSpacedMask instance to generate evenly spaced k-space undersampling masks for MRI reconstruction', 'create a MagicMask instance to generate phase-shifted aliasing pattern masks for k-space undersampling', 'use the mask_factory function to instantiate any named mask type like random equispaced or magic by string name', 'call a MaskFunc instance with a shape and seed to produce a combined center and acceleration mask tensor', 'save MRI reconstructions from a dictionary into h5 files in an output directory for leaderboard submission', 'convert a complex torch tensor with real and imaginary channels into a complex numpy array', 'create a JSON submission file for the fastMRI leaderboard with model metadata and reconstruction URL', 'build a memory-efficient PyTorch dataset that fetches items lazily via a callback function with start, end, and increment', 'measure total host memory usage in gigabytes by inspecting all non-CUDA PyTorch tensors tracked by the garbage collector']
```

Usage

```
{'run_evaluate_cli': 'run the evaluate CLI to compute MSE, NMSE, PSNR, and SSIM metrics on MRI reconstruction HDF5 files', 'run_mse_function': 'run the mse function to compute mean squared error between ground truth and predicted arrays', 'run_nmse_function': 'run the nmse function to compute normalized mean squared error between ground truth and predicted arrays', 'run_psnr_function': 'run the psnr function to compute peak signal to noise ratio between ground truth and predicted arrays', 'review_Metrics_class': 'review the Metrics class that maintains running statistics for MSE, NMSE, PSNR, and SSIM across multiple samples'}
```

## File: facebookresearch_fastmri/banding_removal/fastmri/common/image_grid.py

Prompts

```
['run the evaluate CLI to compute MSE, NMSE, PSNR, and SSIM metrics on MRI reconstruction HDF5 files', 'run the mse function to compute mean squared error between ground truth and predicted arrays', 'run the nmse function to compute normalized mean squared error between ground truth and predicted arrays', 'run the psnr function to compute peak signal to noise ratio between ground truth and predicted arrays', 'review the Metrics class that maintains running statistics for MSE, NMSE, PSNR, and SSIM across multiple samples', 'create a grid of image blocks arranged side by side with optional loss captions', 'create an image grid with a header showing training args and epoch loss history', 'create an image grid with per-image loss values displayed as captions below each block', 'review the grid function that arranges tensor image blocks into a composite PIL image', 'test the grid function with image blocks to verify correct layout and caption rendering', 'create a RandomMask instance to generate random k-space undersampling masks with configurable acceleration factors', 'create an EquiSpacedMask instance to generate evenly spaced k-space undersampling masks for MRI reconstruction', 'create a MagicMask instance to generate phase-shifted aliasing pattern masks for k-space undersampling', 'use the mask_factory function to instantiate any named mask type like random equispaced or magic by string name', 'call a MaskFunc instance with a shape and seed to produce a combined center and acceleration mask tensor', 'save MRI reconstructions from a dictionary into h5 files in an output directory for leaderboard submission', 'convert a complex torch tensor with real and imaginary channels into a complex numpy array', 'create a JSON submission file for the fastMRI leaderboard with model metadata and reconstruction URL', 'build a memory-efficient PyTorch dataset that fetches items lazily via a callback function with start, end, and increment', 'measure total host memory usage in gigabytes by inspecting all non-CUDA PyTorch tensors tracked by the garbage collector']
```

Usage

```
{'create_image_grid': 'create a grid of image blocks arranged side by side with optional loss captions', 'create_grid_with_runinfo': 'create an image grid with a header showing training args and epoch loss history', 'create_grid_with_loss_captions': 'create an image grid with per-image loss values displayed as captions below each block', 'review_grid_function': 'review the grid function that arranges tensor image blocks into a composite PIL image', 'test_grid_layout': 'test the grid function with image blocks to verify correct layout and caption rendering'}
```

## File: facebookresearch_fastmri/banding_removal/fastmri/common/subsample.py

Prompts

```
['run the evaluate CLI to compute MSE, NMSE, PSNR, and SSIM metrics on MRI reconstruction HDF5 files', 'run the mse function to compute mean squared error between ground truth and predicted arrays', 'run the nmse function to compute normalized mean squared error between ground truth and predicted arrays', 'run the psnr function to compute peak signal to noise ratio between ground truth and predicted arrays', 'review the Metrics class that maintains running statistics for MSE, NMSE, PSNR, and SSIM across multiple samples', 'create a grid of image blocks arranged side by side with optional loss captions', 'create an image grid with a header showing training args and epoch loss history', 'create an image grid with per-image loss values displayed as captions below each block', 'review the grid function that arranges tensor image blocks into a composite PIL image', 'test the grid function with image blocks to verify correct layout and caption rendering', 'create a RandomMask instance to generate random k-space undersampling masks with configurable acceleration factors', 'create an EquiSpacedMask instance to generate evenly spaced k-space undersampling masks for MRI reconstruction', 'create a MagicMask instance to generate phase-shifted aliasing pattern masks for k-space undersampling', 'use the mask_factory function to instantiate any named mask type like random equispaced or magic by string name', 'call a MaskFunc instance with a shape and seed to produce a combined center and acceleration mask tensor', 'save MRI reconstructions from a dictionary into h5 files in an output directory for leaderboard submission', 'convert a complex torch tensor with real and imaginary channels into a complex numpy array', 'create a JSON submission file for the fastMRI leaderboard with model metadata and reconstruction URL', 'build a memory-efficient PyTorch dataset that fetches items lazily via a callback function with start, end, and increment', 'measure total host memory usage in gigabytes by inspecting all non-CUDA PyTorch tensors tracked by the garbage collector']
```

Usage

```
{'create_random_mask': 'create a RandomMask instance to generate random k-space undersampling masks with configurable acceleration factors', 'create_equispaced_mask': 'create an EquiSpacedMask instance to generate evenly spaced k-space undersampling masks for MRI reconstruction', 'create_magic_mask': 'create a MagicMask instance to generate phase-shifted aliasing pattern masks for k-space undersampling', 'use_mask_factory': 'use the mask_factory function to instantiate any named mask type like random equispaced or magic by string name', 'call_mask_func': 'call a MaskFunc instance with a shape and seed to produce a combined center and acceleration mask tensor'}
```

## File: facebookresearch_fastmri/banding_removal/fastmri/common/utils.py

Prompts

```
['run the evaluate CLI to compute MSE, NMSE, PSNR, and SSIM metrics on MRI reconstruction HDF5 files', 'run the mse function to compute mean squared error between ground truth and predicted arrays', 'run the nmse function to compute normalized mean squared error between ground truth and predicted arrays', 'run the psnr function to compute peak signal to noise ratio between ground truth and predicted arrays', 'review the Metrics class that maintains running statistics for MSE, NMSE, PSNR, and SSIM across multiple samples', 'create a grid of image blocks arranged side by side with optional loss captions', 'create an image grid with a header showing training args and epoch loss history', 'create an image grid with per-image loss values displayed as captions below each block', 'review the grid function that arranges tensor image blocks into a composite PIL image', 'test the grid function with image blocks to verify correct layout and caption rendering', 'create a RandomMask instance to generate random k-space undersampling masks with configurable acceleration factors', 'create an EquiSpacedMask instance to generate evenly spaced k-space undersampling masks for MRI reconstruction', 'create a MagicMask instance to generate phase-shifted aliasing pattern masks for k-space undersampling', 'use the mask_factory function to instantiate any named mask type like random equispaced or magic by string name', 'call a MaskFunc instance with a shape and seed to produce a combined center and acceleration mask tensor', 'save MRI reconstructions from a dictionary into h5 files in an output directory for leaderboard submission', 'convert a complex torch tensor with real and imaginary channels into a complex numpy array', 'create a JSON submission file for the fastMRI leaderboard with model metadata and reconstruction URL', 'build a memory-efficient PyTorch dataset that fetches items lazily via a callback function with start, end, and increment', 'measure total host memory usage in gigabytes by inspecting all non-CUDA PyTorch tensors tracked by the garbage collector']
```

Usage

```
{'save_reconstructions': 'save MRI reconstructions from a dictionary into h5 files in an output directory for leaderboard submission', 'tensor_to_complex_np': 'convert a complex torch tensor with real and imaginary channels into a complex numpy array', 'create_submission_file': 'create a JSON submission file for the fastMRI leaderboard with model metadata and reconstruction URL', 'CallbackDataset': 'build a memory-efficient PyTorch dataset that fetches items lazily via a callback function with start, end, and increment', 'host_memory_usage_in_gb': 'measure total host memory usage in gigabytes by inspecting all non-CUDA PyTorch tensors tracked by the garbage collector'}
```

