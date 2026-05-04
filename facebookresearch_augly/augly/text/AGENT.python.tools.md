# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/text/functional.py

Prompts

```
['simulate typos in text using keyboard distance, misspellings, or character swaps', 'change the case of random characters or words in text to upper, lower, or title', 'replace letters in text with visually similar unicode characters for obfuscation', 'swap gendered words in text using a provided mapping dictionary', 'encode text using base64 or leetspeak at character, word, or full text granularity', 'compute the intensity score for any named text augmentation function by passing its name and kwargs', 'calculate the intensity score for base64 or leetspeak text encoding augmentation with given granularity and probability', 'compute the intensity score for replacing similar characters in text using character and word probability parameters', 'calculate the intensity score for text insertion augmentation based on the number of insertions', 'compute the intensity score for simulating typos in text using character and word probability and max parameters', 'create a SimulateTypos transform to add misspellings and keyboard typos to text data', 'build a ChangeCase transform to randomly change the case of words or characters in text', 'test the ReplaceSimilarChars transform to replace letters with visually similar characters', 'create a SwapGenderedWords transform to replace gendered words using a provided mapping dictionary', 'build an InsertZeroWidthChars transform to insert invisible zero-width characters into text', 'build a python module that extracts function kwargs from metadata and local arguments for text augmentation', 'create a python function that appends augmentation metadata with intensity scores to a tracking list', 'load a gendered words mapping from a JSON file or dict for text augmentation', 'review the get_func_kwargs function to understand how it filters and merges kwargs for augmentations', 'summarize the get_metadata function and how it computes intensity for text augmentation operations']
```

Usage

```
{'simulate_typos': 'simulate typos in text using keyboard distance, misspellings, or character swaps', 'change_case': 'change the case of random characters or words in text to upper, lower, or title', 'replace_similar_unicode_chars': 'replace letters in text with visually similar unicode characters for obfuscation', 'swap_gendered_words': 'swap gendered words in text using a provided mapping dictionary', 'encode_text': 'encode text using base64 or leetspeak at character, word, or full text granularity'}
```

## File: facebookresearch_augly/augly/text/intensity.py

Prompts

```
['simulate typos in text using keyboard distance, misspellings, or character swaps', 'change the case of random characters or words in text to upper, lower, or title', 'replace letters in text with visually similar unicode characters for obfuscation', 'swap gendered words in text using a provided mapping dictionary', 'encode text using base64 or leetspeak at character, word, or full text granularity', 'compute the intensity score for any named text augmentation function by passing its name and kwargs', 'calculate the intensity score for base64 or leetspeak text encoding augmentation with given granularity and probability', 'compute the intensity score for replacing similar characters in text using character and word probability parameters', 'calculate the intensity score for text insertion augmentation based on the number of insertions', 'compute the intensity score for simulating typos in text using character and word probability and max parameters', 'create a SimulateTypos transform to add misspellings and keyboard typos to text data', 'build a ChangeCase transform to randomly change the case of words or characters in text', 'test the ReplaceSimilarChars transform to replace letters with visually similar characters', 'create a SwapGenderedWords transform to replace gendered words using a provided mapping dictionary', 'build an InsertZeroWidthChars transform to insert invisible zero-width characters into text', 'build a python module that extracts function kwargs from metadata and local arguments for text augmentation', 'create a python function that appends augmentation metadata with intensity scores to a tracking list', 'load a gendered words mapping from a JSON file or dict for text augmentation', 'review the get_func_kwargs function to understand how it filters and merges kwargs for augmentations', 'summarize the get_metadata function and how it computes intensity for text augmentation operations']
```

Usage

```
{'apply_lambda_intensity': 'compute the intensity score for any named text augmentation function by passing its name and kwargs', 'encode_text_intensity': 'calculate the intensity score for base64 or leetspeak text encoding augmentation with given granularity and probability', 'replace_similar_chars_intensity': 'compute the intensity score for replacing similar characters in text using character and word probability parameters', 'insert_text_intensity': 'calculate the intensity score for text insertion augmentation based on the number of insertions', 'simulate_typos_intensity': 'compute the intensity score for simulating typos in text using character and word probability and max parameters'}
```

