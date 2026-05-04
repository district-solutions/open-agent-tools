# Agent Python Tools

- repo: facebookresearch/densepose
- repo_uri: https://github.com/facebookresearch/densepose

## File: facebookresearch_densepose/detectron/ops/collect_and_distribute_fpn_rpn_proposals.py

Prompts

```
['run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect RPN proposals across FPN levels and distribute them for training or inference', 'review the collect function that concatenates ROI and score blobs across FPN levels and returns top scoring proposals by post NMS ranking', 'review the distribute function that maps ROIs to FPN levels and creates per-level ROI blobs with a restore index array', 'test the CollectAndDistributeFpnRpnProposalsOp class to verify it correctly collects RPN proposals and distributes them across FPN pyramid levels', 'refactor the CollectAndDistributeFpnRpnProposalsOp forward method to support custom crowd filtering thresholds instead of the hardcoded zero value', 'run the GenerateProposalLabelsOp forward method to process RPN ROIs and generate Fast R-CNN training blobs', 'review the GenerateProposalLabelsOp class and its forward method for Faster R-CNN proposal label generation', 'refactor the forward method to support configurable crowd threshold filtering instead of hardcoded zero', 'summarize the GenerateProposalLabelsOp class that adds proposals, computes bbox regression targets, and produces Fast R-CNN blobs', 'test the GenerateProposalLabelsOp forward method with mock inputs to verify blob output correctness', 'review the GenerateProposalsOp class that generates object detection proposals from RPN anchors and bbox deltas', 'review the forward method that generates ROI proposals by applying bbox transformations to shifted anchors', 'review the proposals_for_one_image method that filters and applies NMS to proposals for a single image', 'review the _filter_boxes function that keeps only boxes with sufficient size and centers within the image', 'summarize the RPN proposal generation pipeline including anchor shifting, scoring, filtering, and NMS steps']
```

Usage

```
{'run_collect_and_distribute_fpn_rpn_proposals_op': 'run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect RPN proposals across FPN levels and distribute them for training or inference', 'review_collect_function': 'review the collect function that concatenates ROI and score blobs across FPN levels and returns top scoring proposals by post NMS ranking', 'review_distribute_function': 'review the distribute function that maps ROIs to FPN levels and creates per-level ROI blobs with a restore index array', 'test_collect_and_distribute_fpn_rpn_proposals_op': 'test the CollectAndDistributeFpnRpnProposalsOp class to verify it correctly collects RPN proposals and distributes them across FPN pyramid levels', 'refactor_collect_and_distribute_fpn_rpn_proposals_op': 'refactor the CollectAndDistributeFpnRpnProposalsOp forward method to support custom crowd filtering thresholds instead of the hardcoded zero value'}
```

## File: facebookresearch_densepose/detectron/ops/generate_proposal_labels.py

Prompts

```
['run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect RPN proposals across FPN levels and distribute them for training or inference', 'review the collect function that concatenates ROI and score blobs across FPN levels and returns top scoring proposals by post NMS ranking', 'review the distribute function that maps ROIs to FPN levels and creates per-level ROI blobs with a restore index array', 'test the CollectAndDistributeFpnRpnProposalsOp class to verify it correctly collects RPN proposals and distributes them across FPN pyramid levels', 'refactor the CollectAndDistributeFpnRpnProposalsOp forward method to support custom crowd filtering thresholds instead of the hardcoded zero value', 'run the GenerateProposalLabelsOp forward method to process RPN ROIs and generate Fast R-CNN training blobs', 'review the GenerateProposalLabelsOp class and its forward method for Faster R-CNN proposal label generation', 'refactor the forward method to support configurable crowd threshold filtering instead of hardcoded zero', 'summarize the GenerateProposalLabelsOp class that adds proposals, computes bbox regression targets, and produces Fast R-CNN blobs', 'test the GenerateProposalLabelsOp forward method with mock inputs to verify blob output correctness', 'review the GenerateProposalsOp class that generates object detection proposals from RPN anchors and bbox deltas', 'review the forward method that generates ROI proposals by applying bbox transformations to shifted anchors', 'review the proposals_for_one_image method that filters and applies NMS to proposals for a single image', 'review the _filter_boxes function that keeps only boxes with sufficient size and centers within the image', 'summarize the RPN proposal generation pipeline including anchor shifting, scoring, filtering, and NMS steps']
```

Usage

```
{'run_GenerateProposalLabelsOp_forward': 'run the GenerateProposalLabelsOp forward method to process RPN ROIs and generate Fast R-CNN training blobs', 'review_GenerateProposalLabelsOp': 'review the GenerateProposalLabelsOp class and its forward method for Faster R-CNN proposal label generation', 'refactor_GenerateProposalLabelsOp_forward': 'refactor the forward method to support configurable crowd threshold filtering instead of hardcoded zero', 'summarize_GenerateProposalLabelsOp': 'summarize the GenerateProposalLabelsOp class that adds proposals, computes bbox regression targets, and produces Fast R-CNN blobs', 'test_GenerateProposalLabelsOp_forward': 'test the GenerateProposalLabelsOp forward method with mock inputs to verify blob output correctness'}
```

## File: facebookresearch_densepose/detectron/ops/generate_proposals.py

Prompts

```
['run the CollectAndDistributeFpnRpnProposalsOp forward pass to collect RPN proposals across FPN levels and distribute them for training or inference', 'review the collect function that concatenates ROI and score blobs across FPN levels and returns top scoring proposals by post NMS ranking', 'review the distribute function that maps ROIs to FPN levels and creates per-level ROI blobs with a restore index array', 'test the CollectAndDistributeFpnRpnProposalsOp class to verify it correctly collects RPN proposals and distributes them across FPN pyramid levels', 'refactor the CollectAndDistributeFpnRpnProposalsOp forward method to support custom crowd filtering thresholds instead of the hardcoded zero value', 'run the GenerateProposalLabelsOp forward method to process RPN ROIs and generate Fast R-CNN training blobs', 'review the GenerateProposalLabelsOp class and its forward method for Faster R-CNN proposal label generation', 'refactor the forward method to support configurable crowd threshold filtering instead of hardcoded zero', 'summarize the GenerateProposalLabelsOp class that adds proposals, computes bbox regression targets, and produces Fast R-CNN blobs', 'test the GenerateProposalLabelsOp forward method with mock inputs to verify blob output correctness', 'review the GenerateProposalsOp class that generates object detection proposals from RPN anchors and bbox deltas', 'review the forward method that generates ROI proposals by applying bbox transformations to shifted anchors', 'review the proposals_for_one_image method that filters and applies NMS to proposals for a single image', 'review the _filter_boxes function that keeps only boxes with sufficient size and centers within the image', 'summarize the RPN proposal generation pipeline including anchor shifting, scoring, filtering, and NMS steps']
```

Usage

```
{'review_GenerateProposalsOp': 'review the GenerateProposalsOp class that generates object detection proposals from RPN anchors and bbox deltas', 'review_forward_method': 'review the forward method that generates ROI proposals by applying bbox transformations to shifted anchors', 'review_proposals_for_one_image': 'review the proposals_for_one_image method that filters and applies NMS to proposals for a single image', 'review_filter_boxes': 'review the _filter_boxes function that keeps only boxes with sufficient size and centers within the image', 'summarize_RPN_proposal_pipeline': 'summarize the RPN proposal generation pipeline including anchor shifting, scoring, filtering, and NMS steps'}
```

