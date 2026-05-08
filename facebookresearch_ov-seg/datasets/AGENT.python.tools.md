# Agent Python Tools

- repo: facebookresearch/ov-seg
- repo_uri: https://github.com/facebookresearch/ov-seg

## File: facebookresearch_ov-seg/datasets/prepare_ade20k_full_sem_seg.py

Prompts

```
['run the script to convert ADE20K-Full validation annotations to detectron2 format with resized images and uint16 label masks', 'load an ADE20K image file and decode its RGB segmentation PNG into a class mask array using R/10*256+G formula', 'create a mapping from ADE20K original category IDs to contiguous train IDs using the ADE20K_SEM_SEG_FULL_CATEGORIES list', 'resize ADE20K images and labels to max 512px on the longest side using bilinear for images and nearest for labels', 'convert ADE20K class mask labels from int32 to uint16 format with unmapped classes set to 65535 background value', 'convert an ADE20K annotation image to detectron2 format by shifting pixel values by 1', 'convert an annotation image using a custom class index mapping to remap semantic labels', 'run the script to prepare ADE20K validation annotations for detectron2 format', 'refactor the convert function to process multiple annotation files in parallel', 'review the convert function and its uint8 dtype assertion for edge case handling', 'run convert_to_trainID to remap COCO-Stuff class IDs to training IDs and save converted masks', 'run the script to convert all COCO-Stuff train2017 masks to Detectron2-compatible training IDs', 'test convert_to_trainID with a sample mask file to verify class ID remapping works correctly', 'review the full_clsID_to_trID mapping dictionary to understand which COCO-Stuff class IDs are remapped', 'refactor convert_to_trainID to support batch processing of multiple mask files at once', 'run the script to convert PASCAL Context validation masks from .mat to .tif and .png formats', 'convert a PASCAL Context .mat mask file to a 59-class PNG using a label mapping dictionary', 'convert a PASCAL Context .mat mask file to a 459-class TIFF by subtracting one from labels', 'review the convert_pc59 function that maps 459-class labels to 59-class labels and saves as PNG', 'summarize the convert_pc459 function that loads a .mat LabelMap, decrements labels, and saves as TIFF', 'run the script to convert PASCAL VOC 2012 validation segmentation masks to detectron2 format', 'summarize the clsID_to_trID mapping dictionary that remaps 21 PASCAL VOC classes to training IDs']
```

Usage

```
{'run_prepare_ade20k_full_sem_seg': 'run the script to convert ADE20K-Full validation annotations to detectron2 format with resized images and uint16 label masks', 'loadAde20K_decode_segmentation': 'load an ADE20K image file and decode its RGB segmentation PNG into a class mask array using R/10*256+G formula', 'create_ade20K_category_mapping': 'create a mapping from ADE20K original category IDs to contiguous train IDs using the ADE20K_SEM_SEG_FULL_CATEGORIES list', 'resize_ade20K_images_labels': 'resize ADE20K images and labels to max 512px on the longest side using bilinear for images and nearest for labels', 'convert_ade20K_labels_to_uint16': 'convert ADE20K class mask labels from int32 to uint16 format with unmapped classes set to 65535 background value'}
```

## File: facebookresearch_ov-seg/datasets/prepare_ade20k_sem_seg.py

Prompts

```
['run the script to convert ADE20K-Full validation annotations to detectron2 format with resized images and uint16 label masks', 'load an ADE20K image file and decode its RGB segmentation PNG into a class mask array using R/10*256+G formula', 'create a mapping from ADE20K original category IDs to contiguous train IDs using the ADE20K_SEM_SEG_FULL_CATEGORIES list', 'resize ADE20K images and labels to max 512px on the longest side using bilinear for images and nearest for labels', 'convert ADE20K class mask labels from int32 to uint16 format with unmapped classes set to 65535 background value', 'convert an ADE20K annotation image to detectron2 format by shifting pixel values by 1', 'convert an annotation image using a custom class index mapping to remap semantic labels', 'run the script to prepare ADE20K validation annotations for detectron2 format', 'refactor the convert function to process multiple annotation files in parallel', 'review the convert function and its uint8 dtype assertion for edge case handling', 'run convert_to_trainID to remap COCO-Stuff class IDs to training IDs and save converted masks', 'run the script to convert all COCO-Stuff train2017 masks to Detectron2-compatible training IDs', 'test convert_to_trainID with a sample mask file to verify class ID remapping works correctly', 'review the full_clsID_to_trID mapping dictionary to understand which COCO-Stuff class IDs are remapped', 'refactor convert_to_trainID to support batch processing of multiple mask files at once', 'run the script to convert PASCAL Context validation masks from .mat to .tif and .png formats', 'convert a PASCAL Context .mat mask file to a 59-class PNG using a label mapping dictionary', 'convert a PASCAL Context .mat mask file to a 459-class TIFF by subtracting one from labels', 'review the convert_pc59 function that maps 459-class labels to 59-class labels and saves as PNG', 'summarize the convert_pc459 function that loads a .mat LabelMap, decrements labels, and saves as TIFF', 'run the script to convert PASCAL VOC 2012 validation segmentation masks to detectron2 format', 'summarize the clsID_to_trID mapping dictionary that remaps 21 PASCAL VOC classes to training IDs']
```

