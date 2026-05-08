# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/dialogue_nli/agents.py

Prompts

```
['build a DialogueNliTeacher to load and serve dialogue NLI data from JSONL files', 'configure the DialogueNliTeacher with dialog format to remove Premise and Hypothesis tokens', 'configure the DialogueNliTeacher with binary classes for contradiction versus not contradiction labels', 'get a dialogue NLI example by episode index using the DialogueNliTeacher get method', 'load the ExtrasTeacher to serve extra dialogue NLI training data with corrupted JSON handling', 'run the build function to download and set up the dialogue_nli dataset in the datapath directory', 'download the dialogue_nli.zip file from Google Drive using the provided file ID and checksum', 'check if the dialogue_nli dataset has already been built at the specified version', 'remove an older version of the dialogue_nli dataset directory before rebuilding', 'mark the dialogue_nli dataset as built with version 1.0 after downloading completes']
```

Usage

```
{'build_dnli_teacher': 'build a DialogueNliTeacher to load and serve dialogue NLI data from JSONL files', 'configure_dialog_format': 'configure the DialogueNliTeacher with dialog format to remove Premise and Hypothesis tokens', 'configure_binary_classes': 'configure the DialogueNliTeacher with binary classes for contradiction versus not contradiction labels', 'get_dnli_example': 'get a dialogue NLI example by episode index using the DialogueNliTeacher get method', 'load_extras_teacher': 'load the ExtrasTeacher to serve extra dialogue NLI training data with corrupted JSON handling'}
```

## File: facebookresearch_parlai/parlai/tasks/dialogue_nli/build.py

Prompts

```
['build a DialogueNliTeacher to load and serve dialogue NLI data from JSONL files', 'configure the DialogueNliTeacher with dialog format to remove Premise and Hypothesis tokens', 'configure the DialogueNliTeacher with binary classes for contradiction versus not contradiction labels', 'get a dialogue NLI example by episode index using the DialogueNliTeacher get method', 'load the ExtrasTeacher to serve extra dialogue NLI training data with corrupted JSON handling', 'run the build function to download and set up the dialogue_nli dataset in the datapath directory', 'download the dialogue_nli.zip file from Google Drive using the provided file ID and checksum', 'check if the dialogue_nli dataset has already been built at the specified version', 'remove an older version of the dialogue_nli dataset directory before rebuilding', 'mark the dialogue_nli dataset as built with version 1.0 after downloading completes']
```

Usage

```
{'build_dialogue_nli_data': 'run the build function to download and set up the dialogue_nli dataset in the datapath directory', 'download_dialogue_nli_zip': 'download the dialogue_nli.zip file from Google Drive using the provided file ID and checksum', 'check_dialogue_nli_built': 'check if the dialogue_nli dataset has already been built at the specified version', 'remove_outdated_dialogue_nli': 'remove an older version of the dialogue_nli dataset directory before rebuilding', 'mark_dialogue_nli_done': 'mark the dialogue_nli dataset as built with version 1.0 after downloading completes'}
```

