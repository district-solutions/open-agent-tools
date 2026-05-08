# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/redial/agents.py

Prompts

```
['build a ReDialTeacher instance to load and serve ReDial dialogue dataset episodes for training', 'create a movie title to ID mapping dictionary from the movies_with_mentions CSV file', 'remove the year portion from a movie title string like Title (Year) to get Title', 'replace movie ID placeholders like @123 in text with actual movie titles using an ID map', 'get a dialogue turn with text and labels from a specific episode and entry index', 'run the build function to download and set up the ReDial dataset into the specified datapath', 'review the build function that checks version, downloads the ReDial dataset, and marks data as done', 'summarize the build function logic for downloading and versioning the ReDial dataset', 'refactor the build function to support multiple downloadable resources instead of a single file', 'test the build function to verify it downloads the ReDial dataset and marks the directory as built']
```

Usage

```
{'build_redial_teacher': 'build a ReDialTeacher instance to load and serve ReDial dialogue dataset episodes for training', 'create_title_id_map': 'create a movie title to ID mapping dictionary from the movies_with_mentions CSV file', 'remove_year_from_title': 'remove the year portion from a movie title string like Title (Year) to get Title', 'replace_movie_ids': 'replace movie ID placeholders like @123 in text with actual movie titles using an ID map', 'get_dialogue_example': 'get a dialogue turn with text and labels from a specific episode and entry index'}
```

## File: facebookresearch_parlai/parlai/tasks/redial/build.py

Prompts

```
['build a ReDialTeacher instance to load and serve ReDial dialogue dataset episodes for training', 'create a movie title to ID mapping dictionary from the movies_with_mentions CSV file', 'remove the year portion from a movie title string like Title (Year) to get Title', 'replace movie ID placeholders like @123 in text with actual movie titles using an ID map', 'get a dialogue turn with text and labels from a specific episode and entry index', 'run the build function to download and set up the ReDial dataset into the specified datapath', 'review the build function that checks version, downloads the ReDial dataset, and marks data as done', 'summarize the build function logic for downloading and versioning the ReDial dataset', 'refactor the build function to support multiple downloadable resources instead of a single file', 'test the build function to verify it downloads the ReDial dataset and marks the directory as built']
```

Usage

```
{'build_redial_dataset': 'run the build function to download and set up the ReDial dataset into the specified datapath', 'review_build_function': 'review the build function that checks version, downloads the ReDial dataset, and marks data as done', 'summarize_build_function': 'summarize the build function logic for downloading and versioning the ReDial dataset', 'refactor_build_function': 'refactor the build function to support multiple downloadable resources instead of a single file', 'test_build_function': 'test the build function to verify it downloads the ReDial dataset and marks the directory as built'}
```

