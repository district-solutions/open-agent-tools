# Agent Python Tools

- repo: datalab-to/surya
- repo_uri: https://github.com/datalab-to/surya

## File: datalab-to_surya/surya/logging.py

Prompts

```
['configure the surya logger with a stream handler, formatter, and log level from settings', 'get the surya logger instance for use throughout the application', 'test the configure_logging function sets up the logger with correct handler and formatter', 'test the get_logger function returns a logger instance named surya', 'refactor configure_logging to accept custom handler and formatter parameters', 'build a function call to load all surya predictors including layout, detection, recognition, ocr_error, and table_rec', 'create a layout predictor using the surya foundation model checkpoint for document layout analysis', 'create a text detection predictor with optional device and dtype configuration for OCR text regions', 'create an OCR recognition predictor using the surya foundation model for text content extraction', 'create a table recognition predictor with optional device and dtype for table structure extraction', 'create a Settings instance from pydantic_settings that auto-loads from local.env and environment variables', 'get the detected torch device model string (cpu, cuda, mps, or xla) from the Settings class', 'configure the model data type (float32, float16, or bfloat16) based on the detected torch device', 'set text detection thresholds including text threshold and blank threshold for the OCR pipeline', 'configure OCR model checkpoints, batch sizes, and render fonts for text recognition and layout analysis']
```

Usage

```
{'configure_logging': 'configure the surya logger with a stream handler, formatter, and log level from settings', 'get_logger': 'get the surya logger instance for use throughout the application', 'test_configure_logging': 'test the configure_logging function sets up the logger with correct handler and formatter', 'test_get_logger': 'test the get_logger function returns a logger instance named surya', 'refactor_configure_logging': 'refactor configure_logging to accept custom handler and formatter parameters'}
```

## File: datalab-to_surya/surya/models.py

Prompts

```
['configure the surya logger with a stream handler, formatter, and log level from settings', 'get the surya logger instance for use throughout the application', 'test the configure_logging function sets up the logger with correct handler and formatter', 'test the get_logger function returns a logger instance named surya', 'refactor configure_logging to accept custom handler and formatter parameters', 'build a function call to load all surya predictors including layout, detection, recognition, ocr_error, and table_rec', 'create a layout predictor using the surya foundation model checkpoint for document layout analysis', 'create a text detection predictor with optional device and dtype configuration for OCR text regions', 'create an OCR recognition predictor using the surya foundation model for text content extraction', 'create a table recognition predictor with optional device and dtype for table structure extraction', 'create a Settings instance from pydantic_settings that auto-loads from local.env and environment variables', 'get the detected torch device model string (cpu, cuda, mps, or xla) from the Settings class', 'configure the model data type (float32, float16, or bfloat16) based on the detected torch device', 'set text detection thresholds including text threshold and blank threshold for the OCR pipeline', 'configure OCR model checkpoints, batch sizes, and render fonts for text recognition and layout analysis']
```

Usage

```
{'build_load_predictors': 'build a function call to load all surya predictors including layout, detection, recognition, ocr_error, and table_rec', 'create_layout_predictor': 'create a layout predictor using the surya foundation model checkpoint for document layout analysis', 'create_detection_predictor': 'create a text detection predictor with optional device and dtype configuration for OCR text regions', 'create_recognition_predictor': 'create an OCR recognition predictor using the surya foundation model for text content extraction', 'create_table_recognizer': 'create a table recognition predictor with optional device and dtype for table structure extraction'}
```

## File: datalab-to_surya/surya/settings.py

Prompts

```
['configure the surya logger with a stream handler, formatter, and log level from settings', 'get the surya logger instance for use throughout the application', 'test the configure_logging function sets up the logger with correct handler and formatter', 'test the get_logger function returns a logger instance named surya', 'refactor configure_logging to accept custom handler and formatter parameters', 'build a function call to load all surya predictors including layout, detection, recognition, ocr_error, and table_rec', 'create a layout predictor using the surya foundation model checkpoint for document layout analysis', 'create a text detection predictor with optional device and dtype configuration for OCR text regions', 'create an OCR recognition predictor using the surya foundation model for text content extraction', 'create a table recognition predictor with optional device and dtype for table structure extraction', 'create a Settings instance from pydantic_settings that auto-loads from local.env and environment variables', 'get the detected torch device model string (cpu, cuda, mps, or xla) from the Settings class', 'configure the model data type (float32, float16, or bfloat16) based on the detected torch device', 'set text detection thresholds including text threshold and blank threshold for the OCR pipeline', 'configure OCR model checkpoints, batch sizes, and render fonts for text recognition and layout analysis']
```

Usage

```
{'create_settings_instance': 'create a Settings instance from pydantic_settings that auto-loads from local.env and environment variables', 'get_torch_device_model': 'get the detected torch device model string (cpu, cuda, mps, or xla) from the Settings class', 'configure_model_dtype': 'configure the model data type (float32, float16, or bfloat16) based on the detected torch device', 'set_detector_thresholds': 'set text detection thresholds including text threshold and blank threshold for the OCR pipeline', 'configure_ocr_models': 'configure OCR model checkpoints, batch sizes, and render fonts for text recognition and layout analysis'}
```

