# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/semantic_exploration/models/owlvit.py

Prompts

```
['run object detection inference on an OpenCV image using the OwlVit model with custom labels', 'run object detection and return both bounding box results and an image with overlaid bounding boxes', 'get all bounding boxes above a confidence threshold from OwlVit detection results', 'get the most confident bounding box for each label from detection results', 'create an image with bounding boxes and labels overlaid on detected objects', 'build a Semantic_Mapping module that constructs a 3D semantic map from depth observations and agent poses', 'review the ChannelPool class forward method that performs max pooling across channels of a 4D tensor', 'test the Semantic_Mapping forward pass that splats depth features into voxels and produces map predictions', 'refactor the get_grid static method to generate rotation and translation affine grids for pose-based map sampling', 'summarize the Semantic_Mapping constructor that initializes grid buffers, camera matrix, and threshold parameters from config', 'build a SentenceSimilarity class that loads all-MiniLM-L6-v2 from HuggingFace for semantic sentence embeddings', 'create a mean pooling method that averages token embeddings using the attention mask for correct weighting', 'test the get_similarity_two_sentences method to compute cosine similarity between two input sentences', 'run get_most_similar_in_list to find the most semantically similar word from a list given a query', 'review the SentenceSimilarity class and how it normalizes embeddings with L2 norm before computing cosine scores']
```

Usage

```
{'run_object_detection_inference': 'run object detection inference on an OpenCV image using the OwlVit model with custom labels', 'run_inference_and_return_img': 'run object detection and return both bounding box results and an image with overlaid bounding boxes', 'get_bounding_boxes': 'get all bounding boxes above a confidence threshold from OwlVit detection results', 'get_most_confident_bounding_box_per_label': 'get the most confident bounding box for each label from detection results', 'create_img_with_bounding_box': 'create an image with bounding boxes and labels overlaid on detected objects'}
```

## File: facebookresearch_partnr-planner/third_party/semantic_exploration/models/semantic_map.py

Prompts

```
['run object detection inference on an OpenCV image using the OwlVit model with custom labels', 'run object detection and return both bounding box results and an image with overlaid bounding boxes', 'get all bounding boxes above a confidence threshold from OwlVit detection results', 'get the most confident bounding box for each label from detection results', 'create an image with bounding boxes and labels overlaid on detected objects', 'build a Semantic_Mapping module that constructs a 3D semantic map from depth observations and agent poses', 'review the ChannelPool class forward method that performs max pooling across channels of a 4D tensor', 'test the Semantic_Mapping forward pass that splats depth features into voxels and produces map predictions', 'refactor the get_grid static method to generate rotation and translation affine grids for pose-based map sampling', 'summarize the Semantic_Mapping constructor that initializes grid buffers, camera matrix, and threshold parameters from config', 'build a SentenceSimilarity class that loads all-MiniLM-L6-v2 from HuggingFace for semantic sentence embeddings', 'create a mean pooling method that averages token embeddings using the attention mask for correct weighting', 'test the get_similarity_two_sentences method to compute cosine similarity between two input sentences', 'run get_most_similar_in_list to find the most semantically similar word from a list given a query', 'review the SentenceSimilarity class and how it normalizes embeddings with L2 norm before computing cosine scores']
```

Usage

```
{'build_Semantic_Mapping': 'build a Semantic_Mapping module that constructs a 3D semantic map from depth observations and agent poses', 'review_ChannelPool_forward': 'review the ChannelPool class forward method that performs max pooling across channels of a 4D tensor', 'test_Semantic_Mapping_forward': 'test the Semantic_Mapping forward pass that splats depth features into voxels and produces map predictions', 'refactor_Semantic_Mapping_get_grid': 'refactor the get_grid static method to generate rotation and translation affine grids for pose-based map sampling', 'summarize_Semantic_Mapping_init': 'summarize the Semantic_Mapping constructor that initializes grid buffers, camera matrix, and threshold parameters from config'}
```

## File: facebookresearch_partnr-planner/third_party/semantic_exploration/models/sentence_similarity.py

Prompts

```
['run object detection inference on an OpenCV image using the OwlVit model with custom labels', 'run object detection and return both bounding box results and an image with overlaid bounding boxes', 'get all bounding boxes above a confidence threshold from OwlVit detection results', 'get the most confident bounding box for each label from detection results', 'create an image with bounding boxes and labels overlaid on detected objects', 'build a Semantic_Mapping module that constructs a 3D semantic map from depth observations and agent poses', 'review the ChannelPool class forward method that performs max pooling across channels of a 4D tensor', 'test the Semantic_Mapping forward pass that splats depth features into voxels and produces map predictions', 'refactor the get_grid static method to generate rotation and translation affine grids for pose-based map sampling', 'summarize the Semantic_Mapping constructor that initializes grid buffers, camera matrix, and threshold parameters from config', 'build a SentenceSimilarity class that loads all-MiniLM-L6-v2 from HuggingFace for semantic sentence embeddings', 'create a mean pooling method that averages token embeddings using the attention mask for correct weighting', 'test the get_similarity_two_sentences method to compute cosine similarity between two input sentences', 'run get_most_similar_in_list to find the most semantically similar word from a list given a query', 'review the SentenceSimilarity class and how it normalizes embeddings with L2 norm before computing cosine scores']
```

Usage

```
{'build_sentence_similarity_class': 'build a SentenceSimilarity class that loads all-MiniLM-L6-v2 from HuggingFace for semantic sentence embeddings', 'create_mean_pooling_method': 'create a mean pooling method that averages token embeddings using the attention mask for correct weighting', 'test_get_similarity_two_sentences': 'test the get_similarity_two_sentences method to compute cosine similarity between two input sentences', 'run_get_most_similar_in_list': 'run get_most_similar_in_list to find the most semantically similar word from a list given a query', 'review_SentenceSimilarity_normalization': 'review the SentenceSimilarity class and how it normalizes embeddings with L2 norm before computing cosine scores'}
```

