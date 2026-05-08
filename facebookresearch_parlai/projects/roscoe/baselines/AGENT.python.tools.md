# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/roscoe/baselines/run.py

Prompts

```
['run the baseline scoring CLI on human or synthetic datasets with configurable scorers and output directory', 'load human annotation data from JSONL files into Example objects for a given dataset', 'load synthetic perturbation data from JSONL files into Example objects for a given dataset', 'score a list of examples using reference-based metrics and save results to CSV', 'score a list of examples using reference-free metrics and save results to CSV', 'create a RougeBaselineScorer to compute ROUGE-1, ROUGE-2, and ROUGE-L F-measure scores for hypotheses against references', 'create a BertBaselineScorer to compute BERTScore F-measure for comparing candidate texts against reference texts', 'create a BartscoreBaselineScorer to compute BARTScore using the facebook/bart-large checkpoint for text evaluation', 'create a CTCSummaryBaselineScorer to compute CTC relevance and consistency scores for summarization tasks', 'use the register_scorer decorator to register a new scorer class under one or more short name keys']
```

Usage

```
{'run_baseline_scoring': 'run the baseline scoring CLI on human or synthetic datasets with configurable scorers and output directory', 'load_human_data': 'load human annotation data from JSONL files into Example objects for a given dataset', 'load_synthetic_data': 'load synthetic perturbation data from JSONL files into Example objects for a given dataset', 'score_examples_with_ref': 'score a list of examples using reference-based metrics and save results to CSV', 'score_examples_no_ref': 'score a list of examples using reference-free metrics and save results to CSV'}
```

## File: facebookresearch_parlai/projects/roscoe/baselines/scores.py

Prompts

```
['run the baseline scoring CLI on human or synthetic datasets with configurable scorers and output directory', 'load human annotation data from JSONL files into Example objects for a given dataset', 'load synthetic perturbation data from JSONL files into Example objects for a given dataset', 'score a list of examples using reference-based metrics and save results to CSV', 'score a list of examples using reference-free metrics and save results to CSV', 'create a RougeBaselineScorer to compute ROUGE-1, ROUGE-2, and ROUGE-L F-measure scores for hypotheses against references', 'create a BertBaselineScorer to compute BERTScore F-measure for comparing candidate texts against reference texts', 'create a BartscoreBaselineScorer to compute BARTScore using the facebook/bart-large checkpoint for text evaluation', 'create a CTCSummaryBaselineScorer to compute CTC relevance and consistency scores for summarization tasks', 'use the register_scorer decorator to register a new scorer class under one or more short name keys']
```

Usage

```
{'create_rouge_scorer': 'create a RougeBaselineScorer to compute ROUGE-1, ROUGE-2, and ROUGE-L F-measure scores for hypotheses against references', 'create_bertscore_scorer': 'create a BertBaselineScorer to compute BERTScore F-measure for comparing candidate texts against reference texts', 'create_bartscore_scorer': 'create a BartscoreBaselineScorer to compute BARTScore using the facebook/bart-large checkpoint for text evaluation', 'create_ctc_scorer': 'create a CTCSummaryBaselineScorer to compute CTC relevance and consistency scores for summarization tasks', 'register_custom_scorer': 'use the register_scorer decorator to register a new scorer class under one or more short name keys'}
```

