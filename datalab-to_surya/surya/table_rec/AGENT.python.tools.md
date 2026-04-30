# Agent Python Tools

- repo: datalab-to/surya
- repo_uri: https://github.com/datalab-to/surya

## File: datalab-to_surya/surya/table_rec/loader.py

Prompts

```
['build a table recognition model using TableRecModelLoader with custom checkpoint, device, and dtype', 'create a TableRecModelLoader instance to load Surya table recognition model from a checkpoint', 'load a compiled table recognition model on cpu or cuda device with float32 or float16 dtype', 'create a SuryaTableRecProcessor with token pad, eos, bos, and query end ids from checkpoint', 'review the TableRecModelLoader class and its model and processor methods for table recognition', 'create a SuryaTableRecProcessor instance from a model checkpoint path for table recognition', 'build model input tensors by calling the processor with images, query items, and optional columns', 'test resizing and clipping a polygon from an original image size to a fixed box dimension', 'refactor the processor __call__ to support batch encoding of images with polygon query items', 'review the SuryaTableRecProcessor class and its image processing, label shaping, and tensor encoding pipeline', 'create a TableCell with polygon box, row/col IDs, colspan, rowspan, merge flags, and text lines', 'create a TableRow with polygon box geometry, row ID, and header flag', 'create a TableCol with polygon box geometry, column ID, and header flag', 'build a TableResult containing cells, unmerged cells, rows, columns, and image bounding box', 'review the TableCell label property that formats cell ID with rowspan and colspan', 'convert polygon coordinates to bounding boxes with center, width, height, and skew values', 'convert a bounding box vector back to four corner polygon coordinates with skew reconstruction', 'convert label component dictionaries to numeric vectors for model input with validation and clipping', 'get the start and end index range for a box property key in the label vector', 'build a dictionary mapping each box property key to its index range in the label vector']
```

Usage

```
{'build_table_rec_model': 'build a table recognition model using TableRecModelLoader with custom checkpoint, device, and dtype', 'create_model_loader': 'create a TableRecModelLoader instance to load Surya table recognition model from a checkpoint', 'load_model_inference': 'load a compiled table recognition model on cpu or cuda device with float32 or float16 dtype', 'create_table_rec_processor': 'create a SuryaTableRecProcessor with token pad, eos, bos, and query end ids from checkpoint', 'review_table_rec_model': 'review the TableRecModelLoader class and its model and processor methods for table recognition'}
```

## File: datalab-to_surya/surya/table_rec/processor.py

Prompts

```
['build a table recognition model using TableRecModelLoader with custom checkpoint, device, and dtype', 'create a TableRecModelLoader instance to load Surya table recognition model from a checkpoint', 'load a compiled table recognition model on cpu or cuda device with float32 or float16 dtype', 'create a SuryaTableRecProcessor with token pad, eos, bos, and query end ids from checkpoint', 'review the TableRecModelLoader class and its model and processor methods for table recognition', 'create a SuryaTableRecProcessor instance from a model checkpoint path for table recognition', 'build model input tensors by calling the processor with images, query items, and optional columns', 'test resizing and clipping a polygon from an original image size to a fixed box dimension', 'refactor the processor __call__ to support batch encoding of images with polygon query items', 'review the SuryaTableRecProcessor class and its image processing, label shaping, and tensor encoding pipeline', 'create a TableCell with polygon box, row/col IDs, colspan, rowspan, merge flags, and text lines', 'create a TableRow with polygon box geometry, row ID, and header flag', 'create a TableCol with polygon box geometry, column ID, and header flag', 'build a TableResult containing cells, unmerged cells, rows, columns, and image bounding box', 'review the TableCell label property that formats cell ID with rowspan and colspan', 'convert polygon coordinates to bounding boxes with center, width, height, and skew values', 'convert a bounding box vector back to four corner polygon coordinates with skew reconstruction', 'convert label component dictionaries to numeric vectors for model input with validation and clipping', 'get the start and end index range for a box property key in the label vector', 'build a dictionary mapping each box property key to its index range in the label vector']
```

Usage

```
{'create_SuryaTableRecProcessor': 'create a SuryaTableRecProcessor instance from a model checkpoint path for table recognition', 'build_processor_call': 'build model input tensors by calling the processor with images, query items, and optional columns', 'test_resize_polygon': 'test resizing and clipping a polygon from an original image size to a fixed box dimension', 'refactor_processor_call': 'refactor the processor __call__ to support batch encoding of images with polygon query items', 'review_SuryaTableRecProcessor': 'review the SuryaTableRecProcessor class and its image processing, label shaping, and tensor encoding pipeline'}
```

