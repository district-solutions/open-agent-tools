# Agent Python Tools

- repo: google-deepmind/geeflow
- repo_uri: https://github.com/google-deepmind/geeflow

## File: google-deepmind_geeflow/geeflow/configs/public/demo.py

Prompts

```
['build a demo data extraction config with Sentinel2, Sentinel1, and NASA DEM sources for Earth Engine', 'create a sources config with Sentinel2 L2A bands, Sentinel1 IW VV/VH polarizations, and elevation data', 'create a labels config from a CSV file with lat, lon, split meta keys and max sample count', 'run get_config to build a full ConfigDict with sources and labels from a labels CSV path', 'review the get_sources_config function that configures Sentinel2, Sentinel1, and NASA DEM data sources', 'build a data sources config for global drivers 1km model with Sentinel2, Hansen, and elevation layers', 'build a labels config with scale factor and metadata keys for training or inference mode', 'build a complete GeeFlow config by parsing args and combining sources and labels configs', 'review the get_config function to see how scale factor and inference mode affect the output']
```

Usage

```
{'build_demo_config': 'build a demo data extraction config with Sentinel2, Sentinel1, and NASA DEM sources for Earth Engine', 'create_sources_config': 'create a sources config with Sentinel2 L2A bands, Sentinel1 IW VV/VH polarizations, and elevation data', 'create_labels_config': 'create a labels config from a CSV file with lat, lon, split meta keys and max sample count', 'run_get_config': 'run get_config to build a full ConfigDict with sources and labels from a labels CSV path', 'review_get_sources_config': 'review the get_sources_config function that configures Sentinel2, Sentinel1, and NASA DEM data sources'}
```

## File: google-deepmind_geeflow/geeflow/configs/public/global_drivers_1km_2022_v1.py

Prompts

```
['build a demo data extraction config with Sentinel2, Sentinel1, and NASA DEM sources for Earth Engine', 'create a sources config with Sentinel2 L2A bands, Sentinel1 IW VV/VH polarizations, and elevation data', 'create a labels config from a CSV file with lat, lon, split meta keys and max sample count', 'run get_config to build a full ConfigDict with sources and labels from a labels CSV path', 'review the get_sources_config function that configures Sentinel2, Sentinel1, and NASA DEM data sources', 'build a data sources config for global drivers 1km model with Sentinel2, Hansen, and elevation layers', 'build a labels config with scale factor and metadata keys for training or inference mode', 'build a complete GeeFlow config by parsing args and combining sources and labels configs', 'review the get_config function to see how scale factor and inference mode affect the output']
```

Usage

```
{'build_sources_config': 'build a data sources config for global drivers 1km model with Sentinel2, Hansen, and elevation layers', 'build_labels_config': 'build a labels config with scale factor and metadata keys for training or inference mode', 'build_full_config': 'build a complete GeeFlow config by parsing args and combining sources and labels configs', 'review_get_sources_config': 'review the get_sources_config function to understand which Earth Engine data layers are included', 'review_get_config': 'review the get_config function to see how scale factor and inference mode affect the output'}
```

