# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/mdetr/data/datamodule.py

Prompts

```
['build a FlickrDataModule LightningDataModule for the Flickr dataset with a roberta tokenizer and MDETRTransform', 'build a GQADataModule LightningDataModule for the GQA dataset with epoch chunking support for large datasets', 'setup the FlickrDataModule validation dataset using build_flickr with a roberta tokenizer and MDETRTransform', 'setup the GQADataModule training and validation datasets using build_gqa with separate train and val transforms', 'create chunked training dataloaders from GQADataModule by splitting the dataset into smaller epoch chunks', 'build a ModulatedDetection dataset from COCO annotations with caption token grounding and transforms', 'build a GQADataset for visual question answering with answer type classification and token grounding', 'build a collate function that batches positive maps and answer types for MDETR training', 'build a Flickr referential expression dataset with merged or separate ground truth annotations', 'build a GQA dataset for train, val, or test splits with configurable split type', 'parse a Flickr30K sentence text file and extract annotated phrases with their IDs and types', 'parse a Flickr30K XML annotation file to extract bounding boxes, scene IDs, and image dimensions', 'merge a list of bounding boxes into a single smallest enclosing box in xmin ymin xmax ymax format', 'evaluate recall at multiple top-k values for predicted bounding boxes against Flickr30K ground truth annotations', 'run the FlickrEvaluator pipeline by updating predictions, synchronizing across processes, and summarizing recall results', 'create a positive map tensor linking bounding boxes to token positions from tokenized captions', 'convert COCO annotation polygons to bounding boxes, labels, and token positive maps for MDETR', 'compose a pipeline of image and target transforms like crop, resize, flip, and normalize', 'apply MDETR training or inference image transforms and tokenize caption text for detection', 'randomly select between two transform pipelines with configurable probability for data augmentation']
```

Usage

```
{'build_flickr_datamodule': 'build a FlickrDataModule LightningDataModule for the Flickr dataset with a roberta tokenizer and MDETRTransform', 'build_gqa_datamodule': 'build a GQADataModule LightningDataModule for the GQA dataset with epoch chunking support for large datasets', 'setup_flickr_val': 'setup the FlickrDataModule validation dataset using build_flickr with a roberta tokenizer and MDETRTransform', 'setup_gqa_train_val': 'setup the GQADataModule training and validation datasets using build_gqa with separate train and val transforms', 'create_gqa_chunked_dataloader': 'create chunked training dataloaders from GQADataModule by splitting the dataset into smaller epoch chunks'}
```

## File: facebookresearch_multimodal/examples/mdetr/data/dataset.py

Prompts

```
['build a FlickrDataModule LightningDataModule for the Flickr dataset with a roberta tokenizer and MDETRTransform', 'build a GQADataModule LightningDataModule for the GQA dataset with epoch chunking support for large datasets', 'setup the FlickrDataModule validation dataset using build_flickr with a roberta tokenizer and MDETRTransform', 'setup the GQADataModule training and validation datasets using build_gqa with separate train and val transforms', 'create chunked training dataloaders from GQADataModule by splitting the dataset into smaller epoch chunks', 'build a ModulatedDetection dataset from COCO annotations with caption token grounding and transforms', 'build a GQADataset for visual question answering with answer type classification and token grounding', 'build a collate function that batches positive maps and answer types for MDETR training', 'build a Flickr referential expression dataset with merged or separate ground truth annotations', 'build a GQA dataset for train, val, or test splits with configurable split type', 'parse a Flickr30K sentence text file and extract annotated phrases with their IDs and types', 'parse a Flickr30K XML annotation file to extract bounding boxes, scene IDs, and image dimensions', 'merge a list of bounding boxes into a single smallest enclosing box in xmin ymin xmax ymax format', 'evaluate recall at multiple top-k values for predicted bounding boxes against Flickr30K ground truth annotations', 'run the FlickrEvaluator pipeline by updating predictions, synchronizing across processes, and summarizing recall results', 'create a positive map tensor linking bounding boxes to token positions from tokenized captions', 'convert COCO annotation polygons to bounding boxes, labels, and token positive maps for MDETR', 'compose a pipeline of image and target transforms like crop, resize, flip, and normalize', 'apply MDETR training or inference image transforms and tokenize caption text for detection', 'randomly select between two transform pipelines with configurable probability for data augmentation']
```

Usage

```
{'build_ModulatedDetection_dataset': 'build a ModulatedDetection dataset from COCO annotations with caption token grounding and transforms', 'build_GQADataset': 'build a GQADataset for visual question answering with answer type classification and token grounding', 'build_collate_fn_batching': 'build a collate function that batches positive maps and answer types for MDETR training', 'build_flickr_dataset': 'build a Flickr referential expression dataset with merged or separate ground truth annotations', 'build_gqa_dataset': 'build a GQA dataset for train, val, or test splits with configurable split type'}
```

