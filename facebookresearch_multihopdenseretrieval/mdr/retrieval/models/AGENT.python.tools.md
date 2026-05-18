# Agent Python Tools

- repo: facebookresearch/multihopdenseretrieval
- repo_uri: https://github.com/facebookresearch/multihop_dense_retrieval

## File: facebookresearch_multihopdenseretrieval/mdr/retrieval/models/hop1_retriever.py

Prompts

```
['build a one-hop dense retriever using two BERT models for query and context encoding', 'create a forward pass that encodes queries, contexts, and negative contexts with BERT', 'test the Retriever1hop model by passing a batch with query and context token IDs', 'review the Retriever1hop initialization that loads two separate BERT models for query and context', 'summarize the forward method that extracts CLS tokens and sentence-level representations from BERT outputs', 'build a RoBERTa-based retriever model that encodes queries and contexts into embedding vectors', 'create a function that encodes input sequences using RoBERTa and projects CLS representations', 'build a momentum-based dual-encoder retriever with query and key encoders for contrastive learning', 'create a momentum update mechanism that synchronizes key encoder weights from the query encoder', 'create a memory bank queue that manages context embeddings with circular buffer dequeue and enqueue', 'build a single hop BERT retriever model with shared or separate query and context encoders', 'build a single hop RoBERTa retriever model with a shared encoder and projection layer', 'build a momentum retriever with a memory bank queue for storing previous context embeddings', 'build a context encoder supporting layerwise or tokenwise multi-vector embedding schemes', 'build a RoBERTa context encoder with a linear projection and layer normalization for corpus encoding', 'build a UnifiedRetriever model that encodes questions and contexts with stop prediction for multi-hop retrieval', 'build a RobertaNQRetriever model that encodes Natural Questions contexts and queries using RoBERTa', 'build a BertNQRetriever model that encodes Natural Questions contexts and queries using BERT', 'build a BertNQMomentumRetriever with momentum-updated key encoder and embedding queue for contrastive learning', 'review the UnifiedRetriever encode_qsp method that returns question vectors and stop logits']
```

Usage

```
{'build_Retriever1hop': 'build a one-hop dense retriever using two BERT models for query and context encoding', 'create_Retriever1hop_forward': 'create a forward pass that encodes queries, contexts, and negative contexts with BERT', 'test_Retriever1hop': 'test the Retriever1hop model by passing a batch with query and context token IDs', 'review_Retriever1hop_init': 'review the Retriever1hop initialization that loads two separate BERT models for query and context', 'summarize_Retriever1hop_forward': 'summarize the forward method that extracts CLS tokens and sentence-level representations from BERT outputs'}
```

## File: facebookresearch_multihopdenseretrieval/mdr/retrieval/models/mhop_retriever.py

Prompts

```
['build a one-hop dense retriever using two BERT models for query and context encoding', 'create a forward pass that encodes queries, contexts, and negative contexts with BERT', 'test the Retriever1hop model by passing a batch with query and context token IDs', 'review the Retriever1hop initialization that loads two separate BERT models for query and context', 'summarize the forward method that extracts CLS tokens and sentence-level representations from BERT outputs', 'build a RoBERTa-based retriever model that encodes queries and contexts into embedding vectors', 'create a function that encodes input sequences using RoBERTa and projects CLS representations', 'build a momentum-based dual-encoder retriever with query and key encoders for contrastive learning', 'create a momentum update mechanism that synchronizes key encoder weights from the query encoder', 'create a memory bank queue that manages context embeddings with circular buffer dequeue and enqueue', 'build a single hop BERT retriever model with shared or separate query and context encoders', 'build a single hop RoBERTa retriever model with a shared encoder and projection layer', 'build a momentum retriever with a memory bank queue for storing previous context embeddings', 'build a context encoder supporting layerwise or tokenwise multi-vector embedding schemes', 'build a RoBERTa context encoder with a linear projection and layer normalization for corpus encoding', 'build a UnifiedRetriever model that encodes questions and contexts with stop prediction for multi-hop retrieval', 'build a RobertaNQRetriever model that encodes Natural Questions contexts and queries using RoBERTa', 'build a BertNQRetriever model that encodes Natural Questions contexts and queries using BERT', 'build a BertNQMomentumRetriever with momentum-updated key encoder and embedding queue for contrastive learning', 'review the UnifiedRetriever encode_qsp method that returns question vectors and stop logits']
```

Usage

```
{'build_RobertaRetriever': 'build a RoBERTa-based retriever model that encodes queries and contexts into embedding vectors', 'create_RobertaRetriever_encode_seq': 'create a function that encodes input sequences using RoBERTa and projects CLS representations', 'build_RobertaMomentumRetriever': 'build a momentum-based dual-encoder retriever with query and key encoders for contrastive learning', 'create_RobertaMomentumRetriever_momentum_update': 'create a momentum update mechanism that synchronizes key encoder weights from the query encoder', 'create_RobertaMomentumRetriever_dequeue_enqueue': 'create a memory bank queue that manages context embeddings with circular buffer dequeue and enqueue'}
```

