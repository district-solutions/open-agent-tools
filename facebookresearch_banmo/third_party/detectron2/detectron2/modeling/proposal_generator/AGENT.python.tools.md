# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/detectron2/modeling/proposal_generator/build.py

Prompts

```
['build a proposal generator from cfg.MODEL.PROPOSAL_GENERATOR.NAME using the PROPOSAL_GENERATOR_REGISTRY', 'review the PROPOSAL_GENERATOR_REGISTRY registry for object proposal generation from feature maps', 'summarize the build_proposal_generator function that constructs proposal generators from config', 'test the build_proposal_generator function with PrecomputedProposals config to verify it returns None', 'refactor the PROPOSAL_GENERATOR_REGISTRY to support additional proposal generator types beyond RPN and RRPN', 'select top scoring RPN proposals across feature maps, apply NMS, clip boxes, and filter small boxes for each image', 'augment a batch of proposal Instances with ground-truth boxes across all images in the batch', "augment a single image's proposal Instances with ground-truth boxes by assigning high objectness logits", 'review the find_top_rpn_proposals function to understand pre-NMS top-k selection, per-level NMS, and post-NMS filtering logic', 'summarize the add_ground_truth_to_proposals function that concatenates ground-truth boxes with proposals using high objectness logits', 'build an RPN head module from config to predict objectness logits and anchor deltas for feature maps', 'create a StandardRPNHead with configurable conv layers to classify anchors and regress bounding box deltas', 'build a Region Proposal Network from config with anchor generator, matcher, and head for Faster R-CNN', 'label and sample anchors by matching them with ground truth boxes using IoU and subsampling', 'compute RPN classification and localization losses from predicted objectness logits and anchor deltas', 'build a rotated region proposal network using RRPN class registered in PROPOSAL_GENERATOR_REGISTRY', 'create top rotated RPN proposals by selecting pre_nms_topk and applying batched NMS with rotated boxes', 'predict rotated region proposals by decoding anchor deltas and selecting top scoring proposals after NMS', 'review the RRPN from_config method to configure Box2BoxTransformRotated with custom bbox regression weights']
```

Usage

