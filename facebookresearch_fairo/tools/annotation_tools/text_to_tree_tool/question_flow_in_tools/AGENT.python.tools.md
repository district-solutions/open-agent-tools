# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/tools/annotation_tools/text_to_tree_tool/question_flow_in_tools/question_flow_for_step_3.py

Prompts

```
['get annotation questions for a reference object location using get_questions with child reference_object and ref_obj_child location', 'get annotation questions for reference object filters using get_questions with child filters and action tag', 'get level one annotation questions for a reference object using get_questions with child reference_object and ref_obj_child empty string', 'summarize the LOCATION_RADIO list which defines location question options for the annotation tool UI', 'review the LOCATION_REL_OBJECT nested question flow for relative direction and reference object annotation', "get the annotation question flow for a schematic build action with child 'schematic' and action 'build'", "get the annotation question flow for a schematic dig action with child 'schematic' and action 'dig'", "get the annotation question flow for location questions with child 'location' and action 'build'", "get the annotation question flow for facing questions with child 'facing' and any action", "get the annotation question flow for reference object questions with child 'reference_object' and action 'destroy'", 'get the annotation question flow for a receiver reference object with a specified action', 'get the annotation question flow for tag filter actions on reference objects', 'summarize the LOCATION_REL_OBJECT data structure that defines relative object location questions for the annotation tool', "get the annotation question flow for comparison operations by calling get_questions with ref_obj_child set to 'comparison'", 'review the LOCATION_RADIO list to understand location annotation options including coordinates, speaker position, and agent position', 'review the QUANTITY_OPTIONS dict to understand property comparison annotation for height, width, depth, time, and block counts', 'review the ORDINAL_OPTIONS dict to understand ordinal ranking annotation for first, second, third, and other ranked positions']
```

Usage

```
{'get_questions_reference_object_location': 'get annotation questions for a reference object location using get_questions with child reference_object and ref_obj_child location', 'get_questions_reference_object_filters': 'get annotation questions for reference object filters using get_questions with child filters and action tag', 'get_questions_reference_object_level_one': 'get level one annotation questions for a reference object using get_questions with child reference_object and ref_obj_child empty string', 'summarize_LOCATION_RADIO': 'summarize the LOCATION_RADIO list which defines location question options for the annotation tool UI', 'review_LOCATION_REL_OBJECT': 'review the LOCATION_REL_OBJECT nested question flow for relative direction and reference object annotation'}
```

## File: facebookresearch_fairo/tools/annotation_tools/text_to_tree_tool/question_flow_in_tools/question_flow_for_tool_B.py

Prompts

```
['get annotation questions for a reference object location using get_questions with child reference_object and ref_obj_child location', 'get annotation questions for reference object filters using get_questions with child filters and action tag', 'get level one annotation questions for a reference object using get_questions with child reference_object and ref_obj_child empty string', 'summarize the LOCATION_RADIO list which defines location question options for the annotation tool UI', 'review the LOCATION_REL_OBJECT nested question flow for relative direction and reference object annotation', "get the annotation question flow for a schematic build action with child 'schematic' and action 'build'", "get the annotation question flow for a schematic dig action with child 'schematic' and action 'dig'", "get the annotation question flow for location questions with child 'location' and action 'build'", "get the annotation question flow for facing questions with child 'facing' and any action", "get the annotation question flow for reference object questions with child 'reference_object' and action 'destroy'", 'get the annotation question flow for a receiver reference object with a specified action', 'get the annotation question flow for tag filter actions on reference objects', 'summarize the LOCATION_REL_OBJECT data structure that defines relative object location questions for the annotation tool', "get the annotation question flow for comparison operations by calling get_questions with ref_obj_child set to 'comparison'", 'review the LOCATION_RADIO list to understand location annotation options including coordinates, speaker position, and agent position', 'review the QUANTITY_OPTIONS dict to understand property comparison annotation for height, width, depth, time, and block counts', 'review the ORDINAL_OPTIONS dict to understand ordinal ranking annotation for first, second, third, and other ranked positions']
```

Usage

```
{'get_questions_schematic_build': "get the annotation question flow for a schematic build action with child 'schematic' and action 'build'", 'get_questions_schematic_dig': "get the annotation question flow for a schematic dig action with child 'schematic' and action 'dig'", 'get_questions_location': "get the annotation question flow for location questions with child 'location' and action 'build'", 'get_questions_facing': "get the annotation question flow for facing questions with child 'facing' and any action", 'get_questions_reference_object': "get the annotation question flow for reference object questions with child 'reference_object' and action 'destroy'"}
```

