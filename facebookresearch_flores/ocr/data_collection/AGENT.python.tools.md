# Agent Python Tools

- repo: facebookresearch/flores
- repo_uri: https://github.com/facebookresearch/flores

## File: facebookresearch_flores/ocr/data_collection/augment_data.py

Prompts

```
['run the OCR data augmentation pipeline for the FLORES dataset across all languages', 'run the OCR data augmentation pipeline for the UDHR dataset across all languages', 'create a CSS style file with custom font, color, opacity, and spacing properties', 'create an HTML file from a list of sentences with a linked CSS stylesheet', 'add Gaussian noise to an OCR image and save the augmented grayscale version', 'download a UDHR translation PDF for a given language code from ohchr.org', 'download and parse a UDHR XML file into a JSON dictionary of articles and paragraphs', 'convert a downloaded UDHR PDF into individual page images using pdf2image or ImageMagick', 'vertically stack multiple page images into a single combined PNG image', 'convert a UDHR PDF into cropped article images using predefined coordinate boundaries', 'run the FileSplitter to split a large file into smaller files with a set number of lines', 'split a large text file into multiple smaller files each containing a specified number of rows', 'parse command line arguments to configure the input file name and split size for file splitting', 'get a new file object ready to write to with an incremented file number and original extension', 'display the usage instructions for the file splitter CLI tool with file name and optional row count', 'merge two dictionaries and combine values of common keys into a deduplicated list', 'detect anomalous articles by finding CER error rates exceeding mean plus two standard deviations', 'return merged anomaly dictionaries from Google and Tesseract OCR across all language codes', 'read an OCR text file, normalize whitespace, and write the cleaned output to a new file', 'read a CSV file of language names and codes and return them as two separate lists']
```

Usage

```
{'run_augmentation_flores': 'run the OCR data augmentation pipeline for the FLORES dataset across all languages', 'run_augmentation_udhr': 'run the OCR data augmentation pipeline for the UDHR dataset across all languages', 'create_style_file': 'create a CSS style file with custom font, color, opacity, and spacing properties', 'create_html_file': 'create an HTML file from a list of sentences with a linked CSS stylesheet', 'add_gaussian_noise': 'add Gaussian noise to an OCR image and save the augmented grayscale version'}
```

## File: facebookresearch_flores/ocr/data_collection/download_UDHR_data.py

Prompts

```
['run the OCR data augmentation pipeline for the FLORES dataset across all languages', 'run the OCR data augmentation pipeline for the UDHR dataset across all languages', 'create a CSS style file with custom font, color, opacity, and spacing properties', 'create an HTML file from a list of sentences with a linked CSS stylesheet', 'add Gaussian noise to an OCR image and save the augmented grayscale version', 'download a UDHR translation PDF for a given language code from ohchr.org', 'download and parse a UDHR XML file into a JSON dictionary of articles and paragraphs', 'convert a downloaded UDHR PDF into individual page images using pdf2image or ImageMagick', 'vertically stack multiple page images into a single combined PNG image', 'convert a UDHR PDF into cropped article images using predefined coordinate boundaries', 'run the FileSplitter to split a large file into smaller files with a set number of lines', 'split a large text file into multiple smaller files each containing a specified number of rows', 'parse command line arguments to configure the input file name and split size for file splitting', 'get a new file object ready to write to with an incremented file number and original extension', 'display the usage instructions for the file splitter CLI tool with file name and optional row count', 'merge two dictionaries and combine values of common keys into a deduplicated list', 'detect anomalous articles by finding CER error rates exceeding mean plus two standard deviations', 'return merged anomaly dictionaries from Google and Tesseract OCR across all language codes', 'read an OCR text file, normalize whitespace, and write the cleaned output to a new file', 'read a CSV file of language names and codes and return them as two separate lists']
```

Usage

```
{'download_udhr_pdf': 'download a UDHR translation PDF for a given language code from ohchr.org', 'parse_udhr_xml_to_json': 'download and parse a UDHR XML file into a JSON dictionary of articles and paragraphs', 'convert_pdf_to_images': 'convert a downloaded UDHR PDF into individual page images using pdf2image or ImageMagick', 'join_images_vertically': 'vertically stack multiple page images into a single combined PNG image', 'split_pdf_into_articles': 'convert a UDHR PDF into cropped article images using predefined coordinate boundaries'}
```

