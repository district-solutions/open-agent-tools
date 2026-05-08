# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/nlvr/agents.py

Prompts

```
['run the NLVR DialogTeacher to load and serve natural language visual reasoning data', 'review the DefaultTeacher setup_data method that parses NLVR JSON questions and yields image paths', 'review the DefaultTeacher label_candidates method that returns true and false as possible answers', 'summarize the _path function that resolves NLVR dataset file paths for train dev and test splits', 'test the DefaultTeacher class to verify it correctly loads NLVR questions and image file paths', 'run the build function to download and set up the NLVR dataset in the ParlAI datapath directory', 'download the NLVR dataset zip file from the clic-lab GitHub repository using the RESOURCES list', 'check if the NLVR dataset has already been built in the specified data path directory', 'remove the outdated NLVR dataset directory before rebuilding with fresh downloaded data', 'mark the NLVR dataset build as complete after downloading all resources to the data path']
```

Usage

```
{'run_DefaultTeacher': 'run the NLVR DialogTeacher to load and serve natural language visual reasoning data', 'review_DefaultTeacher_setup_data': 'review the DefaultTeacher setup_data method that parses NLVR JSON questions and yields image paths', 'review_DefaultTeacher_label_candidates': 'review the DefaultTeacher label_candidates method that returns true and false as possible answers', 'summarize__path': 'summarize the _path function that resolves NLVR dataset file paths for train dev and test splits', 'test_DefaultTeacher': 'test the DefaultTeacher class to verify it correctly loads NLVR questions and image file paths'}
```

## File: facebookresearch_parlai/parlai/tasks/nlvr/build.py

Prompts

```
['run the NLVR DialogTeacher to load and serve natural language visual reasoning data', 'review the DefaultTeacher setup_data method that parses NLVR JSON questions and yields image paths', 'review the DefaultTeacher label_candidates method that returns true and false as possible answers', 'summarize the _path function that resolves NLVR dataset file paths for train dev and test splits', 'test the DefaultTeacher class to verify it correctly loads NLVR questions and image file paths', 'run the build function to download and set up the NLVR dataset in the ParlAI datapath directory', 'download the NLVR dataset zip file from the clic-lab GitHub repository using the RESOURCES list', 'check if the NLVR dataset has already been built in the specified data path directory', 'remove the outdated NLVR dataset directory before rebuilding with fresh downloaded data', 'mark the NLVR dataset build as complete after downloading all resources to the data path']
```

Usage

```
{'build_nlvr_dataset': 'run the build function to download and set up the NLVR dataset in the ParlAI datapath directory', 'download_nlvr_resources': 'download the NLVR dataset zip file from the clic-lab GitHub repository using the RESOURCES list', 'check_nlvr_built_status': 'check if the NLVR dataset has already been built in the specified data path directory', 'remove_outdated_nlvr_data': 'remove the outdated NLVR dataset directory before rebuilding with fresh downloaded data', 'mark_nlvr_build_done': 'mark the NLVR dataset build as complete after downloading all resources to the data path'}
```

