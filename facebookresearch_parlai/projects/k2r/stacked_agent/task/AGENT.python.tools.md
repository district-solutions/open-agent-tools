# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/k2r/stacked_agent/task/agents.py

Prompts

```
['build a StackedKnowledgeDialogueAgent that generates knowledge first then dialogue responses using Parlai agents', 'create an OracleKnowledgeAgent that extracts ground truth knowledge from Wizard of Wikipedia or Natural Questions observations', 'extract named entities, noun chunks, and POS-tagged tokens from a sentence using spaCy', 'find the best supporting sentence from retrieved docs by scoring recall against a question and answer', 'filter beam search candidates to prefer responses containing knowledge, no questions, and no self-references']
```

Usage

```
{'build_stacked_knowledge_dialogue_agent': 'build a StackedKnowledgeDialogueAgent that generates knowledge first then dialogue responses using Parlai agents', 'create_oracle_knowledge_agent': 'create an OracleKnowledgeAgent that extracts ground truth knowledge from Wizard of Wikipedia or Natural Questions observations', 'extract_entities_from_text': 'extract named entities, noun chunks, and POS-tagged tokens from a sentence using spaCy', 'find_supporting_sentence': 'find the best supporting sentence from retrieved docs by scoring recall against a question and answer', 'filter_dialogue_beams': 'filter beam search candidates to prefer responses containing knowledge, no questions, and no self-references'}
```

