# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/copa/agents.py

Prompts

```
['run the DefaultTeacher to load COPA dataset examples for cause and result reasoning tasks', 'build the COPA dataset path using _path to resolve train, valid, or test XML files', 'setup COPA data by parsing XML and yielding premise, answer, and answer options tuples', 'parse COPA XML data to extract premises, alternatives, and most plausible answers for reasoning', 'review the DefaultTeacher class to understand COPA cause and result question generation', 'build the COPA dataset by downloading resources and marking data as built', 'run the build function to download COPA-resources.tgz into the datapath directory', 'download the COPA dataset resources using the RESOURCES list of DownloadableFile objects', 'check if the COPA dataset has already been built in the datapath directory', 'remove outdated COPA dataset files before rebuilding with the build function']
```

Usage

```
{'run_copa_teacher': 'run the DefaultTeacher to load COPA dataset examples for cause and result reasoning tasks', 'build_copa_data_path': 'build the COPA dataset path using _path to resolve train, valid, or test XML files', 'setup_copa_data': 'setup COPA data by parsing XML and yielding premise, answer, and answer options tuples', 'parse_copa_xml': 'parse COPA XML data to extract premises, alternatives, and most plausible answers for reasoning', 'review_default_teacher': 'review the DefaultTeacher class to understand COPA cause and result question generation'}
```

## File: facebookresearch_parlai/parlai/tasks/copa/build.py

Prompts

```
['run the DefaultTeacher to load COPA dataset examples for cause and result reasoning tasks', 'build the COPA dataset path using _path to resolve train, valid, or test XML files', 'setup COPA data by parsing XML and yielding premise, answer, and answer options tuples', 'parse COPA XML data to extract premises, alternatives, and most plausible answers for reasoning', 'review the DefaultTeacher class to understand COPA cause and result question generation', 'build the COPA dataset by downloading resources and marking data as built', 'run the build function to download COPA-resources.tgz into the datapath directory', 'download the COPA dataset resources using the RESOURCES list of DownloadableFile objects', 'check if the COPA dataset has already been built in the datapath directory', 'remove outdated COPA dataset files before rebuilding with the build function']
```

Usage

```
{'build_copa_dataset': 'build the COPA dataset by downloading resources and marking data as built', 'run_build_function': 'run the build function to download COPA-resources.tgz into the datapath directory', 'download_copa_resources': 'download the COPA dataset resources using the RESOURCES list of DownloadableFile objects', 'check_copa_data_built': 'check if the COPA dataset has already been built in the datapath directory', 'remove_outdated_copa_data': 'remove outdated COPA dataset files before rebuilding with the build function'}
```

