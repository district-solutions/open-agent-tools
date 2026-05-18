# Agent Python Tools

- repo: facebookresearch/neuralstpp
- repo_uri: https://github.com/facebookresearch/neural_stpp

## File: facebookresearch_neuralstpp/data/download_and_preprocess_citibike.py

Prompts

```
['download citibike trip data CSV zip files for a given year and extract them', 'process raw citibike CSV files into subsampled spatiotemporal sequences saved as an NPZ file', 'add Gaussian spatial noise to coordinate arrays with configurable standard deviation per dimension', 'run the full pipeline to download citibike data and preprocess it into NPZ sequences', 'review the process function that groups citibike trips by day and subsamples with spatial noise', 'run the script to download NYT COVID-19 data and preprocess New Jersey county cases into NPZ sequences', 'run the main function to download COVID-19 data, merge geolocation, and save New Jersey case sequences', 'create a function that adds uniform spatial noise to coordinates and validates with reverse geocoding', 'create a function that adds uniform random temporal noise to day values', 'refactor add_unif_spatial_noise to use a different geocoding library or add caching for reverse geocoder lookups', 'download earthquake CSV data from USGS for a given year range and save to local directory', 'preprocess Japan earthquake data into 30-day sliding window sequences and save as numpy NPZ file', 'review the download_data function that constructs USGS API URLs and retrieves earthquake CSV files', 'refactor the preprocess function to support configurable date ranges and output formats', 'download a file from a URL to a specified directory with a progress bar', 'download a file from a URL and save it with a custom filename in the target directory', 'create a tqdm progress bar callback function for tracking download progress', 'download a file from a URL only if it does not already exist in the target directory', 'review the download_url function to understand how it handles URL retrieval and progress reporting']
```

Usage

```
{'download_citibike_tripdata': 'download citibike trip data CSV zip files for a given year and extract them', 'process_citibike_data': 'process raw citibike CSV files into subsampled spatiotemporal sequences saved as an NPZ file', 'add_spatial_noise': 'add Gaussian spatial noise to coordinate arrays with configurable standard deviation per dimension', 'run_download_and_preprocess': 'run the full pipeline to download citibike data and preprocess it into NPZ sequences', 'review_process_function': 'review the process function that groups citibike trips by day and subsamples with spatial noise'}
```

## File: facebookresearch_neuralstpp/data/download_and_preprocess_covid19.py

Prompts

```
['download citibike trip data CSV zip files for a given year and extract them', 'process raw citibike CSV files into subsampled spatiotemporal sequences saved as an NPZ file', 'add Gaussian spatial noise to coordinate arrays with configurable standard deviation per dimension', 'run the full pipeline to download citibike data and preprocess it into NPZ sequences', 'review the process function that groups citibike trips by day and subsamples with spatial noise', 'run the script to download NYT COVID-19 data and preprocess New Jersey county cases into NPZ sequences', 'run the main function to download COVID-19 data, merge geolocation, and save New Jersey case sequences', 'create a function that adds uniform spatial noise to coordinates and validates with reverse geocoding', 'create a function that adds uniform random temporal noise to day values', 'refactor add_unif_spatial_noise to use a different geocoding library or add caching for reverse geocoder lookups', 'download earthquake CSV data from USGS for a given year range and save to local directory', 'preprocess Japan earthquake data into 30-day sliding window sequences and save as numpy NPZ file', 'review the download_data function that constructs USGS API URLs and retrieves earthquake CSV files', 'refactor the preprocess function to support configurable date ranges and output formats', 'download a file from a URL to a specified directory with a progress bar', 'download a file from a URL and save it with a custom filename in the target directory', 'create a tqdm progress bar callback function for tracking download progress', 'download a file from a URL only if it does not already exist in the target directory', 'review the download_url function to understand how it handles URL retrieval and progress reporting']
```

Usage

```
{'run_download_and_preprocess_covid19': 'run the script to download NYT COVID-19 data and preprocess New Jersey county cases into NPZ sequences', 'run_main': 'run the main function to download COVID-19 data, merge geolocation, and save New Jersey case sequences', 'create_add_unif_spatial_noise': 'create a function that adds uniform spatial noise to coordinates and validates with reverse geocoding', 'create_add_temporal_noise': 'create a function that adds uniform random temporal noise to day values', 'refactor_add_unif_spatial_noise': 'refactor add_unif_spatial_noise to use a different geocoding library or add caching for reverse geocoder lookups'}
```

