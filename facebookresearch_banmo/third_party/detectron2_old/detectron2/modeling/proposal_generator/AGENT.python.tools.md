# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/modeling/proposal_generator/build.py

Prompts

```
['build a proposal generator from a detectron2 config and input shape using build_proposal_generator', 'register a custom proposal generator class with PROPOSAL_GENERATOR_REGISTRY for use in detectron2', 'set MODEL.PROPOSAL_GENERATOR.NAME to PrecomputedProposals to skip building a proposal generator', 'review the PROPOSAL_GENERATOR_REGISTRY to see registered RPN and RRPN proposal generators', 'summarize the build_proposal_generator function which constructs RPN or RRPN modules from config', 'find top RPN proposals from feature map predictions using NMS and objectness logits filtering', 'add ground truth boxes to a list of proposal instances across all images in a batch', 'augment a single image proposals with ground truth boxes and high objectness logits', 'review the find_top_rpn_proposals function to understand pre-NMS topk selection and post-NMS filtering logic', 'refactor the add_ground_truth_to_proposals function to support custom ground truth logit values', 'build a StandardRPNHead module that predicts objectness logits and anchor deltas from feature maps', 'build an RPN module with configurable head, anchor generator, matcher, and box2box transform', 'label anchors as positive/negative/ignore by matching them with ground truth instances using IoU', 'compute classification and localization losses for RPN predictions against ground truth labels', 'decode predicted anchor deltas into proposals and select top candidates using NMS filtering', 'select top-k rotated region proposals from feature maps and apply NMS to filter results', 'label rotated anchors with ground-truth boxes using pairwise IoU matching and subsample labels', 'decode anchor deltas into rotated proposals and select top proposals using NMS filtering', 'build a Rotated RPN instance from Detectron2 config with rotated box-to-box transform weights', 'review the Rotated RPN class that extends RPN for rotated region proposal generation in Detectron2']
```

Usage

