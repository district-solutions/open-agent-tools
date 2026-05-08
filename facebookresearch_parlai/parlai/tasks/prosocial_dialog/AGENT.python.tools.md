# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/prosocial_dialog/agents.py

Prompts

```
['run the ProsocialDialogSafetyTeacher to load prosocial dialog data with safety labels for dialogue safety classification', 'run the ProsocialDialogBinarySafetyTeacher to classify dialogues as __ok__ or __notok__ based on safety labels', 'run the ProsocialDialogTeacher to load prosocial dialog data with text and labels for dialogue generation tasks', 'review the ProsocialDialogSafetyTeacher setup_data method to understand how safety labels are extracted from JSON episodes', 'refactor the ProsocialDialogBinarySafetyTeacher to customize the binary safety label mapping from casual to ok or notok', 'run the build function to download and prepare the prosocial_dialog dataset into the specified datapath', 'review the build function to understand how prosocial_dialog data is downloaded and versioned', 'summarize the build function logic for downloading prosocial_dialog data and marking it as built', 'test the build function by passing an opt dict with a datapath key to download prosocial_dialog data', 'refactor the build function to support additional downloadable resources for the prosocial_dialog dataset']
```

Usage

```
{'run_prosocial_dialog_safety_teacher': 'run the ProsocialDialogSafetyTeacher to load prosocial dialog data with safety labels for dialogue safety classification', 'run_prosocial_dialog_binary_safety_teacher': 'run the ProsocialDialogBinarySafetyTeacher to classify dialogues as __ok__ or __notok__ based on safety labels', 'run_prosocial_dialog_teacher': 'run the ProsocialDialogTeacher to load prosocial dialog data with text and labels for dialogue generation tasks', 'review_prosocial_dialog_safety_teacher_setup_data': 'review the ProsocialDialogSafetyTeacher setup_data method to understand how safety labels are extracted from JSON episodes', 'refactor_prosocial_dialog_binary_safety_teacher': 'refactor the ProsocialDialogBinarySafetyTeacher to customize the binary safety label mapping from casual to ok or notok'}
```

## File: facebookresearch_parlai/parlai/tasks/prosocial_dialog/build.py

Prompts

```
['run the ProsocialDialogSafetyTeacher to load prosocial dialog data with safety labels for dialogue safety classification', 'run the ProsocialDialogBinarySafetyTeacher to classify dialogues as __ok__ or __notok__ based on safety labels', 'run the ProsocialDialogTeacher to load prosocial dialog data with text and labels for dialogue generation tasks', 'review the ProsocialDialogSafetyTeacher setup_data method to understand how safety labels are extracted from JSON episodes', 'refactor the ProsocialDialogBinarySafetyTeacher to customize the binary safety label mapping from casual to ok or notok', 'run the build function to download and prepare the prosocial_dialog dataset into the specified datapath', 'review the build function to understand how prosocial_dialog data is downloaded and versioned', 'summarize the build function logic for downloading prosocial_dialog data and marking it as built', 'test the build function by passing an opt dict with a datapath key to download prosocial_dialog data', 'refactor the build function to support additional downloadable resources for the prosocial_dialog dataset']
```

Usage

```
{'build_prosocial_dialog_data': 'run the build function to download and prepare the prosocial_dialog dataset into the specified datapath', 'review_build_function': 'review the build function to understand how prosocial_dialog data is downloaded and versioned', 'summarize_build_function': 'summarize the build function logic for downloading prosocial_dialog data and marking it as built', 'test_build_function': 'test the build function by passing an opt dict with a datapath key to download prosocial_dialog data', 'refactor_build_function': 'refactor the build function to support additional downloadable resources for the prosocial_dialog dataset'}
```

