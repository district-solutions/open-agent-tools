# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/ingest/create_episodes.py

Prompts

```
['create episodes for all data types including books, exercise, places, purchase, streaming, and photos', 'create a list of books and reading episodes from Libby and Amazon Kindle sources', 'create a list of places episodes from Google Timeline and Google Photos location data', 'create a list of streaming episodes from Spotify data with artist and track search', 'create a list of exercise episodes from Apple Health data with duration and calories', 'run the EpisodeDeriver pipeline to derive trips from location tracking data and save results to JSON and CSV', 'derive trips from a sequence of location tracking by clustering nearby places into segments', 'cluster a list of lat/lon coordinates into segments based on a distance threshold in meters', 'summarize places visited during a trip using an LLM to generate a concise or detailed description', 'compute the distance in kilometers between two latitude/longitude pairs using the Haversine formula', 'create a trip summary from LLEntry objects by converting to images, segmenting activities, days, and trips', 'create a k-image summary using k-means clustering on image embeddings to select representative photos', 'create activity, day, and trip segments from a list of LLImage entries using time-based clustering', 'convert a list of LLEntry objects into LLImage objects with enriched embeddings and tabular entries', 'summarize an activity segment by classifying objects, places, and generating a caption via Bloom']
```

Usage

```
{'create_all_episodes': 'create episodes for all data types including books, exercise, places, purchase, streaming, and photos', 'create_books_table': 'create a list of books and reading episodes from Libby and Amazon Kindle sources', 'create_places_table': 'create a list of places episodes from Google Timeline and Google Photos location data', 'create_streaming_table': 'create a list of streaming episodes from Spotify data with artist and track search', 'create_exercise_table': 'create a list of exercise episodes from Apple Health data with duration and calories'}
```

## File: facebookresearch_personal-timeline/src/ingest/derive_episodes.py

Prompts

```
['create episodes for all data types including books, exercise, places, purchase, streaming, and photos', 'create a list of books and reading episodes from Libby and Amazon Kindle sources', 'create a list of places episodes from Google Timeline and Google Photos location data', 'create a list of streaming episodes from Spotify data with artist and track search', 'create a list of exercise episodes from Apple Health data with duration and calories', 'run the EpisodeDeriver pipeline to derive trips from location tracking data and save results to JSON and CSV', 'derive trips from a sequence of location tracking by clustering nearby places into segments', 'cluster a list of lat/lon coordinates into segments based on a distance threshold in meters', 'summarize places visited during a trip using an LLM to generate a concise or detailed description', 'compute the distance in kilometers between two latitude/longitude pairs using the Haversine formula', 'create a trip summary from LLEntry objects by converting to images, segmenting activities, days, and trips', 'create a k-image summary using k-means clustering on image embeddings to select representative photos', 'create activity, day, and trip segments from a list of LLImage entries using time-based clustering', 'convert a list of LLEntry objects into LLImage objects with enriched embeddings and tabular entries', 'summarize an activity segment by classifying objects, places, and generating a caption via Bloom']
```

Usage

```
{'run_episode_deriver_pipeline': 'run the EpisodeDeriver pipeline to derive trips from location tracking data and save results to JSON and CSV', 'derive_trips_from_places': 'derive trips from a sequence of location tracking by clustering nearby places into segments', 'cluster_locations_by_distance': 'cluster a list of lat/lon coordinates into segments based on a distance threshold in meters', 'summarize_trip_with_llm': 'summarize places visited during a trip using an LLM to generate a concise or detailed description', 'compute_distance_between_coordinates': 'compute the distance in kilometers between two latitude/longitude pairs using the Haversine formula'}
```

## File: facebookresearch_personal-timeline/src/ingest/offline_processing.py

Prompts

```
['create episodes for all data types including books, exercise, places, purchase, streaming, and photos', 'create a list of books and reading episodes from Libby and Amazon Kindle sources', 'create a list of places episodes from Google Timeline and Google Photos location data', 'create a list of streaming episodes from Spotify data with artist and track search', 'create a list of exercise episodes from Apple Health data with duration and calories', 'run the EpisodeDeriver pipeline to derive trips from location tracking data and save results to JSON and CSV', 'derive trips from a sequence of location tracking by clustering nearby places into segments', 'cluster a list of lat/lon coordinates into segments based on a distance threshold in meters', 'summarize places visited during a trip using an LLM to generate a concise or detailed description', 'compute the distance in kilometers between two latitude/longitude pairs using the Haversine formula', 'create a trip summary from LLEntry objects by converting to images, segmenting activities, days, and trips', 'create a k-image summary using k-means clustering on image embeddings to select representative photos', 'create activity, day, and trip segments from a list of LLImage entries using time-based clustering', 'convert a list of LLEntry objects into LLImage objects with enriched embeddings and tabular entries', 'summarize an activity segment by classifying objects, places, and generating a caption via Bloom']
```

Usage

```
{'create_trip_summary': 'create a trip summary from LLEntry objects by converting to images, segmenting activities, days, and trips', 'create_image_summary': 'create a k-image summary using k-means clustering on image embeddings to select representative photos', 'create_segments': 'create activity, day, and trip segments from a list of LLImage entries using time-based clustering', 'convert_LLEntry_LLImage': 'convert a list of LLEntry objects into LLImage objects with enriched embeddings and tabular entries', 'summarize_activity': 'summarize an activity segment by classifying objects, places, and generating a caption via Bloom'}
```

