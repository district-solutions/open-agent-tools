# Agent Python Tools

- repo: facebookresearch/maskformer
- repo_uri: https://github.com/facebookresearch/maskformer

## File: facebookresearch_maskformer/mask_former/data/datasets/register_ade20k_full.py

Prompts

```
['register the ADE20K-Full semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog for training and validation splits', 'get the ADE20K-Full category metadata including 847 stuff class names and dataset-to-contiguous ID mappings', 'load ADE20K-Full semantic segmentation images and TIFF annotations using detectron2 load_sem_seg with jpg and tif extensions', 'configure the ADE20K-Full dataset ignore label to 65535 for 16-bit TIFF ground truth images', 'customize the ADE20K-Full dataset root path via the DETECTRON2_DATASETS environment variable or a default datasets directory', 'load ADE20K panoptic JSON annotations and return a list of dicts in Detectron2 standard format', 'register an ADE20K panoptic segmentation dataset split with Detectron2 DatasetCatalog and MetadataCatalog', 'get ADE20K metadata including thing and stuff class names, colors, and ID mappings', 'register all predefined ADE20K panoptic train and val splits under a given root directory', 'review the ADE20K 150 category definitions including names, colors, IDs, and isthing flags', 'register the COCO-Stuff 10k semantic segmentation dataset for train and test splits in Detectron2', 'get the COCO-Stuff 10k metadata including stuff class names and dataset to contiguous ID mappings', 'summarize the 171 COCO-Stuff 10k category definitions including thing and stuff classes with colors and IDs', 'review the register_all_coco_stuff_10k function to understand how train and test splits are registered with DatasetCatalog', 'refactor the _get_coco_stuff_meta function to add additional metadata fields like supercategory groupings', 'register the Mapillary Vistas semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog', 'get the Mapillary Vistas metadata including 65 stuff classes and their corresponding colors', 'summarize the 66 Mapillary Vistas semantic segmentation categories with their colors, names, and evaluation flags', 'review the register_all_mapillary_vistas function to understand how train and val splits are registered', 'refactor the _get_mapillary_vistas_meta function to support a custom subset of evaluation categories']
```

Usage

```
{'register_ade20k_full_dataset': 'register the ADE20K-Full semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog for training and validation splits', 'get_ade20k_full_metadata': 'get the ADE20K-Full category metadata including 847 stuff class names and dataset-to-contiguous ID mappings', 'load_ade20k_full_sem_seg': 'load ADE20K-Full semantic segmentation images and TIFF annotations using detectron2 load_sem_seg with jpg and tif extensions', 'configure_ade20k_full_ignore_label': 'configure the ADE20K-Full dataset ignore label to 65535 for 16-bit TIFF ground truth images', 'customize_ade20k_full_root': 'customize the ADE20K-Full dataset root path via the DETECTRON2_DATASETS environment variable or a default datasets directory'}
```

## File: facebookresearch_maskformer/mask_former/data/datasets/register_ade20k_panoptic.py

Prompts

```
['register the ADE20K-Full semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog for training and validation splits', 'get the ADE20K-Full category metadata including 847 stuff class names and dataset-to-contiguous ID mappings', 'load ADE20K-Full semantic segmentation images and TIFF annotations using detectron2 load_sem_seg with jpg and tif extensions', 'configure the ADE20K-Full dataset ignore label to 65535 for 16-bit TIFF ground truth images', 'customize the ADE20K-Full dataset root path via the DETECTRON2_DATASETS environment variable or a default datasets directory', 'load ADE20K panoptic JSON annotations and return a list of dicts in Detectron2 standard format', 'register an ADE20K panoptic segmentation dataset split with Detectron2 DatasetCatalog and MetadataCatalog', 'get ADE20K metadata including thing and stuff class names, colors, and ID mappings', 'register all predefined ADE20K panoptic train and val splits under a given root directory', 'review the ADE20K 150 category definitions including names, colors, IDs, and isthing flags', 'register the COCO-Stuff 10k semantic segmentation dataset for train and test splits in Detectron2', 'get the COCO-Stuff 10k metadata including stuff class names and dataset to contiguous ID mappings', 'summarize the 171 COCO-Stuff 10k category definitions including thing and stuff classes with colors and IDs', 'review the register_all_coco_stuff_10k function to understand how train and test splits are registered with DatasetCatalog', 'refactor the _get_coco_stuff_meta function to add additional metadata fields like supercategory groupings', 'register the Mapillary Vistas semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog', 'get the Mapillary Vistas metadata including 65 stuff classes and their corresponding colors', 'summarize the 66 Mapillary Vistas semantic segmentation categories with their colors, names, and evaluation flags', 'review the register_all_mapillary_vistas function to understand how train and val splits are registered', 'refactor the _get_mapillary_vistas_meta function to support a custom subset of evaluation categories']
```

Usage

```
{'load_ade20k_panoptic_json': 'load ADE20K panoptic JSON annotations and return a list of dicts in Detectron2 standard format', 'register_ade20k_panoptic': 'register an ADE20K panoptic segmentation dataset split with Detectron2 DatasetCatalog and MetadataCatalog', 'get_metadata': 'get ADE20K metadata including thing and stuff class names, colors, and ID mappings', 'register_all_ade20k_panoptic': 'register all predefined ADE20K panoptic train and val splits under a given root directory', 'review_ADE20K_150_CATEGORIES': 'review the ADE20K 150 category definitions including names, colors, IDs, and isthing flags'}
```

