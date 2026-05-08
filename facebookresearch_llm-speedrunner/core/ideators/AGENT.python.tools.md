# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/core/ideators/base.py

Prompts

```
['ideate a hypothesis for improving code files given a task description and workspace version', 'create an Ideator agent that generates code improvement hypotheses using an LLM', 'ideate a debugging hypothesis for code with bug history and ignore ideas', 'ideate a hypothesis using external knowledge and history alongside code files', 'act on an instruction prompt and validate the LLM response as structured JSON', 'create a DummyIdeator agent that passes through knowledge strings without any model interactions', 'use DummyIdeator ideate method to split a knowledge string into individual lines and return metadata', 'call DummyIdeator ideate with no knowledge to get an empty list and dummy metadata dict', 'review the DummyIdeator class that extends Agent and implements a pass-through ideate method', 'refactor the DummyIdeator ideate method to add custom processing before passing through knowledge']
```

Usage

```
{'ideate_hypothesis_from_code': 'ideate a hypothesis for improving code files given a task description and workspace version', 'create_ideator_agent': 'create an Ideator agent that generates code improvement hypotheses using an LLM', 'ideate_with_debug_context': 'ideate a debugging hypothesis for code with bug history and ignore ideas', 'ideate_with_knowledge': 'ideate a hypothesis using external knowledge and history alongside code files', 'act_with_validator': 'act on an instruction prompt and validate the LLM response as structured JSON'}
```

## File: facebookresearch_llm-speedrunner/core/ideators/dummy_ideator.py

Prompts

```
['ideate a hypothesis for improving code files given a task description and workspace version', 'create an Ideator agent that generates code improvement hypotheses using an LLM', 'ideate a debugging hypothesis for code with bug history and ignore ideas', 'ideate a hypothesis using external knowledge and history alongside code files', 'act on an instruction prompt and validate the LLM response as structured JSON', 'create a DummyIdeator agent that passes through knowledge strings without any model interactions', 'use DummyIdeator ideate method to split a knowledge string into individual lines and return metadata', 'call DummyIdeator ideate with no knowledge to get an empty list and dummy metadata dict', 'review the DummyIdeator class that extends Agent and implements a pass-through ideate method', 'refactor the DummyIdeator ideate method to add custom processing before passing through knowledge']
```

Usage

```
{'ideate_pass_through_knowledge': 'create a DummyIdeator agent that passes through knowledge strings without any model interactions', 'ideate_split_knowledge_lines': 'use DummyIdeator ideate method to split a knowledge string into individual lines and return metadata', 'ideate_empty_knowledge': 'call DummyIdeator ideate with no knowledge to get an empty list and dummy metadata dict', 'review_DummyIdeator_class': 'review the DummyIdeator class that extends Agent and implements a pass-through ideate method', 'refactor_DummyIdeator_ideate': 'refactor the DummyIdeator ideate method to add custom processing before passing through knowledge'}
```

