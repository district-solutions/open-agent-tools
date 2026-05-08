# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/tools/artifact_scripts/compute_checksum.py

Prompts

```
['run the script to compute checksums for the default craftassist NLU model artifacts', 'run the script to compute checksums for the datasets artifact directory', 'run the script to compute checksums for the locobot perception model artifacts', 'run the script to compute checksums for the craftassist perception model artifacts', 'run the script with a custom agent name to compute artifact checksums', 'download a tar.gz artifact from S3 by agent name, artifact type, model, and checksum', 'download datasets from AWS S3 for a specified agent using a tracked checksum file', 'download NLU or perception models from AWS S3 for a specified agent', 'download and extract locobot perception test assets from an S3 bucket', 'download a file from a URL to a local path with a tqdm progress bar', 'fetch the safety.txt keyword list from the droidlet-internal S3 bucket to a local file path', 'run the fetch_safety_words_file function to download internal safety resources from S3', 'test the fetch_safety_words_file function with a specified output directory path', 'review the fetch_safety_words_file function for S3 authentication fallback logic using boto3 and awscli', 'refactor the fetch_safety_words_file function to use explicit error handling instead of bare except clauses', 'run the try_download_artifacts function to download NLU, perception models, and datasets for an agent', 'run the script with --agent_name craftassist to download default artifacts via argparse CLI', 'run the script with --test_mode flag to also download robot perception test assets', 'review the compare_checksum_try_download function that compares local and remote checksums for artifacts', 'refactor the try_download function to support additional artifact types beyond datasets and models', 'compute a SHA checksum for a local artifact folder and write it to a checksum file', 'tar an artifact directory excluding hidden files and upload the archive to an S3 bucket', 'compute a checksum for an artifact, create a tar archive, and upload it to S3 in one step', 'compute checksum and upload agent dataset artifacts to the S3 craftassist bucket', 'compute checksum and upload agent model artifacts like NLU or policy models to S3']
```

Usage

```
{'run_compute_checksum_default': 'run the script to compute checksums for the default craftassist NLU model artifacts', 'run_compute_checksum_datasets': 'run the script to compute checksums for the datasets artifact directory', 'run_compute_checksum_perception': 'run the script to compute checksums for the locobot perception model artifacts', 'run_compute_checksum_craftassist_perception': 'run the script to compute checksums for the craftassist perception model artifacts', 'run_compute_checksum_custom_agent': 'run the script with a custom agent name to compute artifact checksums'}
```

## File: facebookresearch_fairo/droidlet/tools/artifact_scripts/fetch_artifacts_from_aws.py

Prompts

```
['run the script to compute checksums for the default craftassist NLU model artifacts', 'run the script to compute checksums for the datasets artifact directory', 'run the script to compute checksums for the locobot perception model artifacts', 'run the script to compute checksums for the craftassist perception model artifacts', 'run the script with a custom agent name to compute artifact checksums', 'download a tar.gz artifact from S3 by agent name, artifact type, model, and checksum', 'download datasets from AWS S3 for a specified agent using a tracked checksum file', 'download NLU or perception models from AWS S3 for a specified agent', 'download and extract locobot perception test assets from an S3 bucket', 'download a file from a URL to a local path with a tqdm progress bar', 'fetch the safety.txt keyword list from the droidlet-internal S3 bucket to a local file path', 'run the fetch_safety_words_file function to download internal safety resources from S3', 'test the fetch_safety_words_file function with a specified output directory path', 'review the fetch_safety_words_file function for S3 authentication fallback logic using boto3 and awscli', 'refactor the fetch_safety_words_file function to use explicit error handling instead of bare except clauses', 'run the try_download_artifacts function to download NLU, perception models, and datasets for an agent', 'run the script with --agent_name craftassist to download default artifacts via argparse CLI', 'run the script with --test_mode flag to also download robot perception test assets', 'review the compare_checksum_try_download function that compares local and remote checksums for artifacts', 'refactor the try_download function to support additional artifact types beyond datasets and models', 'compute a SHA checksum for a local artifact folder and write it to a checksum file', 'tar an artifact directory excluding hidden files and upload the archive to an S3 bucket', 'compute a checksum for an artifact, create a tar archive, and upload it to S3 in one step', 'compute checksum and upload agent dataset artifacts to the S3 craftassist bucket', 'compute checksum and upload agent model artifacts like NLU or policy models to S3']
```

