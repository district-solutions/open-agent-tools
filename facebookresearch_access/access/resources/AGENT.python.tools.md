# Agent Python Tools

- repo: facebookresearch/access
- repo_uri: https://github.com/facebookresearch/access

## File: facebookresearch_access/access/resources/datasets.py

Prompts

```
['create a preprocessed dataset by applying a list of preprocessors to an existing dataset with parallel jobs', 'create a preprocessed dataset by applying a single preprocessor to an existing dataset with parallel file processing', 'get a hashed dataset name derived from the original dataset name and preprocessor hash', 'check if two files share any common lines by comparing their contents', 'yield the line indexes from a file that match a given set of target lines', 'get the dataset directory path for a given dataset name', 'get the file path for a dataset given its phase, language, and optional reference index', 'get a dictionary mapping phase and language tuples to all data file paths for a dataset', 'access module-level constants like REPO_DIR, DATASETS_DIR, MODELS_DIR, LANGUAGES, and PHASES', 'review the paths module to understand directory structure and file path generation logic', 'download and prepare the wikilarge dataset for sentence simplification tasks', 'download and prepare the turkcorpus lowercased dataset from a git repository', 'download and prepare the turkcorpus dataset with truecased sentences and Levenshtein alignment', 'download and prepare the fasttext English 300-dimensional word embeddings vector file', 'download and prepare the best model and all parameters model directories', 'download a file from a URL to a local path with progress reporting and rollback on failure', 'download a compressed file from a URL and automatically extract it to a temporary directory', 'extract a compressed file (tar.gz, zip, gz, bz2) to an output directory and return extracted paths', 'clone a git repository to a specified output directory with optional overwrite of existing directory', 'replace -lrb- and -rrb- placeholders with parentheses in a text file in place']
```

Usage

```
{'create_preprocessed_dataset': 'create a preprocessed dataset by applying a list of preprocessors to an existing dataset with parallel jobs', 'create_preprocessed_dataset_one_preprocessor': 'create a preprocessed dataset by applying a single preprocessor to an existing dataset with parallel file processing', 'get_preprocessed_dataset_name': 'get a hashed dataset name derived from the original dataset name and preprocessor hash', 'has_lines_in_common': 'check if two files share any common lines by comparing their contents', 'yield_indexes_of_lines': 'yield the line indexes from a file that match a given set of target lines'}
```

## File: facebookresearch_access/access/resources/paths.py

Prompts

```
['create a preprocessed dataset by applying a list of preprocessors to an existing dataset with parallel jobs', 'create a preprocessed dataset by applying a single preprocessor to an existing dataset with parallel file processing', 'get a hashed dataset name derived from the original dataset name and preprocessor hash', 'check if two files share any common lines by comparing their contents', 'yield the line indexes from a file that match a given set of target lines', 'get the dataset directory path for a given dataset name', 'get the file path for a dataset given its phase, language, and optional reference index', 'get a dictionary mapping phase and language tuples to all data file paths for a dataset', 'access module-level constants like REPO_DIR, DATASETS_DIR, MODELS_DIR, LANGUAGES, and PHASES', 'review the paths module to understand directory structure and file path generation logic', 'download and prepare the wikilarge dataset for sentence simplification tasks', 'download and prepare the turkcorpus lowercased dataset from a git repository', 'download and prepare the turkcorpus dataset with truecased sentences and Levenshtein alignment', 'download and prepare the fasttext English 300-dimensional word embeddings vector file', 'download and prepare the best model and all parameters model directories', 'download a file from a URL to a local path with progress reporting and rollback on failure', 'download a compressed file from a URL and automatically extract it to a temporary directory', 'extract a compressed file (tar.gz, zip, gz, bz2) to an output directory and return extracted paths', 'clone a git repository to a specified output directory with optional overwrite of existing directory', 'replace -lrb- and -rrb- placeholders with parentheses in a text file in place']
```

Usage

```
{'get_dataset_dir': 'get the dataset directory path for a given dataset name', 'get_data_filepath': 'get the file path for a dataset given its phase, language, and optional reference index', 'get_filepaths_dict': 'get a dictionary mapping phase and language tuples to all data file paths for a dataset', 'access_constants': 'access module-level constants like REPO_DIR, DATASETS_DIR, MODELS_DIR, LANGUAGES, and PHASES', 'review_paths_module': 'review the paths module to understand directory structure and file path generation logic'}
```

