# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/gateway/platforms/qqbot/adapter.py

Prompts

```
['connect the QQBot platform adapter to authenticate and open the WebSocket gateway', 'disconnect the QQBot platform adapter and close all WebSocket connections', 'send a text or markdown message to a QQ user or group via the REST API', 'send an image natively to a QQ chat by uploading media via the QQ Bot API', 'send a voice message natively to a QQ chat by uploading audio via the QQ Bot API', 'send a file or document natively to a QQ chat by uploading media via the QQ Bot API', 'send a typing indicator notification to a C2C user on QQ', 'check if QQ runtime dependencies aiohttp and httpx are available', 'generate a 256-bit random AES key and return it as base64 for QQBot credential encryption', 'decrypt a base64-encoded AES-256-GCM ciphertext to recover a QQBot client_secret using a base64 key', 'create a base64-encoded AES-256 key for encrypting QQBot bot client_secret during scan-to-configure', 'test decrypting a QQBot encrypted secret with the AES-256-GCM ciphertext layout of IV + ciphertext + auth tag', 'review the AES-256-GCM crypto utilities for QQBot scan-to-configure credential decryption', 'create a QQBot bind task to generate a QR code URL for scanning and bot credential exchange', 'poll the QQBot bind result for a task_id to retrieve bot appid, encrypted secret, and user openid', 'build the QR-code target URL for a given QQBot bind task_id', 'review the BindStatus IntEnum with codes NONE, PENDING, COMPLETED, and EXPIRED for QQBot bind task states', 'test the QQBot onboard module that creates bind tasks, polls results, and builds QR connect URLs', 'build a descriptive User-Agent string for QQBot API requests with Python version, OS, and Hermes version', 'get standard HTTP headers including Content-Type, Accept, and dynamic User-Agent for QQBot API requests', 'coerce config values into a trimmed string list from comma-separated strings, lists, tuples, or single values', 'test the build_user_agent function returns a properly formatted User-Agent string with version info', 'test the coerce_list function handles comma-separated strings, lists, tuples, sets, and None values']
```

Usage

```
{'connect_QQAdapter': 'connect the QQBot platform adapter to authenticate and open the WebSocket gateway', 'disconnect_QQAdapter': 'disconnect the QQBot platform adapter and close all WebSocket connections', 'send_QQAdapter': 'send a text or markdown message to a QQ user or group via the REST API', 'send_image_QQAdapter': 'send an image natively to a QQ chat by uploading media via the QQ Bot API', 'send_voice_QQAdapter': 'send a voice message natively to a QQ chat by uploading audio via the QQ Bot API', 'send_document_QQAdapter': 'send a file or document natively to a QQ chat by uploading media via the QQ Bot API', 'send_typing_QQAdapter': 'send a typing indicator notification to a C2C user on QQ', 'check_qq_requirements': 'check if QQ runtime dependencies aiohttp and httpx are available'}
```

## File: NousResearch_hermes-agent/gateway/platforms/qqbot/crypto.py

Prompts

```
['connect the QQBot platform adapter to authenticate and open the WebSocket gateway', 'disconnect the QQBot platform adapter and close all WebSocket connections', 'send a text or markdown message to a QQ user or group via the REST API', 'send an image natively to a QQ chat by uploading media via the QQ Bot API', 'send a voice message natively to a QQ chat by uploading audio via the QQ Bot API', 'send a file or document natively to a QQ chat by uploading media via the QQ Bot API', 'send a typing indicator notification to a C2C user on QQ', 'check if QQ runtime dependencies aiohttp and httpx are available', 'generate a 256-bit random AES key and return it as base64 for QQBot credential encryption', 'decrypt a base64-encoded AES-256-GCM ciphertext to recover a QQBot client_secret using a base64 key', 'create a base64-encoded AES-256 key for encrypting QQBot bot client_secret during scan-to-configure', 'test decrypting a QQBot encrypted secret with the AES-256-GCM ciphertext layout of IV + ciphertext + auth tag', 'review the AES-256-GCM crypto utilities for QQBot scan-to-configure credential decryption', 'create a QQBot bind task to generate a QR code URL for scanning and bot credential exchange', 'poll the QQBot bind result for a task_id to retrieve bot appid, encrypted secret, and user openid', 'build the QR-code target URL for a given QQBot bind task_id', 'review the BindStatus IntEnum with codes NONE, PENDING, COMPLETED, and EXPIRED for QQBot bind task states', 'test the QQBot onboard module that creates bind tasks, polls results, and builds QR connect URLs', 'build a descriptive User-Agent string for QQBot API requests with Python version, OS, and Hermes version', 'get standard HTTP headers including Content-Type, Accept, and dynamic User-Agent for QQBot API requests', 'coerce config values into a trimmed string list from comma-separated strings, lists, tuples, or single values', 'test the build_user_agent function returns a properly formatted User-Agent string with version info', 'test the coerce_list function handles comma-separated strings, lists, tuples, sets, and None values']
```

Usage

```
{'generate_bind_key': 'generate a 256-bit random AES key and return it as base64 for QQBot credential encryption', 'decrypt_secret': 'decrypt a base64-encoded AES-256-GCM ciphertext to recover a QQBot client_secret using a base64 key', 'create_aes_key_for_qqbot': 'create a base64-encoded AES-256 key for encrypting QQBot bot client_secret during scan-to-configure', 'test_decrypt_qqbot_secret': 'test decrypting a QQBot encrypted secret with the AES-256-GCM ciphertext layout of IV + ciphertext + auth tag', 'review_crypto_utilities': 'review the AES-256-GCM crypto utilities for QQBot scan-to-configure credential decryption'}
```

