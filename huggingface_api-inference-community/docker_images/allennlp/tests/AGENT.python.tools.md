# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/allennlp/tests/test_api.py

Prompts

```
['test that at least one pipeline task is enabled in the AllenNLP inference server', 'test that requesting an unsupported task raises an EnvironmentError via get_pipeline', 'review the PipelineTestCase class and its test methods for the Hugging Face inference API', 'refactor test_unsupported_tasks to add additional task types to the ALL_TASKS set', 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for pipeline testing', 'test the question answering API with a valid question and context input', 'test the question answering API returns 400 for malformed binary input', 'review the QuestionAnsweringTestCase class and its setUp and tearDown environment methods', 'refactor the test_simple method to support additional question answering input formats', 'summarize the QuestionAnsweringTestCase class that tests the HuggingFace question answering API endpoint', 'run docker build in the project root directory using subprocess', 'test that the docker image builds successfully from the project root', 'create a context manager that changes the working directory and restores it on exit', 'run a shell command via subprocess.check_output and capture its output', 'run the DockerBuildTestCase unittest to verify docker image builds correctly']
```

Usage

```
{'test_pipeline_tasks_enabled': 'test that at least one pipeline task is enabled in the AllenNLP inference server', 'test_unsupported_tasks_raise_error': 'test that requesting an unsupported task raises an EnvironmentError via get_pipeline', 'review_PipelineTestCase': 'review the PipelineTestCase class and its test methods for the Hugging Face inference API', 'refactor_test_unsupported_tasks': 'refactor test_unsupported_tasks to add additional task types to the ALL_TASKS set', 'summarize_TESTABLE_MODELS': 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for pipeline testing'}
```

## File: huggingface_api-inference-community/docker_images/allennlp/tests/test_api_question_answering.py

Prompts

```
['test that at least one pipeline task is enabled in the AllenNLP inference server', 'test that requesting an unsupported task raises an EnvironmentError via get_pipeline', 'review the PipelineTestCase class and its test methods for the Hugging Face inference API', 'refactor test_unsupported_tasks to add additional task types to the ALL_TASKS set', 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for pipeline testing', 'test the question answering API with a valid question and context input', 'test the question answering API returns 400 for malformed binary input', 'review the QuestionAnsweringTestCase class and its setUp and tearDown environment methods', 'refactor the test_simple method to support additional question answering input formats', 'summarize the QuestionAnsweringTestCase class that tests the HuggingFace question answering API endpoint', 'run docker build in the project root directory using subprocess', 'test that the docker image builds successfully from the project root', 'create a context manager that changes the working directory and restores it on exit', 'run a shell command via subprocess.check_output and capture its output', 'run the DockerBuildTestCase unittest to verify docker image builds correctly']
```

Usage

```
{'test_question_answering_simple': 'test the question answering API with a valid question and context input', 'test_question_answering_malformed': 'test the question answering API returns 400 for malformed binary input', 'review_QuestionAnsweringTestCase': 'review the QuestionAnsweringTestCase class and its setUp and tearDown environment methods', 'refactor_test_simple': 'refactor the test_simple method to support additional question answering input formats', 'summarize_QuestionAnsweringTestCase': 'summarize the QuestionAnsweringTestCase class that tests the HuggingFace question answering API endpoint'}
```

## File: huggingface_api-inference-community/docker_images/allennlp/tests/test_docker_build.py

Prompts

```
['test that at least one pipeline task is enabled in the AllenNLP inference server', 'test that requesting an unsupported task raises an EnvironmentError via get_pipeline', 'review the PipelineTestCase class and its test methods for the Hugging Face inference API', 'refactor test_unsupported_tasks to add additional task types to the ALL_TASKS set', 'summarize the TESTABLE_MODELS dictionary mapping task names to model IDs for pipeline testing', 'test the question answering API with a valid question and context input', 'test the question answering API returns 400 for malformed binary input', 'review the QuestionAnsweringTestCase class and its setUp and tearDown environment methods', 'refactor the test_simple method to support additional question answering input formats', 'summarize the QuestionAnsweringTestCase class that tests the HuggingFace question answering API endpoint', 'run docker build in the project root directory using subprocess', 'test that the docker image builds successfully from the project root', 'create a context manager that changes the working directory and restores it on exit', 'run a shell command via subprocess.check_output and capture its output', 'run the DockerBuildTestCase unittest to verify docker image builds correctly']
```

Usage

```
{'build_docker_image': 'run docker build in the project root directory using subprocess', 'test_docker_build': 'test that the docker image builds successfully from the project root', 'create_cd_context_manager': 'create a context manager that changes the working directory and restores it on exit', 'run_subprocess_check_output': 'run a shell command via subprocess.check_output and capture its output', 'test_DockerBuildTestCase': 'run the DockerBuildTestCase unittest to verify docker image builds correctly'}
```

