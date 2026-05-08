# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/python/craftassist/voxel_models/geoscorer.py

Prompts

```
['create a Geoscorer instance by providing a merger model path to initialize the ContextSegmentMergerWrapper', 'check if geoscorer should be used by calling use with steps, repeat_num, and rel_dir parameters', 'produce the segment position in context by calling produce_segment_pos_in_context with segment, context, and brc', 'process a sparse voxel segment into an 8x8x8 densified tensor shifted to origin using _process_segment', 'review the Geoscorer blacklist of unsupported relative directions including BETWEEN, INSIDE, AWAY, and NEAR', 'run the CLI tool to create a new segmentation dataset from house data and segmentation pickle files', 'create a block ID vocabulary by scanning all house schematics and mapping unique block-meta pairs to integers', 'transform segmentation data items by replacing block-meta pairs with vocabulary IDs using house schematics', 'extract unique block-meta pairs from a house schematic numpy array by iterating over all voxel coordinates', 'load a house schematic numpy array from a schematic.npy file in the given house directory', 'create a SchematicPlotter instance with a visdom visualization backend for plotting voxel schematics', 'use SchematicPlotter drawPlotly to render a 3D scatter plot of voxel data in visdom', 'use SchematicPlotter drawMatplot to render a 3D matplotlib figure of voxel blocks with Minecraft colors', 'call draw_color_hash to visualize a hash-binned voxel schematic as a colored 3D scatter in visdom', 'call plotCubeAt to draw a single colored cube at a given 3D position on a matplotlib axis', 'create a SubcomponentClassifierWrapper with an agent, model path, vocab path, and perception frequency', 'run perceive on the SubcomponentClassifierWrapper to label nearby block objects and store results in memory', 'start a SubComponentClassifier process with a voxel model path and vocab path for block recognition', 'recognize a list of tuple blocks using SubComponentClassifier recognize method to get tag labels', 'review the _watch_single_object method to understand how block tuples are converted to location tag pairs']
```

Usage

```
{'create_geoscorer_instance': 'create a Geoscorer instance by providing a merger model path to initialize the ContextSegmentMergerWrapper', 'check_geoscorer_use': 'check if geoscorer should be used by calling use with steps, repeat_num, and rel_dir parameters', 'produce_segment_position': 'produce the segment position in context by calling produce_segment_pos_in_context with segment, context, and brc', 'process_voxel_segment': 'process a sparse voxel segment into an 8x8x8 densified tensor shifted to origin using _process_segment', 'review_geoscorer_blacklist': 'review the Geoscorer blacklist of unsupported relative directions including BETWEEN, INSIDE, AWAY, and NEAR'}
```

## File: facebookresearch_craftassist/python/craftassist/voxel_models/make_seg_ds.py

Prompts

```
['create a Geoscorer instance by providing a merger model path to initialize the ContextSegmentMergerWrapper', 'check if geoscorer should be used by calling use with steps, repeat_num, and rel_dir parameters', 'produce the segment position in context by calling produce_segment_pos_in_context with segment, context, and brc', 'process a sparse voxel segment into an 8x8x8 densified tensor shifted to origin using _process_segment', 'review the Geoscorer blacklist of unsupported relative directions including BETWEEN, INSIDE, AWAY, and NEAR', 'run the CLI tool to create a new segmentation dataset from house data and segmentation pickle files', 'create a block ID vocabulary by scanning all house schematics and mapping unique block-meta pairs to integers', 'transform segmentation data items by replacing block-meta pairs with vocabulary IDs using house schematics', 'extract unique block-meta pairs from a house schematic numpy array by iterating over all voxel coordinates', 'load a house schematic numpy array from a schematic.npy file in the given house directory', 'create a SchematicPlotter instance with a visdom visualization backend for plotting voxel schematics', 'use SchematicPlotter drawPlotly to render a 3D scatter plot of voxel data in visdom', 'use SchematicPlotter drawMatplot to render a 3D matplotlib figure of voxel blocks with Minecraft colors', 'call draw_color_hash to visualize a hash-binned voxel schematic as a colored 3D scatter in visdom', 'call plotCubeAt to draw a single colored cube at a given 3D position on a matplotlib axis', 'create a SubcomponentClassifierWrapper with an agent, model path, vocab path, and perception frequency', 'run perceive on the SubcomponentClassifierWrapper to label nearby block objects and store results in memory', 'start a SubComponentClassifier process with a voxel model path and vocab path for block recognition', 'recognize a list of tuple blocks using SubComponentClassifier recognize method to get tag labels', 'review the _watch_single_object method to understand how block tuples are converted to location tag pairs']
```

Usage

```
{'run_make_seg_ds_cli': 'run the CLI tool to create a new segmentation dataset from house data and segmentation pickle files', 'create_id_vocabulary': 'create a block ID vocabulary by scanning all house schematics and mapping unique block-meta pairs to integers', 'transform_segmentation_data': 'transform segmentation data items by replacing block-meta pairs with vocabulary IDs using house schematics', 'extract_unique_block_pairs': 'extract unique block-meta pairs from a house schematic numpy array by iterating over all voxel coordinates', 'load_house_schematic': 'load a house schematic numpy array from a schematic.npy file in the given house directory'}
```