Usage

```
{'fetch_artifact_from_aws': 'download a tar.gz artifact from S3 by agent name, artifact type, model, and checksum', 'fetch_datasets_from_aws': 'download datasets from AWS S3 for a specified agent using a tracked checksum file', 'fetch_models_from_aws': 'download NLU or perception models from AWS S3 for a specified agent', 'fetch_test_assets_from_aws': 'download and extract locobot perception test assets from an S3 bucket', 'download_url': 'download a file from a URL to a local path with a tqdm progress bar'}
```

## File: facebookresearch_fairo/droidlet/tools/artifact_scripts/fetch_internal_resources.py

Prompts

```
['run the script to compute checksums for the default craftassist NLU model artifacts', 'run the script to compute checksums for the datasets artifact directory', 'run the script to compute checksums for the locobot perception model artifacts', 'run the script to compute checksums for the craftassist perception model artifacts', 'run the script with a custom agent name to compute artifact checksums', 'download a tar.gz artifact from S3 by agent name, artifact type, model, and checksum', 'download datasets from AWS S3 for a specified agent using a tracked checksum file', 'download NLU or perception models from AWS S3 for a specified agent', 'download and extract locobot perception test assets from an S3 bucket', 'download a file from a URL to a local path with a tqdm progress bar', 'fetch the safety.txt keyword list from the droidlet-internal S3 bucket to a local file path', 'run the fetch_safety_words_file function to download internal safety resources from S3', 'test the fetch_safety_words_file function with a specified output directory path', 'review the fetch_safety_words_file function for S3 authentication fallback logic using boto3 and awscli', 'refactor the fetch_safety_words_file function to use explicit error handling instead of bare except clauses', 'run the try_download_artifacts function to download NLU, perception models, and datasets for an agent', 'run the script with --agent_name craftassist to download default artifacts via argparse CLI', 'run the script with --test_mode flag to also download robot perception test assets', 'review the compare_checksum_try_download function that compares local and remote checksums for artifacts', 'refactor the try_download function to support additional artifact types beyond datasets and models', 'compute a SHA checksum for a local artifact folder and write it to a checksum file', 'tar an artifact directory excluding hidden files and upload the archive to an S3 bucket', 'compute a checksum for an artifact, create a tar archive, and upload it to S3 in one step', 'compute checksum and upload agent dataset artifacts to the S3 craftassist bucket', 'compute checksum and upload agent model artifacts like NLU or policy models to S3']
```

Usage

```
{'fetch_safety_words': 'fetch the safety.txt keyword list from the droidlet-internal S3 bucket to a local file path', 'run_fetch_safety_words': 'run the fetch_safety_words_file function to download internal safety resources from S3', 'test_fetch_safety_words': 'test the fetch_safety_words_file function with a specified output directory path', 'review_fetch_safety_words': 'review the fetch_safety_words_file function for S3 authentication fallback logic using boto3 and awscli', 'refactor_fetch_safety_words': 'refactor the fetch_safety_words_file function to use explicit error handling instead of bare except clauses'}
```

## File: facebookresearch_fairo/droidlet/tools/artifact_scripts/try_download.py

Prompts

