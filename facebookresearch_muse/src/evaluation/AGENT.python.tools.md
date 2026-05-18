# Agent Python Tools

- repo: facebookresearch/muse
- repo_uri: https://github.com/facebookresearch/muse

## File: facebookresearch_muse/src/evaluation/evaluator.py

Prompts

```
['run all monolingual, cross-lingual, word and sentence translation evaluations on the trained model', 'run monolingual word similarity evaluation on source and target language embeddings', 'run cross-lingual word similarity evaluation between source and target language embeddings', 'run word translation accuracy evaluation using nearest neighbor and CSLS methods', 'run discriminator evaluation to measure source and target embedding classification accuracy', 'load parallel Europarl sentences for two languages, deduplicate them, and shuffle with a fixed random seed', 'evaluate sentence translation accuracy using nearest neighbor scoring and report precision at k for k equals 1, 5, 10', 'evaluate sentence translation accuracy using inverted softmax scoring with a configurable beta parameter and report precision at k', 'evaluate sentence translation accuracy using the CSLS contextual dissimilarity measure with k nearest neighbors and report precision at k', 'review the get_sent_translation_accuracy function to understand how bow_idf embeddings and three scoring methods compute precision at k', 'build a dictionary of identical character strings between two language vocabularies using load_identical_char_dico', 'load a bilingual word pair dictionary from a text file into a sorted torch tensor using load_dictionary', 'evaluate cross-lingual word translation accuracy using precision@k metrics with get_word_translation_accuracy', 'run nearest neighbor word translation evaluation using the nn method in get_word_translation_accuracy', 'run contextual dissimilarity measure word translation evaluation using the csls_knn method in get_word_translation_accuracy', 'parse a word similarity file and return tuples of word pairs with their scores', 'compute the Spearman correlation between predicted cosine similarities and gold similarity scores', 'evaluate monolingual word similarity scores across all datasets for a given language', 'evaluate English word analogy accuracy by category using normalized embeddings', 'compute cross-lingual word similarity Spearman rho between two languages using SEMEVAL17 data']
```

Usage

```
{'run_all_evaluations': 'run all monolingual, cross-lingual, word and sentence translation evaluations on the trained model', 'run_monolingual_wordsim': 'run monolingual word similarity evaluation on source and target language embeddings', 'run_crosslingual_wordsim': 'run cross-lingual word similarity evaluation between source and target language embeddings', 'run_word_translation': 'run word translation accuracy evaluation using nearest neighbor and CSLS methods', 'run_discriminator_eval': 'run discriminator evaluation to measure source and target embedding classification accuracy'}
```

## File: facebookresearch_muse/src/evaluation/sent_translation.py

Prompts

```
['run all monolingual, cross-lingual, word and sentence translation evaluations on the trained model', 'run monolingual word similarity evaluation on source and target language embeddings', 'run cross-lingual word similarity evaluation between source and target language embeddings', 'run word translation accuracy evaluation using nearest neighbor and CSLS methods', 'run discriminator evaluation to measure source and target embedding classification accuracy', 'load parallel Europarl sentences for two languages, deduplicate them, and shuffle with a fixed random seed', 'evaluate sentence translation accuracy using nearest neighbor scoring and report precision at k for k equals 1, 5, 10', 'evaluate sentence translation accuracy using inverted softmax scoring with a configurable beta parameter and report precision at k', 'evaluate sentence translation accuracy using the CSLS contextual dissimilarity measure with k nearest neighbors and report precision at k', 'review the get_sent_translation_accuracy function to understand how bow_idf embeddings and three scoring methods compute precision at k', 'build a dictionary of identical character strings between two language vocabularies using load_identical_char_dico', 'load a bilingual word pair dictionary from a text file into a sorted torch tensor using load_dictionary', 'evaluate cross-lingual word translation accuracy using precision@k metrics with get_word_translation_accuracy', 'run nearest neighbor word translation evaluation using the nn method in get_word_translation_accuracy', 'run contextual dissimilarity measure word translation evaluation using the csls_knn method in get_word_translation_accuracy', 'parse a word similarity file and return tuples of word pairs with their scores', 'compute the Spearman correlation between predicted cosine similarities and gold similarity scores', 'evaluate monolingual word similarity scores across all datasets for a given language', 'evaluate English word analogy accuracy by category using normalized embeddings', 'compute cross-lingual word similarity Spearman rho between two languages using SEMEVAL17 data']
```

Usage

```
{'load_europarl_parallel_sentences': 'load parallel Europarl sentences for two languages, deduplicate them, and shuffle with a fixed random seed', 'evaluate_sent_translation_nn': 'evaluate sentence translation accuracy using nearest neighbor scoring and report precision at k for k equals 1, 5, 10', 'evaluate_sent_translation_invsm': 'evaluate sentence translation accuracy using inverted softmax scoring with a configurable beta parameter and report precision at k', 'evaluate_sent_translation_csls': 'evaluate sentence translation accuracy using the CSLS contextual dissimilarity measure with k nearest neighbors and report precision at k', 'review_sent_translation_accuracy': 'review the get_sent_translation_accuracy function to understand how bow_idf embeddings and three scoring methods compute precision at k'}
```

