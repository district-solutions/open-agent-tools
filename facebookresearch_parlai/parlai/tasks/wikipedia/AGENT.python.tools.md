# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/wikipedia/agents.py

Prompts

```
['run the FullTeacher class to load full Wikipedia articles one at a time from extracted JSON files', 'run the FullSplitTeacher class to split Wikipedia chunks into train, valid, and test sets', 'run the SummaryTeacher class to load Wikipedia article summaries from the summaries JSON file', 'review the FullTeacher setup_data method to understand how it yields title and text tuples from wiki files', 'review the FullSplitTeacher get_fold_chunks method to understand how chunk IDs map to train, valid, and test splits', 'run the build function to download and extract the full Wikipedia dataset for the wikipedia:all task', 'run the build function to download and extract the Wikipedia summaries dataset for a non-all task', 'review the build function to understand how it determines data paths and downloads Wikipedia resources', 'review the RESOURCES list to see the two DownloadableFile entries for Wikipedia full and summary data', 'refactor the build function to support additional Wikipedia task variants beyond all and summary']
```

Usage

```
{'run_fullteacher_wikipedia': 'run the FullTeacher class to load full Wikipedia articles one at a time from extracted JSON files', 'run_fullsplitteacher_train_valid_test': 'run the FullSplitTeacher class to split Wikipedia chunks into train, valid, and test sets', 'run_summaryteacher_wikipedia': 'run the SummaryTeacher class to load Wikipedia article summaries from the summaries JSON file', 'review_fullteacher_setup_data': 'review the FullTeacher setup_data method to understand how it yields title and text tuples from wiki files', 'review_fullsplitteacher_get_fold_chunks': 'review the FullSplitTeacher get_fold_chunks method to understand how chunk IDs map to train, valid, and test splits'}
```

## File: facebookresearch_parlai/parlai/tasks/wikipedia/build.py

Prompts

```
['run the FullTeacher class to load full Wikipedia articles one at a time from extracted JSON files', 'run the FullSplitTeacher class to split Wikipedia chunks into train, valid, and test sets', 'run the SummaryTeacher class to load Wikipedia article summaries from the summaries JSON file', 'review the FullTeacher setup_data method to understand how it yields title and text tuples from wiki files', 'review the FullSplitTeacher get_fold_chunks method to understand how chunk IDs map to train, valid, and test splits', 'run the build function to download and extract the full Wikipedia dataset for the wikipedia:all task', 'run the build function to download and extract the Wikipedia summaries dataset for a non-all task', 'review the build function to understand how it determines data paths and downloads Wikipedia resources', 'review the RESOURCES list to see the two DownloadableFile entries for Wikipedia full and summary data', 'refactor the build function to support additional Wikipedia task variants beyond all and summary']
```

Usage

```
{'build_wikipedia_full_data': 'run the build function to download and extract the full Wikipedia dataset for the wikipedia:all task', 'build_wikipedia_summary_data': 'run the build function to download and extract the Wikipedia summaries dataset for a non-all task', 'review_build_function': 'review the build function to understand how it determines data paths and downloads Wikipedia resources', 'review_RESOURCES_list': 'review the RESOURCES list to see the two DownloadableFile entries for Wikipedia full and summary data', 'refactor_build_task_selection': 'refactor the build function to support additional Wikipedia task variants beyond all and summary'}
```

