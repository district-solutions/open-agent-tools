# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/enterprise/litellm_enterprise/types/enterprise_callbacks/send_emails.py

Prompts

```
['create an EmailParams pydantic model with logo URL, support contact, base URL, recipient email, subject, and signature', 'create a SendKeyCreatedEmailEvent webhook event with a virtual key to notify users of new API keys', 'create a SendKeyRotatedEmailEvent webhook event with a virtual key and optional alias to notify users of rotated keys', 'get the default email event settings as a dictionary using DefaultEmailSettings.get_defaults class method', 'convert DefaultEmailSettings to a string-keyed dictionary using the to_dict method for storage']
```

Usage

```
{'create_email_params': 'create an EmailParams pydantic model with logo URL, support contact, base URL, recipient email, subject, and signature', 'create_key_created_event': 'create a SendKeyCreatedEmailEvent webhook event with a virtual key to notify users of new API keys', 'create_key_rotated_event': 'create a SendKeyRotatedEmailEvent webhook event with a virtual key and optional alias to notify users of rotated keys', 'get_default_email_settings': 'get the default email event settings as a dictionary using DefaultEmailSettings.get_defaults class method', 'convert_email_settings_to_dict': 'convert DefaultEmailSettings to a string-keyed dictionary using the to_dict method for storage'}
```

