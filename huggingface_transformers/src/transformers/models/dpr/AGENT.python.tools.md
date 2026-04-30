# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/dpr/convert_dpr_original_checkpoint_to_pytorch.py

Prompts

```
["convert a DPR original checkpoint from Facebook's repo to HuggingFace PyTorch format", 'load a DPR context encoder from a saved checkpoint file and convert to HuggingFace format', 'load a DPR question encoder from a saved checkpoint file and convert to HuggingFace format', 'load a DPR reader from a saved checkpoint file and convert to HuggingFace format', 'run the DPR checkpoint conversion CLI with type, source, and destination arguments', 'create a DPRContextEncoder model to generate context embeddings for open domain question answering', 'create a DPRQuestionEncoder model to generate question embeddings for open domain question answering', 'create a DPRReader model to predict answer spans and passage relevance from questions and passages', 'build a DPREncoder wrapping BertModel with optional projection layer for embedding generation', 'build a DPRSpanPredictor with DPREncoder and QA heads for start, end, and relevance logits', 'build a DPRContextEncoder tokenizer from a pretrained model for encoding passages', 'build a DPRQuestionEncoder tokenizer from a pretrained model for encoding questions', 'build a DPRReaderTokenizer that encodes questions, titles, and texts for extractive QA', 'run decode_best_spans on DPRReaderTokenizer to extract the best answer spans from model logits', 'create a DPRReaderOutput namedtuple with start_logits, end_logits, and relevance_logits', 'create a fast DPR context encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'create a fast DPR question encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'build a fast DPR reader tokenizer that encodes questions, titles, and texts combined into token ids for extractive QA', 'test the DPRReaderTokenizerFast decode_best_spans method to get span predictions sorted by relevance and span score', 'review the DPRSpanPrediction namedtuple containing span_score, relevance_score, doc_id, start_index, end_index, and text fields']
```

Usage

```
{'convert_dpr_checkpoint': "convert a DPR original checkpoint from Facebook's repo to HuggingFace PyTorch format", 'load_dpr_context_encoder': 'load a DPR context encoder from a saved checkpoint file and convert to HuggingFace format', 'load_dpr_question_encoder': 'load a DPR question encoder from a saved checkpoint file and convert to HuggingFace format', 'load_dpr_reader': 'load a DPR reader from a saved checkpoint file and convert to HuggingFace format', 'run_dpr_conversion_cli': 'run the DPR checkpoint conversion CLI with type, source, and destination arguments'}
```

## File: huggingface_transformers/src/transformers/models/dpr/modeling_dpr.py

Prompts

```
["convert a DPR original checkpoint from Facebook's repo to HuggingFace PyTorch format", 'load a DPR context encoder from a saved checkpoint file and convert to HuggingFace format', 'load a DPR question encoder from a saved checkpoint file and convert to HuggingFace format', 'load a DPR reader from a saved checkpoint file and convert to HuggingFace format', 'run the DPR checkpoint conversion CLI with type, source, and destination arguments', 'create a DPRContextEncoder model to generate context embeddings for open domain question answering', 'create a DPRQuestionEncoder model to generate question embeddings for open domain question answering', 'create a DPRReader model to predict answer spans and passage relevance from questions and passages', 'build a DPREncoder wrapping BertModel with optional projection layer for embedding generation', 'build a DPRSpanPredictor with DPREncoder and QA heads for start, end, and relevance logits', 'build a DPRContextEncoder tokenizer from a pretrained model for encoding passages', 'build a DPRQuestionEncoder tokenizer from a pretrained model for encoding questions', 'build a DPRReaderTokenizer that encodes questions, titles, and texts for extractive QA', 'run decode_best_spans on DPRReaderTokenizer to extract the best answer spans from model logits', 'create a DPRReaderOutput namedtuple with start_logits, end_logits, and relevance_logits', 'create a fast DPR context encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'create a fast DPR question encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'build a fast DPR reader tokenizer that encodes questions, titles, and texts combined into token ids for extractive QA', 'test the DPRReaderTokenizerFast decode_best_spans method to get span predictions sorted by relevance and span score', 'review the DPRSpanPrediction namedtuple containing span_score, relevance_score, doc_id, start_index, end_index, and text fields']
```

Usage

```
{'create_DPRContextEncoder': 'create a DPRContextEncoder model to generate context embeddings for open domain question answering', 'create_DPRQuestionEncoder': 'create a DPRQuestionEncoder model to generate question embeddings for open domain question answering', 'create_DPRReader': 'create a DPRReader model to predict answer spans and passage relevance from questions and passages', 'build_DPREncoder': 'build a DPREncoder wrapping BertModel with optional projection layer for embedding generation', 'build_DPRSpanPredictor': 'build a DPRSpanPredictor with DPREncoder and QA heads for start, end, and relevance logits'}
```

