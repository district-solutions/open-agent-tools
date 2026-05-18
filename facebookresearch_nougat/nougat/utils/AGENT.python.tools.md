# Agent Python Tools

- repo: facebookresearch/nougat
- repo_uri: https://github.com/facebookresearch/nougat.git

## File: facebookresearch_nougat/nougat/utils/checkpoint.py

Prompts

```
['download the nougat model checkpoint files from GitHub to a specified directory path', 'get the path to the nougat model checkpoint and download it if it does not exist', 'download a file from a URL and return its contents as bytes with a progress bar', 'get the torch hub directory path for the nougat model with a given model tag', 'run the checkpoint module as a CLI script to download the default nougat model checkpoint', 'create an ImageDataset from a list of image paths with a custom preparation function', 'create a LazyDataset to lazily load and rasterize PDF pages for model inference', 'create a SciPDFDataset from a JSONL index file with seek map for scientific PDF data', 'create a NougatDataset wrapping SciPDFDataset to produce tokenized image and label pairs for training', 'use the ignore_none_collate static method to filter None entries from a PyTorch DataLoader batch', 'get the default batch size based on available GPU VRAM or fall back to CPU', 'move a PyTorch model to CUDA or MPS device with optional bfloat16 precision', 'check if CUDA is available and compute batch size from GPU memory properties', 'convert a PyTorch model to bfloat16 precision before moving it to the GPU', 'handle MPS device availability for Apple Silicon and fall back to CUDA or CPU']
```

Usage

```
{'download_nougat_checkpoint': 'download the nougat model checkpoint files from GitHub to a specified directory path', 'get_checkpoint_path': 'get the path to the nougat model checkpoint and download it if it does not exist', 'download_file_with_progress': 'download a file from a URL and return its contents as bytes with a progress bar', 'get_torch_hub_path': 'get the torch hub directory path for the nougat model with a given model tag', 'run_checkpoint_download_cli': 'run the checkpoint module as a CLI script to download the default nougat model checkpoint'}
```

## File: facebookresearch_nougat/nougat/utils/dataset.py

Prompts

```
['download the nougat model checkpoint files from GitHub to a specified directory path', 'get the path to the nougat model checkpoint and download it if it does not exist', 'download a file from a URL and return its contents as bytes with a progress bar', 'get the torch hub directory path for the nougat model with a given model tag', 'run the checkpoint module as a CLI script to download the default nougat model checkpoint', 'create an ImageDataset from a list of image paths with a custom preparation function', 'create a LazyDataset to lazily load and rasterize PDF pages for model inference', 'create a SciPDFDataset from a JSONL index file with seek map for scientific PDF data', 'create a NougatDataset wrapping SciPDFDataset to produce tokenized image and label pairs for training', 'use the ignore_none_collate static method to filter None entries from a PyTorch DataLoader batch', 'get the default batch size based on available GPU VRAM or fall back to CPU', 'move a PyTorch model to CUDA or MPS device with optional bfloat16 precision', 'check if CUDA is available and compute batch size from GPU memory properties', 'convert a PyTorch model to bfloat16 precision before moving it to the GPU', 'handle MPS device availability for Apple Silicon and fall back to CUDA or CPU']
```

Usage

```
{'create_ImageDataset': 'create an ImageDataset from a list of image paths with a custom preparation function', 'create_LazyDataset': 'create a LazyDataset to lazily load and rasterize PDF pages for model inference', 'create_SciPDFDataset': 'create a SciPDFDataset from a JSONL index file with seek map for scientific PDF data', 'create_NougatDataset': 'create a NougatDataset wrapping SciPDFDataset to produce tokenized image and label pairs for training', 'use_ignore_none_collate': 'use the ignore_none_collate static method to filter None entries from a PyTorch DataLoader batch'}
```

## File: facebookresearch_nougat/nougat/utils/device.py

Prompts

```
['download the nougat model checkpoint files from GitHub to a specified directory path', 'get the path to the nougat model checkpoint and download it if it does not exist', 'download a file from a URL and return its contents as bytes with a progress bar', 'get the torch hub directory path for the nougat model with a given model tag', 'run the checkpoint module as a CLI script to download the default nougat model checkpoint', 'create an ImageDataset from a list of image paths with a custom preparation function', 'create a LazyDataset to lazily load and rasterize PDF pages for model inference', 'create a SciPDFDataset from a JSONL index file with seek map for scientific PDF data', 'create a NougatDataset wrapping SciPDFDataset to produce tokenized image and label pairs for training', 'use the ignore_none_collate static method to filter None entries from a PyTorch DataLoader batch', 'get the default batch size based on available GPU VRAM or fall back to CPU', 'move a PyTorch model to CUDA or MPS device with optional bfloat16 precision', 'check if CUDA is available and compute batch size from GPU memory properties', 'convert a PyTorch model to bfloat16 precision before moving it to the GPU', 'handle MPS device availability for Apple Silicon and fall back to CUDA or CPU']
```

Usage

```
{'get_default_batch_size': 'get the default batch size based on available GPU VRAM or fall back to CPU', 'move_model_to_device': 'move a PyTorch model to CUDA or MPS device with optional bfloat16 precision', 'check_gpu_availability': 'check if CUDA is available and compute batch size from GPU memory properties', 'convert_model_to_bf16': 'convert a PyTorch model to bfloat16 precision before moving it to the GPU', 'handle_mps_fallback': 'handle MPS device availability for Apple Silicon and fall back to CUDA or CPU'}
```