## File: facebookresearch_access/access/resources/prepare.py

Prompts

```
['create a preprocessed dataset by applying a list of preprocessors to an existing dataset with parallel jobs', 'create a preprocessed dataset by applying a single preprocessor to an existing dataset with parallel file processing', 'get a hashed dataset name derived from the original dataset name and preprocessor hash', 'check if two files share any common lines by comparing their contents', 'yield the line indexes from a file that match a given set of target lines', 'get the dataset directory path for a given dataset name', 'get the file path for a dataset given its phase, language, and optional reference index', 'get a dictionary mapping phase and language tuples to all data file paths for a dataset', 'access module-level constants like REPO_DIR, DATASETS_DIR, MODELS_DIR, LANGUAGES, and PHASES', 'review the paths module to understand directory structure and file path generation logic', 'download and prepare the wikilarge dataset for sentence simplification tasks', 'download and prepare the turkcorpus lowercased dataset from a git repository', 'download and prepare the turkcorpus dataset with truecased sentences and Levenshtein alignment', 'download and prepare the fasttext English 300-dimensional word embeddings vector file', 'download and prepare the best model and all parameters model directories', 'download a file from a URL to a local path with progress reporting and rollback on failure', 'download a compressed file from a URL and automatically extract it to a temporary directory', 'extract a compressed file (tar.gz, zip, gz, bz2) to an output directory and return extracted paths', 'clone a git repository to a specified output directory with optional overwrite of existing directory', 'replace -lrb- and -rrb- placeholders with parentheses in a text file in place']
```

Usage

```
{'prepare_wikilarge_dataset': 'download and prepare the wikilarge dataset for sentence simplification tasks', 'prepare_turkcorpus_lower_dataset': 'download and prepare the turkcorpus lowercased dataset from a git repository', 'prepare_turkcorpus_dataset': 'download and prepare the turkcorpus dataset with truecased sentences and Levenshtein alignment', 'prepare_fasttext_embeddings': 'download and prepare the fasttext English 300-dimensional word embeddings vector file', 'prepare_models': 'download and prepare the best model and all parameters model directories'}
```

## File: facebookresearch_access/access/resources/utils.py

Prompts

```
['create a preprocessed dataset by applying a list of preprocessors to an existing dataset with parallel jobs', 'create a preprocessed dataset by applying a single preprocessor to an existing dataset with parallel file processing', 'get a hashed dataset name derived from the original dataset name and preprocessor hash', 'check if two files share any common lines by comparing their contents', 'yield the line indexes from a file that match a given set of target lines', 'get the dataset directory path for a given dataset name', 'get the file path for a dataset given its phase, language, and optional reference index', 'get a dictionary mapping phase and language tuples to all data file paths for a dataset', 'access module-level constants like REPO_DIR, DATASETS_DIR, MODELS_DIR, LANGUAGES, and PHASES', 'review the paths module to understand directory structure and file path generation logic', 'download and prepare the wikilarge dataset for sentence simplification tasks', 'download and prepare the turkcorpus lowercased dataset from a git repository', 'download and prepare the turkcorpus dataset with truecased sentences and Levenshtein alignment', 'download and prepare the fasttext English 300-dimensional word embeddings vector file', 'download and prepare the best model and all parameters model directories', 'download a file from a URL to a local path with progress reporting and rollback on failure', 'download a compressed file from a URL and automatically extract it to a temporary directory', 'extract a compressed file (tar.gz, zip, gz, bz2) to an output directory and return extracted paths', 'clone a git repository to a specified output directory with optional overwrite of existing directory', 'replace -lrb- and -rrb- placeholders with parentheses in a text file in place']
```

Usage

```
{'download_file': 'download a file from a URL to a local path with progress reporting and rollback on failure', 'download_and_extract': 'download a compressed file from a URL and automatically extract it to a temporary directory', 'extract_archive': 'extract a compressed file (tar.gz, zip, gz, bz2) to an output directory and return extracted paths', 'git_clone_repo': 'clone a git repository to a specified output directory with optional overwrite of existing directory', 'replace_lrb_rrb': 'replace -lrb- and -rrb- placeholders with parentheses in a text file in place'}
```

