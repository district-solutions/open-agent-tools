# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/triviaqa/agents.py

Prompts

```
['create a WebTeacher to load TriviaQA web search evidence and questions from JSON data files', 'create a WikipediaTeacher to load TriviaQA Wikipedia entity page evidence and questions from JSON data files', 'create a VerifiedTeacher multi-task teacher combining verified Wikipedia and web TriviaQA dev data', 'create a NoEvidenceUnionTeacher to load TriviaQA questions without any evidence context attached', 'create a DefaultTeacher multi-task teacher combining Wikipedia and web TriviaQA data sources', 'run the build function to download and prepare the TriviaQA dataset for ParlAI', 'download the TriviaQA-RC tarball using the RESOURCES list of DownloadableFile objects', 'merge web and wikipedia TriviaQA question-answer pairs into a unified noevidence-union JSON file', 'deduplicate and merge answer aliases across web and wikipedia sources for the same question', 'review the build function to understand how TriviaQA data is downloaded, merged, and versioned']
```

Usage

```
{'create_web_teacher': 'create a WebTeacher to load TriviaQA web search evidence and questions from JSON data files', 'create_wikipedia_teacher': 'create a WikipediaTeacher to load TriviaQA Wikipedia entity page evidence and questions from JSON data files', 'create_verified_teacher': 'create a VerifiedTeacher multi-task teacher combining verified Wikipedia and web TriviaQA dev data', 'create_no_evidence_union_teacher': 'create a NoEvidenceUnionTeacher to load TriviaQA questions without any evidence context attached', 'create_default_teacher': 'create a DefaultTeacher multi-task teacher combining Wikipedia and web TriviaQA data sources'}
```

## File: facebookresearch_parlai/parlai/tasks/triviaqa/build.py

Prompts

```
['create a WebTeacher to load TriviaQA web search evidence and questions from JSON data files', 'create a WikipediaTeacher to load TriviaQA Wikipedia entity page evidence and questions from JSON data files', 'create a VerifiedTeacher multi-task teacher combining verified Wikipedia and web TriviaQA dev data', 'create a NoEvidenceUnionTeacher to load TriviaQA questions without any evidence context attached', 'create a DefaultTeacher multi-task teacher combining Wikipedia and web TriviaQA data sources', 'run the build function to download and prepare the TriviaQA dataset for ParlAI', 'download the TriviaQA-RC tarball using the RESOURCES list of DownloadableFile objects', 'merge web and wikipedia TriviaQA question-answer pairs into a unified noevidence-union JSON file', 'deduplicate and merge answer aliases across web and wikipedia sources for the same question', 'review the build function to understand how TriviaQA data is downloaded, merged, and versioned']
```

Usage

```
{'build_triviaqa_data': 'run the build function to download and prepare the TriviaQA dataset for ParlAI', 'download_triviaqa_resources': 'download the TriviaQA-RC tarball using the RESOURCES list of DownloadableFile objects', 'merge_web_wikipedia_questions': 'merge web and wikipedia TriviaQA question-answer pairs into a unified noevidence-union JSON file', 'deduplicate_triviaqa_answers': 'deduplicate and merge answer aliases across web and wikipedia sources for the same question', 'review_build_function': 'review the build function to understand how TriviaQA data is downloaded, merged, and versioned'}
```

