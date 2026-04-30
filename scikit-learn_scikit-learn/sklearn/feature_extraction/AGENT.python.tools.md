# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/feature_extraction/_dict_vectorizer.py

Prompts

```
['create a DictVectorizer to transform lists of feature-value mapping dicts into sparse matrices', 'build a DictVectorizer that converts dicts with string and numeric feature values into feature vectors', 'test DictVectorizer inverse_transform to convert feature vectors back to dictionaries', 'refactor DictVectorizer to restrict features to a subset using a boolean mask or index list', 'review DictVectorizer get_feature_names_out to retrieve sorted feature name strings from fitted model', 'create a FeatureHasher transformer that converts sequences of symbolic feature names into sparse matrices using Murmurhash3', 'transform a list of dictionaries into a sparse matrix using FeatureHasher with dict input type', "test FeatureHasher with input_type='string' to hash string-only feature sequences into sparse matrices", 'build a FeatureHasher with custom n_features, alternate_sign, and dtype parameters for low-memory feature extraction', 'review the FeatureHasher fit method that validates parameters and returns self for API consistency', 'build an adjacency graph from a 2D image using pixel-to-pixel gradient connections', 'create a collection of 2D patches extracted from an image with specified patch size', 'reconstruct a 2D image from its patches by averaging overlapping regions', 'build a grid connectivity graph with optional mask and custom dimensions', 'extract patches from multiple images using PatchExtractor transformer API', 'create a CountVectorizer to tokenize text documents and build a document-term frequency matrix', 'create a HashingVectorizer to hash text tokens into a fixed-size sparse feature matrix without building a vocabulary', 'create a TfidfVectorizer to convert raw text documents into a TF-IDF weighted feature matrix', 'build a TfidfTransformer to normalize a count matrix into TF-IDF weighted representations', 'test the strip_accents_ascii and strip_accents_unicode functions to remove accented characters from text strings']
```

Usage

```
{'create_DictVectorizer_fit_transform': 'create a DictVectorizer to transform lists of feature-value mapping dicts into sparse matrices', 'build_DictVectorizer_transform': 'build a DictVectorizer that converts dicts with string and numeric feature values into feature vectors', 'test_DictVectorizer_inverse_transform': 'test DictVectorizer inverse_transform to convert feature vectors back to dictionaries', 'refactor_DictVectorizer_restrict': 'refactor DictVectorizer to restrict features to a subset using a boolean mask or index list', 'review_DictVectorizer_get_feature_names_out': 'review DictVectorizer get_feature_names_out to retrieve sorted feature name strings from fitted model'}
```

## File: scikit-learn_scikit-learn/sklearn/feature_extraction/_hash.py

Prompts

```
['create a DictVectorizer to transform lists of feature-value mapping dicts into sparse matrices', 'build a DictVectorizer that converts dicts with string and numeric feature values into feature vectors', 'test DictVectorizer inverse_transform to convert feature vectors back to dictionaries', 'refactor DictVectorizer to restrict features to a subset using a boolean mask or index list', 'review DictVectorizer get_feature_names_out to retrieve sorted feature name strings from fitted model', 'create a FeatureHasher transformer that converts sequences of symbolic feature names into sparse matrices using Murmurhash3', 'transform a list of dictionaries into a sparse matrix using FeatureHasher with dict input type', "test FeatureHasher with input_type='string' to hash string-only feature sequences into sparse matrices", 'build a FeatureHasher with custom n_features, alternate_sign, and dtype parameters for low-memory feature extraction', 'review the FeatureHasher fit method that validates parameters and returns self for API consistency', 'build an adjacency graph from a 2D image using pixel-to-pixel gradient connections', 'create a collection of 2D patches extracted from an image with specified patch size', 'reconstruct a 2D image from its patches by averaging overlapping regions', 'build a grid connectivity graph with optional mask and custom dimensions', 'extract patches from multiple images using PatchExtractor transformer API', 'create a CountVectorizer to tokenize text documents and build a document-term frequency matrix', 'create a HashingVectorizer to hash text tokens into a fixed-size sparse feature matrix without building a vocabulary', 'create a TfidfVectorizer to convert raw text documents into a TF-IDF weighted feature matrix', 'build a TfidfTransformer to normalize a count matrix into TF-IDF weighted representations', 'test the strip_accents_ascii and strip_accents_unicode functions to remove accented characters from text strings']
```

Usage

```
{'create_FeatureHasher': 'create a FeatureHasher transformer that converts sequences of symbolic feature names into sparse matrices using Murmurhash3', 'transform_FeatureHasher': 'transform a list of dictionaries into a sparse matrix using FeatureHasher with dict input type', 'test_FeatureHasher_string': "test FeatureHasher with input_type='string' to hash string-only feature sequences into sparse matrices", 'build_FeatureHasher': 'build a FeatureHasher with custom n_features, alternate_sign, and dtype parameters for low-memory feature extraction', 'review_FeatureHasher_fit': 'review the FeatureHasher fit method that validates parameters and returns self for API consistency'}
```

