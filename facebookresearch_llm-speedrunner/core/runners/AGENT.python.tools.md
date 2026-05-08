# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/core/runners/bon_science_runner.py

Prompts

```
['run the BoNScienceRunner to evaluate N hypotheses and continue with best-of-N selection across iterations', 'create a BoNScienceRunner instance with experiment config, workspace, agent, ideator, coder, and slurm config', 'select the next open version to branch from by choosing top-performing or buggy leaf versions', 'run an experiment on a workspace version by coding hypotheses and submitting jobs to SLURM', 'run evaluation on a workspace version by submitting eval jobs and recording results via callback', 'initialize a ScienceRunner with ExperimentConfig, Workspace, Agent, Ideator, Coder, and SlurmConfig', 'extract metrics from job logs for a given version using regex or LLM fallback', 'set results for a workspace version by summarizing logs and extracting metrics', 'run the ScienceRunner experiment loop for a specified number of iterations', 'shutdown the ScienceRunner by cancelling pending SLURM jobs and deleting pending versions']
```

Usage

```
{'run_BON_science_loop': 'run the BoNScienceRunner to evaluate N hypotheses and continue with best-of-N selection across iterations', 'create_BON_science_runner': 'create a BoNScienceRunner instance with experiment config, workspace, agent, ideator, coder, and slurm config', 'select_next_open_version': 'select the next open version to branch from by choosing top-performing or buggy leaf versions', 'run_experiment_on_version': 'run an experiment on a workspace version by coding hypotheses and submitting jobs to SLURM', 'run_evaluation_on_version': 'run evaluation on a workspace version by submitting eval jobs and recording results via callback'}
```

## File: facebookresearch_llm-speedrunner/core/runners/science_runner.py

Prompts

```
['run the BoNScienceRunner to evaluate N hypotheses and continue with best-of-N selection across iterations', 'create a BoNScienceRunner instance with experiment config, workspace, agent, ideator, coder, and slurm config', 'select the next open version to branch from by choosing top-performing or buggy leaf versions', 'run an experiment on a workspace version by coding hypotheses and submitting jobs to SLURM', 'run evaluation on a workspace version by submitting eval jobs and recording results via callback', 'initialize a ScienceRunner with ExperimentConfig, Workspace, Agent, Ideator, Coder, and SlurmConfig', 'extract metrics from job logs for a given version using regex or LLM fallback', 'set results for a workspace version by summarizing logs and extracting metrics', 'run the ScienceRunner experiment loop for a specified number of iterations', 'shutdown the ScienceRunner by cancelling pending SLURM jobs and deleting pending versions']
```

Usage

```
{'init_science_runner': 'initialize a ScienceRunner with ExperimentConfig, Workspace, Agent, Ideator, Coder, and SlurmConfig', 'extract_metrics_from_logs': 'extract metrics from job logs for a given version using regex or LLM fallback', 'set_results_for_version': 'set results for a workspace version by summarizing logs and extracting metrics', 'run_science_experiment': 'run the ScienceRunner experiment loop for a specified number of iterations', 'shutdown_science_runner': 'shutdown the ScienceRunner by cancelling pending SLURM jobs and deleting pending versions'}
```

