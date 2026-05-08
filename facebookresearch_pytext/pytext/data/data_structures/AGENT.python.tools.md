# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/data/data_structures/annotation.py

Prompts

```
['build an Annotation parse tree from a seqlogical string with intent and slot labels', 'validate an Annotation tree structure checking correct nesting of intents, slots, and tokens', 'build a parse tree incrementally using TreeBuilder with SHIFT, REDUCE, and nonterminal actions', 'convert an Annotation tree into a list of SHIFT and REDUCE actions for sequence modeling', 'convert action indices and vocabulary into a list of action-label tuples for decoding', 'create a Span NamedTuple with start and end integer positions for a node in an intent-slot tree', 'create a Node with a label, Span, optional children set, and optional text for an intent-slot tree', 'compare two Node instances for equality by checking label, span, children, and text attributes', 'get the depth of a Node in the intent-slot tree by recursively computing max child depth plus one', 'build an intent-slot tree by creating parent and child Node instances with Spans and labels']
```

Usage

```
{'build_annotation_tree': 'build an Annotation parse tree from a seqlogical string with intent and slot labels', 'validate_annotation_tree': 'validate an Annotation tree structure checking correct nesting of intents, slots, and tokens', 'build_tree_from_actions': 'build a parse tree incrementally using TreeBuilder with SHIFT, REDUCE, and nonterminal actions', 'convert_tree_to_actions': 'convert an Annotation tree into a list of SHIFT and REDUCE actions for sequence modeling', 'list_actions_from_indices': 'convert action indices and vocabulary into a list of action-label tuples for decoding'}
```

## File: facebookresearch_pytext/pytext/data/data_structures/node.py

Prompts

```
['build an Annotation parse tree from a seqlogical string with intent and slot labels', 'validate an Annotation tree structure checking correct nesting of intents, slots, and tokens', 'build a parse tree incrementally using TreeBuilder with SHIFT, REDUCE, and nonterminal actions', 'convert an Annotation tree into a list of SHIFT and REDUCE actions for sequence modeling', 'convert action indices and vocabulary into a list of action-label tuples for decoding', 'create a Span NamedTuple with start and end integer positions for a node in an intent-slot tree', 'create a Node with a label, Span, optional children set, and optional text for an intent-slot tree', 'compare two Node instances for equality by checking label, span, children, and text attributes', 'get the depth of a Node in the intent-slot tree by recursively computing max child depth plus one', 'build an intent-slot tree by creating parent and child Node instances with Spans and labels']
```

Usage

```
{'create_span_namedtuple': 'create a Span NamedTuple with start and end integer positions for a node in an intent-slot tree', 'create_node_with_span': 'create a Node with a label, Span, optional children set, and optional text for an intent-slot tree', 'compare_nodes_for_equality': 'compare two Node instances for equality by checking label, span, children, and text attributes', 'get_node_depth': 'get the depth of a Node in the intent-slot tree by recursively computing max child depth plus one', 'build_intent_slot_tree': 'build an intent-slot tree by creating parent and child Node instances with Spans and labels'}
```

