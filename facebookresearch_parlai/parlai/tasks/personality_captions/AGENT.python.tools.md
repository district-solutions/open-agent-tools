# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/personality_captions/agents.py

Prompts

```
['run the PersonalityCaptionsTeacher to serve personality and caption examples from the dataset', 'create a PersonalityCaptionsTeacher instance with optional image loading and personality inclusion flags', 'test the PersonalityCaptionsTestTeacher using pretrained transresnet image features for evaluation', 'review the PersonalityCaptionsTeacher get method to understand how examples are constructed with labels and candidates', 'refactor the PersonalityCaptionsTeacher next_example method to customize background image loading behavior', 'build the personality_captions dataset by downloading data and images to the ParlAI datapath directory', 'run the build function to download and extract the personality_captions.tgz archive into the specified datapath', 'download YFCC100m images for the personality_captions task by calling download_images with an opt dictionary', 'review the build function that checks version, removes outdated data, and marks the dataset as done', 'summarize the RESOURCES list containing DownloadableFile entries for the personality_captions dataset archive', 'run the download_images script to download YFCC100m images for the personality_captions task', 'run the download_images CLI module with ParlaiParser to download images from S3', 'run the download_images function with task set to image_chat to download valid set images', 'review the download_images function that prompts for YFCC100m permission and downloads images via S3 URLs', 'summarize the download_images function that reads image hashes from JSON and downloads them in parallel']
```

Usage

```
{'run_PersonalityCaptionsTeacher': 'run the PersonalityCaptionsTeacher to serve personality and caption examples from the dataset', 'create_PersonalityCaptionsTeacher': 'create a PersonalityCaptionsTeacher instance with optional image loading and personality inclusion flags', 'test_PersonalityCaptionsTestTeacher': 'test the PersonalityCaptionsTestTeacher using pretrained transresnet image features for evaluation', 'review_PersonalityCaptionsTeacher_get': 'review the PersonalityCaptionsTeacher get method to understand how examples are constructed with labels and candidates', 'refactor_PersonalityCaptionsTeacher_next_example': 'refactor the PersonalityCaptionsTeacher next_example method to customize background image loading behavior'}
```

## File: facebookresearch_parlai/parlai/tasks/personality_captions/build.py

Prompts

```
['run the PersonalityCaptionsTeacher to serve personality and caption examples from the dataset', 'create a PersonalityCaptionsTeacher instance with optional image loading and personality inclusion flags', 'test the PersonalityCaptionsTestTeacher using pretrained transresnet image features for evaluation', 'review the PersonalityCaptionsTeacher get method to understand how examples are constructed with labels and candidates', 'refactor the PersonalityCaptionsTeacher next_example method to customize background image loading behavior', 'build the personality_captions dataset by downloading data and images to the ParlAI datapath directory', 'run the build function to download and extract the personality_captions.tgz archive into the specified datapath', 'download YFCC100m images for the personality_captions task by calling download_images with an opt dictionary', 'review the build function that checks version, removes outdated data, and marks the dataset as done', 'summarize the RESOURCES list containing DownloadableFile entries for the personality_captions dataset archive', 'run the download_images script to download YFCC100m images for the personality_captions task', 'run the download_images CLI module with ParlaiParser to download images from S3', 'run the download_images function with task set to image_chat to download valid set images', 'review the download_images function that prompts for YFCC100m permission and downloads images via S3 URLs', 'summarize the download_images function that reads image hashes from JSON and downloads them in parallel']
```

Usage

```
{'build_personality_captions_dataset': 'build the personality_captions dataset by downloading data and images to the ParlAI datapath directory', 'run_build_function': 'run the build function to download and extract the personality_captions.tgz archive into the specified datapath', 'download_yfcc_images': 'download YFCC100m images for the personality_captions task by calling download_images with an opt dictionary', 'review_build_function': 'review the build function that checks version, removes outdated data, and marks the dataset as done', 'summarize_resources_list': 'summarize the RESOURCES list containing DownloadableFile entries for the personality_captions dataset archive'}
```

## File: facebookresearch_parlai/parlai/tasks/personality_captions/download_images.py

Prompts

```
['run the PersonalityCaptionsTeacher to serve personality and caption examples from the dataset', 'create a PersonalityCaptionsTeacher instance with optional image loading and personality inclusion flags', 'test the PersonalityCaptionsTestTeacher using pretrained transresnet image features for evaluation', 'review the PersonalityCaptionsTeacher get method to understand how examples are constructed with labels and candidates', 'refactor the PersonalityCaptionsTeacher next_example method to customize background image loading behavior', 'build the personality_captions dataset by downloading data and images to the ParlAI datapath directory', 'run the build function to download and extract the personality_captions.tgz archive into the specified datapath', 'download YFCC100m images for the personality_captions task by calling download_images with an opt dictionary', 'review the build function that checks version, removes outdated data, and marks the dataset as done', 'summarize the RESOURCES list containing DownloadableFile entries for the personality_captions dataset archive', 'run the download_images script to download YFCC100m images for the personality_captions task', 'run the download_images CLI module with ParlaiParser to download images from S3', 'run the download_images function with task set to image_chat to download valid set images', 'review the download_images function that prompts for YFCC100m permission and downloads images via S3 URLs', 'summarize the download_images function that reads image hashes from JSON and downloads them in parallel']
```

Usage

```
{'run_download_images': 'run the download_images script to download YFCC100m images for the personality_captions task', 'run_download_images_cli': 'run the download_images CLI module with ParlaiParser to download images from S3', 'run_download_images_image_chat': 'run the download_images function with task set to image_chat to download valid set images', 'review_download_images': 'review the download_images function that prompts for YFCC100m permission and downloads images via S3 URLs', 'summarize_download_images': 'summarize the download_images function that reads image hashes from JSON and downloads them in parallel'}
```

