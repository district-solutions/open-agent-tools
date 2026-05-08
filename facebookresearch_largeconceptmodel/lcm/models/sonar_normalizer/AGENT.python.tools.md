# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/lcm/models/sonar_normalizer/builder.py

Prompts

```
['create a SonarNormalizer instance from a SonarNormalizerConfig with optional device and dtype', 'fit a SonarNormalizer on embeddings to compute center, scale, and optional clip bounds', 'normalize SONAR embeddings using the fitted SonarNormalizer center and scale buffers', 'denormalize SONAR embeddings back to original space using the fitted SonarNormalizer', 'apply FFT transform to embeddings using FFTInterface for frequency-domain normalization']
```

Usage

```
{'create_sonar_normalizer': 'create a SonarNormalizer instance from a SonarNormalizerConfig with optional device and dtype', 'fit_sonar_normalizer': 'fit a SonarNormalizer on embeddings to compute center, scale, and optional clip bounds', 'normalize_embeddings': 'normalize SONAR embeddings using the fitted SonarNormalizer center and scale buffers', 'denormalize_embeddings': 'denormalize SONAR embeddings back to original space using the fitted SonarNormalizer', 'fft_transform_embeddings': 'apply FFT transform to embeddings using FFTInterface for frequency-domain normalization'}
```

