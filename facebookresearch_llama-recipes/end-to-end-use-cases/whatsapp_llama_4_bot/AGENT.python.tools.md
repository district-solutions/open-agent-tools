# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/whatsapp_llama_4_bot/ec2_services.py

Prompts

```
["create a function that synthesizes text into an MP3 audio file using Groq's TTS service", "create a function that transcribes an audio file to text using Groq's Whisper model", 'create a function that gets a response from Llama-4-Maverick LLM with optional image input', 'create an async function that fetches a WhatsApp image media and converts it to base64', 'create an async function that uploads and sends an audio message via the WhatsApp API', 'send a WhatsApp text message to a phone number using the Meta Graph API', 'send a WhatsApp text message asynchronously using the run_in_executor wrapper', 'upload an MP3 file to WhatsApp media and send it as an audio message', 'call an LLM API with user input and media, then send the response via WhatsApp', 'review the send_message function to understand WhatsApp payload structure and error handling']
```

Usage

```
{'text_to_speech': "create a function that synthesizes text into an MP3 audio file using Groq's TTS service", 'speech_to_text': "create a function that transcribes an audio file to text using Groq's Whisper model", 'get_llm_response': 'create a function that gets a response from Llama-4-Maverick LLM with optional image input', 'handle_image_message': 'create an async function that fetches a WhatsApp image media and converts it to base64', 'send_audio_message': 'create an async function that uploads and sends an audio message via the WhatsApp API'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/whatsapp_llama_4_bot/webhook_utils.py

Prompts

```
["create a function that synthesizes text into an MP3 audio file using Groq's TTS service", "create a function that transcribes an audio file to text using Groq's Whisper model", 'create a function that gets a response from Llama-4-Maverick LLM with optional image input', 'create an async function that fetches a WhatsApp image media and converts it to base64', 'create an async function that uploads and sends an audio message via the WhatsApp API', 'send a WhatsApp text message to a phone number using the Meta Graph API', 'send a WhatsApp text message asynchronously using the run_in_executor wrapper', 'upload an MP3 file to WhatsApp media and send it as an audio message', 'call an LLM API with user input and media, then send the response via WhatsApp', 'review the send_message function to understand WhatsApp payload structure and error handling']
```

Usage

```
{'send_whatsapp_text_message': 'send a WhatsApp text message to a phone number using the Meta Graph API', 'send_whatsapp_text_message_async': 'send a WhatsApp text message asynchronously using the run_in_executor wrapper', 'send_whatsapp_audio_message': 'upload an MP3 file to WhatsApp media and send it as an audio message', 'get_llm_reply_and_send': 'call an LLM API with user input and media, then send the response via WhatsApp', 'review_send_message': 'review the send_message function to understand WhatsApp payload structure and error handling'}
```

