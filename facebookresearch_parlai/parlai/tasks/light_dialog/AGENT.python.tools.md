# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/light_dialog/agents.py

Prompts

```
['review the DefaultTeacher class and its LIGHT dialogue command line argument options', 'review the SimpleTeacher class which uses minimal context with partner speech only', 'review the SimpleMultiTeacher class which supports multi-turn dialogue with current self output', 'review the SelfchatTeacher class used to create candidates for selfchat dialogues', 'review the _path function that constructs the data file path from dialogue options', 'download the light dialogue dataset pickle files to the ParlAI datapath directory', 'build the light dialogue dataset with configurable field flags for taskname, setting, and speech', 'review the download function that fetches light dialogue pickle files and handles versioning', 'review the build function that creates configuration-specific dataset instances from light dialogue data', 'summarize the RESOURCES list of downloadable pickle files for the light dialogue dataset', 'generate all possible no-affordance actions for a dialogue turn given room objects and carrying state', 'write dialogue messages to a file with configurable features like speech, action, emote, and persona', 'fix label candidates by clipping to a max size and ensuring the gold label is included', 'write out all unique candidate labels for emote, speech, action, and which types to text files', 'create an InteractiveSimpleWorld that loads LIGHT dialog data and assigns personas for interactive chat sessions', 'run get_contexts on InteractiveSimpleWorld to retrieve paired personas with swapped self and partner names', 'create a SelfChatWorld that loads light_environment.pkl and compacts rooms and characters for self-chat dialog', 'run get_contexts on SelfChatWorld to randomly select a room and two characters and return their contexts', 'review the make_context method in SelfChatWorld that builds a persona string from a room and two characters']
```

Usage

```
{'review_DefaultTeacher': 'review the DefaultTeacher class and its LIGHT dialogue command line argument options', 'review_SimpleTeacher': 'review the SimpleTeacher class which uses minimal context with partner speech only', 'review_SimpleMultiTeacher': 'review the SimpleMultiTeacher class which supports multi-turn dialogue with current self output', 'review_SelfchatTeacher': 'review the SelfchatTeacher class used to create candidates for selfchat dialogues', 'review__path': 'review the _path function that constructs the data file path from dialogue options'}
```

## File: facebookresearch_parlai/parlai/tasks/light_dialog/build.py

Prompts

```
['review the DefaultTeacher class and its LIGHT dialogue command line argument options', 'review the SimpleTeacher class which uses minimal context with partner speech only', 'review the SimpleMultiTeacher class which supports multi-turn dialogue with current self output', 'review the SelfchatTeacher class used to create candidates for selfchat dialogues', 'review the _path function that constructs the data file path from dialogue options', 'download the light dialogue dataset pickle files to the ParlAI datapath directory', 'build the light dialogue dataset with configurable field flags for taskname, setting, and speech', 'review the download function that fetches light dialogue pickle files and handles versioning', 'review the build function that creates configuration-specific dataset instances from light dialogue data', 'summarize the RESOURCES list of downloadable pickle files for the light dialogue dataset', 'generate all possible no-affordance actions for a dialogue turn given room objects and carrying state', 'write dialogue messages to a file with configurable features like speech, action, emote, and persona', 'fix label candidates by clipping to a max size and ensuring the gold label is included', 'write out all unique candidate labels for emote, speech, action, and which types to text files', 'create an InteractiveSimpleWorld that loads LIGHT dialog data and assigns personas for interactive chat sessions', 'run get_contexts on InteractiveSimpleWorld to retrieve paired personas with swapped self and partner names', 'create a SelfChatWorld that loads light_environment.pkl and compacts rooms and characters for self-chat dialog', 'run get_contexts on SelfChatWorld to randomly select a room and two characters and return their contexts', 'review the make_context method in SelfChatWorld that builds a persona string from a room and two characters']
```

Usage

```
{'download_light_dialog_data': 'download the light dialogue dataset pickle files to the ParlAI datapath directory', 'build_light_dialog_dataset': 'build the light dialogue dataset with configurable field flags for taskname, setting, and speech', 'review_download_function': 'review the download function that fetches light dialogue pickle files and handles versioning', 'review_build_function': 'review the build function that creates configuration-specific dataset instances from light dialogue data', 'summarize_resources_list': 'summarize the RESOURCES list of downloadable pickle files for the light dialogue dataset'}
```

## File: facebookresearch_parlai/parlai/tasks/light_dialog/builder.py

