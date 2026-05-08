# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/cmu_dog/agents.py

Prompts

```
['build a Parlai DialogTeacher for the CMU document grounded conversations dataset with knowledge grounding', 'test the _collapse_multi_msgs function to concatenate consecutive messages from the same user in a conversation history', 'refactor the _article_section_to_text function to serialize a wiki article section dict into delimited key-value text', 'review the PrependKnowledgeToMessageMutator class that prepends available knowledge tokens to a message text field', 'summarize the KnowledgeWhenUpdatedMutator class that only includes knowledge in messages when it changes across an episode', 'build the CMU-DoG dataset by downloading, consolidating, deduplicating, and splitting conversations into seen and unseen sets', 'consolidate all WikiData JSON files into a single wiki_data.json indexed by wikiDocumentIdx', 'consolidate conversation JSON files across train, valid, and test splits into separate consolidated files', 'build deduplicated train, valid, and test splits by removing conversations that appear in multiple splits', 'split deduplicated conversations into train, valid, test_seen, and test_unseen sets using an 80:10:5:5 ratio']
```

Usage

```
{'build_CMUDocumentGroundedConversationsTeacher': 'build a Parlai DialogTeacher for the CMU document grounded conversations dataset with knowledge grounding', 'test_collapse_multi_msgs': 'test the _collapse_multi_msgs function to concatenate consecutive messages from the same user in a conversation history', 'refactor_article_section_to_text': 'refactor the _article_section_to_text function to serialize a wiki article section dict into delimited key-value text', 'review_PrependKnowledgeToMessageMutator': 'review the PrependKnowledgeToMessageMutator class that prepends available knowledge tokens to a message text field', 'summarize_KnowledgeWhenUpdatedMutator': 'summarize the KnowledgeWhenUpdatedMutator class that only includes knowledge in messages when it changes across an episode'}
```

## File: facebookresearch_parlai/parlai/tasks/cmu_dog/build.py

Prompts

```
['build a Parlai DialogTeacher for the CMU document grounded conversations dataset with knowledge grounding', 'test the _collapse_multi_msgs function to concatenate consecutive messages from the same user in a conversation history', 'refactor the _article_section_to_text function to serialize a wiki article section dict into delimited key-value text', 'review the PrependKnowledgeToMessageMutator class that prepends available knowledge tokens to a message text field', 'summarize the KnowledgeWhenUpdatedMutator class that only includes knowledge in messages when it changes across an episode', 'build the CMU-DoG dataset by downloading, consolidating, deduplicating, and splitting conversations into seen and unseen sets', 'consolidate all WikiData JSON files into a single wiki_data.json indexed by wikiDocumentIdx', 'consolidate conversation JSON files across train, valid, and test splits into separate consolidated files', 'build deduplicated train, valid, and test splits by removing conversations that appear in multiple splits', 'split deduplicated conversations into train, valid, test_seen, and test_unseen sets using an 80:10:5:5 ratio']
```

Usage

```
{'build_cmu_dog_dataset': 'build the CMU-DoG dataset by downloading, consolidating, deduplicating, and splitting conversations into seen and unseen sets', 'consolidate_wiki_data': 'consolidate all WikiData JSON files into a single wiki_data.json indexed by wikiDocumentIdx', 'consolidate_convos': 'consolidate conversation JSON files across train, valid, and test splits into separate consolidated files', 'build_deduped_split': 'build deduplicated train, valid, and test splits by removing conversations that appear in multiple splits', 'split_into_seen_unseen': 'split deduplicated conversations into train, valid, test_seen, and test_unseen sets using an 80:10:5:5 ratio'}
```

