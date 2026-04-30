# Agent Python Tools

- repo: datalab-to/surya
- repo_uri: https://github.com/datalab-to/surya

## File: datalab-to_surya/surya/input/load.py

Prompts

```
['load a PDF file and return page images with names and optional page range and DPI', 'load a single image file and return it as an RGB image with its name', 'load a file by auto-detecting whether it is a PDF or image and return images with names', 'load all images and PDFs from a folder and return combined images with names', 'load a language mapping JSON file and return language codes for given names', 'convert a list of PIL images to RGB mode, converting any non-RGB images', 'open a PDF file and return a pypdfium2 document object for page extraction', 'extract images from specified pages of a PDF document at a given DPI', 'slice rectangular regions from a numpy image array using bounding box coordinates', 'slice polygonal regions from a numpy image array and pad outside areas with a fill value']
```

Usage

```
{'load_pdf_from_path': 'load a PDF file and return page images with names and optional page range and DPI', 'load_image_from_path': 'load a single image file and return it as an RGB image with its name', 'load_from_file_auto_detect': 'load a file by auto-detecting whether it is a PDF or image and return images with names', 'load_from_folder_batch': 'load all images and PDFs from a folder and return combined images with names', 'load_lang_file_by_names': 'load a language mapping JSON file and return language codes for given names'}
```

## File: datalab-to_surya/surya/input/processing.py

Prompts

```
['load a PDF file and return page images with names and optional page range and DPI', 'load a single image file and return it as an RGB image with its name', 'load a file by auto-detecting whether it is a PDF or image and return images with names', 'load all images and PDFs from a folder and return combined images with names', 'load a language mapping JSON file and return language codes for given names', 'convert a list of PIL images to RGB mode, converting any non-RGB images', 'open a PDF file and return a pypdfium2 document object for page extraction', 'extract images from specified pages of a PDF document at a given DPI', 'slice rectangular regions from a numpy image array using bounding box coordinates', 'slice polygonal regions from a numpy image array and pad outside areas with a fill value']
```

Usage

```
{'convert_images_to_rgb': 'convert a list of PIL images to RGB mode, converting any non-RGB images', 'open_pdf_document': 'open a PDF file and return a pypdfium2 document object for page extraction', 'extract_page_images': 'extract images from specified pages of a PDF document at a given DPI', 'slice_bboxes_from_image': 'slice rectangular regions from a numpy image array using bounding box coordinates', 'slice_polys_from_image': 'slice polygonal regions from a numpy image array and pad outside areas with a fill value'}
```

