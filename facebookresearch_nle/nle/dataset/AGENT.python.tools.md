# Agent Python Tools

- repo: facebookresearch/nle
- repo_uri: https://github.com/facebookresearch/nle

## File: facebookresearch_nle/nle/dataset/dataset.py

Prompts

```
['create a TtyrecDataset to iterate over NetHack ttyrec game recordings from a named dataset', 'iterate over a TtyrecDataset to yield minibatches of tty_chars, tty_colors, and cursor tensors', 'fetch chunked tensor data for multiple game IDs using the get_ttyrecs method', 'fetch chunked tensor data for a single game ID using the get_ttyrec method', 'query game metadata for a given game ID using the get_meta method on TtyrecDataset', 'create a new SQLite database with tables for ttyrecs, games, datasets, roots, and meta', 'list all ttyrecs rows with their rowid and path from the database', 'get all games with name, gameid, starttime, and endtime for a given dataset name', 'add multiple game IDs to a named dataset in the database', 'get the N most recent game IDs ordered by gameid descending', 'add an altorg dataset directory to the NLE database by parsing xlogfiles and matching ttyrecs to games', 'add an NLE data directory to the database by reading xlogfiles and inserting games and ttyrecs', "assign a player's ttyrec recordings to their NetHack games using a timestamp-based matching algorithm", 'parse an alt.org ttyrec filename and return its UTC timestamp as a float', 'parse an xlogfile line by line and yield tuples of game metadata for each recorded game']
```

Usage

```
{'create_TtyrecDataset': 'create a TtyrecDataset to iterate over NetHack ttyrec game recordings from a named dataset', 'iterate_TtyrecDataset_minibatches': 'iterate over a TtyrecDataset to yield minibatches of tty_chars, tty_colors, and cursor tensors', 'fetch_get_ttyrecs': 'fetch chunked tensor data for multiple game IDs using the get_ttyrecs method', 'fetch_get_ttyrec': 'fetch chunked tensor data for a single game ID using the get_ttyrec method', 'query_get_meta': 'query game metadata for a given game ID using the get_meta method on TtyrecDataset'}
```

## File: facebookresearch_nle/nle/dataset/db.py

Prompts

```
['create a TtyrecDataset to iterate over NetHack ttyrec game recordings from a named dataset', 'iterate over a TtyrecDataset to yield minibatches of tty_chars, tty_colors, and cursor tensors', 'fetch chunked tensor data for multiple game IDs using the get_ttyrecs method', 'fetch chunked tensor data for a single game ID using the get_ttyrec method', 'query game metadata for a given game ID using the get_meta method on TtyrecDataset', 'create a new SQLite database with tables for ttyrecs, games, datasets, roots, and meta', 'list all ttyrecs rows with their rowid and path from the database', 'get all games with name, gameid, starttime, and endtime for a given dataset name', 'add multiple game IDs to a named dataset in the database', 'get the N most recent game IDs ordered by gameid descending', 'add an altorg dataset directory to the NLE database by parsing xlogfiles and matching ttyrecs to games', 'add an NLE data directory to the database by reading xlogfiles and inserting games and ttyrecs', "assign a player's ttyrec recordings to their NetHack games using a timestamp-based matching algorithm", 'parse an alt.org ttyrec filename and return its UTC timestamp as a float', 'parse an xlogfile line by line and yield tuples of game metadata for each recorded game']
```

Usage

```
{'create_ttyrecs_database': 'create a new SQLite database with tables for ttyrecs, games, datasets, roots, and meta', 'list_ttyrecs_rows': 'list all ttyrecs rows with their rowid and path from the database', 'get_games_by_dataset': 'get all games with name, gameid, starttime, and endtime for a given dataset name', 'add_games_to_dataset': 'add multiple game IDs to a named dataset in the database', 'get_most_recent_games': 'get the N most recent game IDs ordered by gameid descending'}
```

## File: facebookresearch_nle/nle/dataset/populate_db.py

Prompts

```
['create a TtyrecDataset to iterate over NetHack ttyrec game recordings from a named dataset', 'iterate over a TtyrecDataset to yield minibatches of tty_chars, tty_colors, and cursor tensors', 'fetch chunked tensor data for multiple game IDs using the get_ttyrecs method', 'fetch chunked tensor data for a single game ID using the get_ttyrec method', 'query game metadata for a given game ID using the get_meta method on TtyrecDataset', 'create a new SQLite database with tables for ttyrecs, games, datasets, roots, and meta', 'list all ttyrecs rows with their rowid and path from the database', 'get all games with name, gameid, starttime, and endtime for a given dataset name', 'add multiple game IDs to a named dataset in the database', 'get the N most recent game IDs ordered by gameid descending', 'add an altorg dataset directory to the NLE database by parsing xlogfiles and matching ttyrecs to games', 'add an NLE data directory to the database by reading xlogfiles and inserting games and ttyrecs', "assign a player's ttyrec recordings to their NetHack games using a timestamp-based matching algorithm", 'parse an alt.org ttyrec filename and return its UTC timestamp as a float', 'parse an xlogfile line by line and yield tuples of game metadata for each recorded game']
```

Usage

```
{'add_altorg_directory': 'add an altorg dataset directory to the NLE database by parsing xlogfiles and matching ttyrecs to games', 'add_nledata_directory': 'add an NLE data directory to the database by reading xlogfiles and inserting games and ttyrecs', 'assign_ttyrecs_to_games': "assign a player's ttyrec recordings to their NetHack games using a timestamp-based matching algorithm", 'altorg_filename_to_timestamp': 'parse an alt.org ttyrec filename and return its UTC timestamp as a float', 'game_data_generator': 'parse an xlogfile line by line and yield tuples of game metadata for each recorded game'}
```

