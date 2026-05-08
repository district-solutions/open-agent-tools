# Agent Python Tools

- repo: facebookresearch/llm-transparency-tool
- repo_uri: https://github.com/facebookresearch/llm-transparency-tool

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/server/app.py

Prompts

```
['run the LLM transparency viewer Streamlit app with a JSON config file via argparse', 'create an LlmViewerConfig dataclass to set debug mode, demo mode, models, and dataset options', 'run inference on a selected sentence using cached stateful model and autocast precision', 'draw an interactive contribution graph showing token paths and attention head contributions', 'draw promoted and suppressed token tables to visualize how representations change across layers', 'create a UiGraphNode from a JSON dict containing cell layer, token, and item type', 'create a UiGraphEdge from a JSON dict with source, target nodes, and weight', 'create a GraphSelection from a JSON dict containing a node and an edge', 'review the UiGraphNode.from_json method to parse layer, token, and NodeType from JSON', 'review the GraphSelection.from_json method to parse node and edge from JSON', 'initialize CUDA and measure the GPU memory overhead for each available device', 'create a SystemMonitor context manager to profile code execution and report GPU memory usage', 'use the SystemMonitor as a context manager to profile a block of code with GPU monitoring', 'report GPU memory usage as a bar chart showing overhead, occupied, and free memory per device', 'report the pyinstrument profiler output as an interactive HTML component in the Streamlit app', 'create a RenderSettings dataclass instance with default column proportions and token display counts', 'customize RenderSettings to change n_top_tokens, n_promoted_tokens, or attention_color_map values', 'use string_to_display to replace spaces with middle dots for token display formatting', 'generate a matplotlib LinearSegmentedColormap for logits visualization with positive and negative color ranges', 'apply the margins_css string to reduce Streamlit padding and set sidebar width', 'load a TransformerLensTransparentLlm model by name onto a specified device with Streamlit caching', 'run inference on a single sentence through a loaded TransparentLlm model', 'build a NetworkX contribution graph for a model with a given threshold value', 'load sentences from a text file into a list of strings', 'check which compute devices are available and return a list of gpu or cpu']
```

Usage

```
{'run_llm_viewer_app': 'run the LLM transparency viewer Streamlit app with a JSON config file via argparse', 'configure_llm_viewer': 'create an LlmViewerConfig dataclass to set debug mode, demo mode, models, and dataset options', 'run_inference_on_sentence': 'run inference on a selected sentence using cached stateful model and autocast precision', 'draw_contribution_graph': 'draw an interactive contribution graph showing token paths and attention head contributions', 'draw_token_dynamics': 'draw promoted and suppressed token tables to visualize how representations change across layers'}
```

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/server/graph_selection.py

Prompts

```
['run the LLM transparency viewer Streamlit app with a JSON config file via argparse', 'create an LlmViewerConfig dataclass to set debug mode, demo mode, models, and dataset options', 'run inference on a selected sentence using cached stateful model and autocast precision', 'draw an interactive contribution graph showing token paths and attention head contributions', 'draw promoted and suppressed token tables to visualize how representations change across layers', 'create a UiGraphNode from a JSON dict containing cell layer, token, and item type', 'create a UiGraphEdge from a JSON dict with source, target nodes, and weight', 'create a GraphSelection from a JSON dict containing a node and an edge', 'review the UiGraphNode.from_json method to parse layer, token, and NodeType from JSON', 'review the GraphSelection.from_json method to parse node and edge from JSON', 'initialize CUDA and measure the GPU memory overhead for each available device', 'create a SystemMonitor context manager to profile code execution and report GPU memory usage', 'use the SystemMonitor as a context manager to profile a block of code with GPU monitoring', 'report GPU memory usage as a bar chart showing overhead, occupied, and free memory per device', 'report the pyinstrument profiler output as an interactive HTML component in the Streamlit app', 'create a RenderSettings dataclass instance with default column proportions and token display counts', 'customize RenderSettings to change n_top_tokens, n_promoted_tokens, or attention_color_map values', 'use string_to_display to replace spaces with middle dots for token display formatting', 'generate a matplotlib LinearSegmentedColormap for logits visualization with positive and negative color ranges', 'apply the margins_css string to reduce Streamlit padding and set sidebar width', 'load a TransformerLensTransparentLlm model by name onto a specified device with Streamlit caching', 'run inference on a single sentence through a loaded TransparentLlm model', 'build a NetworkX contribution graph for a model with a given threshold value', 'load sentences from a text file into a list of strings', 'check which compute devices are available and return a list of gpu or cpu']
```

