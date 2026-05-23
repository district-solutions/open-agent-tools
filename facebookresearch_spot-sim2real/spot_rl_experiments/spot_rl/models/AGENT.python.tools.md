# Agent Python Tools

- repo: facebookresearch/spot-sim2real
- repo_uri: https://github.com/facebookresearch/spot-sim2real

## File: facebookresearch_spot-sim2real/spot_rl_experiments/spot_rl/models/owlvit.py

Prompts

```
['run OWL-ViT zero-shot object detection on an image with custom labels and score threshold', 'run OWL-ViT inference and return detected bounding boxes along with an annotated visualization image', 'create an image with bounding boxes overlaid for each detected object without confidence ranking', 'update the detection labels at runtime to detect new object classes without reinitializing the model', 'process raw OWL-ViT detection results and return all bounding boxes above the score threshold per label', 'build a python module that loads all-MiniLM-L6-v2 for sentence embedding and similarity computation', 'create a function that performs attention-masked mean pooling on token embeddings', 'test the SentenceSimilarity method that computes cosine similarity between two input sentences', 'refactor the SentenceSimilarity method to find the most semantically similar word in a list', 'review the SentenceSimilarity class and its cosine similarity scoring methods', 'run the YOLOV8Predictor on a numpy image to get object detections and an optional visualization', 'build a YOLOV8Predictor instance from a TorchScript exported YOLOv8 model with a fixed image size', 'test the non_max_suppression function on raw YOLO model predictions with configurable confidence and IoU thresholds', 'refactor the xywh2xyxy function to convert bounding box coordinates from center format to corner format', 'review the _generate_plot method that draws bounding boxes with class labels and scores on the original image']
```

Usage

```
{'run_OwlVit_inference': 'run OWL-ViT zero-shot object detection on an image with custom labels and score threshold', 'run_OwlVit_inference_and_return_img': 'run OWL-ViT inference and return detected bounding boxes along with an annotated visualization image', 'create_img_with_bounding_box_no_ranking': 'create an image with bounding boxes overlaid for each detected object without confidence ranking', 'update_OwlVit_labels': 'update the detection labels at runtime to detect new object classes without reinitializing the model', 'process_OwlVit_results': 'process raw OWL-ViT detection results and return all bounding boxes above the score threshold per label'}
```

## File: facebookresearch_spot-sim2real/spot_rl_experiments/spot_rl/models/sentence_similarity.py

Prompts

```
['run OWL-ViT zero-shot object detection on an image with custom labels and score threshold', 'run OWL-ViT inference and return detected bounding boxes along with an annotated visualization image', 'create an image with bounding boxes overlaid for each detected object without confidence ranking', 'update the detection labels at runtime to detect new object classes without reinitializing the model', 'process raw OWL-ViT detection results and return all bounding boxes above the score threshold per label', 'build a python module that loads all-MiniLM-L6-v2 for sentence embedding and similarity computation', 'create a function that performs attention-masked mean pooling on token embeddings', 'test the SentenceSimilarity method that computes cosine similarity between two input sentences', 'refactor the SentenceSimilarity method to find the most semantically similar word in a list', 'review the SentenceSimilarity class and its cosine similarity scoring methods', 'run the YOLOV8Predictor on a numpy image to get object detections and an optional visualization', 'build a YOLOV8Predictor instance from a TorchScript exported YOLOv8 model with a fixed image size', 'test the non_max_suppression function on raw YOLO model predictions with configurable confidence and IoU thresholds', 'refactor the xywh2xyxy function to convert bounding box coordinates from center format to corner format', 'review the _generate_plot method that draws bounding boxes with class labels and scores on the original image']
```

Usage

```
{'build_sentence_similarity_class': 'build a python module that loads all-MiniLM-L6-v2 for sentence embedding and similarity computation', 'create_mean_pooling': 'create a function that performs attention-masked mean pooling on token embeddings', 'test_get_similarity_two_sentences': 'test the SentenceSimilarity method that computes cosine similarity between two input sentences', 'refactor_get_most_similar_in_list': 'refactor the SentenceSimilarity method to find the most semantically similar word in a list', 'review_SentenceSimilarity': 'review the SentenceSimilarity class and its cosine similarity scoring methods'}
```

## File: facebookresearch_spot-sim2real/spot_rl_experiments/spot_rl/models/yolov8predictor.py

Prompts

```
['run OWL-ViT zero-shot object detection on an image with custom labels and score threshold', 'run OWL-ViT inference and return detected bounding boxes along with an annotated visualization image', 'create an image with bounding boxes overlaid for each detected object without confidence ranking', 'update the detection labels at runtime to detect new object classes without reinitializing the model', 'process raw OWL-ViT detection results and return all bounding boxes above the score threshold per label', 'build a python module that loads all-MiniLM-L6-v2 for sentence embedding and similarity computation', 'create a function that performs attention-masked mean pooling on token embeddings', 'test the SentenceSimilarity method that computes cosine similarity between two input sentences', 'refactor the SentenceSimilarity method to find the most semantically similar word in a list', 'review the SentenceSimilarity class and its cosine similarity scoring methods', 'run the YOLOV8Predictor on a numpy image to get object detections and an optional visualization', 'build a YOLOV8Predictor instance from a TorchScript exported YOLOv8 model with a fixed image size', 'test the non_max_suppression function on raw YOLO model predictions with configurable confidence and IoU thresholds', 'refactor the xywh2xyxy function to convert bounding box coordinates from center format to corner format', 'review the _generate_plot method that draws bounding boxes with class labels and scores on the original image']
```

Usage

```
{'run_yolov8predictor_on_image': 'run the YOLOV8Predictor on a numpy image to get object detections and an optional visualization', 'build_yolov8predictor_from_torchscript': 'build a YOLOV8Predictor instance from a TorchScript exported YOLOv8 model with a fixed image size', 'test_non_max_suppression': 'test the non_max_suppression function on raw YOLO model predictions with configurable confidence and IoU thresholds', 'refactor_xywh2xyxy': 'refactor the xywh2xyxy function to convert bounding box coordinates from center format to corner format', 'review_generate_plot': 'review the _generate_plot method that draws bounding boxes with class labels and scores on the original image'}
```

