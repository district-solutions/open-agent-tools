# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/light_whoami/task/agents.py

Prompts

```
['build a SpeakerClassifierTeacher to train an RPA classifier on dialogue episodes with speaker labels', 'create RPA episodes from LIGHT dialogue data by enumerating all possible start and label positions', 'run the WhoIsSpeakingTeacher to classify which character is speaking in a dialogue turn', 'test the AmIMeOrYouTeacher to classify whether an utterance belongs to self or partner', 'review the ResponseClassifierTeacher to evaluate model responses against an RPA predictor classifier', 'build a mutator that removes random double-spaces from context lines in LIGHT episodes', 'build a mutator that extracts and attaches the self character name to each episode message', 'build a mutator that breaks episode labels into all partial word sequences left to right', 'review the CleanContextMutator episode_mutation method that splits context and non-context lines and cleans whitespace', 'refactor the LeftToRightMutator episode_mutation method to handle label splitting and partial sequence generation', 'flatten a dialogue episode by prepending prior context lines to each example text field', 'extract self and partner character names from a context string into a dictionary', 'annotate text with a speaker name as a prefix or suffix using optional separator tokens', 'review the flatten function that builds context windows using a deque for dialogue episodes', 'summarize the CONTEXT_KEYS constants that define setting, persona, and name fields for dialogue context']
```

Usage

```
{'build_speaker_classifier_teacher': 'build a SpeakerClassifierTeacher to train an RPA classifier on dialogue episodes with speaker labels', 'create_rpa_episodes': 'create RPA episodes from LIGHT dialogue data by enumerating all possible start and label positions', 'run_who_is_speaking_teacher': 'run the WhoIsSpeakingTeacher to classify which character is speaking in a dialogue turn', 'test_am_i_me_or_you_teacher': 'test the AmIMeOrYouTeacher to classify whether an utterance belongs to self or partner', 'review_response_classifier_teacher': 'review the ResponseClassifierTeacher to evaluate model responses against an RPA predictor classifier'}
```

## File: facebookresearch_parlai/projects/light_whoami/task/mutators.py

Prompts

```
['build a SpeakerClassifierTeacher to train an RPA classifier on dialogue episodes with speaker labels', 'create RPA episodes from LIGHT dialogue data by enumerating all possible start and label positions', 'run the WhoIsSpeakingTeacher to classify which character is speaking in a dialogue turn', 'test the AmIMeOrYouTeacher to classify whether an utterance belongs to self or partner', 'review the ResponseClassifierTeacher to evaluate model responses against an RPA predictor classifier', 'build a mutator that removes random double-spaces from context lines in LIGHT episodes', 'build a mutator that extracts and attaches the self character name to each episode message', 'build a mutator that breaks episode labels into all partial word sequences left to right', 'review the CleanContextMutator episode_mutation method that splits context and non-context lines and cleans whitespace', 'refactor the LeftToRightMutator episode_mutation method to handle label splitting and partial sequence generation', 'flatten a dialogue episode by prepending prior context lines to each example text field', 'extract self and partner character names from a context string into a dictionary', 'annotate text with a speaker name as a prefix or suffix using optional separator tokens', 'review the flatten function that builds context windows using a deque for dialogue episodes', 'summarize the CONTEXT_KEYS constants that define setting, persona, and name fields for dialogue context']
```

Usage

```
{'build_clean_context_mutator': 'build a mutator that removes random double-spaces from context lines in LIGHT episodes', 'build_share_self_character_mutator': 'build a mutator that extracts and attaches the self character name to each episode message', 'build_left_to_right_mutator': 'build a mutator that breaks episode labels into all partial word sequences left to right', 'review_cleancontextmutator_episode_mutation': 'review the CleanContextMutator episode_mutation method that splits context and non-context lines and cleans whitespace', 'refactor_lefttorightmutator_episode_mutation': 'refactor the LeftToRightMutator episode_mutation method to handle label splitting and partial sequence generation'}
```

## File: facebookresearch_parlai/projects/light_whoami/task/utils.py

Prompts

```
['build a SpeakerClassifierTeacher to train an RPA classifier on dialogue episodes with speaker labels', 'create RPA episodes from LIGHT dialogue data by enumerating all possible start and label positions', 'run the WhoIsSpeakingTeacher to classify which character is speaking in a dialogue turn', 'test the AmIMeOrYouTeacher to classify whether an utterance belongs to self or partner', 'review the ResponseClassifierTeacher to evaluate model responses against an RPA predictor classifier', 'build a mutator that removes random double-spaces from context lines in LIGHT episodes', 'build a mutator that extracts and attaches the self character name to each episode message', 'build a mutator that breaks episode labels into all partial word sequences left to right', 'review the CleanContextMutator episode_mutation method that splits context and non-context lines and cleans whitespace', 'refactor the LeftToRightMutator episode_mutation method to handle label splitting and partial sequence generation', 'flatten a dialogue episode by prepending prior context lines to each example text field', 'extract self and partner character names from a context string into a dictionary', 'annotate text with a speaker name as a prefix or suffix using optional separator tokens', 'review the flatten function that builds context windows using a deque for dialogue episodes', 'summarize the CONTEXT_KEYS constants that define setting, persona, and name fields for dialogue context']
```

Usage

```
{'flatten_episode_with_context': 'flatten a dialogue episode by prepending prior context lines to each example text field', 'extract_characters_from_context': 'extract self and partner character names from a context string into a dictionary', 'annotate_speaker_in_text': 'annotate text with a speaker name as a prefix or suffix using optional separator tokens', 'review_flatten_function': 'review the flatten function that builds context windows using a deque for dialogue episodes', 'summarize_context_keys': 'summarize the CONTEXT_KEYS constants that define setting, persona, and name fields for dialogue context'}
```