Usage

```
{'create_UiGraphNode_from_json': 'create a UiGraphNode from a JSON dict containing cell layer, token, and item type', 'create_UiGraphEdge_from_json': 'create a UiGraphEdge from a JSON dict with source, target nodes, and weight', 'create_GraphSelection_from_json': 'create a GraphSelection from a JSON dict containing a node and an edge', 'review_UiGraphNode_from_json': 'review the UiGraphNode.from_json method to parse layer, token, and NodeType from JSON', 'review_GraphSelection_from_json': 'review the GraphSelection.from_json method to parse node and edge from JSON'}
```

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/server/monitor.py

Prompts

```
['run the LLM transparency viewer Streamlit app with a JSON config file via argparse', 'create an LlmViewerConfig dataclass to set debug mode, demo mode, models, and dataset options', 'run inference on a selected sentence using cached stateful model and autocast precision', 'draw an interactive contribution graph showing token paths and attention head contributions', 'draw promoted and suppressed token tables to visualize how representations change across layers', 'create a UiGraphNode from a JSON dict containing cell layer, token, and item type', 'create a UiGraphEdge from a JSON dict with source, target nodes, and weight', 'create a GraphSelection from a JSON dict containing a node and an edge', 'review the UiGraphNode.from_json method to parse layer, token, and NodeType from JSON', 'review the GraphSelection.from_json method to parse node and edge from JSON', 'initialize CUDA and measure the GPU memory overhead for each available device', 'create a SystemMonitor context manager to profile code execution and report GPU memory usage', 'use the SystemMonitor as a context manager to profile a block of code with GPU monitoring', 'report GPU memory usage as a bar chart showing overhead, occupied, and free memory per device', 'report the pyinstrument profiler output as an interactive HTML component in the Streamlit app', 'create a RenderSettings dataclass instance with default column proportions and token display counts', 'customize RenderSettings to change n_top_tokens, n_promoted_tokens, or attention_color_map values', 'use string_to_display to replace spaces with middle dots for token display formatting', 'generate a matplotlib LinearSegmentedColormap for logits visualization with positive and negative color ranges', 'apply the margins_css string to reduce Streamlit padding and set sidebar width', 'load a TransformerLensTransparentLlm model by name onto a specified device with Streamlit caching', 'run inference on a single sentence through a loaded TransparentLlm model', 'build a NetworkX contribution graph for a model with a given threshold value', 'load sentences from a text file into a list of strings', 'check which compute devices are available and return a list of gpu or cpu']
```

Usage

```
{'init_gpu_memory': 'initialize CUDA and measure the GPU memory overhead for each available device', 'create_SystemMonitor': 'create a SystemMonitor context manager to profile code execution and report GPU memory usage', 'use_SystemMonitor_context': 'use the SystemMonitor as a context manager to profile a block of code with GPU monitoring', 'report_gpu_usage': 'report GPU memory usage as a bar chart showing overhead, occupied, and free memory per device', 'report_profiler': 'report the pyinstrument profiler output as an interactive HTML component in the Streamlit app'}
```

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/server/styles.py

Prompts

