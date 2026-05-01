# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/litellm/llms/oci/chat/test_oci_chat_transformation.py

Prompts

```
['test that OCIChatConfig normalizes escaped and CRLF newlines in PEM private keys', 'test that OCIChatConfig rejects non-string oci_key values like dicts or lists', 'test that OCIChatConfig validates required OCI credentials like user, fingerprint, and tenancy', 'test that OCIChatConfig generates correct API URLs for default and custom regions', 'test that adapt_messages_to_generic_oci_standard handles image_url as string or object input']
```

Usage

```
{'test_oci_key_normalization': 'test that OCIChatConfig normalizes escaped and CRLF newlines in PEM private keys', 'test_oci_key_type_validation': 'test that OCIChatConfig rejects non-string oci_key values like dicts or lists', 'test_oci_validate_environment': 'test that OCIChatConfig validates required OCI credentials like user, fingerprint, and tenancy', 'test_oci_get_complete_url': 'test that OCIChatConfig generates correct API URLs for default and custom regions', 'test_oci_image_url_transformation': 'test that adapt_messages_to_generic_oci_standard handles image_url as string or object input'}
```

