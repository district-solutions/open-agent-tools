# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/tools/get_cc_tags.py

Prompts

```
['run the script to extract object category tags from CC3M image captions and save tagged JSON', 'run the script with --convert_caption to move captions from annotations into image records', 'run the script with --cat_path to tag images using a custom category JSON file', 'run the script with --keep_images to retain images that have no matching category tags', 'run the script with --allcaps to search all captions instead of only the first one per image', 'run the script to merge LVIS and COCO annotations into a combined dataset JSON file', 'run the script with NO_SEG set to True to merge LVIS and COCO annotations without segmentation masks', 'review the get_bbox function that converts COCO bbox format from xywh to x1y1x2y2 coordinates', 'review the COCO_SYNSET_CATEGORIES mapping that links COCO category IDs to LVIS WordNet synset identifiers', 'refactor the merge script to accept COCO_PATH, LVIS_PATH, and THRESH as command-line arguments instead of hardcoded values', 'run the preprocess function to convert ImageNet-22K tar archives into numpy metadata files', 'create a _RawTarDataset instance to read JPEG images from a tar archive using an index file', 'read raw image data by index from a tar archive with GZIP decompression support', 'review the _RawTarDataset __init__ method that parses tarlog index files and builds name and offset lists', 'summarize the preprocess function that generates numpy arrays for tarlog files, tar files, and class names']
```

Usage

```
{'run_get_cc_tags': 'run the script to extract object category tags from CC3M image captions and save tagged JSON', 'run_convert_captions': 'run the script with --convert_caption to move captions from annotations into image records', 'run_tag_with_custom_categories': 'run the script with --cat_path to tag images using a custom category JSON file', 'run_keep_all_images': 'run the script with --keep_images to retain images that have no matching category tags', 'run_tag_with_all_captions': 'run the script with --allcaps to search all captions instead of only the first one per image'}
```

## File: facebookresearch_detic/tools/merge_lvis_coco.py

Prompts

```
['run the script to extract object category tags from CC3M image captions and save tagged JSON', 'run the script with --convert_caption to move captions from annotations into image records', 'run the script with --cat_path to tag images using a custom category JSON file', 'run the script with --keep_images to retain images that have no matching category tags', 'run the script with --allcaps to search all captions instead of only the first one per image', 'run the script to merge LVIS and COCO annotations into a combined dataset JSON file', 'run the script with NO_SEG set to True to merge LVIS and COCO annotations without segmentation masks', 'review the get_bbox function that converts COCO bbox format from xywh to x1y1x2y2 coordinates', 'review the COCO_SYNSET_CATEGORIES mapping that links COCO category IDs to LVIS WordNet synset identifiers', 'refactor the merge script to accept COCO_PATH, LVIS_PATH, and THRESH as command-line arguments instead of hardcoded values', 'run the preprocess function to convert ImageNet-22K tar archives into numpy metadata files', 'create a _RawTarDataset instance to read JPEG images from a tar archive using an index file', 'read raw image data by index from a tar archive with GZIP decompression support', 'review the _RawTarDataset __init__ method that parses tarlog index files and builds name and offset lists', 'summarize the preprocess function that generates numpy arrays for tarlog files, tar files, and class names']
```

Usage

```
{'run_merge_lvis_coco': 'run the script to merge LVIS and COCO annotations into a combined dataset JSON file', 'run_merge_lvis_coco_box_only': 'run the script with NO_SEG set to True to merge LVIS and COCO annotations without segmentation masks', 'review_get_bbox': 'review the get_bbox function that converts COCO bbox format from xywh to x1y1x2y2 coordinates', 'review_COCO_SYNSET_CATEGORIES': 'review the COCO_SYNSET_CATEGORIES mapping that links COCO category IDs to LVIS WordNet synset identifiers', 'refactor_merge_lvis_coco': 'refactor the merge script to accept COCO_PATH, LVIS_PATH, and THRESH as command-line arguments instead of hardcoded values'}
```

## File: facebookresearch_detic/tools/preprocess_imagenet22k.py

Prompts

```
['run the script to extract object category tags from CC3M image captions and save tagged JSON', 'run the script with --convert_caption to move captions from annotations into image records', 'run the script with --cat_path to tag images using a custom category JSON file', 'run the script with --keep_images to retain images that have no matching category tags', 'run the script with --allcaps to search all captions instead of only the first one per image', 'run the script to merge LVIS and COCO annotations into a combined dataset JSON file', 'run the script with NO_SEG set to True to merge LVIS and COCO annotations without segmentation masks', 'review the get_bbox function that converts COCO bbox format from xywh to x1y1x2y2 coordinates', 'review the COCO_SYNSET_CATEGORIES mapping that links COCO category IDs to LVIS WordNet synset identifiers', 'refactor the merge script to accept COCO_PATH, LVIS_PATH, and THRESH as command-line arguments instead of hardcoded values', 'run the preprocess function to convert ImageNet-22K tar archives into numpy metadata files', 'create a _RawTarDataset instance to read JPEG images from a tar archive using an index file', 'read raw image data by index from a tar archive with GZIP decompression support', 'review the _RawTarDataset __init__ method that parses tarlog index files and builds name and offset lists', 'summarize the preprocess function that generates numpy arrays for tarlog files, tar files, and class names']
```

Usage

```
{'run_preprocess_imagenet22k': 'run the preprocess function to convert ImageNet-22K tar archives into numpy metadata files', 'create_RawTarDataset': 'create a _RawTarDataset instance to read JPEG images from a tar archive using an index file', 'read_RawTarDataset_getitem': 'read raw image data by index from a tar archive with GZIP decompression support', 'review_RawTarDataset_init': 'review the _RawTarDataset __init__ method that parses tarlog index files and builds name and offset lists', 'summarize_preprocess': 'summarize the preprocess function that generates numpy arrays for tarlog files, tar files, and class names'}
```

