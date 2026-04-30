# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/feature_extraction/tests/test_dict_vectorizer.py

Prompts

```
['create a DictVectorizer to transform a list of feature dictionaries into a sparse or dense matrix', 'test DictVectorizer with SelectKBest feature selection to restrict features by chi2 scores', 'test DictVectorizer one-hot encoding of categorical string values into prefixed feature names', 'test DictVectorizer expanding iterable values into multiple one-hot encoded columns', 'test DictVectorizer inverse_transform to reconstruct original dictionaries from feature matrices', 'test FeatureHasher transform with dict input_type and verify equivalence with pair input_type', 'test FeatureHasher transform with string input_type across multiple feature dimensions', 'test FeatureHasher raises ValueError when input samples are single strings', 'test _hashing_transform produces consistent results with seed=0 and different results with seed=1', 'test FeatureHasher transform with pair input_type and verify non-zero values', 'create a function that extracts 2D patches from an image with configurable size and stride', 'test the python function reconstruct_from_patches_2d to verify perfect reconstruction from extracted patches', 'build a PatchExtractor class instance to extract patches from a collection of images with max_patches and random_state', 'test the python function img_to_graph to build a graph representation of image pixel connections', 'test the python function grid_to_graph to build a graph from a grid with optional mask and dtype parameters', 'create a CountVectorizer to tokenize text documents and build a vocabulary of word frequencies', 'create a TfidfVectorizer to transform text documents into TF-IDF weighted feature vectors', 'create a HashingVectorizer to hash text features without fitting, supporting n-grams and binary mode', 'create a TfidfTransformer to apply TF-IDF weighting to pre-computed term frequency counts', 'create strip_accents_ascii or strip_accents_unicode to remove diacritical marks from text strings']
```

Usage

```
{'create_DictVectorizer_fit_transform': 'create a DictVectorizer to transform a list of feature dictionaries into a sparse or dense matrix', 'test_DictVectorizer_feature_selection': 'test DictVectorizer with SelectKBest feature selection to restrict features by chi2 scores', 'test_DictVectorizer_one_hot_encoding': 'test DictVectorizer one-hot encoding of categorical string values into prefixed feature names', 'test_DictVectorizer_iterable_values': 'test DictVectorizer expanding iterable values into multiple one-hot encoded columns', 'test_DictVectorizer_inverse_transform': 'test DictVectorizer inverse_transform to reconstruct original dictionaries from feature matrices'}
```

## File: scikit-learn_scikit-learn/sklearn/feature_extraction/tests/test_feature_hasher.py

Prompts

```
['create a DictVectorizer to transform a list of feature dictionaries into a sparse or dense matrix', 'test DictVectorizer with SelectKBest feature selection to restrict features by chi2 scores', 'test DictVectorizer one-hot encoding of categorical string values into prefixed feature names', 'test DictVectorizer expanding iterable values into multiple one-hot encoded columns', 'test DictVectorizer inverse_transform to reconstruct original dictionaries from feature matrices', 'test FeatureHasher transform with dict input_type and verify equivalence with pair input_type', 'test FeatureHasher transform with string input_type across multiple feature dimensions', 'test FeatureHasher raises ValueError when input samples are single strings', 'test _hashing_transform produces consistent results with seed=0 and different results with seed=1', 'test FeatureHasher transform with pair input_type and verify non-zero values', 'create a function that extracts 2D patches from an image with configurable size and stride', 'test the python function reconstruct_from_patches_2d to verify perfect reconstruction from extracted patches', 'build a PatchExtractor class instance to extract patches from a collection of images with max_patches and random_state', 'test the python function img_to_graph to build a graph representation of image pixel connections', 'test the python function grid_to_graph to build a graph from a grid with optional mask and dtype parameters', 'create a CountVectorizer to tokenize text documents and build a vocabulary of word frequencies', 'create a TfidfVectorizer to transform text documents into TF-IDF weighted feature vectors', 'create a HashingVectorizer to hash text features without fitting, supporting n-grams and binary mode', 'create a TfidfTransformer to apply TF-IDF weighting to pre-computed term frequency counts', 'create strip_accents_ascii or strip_accents_unicode to remove diacritical marks from text strings']
```

Usage

```
{'test_feature_hasher_dicts': 'test FeatureHasher transform with dict input_type and verify equivalence with pair input_type', 'test_feature_hasher_strings': 'test FeatureHasher transform with string input_type across multiple feature dimensions', 'test_feature_hasher_single_string': 'test FeatureHasher raises ValueError when input samples are single strings', 'test_hashing_transform_seed': 'test _hashing_transform produces consistent results with seed=0 and different results with seed=1', 'test_feature_hasher_pairs': 'test FeatureHasher transform with pair input_type and verify non-zero values'}
```

