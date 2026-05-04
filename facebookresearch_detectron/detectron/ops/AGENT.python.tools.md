# Agent Python Tools

- repo: facebookresearch/detectron
- repo_uri: https://github.com/facebookresearch/detectron

## File: facebookresearch_detectron/detectron/ops/collect_and_distribute_fpn_rpn_proposals.py

Prompts

```
['create a function that collects RPN proposals from multiple FPN levels and returns top scoring ROIs', 'build a module that distributes ROIs across FPN levels based on spatial scale mapping', 'run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect and distribute RPN proposals for training or inference', 'review the CollectAndDistributeFpnRpnProposalsOp class and its forward method for FPN RPN proposal handling', 'summarize the collect and distribute FPN RPN proposals module for object detection ROI processing', 'run the GenerateProposalLabelsOp forward method to generate labeled proposal blobs from RPN outputs', 'review the GenerateProposalLabelsOp class and its forward method for Faster R-CNN proposal label generation', 'summarize the GenerateProposalLabelsOp forward method which adds proposals to roidb and computes bounding box regression targets', 'test the GenerateProposalLabelsOp forward method with sample RPN rois and roidb inputs', 'refactor the GenerateProposalLabelsOp forward method to support filtering crowd proposals instead of using crowd_thresh=0', 'build a python module to generate object detection proposals from RPN anchor boxes and predicted bbox deltas', 'create a GenerateProposalsOp instance with anchors, spatial scale, and regression weights for proposal generation', 'run the forward method on GenerateProposalsOp to produce ROI proposals and probabilities from RPN outputs', 'test the proposals_for_one_image method to verify NMS filtering and scoring of detection proposals', 'review the _filter_boxes function that filters proposal boxes by minimum size and image center bounds']
```

Usage

```
{'collect_fpn_rpn_proposals': 'create a function that collects RPN proposals from multiple FPN levels and returns top scoring ROIs', 'distribute_rois_across_fpn_levels': 'build a module that distributes ROIs across FPN levels based on spatial scale mapping', 'run_CollectAndDistributeFpnRpnProposalsOp_forward': 'run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect and distribute RPN proposals for training or inference', 'review_CollectAndDistributeFpnRpnProposalsOp': 'review the CollectAndDistributeFpnRpnProposalsOp class and its forward method for FPN RPN proposal handling', 'summarize_collect_and_distribute_fpn_rpn_proposals': 'summarize the collect and distribute FPN RPN proposals module for object detection ROI processing'}
```

## File: facebookresearch_detectron/detectron/ops/generate_proposal_labels.py

Prompts

```
['create a function that collects RPN proposals from multiple FPN levels and returns top scoring ROIs', 'build a module that distributes ROIs across FPN levels based on spatial scale mapping', 'run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect and distribute RPN proposals for training or inference', 'review the CollectAndDistributeFpnRpnProposalsOp class and its forward method for FPN RPN proposal handling', 'summarize the collect and distribute FPN RPN proposals module for object detection ROI processing', 'run the GenerateProposalLabelsOp forward method to generate labeled proposal blobs from RPN outputs', 'review the GenerateProposalLabelsOp class and its forward method for Faster R-CNN proposal label generation', 'summarize the GenerateProposalLabelsOp forward method which adds proposals to roidb and computes bounding box regression targets', 'test the GenerateProposalLabelsOp forward method with sample RPN rois and roidb inputs', 'refactor the GenerateProposalLabelsOp forward method to support filtering crowd proposals instead of using crowd_thresh=0', 'build a python module to generate object detection proposals from RPN anchor boxes and predicted bbox deltas', 'create a GenerateProposalsOp instance with anchors, spatial scale, and regression weights for proposal generation', 'run the forward method on GenerateProposalsOp to produce ROI proposals and probabilities from RPN outputs', 'test the proposals_for_one_image method to verify NMS filtering and scoring of detection proposals', 'review the _filter_boxes function that filters proposal boxes by minimum size and image center bounds']
```

Usage

```
{'run_GenerateProposalLabelsOp_forward': 'run the GenerateProposalLabelsOp forward method to generate labeled proposal blobs from RPN outputs', 'review_GenerateProposalLabelsOp': 'review the GenerateProposalLabelsOp class and its forward method for Faster R-CNN proposal label generation', 'summarize_GenerateProposalLabelsOp_forward': 'summarize the GenerateProposalLabelsOp forward method which adds proposals to roidb and computes bounding box regression targets', 'test_GenerateProposalLabelsOp_forward': 'test the GenerateProposalLabelsOp forward method with sample RPN rois and roidb inputs', 'refactor_GenerateProposalLabelsOp_forward': 'refactor the GenerateProposalLabelsOp forward method to support filtering crowd proposals instead of using crowd_thresh=0'}
```

## File: facebookresearch_detectron/detectron/ops/generate_proposals.py

Prompts

```
['create a function that collects RPN proposals from multiple FPN levels and returns top scoring ROIs', 'build a module that distributes ROIs across FPN levels based on spatial scale mapping', 'run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect and distribute RPN proposals for training or inference', 'review the CollectAndDistributeFpnRpnProposalsOp class and its forward method for FPN RPN proposal handling', 'summarize the collect and distribute FPN RPN proposals module for object detection ROI processing', 'run the GenerateProposalLabelsOp forward method to generate labeled proposal blobs from RPN outputs', 'review the GenerateProposalLabelsOp class and its forward method for Faster R-CNN proposal label generation', 'summarize the GenerateProposalLabelsOp forward method which adds proposals to roidb and computes bounding box regression targets', 'test the GenerateProposalLabelsOp forward method with sample RPN rois and roidb inputs', 'refactor the GenerateProposalLabelsOp forward method to support filtering crowd proposals instead of using crowd_thresh=0', 'build a python module to generate object detection proposals from RPN anchor boxes and predicted bbox deltas', 'create a GenerateProposalsOp instance with anchors, spatial scale, and regression weights for proposal generation', 'run the forward method on GenerateProposalsOp to produce ROI proposals and probabilities from RPN outputs', 'test the proposals_for_one_image method to verify NMS filtering and scoring of detection proposals', 'review the _filter_boxes function that filters proposal boxes by minimum size and image center bounds']
```

Usage

```
{'build_rpn_proposal_generator': 'build a python module to generate object detection proposals from RPN anchor boxes and predicted bbox deltas', 'create_generate_proposals_op': 'create a GenerateProposalsOp instance with anchors, spatial scale, and regression weights for proposal generation', 'run_forward_proposals': 'run the forward method on GenerateProposalsOp to produce ROI proposals and probabilities from RPN outputs', 'test_proposals_for_one_image': 'test the proposals_for_one_image method to verify NMS filtering and scoring of detection proposals', 'review_filter_boxes': 'review the _filter_boxes function that filters proposal boxes by minimum size and image center bounds'}
```

