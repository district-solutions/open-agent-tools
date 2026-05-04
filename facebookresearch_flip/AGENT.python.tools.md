# Agent Python Tools

- repo: facebookresearch/flip
- repo_uri: https://github.com/facebookresearch/flip

## File: facebookresearch_flip/input_pipeline_imagenet.py

Prompts

```
['create a tf.data.Dataset split from ImageNet validation using TensorFlow Datasets with sharding', 'preprocess raw image bytes for evaluation with center crop, normalization, and dtype conversion', 'build a sharded ImageNet evaluation data pipeline with batching, prefetching, and caching support', 'decode an ImageNet example into image tensor, label, and one-hot encoded label', 'configure TensorFlow dataset threading options with a private threadpool size for parallel processing', 'create a TensorFlow dataset split from LAION TFRecord files with sharding and batching support', 'parse a single LAION TFRecord example proto into image, text, and metadata fields', 'preprocess text using a BERT tokenizer with padding and optional CLS token prepending', 'preprocess an image with random crop, flip, and normalization for training', 'create a TensorFlow dataset from text tags with BERT tokenization and batching', 'build a FLIP model for fast language-image pre-training with masking using JAX and Flax', 'create a VisionTransformer encoder module with patch embedding, positional encoding, and random masking for image inputs', 'create a LanguageTransformer encoder module with token embedding and positional encoding for text sequence inputs', 'review the Encoder1DBlock transformer encoder layer with multi-head attention, MLP, dropout, and droppath regularization', 'test the compute_contrastive_loss method that calculates image-text contrastive loss with learnable temperature scaling', 'run the FLIP model training and evaluation loop with a given config and workdir', 'build training, validation, and tag data loaders from LAION and ImageNet datasets', 'run a single training step computing gradients and updating model state', 'run an evaluation step computing image-text similarity accuracy against encoded tags', 'run the full evaluation pipeline encoding tags and computing accuracy metrics on ImageNet']
```

Usage

```
{'create_tfds_imagenet_validation_split': 'create a tf.data.Dataset split from ImageNet validation using TensorFlow Datasets with sharding', 'preprocess_image_for_evaluation': 'preprocess raw image bytes for evaluation with center crop, normalization, and dtype conversion', 'build_imagenet_data_pipeline': 'build a sharded ImageNet evaluation data pipeline with batching, prefetching, and caching support', 'decode_imagenet_example': 'decode an ImageNet example into image tensor, label, and one-hot encoded label', 'configure_dataset_threading_options': 'configure TensorFlow dataset threading options with a private threadpool size for parallel processing'}
```

## File: facebookresearch_flip/input_pipeline_laion.py

Prompts

```
['create a tf.data.Dataset split from ImageNet validation using TensorFlow Datasets with sharding', 'preprocess raw image bytes for evaluation with center crop, normalization, and dtype conversion', 'build a sharded ImageNet evaluation data pipeline with batching, prefetching, and caching support', 'decode an ImageNet example into image tensor, label, and one-hot encoded label', 'configure TensorFlow dataset threading options with a private threadpool size for parallel processing', 'create a TensorFlow dataset split from LAION TFRecord files with sharding and batching support', 'parse a single LAION TFRecord example proto into image, text, and metadata fields', 'preprocess text using a BERT tokenizer with padding and optional CLS token prepending', 'preprocess an image with random crop, flip, and normalization for training', 'create a TensorFlow dataset from text tags with BERT tokenization and batching', 'build a FLIP model for fast language-image pre-training with masking using JAX and Flax', 'create a VisionTransformer encoder module with patch embedding, positional encoding, and random masking for image inputs', 'create a LanguageTransformer encoder module with token embedding and positional encoding for text sequence inputs', 'review the Encoder1DBlock transformer encoder layer with multi-head attention, MLP, dropout, and droppath regularization', 'test the compute_contrastive_loss method that calculates image-text contrastive loss with learnable temperature scaling', 'run the FLIP model training and evaluation loop with a given config and workdir', 'build training, validation, and tag data loaders from LAION and ImageNet datasets', 'run a single training step computing gradients and updating model state', 'run an evaluation step computing image-text similarity accuracy against encoded tags', 'run the full evaluation pipeline encoding tags and computing accuracy metrics on ImageNet']
```

Usage

```
{'create_laion_dataset_split': 'create a TensorFlow dataset split from LAION TFRecord files with sharding and batching support', 'parse_laion_tfrecord_example': 'parse a single LAION TFRecord example proto into image, text, and metadata fields', 'preprocess_text_with_bert_tokenizer': 'preprocess text using a BERT tokenizer with padding and optional CLS token prepending', 'preprocess_image_with_augmentation': 'preprocess an image with random crop, flip, and normalization for training', 'create_tags_dataset_split': 'create a TensorFlow dataset from text tags with BERT tokenization and batching'}
```

