# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/blended_skill_talk/agents.py

Prompts

```
['create a BlendedSkillTalkTeacher agent from an Opt config to load the BST dataset', 'use PersonaTopicifier to add persona and topic context to a raw utterance string', 'use ContextGenerator to generate crowdsourcing context with personas and seed utterances for BST conversations', 'use PersonaTopicifier to choose a matching persona from an utterance based on word overlap', 'use ContextGenerator to extract persona strings for both speakers from a ConvAI2 episode', 'build the blended_skill_talk dataset by downloading resources and converting to ParlAI format', 'convert blended_skill_talk JSON dialog files into tab-separated ParlAI text format', 'download all blended_skill_talk resources including personas, annotations, and topicifier files', 'generate a formatted ParlAI line from a dialog episode with persona context and suggestions', 'escape tabs, newlines, and pipe characters in dialog text values', 'run the InteractiveWorld class to start a BST chat session with persona context', 'run the SelfChatWorld class to start a BST self-chat session with two agents', 'load and filter BST personas from raw data using the _load_personas function', 'standardize a persona string by normalizing contractions and punctuation with _standardize', 'retrieve shared or freshly loaded persona contexts data via get_contexts_data']
```

Usage

```
{'create_BlendedSkillTalkTeacher': 'create a BlendedSkillTalkTeacher agent from an Opt config to load the BST dataset', 'use_PersonaTopicifier_get_modified_text': 'use PersonaTopicifier to add persona and topic context to a raw utterance string', 'use_ContextGenerator_get_context': 'use ContextGenerator to generate crowdsourcing context with personas and seed utterances for BST conversations', 'use_PersonaTopicifier_choose_persona_from_text': 'use PersonaTopicifier to choose a matching persona from an utterance based on word overlap', 'use_ContextGenerator_extract_personas': 'use ContextGenerator to extract persona strings for both speakers from a ConvAI2 episode'}
```

## File: facebookresearch_parlai/parlai/tasks/blended_skill_talk/build.py

Prompts

```
['create a BlendedSkillTalkTeacher agent from an Opt config to load the BST dataset', 'use PersonaTopicifier to add persona and topic context to a raw utterance string', 'use ContextGenerator to generate crowdsourcing context with personas and seed utterances for BST conversations', 'use PersonaTopicifier to choose a matching persona from an utterance based on word overlap', 'use ContextGenerator to extract persona strings for both speakers from a ConvAI2 episode', 'build the blended_skill_talk dataset by downloading resources and converting to ParlAI format', 'convert blended_skill_talk JSON dialog files into tab-separated ParlAI text format', 'download all blended_skill_talk resources including personas, annotations, and topicifier files', 'generate a formatted ParlAI line from a dialog episode with persona context and suggestions', 'escape tabs, newlines, and pipe characters in dialog text values', 'run the InteractiveWorld class to start a BST chat session with persona context', 'run the SelfChatWorld class to start a BST self-chat session with two agents', 'load and filter BST personas from raw data using the _load_personas function', 'standardize a persona string by normalizing contractions and punctuation with _standardize', 'retrieve shared or freshly loaded persona contexts data via get_contexts_data']
```

Usage

```
{'build_blended_skill_talk_data': 'build the blended_skill_talk dataset by downloading resources and converting to ParlAI format', 'create_parlai_format': 'convert blended_skill_talk JSON dialog files into tab-separated ParlAI text format', 'download_blended_skill_talk_resources': 'download all blended_skill_talk resources including personas, annotations, and topicifier files', 'get_line_from_episode': 'generate a formatted ParlAI line from a dialog episode with persona context and suggestions', 'escape_special_characters': 'escape tabs, newlines, and pipe characters in dialog text values'}
```

## File: facebookresearch_parlai/parlai/tasks/blended_skill_talk/worlds.py

Prompts

```
['create a BlendedSkillTalkTeacher agent from an Opt config to load the BST dataset', 'use PersonaTopicifier to add persona and topic context to a raw utterance string', 'use ContextGenerator to generate crowdsourcing context with personas and seed utterances for BST conversations', 'use PersonaTopicifier to choose a matching persona from an utterance based on word overlap', 'use ContextGenerator to extract persona strings for both speakers from a ConvAI2 episode', 'build the blended_skill_talk dataset by downloading resources and converting to ParlAI format', 'convert blended_skill_talk JSON dialog files into tab-separated ParlAI text format', 'download all blended_skill_talk resources including personas, annotations, and topicifier files', 'generate a formatted ParlAI line from a dialog episode with persona context and suggestions', 'escape tabs, newlines, and pipe characters in dialog text values', 'run the InteractiveWorld class to start a BST chat session with persona context', 'run the SelfChatWorld class to start a BST self-chat session with two agents', 'load and filter BST personas from raw data using the _load_personas function', 'standardize a persona string by normalizing contractions and punctuation with _standardize', 'retrieve shared or freshly loaded persona contexts data via get_contexts_data']
```

Usage

```
{'run_interactive_world': 'run the InteractiveWorld class to start a BST chat session with persona context', 'run_selfchat_world': 'run the SelfChatWorld class to start a BST self-chat session with two agents', 'load_personas': 'load and filter BST personas from raw data using the _load_personas function', 'standardize_persona_string': 'standardize a persona string by normalizing contractions and punctuation with _standardize', 'get_contexts_data': 'retrieve shared or freshly loaded persona contexts data via get_contexts_data'}
```

