# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/src/beanmachine/ppl/diagnostics/tools/utils/accessor.py

Prompts

```
['create a CachedAccessor descriptor to cache extension methods on a MonteCarloSamples object', 'build a CachedAccessor __get__ method to lazily instantiate and cache an accessor on an object', 'register a custom accessor class on MonteCarloSamples using the register_mcs_accessor decorator', 'refactor an existing class to use _register_accessor for attaching cached extension methods', 'review the CachedAccessor __init__ to understand how name and accessor class are stored', 'create a subclass of DiagnosticToolBaseClass that implements create_document to visualize MonteCarloSamples', 'show the diagnostic tool in a Jupyter notebook by calling the show method on a DiagnosticToolBaseClass instance', 'load the JavaScript bundle for a diagnostic tool from the yarn-built distribution directory', 'get the HTML template with CSS styles for Bokeh loading overlays on diagnostic tools', 'debug a diagnostic tool by calling _tool_json to get a JSON-serializable Bokeh document representation', 'convert Bean Machine MonteCarloSamples into a JSON serializable dictionary for diagnostics tools', 'serialize MCMC chain data from MonteCarloSamples into a flat list of float arrays', 'reshape multi-dimensional random variable chain data into indexed JSON serializable entries', 'review the serialize_bm function to understand how it handles 1D and 3D chain shapes', 'test the serialize_bm function with MonteCarloSamples containing multi-dimensional random variable data', 'style a Bokeh figure with grey grid lines and minor tick colors', 'choose a Bokeh Colorblind palette with the minimum number of colors needed', 'create a merged ToolbarBox from multiple Bokeh figures excluding HoverTool entries', 'create a grid layout of Bokeh figures with merged toolbars and hidden axis labels', 'filter GlyphRenderer objects in a Bokeh figure by exact or substring name match']
```

Usage

