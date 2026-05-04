# Agent Python Tools

- repo: google-deepmind/enn
- repo_uri: https://github.com/google-deepmind/enn

## File: google-deepmind_enn/enn/extra/kmeans.py

Prompts

```
['create a KMeansCluster with num_centroids and num_iterations then call fit on data to get centroids and classes', 'call get_classes_and_distances with data and centroids to assign each point to its nearest centroid', 'call kmeans_iteration with data and a TrainingState to compute updated centroids for one step', 'call compute_output with data and a final TrainingState to get centroids counts std_distance and classes', 'create a KMeansCluster which randomly initializes centroids from data points using a PRNG key', 'test the KMeansCluster class to verify it runs without nan values across parameterized inputs', 'run KMeansCluster fit method on random JAX arrays to compute centroids and counts', 'test that KMeansCluster output centroids match expected shape of num_centroids by dim_x', 'test that KMeansCluster fit returns finite values for centroids, counts, and std_distance', 'run parameterized KMeans test with varying num_x, dim_x, and num_centroids combinations', 'train an MLP VAE on data using get_mlp_vae_encoder_decoder with a custom MLPVAEConfig', 'create an ENN from encoder and decoder functions using make_vae_enn with a latent dimension', 'train a custom VAE with encoder and decoder using train_vae with a specified optimizer and loss function', 'configure an MLP VAE with hidden sizes, latent dimension, and learning rate using MLPVAEConfig', 'encode data to latent space and decode back using the TrainedVAE encoder and decoder functions', 'test VAE encoder and decoder outputs with parameterized bernoulli decoder and latent dimensions', 'train an MLP VAE on test data using MLPVAEConfig with specified hidden sizes and latent dimension', 'run the VaeTest test class to validate VAE encoder decoder shape assertions', 'create an MLPVAEConfig with hidden sizes, latent dimension, bernoulli decoder, and batch settings', 'verify encoder and decoder output shapes match expected latent and input dimensions']
```

Usage

```
{'run_kmeans_clustering': 'create a KMeansCluster with num_centroids and num_iterations then call fit on data to get centroids and classes', 'compute_nearest_centroids': 'call get_classes_and_distances with data and centroids to assign each point to its nearest centroid', 'perform_kmeans_iteration': 'call kmeans_iteration with data and a TrainingState to compute updated centroids for one step', 'extract_kmeans_output': 'call compute_output with data and a final TrainingState to get centroids counts std_distance and classes', 'initialize_kmeans_centroids': 'create a KMeansCluster which randomly initializes centroids from data points using a PRNG key'}
```

## File: google-deepmind_enn/enn/extra/kmeans_test.py

Prompts

```
['create a KMeansCluster with num_centroids and num_iterations then call fit on data to get centroids and classes', 'call get_classes_and_distances with data and centroids to assign each point to its nearest centroid', 'call kmeans_iteration with data and a TrainingState to compute updated centroids for one step', 'call compute_output with data and a final TrainingState to get centroids counts std_distance and classes', 'create a KMeansCluster which randomly initializes centroids from data points using a PRNG key', 'test the KMeansCluster class to verify it runs without nan values across parameterized inputs', 'run KMeansCluster fit method on random JAX arrays to compute centroids and counts', 'test that KMeansCluster output centroids match expected shape of num_centroids by dim_x', 'test that KMeansCluster fit returns finite values for centroids, counts, and std_distance', 'run parameterized KMeans test with varying num_x, dim_x, and num_centroids combinations', 'train an MLP VAE on data using get_mlp_vae_encoder_decoder with a custom MLPVAEConfig', 'create an ENN from encoder and decoder functions using make_vae_enn with a latent dimension', 'train a custom VAE with encoder and decoder using train_vae with a specified optimizer and loss function', 'configure an MLP VAE with hidden sizes, latent dimension, and learning rate using MLPVAEConfig', 'encode data to latent space and decode back using the TrainedVAE encoder and decoder functions', 'test VAE encoder and decoder outputs with parameterized bernoulli decoder and latent dimensions', 'train an MLP VAE on test data using MLPVAEConfig with specified hidden sizes and latent dimension', 'run the VaeTest test class to validate VAE encoder decoder shape assertions', 'create an MLPVAEConfig with hidden sizes, latent dimension, bernoulli decoder, and batch settings', 'verify encoder and decoder output shapes match expected latent and input dimensions']
```

Usage

```
{'test_kmeans_runs': 'test the KMeansCluster class to verify it runs without nan values across parameterized inputs', 'run_KMeansCluster_fit': 'run KMeansCluster fit method on random JAX arrays to compute centroids and counts', 'test_centroid_shapes': 'test that KMeansCluster output centroids match expected shape of num_centroids by dim_x', 'test_finite_outputs': 'test that KMeansCluster fit returns finite values for centroids, counts, and std_distance', 'run_parameterized_kmeans_test': 'run parameterized KMeans test with varying num_x, dim_x, and num_centroids combinations'}
```