## File: huggingface_transformers/src/transformers/models/dpr/tokenization_dpr.py

Prompts

```
["convert a DPR original checkpoint from Facebook's repo to HuggingFace PyTorch format", 'load a DPR context encoder from a saved checkpoint file and convert to HuggingFace format', 'load a DPR question encoder from a saved checkpoint file and convert to HuggingFace format', 'load a DPR reader from a saved checkpoint file and convert to HuggingFace format', 'run the DPR checkpoint conversion CLI with type, source, and destination arguments', 'create a DPRContextEncoder model to generate context embeddings for open domain question answering', 'create a DPRQuestionEncoder model to generate question embeddings for open domain question answering', 'create a DPRReader model to predict answer spans and passage relevance from questions and passages', 'build a DPREncoder wrapping BertModel with optional projection layer for embedding generation', 'build a DPRSpanPredictor with DPREncoder and QA heads for start, end, and relevance logits', 'build a DPRContextEncoder tokenizer from a pretrained model for encoding passages', 'build a DPRQuestionEncoder tokenizer from a pretrained model for encoding questions', 'build a DPRReaderTokenizer that encodes questions, titles, and texts for extractive QA', 'run decode_best_spans on DPRReaderTokenizer to extract the best answer spans from model logits', 'create a DPRReaderOutput namedtuple with start_logits, end_logits, and relevance_logits', 'create a fast DPR context encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'create a fast DPR question encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'build a fast DPR reader tokenizer that encodes questions, titles, and texts combined into token ids for extractive QA', 'test the DPRReaderTokenizerFast decode_best_spans method to get span predictions sorted by relevance and span score', 'review the DPRSpanPrediction namedtuple containing span_score, relevance_score, doc_id, start_index, end_index, and text fields']
```

Usage

```
{'build_dpr_context_tokenizer': 'build a DPRContextEncoder tokenizer from a pretrained model for encoding passages', 'build_dpr_question_tokenizer': 'build a DPRQuestionEncoder tokenizer from a pretrained model for encoding questions', 'build_dpr_reader_tokenizer': 'build a DPRReaderTokenizer that encodes questions, titles, and texts for extractive QA', 'run_decode_best_spans': 'run decode_best_spans on DPRReaderTokenizer to extract the best answer spans from model logits', 'create_dpr_reader_output': 'create a DPRReaderOutput namedtuple with start_logits, end_logits, and relevance_logits'}
```

## File: huggingface_transformers/src/transformers/models/dpr/tokenization_dpr_fast.py

Prompts

```
["convert a DPR original checkpoint from Facebook's repo to HuggingFace PyTorch format", 'load a DPR context encoder from a saved checkpoint file and convert to HuggingFace format', 'load a DPR question encoder from a saved checkpoint file and convert to HuggingFace format', 'load a DPR reader from a saved checkpoint file and convert to HuggingFace format', 'run the DPR checkpoint conversion CLI with type, source, and destination arguments', 'create a DPRContextEncoder model to generate context embeddings for open domain question answering', 'create a DPRQuestionEncoder model to generate question embeddings for open domain question answering', 'create a DPRReader model to predict answer spans and passage relevance from questions and passages', 'build a DPREncoder wrapping BertModel with optional projection layer for embedding generation', 'build a DPRSpanPredictor with DPREncoder and QA heads for start, end, and relevance logits', 'build a DPRContextEncoder tokenizer from a pretrained model for encoding passages', 'build a DPRQuestionEncoder tokenizer from a pretrained model for encoding questions', 'build a DPRReaderTokenizer that encodes questions, titles, and texts for extractive QA', 'run decode_best_spans on DPRReaderTokenizer to extract the best answer spans from model logits', 'create a DPRReaderOutput namedtuple with start_logits, end_logits, and relevance_logits', 'create a fast DPR context encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'create a fast DPR question encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'build a fast DPR reader tokenizer that encodes questions, titles, and texts combined into token ids for extractive QA', 'test the DPRReaderTokenizerFast decode_best_spans method to get span predictions sorted by relevance and span score', 'review the DPRSpanPrediction namedtuple containing span_score, relevance_score, doc_id, start_index, end_index, and text fields']
```

Usage

```
{'create_DPRContextEncoderTokenizerFast': 'create a fast DPR context encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'create_DPRQuestionEncoderTokenizerFast': 'create a fast DPR question encoder tokenizer backed by HuggingFace tokenizers library for punctuation splitting and wordpiece', 'build_DPRReaderTokenizerFast': 'build a fast DPR reader tokenizer that encodes questions, titles, and texts combined into token ids for extractive QA', 'test_decode_best_spans': 'test the DPRReaderTokenizerFast decode_best_spans method to get span predictions sorted by relevance and span score', 'review_DPRSpanPrediction': 'review the DPRSpanPrediction namedtuple containing span_score, relevance_score, doc_id, start_index, end_index, and text fields'}
```

