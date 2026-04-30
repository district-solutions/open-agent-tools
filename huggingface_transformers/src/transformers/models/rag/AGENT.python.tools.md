# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/rag/configuration_rag.py

Prompts

```
['build a RagConfig instance from question encoder and generator model configurations', 'create a RagConfig by passing question_encoder and generator sub-configurations as dicts', 'configure RAG retrieval settings like n_docs, dataset, index_name, and dataset_split', 'test that RagConfig raises ValueError when question_encoder or generator is missing', 'review RagConfig loss-related options including reduce_loss, label_smoothing, and do_marginalize', 'create a RAG model from pretrained question encoder and generator using from_pretrained_question_encoder_generator', 'build a RAG-sequence model that marginalizes over retrieved documents for text generation', 'run RAG-token generation with marginalization over document scores for autoregressive decoding', 'test the RAG forward pass with question encoding, document retrieval, and generator decoding', 'refactor the RAG negative log-likelihood loss computation with label smoothing and BOS exclusion', 'create a RagRetriever from a pretrained model with the default wiki_dpr dataset and compressed index', 'create a RagRetriever using a custom indexed dataset loaded from disk paths for passages and faiss index', 'build a RagRetriever with a legacy Facebook DPR index loaded from a remote or local path', 'test the RagRetriever retrieve method to fetch top documents given question hidden states and n_docs', 'review the RagRetriever __call__ method that retrieves docs, postprocesses them, and returns tokenized context inputs', 'load a RagTokenizer from pretrained model name or path with optional config', "save a RagTokenizer's question encoder and generator tokenizers to a directory", 'tokenize input text using the question encoder tokenizer in input mode', 'decode generated token ids to text strings using the generator tokenizer', 'switch a RagTokenizer between question encoder input mode and generator target mode']
```

Usage

```
{'build_rag_config': 'build a RagConfig instance from question encoder and generator model configurations', 'create_rag_config_directly': 'create a RagConfig by passing question_encoder and generator sub-configurations as dicts', 'configure_rag_retrieval': 'configure RAG retrieval settings like n_docs, dataset, index_name, and dataset_split', 'test_rag_config_validation': 'test that RagConfig raises ValueError when question_encoder or generator is missing', 'review_rag_config_loss_options': 'review RagConfig loss-related options including reduce_loss, label_smoothing, and do_marginalize'}
```

## File: huggingface_transformers/src/transformers/models/rag/modeling_rag.py

Prompts

```
['build a RagConfig instance from question encoder and generator model configurations', 'create a RagConfig by passing question_encoder and generator sub-configurations as dicts', 'configure RAG retrieval settings like n_docs, dataset, index_name, and dataset_split', 'test that RagConfig raises ValueError when question_encoder or generator is missing', 'review RagConfig loss-related options including reduce_loss, label_smoothing, and do_marginalize', 'create a RAG model from pretrained question encoder and generator using from_pretrained_question_encoder_generator', 'build a RAG-sequence model that marginalizes over retrieved documents for text generation', 'run RAG-token generation with marginalization over document scores for autoregressive decoding', 'test the RAG forward pass with question encoding, document retrieval, and generator decoding', 'refactor the RAG negative log-likelihood loss computation with label smoothing and BOS exclusion', 'create a RagRetriever from a pretrained model with the default wiki_dpr dataset and compressed index', 'create a RagRetriever using a custom indexed dataset loaded from disk paths for passages and faiss index', 'build a RagRetriever with a legacy Facebook DPR index loaded from a remote or local path', 'test the RagRetriever retrieve method to fetch top documents given question hidden states and n_docs', 'review the RagRetriever __call__ method that retrieves docs, postprocesses them, and returns tokenized context inputs', 'load a RagTokenizer from pretrained model name or path with optional config', "save a RagTokenizer's question encoder and generator tokenizers to a directory", 'tokenize input text using the question encoder tokenizer in input mode', 'decode generated token ids to text strings using the generator tokenizer', 'switch a RagTokenizer between question encoder input mode and generator target mode']
```

Usage

```
{'create_model_rag_from_pretrained': 'create a RAG model from pretrained question encoder and generator using from_pretrained_question_encoder_generator', 'build_rag_sequence_generation': 'build a RAG-sequence model that marginalizes over retrieved documents for text generation', 'run_rag_token_generation': 'run RAG-token generation with marginalization over document scores for autoregressive decoding', 'test_rag_forward_pass': 'test the RAG forward pass with question encoding, document retrieval, and generator decoding', 'refactor_rag_nll_loss': 'refactor the RAG negative log-likelihood loss computation with label smoothing and BOS exclusion'}
```

