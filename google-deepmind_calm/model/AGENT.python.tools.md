# Agent Python Tools

- repo: google-deepmind/calm
- repo_uri: https://github.com/google-deepmind/calm

## File: google-deepmind_calm/model/calm.py

Prompts

```
['build a CALM model by creating a CALMConfig with anchor and augmented models then instantiating CALM', 'create a CALMConfig specifying anchor_model aug_model num_connections and num_heads for cross attention hooks', 'run a forward pass through the CALM model by calling model with input_ids and attention_mask tensors', 'save a trained CALM model to a directory using the save_pretrained method with a save_directory path', 'review the CALM class cross attention hooks that connect anchor and augmented model hidden states', 'test the CALMConfig class with anchor_model aug_model num_connections and num_heads parameters', 'test the CALM model forward pass returns the same output shape as the anchor model', 'test the CALM model connections are set correctly between anchor and aug model layers', 'test the get_hidden_dims utility returns correct hidden dimensions for anchor and aug model layers', 'test the CALM model generate method produces output token ids from input tensor', 'freeze all parameters of a PyTorch model by setting requires_grad to False', 'extract the main output tensor from a PyTorch forward hook output tuple', 'create a CrossAttentionHook with anchor and augmented hidden dimensions and attention heads', 'run the forward pass of a CrossAttentionHook using anchor query and projected augmented key-value', 'create an ExtractHiddenStateHook to capture hidden states from a model layer via forward hook', 'check if CALM connections are valid given anchor and augmenting model layer counts', 'generate evenly spaced layer connections between anchor and augmenting models for CALM', 'retrieve hidden dimensions for a given anchor and augmenting model layer connection', 'review the check_connections function to validate layer index bounds for anchor and augmenting models', 'refactor get_connections to support custom spacing strategies beyond linspace for CALM layer pairing', 'test the check_connections function to validate CALM model layer connection tuples', 'test the get_connections function to verify layer connection generation for CALM models', 'refactor the check_connections function to support additional validation rules for CALM connections', 'review the UtilsTest class and its test methods for the CALM model utility functions']
```

Usage

```
{'build_calm_model': 'build a CALM model by creating a CALMConfig with anchor and augmented models then instantiating CALM', 'create_calm_config': 'create a CALMConfig specifying anchor_model aug_model num_connections and num_heads for cross attention hooks', 'run_calm_forward': 'run a forward pass through the CALM model by calling model with input_ids and attention_mask tensors', 'save_calm_model': 'save a trained CALM model to a directory using the save_pretrained method with a save_directory path', 'review_calm_cross_attention': 'review the CALM class cross attention hooks that connect anchor and augmented model hidden states'}
```

## File: google-deepmind_calm/model/calm_test.py

Prompts

```
['build a CALM model by creating a CALMConfig with anchor and augmented models then instantiating CALM', 'create a CALMConfig specifying anchor_model aug_model num_connections and num_heads for cross attention hooks', 'run a forward pass through the CALM model by calling model with input_ids and attention_mask tensors', 'save a trained CALM model to a directory using the save_pretrained method with a save_directory path', 'review the CALM class cross attention hooks that connect anchor and augmented model hidden states', 'test the CALMConfig class with anchor_model aug_model num_connections and num_heads parameters', 'test the CALM model forward pass returns the same output shape as the anchor model', 'test the CALM model connections are set correctly between anchor and aug model layers', 'test the get_hidden_dims utility returns correct hidden dimensions for anchor and aug model layers', 'test the CALM model generate method produces output token ids from input tensor', 'freeze all parameters of a PyTorch model by setting requires_grad to False', 'extract the main output tensor from a PyTorch forward hook output tuple', 'create a CrossAttentionHook with anchor and augmented hidden dimensions and attention heads', 'run the forward pass of a CrossAttentionHook using anchor query and projected augmented key-value', 'create an ExtractHiddenStateHook to capture hidden states from a model layer via forward hook', 'check if CALM connections are valid given anchor and augmenting model layer counts', 'generate evenly spaced layer connections between anchor and augmenting models for CALM', 'retrieve hidden dimensions for a given anchor and augmenting model layer connection', 'review the check_connections function to validate layer index bounds for anchor and augmenting models', 'refactor get_connections to support custom spacing strategies beyond linspace for CALM layer pairing', 'test the check_connections function to validate CALM model layer connection tuples', 'test the get_connections function to verify layer connection generation for CALM models', 'refactor the check_connections function to support additional validation rules for CALM connections', 'review the UtilsTest class and its test methods for the CALM model utility functions']
```

