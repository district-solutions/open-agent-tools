# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/extensions/labgraph_viz/labgraph_viz/examples/application_example.py

Prompts

```
['run the Demo graph to start a labgraph visualization with bar and line plots', 'create a Generator node that publishes random bar plot and line plot messages at a configurable sample rate', 'configure a BarPlot with x_field and y_field mapping to message attributes using BarPlotConfig', 'configure a LinePlot in append mode with a window size using LinePlotConfig and Mode.APPEND', 'setup an Application with a title, dimensions, and external timer then add LinePlot and BarPlot to it', 'run the Demo graph to display a live bar plot with random data using labgraph', 'create a Window node that builds a pyqtgraph GraphicsWindow and displays a BarPlot widget', 'setup a SimpleVizGroup that connects input messages to a BarPlot and embeds it in a Window node', 'run the Demo graph to display a live heatmap and colormap visualization window', 'configure a HeatMap plot with data, channel_map, shape, and external_timer settings', 'build a SimpleVizGroup that connects HeatMap and ColorMap plots to a shared input topic', 'run a labgraph Graph with lg.run to start the Demo visualization pipeline', 'run the Demo graph to visualize live noise data with LinePlot in a pyqtgraph window', 'configure a LinePlot with Mode.APPEND and window_size to display a scrolling window of appended samples', 'configure a LinePlot with Mode.UPDATE to overwrite existing data on each incoming message', 'build a Window node that creates a pyqtgraph GraphicsWindow and adds LinePlot items to it', 'run the Demo graph to display a scatter plot with random red and green data points', 'configure a ScatterPlot with x and y fields, axis labels, and named styles for red and green data series', 'setup a SimpleVizGroup that connects input messages to a ScatterPlot and wires it to a Window node', 'run the labgraph Demo graph to visualize random data with a SpatialPlot in a PyQt window', 'configure a SpatialPlot with SpatialPlotConfig including color maps, labels, and point positions']
```

Usage

```
{'run_labgraph_viz_demo': 'run the Demo graph to start a labgraph visualization with bar and line plots', 'create_generator_node': 'create a Generator node that publishes random bar plot and line plot messages at a configurable sample rate', 'configure_bar_plot': 'configure a BarPlot with x_field and y_field mapping to message attributes using BarPlotConfig', 'configure_line_plot': 'configure a LinePlot in append mode with a window size using LinePlotConfig and Mode.APPEND', 'setup_application_with_plots': 'setup an Application with a title, dimensions, and external timer then add LinePlot and BarPlot to it'}
```

## File: facebookresearch_labgraph/extensions/labgraph_viz/labgraph_viz/examples/bar_plot_example.py

Prompts

```
['run the Demo graph to start a labgraph visualization with bar and line plots', 'create a Generator node that publishes random bar plot and line plot messages at a configurable sample rate', 'configure a BarPlot with x_field and y_field mapping to message attributes using BarPlotConfig', 'configure a LinePlot in append mode with a window size using LinePlotConfig and Mode.APPEND', 'setup an Application with a title, dimensions, and external timer then add LinePlot and BarPlot to it', 'run the Demo graph to display a live bar plot with random data using labgraph', 'create a Window node that builds a pyqtgraph GraphicsWindow and displays a BarPlot widget', 'setup a SimpleVizGroup that connects input messages to a BarPlot and embeds it in a Window node', 'run the Demo graph to display a live heatmap and colormap visualization window', 'configure a HeatMap plot with data, channel_map, shape, and external_timer settings', 'build a SimpleVizGroup that connects HeatMap and ColorMap plots to a shared input topic', 'run a labgraph Graph with lg.run to start the Demo visualization pipeline', 'run the Demo graph to visualize live noise data with LinePlot in a pyqtgraph window', 'configure a LinePlot with Mode.APPEND and window_size to display a scrolling window of appended samples', 'configure a LinePlot with Mode.UPDATE to overwrite existing data on each incoming message', 'build a Window node that creates a pyqtgraph GraphicsWindow and adds LinePlot items to it', 'run the Demo graph to display a scatter plot with random red and green data points', 'configure a ScatterPlot with x and y fields, axis labels, and named styles for red and green data series', 'setup a SimpleVizGroup that connects input messages to a ScatterPlot and wires it to a Window node', 'run the labgraph Demo graph to visualize random data with a SpatialPlot in a PyQt window', 'configure a SpatialPlot with SpatialPlotConfig including color maps, labels, and point positions']
```

Usage

```
{'run_bar_plot_demo': 'run the Demo graph to display a live bar plot with random data using labgraph', 'create_generator_node': 'create a Generator node that publishes RandomMessage with domain and range numpy arrays at a configurable sample rate', 'configure_bar_plot': 'configure a BarPlot with BarPlotConfig specifying x_field, y_field, and pyqtgraph style labels for title and axes', 'create_window_node': 'create a Window node that builds a pyqtgraph GraphicsWindow and displays a BarPlot widget', 'setup_simple_viz_group': 'setup a SimpleVizGroup that connects input messages to a BarPlot and embeds it in a Window node'}
```

