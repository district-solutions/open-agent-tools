# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/python/base_agent/dialogue_objects/attribute_helper.py

Prompts

```
['interpret a dialogue span as a FixedValue using the interpreter and optional comparison measure', 'interpret a linear extent attribute with frame of reference, direction, and source or destination', 'resolve a reference object dictionary to a specific memory node or search data using filters and coreference', 'review the attribute_helper module functions for interpreting span values, linear extents, and reference objects', 'refactor interpret_linear_extent to handle missing player frames and force_value logic more cleanly', 'call ConditionInterpreter to parse a dialogue dict and return the appropriate Condition object', 'use interpret_never to create a NeverCondition that always evaluates to false for the agent', 'use interpret_and to build an AndCondition from a list of sub-conditions in the dialogue dict', 'use interpret_or to build an OrCondition from a list of sub-conditions in the dialogue dict', 'use interpret_comparator to compare two values extracted from filters or spans with a given comparison type', 'create a subclass of DialogueObject that implements the step method for custom bot dialogue behavior', 'use the AwaitResponse class to wait for user chat input with a configurable timeout', 'use the Say class to send a random response from a list of options to the user', 'use the ConfirmTask class to ask the user a yes/no question and conditionally push tasks', 'use the BotStackStatus class to report the bot current task like building or moving', 'resolve coreferences in a dialogue logical form dict using memory and chat context', 'process and substitute word spans in a dialogue dict with lemmatized tokens', 'extract tag strings from a dict by filtering keys that start with has_', 'check if a location dict references the SPEAKER_LOOK special reference object', 'strip a given prefix string from the start of another string if present']
```

Usage

```
{'interpret_span_value': 'interpret a dialogue span as a FixedValue using the interpreter and optional comparison measure', 'interpret_linear_extent': 'interpret a linear extent attribute with frame of reference, direction, and source or destination', 'maybe_specific_mem': 'resolve a reference object dictionary to a specific memory node or search data using filters and coreference', 'review_attribute_helper': 'review the attribute_helper module functions for interpreting span values, linear extents, and reference objects', 'refactor_interpret_linear_extent': 'refactor interpret_linear_extent to handle missing player frames and force_value logic more cleanly'}
```

## File: facebookresearch_craftassist/python/base_agent/dialogue_objects/condition_helper.py

Prompts

```
['interpret a dialogue span as a FixedValue using the interpreter and optional comparison measure', 'interpret a linear extent attribute with frame of reference, direction, and source or destination', 'resolve a reference object dictionary to a specific memory node or search data using filters and coreference', 'review the attribute_helper module functions for interpreting span values, linear extents, and reference objects', 'refactor interpret_linear_extent to handle missing player frames and force_value logic more cleanly', 'call ConditionInterpreter to parse a dialogue dict and return the appropriate Condition object', 'use interpret_never to create a NeverCondition that always evaluates to false for the agent', 'use interpret_and to build an AndCondition from a list of sub-conditions in the dialogue dict', 'use interpret_or to build an OrCondition from a list of sub-conditions in the dialogue dict', 'use interpret_comparator to compare two values extracted from filters or spans with a given comparison type', 'create a subclass of DialogueObject that implements the step method for custom bot dialogue behavior', 'use the AwaitResponse class to wait for user chat input with a configurable timeout', 'use the Say class to send a random response from a list of options to the user', 'use the ConfirmTask class to ask the user a yes/no question and conditionally push tasks', 'use the BotStackStatus class to report the bot current task like building or moving', 'resolve coreferences in a dialogue logical form dict using memory and chat context', 'process and substitute word spans in a dialogue dict with lemmatized tokens', 'extract tag strings from a dict by filtering keys that start with has_', 'check if a location dict references the SPEAKER_LOOK special reference object', 'strip a given prefix string from the start of another string if present']
```

Usage

```
{'interpret_condition': 'call ConditionInterpreter to parse a dialogue dict and return the appropriate Condition object', 'interpret_never_condition': 'use interpret_never to create a NeverCondition that always evaluates to false for the agent', 'interpret_and_condition': 'use interpret_and to build an AndCondition from a list of sub-conditions in the dialogue dict', 'interpret_or_condition': 'use interpret_or to build an OrCondition from a list of sub-conditions in the dialogue dict', 'interpret_comparator': 'use interpret_comparator to compare two values extracted from filters or spans with a given comparison type'}
```

