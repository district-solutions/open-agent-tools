# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/common/generate_persona.py

Prompts

```
['generate a random persona dictionary with age, gender, education, marriages, children, and jobs', 'draw a random value from a list using a custom probability distribution with numpy', "return a hardcoded college name for a persona's undergraduate institution", "return a hardcoded graduate school name for a persona's graduate institution", "return a hardcoded college major for a persona's undergraduate degree", 'use GeoHelper.calculateLocation to reverse geocode latitude and longitude into a Location object', 'use GeoHelper.geocode to look up an address string and return its geocoded Location', 'review the GeoHelper class that provides cached forward and reverse geocoding via Nominatim', 'refactor the reverse_cache_key method to use a more robust key format for lat/lon pairs', 'test the GeoHelper.geocode method to verify cache hits and misses work correctly', 'convert a time string from one timezone to another using pytz timezone conversion', 'calculate the distance in kilometers between two latitude longitude coordinate pairs using haversine', 'translate a non-English place name to English using geocoding with caching support', 'extract year month day hour and minute components from an ISO format date string', 'get a specific attribute like city or country from a geocoded location object']
```

Usage

```
{'generate_persona': 'generate a random persona dictionary with age, gender, education, marriages, children, and jobs', 'flip_probability_distribution': 'draw a random value from a list using a custom probability distribution with numpy', 'generate_college': "return a hardcoded college name for a persona's undergraduate institution", 'generate_graduate_school': "return a hardcoded graduate school name for a persona's graduate institution", 'generate_college_major': "return a hardcoded college major for a persona's undergraduate degree"}
```

## File: facebookresearch_personal-timeline/src/common/geo_helper.py

Prompts

```
['generate a random persona dictionary with age, gender, education, marriages, children, and jobs', 'draw a random value from a list using a custom probability distribution with numpy', "return a hardcoded college name for a persona's undergraduate institution", "return a hardcoded graduate school name for a persona's graduate institution", "return a hardcoded college major for a persona's undergraduate degree", 'use GeoHelper.calculateLocation to reverse geocode latitude and longitude into a Location object', 'use GeoHelper.geocode to look up an address string and return its geocoded Location', 'review the GeoHelper class that provides cached forward and reverse geocoding via Nominatim', 'refactor the reverse_cache_key method to use a more robust key format for lat/lon pairs', 'test the GeoHelper.geocode method to verify cache hits and misses work correctly', 'convert a time string from one timezone to another using pytz timezone conversion', 'calculate the distance in kilometers between two latitude longitude coordinate pairs using haversine', 'translate a non-English place name to English using geocoding with caching support', 'extract year month day hour and minute components from an ISO format date string', 'get a specific attribute like city or country from a geocoded location object']
```

Usage

```
{'calculate_location_from_coords': 'use GeoHelper.calculateLocation to reverse geocode latitude and longitude into a Location object', 'geocode_address_to_location': 'use GeoHelper.geocode to look up an address string and return its geocoded Location', 'review_GeoHelper_class': 'review the GeoHelper class that provides cached forward and reverse geocoding via Nominatim', 'refactor_reverse_cache_key': 'refactor the reverse_cache_key method to use a more robust key format for lat/lon pairs', 'test_geocode_caching': 'test the GeoHelper.geocode method to verify cache hits and misses work correctly'}
```

## File: facebookresearch_personal-timeline/src/common/util.py

Prompts

```
['generate a random persona dictionary with age, gender, education, marriages, children, and jobs', 'draw a random value from a list using a custom probability distribution with numpy', "return a hardcoded college name for a persona's undergraduate institution", "return a hardcoded graduate school name for a persona's graduate institution", "return a hardcoded college major for a persona's undergraduate degree", 'use GeoHelper.calculateLocation to reverse geocode latitude and longitude into a Location object', 'use GeoHelper.geocode to look up an address string and return its geocoded Location', 'review the GeoHelper class that provides cached forward and reverse geocoding via Nominatim', 'refactor the reverse_cache_key method to use a more robust key format for lat/lon pairs', 'test the GeoHelper.geocode method to verify cache hits and misses work correctly', 'convert a time string from one timezone to another using pytz timezone conversion', 'calculate the distance in kilometers between two latitude longitude coordinate pairs using haversine', 'translate a non-English place name to English using geocoding with caching support', 'extract year month day hour and minute components from an ISO format date string', 'get a specific attribute like city or country from a geocoded location object']
```

Usage

```
{'convert_time_to_timezone': 'convert a time string from one timezone to another using pytz timezone conversion', 'calculate_distance_between_coordinates': 'calculate the distance in kilometers between two latitude longitude coordinate pairs using haversine', 'translate_place_name_to_english': 'translate a non-English place name to English using geocoding with caching support', 'extract_date_components': 'extract year month day hour and minute components from an ISO format date string', 'get_location_attribute': 'get a specific attribute like city or country from a geocoded location object'}
```

