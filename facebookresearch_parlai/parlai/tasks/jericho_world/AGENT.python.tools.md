# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/jericho_world/agents.py

Prompts

```
['build a knowledge graph string from a list of subject-relation-object edge tuples', 'compute the set of ADD and DEL mutations between two knowledge graph strings', 'encode two sets of strings into parallel integer index lists for F1 metric computation', 'review the StateToKGTeacher class that predicts knowledge graphs from game state and evaluates with F1 metrics', 'create an ActionKGTeacher that generates knowledge graph mutations after a given action in JerichoWorld', 'build the JerichoWorld dataset by cloning the GitHub repo and extracting train and test JSON files', 'build the JerichoWorld dataset only if it has not already been built at the given version', 'build the JerichoWorld dataset by removing old or corrupted data before cloning the repo', 'review the build function that clones JerichoWorld, extracts data.zip, and copies train and test JSON files', 'summarize the build function that downloads and prepares the JerichoWorld dialogue dataset for ParlAI']
```

Usage

```
{'build_knowledge_graph_string': 'build a knowledge graph string from a list of subject-relation-object edge tuples', 'compute_graph_mutation_diff': 'compute the set of ADD and DEL mutations between two knowledge graph strings', 'encode_set_elements': 'encode two sets of strings into parallel integer index lists for F1 metric computation', 'review_StateToKGTeacher': 'review the StateToKGTeacher class that predicts knowledge graphs from game state and evaluates with F1 metrics', 'create_ActionKGTeacher': 'create an ActionKGTeacher that generates knowledge graph mutations after a given action in JerichoWorld'}
```

## File: facebookresearch_parlai/parlai/tasks/jericho_world/build.py

Prompts

```
['build a knowledge graph string from a list of subject-relation-object edge tuples', 'compute the set of ADD and DEL mutations between two knowledge graph strings', 'encode two sets of strings into parallel integer index lists for F1 metric computation', 'review the StateToKGTeacher class that predicts knowledge graphs from game state and evaluates with F1 metrics', 'create an ActionKGTeacher that generates knowledge graph mutations after a given action in JerichoWorld', 'build the JerichoWorld dataset by cloning the GitHub repo and extracting train and test JSON files', 'build the JerichoWorld dataset only if it has not already been built at the given version', 'build the JerichoWorld dataset by removing old or corrupted data before cloning the repo', 'review the build function that clones JerichoWorld, extracts data.zip, and copies train and test JSON files', 'summarize the build function that downloads and prepares the JerichoWorld dialogue dataset for ParlAI']
```

Usage

```
{'build_jericho_dataset': 'build the JerichoWorld dataset by cloning the GitHub repo and extracting train and test JSON files', 'build_check_already_built': 'build the JerichoWorld dataset only if it has not already been built at the given version', 'build_remove_corrupted_data': 'build the JerichoWorld dataset by removing old or corrupted data before cloning the repo', 'review_build_function': 'review the build function that clones JerichoWorld, extracts data.zip, and copies train and test JSON files', 'summarize_build_function': 'summarize the build function that downloads and prepares the JerichoWorld dialogue dataset for ParlAI'}
```

