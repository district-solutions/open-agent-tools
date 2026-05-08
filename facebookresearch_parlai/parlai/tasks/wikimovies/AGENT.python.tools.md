# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/wikimovies/build.py

Prompts

```
['run the build function to download and prepare the WikiMovies dataset for ParlAI', 'download the WikiMovies tar.gz file using the RESOURCES list of DownloadableFile entries', 'check if the WikiMovies dataset has already been built using build_data.built', 'remove an older version of the WikiMovies dataset directory using build_data.remove_dir', 'mark the WikiMovies dataset build as complete using build_data.mark_done']
```

Usage

```
{'build_wikimovies_dataset': 'run the build function to download and prepare the WikiMovies dataset for ParlAI', 'download_wikimovies_resources': 'download the WikiMovies tar.gz file using the RESOURCES list of DownloadableFile entries', 'check_wikimovies_built_status': 'check if the WikiMovies dataset has already been built using build_data.built', 'remove_outdated_wikimovies_data': 'remove an older version of the WikiMovies dataset directory using build_data.remove_dir', 'mark_wikimovies_done': 'mark the WikiMovies dataset build as complete using build_data.mark_done'}
```