## File: scikit-learn_scikit-learn/sklearn/feature_extraction/tests/test_image.py

Prompts

```
['create a DictVectorizer to transform a list of feature dictionaries into a sparse or dense matrix', 'test DictVectorizer with SelectKBest feature selection to restrict features by chi2 scores', 'test DictVectorizer one-hot encoding of categorical string values into prefixed feature names', 'test DictVectorizer expanding iterable values into multiple one-hot encoded columns', 'test DictVectorizer inverse_transform to reconstruct original dictionaries from feature matrices', 'test FeatureHasher transform with dict input_type and verify equivalence with pair input_type', 'test FeatureHasher transform with string input_type across multiple feature dimensions', 'test FeatureHasher raises ValueError when input samples are single strings', 'test _hashing_transform produces consistent results with seed=0 and different results with seed=1', 'test FeatureHasher transform with pair input_type and verify non-zero values', 'create a function that extracts 2D patches from an image with configurable size and stride', 'test the python function reconstruct_from_patches_2d to verify perfect reconstruction from extracted patches', 'build a PatchExtractor class instance to extract patches from a collection of images with max_patches and random_state', 'test the python function img_to_graph to build a graph representation of image pixel connections', 'test the python function grid_to_graph to build a graph from a grid with optional mask and dtype parameters', 'create a CountVectorizer to tokenize text documents and build a vocabulary of word frequencies', 'create a TfidfVectorizer to transform text documents into TF-IDF weighted feature vectors', 'create a HashingVectorizer to hash text features without fitting, supporting n-grams and binary mode', 'create a TfidfTransformer to apply TF-IDF weighting to pre-computed term frequency counts', 'create strip_accents_ascii or strip_accents_unicode to remove diacritical marks from text strings']
```

Usage

```
{'create_function_extract_patches_2d': 'create a function that extracts 2D patches from an image with configurable size and stride', 'test_function_reconstruct_from_patches_2d': 'test the python function reconstruct_from_patches_2d to verify perfect reconstruction from extracted patches', 'build_class_patch_extractor': 'build a PatchExtractor class instance to extract patches from a collection of images with max_patches and random_state', 'test_function_img_to_graph': 'test the python function img_to_graph to build a graph representation of image pixel connections', 'test_function_grid_to_graph': 'test the python function grid_to_graph to build a graph from a grid with optional mask and dtype parameters'}
```

## File: scikit-learn_scikit-learn/sklearn/feature_extraction/tests/test_text.py

Prompts

```
['create a DictVectorizer to transform a list of feature dictionaries into a sparse or dense matrix', 'test DictVectorizer with SelectKBest feature selection to restrict features by chi2 scores', 'test DictVectorizer one-hot encoding of categorical string values into prefixed feature names', 'test DictVectorizer expanding iterable values into multiple one-hot encoded columns', 'test DictVectorizer inverse_transform to reconstruct original dictionaries from feature matrices', 'test FeatureHasher transform with dict input_type and verify equivalence with pair input_type', 'test FeatureHasher transform with string input_type across multiple feature dimensions', 'test FeatureHasher raises ValueError when input samples are single strings', 'test _hashing_transform produces consistent results with seed=0 and different results with seed=1', 'test FeatureHasher transform with pair input_type and verify non-zero values', 'create a function that extracts 2D patches from an image with configurable size and stride', 'test the python function reconstruct_from_patches_2d to verify perfect reconstruction from extracted patches', 'build a PatchExtractor class instance to extract patches from a collection of images with max_patches and random_state', 'test the python function img_to_graph to build a graph representation of image pixel connections', 'test the python function grid_to_graph to build a graph from a grid with optional mask and dtype parameters', 'create a CountVectorizer to tokenize text documents and build a vocabulary of word frequencies', 'create a TfidfVectorizer to transform text documents into TF-IDF weighted feature vectors', 'create a HashingVectorizer to hash text features without fitting, supporting n-grams and binary mode', 'create a TfidfTransformer to apply TF-IDF weighting to pre-computed term frequency counts', 'create strip_accents_ascii or strip_accents_unicode to remove diacritical marks from text strings']
```

Usage

```
{'create_CountVectorizer': 'create a CountVectorizer to tokenize text documents and build a vocabulary of word frequencies', 'create_TfidfVectorizer': 'create a TfidfVectorizer to transform text documents into TF-IDF weighted feature vectors', 'create_HashingVectorizer': 'create a HashingVectorizer to hash text features without fitting, supporting n-grams and binary mode', 'create_TfidfTransformer': 'create a TfidfTransformer to apply TF-IDF weighting to pre-computed term frequency counts', 'create_strip_accents': 'create strip_accents_ascii or strip_accents_unicode to remove diacritical marks from text strings'}
```

