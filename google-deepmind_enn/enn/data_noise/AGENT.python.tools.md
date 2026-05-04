# Agent Python Tools

- repo: google-deepmind/enn
- repo_uri: https://github.com/google-deepmind/enn

## File: google-deepmind_enn/enn/data_noise/base.py

Prompts

```
['review the DataNoiseBase protocol that defines a callable interface for applying noise to data based on epistemic index', 'review the DataNoise type alias that specializes DataNoiseBase to work with ArrayBatch data', 'test the get_indexer function that traverses nested EpistemicIndexer objects to find the innermost indexer', 'summarize the get_indexer utility function that follows the indexer attribute chain to unwrap nested indexers', 'refactor the DataNoiseBase protocol to support additional noise process parameters beyond data and index', 'create a BootstrapNoise dataclass to apply bootstrap reweighting to a batch of data', 'build a bootstrap function for a given ENN and distribution using make_boot_fn', 'test the null_bootstrap function to verify it returns uniform ones-like weights', 'review the DISTRIBUTIONS dict for poisson, exponential, bernoulli, and uniform weight generators', 'summarize the _make_ensemble_bootstrap_fn factory method for creating ensemble-index bootstrap functions', 'test that make_boot_fn produces bootstrap weights with average approximately one', 'test make_boot_fn with EnsembleIndexer across poisson, bernoulli, exponential, uniform, and none distributions', 'test make_boot_fn with PrngIndexer across poisson, bernoulli, exponential, and uniform distributions', 'test make_boot_fn with GaussianWithUnitIndexer and ScaledGaussianIndexer using bernoulli and exponential distributions', 'test that all bootstrap batch weights produced by make_boot_fn are non-negative', 'build a python module that creates a GaussianTargetNoise dataclass to apply Gaussian noise to target y values', 'create a function that uses make_noise_fn to generate a noise function for a given ENN indexer type', 'test the GaussianTargetNoise class by calling it with an ArrayBatch and index to verify noise is applied', 'refactor make_noise_fn to add support for a new ENN indexer type beyond the four currently supported', 'review the GaussianTargetNoise dataclass and its __call__ method to understand how Gaussian noise is applied to targets']
```

Usage

```
{'review_DatanoiseBase_protocol': 'review the DataNoiseBase protocol that defines a callable interface for applying noise to data based on epistemic index', 'review_Datanoise_type_alias': 'review the DataNoise type alias that specializes DataNoiseBase to work with ArrayBatch data', 'test_get_indexer': 'test the get_indexer function that traverses nested EpistemicIndexer objects to find the innermost indexer', 'summarize_get_indexer': 'summarize the get_indexer utility function that follows the indexer attribute chain to unwrap nested indexers', 'refactor_DatanoiseBase_protocol': 'refactor the DataNoiseBase protocol to support additional noise process parameters beyond data and index'}
```

## File: google-deepmind_enn/enn/data_noise/bootstrapping.py

Prompts

```
['review the DataNoiseBase protocol that defines a callable interface for applying noise to data based on epistemic index', 'review the DataNoise type alias that specializes DataNoiseBase to work with ArrayBatch data', 'test the get_indexer function that traverses nested EpistemicIndexer objects to find the innermost indexer', 'summarize the get_indexer utility function that follows the indexer attribute chain to unwrap nested indexers', 'refactor the DataNoiseBase protocol to support additional noise process parameters beyond data and index', 'create a BootstrapNoise dataclass to apply bootstrap reweighting to a batch of data', 'build a bootstrap function for a given ENN and distribution using make_boot_fn', 'test the null_bootstrap function to verify it returns uniform ones-like weights', 'review the DISTRIBUTIONS dict for poisson, exponential, bernoulli, and uniform weight generators', 'summarize the _make_ensemble_bootstrap_fn factory method for creating ensemble-index bootstrap functions', 'test that make_boot_fn produces bootstrap weights with average approximately one', 'test make_boot_fn with EnsembleIndexer across poisson, bernoulli, exponential, uniform, and none distributions', 'test make_boot_fn with PrngIndexer across poisson, bernoulli, exponential, and uniform distributions', 'test make_boot_fn with GaussianWithUnitIndexer and ScaledGaussianIndexer using bernoulli and exponential distributions', 'test that all bootstrap batch weights produced by make_boot_fn are non-negative', 'build a python module that creates a GaussianTargetNoise dataclass to apply Gaussian noise to target y values', 'create a function that uses make_noise_fn to generate a noise function for a given ENN indexer type', 'test the GaussianTargetNoise class by calling it with an ArrayBatch and index to verify noise is applied', 'refactor make_noise_fn to add support for a new ENN indexer type beyond the four currently supported', 'review the GaussianTargetNoise dataclass and its __call__ method to understand how Gaussian noise is applied to targets']
```

Usage

```
{'create_bootstrap_noise': 'create a BootstrapNoise dataclass to apply bootstrap reweighting to a batch of data', 'build_make_boot_fn': 'build a bootstrap function for a given ENN and distribution using make_boot_fn', 'test_null_bootstrap': 'test the null_bootstrap function to verify it returns uniform ones-like weights', 'review_distributions': 'review the DISTRIBUTIONS dict for poisson, exponential, bernoulli, and uniform weight generators', 'summarize_ensemble_bootstrap': 'summarize the _make_ensemble_bootstrap_fn factory method for creating ensemble-index bootstrap functions'}
```

