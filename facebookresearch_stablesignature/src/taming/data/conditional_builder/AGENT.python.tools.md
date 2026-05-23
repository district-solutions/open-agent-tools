# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/taming/data/conditional_builder/objects_bbox.py

Prompts

```
['build an ObjectsBoundingBoxConditionalBuilder to encode object annotations with bounding boxes into a LongTensor', 'inverse build a LongTensor conditional into a list of object bounding box tuples and crop coordinates', 'plot bounding box conditionals as a PIL image with colored rectangles and class labels', 'create object descriptor triples from annotations containing category and bounding box token pairs', "tokenize bounding box coordinates into discrete token pairs using the builder's coordinate grid", 'build a LongTensor from object annotations with optional crop coordinates and horizontal flip using ObjectsCenterPointsConditionalBuilder', 'tokenize normalized 2D coordinates into a single discrete token value using the grid-based encoding scheme', 'decode a conditional LongTensor back into object representations with coordinates and optional crop bounding box', 'plot a conditional tensor as a PIL image with colored circles and labels for each object representation', 'encode an Annotation object into an integer representation using category number and optional group and additional parameters', 'compute the intersection area between two bounding box rectangles given their coordinates', 'horizontally flip a bounding box by recalculating its x coordinate relative to image width', 'convert a relative bounding box to absolute pixel coordinates using image width and height', 'rescale a list of annotations to match new crop coordinates with optional horizontal flip', 'filter annotations to keep only those that intersect with the given crop coordinates']
```

Usage

```
{'build_objects_bbox_conditional': 'build an ObjectsBoundingBoxConditionalBuilder to encode object annotations with bounding boxes into a LongTensor', 'inverse_build_bbox_descriptors': 'inverse build a LongTensor conditional into a list of object bounding box tuples and crop coordinates', 'plot_bbox_conditionals': 'plot bounding box conditionals as a PIL image with colored rectangles and class labels', 'make_object_descriptors': 'create object descriptor triples from annotations containing category and bounding box token pairs', 'tokenize_bbox_coordinates': "tokenize bounding box coordinates into discrete token pairs using the builder's coordinate grid"}
```

## File: facebookresearch_stablesignature/src/taming/data/conditional_builder/objects_center_points.py

Prompts

```
['build an ObjectsBoundingBoxConditionalBuilder to encode object annotations with bounding boxes into a LongTensor', 'inverse build a LongTensor conditional into a list of object bounding box tuples and crop coordinates', 'plot bounding box conditionals as a PIL image with colored rectangles and class labels', 'create object descriptor triples from annotations containing category and bounding box token pairs', "tokenize bounding box coordinates into discrete token pairs using the builder's coordinate grid", 'build a LongTensor from object annotations with optional crop coordinates and horizontal flip using ObjectsCenterPointsConditionalBuilder', 'tokenize normalized 2D coordinates into a single discrete token value using the grid-based encoding scheme', 'decode a conditional LongTensor back into object representations with coordinates and optional crop bounding box', 'plot a conditional tensor as a PIL image with colored circles and labels for each object representation', 'encode an Annotation object into an integer representation using category number and optional group and additional parameters', 'compute the intersection area between two bounding box rectangles given their coordinates', 'horizontally flip a bounding box by recalculating its x coordinate relative to image width', 'convert a relative bounding box to absolute pixel coordinates using image width and height', 'rescale a list of annotations to match new crop coordinates with optional horizontal flip', 'filter annotations to keep only those that intersect with the given crop coordinates']
```

Usage

```
{'build_conditional_tensor': 'build a LongTensor from object annotations with optional crop coordinates and horizontal flip using ObjectsCenterPointsConditionalBuilder', 'tokenize_coordinates': 'tokenize normalized 2D coordinates into a single discrete token value using the grid-based encoding scheme', 'inverse_build_conditional': 'decode a conditional LongTensor back into object representations with coordinates and optional crop bounding box', 'plot_conditional': 'plot a conditional tensor as a PIL image with colored circles and labels for each object representation', 'object_representation': 'encode an Annotation object into an integer representation using category number and optional group and additional parameters'}
```

## File: facebookresearch_stablesignature/src/taming/data/conditional_builder/utils.py

Prompts

```
['build an ObjectsBoundingBoxConditionalBuilder to encode object annotations with bounding boxes into a LongTensor', 'inverse build a LongTensor conditional into a list of object bounding box tuples and crop coordinates', 'plot bounding box conditionals as a PIL image with colored rectangles and class labels', 'create object descriptor triples from annotations containing category and bounding box token pairs', "tokenize bounding box coordinates into discrete token pairs using the builder's coordinate grid", 'build a LongTensor from object annotations with optional crop coordinates and horizontal flip using ObjectsCenterPointsConditionalBuilder', 'tokenize normalized 2D coordinates into a single discrete token value using the grid-based encoding scheme', 'decode a conditional LongTensor back into object representations with coordinates and optional crop bounding box', 'plot a conditional tensor as a PIL image with colored circles and labels for each object representation', 'encode an Annotation object into an integer representation using category number and optional group and additional parameters', 'compute the intersection area between two bounding box rectangles given their coordinates', 'horizontally flip a bounding box by recalculating its x coordinate relative to image width', 'convert a relative bounding box to absolute pixel coordinates using image width and height', 'rescale a list of annotations to match new crop coordinates with optional horizontal flip', 'filter annotations to keep only those that intersect with the given crop coordinates']
```

Usage

```
{'compute_intersection_area': 'compute the intersection area between two bounding box rectangles given their coordinates', 'flip_bbox_horizontally': 'horizontally flip a bounding box by recalculating its x coordinate relative to image width', 'convert_relative_bbox_to_absolute': 'convert a relative bounding box to absolute pixel coordinates using image width and height', 'rescale_annotations_for_crop': 'rescale a list of annotations to match new crop coordinates with optional horizontal flip', 'filter_annotations_by_crop': 'filter annotations to keep only those that intersect with the given crop coordinates'}
```

