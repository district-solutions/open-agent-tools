# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/environments/benchmarks/yc_bench/yc_bench_env.py

Prompts

```
['run YC-Bench evaluation over preset and seed combinations to score agentic LLMs on long-horizon business simulation survival', 'build a YCBenchEvalConfig with preset names, seeds, scoring weights, and simulation horizon parameters', 'read final game state from a YC-Bench SQLite database including funds, survival status, and terminal reason', 'compute composite score from survival and normalised final funds using configurable weights and log-scale normalisation', 'summarize the YC-Bench system prompt that instructs an autonomous CEO agent on managing a simulated AI startup']
```

Usage

```
{'run_yc_bench_evaluation': 'run YC-Bench evaluation over preset and seed combinations to score agentic LLMs on long-horizon business simulation survival', 'build_yc_bench_config': 'build a YCBenchEvalConfig with preset names, seeds, scoring weights, and simulation horizon parameters', 'read_final_score_from_db': 'read final game state from a YC-Bench SQLite database including funds, survival status, and terminal reason', 'compute_composite_score': 'compute composite score from survival and normalised final funds using configurable weights and log-scale normalisation', 'summarize_yc_bench_system_prompt': 'summarize the YC-Bench system prompt that instructs an autonomous CEO agent on managing a simulated AI startup'}
```