## File: NousResearch_hermes-agent/gateway/platforms/qqbot/onboard.py

Prompts

```
['connect the QQBot platform adapter to authenticate and open the WebSocket gateway', 'disconnect the QQBot platform adapter and close all WebSocket connections', 'send a text or markdown message to a QQ user or group via the REST API', 'send an image natively to a QQ chat by uploading media via the QQ Bot API', 'send a voice message natively to a QQ chat by uploading audio via the QQ Bot API', 'send a file or document natively to a QQ chat by uploading media via the QQ Bot API', 'send a typing indicator notification to a C2C user on QQ', 'check if QQ runtime dependencies aiohttp and httpx are available', 'generate a 256-bit random AES key and return it as base64 for QQBot credential encryption', 'decrypt a base64-encoded AES-256-GCM ciphertext to recover a QQBot client_secret using a base64 key', 'create a base64-encoded AES-256 key for encrypting QQBot bot client_secret during scan-to-configure', 'test decrypting a QQBot encrypted secret with the AES-256-GCM ciphertext layout of IV + ciphertext + auth tag', 'review the AES-256-GCM crypto utilities for QQBot scan-to-configure credential decryption', 'create a QQBot bind task to generate a QR code URL for scanning and bot credential exchange', 'poll the QQBot bind result for a task_id to retrieve bot appid, encrypted secret, and user openid', 'build the QR-code target URL for a given QQBot bind task_id', 'review the BindStatus IntEnum with codes NONE, PENDING, COMPLETED, and EXPIRED for QQBot bind task states', 'test the QQBot onboard module that creates bind tasks, polls results, and builds QR connect URLs', 'build a descriptive User-Agent string for QQBot API requests with Python version, OS, and Hermes version', 'get standard HTTP headers including Content-Type, Accept, and dynamic User-Agent for QQBot API requests', 'coerce config values into a trimmed string list from comma-separated strings, lists, tuples, or single values', 'test the build_user_agent function returns a properly formatted User-Agent string with version info', 'test the coerce_list function handles comma-separated strings, lists, tuples, sets, and None values']
```

Usage

```
{'create_bind_task': 'create a QQBot bind task to generate a QR code URL for scanning and bot credential exchange', 'poll_bind_result': 'poll the QQBot bind result for a task_id to retrieve bot appid, encrypted secret, and user openid', 'build_connect_url': 'build the QR-code target URL for a given QQBot bind task_id', 'review_BindStatus': 'review the BindStatus IntEnum with codes NONE, PENDING, COMPLETED, and EXPIRED for QQBot bind task states', 'test_onboard_module': 'test the QQBot onboard module that creates bind tasks, polls results, and builds QR connect URLs'}
```

## File: NousResearch_hermes-agent/gateway/platforms/qqbot/utils.py

Prompts

```
['connect the QQBot platform adapter to authenticate and open the WebSocket gateway', 'disconnect the QQBot platform adapter and close all WebSocket connections', 'send a text or markdown message to a QQ user or group via the REST API', 'send an image natively to a QQ chat by uploading media via the QQ Bot API', 'send a voice message natively to a QQ chat by uploading audio via the QQ Bot API', 'send a file or document natively to a QQ chat by uploading media via the QQ Bot API', 'send a typing indicator notification to a C2C user on QQ', 'check if QQ runtime dependencies aiohttp and httpx are available', 'generate a 256-bit random AES key and return it as base64 for QQBot credential encryption', 'decrypt a base64-encoded AES-256-GCM ciphertext to recover a QQBot client_secret using a base64 key', 'create a base64-encoded AES-256 key for encrypting QQBot bot client_secret during scan-to-configure', 'test decrypting a QQBot encrypted secret with the AES-256-GCM ciphertext layout of IV + ciphertext + auth tag', 'review the AES-256-GCM crypto utilities for QQBot scan-to-configure credential decryption', 'create a QQBot bind task to generate a QR code URL for scanning and bot credential exchange', 'poll the QQBot bind result for a task_id to retrieve bot appid, encrypted secret, and user openid', 'build the QR-code target URL for a given QQBot bind task_id', 'review the BindStatus IntEnum with codes NONE, PENDING, COMPLETED, and EXPIRED for QQBot bind task states', 'test the QQBot onboard module that creates bind tasks, polls results, and builds QR connect URLs', 'build a descriptive User-Agent string for QQBot API requests with Python version, OS, and Hermes version', 'get standard HTTP headers including Content-Type, Accept, and dynamic User-Agent for QQBot API requests', 'coerce config values into a trimmed string list from comma-separated strings, lists, tuples, or single values', 'test the build_user_agent function returns a properly formatted User-Agent string with version info', 'test the coerce_list function handles comma-separated strings, lists, tuples, sets, and None values']
```

Usage

```
{'build_user_agent': 'build a descriptive User-Agent string for QQBot API requests with Python version, OS, and Hermes version', 'get_api_headers': 'get standard HTTP headers including Content-Type, Accept, and dynamic User-Agent for QQBot API requests', 'coerce_list': 'coerce config values into a trimmed string list from comma-separated strings, lists, tuples, or single values', 'test_build_user_agent': 'test the build_user_agent function returns a properly formatted User-Agent string with version info', 'test_coerce_list': 'test the coerce_list function handles comma-separated strings, lists, tuples, sets, and None values'}
```

