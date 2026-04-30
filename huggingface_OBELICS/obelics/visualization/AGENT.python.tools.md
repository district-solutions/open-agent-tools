# Agent Python Tools

- repo: huggingface/OBELICS
- repo_uri: https://github.com/huggingface/OBELICS.git

## File: huggingface_OBELICS/obelics/visualization/choose_filtering_parameters_web_documents_node_level.py

Prompts

```
['run the streamlit app to visualize filtering parameter distributions for web documents at node level', 'compute statistics like word count and character repetition ratio across a web document dataset', 'extract text examples and compute multiple statistics from a HuggingFace dataset using get_exs_and_stats', 'filter out None elements from a list using the non_empty_els_from_list helper function', 'generate histograms of chosen statistics with configurable bins and percentile truncation for web documents', 'run a streamlit app to visualize DOM tree simplification and text-image pair extraction on HTML documents', 'create a Visualization instance with a number of documents and a DOM tree visualization template path', 'use DOMTreeSimplificator to strip tags, remove comments, and simplify an HTML DOM tree', 'use TextMediaPairsExtractor to extract text-image pairs with CLIP scores from an HTML document', 'use get_dom_viz_html to render a DOM tree visualization from raw HTML using a Jinja2 template', 'run node level filtering on web documents using WebDocumentFilteringNodeLevel with configurable thresholds', 'run document level filtering on web documents using WebDocumentFilteringDocLevel with configurable thresholds', 'display original and filtered web documents side by side in the Streamlit visualization interface', 'load a HuggingFace dataset from disk and select a subset size like 100 or 1000 rows', 'select a random document from the loaded dataset using the choose_document method', 'display document texts and images from the current document using streamlit markdown']
```

Usage

```
{'run_streamlit_app': 'run the streamlit app to visualize filtering parameter distributions for web documents at node level', 'compute_dataset_statistics': 'compute statistics like word count and character repetition ratio across a web document dataset', 'extract_examples_and_stats': 'extract text examples and compute multiple statistics from a HuggingFace dataset using get_exs_and_stats', 'filter_none_elements': 'filter out None elements from a list using the non_empty_els_from_list helper function', 'visualize_stat_distributions': 'generate histograms of chosen statistics with configurable bins and percentile truncation for web documents'}
```

## File: huggingface_OBELICS/obelics/visualization/global_visualization.py

Prompts

```
['run the streamlit app to visualize filtering parameter distributions for web documents at node level', 'compute statistics like word count and character repetition ratio across a web document dataset', 'extract text examples and compute multiple statistics from a HuggingFace dataset using get_exs_and_stats', 'filter out None elements from a list using the non_empty_els_from_list helper function', 'generate histograms of chosen statistics with configurable bins and percentile truncation for web documents', 'run a streamlit app to visualize DOM tree simplification and text-image pair extraction on HTML documents', 'create a Visualization instance with a number of documents and a DOM tree visualization template path', 'use DOMTreeSimplificator to strip tags, remove comments, and simplify an HTML DOM tree', 'use TextMediaPairsExtractor to extract text-image pairs with CLIP scores from an HTML document', 'use get_dom_viz_html to render a DOM tree visualization from raw HTML using a Jinja2 template', 'run node level filtering on web documents using WebDocumentFilteringNodeLevel with configurable thresholds', 'run document level filtering on web documents using WebDocumentFilteringDocLevel with configurable thresholds', 'display original and filtered web documents side by side in the Streamlit visualization interface', 'load a HuggingFace dataset from disk and select a subset size like 100 or 1000 rows', 'select a random document from the loaded dataset using the choose_document method', 'display document texts and images from the current document using streamlit markdown']
```

Usage

```
{'run_visualization_app': 'run a streamlit app to visualize DOM tree simplification and text-image pair extraction on HTML documents', 'create_visualization_instance': 'create a Visualization instance with a number of documents and a DOM tree visualization template path', 'simplify_dom_tree': 'use DOMTreeSimplificator to strip tags, remove comments, and simplify an HTML DOM tree', 'extract_text_image_pairs': 'use TextMediaPairsExtractor to extract text-image pairs with CLIP scores from an HTML document', 'render_dom_tree_html': 'use get_dom_viz_html to render a DOM tree visualization from raw HTML using a Jinja2 template'}
```

