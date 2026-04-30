# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/models/stages/layout/layout_model.py

Prompts

```
['create a LayoutModel instance to run document layout prediction on pages with accelerator options', 'run layout prediction on a sequence of document pages and return layout predictions with clusters', 'download layout model artifacts from Hugging Face Hub to a local directory', 'get the LayoutOptions type class used to configure the layout model', 'draw clusters and cells side by side for debugging layout prediction results', 'create a LayoutObjectDetectionModel instance with artifacts path, accelerator options, and layout detection options', 'build a label map mapping engine label IDs to DocItemLabel enum values from the object detection engine', 'convert object detection engine output predictions to a list of Cluster objects with scaled bounding boxes', 'get the LayoutObjectDetectionOptions class type used by the LayoutObjectDetectionModel']
```

Usage

```
{'create_layout_model': 'create a LayoutModel instance to run document layout prediction on pages with accelerator options', 'run_predict_layout': 'run layout prediction on a sequence of document pages and return layout predictions with clusters', 'download_layout_models': 'download layout model artifacts from Hugging Face Hub to a local directory', 'get_layout_options_type': 'get the LayoutOptions type class used to configure the layout model', 'draw_layout_clusters': 'draw clusters and cells side by side for debugging layout prediction results'}
```

## File: docling-project_docling/docling/models/stages/layout/layout_object_detection_model.py

Prompts

```
['create a LayoutModel instance to run document layout prediction on pages with accelerator options', 'run layout prediction on a sequence of document pages and return layout predictions with clusters', 'download layout model artifacts from Hugging Face Hub to a local directory', 'get the LayoutOptions type class used to configure the layout model', 'draw clusters and cells side by side for debugging layout prediction results', 'create a LayoutObjectDetectionModel instance with artifacts path, accelerator options, and layout detection options', 'build a label map mapping engine label IDs to DocItemLabel enum values from the object detection engine', 'convert object detection engine output predictions to a list of Cluster objects with scaled bounding boxes', 'get the LayoutObjectDetectionOptions class type used by the LayoutObjectDetectionModel']
```

Usage

```
{'create_layout_object_detection_model': 'create a LayoutObjectDetectionModel instance with artifacts path, accelerator options, and layout detection options', 'run_predict_layout': 'run predict_layout on a ConversionResult and sequence of Page objects to produce LayoutPrediction results', 'build_label_map': 'build a label map mapping engine label IDs to DocItemLabel enum values from the object detection engine', 'convert_predictions_to_clusters': 'convert object detection engine output predictions to a list of Cluster objects with scaled bounding boxes', 'get_options_type': 'get the LayoutObjectDetectionOptions class type used by the LayoutObjectDetectionModel'}
```