## File: facebookresearch_craftassist/python/base_agent/dialogue_objects/dialogue_object.py

Prompts

```
['interpret a dialogue span as a FixedValue using the interpreter and optional comparison measure', 'interpret a linear extent attribute with frame of reference, direction, and source or destination', 'resolve a reference object dictionary to a specific memory node or search data using filters and coreference', 'review the attribute_helper module functions for interpreting span values, linear extents, and reference objects', 'refactor interpret_linear_extent to handle missing player frames and force_value logic more cleanly', 'call ConditionInterpreter to parse a dialogue dict and return the appropriate Condition object', 'use interpret_never to create a NeverCondition that always evaluates to false for the agent', 'use interpret_and to build an AndCondition from a list of sub-conditions in the dialogue dict', 'use interpret_or to build an OrCondition from a list of sub-conditions in the dialogue dict', 'use interpret_comparator to compare two values extracted from filters or spans with a given comparison type', 'create a subclass of DialogueObject that implements the step method for custom bot dialogue behavior', 'use the AwaitResponse class to wait for user chat input with a configurable timeout', 'use the Say class to send a random response from a list of options to the user', 'use the ConfirmTask class to ask the user a yes/no question and conditionally push tasks', 'use the BotStackStatus class to report the bot current task like building or moving', 'resolve coreferences in a dialogue logical form dict using memory and chat context', 'process and substitute word spans in a dialogue dict with lemmatized tokens', 'extract tag strings from a dict by filtering keys that start with has_', 'check if a location dict references the SPEAKER_LOOK special reference object', 'strip a given prefix string from the start of another string if present']
```

Usage

```
{'create_dialogue_object_subclass': 'create a subclass of DialogueObject that implements the step method for custom bot dialogue behavior', 'use_awaitresponse_class': 'use the AwaitResponse class to wait for user chat input with a configurable timeout', 'use_say_class': 'use the Say class to send a random response from a list of options to the user', 'use_confirmtask_class': 'use the ConfirmTask class to ask the user a yes/no question and conditionally push tasks', 'use_botstackstatus_class': 'use the BotStackStatus class to report the bot current task like building or moving'}
```

## File: facebookresearch_craftassist/python/base_agent/dialogue_objects/dialogue_object_utils.py

Prompts

```
['interpret a dialogue span as a FixedValue using the interpreter and optional comparison measure', 'interpret a linear extent attribute with frame of reference, direction, and source or destination', 'resolve a reference object dictionary to a specific memory node or search data using filters and coreference', 'review the attribute_helper module functions for interpreting span values, linear extents, and reference objects', 'refactor interpret_linear_extent to handle missing player frames and force_value logic more cleanly', 'call ConditionInterpreter to parse a dialogue dict and return the appropriate Condition object', 'use interpret_never to create a NeverCondition that always evaluates to false for the agent', 'use interpret_and to build an AndCondition from a list of sub-conditions in the dialogue dict', 'use interpret_or to build an OrCondition from a list of sub-conditions in the dialogue dict', 'use interpret_comparator to compare two values extracted from filters or spans with a given comparison type', 'create a subclass of DialogueObject that implements the step method for custom bot dialogue behavior', 'use the AwaitResponse class to wait for user chat input with a configurable timeout', 'use the Say class to send a random response from a list of options to the user', 'use the ConfirmTask class to ask the user a yes/no question and conditionally push tasks', 'use the BotStackStatus class to report the bot current task like building or moving', 'resolve coreferences in a dialogue logical form dict using memory and chat context', 'process and substitute word spans in a dialogue dict with lemmatized tokens', 'extract tag strings from a dict by filtering keys that start with has_', 'check if a location dict references the SPEAKER_LOOK special reference object', 'strip a given prefix string from the start of another string if present']
```

Usage

```
{'coref_resolve': 'resolve coreferences in a dialogue logical form dict using memory and chat context', 'process_spans': 'process and substitute word spans in a dialogue dict with lemmatized tokens', 'tags_from_dict': 'extract tag strings from a dict by filtering keys that start with has_', 'is_loc_speakerlook': 'check if a location dict references the SPEAKER_LOOK special reference object', 'strip_prefix': 'strip a given prefix string from the start of another string if present'}
```

