# Agent Python Tools

- repo: facebookresearch/ai4animationpy
- repo_uri: https://github.com/facebookresearch/ai4animationpy

## File: facebookresearch_ai4animationpy/ai4animation/AI/Models/Autoencoder.py

Prompts

```
['build a python module to create an Autoencoder Model with configurable feature, hidden, and latent dimensions', 'create a function that runs a forward pass through the Autoencoder Model and returns reconstructed output', 'train the Autoencoder Model using the learn method with features and update statistics flag', 'get the feature dimension of the Autoencoder Model by calling the feature_dim method', 'get the latent dimension of the Autoencoder Model by calling the latent_dim method', 'build a CategoricalEncoderDecoder Model with input_dim, output_dim, encoder_dim, channels, classes, and decoder_dim parameters', 'run a forward pass through the CategoricalEncoderDecoder model with input tensor x and optional sampling', 'train the CategoricalEncoderDecoder model using learn method with inputs, outputs, and update_statistics flag', 'get the input and output dimensions of the CategoricalEncoderDecoder model using input_dim and output_dim methods', 'review how the CodebookLayer integrates with the Encoder and Decoder in the CategoricalEncoderDecoder model', 'build a CodebookMatching Model with encoder, decoder, estimator, and denoiser for animation data', 'create an Encoder that processes spatial and temporal features through LinearBlock layers', 'create a Decoder that generates output sequences from codes using FiLM regularization', 'run the Model learn method to compute reconstruction, regularization, matching, and denoising losses', 'run the Model forward pass to estimate and denoise codebook codes from input data', 'create a MultiLayerPerceptron Model with specified input, output, and hidden dimensions', 'run the forward pass of the MLP Model to normalize input and produce denormalized output', 'train the MLP Model using learn method with input, output, and statistics update flag', 'inspect the MLP Model to retrieve its input dimension size from the first layer', 'inspect the MLP Model to retrieve its output dimension size from the third layer']
```

Usage

```
{'build_autoencoder_model': 'build a python module to create an Autoencoder Model with configurable feature, hidden, and latent dimensions', 'create_autoencoder_forward_pass': 'create a function that runs a forward pass through the Autoencoder Model and returns reconstructed output', 'train_autoencoder_learn': 'train the Autoencoder Model using the learn method with features and update statistics flag', 'get_autoencoder_feature_dim': 'get the feature dimension of the Autoencoder Model by calling the feature_dim method', 'get_autoencoder_latent_dim': 'get the latent dimension of the Autoencoder Model by calling the latent_dim method'}
```

## File: facebookresearch_ai4animationpy/ai4animation/AI/Models/CategoricalEncoderDecoder.py

Prompts

```
['build a python module to create an Autoencoder Model with configurable feature, hidden, and latent dimensions', 'create a function that runs a forward pass through the Autoencoder Model and returns reconstructed output', 'train the Autoencoder Model using the learn method with features and update statistics flag', 'get the feature dimension of the Autoencoder Model by calling the feature_dim method', 'get the latent dimension of the Autoencoder Model by calling the latent_dim method', 'build a CategoricalEncoderDecoder Model with input_dim, output_dim, encoder_dim, channels, classes, and decoder_dim parameters', 'run a forward pass through the CategoricalEncoderDecoder model with input tensor x and optional sampling', 'train the CategoricalEncoderDecoder model using learn method with inputs, outputs, and update_statistics flag', 'get the input and output dimensions of the CategoricalEncoderDecoder model using input_dim and output_dim methods', 'review how the CodebookLayer integrates with the Encoder and Decoder in the CategoricalEncoderDecoder model', 'build a CodebookMatching Model with encoder, decoder, estimator, and denoiser for animation data', 'create an Encoder that processes spatial and temporal features through LinearBlock layers', 'create a Decoder that generates output sequences from codes using FiLM regularization', 'run the Model learn method to compute reconstruction, regularization, matching, and denoising losses', 'run the Model forward pass to estimate and denoise codebook codes from input data', 'create a MultiLayerPerceptron Model with specified input, output, and hidden dimensions', 'run the forward pass of the MLP Model to normalize input and produce denormalized output', 'train the MLP Model using learn method with input, output, and statistics update flag', 'inspect the MLP Model to retrieve its input dimension size from the first layer', 'inspect the MLP Model to retrieve its output dimension size from the third layer']
```

Usage

```
{'build_categorical_encoder_decoder_model': 'build a CategoricalEncoderDecoder Model with input_dim, output_dim, encoder_dim, channels, classes, and decoder_dim parameters', 'run_forward_pass': 'run a forward pass through the CategoricalEncoderDecoder model with input tensor x and optional sampling', 'train_model_learn': 'train the CategoricalEncoderDecoder model using learn method with inputs, outputs, and update_statistics flag', 'get_input_output_dimensions': 'get the input and output dimensions of the CategoricalEncoderDecoder model using input_dim and output_dim methods', 'review_codebook_layer_integration': 'review how the CodebookLayer integrates with the Encoder and Decoder in the CategoricalEncoderDecoder model'}
```

