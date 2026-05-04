# Agent Python Tools

- repo: facebookresearch/ad-library-api-script-repository
- repo_uri: https://github.com/facebookresearch/ad-library-api-script-repository

## File: facebookresearch_ad-library-api-script-repository/python/fb_ads_library_api.py

Prompts

```
['create a FbAdsLibraryTraversal instance with an access token, search term, and country to query Facebook ads archive', 'generate paginated ad archives from Facebook Ads Library using FbAdsLibraryTraversal with search terms and date filtering', 'extract the ad_archive_id from an ad_snapshot_url using the get_ad_archive_id helper function', 'resume a failed Facebook Ads Library traversal from a specific URL using generate_ad_archives_from_url class method', 'filter Facebook ad archives by delivery start date using the after_date parameter in FbAdsLibraryTraversal', 'run the Facebook Ads Library CLI to search ads by term and country and save results to CSV', 'run the Facebook Ads Library CLI to search ads by specific Facebook Page IDs and country', 'run the Facebook Ads Library CLI to search ads filtered by active status and delivery date', 'review the validate_country_param function that validates comma-separated country codes against supported values', 'review the validate_fields_param function that validates comma-separated API field names against supported fields', 'count the total number of ad archives retrieved from a generator matching a query', 'save all retrieved ad archives to a file with each archive stored as a single JSON line', 'save all retrieved ad archives to a CSV file with specified fields as column headers', 'output a CSV of ad count trends grouped by ad delivery start date', 'get a dictionary of available operator functions for processing Facebook ad library archives', 'convert a country name or code to its ISO alpha-2 code if supported by the Facebook Ads Library API', 'check if a given field name is a valid query field for the Facebook Ads Library API', 'list all ISO alpha-2 country codes supported by the Facebook Ads Library API', 'list all valid query field names supported by the Facebook Ads Library API', 'review the get_country_code function to understand how it converts country names to alpha-2 codes']
```

Usage

```
{'create_fb_ads_traversal': 'create a FbAdsLibraryTraversal instance with an access token, search term, and country to query Facebook ads archive', 'generate_ad_archives': 'generate paginated ad archives from Facebook Ads Library using FbAdsLibraryTraversal with search terms and date filtering', 'extract_ad_archive_id': 'extract the ad_archive_id from an ad_snapshot_url using the get_ad_archive_id helper function', 'resume_failed_traversal': 'resume a failed Facebook Ads Library traversal from a specific URL using generate_ad_archives_from_url class method', 'filter_ads_by_date': 'filter Facebook ad archives by delivery start date using the after_date parameter in FbAdsLibraryTraversal'}
```

## File: facebookresearch_ad-library-api-script-repository/python/fb_ads_library_api_cli.py

Prompts

```
['create a FbAdsLibraryTraversal instance with an access token, search term, and country to query Facebook ads archive', 'generate paginated ad archives from Facebook Ads Library using FbAdsLibraryTraversal with search terms and date filtering', 'extract the ad_archive_id from an ad_snapshot_url using the get_ad_archive_id helper function', 'resume a failed Facebook Ads Library traversal from a specific URL using generate_ad_archives_from_url class method', 'filter Facebook ad archives by delivery start date using the after_date parameter in FbAdsLibraryTraversal', 'run the Facebook Ads Library CLI to search ads by term and country and save results to CSV', 'run the Facebook Ads Library CLI to search ads by specific Facebook Page IDs and country', 'run the Facebook Ads Library CLI to search ads filtered by active status and delivery date', 'review the validate_country_param function that validates comma-separated country codes against supported values', 'review the validate_fields_param function that validates comma-separated API field names against supported fields', 'count the total number of ad archives retrieved from a generator matching a query', 'save all retrieved ad archives to a file with each archive stored as a single JSON line', 'save all retrieved ad archives to a CSV file with specified fields as column headers', 'output a CSV of ad count trends grouped by ad delivery start date', 'get a dictionary of available operator functions for processing Facebook ad library archives', 'convert a country name or code to its ISO alpha-2 code if supported by the Facebook Ads Library API', 'check if a given field name is a valid query field for the Facebook Ads Library API', 'list all ISO alpha-2 country codes supported by the Facebook Ads Library API', 'list all valid query field names supported by the Facebook Ads Library API', 'review the get_country_code function to understand how it converts country names to alpha-2 codes']
```

Usage

```
{'run_fb_ads_library_search': 'run the Facebook Ads Library CLI to search ads by term and country and save results to CSV', 'run_fb_ads_library_page_search': 'run the Facebook Ads Library CLI to search ads by specific Facebook Page IDs and country', 'run_fb_ads_library_filtered_search': 'run the Facebook Ads Library CLI to search ads filtered by active status and delivery date', 'review_validate_country_param': 'review the validate_country_param function that validates comma-separated country codes against supported values', 'review_validate_fields_param': 'review the validate_fields_param function that validates comma-separated API field names against supported fields'}
```

