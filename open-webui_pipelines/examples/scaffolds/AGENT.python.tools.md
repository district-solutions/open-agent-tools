# Agent Python Tools

- repo: open-webui/pipelines
- repo_uri: https://github.com/open-webui/pipelines

## File: open-webui_pipelines/examples/scaffolds/example_pipeline_scaffold.py

Prompts

```
['build a Pipeline class with Valves config and lifecycle hooks for Open WebUI pipelines', 'run the pipeline inlet hook to modify request body before OpenAI API call', 'run the pipeline outlet hook to modify response after OpenAI API call', 'run the pipeline pipe method to process user messages with custom logic like RAG', 'test the pipeline on_startup and on_shutdown lifecycle hooks', 'build a manifold Pipeline class with multiple sub-pipelines for Open WebUI', 'create a list of sub-pipelines with unique ids and names in a manifold Pipeline', 'run the Pipeline on_startup lifecycle hook when the server starts', 'run the Pipeline on_shutdown lifecycle hook when the server stops']
```

Usage

```
{'build_pipeline_class': 'build a Pipeline class with Valves config and lifecycle hooks for Open WebUI pipelines', 'run_pipeline_inlet': 'run the pipeline inlet hook to modify request body before OpenAI API call', 'run_pipeline_outlet': 'run the pipeline outlet hook to modify response after OpenAI API call', 'run_pipeline_pipe': 'run the pipeline pipe method to process user messages with custom logic like RAG', 'test_pipeline_lifecycle': 'test the pipeline on_startup and on_shutdown lifecycle hooks'}
```

## File: open-webui_pipelines/examples/scaffolds/manifold_pipeline_scaffold.py

Prompts

```
['build a Pipeline class with Valves config and lifecycle hooks for Open WebUI pipelines', 'run the pipeline inlet hook to modify request body before OpenAI API call', 'run the pipeline outlet hook to modify response after OpenAI API call', 'run the pipeline pipe method to process user messages with custom logic like RAG', 'test the pipeline on_startup and on_shutdown lifecycle hooks', 'build a manifold Pipeline class with multiple sub-pipelines for Open WebUI', 'create a list of sub-pipelines with unique ids and names in a manifold Pipeline', 'run the Pipeline on_startup lifecycle hook when the server starts', 'run the Pipeline on_shutdown lifecycle hook when the server stops']
```

Usage

```
{'build_manifold_pipeline': 'build a manifold Pipeline class with multiple sub-pipelines for Open WebUI', 'create_pipeline_subpipelines': 'create a list of sub-pipelines with unique ids and names in a manifold Pipeline', 'run_pipeline_on_startup': 'run the Pipeline on_startup lifecycle hook when the server starts', 'run_pipeline_on_shutdown': 'run the Pipeline on_shutdown lifecycle hook when the server stops', 'run_pipeline_pipe': 'run the Pipeline pipe method to handle user messages with model_id and body parameters'}
```

