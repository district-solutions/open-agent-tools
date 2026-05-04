# Agent Python Tools

- repo: google-deepmind/ai-foundations
- repo_uri: https://github.com/google-deepmind/ai-foundations

## File: google-deepmind_ai-foundations/ai_foundations/training/callbacks.py

Prompts

```
['create a TextGenerator Keras callback to generate sample text from a language model during training', 'use the TextGenerator on_epoch_end method to generate and print text after each training epoch', 'create a CustomAccuracyPrinter Keras callback to print training and validation metrics during model training', 'use the CustomAccuracyPrinter on_epoch_end method to print epoch loss and accuracy metrics', 'review the TextGenerator class and how it uses JAX random decoding to sample tokens', 'create a CustomMaskPadLoss instance with a pad_token_id to ignore padding tokens during training', 'use the call method of CustomMaskPadLoss to compute masked sparse categorical crossentropy loss', 'review the CustomMaskPadLoss class to understand how it wraps SparseCategoricalCrossentropy with padding token masking', 'build a Keras model that uses CustomMaskPadLoss as its loss function for sequence-based tasks', 'test the CustomMaskPadLoss class by passing y_true and y_pred arrays to its call method', 'create a compiled Keras transformer model with configurable embedding dim, attention heads, and blocks', 'build a transformer model using the SGD optimizer with a custom learning rate', 'create a transformer model using the AdamW optimizer with weight decay for training', 'get an AdamW optimizer instance with a specified learning rate and default weight decay', 'get an SGD optimizer instance with a specified learning rate for model training']
```

Usage

```
{'create_TextGenerator_callback': 'create a TextGenerator Keras callback to generate sample text from a language model during training', 'use_TextGenerator_on_epoch_end': 'use the TextGenerator on_epoch_end method to generate and print text after each training epoch', 'create_CustomAccuracyPrinter_callback': 'create a CustomAccuracyPrinter Keras callback to print training and validation metrics during model training', 'use_CustomAccuracyPrinter_on_epoch_end': 'use the CustomAccuracyPrinter on_epoch_end method to print epoch loss and accuracy metrics', 'review_TextGenerator_random_decoding': 'review the TextGenerator class and how it uses JAX random decoding to sample tokens'}
```

## File: google-deepmind_ai-foundations/ai_foundations/training/losses.py

Prompts

```
['create a TextGenerator Keras callback to generate sample text from a language model during training', 'use the TextGenerator on_epoch_end method to generate and print text after each training epoch', 'create a CustomAccuracyPrinter Keras callback to print training and validation metrics during model training', 'use the CustomAccuracyPrinter on_epoch_end method to print epoch loss and accuracy metrics', 'review the TextGenerator class and how it uses JAX random decoding to sample tokens', 'create a CustomMaskPadLoss instance with a pad_token_id to ignore padding tokens during training', 'use the call method of CustomMaskPadLoss to compute masked sparse categorical crossentropy loss', 'review the CustomMaskPadLoss class to understand how it wraps SparseCategoricalCrossentropy with padding token masking', 'build a Keras model that uses CustomMaskPadLoss as its loss function for sequence-based tasks', 'test the CustomMaskPadLoss class by passing y_true and y_pred arrays to its call method', 'create a compiled Keras transformer model with configurable embedding dim, attention heads, and blocks', 'build a transformer model using the SGD optimizer with a custom learning rate', 'create a transformer model using the AdamW optimizer with weight decay for training', 'get an AdamW optimizer instance with a specified learning rate and default weight decay', 'get an SGD optimizer instance with a specified learning rate for model training']
```

Usage

```
{'create_custom_mask_pad_loss': 'create a CustomMaskPadLoss instance with a pad_token_id to ignore padding tokens during training', 'use_custom_mask_pad_loss_call': 'use the call method of CustomMaskPadLoss to compute masked sparse categorical crossentropy loss', 'review_custom_mask_pad_loss': 'review the CustomMaskPadLoss class to understand how it wraps SparseCategoricalCrossentropy with padding token masking', 'build_keras_model_with_custom_loss': 'build a Keras model that uses CustomMaskPadLoss as its loss function for sequence-based tasks', 'test_custom_mask_pad_loss': 'test the CustomMaskPadLoss class by passing y_true and y_pred arrays to its call method'}
```

## File: google-deepmind_ai-foundations/ai_foundations/training/model.py

Prompts

```
['create a TextGenerator Keras callback to generate sample text from a language model during training', 'use the TextGenerator on_epoch_end method to generate and print text after each training epoch', 'create a CustomAccuracyPrinter Keras callback to print training and validation metrics during model training', 'use the CustomAccuracyPrinter on_epoch_end method to print epoch loss and accuracy metrics', 'review the TextGenerator class and how it uses JAX random decoding to sample tokens', 'create a CustomMaskPadLoss instance with a pad_token_id to ignore padding tokens during training', 'use the call method of CustomMaskPadLoss to compute masked sparse categorical crossentropy loss', 'review the CustomMaskPadLoss class to understand how it wraps SparseCategoricalCrossentropy with padding token masking', 'build a Keras model that uses CustomMaskPadLoss as its loss function for sequence-based tasks', 'test the CustomMaskPadLoss class by passing y_true and y_pred arrays to its call method', 'create a compiled Keras transformer model with configurable embedding dim, attention heads, and blocks', 'build a transformer model using the SGD optimizer with a custom learning rate', 'create a transformer model using the AdamW optimizer with weight decay for training', 'get an AdamW optimizer instance with a specified learning rate and default weight decay', 'get an SGD optimizer instance with a specified learning rate for model training']
```

Usage

```
{'create_transformer_model': 'create a compiled Keras transformer model with configurable embedding dim, attention heads, and blocks', 'build_model_with_sgd': 'build a transformer model using the SGD optimizer with a custom learning rate', 'create_model_with_adamw': 'create a transformer model using the AdamW optimizer with weight decay for training', 'get_optimizer_adamw': 'get an AdamW optimizer instance with a specified learning rate and default weight decay', 'get_optimizer_sgd': 'get an SGD optimizer instance with a specified learning rate for model training'}
```

