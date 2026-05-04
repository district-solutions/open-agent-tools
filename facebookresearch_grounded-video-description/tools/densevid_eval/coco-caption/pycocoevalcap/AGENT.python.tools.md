# Agent Python Tools

- repo: facebookresearch/grounded-video-description
- repo_uri: https://github.com/facebookresearch/grounded-video-description

## File: facebookresearch_grounded-video-description/tools/densevid_eval/coco-caption/pycocoevalcap/eval.py

Prompts

```
['run COCOEvalCap.evaluate() to compute BLEU, METEOR, ROUGE, CIDEr, and SPICE scores for image captions', 'call COCOEvalCap.tokenize() to tokenize ground truth and predicted annotations using PTBTokenizer', 'use COCOEvalCap.setEval() to store a computed score for a given evaluation method', 'call COCOEvalCap.setImgToEvalImgs() to map per-image scores to their corresponding image IDs', 'invoke COCOEvalCap.setEvalImgs() to compile all per-image evaluation results into a list']
```

Usage

```
{'evaluate_coco_caption': 'run COCOEvalCap.evaluate() to compute BLEU, METEOR, ROUGE, CIDEr, and SPICE scores for image captions', 'tokenize_coco_annotations': 'call COCOEvalCap.tokenize() to tokenize ground truth and predicted annotations using PTBTokenizer', 'set_eval_score': 'use COCOEvalCap.setEval() to store a computed score for a given evaluation method', 'set_img_to_eval': 'call COCOEvalCap.setImgToEvalImgs() to map per-image scores to their corresponding image IDs', 'collect_eval_imgs': 'invoke COCOEvalCap.setEvalImgs() to compile all per-image evaluation results into a list'}
```

