# Agent Python Tools

- repo: facebookresearch/flores
- repo_uri: https://github.com/facebookresearch/flores

## File: facebookresearch_flores/ocr/OCR_eval/OCR_eval.py

Prompts

```
['run OCR evaluation on FLORES or UDHR datasets using tesseract or googlevision', 'run tesseract OCR on FLORES dataset images and compute CER and WER metrics', 'run tesseract OCR on UDHR dataset articles and compute average error rates', 'read language codes and tesseract codes from the languages fonts codes CSV file', 'run tesseract OCR on crawled book images and generate 10k 20k and 30k text samples', 'run Google Vision OCR on TIFF or PDF files stored in GCS buckets', 'run async document text detection on GCS files using Google Cloud Vision API', 'run batch OCR processing on FLORES or UDHR dataset TIFF files via CLI', 'run OCR on GCS files while skipping already processed output files', 'run OCR with automatic logging of failed GCS source URIs to a log file', 'run the python metrics module with --pred and --tgt flags to compute CER and WER', 'compute character error rate and word error rate from predicted and target text files', 'calculate CER and WER between predicted text and transcript using the ErrorMetrics class', 'check and rejoin hyphenated split words in predicted OCR text output', 'preprocess text by stripping whitespace and normalizing spaces using the ErrorMetrics class']
```

Usage

```
{'run_ocr_evaluation': 'run OCR evaluation on FLORES or UDHR datasets using tesseract or googlevision', 'run_tesseract_on_flores': 'run tesseract OCR on FLORES dataset images and compute CER and WER metrics', 'run_tesseract_on_udhr': 'run tesseract OCR on UDHR dataset articles and compute average error rates', 'read_ocr_language_codes': 'read language codes and tesseract codes from the languages fonts codes CSV file', 'run_tesseract_on_books': 'run tesseract OCR on crawled book images and generate 10k 20k and 30k text samples'}
```

## File: facebookresearch_flores/ocr/OCR_eval/google_vision_OCR.py

Prompts

```
['run OCR evaluation on FLORES or UDHR datasets using tesseract or googlevision', 'run tesseract OCR on FLORES dataset images and compute CER and WER metrics', 'run tesseract OCR on UDHR dataset articles and compute average error rates', 'read language codes and tesseract codes from the languages fonts codes CSV file', 'run tesseract OCR on crawled book images and generate 10k 20k and 30k text samples', 'run Google Vision OCR on TIFF or PDF files stored in GCS buckets', 'run async document text detection on GCS files using Google Cloud Vision API', 'run batch OCR processing on FLORES or UDHR dataset TIFF files via CLI', 'run OCR on GCS files while skipping already processed output files', 'run OCR with automatic logging of failed GCS source URIs to a log file', 'run the python metrics module with --pred and --tgt flags to compute CER and WER', 'compute character error rate and word error rate from predicted and target text files', 'calculate CER and WER between predicted text and transcript using the ErrorMetrics class', 'check and rejoin hyphenated split words in predicted OCR text output', 'preprocess text by stripping whitespace and normalizing spaces using the ErrorMetrics class']
```

Usage

```
{'run_google_vision_ocr': 'run Google Vision OCR on TIFF or PDF files stored in GCS buckets', 'run_async_document_detection': 'run async document text detection on GCS files using Google Cloud Vision API', 'run_ocr_batch_processing': 'run batch OCR processing on FLORES or UDHR dataset TIFF files via CLI', 'run_ocr_with_skip': 'run OCR on GCS files while skipping already processed output files', 'run_ocr_with_logging': 'run OCR with automatic logging of failed GCS source URIs to a log file'}
```

## File: facebookresearch_flores/ocr/OCR_eval/metrics.py

Prompts

```
['run OCR evaluation on FLORES or UDHR datasets using tesseract or googlevision', 'run tesseract OCR on FLORES dataset images and compute CER and WER metrics', 'run tesseract OCR on UDHR dataset articles and compute average error rates', 'read language codes and tesseract codes from the languages fonts codes CSV file', 'run tesseract OCR on crawled book images and generate 10k 20k and 30k text samples', 'run Google Vision OCR on TIFF or PDF files stored in GCS buckets', 'run async document text detection on GCS files using Google Cloud Vision API', 'run batch OCR processing on FLORES or UDHR dataset TIFF files via CLI', 'run OCR on GCS files while skipping already processed output files', 'run OCR with automatic logging of failed GCS source URIs to a log file', 'run the python metrics module with --pred and --tgt flags to compute CER and WER', 'compute character error rate and word error rate from predicted and target text files', 'calculate CER and WER between predicted text and transcript using the ErrorMetrics class', 'check and rejoin hyphenated split words in predicted OCR text output', 'preprocess text by stripping whitespace and normalizing spaces using the ErrorMetrics class']
```

Usage

```
{'run_metrics_cli': 'run the python metrics module with --pred and --tgt flags to compute CER and WER', 'compute_metrics_function': 'compute character error rate and word error rate from predicted and target text files', 'calculate_metrics_method': 'calculate CER and WER between predicted text and transcript using the ErrorMetrics class', 'check_splitted_words_function': 'check and rejoin hyphenated split words in predicted OCR text output', 'preprocess_method': 'preprocess text by stripping whitespace and normalizing spaces using the ErrorMetrics class'}
```