## File: facebookresearch_neuralstpp/data/download_and_preprocess_earthquakes.py

Prompts

```
['download citibike trip data CSV zip files for a given year and extract them', 'process raw citibike CSV files into subsampled spatiotemporal sequences saved as an NPZ file', 'add Gaussian spatial noise to coordinate arrays with configurable standard deviation per dimension', 'run the full pipeline to download citibike data and preprocess it into NPZ sequences', 'review the process function that groups citibike trips by day and subsamples with spatial noise', 'run the script to download NYT COVID-19 data and preprocess New Jersey county cases into NPZ sequences', 'run the main function to download COVID-19 data, merge geolocation, and save New Jersey case sequences', 'create a function that adds uniform spatial noise to coordinates and validates with reverse geocoding', 'create a function that adds uniform random temporal noise to day values', 'refactor add_unif_spatial_noise to use a different geocoding library or add caching for reverse geocoder lookups', 'download earthquake CSV data from USGS for a given year range and save to local directory', 'preprocess Japan earthquake data into 30-day sliding window sequences and save as numpy NPZ file', 'review the download_data function that constructs USGS API URLs and retrieves earthquake CSV files', 'refactor the preprocess function to support configurable date ranges and output formats', 'download a file from a URL to a specified directory with a progress bar', 'download a file from a URL and save it with a custom filename in the target directory', 'create a tqdm progress bar callback function for tracking download progress', 'download a file from a URL only if it does not already exist in the target directory', 'review the download_url function to understand how it handles URL retrieval and progress reporting']
```

Usage

```
{'download_earthquake_data': 'download earthquake CSV data from USGS for a given year range and save to local directory', 'preprocess_earthquake_sequences': 'preprocess Japan earthquake data into 30-day sliding window sequences and save as numpy NPZ file', 'run_download_and_preprocess': 'run the script to download 1990-2019 earthquake data, combine CSVs, and preprocess into sequences', 'review_download_data': 'review the download_data function that constructs USGS API URLs and retrieves earthquake CSV files', 'refactor_preprocess': 'refactor the preprocess function to support configurable date ranges and output formats'}
```

## File: facebookresearch_neuralstpp/data/download_utils.py

Prompts

```
['download citibike trip data CSV zip files for a given year and extract them', 'process raw citibike CSV files into subsampled spatiotemporal sequences saved as an NPZ file', 'add Gaussian spatial noise to coordinate arrays with configurable standard deviation per dimension', 'run the full pipeline to download citibike data and preprocess it into NPZ sequences', 'review the process function that groups citibike trips by day and subsamples with spatial noise', 'run the script to download NYT COVID-19 data and preprocess New Jersey county cases into NPZ sequences', 'run the main function to download COVID-19 data, merge geolocation, and save New Jersey case sequences', 'create a function that adds uniform spatial noise to coordinates and validates with reverse geocoding', 'create a function that adds uniform random temporal noise to day values', 'refactor add_unif_spatial_noise to use a different geocoding library or add caching for reverse geocoder lookups', 'download earthquake CSV data from USGS for a given year range and save to local directory', 'preprocess Japan earthquake data into 30-day sliding window sequences and save as numpy NPZ file', 'review the download_data function that constructs USGS API URLs and retrieves earthquake CSV files', 'refactor the preprocess function to support configurable date ranges and output formats', 'download a file from a URL to a specified directory with a progress bar', 'download a file from a URL and save it with a custom filename in the target directory', 'create a tqdm progress bar callback function for tracking download progress', 'download a file from a URL only if it does not already exist in the target directory', 'review the download_url function to understand how it handles URL retrieval and progress reporting']
```

Usage

```
{'download_file_from_url': 'download a file from a URL to a specified directory with a progress bar', 'download_file_with_custom_name': 'download a file from a URL and save it with a custom filename in the target directory', 'create_progress_bar_callback': 'create a tqdm progress bar callback function for tracking download progress', 'download_file_skip_if_exists': 'download a file from a URL only if it does not already exist in the target directory', 'review_download_url_function': 'review the download_url function to understand how it handles URL retrieval and progress reporting'}
```