## File: facebookresearch_maskformer/mask_former/data/datasets/register_coco_stuff_10k.py

Prompts

```
['register the ADE20K-Full semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog for training and validation splits', 'get the ADE20K-Full category metadata including 847 stuff class names and dataset-to-contiguous ID mappings', 'load ADE20K-Full semantic segmentation images and TIFF annotations using detectron2 load_sem_seg with jpg and tif extensions', 'configure the ADE20K-Full dataset ignore label to 65535 for 16-bit TIFF ground truth images', 'customize the ADE20K-Full dataset root path via the DETECTRON2_DATASETS environment variable or a default datasets directory', 'load ADE20K panoptic JSON annotations and return a list of dicts in Detectron2 standard format', 'register an ADE20K panoptic segmentation dataset split with Detectron2 DatasetCatalog and MetadataCatalog', 'get ADE20K metadata including thing and stuff class names, colors, and ID mappings', 'register all predefined ADE20K panoptic train and val splits under a given root directory', 'review the ADE20K 150 category definitions including names, colors, IDs, and isthing flags', 'register the COCO-Stuff 10k semantic segmentation dataset for train and test splits in Detectron2', 'get the COCO-Stuff 10k metadata including stuff class names and dataset to contiguous ID mappings', 'summarize the 171 COCO-Stuff 10k category definitions including thing and stuff classes with colors and IDs', 'review the register_all_coco_stuff_10k function to understand how train and test splits are registered with DatasetCatalog', 'refactor the _get_coco_stuff_meta function to add additional metadata fields like supercategory groupings', 'register the Mapillary Vistas semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog', 'get the Mapillary Vistas metadata including 65 stuff classes and their corresponding colors', 'summarize the 66 Mapillary Vistas semantic segmentation categories with their colors, names, and evaluation flags', 'review the register_all_mapillary_vistas function to understand how train and val splits are registered', 'refactor the _get_mapillary_vistas_meta function to support a custom subset of evaluation categories']
```

Usage

```
{'register_coco_stuff_10k_dataset': 'register the COCO-Stuff 10k semantic segmentation dataset for train and test splits in Detectron2', 'get_coco_stuff_metadata': 'get the COCO-Stuff 10k metadata including stuff class names and dataset to contiguous ID mappings', 'summarize_coco_categories': 'summarize the 171 COCO-Stuff 10k category definitions including thing and stuff classes with colors and IDs', 'review_dataset_registration': 'review the register_all_coco_stuff_10k function to understand how train and test splits are registered with DatasetCatalog', 'refactor_coco_stuff_meta': 'refactor the _get_coco_stuff_meta function to add additional metadata fields like supercategory groupings'}
```

## File: facebookresearch_maskformer/mask_former/data/datasets/register_mapillary_vistas.py

Prompts

```
['register the ADE20K-Full semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog for training and validation splits', 'get the ADE20K-Full category metadata including 847 stuff class names and dataset-to-contiguous ID mappings', 'load ADE20K-Full semantic segmentation images and TIFF annotations using detectron2 load_sem_seg with jpg and tif extensions', 'configure the ADE20K-Full dataset ignore label to 65535 for 16-bit TIFF ground truth images', 'customize the ADE20K-Full dataset root path via the DETECTRON2_DATASETS environment variable or a default datasets directory', 'load ADE20K panoptic JSON annotations and return a list of dicts in Detectron2 standard format', 'register an ADE20K panoptic segmentation dataset split with Detectron2 DatasetCatalog and MetadataCatalog', 'get ADE20K metadata including thing and stuff class names, colors, and ID mappings', 'register all predefined ADE20K panoptic train and val splits under a given root directory', 'review the ADE20K 150 category definitions including names, colors, IDs, and isthing flags', 'register the COCO-Stuff 10k semantic segmentation dataset for train and test splits in Detectron2', 'get the COCO-Stuff 10k metadata including stuff class names and dataset to contiguous ID mappings', 'summarize the 171 COCO-Stuff 10k category definitions including thing and stuff classes with colors and IDs', 'review the register_all_coco_stuff_10k function to understand how train and test splits are registered with DatasetCatalog', 'refactor the _get_coco_stuff_meta function to add additional metadata fields like supercategory groupings', 'register the Mapillary Vistas semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog', 'get the Mapillary Vistas metadata including 65 stuff classes and their corresponding colors', 'summarize the 66 Mapillary Vistas semantic segmentation categories with their colors, names, and evaluation flags', 'review the register_all_mapillary_vistas function to understand how train and val splits are registered', 'refactor the _get_mapillary_vistas_meta function to support a custom subset of evaluation categories']
```

Usage

```
{'register_mapillary_vistas_dataset': 'register the Mapillary Vistas semantic segmentation dataset with detectron2 DatasetCatalog and MetadataCatalog', 'get_mapillary_vistas_meta': 'get the Mapillary Vistas metadata including 65 stuff classes and their corresponding colors', 'summarize_MAPILLARY_VISTAS_SEM_SEG_CATEGORIES': 'summarize the 66 Mapillary Vistas semantic segmentation categories with their colors, names, and evaluation flags', 'review_register_all_mapillary_vistas': 'review the register_all_mapillary_vistas function to understand how train and val splits are registered', 'refactor_get_mapillary_vistas_meta': 'refactor the _get_mapillary_vistas_meta function to support a custom subset of evaluation categories'}
```

