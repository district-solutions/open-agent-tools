# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/dsprites_bvae/archs.py

Prompts

```
['build a CNN encoder that encodes 64x64 images into a latent z_dim vector', 'build a CNN decoder that reconstructs 64x64 images from a latent z_dim vector', 'create a function that applies Kaiming normal initialization to Linear and Conv2d layers', 'create a function that applies normal distribution weight initialization with configurable mean and std', 'review the View nn.Module subclass that reshapes tensors to a specified size in forward pass', 'run the python module to extract dsprites BVAE results from a directory of log files', 'run process_file to parse a single log file and extract z_dim, vocab_size, beta, and random_seed', 'extract topsim and posdis metrics from a dsprites BVAE training log file', 'parse a BVAE log file to extract hyperparameters like z_dim, vocab_size, beta, and random_seed', 'batch process all log files in a directory and collect extracted metrics into a list', 'run the beta-VAE training loop on the dSprites dataset with sender and receiver networks', 'build a betaVAE_Game module with a VisualSender and VisualReceiver for variational autoencoding', 'create a function that computes bernoulli or gaussian reconstruction loss between input and output tensors', 'test the kl_divergence function to compute total, dimension-wise, and mean KL divergence values', 'review the ImageDumpCallback class that saves reconstructed images alongside originals at each epoch end']
```

Usage

```
{'build_visual_sender': 'build a CNN encoder that encodes 64x64 images into a latent z_dim vector', 'build_visual_receiver': 'build a CNN decoder that reconstructs 64x64 images from a latent z_dim vector', 'create_kaiming_init': 'create a function that applies Kaiming normal initialization to Linear and Conv2d layers', 'create_normal_init': 'create a function that applies normal distribution weight initialization with configurable mean and std', 'review_view_module': 'review the View nn.Module subclass that reshapes tensors to a specified size in forward pass'}
```

## File: facebookresearch_egg/egg/zoo/dsprites_bvae/extract_results.py

Prompts

```
['build a CNN encoder that encodes 64x64 images into a latent z_dim vector', 'build a CNN decoder that reconstructs 64x64 images from a latent z_dim vector', 'create a function that applies Kaiming normal initialization to Linear and Conv2d layers', 'create a function that applies normal distribution weight initialization with configurable mean and std', 'review the View nn.Module subclass that reshapes tensors to a specified size in forward pass', 'run the python module to extract dsprites BVAE results from a directory of log files', 'run process_file to parse a single log file and extract z_dim, vocab_size, beta, and random_seed', 'extract topsim and posdis metrics from a dsprites BVAE training log file', 'parse a BVAE log file to extract hyperparameters like z_dim, vocab_size, beta, and random_seed', 'batch process all log files in a directory and collect extracted metrics into a list', 'run the beta-VAE training loop on the dSprites dataset with sender and receiver networks', 'build a betaVAE_Game module with a VisualSender and VisualReceiver for variational autoencoding', 'create a function that computes bernoulli or gaussian reconstruction loss between input and output tensors', 'test the kl_divergence function to compute total, dimension-wise, and mean KL divergence values', 'review the ImageDumpCallback class that saves reconstructed images alongside originals at each epoch end']
```

Usage

```
{'run_extract_results': 'run the python module to extract dsprites BVAE results from a directory of log files', 'run_process_file': 'run process_file to parse a single log file and extract z_dim, vocab_size, beta, and random_seed', 'extract_topsim_posdis': 'extract topsim and posdis metrics from a dsprites BVAE training log file', 'parse_bvae_config': 'parse a BVAE log file to extract hyperparameters like z_dim, vocab_size, beta, and random_seed', 'batch_process_results': 'batch process all log files in a directory and collect extracted metrics into a list'}
```

## File: facebookresearch_egg/egg/zoo/dsprites_bvae/train.py

Prompts

```
['build a CNN encoder that encodes 64x64 images into a latent z_dim vector', 'build a CNN decoder that reconstructs 64x64 images from a latent z_dim vector', 'create a function that applies Kaiming normal initialization to Linear and Conv2d layers', 'create a function that applies normal distribution weight initialization with configurable mean and std', 'review the View nn.Module subclass that reshapes tensors to a specified size in forward pass', 'run the python module to extract dsprites BVAE results from a directory of log files', 'run process_file to parse a single log file and extract z_dim, vocab_size, beta, and random_seed', 'extract topsim and posdis metrics from a dsprites BVAE training log file', 'parse a BVAE log file to extract hyperparameters like z_dim, vocab_size, beta, and random_seed', 'batch process all log files in a directory and collect extracted metrics into a list', 'run the beta-VAE training loop on the dSprites dataset with sender and receiver networks', 'build a betaVAE_Game module with a VisualSender and VisualReceiver for variational autoencoding', 'create a function that computes bernoulli or gaussian reconstruction loss between input and output tensors', 'test the kl_divergence function to compute total, dimension-wise, and mean KL divergence values', 'review the ImageDumpCallback class that saves reconstructed images alongside originals at each epoch end']
```

Usage

```
{'run_beta_vae_training': 'run the beta-VAE training loop on the dSprites dataset with sender and receiver networks', 'build_betaVAE_Game': 'build a betaVAE_Game module with a VisualSender and VisualReceiver for variational autoencoding', 'create_reconstruction_loss': 'create a function that computes bernoulli or gaussian reconstruction loss between input and output tensors', 'test_kl_divergence': 'test the kl_divergence function to compute total, dimension-wise, and mean KL divergence values', 'review_ImageDumpCallback': 'review the ImageDumpCallback class that saves reconstructed images alongside originals at each epoch end'}
```

