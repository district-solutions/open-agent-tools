# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/opensubtitles/agents.py

Prompts

```
['run the DefaultTeacher to load all OpenSubtitles 2018 dialog examples with history', 'create a FullTeacher instance to generate all possible dialog examples from OpenSubtitles data', 'create a HalfTeacher instance to generate half of all possible dialog examples from OpenSubtitles', 'run the Task100kTeacher to load a subset of 100,000 dialogs from OpenSubtitles', 'run the V2018NoHistoryTeacher to load two-turn dialog examples without conversation history', 'run the build function to download and prepare OpenSubtitles 2009 dataset for Parlai', 'create train valid and test dialog files from gzipped OpenSubtitles XML data', 'clean and normalize a sentence by removing HTML entities and special characters', 'download the OpenSubtitles English tar.gz archive using the RESOURCES DownloadableFile list', 'review the build function workflow for downloading cleaning and splitting OpenSubtitles data', 'run create_fb_format to convert subtitle XML files into Parlai dialogue format with multiprocessing', 'parse an OpenSubtitles XML or gzipped XML file and return an ElementTree object', 'clean a subtitle sentence by removing brackets, normalizing apostrophes, and filtering noisy text', 'extract timed conversations from an OpenSubtitles XML file using time-based sentence grouping']
```

Usage

```
{'run_DefaultTeacher': 'run the DefaultTeacher to load all OpenSubtitles 2018 dialog examples with history', 'create_FullTeacher': 'create a FullTeacher instance to generate all possible dialog examples from OpenSubtitles data', 'create_HalfTeacher': 'create a HalfTeacher instance to generate half of all possible dialog examples from OpenSubtitles', 'run_Task100kTeacher': 'run the Task100kTeacher to load a subset of 100,000 dialogs from OpenSubtitles', 'run_V2018NoHistoryTeacher': 'run the V2018NoHistoryTeacher to load two-turn dialog examples without conversation history'}
```

## File: facebookresearch_parlai/parlai/tasks/opensubtitles/build_2009.py

Prompts

```
['run the DefaultTeacher to load all OpenSubtitles 2018 dialog examples with history', 'create a FullTeacher instance to generate all possible dialog examples from OpenSubtitles data', 'create a HalfTeacher instance to generate half of all possible dialog examples from OpenSubtitles', 'run the Task100kTeacher to load a subset of 100,000 dialogs from OpenSubtitles', 'run the V2018NoHistoryTeacher to load two-turn dialog examples without conversation history', 'run the build function to download and prepare OpenSubtitles 2009 dataset for Parlai', 'create train valid and test dialog files from gzipped OpenSubtitles XML data', 'clean and normalize a sentence by removing HTML entities and special characters', 'download the OpenSubtitles English tar.gz archive using the RESOURCES DownloadableFile list', 'review the build function workflow for downloading cleaning and splitting OpenSubtitles data', 'run create_fb_format to convert subtitle XML files into Parlai dialogue format with multiprocessing', 'parse an OpenSubtitles XML or gzipped XML file and return an ElementTree object', 'clean a subtitle sentence by removing brackets, normalizing apostrophes, and filtering noisy text', 'extract timed conversations from an OpenSubtitles XML file using time-based sentence grouping']
```

Usage

```
{'build_opensubtitles_data': 'run the build function to download and prepare OpenSubtitles 2009 dataset for Parlai', 'create_fb_format_dialogs': 'create train valid and test dialog files from gzipped OpenSubtitles XML data', 'regularize_sentence_text': 'clean and normalize a sentence by removing HTML entities and special characters', 'download_opensubtitles_resource': 'download the OpenSubtitles English tar.gz archive using the RESOURCES DownloadableFile list', 'review_build_data_workflow': 'review the build function workflow for downloading cleaning and splitting OpenSubtitles data'}
```

## File: facebookresearch_parlai/parlai/tasks/opensubtitles/build_2018.py

Prompts

```
['run the DefaultTeacher to load all OpenSubtitles 2018 dialog examples with history', 'create a FullTeacher instance to generate all possible dialog examples from OpenSubtitles data', 'create a HalfTeacher instance to generate half of all possible dialog examples from OpenSubtitles', 'run the Task100kTeacher to load a subset of 100,000 dialogs from OpenSubtitles', 'run the V2018NoHistoryTeacher to load two-turn dialog examples without conversation history', 'run the build function to download and prepare OpenSubtitles 2009 dataset for Parlai', 'create train valid and test dialog files from gzipped OpenSubtitles XML data', 'clean and normalize a sentence by removing HTML entities and special characters', 'download the OpenSubtitles English tar.gz archive using the RESOURCES DownloadableFile list', 'review the build function workflow for downloading cleaning and splitting OpenSubtitles data', 'run create_fb_format to convert subtitle XML files into Parlai dialogue format with multiprocessing', 'parse an OpenSubtitles XML or gzipped XML file and return an ElementTree object', 'clean a subtitle sentence by removing brackets, normalizing apostrophes, and filtering noisy text', 'extract timed conversations from an OpenSubtitles XML file using time-based sentence grouping']
```

Usage

```
{'build_opensubtitles_data': 'build the OpenSubtitles 2018 dataset by downloading, parsing XML subtitles, and creating train/valid/test splits', 'run_create_fb_format': 'run create_fb_format to convert subtitle XML files into Parlai dialogue format with multiprocessing', 'parse_xml_subtitles': 'parse an OpenSubtitles XML or gzipped XML file and return an ElementTree object', 'clean_text_sentence': 'clean a subtitle sentence by removing brackets, normalizing apostrophes, and filtering noisy text', 'extract_conversations_from_xml': 'extract timed conversations from an OpenSubtitles XML file using time-based sentence grouping'}
```