## File: scikit-learn_scikit-learn/sklearn/feature_extraction/image.py

Prompts

```
['create a DictVectorizer to transform lists of feature-value mapping dicts into sparse matrices', 'build a DictVectorizer that converts dicts with string and numeric feature values into feature vectors', 'test DictVectorizer inverse_transform to convert feature vectors back to dictionaries', 'refactor DictVectorizer to restrict features to a subset using a boolean mask or index list', 'review DictVectorizer get_feature_names_out to retrieve sorted feature name strings from fitted model', 'create a FeatureHasher transformer that converts sequences of symbolic feature names into sparse matrices using Murmurhash3', 'transform a list of dictionaries into a sparse matrix using FeatureHasher with dict input type', "test FeatureHasher with input_type='string' to hash string-only feature sequences into sparse matrices", 'build a FeatureHasher with custom n_features, alternate_sign, and dtype parameters for low-memory feature extraction', 'review the FeatureHasher fit method that validates parameters and returns self for API consistency', 'build an adjacency graph from a 2D image using pixel-to-pixel gradient connections', 'create a collection of 2D patches extracted from an image with specified patch size', 'reconstruct a 2D image from its patches by averaging overlapping regions', 'build a grid connectivity graph with optional mask and custom dimensions', 'extract patches from multiple images using PatchExtractor transformer API', 'create a CountVectorizer to tokenize text documents and build a document-term frequency matrix', 'create a HashingVectorizer to hash text tokens into a fixed-size sparse feature matrix without building a vocabulary', 'create a TfidfVectorizer to convert raw text documents into a TF-IDF weighted feature matrix', 'build a TfidfTransformer to normalize a count matrix into TF-IDF weighted representations', 'test the strip_accents_ascii and strip_accents_unicode functions to remove accented characters from text strings']
```

Usage

```
{'build_graph_from_image': 'build an adjacency graph from a 2D image using pixel-to-pixel gradient connections', 'create_patches_from_image': 'create a collection of 2D patches extracted from an image with specified patch size', 'reconstruct_image_from_patches': 'reconstruct a 2D image from its patches by averaging overlapping regions', 'build_grid_connectivity_graph': 'build a grid connectivity graph with optional mask and custom dimensions', 'extract_patches_with_transformer': 'extract patches from multiple images using PatchExtractor transformer API'}
```

## File: scikit-learn_scikit-learn/sklearn/feature_extraction/text.py

Prompts

```
['create a DictVectorizer to transform lists of feature-value mapping dicts into sparse matrices', 'build a DictVectorizer that converts dicts with string and numeric feature values into feature vectors', 'test DictVectorizer inverse_transform to convert feature vectors back to dictionaries', 'refactor DictVectorizer to restrict features to a subset using a boolean mask or index list', 'review DictVectorizer get_feature_names_out to retrieve sorted feature name strings from fitted model', 'create a FeatureHasher transformer that converts sequences of symbolic feature names into sparse matrices using Murmurhash3', 'transform a list of dictionaries into a sparse matrix using FeatureHasher with dict input type', "test FeatureHasher with input_type='string' to hash string-only feature sequences into sparse matrices", 'build a FeatureHasher with custom n_features, alternate_sign, and dtype parameters for low-memory feature extraction', 'review the FeatureHasher fit method that validates parameters and returns self for API consistency', 'build an adjacency graph from a 2D image using pixel-to-pixel gradient connections', 'create a collection of 2D patches extracted from an image with specified patch size', 'reconstruct a 2D image from its patches by averaging overlapping regions', 'build a grid connectivity graph with optional mask and custom dimensions', 'extract patches from multiple images using PatchExtractor transformer API', 'create a CountVectorizer to tokenize text documents and build a document-term frequency matrix', 'create a HashingVectorizer to hash text tokens into a fixed-size sparse feature matrix without building a vocabulary', 'create a TfidfVectorizer to convert raw text documents into a TF-IDF weighted feature matrix', 'build a TfidfTransformer to normalize a count matrix into TF-IDF weighted representations', 'test the strip_accents_ascii and strip_accents_unicode functions to remove accented characters from text strings']
```

Usage

```
{'create_vectorizer_count_tokens': 'create a CountVectorizer to tokenize text documents and build a document-term frequency matrix', 'create_vectorizer_hash_tokens': 'create a HashingVectorizer to hash text tokens into a fixed-size sparse feature matrix without building a vocabulary', 'create_vectorizer_tfidf_features': 'create a TfidfVectorizer to convert raw text documents into a TF-IDF weighted feature matrix', 'build_transformer_tfidf_normalize': 'build a TfidfTransformer to normalize a count matrix into TF-IDF weighted representations', 'test_vectorizer_strip_accents': 'test the strip_accents_ascii and strip_accents_unicode functions to remove accented characters from text strings'}
```

