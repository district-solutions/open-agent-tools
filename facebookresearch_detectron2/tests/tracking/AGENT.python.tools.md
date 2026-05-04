# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/tests/tracking/test_bbox_iou_tracker.py

Prompts

```
['test the BBoxIOUTracker instantiation using detectron2 config and instantiate', 'test building a BBoxIOUTracker from a CfgNode config using build_tracker_head', 'test the BBoxIOUTracker _initialize_extra_fields method to add ID and tracking fields', 'test the BBoxIOUTracker _assign_new_id method to assign new tracking IDs to instances', 'test the BBoxIOUTracker update method to track instances across consecutive frames', 'test the BaseHungarianTracker initialization with video dimensions and tracking configuration parameters', 'test the helper method that converts a prediction dictionary to a detectron2 Instances object', 'run the unittest suite for the BaseHungarianTracker test class with setUp fixtures', 'review the TestBaseHungarianTracker class and its test methods for tracker initialization and extra fields', 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking thresholds', 'test building the IOUWeightedHungarianBBoxIOUTracker from a CfgNode configuration object', 'test processing matched instance indices to assign previous track IDs to current instances', 'test the tracker update method to assign track IDs across consecutive frames']
```

Usage

```
{'test_BBoxIOUTracker_init': 'test the BBoxIOUTracker instantiation using detectron2 config and instantiate', 'test_BBoxIOUTracker_from_config': 'test building a BBoxIOUTracker from a CfgNode config using build_tracker_head', 'test_initialize_extra_fields': 'test the BBoxIOUTracker _initialize_extra_fields method to add ID and tracking fields', 'test_assign_new_id': 'test the BBoxIOUTracker _assign_new_id method to assign new tracking IDs to instances', 'test_tracker_update': 'test the BBoxIOUTracker update method to track instances across consecutive frames'}
```

## File: facebookresearch_detectron2/tests/tracking/test_hungarian_tracker.py

Prompts

```
['test the BBoxIOUTracker instantiation using detectron2 config and instantiate', 'test building a BBoxIOUTracker from a CfgNode config using build_tracker_head', 'test the BBoxIOUTracker _initialize_extra_fields method to add ID and tracking fields', 'test the BBoxIOUTracker _assign_new_id method to assign new tracking IDs to instances', 'test the BBoxIOUTracker update method to track instances across consecutive frames', 'test the BaseHungarianTracker initialization with video dimensions and tracking configuration parameters', 'test the helper method that converts a prediction dictionary to a detectron2 Instances object', 'run the unittest suite for the BaseHungarianTracker test class with setUp fixtures', 'review the TestBaseHungarianTracker class and its test methods for tracker initialization and extra fields', 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking thresholds', 'test building the IOUWeightedHungarianBBoxIOUTracker from a CfgNode configuration object', 'test processing matched instance indices to assign previous track IDs to current instances', 'test the tracker update method to assign track IDs across consecutive frames']
```

Usage

```
{'test_BaseHungarianTracker_init': 'test the BaseHungarianTracker initialization with video dimensions and tracking configuration parameters', 'test_initialize_extra_fields': 'test the tracker _initialize_extra_fields method to verify ID and lost_frame_count fields are added', 'test_convertDictPredictionToInstance': 'test the helper method that converts a prediction dictionary to a detectron2 Instances object', 'run_test_hungarian_tracker': 'run the unittest suite for the BaseHungarianTracker test class with setUp fixtures', 'review_TestBaseHungarianTracker': 'review the TestBaseHungarianTracker class and its test methods for tracker initialization and extra fields'}
```

## File: facebookresearch_detectron2/tests/tracking/test_iou_weighted_hungarian_bbox_iou_tracker.py

Prompts

```
['test the BBoxIOUTracker instantiation using detectron2 config and instantiate', 'test building a BBoxIOUTracker from a CfgNode config using build_tracker_head', 'test the BBoxIOUTracker _initialize_extra_fields method to add ID and tracking fields', 'test the BBoxIOUTracker _assign_new_id method to assign new tracking IDs to instances', 'test the BBoxIOUTracker update method to track instances across consecutive frames', 'test the BaseHungarianTracker initialization with video dimensions and tracking configuration parameters', 'test the helper method that converts a prediction dictionary to a detectron2 Instances object', 'run the unittest suite for the BaseHungarianTracker test class with setUp fixtures', 'review the TestBaseHungarianTracker class and its test methods for tracker initialization and extra fields', 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking thresholds', 'test building the IOUWeightedHungarianBBoxIOUTracker from a CfgNode configuration object', 'test processing matched instance indices to assign previous track IDs to current instances', 'test the tracker update method to assign track IDs across consecutive frames']
```

Usage

```
{'test_tracker_init': 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking thresholds', 'test_tracker_from_config': 'test building the IOUWeightedHungarianBBoxIOUTracker from a CfgNode configuration object', 'test_initialize_extra_fields': 'test initializing extra fields like ID, ID_period, and lost_frame_count on instances', 'test_process_matched_idx': 'test processing matched instance indices to assign previous track IDs to current instances', 'test_update': 'test the tracker update method to assign track IDs across consecutive frames'}
```

## File: facebookresearch_detectron2/tests/tracking/test_vanilla_hungarian_bbox_iou_tracker.py

Prompts

```
['test the BBoxIOUTracker instantiation using detectron2 config and instantiate', 'test building a BBoxIOUTracker from a CfgNode config using build_tracker_head', 'test the BBoxIOUTracker _initialize_extra_fields method to add ID and tracking fields', 'test the BBoxIOUTracker _assign_new_id method to assign new tracking IDs to instances', 'test the BBoxIOUTracker update method to track instances across consecutive frames', 'test the BaseHungarianTracker initialization with video dimensions and tracking configuration parameters', 'test the helper method that converts a prediction dictionary to a detectron2 Instances object', 'run the unittest suite for the BaseHungarianTracker test class with setUp fixtures', 'review the TestBaseHungarianTracker class and its test methods for tracker initialization and extra fields', 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking thresholds', 'test building the IOUWeightedHungarianBBoxIOUTracker from a CfgNode configuration object', 'test processing matched instance indices to assign previous track IDs to current instances', 'test the tracker update method to assign track IDs across consecutive frames']
```

Usage

```
{'test_tracker_init': 'test the VanillaHungarianBBoxIOUTracker initialization using instantiate with a config dict', 'test_tracker_from_config': 'test building a VanillaHungarianBBoxIOUTracker from a CfgNode config using build_tracker_head', 'test_initialize_extra_fields': 'test the _initialize_extra_fields method to add ID, ID_period, and lost_frame_count fields', 'test_process_matched_idx': 'test the _process_matched_idx method to assign previous instance IDs to matched current instances', 'test_update': 'test the update method to track instances across frames and assign correct IDs'}
```

