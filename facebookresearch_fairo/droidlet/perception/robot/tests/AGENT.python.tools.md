# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/robot/tests/test_perception.py

Prompts

```
['run the LabelPropagate test to verify label propagation accuracy exceeds 90 percent on noisy and clean data', 'run the ObjectDetection handler test to verify at least 5 objects are detected from an office image', 'run the FaceRecognition test to verify multiple faces are detected in a group photo and none in an office photo', 'run the SampleGoodCandidates test to verify good and bad candidate frame selection for class and instance settings', 'run the MemoryStoring test to verify detected objects and human poses are inserted into LocoAgentMemory and deduplicated', 'create a fake RGBDepth object with random RGB, depth, and point data for testing', 'create a fake Detection object with random mask, bbox, and rgbd for a given class label', 'create a fake Human pose object with random keypoints and rgbd data for testing', 'create a fake bounding box as a list of x1, y1, x2, y2 coordinates for testing', 'create fake human keypoints using HumanKeypointsOrdering with random pixel locations and visibility flags']
```

Usage

```
{'run_label_propagation_test': 'run the LabelPropagate test to verify label propagation accuracy exceeds 90 percent on noisy and clean data', 'run_object_detection_test': 'run the ObjectDetection handler test to verify at least 5 objects are detected from an office image', 'run_face_recognition_test': 'run the FaceRecognition test to verify multiple faces are detected in a group photo and none in an office photo', 'run_candidate_selection_test': 'run the SampleGoodCandidates test to verify good and bad candidate frame selection for class and instance settings', 'run_memory_storing_test': 'run the MemoryStoring test to verify detected objects and human poses are inserted into LocoAgentMemory and deduplicated'}
```

## File: facebookresearch_fairo/droidlet/perception/robot/tests/utils.py

Prompts

```
['run the LabelPropagate test to verify label propagation accuracy exceeds 90 percent on noisy and clean data', 'run the ObjectDetection handler test to verify at least 5 objects are detected from an office image', 'run the FaceRecognition test to verify multiple faces are detected in a group photo and none in an office photo', 'run the SampleGoodCandidates test to verify good and bad candidate frame selection for class and instance settings', 'run the MemoryStoring test to verify detected objects and human poses are inserted into LocoAgentMemory and deduplicated', 'create a fake RGBDepth object with random RGB, depth, and point data for testing', 'create a fake Detection object with random mask, bbox, and rgbd for a given class label', 'create a fake Human pose object with random keypoints and rgbd data for testing', 'create a fake bounding box as a list of x1, y1, x2, y2 coordinates for testing', 'create fake human keypoints using HumanKeypointsOrdering with random pixel locations and visibility flags']
```

Usage

```
{'create_fake_rgbd': 'create a fake RGBDepth object with random RGB, depth, and point data for testing', 'create_fake_detection': 'create a fake Detection object with random mask, bbox, and rgbd for a given class label', 'create_fake_humanpose': 'create a fake Human pose object with random keypoints and rgbd data for testing', 'create_fake_bbox': 'create a fake bounding box as a list of x1, y1, x2, y2 coordinates for testing', 'create_fake_human_keypoints': 'create fake human keypoints using HumanKeypointsOrdering with random pixel locations and visibility flags'}
```

