# Agent Python Tools

- repo: facebookresearch/DensePose
- repo_uri: https://github.com/facebookresearch/DensePose.git

## File: facebookresearch_DensePose/detectron/ops/collect_and_distribute_fpn_rpn_proposals.py

Prompts

```
['collect RPN proposals across FPN levels and retain the top scoring ones by score', 'distribute ROIs into per-level output blobs mapped to their corresponding FPN pyramid level', 'run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect and distribute RPN proposals for training or inference', 'review the collect function that concatenates ROI and score blobs and selects top-N proposals', 'review the distribute function that maps ROIs to FPN levels and creates per-level blobs', 'review the GenerateProposalLabelsOp class and its forward method for RPN ROI label generation', 'run the forward method of GenerateProposalLabelsOp to generate Fast R-CNN proposal labels from RPN ROIs', 'summarize the forward method that adds proposals to roidb and computes bounding box regression targets', 'test the GenerateProposalLabelsOp class to verify it correctly populates roidb entries with RPN-generated ROIs', 'refactor the forward method to support filtering crowd proposals instead of using crowd_thresh=0', 'build a GenerateProposalsOp to generate object detection proposals from RPN anchor boxes and bbox deltas', 'run the forward pass of GenerateProposalsOp to produce ROIs and probabilities from scores and deltas', 'test the proposals_for_one_image method to generate filtered proposals for a single image', 'refactor the _filter_boxes function to filter proposal boxes by minimum size and image bounds', 'review the GenerateProposalsOp class and its NMS-based proposal filtering pipeline for object detection']
```

Usage

```
{'collect_fpn_rpn_proposals': 'collect RPN proposals across FPN levels and retain the top scoring ones by score', 'distribute_rois_to_fpn_levels': 'distribute ROIs into per-level output blobs mapped to their corresponding FPN pyramid level', 'run_collect_and_distribute_op': 'run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect and distribute RPN proposals for training or inference', 'review_collect_function': 'review the collect function that concatenates ROI and score blobs and selects top-N proposals', 'review_distribute_function': 'review the distribute function that maps ROIs to FPN levels and creates per-level blobs'}
```

## File: facebookresearch_DensePose/detectron/ops/generate_proposal_labels.py

Prompts

```
['collect RPN proposals across FPN levels and retain the top scoring ones by score', 'distribute ROIs into per-level output blobs mapped to their corresponding FPN pyramid level', 'run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect and distribute RPN proposals for training or inference', 'review the collect function that concatenates ROI and score blobs and selects top-N proposals', 'review the distribute function that maps ROIs to FPN levels and creates per-level blobs', 'review the GenerateProposalLabelsOp class and its forward method for RPN ROI label generation', 'run the forward method of GenerateProposalLabelsOp to generate Fast R-CNN proposal labels from RPN ROIs', 'summarize the forward method that adds proposals to roidb and computes bounding box regression targets', 'test the GenerateProposalLabelsOp class to verify it correctly populates roidb entries with RPN-generated ROIs', 'refactor the forward method to support filtering crowd proposals instead of using crowd_thresh=0', 'build a GenerateProposalsOp to generate object detection proposals from RPN anchor boxes and bbox deltas', 'run the forward pass of GenerateProposalsOp to produce ROIs and probabilities from scores and deltas', 'test the proposals_for_one_image method to generate filtered proposals for a single image', 'refactor the _filter_boxes function to filter proposal boxes by minimum size and image bounds', 'review the GenerateProposalsOp class and its NMS-based proposal filtering pipeline for object detection']
```

Usage

```
{'review_GenerateProposalLabelsOp': 'review the GenerateProposalLabelsOp class and its forward method for RPN ROI label generation', 'run_GenerateProposalLabelsOp_forward': 'run the forward method of GenerateProposalLabelsOp to generate Fast R-CNN proposal labels from RPN ROIs', 'summarize_GenerateProposalLabelsOp_forward': 'summarize the forward method that adds proposals to roidb and computes bounding box regression targets', 'test_GenerateProposalLabelsOp': 'test the GenerateProposalLabelsOp class to verify it correctly populates roidb entries with RPN-generated ROIs', 'refactor_GenerateProposalLabelsOp_forward': 'refactor the forward method to support filtering crowd proposals instead of using crowd_thresh=0'}
```

## File: facebookresearch_DensePose/detectron/ops/generate_proposals.py

Prompts

```
['collect RPN proposals across FPN levels and retain the top scoring ones by score', 'distribute ROIs into per-level output blobs mapped to their corresponding FPN pyramid level', 'run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect and distribute RPN proposals for training or inference', 'review the collect function that concatenates ROI and score blobs and selects top-N proposals', 'review the distribute function that maps ROIs to FPN levels and creates per-level blobs', 'review the GenerateProposalLabelsOp class and its forward method for RPN ROI label generation', 'run the forward method of GenerateProposalLabelsOp to generate Fast R-CNN proposal labels from RPN ROIs', 'summarize the forward method that adds proposals to roidb and computes bounding box regression targets', 'test the GenerateProposalLabelsOp class to verify it correctly populates roidb entries with RPN-generated ROIs', 'refactor the forward method to support filtering crowd proposals instead of using crowd_thresh=0', 'build a GenerateProposalsOp to generate object detection proposals from RPN anchor boxes and bbox deltas', 'run the forward pass of GenerateProposalsOp to produce ROIs and probabilities from scores and deltas', 'test the proposals_for_one_image method to generate filtered proposals for a single image', 'refactor the _filter_boxes function to filter proposal boxes by minimum size and image bounds', 'review the GenerateProposalsOp class and its NMS-based proposal filtering pipeline for object detection']
```

Usage

```
{'build_RPN_proposal_generator': 'build a GenerateProposalsOp to generate object detection proposals from RPN anchor boxes and bbox deltas', 'run_forward_proposals': 'run the forward pass of GenerateProposalsOp to produce ROIs and probabilities from scores and deltas', 'test_proposals_for_one_image': 'test the proposals_for_one_image method to generate filtered proposals for a single image', 'refactor_filter_boxes': 'refactor the _filter_boxes function to filter proposal boxes by minimum size and image bounds', 'review_NMS_proposal_pipeline': 'review the GenerateProposalsOp class and its NMS-based proposal filtering pipeline for object detection'}
```