## File: facebookresearch_muse/src/evaluation/word_translation.py

Prompts

```
['run all monolingual, cross-lingual, word and sentence translation evaluations on the trained model', 'run monolingual word similarity evaluation on source and target language embeddings', 'run cross-lingual word similarity evaluation between source and target language embeddings', 'run word translation accuracy evaluation using nearest neighbor and CSLS methods', 'run discriminator evaluation to measure source and target embedding classification accuracy', 'load parallel Europarl sentences for two languages, deduplicate them, and shuffle with a fixed random seed', 'evaluate sentence translation accuracy using nearest neighbor scoring and report precision at k for k equals 1, 5, 10', 'evaluate sentence translation accuracy using inverted softmax scoring with a configurable beta parameter and report precision at k', 'evaluate sentence translation accuracy using the CSLS contextual dissimilarity measure with k nearest neighbors and report precision at k', 'review the get_sent_translation_accuracy function to understand how bow_idf embeddings and three scoring methods compute precision at k', 'build a dictionary of identical character strings between two language vocabularies using load_identical_char_dico', 'load a bilingual word pair dictionary from a text file into a sorted torch tensor using load_dictionary', 'evaluate cross-lingual word translation accuracy using precision@k metrics with get_word_translation_accuracy', 'run nearest neighbor word translation evaluation using the nn method in get_word_translation_accuracy', 'run contextual dissimilarity measure word translation evaluation using the csls_knn method in get_word_translation_accuracy', 'parse a word similarity file and return tuples of word pairs with their scores', 'compute the Spearman correlation between predicted cosine similarities and gold similarity scores', 'evaluate monolingual word similarity scores across all datasets for a given language', 'evaluate English word analogy accuracy by category using normalized embeddings', 'compute cross-lingual word similarity Spearman rho between two languages using SEMEVAL17 data']
```

Usage

```
{'build_identical_char_dictionary': 'build a dictionary of identical character strings between two language vocabularies using load_identical_char_dico', 'load_bilingual_dictionary': 'load a bilingual word pair dictionary from a text file into a sorted torch tensor using load_dictionary', 'evaluate_word_translation_accuracy': 'evaluate cross-lingual word translation accuracy using precision@k metrics with get_word_translation_accuracy', 'run_nearest_neighbor_translation': 'run nearest neighbor word translation evaluation using the nn method in get_word_translation_accuracy', 'run_csls_translation_evaluation': 'run contextual dissimilarity measure word translation evaluation using the csls_knn method in get_word_translation_accuracy'}
```

## File: facebookresearch_muse/src/evaluation/wordsim.py

Prompts

```
['run all monolingual, cross-lingual, word and sentence translation evaluations on the trained model', 'run monolingual word similarity evaluation on source and target language embeddings', 'run cross-lingual word similarity evaluation between source and target language embeddings', 'run word translation accuracy evaluation using nearest neighbor and CSLS methods', 'run discriminator evaluation to measure source and target embedding classification accuracy', 'load parallel Europarl sentences for two languages, deduplicate them, and shuffle with a fixed random seed', 'evaluate sentence translation accuracy using nearest neighbor scoring and report precision at k for k equals 1, 5, 10', 'evaluate sentence translation accuracy using inverted softmax scoring with a configurable beta parameter and report precision at k', 'evaluate sentence translation accuracy using the CSLS contextual dissimilarity measure with k nearest neighbors and report precision at k', 'review the get_sent_translation_accuracy function to understand how bow_idf embeddings and three scoring methods compute precision at k', 'build a dictionary of identical character strings between two language vocabularies using load_identical_char_dico', 'load a bilingual word pair dictionary from a text file into a sorted torch tensor using load_dictionary', 'evaluate cross-lingual word translation accuracy using precision@k metrics with get_word_translation_accuracy', 'run nearest neighbor word translation evaluation using the nn method in get_word_translation_accuracy', 'run contextual dissimilarity measure word translation evaluation using the csls_knn method in get_word_translation_accuracy', 'parse a word similarity file and return tuples of word pairs with their scores', 'compute the Spearman correlation between predicted cosine similarities and gold similarity scores', 'evaluate monolingual word similarity scores across all datasets for a given language', 'evaluate English word analogy accuracy by category using normalized embeddings', 'compute cross-lingual word similarity Spearman rho between two languages using SEMEVAL17 data']
```

Usage

```
{'run_get_word_pairs': 'parse a word similarity file and return tuples of word pairs with their scores', 'run_get_spearman_rho': 'compute the Spearman correlation between predicted cosine similarities and gold similarity scores', 'run_get_wordsim_scores': 'evaluate monolingual word similarity scores across all datasets for a given language', 'run_get_wordanalogy_scores': 'evaluate English word analogy accuracy by category using normalized embeddings', 'run_get_crosslingual_wordsim_scores': 'compute cross-lingual word similarity Spearman rho between two languages using SEMEVAL17 data'}
```

