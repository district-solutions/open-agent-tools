# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/tools/autoresearch/tests/test_autoresearch_workflow.py

Prompts

```
['create an AutoresearchAdapter to load initial experiment specs and checkpoint workflow state', 'test that HypothesisNode round-trips through to_dict and from_dict with failure records', 'classify terminal job failures into startup, runtime, or unknown kinds using metrics evidence', 'validate experiment specs against a thread budget to filter out over-committed configurations', 'detect duplicate experiment specs by comparing change sets and launch command parameter diffs', 'parse CLI arguments for the autoresearch tool including workdir, agent, pipeline script, and platform options', 'split parsed CLI args into a workdir path and a free-form user request string', 'build the engine command list with agent, platform, pipeline script, source dir, and launch command flags', 'build a supervisor context string listing missing required first-run configuration inputs for the engine', 'build the supervisor system prompt that loads the autoresearch category and configuration details', 'create an autoresearch platform with local execution mode and a temporary workspace directory', 'launch a subprocess job on the platform and poll its status until it succeeds', 'collect metrics evidence from a completed job run including system metrics and pipeline stats', 'parse agent output to extract JSON from markdown code blocks and report parse errors', 'update the priority of a queued experiment in the engine checkpoint file', 'test AsyncWorkEngine to verify work specs execute in lowest priority order first', 'test AsyncWorkEngine to verify completed work enqueues child work specs automatically', 'test AsyncWorkEngine cancellation to verify interrupted state is persisted in checkpoints', 'test AsyncWorkEngine checkpoint and resume lifecycle to verify work continues after interruption', 'review the AsyncWorkEngine adapter interface methods load, checkpoint, make_coro, and on_result']
```

Usage

```
{'create_autoresearch_adapter': 'create an AutoresearchAdapter to load initial experiment specs and checkpoint workflow state', 'test_hypothesis_node_serialization': 'test that HypothesisNode round-trips through to_dict and from_dict with failure records', 'classify_job_failures': 'classify terminal job failures into startup, runtime, or unknown kinds using metrics evidence', 'validate_thread_budget': 'validate experiment specs against a thread budget to filter out over-committed configurations', 'detect_duplicate_specs': 'detect duplicate experiment specs by comparing change sets and launch command parameter diffs'}
```

## File: facebookresearch_spdl/tools/autoresearch/tests/test_cli.py

Prompts

```
['create an AutoresearchAdapter to load initial experiment specs and checkpoint workflow state', 'test that HypothesisNode round-trips through to_dict and from_dict with failure records', 'classify terminal job failures into startup, runtime, or unknown kinds using metrics evidence', 'validate experiment specs against a thread budget to filter out over-committed configurations', 'detect duplicate experiment specs by comparing change sets and launch command parameter diffs', 'parse CLI arguments for the autoresearch tool including workdir, agent, pipeline script, and platform options', 'split parsed CLI args into a workdir path and a free-form user request string', 'build the engine command list with agent, platform, pipeline script, source dir, and launch command flags', 'build a supervisor context string listing missing required first-run configuration inputs for the engine', 'build the supervisor system prompt that loads the autoresearch category and configuration details', 'create an autoresearch platform with local execution mode and a temporary workspace directory', 'launch a subprocess job on the platform and poll its status until it succeeds', 'collect metrics evidence from a completed job run including system metrics and pipeline stats', 'parse agent output to extract JSON from markdown code blocks and report parse errors', 'update the priority of a queued experiment in the engine checkpoint file', 'test AsyncWorkEngine to verify work specs execute in lowest priority order first', 'test AsyncWorkEngine to verify completed work enqueues child work specs automatically', 'test AsyncWorkEngine cancellation to verify interrupted state is persisted in checkpoints', 'test AsyncWorkEngine checkpoint and resume lifecycle to verify work continues after interruption', 'review the AsyncWorkEngine adapter interface methods load, checkpoint, make_coro, and on_result']
```

Usage

```
{'parse_args_cli': 'parse CLI arguments for the autoresearch tool including workdir, agent, pipeline script, and platform options', 'split_workdir_and_request': 'split parsed CLI args into a workdir path and a free-form user request string', 'build_engine_command': 'build the engine command list with agent, platform, pipeline script, source dir, and launch command flags', 'build_supervisor_context': 'build a supervisor context string listing missing required first-run configuration inputs for the engine', 'build_supervisor_prompt': 'build the supervisor system prompt that loads the autoresearch category and configuration details'}
```

