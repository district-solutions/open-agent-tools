# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/libs/libcommon/tests/viewer_utils/test_assets.py

Prompts

```
['test the create_image_file function to upload and verify a JPEG image asset in storage', 'test the create_audio_file function with WAV and Opus audio files for storage upload', 'test the create_pdf_file function to upload a PDF and generate a thumbnail image', 'test that asset source URLs are sanitized to prevent XSS injection attacks', 'review the test suite for image, audio, and PDF asset creation functions', 'test get_cell_value to convert a dataset cell to a viewer-friendly value for a given feature type', 'test to_features_list to convert a Features dict to an ordered list of feature items with indices', 'test infer_audio_file_extension to detect audio file format from raw bytes using magic number signatures', 'test get_cell_value with OGG audio files stored in a mocked S3 bucket via moto', 'test assert_output_has_valid_files to recursively verify that asset source URLs point to existing non-empty files', 'test the create_first_rows_response function with various dataset fixtures to verify features and rows', 'test the create_first_rows_response function with different byte and row limits to verify truncation', 'test the create_first_rows_response function with audio and image datasets to verify truncation behavior', 'review the create_first_rows_response function that generates first rows responses with truncation support', 'review the transform_rows function that post-processes dataset rows with cell value transformations', 'truncate a single row item cell to a minimum byte size while keeping specified columns untruncated', 'truncate cells across multiple row items to fit within a maximum byte size limit', 'create truncated row items by removing excess rows and truncating cells to fit a byte budget', 'test the truncate_row_item function with parametrized cells and minimum byte size configurations', 'test the create_truncated_row_items function with varying maximum byte size limits and expected row counts']
```

Usage

```
{'test_create_image_file': 'test the create_image_file function to upload and verify a JPEG image asset in storage', 'test_create_audio_file': 'test the create_audio_file function with WAV and Opus audio files for storage upload', 'test_create_pdf_file': 'test the create_pdf_file function to upload a PDF and generate a thumbnail image', 'test_src_is_sanitized': 'test that asset source URLs are sanitized to prevent XSS injection attacks', 'review_asset_creation_tests': 'review the test suite for image, audio, and PDF asset creation functions'}
```

## File: huggingface_dataset-viewer/libs/libcommon/tests/viewer_utils/test_features.py

Prompts

```
['test the create_image_file function to upload and verify a JPEG image asset in storage', 'test the create_audio_file function with WAV and Opus audio files for storage upload', 'test the create_pdf_file function to upload a PDF and generate a thumbnail image', 'test that asset source URLs are sanitized to prevent XSS injection attacks', 'review the test suite for image, audio, and PDF asset creation functions', 'test get_cell_value to convert a dataset cell to a viewer-friendly value for a given feature type', 'test to_features_list to convert a Features dict to an ordered list of feature items with indices', 'test infer_audio_file_extension to detect audio file format from raw bytes using magic number signatures', 'test get_cell_value with OGG audio files stored in a mocked S3 bucket via moto', 'test assert_output_has_valid_files to recursively verify that asset source URLs point to existing non-empty files', 'test the create_first_rows_response function with various dataset fixtures to verify features and rows', 'test the create_first_rows_response function with different byte and row limits to verify truncation', 'test the create_first_rows_response function with audio and image datasets to verify truncation behavior', 'review the create_first_rows_response function that generates first rows responses with truncation support', 'review the transform_rows function that post-processes dataset rows with cell value transformations', 'truncate a single row item cell to a minimum byte size while keeping specified columns untruncated', 'truncate cells across multiple row items to fit within a maximum byte size limit', 'create truncated row items by removing excess rows and truncating cells to fit a byte budget', 'test the truncate_row_item function with parametrized cells and minimum byte size configurations', 'test the create_truncated_row_items function with varying maximum byte size limits and expected row counts']
```

Usage

```
{'test_get_cell_value': 'test get_cell_value to convert a dataset cell to a viewer-friendly value for a given feature type', 'test_to_features_list': 'test to_features_list to convert a Features dict to an ordered list of feature items with indices', 'test_infer_audio_file_extension': 'test infer_audio_file_extension to detect audio file format from raw bytes using magic number signatures', 'test_ogg_audio_with_s3': 'test get_cell_value with OGG audio files stored in a mocked S3 bucket via moto', 'test_assert_output_has_valid_files': 'test assert_output_has_valid_files to recursively verify that asset source URLs point to existing non-empty files'}
```

