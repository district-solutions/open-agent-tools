# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/dialog/dialogue_manager.py

Prompts

```
['step the DialogueManager to process the last chat and return a dialogue object or task', 'get the last m chats from memory with speaker, text, logical form, and status', 'get a DialogueObject or DialogueTask for a given chat and its logical form', 'handle a logical form by returning the appropriate interpreter or dialogue task', 'check if a chat is safe and get a greeting reply if it matches a known greeting', 'create an AwaitResponse task that blocks the agent until a user chat response arrives', 'create a Say task that sends a random chat message from response options to the user', 'create a Point task that makes the agent point at spatial bounds with optional sleep time', 'build a JSON chat object with text, media, and response options for dialogue interactions', 'create a ConfirmTask that asks the user yes or no before executing a list of child tasks', 'extract a set of safety words from the safety.txt file to prevent abuse', 'load a greetings map from greetings.json or return default hello and goodbye greetings', 'review the get_safety_words function that parses safety.txt and filters comments and empty lines', 'review the get_greetings function that loads greeting phrases from a JSON file with fallback defaults', 'refactor get_safety_words to use pathlib instead of string formatting for the safety file path', 'fix a FILL or DESTROY action dict by moving its location into the reference_object field', 'fix location_type values in a dict by converting them to special_reference entries in the reference_object', 'fix reference objects in a dict by wrapping their properties inside a filters key', 'retrieve the obj_text span from a nested dict where pred_text equals has_name', 'post process a logical form action dict by fixing fill/destroy locations, location types, and reference object filters', 'create a SwarmDialogueManager instance with memory, dialogue object classes, and options', 'use the neglect method to filter out speakers whose name contains bot', 'review the SwarmDialogueManager class and its chat retrieval and bot filtering logic', 'summarize the get_last_m_chats method that fetches recent chats with logical form and status']
```

Usage

```
{'step_dialogue_manager': 'step the DialogueManager to process the last chat and return a dialogue object or task', 'get_last_m_chats': 'get the last m chats from memory with speaker, text, logical form, and status', 'get_dialogue_object': 'get a DialogueObject or DialogueTask for a given chat and its logical form', 'handle_logical_form': 'handle a logical form by returning the appropriate interpreter or dialogue task', 'check_safety_and_greetings': 'check if a chat is safe and get a greeting reply if it matches a known greeting'}
```

## File: facebookresearch_fairo/droidlet/dialog/dialogue_task.py

Prompts

```
['step the DialogueManager to process the last chat and return a dialogue object or task', 'get the last m chats from memory with speaker, text, logical form, and status', 'get a DialogueObject or DialogueTask for a given chat and its logical form', 'handle a logical form by returning the appropriate interpreter or dialogue task', 'check if a chat is safe and get a greeting reply if it matches a known greeting', 'create an AwaitResponse task that blocks the agent until a user chat response arrives', 'create a Say task that sends a random chat message from response options to the user', 'create a Point task that makes the agent point at spatial bounds with optional sleep time', 'build a JSON chat object with text, media, and response options for dialogue interactions', 'create a ConfirmTask that asks the user yes or no before executing a list of child tasks', 'extract a set of safety words from the safety.txt file to prevent abuse', 'load a greetings map from greetings.json or return default hello and goodbye greetings', 'review the get_safety_words function that parses safety.txt and filters comments and empty lines', 'review the get_greetings function that loads greeting phrases from a JSON file with fallback defaults', 'refactor get_safety_words to use pathlib instead of string formatting for the safety file path', 'fix a FILL or DESTROY action dict by moving its location into the reference_object field', 'fix location_type values in a dict by converting them to special_reference entries in the reference_object', 'fix reference objects in a dict by wrapping their properties inside a filters key', 'retrieve the obj_text span from a nested dict where pred_text equals has_name', 'post process a logical form action dict by fixing fill/destroy locations, location types, and reference object filters', 'create a SwarmDialogueManager instance with memory, dialogue object classes, and options', 'use the neglect method to filter out speakers whose name contains bot', 'review the SwarmDialogueManager class and its chat retrieval and bot filtering logic', 'summarize the get_last_m_chats method that fetches recent chats with logical form and status']
```

