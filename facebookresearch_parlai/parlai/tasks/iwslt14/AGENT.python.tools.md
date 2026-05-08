# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/iwslt14/agents.py

Prompts

```
['build a Parlai IWSLT14 translation teacher to load German-English or English-German parallel data', 'create an EnDeTeacher instance to load English-to-German IWSLT14 translation data for training', 'create a DeEnTeacher instance to load German-to-English IWSLT14 translation data for training', 'review the DefaultTeacher setup_data method to understand how source and target files are paired and yielded', 'summarize the _format function that strips whitespace and replaces ##AT##-##AT## with __AT__', 'build the iwslt14 dataset by downloading and extracting data files to the datapath directory', 'run the build function to download iwslt14 data given an opt dictionary with datapath', 'download the iwslt14 tgz resource file using the RESOURCES list of DownloadableFile objects', 'review the build function to understand how it checks version and manages outdated data directories', 'summarize the iwslt14 build module that downloads and marks dataset data as built']
```

Usage

```
{'build_iwslt14_teacher': 'build a Parlai IWSLT14 translation teacher to load German-English or English-German parallel data', 'create_en_de_teacher': 'create an EnDeTeacher instance to load English-to-German IWSLT14 translation data for training', 'create_de_en_teacher': 'create a DeEnTeacher instance to load German-to-English IWSLT14 translation data for training', 'review_defaultteacher_setup_data': 'review the DefaultTeacher setup_data method to understand how source and target files are paired and yielded', 'summarize_format_function': 'summarize the _format function that strips whitespace and replaces ##AT##-##AT## with __AT__'}
```

## File: facebookresearch_parlai/parlai/tasks/iwslt14/build.py

Prompts

```
['build a Parlai IWSLT14 translation teacher to load German-English or English-German parallel data', 'create an EnDeTeacher instance to load English-to-German IWSLT14 translation data for training', 'create a DeEnTeacher instance to load German-to-English IWSLT14 translation data for training', 'review the DefaultTeacher setup_data method to understand how source and target files are paired and yielded', 'summarize the _format function that strips whitespace and replaces ##AT##-##AT## with __AT__', 'build the iwslt14 dataset by downloading and extracting data files to the datapath directory', 'run the build function to download iwslt14 data given an opt dictionary with datapath', 'download the iwslt14 tgz resource file using the RESOURCES list of DownloadableFile objects', 'review the build function to understand how it checks version and manages outdated data directories', 'summarize the iwslt14 build module that downloads and marks dataset data as built']
```

Usage

```
{'build_iwslt14_data': 'build the iwslt14 dataset by downloading and extracting data files to the datapath directory', 'run_build_function': 'run the build function to download iwslt14 data given an opt dictionary with datapath', 'download_iwslt14_resources': 'download the iwslt14 tgz resource file using the RESOURCES list of DownloadableFile objects', 'review_build_function': 'review the build function to understand how it checks version and manages outdated data directories', 'summarize_build_module': 'summarize the iwslt14 build module that downloads and marks dataset data as built'}
```

