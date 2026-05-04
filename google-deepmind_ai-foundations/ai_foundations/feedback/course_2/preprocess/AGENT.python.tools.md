# Agent Python Tools

- repo: google-deepmind/ai-foundations
- repo_uri: https://github.com/google-deepmind/ai-foundations

## File: google-deepmind_ai-foundations/ai_foundations/feedback/course_2/preprocess/test_clean_html.py

Prompts

```
["test a learner's clean_html implementation that strips HTML tags and converts entities", "compare a student's HTML cleaning output against the expected gold result string", 'normalize whitespace in a string by collapsing consecutive spaces and trimming edges', 'extract Unicode-aware word tokens from a string using regex pattern matching', 'HTML-escape special characters like ampersand, less than, and greater than in text', "test a learner's clean_unicode implementation against a sample text with special characters and emojis", "compare a student's cleaned text output against the expected gold text and get feedback", 'extract alphanumeric word tokens from a string using regex with unicode support', 'review the compare_unicode_result function logic for checking special characters, missing tokens, and punctuation differences']
```

Usage

```
{'test_clean_html_function': "test a learner's clean_html implementation that strips HTML tags and converts entities", 'compare_html_result': "compare a student's HTML cleaning output against the expected gold result string", 'normalize_spaces': 'normalize whitespace in a string by collapsing consecutive spaces and trimming edges', 'tokenize_text': 'extract Unicode-aware word tokens from a string using regex pattern matching', 'html_escape_text': 'HTML-escape special characters like ampersand, less than, and greater than in text'}
```

## File: google-deepmind_ai-foundations/ai_foundations/feedback/course_2/preprocess/test_clean_unicode.py

Prompts

```
["test a learner's clean_html implementation that strips HTML tags and converts entities", "compare a student's HTML cleaning output against the expected gold result string", 'normalize whitespace in a string by collapsing consecutive spaces and trimming edges', 'extract Unicode-aware word tokens from a string using regex pattern matching', 'HTML-escape special characters like ampersand, less than, and greater than in text', "test a learner's clean_unicode implementation against a sample text with special characters and emojis", "compare a student's cleaned text output against the expected gold text and get feedback", 'extract alphanumeric word tokens from a string using regex with unicode support', 'review the compare_unicode_result function logic for checking special characters, missing tokens, and punctuation differences']
```

Usage

```
{'test_clean_unicode_function': "test a learner's clean_unicode implementation against a sample text with special characters and emojis", 'compare_unicode_result': "compare a student's cleaned text output against the expected gold text and get feedback", 'normalize_spaces': 'normalize whitespace in a string by collapsing multiple spaces and trimming leading or trailing whitespace', 'extract_tokens': 'extract alphanumeric word tokens from a string using regex with unicode support', 'review_compare_unicode_result': 'review the compare_unicode_result function logic for checking special characters, missing tokens, and punctuation differences'}
```