```
['run the LLM transparency viewer Streamlit app with a JSON config file via argparse', 'create an LlmViewerConfig dataclass to set debug mode, demo mode, models, and dataset options', 'run inference on a selected sentence using cached stateful model and autocast precision', 'draw an interactive contribution graph showing token paths and attention head contributions', 'draw promoted and suppressed token tables to visualize how representations change across layers', 'create a UiGraphNode from a JSON dict containing cell layer, token, and item type', 'create a UiGraphEdge from a JSON dict with source, target nodes, and weight', 'create a GraphSelection from a JSON dict containing a node and an edge', 'review the UiGraphNode.from_json method to parse layer, token, and NodeType from JSON', 'review the GraphSelection.from_json method to parse node and edge from JSON', 'initialize CUDA and measure the GPU memory overhead for each available device', 'create a SystemMonitor context manager to profile code execution and report GPU memory usage', 'use the SystemMonitor as a context manager to profile a block of code with GPU monitoring', 'report GPU memory usage as a bar chart showing overhead, occupied, and free memory per device', 'report the pyinstrument profiler output as an interactive HTML component in the Streamlit app', 'create a RenderSettings dataclass instance with default column proportions and token display counts', 'customize RenderSettings to change n_top_tokens, n_promoted_tokens, or attention_color_map values', 'use string_to_display to replace spaces with middle dots for token display formatting', 'generate a matplotlib LinearSegmentedColormap for logits visualization with positive and negative color ranges', 'apply the margins_css string to reduce Streamlit padding and set sidebar width', 'load a TransformerLensTransparentLlm model by name onto a specified device with Streamlit caching', 'run inference on a single sentence through a loaded TransparentLlm model', 'build a NetworkX contribution graph for a model with a given threshold value', 'load sentences from a text file into a list of strings', 'check which compute devices are available and return a list of gpu or cpu']
```

Usage

```
{'create_render_settings': 'create a RenderSettings dataclass instance with default column proportions and token display counts', 'customize_render_settings': 'customize RenderSettings to change n_top_tokens, n_promoted_tokens, or attention_color_map values', 'use_string_to_display': 'use string_to_display to replace spaces with middle dots for token display formatting', 'generate_logits_colormap': 'generate a matplotlib LinearSegmentedColormap for logits visualization with positive and negative color ranges', 'apply_margins_css': 'apply the margins_css string to reduce Streamlit padding and set sidebar width'}
```

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/server/utils.py

Prompts

```
['run the LLM transparency viewer Streamlit app with a JSON config file via argparse', 'create an LlmViewerConfig dataclass to set debug mode, demo mode, models, and dataset options', 'run inference on a selected sentence using cached stateful model and autocast precision', 'draw an interactive contribution graph showing token paths and attention head contributions', 'draw promoted and suppressed token tables to visualize how representations change across layers', 'create a UiGraphNode from a JSON dict containing cell layer, token, and item type', 'create a UiGraphEdge from a JSON dict with source, target nodes, and weight', 'create a GraphSelection from a JSON dict containing a node and an edge', 'review the UiGraphNode.from_json method to parse layer, token, and NodeType from JSON', 'review the GraphSelection.from_json method to parse node and edge from JSON', 'initialize CUDA and measure the GPU memory overhead for each available device', 'create a SystemMonitor context manager to profile code execution and report GPU memory usage', 'use the SystemMonitor as a context manager to profile a block of code with GPU monitoring', 'report GPU memory usage as a bar chart showing overhead, occupied, and free memory per device', 'report the pyinstrument profiler output as an interactive HTML component in the Streamlit app', 'create a RenderSettings dataclass instance with default column proportions and token display counts', 'customize RenderSettings to change n_top_tokens, n_promoted_tokens, or attention_color_map values', 'use string_to_display to replace spaces with middle dots for token display formatting', 'generate a matplotlib LinearSegmentedColormap for logits visualization with positive and negative color ranges', 'apply the margins_css string to reduce Streamlit padding and set sidebar width', 'load a TransformerLensTransparentLlm model by name onto a specified device with Streamlit caching', 'run inference on a single sentence through a loaded TransparentLlm model', 'build a NetworkX contribution graph for a model with a given threshold value', 'load sentences from a text file into a list of strings', 'check which compute devices are available and return a list of gpu or cpu']
```

Usage

```
{'load_model': 'load a TransformerLensTransparentLlm model by name onto a specified device with Streamlit caching', 'run_model': 'run inference on a single sentence through a loaded TransparentLlm model', 'get_contribution_graph': 'build a NetworkX contribution graph for a model with a given threshold value', 'load_dataset': 'load sentences from a text file into a list of strings', 'possible_devices': 'check which compute devices are available and return a list of gpu or cpu'}
```

