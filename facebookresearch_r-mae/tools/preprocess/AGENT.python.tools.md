# Agent Python Tools

- repo: facebookresearch/r-mae
- repo_uri: https://github.com/facebookresearch/r-mae

## File: facebookresearch_r-mae/tools/preprocess/create_fh_mask_for_coco.py

Prompts

```
['run the CLI tool to compute Felzenszwalb-Huttenlocher segmentation masks for all JPG images in a COCO image folder', 'run compute_fh_segmentation on a numpy image array with custom scales and min_sizes to get stacked segmentation masks', 'run _process_image on a single JPG file path to generate and save a Felzenszwalb segmentation NPY file', 'refactor the tool to accept Felzenszwalb scale and min_size parameters as lists instead of comma-separated strings', 'review the main function to understand how it resolves paths, validates folders, and launches multiprocessing for batch segmentation', 'run the Felzenszwalb segmentation algorithm on an image with configurable scale and min_size parameters', 'create Felzenszwalb segmentation masks for all ImageNet images using multiprocessing and save as numpy arrays', 'process a single image by computing Felzenszwalb segmentation and saving the result as an npy file', 'get a list of all image file paths from an ImageNet ImageFolder dataset directory', 'compute Felzenszwalb segmentations at multiple scales and min sizes and stack results into a numpy array']
```

Usage

```
{'run_fh_mask_coco': 'run the CLI tool to compute Felzenszwalb-Huttenlocher segmentation masks for all JPG images in a COCO image folder', 'run_compute_fh_segmentation': 'run compute_fh_segmentation on a numpy image array with custom scales and min_sizes to get stacked segmentation masks', 'run_process_single_image': 'run _process_image on a single JPG file path to generate and save a Felzenszwalb segmentation NPY file', 'refactor_fh_scales': 'refactor the tool to accept Felzenszwalb scale and min_size parameters as lists instead of comma-separated strings', 'review_main': 'review the main function to understand how it resolves paths, validates folders, and launches multiprocessing for batch segmentation'}
```

## File: facebookresearch_r-mae/tools/preprocess/create_fh_mask_for_imnet.py

Prompts

```
['run the CLI tool to compute Felzenszwalb-Huttenlocher segmentation masks for all JPG images in a COCO image folder', 'run compute_fh_segmentation on a numpy image array with custom scales and min_sizes to get stacked segmentation masks', 'run _process_image on a single JPG file path to generate and save a Felzenszwalb segmentation NPY file', 'refactor the tool to accept Felzenszwalb scale and min_size parameters as lists instead of comma-separated strings', 'review the main function to understand how it resolves paths, validates folders, and launches multiprocessing for batch segmentation', 'run the Felzenszwalb segmentation algorithm on an image with configurable scale and min_size parameters', 'create Felzenszwalb segmentation masks for all ImageNet images using multiprocessing and save as numpy arrays', 'process a single image by computing Felzenszwalb segmentation and saving the result as an npy file', 'get a list of all image file paths from an ImageNet ImageFolder dataset directory', 'compute Felzenszwalb segmentations at multiple scales and min sizes and stack results into a numpy array']
```

Usage

```
{'run_felzenszwalb_segmentation': 'run the Felzenszwalb segmentation algorithm on an image with configurable scale and min_size parameters', 'create_fh_masks_for_imagenet': 'create Felzenszwalb segmentation masks for all ImageNet images using multiprocessing and save as numpy arrays', 'process_single_image_segmentation': 'process a single image by computing Felzenszwalb segmentation and saving the result as an npy file', 'get_imagenet_image_files': 'get a list of all image file paths from an ImageNet ImageFolder dataset directory', 'compute_multi_scale_segmentation': 'compute Felzenszwalb segmentations at multiple scales and min sizes and stack results into a numpy array'}
```