## File: facebookresearch_multihopdenseretrieval/mdr/retrieval/models/retriever.py

Prompts

```
['build a one-hop dense retriever using two BERT models for query and context encoding', 'create a forward pass that encodes queries, contexts, and negative contexts with BERT', 'test the Retriever1hop model by passing a batch with query and context token IDs', 'review the Retriever1hop initialization that loads two separate BERT models for query and context', 'summarize the forward method that extracts CLS tokens and sentence-level representations from BERT outputs', 'build a RoBERTa-based retriever model that encodes queries and contexts into embedding vectors', 'create a function that encodes input sequences using RoBERTa and projects CLS representations', 'build a momentum-based dual-encoder retriever with query and key encoders for contrastive learning', 'create a momentum update mechanism that synchronizes key encoder weights from the query encoder', 'create a memory bank queue that manages context embeddings with circular buffer dequeue and enqueue', 'build a single hop BERT retriever model with shared or separate query and context encoders', 'build a single hop RoBERTa retriever model with a shared encoder and projection layer', 'build a momentum retriever with a memory bank queue for storing previous context embeddings', 'build a context encoder supporting layerwise or tokenwise multi-vector embedding schemes', 'build a RoBERTa context encoder with a linear projection and layer normalization for corpus encoding', 'build a UnifiedRetriever model that encodes questions and contexts with stop prediction for multi-hop retrieval', 'build a RobertaNQRetriever model that encodes Natural Questions contexts and queries using RoBERTa', 'build a BertNQRetriever model that encodes Natural Questions contexts and queries using BERT', 'build a BertNQMomentumRetriever with momentum-updated key encoder and embedding queue for contrastive learning', 'review the UnifiedRetriever encode_qsp method that returns question vectors and stop logits']
```

Usage

```
{'build_BertRetrieverSingle': 'build a single hop BERT retriever model with shared or separate query and context encoders', 'build_RobertaRetrieverSingle': 'build a single hop RoBERTa retriever model with a shared encoder and projection layer', 'build_MomentumRetriever': 'build a momentum retriever with a memory bank queue for storing previous context embeddings', 'build_CtxEncoder': 'build a context encoder supporting layerwise or tokenwise multi-vector embedding schemes', 'build_RobertaCtxEncoder': 'build a RoBERTa context encoder with a linear projection and layer normalization for corpus encoding'}
```

## File: facebookresearch_multihopdenseretrieval/mdr/retrieval/models/unified_retriever.py

Prompts

```
['build a one-hop dense retriever using two BERT models for query and context encoding', 'create a forward pass that encodes queries, contexts, and negative contexts with BERT', 'test the Retriever1hop model by passing a batch with query and context token IDs', 'review the Retriever1hop initialization that loads two separate BERT models for query and context', 'summarize the forward method that extracts CLS tokens and sentence-level representations from BERT outputs', 'build a RoBERTa-based retriever model that encodes queries and contexts into embedding vectors', 'create a function that encodes input sequences using RoBERTa and projects CLS representations', 'build a momentum-based dual-encoder retriever with query and key encoders for contrastive learning', 'create a momentum update mechanism that synchronizes key encoder weights from the query encoder', 'create a memory bank queue that manages context embeddings with circular buffer dequeue and enqueue', 'build a single hop BERT retriever model with shared or separate query and context encoders', 'build a single hop RoBERTa retriever model with a shared encoder and projection layer', 'build a momentum retriever with a memory bank queue for storing previous context embeddings', 'build a context encoder supporting layerwise or tokenwise multi-vector embedding schemes', 'build a RoBERTa context encoder with a linear projection and layer normalization for corpus encoding', 'build a UnifiedRetriever model that encodes questions and contexts with stop prediction for multi-hop retrieval', 'build a RobertaNQRetriever model that encodes Natural Questions contexts and queries using RoBERTa', 'build a BertNQRetriever model that encodes Natural Questions contexts and queries using BERT', 'build a BertNQMomentumRetriever with momentum-updated key encoder and embedding queue for contrastive learning', 'review the UnifiedRetriever encode_qsp method that returns question vectors and stop logits']
```

Usage

```
{'build_unified_retriever': 'build a UnifiedRetriever model that encodes questions and contexts with stop prediction for multi-hop retrieval', 'build_roberta_nq_retriever': 'build a RobertaNQRetriever model that encodes Natural Questions contexts and queries using RoBERTa', 'build_bert_nq_retriever': 'build a BertNQRetriever model that encodes Natural Questions contexts and queries using BERT', 'build_bert_nq_momentum_retriever': 'build a BertNQMomentumRetriever with momentum-updated key encoder and embedding queue for contrastive learning', 'review_unified_retriever_encode_qsp': 'review the UnifiedRetriever encode_qsp method that returns question vectors and stop logits'}
```