Usage

```
{'convert_ade20k_annotation': 'convert an ADE20K annotation image to detectron2 format by shifting pixel values by 1', 'convert_with_index_mapping': 'convert an annotation image using a custom class index mapping to remap semantic labels', 'run_ade20k_validation_prep': 'run the script to prepare ADE20K validation annotations for detectron2 format', 'refactor_convert_for_batch': 'refactor the convert function to process multiple annotation files in parallel', 'review_convert_dtype_assertion': 'review the convert function and its uint8 dtype assertion for edge case handling'}
```

## File: facebookresearch_ov-seg/datasets/prepare_coco_stuff_sem_seg.py

Prompts

```
['run the script to convert ADE20K-Full validation annotations to detectron2 format with resized images and uint16 label masks', 'load an ADE20K image file and decode its RGB segmentation PNG into a class mask array using R/10*256+G formula', 'create a mapping from ADE20K original category IDs to contiguous train IDs using the ADE20K_SEM_SEG_FULL_CATEGORIES list', 'resize ADE20K images and labels to max 512px on the longest side using bilinear for images and nearest for labels', 'convert ADE20K class mask labels from int32 to uint16 format with unmapped classes set to 65535 background value', 'convert an ADE20K annotation image to detectron2 format by shifting pixel values by 1', 'convert an annotation image using a custom class index mapping to remap semantic labels', 'run the script to prepare ADE20K validation annotations for detectron2 format', 'refactor the convert function to process multiple annotation files in parallel', 'review the convert function and its uint8 dtype assertion for edge case handling', 'run convert_to_trainID to remap COCO-Stuff class IDs to training IDs and save converted masks', 'run the script to convert all COCO-Stuff train2017 masks to Detectron2-compatible training IDs', 'test convert_to_trainID with a sample mask file to verify class ID remapping works correctly', 'review the full_clsID_to_trID mapping dictionary to understand which COCO-Stuff class IDs are remapped', 'refactor convert_to_trainID to support batch processing of multiple mask files at once', 'run the script to convert PASCAL Context validation masks from .mat to .tif and .png formats', 'convert a PASCAL Context .mat mask file to a 59-class PNG using a label mapping dictionary', 'convert a PASCAL Context .mat mask file to a 459-class TIFF by subtracting one from labels', 'review the convert_pc59 function that maps 459-class labels to 59-class labels and saves as PNG', 'summarize the convert_pc459 function that loads a .mat LabelMap, decrements labels, and saves as TIFF', 'run the script to convert PASCAL VOC 2012 validation segmentation masks to detectron2 format', 'summarize the clsID_to_trID mapping dictionary that remaps 21 PASCAL VOC classes to training IDs']
```

Usage

```
{'run_convert_to_trainID': 'run convert_to_trainID to remap COCO-Stuff class IDs to training IDs and save converted masks', 'run_prepare_coco_stuff': 'run the script to convert all COCO-Stuff train2017 masks to Detectron2-compatible training IDs', 'test_convert_to_trainID': 'test convert_to_trainID with a sample mask file to verify class ID remapping works correctly', 'review_full_clsID_to_trID': 'review the full_clsID_to_trID mapping dictionary to understand which COCO-Stuff class IDs are remapped', 'refactor_convert_to_trainID': 'refactor convert_to_trainID to support batch processing of multiple mask files at once'}
```

## File: facebookresearch_ov-seg/datasets/prepare_pascal_context.py

Prompts