```
{'create_CachedAccessor': 'create a CachedAccessor descriptor to cache extension methods on a MonteCarloSamples object', 'build_CachedAccessor_get': 'build a CachedAccessor __get__ method to lazily instantiate and cache an accessor on an object', 'register_register_mcs_accessor': 'register a custom accessor class on MonteCarloSamples using the register_mcs_accessor decorator', 'refactor_register_accessor': 'refactor an existing class to use _register_accessor for attaching cached extension methods', 'review_CachedAccessor_init': 'review the CachedAccessor __init__ to understand how name and accessor class are stored'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/diagnostics/tools/utils/diagnostic_tool_base.py

Prompts

```
['create a CachedAccessor descriptor to cache extension methods on a MonteCarloSamples object', 'build a CachedAccessor __get__ method to lazily instantiate and cache an accessor on an object', 'register a custom accessor class on MonteCarloSamples using the register_mcs_accessor decorator', 'refactor an existing class to use _register_accessor for attaching cached extension methods', 'review the CachedAccessor __init__ to understand how name and accessor class are stored', 'create a subclass of DiagnosticToolBaseClass that implements create_document to visualize MonteCarloSamples', 'show the diagnostic tool in a Jupyter notebook by calling the show method on a DiagnosticToolBaseClass instance', 'load the JavaScript bundle for a diagnostic tool from the yarn-built distribution directory', 'get the HTML template with CSS styles for Bokeh loading overlays on diagnostic tools', 'debug a diagnostic tool by calling _tool_json to get a JSON-serializable Bokeh document representation', 'convert Bean Machine MonteCarloSamples into a JSON serializable dictionary for diagnostics tools', 'serialize MCMC chain data from MonteCarloSamples into a flat list of float arrays', 'reshape multi-dimensional random variable chain data into indexed JSON serializable entries', 'review the serialize_bm function to understand how it handles 1D and 3D chain shapes', 'test the serialize_bm function with MonteCarloSamples containing multi-dimensional random variable data', 'style a Bokeh figure with grey grid lines and minor tick colors', 'choose a Bokeh Colorblind palette with the minimum number of colors needed', 'create a merged ToolbarBox from multiple Bokeh figures excluding HoverTool entries', 'create a grid layout of Bokeh figures with merged toolbars and hidden axis labels', 'filter GlyphRenderer objects in a Bokeh figure by exact or substring name match']
```

Usage

```
{'create_diagnostic_tool': 'create a subclass of DiagnosticToolBaseClass that implements create_document to visualize MonteCarloSamples', 'show_diagnostic_tool': 'show the diagnostic tool in a Jupyter notebook by calling the show method on a DiagnosticToolBaseClass instance', 'load_tool_js': 'load the JavaScript bundle for a diagnostic tool from the yarn-built distribution directory', 'html_template_css': 'get the HTML template with CSS styles for Bokeh loading overlays on diagnostic tools', 'debug_tool_json': 'debug a diagnostic tool by calling _tool_json to get a JSON-serializable Bokeh document representation'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/diagnostics/tools/utils/model_serializers.py

Prompts

```
['create a CachedAccessor descriptor to cache extension methods on a MonteCarloSamples object', 'build a CachedAccessor __get__ method to lazily instantiate and cache an accessor on an object', 'register a custom accessor class on MonteCarloSamples using the register_mcs_accessor decorator', 'refactor an existing class to use _register_accessor for attaching cached extension methods', 'review the CachedAccessor __init__ to understand how name and accessor class are stored', 'create a subclass of DiagnosticToolBaseClass that implements create_document to visualize MonteCarloSamples', 'show the diagnostic tool in a Jupyter notebook by calling the show method on a DiagnosticToolBaseClass instance', 'load the JavaScript bundle for a diagnostic tool from the yarn-built distribution directory', 'get the HTML template with CSS styles for Bokeh loading overlays on diagnostic tools', 'debug a diagnostic tool by calling _tool_json to get a JSON-serializable Bokeh document representation', 'convert Bean Machine MonteCarloSamples into a JSON serializable dictionary for diagnostics tools', 'serialize MCMC chain data from MonteCarloSamples into a flat list of float arrays', 'reshape multi-dimensional random variable chain data into indexed JSON serializable entries', 'review the serialize_bm function to understand how it handles 1D and 3D chain shapes', 'test the serialize_bm function with MonteCarloSamples containing multi-dimensional random variable data', 'style a Bokeh figure with grey grid lines and minor tick colors', 'choose a Bokeh Colorblind palette with the minimum number of colors needed', 'create a merged ToolbarBox from multiple Bokeh figures excluding HoverTool entries', 'create a grid layout of Bokeh figures with merged toolbars and hidden axis labels', 'filter GlyphRenderer objects in a Bokeh figure by exact or substring name match']
```

Usage

```
{'serialize_bm_samples': 'convert Bean Machine MonteCarloSamples into a JSON serializable dictionary for diagnostics tools', 'serialize_bm_chains': 'serialize MCMC chain data from MonteCarloSamples into a flat list of float arrays', 'serialize_bm_multidimensional': 'reshape multi-dimensional random variable chain data into indexed JSON serializable entries', 'review_serialize_bm': 'review the serialize_bm function to understand how it handles 1D and 3D chain shapes', 'test_serialize_bm': 'test the serialize_bm function with MonteCarloSamples containing multi-dimensional random variable data'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/diagnostics/tools/utils/plotting_utils.py

Prompts

```
['create a CachedAccessor descriptor to cache extension methods on a MonteCarloSamples object', 'build a CachedAccessor __get__ method to lazily instantiate and cache an accessor on an object', 'register a custom accessor class on MonteCarloSamples using the register_mcs_accessor decorator', 'refactor an existing class to use _register_accessor for attaching cached extension methods', 'review the CachedAccessor __init__ to understand how name and accessor class are stored', 'create a subclass of DiagnosticToolBaseClass that implements create_document to visualize MonteCarloSamples', 'show the diagnostic tool in a Jupyter notebook by calling the show method on a DiagnosticToolBaseClass instance', 'load the JavaScript bundle for a diagnostic tool from the yarn-built distribution directory', 'get the HTML template with CSS styles for Bokeh loading overlays on diagnostic tools', 'debug a diagnostic tool by calling _tool_json to get a JSON-serializable Bokeh document representation', 'convert Bean Machine MonteCarloSamples into a JSON serializable dictionary for diagnostics tools', 'serialize MCMC chain data from MonteCarloSamples into a flat list of float arrays', 'reshape multi-dimensional random variable chain data into indexed JSON serializable entries', 'review the serialize_bm function to understand how it handles 1D and 3D chain shapes', 'test the serialize_bm function with MonteCarloSamples containing multi-dimensional random variable data', 'style a Bokeh figure with grey grid lines and minor tick colors', 'choose a Bokeh Colorblind palette with the minimum number of colors needed', 'create a merged ToolbarBox from multiple Bokeh figures excluding HoverTool entries', 'create a grid layout of Bokeh figures with merged toolbars and hidden axis labels', 'filter GlyphRenderer objects in a Bokeh figure by exact or substring name match']
```

Usage

```
{'style_bokeh_figure': 'style a Bokeh figure with grey grid lines and minor tick colors', 'choose_colorblind_palette': 'choose a Bokeh Colorblind palette with the minimum number of colors needed', 'create_merged_toolbar': 'create a merged ToolbarBox from multiple Bokeh figures excluding HoverTool entries', 'create_figure_grid_layout': 'create a grid layout of Bokeh figures with merged toolbars and hidden axis labels', 'filter_figure_renderers': 'filter GlyphRenderer objects in a Bokeh figure by exact or substring name match'}
```

