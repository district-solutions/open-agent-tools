# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/models/stages/table_structure/table_structure_model.py

Prompts

```
['run table structure prediction on document pages using TableFormer model', 'create a TableStructureModel instance with enabled flag, artifacts path, and accelerator options', 'download TableFormer model artifacts from HuggingFace hub to a local directory', 'test the TableStructureModel class and its prediction pipeline on document pages', 'review the TableStructureModel class and its table detection and cell matching logic', 'parse VLM OTSL text output into structured table data with rows, columns, and cell metadata', 'create a GraniteVisionTableStructureModel instance for table structure detection using ibm-granite vision model', 'download the ibm-granite/granite-4.0-3b-vision model artifacts from HuggingFace Hub', 'run table structure prediction on conversion result pages using the granite vision model', 'build a GraniteVisionTableStructureModel with accelerator options and artifacts path for GPU or CPU inference', 'download the TableFormerV2 model from HuggingFace to a local directory', 'predict table structures on document pages using the TableFormerV2 model', 'build table cell structures from an OTSL sequence and predicted bounding boxes', 'decode token IDs into an OTSL tag sequence for table structure parsing', 'match text from page text cells to table cell bounding boxes by overlap']
```

Usage

```
{'run_table_structure_prediction': 'run table structure prediction on document pages using TableFormer model', 'create_table_structure_model': 'create a TableStructureModel instance with enabled flag, artifacts path, and accelerator options', 'download_tableformer_models': 'download TableFormer model artifacts from HuggingFace hub to a local directory', 'test_table_structure_model': 'test the TableStructureModel class and its prediction pipeline on document pages', 'review_table_structure_model': 'review the TableStructureModel class and its table detection and cell matching logic'}
```

## File: docling-project_docling/docling/models/stages/table_structure/table_structure_model_granite_vision.py

Prompts

```
['run table structure prediction on document pages using TableFormer model', 'create a TableStructureModel instance with enabled flag, artifacts path, and accelerator options', 'download TableFormer model artifacts from HuggingFace hub to a local directory', 'test the TableStructureModel class and its prediction pipeline on document pages', 'review the TableStructureModel class and its table detection and cell matching logic', 'parse VLM OTSL text output into structured table data with rows, columns, and cell metadata', 'create a GraniteVisionTableStructureModel instance for table structure detection using ibm-granite vision model', 'download the ibm-granite/granite-4.0-3b-vision model artifacts from HuggingFace Hub', 'run table structure prediction on conversion result pages using the granite vision model', 'build a GraniteVisionTableStructureModel with accelerator options and artifacts path for GPU or CPU inference', 'download the TableFormerV2 model from HuggingFace to a local directory', 'predict table structures on document pages using the TableFormerV2 model', 'build table cell structures from an OTSL sequence and predicted bounding boxes', 'decode token IDs into an OTSL tag sequence for table structure parsing', 'match text from page text cells to table cell bounding boxes by overlap']
```

Usage

```
{'parse_otsl_output': 'parse VLM OTSL text output into structured table data with rows, columns, and cell metadata', 'create_GraniteVisionTableStructureModel': 'create a GraniteVisionTableStructureModel instance for table structure detection using ibm-granite vision model', 'download_GraniteVisionTableStructureModel': 'download the ibm-granite/granite-4.0-3b-vision model artifacts from HuggingFace Hub', 'run_GraniteVisionTableStructureModel_predict_tables': 'run table structure prediction on conversion result pages using the granite vision model', 'build_GraniteVisionTableStructureModel': 'build a GraniteVisionTableStructureModel with accelerator options and artifacts path for GPU or CPU inference'}
```

## File: docling-project_docling/docling/models/stages/table_structure/table_structure_model_v2.py

Prompts

```
['run table structure prediction on document pages using TableFormer model', 'create a TableStructureModel instance with enabled flag, artifacts path, and accelerator options', 'download TableFormer model artifacts from HuggingFace hub to a local directory', 'test the TableStructureModel class and its prediction pipeline on document pages', 'review the TableStructureModel class and its table detection and cell matching logic', 'parse VLM OTSL text output into structured table data with rows, columns, and cell metadata', 'create a GraniteVisionTableStructureModel instance for table structure detection using ibm-granite vision model', 'download the ibm-granite/granite-4.0-3b-vision model artifacts from HuggingFace Hub', 'run table structure prediction on conversion result pages using the granite vision model', 'build a GraniteVisionTableStructureModel with accelerator options and artifacts path for GPU or CPU inference', 'download the TableFormerV2 model from HuggingFace to a local directory', 'predict table structures on document pages using the TableFormerV2 model', 'build table cell structures from an OTSL sequence and predicted bounding boxes', 'decode token IDs into an OTSL tag sequence for table structure parsing', 'match text from page text cells to table cell bounding boxes by overlap']
```

Usage

```
{'download_models': 'download the TableFormerV2 model from HuggingFace to a local directory', 'predict_tables': 'predict table structures on document pages using the TableFormerV2 model', 'build_table_cells': 'build table cell structures from an OTSL sequence and predicted bounding boxes', 'decode_otsl_sequence': 'decode token IDs into an OTSL tag sequence for table structure parsing', 'match_text': 'match text from page text cells to table cell bounding boxes by overlap'}
```

