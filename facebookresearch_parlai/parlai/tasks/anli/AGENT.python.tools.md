# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/anli/agents.py

Prompts

```
['run the RoundBaseTeacher to load ANLI round data with dialog format and binary class options', 'run the R1Teacher to train on ANLI round 1 natural language inference data', 'run the R2Teacher to train on ANLI round 2 natural language inference data', 'run the R3Teacher to train on ANLI round 3 natural language inference data', 'run the DefaultTeacher to train on all three ANLI rounds as a multi-task teacher', 'build the ANLI dataset by downloading and extracting data to the specified datapath', 'run the build function to download ANLI v0.1 data into the ParlAI datapath directory', 'check if the ANLI dataset is already built for version v0.1 in the datapath', 'download the ANLI v0.1 zip file from the FAIR public files server', 'review the build function that handles ANLI dataset download and version management']
```

Usage

```
{'run_roundbase_teacher': 'run the RoundBaseTeacher to load ANLI round data with dialog format and binary class options', 'run_r1_teacher': 'run the R1Teacher to train on ANLI round 1 natural language inference data', 'run_r2_teacher': 'run the R2Teacher to train on ANLI round 2 natural language inference data', 'run_r3_teacher': 'run the R3Teacher to train on ANLI round 3 natural language inference data', 'run_default_teacher': 'run the DefaultTeacher to train on all three ANLI rounds as a multi-task teacher'}
```

## File: facebookresearch_parlai/parlai/tasks/anli/build.py

Prompts

```
['run the RoundBaseTeacher to load ANLI round data with dialog format and binary class options', 'run the R1Teacher to train on ANLI round 1 natural language inference data', 'run the R2Teacher to train on ANLI round 2 natural language inference data', 'run the R3Teacher to train on ANLI round 3 natural language inference data', 'run the DefaultTeacher to train on all three ANLI rounds as a multi-task teacher', 'build the ANLI dataset by downloading and extracting data to the specified datapath', 'run the build function to download ANLI v0.1 data into the ParlAI datapath directory', 'check if the ANLI dataset is already built for version v0.1 in the datapath', 'download the ANLI v0.1 zip file from the FAIR public files server', 'review the build function that handles ANLI dataset download and version management']
```

Usage

```
{'build_anli_dataset': 'build the ANLI dataset by downloading and extracting data to the specified datapath', 'run_build_function': 'run the build function to download ANLI v0.1 data into the ParlAI datapath directory', 'check_anli_version': 'check if the ANLI dataset is already built for version v0.1 in the datapath', 'download_anli_resources': 'download the ANLI v0.1 zip file from the FAIR public files server', 'review_build_function': 'review the build function that handles ANLI dataset download and version management'}
```

