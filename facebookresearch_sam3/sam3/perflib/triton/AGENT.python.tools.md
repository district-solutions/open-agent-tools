# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/perflib/triton/connected_components.py

Prompts

```
['run connected components labeling on a batch of 2D integer tensors using Triton GPU kernels', 'test the find function that traverses parent pointers to locate the root of a disjoint-set element', 'test the union function that merges two disjoint sets using atomic min with retry logic', 'test the local propagation kernel that merges 8-connected neighbor pixels with the same value', 'test the pointer jumping kernel that converges all labels to their root using double buffering', 'run non-maximum suppression on bounding boxes using a Triton GPU kernel with pairwise IoU matrix and scores', 'create a Triton JIT kernel that sequentially suppresses overlapping bounding boxes based on IoU threshold', 'build an NMS suppression pipeline that sorts boxes by score and blocks high-IoU overlapping detections', 'test the nms_triton function with pairwise IoU tensor, scores tensor, and IoU threshold to verify kept box indices', 'review the _nms_suppression_kernel Triton kernel for sequential suppression and debug barrier usage']
```

Usage

```
{'run_connected_components_triton': 'run connected components labeling on a batch of 2D integer tensors using Triton GPU kernels', 'test_find_disjoint_set': 'test the find function that traverses parent pointers to locate the root of a disjoint-set element', 'test_union_disjoint_set': 'test the union function that merges two disjoint sets using atomic min with retry logic', 'test_local_prop_kernel': 'test the local propagation kernel that merges 8-connected neighbor pixels with the same value', 'test_pointer_jump_kernel': 'test the pointer jumping kernel that converges all labels to their root using double buffering'}
```

## File: facebookresearch_sam3/sam3/perflib/triton/nms.py

Prompts

```
['run connected components labeling on a batch of 2D integer tensors using Triton GPU kernels', 'test the find function that traverses parent pointers to locate the root of a disjoint-set element', 'test the union function that merges two disjoint sets using atomic min with retry logic', 'test the local propagation kernel that merges 8-connected neighbor pixels with the same value', 'test the pointer jumping kernel that converges all labels to their root using double buffering', 'run non-maximum suppression on bounding boxes using a Triton GPU kernel with pairwise IoU matrix and scores', 'create a Triton JIT kernel that sequentially suppresses overlapping bounding boxes based on IoU threshold', 'build an NMS suppression pipeline that sorts boxes by score and blocks high-IoU overlapping detections', 'test the nms_triton function with pairwise IoU tensor, scores tensor, and IoU threshold to verify kept box indices', 'review the _nms_suppression_kernel Triton kernel for sequential suppression and debug barrier usage']
```

Usage

```
{'run_nms_triton': 'run non-maximum suppression on bounding boxes using a Triton GPU kernel with pairwise IoU matrix and scores', 'create_nms_suppression_kernel': 'create a Triton JIT kernel that sequentially suppresses overlapping bounding boxes based on IoU threshold', 'build_nms_suppression': 'build an NMS suppression pipeline that sorts boxes by score and blocks high-IoU overlapping detections', 'test_nms_triton': 'test the nms_triton function with pairwise IoU tensor, scores tensor, and IoU threshold to verify kept box indices', 'review_nms_suppression_kernel': 'review the _nms_suppression_kernel Triton kernel for sequential suppression and debug barrier usage'}
```

