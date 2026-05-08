# Agent Python Tools

- repo: facebookresearch/many-to-many-dijkstra
- repo_uri: https://github.com/facebookresearch/many-to-many-dijkstra

## File: facebookresearch_many-to-many-dijkstra/pathfinder.py

Prompts

```
['run the seek function to find shortest paths between origins and targets on a weighted 2D grid', 'run seek with link path handling to grow a connected network by adding found paths as new origins', 'run seek with assimilate path handling to add found targets as origins without connecting paths', 'run seek with none path handling to find paths from a backbone to many leaf nodes', 'run seek with film mode enabled to periodically save PNG snapshots of algorithm progress']
```

Usage

```
{'run_seek_shortest_paths': 'run the seek function to find shortest paths between origins and targets on a weighted 2D grid', 'run_seek_with_link_mode': 'run seek with link path handling to grow a connected network by adding found paths as new origins', 'run_seek_with_assimilate_mode': 'run seek with assimilate path handling to add found targets as origins without connecting paths', 'run_seek_with_none_mode': 'run seek with none path handling to find paths from a backbone to many leaf nodes', 'run_seek_with_film_mode': 'run seek with film mode enabled to periodically save PNG snapshots of algorithm progress'}
```

