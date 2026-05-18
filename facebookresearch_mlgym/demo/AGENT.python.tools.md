# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/demo/demo.py

Prompts

```
['run the streamlit MLGym demo app to replay agent experiment trajectories in a browser', 'load a JSON trajectory file and return the list of agent steps from the trajectory', 'display and animate each step of an ML agent trajectory with thought, action, and result panels', 'highlight action, analysis, performance, error, and optimization keywords in step caption text using regex', 'stream text character by character into a Streamlit placeholder with optional code block formatting', 'run the streamlit MLGym trajectory visualizer web app with a custom trajectory directory', 'parse a trajectory file path into its folder, task, model, and run metadata components', 'recursively find all trajectory files in a directory and return structured metadata for each', 'filter a list of trajectories by folder, task, model, suffix, and a text search query', 'load a trajectory file and append evaluation results and exit status to its content history']
```

Usage

```
{'run_streamlit_demo': 'run the streamlit MLGym demo app to replay agent experiment trajectories in a browser', 'load_trajectory': 'load a JSON trajectory file and return the list of agent steps from the trajectory', 'display_steps': 'display and animate each step of an ML agent trajectory with thought, action, and result panels', 'highlight_step_keywords': 'highlight action, analysis, performance, error, and optimization keywords in step caption text using regex', 'stream_text': 'stream text character by character into a Streamlit placeholder with optional code block formatting'}
```

## File: facebookresearch_mlgym/demo/trajectory_visualizer.py

Prompts

```
['run the streamlit MLGym demo app to replay agent experiment trajectories in a browser', 'load a JSON trajectory file and return the list of agent steps from the trajectory', 'display and animate each step of an ML agent trajectory with thought, action, and result panels', 'highlight action, analysis, performance, error, and optimization keywords in step caption text using regex', 'stream text character by character into a Streamlit placeholder with optional code block formatting', 'run the streamlit MLGym trajectory visualizer web app with a custom trajectory directory', 'parse a trajectory file path into its folder, task, model, and run metadata components', 'recursively find all trajectory files in a directory and return structured metadata for each', 'filter a list of trajectories by folder, task, model, suffix, and a text search query', 'load a trajectory file and append evaluation results and exit status to its content history']
```

Usage

```
{'run_trajectory_visualizer': 'run the streamlit MLGym trajectory visualizer web app with a custom trajectory directory', 'parse_trajectory_filename': 'parse a trajectory file path into its folder, task, model, and run metadata components', 'find_trajectory_files': 'recursively find all trajectory files in a directory and return structured metadata for each', 'filter_trajectories': 'filter a list of trajectories by folder, task, model, suffix, and a text search query', 'load_content': 'load a trajectory file and append evaluation results and exit status to its content history'}
```

