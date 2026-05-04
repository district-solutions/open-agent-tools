# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/contrib/components/agent/adhd_topic_drift.py

Prompts

```
['build a python module using AdhdTopicDrift to periodically inject topic pivot instructions into an agent', 'create an AdhdTopicDrift instance with a custom period to control how often topic pivots occur', 'test the AdhdTopicDrift pre_act method to verify it returns pivot instructions every N steps', 'review the AdhdTopicDrift get_state and set_state methods for serialization and deserialization of step count and period', 'refactor the AdhdTopicDrift _make_pre_act_value method to customize the topic pivot instruction template', 'create a ChoiceOfComponent that selects the most relevant component from a menu using an LLM', 'create a ChoiceOfComponentWithoutPreAct that selects components silently without outputting to pre_act', 'review the _make_pre_act_value method that uses multiple choice to pick the best component', 'refactor the ChoiceOfComponent to customize its logging channel for debug output', 'test the ChoiceOfComponent set_entity method to verify component selection works correctly', 'create an EmotionalStance component that selects an emotion from a curated list before an agent acts', 'build an agent reasoning pipeline that uses EmotionalStance to force emotion selection before actions', 'configure the EmotionalStance component with custom emotion options and observation selection count', 'review the _make_pre_act_value method that uses multiple choice and open question prompts to determine agent emotion', 'summarize the EmotionalStance class that combines situational reasoning with emotion-driven observation selection', "create a SituationRepresentation component that narratively summarizes an agent's current situation using a language model", 'build a SituationRepresentation component with a clock_now function to track the current date and time', 'configure a SituationRepresentation component to declare the entity as the protagonist in prompts', 'get the JSON state of a SituationRepresentation component including the situation_thus_far narrative', 'set the SituationRepresentation component state from JSON data to restore the situation narrative']
```

Usage

```
{'build_adhd_topic_drift_component': 'build a python module using AdhdTopicDrift to periodically inject topic pivot instructions into an agent', 'create_adhd_topic_drift_with_custom_period': 'create an AdhdTopicDrift instance with a custom period to control how often topic pivots occur', 'test_pre_act_method': 'test the AdhdTopicDrift pre_act method to verify it returns pivot instructions every N steps', 'review_get_state_set_state': 'review the AdhdTopicDrift get_state and set_state methods for serialization and deserialization of step count and period', 'refactor_make_pre_act_value': 'refactor the AdhdTopicDrift _make_pre_act_value method to customize the topic pivot instruction template'}
```

## File: google-deepmind_concordia/concordia/contrib/components/agent/choice_of_component.py

Prompts

```
['build a python module using AdhdTopicDrift to periodically inject topic pivot instructions into an agent', 'create an AdhdTopicDrift instance with a custom period to control how often topic pivots occur', 'test the AdhdTopicDrift pre_act method to verify it returns pivot instructions every N steps', 'review the AdhdTopicDrift get_state and set_state methods for serialization and deserialization of step count and period', 'refactor the AdhdTopicDrift _make_pre_act_value method to customize the topic pivot instruction template', 'create a ChoiceOfComponent that selects the most relevant component from a menu using an LLM', 'create a ChoiceOfComponentWithoutPreAct that selects components silently without outputting to pre_act', 'review the _make_pre_act_value method that uses multiple choice to pick the best component', 'refactor the ChoiceOfComponent to customize its logging channel for debug output', 'test the ChoiceOfComponent set_entity method to verify component selection works correctly', 'create an EmotionalStance component that selects an emotion from a curated list before an agent acts', 'build an agent reasoning pipeline that uses EmotionalStance to force emotion selection before actions', 'configure the EmotionalStance component with custom emotion options and observation selection count', 'review the _make_pre_act_value method that uses multiple choice and open question prompts to determine agent emotion', 'summarize the EmotionalStance class that combines situational reasoning with emotion-driven observation selection', "create a SituationRepresentation component that narratively summarizes an agent's current situation using a language model", 'build a SituationRepresentation component with a clock_now function to track the current date and time', 'configure a SituationRepresentation component to declare the entity as the protagonist in prompts', 'get the JSON state of a SituationRepresentation component including the situation_thus_far narrative', 'set the SituationRepresentation component state from JSON data to restore the situation narrative']
```

Usage

```
{'create_choice_of_component': 'create a ChoiceOfComponent that selects the most relevant component from a menu using an LLM', 'create_choice_of_component_without_pre_act': 'create a ChoiceOfComponentWithoutPreAct that selects components silently without outputting to pre_act', 'review_choice_of_component_make_pre_act_value': 'review the _make_pre_act_value method that uses multiple choice to pick the best component', 'refactor_choice_of_component_logging': 'refactor the ChoiceOfComponent to customize its logging channel for debug output', 'test_choice_of_component_entity': 'test the ChoiceOfComponent set_entity method to verify component selection works correctly'}
```