```
['run the script to compute checksums for the default craftassist NLU model artifacts', 'run the script to compute checksums for the datasets artifact directory', 'run the script to compute checksums for the locobot perception model artifacts', 'run the script to compute checksums for the craftassist perception model artifacts', 'run the script with a custom agent name to compute artifact checksums', 'download a tar.gz artifact from S3 by agent name, artifact type, model, and checksum', 'download datasets from AWS S3 for a specified agent using a tracked checksum file', 'download NLU or perception models from AWS S3 for a specified agent', 'download and extract locobot perception test assets from an S3 bucket', 'download a file from a URL to a local path with a tqdm progress bar', 'fetch the safety.txt keyword list from the droidlet-internal S3 bucket to a local file path', 'run the fetch_safety_words_file function to download internal safety resources from S3', 'test the fetch_safety_words_file function with a specified output directory path', 'review the fetch_safety_words_file function for S3 authentication fallback logic using boto3 and awscli', 'refactor the fetch_safety_words_file function to use explicit error handling instead of bare except clauses', 'run the try_download_artifacts function to download NLU, perception models, and datasets for an agent', 'run the script with --agent_name craftassist to download default artifacts via argparse CLI', 'run the script with --test_mode flag to also download robot perception test assets', 'review the compare_checksum_try_download function that compares local and remote checksums for artifacts', 'refactor the try_download function to support additional artifact types beyond datasets and models', 'compute a SHA checksum for a local artifact folder and write it to a checksum file', 'tar an artifact directory excluding hidden files and upload the archive to an S3 bucket', 'compute a checksum for an artifact, create a tar archive, and upload it to S3 in one step', 'compute checksum and upload agent dataset artifacts to the S3 craftassist bucket', 'compute checksum and upload agent model artifacts like NLU or policy models to S3']
```

Usage

```
{'run_try_download_artifacts': 'run the try_download_artifacts function to download NLU, perception models, and datasets for an agent', 'run_try_download_cli': 'run the script with --agent_name craftassist to download default artifacts via argparse CLI', 'run_try_download_test_mode': 'run the script with --test_mode flag to also download robot perception test assets', 'review_compare_checksum_try_download': 'review the compare_checksum_try_download function that compares local and remote checksums for artifacts', 'refactor_try_download': 'refactor the try_download function to support additional artifact types beyond datasets and models'}
```

## File: facebookresearch_fairo/droidlet/tools/artifact_scripts/upload_artifacts_to_aws.py

Prompts

```
['run the script to compute checksums for the default craftassist NLU model artifacts', 'run the script to compute checksums for the datasets artifact directory', 'run the script to compute checksums for the locobot perception model artifacts', 'run the script to compute checksums for the craftassist perception model artifacts', 'run the script with a custom agent name to compute artifact checksums', 'download a tar.gz artifact from S3 by agent name, artifact type, model, and checksum', 'download datasets from AWS S3 for a specified agent using a tracked checksum file', 'download NLU or perception models from AWS S3 for a specified agent', 'download and extract locobot perception test assets from an S3 bucket', 'download a file from a URL to a local path with a tqdm progress bar', 'fetch the safety.txt keyword list from the droidlet-internal S3 bucket to a local file path', 'run the fetch_safety_words_file function to download internal safety resources from S3', 'test the fetch_safety_words_file function with a specified output directory path', 'review the fetch_safety_words_file function for S3 authentication fallback logic using boto3 and awscli', 'refactor the fetch_safety_words_file function to use explicit error handling instead of bare except clauses', 'run the try_download_artifacts function to download NLU, perception models, and datasets for an agent', 'run the script with --agent_name craftassist to download default artifacts via argparse CLI', 'run the script with --test_mode flag to also download robot perception test assets', 'review the compare_checksum_try_download function that compares local and remote checksums for artifacts', 'refactor the try_download function to support additional artifact types beyond datasets and models', 'compute a SHA checksum for a local artifact folder and write it to a checksum file', 'tar an artifact directory excluding hidden files and upload the archive to an S3 bucket', 'compute a checksum for an artifact, create a tar archive, and upload it to S3 in one step', 'compute checksum and upload agent dataset artifacts to the S3 craftassist bucket', 'compute checksum and upload agent model artifacts like NLU or policy models to S3']
```

Usage

```
{'compute_checksum_artifact': 'compute a SHA checksum for a local artifact folder and write it to a checksum file', 'tar_and_upload_artifact': 'tar an artifact directory excluding hidden files and upload the archive to an S3 bucket', 'compute_checksum_tar_and_upload': 'compute a checksum for an artifact, create a tar archive, and upload it to S3 in one step', 'upload_agent_datasets': 'compute checksum and upload agent dataset artifacts to the S3 craftassist bucket', 'upload_agent_models': 'compute checksum and upload agent model artifacts like NLU or policy models to S3'}
```