## File: facebookresearch_spdl/tools/autoresearch/tests/test_platform.py

Prompts

```
['create an AutoresearchAdapter to load initial experiment specs and checkpoint workflow state', 'test that HypothesisNode round-trips through to_dict and from_dict with failure records', 'classify terminal job failures into startup, runtime, or unknown kinds using metrics evidence', 'validate experiment specs against a thread budget to filter out over-committed configurations', 'detect duplicate experiment specs by comparing change sets and launch command parameter diffs', 'parse CLI arguments for the autoresearch tool including workdir, agent, pipeline script, and platform options', 'split parsed CLI args into a workdir path and a free-form user request string', 'build the engine command list with agent, platform, pipeline script, source dir, and launch command flags', 'build a supervisor context string listing missing required first-run configuration inputs for the engine', 'build the supervisor system prompt that loads the autoresearch category and configuration details', 'create an autoresearch platform with local execution mode and a temporary workspace directory', 'launch a subprocess job on the platform and poll its status until it succeeds', 'collect metrics evidence from a completed job run including system metrics and pipeline stats', 'parse agent output to extract JSON from markdown code blocks and report parse errors', 'update the priority of a queued experiment in the engine checkpoint file', 'test AsyncWorkEngine to verify work specs execute in lowest priority order first', 'test AsyncWorkEngine to verify completed work enqueues child work specs automatically', 'test AsyncWorkEngine cancellation to verify interrupted state is persisted in checkpoints', 'test AsyncWorkEngine checkpoint and resume lifecycle to verify work continues after interruption', 'review the AsyncWorkEngine adapter interface methods load, checkpoint, make_coro, and on_result']
```

Usage

```
{'create_autoresearch_platform': 'create an autoresearch platform with local execution mode and a temporary workspace directory', 'launch_execution_job': 'launch a subprocess job on the platform and poll its status until it succeeds', 'collect_metrics_evidence': 'collect metrics evidence from a completed job run including system metrics and pipeline stats', 'parse_agent_result': 'parse agent output to extract JSON from markdown code blocks and report parse errors', 'update_checkpoint_priority': 'update the priority of a queued experiment in the engine checkpoint file'}
```

## File: facebookresearch_spdl/tools/autoresearch/tests/test_runner.py

Prompts

```
['create an AutoresearchAdapter to load initial experiment specs and checkpoint workflow state', 'test that HypothesisNode round-trips through to_dict and from_dict with failure records', 'classify terminal job failures into startup, runtime, or unknown kinds using metrics evidence', 'validate experiment specs against a thread budget to filter out over-committed configurations', 'detect duplicate experiment specs by comparing change sets and launch command parameter diffs', 'parse CLI arguments for the autoresearch tool including workdir, agent, pipeline script, and platform options', 'split parsed CLI args into a workdir path and a free-form user request string', 'build the engine command list with agent, platform, pipeline script, source dir, and launch command flags', 'build a supervisor context string listing missing required first-run configuration inputs for the engine', 'build the supervisor system prompt that loads the autoresearch category and configuration details', 'create an autoresearch platform with local execution mode and a temporary workspace directory', 'launch a subprocess job on the platform and poll its status until it succeeds', 'collect metrics evidence from a completed job run including system metrics and pipeline stats', 'parse agent output to extract JSON from markdown code blocks and report parse errors', 'update the priority of a queued experiment in the engine checkpoint file', 'test AsyncWorkEngine to verify work specs execute in lowest priority order first', 'test AsyncWorkEngine to verify completed work enqueues child work specs automatically', 'test AsyncWorkEngine cancellation to verify interrupted state is persisted in checkpoints', 'test AsyncWorkEngine checkpoint and resume lifecycle to verify work continues after interruption', 'review the AsyncWorkEngine adapter interface methods load, checkpoint, make_coro, and on_result']
```

Usage

```
{'test_asyncworkengine_priority_order': 'test AsyncWorkEngine to verify work specs execute in lowest priority order first', 'test_asyncworkengine_child_enqueuing': 'test AsyncWorkEngine to verify completed work enqueues child work specs automatically', 'test_asyncworkengine_cancellation': 'test AsyncWorkEngine cancellation to verify interrupted state is persisted in checkpoints', 'test_asyncworkengine_checkpoint_resume': 'test AsyncWorkEngine checkpoint and resume lifecycle to verify work continues after interruption', 'review_asyncworkengine_adapter_interface': 'review the AsyncWorkEngine adapter interface methods load, checkpoint, make_coro, and on_result'}
```

