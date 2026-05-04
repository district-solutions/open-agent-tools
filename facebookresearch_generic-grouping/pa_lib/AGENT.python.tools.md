# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/pa_lib/affinity2mask.py

Prompts

```
['build a python module that converts predicted potentials to binary masks using connected component graph thresholding', 'build a python module that converts max potential maps to segmentation masks using watershed algorithm', 'build a python module that generates hierarchical segments from potentials using watershed and RAG merging', 'build a python module that converts 4-directional potential tensors into a skimage RAG graph with weighted edges', 'build a python module that computes globalized boundary maps from local boundary probabilities using eigenvector analysis', 'generate segmentation proposals and scores from a pairwise affinity tensor using potential2masks and ranking', 'compute the IoU between two binary mask arrays or torch tensors with an optional threshold', 'rank segmentation masks by color variance in an image with optional NMS filtering', 'evaluate detection results using the COCO evaluation protocol with optional category filtering', 'rank segmentation proposals by boundary potential scores with NMS and edge filtering', 'generate object proposals from predicted affinity maps using an OLN model with configurable edge and join thresholds', 'compute RPN centerness scores for proposals by matching anchors via IoU overlap with an OLN model', "compute ROI classification scores for proposals using the OLN model's RoI head simple test method", 'review the generate_pa_proposals_with_oln function to understand how affinity maps are converted to ranked object proposals', 'refactor compute_rpn_score_oln to support batched proposal scoring across multiple images', 'build a region adjacency graph from an image and labels using mean color distance between regions', 'build a region adjacency graph from labels and an edge map using boundary pixel values', 'merge regions in a RAG hierarchically by greedily combining nodes with edge weights below a threshold', 'merge two nodes in a RAG and recompute edge weights using a custom weight function', 'visualize a region adjacency graph overlaid on an image with colored edges and region borders']
```

Usage

```
{'build_masks_from_potentials_cc': 'build a python module that converts predicted potentials to binary masks using connected component graph thresholding', 'build_masks_from_potentials_watershed': 'build a python module that converts max potential maps to segmentation masks using watershed algorithm', 'build_masks_from_ucm_hierarchy': 'build a python module that generates hierarchical segments from potentials using watershed and RAG merging', 'build_graph_from_potentials': 'build a python module that converts 4-directional potential tensors into a skimage RAG graph with weighted edges', 'build_globalized_boundary': 'build a python module that computes globalized boundary maps from local boundary probabilities using eigenvector analysis'}
```

## File: facebookresearch_generic-grouping/pa_lib/evaluate_helper.py

Prompts

```
['build a python module that converts predicted potentials to binary masks using connected component graph thresholding', 'build a python module that converts max potential maps to segmentation masks using watershed algorithm', 'build a python module that generates hierarchical segments from potentials using watershed and RAG merging', 'build a python module that converts 4-directional potential tensors into a skimage RAG graph with weighted edges', 'build a python module that computes globalized boundary maps from local boundary probabilities using eigenvector analysis', 'generate segmentation proposals and scores from a pairwise affinity tensor using potential2masks and ranking', 'compute the IoU between two binary mask arrays or torch tensors with an optional threshold', 'rank segmentation masks by color variance in an image with optional NMS filtering', 'evaluate detection results using the COCO evaluation protocol with optional category filtering', 'rank segmentation proposals by boundary potential scores with NMS and edge filtering', 'generate object proposals from predicted affinity maps using an OLN model with configurable edge and join thresholds', 'compute RPN centerness scores for proposals by matching anchors via IoU overlap with an OLN model', "compute ROI classification scores for proposals using the OLN model's RoI head simple test method", 'review the generate_pa_proposals_with_oln function to understand how affinity maps are converted to ranked object proposals', 'refactor compute_rpn_score_oln to support batched proposal scoring across multiple images', 'build a region adjacency graph from an image and labels using mean color distance between regions', 'build a region adjacency graph from labels and an edge map using boundary pixel values', 'merge regions in a RAG hierarchically by greedily combining nodes with edge weights below a threshold', 'merge two nodes in a RAG and recompute edge weights using a custom weight function', 'visualize a region adjacency graph overlaid on an image with colored edges and region borders']
```

Usage

```
{'generate_proposals_from_pairwise_affinity': 'generate segmentation proposals and scores from a pairwise affinity tensor using potential2masks and ranking', 'compute_iou_between_masks': 'compute the IoU between two binary mask arrays or torch tensors with an optional threshold', 'rank_masks_by_color_variance': 'rank segmentation masks by color variance in an image with optional NMS filtering', 'evaluate_coco_protocol': 'evaluate detection results using the COCO evaluation protocol with optional category filtering', 'rank_proposals_by_potential': 'rank segmentation proposals by boundary potential scores with NMS and edge filtering'}
```

