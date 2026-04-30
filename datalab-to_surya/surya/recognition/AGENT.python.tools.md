# Agent Python Tools

- repo: datalab-to/surya
- repo_uri: https://github.com/datalab-to/surya

## File: datalab-to_surya/surya/recognition/postprocessing.py

Prompts

```
['truncate repeated trailing substrings from a text string with a minimum repetition length', 'extract tag names from a list of proposed HTML-like tag strings', 'cleanup math blocks by stripping inner HTML tags while preserving LaTeX math markup', 'fix unbalanced HTML-like tags in a list of TextChar objects by appending missing closing tags', 'match HTML-like opening and closing tags with an optional self-closing slash', 'create a BaseChar with text, confidence, and polygon bounding box coordinates', 'create a TextChar with text, confidence, and bbox_valid flag for individual character recognition', 'create a TextWord with text, confidence, and bbox_valid flag for word-level recognition', 'create a TextLine with text, confidence, a list of TextChar objects, and optional TextWord list', 'create an OCRResult containing a list of TextLine objects and image bounding box coordinates', 'unwrap math tags from a short string and return the inner text content', 'filter blacklisted HTML tags from a list of text characters and return cleaned characters', 'clean math tags from HTML by stripping unwanted inner tags and removing orphan closing tags', 'sort a list of text lines or dicts in reading order by vertical grouping then horizontal position', 'build a list of text words from a list of text characters using bounding box merging and line fitting']
```

Usage

```
{'truncate_repetitions': 'truncate repeated trailing substrings from a text string with a minimum repetition length', 'extract_tags': 'extract tag names from a list of proposed HTML-like tag strings', 'cleanup_math': 'cleanup math blocks by stripping inner HTML tags while preserving LaTeX math markup', 'fix_unbalanced_tags': 'fix unbalanced HTML-like tags in a list of TextChar objects by appending missing closing tags', 'tag_pattern': 'match HTML-like opening and closing tags with an optional self-closing slash'}
```

## File: datalab-to_surya/surya/recognition/schema.py

Prompts

```
['truncate repeated trailing substrings from a text string with a minimum repetition length', 'extract tag names from a list of proposed HTML-like tag strings', 'cleanup math blocks by stripping inner HTML tags while preserving LaTeX math markup', 'fix unbalanced HTML-like tags in a list of TextChar objects by appending missing closing tags', 'match HTML-like opening and closing tags with an optional self-closing slash', 'create a BaseChar with text, confidence, and polygon bounding box coordinates', 'create a TextChar with text, confidence, and bbox_valid flag for individual character recognition', 'create a TextWord with text, confidence, and bbox_valid flag for word-level recognition', 'create a TextLine with text, confidence, a list of TextChar objects, and optional TextWord list', 'create an OCRResult containing a list of TextLine objects and image bounding box coordinates', 'unwrap math tags from a short string and return the inner text content', 'filter blacklisted HTML tags from a list of text characters and return cleaned characters', 'clean math tags from HTML by stripping unwanted inner tags and removing orphan closing tags', 'sort a list of text lines or dicts in reading order by vertical grouping then horizontal position', 'build a list of text words from a list of text characters using bounding box merging and line fitting']
```

Usage

```
{'create_BaseChar': 'create a BaseChar with text, confidence, and polygon bounding box coordinates', 'create_TextChar': 'create a TextChar with text, confidence, and bbox_valid flag for individual character recognition', 'create_TextWord': 'create a TextWord with text, confidence, and bbox_valid flag for word-level recognition', 'create_TextLine': 'create a TextLine with text, confidence, a list of TextChar objects, and optional TextWord list', 'create_OCRResult': 'create an OCRResult containing a list of TextLine objects and image bounding box coordinates'}
```

## File: datalab-to_surya/surya/recognition/util.py

Prompts

```
['truncate repeated trailing substrings from a text string with a minimum repetition length', 'extract tag names from a list of proposed HTML-like tag strings', 'cleanup math blocks by stripping inner HTML tags while preserving LaTeX math markup', 'fix unbalanced HTML-like tags in a list of TextChar objects by appending missing closing tags', 'match HTML-like opening and closing tags with an optional self-closing slash', 'create a BaseChar with text, confidence, and polygon bounding box coordinates', 'create a TextChar with text, confidence, and bbox_valid flag for individual character recognition', 'create a TextWord with text, confidence, and bbox_valid flag for word-level recognition', 'create a TextLine with text, confidence, a list of TextChar objects, and optional TextWord list', 'create an OCRResult containing a list of TextLine objects and image bounding box coordinates', 'unwrap math tags from a short string and return the inner text content', 'filter blacklisted HTML tags from a list of text characters and return cleaned characters', 'clean math tags from HTML by stripping unwanted inner tags and removing orphan closing tags', 'sort a list of text lines or dicts in reading order by vertical grouping then horizontal position', 'build a list of text words from a list of text characters using bounding box merging and line fitting']
```

Usage

```
{'unwrap_math_text': 'unwrap math tags from a short string and return the inner text content', 'filter_blacklist_tags_chars': 'filter blacklisted HTML tags from a list of text characters and return cleaned characters', 'clean_math_tags_html': 'clean math tags from HTML by stripping unwanted inner tags and removing orphan closing tags', 'sort_text_lines_reading_order': 'sort a list of text lines or dicts in reading order by vertical grouping then horizontal position', 'build_words_from_chars': 'build a list of text words from a list of text characters using bounding box merging and line fitting'}
```

