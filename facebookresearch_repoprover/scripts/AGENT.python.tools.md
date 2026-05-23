# Agent Python Tools

- repo: facebookresearch/repoprover
- repo_uri: https://github.com/facebookresearch/repoprover

## File: facebookresearch_repoprover/scripts/count_tokens.py

Prompts

```
['run count_tokens.py on a formalization repo path to get per-agent input and output token counts', 'run count_tokens.py with --json flag to output token statistics as structured JSON data', 'run count_tokens.py with --tex flag to output token statistics as LaTeX tables for papers', 'run count_tokens.py with -v flag to show per-agent breakdown including individual agent details', 'use determine_agent_outcome to classify an agent as merged, approved, errored, or other outcome categories', 'run the script to plot agent efficiency metrics from repoprover runs directory', 'parse session.jsonl files to extract agent outcomes and PR status from a run directory', 'analyze a single agent JSONL file to extract stats like duration, tokens, and outcome', 'plot the fail rate over time using a rolling window of agent outcomes']
```

Usage

```
{'count_tokens_in_run': 'run count_tokens.py on a formalization repo path to get per-agent input and output token counts', 'count_tokens_json_output': 'run count_tokens.py with --json flag to output token statistics as structured JSON data', 'count_tokens_tex_output': 'run count_tokens.py with --tex flag to output token statistics as LaTeX tables for papers', 'count_tokens_verbose': 'run count_tokens.py with -v flag to show per-agent breakdown including individual agent details', 'determine_agent_outcome': 'use determine_agent_outcome to classify an agent as merged, approved, errored, or other outcome categories'}
```

## File: facebookresearch_repoprover/scripts/plot_agent_efficiency.py

Prompts

```
['run count_tokens.py on a formalization repo path to get per-agent input and output token counts', 'run count_tokens.py with --json flag to output token statistics as structured JSON data', 'run count_tokens.py with --tex flag to output token statistics as LaTeX tables for papers', 'run count_tokens.py with -v flag to show per-agent breakdown including individual agent details', 'use determine_agent_outcome to classify an agent as merged, approved, errored, or other outcome categories', 'run the script to plot agent efficiency metrics from repoprover runs directory', 'parse session.jsonl files to extract agent outcomes and PR status from a run directory', 'analyze a single agent JSONL file to extract stats like duration, tokens, and outcome', 'plot the fail rate over time using a rolling window of agent outcomes']
```

Usage

```
{'plot_agent_efficiency': 'run the script to plot agent efficiency metrics from repoprover runs directory', 'parse_session_events': 'parse session.jsonl files to extract agent outcomes and PR status from a run directory', 'analyze_agent_file': 'analyze a single agent JSONL file to extract stats like duration, tokens, and outcome', 'determine_agent_outcome': 'determine the final outcome category for an agent based on session and agent events', 'plot_fail_rate_over_time': 'plot the fail rate over time using a rolling window of agent outcomes'}
```

