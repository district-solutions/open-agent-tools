# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/models/uma/uma_fast/test_execution_backends.py

Prompts

```
['test UMASFastGPUBackend.validate to verify lmax mmax and merge_mole configuration requirements', 'test umas_fast_pytorch backend produces forces matching the general backend for PBC and non-PBC systems', 'test NodeToEdgeWignerPermuteFunction backward pass correctness using torch.autograd.gradcheck with fast_mode', 'test PermuteWignerInvEdgeToNodeFunction backward pass correctness using torch.autograd.gradcheck with fast_mode', 'test compiled execution modes general and umas_fast_gpu produce results matching non-compiled baseline', 'test the node_to_edge_wigner_permute_launcher function to verify Triton kernel gather and Wigner rotation correctness', 'test the permute_wigner_inv_edge_to_node_launcher function to verify M-to-L permutation and Wigner inverse correctness', 'review the node_to_edge_wigner_permute_launcher function for edge feature gathering and L-to-M permutation logic', 'review the permute_wigner_inv_edge_to_node_launcher function for Wigner inverse matrix application and contiguity assertions', 'summarize the triton_test_utils module containing test-only Triton kernel launchers for UMA model Wigner rotation operations']
```

Usage

```
{'test_UMASFastGPUBackend_validate': 'test UMASFastGPUBackend.validate to verify lmax mmax and merge_mole configuration requirements', 'test_umas_fast_pytorch_forces_match_baseline': 'test umas_fast_pytorch backend produces forces matching the general backend for PBC and non-PBC systems', 'test_node_to_edge_wigner_permute_gradcheck': 'test NodeToEdgeWignerPermuteFunction backward pass correctness using torch.autograd.gradcheck with fast_mode', 'test_permute_wigner_inv_edge_to_node_gradcheck': 'test PermuteWignerInvEdgeToNodeFunction backward pass correctness using torch.autograd.gradcheck with fast_mode', 'test_compiled_backends_match_baseline': 'test compiled execution modes general and umas_fast_gpu produce results matching non-compiled baseline'}
```

## File: facebookresearch_fairchem/tests/core/models/uma/uma_fast/triton_test_utils.py

Prompts

```
['test UMASFastGPUBackend.validate to verify lmax mmax and merge_mole configuration requirements', 'test umas_fast_pytorch backend produces forces matching the general backend for PBC and non-PBC systems', 'test NodeToEdgeWignerPermuteFunction backward pass correctness using torch.autograd.gradcheck with fast_mode', 'test PermuteWignerInvEdgeToNodeFunction backward pass correctness using torch.autograd.gradcheck with fast_mode', 'test compiled execution modes general and umas_fast_gpu produce results matching non-compiled baseline', 'test the node_to_edge_wigner_permute_launcher function to verify Triton kernel gather and Wigner rotation correctness', 'test the permute_wigner_inv_edge_to_node_launcher function to verify M-to-L permutation and Wigner inverse correctness', 'review the node_to_edge_wigner_permute_launcher function for edge feature gathering and L-to-M permutation logic', 'review the permute_wigner_inv_edge_to_node_launcher function for Wigner inverse matrix application and contiguity assertions', 'summarize the triton_test_utils module containing test-only Triton kernel launchers for UMA model Wigner rotation operations']
```

Usage

```
{'test_node_to_edge_wigner_permute_launcher': 'test the node_to_edge_wigner_permute_launcher function to verify Triton kernel gather and Wigner rotation correctness', 'test_permute_wigner_inv_edge_to_node_launcher': 'test the permute_wigner_inv_edge_to_node_launcher function to verify M-to-L permutation and Wigner inverse correctness', 'review_node_to_edge_wigner_permute_launcher': 'review the node_to_edge_wigner_permute_launcher function for edge feature gathering and L-to-M permutation logic', 'review_permute_wigner_inv_edge_to_node_launcher': 'review the permute_wigner_inv_edge_to_node_launcher function for Wigner inverse matrix application and contiguity assertions', 'summarize_triton_test_utils': 'summarize the triton_test_utils module containing test-only Triton kernel launchers for UMA model Wigner rotation operations'}
```

