# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/instance/core.py

Prompts

```
['create an InstanceView dataclass to store a single view of a detected instance with bbox, mask, and point cloud', 'create an Instance dataclass to aggregate multiple InstanceView objects for a single detected object in the environment', 'add an InstanceView to an Instance to aggregate point clouds, RGB data, and update bounds across views', 'get the combined image embedding across all instance views using max, mean, or concatenate aggregation', 'get the best InstanceView from an Instance by cropped image area metric', 'create an InstanceMemory object to track instances across environments with configurable association and NMS thresholds', 'process instance segmentation channels, point cloud, and image data to extract and associate instance views with global instances', 'associate unprocessed instance views to existing global instances or create new ones using bbox overlap and visual similarity', 'compute combined similarity between two instances using 3D bounding box overlap and visual embedding dot product', 'perform non-maximum suppression on global instances within an environment based on 3D bounding box IoU and confidence scores', 'compute one-sided IoU similarity matrix between two sets of 3D bounding box bounds', 'compute standard IoU similarity matrix between two sets of 3D bounding box bounds', 'calculate cosine similarity between two sets of feature vectors with L2 normalization', 'calculate raw dot product similarity between two feature vector sets without normalization', 'review the Bbox3dOverlapMethodEnum class that defines IOU and ONE_SIDED_IOU overlap modes']
```

Usage

```
{'create_instance_view': 'create an InstanceView dataclass to store a single view of a detected instance with bbox, mask, and point cloud', 'create_instance': 'create an Instance dataclass to aggregate multiple InstanceView objects for a single detected object in the environment', 'add_instance_view': 'add an InstanceView to an Instance to aggregate point clouds, RGB data, and update bounds across views', 'get_image_embedding': 'get the combined image embedding across all instance views using max, mean, or concatenate aggregation', 'get_best_view': 'get the best InstanceView from an Instance by cropped image area metric'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/instance/instance_map.py

Prompts

```
['create an InstanceView dataclass to store a single view of a detected instance with bbox, mask, and point cloud', 'create an Instance dataclass to aggregate multiple InstanceView objects for a single detected object in the environment', 'add an InstanceView to an Instance to aggregate point clouds, RGB data, and update bounds across views', 'get the combined image embedding across all instance views using max, mean, or concatenate aggregation', 'get the best InstanceView from an Instance by cropped image area metric', 'create an InstanceMemory object to track instances across environments with configurable association and NMS thresholds', 'process instance segmentation channels, point cloud, and image data to extract and associate instance views with global instances', 'associate unprocessed instance views to existing global instances or create new ones using bbox overlap and visual similarity', 'compute combined similarity between two instances using 3D bounding box overlap and visual embedding dot product', 'perform non-maximum suppression on global instances within an environment based on 3D bounding box IoU and confidence scores', 'compute one-sided IoU similarity matrix between two sets of 3D bounding box bounds', 'compute standard IoU similarity matrix between two sets of 3D bounding box bounds', 'calculate cosine similarity between two sets of feature vectors with L2 normalization', 'calculate raw dot product similarity between two feature vector sets without normalization', 'review the Bbox3dOverlapMethodEnum class that defines IOU and ONE_SIDED_IOU overlap modes']
```

Usage

```
{'create_InstanceMemory': 'create an InstanceMemory object to track instances across environments with configurable association and NMS thresholds', 'process_instances_InstanceMemory': 'process instance segmentation channels, point cloud, and image data to extract and associate instance views with global instances', 'associate_instances_to_memory_InstanceMemory': 'associate unprocessed instance views to existing global instances or create new ones using bbox overlap and visual similarity', 'get_similarity': 'compute combined similarity between two instances using 3D bounding box overlap and visual embedding dot product', 'global_instance_nms_InstanceMemory': 'perform non-maximum suppression on global instances within an environment based on 3D bounding box IoU and confidence scores'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/mapping/instance/matching.py

Prompts

```
['create an InstanceView dataclass to store a single view of a detected instance with bbox, mask, and point cloud', 'create an Instance dataclass to aggregate multiple InstanceView objects for a single detected object in the environment', 'add an InstanceView to an Instance to aggregate point clouds, RGB data, and update bounds across views', 'get the combined image embedding across all instance views using max, mean, or concatenate aggregation', 'get the best InstanceView from an Instance by cropped image area metric', 'create an InstanceMemory object to track instances across environments with configurable association and NMS thresholds', 'process instance segmentation channels, point cloud, and image data to extract and associate instance views with global instances', 'associate unprocessed instance views to existing global instances or create new ones using bbox overlap and visual similarity', 'compute combined similarity between two instances using 3D bounding box overlap and visual embedding dot product', 'perform non-maximum suppression on global instances within an environment based on 3D bounding box IoU and confidence scores', 'compute one-sided IoU similarity matrix between two sets of 3D bounding box bounds', 'compute standard IoU similarity matrix between two sets of 3D bounding box bounds', 'calculate cosine similarity between two sets of feature vectors with L2 normalization', 'calculate raw dot product similarity between two feature vector sets without normalization', 'review the Bbox3dOverlapMethodEnum class that defines IOU and ONE_SIDED_IOU overlap modes']
```

Usage

```
{'get_bbox_similarity_one_sided_iou': 'compute one-sided IoU similarity matrix between two sets of 3D bounding box bounds', 'get_bbox_similarity_iou': 'compute standard IoU similarity matrix between two sets of 3D bounding box bounds', 'dot_product_similarity_cosine': 'calculate cosine similarity between two sets of feature vectors with L2 normalization', 'dot_product_similarity_raw': 'calculate raw dot product similarity between two feature vector sets without normalization', 'review_Bbox3dOverlapMethodEnum': 'review the Bbox3dOverlapMethodEnum class that defines IOU and ONE_SIDED_IOU overlap modes'}
```

