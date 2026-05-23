# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/scripts/prediviz/entities/legends/diff_args_legend.py

Prompts

```
['create a DiffArgsLegend instance with config, diff_args, receptacle_icon_mapping, and propositions to visualize entity differences', 'plot a DiffArgsLegend on a matplotlib axis at a given position to render bipartite entity comparison graphs', 'build NetworkX bipartite graphs from diff_args data mapping different entities to corresponding entities with edge styles and colors', 'render a column of Object, Receptacle, or TinyRoom entities on a matplotlib axis at specified midpoint and height', 'draw colored styled lines between left and right entity pairs on a matplotlib axis with endpoint markers', 'create an IsNextToLegend instance with config, is_next_tos relations, and receptacle icon mapping', 'plot the next-to legend visualization showing bipartite entity relationships on a matplotlib axis', 'create a SameArgsLegend instance with config, same_args, receptacle_icon_mapping, and propositions to build a same-as legend visualization', 'plot the SameArgsLegend at a given position on a matplotlib axis to render the same-as legend with entities and connecting lines', 'build NetworkX bipartite graphs from same_args data mapping common entities to corresponding entities with edge styles and colors', 'calculate the total height of the legend based on entity types and spacing across left and right bipartite sets', 'draw colored connecting lines between left and right entities on the matplotlib axis with endpoint markers']
```

Usage

```
{'create_diff_args_legend': 'create a DiffArgsLegend instance with config, diff_args, receptacle_icon_mapping, and propositions to visualize entity differences', 'plot_diff_args_legend': 'plot a DiffArgsLegend on a matplotlib axis at a given position to render bipartite entity comparison graphs', 'set_graph_and_bipartite_sets': 'build NetworkX bipartite graphs from diff_args data mapping different entities to corresponding entities with edge styles and colors', 'plot_entity_column': 'render a column of Object, Receptacle, or TinyRoom entities on a matplotlib axis at specified midpoint and height', 'plot_lines': 'draw colored styled lines between left and right entity pairs on a matplotlib axis with endpoint markers'}
```

## File: facebookresearch_partnr-planner/scripts/prediviz/entities/legends/is_next_to_legend.py

Prompts

```
['create a DiffArgsLegend instance with config, diff_args, receptacle_icon_mapping, and propositions to visualize entity differences', 'plot a DiffArgsLegend on a matplotlib axis at a given position to render bipartite entity comparison graphs', 'build NetworkX bipartite graphs from diff_args data mapping different entities to corresponding entities with edge styles and colors', 'render a column of Object, Receptacle, or TinyRoom entities on a matplotlib axis at specified midpoint and height', 'draw colored styled lines between left and right entity pairs on a matplotlib axis with endpoint markers', 'create an IsNextToLegend instance with config, is_next_tos relations, and receptacle icon mapping', 'plot the next-to legend visualization showing bipartite entity relationships on a matplotlib axis', 'create a SameArgsLegend instance with config, same_args, receptacle_icon_mapping, and propositions to build a same-as legend visualization', 'plot the SameArgsLegend at a given position on a matplotlib axis to render the same-as legend with entities and connecting lines', 'build NetworkX bipartite graphs from same_args data mapping common entities to corresponding entities with edge styles and colors', 'calculate the total height of the legend based on entity types and spacing across left and right bipartite sets', 'draw colored connecting lines between left and right entities on the matplotlib axis with endpoint markers']
```

Usage

```
{'create_IsNextToLegend': 'create an IsNextToLegend instance with config, is_next_tos relations, and receptacle icon mapping', 'plot_IsNextToLegend': 'plot the next-to legend visualization showing bipartite entity relationships on a matplotlib axis', 'set_graph_and_bipartite_sets': 'build a NetworkX bipartite graph from is_next_to relations separating entities into left and right sets', 'plot_entity_column': 'render a column of object and receptacle entities at calculated positions on the matplotlib axis', 'plot_lines': 'draw connecting lines between left and right entities with solid or dotted styles based on relationship confidence'}
```

## File: facebookresearch_partnr-planner/scripts/prediviz/entities/legends/same_args_legend.py

Prompts

```
['create a DiffArgsLegend instance with config, diff_args, receptacle_icon_mapping, and propositions to visualize entity differences', 'plot a DiffArgsLegend on a matplotlib axis at a given position to render bipartite entity comparison graphs', 'build NetworkX bipartite graphs from diff_args data mapping different entities to corresponding entities with edge styles and colors', 'render a column of Object, Receptacle, or TinyRoom entities on a matplotlib axis at specified midpoint and height', 'draw colored styled lines between left and right entity pairs on a matplotlib axis with endpoint markers', 'create an IsNextToLegend instance with config, is_next_tos relations, and receptacle icon mapping', 'plot the next-to legend visualization showing bipartite entity relationships on a matplotlib axis', 'create a SameArgsLegend instance with config, same_args, receptacle_icon_mapping, and propositions to build a same-as legend visualization', 'plot the SameArgsLegend at a given position on a matplotlib axis to render the same-as legend with entities and connecting lines', 'build NetworkX bipartite graphs from same_args data mapping common entities to corresponding entities with edge styles and colors', 'calculate the total height of the legend based on entity types and spacing across left and right bipartite sets', 'draw colored connecting lines between left and right entities on the matplotlib axis with endpoint markers']
```

Usage

```
{'create_SameArgsLegend': 'create a SameArgsLegend instance with config, same_args, receptacle_icon_mapping, and propositions to build a same-as legend visualization', 'plot_SameArgsLegend': 'plot the SameArgsLegend at a given position on a matplotlib axis to render the same-as legend with entities and connecting lines', 'set_graph_and_bipartite_sets_SameArgsLegend': 'build NetworkX bipartite graphs from same_args data mapping common entities to corresponding entities with edge styles and colors', 'set_height_SameArgsLegend': 'calculate the total height of the legend based on entity types and spacing across left and right bipartite sets', 'plot_lines_SameArgsLegend': 'draw colored connecting lines between left and right entities on the matplotlib axis with endpoint markers'}
```

