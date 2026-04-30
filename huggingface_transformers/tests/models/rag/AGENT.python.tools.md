# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/rag/test_modeling_rag.py

Prompts

```
['test the RagTestMixin check_model_with_retriever method to verify RAG model forward pass with retriever integration', 'test the RagTestMixin check_model_generate method to verify RAG model text generation with beam search', 'test the RagTestMixin check_model_without_retriever method to verify RAG model forward pass using pre-retrieved context input ids and doc scores', 'test the RagTestMixin check_model_with_end2end_retriever method to verify RAG model with DPR context encoder for training', 'test the RagModelIntegrationTests test_rag_sequence_inference method to verify RAG sequence model forward pass and loss computation with real pretrained models', 'test RagRetriever retrieve method to fetch top-k documents by inner product similarity', 'test RagRetriever save_pretrained and from_pretrained roundtrip for canonical HF index retriever', 'test CustomHFIndex retriever to retrieve documents using a custom in-memory FAISS index', 'test CustomHFIndex retriever to retrieve documents loaded from a disk-saved FAISS index', 'test RagRetriever call method returning context input ids and attention masks as torch tensors', 'test saving and loading RagTokenizer with DPR and BART tokenizer configs', 'test tokenizing question strings with the pretrained facebook rag-token-nq tokenizer', 'test tokenizing question strings with the pretrained facebook rag-sequence-nq tokenizer', 'create a RagTokenizer by combining a DPRQuestionEncoderTokenizer and a RobertaTokenizer', 'review the RagTokenizerTest class to understand how RAG tokenizer save load and pretrained tests work']
```

Usage

```
{'test_RagTestMixin_check_model_with_retriever': 'test the RagTestMixin check_model_with_retriever method to verify RAG model forward pass with retriever integration', 'test_RagTestMixin_check_model_generate': 'test the RagTestMixin check_model_generate method to verify RAG model text generation with beam search', 'test_RagTestMixin_check_model_without_retriever': 'test the RagTestMixin check_model_without_retriever method to verify RAG model forward pass using pre-retrieved context input ids and doc scores', 'test_RagTestMixin_check_model_with_end2end_retriever': 'test the RagTestMixin check_model_with_end2end_retriever method to verify RAG model with DPR context encoder for training', 'test_RagModelIntegrationTests_test_rag_sequence_inference': 'test the RagModelIntegrationTests test_rag_sequence_inference method to verify RAG sequence model forward pass and loss computation with real pretrained models'}
```

## File: huggingface_transformers/tests/models/rag/test_retrieval_rag.py

Prompts

```
['test the RagTestMixin check_model_with_retriever method to verify RAG model forward pass with retriever integration', 'test the RagTestMixin check_model_generate method to verify RAG model text generation with beam search', 'test the RagTestMixin check_model_without_retriever method to verify RAG model forward pass using pre-retrieved context input ids and doc scores', 'test the RagTestMixin check_model_with_end2end_retriever method to verify RAG model with DPR context encoder for training', 'test the RagModelIntegrationTests test_rag_sequence_inference method to verify RAG sequence model forward pass and loss computation with real pretrained models', 'test RagRetriever retrieve method to fetch top-k documents by inner product similarity', 'test RagRetriever save_pretrained and from_pretrained roundtrip for canonical HF index retriever', 'test CustomHFIndex retriever to retrieve documents using a custom in-memory FAISS index', 'test CustomHFIndex retriever to retrieve documents loaded from a disk-saved FAISS index', 'test RagRetriever call method returning context input ids and attention masks as torch tensors', 'test saving and loading RagTokenizer with DPR and BART tokenizer configs', 'test tokenizing question strings with the pretrained facebook rag-token-nq tokenizer', 'test tokenizing question strings with the pretrained facebook rag-sequence-nq tokenizer', 'create a RagTokenizer by combining a DPRQuestionEncoderTokenizer and a RobertaTokenizer', 'review the RagTokenizerTest class to understand how RAG tokenizer save load and pretrained tests work']
```

Usage

```
{'test_RagRetriever_retrieve': 'test RagRetriever retrieve method to fetch top-k documents by inner product similarity', 'test_RagRetriever_save_and_load': 'test RagRetriever save_pretrained and from_pretrained roundtrip for canonical HF index retriever', 'test_CustomHFIndex_retrieve': 'test CustomHFIndex retriever to retrieve documents using a custom in-memory FAISS index', 'test_CustomHFIndex_from_disk': 'test CustomHFIndex retriever to retrieve documents loaded from a disk-saved FAISS index', 'test_RagRetriever_call_with_tensors': 'test RagRetriever call method returning context input ids and attention masks as torch tensors'}
```

## File: huggingface_transformers/tests/models/rag/test_tokenization_rag.py

Prompts

```
['test the RagTestMixin check_model_with_retriever method to verify RAG model forward pass with retriever integration', 'test the RagTestMixin check_model_generate method to verify RAG model text generation with beam search', 'test the RagTestMixin check_model_without_retriever method to verify RAG model forward pass using pre-retrieved context input ids and doc scores', 'test the RagTestMixin check_model_with_end2end_retriever method to verify RAG model with DPR context encoder for training', 'test the RagModelIntegrationTests test_rag_sequence_inference method to verify RAG sequence model forward pass and loss computation with real pretrained models', 'test RagRetriever retrieve method to fetch top-k documents by inner product similarity', 'test RagRetriever save_pretrained and from_pretrained roundtrip for canonical HF index retriever', 'test CustomHFIndex retriever to retrieve documents using a custom in-memory FAISS index', 'test CustomHFIndex retriever to retrieve documents loaded from a disk-saved FAISS index', 'test RagRetriever call method returning context input ids and attention masks as torch tensors', 'test saving and loading RagTokenizer with DPR and BART tokenizer configs', 'test tokenizing question strings with the pretrained facebook rag-token-nq tokenizer', 'test tokenizing question strings with the pretrained facebook rag-sequence-nq tokenizer', 'create a RagTokenizer by combining a DPRQuestionEncoderTokenizer and a RobertaTokenizer', 'review the RagTokenizerTest class to understand how RAG tokenizer save load and pretrained tests work']
```

Usage

```
{'test_RagTokenizer_save_load': 'test saving and loading RagTokenizer with DPR and BART tokenizer configs', 'test_RagTokenizer_pretrained_token_nq': 'test tokenizing question strings with the pretrained facebook rag-token-nq tokenizer', 'test_RagTokenizer_pretrained_sequence_nq': 'test tokenizing question strings with the pretrained facebook rag-sequence-nq tokenizer', 'create_RagTokenizer_from_components': 'create a RagTokenizer by combining a DPRQuestionEncoderTokenizer and a RobertaTokenizer', 'review_RagTokenizerTest': 'review the RagTokenizerTest class to understand how RAG tokenizer save load and pretrained tests work'}
```

