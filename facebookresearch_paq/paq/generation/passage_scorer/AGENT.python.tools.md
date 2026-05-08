# Agent Python Tools

- repo: facebookresearch/paq
- repo_uri: https://github.com/facebookresearch/paq

## File: facebookresearch_paq/paq/generation/passage_scorer/score_passages.py

Prompts

```
['run the passage scorer CLI to score passages from a file using a config and write results', 'run load_passages to load passages from a JSONL or DPR TSV file by path', 'run score_passages to score a list of passages using a passage scorer config', 'run score_passages_and_write_to_file to score passages and dump annotations to a JSONL output file', 'review the passage scorer CLI arguments for passages_to_score, output_path, path_to_config, and verbose', 'load a passage scorer by name from config using load_passage_scorer', 'score passages with a fixed default score using DummyPassageScorer', 'score passages by looking up precomputed scores from a file using LookupPassageScorer', 'score passages in batches using a pretrained sequence classification model via LearntPassageScorer', 'tokenize a list of text passages into model-ready input tensors using LearntPassageScorer']
```

Usage

```
{'run_score_passages_cli': 'run the passage scorer CLI to score passages from a file using a config and write results', 'run_load_passages': 'run load_passages to load passages from a JSONL or DPR TSV file by path', 'run_score_passages': 'run score_passages to score a list of passages using a passage scorer config', 'run_score_passages_and_write': 'run score_passages_and_write_to_file to score passages and dump annotations to a JSONL output file', 'review_score_passages_cli': 'review the passage scorer CLI arguments for passages_to_score, output_path, path_to_config, and verbose'}
```

## File: facebookresearch_paq/paq/generation/passage_scorer/scorer.py

Prompts

```
['run the passage scorer CLI to score passages from a file using a config and write results', 'run load_passages to load passages from a JSONL or DPR TSV file by path', 'run score_passages to score a list of passages using a passage scorer config', 'run score_passages_and_write_to_file to score passages and dump annotations to a JSONL output file', 'review the passage scorer CLI arguments for passages_to_score, output_path, path_to_config, and verbose', 'load a passage scorer by name from config using load_passage_scorer', 'score passages with a fixed default score using DummyPassageScorer', 'score passages by looking up precomputed scores from a file using LookupPassageScorer', 'score passages in batches using a pretrained sequence classification model via LearntPassageScorer', 'tokenize a list of text passages into model-ready input tensors using LearntPassageScorer']
```

Usage

```
{'load_passage_scorer': 'load a passage scorer by name from config using load_passage_scorer', 'score_passages_dummy': 'score passages with a fixed default score using DummyPassageScorer', 'score_passages_lookup': 'score passages by looking up precomputed scores from a file using LookupPassageScorer', 'score_passages_learnt': 'score passages in batches using a pretrained sequence classification model via LearntPassageScorer', 'tokenize_texts': 'tokenize a list of text passages into model-ready input tensors using LearntPassageScorer'}
```

