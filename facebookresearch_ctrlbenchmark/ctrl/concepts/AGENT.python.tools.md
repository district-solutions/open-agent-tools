# Agent Python Tools

- repo: facebookresearch/ctrlbenchmark
- repo_uri: https://github.com/facebookresearch/ctrlbenchmark

## File: facebookresearch_ctrlbenchmark/ctrl/concepts/concept.py

Prompts

```
['create a subclass of Concept that implements init_samples to initialize concept data', 'create a ComposedConcept from a list of Concept objects with custom sampling weights', 'get the stored samples from a Concept instance using the get_samples method', 'get the flattened list of atomic concepts from a ComposedConcept instance', 'compute an MD5-based hash of a Concept using its descriptor string', 'build a ConceptTree with specified levels, children, and samples per concept for hierarchical concept representation', 'get N compatible concepts from the tree excluding specified concepts and optionally filtering leaf nodes only', 'get the closest category pairs by computing pairwise Wu-Palmer similarity between concepts in each category', 'draw the concept tree as a PyDot graph with optional highlighted concepts colored by group', 'split a category into subcategories based on the lowest common ancestor of concepts in the category']
```

Usage

```
{'create_Concept_subclass': 'create a subclass of Concept that implements init_samples to initialize concept data', 'create_ComposedConcept_with_weights': 'create a ComposedConcept from a list of Concept objects with custom sampling weights', 'get_samples_from_Concept': 'get the stored samples from a Concept instance using the get_samples method', 'get_atomic_concepts_from_composed': 'get the flattened list of atomic concepts from a ComposedConcept instance', 'hash_Concept_by_descriptor': 'compute an MD5-based hash of a Concept using its descriptor string'}
```

## File: facebookresearch_ctrlbenchmark/ctrl/concepts/concept_tree.py

Prompts

```
['create a subclass of Concept that implements init_samples to initialize concept data', 'create a ComposedConcept from a list of Concept objects with custom sampling weights', 'get the stored samples from a Concept instance using the get_samples method', 'get the flattened list of atomic concepts from a ComposedConcept instance', 'compute an MD5-based hash of a Concept using its descriptor string', 'build a ConceptTree with specified levels, children, and samples per concept for hierarchical concept representation', 'get N compatible concepts from the tree excluding specified concepts and optionally filtering leaf nodes only', 'get the closest category pairs by computing pairwise Wu-Palmer similarity between concepts in each category', 'draw the concept tree as a PyDot graph with optional highlighted concepts colored by group', 'split a category into subcategories based on the lowest common ancestor of concepts in the category']
```

Usage

```
{'build_concept_tree': 'build a ConceptTree with specified levels, children, and samples per concept for hierarchical concept representation', 'get_compatible_concepts': 'get N compatible concepts from the tree excluding specified concepts and optionally filtering leaf nodes only', 'get_closest_categories': 'get the closest category pairs by computing pairwise Wu-Palmer similarity between concepts in each category', 'draw_tree': 'draw the concept tree as a PyDot graph with optional highlighted concepts colored by group', 'split_category': 'split a category into subcategories based on the lowest common ancestor of concepts in the category'}
```

