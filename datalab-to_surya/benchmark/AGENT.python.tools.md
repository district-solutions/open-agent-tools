# Agent Python Tools

- repo: datalab-to/surya
- repo_uri: https://github.com/datalab-to/surya

## File: datalab-to_surya/benchmark/recognition.py

Prompts

```
['run the Surya OCR recognition benchmark CLI to evaluate model performance on images', 'run the OCR benchmark with tesseract comparison enabled for accuracy evaluation', 'run the OCR benchmark with textract comparison enabled for accuracy evaluation', 'run the OCR recognition benchmark filtered to a comma-separated list of languages', 'normalize OCR text by removing HTML tags, LaTeX commands, standardizing bullets, and lowercasing', 'run the texify benchmark CLI to evaluate OCR accuracy on math equation images', 'run texify benchmark in line mode to process images with per-line bounding boxes', 'run texify benchmark on a subset of dataset rows for quick evaluation', 'score texify predictions against reference equations using normalized Levenshtein distance', 'run texify inference on a dataset of images to predict LaTeX equation text']
```

Usage

```
{'run_benchmark_recognition': 'run the Surya OCR recognition benchmark CLI to evaluate model performance on images', 'run_benchmark_tesseract': 'run the OCR benchmark with tesseract comparison enabled for accuracy evaluation', 'run_benchmark_textract': 'run the OCR benchmark with textract comparison enabled for accuracy evaluation', 'run_benchmark_languages': 'run the OCR recognition benchmark filtered to a comma-separated list of languages', 'normalize_text': 'normalize OCR text by removing HTML tags, LaTeX commands, standardizing bullets, and lowercasing'}
```

## File: datalab-to_surya/benchmark/texify.py

Prompts

```
['run the Surya OCR recognition benchmark CLI to evaluate model performance on images', 'run the OCR benchmark with tesseract comparison enabled for accuracy evaluation', 'run the OCR benchmark with textract comparison enabled for accuracy evaluation', 'run the OCR recognition benchmark filtered to a comma-separated list of languages', 'normalize OCR text by removing HTML tags, LaTeX commands, standardizing bullets, and lowercasing', 'run the texify benchmark CLI to evaluate OCR accuracy on math equation images', 'run texify benchmark in line mode to process images with per-line bounding boxes', 'run texify benchmark on a subset of dataset rows for quick evaluation', 'score texify predictions against reference equations using normalized Levenshtein distance', 'run texify inference on a dataset of images to predict LaTeX equation text']
```

Usage

```
{'run_benchmark_texify': 'run the texify benchmark CLI to evaluate OCR accuracy on math equation images', 'run_benchmark_line_mode': 'run texify benchmark in line mode to process images with per-line bounding boxes', 'run_benchmark_max_rows': 'run texify benchmark on a subset of dataset rows for quick evaluation', 'score_text_predictions': 'score texify predictions against reference equations using normalized Levenshtein distance', 'inference_texify_images': 'run texify inference on a dataset of images to predict LaTeX equation text'}
```

