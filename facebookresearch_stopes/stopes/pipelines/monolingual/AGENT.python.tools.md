# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/pipelines/monolingual/monolingual_line_processor.py

Prompts

```
['build a monolingual text processing pipeline that splits sentences, normalizes text, and filters by language and script', 'create a FilterConfig dataclass to set min and max character limits, punctuation ratio, and space ratio thresholds for text filtering', 'create a LIDConfig dataclass to configure language identification model paths, dates, and probability thresholds', 'use SentenceSplitClean to split text into sentences, apply Moses normalization, and normalize Unicode characters', 'use FilterLID to filter sentences by character quality, script prediction, and language identification with configurable thresholds', 'test SentenceSplitClean with English text to split and clean sentences using default algorithm', 'test SentenceSplitClean with Chinese text to split and clean sentences using default algorithm', 'test SentenceSplitClean with Thai text to split and clean sentences using default algorithm', 'test SentenceSplitClean with Japanese text to split and clean sentences using default algorithm', 'test SentenceSplitClean with Tibetan, Urdu, Armenian, or Georgian text to split and clean sentences']
```

Usage

```
{'build_monolingual_pipeline': 'build a monolingual text processing pipeline that splits sentences, normalizes text, and filters by language and script', 'create_FilterConfig': 'create a FilterConfig dataclass to set min and max character limits, punctuation ratio, and space ratio thresholds for text filtering', 'create_LIDConfig': 'create a LIDConfig dataclass to configure language identification model paths, dates, and probability thresholds', 'use_SentenceSplitClean': 'use SentenceSplitClean to split text into sentences, apply Moses normalization, and normalize Unicode characters', 'use_FilterLID': 'use FilterLID to filter sentences by character quality, script prediction, and language identification with configurable thresholds'}
```

## File: facebookresearch_stopes/stopes/pipelines/monolingual/test_mono.py

Prompts

```
['build a monolingual text processing pipeline that splits sentences, normalizes text, and filters by language and script', 'create a FilterConfig dataclass to set min and max character limits, punctuation ratio, and space ratio thresholds for text filtering', 'create a LIDConfig dataclass to configure language identification model paths, dates, and probability thresholds', 'use SentenceSplitClean to split text into sentences, apply Moses normalization, and normalize Unicode characters', 'use FilterLID to filter sentences by character quality, script prediction, and language identification with configurable thresholds', 'test SentenceSplitClean with English text to split and clean sentences using default algorithm', 'test SentenceSplitClean with Chinese text to split and clean sentences using default algorithm', 'test SentenceSplitClean with Thai text to split and clean sentences using default algorithm', 'test SentenceSplitClean with Japanese text to split and clean sentences using default algorithm', 'test SentenceSplitClean with Tibetan, Urdu, Armenian, or Georgian text to split and clean sentences']
```

Usage

```
{'test_sentence_split_clean_eng': 'test SentenceSplitClean with English text to split and clean sentences using default algorithm', 'test_sentence_split_clean_zho': 'test SentenceSplitClean with Chinese text to split and clean sentences using default algorithm', 'test_sentence_split_clean_tha': 'test SentenceSplitClean with Thai text to split and clean sentences using default algorithm', 'test_sentence_split_clean_jpn': 'test SentenceSplitClean with Japanese text to split and clean sentences using default algorithm', 'test_sentence_split_clean_multi_lang': 'test SentenceSplitClean with Tibetan, Urdu, Armenian, or Georgian text to split and clean sentences'}
```

