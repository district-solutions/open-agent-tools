# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/fits/agents.py

Prompts

```
['run the FitsBaseTeacher to load and serve FITS dialogue data with metadata extraction', 'run the FitsFeedbackTeacher to serve free-form text feedback examples from FITS dialogues', 'run the FitsSatisfactionTeacher to serve binary OK/NOT_OK classification labels on bot responses', 'run the QueryTeacher to extract and serve search query training data from FITS episodes', 'review the format_to_woi_consistent function that parses docs into WOI-compatible retrieved docs and titles', 'build the FiTS dataset by downloading and extracting the fits_data tarball into the datapath directory', 'build the FiTS v2 dataset by calling build with fits_task_version set to v2', 'get the correct data subdirectory path for a given FiTS task version and unseen task flag', 'review the build function to understand how it handles versioned dataset downloads and cleanup', 'summarize the RESOURCES list to see the downloadable FiTS dataset URL and SHA-256 checksum', 'normalize a reply string by stripping unwanted tokens and joining multiline text into a single line', 'append a knowledge sentence wrapped in special tokens to an existing context string', 'filter dialogue episodes by their last nonperfect feedback type using FeedbackMixin subclasses', 'mutate episode labels to use gold knowledge sentences with or without special tokens', 'prepare dialogue episodes for left-to-right classifier training by splitting context and final utterance']
```

Usage

```
{'run_fits_base_teacher': 'run the FitsBaseTeacher to load and serve FITS dialogue data with metadata extraction', 'run_fits_feedback_teacher': 'run the FitsFeedbackTeacher to serve free-form text feedback examples from FITS dialogues', 'run_fits_satisfaction_teacher': 'run the FitsSatisfactionTeacher to serve binary OK/NOT_OK classification labels on bot responses', 'run_query_teacher': 'run the QueryTeacher to extract and serve search query training data from FITS episodes', 'review_format_to_woi_consistent': 'review the format_to_woi_consistent function that parses docs into WOI-compatible retrieved docs and titles'}
```

## File: facebookresearch_parlai/parlai/tasks/fits/build.py

Prompts

```
['run the FitsBaseTeacher to load and serve FITS dialogue data with metadata extraction', 'run the FitsFeedbackTeacher to serve free-form text feedback examples from FITS dialogues', 'run the FitsSatisfactionTeacher to serve binary OK/NOT_OK classification labels on bot responses', 'run the QueryTeacher to extract and serve search query training data from FITS episodes', 'review the format_to_woi_consistent function that parses docs into WOI-compatible retrieved docs and titles', 'build the FiTS dataset by downloading and extracting the fits_data tarball into the datapath directory', 'build the FiTS v2 dataset by calling build with fits_task_version set to v2', 'get the correct data subdirectory path for a given FiTS task version and unseen task flag', 'review the build function to understand how it handles versioned dataset downloads and cleanup', 'summarize the RESOURCES list to see the downloadable FiTS dataset URL and SHA-256 checksum', 'normalize a reply string by stripping unwanted tokens and joining multiline text into a single line', 'append a knowledge sentence wrapped in special tokens to an existing context string', 'filter dialogue episodes by their last nonperfect feedback type using FeedbackMixin subclasses', 'mutate episode labels to use gold knowledge sentences with or without special tokens', 'prepare dialogue episodes for left-to-right classifier training by splitting context and final utterance']
```

Usage

```
{'build_fits_dataset': 'build the FiTS dataset by downloading and extracting the fits_data tarball into the datapath directory', 'build_fits_dataset_v2': 'build the FiTS v2 dataset by calling build with fits_task_version set to v2', 'get_dpath_by_task_version': 'get the correct data subdirectory path for a given FiTS task version and unseen task flag', 'review_build_function': 'review the build function to understand how it handles versioned dataset downloads and cleanup', 'summarize_resources': 'summarize the RESOURCES list to see the downloadable FiTS dataset URL and SHA-256 checksum'}
```

## File: facebookresearch_parlai/parlai/tasks/fits/mutators.py

Prompts

```
['run the FitsBaseTeacher to load and serve FITS dialogue data with metadata extraction', 'run the FitsFeedbackTeacher to serve free-form text feedback examples from FITS dialogues', 'run the FitsSatisfactionTeacher to serve binary OK/NOT_OK classification labels on bot responses', 'run the QueryTeacher to extract and serve search query training data from FITS episodes', 'review the format_to_woi_consistent function that parses docs into WOI-compatible retrieved docs and titles', 'build the FiTS dataset by downloading and extracting the fits_data tarball into the datapath directory', 'build the FiTS v2 dataset by calling build with fits_task_version set to v2', 'get the correct data subdirectory path for a given FiTS task version and unseen task flag', 'review the build function to understand how it handles versioned dataset downloads and cleanup', 'summarize the RESOURCES list to see the downloadable FiTS dataset URL and SHA-256 checksum', 'normalize a reply string by stripping unwanted tokens and joining multiline text into a single line', 'append a knowledge sentence wrapped in special tokens to an existing context string', 'filter dialogue episodes by their last nonperfect feedback type using FeedbackMixin subclasses', 'mutate episode labels to use gold knowledge sentences with or without special tokens', 'prepare dialogue episodes for left-to-right classifier training by splitting context and final utterance']
```

Usage

```
{'normalize_reply_text': 'normalize a reply string by stripping unwanted tokens and joining multiline text into a single line', 'append_knowledge_to_context': 'append a knowledge sentence wrapped in special tokens to an existing context string', 'filter_episodes_by_feedback': 'filter dialogue episodes by their last nonperfect feedback type using FeedbackMixin subclasses', 'mutate_gold_knowledge_labels': 'mutate episode labels to use gold knowledge sentences with or without special tokens', 'prepare_director_LTR_data': 'prepare dialogue episodes for left-to-right classifier training by splitting context and final utterance'}
```

