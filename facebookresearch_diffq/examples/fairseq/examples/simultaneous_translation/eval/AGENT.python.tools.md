# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/simultaneous_translation/eval/client.py

Prompts

```
['create a SimulSTEvaluationService to start an HTTP-based simultaneous translation evaluation session on localhost', 'get a source segment by sentence ID from the simultaneous translation evaluation server', 'send a translated hypothesis segment to the simultaneous translation evaluation server for scoring', 'retrieve evaluation scores and finish the simultaneous translation evaluation session via HTTP', 'create a SimulSTLocalEvaluationService to run local simultaneous translation scoring with a scorer', 'run the eval_latency script with --input to compute average lagging metrics from a JSONL file', 'run LatencyScorer.score on a list of dicts with delays and src_len to get latency metrics', 'run LatencyScorer.update_reorder to process a list of delay dictionaries and record latency scores', 'run LatencyScorer.cal_latency to compute and return average latency metrics from recorded scores', 'run LatencyInference on delay and source length tensors to compute differentiable average lagging metrics', 'start a Tornado evaluation server for simultaneous translation scoring on a given port', 'run the evaluation server CLI with custom hostname and port arguments', 'create a ScorerHandler base class that initializes a scorer for HTTP request handling', 'build a SourceHandler endpoint that sends source sentences by ID with optional segment size', 'create a HypothesisHandler endpoint that receives hypothesis tokens for a given sentence ID']
```

Usage

```
{'create_simulst_evaluation_service': 'create a SimulSTEvaluationService to start an HTTP-based simultaneous translation evaluation session on localhost', 'get_src_source_segment': 'get a source segment by sentence ID from the simultaneous translation evaluation server', 'send_hypo_translation': 'send a translated hypothesis segment to the simultaneous translation evaluation server for scoring', 'get_scores_evaluation': 'retrieve evaluation scores and finish the simultaneous translation evaluation session via HTTP', 'create_local_evaluation_service': 'create a SimulSTLocalEvaluationService to run local simultaneous translation scoring with a scorer'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/simultaneous_translation/eval/eval_latency.py

Prompts

```
['create a SimulSTEvaluationService to start an HTTP-based simultaneous translation evaluation session on localhost', 'get a source segment by sentence ID from the simultaneous translation evaluation server', 'send a translated hypothesis segment to the simultaneous translation evaluation server for scoring', 'retrieve evaluation scores and finish the simultaneous translation evaluation session via HTTP', 'create a SimulSTLocalEvaluationService to run local simultaneous translation scoring with a scorer', 'run the eval_latency script with --input to compute average lagging metrics from a JSONL file', 'run LatencyScorer.score on a list of dicts with delays and src_len to get latency metrics', 'run LatencyScorer.update_reorder to process a list of delay dictionaries and record latency scores', 'run LatencyScorer.cal_latency to compute and return average latency metrics from recorded scores', 'run LatencyInference on delay and source length tensors to compute differentiable average lagging metrics', 'start a Tornado evaluation server for simultaneous translation scoring on a given port', 'run the evaluation server CLI with custom hostname and port arguments', 'create a ScorerHandler base class that initializes a scorer for HTTP request handling', 'build a SourceHandler endpoint that sends source sentences by ID with optional segment size', 'create a HypothesisHandler endpoint that receives hypothesis tokens for a given sentence ID']
```

Usage

```
{'run_eval_latency_cli': 'run the eval_latency script with --input to compute average lagging metrics from a JSONL file', 'run_LatencyScorer_score': 'run LatencyScorer.score on a list of dicts with delays and src_len to get latency metrics', 'run_LatencyScorer_update_reorder': 'run LatencyScorer.update_reorder to process a list of delay dictionaries and record latency scores', 'run_LatencyScorer_cal_latency': 'run LatencyScorer.cal_latency to compute and return average latency metrics from recorded scores', 'run_LatencyInference': 'run LatencyInference on delay and source length tensors to compute differentiable average lagging metrics'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/simultaneous_translation/eval/server.py

Prompts

```
['create a SimulSTEvaluationService to start an HTTP-based simultaneous translation evaluation session on localhost', 'get a source segment by sentence ID from the simultaneous translation evaluation server', 'send a translated hypothesis segment to the simultaneous translation evaluation server for scoring', 'retrieve evaluation scores and finish the simultaneous translation evaluation session via HTTP', 'create a SimulSTLocalEvaluationService to run local simultaneous translation scoring with a scorer', 'run the eval_latency script with --input to compute average lagging metrics from a JSONL file', 'run LatencyScorer.score on a list of dicts with delays and src_len to get latency metrics', 'run LatencyScorer.update_reorder to process a list of delay dictionaries and record latency scores', 'run LatencyScorer.cal_latency to compute and return average latency metrics from recorded scores', 'run LatencyInference on delay and source length tensors to compute differentiable average lagging metrics', 'start a Tornado evaluation server for simultaneous translation scoring on a given port', 'run the evaluation server CLI with custom hostname and port arguments', 'create a ScorerHandler base class that initializes a scorer for HTTP request handling', 'build a SourceHandler endpoint that sends source sentences by ID with optional segment size', 'create a HypothesisHandler endpoint that receives hypothesis tokens for a given sentence ID']
```

Usage

```
{'start_evaluation_server': 'start a Tornado evaluation server for simultaneous translation scoring on a given port', 'run_server_cli': 'run the evaluation server CLI with custom hostname and port arguments', 'create_scorer_handler': 'create a ScorerHandler base class that initializes a scorer for HTTP request handling', 'build_source_handler': 'build a SourceHandler endpoint that sends source sentences by ID with optional segment size', 'create_hypothesis_handler': 'create a HypothesisHandler endpoint that receives hypothesis tokens for a given sentence ID'}
```