## File: facebookresearch_labgraph/extensions/labgraph_viz/labgraph_viz/examples/heat_map_example.py

Prompts

```
['run the Demo graph to start a labgraph visualization with bar and line plots', 'create a Generator node that publishes random bar plot and line plot messages at a configurable sample rate', 'configure a BarPlot with x_field and y_field mapping to message attributes using BarPlotConfig', 'configure a LinePlot in append mode with a window size using LinePlotConfig and Mode.APPEND', 'setup an Application with a title, dimensions, and external timer then add LinePlot and BarPlot to it', 'run the Demo graph to display a live bar plot with random data using labgraph', 'create a Window node that builds a pyqtgraph GraphicsWindow and displays a BarPlot widget', 'setup a SimpleVizGroup that connects input messages to a BarPlot and embeds it in a Window node', 'run the Demo graph to display a live heatmap and colormap visualization window', 'configure a HeatMap plot with data, channel_map, shape, and external_timer settings', 'build a SimpleVizGroup that connects HeatMap and ColorMap plots to a shared input topic', 'run a labgraph Graph with lg.run to start the Demo visualization pipeline', 'run the Demo graph to visualize live noise data with LinePlot in a pyqtgraph window', 'configure a LinePlot with Mode.APPEND and window_size to display a scrolling window of appended samples', 'configure a LinePlot with Mode.UPDATE to overwrite existing data on each incoming message', 'build a Window node that creates a pyqtgraph GraphicsWindow and adds LinePlot items to it', 'run the Demo graph to display a scatter plot with random red and green data points', 'configure a ScatterPlot with x and y fields, axis labels, and named styles for red and green data series', 'setup a SimpleVizGroup that connects input messages to a ScatterPlot and wires it to a Window node', 'run the labgraph Demo graph to visualize random data with a SpatialPlot in a PyQt window', 'configure a SpatialPlot with SpatialPlotConfig including color maps, labels, and point positions']
```

Usage

```
{'run_heatmap_demo': 'run the Demo graph to display a live heatmap and colormap visualization window', 'create_generator_node': 'create a Generator node that yields random HeatMapMessage data at a configured sample rate', 'configure_heatmap_plot': 'configure a HeatMap plot with data, channel_map, shape, and external_timer settings', 'build_viz_group': 'build a SimpleVizGroup that connects HeatMap and ColorMap plots to a shared input topic', 'run_labgraph_graph': 'run a labgraph Graph with lg.run to start the Demo visualization pipeline'}
```

## File: facebookresearch_labgraph/extensions/labgraph_viz/labgraph_viz/examples/line_plot_example.py

Prompts

```
['run the Demo graph to start a labgraph visualization with bar and line plots', 'create a Generator node that publishes random bar plot and line plot messages at a configurable sample rate', 'configure a BarPlot with x_field and y_field mapping to message attributes using BarPlotConfig', 'configure a LinePlot in append mode with a window size using LinePlotConfig and Mode.APPEND', 'setup an Application with a title, dimensions, and external timer then add LinePlot and BarPlot to it', 'run the Demo graph to display a live bar plot with random data using labgraph', 'create a Window node that builds a pyqtgraph GraphicsWindow and displays a BarPlot widget', 'setup a SimpleVizGroup that connects input messages to a BarPlot and embeds it in a Window node', 'run the Demo graph to display a live heatmap and colormap visualization window', 'configure a HeatMap plot with data, channel_map, shape, and external_timer settings', 'build a SimpleVizGroup that connects HeatMap and ColorMap plots to a shared input topic', 'run a labgraph Graph with lg.run to start the Demo visualization pipeline', 'run the Demo graph to visualize live noise data with LinePlot in a pyqtgraph window', 'configure a LinePlot with Mode.APPEND and window_size to display a scrolling window of appended samples', 'configure a LinePlot with Mode.UPDATE to overwrite existing data on each incoming message', 'build a Window node that creates a pyqtgraph GraphicsWindow and adds LinePlot items to it', 'run the Demo graph to display a scatter plot with random red and green data points', 'configure a ScatterPlot with x and y fields, axis labels, and named styles for red and green data series', 'setup a SimpleVizGroup that connects input messages to a ScatterPlot and wires it to a Window node', 'run the labgraph Demo graph to visualize random data with a SpatialPlot in a PyQt window', 'configure a SpatialPlot with SpatialPlotConfig including color maps, labels, and point positions']
```

Usage

```
{'run_line_plot_demo': 'run the Demo graph to visualize live noise data with LinePlot in a pyqtgraph window', 'create_generator_node': 'create a Generator node that publishes AppendMessage and UpdateMessage topics at a configurable sample rate', 'configure_lineplot_append_mode': 'configure a LinePlot with Mode.APPEND and window_size to display a scrolling window of appended samples', 'configure_lineplot_update_mode': 'configure a LinePlot with Mode.UPDATE to overwrite existing data on each incoming message', 'build_window_node': 'build a Window node that creates a pyqtgraph GraphicsWindow and adds LinePlot items to it'}
```