Usage

```
{'test_CALMConfig': 'test the CALMConfig class with anchor_model aug_model num_connections and num_heads parameters', 'test_CALM_forward': 'test the CALM model forward pass returns the same output shape as the anchor model', 'test_CALM_connections': 'test the CALM model connections are set correctly between anchor and aug model layers', 'test_get_hidden_dims': 'test the get_hidden_dims utility returns correct hidden dimensions for anchor and aug model layers', 'test_CALM_generate': 'test the CALM model generate method produces output token ids from input tensor'}
```

## File: google-deepmind_calm/model/layers.py

Prompts

```
['build a CALM model by creating a CALMConfig with anchor and augmented models then instantiating CALM', 'create a CALMConfig specifying anchor_model aug_model num_connections and num_heads for cross attention hooks', 'run a forward pass through the CALM model by calling model with input_ids and attention_mask tensors', 'save a trained CALM model to a directory using the save_pretrained method with a save_directory path', 'review the CALM class cross attention hooks that connect anchor and augmented model hidden states', 'test the CALMConfig class with anchor_model aug_model num_connections and num_heads parameters', 'test the CALM model forward pass returns the same output shape as the anchor model', 'test the CALM model connections are set correctly between anchor and aug model layers', 'test the get_hidden_dims utility returns correct hidden dimensions for anchor and aug model layers', 'test the CALM model generate method produces output token ids from input tensor', 'freeze all parameters of a PyTorch model by setting requires_grad to False', 'extract the main output tensor from a PyTorch forward hook output tuple', 'create a CrossAttentionHook with anchor and augmented hidden dimensions and attention heads', 'run the forward pass of a CrossAttentionHook using anchor query and projected augmented key-value', 'create an ExtractHiddenStateHook to capture hidden states from a model layer via forward hook', 'check if CALM connections are valid given anchor and augmenting model layer counts', 'generate evenly spaced layer connections between anchor and augmenting models for CALM', 'retrieve hidden dimensions for a given anchor and augmenting model layer connection', 'review the check_connections function to validate layer index bounds for anchor and augmenting models', 'refactor get_connections to support custom spacing strategies beyond linspace for CALM layer pairing', 'test the check_connections function to validate CALM model layer connection tuples', 'test the get_connections function to verify layer connection generation for CALM models', 'refactor the check_connections function to support additional validation rules for CALM connections', 'review the UtilsTest class and its test methods for the CALM model utility functions']
```

Usage

```
{'freeze_model': 'freeze all parameters of a PyTorch model by setting requires_grad to False', 'process_hook_args': 'extract the main output tensor from a PyTorch forward hook output tuple', 'create_cross_attention_hook': 'create a CrossAttentionHook with anchor and augmented hidden dimensions and attention heads', 'cross_attention_hook_forward': 'run the forward pass of a CrossAttentionHook using anchor query and projected augmented key-value', 'create_extract_hidden_state_hook': 'create an ExtractHiddenStateHook to capture hidden states from a model layer via forward hook'}
```

## File: google-deepmind_calm/model/utils.py

Prompts

