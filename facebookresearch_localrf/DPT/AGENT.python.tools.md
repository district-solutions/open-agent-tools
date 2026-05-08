# Agent Python Tools

- repo: facebookresearch/localrf
- repo_uri: https://github.com/facebookresearch/localrf

## File: facebookresearch_localrf/DPT/run_monodepth.py

Prompts

```
['run the monodepth CLI to compute depth maps for images in an input folder', 'run the DPT-Hybrid model to generate depth predictions from a folder of images', 'run the DPT-Large model with vitl16_384 backbone to compute depth maps', 'run monodepth with KITTI crop mode to process images with 1216x352 cropping', 'run the MidasNet v2.1 convolutional model to compute depth maps for input images', 'run the DPT segmentation model on images in an input folder and save output maps', 'run the DPT large model with vitl16_384 backbone on images for semantic segmentation', 'run the DPT hybrid model with vitb_rn50_384 backbone on images for semantic segmentation', 'run the DPT segmentation model with CUDA half precision and channels last optimization enabled', 'run the DPT segmentation model using a custom model weights file path']
```

Usage

```
{'run_monodepth_depth_maps': 'run the monodepth CLI to compute depth maps for images in an input folder', 'run_dpt_hybrid_model': 'run the DPT-Hybrid model to generate depth predictions from a folder of images', 'run_dpt_large_model': 'run the DPT-Large model with vitl16_384 backbone to compute depth maps', 'run_kitti_crop_depth': 'run monodepth with KITTI crop mode to process images with 1216x352 cropping', 'run_midas_v21_depth': 'run the MidasNet v2.1 convolutional model to compute depth maps for input images'}
```

## File: facebookresearch_localrf/DPT/run_segmentation.py

Prompts

```
['run the monodepth CLI to compute depth maps for images in an input folder', 'run the DPT-Hybrid model to generate depth predictions from a folder of images', 'run the DPT-Large model with vitl16_384 backbone to compute depth maps', 'run monodepth with KITTI crop mode to process images with 1216x352 cropping', 'run the MidasNet v2.1 convolutional model to compute depth maps for input images', 'run the DPT segmentation model on images in an input folder and save output maps', 'run the DPT large model with vitl16_384 backbone on images for semantic segmentation', 'run the DPT hybrid model with vitb_rn50_384 backbone on images for semantic segmentation', 'run the DPT segmentation model with CUDA half precision and channels last optimization enabled', 'run the DPT segmentation model using a custom model weights file path']
```

Usage

```
{'run_segmentation': 'run the DPT segmentation model on images in an input folder and save output maps', 'run_dpt_large': 'run the DPT large model with vitl16_384 backbone on images for semantic segmentation', 'run_dpt_hybrid': 'run the DPT hybrid model with vitb_rn50_384 backbone on images for semantic segmentation', 'run_optimized_segmentation': 'run the DPT segmentation model with CUDA half precision and channels last optimization enabled', 'run_segmentation_custom_weights': 'run the DPT segmentation model using a custom model weights file path'}
```

