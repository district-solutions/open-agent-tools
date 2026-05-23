# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/banding_removal/fastmri/orientation_adversary/adversary_mixin.py

Prompts

```
['create an AdversaryModel wrapping a prediction model and adversary model for unified forward passes', 'create an AdversaryEnsemble of multiple adversary models that concatenates their outputs along dimension 1', 'review the AdversaryMixin model_setup method to load and configure discriminator models by type', 'review the AdversaryMixin additional_training_loss_terms method to add orientation adversary loss terms to training', 'use compute_grad2 to calculate the squared gradient norm for gradient penalty regularization', 'test the adversary mixin loss computation against the reference implementation', 'run a generator training step using the ReferenceTrainer with a latent vector', 'run a discriminator training step with optional gradient penalty regularization', 'review the binary cross entropy loss computation in ReferenceTrainer', 'test the toggle_grad and compute_grad2 utilities from the adversary mixin module']
```

Usage

```
{'create_AdversaryModel': 'create an AdversaryModel wrapping a prediction model and adversary model for unified forward passes', 'create_AdversaryEnsemble': 'create an AdversaryEnsemble of multiple adversary models that concatenates their outputs along dimension 1', 'review_AdversaryMixin_model_setup': 'review the AdversaryMixin model_setup method to load and configure discriminator models by type', 'review_AdversaryMixin_additional_training_loss_terms': 'review the AdversaryMixin additional_training_loss_terms method to add orientation adversary loss terms to training', 'use_compute_grad2': 'use compute_grad2 to calculate the squared gradient norm for gradient penalty regularization'}
```

## File: facebookresearch_fastmri/banding_removal/fastmri/orientation_adversary/test_adversary.py

Prompts

```
['create an AdversaryModel wrapping a prediction model and adversary model for unified forward passes', 'create an AdversaryEnsemble of multiple adversary models that concatenates their outputs along dimension 1', 'review the AdversaryMixin model_setup method to load and configure discriminator models by type', 'review the AdversaryMixin additional_training_loss_terms method to add orientation adversary loss terms to training', 'use compute_grad2 to calculate the squared gradient norm for gradient penalty regularization', 'test the adversary mixin loss computation against the reference implementation', 'run a generator training step using the ReferenceTrainer with a latent vector', 'run a discriminator training step with optional gradient penalty regularization', 'review the binary cross entropy loss computation in ReferenceTrainer', 'test the toggle_grad and compute_grad2 utilities from the adversary mixin module']
```

Usage

```
{'test_adversary_training': 'test the adversary mixin loss computation against the reference implementation', 'run_ReferenceTrainer_generator_trainstep': 'run a generator training step using the ReferenceTrainer with a latent vector', 'run_ReferenceTrainer_discriminator_trainstep': 'run a discriminator training step with optional gradient penalty regularization', 'review_ReferenceTrainer_compute_loss': 'review the binary cross entropy loss computation in ReferenceTrainer', 'test_toggle_grad_and_compute_grad2': 'test the toggle_grad and compute_grad2 utilities from the adversary mixin module'}
```

