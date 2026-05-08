# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/eli5/agents.py

Prompts

```
['create an ELI5Teacher instance to load and serve ELI5 dataset episodes for dialogue training', 'load ELI5 dataset from JSON files with optional supporting document knowledge included in text', 'add ELI5-specific command line arguments including the knowledge flag to a ParlaiParser', 'get a specific episode by index from the loaded ELI5 messages dataset', 'review the ELI5Teacher class and its methods for loading and serving ELI5 dialogue data', 'build the ELI5 dataset by downloading pre-computed resources and unzipping gz files into the datapath directory', 'run setup_dir to create a named subdirectory under a given base path if it does not already exist', 'download the ELI5 pre-computed resources including wet.paths, ccrawl IDs, and unigram counts from S3', 'verify that the ELI5 wet.paths and ccrawl IDs files have been unzipped and the train test valid splits exist', 'review the build function to understand how ELI5 data is downloaded, unzipped, and versioned in ParlAI']
```

Usage

```
{'create_ELI5Teacher': 'create an ELI5Teacher instance to load and serve ELI5 dataset episodes for dialogue training', 'load_eli5_data': 'load ELI5 dataset from JSON files with optional supporting document knowledge included in text', 'add_cmdline_args': 'add ELI5-specific command line arguments including the knowledge flag to a ParlaiParser', 'get_episode': 'get a specific episode by index from the loaded ELI5 messages dataset', 'review_ELI5Teacher': 'review the ELI5Teacher class and its methods for loading and serving ELI5 dialogue data'}
```

## File: facebookresearch_parlai/parlai/tasks/eli5/build.py

Prompts

```
['create an ELI5Teacher instance to load and serve ELI5 dataset episodes for dialogue training', 'load ELI5 dataset from JSON files with optional supporting document knowledge included in text', 'add ELI5-specific command line arguments including the knowledge flag to a ParlaiParser', 'get a specific episode by index from the loaded ELI5 messages dataset', 'review the ELI5Teacher class and its methods for loading and serving ELI5 dialogue data', 'build the ELI5 dataset by downloading pre-computed resources and unzipping gz files into the datapath directory', 'run setup_dir to create a named subdirectory under a given base path if it does not already exist', 'download the ELI5 pre-computed resources including wet.paths, ccrawl IDs, and unigram counts from S3', 'verify that the ELI5 wet.paths and ccrawl IDs files have been unzipped and the train test valid splits exist', 'review the build function to understand how ELI5 data is downloaded, unzipped, and versioned in ParlAI']
```

Usage

```
{'build_eli5_data': 'build the ELI5 dataset by downloading pre-computed resources and unzipping gz files into the datapath directory', 'run_setup_dir': 'run setup_dir to create a named subdirectory under a given base path if it does not already exist', 'download_eli5_resources': 'download the ELI5 pre-computed resources including wet.paths, ccrawl IDs, and unigram counts from S3', 'verify_eli5_build': 'verify that the ELI5 wet.paths and ccrawl IDs files have been unzipped and the train test valid splits exist', 'review_build_function': 'review the build function to understand how ELI5 data is downloaded, unzipped, and versioned in ParlAI'}
```

