# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/mms/lid_rerank/rerank/rerank.py

Prompts

```
['run the rerank CLI tool to rerank n-best ASR hypotheses using language ID and ASR scores', 'run the select function to score and pick best candidates from n-best ASR and language ID lists', 'build a reranking pipeline that combines speech language ID, word language ID, ASR, LM, and unigram ASR scores', 'test the select function scoring logic that computes weighted scores and picks the highest-scoring candidate per utterance', 'review the rerank module that evaluates language ID accuracy and ASR word error rate on reranked hypotheses', 'run random search to tune reranking coefficients for MMS language ID and ASR n-best lists', 'run the compute function to score n-best candidates using weighted features and return LID accuracy and WER', 'run parallel evaluation of multiple weight combinations using a multiprocessing pool across n-best hypotheses', 'run word error rate calculation using edit distance between hypothesis and reference transcriptions', 'run linear feature scoring across sLID, wLID, ASR, LM, uASR, and length features for reranking']
```

Usage

```
{'run_rerank_cli': 'run the rerank CLI tool to rerank n-best ASR hypotheses using language ID and ASR scores', 'run_select_function': 'run the select function to score and pick best candidates from n-best ASR and language ID lists', 'build_rerank_pipeline': 'build a reranking pipeline that combines speech language ID, word language ID, ASR, LM, and unigram ASR scores', 'test_select_scoring': 'test the select function scoring logic that computes weighted scores and picks the highest-scoring candidate per utterance', 'review_rerank_evaluation': 'review the rerank module that evaluates language ID accuracy and ASR word error rate on reranked hypotheses'}
```

## File: facebookresearch_fairseq/examples/mms/lid_rerank/rerank/tune_coefficients.py

Prompts

```
['run the rerank CLI tool to rerank n-best ASR hypotheses using language ID and ASR scores', 'run the select function to score and pick best candidates from n-best ASR and language ID lists', 'build a reranking pipeline that combines speech language ID, word language ID, ASR, LM, and unigram ASR scores', 'test the select function scoring logic that computes weighted scores and picks the highest-scoring candidate per utterance', 'review the rerank module that evaluates language ID accuracy and ASR word error rate on reranked hypotheses', 'run random search to tune reranking coefficients for MMS language ID and ASR n-best lists', 'run the compute function to score n-best candidates using weighted features and return LID accuracy and WER', 'run parallel evaluation of multiple weight combinations using a multiprocessing pool across n-best hypotheses', 'run word error rate calculation using edit distance between hypothesis and reference transcriptions', 'run linear feature scoring across sLID, wLID, ASR, LM, uASR, and length features for reranking']
```

Usage

```
{'run_coefficient_tuning': 'run random search to tune reranking coefficients for MMS language ID and ASR n-best lists', 'run_compute_function': 'run the compute function to score n-best candidates using weighted features and return LID accuracy and WER', 'run_multiprocessing_evaluation': 'run parallel evaluation of multiple weight combinations using a multiprocessing pool across n-best hypotheses', 'run_wer_calculation': 'run word error rate calculation using edit distance between hypothesis and reference transcriptions', 'run_feature_scoring': 'run linear feature scoring across sLID, wLID, ASR, LM, uASR, and length features for reranking'}
```

