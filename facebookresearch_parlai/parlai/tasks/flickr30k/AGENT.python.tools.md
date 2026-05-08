# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/flickr30k/agents.py

Prompts

```
['build a Flickr30k DefaultTeacher to load image-caption pairs for training a vision-language model', 'create a DefaultTeacher instance with options for image mode and candidate count for evaluation', 'test the DefaultTeacher get method to retrieve image IDs and caption labels by episode index', 'review the DefaultTeacher next_example method that prefetches images in the background for each example', 'refactor the DefaultTeacher _setup_data method to filter dataset splits and build candidate lists', 'run the build function to download and set up the Flickr30k dataset in the specified datapath', 'review the build function that downloads Flickr30k data and manages versioned data directories', 'refactor the build function to support a newer version string for the Flickr30k dataset', 'test the build function to verify it downloads the Flickr30k tgz file and marks data as built', 'summarize the RESOURCES list containing DownloadableFile entries for the Flickr30k dataset archive']
```

Usage

```
{'build_flickr30k_teacher': 'build a Flickr30k DefaultTeacher to load image-caption pairs for training a vision-language model', 'create_defaultteacher_instance': 'create a DefaultTeacher instance with options for image mode and candidate count for evaluation', 'test_get_method': 'test the DefaultTeacher get method to retrieve image IDs and caption labels by episode index', 'review_next_example': 'review the DefaultTeacher next_example method that prefetches images in the background for each example', 'refactor_setup_data': 'refactor the DefaultTeacher _setup_data method to filter dataset splits and build candidate lists'}
```

## File: facebookresearch_parlai/parlai/tasks/flickr30k/build.py

Prompts

```
['build a Flickr30k DefaultTeacher to load image-caption pairs for training a vision-language model', 'create a DefaultTeacher instance with options for image mode and candidate count for evaluation', 'test the DefaultTeacher get method to retrieve image IDs and caption labels by episode index', 'review the DefaultTeacher next_example method that prefetches images in the background for each example', 'refactor the DefaultTeacher _setup_data method to filter dataset splits and build candidate lists', 'run the build function to download and set up the Flickr30k dataset in the specified datapath', 'review the build function that downloads Flickr30k data and manages versioned data directories', 'refactor the build function to support a newer version string for the Flickr30k dataset', 'test the build function to verify it downloads the Flickr30k tgz file and marks data as built', 'summarize the RESOURCES list containing DownloadableFile entries for the Flickr30k dataset archive']
```

Usage

```
{'build_flickr30k_dataset': 'run the build function to download and set up the Flickr30k dataset in the specified datapath', 'review_build_function': 'review the build function that downloads Flickr30k data and manages versioned data directories', 'refactor_build_versioning': 'refactor the build function to support a newer version string for the Flickr30k dataset', 'test_build_download': 'test the build function to verify it downloads the Flickr30k tgz file and marks data as built', 'summarize_resources_list': 'summarize the RESOURCES list containing DownloadableFile entries for the Flickr30k dataset archive'}
```

