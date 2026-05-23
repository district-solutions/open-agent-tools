# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/ingest/enrichment/find_jpegs.py

Prompts

```
['run the script to scan a photos directory and map JSON files to their corresponding JPEG images', 'create a function that checks if a given filename has a .json or .JSON extension', 'create a function that checks if a given filename has a .jpeg or .JPEG extension', 'create a function that checks if a given filename has a .jpg or .JPG extension', 'create a function that checks if a given filename has a .HEIC extension', 'run the LocationEnricher to incrementally enrich personal data entries with geocoded location information', 'run the LocationEnricher enrich method with incremental false to process all personal data entries', 'use GeoHelper calculateLocation to convert latitude and longitude coordinates into geocoded Location objects', 'use PersonalDataDBConnector search_personal_data to query personal data entries with custom columns and where clauses', 'use PersonalDataDBConnector add_or_replace_personal_data to upsert enriched location data back into the database', 'run CLIP-based zero-shot classification on an image to extract objects, places, and tags', 'deduplicate a list of image paths by comparing their embeddings with a similarity threshold', 'run incremental image enrichment on all pending entries in the personal data database', 'review the ImageEnricher enhance method that uses CLIP embeddings for image classification and tagging', 'refactor the ImageEnricher deduplicate method to use a more efficient similarity search algorithm']
```

Usage

```
{'run_find_jpegs': 'run the script to scan a photos directory and map JSON files to their corresponding JPEG images', 'create_json_file_check': 'create a function that checks if a given filename has a .json or .JSON extension', 'create_jpeg_file_check': 'create a function that checks if a given filename has a .jpeg or .JPEG extension', 'create_jpg_file_check': 'create a function that checks if a given filename has a .jpg or .JPG extension', 'create_heic_file_check': 'create a function that checks if a given filename has a .HEIC extension'}
```

## File: facebookresearch_personal-timeline/src/ingest/enrichment/geo_enrichment.py

Prompts

```
['run the script to scan a photos directory and map JSON files to their corresponding JPEG images', 'create a function that checks if a given filename has a .json or .JSON extension', 'create a function that checks if a given filename has a .jpeg or .JPEG extension', 'create a function that checks if a given filename has a .jpg or .JPG extension', 'create a function that checks if a given filename has a .HEIC extension', 'run the LocationEnricher to incrementally enrich personal data entries with geocoded location information', 'run the LocationEnricher enrich method with incremental false to process all personal data entries', 'use GeoHelper calculateLocation to convert latitude and longitude coordinates into geocoded Location objects', 'use PersonalDataDBConnector search_personal_data to query personal data entries with custom columns and where clauses', 'use PersonalDataDBConnector add_or_replace_personal_data to upsert enriched location data back into the database', 'run CLIP-based zero-shot classification on an image to extract objects, places, and tags', 'deduplicate a list of image paths by comparing their embeddings with a similarity threshold', 'run incremental image enrichment on all pending entries in the personal data database', 'review the ImageEnricher enhance method that uses CLIP embeddings for image classification and tagging', 'refactor the ImageEnricher deduplicate method to use a more efficient similarity search algorithm']
```

Usage

```
{'enrich_location_incremental': 'run the LocationEnricher to incrementally enrich personal data entries with geocoded location information', 'enrich_location_full': 'run the LocationEnricher enrich method with incremental false to process all personal data entries', 'calculate_location_from_coords': 'use GeoHelper calculateLocation to convert latitude and longitude coordinates into geocoded Location objects', 'search_personal_data': 'use PersonalDataDBConnector search_personal_data to query personal data entries with custom columns and where clauses', 'add_or_replace_personal_data': 'use PersonalDataDBConnector add_or_replace_personal_data to upsert enriched location data back into the database'}
```

## File: facebookresearch_personal-timeline/src/ingest/enrichment/image_enrichment.py

Prompts

```
['run the script to scan a photos directory and map JSON files to their corresponding JPEG images', 'create a function that checks if a given filename has a .json or .JSON extension', 'create a function that checks if a given filename has a .jpeg or .JPEG extension', 'create a function that checks if a given filename has a .jpg or .JPG extension', 'create a function that checks if a given filename has a .HEIC extension', 'run the LocationEnricher to incrementally enrich personal data entries with geocoded location information', 'run the LocationEnricher enrich method with incremental false to process all personal data entries', 'use GeoHelper calculateLocation to convert latitude and longitude coordinates into geocoded Location objects', 'use PersonalDataDBConnector search_personal_data to query personal data entries with custom columns and where clauses', 'use PersonalDataDBConnector add_or_replace_personal_data to upsert enriched location data back into the database', 'run CLIP-based zero-shot classification on an image to extract objects, places, and tags', 'deduplicate a list of image paths by comparing their embeddings with a similarity threshold', 'run incremental image enrichment on all pending entries in the personal data database', 'review the ImageEnricher enhance method that uses CLIP embeddings for image classification and tagging', 'refactor the ImageEnricher deduplicate method to use a more efficient similarity search algorithm']
```

Usage

```
{'enhance_image_with_clip': 'run CLIP-based zero-shot classification on an image to extract objects, places, and tags', 'deduplicate_images_by_embedding': 'deduplicate a list of image paths by comparing their embeddings with a similarity threshold', 'enrich_all_images_incremental': 'run incremental image enrichment on all pending entries in the personal data database', 'review_ImageEnricher_enhance': 'review the ImageEnricher enhance method that uses CLIP embeddings for image classification and tagging', 'refactor_ImageEnricher_deduplicate': 'refactor the ImageEnricher deduplicate method to use a more efficient similarity search algorithm'}
```

