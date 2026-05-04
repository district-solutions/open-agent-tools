# Agent Python Tools

- repo: facebookresearch/eli5
- repo_uri: https://github.com/facebookresearch/eli5

## File: facebookresearch_eli5/data_creation/data_utils.py

Prompts

```
['use word_url_tokenize to tokenize text with spaCy while extracting and replacing URLs with placeholders', 'use sentence_split to split tokenized text into sentences with a configurable maximum word length per sentence', 'use tf_idf_vec_uni to compute a normalized sparse TF-IDF vector for a sentence using unigram features', 'use tf_idf_vec to compute a normalized sparse TF-IDF vector for a sentence using unigram and bigram features', 'use tf_idf_dist to compute the dot product between two pre-computed sparse TF-IDF vectors for similarity scoring', 'run the script to download Reddit submissions and comments from PushShift dumps for specified subreddits and date ranges', 'create a function that scrapes PushShift directory pages to collect monthly dump URLs for submissions or comments', 'build a function that downloads compressed Reddit dump files, decompresses them, and filters entries by subreddit names', 'create a function that validates top-level Reddit comments by checking body length, author, and parent ID', 'run post-processing on Reddit QA dictionaries to clean ELI5 titles, deduplicate comments, and sort by score', 'run the python module to select TF-IDF ranked sentences from Reddit ELI5 documents for a given slice', 'select relevant paragraphs from documents using TF-IDF similarity to a question with context window expansion', 'create a QA example dictionary with question, document, and answer fields from Reddit ELI5 data', 'review the select_pars function that scores and ranks document sentences by TF-IDF distance to a question', 'refactor the main function to support loading QA data, documents, and word counts for processing ELI5 slices']
```

Usage

```
{'tokenize_text_with_url_extraction': 'use word_url_tokenize to tokenize text with spaCy while extracting and replacing URLs with placeholders', 'split_text_into_sentences': 'use sentence_split to split tokenized text into sentences with a configurable maximum word length per sentence', 'compute_unigram_tfidf_vector': 'use tf_idf_vec_uni to compute a normalized sparse TF-IDF vector for a sentence using unigram features', 'compute_bigram_tfidf_vector': 'use tf_idf_vec to compute a normalized sparse TF-IDF vector for a sentence using unigram and bigram features', 'calculate_tfidf_similarity': 'use tf_idf_dist to compute the dot product between two pre-computed sparse TF-IDF vectors for similarity scoring'}
```

## File: facebookresearch_eli5/data_creation/download_reddit_qalist.py

Prompts

```
['use word_url_tokenize to tokenize text with spaCy while extracting and replacing URLs with placeholders', 'use sentence_split to split tokenized text into sentences with a configurable maximum word length per sentence', 'use tf_idf_vec_uni to compute a normalized sparse TF-IDF vector for a sentence using unigram features', 'use tf_idf_vec to compute a normalized sparse TF-IDF vector for a sentence using unigram and bigram features', 'use tf_idf_dist to compute the dot product between two pre-computed sparse TF-IDF vectors for similarity scoring', 'run the script to download Reddit submissions and comments from PushShift dumps for specified subreddits and date ranges', 'create a function that scrapes PushShift directory pages to collect monthly dump URLs for submissions or comments', 'build a function that downloads compressed Reddit dump files, decompresses them, and filters entries by subreddit names', 'create a function that validates top-level Reddit comments by checking body length, author, and parent ID', 'run post-processing on Reddit QA dictionaries to clean ELI5 titles, deduplicate comments, and sort by score', 'run the python module to select TF-IDF ranked sentences from Reddit ELI5 documents for a given slice', 'select relevant paragraphs from documents using TF-IDF similarity to a question with context window expansion', 'create a QA example dictionary with question, document, and answer fields from Reddit ELI5 data', 'review the select_pars function that scores and ranks document sentences by TF-IDF distance to a question', 'refactor the main function to support loading QA data, documents, and word counts for processing ELI5 slices']
```

Usage

```
{'download_reddit_qa_pairs': 'run the script to download Reddit submissions and comments from PushShift dumps for specified subreddits and date ranges', 'gather_dump_urls': 'create a function that scrapes PushShift directory pages to collect monthly dump URLs for submissions or comments', 'download_and_process': 'build a function that downloads compressed Reddit dump files, decompresses them, and filters entries by subreddit names', 'valid_comment': 'create a function that validates top-level Reddit comments by checking body length, author, and parent ID', 'post_process': 'run post-processing on Reddit QA dictionaries to clean ELI5 titles, deduplicate comments, and sort by score'}
```

## File: facebookresearch_eli5/data_creation/select_sentences_tfidf.py

Prompts

```
['use word_url_tokenize to tokenize text with spaCy while extracting and replacing URLs with placeholders', 'use sentence_split to split tokenized text into sentences with a configurable maximum word length per sentence', 'use tf_idf_vec_uni to compute a normalized sparse TF-IDF vector for a sentence using unigram features', 'use tf_idf_vec to compute a normalized sparse TF-IDF vector for a sentence using unigram and bigram features', 'use tf_idf_dist to compute the dot product between two pre-computed sparse TF-IDF vectors for similarity scoring', 'run the script to download Reddit submissions and comments from PushShift dumps for specified subreddits and date ranges', 'create a function that scrapes PushShift directory pages to collect monthly dump URLs for submissions or comments', 'build a function that downloads compressed Reddit dump files, decompresses them, and filters entries by subreddit names', 'create a function that validates top-level Reddit comments by checking body length, author, and parent ID', 'run post-processing on Reddit QA dictionaries to clean ELI5 titles, deduplicate comments, and sort by score', 'run the python module to select TF-IDF ranked sentences from Reddit ELI5 documents for a given slice', 'select relevant paragraphs from documents using TF-IDF similarity to a question with context window expansion', 'create a QA example dictionary with question, document, and answer fields from Reddit ELI5 data', 'review the select_pars function that scores and ranks document sentences by TF-IDF distance to a question', 'refactor the main function to support loading QA data, documents, and word counts for processing ELI5 slices']
```

Usage

```
{'run_select_sentences_tfidf': 'run the python module to select TF-IDF ranked sentences from Reddit ELI5 documents for a given slice', 'select_pars_function': 'select relevant paragraphs from documents using TF-IDF similarity to a question with context window expansion', 'make_example_function': 'create a QA example dictionary with question, document, and answer fields from Reddit ELI5 data', 'review_select_pars': 'review the select_pars function that scores and ranks document sentences by TF-IDF distance to a question', 'refactor_main': 'refactor the main function to support loading QA data, documents, and word counts for processing ELI5 slices'}
```