## File: facebookresearch_flip/models_flip.py

Prompts

```
['create a tf.data.Dataset split from ImageNet validation using TensorFlow Datasets with sharding', 'preprocess raw image bytes for evaluation with center crop, normalization, and dtype conversion', 'build a sharded ImageNet evaluation data pipeline with batching, prefetching, and caching support', 'decode an ImageNet example into image tensor, label, and one-hot encoded label', 'configure TensorFlow dataset threading options with a private threadpool size for parallel processing', 'create a TensorFlow dataset split from LAION TFRecord files with sharding and batching support', 'parse a single LAION TFRecord example proto into image, text, and metadata fields', 'preprocess text using a BERT tokenizer with padding and optional CLS token prepending', 'preprocess an image with random crop, flip, and normalization for training', 'create a TensorFlow dataset from text tags with BERT tokenization and batching', 'build a FLIP model for fast language-image pre-training with masking using JAX and Flax', 'create a VisionTransformer encoder module with patch embedding, positional encoding, and random masking for image inputs', 'create a LanguageTransformer encoder module with token embedding and positional encoding for text sequence inputs', 'review the Encoder1DBlock transformer encoder layer with multi-head attention, MLP, dropout, and droppath regularization', 'test the compute_contrastive_loss method that calculates image-text contrastive loss with learnable temperature scaling', 'run the FLIP model training and evaluation loop with a given config and workdir', 'build training, validation, and tag data loaders from LAION and ImageNet datasets', 'run a single training step computing gradients and updating model state', 'run an evaluation step computing image-text similarity accuracy against encoded tags', 'run the full evaluation pipeline encoding tags and computing accuracy metrics on ImageNet']
```

Usage

```
{'build_FLIP_model': 'build a FLIP model for fast language-image pre-training with masking using JAX and Flax', 'create_VisionTransformer_encoder': 'create a VisionTransformer encoder module with patch embedding, positional encoding, and random masking for image inputs', 'create_LanguageTransformer_encoder': 'create a LanguageTransformer encoder module with token embedding and positional encoding for text sequence inputs', 'review_Encoder1DBlock': 'review the Encoder1DBlock transformer encoder layer with multi-head attention, MLP, dropout, and droppath regularization', 'test_compute_contrastive_loss': 'test the compute_contrastive_loss method that calculates image-text contrastive loss with learnable temperature scaling'}
```

## File: facebookresearch_flip/train.py

Prompts

```
['create a tf.data.Dataset split from ImageNet validation using TensorFlow Datasets with sharding', 'preprocess raw image bytes for evaluation with center crop, normalization, and dtype conversion', 'build a sharded ImageNet evaluation data pipeline with batching, prefetching, and caching support', 'decode an ImageNet example into image tensor, label, and one-hot encoded label', 'configure TensorFlow dataset threading options with a private threadpool size for parallel processing', 'create a TensorFlow dataset split from LAION TFRecord files with sharding and batching support', 'parse a single LAION TFRecord example proto into image, text, and metadata fields', 'preprocess text using a BERT tokenizer with padding and optional CLS token prepending', 'preprocess an image with random crop, flip, and normalization for training', 'create a TensorFlow dataset from text tags with BERT tokenization and batching', 'build a FLIP model for fast language-image pre-training with masking using JAX and Flax', 'create a VisionTransformer encoder module with patch embedding, positional encoding, and random masking for image inputs', 'create a LanguageTransformer encoder module with token embedding and positional encoding for text sequence inputs', 'review the Encoder1DBlock transformer encoder layer with multi-head attention, MLP, dropout, and droppath regularization', 'test the compute_contrastive_loss method that calculates image-text contrastive loss with learnable temperature scaling', 'run the FLIP model training and evaluation loop with a given config and workdir', 'build training, validation, and tag data loaders from LAION and ImageNet datasets', 'run a single training step computing gradients and updating model state', 'run an evaluation step computing image-text similarity accuracy against encoded tags', 'run the full evaluation pipeline encoding tags and computing accuracy metrics on ImageNet']
```

Usage

```
{'run_train_and_evaluate': 'run the FLIP model training and evaluation loop with a given config and workdir', 'build_dataloaders': 'build training, validation, and tag data loaders from LAION and ImageNet datasets', 'run_train_step': 'run a single training step computing gradients and updating model state', 'run_eval_step': 'run an evaluation step computing image-text similarity accuracy against encoded tags', 'run_eval': 'run the full evaluation pipeline encoding tags and computing accuracy metrics on ImageNet'}
```

