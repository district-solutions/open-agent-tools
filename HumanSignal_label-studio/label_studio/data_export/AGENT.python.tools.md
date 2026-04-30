# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/data_export/api.py

Prompts

```
['create a new export snapshot for a Label Studio project with task and annotation filters', 'list all export snapshots for a specific Label Studio project ordered by creation date', 'download an export snapshot file in a specified format for a Label Studio project', 'convert an existing export snapshot to a different format like CSV or TSV asynchronously', 'delete an export snapshot and its associated file from storage for a Label Studio project', 'run file export for a Label Studio project with task and annotation filter options', 'convert an exported Label Studio JSON file to another format like CSV or TSV', "get serialized export data from a project's tasks with filtering and serialization options", 'filter a task queryset by view, skipped, finished, or annotated status', 'filter annotations by usual, ground truth, or skipped status with prefetches', 'create a Django model to track export status, file, md5, and project association', 'build a function to get supported export formats for a Label Studio project', 'run a function to generate a project data export file in a specified format', 'test the DataExport.save_export_files method for writing export and info JSON files', 'review the ConvertedFormat model for storing asynchronously converted export files', 'create an AnnotationSerializer that serializes annotation data with optional video key frame interpolation and FSM state support', 'build a BaseExportDataSerializer that serializes Task objects with annotations, drafts, predictions, and resolves undefined task data fields', 'test the ExportCreateSerializer that validates task filter options, annotation filter options, and serialization options for export creation', 'review the ExportParamSerializer that validates export parameters including key frame interpolation, resource download, and export format selection', 'summarize the ExportSerializer that manages export metadata including created_by, created_at, status, md5, and converted formats']
```

Usage

```
{'create_export_snapshot': 'create a new export snapshot for a Label Studio project with task and annotation filters', 'list_export_snapshots': 'list all export snapshots for a specific Label Studio project ordered by creation date', 'download_export_file': 'download an export snapshot file in a specified format for a Label Studio project', 'convert_export_format': 'convert an existing export snapshot to a different format like CSV or TSV asynchronously', 'delete_export_snapshot': 'delete an export snapshot and its associated file from storage for a Label Studio project'}
```

## File: HumanSignal_label-studio/label_studio/data_export/mixins.py

Prompts

```
['create a new export snapshot for a Label Studio project with task and annotation filters', 'list all export snapshots for a specific Label Studio project ordered by creation date', 'download an export snapshot file in a specified format for a Label Studio project', 'convert an existing export snapshot to a different format like CSV or TSV asynchronously', 'delete an export snapshot and its associated file from storage for a Label Studio project', 'run file export for a Label Studio project with task and annotation filter options', 'convert an exported Label Studio JSON file to another format like CSV or TSV', "get serialized export data from a project's tasks with filtering and serialization options", 'filter a task queryset by view, skipped, finished, or annotated status', 'filter annotations by usual, ground truth, or skipped status with prefetches', 'create a Django model to track export status, file, md5, and project association', 'build a function to get supported export formats for a Label Studio project', 'run a function to generate a project data export file in a specified format', 'test the DataExport.save_export_files method for writing export and info JSON files', 'review the ConvertedFormat model for storing asynchronously converted export files', 'create an AnnotationSerializer that serializes annotation data with optional video key frame interpolation and FSM state support', 'build a BaseExportDataSerializer that serializes Task objects with annotations, drafts, predictions, and resolves undefined task data fields', 'test the ExportCreateSerializer that validates task filter options, annotation filter options, and serialization options for export creation', 'review the ExportParamSerializer that validates export parameters including key frame interpolation, resource download, and export format selection', 'summarize the ExportSerializer that manages export metadata including created_by, created_at, status, md5, and converted formats']
```

Usage

```
{'export_run_file_exporting': 'run file export for a Label Studio project with task and annotation filter options', 'export_convert_file': 'convert an exported Label Studio JSON file to another format like CSV or TSV', 'export_get_export_data': "get serialized export data from a project's tasks with filtering and serialization options", 'export_get_filtered_tasks': 'filter a task queryset by view, skipped, finished, or annotated status', 'export_get_filtered_annotations_queryset': 'filter annotations by usual, ground truth, or skipped status with prefetches'}
```

