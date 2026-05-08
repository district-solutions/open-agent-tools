# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/style_gen/agents.py

Prompts

```
['get the filepath for a style-labeled dataset with Image-Chat personalities attached to each example', 'get the path to the list of personalities from the Image-Chat train set', 'create a ParlAI dialog teacher for BlendedSkillTalk data with Image-Chat personalities added to examples', 'create a wrapper teacher that concatenates previous and current utterances for style classification training', 'create a wrapper teacher that uses only the current utterance for style classification training', 'build the style labeled datasets by downloading and extracting them to the data path', 'build the personality list by downloading it to the style_gen task data folder', 'get the file path to the style labeled datasets folder given a data path', 'review the style labeled datasets downloadable file resources and their checksums', 'review the personality list downloadable file resource and its configuration']
```

Usage

```
{'get_style_labeled_data_path': 'get the filepath for a style-labeled dataset with Image-Chat personalities attached to each example', 'get_personality_list_path': 'get the path to the list of personalities from the Image-Chat train set', 'LabeledBlendedSkillTalkTeacher': 'create a ParlAI dialog teacher for BlendedSkillTalk data with Image-Chat personalities added to examples', 'PrevCurrUttStyleTeacher': 'create a wrapper teacher that concatenates previous and current utterances for style classification training', 'CurrUttOnlyStyleTeacher': 'create a wrapper teacher that uses only the current utterance for style classification training'}
```

## File: facebookresearch_parlai/parlai/tasks/style_gen/build.py

Prompts

```
['get the filepath for a style-labeled dataset with Image-Chat personalities attached to each example', 'get the path to the list of personalities from the Image-Chat train set', 'create a ParlAI dialog teacher for BlendedSkillTalk data with Image-Chat personalities added to examples', 'create a wrapper teacher that concatenates previous and current utterances for style classification training', 'create a wrapper teacher that uses only the current utterance for style classification training', 'build the style labeled datasets by downloading and extracting them to the data path', 'build the personality list by downloading it to the style_gen task data folder', 'get the file path to the style labeled datasets folder given a data path', 'review the style labeled datasets downloadable file resources and their checksums', 'review the personality list downloadable file resource and its configuration']
```

Usage

```
{'build_style_labeled_datasets': 'build the style labeled datasets by downloading and extracting them to the data path', 'build_personality_list': 'build the personality list by downloading it to the style_gen task data folder', 'get_style_labeled_data_folder': 'get the file path to the style labeled datasets folder given a data path', 'review_STYLE_LABELED_DATASETS_RESOURCES': 'review the style labeled datasets downloadable file resources and their checksums', 'review_PERSONALITY_LIST_RESOURCES': 'review the personality list downloadable file resource and its configuration'}
```