## File: facebookresearch_fairo/tools/annotation_tools/text_to_tree_tool/question_flow_in_tools/question_flow_for_tool_C.py

Prompts

```
['get annotation questions for a reference object location using get_questions with child reference_object and ref_obj_child location', 'get annotation questions for reference object filters using get_questions with child filters and action tag', 'get level one annotation questions for a reference object using get_questions with child reference_object and ref_obj_child empty string', 'summarize the LOCATION_RADIO list which defines location question options for the annotation tool UI', 'review the LOCATION_REL_OBJECT nested question flow for relative direction and reference object annotation', "get the annotation question flow for a schematic build action with child 'schematic' and action 'build'", "get the annotation question flow for a schematic dig action with child 'schematic' and action 'dig'", "get the annotation question flow for location questions with child 'location' and action 'build'", "get the annotation question flow for facing questions with child 'facing' and any action", "get the annotation question flow for reference object questions with child 'reference_object' and action 'destroy'", 'get the annotation question flow for a receiver reference object with a specified action', 'get the annotation question flow for tag filter actions on reference objects', 'summarize the LOCATION_REL_OBJECT data structure that defines relative object location questions for the annotation tool', "get the annotation question flow for comparison operations by calling get_questions with ref_obj_child set to 'comparison'", 'review the LOCATION_RADIO list to understand location annotation options including coordinates, speaker position, and agent position', 'review the QUANTITY_OPTIONS dict to understand property comparison annotation for height, width, depth, time, and block counts', 'review the ORDINAL_OPTIONS dict to understand ordinal ranking annotation for first, second, third, and other ranked positions']
```

Usage

```
{'get_questions_reference_object': 'get the annotation question flow for a reference object given its action type like spawn or destroy', 'get_questions_receiver_reference_object': 'get the annotation question flow for a receiver reference object with a specified action', 'get_questions_tag_filter': 'get the annotation question flow for tag filter actions on reference objects', 'summarize_LOCATION_RADIO': 'summarize the LOCATION_RADIO data structure that defines location question options for the annotation tool', 'summarize_LOCATION_REL_OBJECT': 'summarize the LOCATION_REL_OBJECT data structure that defines relative object location questions for the annotation tool'}
```

## File: facebookresearch_fairo/tools/annotation_tools/text_to_tree_tool/question_flow_in_tools/question_flow_for_tool_D.py

Prompts

```
['get annotation questions for a reference object location using get_questions with child reference_object and ref_obj_child location', 'get annotation questions for reference object filters using get_questions with child filters and action tag', 'get level one annotation questions for a reference object using get_questions with child reference_object and ref_obj_child empty string', 'summarize the LOCATION_RADIO list which defines location question options for the annotation tool UI', 'review the LOCATION_REL_OBJECT nested question flow for relative direction and reference object annotation', "get the annotation question flow for a schematic build action with child 'schematic' and action 'build'", "get the annotation question flow for a schematic dig action with child 'schematic' and action 'dig'", "get the annotation question flow for location questions with child 'location' and action 'build'", "get the annotation question flow for facing questions with child 'facing' and any action", "get the annotation question flow for reference object questions with child 'reference_object' and action 'destroy'", 'get the annotation question flow for a receiver reference object with a specified action', 'get the annotation question flow for tag filter actions on reference objects', 'summarize the LOCATION_REL_OBJECT data structure that defines relative object location questions for the annotation tool', "get the annotation question flow for comparison operations by calling get_questions with ref_obj_child set to 'comparison'", 'review the LOCATION_RADIO list to understand location annotation options including coordinates, speaker position, and agent position', 'review the QUANTITY_OPTIONS dict to understand property comparison annotation for height, width, depth, time, and block counts', 'review the ORDINAL_OPTIONS dict to understand ordinal ranking annotation for first, second, third, and other ranked positions']
```

Usage

```
{'get_questions_comparison': "get the annotation question flow for comparison operations by calling get_questions with ref_obj_child set to 'comparison'", 'review_LOCATION_RADIO': 'review the LOCATION_RADIO list to understand location annotation options including coordinates, speaker position, and agent position', 'review_LOCATION_REL_OBJECT': 'review the LOCATION_REL_OBJECT list to understand relative object location annotation with directional and span selection options', 'review_QUANTITY_OPTIONS': 'review the QUANTITY_OPTIONS dict to understand property comparison annotation for height, width, depth, time, and block counts', 'review_ORDINAL_OPTIONS': 'review the ORDINAL_OPTIONS dict to understand ordinal ranking annotation for first, second, third, and other ranked positions'}
```

