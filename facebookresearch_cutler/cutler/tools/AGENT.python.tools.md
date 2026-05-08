# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/cutler/tools/get_self_training_ann.py

Prompts

```
['run the CLI to merge new model predictions with previous pseudo-annotations and save a COCO JSON file for self-training', 'use cocosegm2mask to convert a COCO segmentation object into a binary numpy mask given height and width', 'use segmToRLE to convert a COCO segmentation polygon or uncompressed RLE into a compact RLE object', 'use rle2mask to decode an RLE object into a binary numpy mask given height and width', 'use BatchIoU to compute pairwise IoU scores between two batches of binary mask tensors on GPU']
```

Usage

```
{'generate_self_training_annotations': 'run the CLI to merge new model predictions with previous pseudo-annotations and save a COCO JSON file for self-training', 'convert_cocosegm_to_mask': 'use cocosegm2mask to convert a COCO segmentation object into a binary numpy mask given height and width', 'convert_segm_to_rle': 'use segmToRLE to convert a COCO segmentation polygon or uncompressed RLE into a compact RLE object', 'decode_rle_to_mask': 'use rle2mask to decode an RLE object into a binary numpy mask given height and width', 'compute_batch_iou': 'use BatchIoU to compute pairwise IoU scores between two batches of binary mask tensors on GPU'}
```