```
{'build_proposal_generator': 'build a proposal generator from cfg.MODEL.PROPOSAL_GENERATOR.NAME using the PROPOSAL_GENERATOR_REGISTRY', 'review_PROPOSAL_GENERATOR_REGISTRY': 'review the PROPOSAL_GENERATOR_REGISTRY registry for object proposal generation from feature maps', 'summarize_build_proposal_generator': 'summarize the build_proposal_generator function that constructs proposal generators from config', 'test_build_proposal_generator': 'test the build_proposal_generator function with PrecomputedProposals config to verify it returns None', 'refactor_PROPOSAL_GENERATOR_REGISTRY': 'refactor the PROPOSAL_GENERATOR_REGISTRY to support additional proposal generator types beyond RPN and RRPN'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/modeling/proposal_generator/proposal_utils.py

Prompts

```
['build a proposal generator from cfg.MODEL.PROPOSAL_GENERATOR.NAME using the PROPOSAL_GENERATOR_REGISTRY', 'review the PROPOSAL_GENERATOR_REGISTRY registry for object proposal generation from feature maps', 'summarize the build_proposal_generator function that constructs proposal generators from config', 'test the build_proposal_generator function with PrecomputedProposals config to verify it returns None', 'refactor the PROPOSAL_GENERATOR_REGISTRY to support additional proposal generator types beyond RPN and RRPN', 'select top scoring RPN proposals across feature maps, apply NMS, clip boxes, and filter small boxes for each image', 'augment a batch of proposal Instances with ground-truth boxes across all images in the batch', "augment a single image's proposal Instances with ground-truth boxes by assigning high objectness logits", 'review the find_top_rpn_proposals function to understand pre-NMS top-k selection, per-level NMS, and post-NMS filtering logic', 'summarize the add_ground_truth_to_proposals function that concatenates ground-truth boxes with proposals using high objectness logits', 'build an RPN head module from config to predict objectness logits and anchor deltas for feature maps', 'create a StandardRPNHead with configurable conv layers to classify anchors and regress bounding box deltas', 'build a Region Proposal Network from config with anchor generator, matcher, and head for Faster R-CNN', 'label and sample anchors by matching them with ground truth boxes using IoU and subsampling', 'compute RPN classification and localization losses from predicted objectness logits and anchor deltas', 'build a rotated region proposal network using RRPN class registered in PROPOSAL_GENERATOR_REGISTRY', 'create top rotated RPN proposals by selecting pre_nms_topk and applying batched NMS with rotated boxes', 'predict rotated region proposals by decoding anchor deltas and selecting top scoring proposals after NMS', 'review the RRPN from_config method to configure Box2BoxTransformRotated with custom bbox regression weights']
```

Usage

```
{'find_top_rpn_proposals': 'select top scoring RPN proposals across feature maps, apply NMS, clip boxes, and filter small boxes for each image', 'add_ground_truth_to_proposals': 'augment a batch of proposal Instances with ground-truth boxes across all images in the batch', 'add_ground_truth_to_proposals_single_image': "augment a single image's proposal Instances with ground-truth boxes by assigning high objectness logits", 'review_find_top_rpn_proposals': 'review the find_top_rpn_proposals function to understand pre-NMS top-k selection, per-level NMS, and post-NMS filtering logic', 'summarize_add_ground_truth_to_proposals': 'summarize the add_ground_truth_to_proposals function that concatenates ground-truth boxes with proposals using high objectness logits'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/modeling/proposal_generator/rpn.py

Prompts

```
['build a proposal generator from cfg.MODEL.PROPOSAL_GENERATOR.NAME using the PROPOSAL_GENERATOR_REGISTRY', 'review the PROPOSAL_GENERATOR_REGISTRY registry for object proposal generation from feature maps', 'summarize the build_proposal_generator function that constructs proposal generators from config', 'test the build_proposal_generator function with PrecomputedProposals config to verify it returns None', 'refactor the PROPOSAL_GENERATOR_REGISTRY to support additional proposal generator types beyond RPN and RRPN', 'select top scoring RPN proposals across feature maps, apply NMS, clip boxes, and filter small boxes for each image', 'augment a batch of proposal Instances with ground-truth boxes across all images in the batch', "augment a single image's proposal Instances with ground-truth boxes by assigning high objectness logits", 'review the find_top_rpn_proposals function to understand pre-NMS top-k selection, per-level NMS, and post-NMS filtering logic', 'summarize the add_ground_truth_to_proposals function that concatenates ground-truth boxes with proposals using high objectness logits', 'build an RPN head module from config to predict objectness logits and anchor deltas for feature maps', 'create a StandardRPNHead with configurable conv layers to classify anchors and regress bounding box deltas', 'build a Region Proposal Network from config with anchor generator, matcher, and head for Faster R-CNN', 'label and sample anchors by matching them with ground truth boxes using IoU and subsampling', 'compute RPN classification and localization losses from predicted objectness logits and anchor deltas', 'build a rotated region proposal network using RRPN class registered in PROPOSAL_GENERATOR_REGISTRY', 'create top rotated RPN proposals by selecting pre_nms_topk and applying batched NMS with rotated boxes', 'predict rotated region proposals by decoding anchor deltas and selecting top scoring proposals after NMS', 'review the RRPN from_config method to configure Box2BoxTransformRotated with custom bbox regression weights']
```

Usage

```
{'build_rpn_head': 'build an RPN head module from config to predict objectness logits and anchor deltas for feature maps', 'create_standard_rpn_head': 'create a StandardRPNHead with configurable conv layers to classify anchors and regress bounding box deltas', 'build_rpn': 'build a Region Proposal Network from config with anchor generator, matcher, and head for Faster R-CNN', 'label_and_sample_anchors': 'label and sample anchors by matching them with ground truth boxes using IoU and subsampling', 'compute_rpn_losses': 'compute RPN classification and localization losses from predicted objectness logits and anchor deltas'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/modeling/proposal_generator/rrpn.py

Prompts

```
['build a proposal generator from cfg.MODEL.PROPOSAL_GENERATOR.NAME using the PROPOSAL_GENERATOR_REGISTRY', 'review the PROPOSAL_GENERATOR_REGISTRY registry for object proposal generation from feature maps', 'summarize the build_proposal_generator function that constructs proposal generators from config', 'test the build_proposal_generator function with PrecomputedProposals config to verify it returns None', 'refactor the PROPOSAL_GENERATOR_REGISTRY to support additional proposal generator types beyond RPN and RRPN', 'select top scoring RPN proposals across feature maps, apply NMS, clip boxes, and filter small boxes for each image', 'augment a batch of proposal Instances with ground-truth boxes across all images in the batch', "augment a single image's proposal Instances with ground-truth boxes by assigning high objectness logits", 'review the find_top_rpn_proposals function to understand pre-NMS top-k selection, per-level NMS, and post-NMS filtering logic', 'summarize the add_ground_truth_to_proposals function that concatenates ground-truth boxes with proposals using high objectness logits', 'build an RPN head module from config to predict objectness logits and anchor deltas for feature maps', 'create a StandardRPNHead with configurable conv layers to classify anchors and regress bounding box deltas', 'build a Region Proposal Network from config with anchor generator, matcher, and head for Faster R-CNN', 'label and sample anchors by matching them with ground truth boxes using IoU and subsampling', 'compute RPN classification and localization losses from predicted objectness logits and anchor deltas', 'build a rotated region proposal network using RRPN class registered in PROPOSAL_GENERATOR_REGISTRY', 'create top rotated RPN proposals by selecting pre_nms_topk and applying batched NMS with rotated boxes', 'predict rotated region proposals by decoding anchor deltas and selecting top scoring proposals after NMS', 'review the RRPN from_config method to configure Box2BoxTransformRotated with custom bbox regression weights']
```

Usage

```
{'build_rrpn_proposal_generator': 'build a rotated region proposal network using RRPN class registered in PROPOSAL_GENERATOR_REGISTRY', 'create_top_rrpn_proposals': 'create top rotated RPN proposals by selecting pre_nms_topk and applying batched NMS with rotated boxes', 'label_and_sample_anchors': 'label and sample rotated anchors by computing pairwise IoU with ground truth boxes and subsampling labels', 'predict_rrpn_proposals': 'predict rotated region proposals by decoding anchor deltas and selecting top scoring proposals after NMS', 'review_rrpn_from_config': 'review the RRPN from_config method to configure Box2BoxTransformRotated with custom bbox regression weights'}
```

