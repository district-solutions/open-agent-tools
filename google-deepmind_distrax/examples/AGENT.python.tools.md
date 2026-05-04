# Agent Python Tools

- repo: google-deepmind/distrax
- repo_uri: https://github.com/google-deepmind/distrax

## File: google-deepmind_distrax/examples/flow.py

Prompts

```
['run the flow model training script on MNIST with configurable layers, bins, and learning rate', 'build a normalizing flow model using MaskedCoupling layers and RationalQuadraticSpline bijectors on MNIST images', 'create an MLP conditioner network with Haiku for parameterizing flow bijector parameters per layer', 'prepare MNIST image batches by dequantizing with uniform noise and normalizing pixel values to [0,1)', 'evaluate the trained flow model by computing the average negative log likelihood on a validation batch', 'run the HMM changepoint detection example with configurable Poisson rates and state counts', 'generate synthetic data from a Poisson process with changing rates over time', 'build an initial state probability vector and state transition matrix for an HMM', 'create a Hidden Markov Model with Poisson observation distribution using distrax', 'compute run-length durations from a sequence of values by counting consecutive repeats', 'build a variational autoencoder model using distrax distributions and haiku for binarized MNIST', 'create an encoder and decoder network using haiku linear layers for latent space modeling', 'run VAE training on binarized MNIST with Adam optimizer and ELBO loss computation', 'create a loss function that computes negative ELBO with log likelihood and KL divergence terms', 'sample reconstructed images from the VAE likelihood distribution using distrax Bernoulli']
```

Usage

```
{'run_flow_model_training': 'run the flow model training script on MNIST with configurable layers, bins, and learning rate', 'build_flow_model': 'build a normalizing flow model using MaskedCoupling layers and RationalQuadraticSpline bijectors on MNIST images', 'create_mlp_conditioner': 'create an MLP conditioner network with Haiku for parameterizing flow bijector parameters per layer', 'prepare_mnist_data': 'prepare MNIST image batches by dequantizing with uniform noise and normalizing pixel values to [0,1)', 'evaluate_flow_model': 'evaluate the trained flow model by computing the average negative log likelihood on a validation batch'}
```

## File: google-deepmind_distrax/examples/hmm.py

Prompts

```
['run the flow model training script on MNIST with configurable layers, bins, and learning rate', 'build a normalizing flow model using MaskedCoupling layers and RationalQuadraticSpline bijectors on MNIST images', 'create an MLP conditioner network with Haiku for parameterizing flow bijector parameters per layer', 'prepare MNIST image batches by dequantizing with uniform noise and normalizing pixel values to [0,1)', 'evaluate the trained flow model by computing the average negative log likelihood on a validation batch', 'run the HMM changepoint detection example with configurable Poisson rates and state counts', 'generate synthetic data from a Poisson process with changing rates over time', 'build an initial state probability vector and state transition matrix for an HMM', 'create a Hidden Markov Model with Poisson observation distribution using distrax', 'compute run-length durations from a sequence of values by counting consecutive repeats', 'build a variational autoencoder model using distrax distributions and haiku for binarized MNIST', 'create an encoder and decoder network using haiku linear layers for latent space modeling', 'run VAE training on binarized MNIST with Adam optimizer and ELBO loss computation', 'create a loss function that computes negative ELBO with log likelihood and KL divergence terms', 'sample reconstructed images from the VAE likelihood distribution using distrax Bernoulli']
```

Usage

```
{'run_hmm_changepoint_detection': 'run the HMM changepoint detection example with configurable Poisson rates and state counts', 'generate_data_poisson_process': 'generate synthetic data from a Poisson process with changing rates over time', 'build_latent_state_transition_matrix': 'build an initial state probability vector and state transition matrix for an HMM', 'make_hmm_poisson_model': 'create a Hidden Markov Model with Poisson observation distribution using distrax', 'get_durations_run_length': 'compute run-length durations from a sequence of values by counting consecutive repeats'}
```

## File: google-deepmind_distrax/examples/vae.py

Prompts

```
['run the flow model training script on MNIST with configurable layers, bins, and learning rate', 'build a normalizing flow model using MaskedCoupling layers and RationalQuadraticSpline bijectors on MNIST images', 'create an MLP conditioner network with Haiku for parameterizing flow bijector parameters per layer', 'prepare MNIST image batches by dequantizing with uniform noise and normalizing pixel values to [0,1)', 'evaluate the trained flow model by computing the average negative log likelihood on a validation batch', 'run the HMM changepoint detection example with configurable Poisson rates and state counts', 'generate synthetic data from a Poisson process with changing rates over time', 'build an initial state probability vector and state transition matrix for an HMM', 'create a Hidden Markov Model with Poisson observation distribution using distrax', 'compute run-length durations from a sequence of values by counting consecutive repeats', 'build a variational autoencoder model using distrax distributions and haiku for binarized MNIST', 'create an encoder and decoder network using haiku linear layers for latent space modeling', 'run VAE training on binarized MNIST with Adam optimizer and ELBO loss computation', 'create a loss function that computes negative ELBO with log likelihood and KL divergence terms', 'sample reconstructed images from the VAE likelihood distribution using distrax Bernoulli']
```

Usage

```
{'build_vae_model': 'build a variational autoencoder model using distrax distributions and haiku for binarized MNIST', 'create_encoder_decoder': 'create an encoder and decoder network using haiku linear layers for latent space modeling', 'run_vae_training': 'run VAE training on binarized MNIST with Adam optimizer and ELBO loss computation', 'create_elbo_loss': 'create a loss function that computes negative ELBO with log likelihood and KL divergence terms', 'sample_vae_images': 'sample reconstructed images from the VAE likelihood distribution using distrax Bernoulli'}
```

