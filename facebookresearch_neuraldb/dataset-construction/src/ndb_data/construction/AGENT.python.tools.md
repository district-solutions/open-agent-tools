# Agent Python Tools

- repo: facebookresearch/neuraldb
- repo_uri: https://github.com/facebookresearch/neuraldb

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/construction/make_database_finalize.py

Prompts

```
['run the CLI tool to finalize a NeuralDB dataset by sampling extra facts and writing output JSON', 'run generate_hypotheses to filter S,R,O triples from an instance that match final_templates', 'run bring_extra_facts to pull related KELM-mapped facts for joins and complex queries', 'refactor bring_extra_facts to change how duplicate fact filtering or relation matching works', 'review the main pipeline that samples extra facts, deduplicates, normalizes subjects, and writes finalized databases', 'run the script to generate train dev and test database splits from cache files', 'run normalize_subject to match and replace mixed case subject names in a fact string', 'build train dev and test database splits by sampling subjects objects and relations from cached facts', 'review the normalize_subject function that uses Levenshtein similarity to normalize subject names in facts', 'summarize the make_database_initial script that constructs synthetic databases from cached knowledge graph facts', 'run the python module to build a database initial cache from a JSONL input file', 'generate filtered subject-relation-object hypotheses from an instance using final_templates', 'normalize a subject name in a fact string using Levenshtein similarity matching', 'review the generate_hypotheses function that filters valid hypotheses by relation template', 'summarize the normalize_subject function that matches and replaces entity names in facts', 'build questions and answers for a database by generating derivations from triples and fact templates', 'generate a positive question with its answer from a given question ID and candidate set', 'generate a negatively sampled boolean question by mutating the object in the original hypothesis triple', 'generate question-answer derivations for all subject-relation-object triples using configured question templates', 'run the CLI tool to process an input JSONL database file and output questions with answers and derivations']
```

Usage