## File: huggingface_dataset-viewer/libs/libcommon/tests/viewer_utils/test_rows.py

Prompts

```
['test the create_image_file function to upload and verify a JPEG image asset in storage', 'test the create_audio_file function with WAV and Opus audio files for storage upload', 'test the create_pdf_file function to upload a PDF and generate a thumbnail image', 'test that asset source URLs are sanitized to prevent XSS injection attacks', 'review the test suite for image, audio, and PDF asset creation functions', 'test get_cell_value to convert a dataset cell to a viewer-friendly value for a given feature type', 'test to_features_list to convert a Features dict to an ordered list of feature items with indices', 'test infer_audio_file_extension to detect audio file format from raw bytes using magic number signatures', 'test get_cell_value with OGG audio files stored in a mocked S3 bucket via moto', 'test assert_output_has_valid_files to recursively verify that asset source URLs point to existing non-empty files', 'test the create_first_rows_response function with various dataset fixtures to verify features and rows', 'test the create_first_rows_response function with different byte and row limits to verify truncation', 'test the create_first_rows_response function with audio and image datasets to verify truncation behavior', 'review the create_first_rows_response function that generates first rows responses with truncation support', 'review the transform_rows function that post-processes dataset rows with cell value transformations', 'truncate a single row item cell to a minimum byte size while keeping specified columns untruncated', 'truncate cells across multiple row items to fit within a maximum byte size limit', 'create truncated row items by removing excess rows and truncating cells to fit a byte budget', 'test the truncate_row_item function with parametrized cells and minimum byte size configurations', 'test the create_truncated_row_items function with varying maximum byte size limits and expected row counts']
```

Usage

```
{'test_create_first_rows_response': 'test the create_first_rows_response function with various dataset fixtures to verify features and rows', 'test_create_first_rows_response_truncated': 'test the create_first_rows_response function with different byte and row limits to verify truncation', 'test_create_first_rows_response_truncation_on_audio_or_image': 'test the create_first_rows_response function with audio and image datasets to verify truncation behavior', 'review_create_first_rows_response': 'review the create_first_rows_response function that generates first rows responses with truncation support', 'review_transform_rows': 'review the transform_rows function that post-processes dataset rows with cell value transformations'}
```

## File: huggingface_dataset-viewer/libs/libcommon/tests/viewer_utils/test_truncate_rows.py

Prompts

```
['test the create_image_file function to upload and verify a JPEG image asset in storage', 'test the create_audio_file function with WAV and Opus audio files for storage upload', 'test the create_pdf_file function to upload a PDF and generate a thumbnail image', 'test that asset source URLs are sanitized to prevent XSS injection attacks', 'review the test suite for image, audio, and PDF asset creation functions', 'test get_cell_value to convert a dataset cell to a viewer-friendly value for a given feature type', 'test to_features_list to convert a Features dict to an ordered list of feature items with indices', 'test infer_audio_file_extension to detect audio file format from raw bytes using magic number signatures', 'test get_cell_value with OGG audio files stored in a mocked S3 bucket via moto', 'test assert_output_has_valid_files to recursively verify that asset source URLs point to existing non-empty files', 'test the create_first_rows_response function with various dataset fixtures to verify features and rows', 'test the create_first_rows_response function with different byte and row limits to verify truncation', 'test the create_first_rows_response function with audio and image datasets to verify truncation behavior', 'review the create_first_rows_response function that generates first rows responses with truncation support', 'review the transform_rows function that post-processes dataset rows with cell value transformations', 'truncate a single row item cell to a minimum byte size while keeping specified columns untruncated', 'truncate cells across multiple row items to fit within a maximum byte size limit', 'create truncated row items by removing excess rows and truncating cells to fit a byte budget', 'test the truncate_row_item function with parametrized cells and minimum byte size configurations', 'test the create_truncated_row_items function with varying maximum byte size limits and expected row counts']
```

Usage

```
{'truncate_row_item': 'truncate a single row item cell to a minimum byte size while keeping specified columns untruncated', 'truncate_row_items_cells': 'truncate cells across multiple row items to fit within a maximum byte size limit', 'create_truncated_row_items': 'create truncated row items by removing excess rows and truncating cells to fit a byte budget', 'test_truncate_row_item': 'test the truncate_row_item function with parametrized cells and minimum byte size configurations', 'test_create_truncated_row_items': 'test the create_truncated_row_items function with varying maximum byte size limits and expected row counts'}
```

