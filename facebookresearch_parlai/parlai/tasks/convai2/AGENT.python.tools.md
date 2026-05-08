# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/convai2/agents.py

Prompts

```
['run the SelfOriginalTeacher to load ConvAI2 self-original persona dialog data with label candidates', 'run the BothTeacher to load ConvAI2 dialog data with both agent and partner personas', 'run the NormalizedTeacher to load and normalize ConvAI2 dialog replies with configurable persona ordering', 'run the NormalizedTheirTeacher to load ConvAI2 data with only the partner persona normalized', 'run the SampleTeacher to load a small YAML sample of ConvAI2 data for testing', 'run the build function to download and set up the ConvAI2 dataset in the ParlAI datapath', 'review the build function to understand how ConvAI2 data is downloaded and versioned', 'summarize the RESOURCES list to see which ConvAI2 dataset files are downloaded', 'test the build function version check logic to verify outdated data is removed before rebuilding', 'refactor the RESOURCES list to add or remove ConvAI2 downloadable files for the build process', 'load personas from the convai2:both dataset by iterating through episodes and extracting persona text', 'get personas from shared state or load them fresh using the convai2 task data', 'run an interactive ConvAI2 chat world that randomly assigns personas to both agents', 'finalize a ConvAI2 chat episode and optionally display the partner persona at the end', 'run a self-chat ConvAI2 world where two agents are randomly assigned personas from the dataset']
```

Usage

```
{'run_convai2_selforiginal_teacher': 'run the SelfOriginalTeacher to load ConvAI2 self-original persona dialog data with label candidates', 'run_convai2_both_teacher': 'run the BothTeacher to load ConvAI2 dialog data with both agent and partner personas', 'run_convai2_normalized_teacher': 'run the NormalizedTeacher to load and normalize ConvAI2 dialog replies with configurable persona ordering', 'run_convai2_normalized_their_teacher': 'run the NormalizedTheirTeacher to load ConvAI2 data with only the partner persona normalized', 'run_convai2_sample_teacher': 'run the SampleTeacher to load a small YAML sample of ConvAI2 data for testing'}
```

## File: facebookresearch_parlai/parlai/tasks/convai2/build.py

Prompts

```
['run the SelfOriginalTeacher to load ConvAI2 self-original persona dialog data with label candidates', 'run the BothTeacher to load ConvAI2 dialog data with both agent and partner personas', 'run the NormalizedTeacher to load and normalize ConvAI2 dialog replies with configurable persona ordering', 'run the NormalizedTheirTeacher to load ConvAI2 data with only the partner persona normalized', 'run the SampleTeacher to load a small YAML sample of ConvAI2 data for testing', 'run the build function to download and set up the ConvAI2 dataset in the ParlAI datapath', 'review the build function to understand how ConvAI2 data is downloaded and versioned', 'summarize the RESOURCES list to see which ConvAI2 dataset files are downloaded', 'test the build function version check logic to verify outdated data is removed before rebuilding', 'refactor the RESOURCES list to add or remove ConvAI2 downloadable files for the build process', 'load personas from the convai2:both dataset by iterating through episodes and extracting persona text', 'get personas from shared state or load them fresh using the convai2 task data', 'run an interactive ConvAI2 chat world that randomly assigns personas to both agents', 'finalize a ConvAI2 chat episode and optionally display the partner persona at the end', 'run a self-chat ConvAI2 world where two agents are randomly assigned personas from the dataset']
```

Usage

```
{'build_convai2_data': 'run the build function to download and set up the ConvAI2 dataset in the ParlAI datapath', 'review_build_function': 'review the build function to understand how ConvAI2 data is downloaded and versioned', 'summarize_resources': 'summarize the RESOURCES list to see which ConvAI2 dataset files are downloaded', 'test_build_version_check': 'test the build function version check logic to verify outdated data is removed before rebuilding', 'refactor_download_resources': 'refactor the RESOURCES list to add or remove ConvAI2 downloadable files for the build process'}
```

## File: facebookresearch_parlai/parlai/tasks/convai2/worlds.py

Prompts

```
['run the SelfOriginalTeacher to load ConvAI2 self-original persona dialog data with label candidates', 'run the BothTeacher to load ConvAI2 dialog data with both agent and partner personas', 'run the NormalizedTeacher to load and normalize ConvAI2 dialog replies with configurable persona ordering', 'run the NormalizedTheirTeacher to load ConvAI2 data with only the partner persona normalized', 'run the SampleTeacher to load a small YAML sample of ConvAI2 data for testing', 'run the build function to download and set up the ConvAI2 dataset in the ParlAI datapath', 'review the build function to understand how ConvAI2 data is downloaded and versioned', 'summarize the RESOURCES list to see which ConvAI2 dataset files are downloaded', 'test the build function version check logic to verify outdated data is removed before rebuilding', 'refactor the RESOURCES list to add or remove ConvAI2 downloadable files for the build process', 'load personas from the convai2:both dataset by iterating through episodes and extracting persona text', 'get personas from shared state or load them fresh using the convai2 task data', 'run an interactive ConvAI2 chat world that randomly assigns personas to both agents', 'finalize a ConvAI2 chat episode and optionally display the partner persona at the end', 'run a self-chat ConvAI2 world where two agents are randomly assigned personas from the dataset']
```

Usage

```
{'load_personas_from_convai2': 'load personas from the convai2:both dataset by iterating through episodes and extracting persona text', 'get_personas_cached': 'get personas from shared state or load them fresh using the convai2 task data', 'run_interactive_convai2_chat': 'run an interactive ConvAI2 chat world that randomly assigns personas to both agents', 'finalize_convai2_episode': 'finalize a ConvAI2 chat episode and optionally display the partner persona at the end', 'run_selfchat_convai2': 'run a self-chat ConvAI2 world where two agents are randomly assigned personas from the dataset'}
```

