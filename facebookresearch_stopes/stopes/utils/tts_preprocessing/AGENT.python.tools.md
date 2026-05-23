# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/utils/tts_preprocessing/cleaners.py

Prompts

```
['clean English text by expanding numbers, abbreviations, and removing punctuation for TTS preprocessing', 'clean multilingual text supporting Chinese, Arabic, and English with language-specific normalization', 'apply a list of text cleaner functions to a pandas DataFrame column for batch processing', 'remove all substrings within parentheses or brackets from text including nested and full-width brackets', 'expand common English abbreviations like mr, dr, st, and co to their full spelled-out forms', 'normalize Chinese text by converting numbers, dates, money, and phone numbers to Chinese characters for TTS', 'convert Chinese numeral strings like 一百二十三 to Arabic numerals using chn2num', 'convert Arabic numeral strings like 123 to Chinese text using num2chn', 'normalize dates, money, telephone numbers, fractions, and percentages in Chinese text using NSWNormalizer', 'convert cardinal numbers to Chinese text and vice versa using the Cardinal class', 'split a text string into sentence fragments using boundary characters and language-specific word count limits', 'split text into fragments using custom boundary characters like question marks and periods', 'split multilingual text into sentence fragments with language-aware minimum and maximum word count thresholds', 'count the number of words in a text string with special handling for Chinese language code mixing', 'count words in Chinese text treating alphabetic tokens as one word and Chinese characters individually']
```

Usage

```
{'clean_eng_text': 'clean English text by expanding numbers, abbreviations, and removing punctuation for TTS preprocessing', 'clean_multilingual_text': 'clean multilingual text supporting Chinese, Arabic, and English with language-specific normalization', 'apply_cleaners_to_dataframe': 'apply a list of text cleaner functions to a pandas DataFrame column for batch processing', 'remove_parentheses': 'remove all substrings within parentheses or brackets from text including nested and full-width brackets', 'expand_abbreviations': 'expand common English abbreviations like mr, dr, st, and co to their full spelled-out forms'}
```

## File: facebookresearch_stopes/stopes/utils/tts_preprocessing/cmn.py

Prompts

```
['clean English text by expanding numbers, abbreviations, and removing punctuation for TTS preprocessing', 'clean multilingual text supporting Chinese, Arabic, and English with language-specific normalization', 'apply a list of text cleaner functions to a pandas DataFrame column for batch processing', 'remove all substrings within parentheses or brackets from text including nested and full-width brackets', 'expand common English abbreviations like mr, dr, st, and co to their full spelled-out forms', 'normalize Chinese text by converting numbers, dates, money, and phone numbers to Chinese characters for TTS', 'convert Chinese numeral strings like 一百二十三 to Arabic numerals using chn2num', 'convert Arabic numeral strings like 123 to Chinese text using num2chn', 'normalize dates, money, telephone numbers, fractions, and percentages in Chinese text using NSWNormalizer', 'convert cardinal numbers to Chinese text and vice versa using the Cardinal class', 'split a text string into sentence fragments using boundary characters and language-specific word count limits', 'split text into fragments using custom boundary characters like question marks and periods', 'split multilingual text into sentence fragments with language-aware minimum and maximum word count thresholds', 'count the number of words in a text string with special handling for Chinese language code mixing', 'count words in Chinese text treating alphabetic tokens as one word and Chinese characters individually']
```

Usage

```
{'normalize_chinese_text_for_tts': 'normalize Chinese text by converting numbers, dates, money, and phone numbers to Chinese characters for TTS', 'convert_chinese_numerals_to_arabic': 'convert Chinese numeral strings like 一百二十三 to Arabic numerals using chn2num', 'convert_arabic_to_chinese_text': 'convert Arabic numeral strings like 123 to Chinese text using num2chn', 'normalize_non_standard_words': 'normalize dates, money, telephone numbers, fractions, and percentages in Chinese text using NSWNormalizer', 'convert_cardinal_numbers_bidirectionally': 'convert cardinal numbers to Chinese text and vice versa using the Cardinal class'}
```

## File: facebookresearch_stopes/stopes/utils/tts_preprocessing/sentence_split.py

Prompts

```
['clean English text by expanding numbers, abbreviations, and removing punctuation for TTS preprocessing', 'clean multilingual text supporting Chinese, Arabic, and English with language-specific normalization', 'apply a list of text cleaner functions to a pandas DataFrame column for batch processing', 'remove all substrings within parentheses or brackets from text including nested and full-width brackets', 'expand common English abbreviations like mr, dr, st, and co to their full spelled-out forms', 'normalize Chinese text by converting numbers, dates, money, and phone numbers to Chinese characters for TTS', 'convert Chinese numeral strings like 一百二十三 to Arabic numerals using chn2num', 'convert Arabic numeral strings like 123 to Chinese text using num2chn', 'normalize dates, money, telephone numbers, fractions, and percentages in Chinese text using NSWNormalizer', 'convert cardinal numbers to Chinese text and vice versa using the Cardinal class', 'split a text string into sentence fragments using boundary characters and language-specific word count limits', 'split text into fragments using custom boundary characters like question marks and periods', 'split multilingual text into sentence fragments with language-aware minimum and maximum word count thresholds', 'count the number of words in a text string with special handling for Chinese language code mixing', 'count words in Chinese text treating alphabetic tokens as one word and Chinese characters individually']
```

Usage

```
{'split_sentence_text': 'split a text string into sentence fragments using boundary characters and language-specific word count limits', 'split_sentence_custom_boundaries': 'split text into fragments using custom boundary characters like question marks and periods', 'split_sentence_multilingual': 'split multilingual text into sentence fragments with language-aware minimum and maximum word count thresholds', 'get_num_words_text': 'count the number of words in a text string with special handling for Chinese language code mixing', 'get_num_words_chinese': 'count words in Chinese text treating alphabetic tokens as one word and Chinese characters individually'}
```

