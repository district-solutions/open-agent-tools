# Agent Python Tools

- repo: facebookresearch/paq
- repo_uri: https://github.com/facebookresearch/paq

## File: facebookresearch_paq/paq/generation/answer_extractor/extract_answers.py

Prompts

```
['run the CLI to extract answers from passages using a config file and write results to JSONL', 'extract answers from a list of passages using a loaded answer extractor and config', 'extract answers from passages and write the annotations directly to an output JSONL file', 'load passages from a file supporting both JSONL and DPR TSV formats with fallback', 'review the answer extraction module that loads extractors, processes passages, and writes results', 'use SpacyNERExtractor to extract named entities from a passage text with start and end offsets', 'use SpacyNERExtractor to extract named entities from a batch of passages using nlp pipe', 'use Span2DAnswerExtractor to predict answer spans with joint span probability from a passage', 'use Span2DAnswerExtractor to extract answer spans from a batch of passages with topk results', 'use load_answer_extractor to instantiate an answer extractor class from a config dictionary', 'build a BERT-based 2D span extractor model for question answering using AnswerSpanExtractor2DModel', 'run a forward pass through AnswerSpanExtractor2DModel with input_ids and attention_mask to get span logits', 'postprocess span2D model output to extract top N answer predictions from a passage', 'review the AnswerSpanExtractor2DModelOutput dataclass for loss, span_logits, span_masks, hidden_states, and attentions fields', 'test the BCEWithLogitsLoss computation in AnswerSpanExtractor2DModel using start and end position labels']
```

Usage

```
{'run_extract_answers_cli': 'run the CLI to extract answers from passages using a config file and write results to JSONL', 'extract_answers_from_passages': 'extract answers from a list of passages using a loaded answer extractor and config', 'extract_answers_and_write': 'extract answers from passages and write the annotations directly to an output JSONL file', 'load_passages_jsonl_or_tsv': 'load passages from a file supporting both JSONL and DPR TSV formats with fallback', 'review_extract_answers_module': 'review the answer extraction module that loads extractors, processes passages, and writes results'}
```

## File: facebookresearch_paq/paq/generation/answer_extractor/extractors.py

Prompts

```
['run the CLI to extract answers from passages using a config file and write results to JSONL', 'extract answers from a list of passages using a loaded answer extractor and config', 'extract answers from passages and write the annotations directly to an output JSONL file', 'load passages from a file supporting both JSONL and DPR TSV formats with fallback', 'review the answer extraction module that loads extractors, processes passages, and writes results', 'use SpacyNERExtractor to extract named entities from a passage text with start and end offsets', 'use SpacyNERExtractor to extract named entities from a batch of passages using nlp pipe', 'use Span2DAnswerExtractor to predict answer spans with joint span probability from a passage', 'use Span2DAnswerExtractor to extract answer spans from a batch of passages with topk results', 'use load_answer_extractor to instantiate an answer extractor class from a config dictionary', 'build a BERT-based 2D span extractor model for question answering using AnswerSpanExtractor2DModel', 'run a forward pass through AnswerSpanExtractor2DModel with input_ids and attention_mask to get span logits', 'postprocess span2D model output to extract top N answer predictions from a passage', 'review the AnswerSpanExtractor2DModelOutput dataclass for loss, span_logits, span_masks, hidden_states, and attentions fields', 'test the BCEWithLogitsLoss computation in AnswerSpanExtractor2DModel using start and end position labels']
```

Usage

```
{'extract_ner_entities_spacy': 'use SpacyNERExtractor to extract named entities from a passage text with start and end offsets', 'extract_answers_batch_spacy': 'use SpacyNERExtractor to extract named entities from a batch of passages using nlp pipe', 'extract_answer_spans_span2d': 'use Span2DAnswerExtractor to predict answer spans with joint span probability from a passage', 'extract_answers_batch_span2d': 'use Span2DAnswerExtractor to extract answer spans from a batch of passages with topk results', 'load_answer_extractor_by_config': 'use load_answer_extractor to instantiate an answer extractor class from a config dictionary'}
```

## File: facebookresearch_paq/paq/generation/answer_extractor/span2D_model.py

Prompts

```
['run the CLI to extract answers from passages using a config file and write results to JSONL', 'extract answers from a list of passages using a loaded answer extractor and config', 'extract answers from passages and write the annotations directly to an output JSONL file', 'load passages from a file supporting both JSONL and DPR TSV formats with fallback', 'review the answer extraction module that loads extractors, processes passages, and writes results', 'use SpacyNERExtractor to extract named entities from a passage text with start and end offsets', 'use SpacyNERExtractor to extract named entities from a batch of passages using nlp pipe', 'use Span2DAnswerExtractor to predict answer spans with joint span probability from a passage', 'use Span2DAnswerExtractor to extract answer spans from a batch of passages with topk results', 'use load_answer_extractor to instantiate an answer extractor class from a config dictionary', 'build a BERT-based 2D span extractor model for question answering using AnswerSpanExtractor2DModel', 'run a forward pass through AnswerSpanExtractor2DModel with input_ids and attention_mask to get span logits', 'postprocess span2D model output to extract top N answer predictions from a passage', 'review the AnswerSpanExtractor2DModelOutput dataclass for loss, span_logits, span_masks, hidden_states, and attentions fields', 'test the BCEWithLogitsLoss computation in AnswerSpanExtractor2DModel using start and end position labels']
```

Usage

```
{'build_2D_span_extractor_model': 'build a BERT-based 2D span extractor model for question answering using AnswerSpanExtractor2DModel', 'run_forward_pass': 'run a forward pass through AnswerSpanExtractor2DModel with input_ids and attention_mask to get span logits', 'postprocess_span2d_predictions': 'postprocess span2D model output to extract top N answer predictions from a passage', 'review_model_output_dataclass': 'review the AnswerSpanExtractor2DModelOutput dataclass for loss, span_logits, span_masks, hidden_states, and attentions fields', 'test_span2d_loss_computation': 'test the BCEWithLogitsLoss computation in AnswerSpanExtractor2DModel using start and end position labels'}
```