```
['build a CALM model by creating a CALMConfig with anchor and augmented models then instantiating CALM', 'create a CALMConfig specifying anchor_model aug_model num_connections and num_heads for cross attention hooks', 'run a forward pass through the CALM model by calling model with input_ids and attention_mask tensors', 'save a trained CALM model to a directory using the save_pretrained method with a save_directory path', 'review the CALM class cross attention hooks that connect anchor and augmented model hidden states', 'test the CALMConfig class with anchor_model aug_model num_connections and num_heads parameters', 'test the CALM model forward pass returns the same output shape as the anchor model', 'test the CALM model connections are set correctly between anchor and aug model layers', 'test the get_hidden_dims utility returns correct hidden dimensions for anchor and aug model layers', 'test the CALM model generate method produces output token ids from input tensor', 'freeze all parameters of a PyTorch model by setting requires_grad to False', 'extract the main output tensor from a PyTorch forward hook output tuple', 'create a CrossAttentionHook with anchor and augmented hidden dimensions and attention heads', 'run the forward pass of a CrossAttentionHook using anchor query and projected augmented key-value', 'create an ExtractHiddenStateHook to capture hidden states from a model layer via forward hook', 'check if CALM connections are valid given anchor and augmenting model layer counts', 'generate evenly spaced layer connections between anchor and augmenting models for CALM', 'retrieve hidden dimensions for a given anchor and augmenting model layer connection', 'review the check_connections function to validate layer index bounds for anchor and augmenting models', 'refactor get_connections to support custom spacing strategies beyond linspace for CALM layer pairing', 'test the check_connections function to validate CALM model layer connection tuples', 'test the get_connections function to verify layer connection generation for CALM models', 'refactor the check_connections function to support additional validation rules for CALM connections', 'review the UtilsTest class and its test methods for the CALM model utility functions']
```

Usage

```
{'check_connections_validate': 'check if CALM connections are valid given anchor and augmenting model layer counts', 'get_connections_generate': 'generate evenly spaced layer connections between anchor and augmenting models for CALM', 'get_hidden_dims_retrieve': 'retrieve hidden dimensions for a given anchor and augmenting model layer connection', 'review_check_connections': 'review the check_connections function to validate layer index bounds for anchor and augmenting models', 'refactor_get_connections': 'refactor get_connections to support custom spacing strategies beyond linspace for CALM layer pairing'}
```

## File: google-deepmind_calm/model/utils_test.py

Prompts

```
['build a CALM model by creating a CALMConfig with anchor and augmented models then instantiating CALM', 'create a CALMConfig specifying anchor_model aug_model num_connections and num_heads for cross attention hooks', 'run a forward pass through the CALM model by calling model with input_ids and attention_mask tensors', 'save a trained CALM model to a directory using the save_pretrained method with a save_directory path', 'review the CALM class cross attention hooks that connect anchor and augmented model hidden states', 'test the CALMConfig class with anchor_model aug_model num_connections and num_heads parameters', 'test the CALM model forward pass returns the same output shape as the anchor model', 'test the CALM model connections are set correctly between anchor and aug model layers', 'test the get_hidden_dims utility returns correct hidden dimensions for anchor and aug model layers', 'test the CALM model generate method produces output token ids from input tensor', 'freeze all parameters of a PyTorch model by setting requires_grad to False', 'extract the main output tensor from a PyTorch forward hook output tuple', 'create a CrossAttentionHook with anchor and augmented hidden dimensions and attention heads', 'run the forward pass of a CrossAttentionHook using anchor query and projected augmented key-value', 'create an ExtractHiddenStateHook to capture hidden states from a model layer via forward hook', 'check if CALM connections are valid given anchor and augmenting model layer counts', 'generate evenly spaced layer connections between anchor and augmenting models for CALM', 'retrieve hidden dimensions for a given anchor and augmenting model layer connection', 'review the check_connections function to validate layer index bounds for anchor and augmenting models', 'refactor get_connections to support custom spacing strategies beyond linspace for CALM layer pairing', 'test the check_connections function to validate CALM model layer connection tuples', 'test the get_connections function to verify layer connection generation for CALM models', 'refactor the check_connections function to support additional validation rules for CALM connections', 'review the UtilsTest class and its test methods for the CALM model utility functions']
```

Usage

```
{'test_check_connections': 'test the check_connections function to validate CALM model layer connection tuples', 'test_get_connections': 'test the get_connections function to verify layer connection generation for CALM models', 'test_get_hidden_dims': 'test the get_hidden_dims function to verify hidden dimension extraction from CALM model layers', 'refactor_check_connections': 'refactor the check_connections function to support additional validation rules for CALM connections', 'review_utils_test': 'review the UtilsTest class and its test methods for the CALM model utility functions'}
```

