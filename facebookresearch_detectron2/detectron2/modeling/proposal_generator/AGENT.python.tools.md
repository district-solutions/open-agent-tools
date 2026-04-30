# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/detectron2/modeling/proposal_generator/build.py

Prompts

```
['build a proposal generator using RPN from cfg and input_shape', 'build a rotated RPN proposal generator from cfg and input_shape', 'build a proposal generator returning None for PrecomputedProposals name', 'register a custom proposal generator class to PROPOSAL_GENERATOR_REGISTRY', 'get a registered proposal generator from PROPOSAL_GENERATOR_REGISTRY by name', 'run find_top_rpn_proposals to select top-k highest scoring RPN proposals per image and apply NMS', 'add ground truth boxes to RPN proposals for all images in a batch', 'augment per-image RPN proposals with ground truth boxes and high objectness logits', 'test find_top_rpn_proposals with tensor proposals, logits, image sizes, and NMS threshold', 'review add_ground_truth_to_proposals and its single-image variant for concatenating gt with proposals', 'build an RPN head from config and input shape using the RPN_HEAD_REGISTRY', 'create a Region Proposal Network that generates object proposals from feature maps and anchors', 'label and sample RPN anchors by matching them with ground truth instances', 'compute RPN classification and localization losses from predictions and ground truth', 'predict RPN proposals by decoding anchor deltas, applying NMS, and filtering small boxes', 'select top-k rotated region proposals from feature maps with NMS filtering', 'create a rotated region proposal network model from a detectron2 configuration', 'build an RRPN proposal generator from detectron2 config and input feature map shapes', 'label and sample rotated anchors against ground-truth instances for training', 'predict rotated region proposals from anchor deltas and objectness logits']
```

Usage

```
{'build_proposal_generator_rpn': 'build a proposal generator using RPN from cfg and input_shape', 'build_proposal_generator_rrpn': 'build a rotated RPN proposal generator from cfg and input_shape', 'build_proposal_generator_precomputed': 'build a proposal generator returning None for PrecomputedProposals name', 'register_proposal_generator': 'register a custom proposal generator class to PROPOSAL_GENERATOR_REGISTRY', 'get_proposal_generator': 'get a registered proposal generator from PROPOSAL_GENERATOR_REGISTRY by name'}
```

## File: facebookresearch_detectron2/detectron2/modeling/proposal_generator/proposal_utils.py

Prompts

```
['build a proposal generator using RPN from cfg and input_shape', 'build a rotated RPN proposal generator from cfg and input_shape', 'build a proposal generator returning None for PrecomputedProposals name', 'register a custom proposal generator class to PROPOSAL_GENERATOR_REGISTRY', 'get a registered proposal generator from PROPOSAL_GENERATOR_REGISTRY by name', 'run find_top_rpn_proposals to select top-k highest scoring RPN proposals per image and apply NMS', 'add ground truth boxes to RPN proposals for all images in a batch', 'augment per-image RPN proposals with ground truth boxes and high objectness logits', 'test find_top_rpn_proposals with tensor proposals, logits, image sizes, and NMS threshold', 'review add_ground_truth_to_proposals and its single-image variant for concatenating gt with proposals', 'build an RPN head from config and input shape using the RPN_HEAD_REGISTRY', 'create a Region Proposal Network that generates object proposals from feature maps and anchors', 'label and sample RPN anchors by matching them with ground truth instances', 'compute RPN classification and localization losses from predictions and ground truth', 'predict RPN proposals by decoding anchor deltas, applying NMS, and filtering small boxes', 'select top-k rotated region proposals from feature maps with NMS filtering', 'create a rotated region proposal network model from a detectron2 configuration', 'build an RRPN proposal generator from detectron2 config and input feature map shapes', 'label and sample rotated anchors against ground-truth instances for training', 'predict rotated region proposals from anchor deltas and objectness logits']
```

Usage

```
{'run_find_top_rpn_proposals': 'run find_top_rpn_proposals to select top-k highest scoring RPN proposals per image and apply NMS', 'add_ground_truth_to_proposals': 'add ground truth boxes to RPN proposals for all images in a batch', 'add_ground_truth_to_proposals_single_image': 'augment per-image RPN proposals with ground truth boxes and high objectness logits', 'test_find_top_rpn_proposals': 'test find_top_rpn_proposals with tensor proposals, logits, image sizes, and NMS threshold', 'review_add_ground_truth_to_proposals': 'review add_ground_truth_to_proposals and its single-image variant for concatenating gt with proposals'}
```

