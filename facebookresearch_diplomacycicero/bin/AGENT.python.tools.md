# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/bin/get_compare_agent_population_results.py

Prompts

```
['run the CLI tool to compute average square scores and cross-player Elo ratings from game result directories', "run the CLI tool with a base strategy model to analyze each agent's advantage level by game phase", 'run the CLI tool with --compute_elos to fit a multiplayer Elo model across agents and powers', 'run the CLI tool with --include_partial to include incomplete games in the population statistics', 'run the CLI tool against multiple result directories to aggregate population statistics across all games', 'run get_compare_results.py on directories containing game.json files to print RL agent power scores', 'run get_compare_results.py with --stderr flag to print standard error instead of averages', 'run get_compare_results.py with --only-sos flag to print only square score statistics', 'run get_compare_results.py with --all-agents flag to accumulate stats for all agents not just agent_one', 'run get_compare_results.py on multiple result directories at once to aggregate power scores across them']
```

Usage

```
{'run_compare_agent_population_results': 'run the CLI tool to compute average square scores and cross-player Elo ratings from game result directories', 'run_compare_agent_population_results_with_base_model': "run the CLI tool with a base strategy model to analyze each agent's advantage level by game phase", 'run_compare_agent_population_results_compute_elos': 'run the CLI tool with --compute_elos to fit a multiplayer Elo model across agents and powers', 'run_compare_agent_population_results_include_partial': 'run the CLI tool with --include_partial to include incomplete games in the population statistics', 'run_compare_agent_population_results_multiple_dirs': 'run the CLI tool against multiple result directories to aggregate population statistics across all games'}
```

## File: facebookresearch_diplomacycicero/bin/get_compare_results.py

Prompts

```
['run the CLI tool to compute average square scores and cross-player Elo ratings from game result directories', "run the CLI tool with a base strategy model to analyze each agent's advantage level by game phase", 'run the CLI tool with --compute_elos to fit a multiplayer Elo model across agents and powers', 'run the CLI tool with --include_partial to include incomplete games in the population statistics', 'run the CLI tool against multiple result directories to aggregate population statistics across all games', 'run get_compare_results.py on directories containing game.json files to print RL agent power scores', 'run get_compare_results.py with --stderr flag to print standard error instead of averages', 'run get_compare_results.py with --only-sos flag to print only square score statistics', 'run get_compare_results.py with --all-agents flag to accumulate stats for all agents not just agent_one', 'run get_compare_results.py on multiple result directories at once to aggregate power scores across them']
```

Usage

```
{'run_compare_results': 'run get_compare_results.py on directories containing game.json files to print RL agent power scores', 'run_compare_results_stderr': 'run get_compare_results.py with --stderr flag to print standard error instead of averages', 'run_compare_results_sos': 'run get_compare_results.py with --only-sos flag to print only square score statistics', 'run_compare_results_all_agents': 'run get_compare_results.py with --all-agents flag to accumulate stats for all agents not just agent_one', 'run_compare_results_multiple_dirs': 'run get_compare_results.py on multiple result directories at once to aggregate power scores across them'}
```