Usage

```
{'create_AwaitResponse_task': 'create an AwaitResponse task that blocks the agent until a user chat response arrives', 'create_Say_task': 'create a Say task that sends a random chat message from response options to the user', 'create_Point_task': 'create a Point task that makes the agent point at spatial bounds with optional sleep time', 'use_build_question_json': 'build a JSON chat object with text, media, and response options for dialogue interactions', 'create_ConfirmTask': 'create a ConfirmTask that asks the user yes or no before executing a list of child tasks'}
```

## File: facebookresearch_fairo/droidlet/dialog/load_datasets.py

Prompts

```
['step the DialogueManager to process the last chat and return a dialogue object or task', 'get the last m chats from memory with speaker, text, logical form, and status', 'get a DialogueObject or DialogueTask for a given chat and its logical form', 'handle a logical form by returning the appropriate interpreter or dialogue task', 'check if a chat is safe and get a greeting reply if it matches a known greeting', 'create an AwaitResponse task that blocks the agent until a user chat response arrives', 'create a Say task that sends a random chat message from response options to the user', 'create a Point task that makes the agent point at spatial bounds with optional sleep time', 'build a JSON chat object with text, media, and response options for dialogue interactions', 'create a ConfirmTask that asks the user yes or no before executing a list of child tasks', 'extract a set of safety words from the safety.txt file to prevent abuse', 'load a greetings map from greetings.json or return default hello and goodbye greetings', 'review the get_safety_words function that parses safety.txt and filters comments and empty lines', 'review the get_greetings function that loads greeting phrases from a JSON file with fallback defaults', 'refactor get_safety_words to use pathlib instead of string formatting for the safety file path', 'fix a FILL or DESTROY action dict by moving its location into the reference_object field', 'fix location_type values in a dict by converting them to special_reference entries in the reference_object', 'fix reference objects in a dict by wrapping their properties inside a filters key', 'retrieve the obj_text span from a nested dict where pred_text equals has_name', 'post process a logical form action dict by fixing fill/destroy locations, location types, and reference object filters', 'create a SwarmDialogueManager instance with memory, dialogue object classes, and options', 'use the neglect method to filter out speakers whose name contains bot', 'review the SwarmDialogueManager class and its chat retrieval and bot filtering logic', 'summarize the get_last_m_chats method that fetches recent chats with logical form and status']
```

Usage

```
{'get_safety_words': 'extract a set of safety words from the safety.txt file to prevent abuse', 'get_greetings': 'load a greetings map from greetings.json or return default hello and goodbye greetings', 'review_get_safety_words': 'review the get_safety_words function that parses safety.txt and filters comments and empty lines', 'review_get_greetings': 'review the get_greetings function that loads greeting phrases from a JSON file with fallback defaults', 'refactor_get_safety_words': 'refactor get_safety_words to use pathlib instead of string formatting for the safety file path'}
```

## File: facebookresearch_fairo/droidlet/dialog/post_process_logical_form.py

Prompts

