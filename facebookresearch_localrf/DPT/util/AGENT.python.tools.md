# Agent Python Tools

- repo: facebookresearch/localrf
- repo_uri: https://github.com/facebookresearch/localrf

## File: facebookresearch_localrf/DPT/util/io.py

Prompts

```
['read a PFM file from disk and return the numpy array data and scale value', 'write a float32 numpy array as a PFM file to disk with an optional scale', 'read an image file and return an RGB numpy array normalized to 0-1 range', 'write a depth map as both a PFM file and a PNG file with configurable bit depth', 'write a segmentation overlay image by blending labels with the input image and saving as PNG', 'visualize attention maps from a DPT model across multiple transformer layers', 'review the visualize_attention function to understand how it plots attention heatmaps', 'refactor visualize_attention to support additional model types beyond dpt_hybrid', 'summarize the visualize_attention function and its matplotlib subplot layout', 'test the visualize_attention function with a mock DPT model and sample input tensor', 'get a color palette image from a numpy mask array for PASCAL VOC, ADE20K, or Cityscapes datasets', 'get a color palette image from a numpy mask array using the ADE20K dataset palette', 'get a color palette image from a numpy mask array using the Cityscapes dataset palette', 'generate a VOC-style color palette list for a given number of segmentation classes', 'review the palette module containing VOC, ADE20K, and Cityscapes color palettes for segmentation mask visualization']
```

Usage

```
{'read_pfm_file': 'read a PFM file from disk and return the numpy array data and scale value', 'write_pfm_file': 'write a float32 numpy array as a PFM file to disk with an optional scale', 'read_image_rgb': 'read an image file and return an RGB numpy array normalized to 0-1 range', 'write_depth_map': 'write a depth map as both a PFM file and a PNG file with configurable bit depth', 'write_segmentation_image': 'write a segmentation overlay image by blending labels with the input image and saving as PNG'}
```

## File: facebookresearch_localrf/DPT/util/misc.py

Prompts

```
['read a PFM file from disk and return the numpy array data and scale value', 'write a float32 numpy array as a PFM file to disk with an optional scale', 'read an image file and return an RGB numpy array normalized to 0-1 range', 'write a depth map as both a PFM file and a PNG file with configurable bit depth', 'write a segmentation overlay image by blending labels with the input image and saving as PNG', 'visualize attention maps from a DPT model across multiple transformer layers', 'review the visualize_attention function to understand how it plots attention heatmaps', 'refactor visualize_attention to support additional model types beyond dpt_hybrid', 'summarize the visualize_attention function and its matplotlib subplot layout', 'test the visualize_attention function with a mock DPT model and sample input tensor', 'get a color palette image from a numpy mask array for PASCAL VOC, ADE20K, or Cityscapes datasets', 'get a color palette image from a numpy mask array using the ADE20K dataset palette', 'get a color palette image from a numpy mask array using the Cityscapes dataset palette', 'generate a VOC-style color palette list for a given number of segmentation classes', 'review the palette module containing VOC, ADE20K, and Cityscapes color palettes for segmentation mask visualization']
```

Usage

```
{'visualize_attention_maps': 'visualize attention maps from a DPT model across multiple transformer layers', 'review_visualize_attention': 'review the visualize_attention function to understand how it plots attention heatmaps', 'refactor_visualize_attention': 'refactor visualize_attention to support additional model types beyond dpt_hybrid', 'summarize_visualize_attention': 'summarize the visualize_attention function and its matplotlib subplot layout', 'test_visualize_attention': 'test the visualize_attention function with a mock DPT model and sample input tensor'}
```

## File: facebookresearch_localrf/DPT/util/pallete.py

Prompts

```
['read a PFM file from disk and return the numpy array data and scale value', 'write a float32 numpy array as a PFM file to disk with an optional scale', 'read an image file and return an RGB numpy array normalized to 0-1 range', 'write a depth map as both a PFM file and a PNG file with configurable bit depth', 'write a segmentation overlay image by blending labels with the input image and saving as PNG', 'visualize attention maps from a DPT model across multiple transformer layers', 'review the visualize_attention function to understand how it plots attention heatmaps', 'refactor visualize_attention to support additional model types beyond dpt_hybrid', 'summarize the visualize_attention function and its matplotlib subplot layout', 'test the visualize_attention function with a mock DPT model and sample input tensor', 'get a color palette image from a numpy mask array for PASCAL VOC, ADE20K, or Cityscapes datasets', 'get a color palette image from a numpy mask array using the ADE20K dataset palette', 'get a color palette image from a numpy mask array using the Cityscapes dataset palette', 'generate a VOC-style color palette list for a given number of segmentation classes', 'review the palette module containing VOC, ADE20K, and Cityscapes color palettes for segmentation mask visualization']
```

Usage

```
{'get_mask_pallete_visualize_mask': 'get a color palette image from a numpy mask array for PASCAL VOC, ADE20K, or Cityscapes datasets', 'get_mask_pallete_ade20k': 'get a color palette image from a numpy mask array using the ADE20K dataset palette', 'get_mask_pallete_cityscapes': 'get a color palette image from a numpy mask array using the Cityscapes dataset palette', 'get_voc_pallete_generate': 'generate a VOC-style color palette list for a given number of segmentation classes', 'review_pallete_module': 'review the palette module containing VOC, ADE20K, and Cityscapes color palettes for segmentation mask visualization'}
```

