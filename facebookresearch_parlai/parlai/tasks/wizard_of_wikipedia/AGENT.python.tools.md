# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/wizard_of_wikipedia/agents.py

Prompts

```
['build a Parlai teacher that formats Wizard of Wikipedia dialog with knowledge passages and label candidates', 'run the RareWordF1Calculator class to compute F1 scores emphasizing infrequent words in a corpus', 'create a GeneratorTeacher for training a knowledge-grounded response generator with configurable dropout and gold knowledge prepending', 'review the DocreaderTeacher class and its teacher types for training document retrieval and sentence selection models', 'test the WikiPageTitleTeacher to generate Wikipedia page titles from conversation history context', 'build the wizard of wikipedia dataset by downloading and extracting the data archive', 'run the build function to download wizard of wikipedia data to the specified datapath', 'review the build function that downloads and sets up the wizard of wikipedia dataset', 'summarize the build function that handles downloading and versioning of wizard of wikipedia data', 'test the build function to verify it correctly downloads and marks wizard of wikipedia data as built', 'add the checked sentence wrapped in knowledge tokens to the end of a message text field', 'replace message labels with the checked sentence and store original labels as dialogue_response', 'append the dialogue response label wrapped in label tokens to the end of the message text', 'split the dialogue response at a random word and wrap the second half in label tokens for language modeling', 'filter dialogue episodes to include or exclude examples based on whether a knowledge passage was used', 'run an interactive Wizard of Wikipedia dialogue with a human agent and model agent', 'run an interactive Wizard of Wikipedia dialogue with gold knowledge prepended to dialogue input', 'run a self-chat Wizard of Wikipedia world where two agents chat on a random topic', 'review the InteractiveWorld parley method that loops between wizard and apprentice agents with knowledge retrieval', 'refactor the InteractiveWorld knowledge agent setup to use a different retriever model']
```

Usage

```
{'build_wizard_dialog_knowledge_teacher': 'build a Parlai teacher that formats Wizard of Wikipedia dialog with knowledge passages and label candidates', 'run_rare_word_f1_calculator': 'run the RareWordF1Calculator class to compute F1 scores emphasizing infrequent words in a corpus', 'create_generator_teacher': 'create a GeneratorTeacher for training a knowledge-grounded response generator with configurable dropout and gold knowledge prepending', 'review_docreader_teacher': 'review the DocreaderTeacher class and its teacher types for training document retrieval and sentence selection models', 'test_wiki_page_title_teacher': 'test the WikiPageTitleTeacher to generate Wikipedia page titles from conversation history context'}
```

## File: facebookresearch_parlai/parlai/tasks/wizard_of_wikipedia/build.py

Prompts

```
['build a Parlai teacher that formats Wizard of Wikipedia dialog with knowledge passages and label candidates', 'run the RareWordF1Calculator class to compute F1 scores emphasizing infrequent words in a corpus', 'create a GeneratorTeacher for training a knowledge-grounded response generator with configurable dropout and gold knowledge prepending', 'review the DocreaderTeacher class and its teacher types for training document retrieval and sentence selection models', 'test the WikiPageTitleTeacher to generate Wikipedia page titles from conversation history context', 'build the wizard of wikipedia dataset by downloading and extracting the data archive', 'run the build function to download wizard of wikipedia data to the specified datapath', 'review the build function that downloads and sets up the wizard of wikipedia dataset', 'summarize the build function that handles downloading and versioning of wizard of wikipedia data', 'test the build function to verify it correctly downloads and marks wizard of wikipedia data as built', 'add the checked sentence wrapped in knowledge tokens to the end of a message text field', 'replace message labels with the checked sentence and store original labels as dialogue_response', 'append the dialogue response label wrapped in label tokens to the end of the message text', 'split the dialogue response at a random word and wrap the second half in label tokens for language modeling', 'filter dialogue episodes to include or exclude examples based on whether a knowledge passage was used', 'run an interactive Wizard of Wikipedia dialogue with a human agent and model agent', 'run an interactive Wizard of Wikipedia dialogue with gold knowledge prepended to dialogue input', 'run a self-chat Wizard of Wikipedia world where two agents chat on a random topic', 'review the InteractiveWorld parley method that loops between wizard and apprentice agents with knowledge retrieval', 'refactor the InteractiveWorld knowledge agent setup to use a different retriever model']
```

Usage

```
{'build_wizard_of_wikipedia_data': 'build the wizard of wikipedia dataset by downloading and extracting the data archive', 'run_build_function': 'run the build function to download wizard of wikipedia data to the specified datapath', 'review_build_function': 'review the build function that downloads and sets up the wizard of wikipedia dataset', 'summarize_build_function': 'summarize the build function that handles downloading and versioning of wizard of wikipedia data', 'test_build_function': 'test the build function to verify it correctly downloads and marks wizard of wikipedia data as built'}
```

