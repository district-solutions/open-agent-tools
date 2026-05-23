# Agent Python Tools

- repo: facebookresearch/reasonir
- repo_uri: https://github.com/facebookresearch/reasonir

## File: facebookresearch_reasonir/synthetic_data_generation/document_filters/basic_filters.py

Prompts

```
['run the white_space_length_filter function to check if a document has at least 20 words', 'test the white_space_length_filter function with a short document that has fewer than 20 words', 'refactor the white_space_length_filter to use regex instead of split for more accurate word counting', 'review the white_space_length_filter function and its default min_words parameter of 20', 'summarize the white_space_length_filter rule-based document filtering logic for synthetic data generation', 'filter a list of document passages using the fineweb-edu-classifier model and return quality scores', 'score a single text passage with the fineweb-edu-classifier and return its quality score', 'batch score multiple text passages with the fineweb-edu-classifier and return a list of scores', 'review the fineweb_quality_filter function to understand how it scores passages using the HuggingFaceTB/fineweb-edu-classifier model', 'refactor the fineweb_quality_filter function to return the result dict with text, score, and int_score instead of raw scores']
```

Usage

```
{'run_white_space_length_filter': 'run the white_space_length_filter function to check if a document has at least 20 words', 'test_white_space_length_filter': 'test the white_space_length_filter function with a short document that has fewer than 20 words', 'refactor_white_space_length_filter': 'refactor the white_space_length_filter to use regex instead of split for more accurate word counting', 'review_white_space_length_filter': 'review the white_space_length_filter function and its default min_words parameter of 20', 'summarize_white_space_length_filter': 'summarize the white_space_length_filter rule-based document filtering logic for synthetic data generation'}
```

## File: facebookresearch_reasonir/synthetic_data_generation/document_filters/fineweb_edu_filter.py

Prompts

```
['run the white_space_length_filter function to check if a document has at least 20 words', 'test the white_space_length_filter function with a short document that has fewer than 20 words', 'refactor the white_space_length_filter to use regex instead of split for more accurate word counting', 'review the white_space_length_filter function and its default min_words parameter of 20', 'summarize the white_space_length_filter rule-based document filtering logic for synthetic data generation', 'filter a list of document passages using the fineweb-edu-classifier model and return quality scores', 'score a single text passage with the fineweb-edu-classifier and return its quality score', 'batch score multiple text passages with the fineweb-edu-classifier and return a list of scores', 'review the fineweb_quality_filter function to understand how it scores passages using the HuggingFaceTB/fineweb-edu-classifier model', 'refactor the fineweb_quality_filter function to return the result dict with text, score, and int_score instead of raw scores']
```

Usage

```
{'filter_document_quality': 'filter a list of document passages using the fineweb-edu-classifier model and return quality scores', 'score_single_passage': 'score a single text passage with the fineweb-edu-classifier and return its quality score', 'batch_score_passages': 'batch score multiple text passages with the fineweb-edu-classifier and return a list of scores', 'review_fineweb_quality_filter': 'review the fineweb_quality_filter function to understand how it scores passages using the HuggingFaceTB/fineweb-edu-classifier model', 'refactor_fineweb_quality_filter': 'refactor the fineweb_quality_filter function to return the result dict with text, score, and int_score instead of raw scores'}
```

