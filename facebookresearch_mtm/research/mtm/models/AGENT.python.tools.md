# Agent Python Tools

- repo: facebookresearch/mtm
- repo_uri: https://github.com/facebookresearch/mtm

## File: facebookresearch_mtm/research/mtm/models/mlp_model.py

Prompts

```
['create a multi-layer perceptron with configurable hidden dimensions, layers, and activation functions', 'create an MLPConfig dataclass with embedding size, layer count, and task type settings', 'build an MLP behavior cloning model for tasks like bc, id, fd, or rcbc', 'run the MLP_BC forward pass on trajectory data with optional loss computation', 'evaluate the MLP_BC model on an environment using behavior cloning or inverse dynamics', 'build a masked trajectory model using MTMConfig and MTM class with transformer encoder and decoder', 'create an MTMConfig dataclass to configure embedding dimensions, heads, layers, dropout, and normalization', 'run the MTM forward pass on trajectories and masks to get reconstructed trajectory predictions', 'test the forward_loss static method to compute MSE or cross-entropy loss on masked trajectory targets', 'review the mask_git_forward method that performs iterative MaskGIT-style decoding with temperature sampling']
```

Usage

```
{'create_MLP': 'create a multi-layer perceptron with configurable hidden dimensions, layers, and activation functions', 'create_MLPConfig': 'create an MLPConfig dataclass with embedding size, layer count, and task type settings', 'create_MLP_BC': 'build an MLP behavior cloning model for tasks like bc, id, fd, or rcbc', 'run_MLP_BC_forward': 'run the MLP_BC forward pass on trajectory data with optional loss computation', 'run_MLP_BC_evaluate': 'evaluate the MLP_BC model on an environment using behavior cloning or inverse dynamics'}
```

## File: facebookresearch_mtm/research/mtm/models/mtm_model.py

Prompts

```
['create a multi-layer perceptron with configurable hidden dimensions, layers, and activation functions', 'create an MLPConfig dataclass with embedding size, layer count, and task type settings', 'build an MLP behavior cloning model for tasks like bc, id, fd, or rcbc', 'run the MLP_BC forward pass on trajectory data with optional loss computation', 'evaluate the MLP_BC model on an environment using behavior cloning or inverse dynamics', 'build a masked trajectory model using MTMConfig and MTM class with transformer encoder and decoder', 'create an MTMConfig dataclass to configure embedding dimensions, heads, layers, dropout, and normalization', 'run the MTM forward pass on trajectories and masks to get reconstructed trajectory predictions', 'test the forward_loss static method to compute MSE or cross-entropy loss on masked trajectory targets', 'review the mask_git_forward method that performs iterative MaskGIT-style decoding with temperature sampling']
```

Usage

```
{'build_MTM_model': 'build a masked trajectory model using MTMConfig and MTM class with transformer encoder and decoder', 'create_MTMConfig': 'create an MTMConfig dataclass to configure embedding dimensions, heads, layers, dropout, and normalization', 'run_forward_MTM': 'run the MTM forward pass on trajectories and masks to get reconstructed trajectory predictions', 'test_forward_loss': 'test the forward_loss static method to compute MSE or cross-entropy loss on masked trajectory targets', 'review_mask_git_forward': 'review the mask_git_forward method that performs iterative MaskGIT-style decoding with temperature sampling'}
```

