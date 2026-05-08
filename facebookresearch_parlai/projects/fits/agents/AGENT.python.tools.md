# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/fits/agents/director_bb2.py

Prompts

```
['build a DirectorBlenderBot2FidAgent model that combines classifier and generator heads for dialogue generation', 'review the DirectorFidModelMixin decoder_output method that blends generator logprobs with classifier scores using gamma weighting', 'test the DirectorFidAgent compute_classifier_loss method that computes BCE loss with explicit non-target token normalization', 'refactor the DirectorFidModelMixin classifier_output method to switch between linear, ffn, layer, or 2layers classifier architectures', 'summarize the DirectorFidAgent compute_loss method that combines generator and classifier losses with configurable mixing weights', 'build a DirectorComboFidModel that encodes inputs and decodes with director reranking via classifier heads', 'build a DirectorComboFidAgent that batches observations with skip director reranking vectors for generation', 'build a DirectorSeekerAgent that configures subagents with shared director reranking and mixing weight options', 'review the DirectorComboFidModel decoder_output method to understand how classifier logprobs modify generator scores', 'review the DirectorSeekerAgent init to understand how subagent options and reranking overrides are configured']
```

Usage

```
{'build_DirectorBlenderBot2FidAgent': 'build a DirectorBlenderBot2FidAgent model that combines classifier and generator heads for dialogue generation', 'review_DirectorFidModelMixin_decoder_output': 'review the DirectorFidModelMixin decoder_output method that blends generator logprobs with classifier scores using gamma weighting', 'test_DirectorFidAgent_compute_classifier_loss': 'test the DirectorFidAgent compute_classifier_loss method that computes BCE loss with explicit non-target token normalization', 'refactor_DirectorFidModelMixin_classifier_output': 'refactor the DirectorFidModelMixin classifier_output method to switch between linear, ffn, layer, or 2layers classifier architectures', 'summarize_DirectorFidAgent_compute_loss': 'summarize the DirectorFidAgent compute_loss method that combines generator and classifier losses with configurable mixing weights'}
```

## File: facebookresearch_parlai/projects/fits/agents/director_seeker.py

Prompts

```
['build a DirectorBlenderBot2FidAgent model that combines classifier and generator heads for dialogue generation', 'review the DirectorFidModelMixin decoder_output method that blends generator logprobs with classifier scores using gamma weighting', 'test the DirectorFidAgent compute_classifier_loss method that computes BCE loss with explicit non-target token normalization', 'refactor the DirectorFidModelMixin classifier_output method to switch between linear, ffn, layer, or 2layers classifier architectures', 'summarize the DirectorFidAgent compute_loss method that combines generator and classifier losses with configurable mixing weights', 'build a DirectorComboFidModel that encodes inputs and decodes with director reranking via classifier heads', 'build a DirectorComboFidAgent that batches observations with skip director reranking vectors for generation', 'build a DirectorSeekerAgent that configures subagents with shared director reranking and mixing weight options', 'review the DirectorComboFidModel decoder_output method to understand how classifier logprobs modify generator scores', 'review the DirectorSeekerAgent init to understand how subagent options and reranking overrides are configured']
```

Usage

```
{'build_DirectorComboFidModel': 'build a DirectorComboFidModel that encodes inputs and decodes with director reranking via classifier heads', 'build_DirectorComboFidAgent': 'build a DirectorComboFidAgent that batches observations with skip director reranking vectors for generation', 'build_DirectorSeekerAgent': 'build a DirectorSeekerAgent that configures subagents with shared director reranking and mixing weight options', 'review_DirectorComboFidModel_decoder_output': 'review the DirectorComboFidModel decoder_output method to understand how classifier logprobs modify generator scores', 'review_DirectorSeekerAgent_init': 'review the DirectorSeekerAgent init to understand how subagent options and reranking overrides are configured'}
```

