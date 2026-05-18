# Agent Python Tools

- repo: facebookresearch/npm
- repo_uri: https://github.com/facebookresearch/npm

## File: facebookresearch_npm/task/create_lama_uhn.py

Prompts

```
['run the script to create LAMA-UHN by filtering easy-to-guess questions from a source directory', 'run the StringMatchFilter to remove queries where the object label is a substring of the subject label', 'run the PersonNameFilter using BERT masked language modeling to detect name-based reasoning queries', 'review the LAMAUHNFilter base class and its match and filter methods for custom filter implementations', 'review the PersonNameFilter get_top_k_for_name method that uses BERT to predict top-k tokens for a name template', 'load data for NLP tasks like triviaqa, yahoo, amazon, rte, or sst2 from a given data directory', 'load a fuzzy verbalizer mapping from a txt or yahoo.json file for zero-shot classification', "detokenize tokenized text by reattaching punctuation and fixing contractions like n't", 'load the TriviaQA validation dataset with templated questions and answer aliases', 'load the KAMEL knowledge graph dataset from a data directory using question templates', 'normalize an answer string by lowering text and removing punctuation articles and extra whitespace', 'normalize two answer strings to compare them ignoring punctuation articles and whitespace differences', 'normalize an answer string by removing articles like a an and the from the text', 'normalize an answer string by stripping all punctuation characters from the text', 'normalize an answer string by collapsing multiple whitespace characters into single spaces']
```

Usage

```
{'run_create_lama_uhn': 'run the script to create LAMA-UHN by filtering easy-to-guess questions from a source directory', 'run_string_match_filter': 'run the StringMatchFilter to remove queries where the object label is a substring of the subject label', 'run_person_name_filter': 'run the PersonNameFilter using BERT masked language modeling to detect name-based reasoning queries', 'review_LAMAUHNFilter': 'review the LAMAUHNFilter base class and its match and filter methods for custom filter implementations', 'review_PersonNameFilter_get_top_k_for_name': 'review the PersonNameFilter get_top_k_for_name method that uses BERT to predict top-k tokens for a name template'}
```

## File: facebookresearch_npm/task/load_data.py

Prompts

```
['run the script to create LAMA-UHN by filtering easy-to-guess questions from a source directory', 'run the StringMatchFilter to remove queries where the object label is a substring of the subject label', 'run the PersonNameFilter using BERT masked language modeling to detect name-based reasoning queries', 'review the LAMAUHNFilter base class and its match and filter methods for custom filter implementations', 'review the PersonNameFilter get_top_k_for_name method that uses BERT to predict top-k tokens for a name template', 'load data for NLP tasks like triviaqa, yahoo, amazon, rte, or sst2 from a given data directory', 'load a fuzzy verbalizer mapping from a txt or yahoo.json file for zero-shot classification', "detokenize tokenized text by reattaching punctuation and fixing contractions like n't", 'load the TriviaQA validation dataset with templated questions and answer aliases', 'load the KAMEL knowledge graph dataset from a data directory using question templates', 'normalize an answer string by lowering text and removing punctuation articles and extra whitespace', 'normalize two answer strings to compare them ignoring punctuation articles and whitespace differences', 'normalize an answer string by removing articles like a an and the from the text', 'normalize an answer string by stripping all punctuation characters from the text', 'normalize an answer string by collapsing multiple whitespace characters into single spaces']
```

Usage

```
{'load_data': 'load data for NLP tasks like triviaqa, yahoo, amazon, rte, or sst2 from a given data directory', 'load_fuzzy_verbalizer': 'load a fuzzy verbalizer mapping from a txt or yahoo.json file for zero-shot classification', 'detokenize': "detokenize tokenized text by reattaching punctuation and fixing contractions like n't", 'load_triviaqa': 'load the TriviaQA validation dataset with templated questions and answer aliases', 'load_kamel': 'load the KAMEL knowledge graph dataset from a data directory using question templates'}
```

## File: facebookresearch_npm/task/utils_eval.py

Prompts

```
['run the script to create LAMA-UHN by filtering easy-to-guess questions from a source directory', 'run the StringMatchFilter to remove queries where the object label is a substring of the subject label', 'run the PersonNameFilter using BERT masked language modeling to detect name-based reasoning queries', 'review the LAMAUHNFilter base class and its match and filter methods for custom filter implementations', 'review the PersonNameFilter get_top_k_for_name method that uses BERT to predict top-k tokens for a name template', 'load data for NLP tasks like triviaqa, yahoo, amazon, rte, or sst2 from a given data directory', 'load a fuzzy verbalizer mapping from a txt or yahoo.json file for zero-shot classification', "detokenize tokenized text by reattaching punctuation and fixing contractions like n't", 'load the TriviaQA validation dataset with templated questions and answer aliases', 'load the KAMEL knowledge graph dataset from a data directory using question templates', 'normalize an answer string by lowering text and removing punctuation articles and extra whitespace', 'normalize two answer strings to compare them ignoring punctuation articles and whitespace differences', 'normalize an answer string by removing articles like a an and the from the text', 'normalize an answer string by stripping all punctuation characters from the text', 'normalize an answer string by collapsing multiple whitespace characters into single spaces']
```

Usage

```
{'normalize_answer_text': 'normalize an answer string by lowering text and removing punctuation articles and extra whitespace', 'normalize_answer_for_evaluation': 'normalize two answer strings to compare them ignoring punctuation articles and whitespace differences', 'normalize_answer_remove_articles': 'normalize an answer string by removing articles like a an and the from the text', 'normalize_answer_remove_punctuation': 'normalize an answer string by stripping all punctuation characters from the text', 'normalize_answer_whitespace_fix': 'normalize an answer string by collapsing multiple whitespace characters into single spaces'}
```

