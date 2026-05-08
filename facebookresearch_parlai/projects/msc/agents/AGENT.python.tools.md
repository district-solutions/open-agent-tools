# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/msc/agents/long_rag.py

Prompts

```
['build a LongRagModel that uses ShiftInvariantRagEncoder for retrieval-augmented generation', 'build a LongFidModel with DDP compatibility and shift-invariant encoder support', 'create a ShiftInvariantRagEncoder with optional embedding and padding index configuration', 'configure a LongRagAgent with transformer variant generator and max memories settings', 'build a LongFidAgent that constructs T5FidModel or LongFidModel based on generation model', 'build a TransformerVariantAgent that swaps the encoder with a ShiftInvariantEncoder for long context', 'create a ShiftInvariantEncoder that extends TransformerEncoder with shift-invariant position embeddings', 'test the rearrange_positions method to verify shift-invariant position computation for long sequences', 'review the forward_embedding method to understand how position embeddings are computed and rearranged', 'refactor the add_cmdline_args method to add custom n-positions-init argument for the transformer agent', 'build a MemoryRagAgent subclass to provide memory vectors as model inputs for read/write memory access', 'build a MemoryLongRagAgent that combines MemoryRagAgent with LongRagAgent using a ShiftInvariantEncoder', 'build a MemoryLongFidModel with frozen long-term memory encoders and retriever for DDP compatibility', 'build a MemoryLongFidAgent that combines LongFidAgent with MemoryRagAgent for fiducial-based memory retrieval', 'review the _set_memory_vec method to understand how memories are tokenized and filtered by extractor phrases']
```

Usage

```
{'build_long_rag_model': 'build a LongRagModel that uses ShiftInvariantRagEncoder for retrieval-augmented generation', 'build_long_fid_model': 'build a LongFidModel with DDP compatibility and shift-invariant encoder support', 'create_shift_invariant_rag_encoder': 'create a ShiftInvariantRagEncoder with optional embedding and padding index configuration', 'configure_long_rag_agent': 'configure a LongRagAgent with transformer variant generator and max memories settings', 'build_long_fid_agent': 'build a LongFidAgent that constructs T5FidModel or LongFidModel based on generation model'}
```

## File: facebookresearch_parlai/projects/msc/agents/long_tga.py

Prompts

```
['build a LongRagModel that uses ShiftInvariantRagEncoder for retrieval-augmented generation', 'build a LongFidModel with DDP compatibility and shift-invariant encoder support', 'create a ShiftInvariantRagEncoder with optional embedding and padding index configuration', 'configure a LongRagAgent with transformer variant generator and max memories settings', 'build a LongFidAgent that constructs T5FidModel or LongFidModel based on generation model', 'build a TransformerVariantAgent that swaps the encoder with a ShiftInvariantEncoder for long context', 'create a ShiftInvariantEncoder that extends TransformerEncoder with shift-invariant position embeddings', 'test the rearrange_positions method to verify shift-invariant position computation for long sequences', 'review the forward_embedding method to understand how position embeddings are computed and rearranged', 'refactor the add_cmdline_args method to add custom n-positions-init argument for the transformer agent', 'build a MemoryRagAgent subclass to provide memory vectors as model inputs for read/write memory access', 'build a MemoryLongRagAgent that combines MemoryRagAgent with LongRagAgent using a ShiftInvariantEncoder', 'build a MemoryLongFidModel with frozen long-term memory encoders and retriever for DDP compatibility', 'build a MemoryLongFidAgent that combines LongFidAgent with MemoryRagAgent for fiducial-based memory retrieval', 'review the _set_memory_vec method to understand how memories are tokenized and filtered by extractor phrases']
```

Usage

```
{'build_transformer_variant_agent': 'build a TransformerVariantAgent that swaps the encoder with a ShiftInvariantEncoder for long context', 'create_shift_invariant_encoder': 'create a ShiftInvariantEncoder that extends TransformerEncoder with shift-invariant position embeddings', 'test_rearrange_positions': 'test the rearrange_positions method to verify shift-invariant position computation for long sequences', 'review_forward_embedding': 'review the forward_embedding method to understand how position embeddings are computed and rearranged', 'refactor_add_cmdline_args': 'refactor the add_cmdline_args method to add custom n-positions-init argument for the transformer agent'}
```

## File: facebookresearch_parlai/projects/msc/agents/memory_agent.py

Prompts

```
['build a LongRagModel that uses ShiftInvariantRagEncoder for retrieval-augmented generation', 'build a LongFidModel with DDP compatibility and shift-invariant encoder support', 'create a ShiftInvariantRagEncoder with optional embedding and padding index configuration', 'configure a LongRagAgent with transformer variant generator and max memories settings', 'build a LongFidAgent that constructs T5FidModel or LongFidModel based on generation model', 'build a TransformerVariantAgent that swaps the encoder with a ShiftInvariantEncoder for long context', 'create a ShiftInvariantEncoder that extends TransformerEncoder with shift-invariant position embeddings', 'test the rearrange_positions method to verify shift-invariant position computation for long sequences', 'review the forward_embedding method to understand how position embeddings are computed and rearranged', 'refactor the add_cmdline_args method to add custom n-positions-init argument for the transformer agent', 'build a MemoryRagAgent subclass to provide memory vectors as model inputs for read/write memory access', 'build a MemoryLongRagAgent that combines MemoryRagAgent with LongRagAgent using a ShiftInvariantEncoder', 'build a MemoryLongFidModel with frozen long-term memory encoders and retriever for DDP compatibility', 'build a MemoryLongFidAgent that combines LongFidAgent with MemoryRagAgent for fiducial-based memory retrieval', 'review the _set_memory_vec method to understand how memories are tokenized and filtered by extractor phrases']
```

Usage

```
{'build_memory_rag_agent': 'build a MemoryRagAgent subclass to provide memory vectors as model inputs for read/write memory access', 'build_memory_long_rag_agent': 'build a MemoryLongRagAgent that combines MemoryRagAgent with LongRagAgent using a ShiftInvariantEncoder', 'build_memory_long_fid_model': 'build a MemoryLongFidModel with frozen long-term memory encoders and retriever for DDP compatibility', 'build_memory_long_fid_agent': 'build a MemoryLongFidAgent that combines LongFidAgent with MemoryRagAgent for fiducial-based memory retrieval', 'review_set_memory_vec': 'review the _set_memory_vec method to understand how memories are tokenized and filtered by extractor phrases'}
```

