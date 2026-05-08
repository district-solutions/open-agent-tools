# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/holl_e/agents.py

Prompts

```
['build a Holl-E dialog teacher that loads movie knowledge and chat episodes from JSON data files', 'create a knowledge filter to select plot, review, comments, or fact_table types for Holl-E dialog episodes', 'test the Holl-E teacher setup_data method to verify episodes are correctly parsed from raw JSON files', 'review the Holl-E get_knowledge method to understand how fact tables, reviews, and comments are assembled into knowledge strings', 'refactor the list_to_str helper function to use Python join for more efficient list-to-string conversion', 'build the Holl-E dataset by downloading train and test JSON files from Google Drive', 'run the build function to download and prepare the Holl-E dataset in the datapath directory', 'download the Holl-E raw train and test data JSON files using DownloadableFile resources', 'check if the Holl-E dataset has already been built in the specified datapath directory', 'remove outdated versions of the Holl-E dataset before rebuilding with fresh downloads']
```

Usage

```
{'build_holle_teacher': 'build a Holl-E dialog teacher that loads movie knowledge and chat episodes from JSON data files', 'create_knowledge_filter': 'create a knowledge filter to select plot, review, comments, or fact_table types for Holl-E dialog episodes', 'test_setup_data': 'test the Holl-E teacher setup_data method to verify episodes are correctly parsed from raw JSON files', 'review_get_knowledge': 'review the Holl-E get_knowledge method to understand how fact tables, reviews, and comments are assembled into knowledge strings', 'refactor_list_to_str': 'refactor the list_to_str helper function to use Python join for more efficient list-to-string conversion'}
```

## File: facebookresearch_parlai/parlai/tasks/holl_e/build.py

Prompts

```
['build a Holl-E dialog teacher that loads movie knowledge and chat episodes from JSON data files', 'create a knowledge filter to select plot, review, comments, or fact_table types for Holl-E dialog episodes', 'test the Holl-E teacher setup_data method to verify episodes are correctly parsed from raw JSON files', 'review the Holl-E get_knowledge method to understand how fact tables, reviews, and comments are assembled into knowledge strings', 'refactor the list_to_str helper function to use Python join for more efficient list-to-string conversion', 'build the Holl-E dataset by downloading train and test JSON files from Google Drive', 'run the build function to download and prepare the Holl-E dataset in the datapath directory', 'download the Holl-E raw train and test data JSON files using DownloadableFile resources', 'check if the Holl-E dataset has already been built in the specified datapath directory', 'remove outdated versions of the Holl-E dataset before rebuilding with fresh downloads']
```

Usage

```
{'build_holl_e_data': 'build the Holl-E dataset by downloading train and test JSON files from Google Drive', 'run_build_function': 'run the build function to download and prepare the Holl-E dataset in the datapath directory', 'download_holl_e_resources': 'download the Holl-E raw train and test data JSON files using DownloadableFile resources', 'check_data_built': 'check if the Holl-E dataset has already been built in the specified datapath directory', 'remove_outdated_holl_e_data': 'remove outdated versions of the Holl-E dataset before rebuilding with fresh downloads'}
```

