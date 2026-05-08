# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/style_gen/classifier.py

Prompts

```
['build a ClassifierAgent that uses a pretrained generator model with a classifier head for style classification', 'train the ClassifierAgent on a batch of examples with label tensors and cross entropy loss', 'evaluate the ClassifierAgent on a batch and return predictions with optional class probabilities', 'freeze the encoder and decoder weights of the ClassifierAgent so only the classifier head is trained', 'build a CrossEntropyLoss criterion with class weights for the ClassifierAgent supporting FP16 safe mode', 'build a ClassifierOnGeneratorModel with a classifier head on top of a pretrained transformer generator', 'create a StyleAgentMixin to conditionally insert style tokens into agent conversation histories', 'build a TransformerDecoderWithEmbeds decoder that accepts pre-embedded token inputs alongside standard inputs', 'review the ClassificationMixin to add per-class precision, recall, and weighted F1 metrics to non-classifier models', 'test the ClassifierOnGeneratorModel forward method to get per-class logits from encoded text vectors', 'run the StyleGenAgent to generate style-controlled text using a transformer model', 'review the StyleGenAgent class that combines StyleAgentMixin with TransformerGeneratorAgent', 'build command-line arguments for the StyleGenAgent using add_cmdline_args method', 'test the StyleGenAgent style-controlled generation with the use_style_frac parameter', 'refactor the StyleGenAgent to customize style injection via the StyleAgentMixin']
```

Usage

```
{'build_classifier_agent': 'build a ClassifierAgent that uses a pretrained generator model with a classifier head for style classification', 'train_classifier_agent': 'train the ClassifierAgent on a batch of examples with label tensors and cross entropy loss', 'evaluate_classifier_agent': 'evaluate the ClassifierAgent on a batch and return predictions with optional class probabilities', 'freeze_encoder_decoder_weights': 'freeze the encoder and decoder weights of the ClassifierAgent so only the classifier head is trained', 'build_criterion_with_class_weights': 'build a CrossEntropyLoss criterion with class weights for the ClassifierAgent supporting FP16 safe mode'}
```

## File: facebookresearch_parlai/projects/style_gen/modules.py

Prompts

```
['build a ClassifierAgent that uses a pretrained generator model with a classifier head for style classification', 'train the ClassifierAgent on a batch of examples with label tensors and cross entropy loss', 'evaluate the ClassifierAgent on a batch and return predictions with optional class probabilities', 'freeze the encoder and decoder weights of the ClassifierAgent so only the classifier head is trained', 'build a CrossEntropyLoss criterion with class weights for the ClassifierAgent supporting FP16 safe mode', 'build a ClassifierOnGeneratorModel with a classifier head on top of a pretrained transformer generator', 'create a StyleAgentMixin to conditionally insert style tokens into agent conversation histories', 'build a TransformerDecoderWithEmbeds decoder that accepts pre-embedded token inputs alongside standard inputs', 'review the ClassificationMixin to add per-class precision, recall, and weighted F1 metrics to non-classifier models', 'test the ClassifierOnGeneratorModel forward method to get per-class logits from encoded text vectors', 'run the StyleGenAgent to generate style-controlled text using a transformer model', 'review the StyleGenAgent class that combines StyleAgentMixin with TransformerGeneratorAgent', 'build command-line arguments for the StyleGenAgent using add_cmdline_args method', 'test the StyleGenAgent style-controlled generation with the use_style_frac parameter', 'refactor the StyleGenAgent to customize style injection via the StyleAgentMixin']
```

Usage

```
{'build_classifier_on_generator': 'build a ClassifierOnGeneratorModel with a classifier head on top of a pretrained transformer generator', 'create_style_agent_mixin': 'create a StyleAgentMixin to conditionally insert style tokens into agent conversation histories', 'build_decoder_with_embeds': 'build a TransformerDecoderWithEmbeds decoder that accepts pre-embedded token inputs alongside standard inputs', 'review_classification_mixin': 'review the ClassificationMixin to add per-class precision, recall, and weighted F1 metrics to non-classifier models', 'test_forward_classifier_logits': 'test the ClassifierOnGeneratorModel forward method to get per-class logits from encoded text vectors'}
```

## File: facebookresearch_parlai/projects/style_gen/style_gen.py

Prompts

```
['build a ClassifierAgent that uses a pretrained generator model with a classifier head for style classification', 'train the ClassifierAgent on a batch of examples with label tensors and cross entropy loss', 'evaluate the ClassifierAgent on a batch and return predictions with optional class probabilities', 'freeze the encoder and decoder weights of the ClassifierAgent so only the classifier head is trained', 'build a CrossEntropyLoss criterion with class weights for the ClassifierAgent supporting FP16 safe mode', 'build a ClassifierOnGeneratorModel with a classifier head on top of a pretrained transformer generator', 'create a StyleAgentMixin to conditionally insert style tokens into agent conversation histories', 'build a TransformerDecoderWithEmbeds decoder that accepts pre-embedded token inputs alongside standard inputs', 'review the ClassificationMixin to add per-class precision, recall, and weighted F1 metrics to non-classifier models', 'test the ClassifierOnGeneratorModel forward method to get per-class logits from encoded text vectors', 'run the StyleGenAgent to generate style-controlled text using a transformer model', 'review the StyleGenAgent class that combines StyleAgentMixin with TransformerGeneratorAgent', 'build command-line arguments for the StyleGenAgent using add_cmdline_args method', 'test the StyleGenAgent style-controlled generation with the use_style_frac parameter', 'refactor the StyleGenAgent to customize style injection via the StyleAgentMixin']
```

Usage

```
{'run_style_gen_agent': 'run the StyleGenAgent to generate style-controlled text using a transformer model', 'review_style_gen_agent': 'review the StyleGenAgent class that combines StyleAgentMixin with TransformerGeneratorAgent', 'build_style_gen_cmdline_args': 'build command-line arguments for the StyleGenAgent using add_cmdline_args method', 'test_style_gen_agent': 'test the StyleGenAgent style-controlled generation with the use_style_frac parameter', 'refactor_style_gen_agent': 'refactor the StyleGenAgent to customize style injection via the StyleAgentMixin'}
```