## File: huggingface_OBELICS/obelics/visualization/web_document_and_filtering_visualization.py

Prompts

```
['run the streamlit app to visualize filtering parameter distributions for web documents at node level', 'compute statistics like word count and character repetition ratio across a web document dataset', 'extract text examples and compute multiple statistics from a HuggingFace dataset using get_exs_and_stats', 'filter out None elements from a list using the non_empty_els_from_list helper function', 'generate histograms of chosen statistics with configurable bins and percentile truncation for web documents', 'run a streamlit app to visualize DOM tree simplification and text-image pair extraction on HTML documents', 'create a Visualization instance with a number of documents and a DOM tree visualization template path', 'use DOMTreeSimplificator to strip tags, remove comments, and simplify an HTML DOM tree', 'use TextMediaPairsExtractor to extract text-image pairs with CLIP scores from an HTML document', 'use get_dom_viz_html to render a DOM tree visualization from raw HTML using a Jinja2 template', 'run node level filtering on web documents using WebDocumentFilteringNodeLevel with configurable thresholds', 'run document level filtering on web documents using WebDocumentFilteringDocLevel with configurable thresholds', 'display original and filtered web documents side by side in the Streamlit visualization interface', 'load a HuggingFace dataset from disk and select a subset size like 100 or 1000 rows', 'select a random document from the loaded dataset using the choose_document method', 'display document texts and images from the current document using streamlit markdown']
```

Usage

```
{'run_visualization_app': 'run the Streamlit app to visualize and filter web documents from an OBELICS dataset', 'create_visualization_instance': 'create a Visualization instance with paths to dataset, config, common words, and language models', 'run_node_level_filtering': 'run node level filtering on web documents using WebDocumentFilteringNodeLevel with configurable thresholds', 'run_doc_level_filtering': 'run document level filtering on web documents using WebDocumentFilteringDocLevel with configurable thresholds', 'display_filtered_documents': 'display original and filtered web documents side by side in the Streamlit visualization interface'}
```

## File: huggingface_OBELICS/obelics/visualization/web_document_visualization.py

Prompts

```
['run the streamlit app to visualize filtering parameter distributions for web documents at node level', 'compute statistics like word count and character repetition ratio across a web document dataset', 'extract text examples and compute multiple statistics from a HuggingFace dataset using get_exs_and_stats', 'filter out None elements from a list using the non_empty_els_from_list helper function', 'generate histograms of chosen statistics with configurable bins and percentile truncation for web documents', 'run a streamlit app to visualize DOM tree simplification and text-image pair extraction on HTML documents', 'create a Visualization instance with a number of documents and a DOM tree visualization template path', 'use DOMTreeSimplificator to strip tags, remove comments, and simplify an HTML DOM tree', 'use TextMediaPairsExtractor to extract text-image pairs with CLIP scores from an HTML document', 'use get_dom_viz_html to render a DOM tree visualization from raw HTML using a Jinja2 template', 'run node level filtering on web documents using WebDocumentFilteringNodeLevel with configurable thresholds', 'run document level filtering on web documents using WebDocumentFilteringDocLevel with configurable thresholds', 'display original and filtered web documents side by side in the Streamlit visualization interface', 'load a HuggingFace dataset from disk and select a subset size like 100 or 1000 rows', 'select a random document from the loaded dataset using the choose_document method', 'display document texts and images from the current document using streamlit markdown']
```

Usage

```
{'run_visualization_app': 'run the streamlit app to visualize web documents from a local dataset directory', 'create_visualization_instance': 'create a Visualization instance with a path to a web documents dataset on disk', 'load_dataset_select_size': 'load a HuggingFace dataset from disk and select a subset size like 100 or 1000 rows', 'choose_random_document': 'select a random document from the loaded dataset using the choose_document method', 'display_document_texts_images': 'display document texts and images from the current document using streamlit markdown'}
```