## File: facebookresearch_parlai/parlai/tasks/wizard_of_wikipedia/mutators.py

Prompts

```
['build a Parlai teacher that formats Wizard of Wikipedia dialog with knowledge passages and label candidates', 'run the RareWordF1Calculator class to compute F1 scores emphasizing infrequent words in a corpus', 'create a GeneratorTeacher for training a knowledge-grounded response generator with configurable dropout and gold knowledge prepending', 'review the DocreaderTeacher class and its teacher types for training document retrieval and sentence selection models', 'test the WikiPageTitleTeacher to generate Wikipedia page titles from conversation history context', 'build the wizard of wikipedia dataset by downloading and extracting the data archive', 'run the build function to download wizard of wikipedia data to the specified datapath', 'review the build function that downloads and sets up the wizard of wikipedia dataset', 'summarize the build function that handles downloading and versioning of wizard of wikipedia data', 'test the build function to verify it correctly downloads and marks wizard of wikipedia data as built', 'add the checked sentence wrapped in knowledge tokens to the end of a message text field', 'replace message labels with the checked sentence and store original labels as dialogue_response', 'append the dialogue response label wrapped in label tokens to the end of the message text', 'split the dialogue response at a random word and wrap the second half in label tokens for language modeling', 'filter dialogue episodes to include or exclude examples based on whether a knowledge passage was used', 'run an interactive Wizard of Wikipedia dialogue with a human agent and model agent', 'run an interactive Wizard of Wikipedia dialogue with gold knowledge prepended to dialogue input', 'run a self-chat Wizard of Wikipedia world where two agents chat on a random topic', 'review the InteractiveWorld parley method that loops between wizard and apprentice agents with knowledge retrieval', 'refactor the InteractiveWorld knowledge agent setup to use a different retriever model']
```

Usage

```
{'add_checked_sentence_to_input': 'add the checked sentence wrapped in knowledge tokens to the end of a message text field', 'use_checked_sentence_as_label': 'replace message labels with the checked sentence and store original labels as dialogue_response', 'add_label_to_input': 'append the dialogue response label wrapped in label tokens to the end of the message text', 'add_label_to_input_lm': 'split the dialogue response at a random word and wrap the second half in label tokens for language modeling', 'filter_episodes_by_passage_usage': 'filter dialogue episodes to include or exclude examples based on whether a knowledge passage was used'}
```

## File: facebookresearch_parlai/parlai/tasks/wizard_of_wikipedia/worlds.py

Prompts

```
['build a Parlai teacher that formats Wizard of Wikipedia dialog with knowledge passages and label candidates', 'run the RareWordF1Calculator class to compute F1 scores emphasizing infrequent words in a corpus', 'create a GeneratorTeacher for training a knowledge-grounded response generator with configurable dropout and gold knowledge prepending', 'review the DocreaderTeacher class and its teacher types for training document retrieval and sentence selection models', 'test the WikiPageTitleTeacher to generate Wikipedia page titles from conversation history context', 'build the wizard of wikipedia dataset by downloading and extracting the data archive', 'run the build function to download wizard of wikipedia data to the specified datapath', 'review the build function that downloads and sets up the wizard of wikipedia dataset', 'summarize the build function that handles downloading and versioning of wizard of wikipedia data', 'test the build function to verify it correctly downloads and marks wizard of wikipedia data as built', 'add the checked sentence wrapped in knowledge tokens to the end of a message text field', 'replace message labels with the checked sentence and store original labels as dialogue_response', 'append the dialogue response label wrapped in label tokens to the end of the message text', 'split the dialogue response at a random word and wrap the second half in label tokens for language modeling', 'filter dialogue episodes to include or exclude examples based on whether a knowledge passage was used', 'run an interactive Wizard of Wikipedia dialogue with a human agent and model agent', 'run an interactive Wizard of Wikipedia dialogue with gold knowledge prepended to dialogue input', 'run a self-chat Wizard of Wikipedia world where two agents chat on a random topic', 'review the InteractiveWorld parley method that loops between wizard and apprentice agents with knowledge retrieval', 'refactor the InteractiveWorld knowledge agent setup to use a different retriever model']
```

Usage

```
{'run_interactive_world': 'run an interactive Wizard of Wikipedia dialogue with a human agent and model agent', 'run_interactive_generator_world': 'run an interactive Wizard of Wikipedia dialogue with gold knowledge prepended to dialogue input', 'run_self_chat_world': 'run a self-chat Wizard of Wikipedia world where two agents chat on a random topic', 'review_interactive_world_parley': 'review the InteractiveWorld parley method that loops between wizard and apprentice agents with knowledge retrieval', 'refactor_knowledge_agent_setup': 'refactor the InteractiveWorld knowledge agent setup to use a different retriever model'}
```