## File: google-deepmind_concordia/concordia/contrib/components/agent/emotional_stance.py

Prompts

```
['build a python module using AdhdTopicDrift to periodically inject topic pivot instructions into an agent', 'create an AdhdTopicDrift instance with a custom period to control how often topic pivots occur', 'test the AdhdTopicDrift pre_act method to verify it returns pivot instructions every N steps', 'review the AdhdTopicDrift get_state and set_state methods for serialization and deserialization of step count and period', 'refactor the AdhdTopicDrift _make_pre_act_value method to customize the topic pivot instruction template', 'create a ChoiceOfComponent that selects the most relevant component from a menu using an LLM', 'create a ChoiceOfComponentWithoutPreAct that selects components silently without outputting to pre_act', 'review the _make_pre_act_value method that uses multiple choice to pick the best component', 'refactor the ChoiceOfComponent to customize its logging channel for debug output', 'test the ChoiceOfComponent set_entity method to verify component selection works correctly', 'create an EmotionalStance component that selects an emotion from a curated list before an agent acts', 'build an agent reasoning pipeline that uses EmotionalStance to force emotion selection before actions', 'configure the EmotionalStance component with custom emotion options and observation selection count', 'review the _make_pre_act_value method that uses multiple choice and open question prompts to determine agent emotion', 'summarize the EmotionalStance class that combines situational reasoning with emotion-driven observation selection', "create a SituationRepresentation component that narratively summarizes an agent's current situation using a language model", 'build a SituationRepresentation component with a clock_now function to track the current date and time', 'configure a SituationRepresentation component to declare the entity as the protagonist in prompts', 'get the JSON state of a SituationRepresentation component including the situation_thus_far narrative', 'set the SituationRepresentation component state from JSON data to restore the situation narrative']
```

Usage

```
{'create_emotional_stance_component': 'create an EmotionalStance component that selects an emotion from a curated list before an agent acts', 'build_emotion_driven_agent': 'build an agent reasoning pipeline that uses EmotionalStance to force emotion selection before actions', 'configure_emotion_options': 'configure the EmotionalStance component with custom emotion options and observation selection count', 'review_make_pre_act_value': 'review the _make_pre_act_value method that uses multiple choice and open question prompts to determine agent emotion', 'summarize_emotional_stance_class': 'summarize the EmotionalStance class that combines situational reasoning with emotion-driven observation selection'}
```

## File: google-deepmind_concordia/concordia/contrib/components/agent/situation_representation_via_narrative.py

Prompts

```
['build a python module using AdhdTopicDrift to periodically inject topic pivot instructions into an agent', 'create an AdhdTopicDrift instance with a custom period to control how often topic pivots occur', 'test the AdhdTopicDrift pre_act method to verify it returns pivot instructions every N steps', 'review the AdhdTopicDrift get_state and set_state methods for serialization and deserialization of step count and period', 'refactor the AdhdTopicDrift _make_pre_act_value method to customize the topic pivot instruction template', 'create a ChoiceOfComponent that selects the most relevant component from a menu using an LLM', 'create a ChoiceOfComponentWithoutPreAct that selects components silently without outputting to pre_act', 'review the _make_pre_act_value method that uses multiple choice to pick the best component', 'refactor the ChoiceOfComponent to customize its logging channel for debug output', 'test the ChoiceOfComponent set_entity method to verify component selection works correctly', 'create an EmotionalStance component that selects an emotion from a curated list before an agent acts', 'build an agent reasoning pipeline that uses EmotionalStance to force emotion selection before actions', 'configure the EmotionalStance component with custom emotion options and observation selection count', 'review the _make_pre_act_value method that uses multiple choice and open question prompts to determine agent emotion', 'summarize the EmotionalStance class that combines situational reasoning with emotion-driven observation selection', "create a SituationRepresentation component that narratively summarizes an agent's current situation using a language model", 'build a SituationRepresentation component with a clock_now function to track the current date and time', 'configure a SituationRepresentation component to declare the entity as the protagonist in prompts', 'get the JSON state of a SituationRepresentation component including the situation_thus_far narrative', 'set the SituationRepresentation component state from JSON data to restore the situation narrative']
```

Usage

```
{'create_SituationRepresentation_component': "create a SituationRepresentation component that narratively summarizes an agent's current situation using a language model", 'build_SituationRepresentation_with_clock': 'build a SituationRepresentation component with a clock_now function to track the current date and time', 'configure_SituationRepresentation_protagonist': 'configure a SituationRepresentation component to declare the entity as the protagonist in prompts', 'get_state_SituationRepresentation': 'get the JSON state of a SituationRepresentation component including the situation_thus_far narrative', 'set_state_SituationRepresentation': 'set the SituationRepresentation component state from JSON data to restore the situation narrative'}
```

