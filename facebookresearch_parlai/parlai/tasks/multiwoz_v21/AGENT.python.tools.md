# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/multiwoz_v21/agents.py

Prompts

```
['build the MultiWOZ 2.1 dataset by calling the build function to download and prepare data files', 'create a MultiWozTeacher instance with an opt dictionary to load and serve MultiWOZ dialogue data', 'setup dialogue data by loading data.json and splitting into train, validation, and test sets', 'get a dialogue example by episode and entry index returning text and labels from the conversation log', 'count the total number of dialogue turn examples across all conversations in the dataset', 'run the build function to download and set up the MultiWOZ 2.1 dataset into the Parlai datapath', 'review the build function that checks version, downloads resources, and marks the MultiWOZ 2.1 dataset as built', 'review the RESOURCES list containing the DownloadableFile entry for the MultiWOZ 2.1 zip archive', 'summarize the build workflow that downloads MultiWOZ 2.1 data, creates directories, and marks completion with version tracking', 'refactor the build function to support a newer version string for the MultiWOZ 2.1 dataset']
```

Usage

```
{'build_multiwoz_dataset': 'build the MultiWOZ 2.1 dataset by calling the build function to download and prepare data files', 'create_teacher_instance': 'create a MultiWozTeacher instance with an opt dictionary to load and serve MultiWOZ dialogue data', 'setup_dialogue_data': 'setup dialogue data by loading data.json and splitting into train, validation, and test sets', 'get_dialogue_example': 'get a dialogue example by episode and entry index returning text and labels from the conversation log', 'count_dialogue_examples': 'count the total number of dialogue turn examples across all conversations in the dataset'}
```

## File: facebookresearch_parlai/parlai/tasks/multiwoz_v21/build.py

Prompts

```
['build the MultiWOZ 2.1 dataset by calling the build function to download and prepare data files', 'create a MultiWozTeacher instance with an opt dictionary to load and serve MultiWOZ dialogue data', 'setup dialogue data by loading data.json and splitting into train, validation, and test sets', 'get a dialogue example by episode and entry index returning text and labels from the conversation log', 'count the total number of dialogue turn examples across all conversations in the dataset', 'run the build function to download and set up the MultiWOZ 2.1 dataset into the Parlai datapath', 'review the build function that checks version, downloads resources, and marks the MultiWOZ 2.1 dataset as built', 'review the RESOURCES list containing the DownloadableFile entry for the MultiWOZ 2.1 zip archive', 'summarize the build workflow that downloads MultiWOZ 2.1 data, creates directories, and marks completion with version tracking', 'refactor the build function to support a newer version string for the MultiWOZ 2.1 dataset']
```

Usage

```
{'build_multiwoz_v21_data': 'run the build function to download and set up the MultiWOZ 2.1 dataset into the Parlai datapath', 'review_build_function': 'review the build function that checks version, downloads resources, and marks the MultiWOZ 2.1 dataset as built', 'review_resources_list': 'review the RESOURCES list containing the DownloadableFile entry for the MultiWOZ 2.1 zip archive', 'summarize_build_workflow': 'summarize the build workflow that downloads MultiWOZ 2.1 data, creates directories, and marks completion with version tracking', 'refactor_build_versioning': 'refactor the build function to support a newer version string for the MultiWOZ 2.1 dataset'}
```

