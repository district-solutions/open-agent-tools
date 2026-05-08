# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/wizard_of_wikipedia/generator/agents.py

Prompts

```
['build an EndToEndAgent with knowledge attention loss and configurable knowledge truncation', 'build a TwoStageAgent that combines topic, knowledge, and dialogue history into text vectors', 'review the EndToEndAgent compute_loss method that combines token loss with knowledge attention loss', 'review the EndToEndAgent batchify method that parses knowledge passages and creates padded knowledge tensors', 'refactor the EndToEndAgent _parse_knowledge method to ensure correct knowledge is always at index zero', 'build an EndToEndModel with a custom optimizer and dictionary for dialogue generation', 'create sentence embeddings from transformer outputs using masked average pooling with sqrt normalization', 'review the ContextKnowledgeEncoder forward pass that encodes context and knowledge tokens with attention', 'refactor the ContextKnowledgeDecoder to strip the knowledge selection mask from encoder state before decoding', 'test the EndToEndModel reorder_encoder_states method to correctly reindex encoder outputs by batch indices']
```

Usage

```
{'build_EndToEndAgent': 'build an EndToEndAgent with knowledge attention loss and configurable knowledge truncation', 'build_TwoStageAgent': 'build a TwoStageAgent that combines topic, knowledge, and dialogue history into text vectors', 'review_EndToEndAgent_compute_loss': 'review the EndToEndAgent compute_loss method that combines token loss with knowledge attention loss', 'review_EndToEndAgent_batchify': 'review the EndToEndAgent batchify method that parses knowledge passages and creates padded knowledge tensors', 'refactor_EndToEndAgent_parse_knowledge': 'refactor the EndToEndAgent _parse_knowledge method to ensure correct knowledge is always at index zero'}
```

## File: facebookresearch_parlai/projects/wizard_of_wikipedia/generator/modules.py

Prompts

```
['build an EndToEndAgent with knowledge attention loss and configurable knowledge truncation', 'build a TwoStageAgent that combines topic, knowledge, and dialogue history into text vectors', 'review the EndToEndAgent compute_loss method that combines token loss with knowledge attention loss', 'review the EndToEndAgent batchify method that parses knowledge passages and creates padded knowledge tensors', 'refactor the EndToEndAgent _parse_knowledge method to ensure correct knowledge is always at index zero', 'build an EndToEndModel with a custom optimizer and dictionary for dialogue generation', 'create sentence embeddings from transformer outputs using masked average pooling with sqrt normalization', 'review the ContextKnowledgeEncoder forward pass that encodes context and knowledge tokens with attention', 'refactor the ContextKnowledgeDecoder to strip the knowledge selection mask from encoder state before decoding', 'test the EndToEndModel reorder_encoder_states method to correctly reindex encoder outputs by batch indices']
```

Usage

```
{'build_end_to_end_model': 'build an EndToEndModel with a custom optimizer and dictionary for dialogue generation', 'create_universal_sentence_embedding': 'create sentence embeddings from transformer outputs using masked average pooling with sqrt normalization', 'review_context_knowledge_encoder': 'review the ContextKnowledgeEncoder forward pass that encodes context and knowledge tokens with attention', 'refactor_context_knowledge_decoder': 'refactor the ContextKnowledgeDecoder to strip the knowledge selection mask from encoder state before decoding', 'test_reorder_encoder_states': 'test the EndToEndModel reorder_encoder_states method to correctly reindex encoder outputs by batch indices'}
```