## File: google-deepmind_enn/enn/extra/vae.py

Prompts

```
['create a KMeansCluster with num_centroids and num_iterations then call fit on data to get centroids and classes', 'call get_classes_and_distances with data and centroids to assign each point to its nearest centroid', 'call kmeans_iteration with data and a TrainingState to compute updated centroids for one step', 'call compute_output with data and a final TrainingState to get centroids counts std_distance and classes', 'create a KMeansCluster which randomly initializes centroids from data points using a PRNG key', 'test the KMeansCluster class to verify it runs without nan values across parameterized inputs', 'run KMeansCluster fit method on random JAX arrays to compute centroids and counts', 'test that KMeansCluster output centroids match expected shape of num_centroids by dim_x', 'test that KMeansCluster fit returns finite values for centroids, counts, and std_distance', 'run parameterized KMeans test with varying num_x, dim_x, and num_centroids combinations', 'train an MLP VAE on data using get_mlp_vae_encoder_decoder with a custom MLPVAEConfig', 'create an ENN from encoder and decoder functions using make_vae_enn with a latent dimension', 'train a custom VAE with encoder and decoder using train_vae with a specified optimizer and loss function', 'configure an MLP VAE with hidden sizes, latent dimension, and learning rate using MLPVAEConfig', 'encode data to latent space and decode back using the TrainedVAE encoder and decoder functions', 'test VAE encoder and decoder outputs with parameterized bernoulli decoder and latent dimensions', 'train an MLP VAE on test data using MLPVAEConfig with specified hidden sizes and latent dimension', 'run the VaeTest test class to validate VAE encoder decoder shape assertions', 'create an MLPVAEConfig with hidden sizes, latent dimension, bernoulli decoder, and batch settings', 'verify encoder and decoder output shapes match expected latent and input dimensions']
```

Usage

```
{'train_mlp_vae': 'train an MLP VAE on data using get_mlp_vae_encoder_decoder with a custom MLPVAEConfig', 'create_vae_enn': 'create an ENN from encoder and decoder functions using make_vae_enn with a latent dimension', 'train_custom_vae': 'train a custom VAE with encoder and decoder using train_vae with a specified optimizer and loss function', 'configure_mlp_vae': 'configure an MLP VAE with hidden sizes, latent dimension, and learning rate using MLPVAEConfig', 'encode_decode_latent': 'encode data to latent space and decode back using the TrainedVAE encoder and decoder functions'}
```

## File: google-deepmind_enn/enn/extra/vae_test.py

Prompts

```
['create a KMeansCluster with num_centroids and num_iterations then call fit on data to get centroids and classes', 'call get_classes_and_distances with data and centroids to assign each point to its nearest centroid', 'call kmeans_iteration with data and a TrainingState to compute updated centroids for one step', 'call compute_output with data and a final TrainingState to get centroids counts std_distance and classes', 'create a KMeansCluster which randomly initializes centroids from data points using a PRNG key', 'test the KMeansCluster class to verify it runs without nan values across parameterized inputs', 'run KMeansCluster fit method on random JAX arrays to compute centroids and counts', 'test that KMeansCluster output centroids match expected shape of num_centroids by dim_x', 'test that KMeansCluster fit returns finite values for centroids, counts, and std_distance', 'run parameterized KMeans test with varying num_x, dim_x, and num_centroids combinations', 'train an MLP VAE on data using get_mlp_vae_encoder_decoder with a custom MLPVAEConfig', 'create an ENN from encoder and decoder functions using make_vae_enn with a latent dimension', 'train a custom VAE with encoder and decoder using train_vae with a specified optimizer and loss function', 'configure an MLP VAE with hidden sizes, latent dimension, and learning rate using MLPVAEConfig', 'encode data to latent space and decode back using the TrainedVAE encoder and decoder functions', 'test VAE encoder and decoder outputs with parameterized bernoulli decoder and latent dimensions', 'train an MLP VAE on test data using MLPVAEConfig with specified hidden sizes and latent dimension', 'run the VaeTest test class to validate VAE encoder decoder shape assertions', 'create an MLPVAEConfig with hidden sizes, latent dimension, bernoulli decoder, and batch settings', 'verify encoder and decoder output shapes match expected latent and input dimensions']
```

Usage

```
{'test_VAE_outputs': 'test VAE encoder and decoder outputs with parameterized bernoulli decoder and latent dimensions', 'train_MLP_VAE': 'train an MLP VAE on test data using MLPVAEConfig with specified hidden sizes and latent dimension', 'run_VaeTest': 'run the VaeTest test class to validate VAE encoder decoder shape assertions', 'create_MLPVAEConfig': 'create an MLPVAEConfig with hidden sizes, latent dimension, bernoulli decoder, and batch settings', 'verify_encoder_decoder_shapes': 'verify encoder and decoder output shapes match expected latent and input dimensions'}
```