```
{'build_proposal_generator_from_cfg': 'build a proposal generator from a detectron2 config and input shape using build_proposal_generator', 'register_custom_proposal_generator': 'register a custom proposal generator class with PROPOSAL_GENERATOR_REGISTRY for use in detectron2', 'use_precomputed_proposals': 'set MODEL.PROPOSAL_GENERATOR.NAME to PrecomputedProposals to skip building a proposal generator', 'review_PROPOSAL_GENERATOR_REGISTRY': 'review the PROPOSAL_GENERATOR_REGISTRY to see registered RPN and RRPN proposal generators', 'summarize_build_proposal_generator': 'summarize the build_proposal_generator function which constructs RPN or RRPN modules from config'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/modeling/proposal_generator/proposal_utils.py

Prompts

```
['build a proposal generator from a detectron2 config and input shape using build_proposal_generator', 'register a custom proposal generator class with PROPOSAL_GENERATOR_REGISTRY for use in detectron2', 'set MODEL.PROPOSAL_GENERATOR.NAME to PrecomputedProposals to skip building a proposal generator', 'review the PROPOSAL_GENERATOR_REGISTRY to see registered RPN and RRPN proposal generators', 'summarize the build_proposal_generator function which constructs RPN or RRPN modules from config', 'find top RPN proposals from feature map predictions using NMS and objectness logits filtering', 'add ground truth boxes to a list of proposal instances across all images in a batch', 'augment a single image proposals with ground truth boxes and high objectness logits', 'review the find_top_rpn_proposals function to understand pre-NMS topk selection and post-NMS filtering logic', 'refactor the add_ground_truth_to_proposals function to support custom ground truth logit values', 'build a StandardRPNHead module that predicts objectness logits and anchor deltas from feature maps', 'build an RPN module with configurable head, anchor generator, matcher, and box2box transform', 'label anchors as positive/negative/ignore by matching them with ground truth instances using IoU', 'compute classification and localization losses for RPN predictions against ground truth labels', 'decode predicted anchor deltas into proposals and select top candidates using NMS filtering', 'select top-k rotated region proposals from feature maps and apply NMS to filter results', 'label rotated anchors with ground-truth boxes using pairwise IoU matching and subsample labels', 'decode anchor deltas into rotated proposals and select top proposals using NMS filtering', 'build a Rotated RPN instance from Detectron2 config with rotated box-to-box transform weights', 'review the Rotated RPN class that extends RPN for rotated region proposal generation in Detectron2']
```

Usage

```
{'find_top_rpn_proposals': 'find top RPN proposals from feature map predictions using NMS and objectness logits filtering', 'add_ground_truth_to_proposals': 'add ground truth boxes to a list of proposal instances across all images in a batch', 'add_ground_truth_to_proposals_single_image': 'augment a single image proposals with ground truth boxes and high objectness logits', 'review_find_top_rpn_proposals': 'review the find_top_rpn_proposals function to understand pre-NMS topk selection and post-NMS filtering logic', 'refactor_add_ground_truth_to_proposals': 'refactor the add_ground_truth_to_proposals function to support custom ground truth logit values'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/modeling/proposal_generator/rpn.py

Prompts

```
['build a proposal generator from a detectron2 config and input shape using build_proposal_generator', 'register a custom proposal generator class with PROPOSAL_GENERATOR_REGISTRY for use in detectron2', 'set MODEL.PROPOSAL_GENERATOR.NAME to PrecomputedProposals to skip building a proposal generator', 'review the PROPOSAL_GENERATOR_REGISTRY to see registered RPN and RRPN proposal generators', 'summarize the build_proposal_generator function which constructs RPN or RRPN modules from config', 'find top RPN proposals from feature map predictions using NMS and objectness logits filtering', 'add ground truth boxes to a list of proposal instances across all images in a batch', 'augment a single image proposals with ground truth boxes and high objectness logits', 'review the find_top_rpn_proposals function to understand pre-NMS topk selection and post-NMS filtering logic', 'refactor the add_ground_truth_to_proposals function to support custom ground truth logit values', 'build a StandardRPNHead module that predicts objectness logits and anchor deltas from feature maps', 'build an RPN module with configurable head, anchor generator, matcher, and box2box transform', 'label anchors as positive/negative/ignore by matching them with ground truth instances using IoU', 'compute classification and localization losses for RPN predictions against ground truth labels', 'decode predicted anchor deltas into proposals and select top candidates using NMS filtering', 'select top-k rotated region proposals from feature maps and apply NMS to filter results', 'label rotated anchors with ground-truth boxes using pairwise IoU matching and subsample labels', 'decode anchor deltas into rotated proposals and select top proposals using NMS filtering', 'build a Rotated RPN instance from Detectron2 config with rotated box-to-box transform weights', 'review the Rotated RPN class that extends RPN for rotated region proposal generation in Detectron2']
```

Usage

```
{'build_rpn_head': 'build a StandardRPNHead module that predicts objectness logits and anchor deltas from feature maps', 'build_rpn': 'build an RPN module with configurable head, anchor generator, matcher, and box2box transform', 'label_and_sample_anchors': 'label anchors as positive/negative/ignore by matching them with ground truth instances using IoU', 'compute_rpn_losses': 'compute classification and localization losses for RPN predictions against ground truth labels', 'predict_proposals': 'decode predicted anchor deltas into proposals and select top candidates using NMS filtering'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/modeling/proposal_generator/rrpn.py

Prompts

```
['build a proposal generator from a detectron2 config and input shape using build_proposal_generator', 'register a custom proposal generator class with PROPOSAL_GENERATOR_REGISTRY for use in detectron2', 'set MODEL.PROPOSAL_GENERATOR.NAME to PrecomputedProposals to skip building a proposal generator', 'review the PROPOSAL_GENERATOR_REGISTRY to see registered RPN and RRPN proposal generators', 'summarize the build_proposal_generator function which constructs RPN or RRPN modules from config', 'find top RPN proposals from feature map predictions using NMS and objectness logits filtering', 'add ground truth boxes to a list of proposal instances across all images in a batch', 'augment a single image proposals with ground truth boxes and high objectness logits', 'review the find_top_rpn_proposals function to understand pre-NMS topk selection and post-NMS filtering logic', 'refactor the add_ground_truth_to_proposals function to support custom ground truth logit values', 'build a StandardRPNHead module that predicts objectness logits and anchor deltas from feature maps', 'build an RPN module with configurable head, anchor generator, matcher, and box2box transform', 'label anchors as positive/negative/ignore by matching them with ground truth instances using IoU', 'compute classification and localization losses for RPN predictions against ground truth labels', 'decode predicted anchor deltas into proposals and select top candidates using NMS filtering', 'select top-k rotated region proposals from feature maps and apply NMS to filter results', 'label rotated anchors with ground-truth boxes using pairwise IoU matching and subsample labels', 'decode anchor deltas into rotated proposals and select top proposals using NMS filtering', 'build a Rotated RPN instance from Detectron2 config with rotated box-to-box transform weights', 'review the Rotated RPN class that extends RPN for rotated region proposal generation in Detectron2']
```

Usage

```
{'find_top_rrpn_proposals': 'select top-k rotated region proposals from feature maps and apply NMS to filter results', 'RRPN_label_and_sample_anchors': 'label rotated anchors with ground-truth boxes using pairwise IoU matching and subsample labels', 'RRPN_predict_proposals': 'decode anchor deltas into rotated proposals and select top proposals using NMS filtering', 'RRPN_from_config': 'build a Rotated RPN instance from Detectron2 config with rotated box-to-box transform weights', 'review_RRPN_class': 'review the Rotated RPN class that extends RPN for rotated region proposal generation in Detectron2'}
```

