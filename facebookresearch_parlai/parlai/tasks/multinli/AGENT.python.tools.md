# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/multinli/agents.py

Prompts

```
['convert NLI premise and hypothesis text into a dialog format with label candidates', 'load and yield MultiNLI dataset pairs from a JSONL file in DialogData format', 'add dialog format and binary classes command line arguments to a ParlaiParser', 'return the list of label candidates for MultiNLI classification tasks', 'initialize a MultiNLI DialogTeacher with data path and optional binary class settings', 'build the MultiNLI dataset by downloading and extracting data to the ParlAI datapath directory', 'download the MultiNLI 1.0 zip file from NYU to the specified data path', 'check if the MultiNLI dataset has already been built at the given data path', 'remove an older version of the MultiNLI dataset before rebuilding with the latest version', 'mark the MultiNLI dataset build as complete with the current version string']
```

Usage

```
{'convert_to_dialogData': 'convert NLI premise and hypothesis text into a dialog format with label candidates', 'setup_data': 'load and yield MultiNLI dataset pairs from a JSONL file in DialogData format', 'DefaultTeacher_add_cmdline_args': 'add dialog format and binary classes command line arguments to a ParlaiParser', 'DefaultTeacher_label_candidates': 'return the list of label candidates for MultiNLI classification tasks', 'DefaultTeacher_init': 'initialize a MultiNLI DialogTeacher with data path and optional binary class settings'}
```

## File: facebookresearch_parlai/parlai/tasks/multinli/build.py

Prompts

```
['convert NLI premise and hypothesis text into a dialog format with label candidates', 'load and yield MultiNLI dataset pairs from a JSONL file in DialogData format', 'add dialog format and binary classes command line arguments to a ParlaiParser', 'return the list of label candidates for MultiNLI classification tasks', 'initialize a MultiNLI DialogTeacher with data path and optional binary class settings', 'build the MultiNLI dataset by downloading and extracting data to the ParlAI datapath directory', 'download the MultiNLI 1.0 zip file from NYU to the specified data path', 'check if the MultiNLI dataset has already been built at the given data path', 'remove an older version of the MultiNLI dataset before rebuilding with the latest version', 'mark the MultiNLI dataset build as complete with the current version string']
```

Usage

```
{'build_multinli_dataset': 'build the MultiNLI dataset by downloading and extracting data to the ParlAI datapath directory', 'download_multinli_resources': 'download the MultiNLI 1.0 zip file from NYU to the specified data path', 'check_multinli_built': 'check if the MultiNLI dataset has already been built at the given data path', 'remove_outdated_multinli': 'remove an older version of the MultiNLI dataset before rebuilding with the latest version', 'mark_multinli_done': 'mark the MultiNLI dataset build as complete with the current version string'}
```