```
{'run_make_database_finalize': 'run the CLI tool to finalize a NeuralDB dataset by sampling extra facts and writing output JSON', 'run_generate_hypotheses': 'run generate_hypotheses to filter S,R,O triples from an instance that match final_templates', 'run_bring_extra_facts': 'run bring_extra_facts to pull related KELM-mapped facts for joins and complex queries', 'refactor_bring_extra_facts': 'refactor bring_extra_facts to change how duplicate fact filtering or relation matching works', 'review_make_database_finalize': 'review the main pipeline that samples extra facts, deduplicates, normalizes subjects, and writes finalized databases'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/construction/make_database_initial.py

Prompts

```
['run the CLI tool to finalize a NeuralDB dataset by sampling extra facts and writing output JSON', 'run generate_hypotheses to filter S,R,O triples from an instance that match final_templates', 'run bring_extra_facts to pull related KELM-mapped facts for joins and complex queries', 'refactor bring_extra_facts to change how duplicate fact filtering or relation matching works', 'review the main pipeline that samples extra facts, deduplicates, normalizes subjects, and writes finalized databases', 'run the script to generate train dev and test database splits from cache files', 'run normalize_subject to match and replace mixed case subject names in a fact string', 'build train dev and test database splits by sampling subjects objects and relations from cached facts', 'review the normalize_subject function that uses Levenshtein similarity to normalize subject names in facts', 'summarize the make_database_initial script that constructs synthetic databases from cached knowledge graph facts', 'run the python module to build a database initial cache from a JSONL input file', 'generate filtered subject-relation-object hypotheses from an instance using final_templates', 'normalize a subject name in a fact string using Levenshtein similarity matching', 'review the generate_hypotheses function that filters valid hypotheses by relation template', 'summarize the normalize_subject function that matches and replaces entity names in facts', 'build questions and answers for a database by generating derivations from triples and fact templates', 'generate a positive question with its answer from a given question ID and candidate set', 'generate a negatively sampled boolean question by mutating the object in the original hypothesis triple', 'generate question-answer derivations for all subject-relation-object triples using configured question templates', 'run the CLI tool to process an input JSONL database file and output questions with answers and derivations']
```

Usage

```
{'run_make_database_initial': 'run the script to generate train dev and test database splits from cache files', 'run_normalize_subject': 'run normalize_subject to match and replace mixed case subject names in a fact string', 'build_database_splits': 'build train dev and test database splits by sampling subjects objects and relations from cached facts', 'review_normalize_subject': 'review the normalize_subject function that uses Levenshtein similarity to normalize subject names in facts', 'summarize_make_database_initial': 'summarize the make_database_initial script that constructs synthetic databases from cached knowledge graph facts'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/construction/make_database_initial_cache.py

Prompts

```
['run the CLI tool to finalize a NeuralDB dataset by sampling extra facts and writing output JSON', 'run generate_hypotheses to filter S,R,O triples from an instance that match final_templates', 'run bring_extra_facts to pull related KELM-mapped facts for joins and complex queries', 'refactor bring_extra_facts to change how duplicate fact filtering or relation matching works', 'review the main pipeline that samples extra facts, deduplicates, normalizes subjects, and writes finalized databases', 'run the script to generate train dev and test database splits from cache files', 'run normalize_subject to match and replace mixed case subject names in a fact string', 'build train dev and test database splits by sampling subjects objects and relations from cached facts', 'review the normalize_subject function that uses Levenshtein similarity to normalize subject names in facts', 'summarize the make_database_initial script that constructs synthetic databases from cached knowledge graph facts', 'run the python module to build a database initial cache from a JSONL input file', 'generate filtered subject-relation-object hypotheses from an instance using final_templates', 'normalize a subject name in a fact string using Levenshtein similarity matching', 'review the generate_hypotheses function that filters valid hypotheses by relation template', 'summarize the normalize_subject function that matches and replaces entity names in facts', 'build questions and answers for a database by generating derivations from triples and fact templates', 'generate a positive question with its answer from a given question ID and candidate set', 'generate a negatively sampled boolean question by mutating the object in the original hypothesis triple', 'generate question-answer derivations for all subject-relation-object triples using configured question templates', 'run the CLI tool to process an input JSONL database file and output questions with answers and derivations']
```

Usage

```
{'run_make_database_initial_cache': 'run the python module to build a database initial cache from a JSONL input file', 'generate_hypotheses': 'generate filtered subject-relation-object hypotheses from an instance using final_templates', 'normalize_subject': 'normalize a subject name in a fact string using Levenshtein similarity matching', 'review_generate_hypotheses': 'review the generate_hypotheses function that filters valid hypotheses by relation template', 'summarize_normalize_subject': 'summarize the normalize_subject function that matches and replaces entity names in facts'}
```

## File: facebookresearch_neuraldb/dataset-construction/src/ndb_data/construction/make_questions.py

Prompts

```
['run the CLI tool to finalize a NeuralDB dataset by sampling extra facts and writing output JSON', 'run generate_hypotheses to filter S,R,O triples from an instance that match final_templates', 'run bring_extra_facts to pull related KELM-mapped facts for joins and complex queries', 'refactor bring_extra_facts to change how duplicate fact filtering or relation matching works', 'review the main pipeline that samples extra facts, deduplicates, normalizes subjects, and writes finalized databases', 'run the script to generate train dev and test database splits from cache files', 'run normalize_subject to match and replace mixed case subject names in a fact string', 'build train dev and test database splits by sampling subjects objects and relations from cached facts', 'review the normalize_subject function that uses Levenshtein similarity to normalize subject names in facts', 'summarize the make_database_initial script that constructs synthetic databases from cached knowledge graph facts', 'run the python module to build a database initial cache from a JSONL input file', 'generate filtered subject-relation-object hypotheses from an instance using final_templates', 'normalize a subject name in a fact string using Levenshtein similarity matching', 'review the generate_hypotheses function that filters valid hypotheses by relation template', 'summarize the normalize_subject function that matches and replaces entity names in facts', 'build questions and answers for a database by generating derivations from triples and fact templates', 'generate a positive question with its answer from a given question ID and candidate set', 'generate a negatively sampled boolean question by mutating the object in the original hypothesis triple', 'generate question-answer derivations for all subject-relation-object triples using configured question templates', 'run the CLI tool to process an input JSONL database file and output questions with answers and derivations']
```

Usage

```
{'build_questions_for_db': 'build questions and answers for a database by generating derivations from triples and fact templates', 'generate_positive_question': 'generate a positive question with its answer from a given question ID and candidate set', 'generate_negative_bool': 'generate a negatively sampled boolean question by mutating the object in the original hypothesis triple', 'generate_derivations': 'generate question-answer derivations for all subject-relation-object triples using configured question templates', 'run_make_questions_cli': 'run the CLI tool to process an input JSONL database file and output questions with answers and derivations'}
```

