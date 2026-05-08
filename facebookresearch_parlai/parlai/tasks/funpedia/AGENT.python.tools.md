# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/funpedia/agents.py

Prompts

```
['run the FunpediaTeacher to load and serve persona-conditioned Wikipedia rephrasing examples from the datafile', 'create a NopersonaTeacher that strips persona fields and serves only title and passage text', 'build a LmTeacher that drops the query entirely to create a language modeling task', 'test the EchoTeacher that replaces answers with an echo of the passage to measure repetition', 'review the SentencechooseTeacher that serves sentence choosing examples with label candidates for selection', 'build the rephrase_sentences dataset by downloading train, valid, and test files from parl.ai', 'run the build function to download and prepare the Funpedia rephrase sentences data', 'download the rephrase_sentences training, validation, and test data files to the datapath directory', 'check if the rephrase_sentences data is already built at version v6.0 before downloading', 'remove outdated rephrase_sentences data files when an older version exists in the datapath']
```

Usage

```
{'run_funpedia_teacher': 'run the FunpediaTeacher to load and serve persona-conditioned Wikipedia rephrasing examples from the datafile', 'create_nopersona_teacher': 'create a NopersonaTeacher that strips persona fields and serves only title and passage text', 'build_lm_teacher': 'build a LmTeacher that drops the query entirely to create a language modeling task', 'test_echo_teacher': 'test the EchoTeacher that replaces answers with an echo of the passage to measure repetition', 'review_sentencechoose_teacher': 'review the SentencechooseTeacher that serves sentence choosing examples with label candidates for selection'}
```

## File: facebookresearch_parlai/parlai/tasks/funpedia/build.py

Prompts

```
['run the FunpediaTeacher to load and serve persona-conditioned Wikipedia rephrasing examples from the datafile', 'create a NopersonaTeacher that strips persona fields and serves only title and passage text', 'build a LmTeacher that drops the query entirely to create a language modeling task', 'test the EchoTeacher that replaces answers with an echo of the passage to measure repetition', 'review the SentencechooseTeacher that serves sentence choosing examples with label candidates for selection', 'build the rephrase_sentences dataset by downloading train, valid, and test files from parl.ai', 'run the build function to download and prepare the Funpedia rephrase sentences data', 'download the rephrase_sentences training, validation, and test data files to the datapath directory', 'check if the rephrase_sentences data is already built at version v6.0 before downloading', 'remove outdated rephrase_sentences data files when an older version exists in the datapath']
```

Usage

```
{'build_rephrase_sentences_data': 'build the rephrase_sentences dataset by downloading train, valid, and test files from parl.ai', 'run_build_function': 'run the build function to download and prepare the Funpedia rephrase sentences data', 'download_rephrase_sentences_files': 'download the rephrase_sentences training, validation, and test data files to the datapath directory', 'check_data_version': 'check if the rephrase_sentences data is already built at version v6.0 before downloading', 'remove_outdated_data': 'remove outdated rephrase_sentences data files when an older version exists in the datapath'}
```

