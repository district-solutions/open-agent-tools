# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/providers/prolific/api/eligibility_requirement_classes/age_range_eligibility_requirement.py

Prompts

```
['create an AgeRangeEligibilityRequirement instance with min_age and max_age parameters for Prolific study eligibility', 'build a Prolific API eligibility requirement dictionary from an AgeRangeEligibilityRequirement using to_prolific_dict', 'review the AgeRangeEligibilityRequirement class and its to_prolific_dict method for Prolific API integration', 'refactor the to_prolific_dict method to dynamically resolve the age range question ID instead of hardcoding it', 'summarize the AgeRangeEligibilityRequirement class structure and its inheritance from BaseEligibilityRequirement', 'create a subclass of BaseEligibilityRequirement with a prolific_cls_name and init params for Prolific eligibility', 'get the __init__ parameter names from a BaseEligibilityRequirement subclass using the params class method', 'convert a BaseEligibilityRequirement instance to a Prolific API dict with _cls and attributes keys', 'get a string representation of a BaseEligibilityRequirement instance showing class name and param values', 'handle omegaconf ListConfig values when converting eligibility requirement params to a Prolific dict', 'create a ParticipantGroupEligibilityRequirement instance with a participant group id string', 'inspect the prolific_cls_name attribute to get the Prolific web eligibility model class path', 'review the ParticipantGroupEligibilityRequirement class and its to_prolific_dict serialization method']
```

Usage

```
{'create_age_range_requirement': 'create an AgeRangeEligibilityRequirement instance with min_age and max_age parameters for Prolific study eligibility', 'build_prolific_dict': 'build a Prolific API eligibility requirement dictionary from an AgeRangeEligibilityRequirement using to_prolific_dict', 'review_age_range_class': 'review the AgeRangeEligibilityRequirement class and its to_prolific_dict method for Prolific API integration', 'refactor_to_prolific_dict': 'refactor the to_prolific_dict method to dynamically resolve the age range question ID instead of hardcoding it', 'summarize_eligibility_requirement': 'summarize the AgeRangeEligibilityRequirement class structure and its inheritance from BaseEligibilityRequirement'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/providers/prolific/api/eligibility_requirement_classes/base_eligibility_requirement.py

Prompts

```
['create an AgeRangeEligibilityRequirement instance with min_age and max_age parameters for Prolific study eligibility', 'build a Prolific API eligibility requirement dictionary from an AgeRangeEligibilityRequirement using to_prolific_dict', 'review the AgeRangeEligibilityRequirement class and its to_prolific_dict method for Prolific API integration', 'refactor the to_prolific_dict method to dynamically resolve the age range question ID instead of hardcoding it', 'summarize the AgeRangeEligibilityRequirement class structure and its inheritance from BaseEligibilityRequirement', 'create a subclass of BaseEligibilityRequirement with a prolific_cls_name and init params for Prolific eligibility', 'get the __init__ parameter names from a BaseEligibilityRequirement subclass using the params class method', 'convert a BaseEligibilityRequirement instance to a Prolific API dict with _cls and attributes keys', 'get a string representation of a BaseEligibilityRequirement instance showing class name and param values', 'handle omegaconf ListConfig values when converting eligibility requirement params to a Prolific dict', 'create a ParticipantGroupEligibilityRequirement instance with a participant group id string', 'inspect the prolific_cls_name attribute to get the Prolific web eligibility model class path', 'review the ParticipantGroupEligibilityRequirement class and its to_prolific_dict serialization method']
```

Usage

```
{'create_eligibility_requirement_subclass': 'create a subclass of BaseEligibilityRequirement with a prolific_cls_name and init params for Prolific eligibility', 'get_init_params': 'get the __init__ parameter names from a BaseEligibilityRequirement subclass using the params class method', 'convert_to_prolific_dict': 'convert a BaseEligibilityRequirement instance to a Prolific API dict with _cls and attributes keys', 'stringify_eligibility_requirement': 'get a string representation of a BaseEligibilityRequirement instance showing class name and param values', 'handle_listconfig_in_eligibility': 'handle omegaconf ListConfig values when converting eligibility requirement params to a Prolific dict'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/providers/prolific/api/eligibility_requirement_classes/participant_group_eligibility_requirement.py

Prompts

```
['create an AgeRangeEligibilityRequirement instance with min_age and max_age parameters for Prolific study eligibility', 'build a Prolific API eligibility requirement dictionary from an AgeRangeEligibilityRequirement using to_prolific_dict', 'review the AgeRangeEligibilityRequirement class and its to_prolific_dict method for Prolific API integration', 'refactor the to_prolific_dict method to dynamically resolve the age range question ID instead of hardcoding it', 'summarize the AgeRangeEligibilityRequirement class structure and its inheritance from BaseEligibilityRequirement', 'create a subclass of BaseEligibilityRequirement with a prolific_cls_name and init params for Prolific eligibility', 'get the __init__ parameter names from a BaseEligibilityRequirement subclass using the params class method', 'convert a BaseEligibilityRequirement instance to a Prolific API dict with _cls and attributes keys', 'get a string representation of a BaseEligibilityRequirement instance showing class name and param values', 'handle omegaconf ListConfig values when converting eligibility requirement params to a Prolific dict', 'create a ParticipantGroupEligibilityRequirement instance with a participant group id string', 'inspect the prolific_cls_name attribute to get the Prolific web eligibility model class path', 'review the ParticipantGroupEligibilityRequirement class and its to_prolific_dict serialization method']
```

Usage

```
{'create_participant_group_eligibility': 'create a ParticipantGroupEligibilityRequirement instance with a participant group id string', 'convert_to_prolific_dict': 'call to_prolific_dict on a ParticipantGroupEligibilityRequirement to get the Prolific API format dictionary', 'check_eligibility_class_name': 'inspect the prolific_cls_name attribute to get the Prolific web eligibility model class path', 'review_participant_group_requirement': 'review the ParticipantGroupEligibilityRequirement class and its to_prolific_dict serialization method', 'summarize_eligibility_requirement': 'summarize the ParticipantGroupEligibilityRequirement class that restricts Prolific studies to a participant group'}
```

