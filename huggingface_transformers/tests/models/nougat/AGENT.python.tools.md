# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/nougat/test_image_processing_nougat.py

Prompts

```
['test the NougatImageProcessingTest to verify image processor properties like do_resize and do_normalize', 'test the crop_margin method on an all-white image to confirm no cropping occurs', 'test the crop_margin method on a white image with a centered black square', 'test the align_long_axis method to verify image rotation when height exceeds width', 'test pixel value equivalence across PIL and Torchvision backends for the Nougat image processor', 'test the NougatTokenizer by tokenizing and decoding multilingual text with emojis and special characters', 'convert LaTeX equation tags, bold formatting, and URLs to markdown-compatible text using markdown_compatible', 'normalize flat list-like lines into properly indented multiline lists using normalize_list_like_lines', 'correct LaTeX table formatting by adding newlines around tabular environments using NougatTokenizer correct_tables', 'postprocess Nougat tokenizer output text with optional markdown fixing using post_process_single']
```

Usage

```
{'test_nougat_image_processor_properties': 'test the NougatImageProcessingTest to verify image processor properties like do_resize and do_normalize', 'test_crop_margin_all_white': 'test the crop_margin method on an all-white image to confirm no cropping occurs', 'test_crop_margin_centered_black_square': 'test the crop_margin method on a white image with a centered black square', 'test_align_long_axis_with_rotation': 'test the align_long_axis method to verify image rotation when height exceeds width', 'test_backends_equivalence': 'test pixel value equivalence across PIL and Torchvision backends for the Nougat image processor'}
```

## File: huggingface_transformers/tests/models/nougat/test_tokenization_nougat.py

Prompts

```
['test the NougatImageProcessingTest to verify image processor properties like do_resize and do_normalize', 'test the crop_margin method on an all-white image to confirm no cropping occurs', 'test the crop_margin method on a white image with a centered black square', 'test the align_long_axis method to verify image rotation when height exceeds width', 'test pixel value equivalence across PIL and Torchvision backends for the Nougat image processor', 'test the NougatTokenizer by tokenizing and decoding multilingual text with emojis and special characters', 'convert LaTeX equation tags, bold formatting, and URLs to markdown-compatible text using markdown_compatible', 'normalize flat list-like lines into properly indented multiline lists using normalize_list_like_lines', 'correct LaTeX table formatting by adding newlines around tabular environments using NougatTokenizer correct_tables', 'postprocess Nougat tokenizer output text with optional markdown fixing using post_process_single']
```

Usage

```
{'test_nougat_tokenizer': 'test the NougatTokenizer by tokenizing and decoding multilingual text with emojis and special characters', 'convert_markdown_compatible': 'convert LaTeX equation tags, bold formatting, and URLs to markdown-compatible text using markdown_compatible', 'normalize_list_lines': 'normalize flat list-like lines into properly indented multiline lists using normalize_list_like_lines', 'correct_latex_tables': 'correct LaTeX table formatting by adding newlines around tabular environments using NougatTokenizer correct_tables', 'postprocess_nougat_output': 'postprocess Nougat tokenizer output text with optional markdown fixing using post_process_single'}
```

