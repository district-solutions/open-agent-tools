# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/models/qna/bert_squad_qa.py

Prompts

```
['build a BertSquadQAModel instance with a BERT encoder, MLP decoders, and SquadOutputLayer', 'create a BertSquadQAModel from a Config object and tensorizers using the from_config classmethod', 'run a forward pass on tokenized SQuAD inputs to get start and end logits', 'review the arrange_model_inputs method that extracts tokens, pad_mask, segment_labels, and positions', 'refactor the arrange_targets method to handle knowledge distillation logits alongside answer indices', 'build a DrQA model instance from a Config object and tensorizers dictionary using from_config', 'create a word embedding module from model config and tensorizers using create_embedding', 'run the DrQA forward pass with document tokens, question tokens, and their sequence masks', 'review the DrQA model architecture including RNN encoders, attention mechanisms, and output layers', 'refactor the DrQA model to enable knowledge distillation by setting is_kd to True']
```

Usage

```
{'build_bert_squad_qa_model': 'build a BertSquadQAModel instance with a BERT encoder, MLP decoders, and SquadOutputLayer', 'create_model_from_config': 'create a BertSquadQAModel from a Config object and tensorizers using the from_config classmethod', 'run_forward_pass': 'run a forward pass on tokenized SQuAD inputs to get start and end logits', 'review_arrange_model_inputs': 'review the arrange_model_inputs method that extracts tokens, pad_mask, segment_labels, and positions', 'refactor_arrange_targets': 'refactor the arrange_targets method to handle knowledge distillation logits alongside answer indices'}
```

## File: facebookresearch_pytext/pytext/models/qna/dr_qa.py

Prompts

```
['build a BertSquadQAModel instance with a BERT encoder, MLP decoders, and SquadOutputLayer', 'create a BertSquadQAModel from a Config object and tensorizers using the from_config classmethod', 'run a forward pass on tokenized SQuAD inputs to get start and end logits', 'review the arrange_model_inputs method that extracts tokens, pad_mask, segment_labels, and positions', 'refactor the arrange_targets method to handle knowledge distillation logits alongside answer indices', 'build a DrQA model instance from a Config object and tensorizers dictionary using from_config', 'create a word embedding module from model config and tensorizers using create_embedding', 'run the DrQA forward pass with document tokens, question tokens, and their sequence masks', 'review the DrQA model architecture including RNN encoders, attention mechanisms, and output layers', 'refactor the DrQA model to enable knowledge distillation by setting is_kd to True']
```

Usage

```
{'build_drqa_model_from_config': 'build a DrQA model instance from a Config object and tensorizers dictionary using from_config', 'create_drqa_embedding_module': 'create a word embedding module from model config and tensorizers using create_embedding', 'run_drqa_forward_pass': 'run the DrQA forward pass with document tokens, question tokens, and their sequence masks', 'review_drqa_model_architecture': 'review the DrQA model architecture including RNN encoders, attention mechanisms, and output layers', 'refactor_drqa_for_knowledge_distillation': 'refactor the DrQA model to enable knowledge distillation by setting is_kd to True'}
```

