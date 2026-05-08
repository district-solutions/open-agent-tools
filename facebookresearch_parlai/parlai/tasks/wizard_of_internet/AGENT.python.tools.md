# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/wizard_of_internet/agents.py

Prompts

```
['run the WizardDialogTeacher to train a Wizard agent with retrieved and selected knowledge from the Wizard of Internet dataset', 'run the ApprenticeDialogTeacher to train an Apprentice agent using dialogue history from the Wizard of Internet dataset', 'run the SearchQueryTeacher to train a model to generate search queries from dialogue context in the Wizard of Internet task', 'run the GoldKnowledgeTeacher to train a model to predict selected knowledge sentences from retrieved documents in the Wizard of Internet task', 'run the custom_evaluation method on WizardDialogTeacher to compute F1 metrics over selected and retrieved knowledge pieces', 'build the wizard of internet dataset by downloading and extracting data files to the datapath directory', 'run the build function to download the wizard of internet dataset tgz file and mark it done', 'download the wizard of internet dataset file using the DATASET_FILE downloadable file object', 'review the build function that handles dataset download, directory creation, and version marking', 'summarize the DATASET_FILE object that configures the wizard of internet dataset download URL and checksum', 'chunk retrieved documents into smaller pieces using the woi_chunk_retrieved_docs mutator with a configurable character size', 'filter wizard of internet examples where no passage was selected using the woi_filter_no_passage_used mutator', 'filter examples where selected sentences are not found in retrieved docs using the woi_filter_selected_knowledge_in_retrieved_docs mutator', 'add the checked sentence to the end of the input text using the woi_add_checked_sentence_to_input mutator', 'drop out retrieved documents to keep a maximum number of chunks using the woi_dropout_retrieved_docs mutator']
```

Usage

```
{'run_wizard_dialog_teacher': 'run the WizardDialogTeacher to train a Wizard agent with retrieved and selected knowledge from the Wizard of Internet dataset', 'run_apprentice_dialog_teacher': 'run the ApprenticeDialogTeacher to train an Apprentice agent using dialogue history from the Wizard of Internet dataset', 'run_search_query_teacher': 'run the SearchQueryTeacher to train a model to generate search queries from dialogue context in the Wizard of Internet task', 'run_gold_knowledge_teacher': 'run the GoldKnowledgeTeacher to train a model to predict selected knowledge sentences from retrieved documents in the Wizard of Internet task', 'run_custom_evaluation': 'run the custom_evaluation method on WizardDialogTeacher to compute F1 metrics over selected and retrieved knowledge pieces'}
```

## File: facebookresearch_parlai/parlai/tasks/wizard_of_internet/build.py

Prompts

```
['run the WizardDialogTeacher to train a Wizard agent with retrieved and selected knowledge from the Wizard of Internet dataset', 'run the ApprenticeDialogTeacher to train an Apprentice agent using dialogue history from the Wizard of Internet dataset', 'run the SearchQueryTeacher to train a model to generate search queries from dialogue context in the Wizard of Internet task', 'run the GoldKnowledgeTeacher to train a model to predict selected knowledge sentences from retrieved documents in the Wizard of Internet task', 'run the custom_evaluation method on WizardDialogTeacher to compute F1 metrics over selected and retrieved knowledge pieces', 'build the wizard of internet dataset by downloading and extracting data files to the datapath directory', 'run the build function to download the wizard of internet dataset tgz file and mark it done', 'download the wizard of internet dataset file using the DATASET_FILE downloadable file object', 'review the build function that handles dataset download, directory creation, and version marking', 'summarize the DATASET_FILE object that configures the wizard of internet dataset download URL and checksum', 'chunk retrieved documents into smaller pieces using the woi_chunk_retrieved_docs mutator with a configurable character size', 'filter wizard of internet examples where no passage was selected using the woi_filter_no_passage_used mutator', 'filter examples where selected sentences are not found in retrieved docs using the woi_filter_selected_knowledge_in_retrieved_docs mutator', 'add the checked sentence to the end of the input text using the woi_add_checked_sentence_to_input mutator', 'drop out retrieved documents to keep a maximum number of chunks using the woi_dropout_retrieved_docs mutator']
```

Usage

```
{'build_wizard_of_internet_dataset': 'build the wizard of internet dataset by downloading and extracting data files to the datapath directory', 'run_build_function': 'run the build function to download the wizard of internet dataset tgz file and mark it done', 'download_DATASET_FILE': 'download the wizard of internet dataset file using the DATASET_FILE downloadable file object', 'review_build_function': 'review the build function that handles dataset download, directory creation, and version marking', 'summarize_DATASET_FILE': 'summarize the DATASET_FILE object that configures the wizard of internet dataset download URL and checksum'}
```

## File: facebookresearch_parlai/parlai/tasks/wizard_of_internet/mutators.py

Prompts

```
['run the WizardDialogTeacher to train a Wizard agent with retrieved and selected knowledge from the Wizard of Internet dataset', 'run the ApprenticeDialogTeacher to train an Apprentice agent using dialogue history from the Wizard of Internet dataset', 'run the SearchQueryTeacher to train a model to generate search queries from dialogue context in the Wizard of Internet task', 'run the GoldKnowledgeTeacher to train a model to predict selected knowledge sentences from retrieved documents in the Wizard of Internet task', 'run the custom_evaluation method on WizardDialogTeacher to compute F1 metrics over selected and retrieved knowledge pieces', 'build the wizard of internet dataset by downloading and extracting data files to the datapath directory', 'run the build function to download the wizard of internet dataset tgz file and mark it done', 'download the wizard of internet dataset file using the DATASET_FILE downloadable file object', 'review the build function that handles dataset download, directory creation, and version marking', 'summarize the DATASET_FILE object that configures the wizard of internet dataset download URL and checksum', 'chunk retrieved documents into smaller pieces using the woi_chunk_retrieved_docs mutator with a configurable character size', 'filter wizard of internet examples where no passage was selected using the woi_filter_no_passage_used mutator', 'filter examples where selected sentences are not found in retrieved docs using the woi_filter_selected_knowledge_in_retrieved_docs mutator', 'add the checked sentence to the end of the input text using the woi_add_checked_sentence_to_input mutator', 'drop out retrieved documents to keep a maximum number of chunks using the woi_dropout_retrieved_docs mutator']
```

Usage

```
{'chunk_retrieved_docs': 'chunk retrieved documents into smaller pieces using the woi_chunk_retrieved_docs mutator with a configurable character size', 'filter_no_passage_used': 'filter wizard of internet examples where no passage was selected using the woi_filter_no_passage_used mutator', 'filter_selected_knowledge_in_docs': 'filter examples where selected sentences are not found in retrieved docs using the woi_filter_selected_knowledge_in_retrieved_docs mutator', 'add_checked_sentence_to_input': 'add the checked sentence to the end of the input text using the woi_add_checked_sentence_to_input mutator', 'dropout_retrieved_docs': 'drop out retrieved documents to keep a maximum number of chunks using the woi_dropout_retrieved_docs mutator'}
```