## File: facebookresearch_labgraph/extensions/labgraph_viz/labgraph_viz/examples/scatter_plot_example.py

Prompts

```
['run the Demo graph to start a labgraph visualization with bar and line plots', 'create a Generator node that publishes random bar plot and line plot messages at a configurable sample rate', 'configure a BarPlot with x_field and y_field mapping to message attributes using BarPlotConfig', 'configure a LinePlot in append mode with a window size using LinePlotConfig and Mode.APPEND', 'setup an Application with a title, dimensions, and external timer then add LinePlot and BarPlot to it', 'run the Demo graph to display a live bar plot with random data using labgraph', 'create a Window node that builds a pyqtgraph GraphicsWindow and displays a BarPlot widget', 'setup a SimpleVizGroup that connects input messages to a BarPlot and embeds it in a Window node', 'run the Demo graph to display a live heatmap and colormap visualization window', 'configure a HeatMap plot with data, channel_map, shape, and external_timer settings', 'build a SimpleVizGroup that connects HeatMap and ColorMap plots to a shared input topic', 'run a labgraph Graph with lg.run to start the Demo visualization pipeline', 'run the Demo graph to visualize live noise data with LinePlot in a pyqtgraph window', 'configure a LinePlot with Mode.APPEND and window_size to display a scrolling window of appended samples', 'configure a LinePlot with Mode.UPDATE to overwrite existing data on each incoming message', 'build a Window node that creates a pyqtgraph GraphicsWindow and adds LinePlot items to it', 'run the Demo graph to display a scatter plot with random red and green data points', 'configure a ScatterPlot with x and y fields, axis labels, and named styles for red and green data series', 'setup a SimpleVizGroup that connects input messages to a ScatterPlot and wires it to a Window node', 'run the labgraph Demo graph to visualize random data with a SpatialPlot in a PyQt window', 'configure a SpatialPlot with SpatialPlotConfig including color maps, labels, and point positions']
```

Usage

```
{'run_scatter_plot_demo': 'run the Demo graph to display a scatter plot with random red and green data points', 'create_generator_node': 'create a Generator node that publishes RandomMessage with random x and y coordinates at a configurable sample rate', 'configure_scatter_plot': 'configure a ScatterPlot with x and y fields, axis labels, and named styles for red and green data series', 'build_window_node': 'build a Window node that creates a pyqtgraph GraphicsWindow and displays a ScatterPlot inside it', 'setup_viz_group': 'setup a SimpleVizGroup that connects input messages to a ScatterPlot and wires it to a Window node'}
```

## File: facebookresearch_labgraph/extensions/labgraph_viz/labgraph_viz/examples/spatial_plot_example.py

Prompts

```
['run the Demo graph to start a labgraph visualization with bar and line plots', 'create a Generator node that publishes random bar plot and line plot messages at a configurable sample rate', 'configure a BarPlot with x_field and y_field mapping to message attributes using BarPlotConfig', 'configure a LinePlot in append mode with a window size using LinePlotConfig and Mode.APPEND', 'setup an Application with a title, dimensions, and external timer then add LinePlot and BarPlot to it', 'run the Demo graph to display a live bar plot with random data using labgraph', 'create a Window node that builds a pyqtgraph GraphicsWindow and displays a BarPlot widget', 'setup a SimpleVizGroup that connects input messages to a BarPlot and embeds it in a Window node', 'run the Demo graph to display a live heatmap and colormap visualization window', 'configure a HeatMap plot with data, channel_map, shape, and external_timer settings', 'build a SimpleVizGroup that connects HeatMap and ColorMap plots to a shared input topic', 'run a labgraph Graph with lg.run to start the Demo visualization pipeline', 'run the Demo graph to visualize live noise data with LinePlot in a pyqtgraph window', 'configure a LinePlot with Mode.APPEND and window_size to display a scrolling window of appended samples', 'configure a LinePlot with Mode.UPDATE to overwrite existing data on each incoming message', 'build a Window node that creates a pyqtgraph GraphicsWindow and adds LinePlot items to it', 'run the Demo graph to display a scatter plot with random red and green data points', 'configure a ScatterPlot with x and y fields, axis labels, and named styles for red and green data series', 'setup a SimpleVizGroup that connects input messages to a ScatterPlot and wires it to a Window node', 'run the labgraph Demo graph to visualize random data with a SpatialPlot in a PyQt window', 'configure a SpatialPlot with SpatialPlotConfig including color maps, labels, and point positions']
```

Usage

```
{'run_spatial_plot_demo': 'run the labgraph Demo graph to visualize random data with a SpatialPlot in a PyQt window', 'create_generator_node': 'create a labgraph Generator node that publishes RandomMessage data at a configurable sample rate', 'configure_spatial_plot': 'configure a SpatialPlot with SpatialPlotConfig including color maps, labels, and point positions', 'build_window_node': 'build a labgraph Window node that creates a PyQt GraphicsWindow and displays a SpatialPlot', 'setup_viz_group': 'setup a SimpleVizGroup that connects input messages to a SpatialPlot and displays them in a Window'}
```