## File: facebookresearch_craftassist/python/craftassist/voxel_models/plot_voxels.py

Prompts

```
['create a Geoscorer instance by providing a merger model path to initialize the ContextSegmentMergerWrapper', 'check if geoscorer should be used by calling use with steps, repeat_num, and rel_dir parameters', 'produce the segment position in context by calling produce_segment_pos_in_context with segment, context, and brc', 'process a sparse voxel segment into an 8x8x8 densified tensor shifted to origin using _process_segment', 'review the Geoscorer blacklist of unsupported relative directions including BETWEEN, INSIDE, AWAY, and NEAR', 'run the CLI tool to create a new segmentation dataset from house data and segmentation pickle files', 'create a block ID vocabulary by scanning all house schematics and mapping unique block-meta pairs to integers', 'transform segmentation data items by replacing block-meta pairs with vocabulary IDs using house schematics', 'extract unique block-meta pairs from a house schematic numpy array by iterating over all voxel coordinates', 'load a house schematic numpy array from a schematic.npy file in the given house directory', 'create a SchematicPlotter instance with a visdom visualization backend for plotting voxel schematics', 'use SchematicPlotter drawPlotly to render a 3D scatter plot of voxel data in visdom', 'use SchematicPlotter drawMatplot to render a 3D matplotlib figure of voxel blocks with Minecraft colors', 'call draw_color_hash to visualize a hash-binned voxel schematic as a colored 3D scatter in visdom', 'call plotCubeAt to draw a single colored cube at a given 3D position on a matplotlib axis', 'create a SubcomponentClassifierWrapper with an agent, model path, vocab path, and perception frequency', 'run perceive on the SubcomponentClassifierWrapper to label nearby block objects and store results in memory', 'start a SubComponentClassifier process with a voxel model path and vocab path for block recognition', 'recognize a list of tuple blocks using SubComponentClassifier recognize method to get tag labels', 'review the _watch_single_object method to understand how block tuples are converted to location tag pairs']
```

Usage

```
{'create_schematic_plotter': 'create a SchematicPlotter instance with a visdom visualization backend for plotting voxel schematics', 'draw_plotly_scatter': 'use SchematicPlotter drawPlotly to render a 3D scatter plot of voxel data in visdom', 'draw_matplot_3d': 'use SchematicPlotter drawMatplot to render a 3D matplotlib figure of voxel blocks with Minecraft colors', 'draw_color_hash_visdom': 'call draw_color_hash to visualize a hash-binned voxel schematic as a colored 3D scatter in visdom', 'plot_cube_at_position': 'call plotCubeAt to draw a single colored cube at a given 3D position on a matplotlib axis'}
```

## File: facebookresearch_craftassist/python/craftassist/voxel_models/subcomponent_classifier.py

Prompts

```
['create a Geoscorer instance by providing a merger model path to initialize the ContextSegmentMergerWrapper', 'check if geoscorer should be used by calling use with steps, repeat_num, and rel_dir parameters', 'produce the segment position in context by calling produce_segment_pos_in_context with segment, context, and brc', 'process a sparse voxel segment into an 8x8x8 densified tensor shifted to origin using _process_segment', 'review the Geoscorer blacklist of unsupported relative directions including BETWEEN, INSIDE, AWAY, and NEAR', 'run the CLI tool to create a new segmentation dataset from house data and segmentation pickle files', 'create a block ID vocabulary by scanning all house schematics and mapping unique block-meta pairs to integers', 'transform segmentation data items by replacing block-meta pairs with vocabulary IDs using house schematics', 'extract unique block-meta pairs from a house schematic numpy array by iterating over all voxel coordinates', 'load a house schematic numpy array from a schematic.npy file in the given house directory', 'create a SchematicPlotter instance with a visdom visualization backend for plotting voxel schematics', 'use SchematicPlotter drawPlotly to render a 3D scatter plot of voxel data in visdom', 'use SchematicPlotter drawMatplot to render a 3D matplotlib figure of voxel blocks with Minecraft colors', 'call draw_color_hash to visualize a hash-binned voxel schematic as a colored 3D scatter in visdom', 'call plotCubeAt to draw a single colored cube at a given 3D position on a matplotlib axis', 'create a SubcomponentClassifierWrapper with an agent, model path, vocab path, and perception frequency', 'run perceive on the SubcomponentClassifierWrapper to label nearby block objects and store results in memory', 'start a SubComponentClassifier process with a voxel model path and vocab path for block recognition', 'recognize a list of tuple blocks using SubComponentClassifier recognize method to get tag labels', 'review the _watch_single_object method to understand how block tuples are converted to location tag pairs']
```

Usage

```
{'create_subcomponent_classifier_wrapper': 'create a SubcomponentClassifierWrapper with an agent, model path, vocab path, and perception frequency', 'run_perceive_on_wrapper': 'run perceive on the SubcomponentClassifierWrapper to label nearby block objects and store results in memory', 'start_subcomponent_classifier_process': 'start a SubComponentClassifier process with a voxel model path and vocab path for block recognition', 'recognize_block_objects': 'recognize a list of tuple blocks using SubComponentClassifier recognize method to get tag labels', 'review_watch_single_object': 'review the _watch_single_object method to understand how block tuples are converted to location tag pairs'}
```