## File: HumanSignal_label-studio/label_studio/data_export/models.py

Prompts

```
['create a new export snapshot for a Label Studio project with task and annotation filters', 'list all export snapshots for a specific Label Studio project ordered by creation date', 'download an export snapshot file in a specified format for a Label Studio project', 'convert an existing export snapshot to a different format like CSV or TSV asynchronously', 'delete an export snapshot and its associated file from storage for a Label Studio project', 'run file export for a Label Studio project with task and annotation filter options', 'convert an exported Label Studio JSON file to another format like CSV or TSV', "get serialized export data from a project's tasks with filtering and serialization options", 'filter a task queryset by view, skipped, finished, or annotated status', 'filter annotations by usual, ground truth, or skipped status with prefetches', 'create a Django model to track export status, file, md5, and project association', 'build a function to get supported export formats for a Label Studio project', 'run a function to generate a project data export file in a specified format', 'test the DataExport.save_export_files method for writing export and info JSON files', 'review the ConvertedFormat model for storing asynchronously converted export files', 'create an AnnotationSerializer that serializes annotation data with optional video key frame interpolation and FSM state support', 'build a BaseExportDataSerializer that serializes Task objects with annotations, drafts, predictions, and resolves undefined task data fields', 'test the ExportCreateSerializer that validates task filter options, annotation filter options, and serialization options for export creation', 'review the ExportParamSerializer that validates export parameters including key frame interpolation, resource download, and export format selection', 'summarize the ExportSerializer that manages export metadata including created_by, created_at, status, md5, and converted formats']
```

Usage

```
{'create_model_export': 'create a Django model to track export status, file, md5, and project association', 'build_export_formats': 'build a function to get supported export formats for a Label Studio project', 'run_generate_export_file': 'run a function to generate a project data export file in a specified format', 'test_data_export_save': 'test the DataExport.save_export_files method for writing export and info JSON files', 'review_model_converted_format': 'review the ConvertedFormat model for storing asynchronously converted export files'}
```

## File: HumanSignal_label-studio/label_studio/data_export/serializers.py

Prompts

```
['create a new export snapshot for a Label Studio project with task and annotation filters', 'list all export snapshots for a specific Label Studio project ordered by creation date', 'download an export snapshot file in a specified format for a Label Studio project', 'convert an existing export snapshot to a different format like CSV or TSV asynchronously', 'delete an export snapshot and its associated file from storage for a Label Studio project', 'run file export for a Label Studio project with task and annotation filter options', 'convert an exported Label Studio JSON file to another format like CSV or TSV', "get serialized export data from a project's tasks with filtering and serialization options", 'filter a task queryset by view, skipped, finished, or annotated status', 'filter annotations by usual, ground truth, or skipped status with prefetches', 'create a Django model to track export status, file, md5, and project association', 'build a function to get supported export formats for a Label Studio project', 'run a function to generate a project data export file in a specified format', 'test the DataExport.save_export_files method for writing export and info JSON files', 'review the ConvertedFormat model for storing asynchronously converted export files', 'create an AnnotationSerializer that serializes annotation data with optional video key frame interpolation and FSM state support', 'build a BaseExportDataSerializer that serializes Task objects with annotations, drafts, predictions, and resolves undefined task data fields', 'test the ExportCreateSerializer that validates task filter options, annotation filter options, and serialization options for export creation', 'review the ExportParamSerializer that validates export parameters including key frame interpolation, resource download, and export format selection', 'summarize the ExportSerializer that manages export metadata including created_by, created_at, status, md5, and converted formats']
```

Usage

```
{'create_annotation_serializer': 'create an AnnotationSerializer that serializes annotation data with optional video key frame interpolation and FSM state support', 'build_export_data_serializer': 'build a BaseExportDataSerializer that serializes Task objects with annotations, drafts, predictions, and resolves undefined task data fields', 'test_export_create_serializer': 'test the ExportCreateSerializer that validates task filter options, annotation filter options, and serialization options for export creation', 'review_export_param_serializer': 'review the ExportParamSerializer that validates export parameters including key frame interpolation, resource download, and export format selection', 'summarize_export_serializer': 'summarize the ExportSerializer that manages export metadata including created_by, created_at, status, md5, and converted formats'}
```

