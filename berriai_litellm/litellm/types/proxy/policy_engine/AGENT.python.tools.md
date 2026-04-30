# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/types/proxy/policy_engine/pipeline_types.py

Prompts

```
['create a PipelineStep with guardrail name and on_fail, on_pass actions for a guardrail pipeline', 'create a GuardrailPipeline with pre_call or post_call mode and a list of ordered PipelineSteps', 'create a PipelineStepResult with guardrail name, outcome, and action taken after execution', 'create a PipelineExecutionResult with terminal action and a list of step results', 'validate PipelineStep on_fail, on_pass, on_error actions against allowed values', 'create a Policy instance with guardrails to add and an optional parent policy to inherit from', 'build a PolicyCondition that matches requests by model name using exact strings or regex patterns', 'create a PolicyScope to define which teams, keys, models, and tags a policy applies to', 'create a PolicyAttachment that binds a named policy to a scope such as teams, keys, or models', 'build a PolicyConfig containing a dictionary of named policies for the policy engine']
```

Usage

```
{'create_PipelineStep': 'create a PipelineStep with guardrail name and on_fail, on_pass actions for a guardrail pipeline', 'create_GuardrailPipeline': 'create a GuardrailPipeline with pre_call or post_call mode and a list of ordered PipelineSteps', 'create_PipelineStepResult': 'create a PipelineStepResult with guardrail name, outcome, and action taken after execution', 'create_PipelineExecutionResult': 'create a PipelineExecutionResult with terminal action and a list of step results', 'validate_PipelineStep_actions': 'validate PipelineStep on_fail, on_pass, on_error actions against allowed values'}
```

## File: berriai_litellm/litellm/types/proxy/policy_engine/policy_types.py

Prompts

```
['create a PipelineStep with guardrail name and on_fail, on_pass actions for a guardrail pipeline', 'create a GuardrailPipeline with pre_call or post_call mode and a list of ordered PipelineSteps', 'create a PipelineStepResult with guardrail name, outcome, and action taken after execution', 'create a PipelineExecutionResult with terminal action and a list of step results', 'validate PipelineStep on_fail, on_pass, on_error actions against allowed values', 'create a Policy instance with guardrails to add and an optional parent policy to inherit from', 'build a PolicyCondition that matches requests by model name using exact strings or regex patterns', 'create a PolicyScope to define which teams, keys, models, and tags a policy applies to', 'create a PolicyAttachment that binds a named policy to a scope such as teams, keys, or models', 'build a PolicyConfig containing a dictionary of named policies for the policy engine']
```

Usage

```
{'create_policy': 'create a Policy instance with guardrails to add and an optional parent policy to inherit from', 'build_policy_condition': 'build a PolicyCondition that matches requests by model name using exact strings or regex patterns', 'create_policy_scope': 'create a PolicyScope to define which teams, keys, models, and tags a policy applies to', 'create_policy_attachment': 'create a PolicyAttachment that binds a named policy to a scope such as teams, keys, or models', 'build_policy_config': 'build a PolicyConfig containing a dictionary of named policies for the policy engine'}
```