## File: facebookresearch_augly/augly/text/transforms.py

Prompts

```
['simulate typos in text using keyboard distance, misspellings, or character swaps', 'change the case of random characters or words in text to upper, lower, or title', 'replace letters in text with visually similar unicode characters for obfuscation', 'swap gendered words in text using a provided mapping dictionary', 'encode text using base64 or leetspeak at character, word, or full text granularity', 'compute the intensity score for any named text augmentation function by passing its name and kwargs', 'calculate the intensity score for base64 or leetspeak text encoding augmentation with given granularity and probability', 'compute the intensity score for replacing similar characters in text using character and word probability parameters', 'calculate the intensity score for text insertion augmentation based on the number of insertions', 'compute the intensity score for simulating typos in text using character and word probability and max parameters', 'create a SimulateTypos transform to add misspellings and keyboard typos to text data', 'build a ChangeCase transform to randomly change the case of words or characters in text', 'test the ReplaceSimilarChars transform to replace letters with visually similar characters', 'create a SwapGenderedWords transform to replace gendered words using a provided mapping dictionary', 'build an InsertZeroWidthChars transform to insert invisible zero-width characters into text', 'build a python module that extracts function kwargs from metadata and local arguments for text augmentation', 'create a python function that appends augmentation metadata with intensity scores to a tracking list', 'load a gendered words mapping from a JSON file or dict for text augmentation', 'review the get_func_kwargs function to understand how it filters and merges kwargs for augmentations', 'summarize the get_metadata function and how it computes intensity for text augmentation operations']
```

Usage

```
{'create_simulate_typos_transform': 'create a SimulateTypos transform to add misspellings and keyboard typos to text data', 'build_change_case_transform': 'build a ChangeCase transform to randomly change the case of words or characters in text', 'test_replace_similar_chars': 'test the ReplaceSimilarChars transform to replace letters with visually similar characters', 'create_swap_gendered_words_transform': 'create a SwapGenderedWords transform to replace gendered words using a provided mapping dictionary', 'build_insert_zero_width_chars': 'build an InsertZeroWidthChars transform to insert invisible zero-width characters into text'}
```

## File: facebookresearch_augly/augly/text/utils.py

Prompts

```
['simulate typos in text using keyboard distance, misspellings, or character swaps', 'change the case of random characters or words in text to upper, lower, or title', 'replace letters in text with visually similar unicode characters for obfuscation', 'swap gendered words in text using a provided mapping dictionary', 'encode text using base64 or leetspeak at character, word, or full text granularity', 'compute the intensity score for any named text augmentation function by passing its name and kwargs', 'calculate the intensity score for base64 or leetspeak text encoding augmentation with given granularity and probability', 'compute the intensity score for replacing similar characters in text using character and word probability parameters', 'calculate the intensity score for text insertion augmentation based on the number of insertions', 'compute the intensity score for simulating typos in text using character and word probability and max parameters', 'create a SimulateTypos transform to add misspellings and keyboard typos to text data', 'build a ChangeCase transform to randomly change the case of words or characters in text', 'test the ReplaceSimilarChars transform to replace letters with visually similar characters', 'create a SwapGenderedWords transform to replace gendered words using a provided mapping dictionary', 'build an InsertZeroWidthChars transform to insert invisible zero-width characters into text', 'build a python module that extracts function kwargs from metadata and local arguments for text augmentation', 'create a python function that appends augmentation metadata with intensity scores to a tracking list', 'load a gendered words mapping from a JSON file or dict for text augmentation', 'review the get_func_kwargs function to understand how it filters and merges kwargs for augmentations', 'summarize the get_metadata function and how it computes intensity for text augmentation operations']
```

Usage

```
{'get_func_kwargs': 'build a python module that extracts function kwargs from metadata and local arguments for text augmentation', 'get_metadata': 'create a python function that appends augmentation metadata with intensity scores to a tracking list', 'get_gendered_words_mapping': 'load a gendered words mapping from a JSON file or dict for text augmentation', 'review_get_func_kwargs': 'review the get_func_kwargs function to understand how it filters and merges kwargs for augmentations', 'summarize_get_metadata': 'summarize the get_metadata function and how it computes intensity for text augmentation operations'}
```