```
['run the script to convert ADE20K-Full validation annotations to detectron2 format with resized images and uint16 label masks', 'load an ADE20K image file and decode its RGB segmentation PNG into a class mask array using R/10*256+G formula', 'create a mapping from ADE20K original category IDs to contiguous train IDs using the ADE20K_SEM_SEG_FULL_CATEGORIES list', 'resize ADE20K images and labels to max 512px on the longest side using bilinear for images and nearest for labels', 'convert ADE20K class mask labels from int32 to uint16 format with unmapped classes set to 65535 background value', 'convert an ADE20K annotation image to detectron2 format by shifting pixel values by 1', 'convert an annotation image using a custom class index mapping to remap semantic labels', 'run the script to prepare ADE20K validation annotations for detectron2 format', 'refactor the convert function to process multiple annotation files in parallel', 'review the convert function and its uint8 dtype assertion for edge case handling', 'run convert_to_trainID to remap COCO-Stuff class IDs to training IDs and save converted masks', 'run the script to convert all COCO-Stuff train2017 masks to Detectron2-compatible training IDs', 'test convert_to_trainID with a sample mask file to verify class ID remapping works correctly', 'review the full_clsID_to_trID mapping dictionary to understand which COCO-Stuff class IDs are remapped', 'refactor convert_to_trainID to support batch processing of multiple mask files at once', 'run the script to convert PASCAL Context validation masks from .mat to .tif and .png formats', 'convert a PASCAL Context .mat mask file to a 59-class PNG using a label mapping dictionary', 'convert a PASCAL Context .mat mask file to a 459-class TIFF by subtracting one from labels', 'review the convert_pc59 function that maps 459-class labels to 59-class labels and saves as PNG', 'summarize the convert_pc459 function that loads a .mat LabelMap, decrements labels, and saves as TIFF', 'run the script to convert PASCAL VOC 2012 validation segmentation masks to detectron2 format', 'summarize the clsID_to_trID mapping dictionary that remaps 21 PASCAL VOC classes to training IDs']
```

Usage

```
{'run_prepare_pascal_context': 'run the script to convert PASCAL Context validation masks from .mat to .tif and .png formats', 'convert_pc59_mask': 'convert a PASCAL Context .mat mask file to a 59-class PNG using a label mapping dictionary', 'convert_pc459_mask': 'convert a PASCAL Context .mat mask file to a 459-class TIFF by subtracting one from labels', 'review_convert_pc59': 'review the convert_pc59 function that maps 459-class labels to 59-class labels and saves as PNG', 'summarize_convert_pc459': 'summarize the convert_pc459 function that loads a .mat LabelMap, decrements labels, and saves as TIFF'}
```

## File: facebookresearch_ov-seg/datasets/prepare_voc_sem_seg.py

Prompts

```
['run the script to convert ADE20K-Full validation annotations to detectron2 format with resized images and uint16 label masks', 'load an ADE20K image file and decode its RGB segmentation PNG into a class mask array using R/10*256+G formula', 'create a mapping from ADE20K original category IDs to contiguous train IDs using the ADE20K_SEM_SEG_FULL_CATEGORIES list', 'resize ADE20K images and labels to max 512px on the longest side using bilinear for images and nearest for labels', 'convert ADE20K class mask labels from int32 to uint16 format with unmapped classes set to 65535 background value', 'convert an ADE20K annotation image to detectron2 format by shifting pixel values by 1', 'convert an annotation image using a custom class index mapping to remap semantic labels', 'run the script to prepare ADE20K validation annotations for detectron2 format', 'refactor the convert function to process multiple annotation files in parallel', 'review the convert function and its uint8 dtype assertion for edge case handling', 'run convert_to_trainID to remap COCO-Stuff class IDs to training IDs and save converted masks', 'run the script to convert all COCO-Stuff train2017 masks to Detectron2-compatible training IDs', 'test convert_to_trainID with a sample mask file to verify class ID remapping works correctly', 'review the full_clsID_to_trID mapping dictionary to understand which COCO-Stuff class IDs are remapped', 'refactor convert_to_trainID to support batch processing of multiple mask files at once', 'run the script to convert PASCAL Context validation masks from .mat to .tif and .png formats', 'convert a PASCAL Context .mat mask file to a 59-class PNG using a label mapping dictionary', 'convert a PASCAL Context .mat mask file to a 459-class TIFF by subtracting one from labels', 'review the convert_pc59 function that maps 459-class labels to 59-class labels and saves as PNG', 'summarize the convert_pc459 function that loads a .mat LabelMap, decrements labels, and saves as TIFF', 'run the script to convert PASCAL VOC 2012 validation segmentation masks to detectron2 format', 'summarize the clsID_to_trID mapping dictionary that remaps 21 PASCAL VOC classes to training IDs']
```

Usage

```
{'run_prepare_voc_sem_seg': 'run the script to convert PASCAL VOC 2012 validation segmentation masks to detectron2 format', 'run_convert_to_trainID': "run convert_to_trainID to remap a segmentation mask's class IDs to training IDs and save as PNG", 'test_convert_to_trainID': 'test convert_to_trainID with a sample mask path to verify class ID remapping and output', 'refactor_convert_to_trainID': 'refactor convert_to_trainID to support custom clsID_to_trID mappings for other datasets', 'summarize_clsID_to_trID': 'summarize the clsID_to_trID mapping dictionary that remaps 21 PASCAL VOC classes to training IDs'}
```

