# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/reasoning/agents.py

Prompts

```
['create a subclass of StepByStepReasoningTeacher that implements get_data_for_fold yielding steps, question, and answer dicts', 'create a subclass of MWPStepsReasoningTeacher that implements get_data_for_fold yielding math word problem steps and answers', 'create a subclass of NliTeacher that implements get_data_for_fold yielding premise, hypothesis, and reason dicts for NLI tasks', 'review the StepByStepReason class returned by StepByStepReasoningTeacher.get_reason_class for step-by-step reasoning logic', 'review the NliTeacher.add_cmdline_args method that sets the default NLI task prompt for entailment classification', 'build a ParlAI reasoning teacher subclass that extends AbstractReasoningTeacher with custom data loading', 'implement a subclass of AbstractQuestionAnswer to serialize question and answer strings from example dicts', 'implement a subclass of AbstractReason to serialize reasoning chain text from example dicts', 'configure the AbstractReasoningTeacher command line args for reason inclusion, exemplars, and generation targets', 'customize input text and label generation by overriding make_custom_input_text_label in a reasoning teacher', 'build a PremiseHypothesisQuestionAnswer class to serialize premise and hypothesis into a question-answer format with configurable tokens', 'build a SimpleQuestionAnswer class to serialize a question and answer pair with a configurable question token prefix', 'build a MultipleChoiceQuestionAnswer class to serialize multiple choice questions with configurable choice prefixes and answer index lookup', 'refactor the PremiseHypothesisQuestionAnswer class to customize the premise and hypothesis token strings via command-line args', 'review the MultipleChoiceQuestionAnswer class and its choices_prefix default list of lettered option tokens']
```

Usage

```
{'create_step_by_step_reasoning_teacher': 'create a subclass of StepByStepReasoningTeacher that implements get_data_for_fold yielding steps, question, and answer dicts', 'create_mwp_steps_reasoning_teacher': 'create a subclass of MWPStepsReasoningTeacher that implements get_data_for_fold yielding math word problem steps and answers', 'create_nli_teacher': 'create a subclass of NliTeacher that implements get_data_for_fold yielding premise, hypothesis, and reason dicts for NLI tasks', 'review_step_by_step_reason_class': 'review the StepByStepReason class returned by StepByStepReasoningTeacher.get_reason_class for step-by-step reasoning logic', 'review_nli_add_cmdline_args': 'review the NliTeacher.add_cmdline_args method that sets the default NLI task prompt for entailment classification'}
```

## File: facebookresearch_parlai/parlai/tasks/reasoning/base.py

Prompts

```
['create a subclass of StepByStepReasoningTeacher that implements get_data_for_fold yielding steps, question, and answer dicts', 'create a subclass of MWPStepsReasoningTeacher that implements get_data_for_fold yielding math word problem steps and answers', 'create a subclass of NliTeacher that implements get_data_for_fold yielding premise, hypothesis, and reason dicts for NLI tasks', 'review the StepByStepReason class returned by StepByStepReasoningTeacher.get_reason_class for step-by-step reasoning logic', 'review the NliTeacher.add_cmdline_args method that sets the default NLI task prompt for entailment classification', 'build a ParlAI reasoning teacher subclass that extends AbstractReasoningTeacher with custom data loading', 'implement a subclass of AbstractQuestionAnswer to serialize question and answer strings from example dicts', 'implement a subclass of AbstractReason to serialize reasoning chain text from example dicts', 'configure the AbstractReasoningTeacher command line args for reason inclusion, exemplars, and generation targets', 'customize input text and label generation by overriding make_custom_input_text_label in a reasoning teacher', 'build a PremiseHypothesisQuestionAnswer class to serialize premise and hypothesis into a question-answer format with configurable tokens', 'build a SimpleQuestionAnswer class to serialize a question and answer pair with a configurable question token prefix', 'build a MultipleChoiceQuestionAnswer class to serialize multiple choice questions with configurable choice prefixes and answer index lookup', 'refactor the PremiseHypothesisQuestionAnswer class to customize the premise and hypothesis token strings via command-line args', 'review the MultipleChoiceQuestionAnswer class and its choices_prefix default list of lettered option tokens']
```

Usage

```
{'build_reasoning_teacher': 'build a ParlAI reasoning teacher subclass that extends AbstractReasoningTeacher with custom data loading', 'implement_question_answer_class': 'implement a subclass of AbstractQuestionAnswer to serialize question and answer strings from example dicts', 'implement_reason_class': 'implement a subclass of AbstractReason to serialize reasoning chain text from example dicts', 'configure_reasoning_teacher_args': 'configure the AbstractReasoningTeacher command line args for reason inclusion, exemplars, and generation targets', 'customize_input_text_label': 'customize input text and label generation by overriding make_custom_input_text_label in a reasoning teacher'}
```

## File: facebookresearch_parlai/parlai/tasks/reasoning/question_answer.py

Prompts

```
['create a subclass of StepByStepReasoningTeacher that implements get_data_for_fold yielding steps, question, and answer dicts', 'create a subclass of MWPStepsReasoningTeacher that implements get_data_for_fold yielding math word problem steps and answers', 'create a subclass of NliTeacher that implements get_data_for_fold yielding premise, hypothesis, and reason dicts for NLI tasks', 'review the StepByStepReason class returned by StepByStepReasoningTeacher.get_reason_class for step-by-step reasoning logic', 'review the NliTeacher.add_cmdline_args method that sets the default NLI task prompt for entailment classification', 'build a ParlAI reasoning teacher subclass that extends AbstractReasoningTeacher with custom data loading', 'implement a subclass of AbstractQuestionAnswer to serialize question and answer strings from example dicts', 'implement a subclass of AbstractReason to serialize reasoning chain text from example dicts', 'configure the AbstractReasoningTeacher command line args for reason inclusion, exemplars, and generation targets', 'customize input text and label generation by overriding make_custom_input_text_label in a reasoning teacher', 'build a PremiseHypothesisQuestionAnswer class to serialize premise and hypothesis into a question-answer format with configurable tokens', 'build a SimpleQuestionAnswer class to serialize a question and answer pair with a configurable question token prefix', 'build a MultipleChoiceQuestionAnswer class to serialize multiple choice questions with configurable choice prefixes and answer index lookup', 'refactor the PremiseHypothesisQuestionAnswer class to customize the premise and hypothesis token strings via command-line args', 'review the MultipleChoiceQuestionAnswer class and its choices_prefix default list of lettered option tokens']
```

Usage

```
{'build_premise_hypothesis_qa': 'build a PremiseHypothesisQuestionAnswer class to serialize premise and hypothesis into a question-answer format with configurable tokens', 'build_simple_qa': 'build a SimpleQuestionAnswer class to serialize a question and answer pair with a configurable question token prefix', 'build_multiple_choice_qa': 'build a MultipleChoiceQuestionAnswer class to serialize multiple choice questions with configurable choice prefixes and answer index lookup', 'refactor_premise_hypothesis_tokens': 'refactor the PremiseHypothesisQuestionAnswer class to customize the premise and hypothesis token strings via command-line args', 'review_multiple_choice_choices_prefix': 'review the MultipleChoiceQuestionAnswer class and its choices_prefix default list of lettered option tokens'}
```

