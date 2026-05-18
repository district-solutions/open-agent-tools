# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/databases/annotation_database.py

Prompts

```
['create an AnnotationDatabase instance that loads annotation data from a JSON file path', 'create an AnnotationDatabase instance that loads annotation data from a JSONL file path', 'create an AnnotationDatabase instance that loads annotation data from a NumPy .npy file path', 'review the AnnotationDatabase __getitem__ method and its legacy IMDB answer field normalization logic', 'summarize the AnnotationDatabase private loader methods for JSON, JSONL, NPY, and VisualDialog formats', 'create a FeaturesDatabase instance with config, feature paths, and optional annotation database', 'run threaded pre-caching of all image features from the annotation database using a thread pool', 'read image features and metadata from a feature file using registered FeatureReader instances', 'get image features and info for an annotation item by its feature key or derived path', 'retrieve image features and info dictionary from a raw feature file path string', 'create an ImageDatabase instance with config, path, and optional annotation_db to load images from a folder', 'build an ImageDatabase and call from_path with image paths to load and transform images into a dictionary', 'test the ImageDatabase __getitem__ method by indexing into it after setting an annotation_db', 'refactor the default_loader function to open an image file via PathManager and convert it to RGB', 'review the get_possible_image_paths function that resolves image paths by trying common image file extensions']
```

Usage

```
{'build_annotation_database_from_json': 'create an AnnotationDatabase instance that loads annotation data from a JSON file path', 'build_annotation_database_from_jsonl': 'create an AnnotationDatabase instance that loads annotation data from a JSONL file path', 'build_annotation_database_from_npy': 'create an AnnotationDatabase instance that loads annotation data from a NumPy .npy file path', 'review_annotation_database_getitem': 'review the AnnotationDatabase __getitem__ method and its legacy IMDB answer field normalization logic', 'summarize_annotation_database_loaders': 'summarize the AnnotationDatabase private loader methods for JSON, JSONL, NPY, and VisualDialog formats'}
```

## File: facebookresearch_mmf/mmf/datasets/databases/features_database.py

Prompts

```
['create an AnnotationDatabase instance that loads annotation data from a JSON file path', 'create an AnnotationDatabase instance that loads annotation data from a JSONL file path', 'create an AnnotationDatabase instance that loads annotation data from a NumPy .npy file path', 'review the AnnotationDatabase __getitem__ method and its legacy IMDB answer field normalization logic', 'summarize the AnnotationDatabase private loader methods for JSON, JSONL, NPY, and VisualDialog formats', 'create a FeaturesDatabase instance with config, feature paths, and optional annotation database', 'run threaded pre-caching of all image features from the annotation database using a thread pool', 'read image features and metadata from a feature file using registered FeatureReader instances', 'get image features and info for an annotation item by its feature key or derived path', 'retrieve image features and info dictionary from a raw feature file path string', 'create an ImageDatabase instance with config, path, and optional annotation_db to load images from a folder', 'build an ImageDatabase and call from_path with image paths to load and transform images into a dictionary', 'test the ImageDatabase __getitem__ method by indexing into it after setting an annotation_db', 'refactor the default_loader function to open an image file via PathManager and convert it to RGB', 'review the get_possible_image_paths function that resolves image paths by trying common image file extensions']
```

Usage

```
{'init_FeaturesDatabase': 'create a FeaturesDatabase instance with config, feature paths, and optional annotation database', 'threaded_read_FeaturesDatabase': 'run threaded pre-caching of all image features from the annotation database using a thread pool', 'read_features_and_info_FeaturesDatabase': 'read image features and metadata from a feature file using registered FeatureReader instances', 'get_FeaturesDatabase': 'get image features and info for an annotation item by its feature key or derived path', 'from_path_FeaturesDatabase': 'retrieve image features and info dictionary from a raw feature file path string'}
```

## File: facebookresearch_mmf/mmf/datasets/databases/image_database.py

Prompts

```
['create an AnnotationDatabase instance that loads annotation data from a JSON file path', 'create an AnnotationDatabase instance that loads annotation data from a JSONL file path', 'create an AnnotationDatabase instance that loads annotation data from a NumPy .npy file path', 'review the AnnotationDatabase __getitem__ method and its legacy IMDB answer field normalization logic', 'summarize the AnnotationDatabase private loader methods for JSON, JSONL, NPY, and VisualDialog formats', 'create a FeaturesDatabase instance with config, feature paths, and optional annotation database', 'run threaded pre-caching of all image features from the annotation database using a thread pool', 'read image features and metadata from a feature file using registered FeatureReader instances', 'get image features and info for an annotation item by its feature key or derived path', 'retrieve image features and info dictionary from a raw feature file path string', 'create an ImageDatabase instance with config, path, and optional annotation_db to load images from a folder', 'build an ImageDatabase and call from_path with image paths to load and transform images into a dictionary', 'test the ImageDatabase __getitem__ method by indexing into it after setting an annotation_db', 'refactor the default_loader function to open an image file via PathManager and convert it to RGB', 'review the get_possible_image_paths function that resolves image paths by trying common image file extensions']
```

Usage

```
{'create_ImageDatabase': 'create an ImageDatabase instance with config, path, and optional annotation_db to load images from a folder', 'build_ImageDatabase_from_path': 'build an ImageDatabase and call from_path with image paths to load and transform images into a dictionary', 'test_ImageDatabase_getitem': 'test the ImageDatabase __getitem__ method by indexing into it after setting an annotation_db', 'refactor_default_loader': 'refactor the default_loader function to open an image file via PathManager and convert it to RGB', 'review_get_possible_image_paths': 'review the get_possible_image_paths function that resolves image paths by trying common image file extensions'}
```