## File: facebookresearch_flores/ocr/data_collection/file_splitter.py

Prompts

```
['run the OCR data augmentation pipeline for the FLORES dataset across all languages', 'run the OCR data augmentation pipeline for the UDHR dataset across all languages', 'create a CSS style file with custom font, color, opacity, and spacing properties', 'create an HTML file from a list of sentences with a linked CSS stylesheet', 'add Gaussian noise to an OCR image and save the augmented grayscale version', 'download a UDHR translation PDF for a given language code from ohchr.org', 'download and parse a UDHR XML file into a JSON dictionary of articles and paragraphs', 'convert a downloaded UDHR PDF into individual page images using pdf2image or ImageMagick', 'vertically stack multiple page images into a single combined PNG image', 'convert a UDHR PDF into cropped article images using predefined coordinate boundaries', 'run the FileSplitter to split a large file into smaller files with a set number of lines', 'split a large text file into multiple smaller files each containing a specified number of rows', 'parse command line arguments to configure the input file name and split size for file splitting', 'get a new file object ready to write to with an incremented file number and original extension', 'display the usage instructions for the file splitter CLI tool with file name and optional row count', 'merge two dictionaries and combine values of common keys into a deduplicated list', 'detect anomalous articles by finding CER error rates exceeding mean plus two standard deviations', 'return merged anomaly dictionaries from Google and Tesseract OCR across all language codes', 'read an OCR text file, normalize whitespace, and write the cleaned output to a new file', 'read a CSV file of language names and codes and return them as two separate lists']
```

Usage

```
{'run_file_splitter': 'run the FileSplitter to split a large file into smaller files with a set number of lines', 'split_large_file': 'split a large text file into multiple smaller files each containing a specified number of rows', 'parse_args_file_splitter': 'parse command line arguments to configure the input file name and split size for file splitting', 'get_new_file': 'get a new file object ready to write to with an incremented file number and original extension', 'usage_file_splitter': 'display the usage instructions for the file splitter CLI tool with file name and optional row count'}
```

## File: facebookresearch_flores/ocr/data_collection/utils.py

Prompts

```
['run the OCR data augmentation pipeline for the FLORES dataset across all languages', 'run the OCR data augmentation pipeline for the UDHR dataset across all languages', 'create a CSS style file with custom font, color, opacity, and spacing properties', 'create an HTML file from a list of sentences with a linked CSS stylesheet', 'add Gaussian noise to an OCR image and save the augmented grayscale version', 'download a UDHR translation PDF for a given language code from ohchr.org', 'download and parse a UDHR XML file into a JSON dictionary of articles and paragraphs', 'convert a downloaded UDHR PDF into individual page images using pdf2image or ImageMagick', 'vertically stack multiple page images into a single combined PNG image', 'convert a UDHR PDF into cropped article images using predefined coordinate boundaries', 'run the FileSplitter to split a large file into smaller files with a set number of lines', 'split a large text file into multiple smaller files each containing a specified number of rows', 'parse command line arguments to configure the input file name and split size for file splitting', 'get a new file object ready to write to with an incremented file number and original extension', 'display the usage instructions for the file splitter CLI tool with file name and optional row count', 'merge two dictionaries and combine values of common keys into a deduplicated list', 'detect anomalous articles by finding CER error rates exceeding mean plus two standard deviations', 'return merged anomaly dictionaries from Google and Tesseract OCR across all language codes', 'read an OCR text file, normalize whitespace, and write the cleaned output to a new file', 'read a CSV file of language names and codes and return them as two separate lists']
```

Usage

```
{'merge_dicts': 'merge two dictionaries and combine values of common keys into a deduplicated list', 'check_annotations_anomaly': 'detect anomalous articles by finding CER error rates exceeding mean plus two standard deviations', 'return_all_anomalies': 'return merged anomaly dictionaries from Google and Tesseract OCR across all language codes', 'sentence_split': 'read an OCR text file, normalize whitespace, and write the cleaned output to a new file', 'get_languages': 'read a CSV file of language names and codes and return them as two separate lists'}
```