## File: facebookresearch_ad-library-api-script-repository/python/fb_ads_library_api_operators.py

Prompts

```
['create a FbAdsLibraryTraversal instance with an access token, search term, and country to query Facebook ads archive', 'generate paginated ad archives from Facebook Ads Library using FbAdsLibraryTraversal with search terms and date filtering', 'extract the ad_archive_id from an ad_snapshot_url using the get_ad_archive_id helper function', 'resume a failed Facebook Ads Library traversal from a specific URL using generate_ad_archives_from_url class method', 'filter Facebook ad archives by delivery start date using the after_date parameter in FbAdsLibraryTraversal', 'run the Facebook Ads Library CLI to search ads by term and country and save results to CSV', 'run the Facebook Ads Library CLI to search ads by specific Facebook Page IDs and country', 'run the Facebook Ads Library CLI to search ads filtered by active status and delivery date', 'review the validate_country_param function that validates comma-separated country codes against supported values', 'review the validate_fields_param function that validates comma-separated API field names against supported fields', 'count the total number of ad archives retrieved from a generator matching a query', 'save all retrieved ad archives to a file with each archive stored as a single JSON line', 'save all retrieved ad archives to a CSV file with specified fields as column headers', 'output a CSV of ad count trends grouped by ad delivery start date', 'get a dictionary of available operator functions for processing Facebook ad library archives', 'convert a country name or code to its ISO alpha-2 code if supported by the Facebook Ads Library API', 'check if a given field name is a valid query field for the Facebook Ads Library API', 'list all ISO alpha-2 country codes supported by the Facebook Ads Library API', 'list all valid query field names supported by the Facebook Ads Library API', 'review the get_country_code function to understand how it converts country names to alpha-2 codes']
```

Usage

```
{'count_ads_from_generator': 'count the total number of ad archives retrieved from a generator matching a query', 'save_ads_to_json_file': 'save all retrieved ad archives to a file with each archive stored as a single JSON line', 'save_ads_to_csv': 'save all retrieved ad archives to a CSV file with specified fields as column headers', 'analyze_ad_start_time_trending': 'output a CSV of ad count trends grouped by ad delivery start date', 'get_available_operators': 'get a dictionary of available operator functions for processing Facebook ad library archives'}
```

## File: facebookresearch_ad-library-api-script-repository/python/fb_ads_library_api_utils.py

Prompts

```
['create a FbAdsLibraryTraversal instance with an access token, search term, and country to query Facebook ads archive', 'generate paginated ad archives from Facebook Ads Library using FbAdsLibraryTraversal with search terms and date filtering', 'extract the ad_archive_id from an ad_snapshot_url using the get_ad_archive_id helper function', 'resume a failed Facebook Ads Library traversal from a specific URL using generate_ad_archives_from_url class method', 'filter Facebook ad archives by delivery start date using the after_date parameter in FbAdsLibraryTraversal', 'run the Facebook Ads Library CLI to search ads by term and country and save results to CSV', 'run the Facebook Ads Library CLI to search ads by specific Facebook Page IDs and country', 'run the Facebook Ads Library CLI to search ads filtered by active status and delivery date', 'review the validate_country_param function that validates comma-separated country codes against supported values', 'review the validate_fields_param function that validates comma-separated API field names against supported fields', 'count the total number of ad archives retrieved from a generator matching a query', 'save all retrieved ad archives to a file with each archive stored as a single JSON line', 'save all retrieved ad archives to a CSV file with specified fields as column headers', 'output a CSV of ad count trends grouped by ad delivery start date', 'get a dictionary of available operator functions for processing Facebook ad library archives', 'convert a country name or code to its ISO alpha-2 code if supported by the Facebook Ads Library API', 'check if a given field name is a valid query field for the Facebook Ads Library API', 'list all ISO alpha-2 country codes supported by the Facebook Ads Library API', 'list all valid query field names supported by the Facebook Ads Library API', 'review the get_country_code function to understand how it converts country names to alpha-2 codes']
```

Usage

```
{'get_country_code': 'convert a country name or code to its ISO alpha-2 code if supported by the Facebook Ads Library API', 'is_valid_fields': 'check if a given field name is a valid query field for the Facebook Ads Library API', 'supported_countries': 'list all ISO alpha-2 country codes supported by the Facebook Ads Library API', 'valid_query_fields': 'list all valid query field names supported by the Facebook Ads Library API', 'review_get_country_code': 'review the get_country_code function to understand how it converts country names to alpha-2 codes'}
```