Prompts

```
['review the DefaultTeacher class and its LIGHT dialogue command line argument options', 'review the SimpleTeacher class which uses minimal context with partner speech only', 'review the SimpleMultiTeacher class which supports multi-turn dialogue with current self output', 'review the SelfchatTeacher class used to create candidates for selfchat dialogues', 'review the _path function that constructs the data file path from dialogue options', 'download the light dialogue dataset pickle files to the ParlAI datapath directory', 'build the light dialogue dataset with configurable field flags for taskname, setting, and speech', 'review the download function that fetches light dialogue pickle files and handles versioning', 'review the build function that creates configuration-specific dataset instances from light dialogue data', 'summarize the RESOURCES list of downloadable pickle files for the light dialogue dataset', 'generate all possible no-affordance actions for a dialogue turn given room objects and carrying state', 'write dialogue messages to a file with configurable features like speech, action, emote, and persona', 'fix label candidates by clipping to a max size and ensuring the gold label is included', 'write out all unique candidate labels for emote, speech, action, and which types to text files', 'create an InteractiveSimpleWorld that loads LIGHT dialog data and assigns personas for interactive chat sessions', 'run get_contexts on InteractiveSimpleWorld to retrieve paired personas with swapped self and partner names', 'create a SelfChatWorld that loads light_environment.pkl and compacts rooms and characters for self-chat dialog', 'run get_contexts on SelfChatWorld to randomly select a room and two characters and return their contexts', 'review the make_context method in SelfChatWorld that builds a persona string from a room and two characters']
```

Usage

```
{'build_light_dialog_dataset': 'build a ParlAI Light Dialog dataset from pickle databases with train, valid, test splits', 'generate_no_affordance_actions': 'generate all possible no-affordance actions for a dialogue turn given room objects and carrying state', 'write_dialog_messages': 'write dialogue messages to a file with configurable features like speech, action, emote, and persona', 'fix_label_candidates': 'fix label candidates by clipping to a max size and ensuring the gold label is included', 'write_out_candidates': 'write out all unique candidate labels for emote, speech, action, and which types to text files'}
```

## File: facebookresearch_parlai/parlai/tasks/light_dialog/worlds.py

Prompts

```
['review the DefaultTeacher class and its LIGHT dialogue command line argument options', 'review the SimpleTeacher class which uses minimal context with partner speech only', 'review the SimpleMultiTeacher class which supports multi-turn dialogue with current self output', 'review the SelfchatTeacher class used to create candidates for selfchat dialogues', 'review the _path function that constructs the data file path from dialogue options', 'download the light dialogue dataset pickle files to the ParlAI datapath directory', 'build the light dialogue dataset with configurable field flags for taskname, setting, and speech', 'review the download function that fetches light dialogue pickle files and handles versioning', 'review the build function that creates configuration-specific dataset instances from light dialogue data', 'summarize the RESOURCES list of downloadable pickle files for the light dialogue dataset', 'generate all possible no-affordance actions for a dialogue turn given room objects and carrying state', 'write dialogue messages to a file with configurable features like speech, action, emote, and persona', 'fix label candidates by clipping to a max size and ensuring the gold label is included', 'write out all unique candidate labels for emote, speech, action, and which types to text files', 'create an InteractiveSimpleWorld that loads LIGHT dialog data and assigns personas for interactive chat sessions', 'run get_contexts on InteractiveSimpleWorld to retrieve paired personas with swapped self and partner names', 'create a SelfChatWorld that loads light_environment.pkl and compacts rooms and characters for self-chat dialog', 'run get_contexts on SelfChatWorld to randomly select a room and two characters and return their contexts', 'review the make_context method in SelfChatWorld that builds a persona string from a room and two characters']
```

Usage

```
{'create_interactive_simple_world': 'create an InteractiveSimpleWorld that loads LIGHT dialog data and assigns personas for interactive chat sessions', 'run_interactive_simple_world_get_contexts': 'run get_contexts on InteractiveSimpleWorld to retrieve paired personas with swapped self and partner names', 'create_self_chat_world': 'create a SelfChatWorld that loads light_environment.pkl and compacts rooms and characters for self-chat dialog', 'run_self_chat_world_get_contexts': 'run get_contexts on SelfChatWorld to randomly select a room and two characters and return their contexts', 'review_self_chat_world_make_context': 'review the make_context method in SelfChatWorld that builds a persona string from a room and two characters'}
```