## File: facebookresearch_ai4animationpy/ai4animation/AI/Models/CodebookMatching.py

Prompts

```
['build a python module to create an Autoencoder Model with configurable feature, hidden, and latent dimensions', 'create a function that runs a forward pass through the Autoencoder Model and returns reconstructed output', 'train the Autoencoder Model using the learn method with features and update statistics flag', 'get the feature dimension of the Autoencoder Model by calling the feature_dim method', 'get the latent dimension of the Autoencoder Model by calling the latent_dim method', 'build a CategoricalEncoderDecoder Model with input_dim, output_dim, encoder_dim, channels, classes, and decoder_dim parameters', 'run a forward pass through the CategoricalEncoderDecoder model with input tensor x and optional sampling', 'train the CategoricalEncoderDecoder model using learn method with inputs, outputs, and update_statistics flag', 'get the input and output dimensions of the CategoricalEncoderDecoder model using input_dim and output_dim methods', 'review how the CodebookLayer integrates with the Encoder and Decoder in the CategoricalEncoderDecoder model', 'build a CodebookMatching Model with encoder, decoder, estimator, and denoiser for animation data', 'create an Encoder that processes spatial and temporal features through LinearBlock layers', 'create a Decoder that generates output sequences from codes using FiLM regularization', 'run the Model learn method to compute reconstruction, regularization, matching, and denoising losses', 'run the Model forward pass to estimate and denoise codebook codes from input data', 'create a MultiLayerPerceptron Model with specified input, output, and hidden dimensions', 'run the forward pass of the MLP Model to normalize input and produce denormalized output', 'train the MLP Model using learn method with input, output, and statistics update flag', 'inspect the MLP Model to retrieve its input dimension size from the first layer', 'inspect the MLP Model to retrieve its output dimension size from the third layer']
```

Usage

```
{'build_codebook_matching_model': 'build a CodebookMatching Model with encoder, decoder, estimator, and denoiser for animation data', 'create_encoder_forward': 'create an Encoder that processes spatial and temporal features through LinearBlock layers', 'create_decoder_forward': 'create a Decoder that generates output sequences from codes using FiLM regularization', 'run_model_learn': 'run the Model learn method to compute reconstruction, regularization, matching, and denoising losses', 'run_model_forward': 'run the Model forward pass to estimate and denoise codebook codes from input data'}
```

## File: facebookresearch_ai4animationpy/ai4animation/AI/Models/MultiLayerPerceptron.py

Prompts

```
['build a python module to create an Autoencoder Model with configurable feature, hidden, and latent dimensions', 'create a function that runs a forward pass through the Autoencoder Model and returns reconstructed output', 'train the Autoencoder Model using the learn method with features and update statistics flag', 'get the feature dimension of the Autoencoder Model by calling the feature_dim method', 'get the latent dimension of the Autoencoder Model by calling the latent_dim method', 'build a CategoricalEncoderDecoder Model with input_dim, output_dim, encoder_dim, channels, classes, and decoder_dim parameters', 'run a forward pass through the CategoricalEncoderDecoder model with input tensor x and optional sampling', 'train the CategoricalEncoderDecoder model using learn method with inputs, outputs, and update_statistics flag', 'get the input and output dimensions of the CategoricalEncoderDecoder model using input_dim and output_dim methods', 'review how the CodebookLayer integrates with the Encoder and Decoder in the CategoricalEncoderDecoder model', 'build a CodebookMatching Model with encoder, decoder, estimator, and denoiser for animation data', 'create an Encoder that processes spatial and temporal features through LinearBlock layers', 'create a Decoder that generates output sequences from codes using FiLM regularization', 'run the Model learn method to compute reconstruction, regularization, matching, and denoising losses', 'run the Model forward pass to estimate and denoise codebook codes from input data', 'create a MultiLayerPerceptron Model with specified input, output, and hidden dimensions', 'run the forward pass of the MLP Model to normalize input and produce denormalized output', 'train the MLP Model using learn method with input, output, and statistics update flag', 'inspect the MLP Model to retrieve its input dimension size from the first layer', 'inspect the MLP Model to retrieve its output dimension size from the third layer']
```

Usage

```
{'create_MLP_model': 'create a MultiLayerPerceptron Model with specified input, output, and hidden dimensions', 'run_MLP_forward': 'run the forward pass of the MLP Model to normalize input and produce denormalized output', 'train_MLP_learn': 'train the MLP Model using learn method with input, output, and statistics update flag', 'inspect_MLP_input_dim': 'inspect the MLP Model to retrieve its input dimension size from the first layer', 'inspect_MLP_output_dim': 'inspect the MLP Model to retrieve its output dimension size from the third layer'}
```

