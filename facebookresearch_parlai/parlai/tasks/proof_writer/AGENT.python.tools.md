# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/proof_writer/agents.py

Prompts

```
['run the ProofWriterTeacher dialog teacher to load and serve proof writer dataset examples', 'review the ProofWriterTeacher process_base method that parses JSON blobs into messages with steps', 'run the ProofWriterStepByStepReasoningTeacher for step-by-step reasoning on proof writer logical problems', 'review the ProofWriterExpandStepMutator that expands episodes into individual thinking steps with THINK tags', 'run the ProofWriterMultistepMutator to filter episodes that contain at least one reasoning step', 'run the build function to download and set up the proof writer dataset for ParlAI', 'download the proof writer dataset zip file from the S3 URL into the data directory', 'check if the proof writer dataset has already been built at version 1.0', 'remove an older version of the proof writer dataset directory before rebuilding', 'mark the proof writer dataset as built with version string 1.0 in the data directory']
```

Usage

```
{'run_ProofWriterTeacher': 'run the ProofWriterTeacher dialog teacher to load and serve proof writer dataset examples', 'review_ProofWriterTeacher_process_base': 'review the ProofWriterTeacher process_base method that parses JSON blobs into messages with steps', 'run_ProofWriterStepByStepReasoningTeacher': 'run the ProofWriterStepByStepReasoningTeacher for step-by-step reasoning on proof writer logical problems', 'review_ProofWriterExpandStepMutator': 'review the ProofWriterExpandStepMutator that expands episodes into individual thinking steps with THINK tags', 'run_ProofWriterMultistepMutator': 'run the ProofWriterMultistepMutator to filter episodes that contain at least one reasoning step'}
```

## File: facebookresearch_parlai/parlai/tasks/proof_writer/build.py

Prompts

```
['run the ProofWriterTeacher dialog teacher to load and serve proof writer dataset examples', 'review the ProofWriterTeacher process_base method that parses JSON blobs into messages with steps', 'run the ProofWriterStepByStepReasoningTeacher for step-by-step reasoning on proof writer logical problems', 'review the ProofWriterExpandStepMutator that expands episodes into individual thinking steps with THINK tags', 'run the ProofWriterMultistepMutator to filter episodes that contain at least one reasoning step', 'run the build function to download and set up the proof writer dataset for ParlAI', 'download the proof writer dataset zip file from the S3 URL into the data directory', 'check if the proof writer dataset has already been built at version 1.0', 'remove an older version of the proof writer dataset directory before rebuilding', 'mark the proof writer dataset as built with version string 1.0 in the data directory']
```

Usage

```
{'build_proof_writer_dataset': 'run the build function to download and set up the proof writer dataset for ParlAI', 'download_proof_writer_resources': 'download the proof writer dataset zip file from the S3 URL into the data directory', 'check_proof_writer_version': 'check if the proof writer dataset has already been built at version 1.0', 'remove_outdated_proof_writer_data': 'remove an older version of the proof writer dataset directory before rebuilding', 'mark_proof_writer_built': 'mark the proof writer dataset as built with version string 1.0 in the data directory'}
```

