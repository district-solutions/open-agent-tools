# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/tests/tracking/test_bbox_iou_tracker.py

Prompts

```
['test the BBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test building a BBoxIOUTracker from a Detectron2 CfgNode configuration object', 'test the BBoxIOUTracker method that adds ID, ID_period, and lost_frame_count fields', 'test the BBoxIOUTracker method that assigns new unique tracking IDs to instances', 'test the BBoxIOUTracker update method that tracks instances across consecutive video frames', 'test the BaseHungarianTracker instantiation with video dimensions and tracking configuration parameters', 'test the BaseHungarianTracker _initialize_extra_fields method to verify ID and tracking fields are added', 'test converting a prediction dictionary to Detectron2 Instances format with boxes masks and scores', 'run the unittest suite for BaseHungarianTracker to validate tracker initialization and extra field setup', 'review the TestBaseHungarianTracker class and its test methods for tracker configuration and instance field validation', 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test building the IOUWeightedHungarianBBoxIOUTracker tracker head from a Detectron2 CfgNode configuration object', 'test processing matched bounding box indices to assign previous track IDs to current detections', 'test the tracker update method to assign track IDs across consecutive video frame detections']
```

Usage

```
{'test_BBoxIOUTracker_init': 'test the BBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test_BBoxIOUTracker_from_config': 'test building a BBoxIOUTracker from a Detectron2 CfgNode configuration object', 'test_initialize_extra_fields': 'test the BBoxIOUTracker method that adds ID, ID_period, and lost_frame_count fields', 'test_assign_new_id': 'test the BBoxIOUTracker method that assigns new unique tracking IDs to instances', 'test_tracker_update': 'test the BBoxIOUTracker update method that tracks instances across consecutive video frames'}
```

## File: facebookresearch_banmo/third_party/detectron2/tests/tracking/test_hungarian_tracker.py

Prompts

```
['test the BBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test building a BBoxIOUTracker from a Detectron2 CfgNode configuration object', 'test the BBoxIOUTracker method that adds ID, ID_period, and lost_frame_count fields', 'test the BBoxIOUTracker method that assigns new unique tracking IDs to instances', 'test the BBoxIOUTracker update method that tracks instances across consecutive video frames', 'test the BaseHungarianTracker instantiation with video dimensions and tracking configuration parameters', 'test the BaseHungarianTracker _initialize_extra_fields method to verify ID and tracking fields are added', 'test converting a prediction dictionary to Detectron2 Instances format with boxes masks and scores', 'run the unittest suite for BaseHungarianTracker to validate tracker initialization and extra field setup', 'review the TestBaseHungarianTracker class and its test methods for tracker configuration and instance field validation', 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test building the IOUWeightedHungarianBBoxIOUTracker tracker head from a Detectron2 CfgNode configuration object', 'test processing matched bounding box indices to assign previous track IDs to current detections', 'test the tracker update method to assign track IDs across consecutive video frame detections']
```

Usage

```
{'test_BaseHungarianTracker_init': 'test the BaseHungarianTracker instantiation with video dimensions and tracking configuration parameters', 'test_BaseHungarianTracker_initialize_extra_fields': 'test the BaseHungarianTracker _initialize_extra_fields method to verify ID and tracking fields are added', 'test_convertDictPredictionToInstance': 'test converting a prediction dictionary to Detectron2 Instances format with boxes masks and scores', 'run_hungarian_tracker_tests': 'run the unittest suite for BaseHungarianTracker to validate tracker initialization and extra field setup', 'review_TestBaseHungarianTracker': 'review the TestBaseHungarianTracker class and its test methods for tracker configuration and instance field validation'}
```

## File: facebookresearch_banmo/third_party/detectron2/tests/tracking/test_iou_weighted_hungarian_bbox_iou_tracker.py

Prompts

```
['test the BBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test building a BBoxIOUTracker from a Detectron2 CfgNode configuration object', 'test the BBoxIOUTracker method that adds ID, ID_period, and lost_frame_count fields', 'test the BBoxIOUTracker method that assigns new unique tracking IDs to instances', 'test the BBoxIOUTracker update method that tracks instances across consecutive video frames', 'test the BaseHungarianTracker instantiation with video dimensions and tracking configuration parameters', 'test the BaseHungarianTracker _initialize_extra_fields method to verify ID and tracking fields are added', 'test converting a prediction dictionary to Detectron2 Instances format with boxes masks and scores', 'run the unittest suite for BaseHungarianTracker to validate tracker initialization and extra field setup', 'review the TestBaseHungarianTracker class and its test methods for tracker configuration and instance field validation', 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test building the IOUWeightedHungarianBBoxIOUTracker tracker head from a Detectron2 CfgNode configuration object', 'test processing matched bounding box indices to assign previous track IDs to current detections', 'test the tracker update method to assign track IDs across consecutive video frame detections']
```

Usage

```
{'test_tracker_init': 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test_tracker_from_config': 'test building the IOUWeightedHungarianBBoxIOUTracker tracker head from a Detectron2 CfgNode configuration object', 'test_initialize_extra_fields': 'test initializing extra tracking fields like ID, ID_period, and lost_frame_count on detection instances', 'test_process_matched_idx': 'test processing matched bounding box indices to assign previous track IDs to current detections', 'test_update': 'test the tracker update method to assign track IDs across consecutive video frame detections'}
```

## File: facebookresearch_banmo/third_party/detectron2/tests/tracking/test_vanilla_hungarian_bbox_iou_tracker.py

Prompts

```
['test the BBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test building a BBoxIOUTracker from a Detectron2 CfgNode configuration object', 'test the BBoxIOUTracker method that adds ID, ID_period, and lost_frame_count fields', 'test the BBoxIOUTracker method that assigns new unique tracking IDs to instances', 'test the BBoxIOUTracker update method that tracks instances across consecutive video frames', 'test the BaseHungarianTracker instantiation with video dimensions and tracking configuration parameters', 'test the BaseHungarianTracker _initialize_extra_fields method to verify ID and tracking fields are added', 'test converting a prediction dictionary to Detectron2 Instances format with boxes masks and scores', 'run the unittest suite for BaseHungarianTracker to validate tracker initialization and extra field setup', 'review the TestBaseHungarianTracker class and its test methods for tracker configuration and instance field validation', 'test the IOUWeightedHungarianBBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test building the IOUWeightedHungarianBBoxIOUTracker tracker head from a Detectron2 CfgNode configuration object', 'test processing matched bounding box indices to assign previous track IDs to current detections', 'test the tracker update method to assign track IDs across consecutive video frame detections']
```

Usage

```
{'test_tracker_init': 'test the VanillaHungarianBBoxIOUTracker initialization with video dimensions and tracking configuration parameters', 'test_tracker_from_config': 'test building a VanillaHungarianBBoxIOUTracker from a CfgNode configuration using build_tracker_head', 'test_initialize_extra_fields': 'test initializing extra tracking fields like ID, ID_period, and lost_frame_count on instances', 'test_process_matched_idx': 'test processing matched bounding box indices to assign previous track IDs to current instances', 'test_update': 'test the tracker update method to assign track IDs across consecutive frames using Hungarian matching'}
```