## File: facebookresearch_detectron2/detectron2/modeling/proposal_generator/rpn.py

Prompts

```
['build a proposal generator using RPN from cfg and input_shape', 'build a rotated RPN proposal generator from cfg and input_shape', 'build a proposal generator returning None for PrecomputedProposals name', 'register a custom proposal generator class to PROPOSAL_GENERATOR_REGISTRY', 'get a registered proposal generator from PROPOSAL_GENERATOR_REGISTRY by name', 'run find_top_rpn_proposals to select top-k highest scoring RPN proposals per image and apply NMS', 'add ground truth boxes to RPN proposals for all images in a batch', 'augment per-image RPN proposals with ground truth boxes and high objectness logits', 'test find_top_rpn_proposals with tensor proposals, logits, image sizes, and NMS threshold', 'review add_ground_truth_to_proposals and its single-image variant for concatenating gt with proposals', 'build an RPN head from config and input shape using the RPN_HEAD_REGISTRY', 'create a Region Proposal Network that generates object proposals from feature maps and anchors', 'label and sample RPN anchors by matching them with ground truth instances', 'compute RPN classification and localization losses from predictions and ground truth', 'predict RPN proposals by decoding anchor deltas, applying NMS, and filtering small boxes', 'select top-k rotated region proposals from feature maps with NMS filtering', 'create a rotated region proposal network model from a detectron2 configuration', 'build an RRPN proposal generator from detectron2 config and input feature map shapes', 'label and sample rotated anchors against ground-truth instances for training', 'predict rotated region proposals from anchor deltas and objectness logits']
```

Usage

```
{'build_rpn_head': 'build an RPN head from config and input shape using the RPN_HEAD_REGISTRY', 'create_rpn_proposals': 'create a Region Proposal Network that generates object proposals from feature maps and anchors', 'label_and_sample_anchors': 'label and sample RPN anchors by matching them with ground truth instances', 'compute_rpn_losses': 'compute RPN classification and localization losses from predictions and ground truth', 'predict_rpn_proposals': 'predict RPN proposals by decoding anchor deltas, applying NMS, and filtering small boxes'}
```

## File: facebookresearch_detectron2/detectron2/modeling/proposal_generator/rrpn.py

Prompts

```
['build a proposal generator using RPN from cfg and input_shape', 'build a rotated RPN proposal generator from cfg and input_shape', 'build a proposal generator returning None for PrecomputedProposals name', 'register a custom proposal generator class to PROPOSAL_GENERATOR_REGISTRY', 'get a registered proposal generator from PROPOSAL_GENERATOR_REGISTRY by name', 'run find_top_rpn_proposals to select top-k highest scoring RPN proposals per image and apply NMS', 'add ground truth boxes to RPN proposals for all images in a batch', 'augment per-image RPN proposals with ground truth boxes and high objectness logits', 'test find_top_rpn_proposals with tensor proposals, logits, image sizes, and NMS threshold', 'review add_ground_truth_to_proposals and its single-image variant for concatenating gt with proposals', 'build an RPN head from config and input shape using the RPN_HEAD_REGISTRY', 'create a Region Proposal Network that generates object proposals from feature maps and anchors', 'label and sample RPN anchors by matching them with ground truth instances', 'compute RPN classification and localization losses from predictions and ground truth', 'predict RPN proposals by decoding anchor deltas, applying NMS, and filtering small boxes', 'select top-k rotated region proposals from feature maps with NMS filtering', 'create a rotated region proposal network model from a detectron2 configuration', 'build an RRPN proposal generator from detectron2 config and input feature map shapes', 'label and sample rotated anchors against ground-truth instances for training', 'predict rotated region proposals from anchor deltas and objectness logits']
```

Usage

```
{'select_top_rrpn_proposals': 'select top-k rotated region proposals from feature maps with NMS filtering', 'create_rrpn_model': 'create a rotated region proposal network model from a detectron2 configuration', 'build_rrpn_from_config': 'build an RRPN proposal generator from detectron2 config and input feature map shapes', 'label_rrpn_anchors': 'label and sample rotated anchors against ground-truth instances for training', 'predict_rrpn_proposals': 'predict rotated region proposals from anchor deltas and objectness logits'}
```

