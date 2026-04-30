# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/aligner/entrypoint/executor.py

Prompts

```
['execute an aligner plan to unshard, reorder, and align tensor pairs across x and y sides', 'execute per-step unshard and reorder plans on a list of tensors returning step-indexed results', 'execute a sequence of sub-plans on tensors collecting shape snapshots and check results', 'execute a single sub-plan dispatching to unsharder or reorderer based on plan type', 'inspect the result of an aligner plan execution including tensors, failure side, and check results', 'build an aligner plan from a pair of metadata lists with optional token and axis aligner configurations', 'compute per-step alignment plans from a list of metadata dicts grouped by step index', 'compute per-step sub plans including unsharder and reorderer plans from metadata and sequence lengths', 'compute axis alignment plan from a pair of dimension specification strings', 'compute unsharder alignment plan from dimension specs, parallel infos, and replicated axes']
```

Usage

```
{'execute_aligner_plan': 'execute an aligner plan to unshard, reorder, and align tensor pairs across x and y sides', 'execute_step_plans': 'execute per-step unshard and reorder plans on a list of tensors returning step-indexed results', 'execute_sub_plans': 'execute a sequence of sub-plans on tensors collecting shape snapshots and check results', 'execute_sub_plan': 'execute a single sub-plan dispatching to unsharder or reorderer based on plan type', 'AlignerResult': 'inspect the result of an aligner plan execution including tensors, failure side, and check results'}
```

## File: sgl-project_sglang/python/sglang/srt/debug_utils/comparator/aligner/entrypoint/planner.py

Prompts

```
['execute an aligner plan to unshard, reorder, and align tensor pairs across x and y sides', 'execute per-step unshard and reorder plans on a list of tensors returning step-indexed results', 'execute a sequence of sub-plans on tensors collecting shape snapshots and check results', 'execute a single sub-plan dispatching to unsharder or reorderer based on plan type', 'inspect the result of an aligner plan execution including tensors, failure side, and check results', 'build an aligner plan from a pair of metadata lists with optional token and axis aligner configurations', 'compute per-step alignment plans from a list of metadata dicts grouped by step index', 'compute per-step sub plans including unsharder and reorderer plans from metadata and sequence lengths', 'compute axis alignment plan from a pair of dimension specification strings', 'compute unsharder alignment plan from dimension specs, parallel infos, and replicated axes']
```

Usage

```
{'build_aligner_plan': 'build an aligner plan from a pair of metadata lists with optional token and axis aligner configurations', 'compute_per_step_plans': 'compute per-step alignment plans from a list of metadata dicts grouped by step index', 'compute_per_step_sub_plans': 'compute per-step sub plans including unsharder and reorderer plans from metadata and sequence lengths', 'compute_axis_aligner_plan': 'compute axis alignment plan from a pair of dimension specification strings', 'compute_unsharder_plan': 'compute unsharder alignment plan from dimension specs, parallel infos, and replicated axes'}
```

