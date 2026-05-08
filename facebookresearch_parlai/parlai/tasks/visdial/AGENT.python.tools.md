# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/visdial/agents.py

Prompts

```
['build a VisDial visual dialog teacher that loads COCO images and question-answer dialog data', 'create a DefaultTeacher instance with opt config to enable Hogwild training with shared memory', 'setup VisDial dialog data by loading JSON questions, answers, and image paths from the data file', 'load an image from a file path and return it as an RGB PIL Image object', 'review the DefaultTeacher class and its setup_data method that yields question-answer pairs with image paths', 'run the build function to download and prepare the VisDial v0.9 dataset for ParlAI', 'download the VisDial train and validation zip files using the RESOURCES list of DownloadableFile objects', 'split the VisDial training data into train and valid sets using a constant stride to pick 1000 validation examples', 'rename the VisDial validation JSON file to a test JSON file using build_data.move', 'review the build function to understand how VisDial v0.9 data is downloaded, split, and marked as built']
```

Usage

```
{'build_visdial_teacher': 'build a VisDial visual dialog teacher that loads COCO images and question-answer dialog data', 'create_default_teacher': 'create a DefaultTeacher instance with opt config to enable Hogwild training with shared memory', 'setup_visdial_data': 'setup VisDial dialog data by loading JSON questions, answers, and image paths from the data file', 'load_image_pil': 'load an image from a file path and return it as an RGB PIL Image object', 'review_defaultteacher_class': 'review the DefaultTeacher class and its setup_data method that yields question-answer pairs with image paths'}
```

## File: facebookresearch_parlai/parlai/tasks/visdial/build.py

Prompts

```
['build a VisDial visual dialog teacher that loads COCO images and question-answer dialog data', 'create a DefaultTeacher instance with opt config to enable Hogwild training with shared memory', 'setup VisDial dialog data by loading JSON questions, answers, and image paths from the data file', 'load an image from a file path and return it as an RGB PIL Image object', 'review the DefaultTeacher class and its setup_data method that yields question-answer pairs with image paths', 'run the build function to download and prepare the VisDial v0.9 dataset for ParlAI', 'download the VisDial train and validation zip files using the RESOURCES list of DownloadableFile objects', 'split the VisDial training data into train and valid sets using a constant stride to pick 1000 validation examples', 'rename the VisDial validation JSON file to a test JSON file using build_data.move', 'review the build function to understand how VisDial v0.9 data is downloaded, split, and marked as built']
```

Usage

```
{'build_visdial_dataset': 'run the build function to download and prepare the VisDial v0.9 dataset for ParlAI', 'download_visdial_resources': 'download the VisDial train and validation zip files using the RESOURCES list of DownloadableFile objects', 'split_train_valid': 'split the VisDial training data into train and valid sets using a constant stride to pick 1000 validation examples', 'rename_val_to_test': 'rename the VisDial validation JSON file to a test JSON file using build_data.move', 'review_build_function': 'review the build function to understand how VisDial v0.9 data is downloaded, split, and marked as built'}
```