## File: datalab-to_surya/surya/table_rec/schema.py

Prompts

```
['build a table recognition model using TableRecModelLoader with custom checkpoint, device, and dtype', 'create a TableRecModelLoader instance to load Surya table recognition model from a checkpoint', 'load a compiled table recognition model on cpu or cuda device with float32 or float16 dtype', 'create a SuryaTableRecProcessor with token pad, eos, bos, and query end ids from checkpoint', 'review the TableRecModelLoader class and its model and processor methods for table recognition', 'create a SuryaTableRecProcessor instance from a model checkpoint path for table recognition', 'build model input tensors by calling the processor with images, query items, and optional columns', 'test resizing and clipping a polygon from an original image size to a fixed box dimension', 'refactor the processor __call__ to support batch encoding of images with polygon query items', 'review the SuryaTableRecProcessor class and its image processing, label shaping, and tensor encoding pipeline', 'create a TableCell with polygon box, row/col IDs, colspan, rowspan, merge flags, and text lines', 'create a TableRow with polygon box geometry, row ID, and header flag', 'create a TableCol with polygon box geometry, column ID, and header flag', 'build a TableResult containing cells, unmerged cells, rows, columns, and image bounding box', 'review the TableCell label property that formats cell ID with rowspan and colspan', 'convert polygon coordinates to bounding boxes with center, width, height, and skew values', 'convert a bounding box vector back to four corner polygon coordinates with skew reconstruction', 'convert label component dictionaries to numeric vectors for model input with validation and clipping', 'get the start and end index range for a box property key in the label vector', 'build a dictionary mapping each box property key to its index range in the label vector']
```

Usage

```
{'create_table_cell': 'create a TableCell with polygon box, row/col IDs, colspan, rowspan, merge flags, and text lines', 'create_table_row': 'create a TableRow with polygon box geometry, row ID, and header flag', 'create_table_col': 'create a TableCol with polygon box geometry, column ID, and header flag', 'build_table_result': 'build a TableResult containing cells, unmerged cells, rows, columns, and image bounding box', 'review_table_cell_label': 'review the TableCell label property that formats cell ID with rowspan and colspan'}
```

## File: datalab-to_surya/surya/table_rec/shaper.py

Prompts

```
['build a table recognition model using TableRecModelLoader with custom checkpoint, device, and dtype', 'create a TableRecModelLoader instance to load Surya table recognition model from a checkpoint', 'load a compiled table recognition model on cpu or cuda device with float32 or float16 dtype', 'create a SuryaTableRecProcessor with token pad, eos, bos, and query end ids from checkpoint', 'review the TableRecModelLoader class and its model and processor methods for table recognition', 'create a SuryaTableRecProcessor instance from a model checkpoint path for table recognition', 'build model input tensors by calling the processor with images, query items, and optional columns', 'test resizing and clipping a polygon from an original image size to a fixed box dimension', 'refactor the processor __call__ to support batch encoding of images with polygon query items', 'review the SuryaTableRecProcessor class and its image processing, label shaping, and tensor encoding pipeline', 'create a TableCell with polygon box, row/col IDs, colspan, rowspan, merge flags, and text lines', 'create a TableRow with polygon box geometry, row ID, and header flag', 'create a TableCol with polygon box geometry, column ID, and header flag', 'build a TableResult containing cells, unmerged cells, rows, columns, and image bounding box', 'review the TableCell label property that formats cell ID with rowspan and colspan', 'convert polygon coordinates to bounding boxes with center, width, height, and skew values', 'convert a bounding box vector back to four corner polygon coordinates with skew reconstruction', 'convert label component dictionaries to numeric vectors for model input with validation and clipping', 'get the start and end index range for a box property key in the label vector', 'build a dictionary mapping each box property key to its index range in the label vector']
```

Usage

```
{'convert_polygons_to_bboxes': 'convert polygon coordinates to bounding boxes with center, width, height, and skew values', 'convert_bbox_to_polygon': 'convert a bounding box vector back to four corner polygon coordinates with skew reconstruction', 'dict_to_labels': 'convert label component dictionaries to numeric vectors for model input with validation and clipping', 'component_idx': 'get the start and end index range for a box property key in the label vector', 'component_idx_dict': 'build a dictionary mapping each box property key to its index range in the label vector'}
```

