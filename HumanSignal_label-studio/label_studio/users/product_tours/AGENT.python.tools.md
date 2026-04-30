# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/users/product_tours/api.py

Prompts

```
['create a DRF API endpoint that retrieves or updates a user product tour by name', 'retrieve a user product tour record, creating it if it does not already exist', 'update a user product tour record with serialized data from the request body', 'build a method that extracts and normalizes the tour name from query parameters', 'test the get_object method that fetches or creates a UserProductTour for the authenticated user', 'create a DRF serializer for UserProductTour that loads tour steps and dependencies from YAML configs', 'validate a product tour name against available YAML config files in the configs directory', 'get tour steps from a YAML config file for a given product tour name', 'check if a product tour is awaiting completion of its dependency tours before enabling it', 'validate product tour interaction data against a pydantic model schema']
```

Usage

```
{'create_ProductTourAPI': 'create a DRF API endpoint that retrieves or updates a user product tour by name', 'retrieve_ProductTourAPI': 'retrieve a user product tour record, creating it if it does not already exist', 'update_ProductTourAPI': 'update a user product tour record with serialized data from the request body', 'build_get_tour_name': 'build a method that extracts and normalizes the tour name from query parameters', 'test_get_object': 'test the get_object method that fetches or creates a UserProductTour for the authenticated user'}
```

## File: HumanSignal_label-studio/label_studio/users/product_tours/serializers.py

Prompts

```
['create a DRF API endpoint that retrieves or updates a user product tour by name', 'retrieve a user product tour record, creating it if it does not already exist', 'update a user product tour record with serialized data from the request body', 'build a method that extracts and normalizes the tour name from query parameters', 'test the get_object method that fetches or creates a UserProductTour for the authenticated user', 'create a DRF serializer for UserProductTour that loads tour steps and dependencies from YAML configs', 'validate a product tour name against available YAML config files in the configs directory', 'get tour steps from a YAML config file for a given product tour name', 'check if a product tour is awaiting completion of its dependency tours before enabling it', 'validate product tour interaction data against a pydantic model schema']
```

Usage

```
{'create_UserProductTourSerializer': 'create a DRF serializer for UserProductTour that loads tour steps and dependencies from YAML configs', 'validate_UserProductTour_name': 'validate a product tour name against available YAML config files in the configs directory', 'get_UserProductTour_steps': 'get tour steps from a YAML config file for a given product tour name', 'get_UserProductTour_awaiting': 'check if a product tour is awaiting completion of its dependency tours before enabling it', 'validate_UserProductTour_interaction_data': 'validate product tour interaction data against a pydantic model schema'}
```

