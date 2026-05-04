# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/parlai_diplomacy/tasks/discriminator/agents.py

Prompts

```
['insert a discriminator label token after each [EO_M] token in a message string', 'change the sender or recipient of a parsed message to a random other power', 'replace detected entities like powers and locations in a message with random alternatives', 'replace a message with one from a previous phase of the same game', 'stream noisy training data by corrupting dialogue messages with a specified corruption strategy', 'build a pygtrie CharTrie for tokenization-free entity matching of diplomacy powers, locations, and symbols', 'search a message string with a trie to find all diplomacy entity matches and their positions', 'match the case of new text to the original text for consistent entity replacement', 'get a set of possible replacement entities for a given diplomacy entity type like powers or locations', 'splice a replacement string into a message at specified start and end index positions']
```

Usage

```
{'insert_discriminator_label': 'insert a discriminator label token after each [EO_M] token in a message string', 'change_conversation_participants': 'change the sender or recipient of a parsed message to a random other power', 'change_entities': 'replace detected entities like powers and locations in a message with random alternatives', 'message_from_incorrect_phase': 'replace a message with one from a previous phase of the same game', 'BaseCorruptedDialogueChunkTeacher': 'stream noisy training data by corrupting dialogue messages with a specified corruption strategy'}
```

## File: facebookresearch_diplomacycicero/parlai_diplomacy/tasks/discriminator/change_entity_utils.py

Prompts

```
['insert a discriminator label token after each [EO_M] token in a message string', 'change the sender or recipient of a parsed message to a random other power', 'replace detected entities like powers and locations in a message with random alternatives', 'replace a message with one from a previous phase of the same game', 'stream noisy training data by corrupting dialogue messages with a specified corruption strategy', 'build a pygtrie CharTrie for tokenization-free entity matching of diplomacy powers, locations, and symbols', 'search a message string with a trie to find all diplomacy entity matches and their positions', 'match the case of new text to the original text for consistent entity replacement', 'get a set of possible replacement entities for a given diplomacy entity type like powers or locations', 'splice a replacement string into a message at specified start and end index positions']
```

Usage

```
{'build_entity_trie': 'build a pygtrie CharTrie for tokenization-free entity matching of diplomacy powers, locations, and symbols', 'search_entities': 'search a message string with a trie to find all diplomacy entity matches and their positions', 'match_case': 'match the case of new text to the original text for consistent entity replacement', 'get_possible_replacements': 'get a set of possible replacement entities for a given diplomacy entity type like powers or locations', 'splice_replace': 'splice a replacement string into a message at specified start and end index positions'}
```