## File: google-deepmind_enn/enn/data_noise/bootstrapping_test.py

Prompts

```
['review the DataNoiseBase protocol that defines a callable interface for applying noise to data based on epistemic index', 'review the DataNoise type alias that specializes DataNoiseBase to work with ArrayBatch data', 'test the get_indexer function that traverses nested EpistemicIndexer objects to find the innermost indexer', 'summarize the get_indexer utility function that follows the indexer attribute chain to unwrap nested indexers', 'refactor the DataNoiseBase protocol to support additional noise process parameters beyond data and index', 'create a BootstrapNoise dataclass to apply bootstrap reweighting to a batch of data', 'build a bootstrap function for a given ENN and distribution using make_boot_fn', 'test the null_bootstrap function to verify it returns uniform ones-like weights', 'review the DISTRIBUTIONS dict for poisson, exponential, bernoulli, and uniform weight generators', 'summarize the _make_ensemble_bootstrap_fn factory method for creating ensemble-index bootstrap functions', 'test that make_boot_fn produces bootstrap weights with average approximately one', 'test make_boot_fn with EnsembleIndexer across poisson, bernoulli, exponential, uniform, and none distributions', 'test make_boot_fn with PrngIndexer across poisson, bernoulli, exponential, and uniform distributions', 'test make_boot_fn with GaussianWithUnitIndexer and ScaledGaussianIndexer using bernoulli and exponential distributions', 'test that all bootstrap batch weights produced by make_boot_fn are non-negative', 'build a python module that creates a GaussianTargetNoise dataclass to apply Gaussian noise to target y values', 'create a function that uses make_noise_fn to generate a noise function for a given ENN indexer type', 'test the GaussianTargetNoise class by calling it with an ArrayBatch and index to verify noise is applied', 'refactor make_noise_fn to add support for a new ENN indexer type beyond the four currently supported', 'review the GaussianTargetNoise dataclass and its __call__ method to understand how Gaussian noise is applied to targets']
```

Usage

```
{'test_make_boot_fn_average_weight': 'test that make_boot_fn produces bootstrap weights with average approximately one', 'test_make_boot_fn_with_ensemble_indexer': 'test make_boot_fn with EnsembleIndexer across poisson, bernoulli, exponential, uniform, and none distributions', 'test_make_boot_fn_with_prng_indexer': 'test make_boot_fn with PrngIndexer across poisson, bernoulli, exponential, and uniform distributions', 'test_make_boot_fn_with_gaussian_indexers': 'test make_boot_fn with GaussianWithUnitIndexer and ScaledGaussianIndexer using bernoulli and exponential distributions', 'test_bootstrapping_weight_non_negativity': 'test that all bootstrap batch weights produced by make_boot_fn are non-negative'}
```

## File: google-deepmind_enn/enn/data_noise/gaussian.py

Prompts

```
['review the DataNoiseBase protocol that defines a callable interface for applying noise to data based on epistemic index', 'review the DataNoise type alias that specializes DataNoiseBase to work with ArrayBatch data', 'test the get_indexer function that traverses nested EpistemicIndexer objects to find the innermost indexer', 'summarize the get_indexer utility function that follows the indexer attribute chain to unwrap nested indexers', 'refactor the DataNoiseBase protocol to support additional noise process parameters beyond data and index', 'create a BootstrapNoise dataclass to apply bootstrap reweighting to a batch of data', 'build a bootstrap function for a given ENN and distribution using make_boot_fn', 'test the null_bootstrap function to verify it returns uniform ones-like weights', 'review the DISTRIBUTIONS dict for poisson, exponential, bernoulli, and uniform weight generators', 'summarize the _make_ensemble_bootstrap_fn factory method for creating ensemble-index bootstrap functions', 'test that make_boot_fn produces bootstrap weights with average approximately one', 'test make_boot_fn with EnsembleIndexer across poisson, bernoulli, exponential, uniform, and none distributions', 'test make_boot_fn with PrngIndexer across poisson, bernoulli, exponential, and uniform distributions', 'test make_boot_fn with GaussianWithUnitIndexer and ScaledGaussianIndexer using bernoulli and exponential distributions', 'test that all bootstrap batch weights produced by make_boot_fn are non-negative', 'build a python module that creates a GaussianTargetNoise dataclass to apply Gaussian noise to target y values', 'create a function that uses make_noise_fn to generate a noise function for a given ENN indexer type', 'test the GaussianTargetNoise class by calling it with an ArrayBatch and index to verify noise is applied', 'refactor make_noise_fn to add support for a new ENN indexer type beyond the four currently supported', 'review the GaussianTargetNoise dataclass and its __call__ method to understand how Gaussian noise is applied to targets']
```

Usage

```
{'build_GaussianTargetNoise': 'build a python module that creates a GaussianTargetNoise dataclass to apply Gaussian noise to target y values', 'create_make_noise_fn': 'create a function that uses make_noise_fn to generate a noise function for a given ENN indexer type', 'test_GaussianTargetNoise_call': 'test the GaussianTargetNoise class by calling it with an ArrayBatch and index to verify noise is applied', 'refactor_make_noise_fn': 'refactor make_noise_fn to add support for a new ENN indexer type beyond the four currently supported', 'review_GaussianTargetNoise': 'review the GaussianTargetNoise dataclass and its __call__ method to understand how Gaussian noise is applied to targets'}
```