## File: huggingface_transformers/src/transformers/models/rag/retrieval_rag.py

Prompts

```
['build a RagConfig instance from question encoder and generator model configurations', 'create a RagConfig by passing question_encoder and generator sub-configurations as dicts', 'configure RAG retrieval settings like n_docs, dataset, index_name, and dataset_split', 'test that RagConfig raises ValueError when question_encoder or generator is missing', 'review RagConfig loss-related options including reduce_loss, label_smoothing, and do_marginalize', 'create a RAG model from pretrained question encoder and generator using from_pretrained_question_encoder_generator', 'build a RAG-sequence model that marginalizes over retrieved documents for text generation', 'run RAG-token generation with marginalization over document scores for autoregressive decoding', 'test the RAG forward pass with question encoding, document retrieval, and generator decoding', 'refactor the RAG negative log-likelihood loss computation with label smoothing and BOS exclusion', 'create a RagRetriever from a pretrained model with the default wiki_dpr dataset and compressed index', 'create a RagRetriever using a custom indexed dataset loaded from disk paths for passages and faiss index', 'build a RagRetriever with a legacy Facebook DPR index loaded from a remote or local path', 'test the RagRetriever retrieve method to fetch top documents given question hidden states and n_docs', 'review the RagRetriever __call__ method that retrieves docs, postprocesses them, and returns tokenized context inputs', 'load a RagTokenizer from pretrained model name or path with optional config', "save a RagTokenizer's question encoder and generator tokenizers to a directory", 'tokenize input text using the question encoder tokenizer in input mode', 'decode generated token ids to text strings using the generator tokenizer', 'switch a RagTokenizer between question encoder input mode and generator target mode']
```

Usage

```
{'create_retriever_load_pretrained': 'create a RagRetriever from a pretrained model with the default wiki_dpr dataset and compressed index', 'create_retriever_custom_index': 'create a RagRetriever using a custom indexed dataset loaded from disk paths for passages and faiss index', 'build_retriever_with_legacy_index': 'build a RagRetriever with a legacy Facebook DPR index loaded from a remote or local path', 'test_retriever_retrieve_docs': 'test the RagRetriever retrieve method to fetch top documents given question hidden states and n_docs', 'review_rag_retriever_call': 'review the RagRetriever __call__ method that retrieves docs, postprocesses them, and returns tokenized context inputs'}
```

## File: huggingface_transformers/src/transformers/models/rag/tokenization_rag.py

Prompts

```
['build a RagConfig instance from question encoder and generator model configurations', 'create a RagConfig by passing question_encoder and generator sub-configurations as dicts', 'configure RAG retrieval settings like n_docs, dataset, index_name, and dataset_split', 'test that RagConfig raises ValueError when question_encoder or generator is missing', 'review RagConfig loss-related options including reduce_loss, label_smoothing, and do_marginalize', 'create a RAG model from pretrained question encoder and generator using from_pretrained_question_encoder_generator', 'build a RAG-sequence model that marginalizes over retrieved documents for text generation', 'run RAG-token generation with marginalization over document scores for autoregressive decoding', 'test the RAG forward pass with question encoding, document retrieval, and generator decoding', 'refactor the RAG negative log-likelihood loss computation with label smoothing and BOS exclusion', 'create a RagRetriever from a pretrained model with the default wiki_dpr dataset and compressed index', 'create a RagRetriever using a custom indexed dataset loaded from disk paths for passages and faiss index', 'build a RagRetriever with a legacy Facebook DPR index loaded from a remote or local path', 'test the RagRetriever retrieve method to fetch top documents given question hidden states and n_docs', 'review the RagRetriever __call__ method that retrieves docs, postprocesses them, and returns tokenized context inputs', 'load a RagTokenizer from pretrained model name or path with optional config', "save a RagTokenizer's question encoder and generator tokenizers to a directory", 'tokenize input text using the question encoder tokenizer in input mode', 'decode generated token ids to text strings using the generator tokenizer', 'switch a RagTokenizer between question encoder input mode and generator target mode']
```

Usage

```
{'load_ragtokenizer_from_pretrained': 'load a RagTokenizer from pretrained model name or path with optional config', 'save_ragtokenizer_pretrained': "save a RagTokenizer's question encoder and generator tokenizers to a directory", 'tokenize_input_with_ragtokenizer': 'tokenize input text using the question encoder tokenizer in input mode', 'decode_output_with_ragtokenizer': 'decode generated token ids to text strings using the generator tokenizer', 'switch_ragtokenizer_modes': 'switch a RagTokenizer between question encoder input mode and generator target mode'}
```

