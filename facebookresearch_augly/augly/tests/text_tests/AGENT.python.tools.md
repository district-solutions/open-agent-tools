# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/tests/text_tests/functional_unit_test.py

Prompts

```
['test encode_text to base64-encode all characters or a single word in a sentence', 'test encode_text to convert text to leetspeak by replacing letters with numbers', 'test insert_zero_width_chars to inject invisible Unicode characters between every character or word', 'test replace_fun_fonts to replace text with fancy Unicode font characters at word or char granularity', 'test simulate_typos to generate misspellings or character-mix typos in text for adversarial testing', 'run the unittest suite to test all augly text augmentation transforms', "test the Contractions transform to convert phrases like 'I would' into contractions like 'I'd'", 'test the SwapGenderedWords transform to swap gendered words like king/queen and son/daughter', 'test the tokenize function to split text into tokens handling apostrophes and special characters', 'test the detokenize function to rejoin a list of tokens back into a single string', 'test the split_words_on_whitespace function to separate words and their surrounding whitespace', 'test the rejoin_words_and_whitespace function to reconstruct original text from words and whitespace lists', 'run the UtilsTest unittest suite to verify all text augmentation utility functions work correctly']
```

Usage

```
{'test_encode_text_base64': 'test encode_text to base64-encode all characters or a single word in a sentence', 'test_encode_text_leetspeak': 'test encode_text to convert text to leetspeak by replacing letters with numbers', 'test_insert_zero_width_chars': 'test insert_zero_width_chars to inject invisible Unicode characters between every character or word', 'test_replace_fun_fonts': 'test replace_fun_fonts to replace text with fancy Unicode font characters at word or char granularity', 'test_simulate_typos': 'test simulate_typos to generate misspellings or character-mix typos in text for adversarial testing'}
```

## File: facebookresearch_augly/augly/tests/text_tests/transforms_unit_test.py

Prompts

```
['test encode_text to base64-encode all characters or a single word in a sentence', 'test encode_text to convert text to leetspeak by replacing letters with numbers', 'test insert_zero_width_chars to inject invisible Unicode characters between every character or word', 'test replace_fun_fonts to replace text with fancy Unicode font characters at word or char granularity', 'test simulate_typos to generate misspellings or character-mix typos in text for adversarial testing', 'run the unittest suite to test all augly text augmentation transforms', "test the Contractions transform to convert phrases like 'I would' into contractions like 'I'd'", 'test the SwapGenderedWords transform to swap gendered words like king/queen and son/daughter', 'test the tokenize function to split text into tokens handling apostrophes and special characters', 'test the detokenize function to rejoin a list of tokens back into a single string', 'test the split_words_on_whitespace function to separate words and their surrounding whitespace', 'test the rejoin_words_and_whitespace function to reconstruct original text from words and whitespace lists', 'run the UtilsTest unittest suite to verify all text augmentation utility functions work correctly']
```

Usage

```
{'test_text_augmentation_transforms': 'run the unittest suite to test all augly text augmentation transforms', 'test_contractions_transform': "test the Contractions transform to convert phrases like 'I would' into contractions like 'I'd'", 'test_encode_text_base64': 'test the EncodeTextTransform to encode text to base64 at sentence or word granularity', 'test_simulate_typos': 'test the SimulateTypos transform to introduce random typos into text with configurable probability', 'test_swap_gendered_words': 'test the SwapGenderedWords transform to swap gendered words like king/queen and son/daughter'}
```

## File: facebookresearch_augly/augly/tests/text_tests/utils_test.py

Prompts

```
['test encode_text to base64-encode all characters or a single word in a sentence', 'test encode_text to convert text to leetspeak by replacing letters with numbers', 'test insert_zero_width_chars to inject invisible Unicode characters between every character or word', 'test replace_fun_fonts to replace text with fancy Unicode font characters at word or char granularity', 'test simulate_typos to generate misspellings or character-mix typos in text for adversarial testing', 'run the unittest suite to test all augly text augmentation transforms', "test the Contractions transform to convert phrases like 'I would' into contractions like 'I'd'", 'test the SwapGenderedWords transform to swap gendered words like king/queen and son/daughter', 'test the tokenize function to split text into tokens handling apostrophes and special characters', 'test the detokenize function to rejoin a list of tokens back into a single string', 'test the split_words_on_whitespace function to separate words and their surrounding whitespace', 'test the rejoin_words_and_whitespace function to reconstruct original text from words and whitespace lists', 'run the UtilsTest unittest suite to verify all text augmentation utility functions work correctly']
```

Usage

```
{'test_tokenize': 'test the tokenize function to split text into tokens handling apostrophes and special characters', 'test_detokenize': 'test the detokenize function to rejoin a list of tokens back into a single string', 'test_split_words_on_whitespace': 'test the split_words_on_whitespace function to separate words and their surrounding whitespace', 'test_rejoin_words_and_whitespace': 'test the rejoin_words_and_whitespace function to reconstruct original text from words and whitespace lists', 'run_utils_test': 'run the UtilsTest unittest suite to verify all text augmentation utility functions work correctly'}
```

