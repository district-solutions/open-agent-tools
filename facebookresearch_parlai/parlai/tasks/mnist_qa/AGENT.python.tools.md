# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/mnist_qa/agents.py

Prompts

```
['run the MnistQATeacher to serve MNIST digit images with question answering labels for model training', 'setup MNIST QA data by loading labels from a JSON file and yielding image paths with questions', 'get the label candidates for MNIST QA including digits 0-9 and their English word equivalents', 'build the MNIST QA labels and image file paths from the provided ParlAI options dictionary', 'create a DefaultTeacher instance that inherits from MnistQATeacher for use as the task entry point', 'run the build function to download and prepare MNIST QA data into the ParlAI datapath directory', 'download the MNIST tarball from parl.ai into the specified data path directory', 'check whether the MNIST QA data has already been built in the datapath directory', 'remove outdated MNIST QA data files when a newer version needs to be built', 'mark the MNIST QA data build as complete after downloading and extracting files']
```

Usage

```
{'run_mnist_qa_teacher': 'run the MnistQATeacher to serve MNIST digit images with question answering labels for model training', 'setup_mnist_qa_data': 'setup MNIST QA data by loading labels from a JSON file and yielding image paths with questions', 'get_label_candidates': 'get the label candidates for MNIST QA including digits 0-9 and their English word equivalents', 'build_mnist_qa_paths': 'build the MNIST QA labels and image file paths from the provided ParlAI options dictionary', 'create_default_teacher': 'create a DefaultTeacher instance that inherits from MnistQATeacher for use as the task entry point'}
```

## File: facebookresearch_parlai/parlai/tasks/mnist_qa/build.py

Prompts

```
['run the MnistQATeacher to serve MNIST digit images with question answering labels for model training', 'setup MNIST QA data by loading labels from a JSON file and yielding image paths with questions', 'get the label candidates for MNIST QA including digits 0-9 and their English word equivalents', 'build the MNIST QA labels and image file paths from the provided ParlAI options dictionary', 'create a DefaultTeacher instance that inherits from MnistQATeacher for use as the task entry point', 'run the build function to download and prepare MNIST QA data into the ParlAI datapath directory', 'download the MNIST tarball from parl.ai into the specified data path directory', 'check whether the MNIST QA data has already been built in the datapath directory', 'remove outdated MNIST QA data files when a newer version needs to be built', 'mark the MNIST QA data build as complete after downloading and extracting files']
```

Usage

```
{'build_mnist_qa_data': 'run the build function to download and prepare MNIST QA data into the ParlAI datapath directory', 'download_mnist_tarball': 'download the MNIST tarball from parl.ai into the specified data path directory', 'check_mnist_data_built': 'check whether the MNIST QA data has already been built in the datapath directory', 'remove_outdated_mnist_data': 'remove outdated MNIST QA data files when a newer version needs to be built', 'mark_mnist_data_done': 'mark the MNIST QA data build as complete after downloading and extracting files'}
```

