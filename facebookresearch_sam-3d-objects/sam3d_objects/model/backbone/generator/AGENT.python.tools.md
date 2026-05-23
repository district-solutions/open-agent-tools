# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/generator/base.py

Prompts

```
['review the Base class which is a PyTorch nn.Module base for generator models with seed management', 'build a subclass of Base that implements generate_iter and loss methods for a custom generator', 'test the Base class seed setter to verify it creates a torch.Generator with manual seed', 'test the Base class random_generator property to verify it returns the internal torch.Generator', 'run the Base forward method which delegates to generate and returns the final generated tensor', 'build a ClassifierFreeGuidance wrapper around a diffusion backbone with configurable unconditional handling and CFG strength', 'create a PointmapCFG module that applies classifier-free guidance with separate pointmap and unconditional strength parameters', 'test the ClassifierFreeGuidance forward pass in training mode with random unconditional dropout probability', 'refactor the unconditional handling strategy to switch between zeros, discard, drop_tensors, or add_flag modes', 'summarize the get_strength function that computes CFG strength based on timestep and optional interval constraints']
```

Usage

```
{'review_Base_class': 'review the Base class which is a PyTorch nn.Module base for generator models with seed management', 'build_Base_subclass': 'build a subclass of Base that implements generate_iter and loss methods for a custom generator', 'test_Base_seed': 'test the Base class seed setter to verify it creates a torch.Generator with manual seed', 'test_Base_random_generator': 'test the Base class random_generator property to verify it returns the internal torch.Generator', 'run_Base_forward': 'run the Base forward method which delegates to generate and returns the final generated tensor'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/generator/classifier_free_guidance.py

Prompts

```
['review the Base class which is a PyTorch nn.Module base for generator models with seed management', 'build a subclass of Base that implements generate_iter and loss methods for a custom generator', 'test the Base class seed setter to verify it creates a torch.Generator with manual seed', 'test the Base class random_generator property to verify it returns the internal torch.Generator', 'run the Base forward method which delegates to generate and returns the final generated tensor', 'build a ClassifierFreeGuidance wrapper around a diffusion backbone with configurable unconditional handling and CFG strength', 'create a PointmapCFG module that applies classifier-free guidance with separate pointmap and unconditional strength parameters', 'test the ClassifierFreeGuidance forward pass in training mode with random unconditional dropout probability', 'refactor the unconditional handling strategy to switch between zeros, discard, drop_tensors, or add_flag modes', 'summarize the get_strength function that computes CFG strength based on timestep and optional interval constraints']
```

Usage

```
{'build_ClassifierFreeGuidance': 'build a ClassifierFreeGuidance wrapper around a diffusion backbone with configurable unconditional handling and CFG strength', 'create_PointmapCFG': 'create a PointmapCFG module that applies classifier-free guidance with separate pointmap and unconditional strength parameters', 'test_ClassifierFreeGuidance_forward': 'test the ClassifierFreeGuidance forward pass in training mode with random unconditional dropout probability', 'refactor_unconditional_handling': 'refactor the unconditional handling strategy to switch between zeros, discard, drop_tensors, or add_flag modes', 'summarize_get_strength': 'summarize the get_strength function that computes CFG strength based on timestep and optional interval constraints'}
```