## File: facebookresearch_multimodal/examples/mdetr/data/flickr_eval.py

Prompts

```
['build a FlickrDataModule LightningDataModule for the Flickr dataset with a roberta tokenizer and MDETRTransform', 'build a GQADataModule LightningDataModule for the GQA dataset with epoch chunking support for large datasets', 'setup the FlickrDataModule validation dataset using build_flickr with a roberta tokenizer and MDETRTransform', 'setup the GQADataModule training and validation datasets using build_gqa with separate train and val transforms', 'create chunked training dataloaders from GQADataModule by splitting the dataset into smaller epoch chunks', 'build a ModulatedDetection dataset from COCO annotations with caption token grounding and transforms', 'build a GQADataset for visual question answering with answer type classification and token grounding', 'build a collate function that batches positive maps and answer types for MDETR training', 'build a Flickr referential expression dataset with merged or separate ground truth annotations', 'build a GQA dataset for train, val, or test splits with configurable split type', 'parse a Flickr30K sentence text file and extract annotated phrases with their IDs and types', 'parse a Flickr30K XML annotation file to extract bounding boxes, scene IDs, and image dimensions', 'merge a list of bounding boxes into a single smallest enclosing box in xmin ymin xmax ymax format', 'evaluate recall at multiple top-k values for predicted bounding boxes against Flickr30K ground truth annotations', 'run the FlickrEvaluator pipeline by updating predictions, synchronizing across processes, and summarizing recall results', 'create a positive map tensor linking bounding boxes to token positions from tokenized captions', 'convert COCO annotation polygons to bounding boxes, labels, and token positive maps for MDETR', 'compose a pipeline of image and target transforms like crop, resize, flip, and normalize', 'apply MDETR training or inference image transforms and tokenize caption text for detection', 'randomly select between two transform pipelines with configurable probability for data augmentation']
```

Usage

```
{'parse_flickr30k_sentence_file': 'parse a Flickr30K sentence text file and extract annotated phrases with their IDs and types', 'parse_flickr30k_xml_annotations': 'parse a Flickr30K XML annotation file to extract bounding boxes, scene IDs, and image dimensions', 'merge_bounding_boxes': 'merge a list of bounding boxes into a single smallest enclosing box in xmin ymin xmax ymax format', 'evaluate_flickr30k_entities_recall': 'evaluate recall at multiple top-k values for predicted bounding boxes against Flickr30K ground truth annotations', 'run_flickr_evaluator_pipeline': 'run the FlickrEvaluator pipeline by updating predictions, synchronizing across processes, and summarizing recall results'}
```

## File: facebookresearch_multimodal/examples/mdetr/data/transforms.py

Prompts

```
['build a FlickrDataModule LightningDataModule for the Flickr dataset with a roberta tokenizer and MDETRTransform', 'build a GQADataModule LightningDataModule for the GQA dataset with epoch chunking support for large datasets', 'setup the FlickrDataModule validation dataset using build_flickr with a roberta tokenizer and MDETRTransform', 'setup the GQADataModule training and validation datasets using build_gqa with separate train and val transforms', 'create chunked training dataloaders from GQADataModule by splitting the dataset into smaller epoch chunks', 'build a ModulatedDetection dataset from COCO annotations with caption token grounding and transforms', 'build a GQADataset for visual question answering with answer type classification and token grounding', 'build a collate function that batches positive maps and answer types for MDETR training', 'build a Flickr referential expression dataset with merged or separate ground truth annotations', 'build a GQA dataset for train, val, or test splits with configurable split type', 'parse a Flickr30K sentence text file and extract annotated phrases with their IDs and types', 'parse a Flickr30K XML annotation file to extract bounding boxes, scene IDs, and image dimensions', 'merge a list of bounding boxes into a single smallest enclosing box in xmin ymin xmax ymax format', 'evaluate recall at multiple top-k values for predicted bounding boxes against Flickr30K ground truth annotations', 'run the FlickrEvaluator pipeline by updating predictions, synchronizing across processes, and summarizing recall results', 'create a positive map tensor linking bounding boxes to token positions from tokenized captions', 'convert COCO annotation polygons to bounding boxes, labels, and token positive maps for MDETR', 'compose a pipeline of image and target transforms like crop, resize, flip, and normalize', 'apply MDETR training or inference image transforms and tokenize caption text for detection', 'randomly select between two transform pipelines with configurable probability for data augmentation']
```

Usage

```
{'create_positive_map': 'create a positive map tensor linking bounding boxes to token positions from tokenized captions', 'convert_coco_polys_to_mask': 'convert COCO annotation polygons to bounding boxes, labels, and token positive maps for MDETR', 'compose_transforms': 'compose a pipeline of image and target transforms like crop, resize, flip, and normalize', 'apply_mdetr_transform': 'apply MDETR training or inference image transforms and tokenize caption text for detection', 'random_select_transforms': 'randomly select between two transform pipelines with configurable probability for data augmentation'}
```

