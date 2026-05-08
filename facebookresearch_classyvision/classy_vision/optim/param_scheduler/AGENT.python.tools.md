# Agent Python Tools

- repo: facebookresearch/classyvision
- repo_uri: https://github.com/facebookresearch/classyvision

## File: facebookresearch_classyvision/classy_vision/optim/param_scheduler/classy_vision_param_scheduler.py

Prompts

```
['create an UpdateInterval enum value from a config dictionary with update_interval key', 'create a ClassyParamScheduler instance with a specified UpdateInterval for epoch or step updates', 'use the UpdateInterval.EPOCH enum to update parameters before each training epoch', 'use the UpdateInterval.STEP enum to update parameters before each optimizer step', 'review the ClassyParamScheduler from_config classmethod to implement custom scheduler instantiation from config', 'build a CompositeParamScheduler with multiple schedulers, lengths, and interval scaling options', 'create a CompositeParamScheduler instance from a config dictionary with schedulers and lengths', 'review the IntervalScaling enum with RESCALED and FIXED members for scheduler intervals', 'refactor the CompositeParamScheduler init to support custom update intervals and scaling strategies', 'test the from_config class method to instantiate a CompositeParamScheduler from a config dict', 'create a CosineParamScheduler from a config dict with name, start_value, and end_value', 'create a LinearParamScheduler from a config dict with name, start_value, and end_value', 'create a StepParamScheduler from a config dict with name, start_value, and boundaries', 'create a PolynomialDecayParamScheduler from a config dict with name, start_value, and power', 'review the _create_classy_scheduler_class factory function that wraps fvcore schedulers with from_config and update_interval']
```

Usage

```
{'create_update_interval_from_config': 'create an UpdateInterval enum value from a config dictionary with update_interval key', 'create_classy_param_scheduler': 'create a ClassyParamScheduler instance with a specified UpdateInterval for epoch or step updates', 'use_update_interval_epoch': 'use the UpdateInterval.EPOCH enum to update parameters before each training epoch', 'use_update_interval_step': 'use the UpdateInterval.STEP enum to update parameters before each optimizer step', 'review_classy_param_scheduler_from_config': 'review the ClassyParamScheduler from_config classmethod to implement custom scheduler instantiation from config'}
```

## File: facebookresearch_classyvision/classy_vision/optim/param_scheduler/composite_scheduler.py

Prompts

```
['create an UpdateInterval enum value from a config dictionary with update_interval key', 'create a ClassyParamScheduler instance with a specified UpdateInterval for epoch or step updates', 'use the UpdateInterval.EPOCH enum to update parameters before each training epoch', 'use the UpdateInterval.STEP enum to update parameters before each optimizer step', 'review the ClassyParamScheduler from_config classmethod to implement custom scheduler instantiation from config', 'build a CompositeParamScheduler with multiple schedulers, lengths, and interval scaling options', 'create a CompositeParamScheduler instance from a config dictionary with schedulers and lengths', 'review the IntervalScaling enum with RESCALED and FIXED members for scheduler intervals', 'refactor the CompositeParamScheduler init to support custom update intervals and scaling strategies', 'test the from_config class method to instantiate a CompositeParamScheduler from a config dict', 'create a CosineParamScheduler from a config dict with name, start_value, and end_value', 'create a LinearParamScheduler from a config dict with name, start_value, and end_value', 'create a StepParamScheduler from a config dict with name, start_value, and boundaries', 'create a PolynomialDecayParamScheduler from a config dict with name, start_value, and power', 'review the _create_classy_scheduler_class factory function that wraps fvcore schedulers with from_config and update_interval']
```

Usage

```
{'build_composite_scheduler': 'build a CompositeParamScheduler with multiple schedulers, lengths, and interval scaling options', 'create_from_config': 'create a CompositeParamScheduler instance from a config dictionary with schedulers and lengths', 'review_interval_scaling_enum': 'review the IntervalScaling enum with RESCALED and FIXED members for scheduler intervals', 'refactor_composite_init': 'refactor the CompositeParamScheduler init to support custom update intervals and scaling strategies', 'test_from_config': 'test the from_config class method to instantiate a CompositeParamScheduler from a config dict'}
```

## File: facebookresearch_classyvision/classy_vision/optim/param_scheduler/fvcore_schedulers.py

Prompts

```
['create an UpdateInterval enum value from a config dictionary with update_interval key', 'create a ClassyParamScheduler instance with a specified UpdateInterval for epoch or step updates', 'use the UpdateInterval.EPOCH enum to update parameters before each training epoch', 'use the UpdateInterval.STEP enum to update parameters before each optimizer step', 'review the ClassyParamScheduler from_config classmethod to implement custom scheduler instantiation from config', 'build a CompositeParamScheduler with multiple schedulers, lengths, and interval scaling options', 'create a CompositeParamScheduler instance from a config dictionary with schedulers and lengths', 'review the IntervalScaling enum with RESCALED and FIXED members for scheduler intervals', 'refactor the CompositeParamScheduler init to support custom update intervals and scaling strategies', 'test the from_config class method to instantiate a CompositeParamScheduler from a config dict', 'create a CosineParamScheduler from a config dict with name, start_value, and end_value', 'create a LinearParamScheduler from a config dict with name, start_value, and end_value', 'create a StepParamScheduler from a config dict with name, start_value, and boundaries', 'create a PolynomialDecayParamScheduler from a config dict with name, start_value, and power', 'review the _create_classy_scheduler_class factory function that wraps fvcore schedulers with from_config and update_interval']
```

Usage

```
{'create_cosine_scheduler_from_config': 'create a CosineParamScheduler from a config dict with name, start_value, and end_value', 'create_linear_scheduler_from_config': 'create a LinearParamScheduler from a config dict with name, start_value, and end_value', 'create_step_scheduler_from_config': 'create a StepParamScheduler from a config dict with name, start_value, and boundaries', 'create_polynomial_decay_scheduler_from_config': 'create a PolynomialDecayParamScheduler from a config dict with name, start_value, and power', 'review_create_classy_scheduler_class': 'review the _create_classy_scheduler_class factory function that wraps fvcore schedulers with from_config and update_interval'}
```

