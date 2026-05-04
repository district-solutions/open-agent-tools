# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/contrib/prefabs/entity/basic_with_image.py

Prompts

```
['build an Entity prefab that generates both text and image outputs in JSON format', 'configure the Entity image_mode parameter to choice, text_first, or image_first for generation ordering', 'set up SituationPerception, SelfPerception, and PersonBySituation components with configurable memory retrieval lengths', 'configure the observation history length and situation perception history length for the Entity agent', 'add an optional overarching goal to the Entity agent by setting the goal parameter in params', 'build a HumanUserEntity prefab with ADHD topic drift and emotional stance components', 'build an AICompanionEntity prefab with goal-directed reasoning and available options perception', 'configure the adhd_period parameter on HumanUserEntity to control topic drift frequency', 'configure the goal parameter on AICompanionEntity to set the overarching goal for reasoning', 'add extra_components dict to HumanUserEntity or AICompanionEntity to include additional agent components']
```

Usage

```
{'build_entity_with_image_output': 'build an Entity prefab that generates both text and image outputs in JSON format', 'configure_image_generation_mode': 'configure the Entity image_mode parameter to choice, text_first, or image_first for generation ordering', 'set_perception_components': 'set up SituationPerception, SelfPerception, and PersonBySituation components with configurable memory retrieval lengths', 'configure_observation_history': 'configure the observation history length and situation perception history length for the Entity agent', 'add_goal_to_entity': 'add an optional overarching goal to the Entity agent by setting the goal parameter in params'}
```

## File: google-deepmind_concordia/concordia/contrib/prefabs/entity/conversations_with_ai_companions.py

Prompts

```
['build an Entity prefab that generates both text and image outputs in JSON format', 'configure the Entity image_mode parameter to choice, text_first, or image_first for generation ordering', 'set up SituationPerception, SelfPerception, and PersonBySituation components with configurable memory retrieval lengths', 'configure the observation history length and situation perception history length for the Entity agent', 'add an optional overarching goal to the Entity agent by setting the goal parameter in params', 'build a HumanUserEntity prefab with ADHD topic drift and emotional stance components', 'build an AICompanionEntity prefab with goal-directed reasoning and available options perception', 'configure the adhd_period parameter on HumanUserEntity to control topic drift frequency', 'configure the goal parameter on AICompanionEntity to set the overarching goal for reasoning', 'add extra_components dict to HumanUserEntity or AICompanionEntity to include additional agent components']
```

Usage

```
{'build_human_user_entity': 'build a HumanUserEntity prefab with ADHD topic drift and emotional stance components', 'build_ai_companion_entity': 'build an AICompanionEntity prefab with goal-directed reasoning and available options perception', 'configure_human_user_adhd_period': 'configure the adhd_period parameter on HumanUserEntity to control topic drift frequency', 'configure_ai_companion_goal': 'configure the goal parameter on AICompanionEntity to set the overarching goal for reasoning', 'add_extra_components_to_entity': 'add extra_components dict to HumanUserEntity or AICompanionEntity to include additional agent components'}
```