```
['step the DialogueManager to process the last chat and return a dialogue object or task', 'get the last m chats from memory with speaker, text, logical form, and status', 'get a DialogueObject or DialogueTask for a given chat and its logical form', 'handle a logical form by returning the appropriate interpreter or dialogue task', 'check if a chat is safe and get a greeting reply if it matches a known greeting', 'create an AwaitResponse task that blocks the agent until a user chat response arrives', 'create a Say task that sends a random chat message from response options to the user', 'create a Point task that makes the agent point at spatial bounds with optional sleep time', 'build a JSON chat object with text, media, and response options for dialogue interactions', 'create a ConfirmTask that asks the user yes or no before executing a list of child tasks', 'extract a set of safety words from the safety.txt file to prevent abuse', 'load a greetings map from greetings.json or return default hello and goodbye greetings', 'review the get_safety_words function that parses safety.txt and filters comments and empty lines', 'review the get_greetings function that loads greeting phrases from a JSON file with fallback defaults', 'refactor get_safety_words to use pathlib instead of string formatting for the safety file path', 'fix a FILL or DESTROY action dict by moving its location into the reference_object field', 'fix location_type values in a dict by converting them to special_reference entries in the reference_object', 'fix reference objects in a dict by wrapping their properties inside a filters key', 'retrieve the obj_text span from a nested dict where pred_text equals has_name', 'post process a logical form action dict by fixing fill/destroy locations, location types, and reference object filters', 'create a SwarmDialogueManager instance with memory, dialogue object classes, and options', 'use the neglect method to filter out speakers whose name contains bot', 'review the SwarmDialogueManager class and its chat retrieval and bot filtering logic', 'summarize the get_last_m_chats method that fetches recent chats with logical form and status']
```

Usage

```
{'fix_fill_destroy_location': 'fix a FILL or DESTROY action dict by moving its location into the reference_object field', 'fix_location_type_in_location': 'fix location_type values in a dict by converting them to special_reference entries in the reference_object', 'fix_reference_object_with_filters': 'fix reference objects in a dict by wrapping their properties inside a filters key', 'retrieve_ref_obj_span': 'retrieve the obj_text span from a nested dict where pred_text equals has_name', 'post_process_logical_form': 'post process a logical form action dict by fixing fill/destroy locations, location types, and reference object filters'}
```

## File: facebookresearch_fairo/droidlet/dialog/swarm_dialogue_manager.py

Prompts

```
['step the DialogueManager to process the last chat and return a dialogue object or task', 'get the last m chats from memory with speaker, text, logical form, and status', 'get a DialogueObject or DialogueTask for a given chat and its logical form', 'handle a logical form by returning the appropriate interpreter or dialogue task', 'check if a chat is safe and get a greeting reply if it matches a known greeting', 'create an AwaitResponse task that blocks the agent until a user chat response arrives', 'create a Say task that sends a random chat message from response options to the user', 'create a Point task that makes the agent point at spatial bounds with optional sleep time', 'build a JSON chat object with text, media, and response options for dialogue interactions', 'create a ConfirmTask that asks the user yes or no before executing a list of child tasks', 'extract a set of safety words from the safety.txt file to prevent abuse', 'load a greetings map from greetings.json or return default hello and goodbye greetings', 'review the get_safety_words function that parses safety.txt and filters comments and empty lines', 'review the get_greetings function that loads greeting phrases from a JSON file with fallback defaults', 'refactor get_safety_words to use pathlib instead of string formatting for the safety file path', 'fix a FILL or DESTROY action dict by moving its location into the reference_object field', 'fix location_type values in a dict by converting them to special_reference entries in the reference_object', 'fix reference objects in a dict by wrapping their properties inside a filters key', 'retrieve the obj_text span from a nested dict where pred_text equals has_name', 'post process a logical form action dict by fixing fill/destroy locations, location types, and reference object filters', 'create a SwarmDialogueManager instance with memory, dialogue object classes, and options', 'use the neglect method to filter out speakers whose name contains bot', 'review the SwarmDialogueManager class and its chat retrieval and bot filtering logic', 'summarize the get_last_m_chats method that fetches recent chats with logical form and status']
```

Usage

```
{'create_swarm_dialogue_manager': 'create a SwarmDialogueManager instance with memory, dialogue object classes, and options', 'neglect_bot_speaker': 'use the neglect method to filter out speakers whose name contains bot', 'get_last_m_chats': 'get the last m chats from memory excluding bot speakers with their logical forms', 'review_swarm_dialogue_manager_class': 'review the SwarmDialogueManager class and its chat retrieval and bot filtering logic', 'summarize_get_last_m_chats': 'summarize the get_last_m_chats method that fetches recent chats with logical form and status'}
```

