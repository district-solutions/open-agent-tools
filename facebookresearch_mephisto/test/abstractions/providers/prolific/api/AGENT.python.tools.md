# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/abstractions/providers/prolific/api/test_base_api_resourse.py

Prompts

```
['test the BaseAPIResource._base_request method with mocked requests and verify JSON response parsing', 'test the BaseAPIResource._base_request method handles HTTP 204 no content responses correctly', 'test the BaseAPIResource._base_request method raises ProlificAPIKeyError when no API key is provided', 'test the BaseAPIResource._base_request method raises ProlificRequestError on HTTP errors with response content', 'test the BaseAPIResource._base_request method raises ProlificAuthenticationError on HTTP 401 unauthorized responses']
```

Usage

```
{'test_base_request': 'test the BaseAPIResource._base_request method with mocked requests and verify JSON response parsing', 'test_base_request_no_content': 'test the BaseAPIResource._base_request method handles HTTP 204 no content responses correctly', 'test_base_request_api_key_error': 'test the BaseAPIResource._base_request method raises ProlificAPIKeyError when no API key is provided', 'test_base_request_http_error': 'test the BaseAPIResource._base_request method raises ProlificRequestError on HTTP errors with response content', 'test_base_request_unauthorized': 'test the BaseAPIResource._base_request method raises ProlificAuthenticationError on HTTP 401 unauthorized responses'}
```