## File: facebookresearch_generic-grouping/pa_lib/oln_ranker.py

Prompts

```
['build a python module that converts predicted potentials to binary masks using connected component graph thresholding', 'build a python module that converts max potential maps to segmentation masks using watershed algorithm', 'build a python module that generates hierarchical segments from potentials using watershed and RAG merging', 'build a python module that converts 4-directional potential tensors into a skimage RAG graph with weighted edges', 'build a python module that computes globalized boundary maps from local boundary probabilities using eigenvector analysis', 'generate segmentation proposals and scores from a pairwise affinity tensor using potential2masks and ranking', 'compute the IoU between two binary mask arrays or torch tensors with an optional threshold', 'rank segmentation masks by color variance in an image with optional NMS filtering', 'evaluate detection results using the COCO evaluation protocol with optional category filtering', 'rank segmentation proposals by boundary potential scores with NMS and edge filtering', 'generate object proposals from predicted affinity maps using an OLN model with configurable edge and join thresholds', 'compute RPN centerness scores for proposals by matching anchors via IoU overlap with an OLN model', "compute ROI classification scores for proposals using the OLN model's RoI head simple test method", 'review the generate_pa_proposals_with_oln function to understand how affinity maps are converted to ranked object proposals', 'refactor compute_rpn_score_oln to support batched proposal scoring across multiple images', 'build a region adjacency graph from an image and labels using mean color distance between regions', 'build a region adjacency graph from labels and an edge map using boundary pixel values', 'merge regions in a RAG hierarchically by greedily combining nodes with edge weights below a threshold', 'merge two nodes in a RAG and recompute edge weights using a custom weight function', 'visualize a region adjacency graph overlaid on an image with colored edges and region borders']
```

Usage

```
{'generate_pa_proposals_with_oln': 'generate object proposals from predicted affinity maps using an OLN model with configurable edge and join thresholds', 'compute_rpn_score_oln': 'compute RPN centerness scores for proposals by matching anchors via IoU overlap with an OLN model', 'compute_roi_score_oln': "compute ROI classification scores for proposals using the OLN model's RoI head simple test method", 'review_generate_pa_proposals_with_oln': 'review the generate_pa_proposals_with_oln function to understand how affinity maps are converted to ranked object proposals', 'refactor_compute_rpn_score_oln': 'refactor compute_rpn_score_oln to support batched proposal scoring across multiple images'}
```

## File: facebookresearch_generic-grouping/pa_lib/rag.py

Prompts

```
['build a python module that converts predicted potentials to binary masks using connected component graph thresholding', 'build a python module that converts max potential maps to segmentation masks using watershed algorithm', 'build a python module that generates hierarchical segments from potentials using watershed and RAG merging', 'build a python module that converts 4-directional potential tensors into a skimage RAG graph with weighted edges', 'build a python module that computes globalized boundary maps from local boundary probabilities using eigenvector analysis', 'generate segmentation proposals and scores from a pairwise affinity tensor using potential2masks and ranking', 'compute the IoU between two binary mask arrays or torch tensors with an optional threshold', 'rank segmentation masks by color variance in an image with optional NMS filtering', 'evaluate detection results using the COCO evaluation protocol with optional category filtering', 'rank segmentation proposals by boundary potential scores with NMS and edge filtering', 'generate object proposals from predicted affinity maps using an OLN model with configurable edge and join thresholds', 'compute RPN centerness scores for proposals by matching anchors via IoU overlap with an OLN model', "compute ROI classification scores for proposals using the OLN model's RoI head simple test method", 'review the generate_pa_proposals_with_oln function to understand how affinity maps are converted to ranked object proposals', 'refactor compute_rpn_score_oln to support batched proposal scoring across multiple images', 'build a region adjacency graph from an image and labels using mean color distance between regions', 'build a region adjacency graph from labels and an edge map using boundary pixel values', 'merge regions in a RAG hierarchically by greedily combining nodes with edge weights below a threshold', 'merge two nodes in a RAG and recompute edge weights using a custom weight function', 'visualize a region adjacency graph overlaid on an image with colored edges and region borders']
```

Usage

```
{'build_rag_mean_color': 'build a region adjacency graph from an image and labels using mean color distance between regions', 'build_rag_boundary': 'build a region adjacency graph from labels and an edge map using boundary pixel values', 'merge_hierarchical_rag': 'merge regions in a RAG hierarchically by greedily combining nodes with edge weights below a threshold', 'merge_rag_nodes': 'merge two nodes in a RAG and recompute edge weights using a custom weight function', 'show_rag_on_image': 'visualize a region adjacency graph overlaid on an image with colored edges and region borders'}
```

