# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/lxmert/test_modeling_lxmert.py

Prompts

```
['test the LxmertModel class with input_ids, visual_feats, and bounding_boxes to verify language_output, vision_output, and pooled_output shapes', 'test the LxmertForQuestionAnswering class with labels to verify question_answering_score output shape', 'test the LxmertForPreTraining class with masked_lm_labels, obj_labels, matched_label, and ans to verify prediction_logits output shape', 'test that LxmertModel, LxmertForPreTraining, and LxmertForQuestionAnswering return correct language_attentions, vision_attentions, and cross_encoder_attentions shapes', 'test that LxmertModel variants return correct language_hidden_states and vision_hidden_states shapes when output_hidden_states is enabled']
```

Usage

```
{'test_lxmert_model': 'test the LxmertModel class with input_ids, visual_feats, and bounding_boxes to verify language_output, vision_output, and pooled_output shapes', 'test_lxmert_question_answering': 'test the LxmertForQuestionAnswering class with labels to verify question_answering_score output shape', 'test_lxmert_pretraining': 'test the LxmertForPreTraining class with masked_lm_labels, obj_labels, matched_label, and ans to verify prediction_logits output shape', 'test_attention_outputs': 'test that LxmertModel, LxmertForPreTraining, and LxmertForQuestionAnswering return correct language_attentions, vision_attentions, and cross_encoder_attentions shapes', 'test_hidden_states_output': 'test that LxmertModel variants return correct language_hidden_states and vision_hidden_states shapes when output_hidden_states is enabled'}
```

